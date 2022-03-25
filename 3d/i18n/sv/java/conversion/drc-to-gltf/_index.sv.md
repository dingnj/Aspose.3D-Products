﻿---
title: Konvertera DRC till GLTF via Java 
url: /sv/java/conversion/drc-to-gltf/ 
description: Prov Java konverteringskod för DRC-format till GLTF-fil. Använd den här exempelkoden för att konvertera DRC till GLTF inom någon webb- eller skrivbordsbaserad program Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertera DRC till GLTF via Java" h2="DRC till GLTF konvertering med Java bibliotek utan någon 3D modelleringsprogram." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="GLTF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DRC" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="Hur man konverterar DRC till GLTF använder Java" %}}

 För att visa DRC till GLTF, använder vi oss av.
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API som är en funktionsrika, kraftfull och lättanvänd konverteringsplattform API for Java. Du kan ladda ner den senaste versionen direkt från
 [Maven Ordförande](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
 Och installera det i ditt Maven-baserade projekt genom att lägga till följande konfigurationer till pom.xml.

{{% blocks/products/pf/agp/code-block title="Arkiv" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://Repository.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Beroendet" offSpacer="true" %}}

```cs
<dependency>
<groupId>com.aspose</groupId>
<artifactId>aspose-3d</artifactId>
<version>version of aspose-3d API</version>
<classifier>jdk17</classifier>
</dependency>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steg för att konvertera DRC till GLTF via Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java programmerare kan enkelt konvertera DRC filen till GLTF på bara några få kodrader.

{{% /blocks/products/pf/agp/text %}}

1. Ladda DRC- filen via konstruktören i scenens klass1. Skapa en instans av GltfSaveOptions1. Ange GLTF specifika egenskaper för avancerad konvertering1. Ring Scene.save- metoden1. Passera utdata sökvägen med GLTF filändelse & objekt av GltfSaveOptions.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Systemkrav" %}}

{{% blocks/products/pf/agp/text %}}

 Innan du kör Java konverteringskoden, se till att du har följande förutsättningar.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows eller ett kompatibelt operativsystem med Java Runtime Environment för JSP/JSF Applikationer och skrivbordsprogram.- Hämta senaste version av Aspose.3D for Java direkt från Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="DRC till GLTF Java Konverteringskältkod" offSpacer="" %}}

```cs
// Ladda DRC i ett objekt i Scene 
Scene document = new Scene("template.drc");
// Skapa en instans av GltfSaveOptionsName 
AmfSaveOptions options = new GltfSaveOptions();
// Spara DRC som en GLTF 
document.save("output.gltf", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="DRC till GLTF Konvertering levande demos" sectionDescription="[Konvertera DRC till GLTF](https://products.aspose.app/3d/conversion/drc-to-gltf) Just nu genom att besöka vår Live Demos hemsida.The live demo har följande fördelar" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Du behöver inte ladda ner Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Du behöver inte skriva någon kod." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Bara ladda upp din DRC-fil, den kommer att konverteras omedelbart till GLTF." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Du kommer att få nedladdningslänken." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Scenmanipulationsbiblioteket" %}}

 Aspose.3D är en CAD och spelprogram API för att ladda, ändra och konvertera 3D filer. API är en fristående och kräver ingen 3D modellering eller rendering programvara. Man kan enkelt använda API för Discreet3DS, WavefrontOBJ, STL (ASCII, Binary), Universal3D, FBX (ASCII, binär), Collada, glTF, PLY, GLB, DirectX och fler format. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DRC" readMoreLink="https://docs.fileformat.com/3d/drc/" >}}

En fil med . Drc-tillägg är ett komprimerat 3D filformat skapat med Google Draco bibliotek. Google erbjuder Draco som öppen källkodsbibliotek för att komprimera och dekomprimera 3D geometriska maskor och punktmoln, och förbättrar lagring och överföring av 3D grafik. Den kodar indata och sparar den som . Drc-fil. I mottagande slut, står API . Drc-filer och kan lägga ut dessa som PLY eller OBJ filer. Den komprimerade utdatafilen gör det möjligt för användare att ladda ner appar snabbare och ge snabb laddad 3D grafik i webbläsare.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLTF" readMoreLink="https://docs.fileformat.com/3d/gltf/" >}}

glTF (GL Transmission Format) är ett 3D filformat som lagrar 3D modell information i JSON-format. Användningen av JSON minimerar både storleken på 3D tillgångar och den körtidsbehandling som krävs för att packa upp och använda dessa tillgångar. Det antogs för effektiv överföring och lastning av 3D scener och modeller genom ansökningar. glTF utvecklades av Khronos Group 3D Formats Working Group och beskrivs också som JPEG av 3D av dess skapare. Formatet definierar en utökbar, gemensamt publiceringsformat för 3D innehållsverktyg och innehållstjänster som effektiviserar att utveckla arbetsflöden och möjliggör interoperabel användning av innehåll överst industrin. Avsikten bakom skapandet av glTF filformat var att definiera en extensibel, gemensamt publiceringsformat för 3D innehållsverktyg och innehållstjänster som ska effektivisera utvecklingen av arbetsflöden och möjliggöra interoperabel användning av innehåll på alla sätt industrin. Det minimerar körtidsbehandling av program som använder WebGL och andra API.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}