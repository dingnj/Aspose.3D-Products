﻿---
title: 通过 C# 将 USDZ 转换为 FBX 
description: 使用 .NET API 转换 USDZ 和其他 3D 文件
url: /zh/net/conversion/usdz-to-fbx/
family: 3d
platformtag: net
feature: conversion
informat: USDZ
outformat: FBX
otherformats: GLTF PLY FBX STL JT AMF DXF DAE 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="通过 C# 将 USDZ 转换为 FBX" h2="使用 .NET 框架、 .NET 核心和 Mono 导出 USDZ 和其他 3D 文件" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="使用 C# 将 USDZ 场景导出为 FBX" %}}
1. 使用以下构造函数加载 USDZ 文件 [场景](https://apireference.aspose.com/3d/net/aspose.threed/scene) 类2.打电话 [场景。保存](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) 方法
3.传递输出文件名与fbx扩展作为第一个参数
4.指定 'fbx7700binary '字段值从 [文件格式](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) 类
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D 格式转换 API for .NET" %}}
从命令行以 “'nuget Install Aspose.3d” 的身份安装，或通过Visual Studio的软件包管理器控制台安装，并带有 “” install-Package Aspose.3D ”。

或者，从 ZIP 文件中获取离线MSI安装程序或dll [下载](https://downloads.aspose.com/3d/net)。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="C# 用于 USDZ 到 FBX 转换的代码" gistPath="" %}}
```cs
// 加载场景对象中的 USDZ 
var scene = new Aspose.ThreeD.Scene("template.usdz");
// 将 USDZ 保存为 FBX 
scene.Save("output.fbx", Aspose.ThreeD.FileFormat.FBX7700Binary);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}