---
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

head_title: ".NET 문서 뷰어 API, PDF Word Excel 이미지 HTML 다이어그램 렌더링"
head_description: "C# ASP.NET 파일 뷰어 및 렌더링 API. .NET 앱에 PDF 뷰어, Word 뷰어, Excel 뷰어, 이미지 뷰어, HTML 뷰어, 이메일 뷰어 기능 추가."

title: ".NET API를 통한 문서 렌더링 및 표시"
description: ".NET Document Viewer API를 사용하여 강력한 구성 옵션을 사용하여 170개 이상의 문서 형식을 PDF, HTML 및 이미지로 렌더링."
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "무료 평가판 다운로드"
    link: "https://downloads.groupdocs.com/viewer/net"

submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Viewer for .NET"
        image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-viewer-net.png"
        product: "GroupDocs.Viewer"
        platform: ".NET"

    middle:
        button:
            - link: "#overview"
              text: "개요"

            - link: "#features"
              text: "특징"

            - link: "#support"
              text: "지원하다"

            - link: "https://products.groupdocs.app/viewer"
              text: "라이브 데모"

            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "가격"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net/"
        link_buy: "https://purchase.groupdocs.com"

overview:
    enable: true
    content: |
      .NET API용 GroupDocs.Viewer는 C#, ASP.NET 및 기타 .NET 기반 기술로 강력한 응용 프로그램을 만드는 데 도움이 됩니다. 이 응용 프로그램은 외부 소프트웨어를 설치하지 않고도 170개 이상의 파일 형식의 문서와 이미지를 렌더링하고 표시할 수 있습니다. 파일 뷰어 라이브러리는 문서를 래스터화한 다음 SVG+HTML+CSS로 변환하여 전체 문서 렌더링 경험을 최적화하여 비즈니스 문서, 이미지, 텍스트 파일, 다이어그램, 그래픽, 이메일 첨부 파일 및 PDF 파일을 속도, 실제 텍스트 및 애플리케이션 내부의 충실도. 지원되는 파일 형식에 대한 주석 및 주석이 있거나 없는 전체 문서, 부분 문서, 특정 페이지/셀 범위, 개별 문서 레이어를 표시하기 위해 애플리케이션에 문서 보기 및 읽기 기능을 추가할 수 있는 옵션이 있습니다.  

      .NET용 GroupDocs.Viewer는 기본적으로 렌더링된 문서 출력을 로컬 디스크에 캐시합니다. Amazon S3, Dropbox, Google Drive, Windows Azure, Redis 등의 적절한 인터페이스를 구현하여 모든 유형의 외부 캐시 스토리지도 지원합니다.
    tabs:
      enable: true
      
      tab_one:
        description: |
          다음은 .NET용 GroupDocs.Viewer의 개요입니다.
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "개요"
          content: |
            * 170개 이상의 문서 유형 표시
            * HTML, 이미지, PDF 버전 받기
            * 회전 및 재 주문
            * 워터마크 적용
            * 빠른 처리를 위한 캐시
            * 사용자 정의 글꼴 추가
            * 인코딩 표준 적용
            * 사용자 정의 입력 데이터 핸들러
            * 변경 내용 추적으로 렌더링
            * 반응형 HTML로 렌더링
            * PDF 렌더링 및 CAD 레이어
      
      tab_two:
        description: |
          .NET용 GroupDocs.Viewer는 모든 인기 있는 [문서 파일 형식](https://docs.groupdocs.com/viewer/net/supported-document-formats/) 보기를 지원합니다. 몇 줄의 코드로 PDF 뷰어, Microsoft Office Word, Excel 스프레드시트, 이미지, HTML, Outlook 전자 메일, OneNote, 프로젝트 및 그래픽 보기 기능을 .NET 응용 프로그램에 추가할 수 있습니다.

        left:
          enable: true
          table:
            - title: "마이크로 소프트 오피스"
              content: |
                * **단어:** DOC, DOCX, DOCM, DOT, DOTX, DOTM, RTF, TXT
                * **엑셀:** XLS, XLSX, XLSM, XLSB, XLTM, XLT, XLTM, XLTX, XLAM, SXC, SpreadsheetML
                * **파워포인트:** PPT, PPTX, PPS, PPSX, PPSM, POT, POTM, POTX, PPTM
                * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
                * **프로젝트:** MPP, MPT, MPX
                * **전망:** MSG, EML, EMLX, PST, OST
                * **원노트:** ONE

            - title: "기타 형식"
              content: |
                * **PDF 형식:** PDF, TEX, XPS, OXPS
                * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG, OTG, FODP, FODG
                * **구분 기호로 구분된 값:** CSV, TSV
                * **웹:** HTML, MHT, MHTML
                * **메타파일:** WMF, EMF, CGM, WMZ, EMZ
                * **포스트스크립트:** PS, EPS
                * **아카이브:** ZIP, TAR, BZ2, GZ, RAR, RAR5
                * **다양한:** OBJ, EPUB, MOBI, DjVu, XML, VCF, VCARD, NUMBER, NSF

        right:
          enable: true
          table:
            - title: "이미지, 그래픽 및 다이어그램"
              content: |
                * **이미지:** BMP, GIF, JPG, PNG, TIFF, 다중 페이지 TIFF, WebP, DNG, DIB, DCM
                * **Windows 아이콘:** ICO
                * **확장 가능한 벡터 그래픽:** SVG, CDR, CMX, IGS, SVGZ
                * **Jpeg2000:** JP2, J2C, J2K, JPC, JPF, JPX, JPM
                * **어도비 포토샵:** PSD, PSB
                * **프린터 명령 언어:** PCL
                * **스테레오 리소그래피(3D 프린팅):** STL
                * **산업 기초 수업:** IFC
                * **의료 영상:** DICOM
                * **플로터 문서:** PLT, HPG
                * **Autodesk Design 웹 형식:** DWF, DWG
                * **AutoCAD 도면:** DGN, DWT, IFC, STL, CF2
                * **ISFF 기반 DGN(V7):** DGN

            - title: "프로그래밍 언어 형식"
              content: |
                * **C/C++/C# 파일:** C, CC, CS, CPP, CXX, C#, H, HH, M, MM
                * **자바/자바스크립트 파일:** 자바, JS, JSON, 속성
                * **다양한:** VB, PHP, SQL, PL, PY, PV, RB, RST, SASS, SCALA, SCM, SCRIPT, AS, AS3, ASM, BAT, CMAKE, CSS, DIFF, ERB, GROOVY, HAML , 적게, 로그, M, 만들기, MD, ML, MM, SH, SML, VIM, YAML

      tab_three:
        description: |
          .NET용 GroupDocs.Viewer는 다음 운영 체제, 프레임워크 및 패키지 관리자를 지원합니다.
        
        left:
          enable: true
          table:
            - icon: "fab fa-windows"
              title: "운영체제"
              content: |
                * 윈도우 데스크탑
                * 윈도우 서버
                * 마이크로소프트 애저
                * 리눅스

            - icon: "fas fa-code"
              title: "지원되는 프레임워크"
              content: |
                * .NET 프레임워크 2.0 이상
                * .NET 코어 3.1
                * .NET 5 이상

        right:
          enable: true
          table:
            - icon: "fas fa-box"
              title: "패키지 관리자"
              content: |
                * 누겟

            - icon: "fas fa-tools"
              title: "개발 환경"
              content: |
                * 마이크로소프트 비주얼 스튜디오
                * 비주얼 스튜디오 코드
                * .NET CLI

features:
    enable: true
    title: ".NET 기능용 GroupDocs.Viewer"

    feature:
      - icon: "fas fa-copy"
        content: "문서를 래스터화하고 SVG, HTML 및 CSS로 변환"

      - icon: "fas fa-eye"
        content: "텍스트를 HTML로 변환하고 문서를 렌더링하여 HTML, 이미지 또는 PDF 표현 얻기"

      - icon: "fas fa-bolt"
        content: "문서의 캐시된 버전을 사용하여 더 빠른 로딩 시간"
      
      - icon: "fas fa-file-powerpoint"
        content: "3D 효과로 모양과 텍스트가 있는 프레젠테이션 변환"

      - icon: "fas fa-code"
        content: "Word, Excel 및 이메일 문서를 원하는 인코딩 표준으로 인코딩"

      - icon: "fas fa-cloud"
        content: "FTP 또는 Cloud Storage 위치에 있는 렌더링 문서"

      - icon: "fas fa-remove-format"
        content: "결과 파일 크기를 줄이기 위해 HTML로 렌더링할 때 글꼴 제외"

      - icon: "fas fa-comment-slash"
        content: "주석, 추가 공백 등을 제거하여 CSS 및 HTML 출력 최소화."

      - icon: "fas fa-location-arrow"
        content: "좌표를 통해 소스 문서에 포함된 텍스트 읽기"

      - icon: "fas fa-border-all"
        content: "출력 표현에서 Excel 시트의 격자선 표시/숨기기"

      - icon: "fas fa-wrench"
        content: "각 페이지에 렌더링할 Excel 시트의 행 수 지정"

      - icon: "fas fa-columns"
        content: "스프레드시트 문서를 렌더링하는 동안 빈 열 무시"

      - icon: "fas fa-file-word"
        content: "변경 내용 추적을 사용하여 Word 문서를 HTML 페이지, 이미지 또는 PDF로 렌더링"

      - icon: "fas fa-envelope"
        content: "이메일 첨부 파일을 원본 파일, 이미지 또는 HTML 표현으로 렌더링"

      - icon: "fas fa-print"
        content: "PDF 문서에 대한 인쇄 제한 설정"

      - icon: "fas fa-file-archive"
        content: "ZIP 아카이브에 포함된 콘텐츠/파일을 첨부 파일로 렌더링"

      - icon: "fas fa-lock"
        content: "암호로 보호된 문서에서 첨부 파일 얻기"

      - icon: "fas fa-file-code"
        content: "프로그래밍 언어 파일 형식을 일반 텍스트로 렌더링"
      
      - icon: "fas fa-fill-drip"
        content: "CAD 도면을 볼 때 배경색 조정"

      - icon: "fas fa-file-excel"
        content: "Excel 문서 보기 및 PDF, HTML, JPG 및 PNG로 변환"

      - icon: "fas fa-heading"
        content: "Excel 파일에서 워크시트 이름 가져오기 - 스프레드시트 열 머리글 및 행 번호 표시"

      - icon: "fas fa-project-diagram"
        content: "메모가 있는 Microsoft Project 문서 보기 및 변환"

      - icon: "fas fa-cube"
        content: "더 나은 보기 및 확대/축소 경험을 위해 CAD 도면을 SVG로 변환"

      - icon: "fab fa-uncharted"
        content: "구성표 없이 Visio Figure를 렌더링하도록 선택"

    more_feature:
      - title: "효율적이고 안정적으로 문서 보기"
        content: |
          GroupDocs.Viewer API를 사용하면 콘텐츠 및 문서 구조 무결성을 그대로 유지하면서 170개 이상의 문서 형식을 효율적이고 안정적으로 표시할 수 있습니다. 다음 샘플 코드는 DOCX 문서의 HTML 표현을 보는 것이 얼마나 쉬운지를 보여줍니다.

          ```cs
          // 뷰어 인스턴스화
          using (Viewer viewer = new Viewer("sample.docx")
          {
              // 보기 옵션 설정
              HtmlViewOptions options = HtmlViewOptions.ForEmbeddedResources();
              // 포함된 리소스를 사용하여 파일을 HTML로 변환
              viewer.View(options);
          }
          ```
      - title: "렌더링된 출력에 변환 적용"
        content: "GroupDocs.Viewer for .NET API를 사용하여 렌더링된 출력 문서에 다양한 변환을 수행할 수 있습니다. 이러한 변환 옵션을 사용하면 렌더링된 출력을 표시할 방법을 제어할 수 있습니다. 사용 가능한 변환은 페이지 회전 옵션, 페이지 재정렬 옵션 및 텍스트 워터마크 적용입니다.."

      - title: "Outlook 데이터 파일 작업"
        content: ".NET API용 GroupDocs.Viewer는 Outlook 데이터 파일(OST/PST)의 항목을 PDF, HTML 및 이미지 파일로 렌더링할 수 있습니다. 뷰어 API에는 Outlook 데이터 파일에 포함된 폴더 목록을 얻을 수 있는 기능도 있습니다. GroupDocs.Viewer for .NET API를 사용하여 Outlook 데이터 파일에서 렌더링할 폴더를 지정할 수 있습니다. 마찬가지로 OST/PST 형식에 포함된 이메일 메시지를 첨부 파일로 얻을 수도 있습니다. .NET용 GroupDocs.Viewer를 사용하면 제목, 콘텐츠 또는 보낸 사람을 기반으로 OST/PST 형식의 메시지를 필터링할 수도 있습니다.."

      - title: "CAD 문서 작업"
        content: ".NET API용 GroupDocs.Viewer는 모델 및 비어 있지 않은 모든 레이아웃을 렌더링하거나 CAD 파일의 특정 레이아웃을 렌더링할 수 있습니다. .NET API용 GroupDocs.Viewer는 또한 CAD 문서의 좌표에 의한 이미지, HTML 또는 PDF로의 렌더링 또는 타일링을 지원합니다. CAD 문서의 레이어 상태도 얻을 수 있습니다.."

testimonials:
  enable: true

  testimonial:
    - name: "Mats Oustad"
      designation: "Senior Consultant/Partner at Novanet AS"
      content: "프로젝트에서 .NET용 GroupDocs.Viewer를 구현하고 사용한 후에는 매우 잘 작동하는 것으로 보입니다. 나는 많은 문서로 테스트했고 지금까지 아주 좋습니다. 내가 던진 모든 것이 멋지게 렌더링되고 PDF 뷰어 또는 MS Word에서와 마찬가지로 멋지게 보입니다.."
              
    - name: "Martin Lasarga"
      designation: "Product Manager at Axentria ECM by G.S.I."
      content: "우수한 서비스와 우수한 제품. GroupDocs.Viewer for .NET 구현 프로세스 동안 매우 유용하고 반응이 좋았습니다. 충분히 추천할 수 없습니다.."

support:
    enable: true

solutions:
    enable: true
    title: "GroupDocs.Viewer는 다른 인기 있는 개발 환경을 위한 문서 보기 API를 제공합니다."

    solution:
        - img_alt: "GroupDocs.Viewer for Java"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-viewer-java.png"
          product: "GroupDocs.Viewer"
          platform: "Java"
          link: "/viewer/java/"

back_to_top:
  enable: true
---
