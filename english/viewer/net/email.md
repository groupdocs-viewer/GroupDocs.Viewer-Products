---
############################# Static ############################
layout: "auto-gen"
date: 2021-05-12T12:18:34+03:00
draft: false

############################# Head ############################
head_title: ".NET Email Viewer API - Read, View, Render in C# VB.NET"
head_description: ".NET document viewer API to read, render and display Email file in any type of C#, ASP.NET, VB.NET & .NET Core applications."

############################# Header ############################
title: "Email File Viewer for C# .NET Applications"
description: ".NET document viewer API to read, render and display Email file in any type of C#, ASP.NET, VB.NET & .NET Core applications. View the rendered files with true formatting & layout in HTML5, PDF or as an image using a few lines of the code."
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
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Code Examples"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Live Demos"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Pricing"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
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
    title_left: "Steps for Viewing Email File in C#"
    content_left: |
        [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/) makes it easy for .NET developers to add Email file viewing feature in their applications by implementing a few easy steps.

        *   Create an instance of Viewer class and load the MSG file with full path.
        *   Set options to convert MSG file into PNG format.
        *   Convert file and check output in the current directory.
        
    title_right: "System Requirements"
    content_right: |
        GroupDocs.Viewer for .NET APIs are supported on all major platforms and operating systems. Before executing the code below, please make sure that you have the following prerequisites installed on your system.

        *   Operating Systems: Microsoft Windows, Linux, MacOS
        *   Development Environments: Microsoft Visual Studio, Visual Studio Code, .NET CLI
        *   Frameworks: .NET Framework, .NET Standard, .NET Core, .NET
        *   Get the latest version of GroupDocs.Viewer for .NET from [Nuget](https://www.nuget.org/packages/groupdocs.viewer)
        
    code: |
        ```cs
        // Instantiate viewer
        using (Viewer viewer = new Viewer("sample.msg"))
        {
        	// Set view options 
        	ViewOptions viewOptions = new PngViewOptions();
        	// Convert file to PNG and check the output in the current directory 
        	viewer.View(viewOptions);
        }
        ```
        
############################# Demos ############################
demos:
    enable: true
    title: "Email Viewer Live Demos"
    content: |
        Display Email file right now by visiting [GroupDocs.Viewer Live Demos](https://products.groupdocs.app/viewer/email) website.  
        The live demo has the following benefits
        
############################# About Formats ############################
about_formats:
    enable: true
    format:
        # format loop
        - icon: "far fa-envelope-open-o"
          title: "About Email File Format"
          content: |
            Have you ever come across Email file formats and failed to open it? You have come to the right place, we are going to explain what Email file formats are and what are the recommended software that can open or use them. Email file formats are used by email applications to store their various data including email messages, attachments, folders, address books etc. Email file formats are mainly associated with Outlook Express Email Message file. Additional types of files may also be using the Email file extension. There are several common file types used with regards to email.  Below is the list of the most popular file formats used by various email clients to store e-mail messages and other related data.

          link: "https://docs.fileformat.com/email/"

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
