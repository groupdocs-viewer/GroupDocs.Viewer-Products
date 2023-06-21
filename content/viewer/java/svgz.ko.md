---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: ko

############################# Head #############################
head_title: "Java SVGZ 뷰어 API - Java 앱에서 SVGZ 렌더링 및 표시"
head_description: "Java, J2EE, J2SE 애플리케이션에서 SVGZ 파일을 봅니다. 문서 보기 옵션을 관리하는 고급 기능을 사용하여 HTML, PDF 또는 이미지 모드에서 170개 이상의 문서 및 이미지 파일 형식 보기를 지원합니다."

############################# Header ############################
title: "자바에서 SVGZ 렌더링 및 보기" 
description: "Java, J2EE 및 J2SE 기반 응용 프로그램을 위한 기본 및 고성능 SVGZ 파일 뷰어 API는 출력 문서 형식의 모양을 사용자 지정하는 다양한 추가 기능을 지원합니다." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "무료 평가판 다운로드"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Java API용 GroupDocs.Viewer 정보" 
    content: |
        추가 소프트웨어를 설치하지 않고도 Java API용 GroupDocs.Viewer를 사용하여 Java 응용 프로그램이 HTML, PDF 또는 이미지 모드로 170개 이상의 파일 형식을 표시할 수 있습니다. Microsoft Office, Apache Open Office, Adobe Acrobat Reader 등 개발자는 Microsoft Office, OpenDocument, HTML, PDF, 아카이브, 다이어그램, Photoshop, AutoCAD 및 프로그래밍 언어 형식을 포함한 모든 인기 있는 이미지와 문서 유형을 Java 애플리케이션 내에서 쉽게 볼 수 있습니다. 빠르고 최고 품질의 렌더링.

############################# SubMenu ############################
submenu:
    enable: true

    left:
        img_alt: "GroupDocs.Viewer for .NET"
        image: "https://cms.admin.containerize.com/templates/groupdocs/images/product-logos/90x90-noborder/groupdocs-viewer-net.png"
        product: "GroupDocs.Viewer"
        platform: ".NET"

    middle:
        button:

            # button loop
            - link: "https://apireference.groupdocs.com/viewer/net"
              text: "API 참조"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "코드 예제"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "라이브 데모"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "가격"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "Java에서 SVGZ 파일을 렌더링하는 단계" 
    content_left: |
        [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/)를 사용하면 몇 단계 만에 SVGZ을 HTML, JPEG, PNG 또는 PDF로 렌더링할 수 있습니다.

        * [Java용 GroupDocs.Viewer](https://releases.groupdocs.com/viewer/java/)를 프로젝트에 대한 종속성으로 추가합니다. 
        * Viewer 클래스의 인스턴스를 생성하고 전체 경로로 SVGZ 파일을 로드합니다. 
        * SVGZ 파일을 HTML, PNG, JPEG 또는 PDF 형식으로 렌더링하는 옵션을 설정합니다. 
        * 파일을 렌더링하고 현재 디렉터리에서 출력을 확인합니다. 
        
    title_right: "시스템 요구 사항" 
    content_right: |
        GroupDocs.Viewer for Java API는 모든 주요 플랫폼 및 운영 체제에서 지원됩니다. 아래 코드를 실행하기 전에 시스템에 다음 필수 구성 요소가 설치되어 있는지 확인하십시오.

        * 운영 체제: 마이크로소프트 윈도우, 리눅스, 맥OS 
        * 개발 환경: NetBeans, IntelliJ IDEA, Eclipse 등 
        * 프레임워크: J2SE 8.0(1.8) 이상(예: Java 17) 
    code: |
        ```java
                        
            // Set up input SVGZ file
            String filePath = "input.svgz";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render SVGZ file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "SVGZ 뷰어 라이브 데모"
    content: |
        지금 바로 [GroupDocs.Viewer 온라인 앱](https://products.groupdocs.app/viewer/svgz) 웹사이트를 방문하여 SVGZ 파일을 확인하세요.
    lang: "ko"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Java을 사용한 다른 파일 형식 렌더링 및 보기"
    exclude: "SVGZ"
    content: |
        Java용 다중 형식 문서 및 이미지 뷰어 API. 외부 뷰어 없이 아래에서 인기 있는 파일 형식 중 일부를 볼 수 있습니다.
    format: 
        # format loop 1
        - name: "DOCX 렌더링"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Open XML 문서" 

        # format loop 2
        - name: "렌더링 CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "CorelDRAW 파일" 

        # format loop 3
        - name: "PPTX 렌더링"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint Open XML 프레젠테이션" 

        # format loop 4
        - name: "XLSX 렌더링"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Open XML 스프레드시트" 

        # format loop 5
        - name: "렌더 DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "AutoCAD 도면"

        # format loop 6
        - name: "XML 렌더링"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "XML 파일"

        # format loop 7
        - name: "PSD 렌더링"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "어도비 포토샵 문서"

        # format loop 8
        - name: "Adobe Illustrator 파일 렌더링"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "어도비 일러스트레이터 작품"

        # format loop 9
        - name: "렌더 DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "마이크로소프트 워드 문서" 

        # format loop 10
        - name: "렌더링 TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "일반 텍스트 파일" 

        # format loop 11
        - name: "DXF 렌더링" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "도면 교환 형식 파일"  
          
        # format loop 12
        - name: "VCF 렌더링"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "vCard 파일"  
              
        # format loop 13
        - name: "렌더링 SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "확장 가능한 벡터 그래픽" 
          
        # format loop 14
        - name: "HTML 렌더링"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "하이퍼텍스트 마크업 언어 파일" 
          
        # format loop 15
        - name: "PDF 렌더링"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "휴대용 문서 형식 파일"
          
        # format loop 16
        - name: "JPEG 렌더링"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "JPEG 이미지"
          
        # format loop 17
        - name: "렌더 PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "휴대용 네트워크 그래픽" 
          
        # format loop 18
        - name: "렌더링 EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "이메일 메시지" 
          
        # format loop 19
        - name: "RTF 렌더링"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "서식 있는 텍스트 형식 파일" 
          
        # format loop 20
        - name: "렌더링 ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "OpenDocument 텍스트 문서" 
          
        # format loop 21
        - name: "CSV 렌더링"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "쉼표로 구분된 값 파일" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
