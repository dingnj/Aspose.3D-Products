﻿---
title: C# 経由で USDZ を HTML に変換 
description: .NET API を使用して USDZ およびその他の 3D ファイルを変換します
url: /ja/net/conversion/usdz-to-html/
family: 3d
platformtag: net
feature: conversion
informat: USDZ
outformat: HTML
otherformats: DRC ASE RVM DAE 3MF AMF JT FBX 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="C# 経由で USDZ を HTML に変換" h2=".NET Framework、 .NET Core、 Mono を使用して USDZ およびその他の 3D ファイルをエクスポート" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="USDZ シーンを HTML として C# でエクスポート" %}}
1. のコンストラクタを使用して USDZ ファイルをロード [シーン](https://apireference.aspose.com/3d/net/aspose.threed/scene) クラス2.コール [シーン保存](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) メソッド
3.で出力ファイル名を渡します。最初のパラメータとしてのhtml extension
4.から「 HTML5 」フィールド値を指定します。 [ファイル形式](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) クラス
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D フォーマット変換 API for .NET" %}}
コマンドラインから「nuget install Aspose.3d 」として、またはVisual StudioのPackage Manager Consoleから「Install-Package Aspose.3D 」でインストールします。

または、オフラインのMSIインストーラまたはDLLを ZIP ファイルから取得します。 [ダウンロード](https://downloads.aspose.com/3d/net)を使用します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="USDZ から HTML の変換のための C# コード" gistPath="" %}}
```cs
// Sceneのオブジェクトに USDZ をロードする 
var scene = new Aspose.ThreeD.Scene("template.usdz");
// USDZ を HTML として保存 
scene.Save("output.html", Aspose.ThreeD.FileFormat.HTML5);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}