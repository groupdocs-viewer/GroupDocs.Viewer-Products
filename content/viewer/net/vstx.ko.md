---
############################# Static ############################
layout: "format"
date: 2024-04-10T13:10:19
draft: false
lang: ko
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head #############################
head_title: ".NET VSTX 뷰어 API - C# VB.NET에서 읽기, 보기, 렌더링"
head_description: "모든 유형의 C#, ASP.NET, VB.NET 및 .NET Core 애플리케이션에서 VSTX을 읽고 렌더링하고 표시하는 .NET 문서 뷰어 API입니다."

############################# Header ############################
title: "C# .NET 애플리케이션용 VSTX 파일 뷰어" 
description: "모든 유형의 C#, ASP.NET, VB.NET 및 .NET Core 애플리케이션에서 VSTX 파일을 읽고, 렌더링하고 표시하는 .NET 문서 뷰어 API입니다. HTML5, PDF 또는 몇 줄의 코드를 사용하여 이미지로 실제 형식 및 레이아웃으로 렌더링된 파일을 봅니다." 
subtitle: "문서 렌더링 솔루션" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "무료 너겟 다운로드"
      link: "https://nuget.org/packages/GroupDocs.Viewer"



############################# About ############################
about:
    enable: true
    title: ".NET API용 GroupDocs.Viewer 정보"
    link: "/viewer/net/"
    link_title: "더 알아보기"
    picture: "about_viewer.svg" # 480 X 400
    content: |
      몇 줄의 코드를 추가하면 .NET용 GroupDocs.Viewer API를 사용하여 .NET 응용 프로그램에서 190개 이상의 인기 있는 문서 형식을 볼 수 있습니다. 개발자는 PDF, 워드 프로세싱, Excel 스프레드시트, 프리젠테이션, Visio, Project, Outlook 및 기타 널리 사용되는 문서 형식을 HTML5, 이미지 또는 PDF 모드로 쉽게 표시할 수 있습니다. 문서 렌더링은 빠르고 원본 소스 파일과 동일하며 추가 소프트웨어나 기타 외부 라이브러리를 설치할 필요가 없습니다.



############################# Steps ############################
steps:
    enable: true
    title: "C#에서 VSTX 파일을 렌더링하는 단계" 
    content: |
      <a href='https://products.groupdocs.com/viewer/net/'>GroupDocs.Viewer</a>를 사용하면 몇 단계만으로 VSTX을(를) HTML, JPEG, PNG 또는 PDF로 렌더링할 수 있습니다.
      
      1. 선호하는 패키지 관리자를 사용하여 <a href='https://www.nuget.org/packages/groupdocs.viewer'>GroupDocs.Viewer for .NET</a>을 설치하세요. 
      2. Viewer 클래스의 인스턴스를 생성하고 전체 경로와 함께 VSTX 파일을 로드합니다.  
      3. VSTX 파일을 HTML, PNG, JPEG 또는 PDF 형식으로 렌더링하는 옵션을 설정합니다. 
      4. 파일을 렌더링하고 현재 디렉터리에서 출력을 확인합니다. 
   
    code:
      platform: "net"
      copy_title: "복사"
      install:
        command: "dotnet add package GroupDocs.Viewer"
        copy_tip: "복사하려면 클릭하세요"
        copy_done: "복사됨"
      links:
        #  loop
        - title: "더 많은 예시"
          link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
        #  loop
        - title: "선적 서류 비치"
          link: "https://docs.groupdocs.com/viewer/net/"
          
      content: |
        ```csharp {style=abap}

        // 입력 VSTX 파일 설정
        string filePath = "input.vstx";

        // GroupDocs.Viewer 인스턴스화
        using (Viewer viewer = new Viewer(filePath))
        {
            // 보기 옵션 설정
            HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                
            // 포함된 리소스가 있는 HTML로 VSTX 파일을 렌더링합니다.
            viewer.View(viewOptions);
        }

        ```            


############################# Actions ############################

actions:
  enable: true
  title: "시작할 준비가 되셨나요?"
  description: "GroupDocs.Viewer 기능을 무료로 사용해 보거나 라이선스를 요청하세요"
  items:
    #  loop
    - title: "너겟 다운로드"
      link: "https://nuget.org/packages/GroupDocs.Viewer"
      color: "red"
        #  loop
    - title: "라이선스"
      link: "https://purchase.groupdocs.com/pricing/viewer/net/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "C#을 사용하여 다른 파일 형식을 렌더링합니다."
    exclude: "VSTX"
    description: ".NET용 다중 형식 문서 및 이미지 뷰어 API. 외부 뷰어 없이 아래의 인기 있는 파일 형식 중 일부를 확인하세요."
    items: 
        # format loop 1
        - name: "DOCX 렌더링"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word Open XML Document" 

        # format loop 2
        - name: "렌더 CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "CorelDRAW File" 

        # format loop 3
        - name: "PPTX 렌더링"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint Open XML Presentation" 

        # format loop 4
        - name: "XLSX 렌더링"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet" 

        # format loop 5
        - name: "DWG 렌더링"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "AutoCAD Drawing"

        # format loop 6
        - name: "XML 렌더링"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "XML File"

        # format loop 7
        - name: "PSD 렌더링"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Adobe Photoshop Document"

        # format loop 8
        - name: "렌더 AI"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Adobe Illustrator Artwork"

        # format loop 9
        - name: "렌더링 DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Microsoft Word Document" 

        # format loop 10
        - name: "TXT 렌더링" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Plain Text File" 

        # format loop 11
        - name: "DXF 렌더링" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Drawing Exchange Format File"  
          
        # format loop 12
        - name: "VCF 렌더링"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "vCard File"  
              
        # format loop 13
        - name: "SVG 렌더링"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Scalable Vector Graphic" 
          
        # format loop 14
        - name: "HTML 렌더링"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "PDF 렌더링"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Portable Document Format File"
          
        # format loop 16
        - name: "JPEG 렌더링"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "JPEG Image"
          
        # format loop 17
        - name: "PNG 렌더링"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Portable Network Graphic" 
          
        # format loop 18
        - name: "EML 렌더링"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "E-Mail Message" 
          
        # format loop 19
        - name: "RTF 렌더링"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Rich Text Format File" 
          
        # format loop 20
        - name: "ODT 렌더링"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "OpenDocument Text Document" 
          
        # format loop 21
        - name: "CSV 렌더링"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Comma-Separated Values File" 



---
