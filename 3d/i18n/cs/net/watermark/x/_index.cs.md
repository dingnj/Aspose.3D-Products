﻿---
title: Přidat slepý vodík do formátů souborů x pomocí .NET 
weight: 830
url: /cs/net/watermark/x/ 
description: C# zdrojový kód pro načtení, renderování a přidání slepého vodního označení k dokumentům x na .NET framework, .NET core, Mono.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Přidat slepý vodní znak k x přes C#" h2="Vytvořte si vlastní aplikace .NET do souborů watermark x pomocí serverových api." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="X" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="X" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="How to watermark to x file using C#" %}}

 S cílem použít soubor vodík x, použijeme ho!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API, který je bohatý na funkce, výkonný a snadno použitelný API pro platformu C# pro použití s přidáním jakéhokoli vodního označení. Otevřít
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

{{% blocks/products/pf/agp/feature-section-col title="Kroky pro přidání slepého vodního označení do x přes C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D umožňuje vývojářům snadno přidat slepý vodík do souboru x jen s několika řádky kódu.

{{% /blocks/products/pf/agp/text %}}

- Načíst soubor x prostřednictvím konstruktora třídy scény- Získejte třídu mesh Aspose.3D- Přidat vodopis a heslo pomocí metody encodewatermark Aspose.3D- Volejte scénu. uložit metodu s objektem
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na systém" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D for .NET je podporován ve všech hlavních operačních systémech. Jen se ujistěte, že máte následující předpoklady.

{{% /blocks/products/pf/agp/text %}}

- Microsoft windows nebo kompatibilní os s .NET framework, .NET core, Mono- Vývojové prostředí jako microsoft visual studio- Aspose.3D for .NET odkazováno ve vašem projektu
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kód pro přidání slepého vodního označení k x" offSpacer="" %}}

```cs

//Zdrojový soubor, který musí být označen vodou, a výstupní soubor po uložení
string file = "template.x";
string output =System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".fbx";

// Vytvořit instance scény
Scene scene = new Scene(file);

//Přidat vodopis a heslo do souborů
var numMeshes = 0;
scene.RootNode.Accept((Node node) =>
{
    var mesh = node.GetEntity<Mesh>();
    if (mesh != null)
    {
        numMeshes++;
        mesh = Watermark.EncodeWatermark(mesh, "HelloWorld", "1234");
        if (mesh != null)
        {
            node.Entity = mesh;
        }
    }
    return true;
});

//Uložit soubor ve formátu, který chcete
scene.Save(output, FileFormat.FBX7400ASCII);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="About Aspose.3D for .NET API" %}}

 Aspose.3D je CAD a gameware API pro načtení, úpravu a převod souborů 3D. API je samostatný a nevyžaduje žádný 3D modelování nebo vykreslování softwaru. Lze snadno použít API pro Discreet3DS, WavefrontOBJ, STL (ascii, binární), Universal3D, FBX (ascii, binární), Collada, glTF, PLY, GLB, directx a další formáty. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Free app to add blind watermark to x" sectionDescription="Check our live demos to [Vodní značka x](https://products.aspose.app/3d/watermark/x) S následujícími přínosy." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Není třeba stáhnout nebo nastavit nic" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Není třeba napsat nebo sestavit kód" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Stačí nahrát soubor x a stiskněte tlačítko \"vodní značka\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Download x file from the link, if required" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="X" readMoreLink="https://docs.fileformat.com/3d/x/" >}}
X je souborem obrazu modelu directx používaný technologií directx, který je určen pro 3D vykreslování grafiky v hrách. Formát souboru určuje 3D objektové struktury pro řetězce, textury, animace a objekty.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Další podporovaná aplikace pro přidání slepého vodopáku do formátů" subTitle="Using C#, one can also add blind watermark to many other file formats including." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/3mf/" name="3MF" description="3D formát výroby" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/amf/" name="AMF" description="Aditivní formát výroby" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/ase/" name="ASE" description="Soubor 2d animace" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/dae/" name="DAE" description="Výměna digitálních aktiv" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/dxf/" name="DXF" description="Formát výkresu" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/drc/" name="DRC" description="Google Draco" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/fbx/" name="FBX" description="Formát 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/glb/" name="GLB" description="3D binární zobrazení souboru" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/gltf/" name="GLTF" description="Formát přenosu gl" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/jt/" name="JT" description="Soubor jupiter tessellation" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/obj/" name="OBJ" description="3D formát souboru" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/ply/" name="PLY" description="Formát souboru polygon" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/pdf/" name="PDF" description="3D PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/rvm/" name="RVM" description="Aveva plant design model" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/stl/" name="STL" description="Zaměnitelná geometrie povrchu 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/u3d/" name="U3D" description="Universal 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/vrml/" name="VRML" description="Jazyk modelování virtuální reality" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/3ds/" name="3DS" description="3D formát souboru studio mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/usd/" name="USD" description="Univerzální popis scény" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/watermark/usdz/" name="USDZ" description="Univerzální scéna popis zip archiv" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}