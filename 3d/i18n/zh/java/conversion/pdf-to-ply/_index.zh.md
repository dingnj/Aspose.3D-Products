﻿---
title: 通过 Java 将 PDF 转换为 PLY 
url: /zh/java/conversion/pdf-to-ply/ 
description: 示例 Java 格式到 PLY 文件的转换代码。使用此示例代码可以在任何基于Web或桌面的应用程序中将 PDF 转换为 PLY。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="通过 Java 将 PDF 转换为 PLY" h2="使用 Java 库进行 PDF 到 PLY 转换，无需任何 3D 建模软件。" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="PLY" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PDF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="如何使用 Java 将 PDF 转换为 PLY" %}}

 为了将 PDF 渲染为 PLY，我们将使用
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API 这是一个功能丰富，功能强大且易于使用的转换 API for Java 平台。您可以直接从以下位置下载其最新版本
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
 并通过将以下配置添加到pom.xml中，将其安装在基于Maven的项目中。

{{% blocks/products/pf/agp/code-block title="存储库" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://存储库
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="依赖关系" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="通过 Java 将 PDF 转换为 PLY 的步骤" %}}

{{% blocks/products/pf/agp/text %}}

 Java 程序员只需几行代码就可以轻松地将 PDF 文件转换为 PLY。

{{% /blocks/products/pf/agp/text %}}

1. 通过场景类的构造函数加载 PDF 文件1. 创建PlySaveOptions实例1. 为高级转换设置 PLY 特定属性1. 调用场景。保存方法1. 传递带有 PLY 文件扩展名和PlySaveOptions对象的输出路径
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系统要求" %}}

{{% blocks/products/pf/agp/text %}}

 在运行 Java 转换代码之前，请确保您具有以下先决条件。

{{% /blocks/products/pf/agp/text %}}

- 适用于JSP/JSF应用程序和桌面应用程序的具有 Java 运行时环境的Microsoft Windows或兼容操作系统。- 直接从Maven获取最新版本的 Aspose.3D for Java。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PDF 到 PLY Java 的转换源代码" offSpacer="" %}}

```cs
// 加载场景对象中的 PDF 
Scene document = new Scene("template.pdf");
// 创建PlySaveOptions实例 
AmfSaveOptions options = new PlySaveOptions();
// 将 PDF 保存为 PLY 
document.save("output.ply", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="PDF 到 PLY 转换实时演示" sectionDescription="[将 PDF 转换为 PLY](https://products.aspose.app/3d/conversion/pdf-to-ply) 现在通过访问我们的现场演示网站。现场演示有以下好处" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 无需下载 Aspose API。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 不需要编写任何代码。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" 只需上传您的 PDF 文件，它将立即转换为 PLY。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 你会得到下载链接。" >}}

    {{% blocks/products/pf/agp/content h2="Java 3D 场景操作库" %}}

 Aspose.3D 是一个 CAD 和游戏软件 API，用于加载、修改和转换 3D 文件。API 是独立的，不需要任何 3D 建模或渲染软件。人们可以轻松地将 API 用于 Discreet3DS 、 WavefrontOBJ 、 STL (ASCII，二进制) 、 Universal3D 、 FBX (ASCII，二进制) 、 Collada 、 glTF 、 PLY 、 GLB 、DirectX等多种格式。 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/view/pdf/" >}}

可移植文档格式 (PDF) 是Adobe在20世纪90年代中创建的一种文档。此文件格式的目的是引入一种标准，以独立于应用软件，硬件和操作系统的格式表示文档和其他参考材料。PDF 文件可以在Adobe Acrobat Reader/Writer中打开，也可以在大多数现代浏览器 (如Chrome，Safari，Firefox) 中通过扩展/插件打开。大多数市售软件套件还提供将其文档转换为 PDF 文件格式，而无需任何其他软件组件。因此，PDF 文件格式具有完整的功能，可以包含文本、图像、超链接、表单字段、富媒体、数字签名、附件、元数据、地理空间特征和 3D 对象等信息，这些信息可以成为源文件的一部分。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PLY" readMoreLink="https://docs.fileformat.com/3d/ply/" >}}

PLY，多边形文件格式，表示存储描述为多边形集合的图形对象的 3D 文件格式。此文件格式的目的是建立一种简单易用的文件类型，该类型足够通用，可以用于各种模型。PLY 文件格式作为ASCII以及二进制格式，用于紧凑存储和快速保存和加载。文件格式由提供 3D 文件读取支持的不同应用程序使用。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->


{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}