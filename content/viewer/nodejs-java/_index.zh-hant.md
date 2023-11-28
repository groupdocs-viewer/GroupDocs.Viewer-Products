---
############################# Static ############################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: zh-hant
product: "Viewer"
product_tag: "viewer"
platform: "Node.js via Java"
platform_tag: "nodejs-java"

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
head_title: "用於 PDF、Word、Excel、HTML 圖片和電子郵件的 Node.js 文件檢視器 API"
head_description: "Node.js 文件檢視器和檔案渲染 API。在 JavaScript 應用程式中新增 PDF 檢視器、Word 檢視器、Excel 檢視器、影像檢視器、HTML 檢視器、電子郵件檢視器。"

############################# Header ############################
title: "用於渲染和顯示文件的 Node.js API"
description: "文件檢視器庫，用於開發原生渲染、檢視和操作支援 180 多種文件格式的多格式文件的 JavaScript 應用程式。"
words:
  for: "for"

actions:
  main: "免費 NPM 下載"
  main_link: "https://www.npmjs.com/package/@groupdocs/groupdocs.viewer"
  alt: "授權"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/nodejs-java"
  title: "準備好開始了嗎？"
  description: "免費試用 GroupDocs.Viewer 功能或申請許可證"

release:
  title: "版本 {0} 已發布"
  notes: "看看有什麼新鮮事"
  downloads: "下載"
  link: "https://releases.groupdocs.com/viewer/nodejs-java/release-notes/latest/"

code:
  title: "在 JavaScript 中渲染 PDF 文件"
  more: "更多範例"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Node.js-via-Java"
  install: "npm i @groupdocs/groupdocs.viewer"
  content: |
    ```javascript {style=abap}   
    //Set output HTML options, one file per page
    const viewOptions = HtmlViewOptions.forEmbeddedResources()

    // Instantiate Viewer
    const viewer = new Viewer("resume.pdf")

    // Render PDF to HTML with embedded resources
    viewer.view(viewOptions)
    viewer.close()
    ```
############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Viewer 概覽"
  description: "用於在 Node.js 應用程式中渲染、顯示、轉換文件、投影片、圖表和許多其他文件類型的 API"
  features:
    # feature loop
    - title: "有效率可靠地檢視文檔"
      content: "透過 GroupDocs.Viewer API，您可以使用靈活且強大的選項將任何支援格式的文件高效呈現為 HTML、JPEG、PNG 和 PDF，同時保持內容和文件結構的完整性。 GroupDocs.Viewer for Node.js 適用於 Windows 和 Linux 平台。"

    # feature loop
    - title: "支援最受歡迎的文件和文件格式"
      content: "我們支援渲染180 多種最受歡迎的文件和文件格式，包括Word、Excel、PDF、PowerPoint、OpenDocument 格式系列、檔案、光柵和向量圖像、電子書、程式語言和標記以及許多其他文件類型，包括加密的文件類型受密碼保護的文件。"

    # feature loop
    - title: "可自訂的輸出"
      content: "GroupDocs.Viewer 不僅允許渲染文檔，還可以控制渲染的準確方式、文檔的哪些部分應該渲染或現在渲染、如何渲染，以及對渲染的輸出應用不同的轉換。"

############################# Platforms ############################
platforms:
  enable: true
  title: "平台獨立性"
  description: "GroupDocs.Viewer for Node.js 支援以下作業系統、框架和套件管理器"
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
    - title: "NPM"
      image: "npm"

############################# File formats ############################
formats:
  enable: true
  title: "支援的文件格式"
  description: |
    GroupDocs.Viewer for Node.js via Java 支援以下[檔案格式](https://docs.groupdocs.com/viewer/nodejs-java/supported-document-formats/) 的操作。
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
  description: "透過 Java 操作用於 Node.js 的典型 GroupDocs.Viewer 的一些用例"
  items:
    # code sample loop
    - title: "將 DOCX 渲染為 HTML"
      content: |
        `HtmlViewOptions` 類別屬性可讓您控制轉換過程，更多資訊請參閱[此處](https://docs.groupdocs.com/viewer/nodejs-java/rendering-to-html/)。 例如，您可以將所有外部資源嵌入到輸出 HTML 檔案中、縮小輸出檔案並最佳化其列印。
        {{< landing/code title="JavaScript">}}
        ```javascript {style=abap}
        import { Viewer, HtmlViewOptions } from '@groupdocs/groupdocs.viewer'

        //Set output HTML options, one file per page
        const viewOptions = HtmlViewOptions.forEmbeddedResources()

        // Instantiate Viewer
        const viewer = new Viewer("resume.docx")

        // Render PDF to HTML with embedded resources
        viewer.view(viewOptions)
        viewer.close()
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "將 PPTX 匯出為 PDF"
      content: |
        建立一個「PdfViewOptions」類別實例並將其傳遞給「Viewer.view」方法以將 PowerPoint PPTX 檔案轉換為 PDF。 `PdfViewOptions` 類別屬性可讓您控制轉換過程。例如，您可以保護輸出 PDF 文件、重新排序其頁面以及指定文件影像的品質。有關詳細信息，請參閱[以下文件部分](https://docs.groupdocs.com/viewer/nodejs-java/rendering-to-pdf/)。
        {{< landing/code title="JavaScript">}}
        ```javascript {style=abap}   
        import { Viewer, PdfViewOptions } from '@groupdocs/groupdocs.viewer'

        //Set output PDF options
        const viewOptions = new PdfViewOptions("presentation.pdf")

        // Instantiate Viewer
        const viewer = new Viewer("presentation.pptx")

        // Render PDF to HTML with embedded resources
        viewer.view(viewOptions)
        viewer.close()
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
