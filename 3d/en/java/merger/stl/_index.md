---
title: Merge STL File Formats via Java
weight: 810
url: /java/merger/stl
description: Sample Java merge STL file. Use this example code to merge STL file within any Web or Desktop Java based application.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Merge STL via Java" h2="Merge STL using Java library  without any 3D modeling software." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="STL" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="STL" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://releases.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/3d/" >}}

{{% blocks/products/pf/agp/content h2="How to Merge STL File Using Java" %}}

In order to merge STL file, we’ll use
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API which is a feature-rich, powerful and easy to use Merger API for Java platform. You can download its latest version directly from
 [Aspose Maven Repository](https://repository.aspose.com/3d/) 
 and install it within your Maven-based project by adding the following configurations to the pom.xml.

{{% blocks/products/pf/agp/code-block title="Repository" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>

```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Dependency" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Steps to Merge STL via Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java programmers can easily merge STL in just a few lines of code.

{{% /blocks/products/pf/agp/text %}}

-  Merge multiple STL files by looping
-  After merging, a usdz file is generated, waiting for download processing
-  Load the generated usdz file through the constructor of the Scene class
-  Process usdz files and save them in the format you want

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D for JAVA is supported on all major operating systems. Just make sure that you have the following prerequisites.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows or a compatible OS with Java Runtime Environment for JSP/JSF Application and Desktop Applications.
- Get latest version of Aspose.3D for Java directly from Maven.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="JAVA code to Merge STL" offSpacer="" %}}

```cs

//Multiple source files that need to be merged
String[] files = {"template.stl","template2.stl"};

//Process file merge to generate usdz file
Scene scene = new Scene();
int i = 0;

for(String file: files)
{
    FileStream fs = new FileStream(file, FileStream.OPEN, FileStream.READ);
    FileFormat fmt = FileFormat.detect(fs, files[i]);
    Node subNode = scene.getRootNode().createChildNode(files[i]);
    i++;
    try
    {
        Scene subScene = new Scene();
        LoadOptions opt = fmt.createLoadOptions();
        subScene.open(fs, opt);
        subNode.setEntity(PolygonModifier.mergeMesh(subScene));
        MoveTo(subScene.getRootNode(), subNode);
    }
    catch (Exception e)
    {
    }
}

String reviewFile = "result.usdz";
UsdSaveOptions usdz = new UsdSaveOptions(FileFormat.USDZ);
usdz.setPrimitiveToMesh(false);
usdz.setExportMetaData(true);

scene.save(reviewFile, usdz);

//Process usdz files and save them in the format you want
Scene scene2 = new Scene();
String physicalFile = reviewFile;
FileStream fs2 = new FileStream(physicalFile, FileStream.OPEN, FileStream.READ);
FileFormat fmt2 = FileFormat.detect(fs2, "result");
Scene subScene2 = new Scene();
LoadOptions opt2 = fmt2.createLoadOptions();
subScene2.open(fs2, opt2);
Node newNode = scene2.getRootNode().createChildNode("");
double[] value = { 1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1 };
newNode.getTransform().setTransformMatrix(new Matrix4(value));
MoveTo(subScene2.getRootNode(), newNode);
String output = "merger.fbx";
scene2.save(output, FileFormat.FBX7400ASCII);

//MoveTo class for call processing
public static void MoveTo(Node subScene, Node parent)
{
    while (subScene.getChildNodes().size() > 0)
    {
        Node node = subScene.getChildNodes().get(0);
        subScene.getChildNodes().remove(0);
        parent.addChildNode(node);
    }
}

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox-app sectionTitle="Free App to Merge STL" sectionDescription="[Merger STL](https://products.aspose.app/3d/merger/stl) right now by visiting our Live Demos website.The live demo has the following benefits" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload STL file and hit the \"Merger\" button" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" You will get the download link." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Scene Manipulation Library" %}}

 Aspose.3D is a CAD and Gameware API to load, modify and convert 3D files. API is a standalone and does not require any any 3D modeling or rendering software. One can easily use API for Discreet3DS, WavefrontOBJ, STL (ASCII, Binary), Universal3D, FBX (ASCII, Binary), Collada, glTF, PLY, GLB, DirectX and more formats. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="STL" readMoreLink="https://docs.fileformat.com/cad/stl/" >}}

STL, abbreviation for stereolithrography, is an interchangeable file format that represents 3-dimensional surface geometry. The file format finds its usage in several fields such as rapid prototyping, 3D printing and computer-aided manufacturing. It represents a surface as a series of small triangles, known as facets, where each facet is described by a perpendicular direction and three points representing the vertices of the triangle.

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported App to Merge Formats" subTitle="Using JAVA, One can also merge many other file formats including." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/merger/3ds/" name="3DS" description="3D Studio Mesh File Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/merger/3mf/" name="3MF" description="3D Manufacturing Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/merger/amf/" name="AMF" description="Additive Manufacturing Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/merger/ase/" name="ASE" description="Aseprite Sprite File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/merger/dae/" name="DAE" description="Digital Asset Exchange File Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/merger/dxf/" name="DXF" description="Autodesk Drawing Exchange File Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/merger/drc/" name="DRC" description="Google Draco" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/merger/fbx/" name="FBX" description="Filmbox Interchange File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/merger/glb/" name="GLB" description="Binary GlTF File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/merger/gltf/" name="GLTF" description="GL Transmission Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/merger/jt/" name="JT" description="JT File Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/merger/obj/" name="OBJ" description="OBJ File Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/merger/ply/" name="PLY" description="Polygon File Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/merger/pdf/" name="PDF" description="3D PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/merger/rvm/" name="RVM" description="RVM File Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/merger/stl/" name="STL" description="Stereolithography" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/merger/u3d/" name="U3D" description="Universal 3D File Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/merger/vrml/" name="VRML" description="Virtual Reality Modeling Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/merger/x/" name="X" description="DirectX Model File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/merger/usd/" name="USD" description="Universal Scene Description" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/merger/usdz/" name="USDZ" description="Universal Scene Description Zip Archive" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}