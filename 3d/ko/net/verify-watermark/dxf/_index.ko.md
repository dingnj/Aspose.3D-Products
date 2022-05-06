﻿---
title: .NET을(를) 통해 DXF 파일 형식에 블라인드 워터마크 확인 추가 
weight: 830
url: /ko/net/verify-watermark/dxf/ 
description: C# 소스 코드는 .NET Framework, .NET Core, Mono의 DXF 문서에 블라인드 워터마크 확인을 로드, 렌더링 및 추가합니다.
---
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/i18n/upper-banner h1="C#을(를) 통해 DXF에 블라인드 워터마크 확인 추가" h2="서버 측 API를 사용하여 DXF 파일에 블라인드 워터마크 확인을 추가하려면 고유한 .NET 앱을 빌드하세요." logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="DXF" pfName="Aspose.3D" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="DXF" >}}

{{< blocks/products/pf/main-container pfName="Aspose.3D " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/i18n/sub-menu autoGeneratedVersion="true" logoImageSrc="https://cms.admin.containerize.com/templates/aspose/img/products/3d/aspose_3d-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-3d" liveDemosLink="https://products.aspose.app/3d/family" docsLink="https://docs.aspose.com/3d/net" installationsDocsLink="https://docs.aspose.com/3d/net" nugetLink="https://www.nuget.org/packages/aspose.3d" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/3d/net" learnAsLink="https://docs.aspose.com/3d/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="C#을 사용하여 DXF 파일에 워터마크 확인 방법" %}}

 확인 DXF 파일을 워터마크하기 위해 다음을 사용합니다.
 [Aspose.3D for .NET](https://products.aspose.com/3d/net) 
 API은(는) 워터마크 확인을 추가하는 데 사용할 C# 플랫폼용 API 기능이 풍부하고 강력하며 사용하기 쉽습니다. 열려있는
 [누겟](https://www.nuget.org/packages/aspose.3d) 
 패키지 관리자, 검색
 **Aspose.3D** 
 설치합니다. 패키지 관리자 콘솔에서 다음 명령을 사용할 수도 있습니다.

{{% blocks/products/pf/agp/code-block title="패키지 관리자 콘솔 명령" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.3D


```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="C#을(를) 통해 DXF에 블라인드 워터마크 확인을 추가하는 단계" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D를 사용하면 개발자가 몇 줄의 코드로 블라인드 워터마크 확인을 DXF 파일에 쉽게 추가할 수 있습니다.

{{% /blocks/products/pf/agp/text %}}

- Scene 클래스의 생성자를 통해 DXF 파일 로드- Aspose.3D의 메시 클래스 가져오기- Aspose.3D의 DecodeWatermark 메소드를 사용하여 비밀번호 추가- 개체와 함께 Scene.Save 메서드를 호출합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="시스템 요구 사항" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.3D for .NET은(는) 모든 주요 운영 체제에서 지원됩니다. 다음 전제 조건이 있는지 확인하십시오.

{{% /blocks/products/pf/agp/text %}}

- Microsoft Windows 또는 .NET Framework, .NET Core, Mono 호환 OS- Microsoft Visual Studio와 같은 개발 환경- 프로젝트에서 참조된 Aspose.3D for .NET
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="DXF에 블라인드 워터마크 확인을 추가하는 C# 코드" offSpacer="" %}}

```cs

//확인을 위해 워터마크가 필요한 소스 파일
string file = "template.dxf";

// Scene의 인스턴스 생성
Scene scene = new Scene(file);
string text =null;

//DecodeWatermark 방식으로 워터마크 확인을 위한 비밀번호 추가
try
{
    scene.RootNode.Accept((Node node) =>
    {
        var mesh = node.GetEntity<Mesh>();
        if (mesh != null)
        {
            text = Watermark.DecodeWatermark(mesh, "1234");
            if (text != null)
                return false;
            }
            return true;
    });
}
catch (UnauthorizedAccessException)
{
    return "Password error";
}

//이 파일에 워터마크가 없으면 null을 반환하고, 워터마크가 있으면 워터마크 내용을 반환합니다.
return text;



```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="Aspose.3D for .NET API 정보" %}}

 Aspose.3D은(는) 3D 파일을 로드, 수정 및 변환하는 CAD 및 Gameware API입니다. API는 독립 실행형이며 3D 모델링 또는 렌더링 소프트웨어가 필요하지 않습니다. Discreet3DS, WavefrontOBJ, STL(ASCII, 바이너리), Universal3D, FBX(ASCII, 바이너리), Collada, glTF, PLY, GLB, DirectX 및 기타 형식. 



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

  {{< blocks/products/pf/agp/i18n/demobox-app sectionTitle="DXF에 블라인드 워터마크 인증을 추가하는 무료 앱" sectionDescription="라이브 데모를 확인하려면 [워터마크 확인 DXF](https://products.aspose.app/3d/verify-watermark/dxf) 다음과 같은 혜택이 있습니다." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" 아무것도 다운로드하거나 설정할 필요가 없습니다" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" 코드를 작성하거나 컴파일할 필요가 없습니다." >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" DXF 파일을 업로드하고 \"워터마크\" 버튼을 누르기만 하면 됩니다." >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" 필요한 경우 링크에서 DXF 파일 다운로드" >}}

        {{< blocks/products/pf/agp/i18n/about-file-text fileFormat="DXF" readMoreLink="https://docs.fileformat.com/cad/dxf/" >}}
DXF, 도면 교환 형식 또는 도면 교환 형식은 AutoCAD 도면 파일의 태그가 지정된 데이터 표현입니다. 파일의 각 요소에는 그룹 코드라는 접두어 정수 번호가 있습니다. 이 그룹 코드는 실제로 뒤에 오는 요소를 나타내고 주어진 개체 유형에 대한 데이터 요소의 의미를 나타냅니다. DXF을 사용하면 도면 파일에서 거의 모든 사용자 지정 정보를 표현할 수 있습니다.

        {{< /blocks/products/pf/agp/i18n/about-file-text >}}

    {{< /blocks/products/pf/agp/i18n/demobox-app >}}

{{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="형식에 블라인드 워터마크 확인을 추가하기 위해 지원되는 기타 앱" subTitle="C#을 사용하여 다음을 포함한 많은 다른 파일 형식에 블라인드 워터마크 확인을 추가할 수도 있습니다." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/3mf/" name="3MF" description="3D 제조 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/amf/" name="AMF" description="적층 제조 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/ase/" name="ASE" description="2D 애니메이션 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/dae/" name="DAE" description="디지털 자산 교환" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/3ds/" name="3DS" description="3D Studio 메시 파일 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/drc/" name="DRC" description="Google Draco" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/fbx/" name="FBX" description="3D 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/glb/" name="GLB" description="3D 파일 이진 표현" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/gltf/" name="GLTF" description="GL 전송 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/jt/" name="JT" description="목성 테셀레이션 파일" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/obj/" name="OBJ" description="3D 파일 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/ply/" name="PLY" description="다각형 파일 형식" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/pdf/" name="PDF" description="3D PDF" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/rvm/" name="RVM" description="AVEVA 플랜트 설계 모델" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/stl/" name="STL" description="교체 가능한 3D 표면 기하학" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/u3d/" name="U3D" description="Universal 3D" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/vrml/" name="VRML" description="가상 현실 모델링 언어" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/x/" name="엑스" description="DirectX 모델 이미지" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/usd/" name="USD" description="보편적인 장면 설명" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/3d/net/verify-watermark/usdz/" name="USDZ" description="유니버설 장면 설명 Zip 아카이브" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}