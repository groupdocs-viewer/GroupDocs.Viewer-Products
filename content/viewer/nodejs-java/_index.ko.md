---
############################# Static ############################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: ko
product: "Viewer"
product_tag: "viewer"
platform: "Node.js via Java"
platform_tag: "nodejs-java"

############################# Drop-down ############################
supported_platforms:
  items:
    # supported_platforms loop
    - title: ".NET"
      tag: "net"
    # supported_platforms loop
    - title: "Java"
      tag: "java"
    # supported_platforms loop
    - title: "Node.js"
      tag: "nodejs-java" 


############################# Head ############################
head_title: "PDF Word Excel HTML 이미지 및 이메일용 Node.js 문서 뷰어 API"
head_description: "Node.js 문서 뷰어 및 파일 렌더링 API. JavaScript 애플리케이션에 PDF 뷰어, Word 뷰어, Excel 뷰어, 이미지 뷰어, HTML 뷰어, 이메일 뷰어를 추가합니다."

############################# Header ############################
title: "문서를 렌더링하고 표시하는 Node.js API"
description: "180개 이상의 파일 형식을 지원하는 다중 형식 문서를 기본적으로 렌더링, 보기 및 조작하는 JavaScript 애플리케이션을 개발하기 위한 문서 뷰어 라이브러리입니다."
words:
  for: "for"

actions:
  main: "무료 NPM 다운로드"
  main_link: "https://www.npmjs.com/package/@groupdocs/groupdocs.viewer"
  alt: "라이선스"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/nodejs-java"
  title: "시작할 준비가 되셨나요?"
  description: "GroupDocs.Viewer 기능을 무료로 사용해 보거나 라이선스를 요청하세요"

release:
  title: "버전 {0} 출시됨"
  notes: "새로운 소식 보기"
  downloads: "다운로드"
  link: "https://releases.groupdocs.com/viewer/nodejs-java/release-notes/latest/"

code:
  title: "JavaScript로 PDF 파일 렌더링"
  more: "더 많은 예시"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Node.js-via-Java"
  install: "npm i @groupdocs/groupdocs.viewer"
  content: |
    ```javascript {style=abap}       
    // 출력 HTML 옵션 설정(페이지당 파일 1개)
    const viewOptions = HtmlViewOptions.forEmbeddedResources()
    
    // 인스턴스화 뷰어
    const viewer = new Viewer("resume.pdf")

    // 포함된 리소스를 사용하여 PDF를 HTML로 렌더링
    viewer.view(viewOptions)
    viewer.close()
    ```
############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Viewer 개요"
  description: "Node.js 애플리케이션에서 문서, 슬라이드, 다이어그램 및 기타 다양한 문서 유형을 렌더링, 표시, 변환하는 API"
  features:
    # feature loop
    - title: "효율적이고 안정적으로 문서 보기"
      content: "GroupDocs.Viewer API를 사용하면 콘텐츠와 문서 구조 무결성을 유지하면서 유연하고 강력한 옵션을 사용하여 지원 가능한 모든 형식의 문서를 HTML, JPEG, PNG 및 PDF로 효율적으로 렌더링할 수 있습니다. Node.js용 GroupDocs.Viewer는 Windows 및 Linux 플랫폼에서 작동합니다."

    # feature loop
    - title: "가장 널리 사용되는 파일 및 문서 형식이 지원됩니다."
      content: "우리는 Word, Excel, PDF, PowerPoint, OpenDocument 형식 제품군, 아카이브, 래스터 및 벡터 이미지, 전자책, 프로그래밍 언어 및 마크업, 암호화된 파일을 포함한 기타 다양한 파일 형식을 포함하는 180개 이상의 가장 널리 사용되는 파일 및 문서 형식의 렌더링을 지원합니다. 비밀번호로 보호된 파일."

    # feature loop
    - title: "맞춤형 출력"
      content: "GroupDocs.Viewer를 사용하면 문서를 렌더링할 수 있을 뿐만 아니라 문서의 어느 부분을 정확히 렌더링해야 하는지, 렌더링해야 하는지, 어떻게 렌더링해야 하는지 제어하고 렌더링된 출력에 다양한 변환을 적용할 수 있습니다."

############################# Platforms ############################
platforms:
  enable: true
  title: "플랫폼 독립성"
  description: "Node.js용 GroupDocs.Viewer는 다음 운영 체제, 프레임워크 및 패키지 관리자를 지원합니다."
  items:
    # platform loop
    - title: "Amazon"
      image: "amazon"
    # platform loop
    - title: "Docker"
      image: "docker"
    # platform loop
    - title: "Azure"
      image: "azure"
    # platform loop
    - title: "Eclipse"
      image: "eclipse"
    # platform loop
    - title: "IntelliJ"
      image: "intellij"
    # platform loop
    - title: "Windows"
      image: "windows"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "NPM"
      image: "npm"

############################# File formats ############################
formats:
  enable: true
  title: "지원되는 파일 형식"
  description: |
    Java를 통한 Node.js용 GroupDocs.Viewer는 다음 [파일 형식](https://docs.groupdocs.com/viewer/nodejs-java/supported-document-formats/)을 사용한 작업을 지원합니다.
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office, OpenDocument 및 텍스트 형식
        * **Word:** DOC, DOCX, DOCM, DOT, DOTX, DOTM, RTF, TXT
        * **Excel:** XLS, XLSX, XLSM, XLSB, XLTM, XLT, XLTM, XLTX
        * **PowerPoint:** PPT, PPTX, PPS, PPSX, PPSM, POT, POTM, POTX, PPTM        
        * **Project:** MPP, MPT, MPX
        * **Outlook:** MSG, EML, EMLX, PST, OST
        * **OneNote:** ONE
        * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG
        * **Fixed Page Layout:** PDF, TEX, XPS, OXPS
        * **e-Books:** EPUB, MOBI, DjVu
        * **Delimiter-Separated Values:** CSV, TSV
    # group loop
    - color: "blue"
      content: |
        ### 이미지, 그래픽 및 다이어그램
        * **래스터 이미지:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
        * **Windows Icon:** ICO
        * **Scalable Vector Graphics:** SVG, CDR, CMX, IGS, SVGZ        
        * **Adobe Photoshop:** PSD, PSB        
        * **Stereo Lithography (3D Printing):** STL        
        * **Medical Imaging:** DICOM
        * **Plotter Documents:** PLT, HPG
        * **Autodesk Design Web Formats:** DWF, DWG
        * **AutoCAD Drawing:** DWT, IFC, STL, CF2        
      # group loop
    - color: "red"
      content: |
        ### 다른        
        * **편물:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **아카이브:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **다른:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "GroupDocs.Viewer 기능"
  description: "PDF 및 Office 문서를 원활하게 렌더링, 표시 및 변환합니다."

  items:
    # feature loop
    - icon: "viewhtml"
      title: "HTML로 문서 보기"
      content: "모든 유형의 문서를 CSS 및 SVG를 사용하여 최신 웹 브라우저에서 표시할 수 있는 HTML 문서로 변환합니다."

    # feature loop
    - icon: "rasterize"
      title: "문서 래스터화"
      content: "조정 가능한 이미지 형식과 압축 품질을 사용하여 지원 가능한 모든 문서 형식을 래스터 이미지로 래스터화합니다."

    # feature loop
    - icon: "sourcecode"
      title: "프로그래밍 코드 렌더링 및 강조 표시"
      content: "구문을 분석하고 강조 표시하는 기능을 통해 널리 사용되는 모든 프로그래밍, 스크립팅 및 마크업 언어를 지원합니다."

    # feature loop
    - icon: "convertpdf"
      title: "PDF로 변환"
      content: "지원되는 모든 형식의 문서는 조정 가능한 옵션을 사용하여 쉽게 변환하고 PDF로 저장할 수 있습니다."

    # feature loop
    - icon: "transform"
      title: "변환 적용"
      content: "출력 문서는 렌더링 중에 변형될 수 있습니다. 페이지를 회전 및/또는 재배열할 수 있으며 텍스트 워터마크가 페이지 위에 배치될 수 있습니다."

    # feature loop
    - icon: "adjustment"
      title: "HTML 출력 조정"
      content: "GroupDocs.Viewer에 의해 생성된 출력 HTML 문서는 매우 세밀하게 조정될 수 있습니다. 외부 또는 내장 리소스, 콜백 등과 함께 스트림이나 파일에 저장할 수 있습니다."

    # feature loop
    - icon: "complex"
      title: "복잡한 문서 구조 지원"
      content: "GroupDocs.Viewer는 단일 문서뿐만 아니라 첨부 파일이 있는 이메일 메시지, 폴더 내에 내부 파일이 있는 ZIP 아카이브, 다중 페이지 TIFF 이미지 등과 같은 문서의 목록 또는 계층 구조를 내부적으로 포함하는 파일도 지원합니다."

    # feature loop
    - icon: "optimization"
      title: "최적화 옵션"
      content: "GroupDocs.Viewer에는 캐시된 문서 버전을 사용하여 로딩 시간을 단축할 수 있는 조정 가능한 캐시 하위 시스템이 포함되어 있습니다. 또한 다양한 형식에 대한 다양한 옵션 세트를 사용하면 렌더링에서 문서의 불필요한 부분이나 측면(글꼴, 숨겨진 워크시트, 이메일 첨부 파일)을 제외하여 전반적인 성능을 최적화할 수 있습니다."

    # feature loop
    - icon: "passwordprotected"
      title: "비밀번호로 보호된 문서 지원"
      content: "GroupDocs.Viewer를 사용하면 로딩 옵션에 비밀번호를 지정하여 PDF, 워드프로세싱, 스프레드시트, 프리젠테이션 등 다양한 유형의 암호화된 문서를 열 수 있습니다."

############################# Code samples ############################
code_samples:
  enable: true
  title: "코드 샘플"
  description: "Java 작업을 통한 Node.js용 일반적인 GroupDocs.Viewer의 일부 사용 사례"
  items:
    # code sample loop
    - title: "DOCX를 HTML로 렌더링"
      content: |
        `HtmlViewOptions` 클래스 속성을 사용하면 변환 프로세스를 제어할 수 있으며, 이에 대한 자세한 내용은 [여기](https://docs.groupdocs.com/viewer/nodejs-java/rendering-to-html/)에서 확인하세요. 예를 들어 출력 HTML 파일에 모든 외부 리소스를 포함하고, 출력 파일을 축소하고, 인쇄용으로 최적화할 수 있습니다.
        {{< landing/code title="JavaScript">}}
        ```javascript {style=abap}
        import { Viewer, HtmlViewOptions } from '@groupdocs/groupdocs.viewer'

        // 출력 HTML 옵션 설정(페이지당 파일 1개)
        const viewOptions = HtmlViewOptions.forEmbeddedResources()

        // 인스턴스화 뷰어
        const viewer = new Viewer("resume.docx")

        // 포함된 리소스를 사용하여 DOCX를 HTML로 렌더링
        viewer.view(viewOptions)
        viewer.close()
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "PPTX를 PDF로 내보내기"
      content: |
        'PdfViewOptions' 클래스 인스턴스를 생성하고 이를 'Viewer.view' 메서드에 전달하여 PowerPoint PPTX 파일을 PDF로 변환합니다. `PdfViewOptions` 클래스 속성을 사용하면 변환 프로세스를 제어할 수 있습니다. 예를 들어, 출력 PDF 파일을 보호하고, 페이지 순서를 변경하고, 문서 이미지의 품질을 지정할 수 있습니다. 자세한 내용은 [다음 문서 섹션](https://docs.groupdocs.com/viewer/nodejs-java/rendering-to-pdf/)을 참조하세요.
        {{< landing/code title="JavaScript">}}
        ```javascript {style=abap}   
        import { Viewer, PdfViewOptions } from '@groupdocs/groupdocs.viewer'

        // 출력 PDF 옵션 설정
        const viewOptions = new PdfViewOptions("presentation.pdf")

        // 인스턴스화 뷰어
        const viewer = new Viewer("presentation.pptx")

        // PPTX를 PDF로 내보내기
        viewer.view(viewOptions)
        viewer.close()
        ```
        {{< /landing/code >}}
############################# Reviews ############################
# reviews:
# enable: true
# title: "GroupDocs 제품 리뷰"
# description: "우리의 말만 받아들이지 마십시오. 다른 개발자가 우리 API에 대해 어떻게 말하는지 확인하세요."

# items:
#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "우수한 서비스와 우수한 제품. .NET용 GroupDocs.Viewer 구현 프로세스 동안 매우 도움이 되고 응답이 빨랐기 때문에 충분히 추천할 수는 없습니다."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "프로젝트에서 .NET용 GroupDocs.Viewer를 구현하고 사용한 후에는 매우 잘 작동하는 것으로 보입니다. 나는 많은 문서를 가지고 테스트해 보았는데 지금까지는 아주 좋았다. 내가 던진 모든 것은 PDF 뷰어나 MS Word에서와 마찬가지로 멋지게 렌더링되고 보기에도 좋습니다."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---
