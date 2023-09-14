---
############################# Static ##########################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

lang: ko
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: ".NET 문서 뷰어 API, PDF Word Excel 이미지 HTML 다이어그램 렌더링"
head_description: "C# ASP.NET 파일 뷰어 및 렌더링 API. .NET 앱에 PDF 뷰어, Word 뷰어, Excel 뷰어, 이미지 뷰어, HTML 뷰어, 이메일 뷰어 기능을 추가합니다."

############################# Header ##########################
title: ".NET API를 통해 문서 렌더링 및 표시"
description: "강력한 구성 옵션을 사용하여 190개 이상의 문서 형식을 PDF, HTML 및 이미지로 렌더링하는 .NET 문서 뷰어 API."
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Download Free Trial"
    link: "https://downloads.groupdocs.com/viewer/net"

############################# SubMenu #########################
submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Viewer for .NET"
        image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-viewer-net.png"
        product: "GroupDocs.Viewer"
        platform: ".NET"

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
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "가격"

    right:
        link_download: "https://www.nuget.org/packages/GroupDocs.Viewer"
        link_learn: "https://docs.groupdocs.com/viewer/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    content: |
      .NET API용 GroupDocs.Viewer는 C#, ASP.NET 및 기타 .NET 기반 기술로 강력한 응용 프로그램을 만들 수 있도록 도와줍니다. 이 응용 프로그램은 외부 소프트웨어를 설치하지 않고도 190개 이상의 파일 형식의 문서와 이미지를 렌더링하고 표시할 수 있습니다. 파일 뷰어 라이브러리는 문서를 래스터화한 다음 SVG+HTML+CSS로 변환하여 비즈니스 문서, 이미지, 텍스트 파일, 다이어그램, 그래픽, 이메일 첨부 파일 및 PDF 파일을 보기 위한 전체 문서 렌더링 경험을 최적화합니다. 애플리케이션 내부의 충실도가 높습니다. 애플리케이션에서 문서 보기 및 읽기 기능을 추가하여 전체 문서, 부분 문서, 특정 페이지/셀 범위, 개별 문서 계층을 표시하고 지원되는 파일 형식에 대한 주석 및 주석을 포함하거나 포함하지 않는 옵션이 있습니다.
       
      .NET용 GroupDocs.Viewer는 기본적으로 렌더링된 문서 출력을 로컬 디스크에 캐시합니다. Amazon S3, Dropbox, Google Drive, Windows Azure, Redis 또는 기타 적절한 인터페이스를 구현하여 모든 유형의 외부 캐시 스토리지도 지원됩니다.
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          다음은 .NET용 GroupDocs.Viewer의 개요입니다.
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "개요"
          content: |
            * 190개 이상의 문서 유형 표시 
            * HTML, 이미지, PDF 형식의 파일 가져오기 
            * 회전 및 재정렬 
            * 워터마크 적용 
            * 빠른 프로세스를 위한 캐시 
            * 사용자 지정 글꼴 추가 
            * 인코딩 표준 적용 
            * 사용자 정의 입력 데이터 핸들러 
            * 변경 사항 추적으로 렌더링 
            * 반응형 HTML로 렌더링 
            * PDF 및 CAD 레이어 렌더링 
      
      ## TAB TWO ##
      tab_two:
        description: |
          .NET용 GroupDocs.Viewer는 널리 사용되는 모든 문서 파일 형식 보기를 지원합니다. 몇 줄의 코드만으로 PDF 뷰어, Microsoft Office Word, Excel 스프레드시트, 이미지, HTML, Outlook 전자 메일, OneNote, Project 및 그래픽 보기 기능을 .NET 응용 프로그램에 추가할 수 있습니다.

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
            - title: "Other Formats"
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
          .NET용 GroupDocs.Viewer는 다음 운영 체제, 프레임워크 및 패키지 관리자를 지원합니다.
        
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
                * .NET 프레임워크 2.0 이상 
                * .NET 코어 3.1 
                * .NET 5 이상 

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-box"
              title: "패키지 관리자"
              content: |
                * NuGet

            # table loop
            - icon: "fas fa-tools"
              title: "개발 환경"
              content: |
                * Microsoft Visual Studio
                * Visual Studio Code
                * .NET CLI

############################# Features ############################
features:
    enable: true
    title: ".NET용 GroupDocs.Viewer 기능"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "문서를 래스터화하고 SVG, HTML 및 CSS로 변환"

      # feature loop
      - icon: "fas fa-eye"
        content: "텍스트를 HTML로 변환하고 문서를 렌더링하여 HTML, 이미지 또는 PDF 표현을 얻습니다."

      # feature loop
      - icon: "fas fa-bolt"
        content: "문서의 캐시된 버전을 사용하여 더 빠른 로드 시간"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "3D 효과를 사용하여 도형 및 텍스트가 있는 프레젠테이션 변환"

      # feature loop
      - icon: "fas fa-code"
        content: "Word, Excel 및 이메일 문서를 원하는 인코딩 표준으로 인코딩"

      # feature loop
      - icon: "fas fa-cloud"
        content: "FTP 또는 클라우드 저장소 위치에 있는 문서 렌더링"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "결과 파일 크기를 줄이기 위해 HTML로 렌더링할 때 글꼴 제외"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "주석, 추가 공백 등을 제거하여 CSS 및 HTML 출력 축소"

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "좌표를 통해 소스 문서에 포함된 텍스트 읽기"

      # feature loop
      - icon: "fas fa-border-all"
        content: "출력 표시에서 Excel 시트의 격자선 표시/숨기기"

      # feature loop
      - icon: "fas fa-wrench"
        content: "각 페이지에 렌더링할 Excel 시트의 행 수 지정"

      # feature loop
      - icon: "fas fa-columns"
        content: "스프레드시트 문서를 렌더링하는 동안 빈 열 무시"

      # feature loop
      - icon: "fas fa-file-word"
        content: "변경 사항 추적을 통해 Word 문서를 HTML 페이지, 이미지 또는 PDF로 렌더링"

      # feature loop
      - icon: "fas fa-envelope"
        content: "이메일 첨부 파일을 원본 파일, 이미지 또는 HTML 표현으로 렌더링"

      # feature loop
      - icon: "fas fa-print"
        content: "PDF 문서에 대한 인쇄 제한 설정"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "ZIP 아카이브에 포함된 콘텐츠/파일을 첨부 파일로 렌더링"

      # feature loop
      - icon: "fas fa-lock"
        content: "암호로 보호된 문서에서 첨부 파일 가져오기"

      # feature loop
      - icon: "fas fa-file-code"
        content: "프로그래밍 언어 파일 형식을 일반 텍스트로 렌더링"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "CAD 도면을 볼 때 배경 색상 조정"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "Excel 문서 보기 및 PDF, HTML, JPG 및 PNG로 변환"

      # feature loop
      - icon: "fas fa-heading"
        content: "Excel 파일에서 워크시트 이름 가져오기 – 스프레드시트 열 머리글 및 행 번호 표시"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "메모가 있는 Microsoft Project 문서 보기 및 변환"

      # feature loop
      - icon: "fas fa-cube"
        content: "더 나은 보기 및 확대/축소 경험을 위해 CAD 도면을 SVG로 변환"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "구성표 없이 Visio 그림을 렌더링하도록 선택"

    more_feature:
      # more_feature_loop
      - title: "효율적이고 안정적으로 문서 보기"
        content: |
          GroupDocs.Viewer API를 사용하면 콘텐츠 및 문서 구조 무결성을 그대로 유지하면서 효율적이고 안정적으로 190개 이상의 문서 형식을 표시할 수 있습니다. 다음 샘플 코드는 DOCX 문서의 HTML 표현을 보는 것이 얼마나 쉬운지 보여줍니다.

          ```cs
          // Instantiate viewer
          using (Viewer viewer = new Viewer("invoice.docx"))
          {
              // Set view options
              HtmlViewOptions options = HtmlViewOptions.ForEmbeddedResources();
              // Convert file to HTML with embedded resources
              viewer.View(options);
          }
          ```
      # more_feature_loop
      - title: "렌더링된 출력에 변환 적용"
        content: ".NET API용 GroupDocs.Viewer를 사용하여 렌더링된 출력 문서에 다양한 변환을 수행할 수 있습니다. 이러한 변환 옵션을 사용하면 렌더링된 출력을 표시하는 방법을 제어할 수 있습니다. 사용 가능한 변환은 페이지 회전 옵션, 페이지 재정렬 옵션 및 텍스트 워터마크 적용입니다."

      # more_feature_loop
      - title: "Outlook 데이터 파일 작업"
        content: ".NET API용 GroupDocs.Viewer는 Outlook 데이터 파일(OST/PST)의 항목을 PDF, HTML 및 이미지 파일로 렌더링할 수 있습니다. Viewer API에는 Outlook 데이터 파일에 포함된 폴더 목록을 가져오는 기능도 있습니다. .NET API용 GroupDocs.Viewer를 사용하여 Outlook 데이터 파일에서 렌더링할 폴더를 지정할 수 있습니다. 마찬가지로 첨부 파일로 OST/PST 형식으로 포함된 이메일 메시지를 얻을 수도 있습니다. .NET용 GroupDocs.Viewer를 사용하면 제목, 콘텐츠 또는 발신자를 기준으로 OST/PST 형식의 메시지를 필터링할 수도 있습니다."

      # more_feature_loop
      - title: "CAD 문서 작업"
        content: ".NET API용 GroupDocs.Viewer는 모델 및 비어 있지 않은 모든 레이아웃을 렌더링하거나 CAD 파일의 특정 레이아웃을 렌더링할 수 있습니다. .NET API용 GroupDocs.Viewer는 CAD 문서의 좌표를 이미지, HTML 또는 PDF로 바둑판식 렌더링 또는 렌더링도 지원합니다. CAD 문서의 레이어 상태를 가져올 수도 있습니다."

############################# Testimonials ###############################
testimonials:
  enable: true

  testimonial:
    # testimonial item loop
    - name: "Margot Baill"
      designation: "Hireology의 제품 개발 이사"
      content: "환상적인 Ruby SDK를 사용하여 Cloud API용 GroupDocs.Viewer를 간단하게 통합할 수 있습니다. 우리가 원하는 것을 기꺼이 우리와 함께 일할 회사가 많지 않습니다. 훌륭한 파트너십입니다."

    # testimonial item loop
    - name: "Mats Oustad"
      designation: "Novanet AS 선임 컨설턴트/파트너"
      content: "프로젝트에서 GroupDocs.Viewer for .NET을 구현하고 사용한 후 매우 잘 작동하는 것 같습니다. 나는 많은 문서로 테스트했으며 지금까지 너무 좋습니다. 내가 던진 모든 것이 멋지게 렌더링되고 PDF 뷰어나 MS Word에서처럼 보기 좋습니다."
              
    # testimonial item loop
    - name: "Martin Lasarga"
      designation: "G.S.I.의 Axentria ECM 제품 관리자"
      content: "우수한 서비스와 우수한 제품. 그들은 GroupDocs.Viewer for .NET 구현 프로세스 동안 매우 유용하고 반응이 좋았으며 충분히 추천할 수 없었습니다."

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Viewer는 널리 사용되는 다른 개발 환경을 위한 문서 보기 API를 제공합니다."

    solution:
        # solution loop
        - img_alt: "GroupDocs.Viewer for Java"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-viewer-java.png"
          product: "GroupDocs.Viewer"
          platform: "Java"
          link: "/viewer/java/"

############################# Back to top ###############################
back_to_top:
  enable: true
---
