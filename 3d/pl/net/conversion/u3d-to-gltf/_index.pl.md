﻿---
title: Konwertuj U3D na GLTF przez C# 
url: /pl/net/conversion/u3d-to-gltf/ 
description: Przykładowy kod konwersji U3D na GLTF C#. Użyj API przykładowego kodu dla plików wsadowych U3D do konwersji GLTF w VB.NET, Asp.NET lub dowolnej aplikacji opartej na .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konwertuj U3D na GLTF przez C#" h2="Renderuj U3D jako GLTF bez żadnego oprogramowania do modelowania i renderowania 3D." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="GLTF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="U3D" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak przekonwertować U3D na GLTF za pomocą C#" %}}

 Aby przekonwertować U3D na GLTF, użyjemy
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API, który jest bogatym w funkcje, wydajnym i łatwym w użyciu narzędziem do manipulacji i konwersji dokumentów API na platformę C#. otwarty
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 menedżer pakietów, szukaj
 Aspose.3D 
 i zainstaluj. Możesz również użyć następującego polecenia z konsoli Menedżera pakietów.

{{% blocks/products/pf/agp/code-block title="Polecenie konsoli menedżera pakietów" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroki, aby przekonwertować U3D na GLTF przez C#" %}}

{{% blocks/products/pf/agp/text %}}

 .NET programiści mogą łatwo ładować i konwertować pliki U3D na GLTF w zaledwie kilku wierszach kodu.

{{% /blocks/products/pf/agp/text %}}

1. Załaduj plik U3D za pomocą konstruktora klasy Scene1. Utwórz instancję AmfSaveOptions1. Ustaw GLTF określone właściwości dla zaawansowanej konwersji1. Wywołaj metodę Scene.Save1. Przekaż ścieżkę wyjściową z rozszerzeniem pliku GLTF i obiektem GltfSaveOptions1. Sprawdź wynikowy plik GLTF w określonej ścieżce
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Przed uruchomieniem kodu konwersji .NET upewnij się, że spełniasz następujące wymagania wstępne.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows lub zgodny system operacyjny z .NET Framework, .NET Core, Mono.- Środowisko programistyczne, takie jak Microsoft Visual Studio.- Aspose.3D for .NET DLL, do którego odwołuje się Twój projekt.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Ten przykładowy kod pokazuje konwersję od U3D do GLTF C#" offSpacer="" %}}

```cs
// załaduj U3D do obiektu sceny 
var document = new Aspose.ThreeD.Scene("template.u3d");
// utwórz instancję GltfSaveOptions 
var options = new Aspose.ThreeD.Formats.GltfSaveOptions();
// zapisz U3D jako GLTF 
document.Save("output.gltf", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Darmowa aplikacja do konwersji U3D na GLTF" sectionDescription="Sprawdź nasze prezentacje na żywo dla [Konwersja z U3D do GLTF](https://products.aspose.app/3d/conversion/u3d-to-gltf) z następującymi korzyściami." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nie musisz niczego pobierać ani konfigurować." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nie musisz pisać żadnego kodu." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Po prostu prześlij swój plik U3D i naciśnij przycisk „Konwertuj”." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Natychmiast otrzymasz link do pobrania wynikowego pliku GLTF." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Biblioteka przetwarzania plików 3D do manipulowania plikami 3D bez żadnego oprogramowania do modelowania i renderowania. 3D API obsługuje Discreet3DS, WavefrontOBJ, FBX (ASCII, Binary), STL (ASCII, Binary), Universal3D, Collada, glTF, GLB, PLY, DirectX, Google Draco formaty plików i inne. Deweloperzy mogą łatwo tworzyć, czytać, konwertować, modyfikować i kontrolować treść 3D formatów dokumentów.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="U3D" readMoreLink="https://docs.fileformat.com/3d/u3d/" >}}
U3D (Universal 3D) to skompresowany format pliku i struktura danych dla 3D grafiki komputerowej. Zawiera 3D informacje o modelu, takie jak siatki trójkątów, oświetlenie, cieniowanie, dane ruchu, linie i punkty z kolorem i strukturą. Format został zaakceptowany jako standard ECMA-363 w sierpniu 2005. 3D Dokumenty PDF obsługują osadzanie obiektów U3D i można je przeglądać w programie Adobe Reader (wersja 7 i nowsze). Format U3D został opracowany z myślą o ustanowieniu uniwersalnego standardu trójwymiarowego przechowywania i wymiany danych. Jednak format znajduje swoje główne zastosowanie w kodowaniu dla 3D PDF, a nie jako format wymiany. Acrobat 3D konwertuje obsługiwany typ pliku 3D na U3D lub PRC po konwersji na PDF.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="gltf" readMoreLink="https://docs.fileformat.com/3d/gltf/" >}}
glTF (GL Transmission Format) to format pliku 3D, który przechowuje informacje o modelu 3D w formacie JSON. Użycie JSON minimalizuje zarówno rozmiar 3D zasobów, jak i przetwarzanie w czasie wykonywania potrzebne do rozpakowania i używania tych zasobów. Został przystosowany do wydajnej transmisji i ładowania 3D scen i modeli przez aplikacje. glTF został opracowany przez grupę roboczą ds. formatów Khronos Group 3D i jest również określany jako JPEG 3D przez jego twórców. Format definiuje rozszerzalny, wspólny format publikowania dla 3D narzędzi i usług dotyczących treści, który usprawnia przepływy pracy związane z tworzeniem i umożliwia interoperacyjne korzystanie z treści w całej branży. Intencją stworzenia formatu pliku glTF było zdefiniowanie rozszerzalnego, wspólnego formatu publikowania dla 3D narzędzi i usług dotyczących treści, które powinny usprawnić przepływy pracy związane z tworzeniem treści i umożliwić interoperacyjne korzystanie z treści w całej branży. Minimalizuje przetwarzanie w czasie wykonywania przez aplikacje korzystające z WebGL i innych interfejsów API.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="Możesz także przekonwertować U3D na wiele innych formatów plików, w tym kilka wymienionych poniżej." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/u3d-to-3ds/" name="U3D DO 3DS" description="3D Studio DOS Mesh" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/u3d-to-amf/" name="U3D DO AMF" description="Format wytwarzania przyrostowego" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/u3d-to-dae/" name="U3D DO DAE" description="Wymiana aktywów cyfrowych" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/u3d-to-fbx/" name="U3D DO FBX" description="3D Format" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/u3d-to-html/" name="U3D DO HTML" description="hipertekstowy język znaczników" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/u3d-to-obj/" name="U3D DO OBJ" description="3D Format pliku" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/u3d-to-pdf/" name="U3D DO PDF" description="format dokumentu przenośnego" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/u3d-to-ply/" name="U3D DO PLY" description="Format pliku wielokąta" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/u3d-to-rvm/" name="U3D DO RVM" description="Model projektowy zakładu AVEVA" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/u3d-to-stl/" name="U3D DO STL" description="Wymienna 3D geometria powierzchni" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}