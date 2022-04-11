---
############################# Static ############################
layout: "auto-gen"
date: 2022-02-23T12:00:00+02:00
draft: false

############################# Head ############################
head_title: "Java STL Viewer API - Render & Display STL in Java Apps"
head_description: "View STL files in Java, J2EE, J2SE applications. Supports viewing 150+ document and image file formats in HTML, PDF or image mode with advanced features to manage document viewing options."

############################# Header ############################
title: "Render & View STL File in Java"
description: "Native and high performance STL file viewer API for Java, J2EE and J2SE based applications, supporting a wide range of additional features to customize the appearance of the output document format."

bg_overlay: false
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
        image: "https://cms.admin.containerize.com/templates/groupdocs/images/product-logos/90x90-noborder/groupdocs-viewer-java.png"
        product: "GroupDocs.Viewer"
        platform: "Java"

    middle:
        button:

            # button loop
            - link: "https://apireference.groupdocs.com/viewer/java"
              text: "API Reference"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Java"
              text: "Code Examples"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Live Demos"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/java"
              text: "Pricing"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/java"
        link_learn: "https://docs.groupdocs.com/viewer/java"
        link_buy: "https://purchase.groupdocs.com"

############################# About ############################
about:
    enable: true
    title: "About GroupDocs.Viewer for Java API"
    content: |
        Enable your Java applications to display over 150+ file formats in HTML, PDF or image modes using GroupDocs.Viewer for Java APIs without any additional software installed; such as Microsoft Office, Apache Open Office, Adobe Acrobat Reader etc. Developers can easily view all popular images and document types including Microsoft Office, OpenDocument, HTML, PDF, Archive, Diagrams, Photoshop, AutoCAD and programming language formats inside the Java applications with fast and highest quality rendering.

############################# Steps ############################
steps:
    enable: true
    title_left: "Steps for View STL File in Java"
    content_left: |
        [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/) makes it easy for Java developers to add STL file viewing feature in their applications using a few lines of code.

        *   Create an instance of Viewer class and load the STL file with full path.
        *   Set view options to convert STL file into PNG format.
        *   Convert file and check the output in the current directory.
        
    title_right: "System Requirements"
    content_right: |
        GroupDocs.Viewer for Java APIs are supported on all major platforms and operating systems. Before executing the code below, please make sure that you have the following prerequisites installed on your system.

        *   Operating Systems: Microsoft Windows, Linux, MacOS
        *   Development Environment: NetBeans, IntelliJ IDEA, Eclipse etc.
        *   Java Runtime Environment: Java 7 (1.7) and above
        *   Get the latest version of GroupDocs.Viewer for Java from [GroupDocs Artifact Repository](https://repository.groupdocs.com/webapp/#/artifacts/browse/tree/General/repo/com/groupdocs/groupdocs-viewer)
        
    code: |
        ```java
        // Instantiate viewer
        try (Viewer viewer = new Viewer("sample.stl"))
        {
        	// Set view options
        	PngViewOptions viewOptions = new PngViewOptions();
        	// Convert file to PNG and check the output in the current directory
        	viewer.view(viewOptions);
        }
        ```
        
############################# Demos ############################
demos:
    enable: true
    title: "STL Viewer Live Demos"
    content: |
        Display STL file right now by visiting [GroupDocs.Viewer Live Demos](https://products.groupdocs.app/viewer/) website.  
        The live demo has the following benefits
        
############################# About Formats ############################
about_formats:
    enable: true
    format:
        # format loop
        - icon: "far fa-file-stl"
          title: "About STL File Format"
          content: |
            STL, abbreviation for stereolithrography, is an interchangeable file format that represents 3-dimensional surface geometry. The file format finds its usage in several fields such as rapid prototyping, 3D printing and computer-aided manufacturing. It represents a surface as a series of small triangles, known as facets, where each facet is described by a perpendicular direction and three points representing the vertices of the triangle. Resultant data is used by applications to determine the cross section of the 3D shape to be built by the fabber. There is no information available in the STL file format for representation of colour, texture or other common CAD model attributes.

          link: "https://docs.fileformat.com/cad/stl/"

############################# More Formats ############################
more_formats:
    enable: true
    title: "Other File Formats Rendering & Viewing"
    content: |
        Multi format documents and images viewer API for Java. View some of the popular file formats below without any external viewers.
    format: 
        # format loop
        - name: "Java DOC Viewer"
          link: "/viewer/java/doc/"
          description: "Microsoft Word Document"

        # format loop
        - name: "Java DOCM Viewer"
          link: "/viewer/java/docm/"
          description: "Microsoft Word Macro-Enabled Document"

        # format loop
        - name: "Java DOCX Viewer"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Open XML Document"

        # format loop
        - name: "Java DOT Viewer"
          link: "/viewer/java/dot/"
          description: "Microsoft Word Document Template"

        # format loop
        - name: "Java DOTM Viewer"
          link: "/viewer/java/dotm/"
          description: "Microsoft Word Macro-Enabled Template"

        # format loop
        - name: "Java DOTX Viewer"
          link: "/viewer/java/dotx/"
          description: "Word Open XML Document Template"

        # format loop
        - name: "Java RTF Viewer"
          link: "/viewer/java/rtf/"
          description: "Rich Text File Format"

        # format loop
        - name: "Java TXT Viewer"
          link: "/viewer/java/txt/"
          description: "Plain Text File Format"

        # format loop
        - name: "Java XLS Viewer"
          link: "/viewer/java/xls/"
          description: "Microsoft Excel Binary File Format"

        # format loop
        - name: "Java XLSX Viewer"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet"

        # format loop
        - name: "Java XLSM Viewer"
          link: "/viewer/java/xlsm/"
          description: "Microsoft Excel Macro-Enabled Spreadsheet"

        # format loop
        - name: "Java XLSB Viewer"
          link: "/viewer/java/xlsb/"
          description: "Microsoft Excel Binary Spreadsheet File"

        # format loop
        - name: "Java XLTX Viewer"
          link: "/viewer/java/xltx/"
          description: "Microsoft Excel Open XML Template"

        # format loop
        - name: "Java TSV Viewer"
          link: "/viewer/java/tsv/"
          description: "Tab Separated Values File"

        # format loop
        - name: "Java XLAM Viewer"
          link: "/viewer/java/xlam/"
          description: "Microsoft Excel Macro-Enabled Add-In"

        # format loop
        - name: "Java CSV Viewer"
          link: "/viewer/java/csv/"
          description: "Comma Separated Values File"

        # format loop
        - name: "Java PPT Viewer"
          link: "/viewer/java/ppt/"
          description: "PowerPoint Presentation"

        # format loop
        - name: "Java PPS Viewer"
          link: "/viewer/java/pps/"
          description: "Microsoft PowerPoint Slide Show"

        # format loop
        - name: "Java PPTX Viewer"
          link: "/viewer/java/pptx/"
          description: "PowerPoint Open XML Presentation"

        # format loop
        - name: "Java PPSX Viewer"
          link: "/viewer/java/ppsx/"
          description: "PowerPoint Open XML Slide Show"

        # format loop
        - name: "Java POTX Viewer"
          link: "/viewer/java/potx/"
          description: "Microsoft PowerPoint Open XML Template"

        # format loop
        - name: "Java POTM Viewer"
          link: "/viewer/java/potm/"
          description: "Microsoft PowerPoint Template"

        # format loop
        - name: "Java PPTM Viewer"
          link: "/viewer/java/pptm/"
          description: "Microsoft PowerPoint Presentation"

        # format loop
        - name: "Java PPSM Viewer"
          link: "/viewer/java/ppsm/"
          description: "Microsoft PowerPoint Slide Show"

        # format loop
        - name: "Java PDF Viewer"
          link: "/viewer/java/pdf/"
          description: "Adobe Portable Document Format"

        # format loop
        - name: "Java XPS Viewer"
          link: "/viewer/java/xps/"
          description: "Open XML Paper Specification"

        # format loop
        - name: "Java TEX Viewer"
          link: "/viewer/java/tex/"
          description: "LaTeX Source Document"

        # format loop
        - name: "Java ODS Viewer"
          link: "/viewer/java/ods/"
          description: "Open Document Spreadsheet"

        # format loop
        - name: "Java ODP Viewer"
          link: "/viewer/java/odp/"
          description: "OpenDocument Presentation File Format"

        # format loop
        - name: "Java OTP Viewer"
          link: "/viewer/java/otp/"
          description: "Origin Graph Template"

        # format loop
        - name: "Java ODT Viewer"
          link: "/viewer/java/odt/"
          description: "Open Document Text"

        # format loop
        - name: "Java OTT Viewer"
          link: "/viewer/java/ott/"
          description: "Open Document Template"

        # format loop
        - name: "Java VST Viewer"
          link: "/viewer/java/vst/"
          description: "Microsoft Visio 2003-2010 XML Drawing"

        # format loop
        - name: "Java TIFF Viewer"
          link: "/viewer/java/tiff/"
          description: "Tagged Image File Format"

        # format loop
        - name: "Java JPEG Viewer"
          link: "/viewer/java/jpeg/"
          description: "JPEG Image"

        # format loop
        - name: "Java PNG Viewer"
          link: "/viewer/java/png/"
          description: "Portable Network Graphic"

        # format loop
        - name: "Java GIF Viewer"
          link: "/viewer/java/gif/"
          description: "Graphical Interchange Format File"

        # format loop
        - name: "Java BMP Viewer"
          link: "/viewer/java/bmp/"
          description: "Bitmap File Format"

        # format loop
        - name: "Java ICO Viewer"
          link: "/viewer/java/ico/"
          description: "Microsoft Icon File"

        # format loop
        - name: "Java PSD Viewer"
          link: "/viewer/java/psd/"
          description: "Adobe Photoshop Document"



        # format loop
        - name: "Java WEBP Viewer"
          link: "/viewer/java/webp/"
          description: "Raster Web Image File Format"

        # format loop
        - name: "Java SVG Viewer"
          link: "/viewer/java/svg/"
          description: "Scalable Vector Graphics File"

        # format loop
        - name: "Java JP2 Viewer"
          link: "/viewer/java/jp2/"
          description: "JPEG 2000 Core Image File"

        # format loop
        - name: "Java MPP Viewer"
          link: "/viewer/java/emz/"
          description: "Microsoft Project Document"

        # format loop
        - name: "Java MPT Viewer"
          link: "/viewer/java/wmz/"
          description: "Microsoft Project Template"

        # format loop
        - name: "Java HTML Viewer"
          link: "/viewer/java/html/"
          description: "Hyper Text Markup Language"

        # format loop
        - name: "Java MHT Viewer"
          link: "/viewer/java/mht/"
          description: "MIME Encapsulation of Aggregate HTML"

        # format loop
        - name: "Java MHTML Viewer"
          link: "/viewer/java/mhtml/"
          description: "MIME Encapsulation of Aggregate HTML"

        # format loop
        - name: "Java MSG Viewer"
          link: "/viewer/java/msg/"
          description: "Microsoft Outlook E-mail Message"

        # format loop
        - name: "Java EML Viewer"
          link: "/viewer/java/eml/"
          description: "E-mail Message"

        # format loop
        - name: "Java ONE Viewer"
          link: "/viewer/java/one/"
          description: "Microsoft OneNote"


        # format loop
        - name: "Java WMF Viewer"
          link: "/viewer/java/wmf/"
          description: "Windows Metafile"

        # format loop
        - name: "Java EMF Viewer"
          link: "/viewer/java/emf/"
          description: "Enhanced Metafile Format"

        # format loop
        - name: "Java PSD Viewer"
          link: "/viewer/java/psd/"
          description: "Adobe Photoshop Document"

        # format loop
        - name: "Java VSD Viewer"
          link: "/viewer/java/vsd/"
          description: "Microsoft Visio 2003-2010 Drawing"

        # format loop
        - name: "Java VSDX Viewer"
          link: "/viewer/java/vsdx/"
          description: "Microsoft Visio Drawing"

        # format loop
        - name: "Java VSS Viewer"
          link: "/viewer/java/vss/"
          description: "Microsoft Visio 2003-2010 Stencil"

        # format loop
        - name: "Java VDX Viewer"
          link: "/viewer/java/vdx/"
          description: "Microsoft Visio 2003-2010 XML Drawing"

        # format loop
        - name: "Java VDW Viewer"
          link: "/viewer/java/vdw/"
          description: "Microsoft Visio 2010 Web Drawing"

        # format loop
        - name: "Java EPUB Viewer"
          link: "/viewer/java/epub/"
          description: "Digital E-Book File Format"


############################# Back to top ###############################
back_to_top:
    enable: true
---
