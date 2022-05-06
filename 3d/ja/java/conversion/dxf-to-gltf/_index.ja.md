﻿---
title: Javaを介してDXFをGLTFに変換します 
weight: 2080
url: /ja/java/conversion/dxf-to-gltf/ 
description: DXF形式からGLTFファイルへのJava変換コードのサンプル。このサンプルコードを使用して、WebまたはデスクトップのJavaベースのアプリケーション内でDXFをGLTFに変換します。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Javaを介してDXFをGLTFに変換します" h2="3Dモデリングソフトウェアを使用せずにJavaライブラリを使用してDXFからGLTFに変換します。" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="GLTF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DXF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="Javaを使用してDXFをGLTFに変換する方法" %}}

 DXFをGLTFにレンダリングするために、
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 APIは、機能が豊富で、強力で、使いやすい変換APIfor Javaプラットフォームです。最新バージョンはから直接ダウンロードできます
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
 次の構成をpom.xmlに追加して、Mavenベースのプロジェクトにインストールします。

{{% blocks/products/pf/agp/code-block title="リポジトリ" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/ </ url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="依存" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Javaを介してDXFをGLTFに変換する手順" %}}

{{% blocks/products/pf/agp/text %}}

 Javaプログラマーは、わずか数行のコードでDXFファイルをGLTFに簡単に変換できます。

{{% /blocks/products/pf/agp/text %}}

1. Sceneクラスのコンストラクターを介してDXFファイルをロードします1. GltfSaveOptionsのインスタンスを作成します1. 高度な変換のためにGLTF固有のプロパティを設定します1. Scene.saveメソッドを呼び出す1. GLTFファイル拡張子とGltfSaveOptionsのオブジェクトを使用して出力パスを渡します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

 Java変換コードを実行する前に、次の前提条件があることを確認してください。

{{% /blocks/products/pf/agp/text %}}

- MicrosoftWindowsまたはJSP/JSFアプリケーションおよびデスクトップアプリケーション用のJavaランタイム環境と互換性のあるOS。- Mavenから直接Aspose.3Dfor Javaの最新バージョンを入手します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="DXFからGLTFJavaへの変換ソースコード" offSpacer="" %}}

```cs
// シーンのオブジェクトにDXFをロードします 
Scene document = new Scene("template.dxf");
// GltfSaveOptionsのインスタンスを作成します 
GltfSaveOptions options = new GltfSaveOptions();
// DXFをGLTFとして保存 
document.save("output.gltf", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="DXFからGLTFへの変換ライブデモ" sectionDescription="[DXFをGLTFに変換](https://products.aspose.app/3d/conversion/dxf-to-gltf) 今すぐライブデモのウェブサイトにアクセスしてください。ライブデモには次の利点があります。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" AsposeAPIをダウンロードする必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" コードを書く必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" DXFファイルをアップロードするだけで、すぐにGLTFに変換されます。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" ダウンロードリンクが表示されます。" >}}

    {{% blocks/products/pf/agp/content h2="Java3Dシーン操作ライブラリ" %}}

 Aspose.3Dは、3Dファイルをロード、変更、変換するためのCADおよびゲームウェアAPIです。 APIはスタンドアロンであり、3Dモデリングまたはレンダリングソフトウェアを必要としません。 Discreet3DS、WavefrontOBJ、STL（ASCII、バイナリ）、Universal3D、FBX（ASCII、バイナリ）、Collada、glTF、PLY、 GLB、DirectXおよびその他の形式。 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DXF" readMoreLink="https://docs.fileformat.com/cad/dxf/" >}}

DXF、Drawing Interchange Format、またはDrawing Exchange Formatは、AutoCAD図面ファイルのタグ付きデータ表現です。ファイル内の各要素には、グループコードと呼ばれるプレフィックス整数があります。このグループコードは、実際には後続の要素を表し、特定のオブジェクトタイプのデータ要素の意味を示します。 DXFを使用すると、ユーザーが指定したほとんどすべての情報を図面ファイルで表すことができます。 DXFファイル形式は、AutoCADと他のアプリケーション間のデータ相互運用性のためにCADデータファイル形式としてオートデスクによって開発されました。したがって、データは、DXFファイル形式の相互運用性仕様に従って、他の形式からDXFにAutoCADにインポートできます。


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLTF" readMoreLink="https://docs.fileformat.com/3d/gltf/" >}}

glTF（GL Transmission Format）は、3Dモデル情報をJSON形式で保存する3Dファイル形式です。 JSONを使用すると、3Dアセットのサイズと、それらのアセットを解凍して使用するために必要なランタイム処理の両方が最小限に抑えられます。アプリケーションによる3Dシーンとモデルの効率的な送信とロードに採用されました。 glTFは、Khronos Group 3D Formats Working Groupによって開発され、その作成者によって3DのJPEGとしても説明されています。この形式は、3Dコンテンツツールとサービスの拡張可能な共通の公開形式を定義し、オーサリングワークフローを合理化し、業界全体でコンテンツの相互運用可能な使用を可能にします。 glTFファイル形式の作成の背後にある意図は、オーサリングワークフローを合理化し、業界全体でコンテンツの相互運用可能な使用を可能にする3Dコンテンツツールとサービスの拡張可能な共通の公開形式を定義することでした。 WebGLやその他のAPIを使用するアプリケーションによるランタイム処理を最小限に抑えます。


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="DXFを、以下にリストされているものを含む他の多くのファイル形式に変換することもできます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-3ds/" name="DXFから3DS" description="3DスタジオDOSメッシュ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-amf/" name="DXFからAMF" description="アディティブマニュファクチャリングフォーマット" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-ase/" name="DXFからASE" description="2Dアニメーションファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-dae/" name="DXFからDAE" description="デジタル資産交換" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-fbx/" name="DXFからFBX" description="3D形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-html/" name="DXFからHTML" description="ハイパーテキストマークアップ言語" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-obj/" name="DXFからOBJ" description="3Dファイル形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-ply/" name="DXFからPLY" description="ポリゴンファイル形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-rvm/" name="DXFからRVM" description="AVEVAプラント設計モデル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-stl/" name="DXFからSTL" description="交換可能な3D表面形状" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-u3d/" name="DXFからU3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}