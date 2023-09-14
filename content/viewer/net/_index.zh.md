---
############################# Static ##########################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

lang: zh
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: ".NET 文档查看器 API，呈现 PDF Word Excel 图像 HTML 图表"
head_description: "C# ASP.NET 文件查看器和呈现 API。在 .NET 应用程序中添加 PDF 查看器、Word 查看器、Excel 查看器、图像查看器、HTML 查看器、电子邮件查看器功能。"

############################# Header ##########################
title: "通过 .NET API 呈现和显示文档"
description: ".NET Document Viewer API 使用强大的配置选项将 190 多种文档格式呈现为 PDF、HTML 和图像。"
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
              text: "特征"

            # button loop
            - link: "#support"
              text: "支持"

            # button loop
            - link: "https://products.groupdocs.app/viewer/total"
              text: "现场演示"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "价钱"

    right:
        link_download: "https://www.nuget.org/packages/GroupDocs.Viewer"
        link_learn: "https://docs.groupdocs.com/viewer/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    content: |
      GroupDocs.Viewer for .NET API 帮助您使用 C#、ASP.NET 和其他基于 .NET 的技术创建功能强大的应用程序，这些应用程序可以渲染和显示 190 多种文件格式的文档和图像，而无需安装任何外部软件。文件查看器库将文档光栅化，然后将它们转换为 SVG+HTML+CSS 以优化整体文档呈现体验，以快速、真实文本和应用程序内部的高保真度。您可以选择在您的应用程序中添加文档查看和阅读功能，以显示整个文档、部分文档、特定页面/单元格范围、单个文档层，带有或不带有支持文件格式的注释和评论。
       
      .NET 的 GroupDocs.Viewer 默认将呈现的文档输出缓存到本地磁盘。通过实施适当的接口也支持任何类型的外部缓存存储——Amazon S3、Dropbox、Google Drive、Windows Azure、Redis 或任何其他接口。
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          以下是 GroupDocs.Viewer for .NET 的概述：
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "概述"
          content: |
            * 显示 190 多种文档类型 
            * 获取 HTML、图像、PDF 格式的文件 
            * 旋转和重新排序 
            * 应用水印 
            * 高速缓存 
            * 添加自定义字体 
            * 应用编码标准 
            * 自定义输入数据处理程序 
            * 渲染跟踪更改 
            * 呈现为响应式 HTML 
            * 渲染 PDF 和 CAD 图层 
      
      ## TAB TWO ##
      tab_two:
        description: |
          .NET 的 GroupDocs.Viewer 支持查看所有流行的文档文件格式。只需几行代码，即可在您的 .NET 应用程序中添加 PDF 查看器、Microsoft Office Word、Excel 电子表格、图像、HTML、Outlook 电子邮件、OneNote、项目和图形查看功能。

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
                * **页面布局文件:** PDF, TEX, XPS, OXPS
                * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG, OTG, FODP, FODG
                * **定界符分隔值:** CSV, TSV
                * **网络:** HTML, MHT, MHTML
                * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
                * **PostScript:** PS, EPS
                * **档案:** ZIP, TAR, BZ2, GZ, RAR, RAR5
                * **各种各样的:** OBJ, EPUB, MOBI, DjVu, XML, VCF, VCARD, NUMBERS, NSF

        right:
          enable: true
          table:
            # table loop
            - title: "图像、图形和图表"
              content: |
                * **图片:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB
                * **Windows 图标:** ICO
                * **可缩放矢量图形:** SVG, CDR, CMX, IGS, SVGZ
                * **JPEG2000格式:** JP2, J2C, J2K, JPC, JPF, JPX, JPM
                * **Adobe Photoshop:** PSD, PSB
                * **打印机命令语言:** PCL
                * **立体光刻（3D 打印）:** STL
                * **行业基础课程:** IFC
                * **医学影像:** DICOM
                * **绘图仪文档:** PLT, HPG
                * **Autodesk 设计 Web 格式:** DWF, DWG
                * **AutoCAD 绘图:** DWT, IFC, STL, CF2
                * **基于 ISFF 的 DGN (V7):** DGN

            # table loop
            - title: "编程语言格式"
              content: |
                * **C/C++/C# 文件:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
                * **Java/JavaScript 文件:** JAVA, JS, JSON, PROPERTIES
                * **各种各样的:** VB, PHP, SQL, PL, PY, PV, RB, RST, SASS, SCALA, SCM, SCRIPT, AS, AS3, ASM, BAT, CMAKE, CSS, DIFF, ERB, GROOVY, HAML, LESS, LOG, M, MAKE, MD, ML, MM, SH, SML, VIM, YAML

      ## TAB THREE ##
      tab_three:
        description: |
          .NET 的 GroupDocs.Viewer 支持以下操作系统、框架和包管理器：
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "操作系统"
              content: |
                * Microsoft Windows Server 2003 及更高版本 
                * Microsoft Windows XP 及更高版本 
                * 微软 Windows 10 和 11 
                * Linux（Ubuntu、OpenSUSE、CentOS 等） 
                * 苹果操作系统 

            # table loop
            - icon: "fas fa-code"
              title: "支持的框架"
              content: |
                * .NET Framework 2.0 或更高版本 
                * .NET 核心 3.1 
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
              title: "开发环境"
              content: |
                * Microsoft Visual Studio
                * Visual Studio Code
                * .NET CLI

############################# Features ############################
features:
    enable: true
    title: ".NET 功能的 GroupDocs.Viewer"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "栅格化文档并将其转换为 SVG、HTML 和 CSS"

      # feature loop
      - icon: "fas fa-eye"
        content: "将文本转换为 HTML 并呈现文档以获取 HTML、图像或 PDF 表示"

      # feature loop
      - icon: "fas fa-bolt"
        content: "使用文档的缓存版本加快加载时间"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "使用 3D 效果转换带有形状和文本的演示文稿"

      # feature loop
      - icon: "fas fa-code"
        content: "将 Word、Excel 和电子邮件文档编码为所需的编码标准"

      # feature loop
      - icon: "fas fa-cloud"
        content: "呈现位于 FTP 或云存储位置的文档"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "呈现为 HTML 时排除字体以减小生成的文件大小"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "通过删除注释、额外的空白等来缩小 CSS 和 HTML 输出。"

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
        content: "将 Word 文档呈现为 HTML 页面、图像或 PDF，并带有跟踪更改"

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
        content: "查看 CAD 工程图时调整背景颜色"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "查看 Excel 文档并转换为 PDF、HTML、JPG 和 PNG"

      # feature loop
      - icon: "fas fa-heading"
        content: "从 Excel 文件中获取工作表名称——显示电子表格列标题和行号"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "使用注释查看和转换 Microsoft Project 文档"

      # feature loop
      - icon: "fas fa-cube"
        content: "将 CAD 绘图转换为 SVG 以获得更好的查看和缩放体验"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "选择不使用 Scheme 渲染 Visio 图"

    more_feature:
      # more_feature_loop
      - title: "高效可靠地查看文档"
        content: |
          使用 GroupDocs.Viewer API，您可以高效可靠地显示 190 多种文档格式，同时保持内容和文档结构的完整性。以下示例代码显示查看 DOCX 文档的 HTML 表示是多么容易：

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
      - title: "将转换应用于渲染输出"
        content: "您可以使用 GroupDocs.Viewer for .NET API 对呈现的输出文档执行各种转换。这些转换选项使您可以控制呈现渲染输出以供显示的方式。可用的转换包括页面旋转选项、页面重新排序选项和应用文本水印。"

      # more_feature_loop
      - title: "使用 Outlook 数据文件"
        content: ".NET API 的 GroupDocs.Viewer 可以将 Outlook 数据文件 (OST/PST) 中的项目呈现为 PDF、HTML 和图像文件。我们的查看器 API 还能够获取 Outlook 数据文件中包含的文件夹列表。使用 GroupDocs.Viewer for .NET API，您可以指定要从 Outlook 数据文件呈现的文件夹。同样，您也可以获取以 OST/PST 格式作为附件的电子邮件信息。 .NET 的 GroupDocs.Viewer 还使您能够根据主题、内容或发件人过滤 OST/PST 格式的消息。"

      # more_feature_loop
      - title: "使用 CAD 文档"
        content: "GroupDocs.Viewer for .NET API 可以呈现模型和所有非空布局或呈现 CAD 文件的特定布局。 GroupDocs.Viewer for .NET API 还支持平铺渲染或将 CAD 文档的坐标渲染为图像、HTML 或 PDF。您还可以获得 CAD 文档的图层状态。"

############################# Testimonials ###############################
testimonials:
  enable: true

  testimonial:
    # testimonial item loop
    - name: "Margot Baill"
      designation: "Hireology 产品开发总监"
      content: "使用他们出色的 Ruby SDK 集成 GroupDocs.Viewer for Cloud API 非常简单。没有那么多公司愿意与我们合作来实现我们想要的东西。这是一个很好的伙伴关系。"

    # testimonial item loop
    - name: "Mats Oustad"
      designation: "Novanet AS 高级顾问/合伙人"
      content: "在项目中为 .NET 实施和使用 GroupDocs.Viewer 后，它看起来运行良好。我已经测试了很多文件，到目前为止一切顺利。我投入其中的所有内容都呈现得很好，看起来和在 PDF 查看器或 MS Word 中一样好。"
              
    # testimonial item loop
    - name: "Martin Lasarga"
      designation: "G.S.I. Axentria ECM 产品经理"
      content: "优良的服务和优良的产品。在 GroupDocs.Viewer for .NET 实施过程中，他们提供了极大的帮助和响应，怎么推荐都不为过。"

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
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-viewer-java.png"
          product: "GroupDocs.Viewer"
          platform: "Java"
          link: "/viewer/java/"

############################# Back to top ###############################
back_to_top:
  enable: true
---
