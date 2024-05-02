---
############################# Static ############################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: zh
product: "Viewer"
product_tag: "viewer"
platform: "Python via .NET"
platform_tag: "python-net"

############################# Drop-down ############################
supported_platforms:
  items:
    # supported_platforms loop
    - title: ".NET"
      tag: "net"
    # supported_platforms loop
    - title: "Java"
      tag: "java"
    # supported_platforms loop
    - title: "Node.js"
      tag: "nodejs-java" 
    # supported_platforms loop
    - title: "Python"
      tag: "python-net" 


############################# Head ############################
head_title: "Python API 用于查看文档（PDF、Word、Excel、HTML、图像和电子邮件）"
head_description: "Python API 用于文件可视化和文档查看。将 PDF 查看器、Word 查看器、Excel 查看器、图像查看器、HTML 查看器和电子邮件查看器添加到您的 Python 应用中。"

############################# Header ############################
title: "用于优化文档可视化的强大 Python API"
description: "使用功能强大的 API 和灵活的配置选项，可视化和呈现超过 180 种文档格式（PDF、HTML、图像），用于开发 Python 应用。"
words:
  for: "for"

actions:
  main: "从 PyPI 免费下载"
  main_link: "https://pypi.org/project/groupdocs-viewer/"
  alt: "许可"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/python-net"
  title: "准备好开始了吗？"
  description: "免费试用 GroupDocs.Viewer 功能或申请许可证"

release:
  title: "版本 {0} 已发布"
  notes: "看看有什么新鲜事"
  downloads: "下载"
  link: "https://releases.groupdocs.com/viewer/python-net/release-notes/latest/"

code:
  title: "在 Python 中可视化 PDF 文件"
  more: "更多示例"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Python-via-.NET"
  install: "pip install GroupDocs.Viewer"
  content: |
    ```python {style=abap}
    import groupdocs.viewer as gv
    import groupdocs.viewer.options as gvo
    hvo = gvo.HtmlViewOptions  
  
    // 设置 HTML 输出选项（每页一个文件）
    with gv.Viewer("resume.docx") as viewer:
      // 创建查看器实例
      opts = hvo.for_embedded_resources("page_{0}.html")

      // 使用嵌入资源将 PDF 渲染为 HTML
      viewer.view(opts)
    ```
############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Viewer 概述"
  description: "用于在 Python 应用中可视化、查看和转换文档、幻灯片、图表和许多其他类型文档的 API"
  features:
    # feature loop
    - title: "高效可靠地呈现文档"
      content: "使用 GroupDocs.Viewer API，您可以使用灵活强大的选项，将任何受支持格式的文档高效可视化为 HTML、JPEG、PNG 和 PDF，同时保持文档内容和结构的完整性。GroupDocs.Viewer for Python 适用于 Windows 和 Linux 平台。"

    # feature loop
    - title: "支持大多数常用文件和文档格式"
      content: "我们支持可视化 180 多种最常用的文件和文档格式，包括 Word、Excel、PDF、PowerPoint、OpenDocument 格式系列、存档文件、光栅和矢量图像、电子书、编程语言和标记语言以及许多其他类型的文件，包括使用密码保护进行加密的文件。"

    # feature loop
    - title: "可定制的输出"
      content: "GroupDocs.Viewer 不仅可以让您可视化文档，还可以精确控制需要可视化或不需可视化的文档部分、可视化方式以及将各种转换应用于可视化输出。"

############################# Platforms ############################
platforms:
  enable: true
  title: "与平台无关"
  description: "GroupDocs.Viewer for Python 支持以下操作系统、框架和包管理器"
  items:
    # platform loop
    - title: "Amazon"
      image: "amazon"
    # platform loop
    - title: "Docker"
      image: "docker"
    # platform loop
    - title: "Azure"
      image: "azure"
    # platform loop
    - title: "Eclipse"
      image: "eclipse"
    # platform loop
    - title: "IntelliJ"
      image: "intellij"
    # platform loop
    - title: "Windows"
      image: "windows"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "NPM"
      image: "npm"
    # platform loop
    - title: "PyPI"
      image: "pypi"

############################# File formats ############################
formats:
  enable: true
  title: "支持的文件格式"
  description: |
    GroupDocs.Viewer for Python (通过 .NET) 支持以下文件格式的操作: [受支持的文件格式](https://docs.groupdocs.com/viewer/python-net/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office、OpenDocument 和文本格式
        * **Word:** DOC, DOCX, DOCM, DOT, DOTX, DOTM, RTF, TXT
        * **Excel:** XLS, XLSX, XLSM, XLSB, XLTM, XLT, XLTM, XLTX
        * **PowerPoint:** PPT, PPTX, PPS, PPSX, PPSM, POT, POTM, POTX, PPTM        
        * **Project:** MPP, MPT, MPX
        * **Outlook:** MSG, EML, EMLX, PST, OST
        * **OneNote:** ONE
        * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG
        * **Fixed Page Layout:** PDF, TEX, XPS, OXPS
        * **e-Books:** EPUB, MOBI, DjVu
        * **Delimiter-Separated Values:** CSV, TSV
    # group loop
    - color: "blue"
      content: |
        ### 图像、图形和图表
        * **光栅图像:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
        * **Windows Icon:** ICO
        * **Scalable Vector Graphics:** SVG, CDR, CMX, IGS, SVGZ        
        * **Adobe Photoshop:** PSD, PSB        
        * **Stereo Lithography (3D Printing):** STL        
        * **Medical Imaging:** DICOM
        * **Plotter Documents:** PLT, HPG
        * **Autodesk Design Web Formats:** DWF, DWG
        * **AutoCAD Drawing:** DWT, IFC, STL, CF2        
      # group loop
    - color: "red"
      content: |
        ### 其他        
        * **网络:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **档案:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **其他:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "GroupDocs.Viewer 功能"
  description: "无缝渲染、显示和转换 PDF 和 Office 文档"

  items:
    # feature loop
    - icon: "viewhtml"
      title: "查看 HTML 格式的文档"
      content: "使用 CSS 和 SVG 将任何类型的文档转换为 HTML 文档，可以在任何现代网络浏览器中显示。"

    # feature loop
    - icon: "rasterize"
      title: "光栅化文档"
      content: "将任何支持的文档格式光栅化为光栅图像，并具有可调整的图像格式和压缩质量。"

    # feature loop
    - icon: "sourcecode"
      title: "渲染并突出显示编程代码"
      content: "支持所有流行的编程、脚本和标记语言，能够解析和突出显示其语法。"

    # feature loop
    - icon: "convertpdf"
      title: "转换为 PDF"
      content: "任何支持格式的文档都可以通过可调整的选项轻松转换并保存为 PDF。"

    # feature loop
    - icon: "transform"
      title: "应用转换"
      content: "输出文档可以在渲染过程中进行转换 - 页面可以旋转和/或重新排列，并且文本水印可以放置在它们的顶部。"

    # feature loop
    - icon: "adjustment"
      title: "HTML 输出调整"
      content: "由 GroupDocs.Viewer 生成的输出 HTML 文档可以进行非常精细的调整：允许使用外部或嵌入资源、回调等保存到流或文件。"

    # feature loop
    - icon: "complex"
      title: "支持复杂的文档结构"
      content: "GroupDocs.Viewer 不仅支持单个文档，还支持内部包含文档列表或层次结构的文件，例如带有附件的电子邮件、文件夹内带有内部文件的 ZIP 存档、多页 TIFF 图像等。"

    # feature loop
    - icon: "optimization"
      title: "优化选项"
      content: "GroupDocs.Viewer 包含一个可调整的缓存子系统，它可以通过使用文档的缓存版本来缩短加载时间。此外，针对不同格式的一组不同选项允许从渲染中排除文档的一些不必要的部分或方面（字体、隐藏的工作表、电子邮件附件），以优化整体性能"

    # feature loop
    - icon: "passwordprotected"
      title: "支持受密码保护的文档"
      content: "GroupDocs.Viewer 允许通过在加载选项中指定密码来打开不同类型的加密文档：PDF、WordProcessing、电子表格、演示文稿等。"

############################# Code samples ############################
code_samples:
  enable: true
  title: "代码示例"
  description: "通过 .NET 使用 Python 的 GroupDocs.Viewer 操作的一些典型用例"
  items:
    # code sample loop
    - title: "将 DOCX 转换为 HTML"
      content: |
        `HtmlViewOptions` 类属性可以让您控制转换过程。有关详细信息，请参阅 [此处](https://docs.groupdocs.com/viewer/python-net/rendering-to-html/). 例如，您可以将所有外部资源嵌入输出 HTML 文件，压缩输出文件并将其优化为打印。
        {{< landing/code title="Python">}}
        ```python {style=abap}
        import groupdocs.viewer as gv
        import groupdocs.viewer.options as gvo 

        // 创建查看器实例 (already translated)
        with gv.Viewer("resume.docx") as viewer:
          // 设置 HTML 输出选项（每页一个文件） (already translated)
          viewOptions = gvo.HtmlViewOptions.for_embedded_resources("page_{0}.html")
          // 使用嵌入资源将 PDF 渲染为 HTML (already translated)
          viewer.view(viewOptions)
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "将 PPTX 导出为 PDF"
      content: |
        创建一个 `PdfViewOptions` 类实例并将其传递给 `Viewer.view` 方法，以将 PowerPoint PPTX 文件转换为 PDF。 `PdfViewOptions` 类属性可以让您控制转换过程。例如，您可以保护输出 PDF 文件，更改其页面顺序并指定文档图像质量。有关详细信息，请参阅 [文档的下一部分](https://docs.groupdocs.com/viewer/python-net/rendering-to-pdf/).
        {{< landing/code title="JavaScript">}}
        ```python {style=abap}
        import groupdocs.viewer as gv
        import groupdocs.viewer.options as gvo  

        // 创建查看器实例 (already translated)
        with gv.Viewer("presentation.pptx") as viewer:
          // 设置输出 PDF 选项 (Set output PDF options)
          viewOptions = gvo.PdfViewOptions("presentation.pdf")
          // 将 PPTX 导出为 PDF (Export PPTX to PDF) (already translated)
          viewer.view(viewOptions)
        ```
        {{< /landing/code >}}
############################# Reviews ############################
# reviews:
# enable: true
# title: "GroupDocs 产品评论"
# description: "不要只相信我们的话。看看其他开发人员如何评价我们的 API"

# items:
#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "优质的服务和优质的产品。他们在 GroupDocs.Viewer for .NET 实施过程中提供了极大的帮助和响应，强烈推荐他们。"
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "在项目中实现并使用 GroupDocs.Viewer for .NET 后，它看起来运行得很好。我已经用很多文档进行了测试，到目前为止一切顺利。我扔给它的所有内容都可以很好地呈现，并且看起来与在 PDF 查看器或 MS Word 中一样好。"
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---
