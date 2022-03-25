﻿---
title: PLY GLTF-re konvertálni C#-en keresztül 
url: /hu/net/conversion/ply-to-gltf/ 
description: Minta kód a PLY to GLTF C# konverzióra. API példa kód a batch PLY fájlokat GLTF konverzióra a vb .NET, asp .NET vagy bármely .NET alapú alkalmazásra.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="PLY GLTF-re konvertálni C#-en keresztül" h2="PLY GLTF-ként rendereljen minden 3D modellezési és renderezési szoftver nélkül." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="GLTF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PLY" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Hogyan lehet konvertálni PLY GLTF C# használatával" %}}

 Annak érdekében, hogy PLY GLTF-re konvertáljuk, használjuk
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API ami egy feature-rich, erős és könnyen használható dokumentum manipuláció és konverzió API for C# platform. Open
 [Nuget](https://www.nuget.org/packages/aspose.3d) 
 Csomagkezelő, keresés
 Aspose.3D 
 És telepíteni. A csomagkezelő konzolból az alábbi parancsot is használhatja.

{{% blocks/products/pf/agp/code-block title="Csomagkezelő konzol parancs" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Lépések a PLY GLTF-re való konvertálásához C#-en keresztül" %}}

{{% blocks/products/pf/agp/text %}}

 .NET a programozók a PLY fájlokat egyszerűen GLTF-re tölthetik és konvertálhatják néhány sor kóddal.

{{% /blocks/products/pf/agp/text %}}

1. A PLY fájl betöltése a jelenet-osztály konstruktőrjén keresztül1. Hozzon létre egy példány amfsaveoptions1. GLTF specifikus tulajdonságok beállítása a fejlett konverzióhoz1. Hívja a jelenetet. mentse módszer1. Adja át a kimeneti utat GLTF fájl kiterjesztés & objektum gltfsaveoptions1. Ellenőrizze a resultant GLTF fájlt a megadott útvonalon
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Rendszerkövetelmények" %}}

{{% blocks/products/pf/agp/text %}}

 A .NET konverziós kód futtatása előtt győződjön meg róla, hogy a következő feltételekkel rendelkezik.

{{% /blocks/products/pf/agp/text %}}

- Microsoft windows vagy egy kompatibilis operációs rendszer .NET framework, .NET core, Mono.- Fejlesztési környezet, mint a microsoft visual studio.- Aspose.3D for .NET dll hivatkozott a projektben.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Ez a minta kód megmutatja a PLY to GLTF C# konverziót" offSpacer="" %}}

```cs
// A PLY-t a jelenet objektumába tölti 
var document = new Aspose.ThreeD.Scene("template.ply");
// Hozzon létre egy példány gltfsaveoptions 
var options = new Aspose.ThreeD.Formats.GltfSaveOptions();
// Mentés PLY GLTF 
document.Save("output.gltf", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Free app to convert PLY to GLTF" sectionDescription="Ellenőrizze az élő demók [PLY a GLTF konverzióra](https://products.aspose.app/3d/conversion/ply-to-gltf) A következő előnyökkel." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nem kell letölteni vagy beállítani semmit." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nem kell semmiféle kódot írni." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Csak töltsön fel a PLY fájlt, és nyomja meg a \"convert\" gombot." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Azonnal kap a letöltési linket eredményes GLTF fájl." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 3D fájlfeldolgozó könyvtár a 3D fájlok manipulálására minden modellező és renderező szoftver nélkül. A 3D API Discreet3DS, WavefrontOBJ, FBX (ascii, bináris), STL (ascii, bináris), Universal3D, Collada, glTF, GLB, PLY, directx, Google Draco fájlformátumok és több. A fejlesztők könnyen létrehozhatják, olvashatják, átalakíthatják, módosíthatják és irányíthatják a 3D dokumentumformátumok anyagát.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PLY" readMoreLink="https://docs.fileformat.com/3d/ply/" >}}
PLY, sokszög fájlformátum, a 3D fájlformátumot jelenti, amely poligonok gyűjteményeként leírt grafikus objektumokat tárol. Ennek a fájlformátumnak a célja az volt, hogy egy egyszerű és egyszerű fájltípust hozzanak létre, amely elég általános ahhoz, hogy hasznos legyen a modellek széles skálájához. PLY fájlformátum jön ascii, valamint bináris formátumban a kompakt tárolás és a gyors megtakarítás és betöltés. A fájlformátumot különböző alkalmazások használják, amelyek támogatást nyújtanak a 3D fájlok olvasására.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="gltf" readMoreLink="https://docs.fileformat.com/3d/gltf/" >}}
A glTF (gl átviteli formátum) egy 3D fájlformátum, amely a 3D modellinformációkat json formátumban tárolja. A json használata minimálisra csökkenti a 3D eszközök méretét és a futásidejű feldolgozást is, amely az eszközök kicsomagolásához és használatához szükséges. Elfogadták a 3D jelenetek és modellek hatékony átvitelére és betöltésére az alkalmazások által. A glTF-t a khronos group 3D formats munkacsoport fejlesztette ki, és alkotói a 3D jpeg-ként is leírják. A formátum meghatározza a 3D tartalmi eszközök és szolgáltatások kiterjeszthető, közös kiadási formátumát, amely a munkafolyamatok létrehozását egyszerűsíti, és lehetővé teszi a tartalom átjárható felhasználását az iparágban. A glTF fájlformátum létrehozása mögött az volt a szándék, hogy egy kiterjeszthető, általános kiadói formátum 3D tartalmi eszközök és szolgáltatások számára, amelyek egyszerűsíteni kell az alkotási munkafolyamatokat, és lehetővé teszik a tartalom átjárható felhasználását az iparágban. Minimálisra csökkenti a webgl és más api-k használatával végzett alkalmazások futási idejű feldolgozását.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Egyéb támogatott konverziók" subTitle="Lehet konvertálni PLY számos más fájlformátumba, beleértve néhány az alábbiakban felsorolt." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-3ds/" name="PLY to 3DS" description="3D studio dos mesh" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-amf/" name="PLY to AMF" description="Adalékanyag gyártási formátum" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-dae/" name="PLY to DAE" description="Digitális eszközcsere" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-fbx/" name="PLY to FBX" description="3D formátum" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-html/" name="PLY to HTML" description="Hiper szöveg jelölő nyelv" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-obj/" name="PLY to OBJ" description="3D fájlformátum" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-pdf/" name="PLY to PDF" description="Hordozható dokumentum formátum" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-rvm/" name="PLY to RVM" description="Aveva üzem tervezési modell" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-stl/" name="PLY to STL" description="Cserélhető 3D felületi geometria" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/ply-to-u3d/" name="PLY to U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}