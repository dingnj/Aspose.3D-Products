﻿---
title: 通過 Java 將 DXF 轉換為 3DS 
weight: 510
url: /zh-hant/java/conversion/dxf-to-3ds/ 
description: DXF 格式到 3DS 文件的示例 Java 轉換代碼。使用此示例代碼在任何基於 Web 或桌面 Java 的應用程序中將 DXF 轉換為 3DS。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="通過 Java 將 DXF 轉換為 3DS" h2="在沒有任何 3D 建模軟件的情況下，使用 Java 庫進行 DXF 到 3DS 的轉換。" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="3DS" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DXF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="如何使用 Java 將 DXF 轉換為 3DS" %}}

 為了將 DXF 呈現為 3DS，我們將使用
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API 是一個功能豐富、功能強大且易於使用的轉換API for Java 平台。您可以直接從
 [馬文](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
 並通過將以下配置添加到 pom.xml 將其安裝在基於 Maven 的項目中。

{{% blocks/products/pf/agp/code-block title="存儲庫" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="依賴" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="通過 Java 將 DXF 轉換為 3DS 的步驟" %}}

{{% blocks/products/pf/agp/text %}}

 Java 程序員只需幾行代碼即可輕鬆地將 DXF 文件轉換為 3DS。

{{% /blocks/products/pf/agp/text %}}

1. 通過 Scene 類的構造函數加載 DXF 文件1. 創建 3dsSaveOptions 的實例1. 為高級轉換設置 3DS 個特定屬性1. 調用 Scene.save 方法1. 傳遞帶有 3DS 文件擴展名和 3dsSaveOptions 對象的輸出路徑
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系統要求" %}}

{{% blocks/products/pf/agp/text %}}

 在運行 Java 轉換代碼之前，請確保您具有以下先決條件。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 或具有 Java JSP/JSF 應用程序和桌面應用程序運行時環境的兼容操作系統。- 直接從 Maven 獲取最新版本的 Aspose.3D for Java。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="DXF 到 3DS Java 轉換源代碼" offSpacer="" %}}

```cs
// 在 Scene 對像中加載 DXF 
Scene document = new Scene("template.dxf");
// 創建 3dsSaveOptions 的實例 
Discreet3dsSaveOptions options = new Discreet3dsSaveOptions();
// 將 DXF 保存為 3DS 
document.save("output.3ds", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="DXF 到 3DS 轉換現場演示" sectionDescription="[將 DXF 轉換為 3DS](https://products.aspose.app/3d/conversion/dxf-to-3ds) 立即訪問我們的現場演示網站。現場演示具有以下好處" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 無需下載 Aspose API。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 無需編寫任何代碼。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" 只需上傳您的 DXF 文件，它就會立即轉換為 3DS。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 您將獲得下載鏈接。" >}}

    {{% blocks/products/pf/agp/content h2="Java 3D 場景操作庫" %}}

 Aspose.3D 是用於加載、修改和轉換 3D 文件的 CAD 和遊戲軟件 API。 API 是獨立的，不需要任何 3D 建模或渲染軟件。可以輕鬆地將 API 用於 Discreet3DS、WavefrontOBJ、STL（ASCII，二進制）、Universal3D、FBX（ASCII，二進制）、Collada、glTF、PLY、 GLB、DirectX 和更多格式。 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DXF" readMoreLink="https://docs.fileformat.com/cad/dxf/" >}}

DXF，繪圖交換格式，或繪圖交換格式，是 AutoCAD 繪圖文件的標記數據表示。文件中的每個元素都有一個前綴整數，稱為組代碼。該組代碼實際上表示後面的元素，並指示給定對像類型的數據元素的含義。 DXF 可以在圖形文件中表示幾乎所有用戶指定的信息。 DXF 文件格式由 Autodesk 開發為 CAD 數據文件格式，用於 AutoCAD 和其他應用程序之間的數據互操作性。因此，可以根據 DXF 文件格式互操作性規範將數據從其他格式導入到 DXF 到 AutoCAD。


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="3DS" readMoreLink="https://docs.fileformat.com/3d/3ds/" >}}

帶有 3DS 擴展名的文件代表 Autodesk 3D Studio 使用的 3D Studio (DOS) 網格文件格式。 Autodesk 3D Studio 自 1990 年代以來一直處於 3D 文件格式市場，現在已發展為 3D Studio MAX，用於處理 3D 建模、動畫和渲染。 3DS 文件包含用於 3D 表示場景和圖像的數據，並且是用於 3D 數據導入和導出的流行文件格式之一。它考慮相機位置、網格數據、照明信息、視口配置、平滑組數據、位圖參考和屬性等信息，以創建用於渲染場景的頂點和多邊形。


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的轉換" subTitle="您還可以將 DXF 轉換為許多其他文件格式，包括下面列出的幾種。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-amf/" name="DXF 至 AMF" description="增材製造形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-ase/" name="DXF 至 ASE" description="二維動畫文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-dae/" name="DXF 至 DAE" description="數字資產交易所" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-fbx/" name="DXF 至 FBX" description="3D 格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-gltf/" name="DXF 至 GLTF" description="GL 傳輸格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-html/" name="DXF 至 HTML" description="超文本標記語言" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-obj/" name="DXF 至 OBJ" description="3D 文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-ply/" name="DXF 至 PLY" description="多邊形文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-rvm/" name="DXF 至 RVM" description="AVEVA 工廠設計模型" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-stl/" name="DXF 至 STL" description="可互換的 3D 表面幾何形狀" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-u3d/" name="DXF 至 U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}