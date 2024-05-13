---
############################# Static ##########################
layout: "family"
date: 2023-12-20T06:39:57
draft: false

product: "Viewer"
product_tag: "viewer"

############################# Head ############################
head_title: "문서 API 렌더링 및 보기 | 온프레미스 API 및 온라인 서비스"
head_description: "Word, PDF, Excel, Powerpoint 또는 이미지 파일을 무료로 쉽게 렌더링 및 보기"

############################# Header ##########################
title: "쉽게 문서를 렌더링하고 확인하세요"
description: |
  다양한 파일을 PDF, HTML 및 이미지로 렌더링하는 강력한 뷰어 API입니다.

  파일, 스트림, URL, FTP 서버, Amazon S3, Azure Blob Storage 등을 포함한 다양한 소스에서 문서를 로드합니다.

  반응형 HTML 페이지를 생성하고, 출력 PDF 파일을 보호하고, 페이지 순서를 변경하고, 페이지를 회전하고, 필요한 경우 메모와 설명을 렌더링합니다.

############################# Platforms ############################
supported_platforms:
  enable: true  
  head_title: "플랫폼을 선택하세요"
  title: "지원되는 플랫폼"
  description: "GroupDocs.Viewer 라이브러리는 다음 운영 체제 및 프레임워크를 지원합니다."
  details_link_title: "더 알아보기"
  items:
    # supported_platforms loop
    - title: ".NET"
      description: "GroupDocs.Viewer for .NET"
      color: "blue"
      tag: "net"
      link: "/viewer/net/"
      features_link: "https://docs.groupdocs.com/viewer/net/system-requirements/"
      features:
        # features loop
        - content: ".NET Framework 4.6.2+  <br>  .NET Core 3.1  <br>  .NET 6+"
          rows: "3"
        # features loop
        - content: "Windows, Linux"
          rows: "1"
        # features loop
        - content: "180개 이상의 파일 형식"
          rows: "1"
        # features loop
        - content: "ASP.NET Core용 UI 패키지"
          rows: "1"
        # features loop
        - content: "ASP.NET WebForms Demo  <br>  ASP.NET MVC Demo  <br>  ASP.NET Core Demo"
          rows: "3"
    
    # supported_platforms loop
    - title: "Java"
      description: "GroupDocs.Viewer for Java"
      color: "red"
      tag: "java"
      link: "/viewer/java/"
      features_link: "https://docs.groupdocs.com/viewer/java/system-requirements/"
      features:
        # features loop
        - content: "J2SE 8.0 (1.8)+"
          rows: "3"
        # features loop
        - content:  "Windows, Linux, macOS"
          rows: "1"       
        # features loop
        - content: "180개 이상의 파일 형식"
          rows: "1"
        # features loop
        - content:  "Spring 및 Dropwizard용 UI 패키지"
          rows: "1"
        # features loop
        - content:  "Spring Demo  <br>  Dropwizard demo"
          rows: "3"

    # supported_platforms loop
    - title: "Node.js"
      description: "GroupDocs.Viewer for Node.js"
      color: "green"
      tag: "nodejs-java"
      link: "/viewer/nodejs-java/"
      features_link: "https://docs.groupdocs.com/viewer/nodejs-java/system-requirements/"
      features:
        # features loop
        - content: "Node.js 16+  <br>  and J2SE 8.0 (1.8)+"
          rows: "3"
        # features loop
        - content:  "Windows, Linux, macOS"
          rows: "1"
        # features loop
        - content:  "180개 이상의 파일 형식"
          rows: "1"
        # features loop
        - content:  "UI 패키지 - 출시 예정"
          rows: "1" 
        # features loop
        - content:  "데모 - 곧 출시 예정"
          rows: "3" 

    # supported_platforms loop
    - title: "Python"
      description: "GroupDocs.Viewer for Python"
      color: "yellow"
      tag: "python-net"
      link: "/viewer/python-net/"
      features_link: "https://docs.groupdocs.com/viewer/python-net/system-requirements/"
      features:
        # features loop
        - content: "Python 3.9+  <br>  and .Net 6+"
          rows: "3"
        # features loop
        - content:  "Windows, Linux, macOS"
          rows: "1"
        # features loop
        - content:  "180개 이상의 파일 형식"
          rows: "1"
        # features loop
        - content:  "UI 패키지 - 출시 예정"
          rows: "1" 
        # features loop
        - content:  "데모 - 곧 출시 예정"
          rows: "3" 

############################# Features ############################

features:
  enable: true
  title: "GroupDocs.Viewer의 기능 세트"
  description: "타사 소프트웨어 없이 볼 수 있도록 애플리케이션에서 HTML, PDF, PNG 및 JPEG와 같은 다양한 유형의 파일을 렌더링하는 API입니다."

  items:
    # feature loop
    - icon: "view"
      title: "문서 및 이미지 보기"
      content: "문서를 HTML, PDF, PNG 및 JPEG 파일로 렌더링하여 봅니다."

    # feature loop
    - icon: "password"
      title: "보안 문서 열기"
      content: "암호화된 문서를 열려면 비밀번호를 지정하세요."

    # feature loop
    - icon: "load"
      title: "어디서나 파일 로드"
      content: "다양한 파일, URL, FTP 서버, Amazon S3 등에서 문서를 로드하세요."
    
    # feature loop
    - icon: "pages"
      title: "전체 또는 특정 페이지 렌더링"
      content: "렌더링할 페이지 번호 범위를 지정합니다."


############################# Code samples ############################
code_samples:
  enable: true
  title: "GroupDocs.Viewer 코드 샘플"
  description: "C#, Java, TypeScript의 일반적인 GroupDocs.Viewer 작업의 일부 사용 사례"
  items:
    # code sample loop
    - title: "DOCX 파일을 PDF로 렌더링하는 방법"
      content: |
       Microsoft Word나 기타 소프트웨어를 설치하지 않고도 DOCX 문서를 PDF로 렌더링할 수 있습니다. 웹 애플리케이션이든 데스크탑 애플리케이션이든 관계없이 .NET 애플리케이션 내에서 DOCX 파일을 쉽게 로드하고 볼 수 있습니다. 다음은 DOCX 파일을 PDF로 렌더링하는 방법의 예입니다.
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // 렌더링할 DOCX 파일 로드
            using (Viewer viewer = new Viewer("sample.docx"))
            {
              // DOCX를 PDF 파일로 렌더링
              PdfViewOptions viewOptions = new PdfViewOptions();
              viewer.View(viewOptions);
            }
            ```
        - language: "Java"
          color: "red"
          content: |
            ```java {style=abap}   
            import com.groupdocs.viewer.Viewer;
            import com.groupdocs.viewer.options.PdfViewOptions;
            // ...
            // 렌더링할 DOCX 파일 로드
            try (Viewer viewer = new Viewer("sample.docx")) {
                // DOCX를 PDF 파일로 렌더링
                PdfViewOptions viewOptions = new PdfViewOptions();
                viewer.view(viewOptions);
            }
            ```
        - language: "TypeScript"
          color: "green"
          content: |
            ```javascript {style=abap}  
            // 렌더링할 DOCX 파일 로드
            const viewer = new groupdocs.viewer.Viewer("sample.docx")
            
            // DOCX를 PDF 파일로 렌더링
            const viewOptions = groupdocs.viewer.PdfViewOptions(output.pdf)
            viewer.view(viewOptions)
            ```

        - language: "Python"
          color: "yellow"
          content: |
            ```python {style=abap} 
            import groupdocs.viewer as gv
            import groupdocs.viewer.options as gvo   
            // 렌더링할 DOCX 파일 로드
            with gv.Viewer("sample.docx") as viewer:
            
                // DOCX를 PDF 파일로 렌더링
                viewOptions = gvo.PdfViewOptions("output.pdf")
                viewer.view(viewOptions)
            ```

############################# Formats ############################
formats:
  enable: true
  title:  "180개 이상의 파일 형식 지원"
  description: "GroupDocs.Viewer는 가장 널리 사용되는 [파일 형식](https://docs.groupdocs.com/viewer/net/supported-document-formats/) 작업을 지원합니다."


############################# Metrics ############################

metrics:
  enable: true
  title: "심층적인 지표 및 통계적 통찰력"
  description: "당사의 성과, 영향 및 성장에 대한 포괄적인 지표와 통계적 통찰력을 제공하는 주요 수치에 대한 자세한 분석을 살펴보세요."

  items:
    # metrics loop
    - number: "180+"
      title: "지원되는 형식"
      content: "문서, 이미지, CAD 도면을 포함한 180개 이상의 파일 형식을 번거로움 없이 쉽게 볼 수 있습니다. 포괄적인 보기 솔루션을 사용하여 호환성 장벽을 허물고 다양한 파일에 쉽게 액세스하세요."
    # metrics loop
    - number: "1.0M"
      title: "NuGet 다운로드"
      content: "NuGet 패키지 솔루션은 수많은 프로젝트에 원활한 통합과 귀중한 기능을 제공하여 개발자 커뮤니티에서 신뢰할 수 있고 널리 채택되는 리소스가 되었습니다."

    # metrics loop
    - number: "10+"
      title: "도서관"
      content: "우리 제품에는 성능 최적화를 위한 고급 기능을 제공하는 10개 이상의 라이브러리가 포함되어 있습니다. 이러한 라이브러리는 비교할 수 없는 기능으로 다양한 개발 요구 사항을 충족하도록 설계되었습니다."
    
    # metrics loop
    - number: "100+"
      title: "행복한 고객"
      content: "전 세계에서 가장 상징적인 브랜드에 서비스를 제공합니다. 수백 명이 GroupDocs.Viewer를 좋아하는 이유를 알아보세요! 원활한 탐색, 편리한 공동작업, 비교할 수 없는 사용 편의성을 살펴보세요. 지금 가입하세요!"


############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "우리의 행복한 고객"
  description: "GroupDocs 라이브러리는 전 세계적으로 유명하고 뛰어난 브랜드에서 사용됩니다."

  items:
    # customers loop
    - title: "BenQ Corporation"
      logo: "benq"
    # customers loop
    - title: "Nasdaq Stock Market"
      logo: "nasdaq"
    # customers loop
    - title: "AT&T Inc."
      logo: "att"
    # customers loop
    - title: "AstraZeneca"
      logo: "astrazeneca"
    # customers loop
    - title: "Central Bank of Argentina"
      logo: "argentinacentralbank"
    # customers loop
    - title: "Roche Holding AG"
      logo: "roche"
    # customers loop
    - title: "Capita"
      logo: "capita"
    # customers loop
    - title: "Axa S.A."
      logo: "axa"
    # customers loop
    - title: "Instructure Inc."
      logo: "instructure"
     # customers loop
    - title: "Wipro"
      logo: "wipro"



############################# Actions ############################

actions:
  enable: true
  title: "시작할 준비가 되셨나요?"
  description: "GroupDocs.Viewer 기능을 무료로 사용해 보거나 라이선스를 요청하세요"

  items:
    #  loop
    - title: ".NET"
      link: "/viewer/net/"
      color: "blue"
        #  loop
    - title: "Java"
      link: "/viewer/java/"
      color: "red"
        #  loop
    - title: "Node.js"
      link: "/viewer/nodejs-java/"
      color: "green"
        #  loop
    - title: "Python"
      link: "/viewer/python-net/"
      color: "yellow"

############################# Faq ############################

faq:
  enable: true
  title: "일반적인 질문과 우려 사항"
  description: "자주 묻는 질문(FAQ) 섹션에서 일반적인 문의에 대한 답변을 찾아 문의 사항과 우려 사항을 빠르게 해결하세요."

  items:
    #  loop
    - question: "구매하기 전에 GroupDocs 제품을 평가할 수 있습니까?"
      answer: |
        예! 모든 GroupDocs 제품에는 위험이 없는 평가판이 제공됩니다. 우리는 개발자들이 귀하의 요구 사항을 100% 충족할 수 있도록 구매하기 전에 API를 다운로드하고 사용해 볼 것을 강력히 권장합니다.
    #  loop
    - question: "GroupDocs에서는 제품 시연을 합니까?"
      answer: |
        아니요, 우리의 초점은 API와 가장 기능적이고 안정적인 제품을 만드는 것입니다. 우리는 [임시 라이선스](https://purchase.groupdocs.com/temporary-license/) 형태로 모든 기능을 갖춘 무료 평가판을 제공하므로 직접 제품을 테스트해 볼 수 있습니다.
    #  loop
    - question: "제품은 어디서 다운로드할 수 있나요?"
      answer: |
        모든 제품은 [웹사이트](https://releases.groupdocs.com)에서 다운로드할 수 있습니다. 우리는 소프트웨어의 물리적 사본을 우편으로 보내지 않습니다.    
    #  loop
    - question: "GroupDocs 개발자 라이센스는 사용자별인가요, 아니면 지정된 사용자별인가요?"
      answer: |
        GroupDocs 개발자 라이센스는 지정 사용자별이 아닌 사용자별입니다. 우리는 코딩 팀의 구성원이 시간이 지남에 따라 변경될 수 있으며 발생할 때마다 라이선스를 업데이트하는 것이 실용적이지 않다는 것을 알고 있습니다.
    #  loop
    - question: "활동 중인 개발자에게만 라이선스가 필요합니까? 예를 들어, 두 명의 개발자로 구성된 팀이 A 교대 근무를 하고 두 번째 개발자 두 팀이 교대 B 근무를 하고 있습니다. 이 상황에서 라이선스가 2개 또는 4개가 필요합니까?"
      answer: |
        프로젝트에 참여하는 모든 개발자는 라이선스를 취득해야 합니다. 이 상황에서 GroupDocs는 팀 구성원이 4명인 것으로 간주합니다(그들이 서로 다른 시간에 일하더라도).

############################# Cloud ############################

cloud_links:
  enable: true
  title: "GroupDocs.Viewer 로우 코드 API"
  description: "클라우드 기반 REST API를 사용하여 모든 유형의 애플리케이션에서 문서 또는 이미지 보기를 가속화하세요."

  items:
    #  loop
    - icon: "groupdocs_viewer-for-curl"
      title: "GroupDocs.Viewer Cloud for cURL"
      link: "https://products.groupdocs.cloud/viewer/curl"
      content: "cURL RESTful 문서 뷰어 API를 사용하여 애플리케이션에서 Microsoft Office, PDF 및 기타 다양한 표준 파일 형식을 효율적으로 렌더링하고 선보일 수 있습니다."

    #  loop
    - icon: "groupdocs_viewer-for-net"
      title: "GroupDocs.Viewer Cloud for .NET"
      link: "https://products.groupdocs.cloud/viewer/net"
      content: ".NET용 Cloud SDK를 사용하여 .NET 애플리케이션의 문서 보기 기능을 향상하세요. HTML, PDF 또는 이미지 형식으로 문서를 원활하게 볼 수 있습니다."
    #  loop
    - icon: "groupdocs_viewer-for-java"
      title: "GroupDocs.Viewer Cloud for Java"
      link: "https://products.groupdocs.cloud/viewer/java"
      content: "특별히 제작된 Java용 Document Viewer SDK를 사용하여 고급 문서 렌더링 기능을 Java 애플리케이션에 통합하세요."

############################# Apps ############################

app_links:
  enable: true
  title: "GroupDocs.Viewer NoCode 앱"
  description: "브라우저에서 180개 이상의 인기 있는 파일 형식을 볼 수 있는 온라인 애플리케이션"

  items:
    #  loop
    - icon: "groupdocs_viewer-app"
      title: "GroupDocs.Viewer Total"
      link: "https://products.groupdocs.app/viewer/total"
      content: "무료 온라인 애플리케이션을 탐색하여 선호하는 웹 브라우저에서 직접 180개 이상의 파일 형식을 확인하세요."

    #  loop
    - icon: "groupdocs_words-app"
      title:  "GroupDocs.Viewer DOCX"
      link: "https://products.groupdocs.app/viewer/docx"
      content: "다양한 장치에서 Microsoft Word 파일을 쉽게 볼 수 있는 웹 기반 도구입니다."

    #  loop
    - icon: "groupdocs_pdf-app"
      title:  "GroupDocs.Viewer PDF"
      link: "https://products.groupdocs.app/viewer/pdf"
      content: "무료 PDF 뷰어를 사용하여 온라인으로 PDF 파일을 열고 봅니다."
    

---