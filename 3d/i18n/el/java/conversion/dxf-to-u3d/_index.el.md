﻿---
title: Μετατροπή DXF σε U3D μέσω Java 
weight: 500
url: /el/java/conversion/dxf-to-u3d/ 
description: Δείγμα Java κώδικα μετατροπής για τη μορφή DXF σε αρχείο U3D. Χρησιμοποιήστε αυτό το παράδειγμα κωδικό για να μετατρέψετε DXF σε U3D μέσα σε οποιαδήποτε εφαρμογή Web ή Επιφάνεια Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Μετατροπή DXF σε U3D μέσω Java" h2="DXF σε U3D μετατροπή με τη χρήση βιβλιοθήκης Java χωρίς λογισμικό μοντελοποίησης 3D." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="U3D" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DXF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="Πώς να μετατρέψετε DXF σε U3D χρησιμοποιώντας Java" %}}

 Για να αναγνωρίσουμε το DXF έως U3D, θα χρησιμοποιήσουμε τα ακόλουθα:
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API πλούσια σε χαρακτηριστικά, ισχυρή και εύκολη στη χρήση πλατφόρμα μετατροπής API for Java. Μπορείτε να κατεβάσετε την τελευταία έκδοσή του απευθείας από την τελευταία έκδοση
 [Μέιβεν](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
 Και να το εγκαταστήσετε μέσα στο Maven-based project σας προσθέτοντας τις παρακάτω διαμορφώσεις στο pom.xml.

{{% blocks/products/pf/agp/code-block title="Χώρος αποθήκευσης" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://Repository.aspose.com/repo/</url>
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

{{% blocks/products/pf/agp/feature-section-col title="Βήματα για τη μετατροπή DXF σε U3D μέσω Java" %}}

{{% blocks/products/pf/agp/text %}}

 Οι προγραμματιστές Java μπορούν εύκολα να μετατρέψουν το DXF αρχείο σε U3D σε λίγες μόνο γραμμές του κώδικα.

{{% /blocks/products/pf/agp/text %}}

1. Φόρτωση αρχείου DXF μέσω του κατασκευαστή της κλάσης σκηνής1. Δημιουργία μιας διάταξης του U3dSaveOptionsName1. Ορισμός συγκεκριμένων ιδιοτήτων U3D για προηγμένη μετατροπή1. Μέθοδος κλήσης Scene.save1. Πέρασε τη διαδρομή εξόδου με επέκταση αρχείου U3D & αντικείμενο του U3dSaveOptionsName
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαιτήσεις συστήματος" %}}

{{% blocks/products/pf/agp/text %}}

 Πριν εκτελέσετε τον κώδικα μετατροπής Java, βεβαιωθείτε ότι έχετε τις ακόλουθες προϋποθέσεις.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows ή ένα συμβατό OS με Java Περιβάλλον εκμετάλλευσης για εφαρμογές JSP/JSF και επιφάνειες εφαρμογές.- Πάρτε την τελευταία έκδοση του Aspose.3D for Java απευθείας από το Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="DXF σε U3D Java Πηγαίος κώδικας μετατροπής" offSpacer="" %}}

```cs
// Φόρτωση του DXF σε ένα αντικείμενο σκηνής 
Scene document = new Scene("template.dxf");
// Δημιουργία μιας διάταξης U3dSaveOptionsName 
U3dSaveOptions options = new U3dSaveOptions();
// Αποθήκευση DXF ως U3D 
document.save("output.u3d", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="DXF σε U3D Ζωντανή μετατροπή" sectionDescription="[Μετατροπή DXF σε U3D](https://products.aspose.app/3d/conversion/dxf-to-u3d) Αυτή τη στιγμή επισκεπτώντας την ιστοσελίδα μας Live Demos.Το live demo έχει τα ακόλουθα οφέλη" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Δεν χρειάζεται λήψη Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" Δεν χρειάζεται να γράφεις κανένα κώδικα." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Απλά ανεβάστε το αρχείο DXF σας, θα μετατραπεί άμεσα σε U3D." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" Θα πάρετε το σύνδεσμο λήψης." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D Βιβλιοθήκη χειραγωγής σκηνής" %}}

 Το Aspose.3D είναι ένα CAD και το λογισμικό API για τη φόρτωση, την τροποποίηση και τη μετατροπή αρχείων 3D. Το API είναι αυτόνομο και δεν απαιτεί κανένα λογισμικό μοντελοποίησης ή αποτύπωσης 3D. Μπορεί κανείς να χρησιμοποιήσει το API για Discreet3DS, WavefrontOBJ, STL (ASCII, δυαδικό), Universal3D, FBX (ASCII, δυαδικό), Collada, glTF, PLY, GLB, DirectX και περισσότερες μορφές. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DXF" readMoreLink="https://docs.fileformat.com/cad/dxf/" >}}

DXF, Σχέδιο Interchange Format, ή σχεδίαση Exchange Format, είναι μια ετικέτα αναπαράσταση δεδομένων του αρχείου σχεδίασης AutoCAD. Κάθε στοιχείο του αρχείου έχει έναν αριθμό ακέραιο πρόθεμα που ονομάζεται κωδικός ομάδας. Αυτός ο κωδικός ομάδας αντιπροσωπεύει το στοιχείο που ακολουθεί και δείχνει την έννοια ενός στοιχείου δεδομένων για έναν συγκεκριμένο τύπο αντικειμένου. Η DXF καθιστά δυνατή την αντιπροσωπεία σχεδόν όλων των πληροφοριών που καθορίζονται από το χρήστη σε ένα αρχείο σχεδίασης. DXF μορφή αρχείου αναπτύχθηκε από την Autodesk ως μορφή αρχείου δεδομένων CAD για τη διαλειτουργικότητα δεδομένων μεταξύ AutoCAD και άλλων εφαρμογών. Έτσι, τα δεδομένα μπορούν να εισαχθούν από άλλες μορφές έως DXF σε AutoCAD σύμφωνα με τις προδιαγραφές διαλειτουργικότητας του μορφού αρχείου DXF.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="U3D" readMoreLink="https://docs.fileformat.com/3d/u3d/" >}}

Το U3D (Universal 3D) είναι μια συμπιεσμένη μορφή αρχείων και δομή δεδομένων για τα γραφικά του 3D. Περιέχει πληροφορίες 3D μοντέλο όπως τριγωνικά πλέγματα, φωτισμός, σκίαση, δεδομένα κίνησης, γραμμές και σημεία με χρώμα και δομή. Η μορφή έγινε δεκτή ως πρότυπο ECMA-363 τον Αύγουστο του 2005. 3D PDF αρχείο υποστηρίζει U3D αντικείμενα ενσωμάτωσης και μπορεί να προβλεφθεί στο Adobe Reader (έκδοση 7 και μετά). Η μορφή U3D αναπτύχθηκε με βάση τον στόχο να καθιερωθεί ένα καθολικό πρότυπο για τρισδιάστατη αποθήκευση και ανταλλαγή δεδομένων. Ωστόσο, η μορφή βρίσκει την κύρια χρήση της στην κωδικοποίηση του 3D PDF αντί να χρησιμοποιείται ως μορφή ανταλλαγής. Το Acrobat 3D μετατρέπει έναν υποστηριζόμενο τύπο αρχείου 3D σε U3D ή PRC μετά τη μετατροπή σε PDF.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Άλλες υποστηριζόμενες μετατροπές" subTitle="Μπορείτε επίσης να μετατρέψετε DXF σε πολλές άλλες μορφές αρχείων, συμπεριλαμβανομένων λίγα που αναφέρονται παρακάτω." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-3ds/" name="DXF έως 3DS" description="3D Μέσα DOS στούντιο" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-amf/" name="DXF έως AMF" description="Πρόσθετη μορφή παραγωγής παραγωγής" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-ase/" name="DXF έως ASE" description="Αρχείο κινούμενων 2D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-dae/" name="DXF έως DAE" description="Ανταλλαγή ψηφιακών περιουσιακών στοιχείων" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-fbx/" name="DXF έως FBX" description="Μορφή 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-gltf/" name="DXF έως GLTF" description="Μορφή μετάδοσης GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-html/" name="DXF έως HTML" description="Γλώσσα σήμανσης Hyper κειμένου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-obj/" name="DXF έως OBJ" description="Μορφή αρχείου 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-ply/" name="DXF έως PLY" description="Μορφή αρχείων Πολυγόνου" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-rvm/" name="DXF έως RVM" description="Σχεδιασμός φυτών AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dxf-to-stl/" name="DXF έως STL" description="Εναλλάξιμο 3D Γεωμετρία επιφάνειας" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}