---
############################# Static ############################
layout: "auto-gen"
date: 2021-05-12T12:18:34+03:00
draft: false

############################# Head ############################
head_title: "View ML files in C# .NET Applications | Document Viewer APIs"
head_description: "Render and view ML files in .NET applications. Also display a wide range of business documents, images, diagrams, web and other formats using native .NET APIs."

############################# Header ############################
title: "View ML Files in C#"
description: "Cross-platform ML files viewing solution using server side GroupDocs.Viewer for .NET APIs, without depending on any third party software, pre-installed on your system."
bg_image: "https://cms.admin.containerize.com/templates/aspose/App_Themes/V3/images/bg/header1.png"
bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Download Free Trial"
    link: "https://downloads.groupdocs.com/viewer/net"

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
              text: "API Reference"

            # button loop
            - link: "https://github.com/groupdocs-viewer"
              text: "Code Examples"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Live Demos"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Pricing"

    right:
        link_download: "https://downloads.groupdocs.com/viewer"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# About ############################
about:
    enable: true
    title: "About GroupDocs.Viewer for .NET API"
    content: |
        Start viewing [170+ popular document formats](https://docs.groupdocs.com/viewer/net/supported-document-formats/) in your .NET applications using [GroupDocs.Viewer for .NET](https://products.groupdocs.com/viewer/net) APIs by adding a few lines of code. Developers can easily display PDF, Word Processing, Excel Spreadsheet, Presentation, Visio, Project, Outlook and many other popular document formats in HTML5, image or PDF modes. The document rendering is fast, identical to the original source file, and it does not require installing Microsoft Office or any other external libraries.

############################# Steps ############################
steps:
    enable: true
    title_left: "Steps for Viewing ML File in C#"
    content_left: |
        [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net) makes it easy for .NET developers to add ML file viewing feature in their applications by implementing a few easy steps.

        *   Create an instance of Viewer class and load the ML file with full path.
        *   Set options for rendering ML file into PNG format.
        *   Create view for rendered output file.
        
    title_right: "System Requirements"
    content_right: |
        GroupDocs.Viewer for .NET APIs are supported on all major platforms and operating systems. Before executing the code below, please make sure that you have the following prerequisites installled on your system.

        *   Operating Systems: Microsoft Windows, Linux, MacOS
        *   Development Environments: Microsoft Visual Studio, Xamarin, MonoDevelop
        *   Frameworks: .NET Framework, .NET Standard, .NET Core, Mono
        *   Get the latest version of GroupDocs.Viewer for .NET downloaded from [Nuget](https://www.nuget.org/packages/groupdocs.viewer)
        
    code: |
        ```cs
        // Instantiate viewer
        using (Viewer viewer = new Viewer("sample.ml"))
        {
        	ViewOptions viewOptions = new PngViewOptions();
        	viewer.View(viewOptions);
        }
        ```
        
############################# Demos ############################
demos:
    enable: true
    title: "ML Viewer Live Demos"
    content: |
        Display ML file right now by visiting [GroupDocs.Viewer Live Demos](https://products.groupdocs.app/viewer/family) website.  
        The live demo has the following benefits
        
############################# About Formats ############################
about_formats:
    enable: true
    format:
        # format loop
        - icon: "far fa-file-ml"
          title: "About ML File Format"
          content: |
            {{ml}}

          link: "/{{ml_url}}"

############################# More Formats ############################
more_formats:
    enable: true
    title: "Other File Formats Rendering & Viewing"
    content: |
        Multi format documents and images viewer API for .NET. View some of the popular file formats below without any external viewers.
    format: 
        # format loop
        - name: "DOC Viewer"
          link: "https://products.groupdocs.com/viewer/net/doc"
          description: "Microsoft Word Document"

        # format loop
        - name: "DOCM Viewer"
          link: "https://products.groupdocs.com/viewer/net/docm"
          description: "Microsoft Word Macro-Enabled Document"

        # format loop
        - name: "DOCX Viewer"
          link: "https://products.groupdocs.com/viewer/net/docx"
          description: "Microsoft Word Open XML Document"

        # format loop
        - name: "DOT Viewer"
          link: "https://products.groupdocs.com/viewer/net/dot"
          description: "Microsoft Word Document Template"

        # format loop
        - name: "DOTM Viewer"
          link: "https://products.groupdocs.com/viewer/net/dotm"
          description: "Microsoft Word Macro-Enabled Template"

        # format loop
        - name: "DOTX Viewer"
          link: "https://products.groupdocs.com/viewer/net/dotx"
          description: "Word Open XML Document Template"

        # format loop
        - name: "RTF Viewer"
          link: "https://products.groupdocs.com/viewer/net/rtf"
          description: "Rich Text File Format"

        # format loop
        - name: "TXT Viewer"
          link: "https://products.groupdocs.com/viewer/net/txt"
          description: "Plain Text File Format"

        # format loop
        - name: "XLS Viewer"
          link: "https://products.groupdocs.com/viewer/net/xls"
          description: "Microsoft Excel Binary File Format"

        # format loop
        - name: "XLSX Viewer"
          link: "https://products.groupdocs.com/viewer/net/xlsx"
          description: "Microsoft Excel Open XML Spreadsheet"

        # format loop
        - name: "XLSM Viewer"
          link: "https://products.groupdocs.com/viewer/net/xlsm"
          description: "Microsoft Excel Macro-Enabled Spreadsheet"

        # format loop
        - name: "XLSB Viewer"
          link: "https://products.groupdocs.com/viewer/net/xlsb"
          description: "Microsoft Excel Binary Spreadsheet File"

        # format loop
        - name: "XLTX Viewer"
          link: "https://products.groupdocs.com/viewer/net/xltx"
          description: "Microsoft Excel Open XML Template"

        # format loop
        - name: "TSV Viewer"
          link: "https://products.groupdocs.com/viewer/net/tsv"
          description: "Tab Separated Values File"

        # format loop
        - name: "XLAM Viewer"
          link: "https://products.groupdocs.com/viewer/net/xlam"
          description: "Microsoft Excel Macro-Enabled Add-In"

        # format loop
        - name: "CSV Viewer"
          link: "https://products.groupdocs.com/viewer/net/csv"
          description: "Comma Separated Values File"

        # format loop
        - name: "PPT Viewer"
          link: "https://products.groupdocs.com/viewer/net/ppt"
          description: "PowerPoint Presentation"

        # format loop
        - name: "PPS Viewer"
          link: "https://products.groupdocs.com/viewer/net/pps"
          description: "Microsoft PowerPoint Slide Show"

        # format loop
        - name: "PPTX Viewer"
          link: "https://products.groupdocs.com/viewer/net/pptx"
          description: "PowerPoint Open XML Presentation"

        # format loop
        - name: "PPSX Viewer"
          link: "https://products.groupdocs.com/viewer/net/ppsx"
          description: "PowerPoint Open XML Slide Show"

        # format loop
        - name: "POTX Viewer"
          link: "https://products.groupdocs.com/viewer/net/potx"
          description: "Microsoft PowerPoint Open XML Template"

        # format loop
        - name: "POTM Viewer"
          link: "https://products.groupdocs.com/viewer/net/potm"
          description: "Microsoft PowerPoint Template"

        # format loop
        - name: "PPTM Viewer"
          link: "https://products.groupdocs.com/viewer/net/pptm"
          description: "Microsoft PowerPoint Presentation"

        # format loop
        - name: "PPSM Viewer"
          link: "https://products.groupdocs.com/viewer/net/ppsm"
          description: "Microsoft PowerPoint Slide Show"

        # format loop
        - name: "PDF Viewer"
          link: "https://products.groupdocs.com/viewer/net/pdf"
          description: "Adobe Portable Document Format"

        # format loop
        - name: "XPS Viewer"
          link: "https://products.groupdocs.com/viewer/net/xps"
          description: "Open XML Paper Specification"

        # format loop
        - name: "TEX Viewer"
          link: "https://products.groupdocs.com/viewer/net/tex"
          description: "LaTeX Source Document"

        # format loop
        - name: "ODS Viewer"
          link: "https://products.groupdocs.com/viewer/net/ods"
          description: "Open Document Spreadsheet"

        # format loop
        - name: "ODP Viewer"
          link: "https://products.groupdocs.com/viewer/net/odp"
          description: "OpenDocument Presentation File Format"

        # format loop
        - name: "OTP Viewer"
          link: "https://products.groupdocs.com/viewer/net/otp"
          description: "Origin Graph Template"

        # format loop
        - name: "ODT Viewer"
          link: "https://products.groupdocs.com/viewer/net/odt"
          description: "Open Document Text"

        # format loop
        - name: "OTT Viewer"
          link: "https://products.groupdocs.com/viewer/net/ott"
          description: "Open Document Template"

        # format loop
        - name: "VST Viewer"
          link: "https://products.groupdocs.com/viewer/net/vst"
          description: "Microsoft Visio 2003-2010 XML Drawing"

        # format loop
        - name: "TIFF Viewer"
          link: "https://products.groupdocs.com/viewer/net/tiff"
          description: "Tagged Image File Format"

        # format loop
        - name: "JPEG Viewer"
          link: "https://products.groupdocs.com/viewer/net/jpeg"
          description: "JPEG Image"

        # format loop
        - name: "PNG Viewer"
          link: "https://products.groupdocs.com/viewer/net/png"
          description: "Portable Network Graphic"

        # format loop
        - name: "GIF Viewer"
          link: "https://products.groupdocs.com/viewer/net/gif"
          description: "Graphical Interchange Format File"

        # format loop
        - name: "BMP Viewer"
          link: "https://products.groupdocs.com/viewer/net/bmp"
          description: "Bitmap File Format"

        # format loop
        - name: "ICO Viewer"
          link: "https://products.groupdocs.com/viewer/net/ico"
          description: "Microsoft Icon File"

        # format loop
        - name: "PSD Viewer"
          link: "https://products.groupdocs.com/viewer/net/psd"
          description: "Adobe Photoshop Document"

        # format loop
        - name: "WMF Viewer"
          link: "https://products.groupdocs.com/viewer/net/wmf"
          description: "Windows Metafile"

        # format loop
        - name: "EMF Viewer"
          link: "https://products.groupdocs.com/viewer/net/emf"
          description: "Enhanced Metafile Format"

        # format loop
        - name: "WEBP Viewer"
          link: "https://products.groupdocs.com/viewer/net/webp"
          description: "Raster Web Image File Format"

        # format loop
        - name: "SVG Viewer"
          link: "https://products.groupdocs.com/viewer/net/svg"
          description: "Scalable Vector Graphics File"

        # format loop
        - name: "JP2 Viewer"
          link: "https://products.groupdocs.com/viewer/net/jp2"
          description: "JPEG 2000 Core Image File"

        # format loop
        - name: "MPP Viewer"
          link: "https://products.groupdocs.com/viewer/net/emz"
          description: "Microsoft Project Document"

        # format loop
        - name: "MPT Viewer"
          link: "https://products.groupdocs.com/viewer/net/wmz"
          description: "Microsoft Project Template"

        # format loop
        - name: "HTML Viewer"
          link: "https://products.groupdocs.com/viewer/net/html"
          description: "Hyper Text Markup Language"

        # format loop
        - name: "MHT Viewer"
          link: "https://products.groupdocs.com/viewer/net/mht"
          description: "MIME Encapsulation of Aggregate HTML"

        # format loop
        - name: "MHTML Viewer"
          link: "https://products.groupdocs.com/viewer/net/mhtml"
          description: "MIME Encapsulation of Aggregate HTML"

        # format loop
        - name: "MSG Viewer"
          link: "https://products.groupdocs.com/viewer/net/msg"
          description: "Microsoft Outlook E-mail Message"

        # format loop
        - name: "EML Viewer"
          link: "https://products.groupdocs.com/viewer/net/eml"
          description: "E-mail Message"

        # format loop
        - name: "ONE Viewer"
          link: "https://products.groupdocs.com/viewer/net/one"
          description: "Microsoft OneNote"

        # format loop
        - name: "WMF Viewer"
          link: "https://products.groupdocs.com/viewer/net/wmf"
          description: "Windows Metafile"

        # format loop
        - name: "EMF Viewer"
          link: "https://products.groupdocs.com/viewer/net/emf"
          description: "Windows Enhanced Metafile"

        # format loop
        - name: "PSD Viewer"
          link: "https://products.groupdocs.com/viewer/net/psd"
          description: "Adobe Photoshop Document"

        # format loop
        - name: "VSD Viewer"
          link: "https://products.groupdocs.com/viewer/net/vsd"
          description: "Microsoft Visio 2003-2010 Drawing"

        # format loop
        - name: "VSDX Viewer"
          link: "https://products.groupdocs.com/viewer/net/vsdx"
          description: "Microsoft Visio Drawing"

        # format loop
        - name: "VSS Viewer"
          link: "https://products.groupdocs.com/viewer/net/vss"
          description: "Microsoft Visio 2003-2010 Stencil"

        # format loop
        - name: "VDX Viewer"
          link: "https://products.groupdocs.com/viewer/net/vdx"
          description: "Microsoft Visio 2003-2010 XML Drawing"

        # format loop
        - name: "VDW Viewer"
          link: "https://products.groupdocs.com/viewer/net/vdw"
          description: "Microsoft Visio 2010 Web Drawing"

        # format loop
        - name: "EPUB Viewer"
          link: "https://products.groupdocs.com/viewer/net/epub"
          description: "Digital E-Book File Format"


############################# Back to top ###############################
back_to_top:
    enable: true
---
