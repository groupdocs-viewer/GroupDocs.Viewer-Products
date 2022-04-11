---
############################# Static ############################
layout: "auto-gen"
date: 2022-02-23T12:00:00+02:00
draft: false

############################# Head ############################
head_title: ".NET DXF Viewer API - Read, View, Render in C# VB.NET"
head_description: ".NET document viewer API to read, render and display DXF in any type of C#, ASP.NET, VB.NET & .NET Core applications."

############################# Header ############################
title: "DXF File Viewer for C# .NET Applications"
description: ".NET document viewer API to read, render and display DXF file in any type of C#, ASP.NET, VB.NET & .NET Core applications. View the rendered files with true formatting & layout in HTML5, PDF or as an image using a few lines of the code."

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
    title_left: "Steps for View DXF File in C#"
    content_left: |
        [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/) makes it easy for .NET developers to add DXF file viewing feature in their applications by implementing a few easy steps.

        *   Create an instance of Viewer class and load the DXF file with full path.
        *   Set options to convert DXF file into PNG format.
        *   Convert file and check output in the current directory.
        
    title_right: "System Requirements"
    content_right: |
        GroupDocs.Viewer for .NET APIs are supported on all major platforms and operating systems. Before executing the code below, please make sure that you have the following prerequisites installed on your system.

        *   Operating Systems: Microsoft Windows, Linux, MacOS
        *   Development Environments: Microsoft Visual Studio, Visual Studio Code, .NET CLI
        *   Frameworks: .NET Framework, .NET Standard, .NET Core, .NET
        *   Get the latest version of GroupDocs.Viewer for .NET from [NuGet](https://www.nuget.org/packages/groupdocs.viewer)
        
    code: |
        ```cs
        // Instantiate viewer
        using (Viewer viewer = new Viewer("sample.dxf"))
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
    title: "DXF Viewer Live Demos"
    content: |
        Display DXF file right now by visiting [GroupDocs.Viewer Live Demos](https://products.groupdocs.app/viewer/dxf) website.  
        The live demo has the following benefits
        
############################# About Formats ############################
about_formats:
    enable: true
    format:
        # format loop
        - icon: "far fa-file-dxf"
          title: "About DXF File Format"
          content: |
            DXF, Drawing Interchange Format, or Drawing Exchange Format, is a tagged data representation of AutoCAD drawing file. Each element in the file has a prefix integer number called a group code. This group code actually represents the element that follows and indicates the meaning of a data element for a given object type. DXF makes it possible to represent almost all user-specified information in a drawing file. DXF file format was developed by Autodesk as CAD data file format for data interoperability between AutoCAD and other applications. Thus, data can be imported from other formats to DXF to AutoCAD as per the DXF file format interoperability specifications.

          link: "https://docs.fileformat.com/cad/dxf/"

############################# More Formats ############################
more_formats:
    enable: true
    title: "Other File Formats Rendering & Viewing"
    content: |
        Multi format documents and images viewer API for .NET. View some of the popular file formats below without any external viewers.
    format: 
        # format loop
        - name: ".NET DOC Viewer"
          link: "/viewer/net/doc/"
          description: "Microsoft Word Document"

        # format loop
        - name: ".NET DOCM Viewer"
          link: "/viewer/net/docm/"
          description: "Microsoft Word Macro-Enabled Document"

        # format loop
        - name: ".NET DOCX Viewer"
          link: "/viewer/net/docx/"
          description: "Microsoft Word Open XML Document"

        # format loop
        - name: ".NET DOT Viewer"
          link: "/viewer/net/dot/"
          description: "Microsoft Word Document Template"

        # format loop
        - name: ".NET DOTM Viewer"
          link: "/viewer/net/dotm/"
          description: "Microsoft Word Macro-Enabled Template"

        # format loop
        - name: ".NET DOTX Viewer"
          link: "/viewer/net/dotx/"
          description: "Word Open XML Document Template"

        # format loop
        - name: ".NET RTF Viewer"
          link: "/viewer/net/rtf/"
          description: "Rich Text File Format"

        # format loop
        - name: ".NET TXT Viewer"
          link: "/viewer/net/txt/"
          description: "Plain Text File Format"

        # format loop
        - name: ".NET XLS Viewer"
          link: "/viewer/net/xls/"
          description: "Microsoft Excel Binary File Format"

        # format loop
        - name: ".NET XLSX Viewer"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet"

        # format loop
        - name: ".NET XLSM Viewer"
          link: "/viewer/net/xlsm/"
          description: "Microsoft Excel Macro-Enabled Spreadsheet"

        # format loop
        - name: ".NET XLSB Viewer"
          link: "/viewer/net/xlsb/"
          description: "Microsoft Excel Binary Spreadsheet File"

        # format loop
        - name: ".NET XLTX Viewer"
          link: "/viewer/net/xltx/"
          description: "Microsoft Excel Open XML Template"

        # format loop
        - name: ".NET TSV Viewer"
          link: "/viewer/net/tsv/"
          description: "Tab Separated Values File"

        # format loop
        - name: ".NET XLAM Viewer"
          link: "/viewer/net/xlam/"
          description: "Microsoft Excel Macro-Enabled Add-In"

        # format loop
        - name: ".NET CSV Viewer"
          link: "/viewer/net/csv/"
          description: "Comma Separated Values File"

        # format loop
        - name: ".NET PPT Viewer"
          link: "/viewer/net/ppt/"
          description: "PowerPoint Presentation"

        # format loop
        - name: ".NET PPS Viewer"
          link: "/viewer/net/pps/"
          description: "Microsoft PowerPoint Slide Show"

        # format loop
        - name: ".NET PPTX Viewer"
          link: "/viewer/net/pptx/"
          description: "PowerPoint Open XML Presentation"

        # format loop
        - name: ".NET PPSX Viewer"
          link: "/viewer/net/ppsx/"
          description: "PowerPoint Open XML Slide Show"

        # format loop
        - name: ".NET POTX Viewer"
          link: "/viewer/net/potx/"
          description: "Microsoft PowerPoint Open XML Template"

        # format loop
        - name: ".NET POTM Viewer"
          link: "/viewer/net/potm/"
          description: "Microsoft PowerPoint Template"

        # format loop
        - name: ".NET PPTM Viewer"
          link: "/viewer/net/pptm/"
          description: "Microsoft PowerPoint Presentation"

        # format loop
        - name: ".NET PPSM Viewer"
          link: "/viewer/net/ppsm/"
          description: "Microsoft PowerPoint Slide Show"

        # format loop
        - name: ".NET PDF Viewer"
          link: "/viewer/net/pdf/"
          description: "Adobe Portable Document Format"

        # format loop
        - name: ".NET XPS Viewer"
          link: "/viewer/net/xps/"
          description: "Open XML Paper Specification"

        # format loop
        - name: ".NET TEX Viewer"
          link: "/viewer/net/tex/"
          description: "LaTeX Source Document"

        # format loop
        - name: ".NET ODS Viewer"
          link: "/viewer/net/ods/"
          description: "Open Document Spreadsheet"

        # format loop
        - name: ".NET ODP Viewer"
          link: "/viewer/net/odp/"
          description: "OpenDocument Presentation File Format"

        # format loop
        - name: ".NET OTP Viewer"
          link: "/viewer/net/otp/"
          description: "Origin Graph Template"

        # format loop
        - name: ".NET ODT Viewer"
          link: "/viewer/net/odt/"
          description: "Open Document Text"

        # format loop
        - name: ".NET OTT Viewer"
          link: "/viewer/net/ott/"
          description: "Open Document Template"

        # format loop
        - name: ".NET VST Viewer"
          link: "/viewer/net/vst/"
          description: "Microsoft Visio 2003-2010 XML Drawing"

        # format loop
        - name: ".NET TIFF Viewer"
          link: "/viewer/net/tiff/"
          description: "Tagged Image File Format"

        # format loop
        - name: ".NET JPEG Viewer"
          link: "/viewer/net/jpeg/"
          description: "JPEG Image"

        # format loop
        - name: ".NET PNG Viewer"
          link: "/viewer/net/png/"
          description: "Portable Network Graphic"

        # format loop
        - name: ".NET GIF Viewer"
          link: "/viewer/net/gif/"
          description: "Graphical Interchange Format File"

        # format loop
        - name: ".NET BMP Viewer"
          link: "/viewer/net/bmp/"
          description: "Bitmap File Format"

        # format loop
        - name: ".NET ICO Viewer"
          link: "/viewer/net/ico/"
          description: "Microsoft Icon File"

        # format loop
        - name: ".NET PSD Viewer"
          link: "/viewer/net/psd/"
          description: "Adobe Photoshop Document"


        # format loop
        - name: ".NET WEBP Viewer"
          link: "/viewer/net/webp/"
          description: "Raster Web Image File Format"

        # format loop
        - name: ".NET SVG Viewer"
          link: "/viewer/net/svg/"
          description: "Scalable Vector Graphics File"

        # format loop
        - name: ".NET JP2 Viewer"
          link: "/viewer/net/jp2/"
          description: "JPEG 2000 Core Image File"

        # format loop
        - name: ".NET MPP Viewer"
          link: "/viewer/net/emz/"
          description: "Microsoft Project Document"

        # format loop
        - name: ".NET MPT Viewer"
          link: "/viewer/net/wmz/"
          description: "Microsoft Project Template"

        # format loop
        - name: ".NET HTML Viewer"
          link: "/viewer/net/html/"
          description: "Hyper Text Markup Language"

        # format loop
        - name: ".NET MHT Viewer"
          link: "/viewer/net/mht/"
          description: "MIME Encapsulation of Aggregate HTML"

        # format loop
        - name: ".NET MHTML Viewer"
          link: "/viewer/net/mhtml/"
          description: "MIME Encapsulation of Aggregate HTML"

        # format loop
        - name: ".NET MSG Viewer"
          link: "/viewer/net/msg/"
          description: "Microsoft Outlook E-mail Message"

        # format loop
        - name: ".NET EML Viewer"
          link: "/viewer/net/eml/"
          description: "E-mail Message"

        # format loop
        - name: ".NET ONE Viewer"
          link: "/viewer/net/one/"
          description: "Microsoft OneNote"

        # format loop
        - name: ".NET WMF Viewer"
          link: "/viewer/net/wmf/"
          description: "Windows Metafile"

        # format loop
        - name: ".NET EMF Viewer"
          link: "/viewer/net/emf/"
          description: "Windows Enhanced Metafile"

        # format loop
        - name: ".NET PSD Viewer"
          link: "/viewer/net/psd/"
          description: "Adobe Photoshop Document"

        # format loop
        - name: ".NET VSD Viewer"
          link: "/viewer/net/vsd/"
          description: "Microsoft Visio 2003-2010 Drawing"

        # format loop
        - name: ".NET VSDX Viewer"
          link: "/viewer/net/vsdx/"
          description: "Microsoft Visio Drawing"

        # format loop
        - name: ".NET VSS Viewer"
          link: "/viewer/net/vss/"
          description: "Microsoft Visio 2003-2010 Stencil"

        # format loop
        - name: ".NET VDX Viewer"
          link: "/viewer/net/vdx/"
          description: "Microsoft Visio 2003-2010 XML Drawing"

        # format loop
        - name: ".NET VDW Viewer"
          link: "/viewer/net/vdw/"
          description: "Microsoft Visio 2010 Web Drawing"

        # format loop
        - name: ".NET EPUB Viewer"
          link: "/viewer/net/epub/"
          description: "Digital E-Book File Format"


############################# Back to top ###############################
back_to_top:
    enable: true
---
