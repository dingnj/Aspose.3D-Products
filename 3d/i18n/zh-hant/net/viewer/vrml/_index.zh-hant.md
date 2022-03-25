﻿---
title: 通過 .NET 查看 VRML 文件格式 
weight: 2540
url: /zh-hant/net/viewer/vrml/ 
description: C# 源代碼,用於在 .NET 框架,.NET 核心,Mono 上加載,呈現和顯示 VRML 文檔。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="VRML 文件查看器 for .NET" h2="渲染 VRML 文件,無需任何 3D 建模和渲染軟件。" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="VRML" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="VRML" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="如何使用 C# 查看 VRML 文件" %}}

 為了查看 VRML 文件,我們將使用
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API 這是一個功能豐富,功能強大且易於使用的 API 平台,可用於任何查看器。 打開
 [努get](https://www.nuget.org/packages/aspose.3d) 
 包管理器,搜索
 **Aspose.3D** 
 並安裝。 您也可以使用包管理器控制台中的以下命令。

{{% blocks/products/pf/agp/code-block title="包管理器控制台命令" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="通過 C# 查看 VRML 的步驟" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D 使開發人員只需幾行代碼即可輕鬆查看 VRML 文件。

{{% /blocks/products/pf/agp/text %}}

1. 通過場景類的構造函數加載 VRML 文件1. 創建Html5SaveOptions實例1. 設置高級格式的屬性1. 使用Html5SaveOptions的對象調用Scene.Save方法1. 在默認瀏覽器中檢查結果 HTML 文件
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="系統要求" %}}

{{% blocks/products/pf/agp/text %}}

 所有主要操作系統都支持 Aspose.3D for .NET。 只需確保您具有以下先決條件即可。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows或具有 .NET 框架,.NET 核心,Mono 的兼容操作系統- 像微軟Visual Studio這樣的開發環境- 項目中引用的 Aspose.3D for .NET
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="查看 VRML 的 C# 代碼" offSpacer="" %}}

```cs

string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// 通過場景實例加載 VRML 場景
var scene = new ThreeD.Scene("template.vrml");
// 創建Html5SaveOptions的對象並設置用於格式化的屬性
var options = new ThreeD.Formats.Html5SaveOptions()
{
    // 關閉電網
    ShowGrid = false,
    // 關閉用戶界面
    ShowUI = false
};

// 將 3D 場景保存為 HTML5
scene.Save(output, options);
// 在默認瀏覽器中加載結果 HTML
System.Diagnostics.Process.Start(output);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="關於 Aspose.3D for .NET API" %}}

 Aspose.3D 是一個 CAD 和遊戲軟件 API,用於加載、修改和轉換 3D 文件。 API 是獨立的,不需要任何 3D 建模或渲染軟件。 人們可以輕鬆地將 API 用於 Discreet3DS 、 WavefrontOBJ 、 STL (ASCII,二進製) 、 Universal3D 、 FBX (ASCII,二進製) 、 Collada 、 glTF 、 PLY 、 GLB 、DirectX等多種格式。 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="免費應用程序查看 VRML" sectionDescription="查看我們的實時演示 [視圖 VRML](https://products.aspose.app/3d/viewer/vrml) 有以下好處。" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 不需要下載或設置任何東西" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 無需編寫或編譯代碼" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" 只需上傳 VRML 文件並點擊 「查看」 按鈕" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" 如果需要,從鏈接下載 VRML 文件" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="VRML" readMoreLink="https://docs.fileformat.com/3d/vrml/" >}}
虛擬現實建模語言 (VRML) 是一種文件格式,用於通過全球資訊網 (www) 表示交互式 3D 世界對象。它在創建複雜場景的三維表示 (例如插圖,定義和虛擬現實演示) 中找到了它的用法。該格式已被X3D取代。許多 3D 建模應用程序可以以 VRML 格式保存對象和場景。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="其他支持的查看器格式" subTitle="使用 C#,還可以查看許多其他文件格式,包括。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/3ds/" name="3DS" description="3D 工作室DOS網格" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/3mf/" name="3MF" description="3D 製造格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/amf/" name="AMF" description="增材製造格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/ase/" name="ASE" description="2D動畫文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/dae/" name="DAE" description="數字資產交換" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/dxf/" name="DXF" description="圖紙互換格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/fbx/" name="FBX" description="3D 格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/glb/" name="GLB" description="3D 文件二進製表示" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/gltf/" name="GLTF" description="GL傳輸格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/jt/" name="JT" description="木星鑲嵌文件" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/obj/" name="OBJ" description="3D 文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/ply/" name="PLY" description="多邊形文件格式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/rvm/" name="RVM" description="AVEVA工廠設計模型" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/stl/" name="STL" description="可互換的 3D 曲面幾何形狀" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/u3d/" name="U3D" description="Universal 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/x/" name="X" description="DirectX模型圖像" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/zip/" name="ZIP" description="ZIP 存檔格式" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}