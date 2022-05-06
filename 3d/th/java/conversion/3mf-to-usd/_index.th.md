﻿---
title: แปลง 3MF เป็น USD ผ่าน Java
weight: 530
url: /th/java/conversion/3mf-to-usd/ 
description: ตัวอย่างโค้ดการแปลง Java สำหรับรูปแบบ 3MF เป็นไฟล์ USD ใช้โค้ดตัวอย่างนี้เพื่อแปลง 3MF เป็น USD ภายในแอปพลิเคชันบนเว็บหรือเดสก์ท็อป Java
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="แปลง 3MF เป็น USD ผ่าน Java" h2="การแปลง 3MF เป็น USD โดยใช้ไลบรารี Java โดยไม่มีซอฟต์แวร์การสร้างแบบจำลอง 3D ใดๆ" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="USD" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="3MF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="วิธีแปลง 3MF เป็น USD โดยใช้ Java" %}}

 เพื่อแสดง 3MF เป็น USD เราจะใช้
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API ซึ่งเป็นแพลตฟอร์มการแปลง API for Java ที่มีคุณลักษณะหลากหลาย มีประสิทธิภาพ และใช้งานง่าย คุณสามารถดาวน์โหลดเวอร์ชันล่าสุดได้โดยตรงจาก
 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
 และติดตั้งภายในโปรเจ็กต์ที่ใช้ Maven โดยเพิ่มการกำหนดค่าต่อไปนี้ใน pom.xml

{{% blocks/products/pf/agp/code-block title="ที่เก็บ" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://repository.aspose.com/repo/</url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="การพึ่งพา" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนในการแปลง 3MF เป็น USD ผ่าน Java" %}}

{{% blocks/products/pf/agp/text %}}

 โปรแกรมเมอร์ Java สามารถแปลงไฟล์ 3MF เป็น USD ได้อย่างง่ายดายด้วยโค้ดเพียงไม่กี่บรรทัด

{{% /blocks/products/pf/agp/text %}}

1. โหลดไฟล์ 3MF ผ่านตัวสร้างของ Scene class1. เรียกเมธอด Scene.save ด้วยรูปแบบของ USD1. ตรวจสอบไฟล์ผลลัพธ์ USD ที่เส้นทางที่ระบุ
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 ก่อนเรียกใช้โค้ด Conversion Java ตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ Java Runtime Environment สำหรับแอปพลิเคชัน JSP/JSF และแอปพลิเคชันเดสก์ท็อป- รับเวอร์ชันล่าสุดของ Aspose.3D for Java โดยตรงจาก Maven
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="3MF ถึง USD Java รหัสแหล่งที่มาของการแปลง" offSpacer="" %}}

```cs
// โหลดซอร์ส 3MF file
Scene scene = new Scene("sourceFile.3mf");
// แปลง 3D ฉากเป็นไฟล์ในรูปแบบ USD
scene.save("output.usd", FileFormat.USD)

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="3MF ถึง USD การสาธิตการแปลงสด" sectionDescription="[แปลง 3MF เป็น USD](https://products.aspose.app/3d/conversion/3mf-to-usd) ตอนนี้โดยไปที่เว็บไซต์ Live Demos ของเรา การสาธิตสดมีประโยชน์ดังต่อไปนี้" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" ไม่จำเป็นต้องดาวน์โหลด Aspose API" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" ไม่จำเป็นต้องเขียนโค้ดใดๆ" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" เพียงอัปโหลดไฟล์ 3MF ของคุณ ไฟล์จะถูกแปลงเป็น USD ทันที" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" คุณจะได้รับลิงค์ดาวน์โหลด" >}}

    {{% blocks/products/pf/agp/content h2="Java 3D ไลบรารีการจัดการฉาก" %}}

 Aspose.3D เป็น CAD และ Gameware API ในการโหลด แก้ไข และแปลงไฟล์ 3D API เป็นแบบสแตนด์อโลนและไม่จำเป็นต้องมี 3D ซอฟต์แวร์สร้างแบบจำลองหรือเรนเดอร์ใดๆ สามารถใช้ API สำหรับ USD, Discreet3DS, WavefrontOBJ, STL (ASCII, Binary), Universal3D, FBX (ASCII, Binary), Collada, glTF, PLY, GLB, DirectX และรูปแบบอื่นๆ 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="3MF" readMoreLink="https://docs.fileformat.com/3d/3mf/" >}}

3MF, 3D รูปแบบการผลิต ถูกใช้โดยแอปพลิเคชันเพื่อแสดงโมเดลอ็อบเจ็กต์ 3D ให้กับแอปพลิเคชัน แพลตฟอร์ม บริการ และเครื่องพิมพ์อื่นๆ ที่หลากหลาย สร้างขึ้นเพื่อหลีกเลี่ยงข้อจำกัดและปัญหาในรูปแบบไฟล์ 3D อื่นๆ เช่น STL สำหรับการทำงานกับเครื่องพิมพ์ 3D เวอร์ชันล่าสุด 3MF ค่อนข้างเป็นรูปแบบไฟล์ใหม่ที่ได้รับการพัฒนาและเผยแพร่โดยกลุ่ม 3MF มีเนื้อหาเพียงพอที่จะอธิบายแบบจำลองได้อย่างเต็มที่ เก็บข้อมูลภายใน สี และคุณลักษณะอื่นๆ ที่ทำให้ขยายได้เพื่อรองรับนวัตกรรมใหม่ในการพิมพ์ 3D รูปแบบนี้ขยายได้ นำไปใช้ในวงกว้างและไม่มีปัญหาที่รุมเร้ารูปแบบไฟล์อื่นๆ ที่ใช้กันอย่างแพร่หลาย

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="USD" readMoreLink="https://docs.fileformat.com/3d/usd/" >}}

ไฟล์ที่มีนามสกุล .usd เป็นรูปแบบไฟล์ Universal Scene Description ที่เข้ารหัสข้อมูลเพื่อวัตถุประสงค์ในการแลกเปลี่ยนข้อมูลและเพิ่มพูนระหว่างแอปพลิเคชันการสร้างเนื้อหาดิจิทัล พัฒนาโดย Pixar USD ให้ความสามารถในการแลกเปลี่ยนเนื้อหาองค์ประกอบ (เช่น โมเดล) หรือแอนิเมชั่น


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/i18n/demobox-app >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="การแปลงอื่น ๆ ที่รองรับ" subTitle="คุณยังสามารถแปลง 3MF เป็นรูปแบบไฟล์อื่นๆ ได้มากมาย รวมถึงบางรูปแบบตามรายการด้านล่าง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-gltf/" name="3MF ถึง GLTF" description="ไฟล์รูปแบบการส่ง GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-glb/" name="3MF ถึง GLB" description="รูปแบบการส่งไบนารี GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-pdf/" name="3MF ถึง PDF" description="รูปแบบเอกสารพกพา" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-fbx/" name="3MF ถึง FBX" description="Autodesk FBX ไฟล์ Interchange" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-stl/" name="3MF ถึง STL" description="ไฟล์ Stereolithography" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-obj/" name="3MF ถึง OBJ" description="Wavefront 3D ไฟล์อ็อบเจ็กต์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-3ds/" name="3MF ถึง 3DS" description="3D ฉากสตูดิโอ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-dae/" name="3MF ถึง DAE" description="ไฟล์การแลกเปลี่ยนสินทรัพย์ดิจิทัล" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-u3d/" name="3MF ถึง U3D" description="Universal 3D ไฟล์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-ply/" name="3MF ถึง PLY" description="รูปแบบไฟล์รูปหลายเหลี่ยม" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-drc/" name="3MF ถึง DRC" description="Google Draco รูปแบบไฟล์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-rvm/" name="3MF ถึง RVM" description="อาวีว่า RVM" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-jt/" name="3MF ถึง JT" description="JT เปิด CAD ไฟล์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-amf/" name="3MF ถึง AMF" description="ไฟล์การผลิตสารเติมแต่ง" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-html/" name="3MF ถึง HTML" description="ภาษามาร์กอัปข้อความไฮเปอร์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-usd/" name="3MF ถึง USD" description="รูปแบบคำอธิบายฉากสากล" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-usdz/" name="3MF ถึง USDZ" description="คำอธิบายฉากสากล รูปแบบซิป" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}