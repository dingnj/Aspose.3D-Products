﻿---
title: Java 를 통해 DAE 에서 PLY 로 변환 
weight: 2930
url: /ko/java/conversion/dae-to-ply/ 
description: DAE 형식의 Java 변환 코드를 PLY 파일로 샘플링합니다. 이 예제 코드를 사용하여 모든 웹 또는 데스크톱 Java 기반 응용 프로그램 내에서 DAE 에서 PLY 로 변환할 수 있습니다.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Java 를 통해 DAE 에서 PLY 로 변환" h2="3D 모델링 소프트웨어없이 Java 라이브러리를 사용하여 DAE ~ PLY 변환." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="PLY" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DAE" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="Java 를 사용하여 DAE 에서 PLY 로 변환하는 방법" %}}

 DAE 을 PLY 로 렌더링하려면
 [Aspose.3D for Java](https://products.aspose.com/3d/java) 
 API 기능이 풍부하고 강력하며 사용하기 쉬운 변환 API for Java 플랫폼입니다. 최신 버전을 직접 다운로드 할 수 있습니다.
 [메이븐](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d) 
 Pom. Xml에 다음 구성을 추가하여 Maven 기반 프로젝트에 설치하십시오.

{{% blocks/products/pf/agp/code-block title="저장소" offSpacer="true" %}}

```cs

<repository>
<id>AsposeJavaAPI</id>
<name>Aspose Java API</name>
<url>https://Repository.aspose.com/repo/ </url>
</repository>


```

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="의존성" offSpacer="true" %}}

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

{{% blocks/products/pf/agp/feature-section-col title="Java 를 통해 DAE 에서 PLY 로 변환하는 단계" %}}

{{% blocks/products/pf/agp/text %}}

 Java 프로그래머는 몇 줄의 코드로 DAE 파일을 PLY 로 쉽게 변환 할 수 있습니다.

{{% /blocks/products/pf/agp/text %}}

1. 장면 클래스의 생성자를 통해 DAE 파일을로드1. PlySaveOptions 인스턴스 만들기1. 고급 변환을위한 PLY 특정 속성 설정1. 전화 장면. 저장 방법1. PLY 파일 확장자 및 PlySaveOptions 객체를 사용하여 출력 경로를 전달합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

{{% blocks/products/pf/agp/text %}}

 Java 변환 코드를 실행하기 전에 다음과 같은 전제 조건이 있는지 확인하십시오.

{{% /blocks/products/pf/agp/text %}}

- Microsoft 창 또는 JSP/JSF 응용 프로그램 및 데스크톱 응용 프로그램에 대한 Java 런타임 환경과 호환되는 OS.- Maven에서 직접 Aspose.3D for Java 의 최신 버전을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="DAE ~ PLY Java 변환 소스 코드" offSpacer="" %}}

```cs
// 장면의 객체에 DAE 로드 
Scene document = new Scene("template.dae");
// PlySaveOptions 인스턴스 만들기 
PlySaveOptions options = new PlySaveOptions();
// DAE 을 PLY 로 저장 
document.save("output.ply", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="DAE ~ PLY 변환 라이브 데모" sectionDescription="[DAE 에서 PLY 로 변환](https://products.aspose.app/3d/conversion/dae-to-ply) 라이브 데모 웹 사이트를 방문하여 지금. 라이브 데모에는 다음과 같은 이점이 있습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API 을 다운로드할 필요가 없습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 코드를 작성할 필요가 없습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" DAE 파일을 업로드하면 즉시 PLY 로 변환됩니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 다운로드 링크를 얻을 수 있습니다." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D 장면 조작 라이브러리" %}}

 Aspose.3D 은 CAD 및 Gameware API 로 3D 파일을 로드, 수정 및 변환합니다. API 는 독립형이며 3D 모델링 또는 렌더링 소프트웨어가 필요하지 않습니다. Discreet3DS, WavefrontOBJ, STL (ASCII, Binary), Universal3D, FBX (ASCII, Binary) 에 API 를 쉽게 사용할 수 있습니다. Collada, glTF, PLY, GLB, DirectX 및 더 많은 형식. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DAE" readMoreLink="https://docs.fileformat.com/3d/dae/" >}}

DAE 파일은 대화형 3D 응용 프로그램간에 데이터를 교환하는 데 사용되는 디지털 자산 교환 파일 형식입니다. 이 파일 형식은 그래픽 소프트웨어 응용 프로그램 간의 디지털 자산 교환을위한 개방형 표준 XML 스키마 인 COLLADA (협업 설계 활동) XML 스키마를 기반으로합니다. 그것은 공개적으로 사용 가능한 사양, ISO/pAS 17506 iso에 의해 채택되었습니다.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="PLY" readMoreLink="https://docs.fileformat.com/3d/ply/" >}}

다각형 파일 형식 PLY 은 다각형 컬렉션으로 설명 된 그래픽 객체를 저장하는 3D 파일 형식을 나타냅니다. 이 파일 형식의 목적은 다양한 모델에 유용 할만큼 일반적으로 간단하고 쉬운 파일 형식을 설정하는 것이 었습니다. PLY 파일 형식은 컴팩트 한 저장 및 신속한 저장 및 로딩을위한 이진 형식뿐만 아니라 ascii로 제공됩니다. 파일 형식은 3D 파일 읽기를 지원하는 다른 응용 프로그램에서 사용됩니다.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="다른 지원되는 변환" subTitle="DAE 을 아래에 나열된 몇 가지를 포함하여 다른 많은 파일 형식으로 변환 할 수도 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-3ds/" name="DAE ~ 3DS" description="3D 스튜디오 도스 메쉬" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-amf/" name="DAE ~ AMF" description="첨가제 제조 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-ase/" name="DAE ~ ASE" description="2D 애니메이션 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-fbx/" name="DAE ~ FBX" description="3D 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-gltf/" name="DAE ~ GLTF" description="GL 전송 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-html/" name="DAE ~ HTML" description="하이퍼 텍스트 마크 업 언어" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-obj/" name="DAE ~ OBJ" description="3D 파일 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-rvm/" name="DAE ~ RVM" description="AVEVA 식물 디자인 모델" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-stl/" name="DAE ~ STL" description="교환 가능한 3D 표면 기하학" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/dae-to-u3d/" name="DAE ~ U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}