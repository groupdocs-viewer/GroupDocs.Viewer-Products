---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: ko

############################# Head #############################
head_title: ".NET VSD 뷰어 API - C# VB.NET에서 읽기, 보기, 렌더링"
head_description: ".NET 문서 뷰어 API는 모든 유형의 C#, ASP.NET, VB.NET 및 .NET Core 애플리케이션에서 VSD을 읽고 렌더링하고 표시합니다."

############################# Header ############################
title: "VSD C# .NET 애플리케이션용 파일 뷰어" 
description: ".NET 문서 뷰어 API는 모든 유형의 C#, ASP.NET, VB.NET 및 .NET Core 애플리케이션에서 VSD 파일을 읽고 렌더링하고 표시합니다. HTML5, PDF 또는 몇 줄의 코드를 사용하여 이미지로 진정한 형식 및 레이아웃으로 렌더링된 파일을 봅니다." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "무료 평가판 다운로드"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: ".NET API용 GroupDocs.Viewer 정보" 
    content: |
        몇 줄의 코드를 추가하여 .NET API용 GroupDocs.Viewer를 사용하여 .NET 애플리케이션에서 190개 이상의 인기 있는 문서 형식을 볼 수 있습니다. 개발자는 HTML5, 이미지 또는 PDF 모드에서 PDF, 워드 프로세싱, Excel 스프레드시트, 프레젠테이션, Visio, 프로젝트, Outlook 및 기타 널리 사용되는 문서 형식을 쉽게 표시할 수 있습니다. 문서 렌더링은 빠르고 원본 소스 파일과 동일하며 추가 소프트웨어나 기타 외부 라이브러리를 설치할 필요가 없습니다.

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
    title_left: "C#에서 VSD 파일을 렌더링하는 단계" 
    content_left: |
        [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/)를 사용하면 몇 단계 만에 VSD을 HTML, JPEG, PNG 또는 PDF로 렌더링할 수 있습니다.

        * 원하는 패키지 관리자를 사용하여 [.NET용 GroupDocs.Viewer](https://www.nuget.org/packages/groupdocs.viewer)를 설치합니다. 
        * Viewer 클래스의 인스턴스를 생성하고 전체 경로로 VSD 파일을 로드합니다. 
        * VSD 파일을 HTML, PNG, JPEG 또는 PDF 형식으로 렌더링하는 옵션을 설정합니다. 
        * 파일을 렌더링하고 현재 디렉터리에서 출력을 확인합니다. 
        
    title_right: "시스템 요구 사항" 
    content_right: |
        .NET API용 GroupDocs.Viewer는 모든 주요 플랫폼 및 운영 체제에서 지원됩니다. 아래 코드를 실행하기 전에 시스템에 다음 필수 구성 요소가 설치되어 있는지 확인하십시오.

        * 운영 체제: 마이크로소프트 윈도우, 리눅스, 맥OS 
        * 개발 환경: Microsoft Visual Studio, Visual Studio Code, .NET CLI 
        * 프레임워크: .NET Framework, .NET Standard, .NET Core, .NET 
    code: |
        ```cs
                        
            // Set up input VSD file
            string filePath = "input.vsd";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render VSD file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "VSD 뷰어 라이브 데모"
    content: |
        지금 바로 [GroupDocs.Viewer 온라인 앱](https://products.groupdocs.app/viewer/vsd) 웹사이트를 방문하여 VSD 파일을 확인하세요.
    lang: "ko"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "기타 파일 형식 C#을 사용한 렌더링 및 보기"
    exclude: "VSD"
    content: |
        .NET용 다중 형식 문서 및 이미지 뷰어 API. 외부 뷰어 없이 아래에서 인기 있는 파일 형식 중 일부를 볼 수 있습니다.
    format: 
        # format loop 1
        - name: "DOCX 렌더링"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word Open XML 문서" 

        # format loop 2
        - name: "렌더링 CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "CorelDRAW 파일" 

        # format loop 3
        - name: "PPTX 렌더링"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint Open XML 프레젠테이션" 

        # format loop 4
        - name: "XLSX 렌더링"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Open XML 스프레드시트" 

        # format loop 5
        - name: "렌더 DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "AutoCAD 도면"

        # format loop 6
        - name: "XML 렌더링"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "XML 파일"

        # format loop 7
        - name: "PSD 렌더링"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "어도비 포토샵 문서"

        # format loop 8
        - name: "Adobe Illustrator 파일 렌더링"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "어도비 일러스트레이터 작품"

        # format loop 9
        - name: "렌더 DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "마이크로소프트 워드 문서" 

        # format loop 10
        - name: "렌더링 TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "일반 텍스트 파일" 

        # format loop 11
        - name: "DXF 렌더링" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "도면 교환 형식 파일"  
          
        # format loop 12
        - name: "VCF 렌더링"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "vCard 파일"  
              
        # format loop 13
        - name: "렌더링 SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "확장 가능한 벡터 그래픽" 
          
        # format loop 14
        - name: "HTML 렌더링"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "하이퍼텍스트 마크업 언어 파일" 
          
        # format loop 15
        - name: "PDF 렌더링"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "휴대용 문서 형식 파일"
          
        # format loop 16
        - name: "JPEG 렌더링"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "JPEG 이미지"
          
        # format loop 17
        - name: "렌더 PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "휴대용 네트워크 그래픽" 
          
        # format loop 18
        - name: "렌더링 EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "이메일 메시지" 
          
        # format loop 19
        - name: "RTF 렌더링"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "서식 있는 텍스트 형식 파일" 
          
        # format loop 20
        - name: "렌더링 ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "OpenDocument 텍스트 문서" 
          
        # format loop 21
        - name: "CSV 렌더링"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "쉼표로 구분된 값 파일" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
