﻿---
title: Convertir 3DS a AMF a través de C# 
weight: 1090
url: /es/net/conversion/3ds-to-amf/ 
description: Ejemplo de código para la conversión de 3DS a AMF C#. Utilice el código de ejemplo API para la conversión por lotes de archivos 3DS a AMF dentro de VB.NET, Asp.NET o cualquier aplicación basada en .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Convertir 3DS a AMF a través de C#" h2="Renderizar 3DS como AMF sin ningún software de modelado y renderizado 3D." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="AMF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="3DS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cómo convertir 3DS a AMF usando C#" %}}

 Para convertir 3DS a AMF, usaremos
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API, que es una manipulación y conversión de documentos rica en funciones, potente y fácil de usar API para la plataforma C#. Abierto
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 administrador de paquetes, busque
 Aspose.3D 
 e instalar También puede usar el siguiente comando desde la Consola del administrador de paquetes.

{{% blocks/products/pf/agp/code-block title="Comando de la consola del Administrador de paquetes" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Pasos para convertir 3DS a AMF a través de C#" %}}

{{% blocks/products/pf/agp/text %}}

 Los programadores de .NET pueden cargar y convertir fácilmente archivos 3DS a AMF con solo unas pocas líneas de código.

{{% /blocks/products/pf/agp/text %}}

1. Cargue el archivo 3DS a través del constructor de la clase Escena1. Crear una instancia de AmfSaveOptions1. Establecer AMF propiedades específicas para la conversión avanzada1. Llame al método Scene.Save1. Pase la ruta de salida con la extensión de archivo AMF y el objeto de AmfSaveOptions1. Compruebe el archivo AMF resultante en la ruta especificada
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de ejecutar el código de conversión .NET, asegúrese de cumplir los siguientes requisitos previos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatible con .NET Framework, .NET Core, Mono.- Entorno de desarrollo como Microsoft Visual Studio.- Aspose.3D for .NET DLL a la que se hace referencia en tu proyecto.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Este código de muestra muestra la conversión de 3DS a AMF C#" offSpacer="" %}}

```cs
// carga el 3DS en un objeto de Escena 
var document = new Aspose.ThreeD.Scene("template.3ds");
// crear una instancia de AmfSaveOptions 
var options = new Aspose.ThreeD.Formats.AmfSaveOptions();
// guardar 3DS como AMF 
document.Save("output.amf", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Aplicación gratuita para convertir 3DS a AMF" sectionDescription="Consulte nuestras demostraciones en vivo para [conversión de 3DS a AMF](https://products.aspose.app/3d/conversion/3ds-to-amf) con los siguientes beneficios." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No es necesario descargar ni configurar nada." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No es necesario escribir ningún código." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Simplemente cargue su archivo 3DS y presione el botón \"Convertir\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Obtendrá instantáneamente el enlace de descarga para el archivo AMF resultante." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Una biblioteca de procesamiento de archivos 3D para manipular archivos 3D sin ningún software de modelado y renderizado. 3D API admite Discreet3DS, WavefrontOBJ, FBX (ASCII, binario), STL (ASCII, binario), Universal3D, Collada, glTF, GLB, PLY, DirectX, Google Draco formatos de archivo y más. Los desarrolladores pueden crear, leer, convertir, modificar y controlar la esencia de los formatos de documentos 3D fácilmente.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="3DS" readMoreLink="https://docs.fileformat.com/3d/3ds/" >}}
Un archivo con la extensión 3DS representa el formato de archivo de malla de 3D Studio (DOS) utilizado por Autodesk 3D Studio. Autodesk 3D Studio ha estado en el mercado de formatos de archivo 3D desde la década de 1990 y ahora ha evolucionado a 3D Studio MAX para trabajar con 3D modelado, animación y renderizado. Un archivo 3DS contiene datos para la representación 3D de escenas e imágenes y es uno de los formatos de archivo populares para la importación y exportación de datos 3D. Considera información como ubicaciones de cámaras, datos de malla, información de iluminación, configuraciones de ventanas gráficas, datos de grupos de suavizado, referencias de mapas de bits y atributos para crear vértices y polígonos para renderizar una escena.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="amf" readMoreLink="https://docs.fileformat.com/3d/amf/" >}}
El formato de archivo de fabricación aditiva (AMF) define estándares abiertos para la descripción de objetos para ser utilizados por procesos de fabricación aditiva como la impresión 3D. Los programas CAD usan el formato de archivo AMF haciendo uso de información como la geometría, el color y el material de los objetos. AMF es diferente al formato STL ya que el lateral no admite color, materiales, entramados ni constelaciones.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="También puede convertir 3DS en muchos otros formatos de archivo, incluidos algunos de los que se enumeran a continuación." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-dae/" name="3DS A DAE" description="Intercambio de activos digitales" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-fbx/" name="3DS A FBX" description="3D Formato" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-html/" name="3DS A HTML" description="Lenguaje de marcado de hipertexto" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-obj/" name="3DS A OBJ" description="3D formato de archivo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-pdf/" name="3DS A PDF" description="Formato de Documento Portable" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-ply/" name="3DS A PLY" description="Formato de archivo de polígono" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-rvm/" name="3DS A RVM" description="Modelo de diseño de planta de AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-stl/" name="3DS A STL" description="Geometría de superficie intercambiable 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/3ds-to-u3d/" name="3DS A U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}