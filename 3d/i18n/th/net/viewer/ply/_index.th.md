﻿---
title: ดู PLY รูปแบบไฟล์ผ่าน .NET 
weight: 3140
url: /th/net/viewer/ply/ 
description: C# รหัสต้นฉบับในการโหลดแสดงผลและแสดงเอกสาร PLY ในกรอบ .NET, .NET Core, Mono
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="PLY File Viewer for .NET" h2="Render PLY ไฟล์โดยไม่ต้องใดๆ 3D การสร้างแบบจำลองและการแสดงผลซอฟแวร์" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="PLY" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PLY" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="วิธีการดู PLY การใช้ไฟล์ C#" %}}

 เพื่อดู PLY แฟ้มเราจะใช้
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API ซึ่งเป็นคุณลักษณะที่อุดมไปด้วยที่มีประสิทธิภาพและใช้งานง่าย API สำหรับ C# แพลตฟอร์มที่จะใช้กับผู้ชมใดๆเปิด
 [Nuget](https://www.nuget.org/packages/aspose.3d) 
 ผู้จัดการแพคเกจค้นหา
 **Aspose.3D** 
 และติดตั้งนอกจากนี้คุณยังสามารถใช้คำสั่งต่อไปนี้จากคอนโซลผู้จัดการแพคเกจ

{{% blocks/products/pf/agp/code-block title="ผู้จัดการแพคเกจคำสั่งคอนโซล" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="ขั้นตอนในการดู PLY ผ่าน C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D ทำให้นักพัฒนาซอฟต์แวร์สามารถดูไฟล์ PLY ได้ง่ายโดยใช้โค้ดเพียงไม่กี่บรรทัด

{{% /blocks/products/pf/agp/text %}}

1. โหลด PLY ไฟล์ผ่านตัวสร้างชั้นฉาก1. สร้างอินสแตนซ์ของ Html5SaveOptions1. ตั้งค่าคุณสมบัติสำหรับการจัดรูปแบบขั้นสูง1. เรียกฉากบันทึกวิธีการด้วยวัตถุ Html5SaveOptions1. ตรวจสอบผล HTML ไฟล์ในเบราว์เซอร์เริ่มต้น
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="ความต้องการของระบบ" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D for .NET ได้รับการสนับสนุนบนระบบปฏิบัติการที่สำคัญทั้งหมดเพียงตรวจสอบให้แน่ใจว่าคุณมีข้อกำหนดเบื้องต้นดังต่อไปนี้

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows หรือระบบปฏิบัติการที่เข้ากันได้กับ .NET Framework, .NET Core, Mono- สภาพแวดล้อมการพัฒนาเช่น Microsoft Visual Studio- Aspose.3D for .NET อ้างอิงในโครงการของคุณ
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# Code to view PLY" offSpacer="" %}}

```cs

string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// โหลด PLY ฉากผ่านอินสแตนซ์ของฉาก
var scene = new ThreeD.Scene("template.ply");
// สร้างวัตถุของ Html5SaveOptions และกำหนดคุณสมบัติสำหรับการจัดรูปแบบ
var options = new ThreeD.Formats.Html5SaveOptions()
{
    // ปิดตาราง
    ShowGrid = false,
    // ปิดส่วนติดต่อผู้ใช้
    ShowUI = false
};

// บันทึก 3D ฉากเป็น HTML5
scene.Save(output, options);
// โหลดผลลัพธ์ HTML ในเบราว์เซอร์เริ่มต้น
System.Diagnostics.Process.Start(output);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="About Aspose.3D for .NET API" %}}

 Aspose.3D เป็น CAD และ gameware API ในการโหลดแก้ไขและแปลง 3D ไฟล์ API เป็นแบบสแตนด์อโลนและไม่ต้องใช้ใดๆ 3D การสร้างแบบจำลองหรือซอฟต์แวร์การแสดงผลหนึ่งสามารถใช้ API สำหรับ Discreet3DS, WavefrontOBJ, STL (ASCII, binary), Universal3D, FBX (ASCII, binary), Collada, glTF, PLY, GLB, DirectX และรูปแบบอื่นๆ 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="App ฟรีเพื่อดู PLY" sectionDescription="ตรวจสอบการสาธิตสดของเราเพื่อ [View PLY](https://products.aspose.app/3d/viewer/ply) ที่มีประโยชน์ดังต่อไปนี้" >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" ไม่จำเป็นต้องดาวน์โหลดหรือตั้งค่าอะไร" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" ไม่จำเป็นต้องเขียนหรือรวบรวมรหัส" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" เพียงแค่อัปโหลดไฟล์ PLY และกดปุ่ม \"มุมมอง\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" ดาวน์โหลดไฟล์ PLY จากลิงก์ถ้าจำเป็น" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PLY" readMoreLink="https://docs.fileformat.com/3d/ply/" >}}
PLY, รูปแบบไฟล์รูปหลายเหลี่ยมหมายถึงรูปแบบไฟล์ 3D ที่จัดเก็บวัตถุกราฟิกที่อธิบายว่าเป็นชุดของรูปหลายเหลี่ยมวัตถุประสงค์ของรูปแบบไฟล์นี้คือการสร้างประเภทไฟล์ที่ง่ายและง่ายซึ่งโดยทั่วไปเพียงพอที่จะเป็นประโยชน์สำหรับรูปแบบต่างๆ PLY รูปแบบไฟล์มาเป็น ASCII เช่นเดียวกับรูปแบบไบนารีสำหรับการเก็บรักษาที่มีขนาดกะทัดรัดและสำหรับการประหยัดและการโหลดอย่างรวดเร็วรูปแบบไฟล์ถูกใช้โดยการใช้งานที่แตกต่างกันซึ่งให้การสนับสนุนการอ่านไฟล์ 3D

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="รูปแบบอื่นๆที่สนับสนุน Viewer" subTitle="ใช้ C# หนึ่งยังสามารถดูรูปแบบไฟล์อื่นๆอีกมากมายรวมทั้ง" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/3ds/" name="3DS" description="3D Studio DOS Mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/3mf/" name="3MF" description="3D รูปแบบการผลิต" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/amf/" name="AMF" description="รูปแบบการผลิตสารเติมแต่ง" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/ase/" name="ASE" description="วิธีด้วย.2D ไฟล์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/dae/" name="DAE" description="การแลกเปลี่ยนสินทรัพย์ดิจิทัล" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/dxf/" name="DXF" description="รูปแบบการแลกเปลี่ยนการวาดภาพ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/fbx/" name="FBX" description="3D รูปแบบ" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/glb/" name="GLB" description="3D แสดงไบนารีไฟล์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/gltf/" name="GLTF" description="รูปแบบการส่ง GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/jt/" name="JT" description="วิธีด้วย.kgm ไฟล์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/obj/" name="OBJ" description="3D รูปแบบไฟล์" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/rvm/" name="RVM" description="Aveva รุ่น Plant Design" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/stl/" name="STL" description="เปลี่ยนได้ 3D เรขาคณิตพื้นผิว" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/u3d/" name="U3D" description="Universal 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/vrml/" name="VRML" description="ภาษาการสร้างแบบจำลองความเป็นจริงเสมือนจริง" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/x/" name="X" description="ภาพรุ่น DirectX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/zip/" name="ZIP" description="ZIP รูปแบบการจัดเก็บ" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}