﻿---
title: Afficher les formats de fichier 3DS via .NET 
weight: 830
url: /fr/net/viewer/3ds/ 
description: C# code source pour charger, restituer et afficher 3DS documents sur .NET Framework, .NET Core, Mono.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="3DS Visionneuse de fichiers for .NET" h2="Rendez les fichiers 3DS sans aucun logiciel de modélisation et de rendu 3D." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="3DS" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="3DS" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="Comment afficher le fichier 3DS à l\'aide de C#" %}}

 Pour afficher le fichier 3DS, nous utiliserons
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API qui est une plate-forme riche en fonctionnalités, puissante et facile à utiliser API pour C# à utiliser avec n'importe quelle visionneuse. Ouvrir
 [NuGet](https://www.nuget.org/packages/aspose.3d) 
 gestionnaire de paquets, recherchez
 **Aspose.3D** 
 et installer. Vous pouvez également utiliser la commande suivante à partir de la console du gestionnaire de packages.

{{% blocks/products/pf/agp/code-block title="Commande de la console du gestionnaire de packages" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Étapes pour afficher 3DS via C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D permet aux développeurs d'afficher facilement le fichier 3DS avec seulement quelques lignes de code.

{{% /blocks/products/pf/agp/text %}}

1. Charger le fichier 3DS via le constructeur de la classe Scene1. Créer une instance de Html5SaveOptions1. Définir les propriétés du formatage avancé1. Appelez la méthode Scene.Save avec l'objet de Html5SaveOptions1. Vérifiez le fichier HTML résultant dans le navigateur par défaut
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Configuration requise" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D for .NET est pris en charge sur tous les principaux systèmes d'exploitation. Assurez-vous simplement que vous disposez des prérequis suivants.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou un système d'exploitation compatible avec .NET Framework, .NET Core, Mono- Environnement de développement comme Microsoft Visual Studio- Aspose.3D for .NET référencé dans votre projet
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# code pour afficher 3DS" offSpacer="" %}}

```cs

string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// charger 3DS scène via une instance de Scene
var scene = new ThreeD.Scene("template.3ds");
// créer un objet de Html5SaveOptions et définir les propriétés de formatage
var options = new ThreeD.Formats.Html5SaveOptions()
{
    // éteindre la grille
    ShowGrid = false,
    // désactiver l'interface utilisateur
    ShowUI = false
};

// enregistrer 3D scène sous HTML5
scene.Save(output, options);
// charger le résultat HTML dans le navigateur par défaut
System.Diagnostics.Process.Start(output);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="À propos de Aspose.3D for .NET API" %}}

 Aspose.3D est un CAD et un Gameware API pour charger, modifier et convertir des fichiers 3D. API est autonome et ne nécessite aucun logiciel de modélisation ou de rendu 3D. On peut facilement utiliser API pour Discreet3DS, WavefrontOBJ, STL (ASCII, Binaire), Universal3D, FBX (ASCII, Binaire), Collada, glTF, PLY, GLB, DirectX et d'autres formats. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Application gratuite pour afficher 3DS" sectionDescription="Consultez nos démos en direct pour [Afficher 3DS](https://products.aspose.app/3d/viewer/3ds) avec les avantages suivants." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Pas besoin de télécharger ou de configurer quoi que ce soit" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Pas besoin d\'écrire ou de compiler du code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Téléchargez simplement le fichier 3DS et appuyez sur le bouton \"Afficher\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Téléchargez le fichier 3DS à partir du lien, si nécessaire" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="3DS" readMoreLink="https://docs.fileformat.com/3d/3ds/" >}}
Un fichier avec l'extension 3DS représente le format de fichier de maillage 3D Studio (DOS) utilisé par Autodesk 3D Studio. Autodesk 3D Studio est présent sur le marché des formats de fichiers 3D depuis les années 1990 et a maintenant évolué vers 3D Studio MAX pour travailler avec 3D la modélisation, l'animation et le rendu. Un fichier 3DS contient des données pour la représentation 3D de scènes et d'images et est l'un des formats de fichier populaires pour l'importation et l'exportation de données 3D. Il prend en compte des informations telles que les emplacements des caméras, les données de maillage, les informations d'éclairage, les configurations de fenêtres, les données de groupe de lissage, les références bitmap et les attributs pour créer des sommets et des polygones pour le rendu d'une scène.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}
        
    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Autres formats de visionneuse pris en charge" subTitle="À l\'aide de C#, on peut également afficher de nombreux autres formats de fichiers, y compris." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/3mf/" name="3MF" description="3D Format de fabrication" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/amf/" name="AMF" description="Format de fabrication additive" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/ase/" name="ASE" description="Fichier d\'animation 2D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/dae/" name="DAE" description="Échange d\'actifs numériques" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/dxf/" name="DXF" description="Format d\'échange de dessin" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/fbx/" name="FBX" description="Format 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/glb/" name="GLB" description="3D Représentation binaire du fichier" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/gltf/" name="GLTF" description="Format de transmission GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/jt/" name="JT" description="Fichier de tessellation Jupiter" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/obj/" name="OBJ" description="3D Format de fichier" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/ply/" name="PLY" description="Format de fichier polygone" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/rvm/" name="RVM" description="Modèle de conception d\'usine AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/stl/" name="STL" description="Géométrie de surface 3D interchangeable" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/u3d/" name="U3D" description="Universal 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/vrml/" name="VRML" description="Langage de modélisation de réalité virtuelle" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/x/" name="X" description="Image du modèle DirectX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/zip/" name="ZIP" description="ZIP Format d\'archivage" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}