---
############################# Static ############################
layout: "format"
date: 2024-05-14T11:12:56
draft: false
lang: zh
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head #############################
head_title: ".NET TIFF Viewer API - 在 C# VB.NET 中读取、查看、渲染"
head_description: ".NET 文档查看器 API，用于在任何类型的 C#、ASP.NET、VB.NET 和 .NET Core 应用程序中读取、渲染和显示 TIFF。"

############################# Header ############################
title: "用于 C# .NET 应用程序的 TIFF 文件查看器" 
description: ".NET 文档查看器 API，用于在任何类型的 C#、ASP.NET、VB.NET 和 .NET Core 应用程序中读取、渲染和显示 TIFF 文件。使用 HTML5、PDF 或使用几行代码以图像形式查看具有真实格式和布局的渲染文件。" 
subtitle: "文档渲染解决方案" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "免费 Nuget 下载"
      link: "https://nuget.org/packages/GroupDocs.Viewer"



############################# About ############################
about:
    enable: true
    title: "关于 .NET API 的 GroupDocs.Viewer"
    link: "/viewer/net/"
    link_title: "了解更多"
    picture: "about_viewer.svg" # 480 X 400
    content: |
      通过添加几行代码，即可使用适用于 .NET API 的 GroupDocs.Viewer 在 .NET 应用程序中查看 190 多种流行文档格式。开发人员可以轻松地以 HTML5、图像或 PDF 模式显示 PDF、文字处理、Excel 电子表格、演示文稿、Visio、Project、Outlook 和许多其他流行的文档格式。文档渲染速度快，与原始源文件相同，并且不需要安装额外的软件或任何其他外部库。



############################# Steps ############################
steps:
    enable: true
    title: "在 C# 中渲染 TIFF 文件的步骤" 
    content: |
      借助 <a href='https://products.groupdocs.com/viewer/net/'>GroupDocs.Viewer</a>，您只需几个步骤即可将 TIFF 呈现为 HTML、JPEG、PNG 或 PDF。
      
      1. 使用您最喜欢的包管理器安装 <a href='https://www.nuget.org/packages/groupdocs.viewer'>GroupDocs.Viewer for .NET</a>。 
      2. 创建 Viewer 类的实例并加载具有完整路径的 TIFF 文件。  
      3. 设置选项以将 TIFF 文件呈现为 HTML、PNG、JPEG 或 PDF 格式。 
      4. 渲染文件并检查当前目录中的输出。 
   
    code:
      platform: "net"
      copy_title: "复制"
      install:
        command: "dotnet add package GroupDocs.Viewer"
        copy_tip: "点击复制"
        copy_done: "复制的"
      links:
        #  loop
        - title: "更多示例"
          link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
        #  loop
        - title: "文档"
          link: "https://docs.groupdocs.com/viewer/net/"
          
      content: |
        ```csharp {style=abap}

        // 设置输入 TIFF 文件
        string filePath = "input.tiff";

        // 实例化 GroupDocs.Viewer
        using (Viewer viewer = new Viewer(filePath))
        {
            // 设置视图选项
            HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                
            // 将 TIFF 文件渲染为带有嵌入资源的 HTML
            viewer.View(viewOptions);
        }

        ```            


############################# Actions ############################

actions:
  enable: true
  title: "准备好开始了吗？"
  description: "免费试用 GroupDocs.Viewer 功能或申请许可证"
  items:
    #  loop
    - title: "努吉特下载"
      link: "https://nuget.org/packages/GroupDocs.Viewer"
      color: "red"
        #  loop
    - title: "许可"
      link: "https://purchase.groupdocs.com/pricing/viewer/net/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "使用 C# 渲染其他文件格式"
    exclude: "TIFF"
    description: "适用于 .NET 的多格式文档和图像查看器 API。无需任何外部查看器即可查看以下一些流行的文件格式。"
    items: 
        # format loop 1
        - name: "渲染 DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word Open XML Document" 

        # format loop 2
        - name: "渲染 CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "CorelDRAW File" 

        # format loop 3
        - name: "渲染 PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint Open XML Presentation" 

        # format loop 4
        - name: "渲染 XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet" 

        # format loop 5
        - name: "渲染 DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "AutoCAD Drawing"

        # format loop 6
        - name: "渲染 XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "XML File"

        # format loop 7
        - name: "渲染 PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Adobe Photoshop Document"

        # format loop 8
        - name: "渲染 AI"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Adobe Illustrator Artwork"

        # format loop 9
        - name: "渲染 DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Microsoft Word Document" 

        # format loop 10
        - name: "渲染 TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Plain Text File" 

        # format loop 11
        - name: "渲染 DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Drawing Exchange Format File"  
          
        # format loop 12
        - name: "渲染VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "vCard File"  
              
        # format loop 13
        - name: "渲染 SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Scalable Vector Graphic" 
          
        # format loop 14
        - name: "渲染 HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "渲染 PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Portable Document Format File"
          
        # format loop 16
        - name: "渲染 JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "JPEG Image"
          
        # format loop 17
        - name: "渲染 PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Portable Network Graphic" 
          
        # format loop 18
        - name: "渲染EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "E-Mail Message" 
          
        # format loop 19
        - name: "渲染 RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Rich Text Format File" 
          
        # format loop 20
        - name: "渲染 ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "OpenDocument Text Document" 
          
        # format loop 21
        - name: "渲染 CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Comma-Separated Values File" 



---
