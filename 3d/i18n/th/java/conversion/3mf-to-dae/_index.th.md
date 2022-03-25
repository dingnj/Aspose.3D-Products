﻿---
title: แปลง 3MF TO DAE Via Java 
weight: 1650
url: /th/java/conversion/3mf-to-dae/ 
description: ตัวอย่าง Java รหัสการแปลงสำหรับ 3MF รูปแบบเป็น DAE ไฟล์ใช้โค้ดตัวอย่างนี้เพื่อแปลง 3MF เป็น DAE ภายในเว็บหรือเดสก์ท็อป Java
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="แปลง 3MF TO DAE Via Java" h2="3MF ถึง DAE การแปลงโดยใช้ไลบรารี Java โดยไม่มีซอฟต์แวร์แบบจำลอง 3D" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="DAE" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="3MF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="How to convert 3MF TO DAE การใช้ Java" %}}

 เพื่อแสดงผล 3MF ถึง DAE เราจะใช้
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API ซึ่งเป็นคุณลักษณะที่อุดมไปด้วยที่มีประสิทธิภาพและง่ายต่อการใช้การแปลง API for Java แพลตฟอร์มคุณสามารถดาวน์โหลดเวอร์ชันล่าสุดได้โดยตรงจาก
 [MAVEN](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
 และติดตั้งภายในโครงการ MAVEN ของคุณโดยการเพิ่มการกำหนดค่าต่อไปนี้ไปยัง POM.XML.

{{% blocks/products/pf/agp/code-block title="พื้นที่เก็บข้อมูล" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://Repository.aspose.com/repo/ </URL>
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

{{% blocks/products/pf/agp/feature-section-col title="Steps TO convert 3MF TO DAE Via Java [ตัวอย่าง]" %}}

{{% blocks/products/pf/agp/text %}}

 Java โปรแกรมเมอร์สามารถแปลง 3MF ไฟล์เป็น DAE ในเพียงไม่กี่บรรทัดของรหัส

{{% /blocks/products/pf/agp/text %}}

1. โหลด 3MF ไฟล์ผ่านตัวสร้างชั้นฉาก1. สร้างอินสแตนซ์ของ daesaveoptions1. ตั้งค่า DAE คุณสมบัติเฉพาะสำหรับการแปลงขั้นสูง1. ฉากโทร.บันทึกวิธีการ1. ผ่านเส้นทางเอาต์พุตด้วย DAE นามสกุลไฟล์และวัตถุของ daesaveoptions
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 ก่อนที่จะใช้รหัสการแปลง Java โปรดตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับสภาพแวดล้อมรันไทม์ Java สำหรับแอพพลิเคชัน JSP/JSF และแอพพลิเคชันเดสก์ท็อป- รับเวอร์ชั่นล่าสุด Aspose.3D for Java โดยตรงจาก MAVEN
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="3MF ถึง DAE Java รหัสแหล่งที่มาของการแปลง" offSpacer="" %}}

```cs
// โหลด 3MF ในวัตถุของฉาก 
Scene document = new Scene("template.3mf");
// สร้างอินสแตนซ์ของ daesaveoptions 
DaeSaveOptions options = new DaeSaveOptions();
// บันทึก 3MF เป็น DAE 
document.save("output.dae", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="3MF TO DAE Conversion การสาธิตสด" sectionDescription="[แปลง 3MF TO DAE](https://products.aspose.app/3d/conversion/3mf-to-dae) ขณะนี้โดยการเยี่ยมชมเว็บไซต์สาธิตสดของเราการสาธิตสดมีประโยชน์ดังต่อไปนี้" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" ไม่จำเป็นต้องดาวน์โหลด Aspose API" >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" ไม่ต้องเขียนโค้ดใดๆ" >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" เพียงแค่อัปโหลดไฟล์ 3MF ของคุณก็จะถูกแปลงทันทีเป็น DAE" >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" คุณจะได้รับลิงค์ดาวน์โหลด" >}}

    {{% blocks/products/pf/agp/content h2="Java 3D ห้องสมุดการจัดการฉาก" %}}

 Aspose.3D เป็น CAD และ gameware API ในการโหลดแก้ไขและแปลง 3D ไฟล์ API เป็นแบบสแตนด์อโลนและไม่ต้องใช้ใดๆ 3D การสร้างแบบจำลองหรือซอฟต์แวร์การแสดงผลหนึ่งสามารถใช้ API สำหรับ Discreet3DS, WavefrontOBJ, STL (ASCII, binary), Universal3D, FBX (ASCII, binary), Collada, glTF, PLY, GLB, DirectX และรูปแบบอื่นๆ 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="3MF" readMoreLink="https://docs.fileformat.com/3d/3mf/" >}}

3MF, 3D รูปแบบการผลิตถูกใช้โดยแอพพลิเคชั่นเพื่อแสดงผลโมเดลวัตถุ 3D ไปยังแอพพลิเคชั่นอื่นๆแพลตฟอร์มบริการและเครื่องพิมพ์มันถูกสร้างขึ้นเพื่อหลีกเลี่ยงข้อจำกัดและปัญหาในรูปแบบไฟล์ 3D อื่นๆเช่น STL สำหรับการทำงานกับเครื่องพิมพ์รุ่นล่าสุด 3D 3MF เป็นรูปแบบไฟล์ใหม่ที่ได้รับการพัฒนาและเผยแพร่โดยกลุ่ม 3MF มันอุดมไปด้วยพอที่จะอธิบายรูปแบบการรักษาข้อมูลภายในสีและลักษณะอื่นๆที่ทำให้สามารถขยายได้สำหรับการสนับสนุนนวัตกรรมใหม่ๆในการพิมพ์ 3D รูปแบบนี้สามารถขยายได้สามารถนำมาใช้อย่างกว้างขวางและไม่มีปัญหาในการตั้งค่ารูปแบบไฟล์ที่ใช้กันอย่างแพร่หลายอื่นๆ


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DAE" readMoreLink="https://docs.fileformat.com/3d/dae/" >}}

ไฟล์ DAE เป็นรูปแบบไฟล์แลกเปลี่ยนสินทรัพย์ดิจิทัลที่ใช้สำหรับการแลกเปลี่ยนข้อมูลระหว่างแอพพลิเคชัน Interactive 3D รูปแบบไฟล์นี้จะขึ้นอยู่กับ collada (collada Design activity) XML Schema ซึ่งเป็นรูปแบบ XML มาตรฐานแบบเปิดสำหรับการแลกเปลี่ยนสินทรัพย์ดิจิทัลระหว่างแอพพลิเคชันซอฟต์แวร์กราฟิกได้รับการรับรองโดย ISO เป็นข้อกำหนดที่เปิดเผยต่อสาธารณชน ISO/PAS 17506.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="การแปลงที่สนับสนุนอื่นๆ" subTitle="3MF ลงในรูปแบบไฟล์อื่นๆอีกมากมายรวมทั้งไม่กี่รายการด้านล่าง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-3ds/" name="3MF TO 3DS" description="3D Studio DOS Mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-amf/" name="3MF TO AMF" description="รูปแบบการผลิตสารเติมแต่ง" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-fbx/" name="3MF TO FBX" description="3D รูปแบบ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-gltf/" name="3MF TO GLTF" description="รูปแบบการส่ง GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-html/" name="3MF TO HTML" description="ภาษามาร์กอัปข้อความไฮเปอร์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-obj/" name="3MF TO OBJ" description="3D รูปแบบไฟล์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-ply/" name="3MF TO PLY" description="รูปแบบไฟล์รูปหลายเหลี่ยม" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-rvm/" name="3MF TO RVM" description="Aveva รุ่น Plant Design" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-stl/" name="3MF TO STL" description="เปลี่ยนได้ 3D เรขาคณิตพื้นผิว" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/3mf-to-u3d/" name="3MF TO U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}