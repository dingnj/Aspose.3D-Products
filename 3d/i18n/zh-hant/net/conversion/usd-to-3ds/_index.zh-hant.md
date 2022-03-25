﻿---
title: 通過 C# 將 USD 轉換為 3DS 
description: 使用 .NET API 轉換 USD 和其他 3D 文件
url: /zh-hant/net/conversion/usd-to-3ds/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: 3DS
otherformats: OBJ STL HTML FBX RVM JT DAE DXF 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="通過 C# 將 USD 轉換為 3DS" h2="使用 .NET 框架、 .NET 核心和 Mono 導出 USD 和其他 3D 文件" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="使用 C# 將 USD 場景導出為 3DS" %}}
1. 使用以下構造函數加載 USD 文件 [場景](https://apireference.aspose.com/3d/net/aspose.threed/scene) 類2.打電話 [場景。 保存](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) 方法
3.以.3ds擴展名作為第一個參數傳遞輸出文件名
4.從中指定 "Discreet3DS」 字段值 [文件格式](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) 類
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D 格式轉換 API for .NET" %}}
從命令行以 「'nuget Install Aspose.3d」 的身份安裝,或通過Visual Studio的軟件包管理器控制台安裝,並帶有 「」 install-Package Aspose.3D ”。

或者,從 ZIP 文件中獲取離線MSI安裝程序或dll [下載](https://downloads.aspose.com/3d/net)。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# 用於 USD 到 3DS 轉換的代碼" gistPath="" %}}
```cs
// 加載場景對象中的 USD 
var scene = new Aspose.ThreeD.Scene("template.usd");
// 將 USD 保存為 3DS 
scene.Save("output.3ds", Aspose.ThreeD.FileFormat.Discreet3DS);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}