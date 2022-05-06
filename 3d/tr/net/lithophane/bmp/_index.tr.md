﻿---
title: Lithophane'nizi .NET aracılığıyla BMP Dosya Biçimlerinden oluşturun 
weight: 830
url: /tr/net/lithophane/bmp/ 
description: .NET Framework, .NET Core, Mono üzerinde litotandan BMP'ye belgelerinizi yüklemek, oluşturmak ve oluşturmak için C# kaynak kodu.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Lithophane\'nizi C# üzerinden BMP\'ye oluşturun" h2="Sunucu tarafı API\'lerini kullanarak litofan - BMP dosyalarınızı oluşturmak için kendi .NET uygulamalarınızı oluşturun." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="BMP" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="BMP" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="BMP" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C# Kullanarak Litofan - BMP Dosyanızı Nasıl Oluşturursunuz" %}}

 Litofan to BMP dosyanızı oluşturmak için kullanacağız
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 Litofanınızı oluşturmak için kullanılacak C# platformu için zengin özelliklere sahip, güçlü ve kullanımı kolay bir API olan API. Açık
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 paket yöneticisi, ara
 **Aspose.3D** 
 ve yükleyin. Paket Yöneticisi Konsolundan aşağıdaki komutu da kullanabilirsiniz.

{{% blocks/products/pf/agp/code-block title="Paket Yöneticisi Konsol Komutu" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C# üzerinden BMP\'ye Litofan Oluşturma Adımları" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D, geliştiricilerin yalnızca birkaç satır kodla litofanınızı BMP dosyasında oluşturmasını kolaylaştırır.

{{% /blocks/products/pf/agp/text %}}

- Bazı yeni parametreler oluşturun ve bir Mesh nesnesi oluşturun- Mesh nesneleri üzerinde hesaplama işlemleri gerçekleştirin- BMP dosyası, Mesh sınıfı aracılığıyla 3d sahneyi yükler- Nesne ile Scene.Save yöntemini çağırın
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="sistem gereksinimleri" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D for .NET, tüm büyük işletim sistemlerinde desteklenir. Sadece aşağıdaki ön koşullara sahip olduğunuzdan emin olun.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows veya .NET Framework, .NET Core, Mono ile uyumlu bir işletim sistemi- Microsoft Visual Studio gibi geliştirme ortamı- Projenizde referans verilen Aspose.3D for .NET
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Litofanınızı BMP\'ye Oluşturmak için C# kodu" offSpacer="" %}}

```cs

//Yüklenmesi gereken orijinal görüntü ve kaydettikten sonra 3d dosya çıktısı
    string file = "template.bmp";
    string output =System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".fbx";

//Bazı yeni parametreler oluşturun
    var td= TextureData.FromFile(file);
    const float nozzleSize = 0.9f;//0,2 mm
    const float layerHeight = 0.2f;
    var grayscale = ToGrayscale(td);
    const float width = 120.0f;//tuval genişliği 200.0 mm'dir
    float height = width / td.Width * td.Height;
    float thickness = 10.0f;//10 mm kalınlık
    float layers = thickness / layerHeight;
    int widthSegs = (int)Math.Floor(width / nozzleSize);
    int heightSegs = (int)Math.Floor(height / nozzleSize);

//Mesh nesneleri üzerinde hesaplama işlemleri gerçekleştirin
    var mesh = new Mesh();
    for (int y = 0; y < heightSegs; y++)
    {
        float dy = (float)y / heightSegs;
        for (int x = 0; x < widthSegs; x++)
        {
            float dx = (float)x / widthSegs;
            float gray = Sample(grayscale, td.Width, td.Height, dx, dy);
            float v = (1 - gray) * thickness;
            mesh.ControlPoints.Add(new Vector4(dx * width, dy * height, v));
        }
    }


    for (int y = 0; y < heightSegs - 1; y++)
    {
        int row = (y * heightSegs);
        int ptr = row;
        for (int x = 0; x < widthSegs - 1; x++)
        {
            mesh.CreatePolygon(ptr, ptr + widthSegs, ptr + 1);
            mesh.CreatePolygon(ptr + 1, ptr + widthSegs, ptr + widthSegs + 1);
            ptr++;
        }
    }

//3B sahne oluşturun ve nesneleri kaydedin
    var scene = new Scene(mesh);
    scene.Save(output, FileFormat.FBX7400ASCII);

//Çağrılacak örnek yöntem
    static float Sample(float[,] data, int w, int h, float x, float y)
    {
        return data[(int)(x * w), (int)(y * h)];
    }

//Çağrılacak ToGrayscale yöntemi
    static float[,] ToGrayscale(TextureData td)
    {
        var ret = new float[td.Width, td.Height];
        var stride = td.Stride;
        var data = td.Data;
        var bytesPerPixel = td.BytesPerPixel;
        for (int y = 0; y < td.Height; y++)
        {
            int ptr = y * stride;
            for (int x = 0; x < td.Width; x++)
            {
                var v = (data[ptr] * 0.21f + data[ptr + 1] * 0.72f + data[ptr + 2] * 0.07f) / 255.0f;
                ret[x, y] = v;
                ptr += bytesPerPixel;
            }
        }
        return ret;
    }

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Aspose.3D for .NET API hakkında" %}}

 Aspose.3D, 3D dosyalarını yüklemek, değiştirmek ve dönüştürmek için kullanılan bir CAD ve Oyun Yazılımıdır API. API bağımsızdır ve herhangi bir 3D modelleme veya işleme yazılımı gerektirmez. Discreet3DS, WavefrontOBJ, STL (ASCII, Binary), Universal3D, FBX (ASCII, Binary), Collada, glTF, PLY için API kolayca kullanılabilir, GLB, DirectX ve diğer biçimler. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

  {{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Litofhanenizi BMP\'ye Oluşturmak için Ücretsiz Uygulama" sectionDescription="için canlı demolarımızı kontrol edin [Litofan BMP](https://products.aspose.app/3d/lithophane/bmp) aşağıdaki faydaları ile." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Hiçbir şey indirmenize veya kurmanıza gerek yok" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Kod yazmaya veya derlemeye gerek yok" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Sadece BMP dosyasını yükleyin ve \"litofan\" düğmesine basın" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Gerekirse bağlantıdan BMP dosyasını indirin" >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Litofanınızı Biçimlere Göre Oluşturmak için Desteklenen Diğer Uygulama" subTitle="C# kullanarak One, litofanınızı da dahil olmak üzere diğer birçok dosya biçiminde oluşturabilir." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/lithophane/jpeg/" name="JPEG" description="Birleşmiş Fotoğraf Uzmanları Grubu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/lithophane/png/" name="PNG" description="taşınabilir Ağ Grafikleri" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/lithophane/tga/" name="TGA" description="Truevision Gelişmiş Raster Adaptörü" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/lithophane/jpg/" name="JPG" description="Birleşmiş Fotoğraf Uzmanları Grubu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/lithophane/gif/" name="GIF" description="Grafik Değişim Formatı" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/lithophane/tiff/" name="TIFF" description="Etiketli Görüntü Dosyası Formatı" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}