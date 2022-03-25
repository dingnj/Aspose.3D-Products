﻿---
title: Convertir PDF en DAE via Java 
url: /fr/java/conversion/pdf-to-dae/ 
description: Exemple de code de conversion Java pour le format PDF en fichier DAE. Utilisez cet exemple de code pour convertir PDF en DAE dans n'importe quelle application Web ou Desktop Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Convertir PDF en DAE via Java" h2="PDF à DAE conversion à l\'aide de la bibliothèque Java sans logiciel de modélisation 3D." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="DAE" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PDF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="Comment convertir PDF en DAE en utilisant Java" %}}

 Pour rendre PDF à DAE, nous utiliserons
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API qui est une plate-forme de conversion API for Java, puissante et facile à utiliser. Vous pouvez télécharger sa dernière version directement à partir de
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
 Et installez-le dans votre projet basé sur Maven en ajoutant les configurations suivantes au pom.xml.

{{% blocks/products/pf/agp/code-block title="Répositoire" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://Repository.aspose.com/repo/ </url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Dépendance" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Étapes pour convertir PDF en DAE via Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java les programmeurs peuvent facilement convertir PDF fichier en DAE en seulement quelques lignes de code.

{{% /blocks/products/pf/agp/text %}}

1. Charger le fichier PDF via le constructeur de la classe Scène1. Créer une instance de DaeSaveOptions1. Définir des propriétés spécifiques DAE pour une conversion avancée1. Call Scene.save méthode1. Passer le chemin de sortie avec DAE extension de fichier et objet de DaeSaveOptions
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences du système" %}}

{{% blocks/products/pf/agp/text %}}

 Avant d'exécuter le code de conversion Java, assurez-vous que vous avez les conditions préalables suivantes.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ou un système d'exploitation compatible avec Java environnement d'exécution pour les applications JSP/JSF et les applications de bureau.- Obtenez la dernière version de Aspose.3D for Java directement de Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PDF à DAE Java Code source de conversion" offSpacer="" %}}

```cs
// Charger le PDF dans un objet de la scène 
Scene document = new Scene("template.pdf");
// Créer une instance de DaeSaveOptions 
AmfSaveOptions options = new DaeSaveOptions();
// Enregistrer PDF en tant que DAE 
document.save("output.dae", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="PDF en DAE Démos en direct de conversion" sectionDescription="[Convertir PDF en DAE](https://products.aspose.app/3d/conversion/pdf-to-dae) En ce moment en visitant notre site Web Live Demos. La démo en direct présente les avantages suivants" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Pas besoin de télécharger Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Pas besoin d\'écrire un code." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Téléchargez simplement votre fichier PDF, il sera converti instantanément en DAE." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Vous obtiendrez le lien de téléchargement." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Bibliothèque de manipulation de scène" %}}

 Aspose.3D est un CAD et Gameware API pour charger, modifier et convertir des fichiers 3D. API est autonome et ne nécessite aucun logiciel de modélisation ou de rendu de 3D. On peut facilement utiliser API pour Discreet3DS, WavefrontOBJ, STL (ASCII, Binaire), Universal3D, FBX (ASCII, Binaire), Collada, glTF, PLY, GLB, DirectX et plusieurs formats. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/view/pdf/" >}}

Le format de document portable (PDF) est un type de document créé par Adobe dans les années 1990. Le but de ce format de fichier était d'introduire une norme pour la représentation des documents et autres documents de référence dans un format indépendant des logiciels d'application, du matériel ainsi que du système d'exploitation. PDF fichiers peuvent être ouverts dans Adobe Acrobat Reader/Writer ainsi que dans la plupart des navigateurs modernes comme Chrome, Safari, Firefox via des extensions/plug-ins. La plupart des suites logicielles disponibles dans le commerce offrent également la conversion de leurs documents au format de fichier PDF sans avoir besoin d'un composant logiciel supplémentaire. Ainsi, le format de fichier PDF a la pleine capacité de contenir des informations telles que du texte, des images, des hyperliens, des champs de formulaire, des médias riches, des signatures numériques, des pièces jointes, des métadonnées, des fonctionnalités géospatiales et 3D des objets qui peuvent faire partie de document source.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DAE" readMoreLink="https://docs.fileformat.com/3d/dae/" >}}

Un fichier DAE est un format de fichier Digital Asset Exchange qui est utilisé pour échanger des données entre des applications interactives 3D. Ce format de fichier est basé sur le schéma XML COLLADA (COLLAaborative Design Activity) qui est un schéma XML standard ouvert pour l'échange d'actifs numériques entre les applications de logiciels graphiques. Il a été adopté par l'ISO en tant que spécification accessible au public, ISO/pAS 17506.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->


{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}