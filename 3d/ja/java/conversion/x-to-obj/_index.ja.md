﻿---
title: Javaを介してXをOBJに変換します 
weight: 60
url: /ja/java/conversion/x-to-obj/ 
description: X形式からOBJファイルへのサンプルJava変換コード。このサンプルコードを使用して、WebまたはデスクトップJavaベースのアプリケーション内でXをOBJに変換します。
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Javaを介してXをOBJに変換します" h2="3Dモデリングソフトウェアを使用せずにJavaライブラリを使用したXからOBJへの変換。" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="OBJ" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="X" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="Javaを使用してXをOBJに変換する方法" %}}

 XをOBJにレンダリングするために、
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

{{% blocks/products/pf/agp/feature-section-col title="Javaを介してXをOBJに変換する手順" %}}

{{% blocks/products/pf/agp/text %}}

 Javaプログラマーは、わずか数行のコードでXファイルをOBJに簡単に変換できます。

{{% /blocks/products/pf/agp/text %}}

1. Sceneクラスのコンストラクターを介してXファイルをロードします1. ObjSaveOptionsのインスタンスを作成します1. 高度な変換のためにOBJ固有のプロパティを設定します1. Scene.saveメソッドを呼び出す1. OBJファイル拡張子とObjSaveOptionsのオブジェクトを使用して出力パスを渡します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="システム要求" %}}

{{% blocks/products/pf/agp/text %}}

 Java変換コードを実行する前に、次の前提条件があることを確認してください。

{{% /blocks/products/pf/agp/text %}}

- MicrosoftWindowsまたはJSP/JSFアプリケーションおよびデスクトップアプリケーション用のJavaランタイム環境と互換性のあるOS。- Mavenから直接Aspose.3Dfor Javaの最新バージョンを入手します。
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="XからOBJJavaへの変換ソースコード" offSpacer="" %}}

```cs
// シーンのオブジェクトにXをロードします 
Scene document = new Scene("template.x");
// ObjSaveOptionsのインスタンスを作成します 
ObjSaveOptions options = new ObjSaveOptions();
// XをOBJとして保存 
document.save("output.obj", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="XからOBJへの変換ライブデモ" sectionDescription="[XをOBJに変換する](https://products.aspose.app/3d/conversion/x-to-obj) 今すぐライブデモのウェブサイトにアクセスしてください。ライブデモには次の利点があります。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" AsposeAPIをダウンロードする必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" コードを書く必要はありません。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Xファイルをアップロードするだけで、すぐにOBJに変換されます。" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" ダウンロードリンクが表示されます。" >}}

    {{% blocks/products/pf/agp/content h2="Java3Dシーン操作ライブラリ" %}}

 Aspose.3Dは、3Dファイルをロード、変更、変換するためのCADおよびゲームウェアAPIです。 APIはスタンドアロンであり、3Dモデリングまたはレンダリングソフトウェアを必要としません。 Discreet3DS、WavefrontOBJ、STL（ASCII、バイナリ）、Universal3D、FBX（ASCII、バイナリ）、Collada、glTF、PLY、 GLB、DirectXおよびその他の形式。 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="X" readMoreLink="https://docs.fileformat.com/3d/x/" >}}

Xは、ゲームでの3Dグラフィックレンダリング用のDirectXテクノロジで使用されるDirectXモデルの画像ファイルです。ファイル形式は、メッシュ、テクスチャ、アニメーション、およびオブジェクトの3Dオブジェクト構造を指定します。


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="OBJ" readMoreLink="https://docs.fileformat.com/3d/obj/" >}}

OBJファイルは、幾何学的オブジェクトを定義および保存するためにWavefrontのAdvancedVisualizerアプリケーションによって使用されます。幾何学的データの前後の送信は、OBJファイルを介して可能になります。ポイント、ライン、テクスチャ頂点、面、フリーフォームジオメトリ（曲線とサーフェス）などのポリゴンジオメトリは、OBJ形式でサポートされています。この形式は、シーンの光と位置に関連するアニメーションや情報をサポートしていません。 OBJファイルは通常、CAD（コンピューター支援設計）によって生成された3Dモデリングプロセスの最終製品です。頂点を格納するデフォルトの順序は、面法線の明示的な宣言を避けて反時計回りです。 OBJファイルはコメント行でスケール情報を宣言していますが、OBJ座標の単位は宣言されていません。


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="その他のサポートされている変換" subTitle="Xを他の多くのファイル形式に変換することもできます。" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/x-to-3ds/" name="Xから3DS" description="3DスタジオDOSメッシュ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/x-to-amf/" name="XからAMF" description="アディティブマニュファクチャリングフォーマット" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/x-to-ase/" name="XからASE" description="2Dアニメーションファイル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/x-to-dae/" name="XからDAE" description="デジタル資産交換" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/x-to-fbx/" name="XからFBX" description="3D形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/x-to-gltf/" name="XからGLTF" description="GL伝送フォーマット" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/x-to-html/" name="XからHTML" description="ハイパーテキストマークアップ言語" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/x-to-ply/" name="XからPLY" description="ポリゴンファイル形式" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/x-to-rvm/" name="XからRVM" description="AVEVAプラント設計モデル" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/x-to-stl/" name="XからSTL" description="交換可能な3D表面形状" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/x-to-u3d/" name="XからU3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}