---
############################# Static ############################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: ko
product: "Viewer"
product_tag: "viewer"
platform: "Python via .NET"
platform_tag: "python-net"

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
    # supported_platforms loop
    - title: "Python"
      tag: "python-net" 


############################# Head ############################
head_title: "Python 문서 뷰어 API (PDF, Word, Excel, HTML, 이미지, 이메일)"
head_description: "Python 파일 렌더링 및 문서 뷰어 API입니다. Python 애플리케이션에 PDF 뷰어, Word 뷰어, Excel 뷰어, 이미지 뷰어, HTML 뷰어, 이메일 뷰어를 추가하세요."

############################# Header ############################
title: "최적화된 문서 렌더링을 위한 강력한 Python API"
description: "강력한 API 및 다양한 구성 옵션을 사용하여 Python 애플리케이션에서 180개 이상의 문서 형식(PDF, HTML, 이미지)을 렌더링하고 표시하세요."
words:
  for: "for"

actions:
  viewer_demo: true
  viewer_demo_file_name: "quarterly-report.docx"
  main: "PyPI에서 무료 다운로드"
  main_link: "https://pypi.org/project/groupdocs-viewer-net/"
  alt: "라이선스"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/python-net"
  title: "시작할 준비가 되셨나요?"
  description: "GroupDocs.Viewer 기능을 무료로 사용해 보거나 라이선스를 요청하세요"

release:
  title: "버전 {0} 출시됨"
  notes: "새로운 소식 보기"
  downloads: "다운로드"
  link: "https://releases.groupdocs.com/viewer/python-net/release-notes/latest/"

code:
  title: "Python에서의 PDF 파일 렌더링"
  more: "더 많은 예시"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Python-via-.NET"
  install: "pip install groupdocs-viewer-net"
  content: |
    ```python {style=abap}
    import groupdocs.viewer as gv
    import groupdocs.viewer.options as gvo
    hvo = gvo.HtmlViewOptions  
  
    // 출력 HTML 옵션 설정 (1페이지당 1개 파일)
    with gv.Viewer("resume.docx") as viewer:
      // 뷰어 인스턴스화
      opts = hvo.for_embedded_resources("page_{0}.html")

      // 埋め込み 리소스를 사용한 PDF에서 HTML로의 렌더링
      viewer.view(opts)
    ```
############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Viewer 개요"
  description: "Python 애플리케이션에서 문서, 슬라이드, 다이어그램 및 기타 여러 문서 유형의 렌더링, 표시, 변환을 위한 API"
  features:
    # feature loop
    - title: "문서를 효율적이고 안정적으로 보기"
      content: "GroupDocs.Viewer API를 사용하면 지원되는 모든 형식의 문서를 [HTML](https://docs.groupdocs.com/viewer/python-net/rendering-to-html/), JPEG, PNG, 및 [PDF](https://docs.groupdocs.com/viewer/python-net/rendering-to-pdf/) 로 효율적으로 렌더링할 수 있습니다. 유연하고 강력한 옵션을 제공하며 콘텐츠와 문서 구조의 완전성을 유지합니다. GroupDocs.Viewer for Python은 Windows와 Linux 플랫폼에서 작동합니다."

    # feature loop
    - title: "가장 인기 있는 파일 형식과 문서 형식이 지원됩니다"
      content: "우리는 [Word](https://docs.groupdocs.com/viewer/python-net/render-word-documents/), [Excel](https://docs.groupdocs.com/viewer/python-net/specify-rendering-options/), [PDF](https://docs.groupdocs.com/viewer/python-net/render-pdf-documents/), [PowerPoint](https://docs.groupdocs.com/viewer/python-net/render-presentations/) 등 180개 이상의 가장 많이 사용되는 파일 및 문서 형식을 렌더링합니다. OpenDocument 형식군, 아카이브, 래스터 및 벡터 이미지, 전자책, 프로그래밍 언어 및 마크업 등 다양한 파일 유형을 지원하며, 비밀번호로 보호된 암호화 파일도 처리합니다."

    # feature loop
    - title: "사용자 정의 가능한 출력"
      content: "GroupDocs.Viewer를 사용하면 문서 렌더링뿐만 아니라 렌더링해야 하는 문서 부분을 정확하게 제어하거나, 렌더링 방법을 제어하거나, 렌더링된 출력에 다양한 변환을 적용할 수도 있습니다."

############################# Platforms ############################
platforms:
  enable: true
  title: "플랫폼 독립성"
  description: "GroupDocs.Viewer for Python은 다음 운영 체제, 프레임워크 및 패키지 관리자를 지원합니다"
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
    - title: "PyPI"
      image: "pypi"

############################# File formats ############################
formats:
  enable: true
  title: "지원되는 파일 형식"
  description: |
    GroupDocs.Viewer for Python (via .NET)은 다음 파일 형식에 대한 작업을 지원합니다: [지원되는 파일 형식](https://docs.groupdocs.com/viewer/python-net/supported-document-formats/).
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
      title: "[HTML로 문서 보기](https://docs.groupdocs.com/viewer/python-net/rendering-to-html/)"
      content: "모든 유형의 문서를 CSS 및 SVG를 사용하여 최신 웹 브라우저에서 표시할 수 있는 HTML 문서로 변환합니다."

    # feature loop
    - icon: "rasterize"
      title: "[문서 래스터화](https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Python-via-.NET/blob/master/Examples/basic_usage/render_document_to_image/render_to_png.py)"
      content: "조정 가능한 이미지 형식과 압축 품질을 사용하여 지원 가능한 모든 문서 형식을 래스터 이미지로 래스터화합니다."

    # feature loop
    - icon: "font"
      title: "[문서 글꼴 제어](https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Python-via-.NET/blob/master/Examples/advanced_usage/rendering/common_rendering_options/replace_missing_font.py)"
      content: "문서에 사용된 글꼴을 확인하고, 누락된 글꼴을 교체하거나 출력에서 제외하여 관리합니다."

    # feature loop
    - icon: "convertpdf"
      title: "[PDF로 변환](https://docs.groupdocs.com/viewer/python-net/rendering-to-pdf/)"
      content: "지원되는 모든 형식의 문서는 조정 가능한 옵션을 사용하여 쉽게 변환하고 PDF로 저장할 수 있습니다."

    # feature loop
    - icon: "transform"
      title: "[변환 적용](https://docs.groupdocs.com/viewer/python-net/add-text-watermark/)"
      content: "출력 문서는 렌더링 중에 변형될 수 있습니다. 페이지를 회전 및/또는 재배열할 수 있으며 텍스트 워터마크가 페이지 위에 배치될 수 있습니다."

    # feature loop
    - icon: "adjustment"
      title: "[HTML 출력 조정](https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Python-via-.NET/blob/master/Examples/basic_usage/render_document_to_html/render_to_html_with_embedded_resources.py)"
      content: "GroupDocs.Viewer에 의해 생성된 출력 HTML 문서는 매우 세밀하게 조정될 수 있습니다. 외부 또는 내장 리소스, 콜백 등과 함께 스트림이나 파일에 저장할 수 있습니다."

    # feature loop
    - icon: "complex"
      title: "[복잡한 문서 구조 지원](https://docs.groupdocs.com/viewer/python-net/how-to-extract-and-save-attachments/)"
      content: "GroupDocs.Viewer는 단일 문서뿐만 아니라 첨부 파일이 있는 이메일 메시지, 폴더 내에 내부 파일이 있는 ZIP 아카이브, 다중 페이지 TIFF 이미지 등과 같은 문서의 목록 또는 계층 구조를 내부적으로 포함하는 파일도 지원합니다."

    # feature loop
    - icon: "optimization"
      title: "최적화 옵션"
      content: "GroupDocs.Viewer에는 캐시된 문서 버전을 사용하여 로딩 시간을 단축할 수 있는 조정 가능한 캐시 하위 시스템이 포함되어 있습니다. 또한 다양한 형식에 대한 다양한 옵션 세트를 사용하면 렌더링에서 문서의 불필요한 부분이나 측면(글꼴, 숨겨진 워크시트, 이메일 첨부 파일)을 제외하여 전반적인 성능을 최적화할 수 있습니다."

    # feature loop
    - icon: "passwordprotected"
      title: "[비밀번호로 보호된 문서 지원](https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Python-via-.NET/blob/master/Examples/advanced_usage/loading/load_password_protected_document.py)"
      content: "GroupDocs.Viewer를 사용하면 로딩 옵션에 비밀번호를 지정하여 PDF, 워드프로세싱, 스프레드시트, 프리젠테이션 등 다양한 유형의 암호화된 문서를 열 수 있습니다."

############################# Code samples ############################
code_samples:
  enable: true
  title: "코드 샘플"
  description: "Python을 통한 .Net를 사용한 GroupDocs.Viewer 작업의 일반적인 사용 사례"
  items:
    # code sample loop
    - title: "DOCX를 HTML로 변환"
      content: |
        ``HtmlViewOptions`` 클래스의 속성을 사용하면 변환 프로세스를 제어할 수 있습니다. 자세한 내용은 [여기](https://docs.groupdocs.com/viewer/python-net/rendering-to-html/)를 참조하십시오. 예를 들어 모든 외부 리소스를 출력 HTML 파일에 삽입하고, 출력 파일을 압축하며, 인쇄用に 최적화할 수 있습니다.
        {{< landing/code title="Python">}}
        ```python {style=abap}
        import groupdocs.viewer as gv
        import groupdocs.viewer.options as gvo 

        // 뷰어 인스턴스화
        with gv.Viewer("resume.docx") as viewer:
          // 출력 HTML 옵션 설정 (1페이지당 1개 파일)
          viewOptions = gvo.HtmlViewOptions.for_embedded_resources("page_{0}.html")
          // 埋め込み 리소스를 사용한 PDF에서 HTML로의 렌더링
          viewer.view(viewOptions)
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "PPTX를 PDF로 내보내기"
      content: |
        ``PdfViewOptions`` 클래스의 인스턴스를 만들어 ``Viewer.view`` 메서드에 전달하여 PowerPoint PPTX 파일을 PDF로 변환합니다. ``PdfViewOptions`` 클래스의 속성을 사용하면 변환 프로세스를 제어할 수 있습니다. 예를 들어 출력 PDF 파일을 보호하거나, 페이지 순서를 변경하거나, 문서 이미지의 품질을 지정할 수 있습니다. 자세한 내용은 [다음 문서 섹션](https://docs.groupdocs.com/viewer/python-net/rendering-to-pdf/)을 참조하십시오.
        {{< landing/code title="Python">}}
        ```python {style=abap}
        import groupdocs.viewer as gv
        import groupdocs.viewer.options as gvo  

        // 뷰어 인스턴스화
        with gv.Viewer("presentation.pptx") as viewer:
          // 출력 PDF 옵션 설정 (Set output PDF options)
          viewOptions = gvo.PdfViewOptions("presentation.pdf")
          // PPTX를 PDF로 내보내기 (Export PPTX to PDF)
          viewer.view(viewOptions)
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
