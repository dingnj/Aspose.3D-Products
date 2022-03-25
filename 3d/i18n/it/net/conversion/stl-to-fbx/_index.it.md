﻿---
title: Convertire da STL a FBX tramite C# 
weight: 390
url: /it/net/conversion/stl-to-fbx/ 
description: Codice di esempio per la conversione da STL a FBX C#. Utilizza API codice di esempio per la conversione da STL file batch a FBX all'interno di VB.NET, Asp.NET o qualsiasi applicazione basata su .NET.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Convertire da STL a FBX tramite C#" h2="Rendera STL come FBX senza alcun software di modellazione e rendering 3D." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="FBX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="STL" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Come convertire da STL a FBX usando C#" %}}

 Per convertire da STL a FBX, useremo
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API che è una piattaforma di conversione e manipolazione di documenti API ricca di funzionalità, potente e facile da usare per C#. Apri
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 Gestore di pacchetti, ricerca di
 Aspose.3D 
 E installare. È inoltre possibile utilizzare il seguente comando dalla Console di Gestione pacchetti.

{{% blocks/products/pf/agp/code-block title="Comando Console Gestione pacchetti" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Passi per convertire da STL a FBX tramite C#" %}}

{{% blocks/products/pf/agp/text %}}

 .NET programmatori possono facilmente caricare e convertire STL file in FBX in poche righe di codice.

{{% /blocks/products/pf/agp/text %}}

1. Carica STL file tramite il costruttore della classe Scene1. Creare un'istanza di FbxSaveOptions1. Imposta FBX proprietà specifiche per la conversione avanzata1. Chiama il metodo Scena. Salva1. Passa il percorso di output con FBX estensione file e oggetto di FbxSaveOptions1. Controlla il file FBX risultante nel percorso specificato
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di sistema" %}}

{{% blocks/products/pf/agp/text %}}

 Prima di eseguire il codice di conversione .NET, assicurati di avere i seguenti prerequisiti.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows o un sistema operativo compatibile con .NET Framework, .NET Core, Mono.- Ambiente di sviluppo come Microsoft Visual Studio.- Aspose.3D for .NET DLL a cui si fa riferimento nel progetto.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Questo codice di esempio mostra la conversione da STL a FBX C#" offSpacer="" %}}

```cs
// Caricare il STL in un oggetto di scena 
var document = new Aspose.ThreeD.Scene("template.stl");
// Creare un'istanza di FbxSaveOptions 
var options = new Aspose.ThreeD.Formats.FbxSaveOptions();
// Salva STL come FBX 
document.Save("output.fbx", options); 


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="App gratuita da convertire da STL a FBX" sectionDescription="Controlla le nostre demo live per [Conversione da STL a FBX](https://products.aspose.app/3d/conversion/stl-to-fbx) Con i seguenti vantaggi." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Non c\' è bisogno di scaricare o configurare nulla." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Non c\' è bisogno di scrivere alcun codice." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Basta caricare il tuo file STL e premere il pulsante \"Converti\"." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Riceverai immediatamente il link per il download del file FBX risultante." >}}

    {{% blocks/products/pf/agp/content h2="" %}}

 Una libreria di elaborazione file 3D per manipolare 3D file senza alcun software di modellazione e rendering. Il 3D API supporta Discreet3DS, WavefrontOBJ, FBX (ASCII, Binary), STL (ASCII, Binary), Universal3D, Collada, glTF, GLB, PLY, DirectX, Google Draco formati di file e altro ancora. Gli sviluppatori possono creare, leggere, convertire, modificare e controllare facilmente la sostanza di 3D formati di documenti.



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="STL" readMoreLink="https://docs.fileformat.com/cad/stl/" >}}
STL, abbreviazione di stereolithrography, è un formato di file intercambiabile che rappresenta la geometria della superficie tridimensionale. Il formato del file trova il suo utilizzo in diversi campi come la prototipazione rapida, la stampa 3D e la produzione assistita da computer. Rappresenta una superficie come una serie di piccoli triangoli, noti come sfaccettature, in cui ciascuna sfaccettatura è descritta da una direzione perpendicolare e tre punti che rappresentano i vertici del triangolo. I dati risultanti vengono utilizzati dalle applicazioni per determinare la sezione trasversale della forma 3D che deve essere costruita dal fabber. Non sono disponibili informazioni nel formato di file STL per la rappresentazione di colore, texture o altri attributi comuni del modello CAD.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="fbx" readMoreLink="https://docs.fileformat.com/3d/fbx/" >}}
FBX, FilmBox, è un popolare formato di file 3D originariamente sviluppato da Kaydara per MotionBuilder. È stata acquisita da Autodesk Inc nel 2006 ed è ora uno dei principali formati di scambio 3D utilizzati da molti 3D strumenti. FBX è disponibile sia in formato binario che ASCII. Il formato è stato istituito per fornire l'interoperabilità tra le applicazioni per la creazione di contenuti digitali. Ci sono molti strumenti disponibili per la conversione da/a FBX formato di file.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Altre conversioni supportate" subTitle="Puoi anche convertire STL in molti altri formati di file, inclusi alcuni elencati di seguito." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/stl-to-3ds/" name="Da STL a 3DS" description="Mesh DOS da studio 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/stl-to-amf/" name="Da STL a AMF" description="Formato di produzione additiva" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/stl-to-dae/" name="Da STL a DAE" description="Scambio di beni digitali" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/stl-to-html/" name="Da STL a HTML" description="Linguaggio di markup iper testo" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/stl-to-obj/" name="Da STL a OBJ" description="Formato file 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/stl-to-pdf/" name="Da STL a PDF" description="Formato documento portatile" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/stl-to-ply/" name="Da STL a PLY" description="Formato file poligono" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/stl-to-rvm/" name="Da STL a RVM" description="Modello di progettazione di piante AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/conversion/stl-to-u3d/" name="Da STL a U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}