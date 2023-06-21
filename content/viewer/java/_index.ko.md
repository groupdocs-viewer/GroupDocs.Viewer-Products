---
############################# Static ############################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

lang: ko
product: "Viewer"
product_tag: "viewer"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "PDF Word Excel HTML 이미지 및 이메일용 Java 문서 뷰어 API"
head_description: "Java 문서 뷰어 및 파일 렌더링 API. Java 애플리케이션에 PDF 뷰어, Word 뷰어, Excel 뷰어, 이미지 뷰어, HTML 뷰어, 이메일 뷰어를 추가합니다."

############################# Header ############################
title: "문서 렌더링 및 표시를 위한 Java API"
description: "기본적으로 170개 이상의 파일 형식을 지원하는 다중 형식 문서를 렌더링, 보기 및 조작하는 Java 애플리케이션을 개발하기 위한 문서 뷰어 라이브러리."
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Download Free Trial"
    link: "https://downloads.groupdocs.com/viewer/java"

############################# SubMenu ############################
submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Viewer for Java"
        image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-viewer-java.png"
        product: "GroupDocs.Viewer"
        platform: "Java"

    middle:
        button:
            # button loop
            - link: "#overview"
              text: "개요"

            # button loop
            - link: "#features"
              text: "특징"

            # button loop
            - link: "#support"
              text: "지원하다"

            # button loop
            - link: "https://products.groupdocs.app/viewer/total"
              text: "라이브 데모"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/java"
              text: "가격"

    right:
        link_download: "https://releases.groupdocs.com/viewer/java/"
        link_learn: "https://docs.groupdocs.com/viewer/java/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    content: |
      Java용 GroupDocs.Viewer는 강력한 문서 뷰어 API 세트를 결합하여 추가 소프트웨어를 설치할 필요 없이 Java 응용 프로그램에 이미지와 문서 형식을 표시합니다. 기본적으로 문서를 래스터화하고 SVG+HTML+CSS로 변환하여 문서 보기의 품질을 향상하는 동시에 진정한 텍스트의 고충실도 출력을 제공합니다. 문서 렌더링 API 사용 – PDF, HTML, XML, Microsoft Office Word, Excel 워크시트, PowerPoint 프레젠테이션, Outlook 전자 메일, Visio 다이어그램, 프로젝트, 메타파일, 이미지 및 기타 다양한 파일 형식을 쉽고 프로그래밍 위험 없이 빠르게 볼 수 있습니다. 또한 암호로 보호된 파일을 표시하고 렌더링 후 HTML, 이미지 또는 PDF 형식으로 문서 표현을 얻을 수 있습니다. 파일 뷰어 라이브러리는 전체 문서를 표시하거나 프로세스 속도를 높이기 위해 부분적으로 렌더링할 수 있으므로 사용자 정의가 가능합니다. GroupDocs.Viewer for Java API를 통해 페이지, 스프레드시트의 특정 셀 범위를 보거나 개별 문서 계층을 PDF 및 CAD와 같은 형식으로 렌더링할 수도 있습니다.  

      GroupDocs.Viewer for Java API를 사용하면 지원되는 파일 형식에 대한 주석 또는 설명이 있거나 없는 문서를 렌더링할 수 있습니다. 또한 사용자 정의 글꼴 디렉토리를 추가하고 FileType, Extension, Name, PageCount 등과 같은 기본 문서 정보를 추출할 수 있습니다.  

      Java용 GroupDocs.Viewer는 모든 Java 버전과 호환되며 Java 런타임을 실행할 수 있는 널리 사용되는 운영 체제(Windows, Linux, macOS)를 지원합니다.
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          다음은 Java용 GroupDocs.Viewer의 개요입니다.
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "개요"
          content: |
            * 170개 이상의 문서 유형 표시 
            * HTML, 이미지, PDF 버전 받기 
            * 회전 및 재정렬 
            * 워터마크 적용 
            * 빠른 프로세스를 위한 캐시 
            * 사용자 지정 글꼴 추가 
            * 인코딩 표준 적용 
            * 사용자 정의 입력 데이터 핸들러 
            * 변경 사항 추적으로 렌더링 
            * 반응형 HTML로 렌더링 
            * PDF 및 CAD 레이어 렌더링 
            * 보호된 파일 렌더링 
      
      ## TAB TWO ##
      tab_two:
        description: |
          Java용 GroupDocs.Viewer는 Microsoft Office, 이미지, 다이어그램 등을 포함하여 널리 사용되는 모든 문서 파일 형식을 지원합니다.

        left:
          enable: true
          table:
            # table loop
            - title: "Microsoft Office"
              content: |
                * **Word:** DOC, DOCX, DOCM, DOT, DOTX, DOTM, RTF, TXT
                * **Excel:** XLS, XLSX, XLSM, XLSB, XLTM, XLT, XLTM, XLTX, XLAM, SXC, SpreadsheetML
                * **PowerPoint:** PPT, PPTX, PPS, PPSX, PPSM, POT, POTM, POTX, PPTM
                * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
                * **Project:** MPP, MPT, MPX
                * **Outlook:** MSG, EML, EMLX, PST, OST
                * **OneNote:** ONE

            # table loop
            - title: "기타 형식"
              content: |
                * **페이지 레이아웃 파일:** PDF, TEX, XPS, OXPS
                * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG, OTG, FODP, FODG
                * **구분 기호로 구분된 값:** CSV, TSV
                * **편물:** HTML, MHT, MHTML
                * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
                * **PostScript:** PS, EPS
                * **아카이브:** ZIP, TAR, BZ2, GZ, RAR, RAR5
                * **다양한:** OBJ, EPUB, MOBI, DjVu, XML, VCF, VCARD, NUMBERS, NSF

        right:
          enable: true
          table:
            # table loop
            - title: "이미지, 그래픽 및 다이어그램"
              content: |
                * **이미지:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB
                * **윈도우 아이콘:** ICO
                * **확장 가능한 벡터 그래픽:** SVG, CDR, CMX, IGS, SVGZ
                * **Jpeg2000:** JP2, J2C, J2K, JPC, JPF, JPX, JPM
                * **어도비 포토샵:** PSD, PSB
                * **프린터 명령 언어:** PCL
                * **스테레오 리소그래피(3D 인쇄):** STL
                * **산업 기초 수업:** IFC
                * **의료 영상:** DICOM
                * **플로터 문서:** PLT, HPG
                * **Autodesk 디자인 웹 형식:** DWF, DWG
                * **AutoCAD 도면:** DWT, IFC, STL, CF2
                * **ISFF 기반 DGN(V7):** DGN

            # table loop
            - title: "프로그래밍 언어 형식"
              content: |
                * **C/C++/C# 파일:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
                * **자바/자바스크립트 파일:** JAVA, JS, JSON, PROPERTIES
                * **다양한:** VB, PHP, SQL, PL, PY, PV, RB, RST, SASS, SCALA, SCM, SCRIPT, AS, AS3, ASM, BAT, CMAKE, CSS, DIFF, ERB, GROOVY, HAML, LESS, LOG, M, MAKE, MD, ML, MM, SH, SML, VIM, YAML

      ## TAB THREE ##
      tab_three:
        description: |
          Java용 GroupDocs.Viewer는 다음 운영 체제, 프레임워크 및 패키지 관리자를 지원합니다.
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "운영체제"
              content: |
                * 마이크로소프트 윈도우 서버 2003 이상 
                * 마이크로소프트 윈도우 XP 이상 
                * 마이크로소프트 윈도우 10 & 11 
                * Linux(Ubuntu, OpenSUSE, CentOS 등) 
                * 맥 OS X 

            # table loop
            - icon: "fas fa-code"
              title: "지원되는 프레임워크"
              content: |
                * J2SE 8.0(1.8) 이상(예: Java 17) 

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-cogs"
              title: "개발 환경"
              content: |
                * NetBeans
                * IntelliJ IDEA
                * Eclipse

            # table loop
            - icon: "fas fa-tools"
              title: "빌드 자동화 도구"
              content: |
                * Maven
                * Gradle

############################# Features ############################
features:
    enable: true
    title: "Java용 GroupDocs.Viewer 기능"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "HTML, PDF, 이미지, Word, Excel 및 기타 문서 형식용 뷰어"

      # feature loop
      - icon: "fas fa-eye"
        content: "AutoCAD 도면(DWG) 파일을 SVG 형식으로 렌더링"

      # feature loop
      - icon: "fas fa-bolt"
        content: "변환된 파일의 배경색 조정"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "문서를 SVG, HTML 및 CSS로 래스터화 및 변환"

      # feature loop
      - icon: "fas fa-code"
        content: "렌더링을 통해 문서의 HTML, 이미지 또는 PDF 표현 얻기"

      # feature loop
      - icon: "fas fa-cloud"
        content: "로드 시간 단축을 위한 캐시된 문서 버전"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "사용자 정의 글꼴 디렉토리 구성"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "Word, Excel 및 이메일 문서에 인코딩 표준 적용"

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "FTP 또는 클라우드 저장소에서 원격으로 문서 렌더링"

      # feature loop
      - icon: "fas fa-border-all"
        content: "렌더링하는 동안 주석 및 주석 제거 또는 유지"

      # feature loop
      - icon: "fas fa-wrench"
        content: "문서 페이지를 별도의 HTML 페이지로 렌더링"

      # feature loop
      - icon: "fas fa-columns"
        content: "숨겨진 슬라이드 및 페이지 렌더링 및 렌더링된 문서에 페이지 재정렬 적용"

      # feature loop
      - icon: "fas fa-file-word"
        content: "페이지 범위, 특정 페이지 또는 모든 페이지를 HTML로 렌더링"

      # feature loop
      - icon: "fas fa-envelope"
        content: "문서 주석 렌더링 또는 숨기기"

      # feature loop
      - icon: "fas fa-print"
        content: "렌더링을 통해 일부 문서 형식에 대한 반응형 HTML 만들기"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "글꼴을 제외하여 렌더링된 HTML의 결과 파일 크기 줄이기"

      # feature loop
      - icon: "fas fa-lock"
        content: "출력 HTML 및 CSS를 축소하기 위해 주석, 추가 공백 등을 제거합니다."

      # feature loop
      - icon: "fas fa-file-code"
        content: "소스 문서의 좌표를 사용하여 포함된 텍스트 읽기"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "렌더링된 출력의 Excel 시트에서 셀 테두리 표시/숨기기"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "Excel 시트에서 각 페이지의 특정 행 수 렌더링"

      # feature loop
      - icon: "fas fa-heading"
        content: "렌더링 모델 및 비어 있지 않은 모든 레이아웃 또는 CAD 파일의 특정 레이아웃"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "Outlook 데이터 파일(OST/PST)의 항목을 PDF로 렌더링"

      # feature loop
      - icon: "fas fa-cube"
        content: "타일 ​​렌더링 또는 이미지, HTML 또는 PDF로 CAD 문서의 좌표에 의한 렌더링"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "PDF로 렌더링할 때 인쇄 제한 설정"

    more_feature:
      # more_feature_loop
      - title: "문서 보기를 위한 효율적이고 신뢰할 수 있는 API"
        content: |
          GroupDocs.Viewer for Java API는 150개 이상의 다양한 파일 형식의 문서를 보고 렌더링하고 표시하는 데 사용할 수 있습니다. 문서의 내용과 구조를 그대로 유지하면서 안정적이고 효율적으로 수행됩니다. 다음 예는 Java API용 GroupDocs.Viewer가 Java를 사용하여 DOCX 파일을 이미지 파일로 렌더링하는 용이성 수준을 보여줍니다.

          ```java
          // Initialize Viewer
          Viewer viewer = new Viewer("invoice.docx");
          // Create view options
          PdfViewOptions viewOptions = new PdfViewOptions();
          // Convert file to PDF and check the output in the current directory
          viewer.view(viewOptions);
          ```
      # more_feature_loop
      - title: "문서를 렌더링하는 동안 변환 수행"
        content: "Java API용 GroupDocs.Viewer는 렌더링된 문서에 적용할 수 있는 다양한 변환 옵션을 제공하여 보다 사용자 정의된 보기 및 표시를 제공합니다. 각도를 제공하여 페이지를 회전할 수 있습니다. 렌더링된 페이지의 순서를 지정할 수 있습니다. 렌더링된 페이지 또는 이미지에 특정 텍스트를 워터마크로 적용합니다. GroupDocs.Viewer for Java API를 통해 렌더링되는 문서에 사용자 지정 글꼴을 추가할 수도 있습니다."

      # more_feature_loop
      - title: "이메일 첨부 파일 작업"
        content: "GroupDocs.Viewer for Java API를 사용하면 이메일의 특정 첨부 파일이나 모든 첨부 파일을 가져올 수 있습니다. 필요한 이메일 첨부 파일을 받으면 이러한 첨부 파일을 이미지 또는 HTML로 렌더링할 수 있습니다."

############################# Support ############################
support:
    enable: true

############################# Solutions ##########################
solutions:
    enable: true
    title: "GroupDocs.Viewer는 널리 사용되는 다른 개발 환경을 위한 문서 보기 API를 제공합니다."

    solution:
        # solution loop
        - img_alt: "GroupDocs.Viewer for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-viewer-net.png"
          product: "GroupDocs.Viewer"
          platform: ".NET"
          link: "/viewer/net/"

############################# Back to top ##########################
back_to_top:
  enable: true
---