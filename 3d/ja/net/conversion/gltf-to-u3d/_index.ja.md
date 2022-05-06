﻿---
title: C#を介してGLTFをU3Dに変換します 
url: /ja/net/conversion/gltf-to-u3d/ 
description: GLTFからU3DC#への変換のサンプルコード。 VB .NET、Asp .NET、または任意の.NETベースのアプリケーション内でのバッチGLTFファイルからU3Dへの変換にはAPIサンプルコードを使用します。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C#を介してGLTFをU3Dに変換します" h2="3Dモデリングおよびレンダリングソフトウェアを使用せずに、GLTFをU3Dとしてレンダリングします。" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="U3D" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="GLTF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C#を使用してGLTFをU3Dに変換する方法" %}}

 GLTFをU3Dに変換するには、
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 APIは、機能が豊富で、強力で、使いやすいドキュメント操作と変換APIforC#プラットフォームです。開ける
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 パッケージマネージャー、検索
 Aspose.3D 
 とインストールします。パッケージマネージャーコンソールから次のコマンドを使用することもできます。

{{% blocks/products/pf/agp/code-block title="パッケージマネージャーコンソールコマンド" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C#を介してGLTFをU3Dに変換する手順" %}}

{{% blocks/products/pf/agp/text %}}

 .NETプログラマーは、わずか数行のコードでGLTFファイルを簡単にロードしてU3Dに変換できます。

{{% /blocks/products/pf/agp/text %}}

1. Sceneクラスのコンストラクターを介してGLTFファイルをロードします1. AmfSaveOptionsのインスタンスを作成します1. 高度な変換のためにU3D固有のプロパティを設定します1. Scene.Saveメソッドを呼び出します1. U3Dファイル拡張子とU3dSaveOptionsのオブジェクトを使用して出力パスを渡します1. 指定されたパスで結果のU3Dファイルを確認します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

 .NET変換コードを実行する前に、次の前提条件があることを確認してください。

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windowsまたは.NETフレームワーク、.NETコア、Monoと互換性のあるOS。- MicrosoftVisualStudioのような開発環境。- Aspose.3Dfor .NETプロジェクトで参照されているDLL。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="このサンプルコードは、GLTFからU3DC#への変換を示しています" offSpacer="" %}}

```cs
// シーンのオブジェクトにGLTFをロードします 
var document = new Aspose.ThreeD.Scene("template.gltf");
// U3dSaveOptionsのインスタンスを作成します 
var options = new Aspose.ThreeD.Formats.U3dSaveOptions();
// GLTFをU3Dとして保存 
document.Save("output.u3d", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="GLTFをU3Dに変換する無料アプリ" sectionDescription="ライブデモをチェックしてください [GLTFからU3Dへの変換](https://products.aspose.app/3d/conversion/gltf-to-u3d) 以下の利点があります。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 何かをダウンロードしたりセットアップしたりする必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" コードを書く必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" GLTFファイルをアップロードして[変換]ボタンを押すだけです。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 結果のU3Dファイルのダウンロードリンクがすぐに表示されます。" >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 モデリングおよびレンダリングソフトウェアなしで3Dファイルを操作するための3Dファイル処理ライブラリ。 3D APIは、Discreet3DS、WavefrontOBJ、FBX（ASCII、バイナリ）、STL（ASCII、バイナリ）、Universal3D、Collada、glTF、GLB、 PLY、DirectX、GoogleDracoファイル形式など。開発者は、3Dドキュメント形式の実体を簡単に作成、読み取り、変換、変更、および制御できます。



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLTF" readMoreLink="https://docs.fileformat.com/3d/gltf/" >}}
glTF（GL Transmission Format）は、3Dモデル情報をJSON形式で保存する3Dファイル形式です。 JSONを使用すると、3Dアセットのサイズと、それらのアセットを解凍して使用するために必要なランタイム処理の両方が最小限に抑えられます。アプリケーションによる3Dシーンとモデルの効率的な送信とロードに採用されました。 glTFは、Khronos Group 3D Formats Working Groupによって開発され、その作成者によって3DのJPEGとしても説明されています。この形式は、3Dコンテンツツールとサービスの拡張可能な共通の公開形式を定義し、オーサリングワークフローを合理化し、業界全体でコンテンツの相互運用可能な使用を可能にします。 glTFファイル形式の作成の背後にある意図は、オーサリングワークフローを合理化し、業界全体でコンテンツの相互運用可能な使用を可能にする3Dコンテンツツールとサービスの拡張可能な共通の公開形式を定義することでした。 WebGLやその他のAPIを使用するアプリケーションによるランタイム処理を最小限に抑えます。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="u3d" readMoreLink="https://docs.fileformat.com/3d/u3d/" >}}
U3D（Universal 3D）は、3Dコンピュータグラフィックスの圧縮ファイル形式とデータ構造です。三角形メッシュ、照明、シェーディング、モーションデータ、色と構造の線と点などの3Dモデル情報が含まれています。このフォーマットは、2005年8月にECMA-363標準として承認されました。3D PDFドキュメントはU3Dオブジェクトの埋め込みをサポートし、Adobe Reader（バージョン7以降）で表示できます。 U3D形式は、3次元データの保存と交換のための普遍的な標準を確立することを目的として開発されました。ただし、この形式は、交換形式として使用されるのではなく、3DPDFのエンコードで主に使用されます。 Acrobat 3Dは、サポートされている3DファイルタイプをPDFに変換するときにU3DまたはPRCに変換します。

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}