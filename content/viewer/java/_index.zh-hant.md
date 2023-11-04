---
############################# Static ############################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

lang: zh-hant
product: "Viewer"
product_tag: "viewer"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "用於 PDF、Word、Excel、HTML 圖像和電子郵件的 Java 文檔查看器 API"
head_description: "Java 文檔查看器和文件渲染 API。在 Java 應用程序中添加 PDF 查看器、Word 查看器、Excel 查看器、圖像查看器、HTML 查看器、電子郵件查看器。"

############################# Header ############################
title: "用於渲染和顯示文檔的 Java API"
description: "文檔查看器庫，用於開發本地渲染、查看和操作支持 170 多種文件格式的多格式文檔的 Java 應用程序。"
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
              text: "概述"

            # button loop
            - link: "#features"
              text: "特徵"

            # button loop
            - link: "#support"
              text: "支持"

            # button loop
            - link: "https://products.groupdocs.app/viewer/total"
              text: "現場演示"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/java"
              text: "價錢"

    right:
        link_download: "https://releases.groupdocs.com/viewer/java/"
        link_learn: "https://docs.groupdocs.com/viewer/java/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    content: |
      GroupDocs.Viewer for Java 結合了一組功能強大的文檔查看器 API，可以在 Java 應用程序中顯示圖像和文檔格式，而無需安裝其他軟件。它對文檔進行原生光柵化並將其轉換為 SVG+HTML+CSS，以提高文檔查看質量，同時提供真實文本、高保真輸出。使用文檔渲染 API – 輕鬆快速查看 PDF、HTML、XML、Microsoft Office Word、Excel 工作表、PowerPoint 演示文稿、Outlook 電子郵件、Visio 圖表、項目、圖元文件、圖像和各種其他文件格式，並減少編程風險。它還可以顯示受密碼保護的文件，並允許在渲染後以 HTML、圖像或 PDF 形式獲取文檔表示。我們的文件查看器庫是完全可定制的，因為它允許您顯示整個文檔，或部分渲染它以加快過程。通過 Java API 的 GroupDocs.Viewer，您可以查看頁面、電子表格中的特定單元格範圍，甚至可以以 PDF 和 CAD 等格式呈現單個文檔層。  

      GroupDocs.Viewer for Java API 允許您呈現帶有/不帶有受支持文件格式的註釋或註釋的文檔。它還使您能夠添加自定義字體目錄並提取基本文檔信息，例如文件類型、擴展名、名稱、頁數等。  

      GroupDocs.Viewer for Java 與所有 Java 版本兼容，並支持能夠運行 Java 運行時的流行操作系統（Windows、Linux、macOS）。
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          以下是 Java 版 GroupDocs.Viewer 的概述：
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "概述"
          content: |
            * 顯示 170 多種文檔類型 
            * 獲取 HTML、圖像、PDF 版本 
            * 旋轉和重新排序 
            * 應用水印 
            * 用於快速處理的緩存 
            * 添加自定義字體 
            * 應用編碼標準 
            * 自定義輸入數據處理程序 
            * 渲染並跟踪更改 
            * 呈現為響應式 HTML 
            * 渲染 PDF 和 CAD 圖層 
            * 渲染受保護的文件 
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Viewer for Java 支持所有流行的文檔文件格式，包括：Microsoft Office、圖像、圖表等。

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
            - title: "其他格式"
              content: |
                * **頁面佈局文件:** PDF, TEX, XPS, OXPS
                * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG, OTG, FODP, FODG
                * **分隔符分隔值:** CSV, TSV
                * **網絡:** HTML, MHT, MHTML
                * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
                * **PostScript:** PS, EPS
                * **檔案:** ZIP, TAR, BZ2, GZ, RAR, RAR5
                * **各種各樣的:** OBJ, EPUB, MOBI, DjVu, XML, VCF, VCARD, NUMBERS, NSF

        right:
          enable: true
          table:
            # table loop
            - title: "圖像、圖形和圖表"
              content: |
                * **圖片:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB
                * **窗口圖標:** ICO
                * **可縮放矢量圖形:** SVG, CDR, CMX, IGS, SVGZ
                * **JPEG2000:** JP2, J2C, J2K, JPC, JPF, JPX, JPM
                * **Adobe Photoshop:** PSD, PSB
                * **打印機命令語言:** PCL
                * **立體光刻（3D 打印）:** STL
                * **行業基礎課程:** IFC
                * **醫學影像:** DICOM
                * **繪圖儀文檔:** PLT, HPG
                * **Autodesk 設計 Web 格式:** DWF, DWG
                * **AutoCAD繪圖:** DWT, IFC, STL, CF2
                * **基於 ISFF 的 DGN (V7):** DGN

            # table loop
            - title: "編程語言格式"
              content: |
                * **C/C++/C# 文件:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
                * **Java/JavaScript 文件:** JAVA, JS, JSON, PROPERTIES
                * **各種各樣的:** VB, PHP, SQL, PL, PY, PV, RB, RST, SASS, SCALA, SCM, SCRIPT, AS, AS3, ASM, BAT, CMAKE, CSS, DIFF, ERB, GROOVY, HAML, LESS, LOG, M, MAKE, MD, ML, MM, SH, SML, VIM, YAML

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Viewer for Java 支持以下操作系統、框架和包管理器：
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "操作系統"
              content: |
                * Microsoft Windows Server 2003 及更高版本 
                * Microsoft Windows XP 及更高版本 
                * 微軟 Windows 10 和 11 
                * Linux（Ubuntu、OpenSUSE、CentOS 等） 
                * Mac OS X 

            # table loop
            - icon: "fas fa-code"
              title: "支持的框架"
              content: |
                * J2SE 8.0 (1.8) 或更高版本（例如 Java 17） 

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-cogs"
              title: "開發環境"
              content: |
                * NetBeans
                * IntelliJ IDEA
                * Eclipse

            # table loop
            - icon: "fas fa-tools"
              title: "構建自動化工具"
              content: |
                * Maven
                * Gradle

############################# Features ############################
features:
    enable: true
    title: "GroupDocs.Viewer for Java 功能"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "HTML、PDF、圖像、Word、Excel 和其他文檔格式的查看器"

      # feature loop
      - icon: "fas fa-eye"
        content: "將 AutoCAD 工程圖 (DWG) 文件渲染為 SVG 格式"

      # feature loop
      - icon: "fas fa-bolt"
        content: "調整轉換文件的背景顏色"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "光柵化文檔並將其轉換為 SVG、HTML 和 CSS"

      # feature loop
      - icon: "fas fa-code"
        content: "通過渲染獲取文檔的 HTML、圖像或 PDF 表示形式"

      # feature loop
      - icon: "fas fa-cloud"
        content: "文檔的緩存版本可加快加載時間"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "配置自定義字體目錄"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "將編碼標準應用於 Word、Excel 和電子郵件文檔"

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "通過 FTP 或云存儲遠程渲染文檔"

      # feature loop
      - icon: "fas fa-border-all"
        content: "渲染時刪除或保留註釋和註釋"

      # feature loop
      - icon: "fas fa-wrench"
        content: "將文檔頁面呈現為單獨的 HTML 頁面"

      # feature loop
      - icon: "fas fa-columns"
        content: "渲染隱藏的幻燈片和頁面並將頁面重新排序應用於渲染的文檔"

      # feature loop
      - icon: "fas fa-file-word"
        content: "將頁面範圍、特定頁面或所有頁面渲染為 HTML"

      # feature loop
      - icon: "fas fa-envelope"
        content: "呈現或隱藏文檔註釋"

      # feature loop
      - icon: "fas fa-print"
        content: "通過渲染為某些文檔格式創建響應式 HTML"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "通過排除字體來減少渲染 HTML 的最終文件大小"

      # feature loop
      - icon: "fas fa-lock"
        content: "刪除註釋、額外的空格等，以縮小輸出 HTML 和 CSS"

      # feature loop
      - icon: "fas fa-file-code"
        content: "使用源文檔的坐標來讀取所包含的文本"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "在渲染輸出的 Excel 工作表中顯示/隱藏單元格邊框"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "渲染 Excel 工作表中每頁的特定行數"

      # feature loop
      - icon: "fas fa-heading"
        content: "渲染模型和所有非空佈局或 CAD 文件的特定佈局"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "將 Outlook 數據文件 (OST/PST) 中的項目呈現為 PDF"

      # feature loop
      - icon: "fas fa-cube"
        content: "平鋪渲染或按 CAD 文檔坐標渲染為圖像、HTML 或 PDF"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "渲染為 PDF 時設置打印限制"

    more_feature:
      # more_feature_loop
      - title: "用於查看文檔的高效可靠的 API"
        content: |
          GroupDocs.Viewer for Java API 可用於查看、渲染和顯示 150 多種不同文件格式的文檔。它可靠且高效地完成，同時保持文檔的內容和結構完整。以下示例顯示了 GroupDocs.Viewer for Java API 使用 Java 將 DOCX 文件呈現為圖像文件的輕鬆程度：

          ```java
          // Initialize Viewer
          Viewer viewer = new Viewer("invoice.docx");
          // Create view options
          PdfViewOptions viewOptions = new PdfViewOptions();
          // Convert file to PDF and check the output in the current directory
          viewer.view(viewOptions);
          ```
      # more_feature_loop
      - title: "渲染文檔時執行轉換"
        content: "GroupDocs.Viewer for Java API 為您提供了應用於渲染文檔的各種轉換選項，以實現更加自定義的視圖和顯示。您可以通過提供角度來旋轉頁面。您可以調整渲染頁面的順序。將特定文本作為水印應用到渲染的頁面或圖像。通過 Java API 的 GroupDocs.Viewer，您還可以將自定義字體添加到正在呈現的文檔中。"

      # more_feature_loop
      - title: "使用電子郵件附件"
        content: "GroupDocs.Viewer for Java API 允許您獲取電子郵件的特定或所有附件。獲得所需的電子郵件附件後，您可以將這些附件呈現為圖像或 HTML。"

############################# Support ############################
support:
    enable: true

############################# Solutions ##########################
solutions:
    enable: true
    title: "GroupDocs.Viewer 為其他流行的開發環境提供文檔查看 API"

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