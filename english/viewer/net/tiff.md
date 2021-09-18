---
############################# Static ############################
layout: "auto-gen"
date: 2021-05-12T12:19:06+03:00
draft: false

############################# Head ############################
head_title: ".NET TIFF Viewer API - Read, View, Render in C# VB.NET"
head_description: ".NET document viewer API to read, render and display TIFF in any type of C#, ASP.NET, VB.NET & .NET Core applications."

############################# Header ############################
title: "TIFF File Viewer for C# .NET Applications"
description: ".NET document viewer API to read, render and display TIFF file in any type of C#, ASP.NET, VB.NET & .NET Core applications. View the rendered files with true formatting & layout in HTML5, PDF or as an image using a few lines of the code."
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
        Start viewing 170+ popular document formats in your .NET applications using GroupDocs.Viewer for .NET APIs by adding a few lines of code. Developers can easily display PDF, Word Processing, Excel Spreadsheet, Presentation, Visio, Project, Outlook and many other popular document formats in HTML5, image or PDF modes. The document rendering is fast, identical to the original source file, and it does not require installing Microsoft Office or any other external libraries.

############################# Steps ############################
steps:
    enable: true
    title_left: "Steps for Viewing TIFF File in C#"
    content_left: |
        [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/) makes it easy for .NET developers to add TIFF file viewing feature in their applications by implementing a few easy steps.

        *   Create an instance of Viewer class and load the TIFF file with full path.
        *   Set options for rendering TIFF file into PNG format.
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
        using (Viewer viewer = new Viewer("sample.tiff"))
        {
        	ViewOptions viewOptions = new PngViewOptions();
        	viewer.View(viewOptions);
        }
        ```
        
############################# Demos ############################
demos:
    enable: true
    title: "TIFF Viewer Live Demos"
    content: |
        Display TIFF file right now by visiting [GroupDocs.Viewer Live Demos](https://products.groupdocs.app/viewer/tiff) website.  
        The live demo has the following benefits
        
############################# About Formats ############################
about_formats:
    enable: true
    format:
        # format loop
        - icon: "far fa-file-tiff"
          title: "About TIFF File Format"
          content: |
            TIFF or TIF, Tagged Image File Format, represents raster images that are meant for usage on a variety of devices that comply with this file format standard. It is capable of describing bilevel, grayscale, palette-color and full-color image data in several color spaces. It supports lossy as well as lossless compression schemes to choose between space and time for applications using the format. The format is extensible and has underwent several revisions that allows the inclusion of an unlimited amount of private or special-purpose information. The format is not machine dependent and is free from bounds like processor, operating system, or file systems.

          link: "https://docs.fileformat.com/image/tiff/"

############################# More Formats ############################
more_formats:
    enable: true
    title: "Other File Formats Rendering & Viewing"
    content: |
        Multi format documents and images viewer API for .NET. View some of the popular file formats below without any external viewers.
    format: 
        # format loop
        - name: ".NET DOC Viewer"
          link: "https://products.groupdocs.com/viewer/net/doc/"
          description: "Microsoft Word Document"

        # format loop
        - name: ".NET DOCM Viewer"
          link: "https://products.groupdocs.com/viewer/net/docm/"
          description: "Microsoft Word Macro-Enabled Document"

        # format loop
        - name: ".NET DOCX Viewer"
          link: "https://products.groupdocs.com/viewer/net/docx/"
          description: "Microsoft Word Open XML Document"

        # format loop
        - name: ".NET DOT Viewer"
          link: "https://products.groupdocs.com/viewer/net/dot/"
          description: "Microsoft Word Document Template"

        # format loop
        - name: ".NET DOTM Viewer"
          link: "https://products.groupdocs.com/viewer/net/dotm/"
          description: "Microsoft Word Macro-Enabled Template"

        # format loop
        - name: ".NET DOTX Viewer"
          link: "https://products.groupdocs.com/viewer/net/dotx/"
          description: "Word Open XML Document Template"

        # format loop
        - name: ".NET RTF Viewer"
          link: "https://products.groupdocs.com/viewer/net/rtf/"
          description: "Rich Text File Format"

        # format loop
        - name: ".NET TXT Viewer"
          link: "https://products.groupdocs.com/viewer/net/txt/"
          description: "Plain Text File Format"

        # format loop
        - name: ".NET XLS Viewer"
          link: "https://products.groupdocs.com/viewer/net/xls/"
          description: "Microsoft Excel Binary File Format"

        # format loop
        - name: ".NET XLSX Viewer"
          link: "https://products.groupdocs.com/viewer/net/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet"

        # format loop
        - name: ".NET XLSM Viewer"
          link: "https://products.groupdocs.com/viewer/net/xlsm/"
          description: "Microsoft Excel Macro-Enabled Spreadsheet"

        # format loop
        - name: ".NET XLSB Viewer"
          link: "https://products.groupdocs.com/viewer/net/xlsb/"
          description: "Microsoft Excel Binary Spreadsheet File"

        # format loop
        - name: ".NET XLTX Viewer"
          link: "https://products.groupdocs.com/viewer/net/xltx/"
          description: "Microsoft Excel Open XML Template"

        # format loop
        - name: ".NET TSV Viewer"
          link: "https://products.groupdocs.com/viewer/net/tsv/"
          description: "Tab Separated Values File"

        # format loop
        - name: ".NET XLAM Viewer"
          link: "https://products.groupdocs.com/viewer/net/xlam/"
          description: "Microsoft Excel Macro-Enabled Add-In"

        # format loop
        - name: ".NET CSV Viewer"
          link: "https://products.groupdocs.com/viewer/net/csv/"
          description: "Comma Separated Values File"

        # format loop
        - name: ".NET PPT Viewer"
          link: "https://products.groupdocs.com/viewer/net/ppt/"
          description: "PowerPoint Presentation"

        # format loop
        - name: ".NET PPS Viewer"
          link: "https://products.groupdocs.com/viewer/net/pps/"
          description: "Microsoft PowerPoint Slide Show"

        # format loop
        - name: ".NET PPTX Viewer"
          link: "https://products.groupdocs.com/viewer/net/pptx/"
          description: "PowerPoint Open XML Presentation"

        # format loop
        - name: ".NET PPSX Viewer"
          link: "https://products.groupdocs.com/viewer/net/ppsx/"
          description: "PowerPoint Open XML Slide Show"

        # format loop
        - name: ".NET POTX Viewer"
          link: "https://products.groupdocs.com/viewer/net/potx/"
          description: "Microsoft PowerPoint Open XML Template"

        # format loop
        - name: ".NET POTM Viewer"
          link: "https://products.groupdocs.com/viewer/net/potm/"
          description: "Microsoft PowerPoint Template"

        # format loop
        - name: ".NET PPTM Viewer"
          link: "https://products.groupdocs.com/viewer/net/pptm/"
          description: "Microsoft PowerPoint Presentation"

        # format loop
        - name: ".NET PPSM Viewer"
          link: "https://products.groupdocs.com/viewer/net/ppsm/"
          description: "Microsoft PowerPoint Slide Show"

        # format loop
        - name: ".NET PDF Viewer"
          link: "https://products.groupdocs.com/viewer/net/pdf/"
          description: "Adobe Portable Document Format"

        # format loop
        - name: ".NET XPS Viewer"
          link: "https://products.groupdocs.com/viewer/net/xps/"
          description: "Open XML Paper Specification"

        # format loop
        - name: ".NET TEX Viewer"
          link: "https://products.groupdocs.com/viewer/net/tex/"
          description: "LaTeX Source Document"

        # format loop
        - name: ".NET ODS Viewer"
          link: "https://products.groupdocs.com/viewer/net/ods/"
          description: "Open Document Spreadsheet"

        # format loop
        - name: ".NET ODP Viewer"
          link: "https://products.groupdocs.com/viewer/net/odp/"
          description: "OpenDocument Presentation File Format"

        # format loop
        - name: ".NET OTP Viewer"
          link: "https://products.groupdocs.com/viewer/net/otp/"
          description: "Origin Graph Template"

        # format loop
        - name: ".NET ODT Viewer"
          link: "https://products.groupdocs.com/viewer/net/odt/"
          description: "Open Document Text"

        # format loop
        - name: ".NET OTT Viewer"
          link: "https://products.groupdocs.com/viewer/net/ott/"
          description: "Open Document Template"

        # format loop
        - name: ".NET VST Viewer"
          link: "https://products.groupdocs.com/viewer/net/vst/"
          description: "Microsoft Visio 2003-2010 XML Drawing"

        # format loop
        - name: ".NET TIFF Viewer"
          link: "https://products.groupdocs.com/viewer/net/tiff/"
          description: "Tagged Image File Format"

        # format loop
        - name: ".NET JPEG Viewer"
          link: "https://products.groupdocs.com/viewer/net/jpeg/"
          description: "JPEG Image"

        # format loop
        - name: ".NET PNG Viewer"
          link: "https://products.groupdocs.com/viewer/net/png/"
          description: "Portable Network Graphic"

        # format loop
        - name: ".NET GIF Viewer"
          link: "https://products.groupdocs.com/viewer/net/gif/"
          description: "Graphical Interchange Format File"

        # format loop
        - name: ".NET BMP Viewer"
          link: "https://products.groupdocs.com/viewer/net/bmp/"
          description: "Bitmap File Format"

        # format loop
        - name: ".NET ICO Viewer"
          link: "https://products.groupdocs.com/viewer/net/ico/"
          description: "Microsoft Icon File"

        # format loop
        - name: ".NET PSD Viewer"
          link: "https://products.groupdocs.com/viewer/net/psd/"
          description: "Adobe Photoshop Document"

        # format loop
        - name: ".NET WMF Viewer"
          link: "https://products.groupdocs.com/viewer/net/wmf/"
          description: "Windows Metafile"

        # format loop
        - name: ".NET EMF Viewer"
          link: "https://products.groupdocs.com/viewer/net/emf/"
          description: "Enhanced Metafile Format"

        # format loop
        - name: ".NET WEBP Viewer"
          link: "https://products.groupdocs.com/viewer/net/webp/"
          description: "Raster Web Image File Format"

        # format loop
        - name: ".NET SVG Viewer"
          link: "https://products.groupdocs.com/viewer/net/svg/"
          description: "Scalable Vector Graphics File"

        # format loop
        - name: ".NET JP2 Viewer"
          link: "https://products.groupdocs.com/viewer/net/jp2/"
          description: "JPEG 2000 Core Image File"

        # format loop
        - name: ".NET MPP Viewer"
          link: "https://products.groupdocs.com/viewer/net/emz/"
          description: "Microsoft Project Document"

        # format loop
        - name: ".NET MPT Viewer"
          link: "https://products.groupdocs.com/viewer/net/wmz/"
          description: "Microsoft Project Template"

        # format loop
        - name: ".NET HTML Viewer"
          link: "https://products.groupdocs.com/viewer/net/html/"
          description: "Hyper Text Markup Language"

        # format loop
        - name: ".NET MHT Viewer"
          link: "https://products.groupdocs.com/viewer/net/mht/"
          description: "MIME Encapsulation of Aggregate HTML"

        # format loop
        - name: ".NET MHTML Viewer"
          link: "https://products.groupdocs.com/viewer/net/mhtml/"
          description: "MIME Encapsulation of Aggregate HTML"

        # format loop
        - name: ".NET MSG Viewer"
          link: "https://products.groupdocs.com/viewer/net/msg/"
          description: "Microsoft Outlook E-mail Message"

        # format loop
        - name: ".NET EML Viewer"
          link: "https://products.groupdocs.com/viewer/net/eml/"
          description: "E-mail Message"

        # format loop
        - name: ".NET ONE Viewer"
          link: "https://products.groupdocs.com/viewer/net/one/"
          description: "Microsoft OneNote"

        # format loop
        - name: ".NET WMF Viewer"
          link: "https://products.groupdocs.com/viewer/net/wmf/"
          description: "Windows Metafile"

        # format loop
        - name: ".NET EMF Viewer"
          link: "https://products.groupdocs.com/viewer/net/emf/"
          description: "Windows Enhanced Metafile"

        # format loop
        - name: ".NET PSD Viewer"
          link: "https://products.groupdocs.com/viewer/net/psd/"
          description: "Adobe Photoshop Document"

        # format loop
        - name: ".NET VSD Viewer"
          link: "https://products.groupdocs.com/viewer/net/vsd/"
          description: "Microsoft Visio 2003-2010 Drawing"

        # format loop
        - name: ".NET VSDX Viewer"
          link: "https://products.groupdocs.com/viewer/net/vsdx/"
          description: "Microsoft Visio Drawing"

        # format loop
        - name: ".NET VSS Viewer"
          link: "https://products.groupdocs.com/viewer/net/vss/"
          description: "Microsoft Visio 2003-2010 Stencil"

        # format loop
        - name: ".NET VDX Viewer"
          link: "https://products.groupdocs.com/viewer/net/vdx/"
          description: "Microsoft Visio 2003-2010 XML Drawing"

        # format loop
        - name: ".NET VDW Viewer"
          link: "https://products.groupdocs.com/viewer/net/vdw/"
          description: "Microsoft Visio 2010 Web Drawing"

        # format loop
        - name: ".NET EPUB Viewer"
          link: "https://products.groupdocs.com/viewer/net/epub/"
          description: "Digital E-Book File Format"


############################# Back to top ###############################
back_to_top:
    enable: true
---
