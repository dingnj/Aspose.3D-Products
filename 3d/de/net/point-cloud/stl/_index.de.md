﻿---
title: Punktwolke in STL Dateiformaten über .NET generieren 
weight: 830
url: /de/net/point-cloud/stl/ 
description: C# Quellcode zum Laden, Rendern und Hinzufügen von generierten Punktwolken zu STL Dokumenten auf .NET Framework, .NET Core, Mono.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Punktwolke zu STL über C# generieren" h2="Erstellen Sie Ihre eigenen .NET-Apps, um mit serverseitigen APIs Punktwolken in STL-Dateien zu generieren." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="STL" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="STL" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="So generieren Sie eine Punktwolke in eine STL-Datei mit C#" %}}

 Um eine Punktwolke in der STL-Datei zu generieren, verwenden wir
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API, eine funktionsreiche, leistungsstarke und benutzerfreundliche API für C#-Plattform, die mit der Generierung von Punktwolken verwendet werden kann. Offen
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 Paketmanager, suche nach
 **Aspose.3D** 
 und installieren. Sie können auch den folgenden Befehl in der Paket-Manager-Konsole verwenden.

{{% blocks/products/pf/agp/code-block title="Paket-Manager-Konsolenbefehl" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Schritte zum Generieren einer Punktwolke zu STL über C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D macht es Entwicklern leicht, mit nur wenigen Codezeilen Punktwolken für die STL-Datei zu generieren.

{{% /blocks/products/pf/agp/text %}}

- Laden Sie die STL-Datei über den Konstruktor der Scene-Klasse- Punktwolkenobjekt von Aspose.3D abrufen- Erstellen Sie ein Transformationsobjekt mit der EvaluateGlobalTransform-Methode- Generieren Sie Punktwolken mit der Merge-Methode- Rufen Sie die Scene.Save-Methode mit Objekt auf
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Anforderungen" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D for .NET wird auf allen wichtigen Betriebssystemen unterstützt. Stellen Sie einfach sicher, dass Sie die folgenden Voraussetzungen erfüllen.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows oder ein kompatibles Betriebssystem mit .NET Framework, .NET Core, Mono- Entwicklungsumgebung wie Microsoft Visual Studio- Aspose.3D for .NET in Ihrem Projekt referenziert
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C#-Code zum Generieren einer Punktwolke für STL" offSpacer="" %}}

```cs

//Die Quelldatei, die zum Generieren der Punktwolke benötigt wird
string file = "template.stl";

// Erstellen Sie eine Instanz von Scene
Scene scene = new Scene(file);

//Rufen Sie das Punktwolkenobjekt von Aspose.3D ab und generieren Sie eine Punktwolke
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

//Merge-Methode zum Generieren von Punktwolken
private void Merge(PointCloud pc, Geometry g, Matrix4 transform)
{
    var tmp = PointCloud.FromGeometry(g, 10);
    for (int i = 0; i < tmp.ControlPoints.Count; i++)
    {
        var pt = transform * tmp.ControlPoints[i];
        pc.ControlPoints.Add(pt);
    }
}

// Erstellen Sie eine Instanz von newScene
var newScene = new Scene(pc);

//Beim Speichern müssen Sie ein SaveOptions-Objekt des Speicherformats erstellen
string output=System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".ply";
PlySaveOptions ply = new PlySaveOptions();
ply.PointCloud = true;
newScene.Save(output,ply);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Über Aspose.3D for .NET API" %}}

 Aspose.3D ist eine CAD und Gameware API zum Laden, Modifizieren und Konvertieren von 3D Dateien. API ist eigenständig und erfordert keine 3D-Modellierungs- oder Rendering-Software. Man kann API einfach für Discreet3DS, WavefrontOBJ, STL (ASCII, binär), Universal3D, FBX (ASCII, binär), Collada, glTF, PLY, GLB, DirectX und weitere Formate. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

  {{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Kostenlose App zum Generieren von Punktwolken zu STL" sectionDescription="Sehen Sie sich unsere Live-Demos an [Punktwolke 3DS](https://products.aspose.app/3d/point-cloud/stl) mit folgenden Vorteilen." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Sie müssen nichts herunterladen oder einrichten" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Es ist nicht erforderlich, Code zu schreiben oder zu kompilieren" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Laden Sie einfach die Datei STL hoch und klicken Sie auf die Schaltfläche \"Generieren\"." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Laden Sie bei Bedarf die Datei STL über den Link herunter" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="STL" readMoreLink="https://docs.fileformat.com/cad/stl/" >}}
STL, Abkürzung für Stereolithrographie, ist ein austauschbares Dateiformat, das dreidimensionale Oberflächengeometrie darstellt. Das Dateiformat findet seine Verwendung in mehreren Bereichen wie Rapid Prototyping, 3D Drucken und computergestützter Fertigung. Es stellt eine Oberfläche als eine Reihe kleiner Dreiecke dar, die als Facetten bekannt sind, wobei jede Facette durch eine senkrechte Richtung und drei Punkte beschrieben wird, die die Eckpunkte des Dreiecks darstellen.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Andere unterstützte App zum Generieren von Punktwolken in Formate" subTitle="Mit C# kann man auch Punktwolken für viele andere Dateiformate generieren, einschließlich." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/3mf/" name="3MF" description="3D Herstellungsformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/amf/" name="AMF" description="Format der additiven Fertigung" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/ase/" name="ASE" description="2D-Animationsdatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/dae/" name="DAE" description="Austausch digitaler Assets" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/dxf/" name="DXF" description="Zeichnungsaustauschformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/drc/" name="DRC" description="Google Draco" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/fbx/" name="FBX" description="3D-Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/glb/" name="GLB" description="3D Binäre Dateidarstellung" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/gltf/" name="GLTF" description="GL-Übertragungsformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/jt/" name="JT" description="Jupiter-Tessellationsdatei" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/obj/" name="OBJ" description="3D Dateiformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/ply/" name="PLY" description="Polygon-Dateiformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/pdf/" name="PDF" description="3D PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/rvm/" name="RVM" description="AVEVA Anlagendesignmodell" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/3ds/" name="3DS" description="3D Studio-Mesh-Dateiformat" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/u3d/" name="U3D" description="Universal 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/vrml/" name="VRML" description="Modellierungssprache für virtuelle Realität" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/x/" name="x" description="DirectX-Modellbild" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/usd/" name="USD" description="Universelle Szenenbeschreibung" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/point-cloud/usdz/" name="USDZ" description="Universelle Szene Beschreibung Zip-Archiv" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}