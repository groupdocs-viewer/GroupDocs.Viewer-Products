---
############################# Static ############################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: en
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
head_title: "Python Document Viewer API for PDF Word Excel HTML Images & Emails"
head_description: "Python document viewer & files rendering API. Add PDF viewer, Word viewer, Excel viewer, Image viewer, HTML viewer, Email viewer in Python applications."

############################# Header ############################
title: "A Powerful Python API for Streamlined Document Rendering"
description: "Render and View 180+ Document Formats (PDF, HTML, Image) with Powerful APIs and Versatile Configuration Options to develop Python applications."
words:
  for: "for"

actions:
  viewer_demo: true
  viewer_demo_file_name: "quarterly-report.docx"
  main: "Free PyPI Download"
  main_link: "https://pypi.org/project/groupdocs-viewer-net/"
  alt: "Licensing"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/python-net"
  title: "Ready to get started?"
  description: "Try GroupDocs.Viewer features for free or request a license"

release:
  title: "Version {0}&nbsp;released"
  notes: "See what’s new"
  downloads: "Downloads"
  link: "https://releases.groupdocs.com/viewer/python-net/release-notes/latest/"

code:
  title: "Render PDF files in Python"
  more: "More examples"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Python-via-.NET"
  install: "pip install groupdocs-viewer-net"
  content: |
    ```python {style=abap}
    import groupdocs.viewer as gv
    import groupdocs.viewer.options as gvo
    hvo = gvo.HtmlViewOptions  
  
    // Set output HTML options, one file per page
    with gv.Viewer("resume.docx") as viewer:
      // Instantiate Viewer
      opts = hvo.for_embedded_resources("page_{0}.html")

      // Render PDF to HTML with embedded resources
      viewer.view(opts)
    ```
############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Viewer at a glance"
  description: "API to render, display, convert documents, slides, diagrams, and many other document types in Python applications"
  features:
    # feature loop
    - title: "View documents efficiently & reliably"
      content: "With GroupDocs.Viewer API you can efficiently render documents of any supportable formats to [HTML](https://docs.groupdocs.com/viewer/python-net/rendering-to-html/), JPEG, PNG, and [PDF](https://docs.groupdocs.com/viewer/python-net/rendering-to-pdf/) with flexible and powerful options while maintaining content and document structure integrity. GroupDocs.Viewer for Python works on Windows and Linux platforms."

    # feature loop
    - title: "Most popular file and document formats are supported"
      content: "We support rendering over the 180 most popular file and document formats that include [Word](https://docs.groupdocs.com/viewer/python-net/render-word-documents/), [Excel](https://docs.groupdocs.com/viewer/python-net/specify-rendering-options/), [PDF](https://docs.groupdocs.com/viewer/python-net/render-pdf-documents/), [PowerPoint](https://docs.groupdocs.com/viewer/python-net/render-presentations/), OpenDocument formats family, Archives, Raster and Vector images, e-Books, programming languages and markups, and many other file types, including encrypted files with password protection."

    # feature loop
    - title: "Customizable output"
      content: "GroupDocs.Viewer allows not only to render the document, but also to control how exactly, which parts of the document should be rendered or now, how they should be rendered, and to apply different transformations to the rendered output."

############################# Platforms ############################
platforms:
  enable: true
  title: "Platform independence"
  description: "GroupDocs.Viewer for Python supports the following operating systems, frameworks and package managers"
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
    - title: "PyPI"
      image: "pypi"

############################# File formats ############################
formats:
  enable: true
  title: "Supported file formats"
  description: |
    GroupDocs.Viewer for Python via .NET supports operations with the following [file formats](https://docs.groupdocs.com/viewer/python-net/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office, OpenDocument and text formats
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
        ### Images, Graphics & Diagrams
        * **Raster images:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
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
        ### Other        
        * **Web:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **Archives:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **Other:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "GroupDocs.Viewer features"
  description: "Seamlessly render, display, and convert PDF and Office Documents"

  items:
    # feature loop
    - icon: "viewhtml"
      title: "[View documents in HTML](https://docs.groupdocs.com/viewer/python-net/rendering-to-html/)"
      content: "Convert document of any type into a HTML document with CSS and SVG, which can be displayed in any modern web-browser."

    # feature loop
    - icon: "rasterize"
      title: "[Rasterize documents to Jpeg or PNG](https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Python-via-.NET/blob/master/Examples/basic_usage/render_document_to_image/render_to_png.py)"
      content: "Rasterize any supportable document format to the raster image, with adjustable image format and compression quality."

    # feature loop
    - icon: "font"
      title: "[Control document fonts](https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Python-via-.NET/blob/master/Examples/advanced_usage/rendering/common_rendering_options/replace_missing_font.py)"
      content: "Identify which fonts are used in a document. Manage missing fonts by replacing them or excluding them from the output."

    # feature loop
    - icon: "convertpdf"
      title: "[Convert to PDF](https://docs.groupdocs.com/viewer/python-net/rendering-to-pdf/)"
      content: "Document of any supportable format can be easily converted and saved to the PDF with adjustable options."

    # feature loop
    - icon: "transform"
      title: "[Apply transformations](https://docs.groupdocs.com/viewer/python-net/add-text-watermark/)"
      content: "Output document can be transformed during rendering - pages can be rotated and/or rearranged, and text watermark may be placed atop of them."

    # feature loop
    - icon: "adjustment"
      title: "[HTML output adjustment](https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Python-via-.NET/blob/master/Examples/basic_usage/render_document_to_html/render_to_html_with_embedded_resources.py)"
      content: "Output HTML documents, generated by the GroupDocs.Viewer, can be tuned very finely: it is allowed to save to the stream or file, with external or embedded resources, callbacks and so on."

    # feature loop
    - icon: "complex"
      title: "[Support of complex document structures](https://docs.groupdocs.com/viewer/python-net/how-to-extract-and-save-attachments/)"
      content: "GroupDocs.Viewer supports not only the single documents, but also files, which internally contain a list or hierarchical structure of documents, like email messages with attachments, ZIP archives with internal files within folders, multi-page TIFF images, and so on."

    # feature loop
    - icon: "optimization"
      title: "[Optimization options](https://docs.groupdocs.com/viewer/python-net/caching-results/)"
      content: "GroupDocs.Viewer contains an adjustable cache subsystem, which can fasten the loading time by using the cached versions of the documents. Also a set of different options for different formats allows to exclude some unnecessary parts or aspects of documents from the rendering (fonts, hidded worksheets, email attachments) to optimize the overall performance"

    # feature loop
    - icon: "passwordprotected"
      title: "[Support of password-protected documents](https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Python-via-.NET/blob/master/Examples/advanced_usage/loading/load_password_protected_document.py)"
      content: "GroupDocs.Viewer allows to open the encrypted documents of different types: PDF, WordProcessing, Spreadsheet, Presentation, and other, by specifying a password in the loading options."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Code samples"
  description: "Some use cases of typical GroupDocs.Viewer for Python via .NET operations"
  items:
    # code sample loop
    - title: "Render DOCX to HTML"
      content: |
        The `HtmlViewOptions` class properties allow you to control the conversion process, more on that [here](https://docs.groupdocs.com/viewer/python-net/rendering-to-html/). For instance, you can embed all external resources in the output HTML file, minify the output file, and optimize it for printing.
        {{< landing/code title="Python">}}
        ```python {style=abap}
        import groupdocs.viewer as gv
        import groupdocs.viewer.options as gvo 

        // Instantiate Viewer
        with gv.Viewer("resume.docx") as viewer:
          // Set output HTML options, one file per page
          viewOptions = gvo.HtmlViewOptions.for_embedded_resources("page_{0}.html")
          // Render DOCX to HTML with embedded resources
          viewer.view(viewOptions)
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Export PPTX to PDF"
      content: |
        Create a `PdfViewOptions` class instance and pass it to the `Viewer.view` method to convert a PowerPoint PPTX file to PDF. The `PdfViewOptions` class properties allow you to control the conversion process. For instance, you can protect the output PDF file, reorder its pages, and specify the quality of document images. Refer to the [following documentation section](https://docs.groupdocs.com/viewer/python-net/rendering-to-pdf/) for details.
        {{< landing/code title="Python">}}
        ```python {style=abap}
        import groupdocs.viewer as gv
        import groupdocs.viewer.options as gvo  

        // Instantiate Viewer
        with gv.Viewer("presentation.pptx") as viewer:
          // Set output PDF options
          viewOptions = gvo.PdfViewOptions("presentation.pdf")
          // Export PPTX to PDF
          viewer.view(viewOptions)
        ```
        {{< /landing/code >}}
############################# Reviews ############################
# reviews:
# enable: true
# title: "GroupDocs products reviews"
# description: "Don't just take our word for it. See what other developers say about our APIs"

# items:
#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "Excellent service and excellent products. They were extremely helpful and responsive during the GroupDocs.Viewer for .NET implementation process, can’t recommend them highly enough."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "After implementing and using GroupDocs.Viewer for .NET in the project it looks to be working very well. I have tested with a lot of documents and so far so good. Everything I’ve thrown at it renders nicely and looks just as good as it would in a PDF viewer or MS Word."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---
