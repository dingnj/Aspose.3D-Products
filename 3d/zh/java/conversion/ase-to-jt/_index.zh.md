﻿---
title: 通过 Java 将 ASE 转换为 JT
weight: 530
url: /zh/java/conversion/ase-to-jt/ 
description: ASE 格式到 JT 文件的示例 Java 转换代码。使用此示例代码在任何基于 Web 或桌面 Java 的应用程序中将 ASE 转换为 JT。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="通过 Java 将 ASE 转换为 JT" h2="在没有任何 3D 建模软件的情况下，使用 Java 库进行 ASE 到 JT 的转换。" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="JT" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ASE" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="如何使用 Java 将 ASE 转换为 JT" %}}

 为了将 ASE 呈现为 JT，我们将使用
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API 是一个功能丰富、功能强大且易于使用的转换API for Java 平台。您可以直接从
 [马文](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
 并通过将以下配置添加到 pom.xml 将其安装在基于 Maven 的项目中。

{{% blocks/products/pf/agp/code-block title="存储库" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="依赖" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="通过 Java 将 ASE 转换为 JT 的步骤" %}}

{{% blocks/products/pf/agp/text %}}

 Java 程序员只需几行代码即可轻松地将 ASE 文件转换为 JT。

{{% /blocks/products/pf/agp/text %}}

1. 通过 Scene 类的构造函数加载 ASE 文件1. 使用 JT 的格式调用 Scene.save 方法。1. 检查指定路径的结果 JT 文件
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}

{{% blocks/products/pf/agp/text %}}

 在运行 Java 转换代码之前，请确保您具有以下先决条件。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 或具有 Java JSP/JSF 应用程序和桌面应用程序运行时环境的兼容操作系统。- 直接从 Maven 获取最新版本的 Aspose.3D for Java。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="ASE 到 JT Java 转换源代码" offSpacer="" %}}

```cs
// 加载源 ASE 文件
Scene scene = new Scene("sourceFile.ase");
// 将 3D 场景转换为 Siemens JT 格式的文件
scene.save("output.jt", FileFormat.SIEMENSJT9)

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="ASE 到 JT 转换现场演示" sectionDescription="[将 ASE 转换为 JT](https://products.aspose.app/3d/conversion/ase-to-jt) 立即访问我们的现场演示网站。现场演示具有以下好处" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 无需下载 Aspose API。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 无需编写任何代码。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" 只需上传您的 ASE 文件，它就会立即转换为 JT。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 您将获得下载链接。" >}}

    {{% blocks/products/pf/agp/content h2="Java 3D 场景操作库" %}}

 Aspose.3D 是用于加载、修改和转换 3D 文件的 CAD 和游戏软件 API。 API 是独立的，不需要任何 3D 建模或渲染软件。可以轻松地将 API 用于 USD、Discreet3DS、WavefrontOBJ、STL（ASCII，二进制）、Universal3D、FBX（ASCII，二进制）、Collada、glTF、 PLY、GLB、DirectX 等格式。 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ASE" readMoreLink="https://docs.fileformat.com/3d/ase/" >}}

具有 .ase 扩展名的文件是 Autodesk ASCII 场景导出文件格式，它是场景的 ASCII 表示，在使用 Autodesk 导出场景数据时包含 2D 或 3D 信息。 Autodesk 提供了在导出场景数据时包含场景组件的选项。您可以包括网格定义以及顶点和面信息、材质描述、对象的变换动画数据、每 n 帧的完整网格定义、相机和灯光的动画数据以及 IK 关节设置。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JT" readMoreLink="https://docs.fileformat.com/3d/jt/" >}}

JT（Jupiter Tessellation）是一种高效、专注于行业且灵活的 ISO 标准化 3D 数据格式，由 Siemens PLM Software 开发。航空航天、汽车工业和重型设备的机械 CAD 领域使用 JT 作为其最领先的 3D 可视化格式。


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的转换" subTitle="您还可以将 ASE 转换为许多其他文件格式，包括下面列出的几种。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-gltf/" name="ASE 至 GLTF" description="GL传输格式文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-glb/" name="ASE 至 GLB" description="二进制 GL 传输格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-pdf/" name="ASE 至 PDF" description="便携式文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-fbx/" name="ASE 至 FBX" description="Autodesk FBX 交换文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-stl/" name="ASE 至 STL" description="立体光刻文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-obj/" name="ASE 至 OBJ" description="Wavefront 3D 对象文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-3ds/" name="ASE 至 3DS" description="3D 工作室场景" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-dae/" name="ASE 至 DAE" description="数字资产交换文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-u3d/" name="ASE 至 U3D" description="Universal 3D 文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-ply/" name="ASE 至 PLY" description="多边形文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-drc/" name="ASE 至 DRC" description="Google Draco 文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-rvm/" name="ASE 至 RVM" description="爱华RVM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-jt/" name="ASE 至 JT" description="JT 打开 CAD 文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-amf/" name="ASE 至 AMF" description="增材制造文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-html/" name="ASE 至 HTML" description="超文本标记语言" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-usd/" name="ASE 至 USD" description="通用场景描述格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-usdz/" name="ASE 至 USDZ" description="通用场景描述压缩格式" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}