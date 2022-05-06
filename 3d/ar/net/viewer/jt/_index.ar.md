﻿---
title: عرض JT تنسيقات الملفات عبر .NET 
weight: 3090
url: /ar/net/viewer/jt/ 
description: C# شفرة المصدر لتحميل وعرض وعرض مستندات JT على .NET Framework ، .NET Core ، Mono.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="JT عارض الملفات for .NET" h2="عرض ملفات JT بدون أي 3D برامج تصميم وعرض." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="JT" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="JT" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="كيفية عرض JT ملف باستخدام C#" %}}

 من أجل عرض ملف JT ، سنستخدم
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API وهو نظام غني بالميزات وقوي وسهل الاستخدام API لمنصة C# ليتم استخدامه مع أي عارض. افتح
 [نوجيت](https://www.nuget.org/packages/aspose.3d) 
 مدير الحزم ، ابحث عن
 ** Aspose.3D ** 
 وتثبيت. يمكنك أيضًا استخدام الأمر التالي من Package Manager Console.

{{% blocks/products/pf/agp/code-block title="أمر وحدة تحكم مدير الحزم" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="خطوات لعرض JT عبر C#" %}}

{{% blocks/products/pf/agp/text %}}

 يسهّل Aspose.3D على المطورين عرض ملف JT ببضعة أسطر من التعليمات البرمجية.

{{% /blocks/products/pf/agp/text %}}

1. تحميل ملف JT عبر منشئ فئة المشهد1. قم بإنشاء مثيل لـ Html5SaveOptions1. قم بتعيين خصائص التنسيق المتقدم1. قم باستدعاء الأسلوب Scene.Save مع كائن Html5SaveOptions1. تحقق من الملف الناتج HTML في المتصفح الافتراضي
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات النظام" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D for .NET مدعوم في جميع أنظمة التشغيل الرئيسية. فقط تأكد من أن لديك المتطلبات الأساسية التالية.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows أو نظام تشغيل متوافق مع .NET Framework ، .NET Core ، Mono- بيئة التطوير مثل Microsoft Visual Studio- تمت الإشارة إلى Aspose.3D for .NET في مشروعك
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# رمز لعرضه JT" offSpacer="" %}}

```cs

string output = System.IO.Path.GetTempPath() + Guid.NewGuid().ToString() + ".html";

// تحميل المشهد JT عبر مثيل المشهد
var scene = new ThreeD.Scene("template.jt");
// إنشاء كائن Html5SaveOptions وتعيين خصائص التنسيق
var options = new ThreeD.Formats.Html5SaveOptions()
{
    // قم بإيقاف تشغيل الشبكة
    ShowGrid = false,
    // قم بإيقاف تشغيل واجهة المستخدم
    ShowUI = false
};

// حفظ 3D المشهد باسم HTML5
scene.Save(output, options);
// تحميل الناتج HTML في المتصفح الافتراضي
System.Diagnostics.Process.Start(output);


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="حول Aspose.3D for .NET API" %}}

 Aspose.3D هو برنامج ألعاب CAD وألعاب API لتحميل وتعديل وتحويل ملفات 3D. API هو برنامج قائم بذاته ولا يتطلب أي 3D برامج عرض أو نماذج. يمكن للمرء بسهولة استخدام API لـ Discreet3DS ، WavefrontOBJ ، STL (ASCII ، ثنائي) ، Universal3D ، FBX (ASCII ، ثنائي) ، Collada ، glTF ، PLY ، GLB و DirectX والمزيد من التنسيقات. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="تطبيق مجاني لعرضه JT" sectionDescription="تحقق من العروض الحية لدينا ل [عرض JT](https://products.aspose.app/3d/viewer/jt) مع الفوائد التالية." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" لا حاجة لتنزيل أو إعداد أي شيء" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" لا حاجة لكتابة أو ترجمة التعليمات البرمجية" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" ما عليك سوى تحميل ملف JT واضغط على الزر \"عرض\"" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" قم بتنزيل ملف JT من الرابط ، إذا لزم الأمر" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="JT" readMoreLink="https://docs.fileformat.com/3d/jt/" >}}
JT (Jupiter Tessellation) هو تنسيق بيانات فعال ومرن يركز على الصناعة ومرن ومعيار ISO 3D تم تطويره بواسطة Siemens PLM Software. تستخدم نطاقات CAD الميكانيكية الخاصة بالفضاء وصناعة السيارات والمعدات الثقيلة JT كأكثر 3D تنسيق مرئي لها. تنسيق JT هو رسم بياني للمشهد يدعم السمات والعقد المحددة CAD. تُستخدم تقنيات الضغط المتطورة لتخزين بيانات الوجه (مثلثات). تم تصميم هذا التنسيق لدعم السمات المرئية ومعلومات المنتج والتصنيع (PMI) والبيانات الوصفية. يوجد دعم جيد للتدفق غير المتزامن للمحتوى. في الصناعات الميكانيكية الثقيلة ، يستخدم المحترفون JT ملفًا في CAD الحلول وبرامج إدارة دورة حياة المنتج (PLM) لفحص هندسة البضائع المعقدة.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="تنسيقات العارض الأخرى المدعومة" subTitle="باستخدام C# ، يمكن للمرء أيضًا عرض العديد من تنسيقات الملفات الأخرى بما في ذلك." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/3ds/" name="3DS" description="3D Studio DOS Mesh" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/3mf/" name="3MF" description="3D تنسيق التصنيع" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/amf/" name="AMF" description="تنسيق التصنيع الإضافي" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/ase/" name="ASE" description="ملف الرسوم المتحركة ثنائي الأبعاد" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/dae/" name="DAE" description="تبادل الأصول الرقمية" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/dxf/" name="DXF" description="تنسيق تبادل الرسم" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/fbx/" name="FBX" description="3D تنسيق" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/glb/" name="GLB" description="3D التمثيل الثنائي للملف" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/gltf/" name="GLTF" description="تنسيق نقل GL" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/obj/" name="OBJ" description="3D تنسيق الملف" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/ply/" name="PLY" description="تنسيق ملف مضلع" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/rvm/" name="RVM" description="نموذج تصميم مصنع AVEVA" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/stl/" name="STL" description="قابلة للتبديل 3D هندسة السطح" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/u3d/" name="U3D" description="Universal 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/vrml/" name="VRML" description="لغة نمذجة الواقع الافتراضي" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/x/" name="X" description="صورة طراز DirectX" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/viewer/zip/" name="ZIP" description="ZIP تنسيق الأرشفة" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}