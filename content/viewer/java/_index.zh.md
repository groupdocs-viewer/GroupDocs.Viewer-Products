---
############################# Static ############################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

lang: zh
product: "Viewer"
product_tag: "viewer"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "用于 PDF Word Excel HTML 图像和电子邮件的 Java 文档查看器 API"
head_description: "Java 文档查看器和文件呈现 API。在 Java 应用程序中添加 PDF 查看器、Word 查看器、Excel 查看器、图像查看器、HTML 查看器、电子邮件查看器。"

############################# Header ############################
title: "用于呈现和显示文档的 Java API"
description: "用于开发 Java 应用程序的文档查看器库，这些应用程序本机呈现、查看和操作多格式文档，支持 170 多种文件格式。"
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
              text: "特征"

            # button loop
            - link: "#support"
              text: "支持"

            # button loop
            - link: "https://products.groupdocs.app/viewer/total"
              text: "现场演示"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/java"
              text: "价钱"

    right:
        link_download: "https://releases.groupdocs.com/viewer/java/"
        link_learn: "https://docs.groupdocs.com/viewer/java/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    content: |
      GroupDocs.Viewer for Java 结合了一组强大的文档查看器 API，无需安装额外的软件即可在您的 Java 应用程序中显示图像和文档格式。它本机光栅化文档并将它们转换为 SVG+HTML+CSS 以提高文档查看质量，同时提供真实文本、高保真输出。使用文档呈现 API – 快速查看 PDF、HTML、XML、Microsoft Office Word、Excel 工作表、PowerPoint 演示文稿、Outlook 电子邮件、Visio 图表、项目、图元文件、图像和各种其他文件格式，轻松且编程风险更少。它还可以显示受密码保护的文件，并允许在呈现后以 HTML、图像或 PDF 形式获取文档表示。我们的文件查看器库是非常可定制的，因为它允许您显示整个文档，或部分呈现它以加快流程。通过 GroupDocs.Viewer for Java API，您可以查看页面、电子表格中的特定单元格范围，甚至可以呈现 PDF 和 CAD 等格式的单个文档层。  

      GroupDocs.Viewer for Java API 允许您呈现带/不带注释或支持文件格式注释的文档。它还使您能够添加自定义字体目录并提取基本文档信息，例如文件类型、扩展名、名称、页数等。  

      GroupDocs.Viewer for Java 与所有 Java 版本兼容，并支持能够运行 Java 运行时的流行操作系统（Windows、Linux、macOS）。
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          以下是 GroupDocs.Viewer for Java 的概述：
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "概述"
          content: |
            * 显示 170 多种文档类型 
            * 获取 HTML、图像、PDF 版本 
            * 旋转和重新排序 
            * 应用水印 
            * 高速缓存 
            * 添加自定义字体 
            * 应用编码标准 
            * 自定义输入数据处理程序 
            * 渲染跟踪更改 
            * 呈现为响应式 HTML 
            * 渲染 PDF 和 CAD 图层 
            * 渲染受保护的文件 
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Viewer for Java 支持所有流行的文档文件格式，包括：Microsoft Office、图像、图表和许多其他格式。

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
          GroupDocs.Viewer for Java 支持以下操作系统、框架和包管理器：
        
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
                * J2SE 8.0 (1.8) 或更高版本（例如 Java 17） 

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-cogs"
              title: "开发环境"
              content: |
                * NetBeans
                * IntelliJ IDEA
                * Eclipse

            # table loop
            - icon: "fas fa-tools"
              title: "构建自动化工具"
              content: |
                * Maven
                * Gradle

############################# Features ############################
features:
    enable: true
    title: "Java 功能的 GroupDocs.Viewer"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "HTML、PDF、图像、Word、Excel 和其他文档格式的查看器"

      # feature loop
      - icon: "fas fa-eye"
        content: "将 AutoCAD 工程图 (DWG) 文件渲染为 SVG 格式"

      # feature loop
      - icon: "fas fa-bolt"
        content: "调整转换文件的背景颜色"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "栅格化文档并将其转换为 SVG、HTML 和 CSS"

      # feature loop
      - icon: "fas fa-code"
        content: "通过渲染获取文档的 HTML、图像或 PDF 表示"

      # feature loop
      - icon: "fas fa-cloud"
        content: "文档的缓存版本可加快加载时间"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "配置自定义字体目录"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "将编码标准应用于 Word、Excel 和电子邮件文档"

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "在 FTP 或云存储中远程呈现文档"

      # feature loop
      - icon: "fas fa-border-all"
        content: "渲染时删除或保留注释和评论"

      # feature loop
      - icon: "fas fa-wrench"
        content: "将文档页面呈现为单独的 HTML 页面"

      # feature loop
      - icon: "fas fa-columns"
        content: "呈现隐藏的幻灯片和页面并将页面重新排序应用于呈现的文档"

      # feature loop
      - icon: "fas fa-file-word"
        content: "将页面范围、特定页面或所有页面呈现为 HTML"

      # feature loop
      - icon: "fas fa-envelope"
        content: "呈现或隐藏文档注释"

      # feature loop
      - icon: "fas fa-print"
        content: "通过渲染为某些文档格式创建响应式 HTML"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "通过排除字体减少呈现的 HTML 的结果文件大小"

      # feature loop
      - icon: "fas fa-lock"
        content: "删除注释、额外的空白等，以缩小输出 HTML 和 CSS"

      # feature loop
      - icon: "fas fa-file-code"
        content: "使用源文档的坐标来阅读包含的文本"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "在渲染输出的 Excel 工作表中显示/隐藏单元格边框"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "在 Excel 工作表中呈现每页的特定行数"

      # feature loop
      - icon: "fas fa-heading"
        content: "渲染模型和所有非空布局或 CAD 文件的特定布局"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "将 Outlook 数据文件 (OST/PST) 中的项目呈现为 PDF"

      # feature loop
      - icon: "fas fa-cube"
        content: "平铺渲染或按 CAD 文档的坐标渲染为图像、HTML 或 PDF"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "渲染为 PDF 时设置打印限制"

    more_feature:
      # more_feature_loop
      - title: "用于查看文档的高效可靠的 API"
        content: |
          GroupDocs.Viewer for Java API 可用于查看、呈现和显示超过 150 种不同文件格式的文档。它可靠且高效地完成，同时保持文档的内容和结构完好无损。以下示例显示了 GroupDocs.Viewer for Java API 使用 Java 将 DOCX 文件呈现为图像文件的难易程度：

          ```java
          // Initialize Viewer
          Viewer viewer = new Viewer("invoice.docx");
          // Create view options
          PdfViewOptions viewOptions = new PdfViewOptions();
          // Convert file to PDF and check the output in the current directory
          viewer.view(viewOptions);
          ```
      # more_feature_loop
      - title: "在呈现文档时执行转换"
        content: "用于 Java API 的 GroupDocs.Viewer 为您提供了多种转换选项，可应用于呈现的文档以获得更加自定义的视图和显示。您可以通过提供角度来旋转页面。您可以对呈现页面的顺序进行排序。将特定文本作为水印应用于呈现的页面或图像。通过 GroupDocs.Viewer for Java API，您还可以将自定义字体添加到正在呈现的文档中。"

      # more_feature_loop
      - title: "使用电子邮件附件"
        content: "GroupDocs.Viewer for Java API 允许您获取电子邮件的特定或所有附件。获得所需的电子邮件附件后，您可以将这些附件呈现为图像或 HTML。"

############################# Support ############################
support:
    enable: true

############################# Solutions ##########################
solutions:
    enable: true
    title: "GroupDocs.Viewer 为其他流行的开发环境提供文档查看 API"

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