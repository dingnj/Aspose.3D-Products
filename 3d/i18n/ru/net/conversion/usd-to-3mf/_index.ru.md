﻿---
title: Конвертировать USD в 3MF через C# 
description: Конвертируйте USD и другие 3D файлы с помощью .NET API
url: /ru/net/conversion/usd-to-3mf/
family: 3d
platformtag: net
feature: conversion
informat: USD
outformat: 3MF
otherformats: DAE STL JT GLTF RVM DXF PDF ASE 
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Конвертировать USD в 3MF через C#" h2="Экспорт USD и других 3D файлов с использованием .NET Framework, .NET Core и Mono" >}}
{{< blocks/products/pf/main-container >}}
{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Экспорт USD сцены как 3MF с C#" %}}
1. Загрузить файл USD с помощью конструктора [Сцена](https://apireference.aspose.com/3d/net/aspose.threed/scene) Класс2. Звоните [Сцена. Сохранить](https://apireference.aspose.com/3d/net/aspose.threed/scene/methods/save/index) Метод
3. Передайте имя выходного файла с расширением. 3mf в качестве первого параметра
4. Укажите значение поля "Microsoft3MF" из [Файл Формат](https://apireference.aspose.com/3d/net/aspose.threed/fileformat/fields/index) Класс
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="3D Преобразование формата API for .NET" %}}
Установите из командной строки как «nuget install Aspose.3d» или через консоль диспетчера пакетов Visual Studio с «Install-Package Aspose.3D».

Кроме того, получите автономный установщик MSI или DLL в файле ZIP из [Загрузки](https://downloads.aspose.com/3d/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Код C# для преобразования USD в 3MF" gistPath="" %}}
```cs
// Загрузить USD в объект сцены 
var scene = new Aspose.ThreeD.Scene("template.usd");
// Сохранить USD как 3MF 
scene.Save("output.3mf", Aspose.ThreeD.FileFormat.Microsoft3MF);

```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< blocks/products/pf/agp/about-file-autogen >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}