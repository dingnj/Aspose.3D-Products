﻿---
title: Konwertuj 3MF na PLY za pośrednictwem Java 
weight: 3040
url: /pl/java/conversion/3mf-to-ply/ 
description: Przykładowy kod konwersji Java dla formatu 3MF do pliku PLY. Użyj tego przykładowego kodu, aby przekonwertować 3MF na PLY w dowolnej aplikacji opartej na sieci Web lub pulpicie Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Konwertuj 3MF na PLY za pośrednictwem Java" h2="Konwersja 3MF do PLY przy użyciu biblioteki Java bez oprogramowania do modelowania 3D." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="PLY" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="3MF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="Jak przekonwertować 3MF na PLY za pomocą Java" %}}

 Aby renderować 3MF do PLY, użyjemy
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API, która jest bogatą w funkcje, wydajną i łatwą w użyciu konwersją API for Java platformą. Możesz pobrać jego najnowszą wersję bezpośrednio z
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
 I zainstaluj go w swoim projekcie opartym na Maven, dodając następujące konfiguracje do pom.xml.

{{% blocks/products/pf/agp/code-block title="Repozytorium" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://Repository.aspose.com/repo/ </url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Zależność" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Kroki, aby przekonwertować 3MF na PLY za pośrednictwem Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java programiści mogą z łatwością przekonwertować 3MF plik na PLY w zaledwie kilku wierszach kodu.

{{% /blocks/products/pf/agp/text %}}

1. Załaduj plik 3MF przez konstruktora klasy Scene1. Utwórz instancję PlySaveOptions1. Zestaw PLY specyficznych właściwości dla zaawansowanej konwersji1. Scena wywołania. Metoda zapisywania1. Przekaż ścieżkę wyjściową z rozszerzeniem i obiektem PlySaveOptions PLY
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Wymagania systemowe" %}}

{{% blocks/products/pf/agp/text %}}

 Przed uruchomieniem kodu konwersji Java upewnij się, że masz następujące warunki wstępne.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows lub kompatybilny system operacyjny z Java Runtime Environment dla JSP/JSF Application and Desktop Applications.- Pobierz najnowszą wersję Aspose.3D for Java bezpośrednio z Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="3MF do PLY Java Kod źródłowy konwersji" offSpacer="" %}}

```cs
// Załaduj 3MF w obiekcie Scene 
Scene document = new Scene("template.3mf");
// Utwórz instancję PlySaveOptions 
PlySaveOptions options = new PlySaveOptions();
// Zapisz 3MF jako PLY 
document.save("output.ply", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="3MF do PLY Konwersja na żywo Dema" sectionDescription="[Przelicz 3MF na PLY](https://products.aspose.app/3d/conversion/3mf-to-ply) Teraz odwiedzając naszą stronę Live Demos. Demo na żywo ma następujące zalety" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Nie musisz pobierać Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Nie trzeba pisać żadnego kodu." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Po prostu prześlij swój plik 3MF, a zostanie on natychmiast przekonwertowany na PLY." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Otrzymasz link do pobrania." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Biblioteka manipulacji scenami" %}}

 Aspose.3D to CAD i Gameware API do ładowania, modyfikowania i konwertowania plików 3D. API jest samodzielny i nie wymaga żadnego 3D oprogramowania do modelowania lub renderowania. Można z łatwością użyć API dla Discreet3DS, WavefrontOBJ, STL (ASCII, Binary), Universal3D, FBX (ASCII, Binary), Collada, glTF, PLY, GLB, DirectX i więcej formatów. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="3MF" readMoreLink="https://docs.fileformat.com/3d/3mf/" >}}

3MF, 3D Format produkcji jest używany przez aplikacje do renderowania 3D modeli obiektowych do wielu innych aplikacji, platform, usług i drukarek. Został zbudowany, aby uniknąć ograniczeń i problemów w innych 3D formatach plików, takich jak STL, do pracy z najnowszymi wersjami 3D drukarek. 3MF to stosunkowo nowy format pliku, który został opracowany i opublikowany przez konsorcjum 3MF. Jest wystarczająco bogaty, aby w pełni opisać model, zachowując wewnętrzne informacje, kolor i inne cechy, które sprawiają, że można go rozszerzyć do wspierania nowych innowacji w druku 3D. Format jest rozszerzalny, może być szeroko przyjęty i wolny od problemów związanych z innymi szeroko stosowanymi formatami plików.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PLY" readMoreLink="https://docs.fileformat.com/3d/ply/" >}}

PLY, format pliku Polygon, reprezentuje format pliku 3D, który przechowuje obiekty graficzne opisane jako zbiór wielokątów. Celem tego formatu pliku było ustanowienie prostego i łatwego typu pliku, który jest na tyle ogólny, aby był przydatny w szerokiej gamie modeli. Format pliku PLY jest dostępny jako ASCII, a także format binarny do kompaktowego przechowywania oraz do szybkiego zapisywania i ładowania. Format pliku jest używany przez różne aplikacje, które zapewniają obsługę 3D odczytu plików.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Inne obsługiwane konwersje" subTitle="Możesz także przekonwertować 3MF na wiele innych formatów plików, w tym kilka wymienionych poniżej." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-3ds/" name="3MF DO 3DS" description="3D Studio DOS Mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-amf/" name="3MF DO AMF" description="Format wytwarzania dodatków" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-dae/" name="3MF DO DAE" description="Cyfrowa wymiana aktywów" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-fbx/" name="3MF DO FBX" description="Format 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-gltf/" name="3MF DO GLTF" description="GL Format transmisji" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-html/" name="3MF DO HTML" description="Hyper Text Markup Language" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-obj/" name="3MF DO OBJ" description="Format pliku 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-rvm/" name="3MF DO RVM" description="Model projektowy zakładu AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-stl/" name="3MF DO STL" description="Wymienna 3D geometria powierzchni" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-u3d/" name="3MF DO U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}