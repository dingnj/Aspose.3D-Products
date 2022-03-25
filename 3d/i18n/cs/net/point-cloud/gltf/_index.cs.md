﻿---
title: Generovat formát souborů point cloud do GLTF prostřednictvím .NET 
weight: 830
url: /cs/net/point-cloud/gltf/ 
description: C# zdrojový kód pro načtení, renderování a přidání generování bodu cloud do dokumentů GLTF na .NET framework, .NET core, Mono.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Generovat point cloud na GLTF přes C#" h2="Vytvořte vlastní aplikace .NET pro generování souborů point cloud do GLTF pomocí api na straně serveru." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="GLTF" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="GLTF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="How to generate point cloud to GLTF file using C#" %}}

 Pro generování souboru point cloud do GLTF použijeme
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API, který je bohatý na funkce, výkonný a snadno použitelný API pro platformu C#, která má být používána při generování point cloud. Otevřít
 [Nuget](https://www.nuget.org/packages/aspose.3d) 
 Správce balíčků, hledat
 **Aspose.3D** 
 A nainstalovat. Můžete použít také následující příkaz z konzoly správce balíků.

{{% blocks/products/pf/agp/code-block title="Příkaz konzoly správce balíků" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroky pro generování point cloud na GLTF prostřednictvím C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D umožňuje vývojářům snadno generovat point cloud do souboru GLTF s několika řadami kódu.

{{% /blocks/products/pf/agp/text %}}

- Načíst soubor GLTF prostřednictvím konstruktora třídy scény- Získat objekt pointcloud z Aspose.3D- Vytvořit objekt transformace pomocí metody evaluateglobaltransform- Generovat point cloud pomocí metody sloučení- Volejte scénu. uložit metodu s objektem
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D for .NET je podporován ve všech hlavních operačních systémech. Jen se ujistěte, že máte následující předpoklady.

{{% /blocks/products/pf/agp/text %}}

- Microsoft windows nebo kompatibilní os s .NET framework, .NET core, Mono- Vývojové prostředí jako microsoft visual studio- Aspose.3D for .NET odkazováno ve vašem projektu
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kód pro generování point cloud na GLTF" offSpacer="" %}}

```cs

//Zdrojový soubor, který musí generovat point cloud
string file = "template.gltf";

// Vytvořit instance scény
Scene scene = new Scene(file);

//Získat objekt pointcloud z Aspose.3D a generovat point cloud
var pc = new PointCloud();
scene.RootNode.Accept((Node n) =>
{
    if (n.Entities.Count > 0)
    {
        var transform = n.EvaluateGlobalTransform(true);
        foreach (var entity in n.Entities)
        {
            if (entity is Geometry g)
            {
                Merge(pc, g, transform);
            }
            else if (entity is IMeshConvertible mc)
            {
                var mesh = mc.ToMesh();
                Merge(pc, mesh, transform);
            }

        }
    }
    return true;
});

//Metoda sloučení pro generování bodových mračen
private void Merge(PointCloud pc, Geometry g, Matrix4 transform)
{
    var tmp = PointCloud.FromGeometry(g, 10);
    for (int i = 0; i < tmp.ControlPoints.Count; i++)
    {
        var pt = transform * tmp.ControlPoints[i];
        pc.ControlPoints.Add(pt);
    }
}

// Vytvořit instance newscene
var newScene = new Scene(pc);

//Při ukládání je třeba vytvořit objekt saveoptions ve formátu uložit
string output=System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".ply";
PlySaveOptions ply = new PlySaveOptions();
ply.PointCloud = true;
newScene.Save(output,ply);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="About Aspose.3D for .NET API" %}}

 Aspose.3D je CAD a gameware API pro načtení, úpravu a převod souborů 3D. API je samostatný a nevyžaduje žádný 3D modelování nebo vykreslování softwaru. Lze snadno použít API pro Discreet3DS, WavefrontOBJ, STL (ascii, binární), Universal3D, FBX (ascii, binární), Collada, glTF, PLY, GLB, directx a další formáty. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

  {{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Free app to generate point cloud to GLTF" sectionDescription="Check our live demos to [Point cloud 3DS](https://products.aspose.app/3d/point-cloud/gltf) S následujícími přínosy." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Není třeba stáhnout nebo nastavit nic" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Není třeba napsat nebo sestavit kód" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Stačí nahrát soubor GLTF a stiskněte tlačítko \"generovat\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Download GLTF file from the link, if required" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLTF" readMoreLink="https://docs.fileformat.com/3d/gltf/" >}}
glTF (gl transmission format) je formát 3D, který uchovává informace o modelu 3D ve formátu json. Použití json minimalizuje jak velikost aktiv 3D, tak i provozní zpracování potřebné k rozbalení a využití těchto aktiv. It was adopted for the efficient transmission and loading of 3D scenes and models by applications.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Další podporovaná aplikace pro vytváření formátů point cloud" subTitle="Using C#, one can also generate point cloud to many other file formats including." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/3mf/" name="3MF" description="3D formát výroby" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/amf/" name="AMF" description="Aditivní formát výroby" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/ase/" name="ASE" description="Soubor 2d animace" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/dae/" name="DAE" description="Výměna digitálních aktiv" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/dxf/" name="DXF" description="Formát výkresu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/drc/" name="DRC" description="Google Draco" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/fbx/" name="FBX" description="Formát 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/glb/" name="GLB" description="3D binární zobrazení souboru" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/3ds/" name="3DS" description="3D formát souboru studio mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/jt/" name="JT" description="Soubor jupiter tessellation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/obj/" name="OBJ" description="3D formát souboru" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/ply/" name="PLY" description="Formát souboru polygon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/pdf/" name="PDF" description="3D PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/rvm/" name="RVM" description="Aveva plant design model" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/stl/" name="STL" description="Zaměnitelná geometrie povrchu 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/u3d/" name="U3D" description="Universal 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/vrml/" name="VRML" description="Jazyk modelování virtuální reality" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/x/" name="X" description="Obrázek modelu directx" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/usd/" name="USD" description="Univerzální popis scény" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/usdz/" name="USDZ" description="Univerzální scéna popis zip archiv" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}