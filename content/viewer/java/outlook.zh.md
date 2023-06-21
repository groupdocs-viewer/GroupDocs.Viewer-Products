---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: zh

############################# Head #############################
head_title: "Java Outlook 查看器 API - 在 Java 应用程序中呈现和显示 Outlook"
head_description: "查看 Java、J2EE、J2SE 应用程序中的 Outlook 文件。支持以 HTML、PDF 或图像模式查看 170 多种文档和图像文件格式，并具有管理文档查看选项的高级功能。"

############################# Header ############################
title: "在 Java 中渲染和查看 Outlook" 
description: "用于基于 Java、J2EE 和 J2SE 的应用程序的本机和高性能 Outlook 文件查看器 API，支持广泛的附加功能以自定义输出文档格式的外观。" 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "下载免费试用版"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "关于 GroupDocs.Viewer for Java API" 
    content: |
        使用 GroupDocs.Viewer for Java API 使您的 Java 应用程序能够以 HTML、PDF 或图像模式显示 170 多种文件格式，而无需安装任何其他软件；例如 Microsoft Office、Apache Open Office、Adobe Acrobat Reader 等。开发人员可以使用 Java 应用程序轻松查看所有流行的图像和文档类型，包括 Microsoft Office、OpenDocument、HTML、PDF、Archive、Diagrams、Photoshop、AutoCAD 和编程语言格式快速和最高质量的渲染。

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
    title_left: "在 Java 中呈现 Outlook 文件的步骤" 
    content_left: |
        使用 [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/)，您可以通过几个步骤将 Outlook 呈现为 HTML、JPEG、PNG 或 PDF。

        * 添加 [GroupDocs.Viewer for Java](https://releases.groupdocs.com/viewer/java/) 作为项目的依赖项。 
        * 创建 Viewer 类的实例并加载具有完整路径的 Outlook 文件。 
        * 设置选项以将 Outlook 文件呈现为 HTML、PNG、JPEG 或 PDF 格式。 
        * 渲染文件并检查当前目录中的输出。 
        
    title_right: "系统要求" 
    content_right: |
        所有主要平台和操作系统都支持 Java API 的 GroupDocs.Viewer。在执行下面的代码之前，请确保您的系统上安装了以下先决条件。

        * 操作系统：Microsoft Windows、Linux、MacOS 
        * 开发环境：NetBeans、IntelliJ IDEA、Eclipse 等。 
        * 框架：J2SE 8.0 (1.8) 或更高版本（例如 Java 17） 
    code: |
        ```java
                        
            // Set up input Outlook file
            String filePath = "input.pst";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render Outlook file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "Outlook 查看器现场演示"
    content: |
        立即访问 [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/outlook) 网站查看 Outlook 文件。
    lang: "zh"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "使用 Java 渲染和查看其他文件格式"
    exclude: "Outlook"
    content: |
        用于 Java 的多格式文档和图像查看器 API。在没有任何外部查看器的情况下查看下面的一些流行文件格式。
    format: 
        # format loop 1
        - name: "渲染 DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word 打开 XML 文档" 

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
          description: "Microsoft Excel 打开 XML 电子表格" 

        # format loop 5
        - name: "渲染 DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "AutoCAD 绘图"

        # format loop 6
        - name: "呈现 XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "文件"

        # format loop 7
        - name: "渲染 PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Adobe Photoshop 文档"

        # format loop 8
        - name: "渲染 Adob​​e Illustrator 文件"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Adobe Illustrator 图稿"

        # format loop 9
        - name: "渲染文档"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "微软 Word 文档" 

        # format loop 10
        - name: "渲染 TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "纯文本文件" 

        # format loop 11
        - name: "渲染 DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "绘图交换格式文件"  
          
        # format loop 12
        - name: "渲染 VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "电子名片文件"  
              
        # format loop 13
        - name: "渲染 SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "可缩放矢量图形" 
          
        # format loop 14
        - name: "呈现 HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "超文本标记语言文件" 
          
        # format loop 15
        - name: "渲染 PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "便携式文档格式文件"
          
        # format loop 16
        - name: "渲染 JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "JPEG图像"
          
        # format loop 17
        - name: "渲染 PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "便携式网络图形" 
          
        # format loop 18
        - name: "渲染 EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "电子邮件信息" 
          
        # format loop 19
        - name: "渲染 RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "富文本格式文件" 
          
        # format loop 20
        - name: "渲染ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "OpenDocument 文本文档" 
          
        # format loop 21
        - name: "渲染 CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "逗号分隔值文件" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
