﻿---
title: تحويل PDF إلى U3D عبر Java 
url: /ar/java/conversion/pdf-to-u3d/ 
description: نموذج Java من رمز التحويل لتنسيق PDF إلى ملف U3D. استخدم رمز المثال هذا لتحويل PDF إلى U3D داخل أي تطبيق ويب أو سطح المكتب Java.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="تحويل PDF إلى U3D عبر Java" h2="PDF إلى U3D التحويل باستخدام Java مكتبة بدون أي برنامج نمذجة 3D." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="U3D" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="PDF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="كيفية تحويل PDF إلى U3D باستخدام Java" %}}

 من أجل تقديم PDF إلى U3D ، سنستخدم
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API وهي عبارة عن نظام تحويل غني بالميزات وقوي وسهل الاستخدام API for Java. يمكنك تحميل أحدث إصدار لها مباشرة من
 [مافن](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
 وقم بتثبيته داخل مشروعك القائم على Maven عن طريق إضافة التكوينات التالية إلى pom.xml.

{{% blocks/products/pf/agp/code-block title="مستودع" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://Repository.aspose.com/repo/ </url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="التبعية" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="خطوات تحويل PDF إلى U3D عبر Java" %}}

{{% blocks/products/pf/agp/text %}}

 Java يمكن للمبرمجين تحويل PDF بسهولة إلى U3D في بضعة أسطر من التعليمات البرمجية.

{{% /blocks/products/pf/agp/text %}}

1. تحميل PDF الملف عبر مُنشئ فئة المشهد1. إنشاء مثيل لـ U3dSaveOptions1. تعيين U3D خصائص محددة للتحويل المتقدم1. استدعاء المشهد. طريقة حفظ1. اجتياز مسار الإخراج مع امتداد الملف U3D والكائن U3dSaveOptions
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="متطلبات النظام" %}}

{{% blocks/products/pf/agp/text %}}

 قبل تشغيل Java رمز التحويل ، تأكد من أن لديك المتطلبات الأساسية التالية.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows أو نظام تشغيل متوافق مع Java بيئة وقت التشغيل لتطبيق JSP/JSF وتطبيقات سطح المكتب.- احصل على أحدث إصدار من Aspose.3D for Java مباشرةً من Maven.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PDF إلى U3D Java رمز مصدر التحويل" offSpacer="" %}}

```cs
// تحميل PDF في كائن من المشهد 
Scene document = new Scene("template.pdf");
// إنشاء مثيل لـ U3dSaveOptions 
AmfSaveOptions options = new U3dSaveOptions();
// احفظ PDF كU3D 
document.save("output.u3d", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="PDF إلى U3D تحويل العروض التوضيحية المباشرة" sectionDescription="[تحويل PDF إلى U3D](https://products.aspose.app/3d/conversion/pdf-to-u3d) الآن من خلال زيارة موقع Live Demos الإلكتروني. يحتوي العرض التوضيحي المباشر على الفوائد التالية" >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" لا حاجة لتنزيل Aspose API." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" لا حاجة لكتابة أي رمز." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" ما عليك سوى تحميل ملف PDF ، وسيتم تحويله على الفور إلى U3D." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" سوف تحصل على رابط التحميل." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D مكتبة التلاعب بالمشهد" %}}

 Aspose.3D هو CAD و Gameweware API لتحميل وتعديل وتحويل 3D من الملفات. API مستقل ولا يتطلب أي برنامج نمذجة أو عرض 3D. يمكن للمرء بسهولة استخدام API لـ Discreet3DS ، WavefrontOBJ ، STL (ASCII ، ثنائي) ، Universal3D ، FBX (ASCII ، ثنائي) ، Collada ، glTF ، PLY ، GLB ، DirectX والمزيد من التنسيقات. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PDF" readMoreLink="https://docs.fileformat.com/view/pdf/" >}}

تنسيق المستندات المحمولة (PDF) هو نوع من المستندات تم إنشاؤه بواسطة Adobe في التسعينيات. كان الغرض من تنسيق الملف هذا هو تقديم معيار لتمثيل المستندات والمواد المرجعية الأخرى بتنسيق مستقل عن برامج التطبيقات والأجهزة وكذلك نظام التشغيل. PDF يمكن فتح ملفات في Adobe Acrobat Reader/Writer أيضًا في معظم المتصفحات الحديثة مثل Chrome و Safari و Firefox عبر الإضافات/المكونات الإضافية. تقدم معظم أجنحة البرامج المتاحة تجاريًا أيضًا تحويل مستنداتها إلى تنسيق ملف PDF دون الحاجة إلى أي مكون برنامج إضافي. وبالتالي ، فإن تنسيق الملف PDF لديه القدرة الكاملة على احتواء معلومات مثل النصوص والصور والارتباطات التشعبية وحقول النموذج والوسائط الغنية والتوقيعات الرقمية والمرفقات والبيانات الوصفية والميزات الجغرافية المكانية و 3D الكائنات الموجودة فيه والتي يمكن أن تصبح جزءًا من مستند المصدر.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="U3D" readMoreLink="https://docs.fileformat.com/3d/u3d/" >}}

U3D (Universal 3D) هو تنسيق ملف مضغوط وبنية بيانات لـ 3D رسومات الكمبيوتر. يحتوي على 3D من معلومات النموذج مثل شبكات المثلث والإضاءة والتظليل وبيانات الحركة والخطوط والنقاط ذات اللون والبنية. تم قبول الشكل كمعيار ECMA-363 في أغسطس 2005. تدعم 3D PDF مستندات U3D كائنات التضمين ويمكن عرضها في Adobe Reader (الإصدار 7 وما بعده). تم تطوير تنسيق U3D مع مراعاة الهدف المتمثل في إنشاء معيار عالمي لتخزين البيانات ثلاثية الأبعاد وتبادلها. ومع ذلك ، يجد التنسيق استخدامه الرئيسي في ترميز 3D PDF بدلاً من استخدامه كتنسيق تبادل. يقوم Acrobat 3D بتحويل نوع ملف مدعوم إلى 3D إما U3D أو PRC عند التحويل إلى PDF.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->


{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}