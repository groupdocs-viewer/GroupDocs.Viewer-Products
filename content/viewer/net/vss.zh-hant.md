---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: zh-hant

############################# Head #############################
head_title: ".NET VSS 查看器 API - 在 C# VB.NET 中讀取、查看、渲染"
head_description: ".NET 文檔查看器 API，用於在任何類型的 C#、ASP.NET、VB.NET 和 .NET Core 應用程序中讀取、渲染和顯示 VSS。"

############################# Header ############################
title: "用於 C# .NET 應用程序的 VSS 文件查看器" 
description: ".NET 文檔查看器 API，用於在任何類型的 C#、ASP.NET、VB.NET 和 .NET Core 應用程序中讀取、渲染和顯示 VSS 文件。使用 HTML5、PDF 或使用幾行代碼以圖像形式查看具有真實格式和佈局的渲染文件。" 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "下載免費試用版"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "關於 .NET API 的 GroupDocs.Viewer" 
    content: |
        通過添加幾行代碼，即可使用適用於 .NET API 的 GroupDocs.Viewer 在 .NET 應用程序中查看 190 多種流行文檔格式。開發人員可以輕鬆地以 HTML5、圖像或 PDF 模式顯示 PDF、文字處理、Excel 電子表格、演示文稿、Visio、Project、Outlook 和許多其他流行的文檔格式。文檔渲染速度快，與原始源文件相同，並且不需要安裝額外的軟件或任何其他外部庫。

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
    title_left: "在 C# 中渲染 VSS 文件的步驟" 
    content_left: |
        使用 [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/)，您只需幾個步驟即可將 VSS 呈現為 HTML、JPEG、PNG 或 PDF。

        * 使用您最喜歡的包管理器安裝 [GroupDocs.Viewer for .NET](https://www.nuget.org/packages/groupdocs.viewer)。 
        * 創建 Viewer 類的實例並加載具有完整路徑的 VSS 文件。 
        * 設置選項以將 VSS 文件呈現為 HTML、PNG、JPEG 或 PDF 格式。 
        * 渲染文件並檢查當前目錄中的輸出。 
        
    title_right: "系統要求" 
    content_right: |
        所有主要平台和操作系統均支持 GroupDocs.Viewer for .NET API。在執行下面的代碼之前，請確保您的系統上安裝了以下先決條件。

        * 操作系統：Microsoft Windows、Linux、MacOS 
        * 開發環境：Microsoft Visual Studio、Visual Studio Code、.NET CLI 
        * 框架：.NET Framework、.NET Standard、.NET Core、.NET 
    code: |
        ```cs
                        
            // Set up input VSS file
            string filePath = "input.vss";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render VSS file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "VSS查看器現場演示"
    content: |
        立即訪問 [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/vss) 網站查看 VSS 文件。
    lang: "zh-hant"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "使用 C# 渲染和查看其他文件格式"
    exclude: "VSS"
    content: |
        適用於 .NET 的多格式文檔和圖像查看器 API。無需任何外部查看器即可查看以下一些流行的文件格式。
    format: 
        # format loop 1
        - name: "渲染 DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word 打開 XML 文檔" 

        # format loop 2
        - name: "渲染CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "CorelDRAW 文件" 

        # format loop 3
        - name: "渲染 PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint Open XML 演示文稿" 

        # format loop 4
        - name: "渲染 XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel 打開 XML 電子表格" 

        # format loop 5
        - name: "渲染 DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "AutoCAD繪圖"

        # format loop 6
        - name: "渲染 XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "XML文件"

        # format loop 7
        - name: "渲染 PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Adobe Photoshop 文檔"

        # format loop 8
        - name: "渲染 Adob​​e Illustrator 文件"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Adobe Illustrator 作品"

        # format loop 9
        - name: "渲染文檔"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "微軟Word文檔" 

        # format loop 10
        - name: "渲染 TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "純文本文件" 

        # format loop 11
        - name: "渲染 DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "繪圖交換格式文件"  
          
        # format loop 12
        - name: "渲染VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "電子名片文件"  
              
        # format loop 13
        - name: "渲染 SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "可縮放矢量圖形" 
          
        # format loop 14
        - name: "渲染 HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "超文本標記語言文件" 
          
        # format loop 15
        - name: "渲染 PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "便攜式文檔格式文件"
          
        # format loop 16
        - name: "渲染 JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "JPEG圖像"
          
        # format loop 17
        - name: "渲染 PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "便攜式網絡圖形" 
          
        # format loop 18
        - name: "渲染EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "電子郵件信息" 
          
        # format loop 19
        - name: "渲染RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "富文本格式文件" 
          
        # format loop 20
        - name: "渲染 ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "OpenDocument 文本文檔" 
          
        # format loop 21
        - name: "渲染 CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "逗號分隔值文件" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
