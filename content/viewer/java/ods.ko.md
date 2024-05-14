---
############################# Static ############################
layout: "format"
date: 2024-05-14T11:12:40
draft: false
lang: ko
product: "Viewer"
product_tag: "viewer"
platform: "Java"
platform_tag: "java"

############################# Head #############################
head_title: "Java ODS 뷰어 API - Java 앱에서 ODS 렌더링 및 표시"
head_description: "Java, J2EE, J2SE 애플리케이션에서 ODS 파일을 봅니다. 문서 보기 옵션을 관리하는 고급 기능을 통해 HTML, PDF 또는 이미지 모드에서 180개 이상의 문서 및 이미지 파일 형식 보기를 지원합니다."

############################# Header ############################
title: "Java에서 ODS 렌더링 및 보기" 
description: "Java, J2EE 및 J2SE 기반 애플리케이션을 위한 기본 및 고성능 ODS 파일 뷰어 API로, 출력 문서 형식의 모양을 사용자 정의하기 위한 광범위한 추가 기능을 지원합니다." 
subtitle: "문서 렌더링 솔루션" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "무료 메이븐 다운로드"
      link: "https://releases.groupdocs.com/viewer/java/"



############################# About ############################
about:
    enable: true
    title: "Java API용 GroupDocs.Viewer 정보"
    link: "/viewer/java/"
    link_title: "더 알아보기"
    picture: "about_viewer.svg" # 480 X 400
    content: |
      추가 소프트웨어를 설치하지 않고도 Java API용 GroupDocs.Viewer를 사용하여 Java 응용 프로그램이 HTML, PDF 또는 이미지 모드로 180개 이상의 파일 형식을 표시할 수 있도록 합니다. Microsoft Office, Apache Open Office, Adobe Acrobat Reader 등과 같은 개발자는 Microsoft Office, OpenDocument, HTML, PDF, 아카이브, 다이어그램, Photoshop, AutoCAD 및 Java 응용 프로그램 내의 프로그래밍 언어 형식을 포함하여 널리 사용되는 모든 이미지와 문서 유형을 쉽게 볼 수 있습니다. 빠르고 최고 품질의 렌더링.



############################# Steps ############################
steps:
    enable: true
    title: "Java에서 ODS 파일을 렌더링하는 단계" 
    content: |
      <a href='https://products.groupdocs.com/viewer/java/'>GroupDocs.Viewer</a>를 사용하면 몇 단계만으로 ODS을(를) HTML, JPEG, PNG 또는 PDF로 렌더링할 수 있습니다.
      
      1. <a href='https://releases.groupdocs.com/viewer/java/'>GroupDocs.Viewer for Java</a>를 프로젝트에 대한 종속성으로 추가하세요. 
      2. Viewer 클래스의 인스턴스를 생성하고 전체 경로와 함께 ODS 파일을 로드합니다.  
      3. ODS 파일을 HTML, PNG, JPEG 또는 PDF 형식으로 렌더링하는 옵션을 설정합니다. 
      4. 파일을 렌더링하고 현재 디렉터리에서 출력을 확인합니다. 
   
    code:
      platform: "java"
      copy_title: "복사"
      install:
        command: |
          <dependencies>
            <dependency>
              <groupId>com.groupdocs</groupId>
              <artifactId>groupdocs-viewer</artifactId>
              <version>{0}</version>
            </dependency>
          </dependencies>

          <repositories>
            <repository>
              <id>repository.groupdocs.com</id>
              <name>GroupDocs Repository</name>
              <url>https://repository.groupdocs.com/repo/</url>
            </repository>
          </repositories>
        copy_tip: "복사하려면 클릭하세요"
        copy_done: "복사됨"
      links:
        #  loop
        - title: "더 많은 예시"
          link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Java"
        #  loop
        - title: "선적 서류 비치"
          link: "https://docs.groupdocs.com/viewer/java/"
          
      content: |
        ```java {style=abap}

        // 입력 ODS 파일 설정
        String filePath = "input.ods";

        // GroupDocs.Viewer 인스턴스화
        try (Viewer viewer = new Viewer(filePath))
        {
            // 보기 옵션 설정
            HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                
            // 포함된 리소스가 있는 HTML로 ODS 파일을 렌더링합니다.
            viewer.view(viewOptions);
        }

        ```
            

############################# Actions ############################

actions:
  enable: true
  title: "시작할 준비가 되셨나요?"
  description: "GroupDocs.Viewer 기능을 무료로 사용해 보거나 라이선스를 요청하세요"
  items:
    #  loop
    - title: "메이븐 다운로드"
      link: "https://releases.groupdocs.com/viewer/java/"
      color: "red"
        #  loop
    - title: "라이선스"
      link: "https://purchase.groupdocs.com/pricing/viewer/java/"
      color: "light"



############################# More Formats #####################
more_formats:
    enable: true
    title: "Java을 사용하여 다른 파일 형식을 렌더링합니다."
    exclude: "ODS"
    description: "Java용 다중 형식 문서 및 이미지 뷰어 API. 외부 뷰어 없이 아래의 인기 있는 파일 형식 중 일부를 확인하세요."
    items: 
        # format loop 1
        - name: "DOCX 렌더링"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Open XML Document" 

        # format loop 2
        - name: "렌더 CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "CorelDRAW File" 

        # format loop 3
        - name: "PPTX 렌더링"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint Open XML Presentation" 

        # format loop 4
        - name: "XLSX 렌더링"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet" 

        # format loop 5
        - name: "DWG 렌더링"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "AutoCAD Drawing"

        # format loop 6
        - name: "XML 렌더링"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "XML File"

        # format loop 7
        - name: "PSD 렌더링"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Adobe Photoshop Document"

        # format loop 8
        - name: "렌더 AI"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Adobe Illustrator Artwork"

        # format loop 9
        - name: "렌더링 DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Microsoft Word Document" 

        # format loop 10
        - name: "TXT 렌더링" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Plain Text File" 

        # format loop 11
        - name: "DXF 렌더링" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Drawing Exchange Format File"  
          
        # format loop 12
        - name: "VCF 렌더링"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "vCard File"  
              
        # format loop 13
        - name: "SVG 렌더링"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Scalable Vector Graphic" 
          
        # format loop 14
        - name: "HTML 렌더링"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "PDF 렌더링"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Portable Document Format File"
          
        # format loop 16
        - name: "JPEG 렌더링"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "JPEG Image"
          
        # format loop 17
        - name: "PNG 렌더링"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Portable Network Graphic" 
          
        # format loop 18
        - name: "EML 렌더링"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "E-Mail Message" 
          
        # format loop 19
        - name: "RTF 렌더링"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Rich Text Format File" 
          
        # format loop 20
        - name: "ODT 렌더링"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "OpenDocument Text Document" 
          
        # format loop 21
        - name: "CSV 렌더링"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Comma-Separated Values File" 


---
