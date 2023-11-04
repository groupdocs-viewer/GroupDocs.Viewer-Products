---
############################# Static ##########################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

lang: zh-hant
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: ".NET 文檔查看器 API，渲染 PDF Word Excel 圖像 HTML 圖表"
head_description: "C# ASP.NET 文件查看器和渲染 API。在 .NET 應用程序中添加 PDF 查看器、Word 查看器、Excel 查看器、圖像查看器、HTML 查看器、電子郵件查看器功能。"

############################# Header ##########################
title: "通過 .NET API 渲染和顯示文檔"
description: ".NET 文檔查看器 API 通過強大的配置選項將 190 多種文檔格式呈現為 PDF、HTML 和圖像。"
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
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "價錢"

    right:
        link_download: "https://releases.groupdocs.com/viewer/net/"
        link_learn: "https://docs.groupdocs.com/viewer/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    content: |
      GroupDocs.Viewer for .NET API 可幫助您使用 C#、ASP.NET 和其他基於 .NET 的技術創建功能強大的應用程序，無需安裝任何外部軟件即可渲染和顯示 190 多種文件格式的文檔和圖像。文件查看器庫對文檔進行光柵化，然後將其轉換為 SVG+HTML+CSS，以優化整體文檔渲染體驗，以快速、真實的文本和格式查看業務文檔、圖像、文本文件、圖表、圖形、電子郵件附件和 PDF 文件。應用程序內的高保真度。您可以選擇在應用程序中添加文檔查看和閱讀功能，以顯示整個文檔、部分文檔、特定頁面/單元格範圍、單個文檔層，帶或不帶支持文件格式的註釋和註釋。
       
      GroupDocs.Viewer for .NET 默認將渲染的文檔輸出緩存到本地磁盤。通過實施適當的接口，還可以支持任何類型的外部緩存存儲 - Amazon S3、Dropbox、Google Drive、Windows Azure、Redis 或任何其他接口。
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          以下是適用於 .NET 的 GroupDocs.Viewer 的概述：
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "概述"
          content: |
            * 顯示 190 多種文檔類型 
            * 獲取 HTML、圖像、PDF 格式的文件 
            * 旋轉和重新排序 
            * 應用水印 
            * 用於快速處理的緩存 
            * 添加自定義字體 
            * 應用編碼標準 
            * 自定義輸入數據處理程序 
            * 渲染並跟踪更改 
            * 呈現為響應式 HTML 
            * 渲染 PDF 和 CAD 圖層 
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Viewer for .NET 支持查看所有流行的文檔文件格式。只需幾行代碼，即可在 .NET 應用程序中添加 PDF 查看器、Microsoft Office Word、Excel 電子表格、圖像、HTML、Outlook 電子郵件、OneNote、項目和圖形查看功能。

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
          GroupDocs.Viewer for .NET 支持以下操作系統、框架和包管理器：
        
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
                * .NET Framework 2.0 或更高版本 
                * .NET核心3.1 
                * .NET 5 或更高版本 

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-box"
              title: "包管理器"
              content: |
                * NuGet

            # table loop
            - icon: "fas fa-tools"
              title: "開發環境"
              content: |
                * Microsoft Visual Studio
                * Visual Studio Code
                * .NET CLI

############################# Features ############################
features:
    enable: true
    title: "GroupDocs.Viewer for .NET 功能"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "光柵化文檔並將其轉換為 SVG、HTML 和 CSS"

      # feature loop
      - icon: "fas fa-eye"
        content: "將文本轉換為 HTML 並渲染文檔以獲得 HTML、圖像或 PDF 表示形式"

      # feature loop
      - icon: "fas fa-bolt"
        content: "使用文檔的緩存版本加快加載時間"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "使用 3D 效果轉換具有形狀和文本的演示文稿"

      # feature loop
      - icon: "fas fa-code"
        content: "將 Word、Excel 和電子郵件文檔編碼為所需的編碼標準"

      # feature loop
      - icon: "fas fa-cloud"
        content: "渲染位於 FTP 或云存儲位置的文檔"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "渲染為 HTML 時排除字體以減少結果文件大小"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "通過刪除註釋、額外的空白等來縮小 CSS 和 HTML 輸出。"

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "通過坐標讀取源文檔中包含的文本"

      # feature loop
      - icon: "fas fa-border-all"
        content: "在輸出表示中顯示/隱藏 Excel 工作表的網格線"

      # feature loop
      - icon: "fas fa-wrench"
        content: "指定要在每頁上呈現的 Excel 工作表中的行數"

      # feature loop
      - icon: "fas fa-columns"
        content: "渲染電子表格文檔時忽略空列"

      # feature loop
      - icon: "fas fa-file-word"
        content: "將 Word 文檔渲染為 HTML 頁面、圖像或 PDF，並跟踪更改"

      # feature loop
      - icon: "fas fa-envelope"
        content: "將電子郵件附件呈現為原始文件、圖像或 HTML 表示形式"

      # feature loop
      - icon: "fas fa-print"
        content: "設置 PDF 文檔的打印限制"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "將 ZIP 存檔中包含的內容/文件呈現為附件"

      # feature loop
      - icon: "fas fa-lock"
        content: "從受密碼保護的文檔獲取附件"

      # feature loop
      - icon: "fas fa-file-code"
        content: "將編程語言文件格式渲染為純文本"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "查看 CAD 工程圖時調整背景顏色"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "查看 Excel 文檔並轉換為 PDF、HTML、JPG 和 PNG"

      # feature loop
      - icon: "fas fa-heading"
        content: "從 Excel 文件獲取工作表名稱 - 顯示電子表格列標題和行號"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "使用註釋查看和轉換 Microsoft Project 文檔"

      # feature loop
      - icon: "fas fa-cube"
        content: "將 CAD 繪圖轉換為 SVG，以獲得更好的查看和縮放體驗"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "選擇在沒有方案的情況下渲染 Visio 圖"

    more_feature:
      # more_feature_loop
      - title: "高效可靠地查看文檔"
        content: |
          使用 GroupDocs.Viewer API，您可以高效可靠地顯示 190 多種文檔格式，並且內容和文檔結構完整無損。以下示例代碼顯示查看 DOCX 文檔的 HTML 表示是多麼容易：

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
      - title: "將轉換應用於渲染輸出"
        content: "您可以使用 GroupDocs.Viewer for .NET API 對呈現的輸出文檔執行各種轉換。這些轉換選項使您可以控制呈現渲染輸出的顯示方式。可用的轉換包括頁面旋轉選項、頁面重新排序選項和應用文本水印。"

      # more_feature_loop
      - title: "使用 Outlook 數據文件"
        content: "GroupDocs.Viewer for .NET API 可以將 Outlook 數據文件 (OST/PST) 中的項目呈現為 PDF、HTML 和圖像文件。我們的查看器 API 還能夠獲取 Outlook 數據文件中包含的文件夾列表。使用 GroupDocs.Viewer for .NET API，您可以指定要從 Outlook 數據文件呈現的文件夾。同樣，您還可以獲取 OST/PST 格式的電子郵件作為附件。 GroupDocs.Viewer for .NET 還使您能夠根據主題、內容或發件人過濾 OST/PST 格式的消息。"

      # more_feature_loop
      - title: "使用 CAD 文檔"
        content: "GroupDocs.Viewer for .NET API 可以渲染模型和所有非空佈局或渲染 CAD 文件的特定佈局。 GroupDocs.Viewer for .NET API 還支持平鋪渲染或按 CAD 文檔坐標渲染為圖像、HTML 或 PDF。您還可以獲得 CAD 文檔的圖層狀態。"

############################# Testimonials ###############################
testimonials:
  enable: true

  testimonial:
    # testimonial item loop
    - name: "Margot Baill"
      designation: "Hireology 產品開發總監"
      content: "使用其出色的 Ruby SDK 集成 GroupDocs.Viewer for Cloud API 非常簡單。願意與我們合作實現我們想要的目標的公司並不多。這是一個很好的合作夥伴關係。"

    # testimonial item loop
    - name: "Mats Oustad"
      designation: "Novanet AS 高級顧問/合夥人"
      content: "在項目中實現並使用 GroupDocs.Viewer for .NET 後，它看起來運行得很好。我已經用很多文檔進行了測試，到目前為止一切順利。我向它添加的所有內容都可以很好地呈現，並且看起來與在 PDF 查看器或 MS Word 中一樣好。"
              
    # testimonial item loop
    - name: "Martin Lasarga"
      designation: "Axentria ECM by G.S.I. 產品經理"
      content: "優質的服務和優質的產品。他們在 GroupDocs.Viewer for .NET 實施過程中提供了極大的幫助和響應，強烈推薦他們。"

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Viewer 為其他流行的開發環境提供文檔查看 API"

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
