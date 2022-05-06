﻿---
title: Wyświetl GLTF formaty plików za pośrednictwem .NET 
weight: 2640
url: /pl/net/viewer/gltf/ 
description: C# kod źródłowy do ładowania, renderowania i wyświetlania GLTF dokumentów w .NET Framework, .NET Core, Mono.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="GLTF Przeglądarka plików for .NET" h2="Renderuj pliki GLTF bez żadnego oprogramowania do modelowania i renderowania 3D." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="GLTF" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="GLTF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Jak wyświetlić GLTF plik za pomocą C#" %}}

 Aby wyświetlić plik GLTF, użyjemy
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API to bogata w funkcje, wydajna i łatwa w użyciu platforma API dla C#, której można używać z dowolną przeglądarką. otwarty
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 menedżer pakietów, szukaj
 ***** 
 i zainstaluj. Możesz również użyć następującego polecenia z konsoli Menedżera pakietów.

{{% blocks/products/pf/agp/code-block title="Polecenie konsoli menedżera pakietów" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Kroki, aby wyświetlić GLTF przez C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D ułatwia programistom przeglądanie pliku GLTF za pomocą zaledwie kilku linijek kodu.

{{% /blocks/products/pf/agp/text %}}

1. Załaduj plik GLTF za pomocą konstruktora klasy Scene1. Utwórz instancję Html5SaveOptions1. Ustaw właściwości zaawansowanego formatowania1. Wywołaj metodę Scene.Save z obiektem Html5SaveOptions1. Sprawdź wynikowy plik HTML w domyślnej przeglądarce
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D for .NET jest obsługiwany we wszystkich głównych systemach operacyjnych. Tylko upewnij się, że masz następujące wymagania wstępne.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows lub zgodny system operacyjny z .NET Framework, .NET Core, Mono- Środowisko programistyczne, takie jak Microsoft Visual Studio- Aspose.3D for .NET, o którym mowa w Twoim projekcie
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# kod do wyświetlenia GLTF" offSpacer="" %}}

```cs

string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// załaduj GLTF scenę przez instancję Scene
var scene = new ThreeD.Scene("template.gltf");
// utwórz obiekt Html5SaveOptions i ustaw właściwości do formatowania
var options = new ThreeD.Formats.Html5SaveOptions()
{
    // wyłącz siatkę
    ShowGrid = false,
    // wyłącz interfejs użytkownika
    ShowUI = false
};

// zapisz 3D scenę jako HTML5
scene.Save(output, options);
// wczytaj wynikowy HTML w domyślnej przeglądarce
System.Diagnostics.Process.Start(output);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Aspose.3D for .NET API" %}}

 Aspose.3D to CAD i Gameware API do ładowania, modyfikowania i konwertowania plików 3D. API jest samodzielny i nie wymaga żadnego 3D oprogramowania do modelowania ani renderowania. Można łatwo użyć API dla Discreet3DS, WavefrontOBJ, STL (ASCII, Binary), Universal3D, FBX (ASCII, Binary), Collada, glTF, PLY, GLB, DirectX i inne formaty. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Bezpłatna aplikacja do wyświetlenia GLTF" sectionDescription="Sprawdź nasze prezentacje na żywo, aby [Zobacz GLTF](https://products.aspose.app/3d/viewer/gltf) z następującymi korzyściami." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nie musisz niczego pobierać ani konfigurować" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nie ma potrzeby pisania ani kompilowania kodu" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Po prostu prześlij plik GLTF i naciśnij przycisk „Wyświetl”" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" W razie potrzeby pobierz plik GLTF z linku" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="GLTF" readMoreLink="https://docs.fileformat.com/3d/gltf/" >}}
glTF (GL Transmission Format) to format pliku 3D, który przechowuje informacje o modelu 3D w formacie JSON. Użycie JSON minimalizuje zarówno rozmiar 3D zasobów, jak i przetwarzanie w czasie wykonywania potrzebne do rozpakowania i używania tych zasobów. Został przystosowany do wydajnej transmisji i ładowania 3D scen i modeli przez aplikacje. glTF został opracowany przez grupę roboczą ds. formatów Khronos Group 3D i jest również określany jako JPEG 3D przez jego twórców. Format definiuje rozszerzalny, wspólny format publikowania dla 3D narzędzi i usług dotyczących treści, który usprawnia przepływy pracy związane z tworzeniem i umożliwia interoperacyjne korzystanie z treści w całej branży. Intencją stworzenia formatu pliku glTF było zdefiniowanie rozszerzalnego, wspólnego formatu publikowania dla 3D narzędzi i usług dotyczących treści, które powinny usprawnić przepływy pracy związane z tworzeniem treści i umożliwić interoperacyjne korzystanie z treści w całej branży. Minimalizuje przetwarzanie w czasie wykonywania przez aplikacje korzystające z WebGL i innych interfejsów API.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane formaty przeglądarki" subTitle="Używając C#, można również wyświetlić wiele innych formatów plików, w tym." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/3ds/" name="3DS" description="3D Studio DOS Mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/3mf/" name="3MF" description="3D Format produkcyjny" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/amf/" name="AMF" description="Format wytwarzania przyrostowego" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/ase/" name="ASE" description="Plik animacji 2D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/dae/" name="DAE" description="Wymiana aktywów cyfrowych" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/dxf/" name="DXF" description="Format wymiany rysunków" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/fbx/" name="FBX" description="3D Format" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/glb/" name="GLB" description="3D Reprezentacja plików binarnych" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/jt/" name="JT" description="Plik teselacji Jowisza" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/obj/" name="OBJ" description="3D Format pliku" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/ply/" name="PLY" description="Format pliku wielokąta" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/rvm/" name="RVM" description="Model projektowy zakładu AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/stl/" name="STL" description="Wymienna 3D geometria powierzchni" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/u3d/" name="U3D" description="Universal 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/vrml/" name="VRML" description="Język modelowania rzeczywistości wirtualnej" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/x/" name="x" description="Obraz modelu DirectX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/zip/" name="ZIP" description="ZIP Format archiwizacji" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}