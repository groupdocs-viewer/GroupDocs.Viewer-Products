---
############################# Static ############################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: ".NET 文档查看器 API，呈现 PDF Word Excel 图像 HTML 图表"
head_description: "C# ASP.NET 文件查看器和渲染 API。在 .NET 应用程序中添加 PDF 查看器、Word 查看器、Excel 查看器、图像查看器、HTML 查看器、电子邮件查看器功能."

############################# Header ############################
title: "通过 .NET API 渲染和显示文档"
description: ".NET 文档查看器 API 可通过强大的配置选项将 170 多种文档格式呈现为 PDF、HTML 和图像。"
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "下载免费试用版"
    link: "https://downloads.groupdocs.com/viewer/net"

############################# SubMenu ############################
submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Viewer for .NET"
        image: "/border/groupdocs-viewer-net.svg"
        product: "GroupDocs.Viewer"
        platform: ".NET"

    middle:
        button:
            # button loop
            - link: "#overview"
              text: "概述"

            # button loop
            - link: "#features"
              text: "特征"

            # button loop
            - link: "#support"
              text: "Support"

            # button loop
            - link: "https://products.groupdocs.app/viewer"
              text: "Live Demo"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "价钱"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# 概述 ############################
overview:
    enable: true
    content: |
      GroupDocs.Viewer for .NET API 可帮助您使用 C#、ASP.NET 和其他基于 .NET 的技术创建功能强大的应用程序，无需安装任何外部软件即可渲染和显示 170 多种文件格式的文档和图像。文件查看器库将文档栅格化，然后将其转换为 SVG+HTML+CSS，以优化整体文档呈现体验，以快速、真实文本和应用程序内部的高保真度。您可以选择在应用程序中添加文档查看和阅读功能，以显示整个文档、部分文档、特定页面/单元格范围、单个文档层，无论是否支持支持的文件格式的注释和注释。

      默认情况下，用于 .NET 的 GroupDocs.Viewer 将呈现的文档输出缓存到本地磁盘。通过实施适当的接口（Amazon S3、Dropbox、Google Drive、Windows Azure、Redis 或任何其他接口）也支持任何类型的外部缓存存储。
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          以下是 .NET 的 GroupDocs.Viewer 的概述：
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "概述"
          content: |
            * 显示 170 多种文档类型
            * 获取 HTML、图像、PDF 版本
            * Rotate &amp; Reorder
            * 应用水印
            * 高速缓存
            * 添加自定义字体
            * 应用编码标准
            * 自定义输入数据处理程序
            * 使用跟踪更改进行渲染
            * 呈现为响应式 HTML
            * Render PDF &amp; CAD Layers
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Viewer for .NET 支持查看所有流行的[文档文件格式](https://docs.groupdocs.com/viewer/net/supported-document-formats/)。只需几行代码，即可在您的 .NET 应用程序中添加 PDF 查看器、微软办公软件 Word、Excel 电子表格、图像、HTML、Outlook 电子邮件、OneNote、项目和图形查看功能。

        left:
          enable: true
          table:
            # table loop
            - title: "微软办公软件"
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
                * **PDF Formats:** PDF, TEX, XPS, OXPS
                * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG, OTG, FODP, FODG
                * **Delimiter-Separated Values:** CSV, TSV
                * **Web:** HTML, MHT, MHTML
                * **Metafile:** WMF, EMF, CGM, WMZ, EMZ
                * **PostScript:** PS, EPS
                * **Archives:** ZIP, TAR, BZ2, GZ, RAR, RAR5
                * **Various:** OBJ, EPUB, MOBI, DjVu, XML, VCF, VCARD, NUMBER, NSF

        right:
          enable: true
          table:
            # table loop
            - title: "图像、图形和图表"
              content: |
                * **Images:** BMP, GIF, JPG, PNG, TIFF, multi-page TIFF, WebP, DNG, DIB, DCM
                * **Windows Icon:** ICO
                * **Scalable Vector Graphics:** SVG, CDR, CMX, IGS, SVGZ
                * **Jpeg2000:** JP2, J2C, J2K, JPC, JPF, JPX, JPM
                * **Adobe Photoshop:** PSD, PSB
                * **Printer Command Language:** PCL
                * **Stereo Lithography (3D Printing):** STL
                * **Industry Foundation Classes:** IFC
                * **Medical Imaging:** DICOM
                * **Plotter Documents:** PLT, HPG
                * **Autodesk Design Web Formats:** DWF, DWG
                * **AutoCAD Drawing:** DGN, DWT, IFC, STL, CF2
                * **ISFF-based DGN (V7):** DGN

            # table loop
            - title: "编程语言格式"
              content: |
                * **C/C++/C# Files:** C, CC, CS, CPP, CXX, C#, H, HH, M, MM
                * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES
                * **Various:** VB, PHP, SQL, PL, PY, PV, RB, RST, SASS, SCALA, SCM, SCRIPT, AS, AS3, ASM, BAT, CMAKE, CSS, DIFF, ERB, GROOVY, HAML, LESS, LOG, M, MAKE, MD, ML, MM, SH, SML, VIM, YAML

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Viewer for .NET 支持以下操作系统、框架和包管理器:
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "操作系统"
              content: |
                * Windows Desktop
                * Windows Server
                * Microsoft Azure
                * Linux

            # table loop
            - icon: "fas fa-code"
              title: "支持的框架"
              content: |
                * .NET Framework 2.0 或更高版本
                * .NET Core 3.1
                * .NET 5 or higher

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
              title: "开发环境"
              content: |
                * Microsoft Visual Studio
                * Visual Studio Code
                * .NET CLI

############################# 特征 ############################
features:
    enable: true
    title: "GroupDocs.Viewer for .NET 特征"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "光栅化文档并将其转换为 SVG、HTML 和 CSS"

      # feature loop
      - icon: "fas fa-eye"
        content: "将文本转换为 HTML 并渲染文档以获取 HTML、图像或 PDF 表示"

      # feature loop
      - icon: "fas fa-bolt"
        content: "使用缓存的文档版本加快加载时间"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "带有 3D 效果的形状和文本的转换演示文稿"

      # feature loop
      - icon: "fas fa-code"
        content: "将 Word、Excel 和电子邮件文档编码为所需的编码标准"

      # feature loop
      - icon: "fas fa-cloud"
        content: "渲染位于 FTP 或云存储位置的文档"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "在呈现为 HTML 时排除字体以减小结果文件大小"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "通过删除注释、多余的空格等来缩小 CSS 和 HTML 输出"

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "通过坐标读取源文档中包含的文本"

      # feature loop
      - icon: "fas fa-border-all"
        content: "在输出表示中显示/隐藏 Excel 工作表的网格线"

      # feature loop
      - icon: "fas fa-wrench"
        content: "指定要在每页上呈现的 Excel 工作表中的行数"

      # feature loop
      - icon: "fas fa-columns"
        content: "呈现电子表格文档时忽略空列"

      # feature loop
      - icon: "fas fa-file-word"
        content: "将 Word 文档渲染为 HTML 页面、图像或 PDF，并带有跟踪更改"

      # feature loop
      - icon: "fas fa-envelope"
        content: "将电子邮件附件呈现为原始文件、图像或 HTML 表示形式"

      # feature loop
      - icon: "fas fa-print"
        content: "设置 PDF 文档的打印限制"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "将 ZIP 存档中包含的内容/文件呈现为附件"

      # feature loop
      - icon: "fas fa-lock"
        content: "从受密码保护的文档中获取附件"

      # feature loop
      - icon: "fas fa-file-code"
        content: "将编程语言文件格式呈现为纯文本"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "查看 CAD 绘图时调整背景颜色"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "查看 Excel 文档并转换为 PDF、HTML、JPG 和 PNG"

      # feature loop
      - icon: "fas fa-heading"
        content: "从 Excel 文件中获取工作表名称 - 显示电子表格的列标题和行号"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "使用注释查看和转换 Microsoft Project 文档"

      # feature loop
      - icon: "fas fa-cube"
        content: "将 CAD 绘图转换为 SVG，以获得更好的查看和缩放体验"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "选择在没有方案的情况下呈现 Visio 图"

    more_feature:
      # more_feature_loop
      - title: "高效可靠地查看文档"
        content: |
          使用 GroupDocs.Viewer API，您可以高效可靠地显示 170 多种文档格式，并且内容和文档结构完整无缺。以下示例代码显示了查看 DOCX 文档的 HTML 表示是多么容易：

          ```cs
          // 实例化查看器
          using (Viewer viewer = new Viewer("sample.docx")
          {
              // 设置视图选项
              HtmlViewOptions options = HtmlViewOptions.ForEmbeddedResources();
              // 将文件转换为带有嵌入资源的 HTML
              viewer.View(options);
          }
          ```
      # more_feature_loop
      - title: "将转换应用于渲染输出"
        content: "您可以使用 GroupDocs.Viewer for .NET API 对呈现的输出文档执行各种转换。这些转换选项使您可以控制呈现渲染输出以供显示的方式。可用的转换是页面旋转选项、页面重新排序选项和应用文本水印。"

      # more_feature_loop
      - title: "使用 Outlook 数据文件"
        content: "GroupDocs.Viewer for .NET API 可以将 Outlook 数据文件 (OST/PST) 中的项目呈现为 PDF、HTML 和图像文件。我们的查看器 API 还能够获取 Outlook 数据文件中包含的文件夹列表。使用 GroupDocs.Viewer for .NET API，您可以指定要从 Outlook 数据文件呈现的文件夹。同样，您也可以获取包含在 OST/PST 格式中的电子邮件作为附件。 GroupDocs.Viewer for .NET 还使您能够根据主题、内容或发件人过滤来自 OST/PST 格式的消息。"

      # more_feature_loop
      - title: "使用 CAD 文档"
        content: "GroupDocs.Viewer for .NET API 可以渲染模型和所有非空布局或渲染 CAD 文件的特定布局。 GroupDocs.Viewer for .NET API 还支持平铺渲染或将 CAD 文档坐标渲染成图像、HTML 或 PDF。您还可以获得 CAD 文档的图层状态."

############################# Testimonials ###############################
testimonials:
  enable: true

  testimonial:
    # testimonial item loop
    - name: "Mats Oustad"
      designation: "Senior Consultant/Partner at Novanet AS"
      content: "在项目中实现和使用 GroupDocs.Viewer for .NET 后，它看起来运行良好。我已经用很多文件进行了测试，到目前为止一切都很好。我扔给它的所有东西都呈现得很好，看起来和在 PDF 查看器或 MS Word 中一样好."
              
    # testimonial item loop
    - name: "Martin Lasarga"
      designation: "Product Manager at Axentria ECM by G.S.I."
      content: "优质的服务和优质的产品。在 GroupDocs.Viewer for .NET 实施过程中，它们非常有帮助和响应迅速，不能高度推荐它们."

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Viewer 为其他流行的开发环境提供文档查看 API"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Viewer for Java"
          image: "/border/groupdocs-viewer-java.svg"
          product: "GroupDocs.Viewer"
          platform: "Java"
          link: "/viewer/java/"

############################# Back to top ###############################
back_to_top:
  enable: true
---
