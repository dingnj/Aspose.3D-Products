﻿---
title: Java 経由で PLY を ASE に変換 
weight: 890
url: /ja/java/conversion/ply-to-ase/ 
description: PLY 形式の Java ファイルへの変換コードのサンプル。このコード例を使用して、Webまたはデスクトップ Java ベースのアプリケーション内で PLY を ASE に変換します。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Java 経由で PLY を ASE に変換" h2="3D モデリングソフトウェアなしで Java ライブラリを使用した PLY から ASE への変換。" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="ASE" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PLY" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="Java を使用して PLY を ASE に変換する方法" %}}

 PLY を ASE にレンダリングするには、を使用します。
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API は、機能が豊富でパワフルで使いやすいコンバージョン API for Java プラットフォームです。から直接最新バージョンをダウンロードできます
 [メイヴン](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
 以下の設定をpom.xmlに追加して、Mavenベースのプロジェクト内にインストールします。

{{% blocks/products/pf/agp/code-block title="リポジトリ" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://Repository.aspose.com/repo/ </url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="依存関係" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Java 経由で PLY を ASE に変換する手順" %}}

{{% blocks/products/pf/agp/text %}}

 Java 人のプログラマーは、わずか数行のコードで PLY ファイルを ASE に簡単に変換できます。

{{% /blocks/products/pf/agp/text %}}

1. Sceneクラスのコンストラクターを介した PLY ファイルの読み込み1. AseSaveOptionsのインスタンスの作成1. 高度な変換のために ASE 固有のプロパティを設定する1. Scene.saveメソッドを呼び出す1. ASE ファイル拡張子とAseSaveOptionsのオブジェクトで出力パスを渡します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要件" %}}

{{% blocks/products/pf/agp/text %}}

 Java 変換コードを実行する前に、次の前提条件があることを確認してください。

{{% /blocks/products/pf/agp/text %}}

- Microsoft WindowsまたはJSP/JSFアプリケーションおよびデスクトップアプリケーション用の Java ランタイム環境を備えた互換性のあるOS。- 最新バージョンの Aspose.3D for Java をMavenから直接入手してください。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PLY ~ ASE Java 変換ソースコード" offSpacer="" %}}

```cs
// Sceneのオブジェクトに PLY をロードする 
Scene document = new Scene("template.ply");
// AseSaveOptionsのインスタンスを作成する 
AseSaveOptions options = new AseSaveOptions();
// PLY を ASE として保存 
document.save("output.ase", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="PLY から ASE の変換ライブデモ" sectionDescription="[PLY を ASE に変換](https://products.aspose.app/3d/conversion/ply-to-ase) ライブデモのウェブサイトをご覧ください。ライブデモには次の利点があります" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API をダウンロードする必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" コードを書く必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" PLY ファイルをアップロードするだけで、即座に ASE に変換されます。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" ダウンロードリンクが表示されます。" >}}

    {{% blocks/products/pf/agp/content h2="Java 3D シーン操作ライブラリ" %}}

 Aspose.3D は CAD で、 3D ファイルをロード、変更、変換するためのゲームウェア API です。 API はスタンドアロンであり、 3D モデリングまたはレンダリングソフトウェアを必要としません。 Discreet3DS 、 WavefrontOBJ 、 STL (ASCII、Binary) 、 Universal3D 、 FBX (ASCII、Binary) 、 Collada 、 glTF 、 PLY 、 GLB 、DirectXなどのフォーマットに API を簡単に使用できます。 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PLY" readMoreLink="https://docs.fileformat.com/3d/ply/" >}}

PLY 、Polygon File Formatは、ポリゴンのコレクションとして記述されたグラフィカルオブジェクトを格納する 3D ファイル形式を表します。このファイル形式の目的は、幅広いモデルに役立つのに十分な一般的なシンプルで簡単なファイルタイプを確立することでした。 PLY ファイル形式はASCIIとバイナリ形式で提供され、コンパクトなストレージと迅速な保存と読み込みが可能です。ファイル形式は、 3D 個のファイル読み取りをサポートするさまざまなアプリケーションで使用されます。


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ASE" readMoreLink="https://docs.fileformat.com/3d/ase/" >}}

ASE ファイルは、レイヤー、フレーム、パレット、タグ、および設定を含む2Dアニメーションまたはグラフィックスです。


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされる変換" subTitle="PLY を以下のいくつかを含む他の多くのファイル形式に変換することもできます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-3ds/" name="PLY から 3DS" description="3D Studio DOSメッシュ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-amf/" name="PLY から AMF" description="添加剤製造フォーマット" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-dae/" name="PLY から DAE" description="デジタル資産交換" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-fbx/" name="PLY から FBX" description="3D フォーマット" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-gltf/" name="PLY から GLTF" description="GL伝送形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-html/" name="PLY から HTML" description="ハイパーテキストマークアップ言語" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-obj/" name="PLY から OBJ" description="3D ファイル形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-rvm/" name="PLY から RVM" description="AVEVA植物デザインモデル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-stl/" name="PLY から STL" description="交換可能な 3D 面ジオメトリ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ply-to-u3d/" name="PLY から U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}