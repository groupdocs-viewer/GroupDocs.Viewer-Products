---
############################# Static ############################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

product: "Viewer"
product_tag: "viewer"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "用于 PDF Word Excel HTML 图像和电子邮件的 Java 文档查看器 API"
head_description: "Java 文档查看器和文件渲染 API。在 Java 应用程序中添加 PDF 查看器、Word 查看器、Excel 查看器、图像查看器、HTML 查看器、电子邮件查看器."

############################# Header ############################
title: "用于渲染和显示文档的 Java API"
description: "文档查看器库，用于开发原生渲染、查看和操作支持 170 多种文件格式的多格式文档的 Java 应用程序。"
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "下载免费试用版"
    link: "https://downloads.groupdocs.com/viewer/java"

############################# SubMenu ############################
submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Viewer for Java"
        image: "/border/groupdocs-viewer-java.svg"
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
              text: "Support"

            # button loop
            - link: "https://products.groupdocs.app/viewer"
              text: "Live Demo"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/java"
              text: "价钱"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/java"
        link_learn: "https://docs.groupdocs.com/viewer/java/"
        link_buy: "https://purchase.groupdocs.com"

############################# 概述 ############################
overview:
    enable: true
    content: |
      GroupDocs.Viewer for Java 结合了一组强大的文档查看器 API，可以在您的 Java 应用程序中显示图像和文档格式，而无需安装其他软件。它原生光栅化文档并将它们转换为 SVG+HTML+CSS 以提高文档查看质量，同时提供真实文本、高保真输出。使用文档呈现 API - 快速查看 PDF、HTML、XML、微软办公软件 Word、Excel 工作表、PowerPoint 演示文稿、Outlook 电子邮件、Visio 图表、项目、元文件、图像和各种其他文件格式，轻松且减少编程风险。它还可以显示受密码保护的文件，并允许在渲染后将文档表示为 HTML、图像或 PDF 形式。我们的文件查看器库是完全可定制的，因为它允许您显示整个文档，或部分呈现它以加快处理过程。通过 GroupDocs.Viewer for Java API，您可以查看页面、电子表格中的特定单元格范围，甚至可以以 PDF 和 CAD 等格式呈现单个文档层。  
        
      Java API 的 GroupDocs.Viewer 允许您呈现带有/不带有注释或注释的文档以支持文件格式。它还使您能够添加自定义字体目录并提取基本文档信息，例如 FileType、Extension、Name、PageCount 等。 
        
      GroupDocs.Viewer for Java 与所有 Java 版本兼容，并支持能够运行 Java 运行时的流行操作系统（Windows、Linux、macOS）。
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
            * 显示 50 多种文档类型
            * 获取 HTML、图像、PDF 版本
            * 旋转和重新排序
            * 应用水印
            * 高速缓存
            * 添加自定义字体
            * 应用编码标准
            * 自定义输入数据处理程序
            * 使用跟踪更改进行渲染
            * 呈现为响应式 HTML
            * 渲染 PDF 和 CAD 图层
            * 渲染受保护的文件
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Viewer for Java 支持所有流行的[文档文件格式](https://docs.groupdocs.com/viewer/java/supported-document-formats/)，包括：微软办公软件、图像、图表等.

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
          GroupDocs.Viewer for Java supports following 操作系统, Frameworks & 包管理器s:
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "操作系统"
              content: |
                * Microsoft Windows Desktop
                * Microsoft Windows Server
                * Linux
                * MacOS

            # table loop
            - icon: "fas fa-code"
              title: "支持的框架"
              content: |
                * Java 7 (1.7) 及更高版本

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

############################# 特征 ############################
features:
    enable: true
    title: "GroupDocs.Viewer for Java 特征"

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
        content: "Rasterize and 转换文档 into SVG, HTML & CSS"

      # feature loop
      - icon: "fas fa-code"
        content: "通过渲染获取文档的 HTML、图像或 PDF 表示"

      # feature loop
      - icon: "fas fa-cloud"
        content: "缓存文档版本以加快加载时间"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "配置自定义字体目录"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "应用编码标准 to Word, Excel and Email Documents"

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "在 FTP 或云存储上远程渲染文档"

      # feature loop
      - icon: "fas fa-border-all"
        content: "渲染时删除或保留注释和评论"

      # feature loop
      - icon: "fas fa-wrench"
        content: "将文档页面呈现为单独的 HTML 页面"

      # feature loop
      - icon: "fas fa-columns"
        content: "渲染隐藏的幻灯片和页面并将页面重新排序应用于渲染文档"

      # feature loop
      - icon: "fas fa-file-word"
        content: "将页面范围、特定页面或所有页面呈现为 HTML"

      # feature loop
      - icon: "fas fa-envelope"
        content: "渲染或隐藏文档注释"

      # feature loop
      - icon: "fas fa-print"
        content: "通过渲染为某些文档格式创建响应式 HTML"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "通过排除字体减少渲染 HTML 的结果文件大小"

      # feature loop
      - icon: "fas fa-lock"
        content: "删除注释、多余的空格等，以缩小输出 HTML 和 CSS"

      # feature loop
      - icon: "fas fa-file-code"
        content: "使用源文档的坐标读取包含的文本"
      
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
        content: "平铺渲染或按 CAD 文档坐标渲染为图像、HTML 或 PDF"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "渲染为 PDF 时设置打印限制"

    more_feature:
      # more_feature_loop
      - title: "用于查看文档的高效可靠 API"
        content: |
          GroupDocs.Viewer for Java API 可用于查看、渲染和显示超过 150 种不同文件格式的文档。它在保持文档内容和结构完整的同时可靠有效地完成。以下示例显示了 GroupDocs.Viewer for Java API 使用 Java 将 DOCX 文件呈现为图像文件的难易程度：
          
          ```java
          // 初始化查看器
          Viewer viewer = new Viewer("sample.docx");
          // 创建视图选项
          PdfViewOptions viewOptions = new PdfViewOptions();
          // 将文件转换为 PDF 并检查当前目录中的输出
          viewer.view(viewOptions);
          ```
      # more_feature_loop
      - title: "在渲染文档时执行转换"
        content: "Java API 的 GroupDocs.Viewer 为您提供了各种转换选项，可应用于呈现的文档，以获得更加自定义的视图和显示。您可以通过提供角度来旋转页面。您可以按呈现页面的顺序。将特定文本作为水印应用到渲染的页面或图像。通过 GroupDocs.Viewer for Java API，您还可以将自定义字体添加到正在呈现的文档中。"

      # more_feature_loop
      - title: "使用电子邮件附件"
        content: "GroupDocs.Viewer for Java API 允许您获取电子邮件的特定或所有附件。获得所需的电子邮件附件后，您可以将这些附件呈现为图像或 HTML。"

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Viewer 为其他流行的开发环境提供文档查看 API"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Viewer for .NET"
          image: "/border/groupdocs-viewer-net.svg"
          product: "GroupDocs.Viewer"
          platform: ".NET"
          link: "/viewer/net/"

############################# Back to top ###############################
back_to_top:
  enable: true
---