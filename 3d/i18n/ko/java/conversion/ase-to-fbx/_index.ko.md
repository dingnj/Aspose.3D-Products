﻿---
title: Java 를 통해 ASE 에서 FBX 로 변환 
weight: 970
url: /ko/java/conversion/ase-to-fbx/ 
description: ASE 형식의 Java 변환 코드를 FBX 파일로 샘플링합니다. 이 예제 코드를 사용하여 모든 웹 또는 데스크톱 Java 기반 응용 프로그램 내에서 ASE 에서 FBX 로 변환할 수 있습니다.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="Java 를 통해 ASE 에서 FBX 로 변환" h2="3D 모델링 소프트웨어없이 Java 라이브러리를 사용하여 ASE ~ FBX 변환." logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" sourceAdditionalConversionTag="" additionalConversionTag="FBX" pfName="" subTitlepfName="" downloadUrl="" fileiconsmall1="DOCX" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="ASE" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for Java" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.com/templates/aspose/App_Themes/V3/images/3d/272x272/aspose_3d-for-java.png" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/java" installationsDocsLink="https://docs.aspose.com/3d/java" nugetLink="" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/java" learnAsLink="https://docs.aspose.com/3d/java" apiReference="" mavenRepoLink="https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-3d" >}}

{{% blocks/products/pf/agp/content h2="Java 를 사용하여 ASE 에서 FBX 로 변환하는 방법" %}}

 ASE 을 FBX 로 렌더링하려면
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

{{% blocks/products/pf/agp/feature-section-col title="Java 를 통해 ASE 에서 FBX 로 변환하는 단계" %}}

{{% blocks/products/pf/agp/text %}}

 Java 프로그래머는 몇 줄의 코드로 ASE 파일을 FBX 로 쉽게 변환 할 수 있습니다.

{{% /blocks/products/pf/agp/text %}}

1. 장면 클래스의 생성자를 통해 ASE 파일을로드1. FbxSaveOptions 인스턴스 만들기1. 고급 변환을위한 FBX 특정 속성 설정1. 전화 장면. 저장 방법1. FBX 파일 확장자 및 FbxSaveOptions 개체로 출력 경로를 전달합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

{{% blocks/products/pf/agp/text %}}

 Java 변환 코드를 실행하기 전에 다음과 같은 전제 조건이 있는지 확인하십시오.

{{% /blocks/products/pf/agp/text %}}

- Microsoft 창 또는 JSP/JSF 응용 프로그램 및 데스크톱 응용 프로그램에 대한 Java 런타임 환경과 호환되는 OS.- Maven에서 직접 Aspose.3D for Java 의 최신 버전을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="ASE ~ FBX Java 변환 소스 코드" offSpacer="" %}}

```cs
// 장면의 객체에 ASE 로드 
Scene document = new Scene("template.ase");
// FbxSaveOptions 인스턴스 만들기 
FbxSaveOptions options = new FbxSaveOptions();
// ASE 을 FBX 로 저장 
document.save("output.fbx", options);   


```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

{{< blocks/products/pf/agp/demobox sectionTitle="ASE ~ FBX 변환 라이브 데모" sectionDescription="[ASE 에서 FBX 로 변환](https://products.aspose.app/3d/conversion/ase-to-fbx) 라이브 데모 웹 사이트를 방문하여 지금. 라이브 데모에는 다음과 같은 이점이 있습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" Aspose API 을 다운로드할 필요가 없습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 코드를 작성할 필요가 없습니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" ASE 파일을 업로드하면 즉시 FBX 로 변환됩니다." >}}
        {{< blocks/products/pf/agp/democard icon="fa-download" text=" 다운로드 링크를 얻을 수 있습니다." >}}

    {{% blocks/products/pf/agp/content h2="Java 3D 장면 조작 라이브러리" %}}

 Aspose.3D 은 CAD 및 Gameware API 로 3D 파일을 로드, 수정 및 변환합니다. API 는 독립형이며 3D 모델링 또는 렌더링 소프트웨어가 필요하지 않습니다. Discreet3DS, WavefrontOBJ, STL (ASCII, Binary), Universal3D, FBX (ASCII, Binary) 에 API 를 쉽게 사용할 수 있습니다. Collada, glTF, PLY, GLB, DirectX 및 더 많은 형식. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="ASE" readMoreLink="https://docs.fileformat.com/3d/ase/" >}}

ASE 파일은 레이어, 프레임, 팔레트, 태그 및 설정을 포함하는 2D 애니메이션 또는 그래픽입니다.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="FBX" readMoreLink="https://docs.fileformat.com/3d/fbx/" >}}

FBX, filmbox는 원래 kaydara에서 MotionBuilder 용으로 개발 한 인기있는 3D 파일 형식입니다. 2006 년에 Autodesk inc에 의해 인수되었으며 현재 많은 3D 도구에서 사용되는 주요 3D 교환 형식 중 하나입니다. FBX 는 바이너리 및 ASCII 파일 형식으로 모두 사용할 수 있습니다. 이 형식은 디지털 콘텐츠 생성 응용 프로그램 간의 상호 운용성을 제공하기 위해 설정되었습니다. /에서 FBX 파일 형식으로 변환 할 수있는 많은 도구가 있습니다.


        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

{{< /blocks/products/pf/agp/demobox >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="다른 지원되는 변환" subTitle="ASE 을 아래에 나열된 몇 가지를 포함하여 다른 많은 파일 형식으로 변환 할 수도 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-3ds/" name="ASE ~ 3DS" description="3D 스튜디오 도스 메쉬" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-amf/" name="ASE ~ AMF" description="첨가제 제조 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-dae/" name="ASE ~ DAE" description="디지털 자산 교환" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-gltf/" name="ASE ~ GLTF" description="GL 전송 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-html/" name="ASE ~ HTML" description="하이퍼 텍스트 마크 업 언어" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-obj/" name="ASE ~ OBJ" description="3D 파일 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-ply/" name="ASE ~ PLY" description="다각형 파일 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-rvm/" name="ASE ~ RVM" description="AVEVA 식물 디자인 모델" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-stl/" name="ASE ~ STL" description="교환 가능한 3D 표면 기하학" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/java/conversion/ase-to-u3d/" name="ASE ~ U3D" description="Universal 3D" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}