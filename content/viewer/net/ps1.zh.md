---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: zh

############################# Head #############################
head_title: ".NET PS1 查看器 API - 在 C# VB.NET 中读取、查看、呈现"
head_description: ".NET 文档查看器 API，用于在任何类型的 C#、ASP.NET、VB.NET 和 .NET Core 应用程序中读取、呈现和显示 PS1。"

############################# Header ############################
title: "PS1 C# .NET 应用程序的文件查看器" 
description: ".NET 文档查看器 API，用于在任何类型的 C#、ASP.NET、VB.NET 和 .NET Core 应用程序中读取、呈现和显示 PS1 文件。使用几行代码以 HTML5、PDF 或图像形式查看具有真实格式和布局的渲染文件。" 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "下载免费试用版"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "关于 .NET API 的 GroupDocs.Viewer" 
    content: |
        通过添加几行代码，使用适用于 .NET API 的 GroupDocs.Viewer，开始在您的 .NET 应用程序中查看 190 多种流行的文档格式。开发人员可以轻松地以 HTML5、图像或 PDF 模式显示 PDF、Word Processing、Excel Spreadsheet、Presentation、Visio、Project、Outlook 和许多其他流行的文档格式。文档渲染速度快，与原始源文件相同，不需要安装额外的软件或任何其他外部库。

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
              text: "API参考"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "代码示例"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "现场演示"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "价钱"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "在 C# 中渲染 PS1 文件的步骤" 
    content_left: |
        使用 [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/)，您可以通过几个步骤将 PS1 呈现为 HTML、JPEG、PNG 或 PDF。

        * 使用您最喜欢的包管理器安装 [GroupDocs.Viewer for .NET](https://www.nuget.org/packages/groupdocs.viewer)。 
        * 创建 Viewer 类的实例并加载具有完整路径的 PS1 文件。 
        * 设置选项以将 PS1 文件呈现为 HTML、PNG、JPEG 或 PDF 格式。 
        * 渲染文件并检查当前目录中的输出。 
        
    title_right: "系统要求" 
    content_right: |
        所有主要平台和操作系统都支持 .NET API 的 GroupDocs.Viewer。在执行下面的代码之前，请确保您的系统上安装了以下先决条件。

        * 操作系统：Microsoft Windows、Linux、MacOS 
        * 开发环境：Microsoft Visual Studio、Visual Studio Code、.NET CLI 
        * 框架：.NET Framework、.NET Standard、.NET Core、.NET 
    code: |
        ```cs
                        
            // Set up input PS1 file
            string filePath = "input.ps1";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render PS1 file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "PS1 查看器现场演示"
    content: |
        立即访问 [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/ps1) 网站查看 PS1 文件。
    lang: "zh"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "使用 C# 渲染和查看其他文件格式"
    exclude: "PS1"
    content: |
        .NET 的多格式文档和图像查看器 API。在没有任何外部查看器的情况下查看下面的一些流行文件格式。
    format: 
        # format loop 1
        - name: "渲染 DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word 打开 XML 文档" 

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
          description: "Microsoft Excel 打开 XML 电子表格" 

        # format loop 5
        - name: "渲染 DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "AutoCAD 绘图"

        # format loop 6
        - name: "呈现 XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "文件"

        # format loop 7
        - name: "渲染 PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Adobe Photoshop 文档"

        # format loop 8
        - name: "渲染 Adob​​e Illustrator 文件"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Adobe Illustrator 图稿"

        # format loop 9
        - name: "渲染文档"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "微软 Word 文档" 

        # format loop 10
        - name: "渲染 TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "纯文本文件" 

        # format loop 11
        - name: "渲染 DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "绘图交换格式文件"  
          
        # format loop 12
        - name: "渲染 VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "电子名片文件"  
              
        # format loop 13
        - name: "渲染 SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "可缩放矢量图形" 
          
        # format loop 14
        - name: "呈现 HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "超文本标记语言文件" 
          
        # format loop 15
        - name: "渲染 PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "便携式文档格式文件"
          
        # format loop 16
        - name: "渲染 JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "JPEG图像"
          
        # format loop 17
        - name: "渲染 PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "便携式网络图形" 
          
        # format loop 18
        - name: "渲染 EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "电子邮件信息" 
          
        # format loop 19
        - name: "渲染 RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "富文本格式文件" 
          
        # format loop 20
        - name: "渲染ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "OpenDocument 文本文档" 
          
        # format loop 21
        - name: "渲染 CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "逗号分隔值文件" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
