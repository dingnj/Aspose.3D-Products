﻿---
title: Конвертировать 3DS в STL через C# 
weight: 2250
url: /ru/net/conversion/3ds-to-stl/ 
description: Пример кода для преобразования 3DS в STL C#. Используйте API пример кода для пакетного преобразования 3DS файлов в STL в VB.NET, Asp.NET или любом приложении на основе .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Конвертировать 3DS в STL через C#" h2="Отправка 3DS как STL без программного обеспечения для моделирования и рендеринга 3D." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="STL" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="3DS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Как конвертировать 3DS в STL с помощью C#" %}}

 Чтобы конвертировать 3DS в STL, мы будем использовать
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API, который представляет собой многофункциональный, мощный и простой в использовании документ обработки и преобразования API для платформы C#. Открытая
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 Менеджер пакетов, поиск
 Aspose.3D 
 И установить. Вы также можете использовать следующую команду из консоли диспетчера пакетов.

{{% blocks/products/pf/agp/code-block title="Команда консоли диспетчера пакетов" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Шаги для преобразования 3DS в STL через C#" %}}

{{% blocks/products/pf/agp/text %}}

 .NET программисты могут легко загружать и конвертировать 3DS файлы в STL всего за несколько строк кода.

{{% /blocks/products/pf/agp/text %}}

1. Загрузить файл 3DS через конструктор класса Scene1. Создать экземпляр StlSaveOptions1. Установите специальные свойства STL для расширенного преобразования1. Вызовите метод Scene.Save1. Передайте выходной путь с расширением файла STL и объектом StlSaveOptions1. Проверьте результирующий файл STL по указанному пути
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к системе" %}}

{{% blocks/products/pf/agp/text %}}

 Перед запуском кода преобразования .NET убедитесь, что у вас есть следующие предпосылки.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows или совместимая ОС с .NET Framework, .NET Core, Mono.- Среда разработки, такая как Microsoft Visual Studio.- Aspose.3D for .NET DLL, упомянутые в вашем проекте.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Этот пример кода показывает 3DS в STL C# преобразования" offSpacer="" %}}

```cs
// Загрузить 3DS в объект сцены 
var document = new Aspose.ThreeD.Scene("template.3ds");
// Создать экземпляр StlSaveOptions 
var options = new Aspose.ThreeD.Formats.StlSaveOptions();
// Сохранить 3DS как STL 
document.Save("output.stl", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Бесплатное приложение для преобразования 3DS в STL" sectionDescription="Проверьте наши живые демо для [Преобразование 3DS в STL](https://products.aspose.app/3d/conversion/3ds-to-stl) Со следующими преимуществами." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Нет необходимости загружать или настраивать что-либо." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Не нужно писать какой-либо код." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Просто загрузите свой 3DS файл и нажмите кнопку \"Конвертировать\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Вы мгновенно получите ссылку для загрузки полученного файла STL." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Библиотека обработки файлов 3D для управления файлами 3D без какого-либо программного обеспечения для моделирования и рендеринга. 3D API поддерживает Discreet3DS, WavefrontOBJ, FBX (ASCII, двоичный), STL (ASCII, двоичный), Universal3D, Collada, glTF, GLB, PLY, DirectX, Google Draco форматы файлов и многое другое. Разработчики могут легко создавать, читать, преобразовывать, изменять и контролировать содержание форматов документов 3D.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="3DS" readMoreLink="https://docs.fileformat.com/3d/3ds/" >}}
Файл с расширением 3DS представляет формат сетчатого файла 3D Studio (DOS), используемый Autodesk 3D Studio. Autodesk 3D Studio работает на рынке форматов файлов 3D с 1990-х годов и теперь превратилась в 3D Studio MAX для работы с моделированием, анимацией и рендерингом 3D. Файл 3DS содержит данные для 3D представления сцен и изображений и является одним из популярных форматов файлов для импорта и экспорта данных 3D. Он рассматривает такую информацию, как местоположение камеры, данные Mesh, информацию об освещении, конфигурации видовых экранов, данные сглаживающей группы, растровые ссылки и атрибуты для создания вершин и полигонов для рендеринга сцены.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="stl" readMoreLink="https://docs.fileformat.com/cad/stl/" >}}
STL, аббревиатура от стереолитрографии, представляет собой взаимозаменяемый формат файла, который представляет трехмерную геометрию поверхности. Формат файла находит свое применение в нескольких областях, таких как быстрое прототипирование, печать 3D и компьютерное производство. Он представляет поверхность как серию небольших треугольников, известных как грани, где каждая фасетка описывается перпендикулярным направлением и тремя точками, представляющими вершины треугольника. Результирующие данные используются приложениями для определения поперечного сечения формы 3D, которая будет построена fabber. В формате STL отсутствует информация о представлении цвета, текстуры или других общих атрибутов модели CAD.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="Вы также можете конвертировать 3DS во многие другие форматы файлов, включая несколько перечисленных ниже." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-amf/" name="3DS ДО AMF" description="Аддитивный формат производства" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-dae/" name="3DS ДО DAE" description="Обмен цифровых активов" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-fbx/" name="3DS ДО FBX" description="Формат 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-html/" name="3DS ДО HTML" description="Язык разметки текста Hyper" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-obj/" name="3DS ДО OBJ" description="Формат файла 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-pdf/" name="3DS ДО PDF" description="Портативный формат документа" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-ply/" name="3DS ДО PLY" description="Формат файла многоугольника" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-rvm/" name="3DS ДО RVM" description="Модель дизайна завода AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-u3d/" name="3DS ДО U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}