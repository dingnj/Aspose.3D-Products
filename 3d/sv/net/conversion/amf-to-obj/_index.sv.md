﻿---
title: Konvertera AMF till OBJ via C# 
weight: 2630
url: /sv/net/conversion/amf-to-obj/ 
description: Exempelkod för konvertering från AMF till OBJ C#. Använd API exempelkod för batch-AMF-filer till OBJkonvertering inom VB.NET, Asp.NET eller någon .NET-baserad applikation.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertera AMF till OBJ via C#" h2="Rendera AMF som OBJ utan någon 3D-modellerings- och renderingsprogramvara." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="OBJ" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="AMF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Så här konverterar du AMF till OBJ med C#" %}}

 För att konvertera AMF till OBJ använder vi
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API som är en funktionsrik, kraftfull och lättanvänd dokumenthantering och konvertering API för C#-plattformen. Öppen
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 pakethanterare, sök efter
 Aspose.3D 
 och installera. Du kan också använda följande kommando från Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Pakethanterarens konsolkommando" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steg för att konvertera AMF till OBJ via C#" %}}

{{% blocks/products/pf/agp/text %}}

 .NET programmerare kan enkelt ladda och konvertera AMF filer till OBJ på bara några rader kod.

{{% /blocks/products/pf/agp/text %}}

1. Ladda AMF-filen via konstruktorn för Scene-klassen1. Skapa en instans av ObjSaveOptions1. Ställ in OBJ specifika egenskaper för avancerad konvertering1. Anropa metoden Scene.Save1. Skicka utdatasökvägen med OBJ filtillägg och objekt för ObjSaveOptions1. Kontrollera den resulterande filen OBJ vid angiven sökväg
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Systemkrav" %}}

{{% blocks/products/pf/agp/text %}}

 Innan du kör omvandlingskoden .NET, se till att du har följande förutsättningar.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows eller ett kompatibelt operativsystem med .NET Framework, .NET Core, Mono.- Utvecklingsmiljö som Microsoft Visual Studio.- Aspose.3D for .NET DLL som refereras till i ditt projekt.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Den här exempelkoden visar omvandling från AMF till OBJ C#" offSpacer="" %}}

```cs
// ladda AMF i ett objekt av Scene 
var document = new Aspose.ThreeD.Scene("template.amf");
// skapa en instans av ObjSaveOptions 
var options = new Aspose.ThreeD.Formats.ObjSaveOptions();
// spara AMF som en OBJ 
document.Save("output.obj", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Gratis app för att konvertera AMF till OBJ" sectionDescription="Kolla in våra livedemos för [AMF till OBJ omvandling](https://products.aspose.app/3d/conversion/amf-to-obj) med följande förmåner." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Du behöver inte ladda ner eller ställa in någonting." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Du behöver inte skriva någon kod." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Ladda bara upp din AMF-fil och tryck på \"Konvertera\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Du får omedelbart nedladdningslänken för den resulterande filen OBJ." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Ett 3D filbearbetningsbibliotek för att manipulera 3D filer utan några modellerings- och renderingsprogram. 3D API stöder Discreet3DS, WavefrontOBJ, FBX (ASCII, binär), STL (ASCII, binär), Universal3D, Collada, glTF, GLB, Filformaten PLY, DirectX, Google Draco och mer. Utvecklare kan enkelt skapa, läsa, konvertera, ändra och kontrollera innehållet i 3D dokumentformat.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="AMF" readMoreLink="https://docs.fileformat.com/3d/amf/" >}}
Filformatet Additive Manufacturing (AMF) definierar öppna standarder för objektbeskrivningar för att kunna användas av additiv tillverkningsprocess som 3D utskrift. CAD-program använder filformatet AMF genom att använda informationen som geometri, färg och material för objekten. AMF skiljer sig från formatet STL eftersom lateralen inte stöder färg, material, gitter och konstellationer.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="obj" readMoreLink="https://docs.fileformat.com/3d/obj/" >}}
OBJ filer används av Wavefronts Advanced Visualizer-applikation för att definiera och lagra de geometriska objekten. Bakåt- och framåtöverföring av geometriska data är möjlig genom OBJ filer. Både polygonal geometri som punkter, linjer, texturhörn, ytor och friformsgeometri (kurvor och ytor) stöds av formatet OBJ. Det här formatet stöder inte animering eller information relaterad till ljus och sceners position. En OBJ-fil är vanligtvis en slutprodukt av 3D-modelleringsprocessen som genereras av en CAD (Computer Aided Design). Standardordningen för att lagra hörn är moturs för att undvika explicit deklaration av ansiktsnormaler. Även om OBJ filer deklarerar skalinformation i en kommentarsrad har inga enheter deklarerats för OBJ koordinater.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="Du kan också konvertera AMF till många andra filformat, inklusive några som anges nedan." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/amf-to-3ds/" name="AMF TILL 3DS" description="3D Studio DOS Mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/amf-to-dae/" name="AMF TILL DAE" description="Digital Asset Exchange" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/amf-to-fbx/" name="AMF TILL FBX" description="3D Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/amf-to-html/" name="AMF TILL HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/amf-to-obj/" name="AMF TILL OBJ" description="3D Filformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/amf-to-pdf/" name="AMF TILL PDF" description="Portabelt dokumentformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/amf-to-ply/" name="AMF TILL PLY" description="Polygon filformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/amf-to-rvm/" name="AMF TILL RVM" description="AVEVA Plant Design Model" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/amf-to-stl/" name="AMF TILL STL" description="Utbytbar 3D ytgeometri" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/amf-to-u3d/" name="AMF TILL U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}