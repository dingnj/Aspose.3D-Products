﻿---
title: GLTF in PDF konvertieren über C# 
url: /de/net/conversion/gltf-to-pdf/ 
description: Beispielcode für die Konvertierung von GLTF in PDF C#. Verwenden Sie API Beispielcode für Batch GLTF-Dateien in PDF-Konvertierung innerhalb von VB.NET, Asp.NET oder einer beliebigen .NET-basierten Anwendung.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="GLTF in PDF konvertieren über C#" h2="Rendern Sie GLTF als PDF ohne 3D Modellierungs-und Rendering software." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PDF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="GLTF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="So konvertieren Sie GLTF in PDF mit C#" %}}

 Um GLTF in PDF zu konvertieren, verwenden wir
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API, eine funktions reiche, leistungs starke und einfach zu verwendende Dokumenten manipulation und-konvertierung API für C# Plattform. Öffnen Sie
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 Paket manager, suche nach
 Aspose.3D 
 Und installieren. Sie können auch den folgenden Befehl von der Package Manager-Konsole verwenden.

{{% blocks/products/pf/agp/code-block title="Paket-Manager-Konsolen befehl" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Schritte zum Konvertieren von GLTF in PDF über C#" %}}

{{% blocks/products/pf/agp/text %}}

 .NET Programmierer können GLTF Dateien in nur wenigen Code zeilen einfach in PDF laden und konvertieren.

{{% /blocks/products/pf/agp/text %}}

1. Laden Sie die GLTF-Datei über den Konstruktor der Scene-Klasse1. Erstellen Sie eine Instanz von AmfSaveOptions1. Legen Sie PDF spezifische Eigenschaften für die erweiterte Konvertierung fest1. Rufen Sie die Szene auf. Methode speichern1. Übergeben Sie den Ausgabe pfad mit PDF Datei erweiterung & Objekt von PdfSaveOptions1. Überprüfen Sie die resultierende PDF-Datei unter dem angegebenen Pfad
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Systema forderungen" %}}

{{% blocks/products/pf/agp/text %}}

 Bevor Sie den .NET-Konvertierungs code ausführen, stellen Sie sicher, dass Sie über die folgenden Voraussetzungen verfügen.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows oder ein kompatibles Betriebs system mit .NET Framework, .NET Core, Mono.- Entwicklungs umgebung wie Microsoft Visual Studio.- Aspose.3D for .NET DLL, auf die in Ihrem Projekt verwiesen wird.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Dieser Beispielcode zeigt GLTF in PDF C# Konvertierung" offSpacer="" %}}

```cs
// Laden Sie die GLTF in einem Objekt der Szene 
var document = new Aspose.ThreeD.Scene("template.gltf");
// Erstellen Sie eine Instanz von PdfSaveOptions 
var options = new Aspose.ThreeD.Formats.PdfSaveOptions();
// GLTF als PDF speichern 
document.Save("output.pdf", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Kostenlose App zum Konvertieren von GLTF in PDF" sectionDescription="Überprüfen Sie unsere Live-Demos für [GLTF auf PDF Konvertierung](https://products.aspose.app/3d/conversion/gltf-to-pdf) Mit folgenden Vorteilen." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Keine Notwendigkeit, etwas herunter zuladen oder einzurichten." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Sie müssen keinen Code schreiben." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Laden Sie einfach Ihre GLTF-Datei hoch und klicken Sie auf die Schaltfläche \"Konvertieren\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Sie erhalten sofort den Download-Link für die resultierende PDF-Datei." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Eine 3D Datei verarbeitung bibliothek zum Bearbeiten von 3D Dateien ohne Modellierung und Rendering-Software. Die 3D API unterstützt Discreet3DS, WavefrontOBJ, FBX (ASCII, Binär), STL (ASCII, Binär), Universal3D, Collada, glTF, GLB, PLY, DirectX, Google Draco Dateiformate und mehr. Entwickler können den Inhalt von 3D Dokument formaten einfach erstellen, lesen, konvertieren, ändern und steuern.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLTF" readMoreLink="https://docs.fileformat.com/3d/gltf/" >}}
glTF (GL Transmission Format) ist ein 3D-Dateiformat, das 3D Modell informationen im JSON-Format speichert. Die Verwendung von JSON minimiert sowohl die Größe von 3D Assets als auch die Laufzeit verarbeitung, die zum Entpacken und Verwenden dieser Assets erforderlich ist. Es wurde für die effiziente Übertragung und das Laden von 3D Szenen und Modellen durch Anwendungen übernommen. glTF wurde von der Khronos Group 3D Formate Working Group entwickelt und wird von ihren Erstellern auch als JPEG von 3D bezeichnet. Das Format definiert ein erweiterbares, allgemeines Veröffentlichung format für 3D Inhalts tools und-dienste, das die Erstellung von Workflows optimiert und die inter opera ble Verwendung von Inhalten in der gesamten Branche ermöglicht. Die Absicht hinter der Erstellung des glTF-Dateiformats bestand darin, ein erweiterbares, allgemeines Veröffentlichung format für 3D Inhalts tools und-dienste zu definieren, das die Workflows für die Autor isierung rationalisieren und die inter opera ble Nutzung von Inhalten in der gesamten Branche ermöglichen sollte. Es minimiert die Laufzeit verarbeitung durch Anwendungen mit WebGL und anderen APIs.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="pdf" readMoreLink="https://docs.fileformat.com/view/pdf/" >}}
Portable Document Format (PDF) ist eine Art von Dokument von Adobe in den 1990er Jahren erstellt. Der Zweck dieses Dateiformats bestand darin, einen Standard für die Darstellung von Dokumenten und anderem Referenz material in einem Format einzuführen, das unabhängig von Anwendungs software, Hardware und Betriebs system ist. PDF Dateien können in Adobe Acrobat Reader/Writer sowie in den meisten modernen Browsern wie Chrome, Safari, Firefox über Erweiterungen/Plug-Ins geöffnet werden. Die meisten im Handel erhältlichen Software-Suiten bieten auch die Konvertierung ihrer Dokumente in ein PDF-Dateiformat an, ohne dass zusätzliche Software komponenten erforderlich sind. Somit kann das PDF-Dateiformat Informationen wie Text, Bilder, Hyperlinks, Formular felder, Rich Media, digitale Signaturen, Anhänge, Metadaten, Geospatial-Features und 3D Objekte enthalten, die als Teil des Quell dokuments werden können.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}