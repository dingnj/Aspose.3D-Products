﻿---
title: Μετατροπή DRC σε DAE μέσω Java 
url: /el/java/conversion/drc-to-dae/ 
description: Δείγμα κώδικα μετατροπής Java για μορφή DRC σε αρχείο DAE. Χρησιμοποιήστε αυτό το παράδειγμα κώδικα για να μετατρέψετε το DRC σε DAE σε οποιαδήποτε εφαρμογή που βασίζεται στον Ιστό ή στην επιφάνεια εργασίας Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Μετατροπή DRC σε DAE μέσω Java" h2="Μετατροπή DRC σε DAE με χρήση βιβλιοθήκης Java χωρίς λογισμικό μοντελοποίησης 3D." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="DAE" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DRC" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="Πώς να μετατρέψετε το DRC σε DAE χρησιμοποιώντας το Java" %}}

 Για να αποδώσουμε το DRC στο DAE, θα χρησιμοποιήσουμε
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API που είναι μια πλούσια σε χαρακτηριστικά, ισχυρή και εύκολη στη χρήση πλατφόρμα μετατροπής API for Java. Μπορείτε να κατεβάσετε την τελευταία του έκδοση απευθείας από
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
 και εγκαταστήστε το στο έργο σας που βασίζεται στο Maven προσθέτοντας τις ακόλουθες διαμορφώσεις στο pom.xml.

{{% blocks/products/pf/agp/code-block title="Αποθήκη" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Εξάρτηση" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Βήματα για τη μετατροπή DRC σε DAE μέσω Java" %}}

{{% blocks/products/pf/agp/text %}}

 Οι προγραμματιστές Java μπορούν εύκολα να μετατρέψουν το αρχείο DRC σε DAE σε λίγες μόνο γραμμές κώδικα.

{{% /blocks/products/pf/agp/text %}}

1. Φόρτωση αρχείου DRC μέσω του κατασκευαστή της κλάσης Scene1. Δημιουργήστε μια παρουσία του DaeSaveOptions1. Ορίστε DAE συγκεκριμένες ιδιότητες για σύνθετη μετατροπή1. Μέθοδος κλήσης Scene.save1. Περάστε τη διαδρομή εξόδου με την επέκταση αρχείου DAE και το αντικείμενο του DaeSaveOptions
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Προτού εκτελέσετε τον κωδικό μετατροπής Java, βεβαιωθείτε ότι διαθέτετε τις ακόλουθες προϋποθέσεις.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ή συμβατό λειτουργικό σύστημα με Java Runtime Environment για JSP/JSF Application and Desktop Applications.- Λάβετε την τελευταία έκδοση του Aspose.3D for Java απευθείας από τη Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Πηγαίος κώδικας μετατροπής DRC σε DAE Java" offSpacer="" %}}

```cs
// φορτώστε το DRC σε ένα αντικείμενο της σκηνής 
Scene document = new Scene("template.drc");
// δημιουργήστε μια παρουσία του DaeSaveOptions 
AmfSaveOptions options = new DaeSaveOptions();
// αποθήκευση DRC ως DAE 
document.save("output.dae", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="Ζωντανές επιδείξεις μετατροπής DRC σε DAE" sectionDescription="[Μετατροπή DRC σε DAE](https://products.aspose.app/3d/conversion/drc-to-dae) αυτή τη στιγμή, επισκεπτόμενοι τον ιστότοπο Live Demos. Η ζωντανή επίδειξη έχει τα ακόλουθα πλεονεκτήματα" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Δεν χρειάζεται να κάνετε λήψη του Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Δεν χρειάζεται να γράψετε κανέναν κώδικα." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Απλώς μεταφορτώστε το αρχείο σας DRC, θα μετατραπεί αμέσως σε DAE." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Θα λάβετε τον σύνδεσμο λήψης." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Βιβλιοθήκη χειρισμού σκηνής" %}}

 Το Aspose.3D είναι ένα CAD και ένα Gameware API για τη φόρτωση, τροποποίηση και μετατροπή αρχείων 3D. Το API είναι αυτόνομο και δεν απαιτεί κανένα λογισμικό μοντελοποίησης ή απόδοσης 3D. Μπορεί κανείς εύκολα να χρησιμοποιήσει το API για Discreet3DS, WavefrontOBJ, STL (ASCII, Binary), Universal3D, FBX (ASCII, Binary), Collada, glTF, PLY, GLB, DirectX και άλλες μορφές. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DRC" readMoreLink="https://docs.fileformat.com/3d/drc/" >}}

Ένα αρχείο με επέκταση .drc είναι μια συμπιεσμένη μορφή αρχείου 3D που δημιουργήθηκε με τη βιβλιοθήκη Google Draco. Το Google προσφέρει το Draco ως βιβλιοθήκη ανοιχτού κώδικα για τη συμπίεση και την αποσυμπίεση 3D γεωμετρικών ματιών και νέφους σημείων και βελτιώνει την αποθήκευση και τη μετάδοση γραφικών 3D. Κωδικοποιεί τα δεδομένα εισόδου και τα αποθηκεύει ως αρχείο .drc. Στο τέλος λήψης, το API διαβάζει αρχεία .drc και μπορεί να τα εξάγει ως αρχεία PLY ή OBJ. Το συμπιεσμένο αρχείο εξόδου επιτρέπει στους χρήστες να κάνουν λήψη εφαρμογών πιο γρήγορα και να παρέχουν γρήγορη φόρτωση 3D γραφικών στα προγράμματα περιήγησης.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DAE" readMoreLink="https://docs.fileformat.com/3d/dae/" >}}

Ένα αρχείο DAE είναι μια μορφή αρχείου Digital Asset Exchange που χρησιμοποιείται για την ανταλλαγή δεδομένων μεταξύ διαδραστικών εφαρμογών 3D. Αυτή η μορφή αρχείου βασίζεται στο σχήμα XML COLLADA (COLLAborative Design Activity), το οποίο είναι ένα ανοιχτό πρότυπο σχήμα XML για την ανταλλαγή ψηφιακών στοιχείων μεταξύ εφαρμογών λογισμικού γραφικών. Έχει υιοθετηθεί από τον ISO ως δημόσια διαθέσιμη προδιαγραφή, ISO/pAS 17506.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->



{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}