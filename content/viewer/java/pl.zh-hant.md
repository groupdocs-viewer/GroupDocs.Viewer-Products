---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: zh-hant

############################# Head #############################
head_title: "Java PL 查看器 API - 在 Java 應用程序中渲染和顯示 PL"
head_description: "在 Java、J2EE、J2SE 應用程序中查看 PL 文件。支持以 HTML、PDF 或圖像模式查看 170 多種文檔和圖像文件格式，並具有管理文檔查看選項的高級功能。"

############################# Header ############################
title: "在 Java 中渲染和查看 PL" 
description: "適用於基於 Java、J2EE 和 J2SE 的應用程序的本機高性能 PL 文件查看器 API，支持多種附加功能來自定義輸出文檔格式的外觀。" 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "下載免費試用版"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "關於 Java API 的 GroupDocs.Viewer" 
    content: |
        使用 GroupDocs.Viewer for Java API，使您的 Java 應用程序能夠以 HTML、PDF 或圖像模式顯示超過 170 種文件格式，無需安裝任何其他軟件；例如 Microsoft Office、Apache Open Office、Adobe Acrobat Reader 等。開發人員可以在 Java 應用程序中輕鬆查看所有流行的圖像和文檔類型，包括 Microsoft Office、OpenDocument、HTML、PDF、Archive、圖表、Photoshop、AutoCAD 和編程語言格式快速且最高質量的渲染。

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
              text: "API參考"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "代碼示例"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "現場演示"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "價錢"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "在 Java 中渲染 PL 文件的步驟" 
    content_left: |
        使用 [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/)，您只需幾個步驟即可將 PL 呈現為 HTML、JPEG、PNG 或 PDF。

        * 添加 [GroupDocs.Viewer for Java](https://releases.groupdocs.com/viewer/java/) 作為項目的依賴項。 
        * 創建 Viewer 類的實例並加載具有完整路徑的 PL 文件。 
        * 設置選項以將 PL 文件呈現為 HTML、PNG、JPEG 或 PDF 格式。 
        * 渲染文件並檢查當前目錄中的輸出。 
        
    title_right: "系統要求" 
    content_right: |
        所有主要平台和操作系統均支持 Java API 的 GroupDocs.Viewer。在執行下面的代碼之前，請確保您的系統上安裝了以下先決條件。

        * 操作系統：Microsoft Windows、Linux、MacOS 
        * 開發環境：NetBeans、IntelliJ IDEA、Eclipse 等。 
        * 框架：J2SE 8.0 (1.8) 或更高版本（例如 Java 17） 
    code: |
        ```java
                        
            // Set up input PL file
            String filePath = "input.pl";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render PL file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "PL查看器現場演示"
    content: |
        立即訪問 [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/pl) 網站查看 PL 文件。
    lang: "zh-hant"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "使用 Java 渲染和查看其他文件格式"
    exclude: "PL"
    content: |
        適用於 Java 的多格式文檔和圖像查看器 API。無需任何外部查看器即可查看以下一些流行的文件格式。
    format: 
        # format loop 1
        - name: "渲染 DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word 打開 XML 文檔" 

        # format loop 2
        - name: "渲染CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "CorelDRAW 文件" 

        # format loop 3
        - name: "渲染 PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint Open XML 演示文稿" 

        # format loop 4
        - name: "渲染 XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel 打開 XML 電子表格" 

        # format loop 5
        - name: "渲染 DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "AutoCAD繪圖"

        # format loop 6
        - name: "渲染 XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "XML文件"

        # format loop 7
        - name: "渲染 PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Adobe Photoshop 文檔"

        # format loop 8
        - name: "渲染 Adob​​e Illustrator 文件"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Adobe Illustrator 作品"

        # format loop 9
        - name: "渲染文檔"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "微軟Word文檔" 

        # format loop 10
        - name: "渲染 TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "純文本文件" 

        # format loop 11
        - name: "渲染 DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "繪圖交換格式文件"  
          
        # format loop 12
        - name: "渲染VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "電子名片文件"  
              
        # format loop 13
        - name: "渲染 SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "可縮放矢量圖形" 
          
        # format loop 14
        - name: "渲染 HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "超文本標記語言文件" 
          
        # format loop 15
        - name: "渲染 PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "便攜式文檔格式文件"
          
        # format loop 16
        - name: "渲染 JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "JPEG圖像"
          
        # format loop 17
        - name: "渲染 PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "便攜式網絡圖形" 
          
        # format loop 18
        - name: "渲染EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "電子郵件信息" 
          
        # format loop 19
        - name: "渲染RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "富文本格式文件" 
          
        # format loop 20
        - name: "渲染 ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "OpenDocument 文本文檔" 
          
        # format loop 21
        - name: "渲染 CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "逗號分隔值文件" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
