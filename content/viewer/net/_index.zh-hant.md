---
############################# Static ##########################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: zh-hant
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

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
head_title: ".NET 文件檢視器 API，渲染 PDF Word Excel 圖像 HTML 圖表"
head_description: "C# ASP.NET 檔案檢視器和渲染 API。在 .NET 應用程式中新增 PDF 檢視器、Word 檢視器、Excel 檢視器、影像檢視器、HTML 檢視器、電子郵件檢視器功能。"

############################# Header ##########################
title: "使用 .NET API 渲染和顯示文件<br>"
description: "強大的檢視器 API，可透過多種設定選項將 180 多種文件格式呈現為 PDF、HTML 和影像。"
words:
  for: "for"

actions:
  main: "免費 NuGet 下載"
  main_link: "https://www.nuget.org/packages/GroupDocs.Viewer"
  alt: "授權"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/net"
  title: "準備好開始了嗎？"
  description: "免費試用 GroupDocs.Viewer 功能或申請許可證"

release:
  title: "版本 {0} 已發布"
  notes: "看看有什麼新鮮事"
  downloads: "下載"
  link: "https://releases.groupdocs.com/viewer/net/release-notes/latest/"

code:
  title: "在 C# 中渲染 PDF 文件"
  more: "更多範例"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
  install: "dotnet add package GroupDocs.Viewer"
  content: |
    ```csharp {style=abap}   
    // Load the source PDF file
    using (var viewer = new Viewer("resume.pdf"))
    {
        // Set output HTML options, one file per page
        var viewOptions = 
          HtmlViewOptions.ForEmbeddedResources("page_{0}.html");
        
        // Render PDF to HTML with embedded resources
        viewer.View(viewOptions);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Viewer 概覽"
  description: "用於在 .NET 應用程式中渲染、顯示、轉換文件、幻燈片、圖表和許多其他文件類型的 API"
  features:
    # feature loop
    - title: "有效率可靠地檢視文檔"
      content: "透過 GroupDocs.Viewer API，您可以使用靈活且強大的選項將任何支援格式的文件高效呈現為 HTML、JPEG、PNG 和 PDF，同時保持內容和文件結構的完整性。 GroupDocs.Viewer支援.NET Framework 4.6.2和.NET 6.0，它可以在Windows和Linux平台上運作。"

    # feature loop
    - title: "支援最受歡迎的文件和文件格式"
      content: "我們支援渲染180 多種最受歡迎的文件和文件格式，包括Word、Excel、PDF、PowerPoint、OpenDocument 格式系列、檔案、光柵和向量圖像、電子書、程式語言和標記以及許多其他文件類型，包括加密的文件類型受密碼保護的文件。"

    # feature loop
    - title: "可自訂的輸出"
      content: "GroupDocs.Viewer 不僅允許渲染文檔，還可以控制渲染的準確方式、文檔的哪些部分應該渲染或現在渲染、如何渲染，以及對渲染的輸出應用不同的轉換。"

    # feature loop
    - title: "ASP.NET Core 的 UI"
      content: "我們為 ASP.NET Core 提供了一個開源 UI 包，可以在幾分鐘內將其新增至您的專案。 Viewer.UI 套件包含一個基於 Angular 的 Web UI，並提供了一組有用的 API 和資料儲存提供者。"

############################# Platforms ############################
platforms:
  enable: true
  title: "平台獨立性"
  description: "GroupDocs.Viewer for .NET 支援以下作業系統、框架和套件管理器"
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
    - title: "VS Code"
      image: "vs_code"
    # platform loop
    - title: "ReSharper"
      image: "resharper"
    # platform loop
    - title: "macOS"
      image: "finder"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "NuGet"
      image: "nuget"

############################# File formats ############################
formats:
  enable: true
  title: "支援的文件格式"
  description: |
    GroupDocs.Viewer for .NET 支援以下[檔案格式](https://docs.groupdocs.com/viewer/net/supported-document-formats/) 的操作。
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office、OpenDocument 和文字格式
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
        ### 圖像、圖形和圖表
        * **光柵影像:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
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
        ### 其他        
        * **網路:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **檔案:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **其他:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "GroupDocs.Viewer 功能"
  description: "無縫渲染、顯示和轉換 PDF 和 Office 文件"

  items:
    # feature loop
    - icon: "viewhtml"
      title: "查看 HTML 格式的文檔"
      content: "使用 CSS 和 SVG 將任何類型的文檔轉換為 HTML 文檔，可以在任何現代網頁瀏覽器中顯示。"

    # feature loop
    - icon: "rasterize"
      title: "光柵化文檔"
      content: "將任何支援的文件格式光柵化為光柵影像，並具有可調整的影像格式和壓縮品質。"

    # feature loop
    - icon: "sourcecode"
      title: "渲染並突出顯示程式碼"
      content: "支援所有流行的程式設計、腳本和標記語言，能夠解析和突出顯示其語法。"

    # feature loop
    - icon: "convertpdf"
      title: "轉換為 PDF"
      content: "任何支援格式的文件都可以透過可調整的選項輕鬆轉換並儲存為 PDF。"

    # feature loop
    - icon: "transform"
      title: "應用轉換"
      content: "輸出文件可以在渲染過程中進行轉換 - 頁面可以旋轉和/或重新排列，並且文字浮水印可以放置在它們的頂部。"

    # feature loop
    - icon: "adjustment"
      title: "HTML 輸出調整"
      content: "由 GroupDocs.Viewer 產生的輸出 HTML 文件可以進行非常精細的調整：允許使用外部或嵌入資源、回調等儲存到流或檔案。"

    # feature loop
    - icon: "complex"
      title: "支援複雜的文檔結構"
      content: "GroupDocs.Viewer 不僅支援單一文檔，還支援內部包含文件清單或層次結構的文件，例如帶有附件的電子郵件、資料夾內帶有內部文件的 ZIP 存檔、多頁 TIFF 映像等。"

    # feature loop
    - icon: "optimization"
      title: "最佳化選項"
      content: "GroupDocs.Viewer 包含一個可調整的快取子系統，它可以透過使用文件的快取版本來縮短載入時間。此外，針對不同格式的一組不同選項允許從渲染中排除文件的一些不必要的部分或方面（字體、隱藏的工作表、電子郵件附件），以優化整體效能"

    # feature loop
    - icon: "passwordprotected"
      title: "支援受密碼保護的文檔"
      content: "GroupDocs.Viewer 允許透過在載入選項中指定密碼來開啟不同類型的加密文件：PDF、WordProcessing、電子表格、簡報等。"

############################# Code samples ############################
code_samples:
  enable: true
  title: "程式碼範例"
  description: "用於 .NET 操作的典型 GroupDocs.Viewer 的一些用例"
  items:
    # code sample loop
    - title: "將 DOCX 渲染為 HTML"
      content: |
        [HtmlViewOptions](https://reference.groupdocs.com/viewer/net/groupdocs.viewer.options/htmlviewoptions/) 類別屬性可讓您控制轉換過程，更多資訊[此處](https://docs .groupdocs .com/viewer/net/rendering-to-html/)。 例如，您可以將所有外部資源嵌入到輸出 HTML 檔案中、縮小輸出檔案並最佳化其列印。
        {{< landing/code title="C#">}}
        ```csharp {style=abap}
        using GroupDocs.Viewer;
        using GroupDocs.Viewer.Options;
        
        // Instantiate viewer
        using (Viewer viewer = new Viewer("resume.docx"))
        {
            // Set output HTML options
            HtmlViewOptions options = HtmlViewOptions.ForEmbeddedResources();
            
            // Render DOCX to HTML with embedded resources
            viewer.View(options);
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "將 PPTX 匯出為 PDF"
      content: |
        建立一個 [PdfViewOptions](https://reference.groupdocs.com/viewer/net/groupdocs.viewer.options/pdfviewoptions/) 類別實例並將其傳遞給 [Viewer.View](https://reference.groupdocs. com/viewer/net/groupdocs.viewer/viewer/view/#view) 方法將PowerPoint PPTX 檔案轉換為PDF。 PdfViewOptions 類別屬性可讓您控制轉換過程。例如，您可以保護輸出 PDF 文件、重新排序其頁面以及指定文件影像的品質。有關詳細信息，請參閱[以下文件部分](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/)。
        {{< landing/code title="C#">}}
        ```csharp {style=abap}   
        using GroupDocs.Viewer;
        using GroupDocs.Viewer.Options;
        
        using (var viewer = new Viewer("presentation.pptx"))
        {
            // Set output PDF options
            var viewOptions = new PdfViewOptions("presentation.pdf");
            
            // Export PPTX to PDF
            viewer.View(viewOptions);
        }
        ```
        {{< /landing/code >}}
############################# Reviews ############################
# reviews:
# enable: true
# title: "GroupDocs 商品評論"
# description: "不要只相信我們的話。看看其他開發人員如何評價我們的 API"

# items:
#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "優質的服務和優質的產品。他們在 GroupDocs.Viewer for .NET 實施過程中提供了極大的幫助和回應，強烈推薦他們。"
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "在專案中實作並使用 GroupDocs.Viewer for .NET 後，它看起來運作得很好。我已經用很多文件進行了測試，到目前為止一切順利。我扔給它的所有內容都可以很好地呈現，並且看起來與在 PDF 檢視器或 MS Word 中一樣好。"
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---