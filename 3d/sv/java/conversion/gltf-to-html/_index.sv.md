﻿---
title: Konvertera GLTF till HTML via Java 
weight: 1700
url: /sv/java/conversion/gltf-to-html/ 
description: Exempel på Java-konverteringskod för GLTF-format till HTML-fil. Använd den här exempelkoden för att konvertera GLTF till HTML i valfri webb- eller datorbaserad applikation Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konvertera GLTF till HTML via Java" h2="GLTF till HTML omvandling med Java-biblioteket utan någon 3D-modelleringsprogramvara." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="HTML" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="GLTF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="Så här konverterar du GLTF till HTML med Java" %}}

 För att rendera GLTF till HTML använder vi
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API som är en funktionsrik, kraftfull och lättanvänd konverteringsplattform API for Java. Du kan ladda ner den senaste versionen direkt från
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
 och installera det i ditt Maven-baserade projekt genom att lägga till följande konfigurationer till pom.xml.

{{% blocks/products/pf/agp/code-block title="Förvar" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Beroende" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Steg för att konvertera GLTF till HTML via Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java-programmerare kan enkelt konvertera GLTF-filen till HTML på bara några rader kod.

{{% /blocks/products/pf/agp/text %}}

1. Ladda GLTF-filen via konstruktorn för Scene-klassen1. Skapa en instans av HtmlSaveOptions1. Ställ in HTML specifika egenskaper för avancerad konvertering1. Ring Scene.save-metoden1. Skicka utdatasökvägen med HTML filtillägg och objekt för HtmlSaveOptions
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Systemkrav" %}}

{{% blocks/products/pf/agp/text %}}

 Innan du kör omvandlingskoden Java, se till att du har följande förutsättningar.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows eller ett kompatibelt operativsystem med Java Runtime Environment för JSP/JSF Application och Desktop Applications.- Hämta den senaste versionen av Aspose.3D for Java direkt från Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="GLTF till HTML Java Omvandlingskällkod" offSpacer="" %}}

```cs
// ladda GLTF i ett objekt av Scene 
Scene document = new Scene("template.gltf");
// skapa en instans av HtmlSaveOptions 
Html5SaveOptions options = new Html5SaveOptions();
// spara GLTF som en HTML 
document.save("output.html", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="GLTF till HTML Live Demos för konvertering" sectionDescription="[Konvertera GLTF till HTML](https://products.aspose.app/3d/conversion/gltf-to-html) just nu genom att besöka vår Live Demos-webbplats. Livedemon har följande fördelar" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Du behöver inte ladda ned Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Du behöver inte skriva någon kod." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Ladda bara upp din GLTF-fil, den konverteras omedelbart till HTML." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Du kommer att få nedladdningslänken." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Scenmanipulationsbibliotek" %}}

 Aspose.3D är ett CAD och spelprogram API för att ladda, ändra och konvertera 3D filer. API är en fristående och kräver ingen 3D-modellerings- eller renderingsprogramvara. Man kan enkelt använda API för Discreet3DS, WavefrontOBJ, STL (ASCII, binär), Universal3D, FBX (ASCII, binär), Collada, glTF, PLY, GLB, DirectX och fler format. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLTF" readMoreLink="https://docs.fileformat.com/3d/gltf/" >}}

glTF (GL-överföringsformat) är ett 3D-filformat som lagrar 3D modellinformation i JSON-format. Användningen av JSON minimerar både storleken på 3D tillgångar och den körtidsbearbetning som krävs för att packa upp och använda dessa tillgångar. Den användes för effektiv överföring och laddning av 3D scener och modeller efter applikationer. glTF har utvecklats av Khronos Group 3D Formats Working Group och beskrivs också som JPEG av 3D av dess skapare. Formatet definierar ett utbyggbart, vanligt publiceringsformat för 3D innehållsverktyg och tjänster som effektiviserar författararbetsflöden och möjliggör interoperabel användning av innehåll i hela branschen. Avsikten bakom skapandet av filformatet glTF var att definiera ett utbyggbart, vanligt publiceringsformat för 3D innehållsverktyg och tjänster som skulle effektivisera författararbetsflöden och möjliggöra interoperabel användning av innehåll i hela branschen. Det minimerar körtidsbearbetning av applikationer som använder WebGL och andra API:er.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="HTML" readMoreLink="https://docs.fileformat.com/web/html/" >}}

HTML (Hyper Text Markup Language) är tillägget för webbsidor som skapats för visning i webbläsare. Känt som webbens språk, har HTML utvecklats med krav på nya informationskrav som ska visas som en del av webbsidor. Den senaste varianten är känd som HTML 5 som ger mycket flexibilitet för att arbeta med språket. HTML sidor tas antingen emot från servern, där dessa är värd, eller kan också laddas från det lokala systemet. Varje HTML-sida består av HTML element som formulär, text, bilder, animationer, länkar etc. Dessa element representeras av taggar som img, a, p och flera andra där varje tagg har start och slut . Den kan också bädda in applikationer skrivna på skriptspråk som JavaScript och Style Sheets (CSS) för övergripande layoutrepresentation.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andra omvandlingar som stöds" subTitle="Du kan också konvertera GLTF till många andra filformat, inklusive några som anges nedan." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-3ds/" name="GLTF TILL 3DS" description="3D Studio DOS Mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-amf/" name="GLTF TILL AMF" description="Additiv tillverkningsformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-ase/" name="GLTF TILL ASE" description="2D-animationsfil" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-dae/" name="GLTF TILL DAE" description="Digital Asset Exchange" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-fbx/" name="GLTF TILL FBX" description="3D Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-obj/" name="GLTF TILL OBJ" description="3D Filformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-ply/" name="GLTF TILL PLY" description="Polygon filformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-rvm/" name="GLTF TILL RVM" description="AVEVA Plant Design Model" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-stl/" name="GLTF TILL STL" description="Utbytbar 3D ytgeometri" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/gltf-to-u3d/" name="GLTF TILL U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}