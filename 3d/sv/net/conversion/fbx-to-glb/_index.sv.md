﻿---
title: Konvertera FBX till GLB via C# 
url: /sv/net/conversion/fbx-to-glb/ 
description: Exempelkod för konvertering från FBX till GLB C#. Använd API exempelkod för batch-FBX-filer till GLBkonvertering inom VB.NET, Asp.NET eller någon .NET-baserad applikation.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertera FBX till GLB via C#" h2="Rendera FBX som GLB utan någon 3D-modellerings- och renderingsprogramvara." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="GLB" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="FBX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Så här konverterar du FBX till GLB med C#" %}}

 För att konvertera FBX till GLB använder vi
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

{{% blocks/products/pf/agp/feature-section-col title="Steg för att konvertera FBX till GLB via C#" %}}

{{% blocks/products/pf/agp/text %}}

 .NET programmerare kan enkelt ladda och konvertera FBX filer till GLB på bara några rader kod.

{{% /blocks/products/pf/agp/text %}}

1. Ladda FBX-filen via konstruktorn för Scene-klassen1. Skapa en instans av AmfSaveOptions1. Ställ in GLB specifika egenskaper för avancerad konvertering1. Anropa metoden Scene.Save1. Skicka utdatasökvägen med GLB filtillägg och objekt för StlSaveOptions1. Kontrollera den resulterande filen GLB vid angiven sökväg
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Systemkrav" %}}

{{% blocks/products/pf/agp/text %}}

 Innan du kör omvandlingskoden .NET, se till att du har följande förutsättningar.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows eller ett kompatibelt operativsystem med .NET Framework, .NET Core, Mono.- Utvecklingsmiljö som Microsoft Visual Studio.- Aspose.3D for .NET DLL som refereras till i ditt projekt.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Den här exempelkoden visar omvandling från FBX till GLB C#" offSpacer="" %}}

```cs
// ladda FBX i ett objekt av Scene 
var document = new Aspose.ThreeD.Scene("template.fbx");
// skapa en instans av GltfSaveOptions 
var options = new Aspose.ThreeD.Formats.GltfSaveOptions(FileContentType.Binary);
// spara FBX som en GLB 
document.Save("output.glb", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Gratis app för att konvertera FBX till GLB" sectionDescription="Kolla in våra livedemos för [FBX till GLB omvandling](https://products.aspose.app/3d/conversion/fbx-to-glb) med följande förmåner." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Du behöver inte ladda ner eller ställa in någonting." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Du behöver inte skriva någon kod." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Ladda bara upp din FBX-fil och tryck på \"Konvertera\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Du får omedelbart nedladdningslänken för den resulterande filen GLB." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Ett 3D filbearbetningsbibliotek för att manipulera 3D filer utan några modellerings- och renderingsprogram. 3D API stöder Discreet3DS, WavefrontOBJ, FBX (ASCII, binär), GLB (ASCII, binär), Universal3D, Collada, glTF, GLB, Filformaten PLY, DirectX, Google Draco och mer. Utvecklare kan enkelt skapa, läsa, konvertera, ändra och kontrollera innehållet i 3D dokumentformat.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="FBX" readMoreLink="https://docs.fileformat.com/3d/fbx/" >}}
FBX, FilmBox, är ett populärt 3D-filformat som ursprungligen utvecklades av Kaydara för MotionBuilder. Det förvärvades av Autodesk Inc 2006 och är nu ett av de viktigaste 3D-utbytesformaten som används av många 3D-verktyg. FBX är tillgänglig i både binärt och ASCII-filformat. Formatet skapades för att tillhandahålla interoperabilitet mellan applikationer för skapande av digitalt innehåll. Det finns många tillgängliga verktyg för konvertering från/till filformatet FBX.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLB" readMoreLink="https://docs.fileformat.com/3d/glb/" >}}
GLB är den binära filformatsrepresentationen av 3D modeller sparade i GL-överföringsformatet (glTF). Information om 3D-modeller som nodhierarki, kameror, material, animationer och maskor i binärt format. Det här binära formatet lagrar tillgången glTF (JSON, .bin och bilder) i en binär blob. Det undviker också problemet med ökning av filstorleken som inträffar vid glTF. Filformatet GLB resulterar i kompakta filstorlekar, snabb inläsning, komplett 3D scenrepresentation och utökbarhet för vidareutveckling. Formatet använder model/gltf-binary som MIME-typ.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}