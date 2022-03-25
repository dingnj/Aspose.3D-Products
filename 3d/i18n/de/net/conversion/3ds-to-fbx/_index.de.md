﻿---
title: 3DS in FBX konvertieren über C# 
weight: 2020
url: /de/net/conversion/3ds-to-fbx/ 
description: Beispielcode für die Konvertierung von 3DS in FBX C#. Verwenden Sie API Beispielcode für Batch 3DS-Dateien in FBX-Konvertierung innerhalb von VB.NET, Asp.NET oder einer beliebigen .NET-basierten Anwendung.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="3DS in FBX konvertieren über C#" h2="Rendern Sie 3DS als FBX ohne 3D Modellierungs-und Rendering software." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="FBX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="3DS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="So konvertieren Sie 3DS in FBX mit C#" %}}

 Um 3DS in FBX zu konvertieren, verwenden wir
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

{{% blocks/products/pf/agp/feature-section-col title="Schritte zum Konvertieren von 3DS in FBX über C#" %}}

{{% blocks/products/pf/agp/text %}}

 .NET Programmierer können 3DS Dateien in nur wenigen Code zeilen einfach in FBX laden und konvertieren.

{{% /blocks/products/pf/agp/text %}}

1. Laden Sie die 3DS-Datei über den Konstruktor der Scene-Klasse1. Erstellen Sie eine Instanz von FbxSaveOptions1. Legen Sie FBX spezifische Eigenschaften für die erweiterte Konvertierung fest1. Rufen Sie die Szene auf. Methode speichern1. Übergeben Sie den Ausgabe pfad mit der Datei erweiterung FBX und dem Objekt von FbxSaveOptions1. Überprüfen Sie die resultierende FBX-Datei unter dem angegebenen Pfad
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Systema forderungen" %}}

{{% blocks/products/pf/agp/text %}}

 Bevor Sie den .NET-Konvertierungs code ausführen, stellen Sie sicher, dass Sie über die folgenden Voraussetzungen verfügen.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows oder ein kompatibles Betriebs system mit .NET Framework, .NET Core, Mono.- Entwicklungs umgebung wie Microsoft Visual Studio.- Aspose.3D for .NET DLL, auf die in Ihrem Projekt verwiesen wird.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Dieser Beispielcode zeigt 3DS in FBX C# Konvertierung" offSpacer="" %}}

```cs
// Laden Sie die 3DS in einem Objekt der Szene 
var document = new Aspose.ThreeD.Scene("template.3ds");
// Erstellen Sie eine Instanz von FbxSaveOptions 
var options = new Aspose.ThreeD.Formats.FbxSaveOptions();
// 3DS als FBX speichern 
document.Save("output.fbx", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Kostenlose App zum Konvertieren von 3DS in FBX" sectionDescription="Überprüfen Sie unsere Live-Demos für [3DS auf FBX Konvertierung](https://products.aspose.app/3d/conversion/3ds-to-fbx) Mit folgenden Vorteilen." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Keine Notwendigkeit, etwas herunter zuladen oder einzurichten." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Sie müssen keinen Code schreiben." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Laden Sie einfach Ihre 3DS-Datei hoch und klicken Sie auf die Schaltfläche \"Konvertieren\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Sie erhalten sofort den Download-Link für die resultierende FBX-Datei." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Eine 3D Datei verarbeitung bibliothek zum Bearbeiten von 3D Dateien ohne Modellierung und Rendering-Software. Die 3D API unterstützt Discreet3DS, WavefrontOBJ, FBX (ASCII, Binär), STL (ASCII, Binär), Universal3D, Collada, glTF, GLB, PLY, DirectX, Google Draco Dateiformate und mehr. Entwickler können den Inhalt von 3D Dokument formaten einfach erstellen, lesen, konvertieren, ändern und steuern.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="3DS" readMoreLink="https://docs.fileformat.com/3d/3ds/" >}}
Eine Datei mit 3DS Erweiterung steht für das von Autodesk 3D Studio (DOS) verwendete Mesh-Dateiformat 3D Studio. Autodesk 3D Studio ist seit den 1990er Jahren auf dem Markt für 3D Dateiformate und hat sich nun zu 3D Studio MAX für die Arbeit mit 3D Modellierung, Animation und Rendering entwickelt. Eine 3DS-Datei enthält Daten zur 3D Darstellung von Szenen und Bildern und ist eines der gängigen Dateiformate für 3D Daten import und-export. Es berücksicht igt Informationen wie Kamera positionen, Mesh-Daten, Beleuchtungs informationen, Ansicht fenster konfigurationen, Glättung gruppen daten, Bitmap-Referenzen und Attribute, um Eckpunkte und Polygone zum Rendern einer Szene zu erstellen.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="fbx" readMoreLink="https://docs.fileformat.com/3d/fbx/" >}}
FBX, FilmBox, ist ein beliebtes 3D Dateiformat, das ursprünglich von Kaydara für Motion Builder entwickelt wurde. Es wurde 2006 von Autodesk Inc übernommen und ist heute eines der wichtigsten 3D-Austausch formate, wie es von vielen 3D-Tools verwendet wird. FBX ist sowohl im binären als auch im ASCII-Dateiformat verfügbar. Das Format wurde eingerichtet, um Inter operabilität zwischen Anwendungen zur Erstellung digitaler Inhalte zu schaffen. Es gibt viele Tools für die Konvertierung von/in FBX Dateiformat.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte Conversions" subTitle="Sie können 3DS auch in viele andere Dateiformate konvertieren, darunter einige unten aufgeführten." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-amf/" name="3DS BIS AMF" description="Additives Fertigungs format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-dae/" name="3DS BIS DAE" description="Digital Asset Exchange" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-html/" name="3DS BIS HTML" description="Hyper Text Markup Sprache" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-obj/" name="3DS BIS OBJ" description="3D Dateiformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-pdf/" name="3DS BIS PDF" description="Tragbares Dokument format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-ply/" name="3DS BIS PLY" description="Polygon-Dateiformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-rvm/" name="3DS BIS RVM" description="AVEVA Plant Design Modell" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-stl/" name="3DS BIS STL" description="Austauschbare 3D Oberflächen geometrie" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-u3d/" name="3DS BIS U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}