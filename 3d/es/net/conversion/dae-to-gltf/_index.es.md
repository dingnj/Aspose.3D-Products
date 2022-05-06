﻿---
title: Convertir DAE a GLTF a través de C# 
url: /es/net/conversion/dae-to-gltf/ 
description: Ejemplo de código para la conversión de DAE a GLTF C#. Utilice el código de ejemplo API para la conversión por lotes de archivos DAE a GLTF dentro de VB.NET, Asp.NET o cualquier aplicación basada en .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Convertir DAE a GLTF a través de C#" h2="Renderizar DAE como GLTF sin ningún software de modelado y renderizado 3D." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="GLTF" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DAE" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Cómo convertir DAE a GLTF usando C#" %}}

 Para convertir DAE a GLTF, usaremos
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

{{% blocks/products/pf/agp/feature-section-col title="Pasos para convertir DAE a GLTF a través de C#" %}}

{{% blocks/products/pf/agp/text %}}

 Los programadores de .NET pueden cargar y convertir fácilmente archivos DAE a GLTF con solo unas pocas líneas de código.

{{% /blocks/products/pf/agp/text %}}

1. Cargue el archivo DAE a través del constructor de la clase Escena1. Crear una instancia de AmfSaveOptions1. Establecer GLTF propiedades específicas para la conversión avanzada1. Llame al método Scene.Save1. Pase la ruta de salida con la extensión de archivo GLTF y el objeto de GltfSaveOptions1. Compruebe el archivo GLTF resultante en la ruta especificada
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos del sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Antes de ejecutar el código de conversión .NET, asegúrese de cumplir los siguientes requisitos previos.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatible con .NET Framework, .NET Core, Mono.- Entorno de desarrollo como Microsoft Visual Studio.- Aspose.3D for .NET DLL a la que se hace referencia en tu proyecto.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Este código de muestra muestra la conversión de DAE a GLTF C#" offSpacer="" %}}

```cs
// carga el DAE en un objeto de Escena 
var document = new Aspose.ThreeD.Scene("template.dae");
// crear una instancia de GltfSaveOptions 
var options = new Aspose.ThreeD.Formats.GltfSaveOptions();
// guardar DAE como GLTF 
document.Save("output.gltf", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Aplicación gratuita para convertir DAE a GLTF" sectionDescription="Consulte nuestras demostraciones en vivo para [conversión de DAE a GLTF](https://products.aspose.app/3d/conversion/dae-to-gltf) con los siguientes beneficios." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No es necesario descargar ni configurar nada." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No es necesario escribir ningún código." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Simplemente cargue su archivo DAE y presione el botón \"Convertir\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Obtendrá instantáneamente el enlace de descarga para el archivo GLTF resultante." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Una biblioteca de procesamiento de archivos 3D para manipular archivos 3D sin ningún software de modelado y renderizado. 3D API admite Discreet3DS, WavefrontOBJ, FBX (ASCII, binario), STL (ASCII, binario), Universal3D, Collada, glTF, GLB, PLY, DirectX, Google Draco formatos de archivo y más. Los desarrolladores pueden crear, leer, convertir, modificar y controlar la esencia de los formatos de documentos 3D fácilmente.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DAE" readMoreLink="https://docs.fileformat.com/3d/dae/" >}}
Un archivo DAE es un formato de archivo de intercambio de activos digitales que se utiliza para intercambiar datos entre aplicaciones 3D interactivas. Este formato de archivo se basa en el esquema XML COLLADA (COLLAborative Design Activity), que es un esquema XML estándar abierto para el intercambio de activos digitales entre aplicaciones de software de gráficos. Ha sido adoptado por ISO como una especificación disponible públicamente, ISO/pAS 17506.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="gltf" readMoreLink="https://docs.fileformat.com/3d/gltf/" >}}
glTF (formato de transmisión GL) es un formato de archivo 3D que almacena información del modelo 3D en formato JSON. El uso de JSON minimiza tanto el tamaño de los activos 3D como el procesamiento en tiempo de ejecución necesario para desempaquetar y usar esos activos. Fue adoptado para la transmisión y carga eficiente de 3D escenas y modelos por aplicaciones. glTF fue desarrollado por el grupo de trabajo de formatos 3D de Khronos Group y sus creadores también lo describen como JPEG de 3D. El formato define un formato de publicación común extensible para 3D herramientas y servicios de contenido que agiliza los flujos de trabajo de creación y permite el uso interoperable de contenido en toda la industria. La intención detrás de la creación del formato de archivo glTF era definir un formato de publicación común y extensible para las herramientas y servicios de contenido 3D que debería optimizar los flujos de trabajo de creación y permitir el uso interoperable del contenido en toda la industria. Minimiza el procesamiento en tiempo de ejecución de las aplicaciones que utilizan WebGL y otras API.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="También puede convertir DAE en muchos otros formatos de archivo, incluidos algunos de los que se enumeran a continuación." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dae-to-3ds/" name="DAE A 3DS" description="3D Malla DOS de estudio" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dae-to-amf/" name="DAE A AMF" description="Formato de fabricación aditiva" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dae-to-fbx/" name="DAE A FBX" description="3D Formato" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dae-to-html/" name="DAE A HTML" description="Lenguaje de marcado de hipertexto" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dae-to-obj/" name="DAE A OBJ" description="3D formato de archivo" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dae-to-pdf/" name="DAE A PDF" description="Formato de Documento Portable" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dae-to-ply/" name="DAE A PLY" description="Formato de archivo de polígono" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dae-to-rvm/" name="DAE A RVM" description="Modelo de diseño de planta de AVEVA" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dae-to-stl/" name="DAE A STL" description="Geometría de superficie intercambiable 3D" >}}{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/dae-to-u3d/" name="DAE A U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}