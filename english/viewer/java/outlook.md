---
############################# Static ############################
layout: "auto-gen"
date: 2021-05-12T12:50:30+03:00
draft: false

############################# Head ############################
head_title: "Java Outlook Viewer API - Render & Display Outlook in Java Apps"
head_description: "View Outlook files in Java, J2EE, J2SE applications. Supports viewing 150+ document and image file formats in HTML, PDF or image mode with advanced features to manage document viewing options."

############################# Header ############################
title: "Render & View Outlook File in Java"
description: "Native and high performance Outlook file viewer API for Java, J2EE and J2SE based applications, supporting a wide range of additional features to customize the appearance of the output document format."
bg_image: "https://cms.admin.containerize.com/templates/aspose/App_Themes/V3/images/bg/header1.png"
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
            - link: "https://github.com/groupdocs-viewer"
              text: "Code Examples"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Live Demos"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/java"
              text: "Pricing"

    right:
        link_download: "https://downloads.groupdocs.com/viewer"
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
    title_left: "Steps for Viewing Outlook File in Java"
    content_left: |
        [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/) makes it easy for Java developers to add Outlook file viewing feature in their applications using a few lines of code.

        *   Create an instance of Viewer class and load the MSG file with full path.
        *   Set options for rendering MSG file into PNG format.
        *   Create view for rendered output file.
        
    title_right: "System Requirements"
    content_right: |
        GroupDocs.Viewer for Java APIs are supported on all major platforms and operating systems. Before executing the code below, please make sure that you have the following prerequisites installled on your system.

        *   Operating Systems: Microsoft Windows, Linux, MacOS
        *   Development Environment: NetBeans, Intellij IDEA, Eclipse etc
        *   Java Runtime Environment: J2SE 6.0 and above
        *   Get the latest version of GroupDocs.Viewer for Java from [Maven](https://repository.groupdocs.com/webapp/#/artifacts/browse/tree/General/repo/com/groupdocs/groupdocs-viewer)
        
    code: |
        ```java
        // Instantiate viewer
        try (Viewer viewer = new Viewer("sample.msg"))
        {
        	// Set options to view rendered file
        	PngViewOptions viewOptions = new PngViewOptions();
        	// Render file
            viewer.view(viewOptions);
        }
        ```
        
############################# Demos ############################
demos:
    enable: true
    title: "Outlook Viewer Live Demos"
    content: |
        Display Outlook file right now by visiting [GroupDocs.Viewer Live Demos](https://products.groupdocs.app/viewer/) website.  
        The live demo has the following benefits
        
############################# About Formats ############################
about_formats:
    enable: true
    format:
        # format loop
        - icon: "far fa-envelope-open-o"
          title: "About Outlook File Format"
          content: |
            Have you ever come across Email file formats and failed to open it? You have come to the right place, we are going to explain what Email file formats are and what are the recommended software that can open or use them. Email file formats are used by email applications to store their various data including email messages, attachments, folders, address books etc. Email file formats are mainly associated with Outlook Express Email Message file. Additional types of files may also be using the Email file extension. There are several common file types used with regards to email.  Below is the list of the most popular file formats used by various email clients to store e-mail messages and other related data.

          link: "https://docs.fileformat.com/email/"

############################# More Formats ############################
more_formats:
    enable: true
    title: "Other File Formats Rendering & Viewing"
    content: |
        Multi format documents and images viewer API for Java. View some of the popular file formats below without any external viewers.
    format: 
        # format loop
        - name: "Java DOC Viewer"
          link: "https://products.groupdocs.com/viewer/java/doc/"
          description: "Microsoft Word Document"

        # format loop
        - name: "Java DOCM Viewer"
          link: "https://products.groupdocs.com/viewer/java/docm/"
          description: "Microsoft Word Macro-Enabled Document"

        # format loop
        - name: "Java DOCX Viewer"
          link: "https://products.groupdocs.com/viewer/java/docx/"
          description: "Microsoft Word Open XML Document"

        # format loop
        - name: "Java DOT Viewer"
          link: "https://products.groupdocs.com/viewer/java/dot/"
          description: "Microsoft Word Document Template"

        # format loop
        - name: "Java DOTM Viewer"
          link: "https://products.groupdocs.com/viewer/java/dotm/"
          description: "Microsoft Word Macro-Enabled Template"

        # format loop
        - name: "Java DOTX Viewer"
          link: "https://products.groupdocs.com/viewer/java/dotx/"
          description: "Word Open XML Document Template"

        # format loop
        - name: "Java RTF Viewer"
          link: "https://products.groupdocs.com/viewer/java/rtf/"
          description: "Rich Text File Format"

        # format loop
        - name: "Java TXT Viewer"
          link: "https://products.groupdocs.com/viewer/java/txt/"
          description: "Plain Text File Format"

        # format loop
        - name: "Java XLS Viewer"
          link: "https://products.groupdocs.com/viewer/java/xls/"
          description: "Microsoft Excel Binary File Format"

        # format loop
        - name: "Java XLSX Viewer"
          link: "https://products.groupdocs.com/viewer/java/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet"

        # format loop
        - name: "Java XLSM Viewer"
          link: "https://products.groupdocs.com/viewer/java/xlsm/"
          description: "Microsoft Excel Macro-Enabled Spreadsheet"

        # format loop
        - name: "Java XLSB Viewer"
          link: "https://products.groupdocs.com/viewer/java/xlsb/"
          description: "Microsoft Excel Binary Spreadsheet File"

        # format loop
        - name: "Java XLTX Viewer"
          link: "https://products.groupdocs.com/viewer/java/xltx/"
          description: "Microsoft Excel Open XML Template"

        # format loop
        - name: "Java TSV Viewer"
          link: "https://products.groupdocs.com/viewer/java/tsv/"
          description: "Tab Separated Values File"

        # format loop
        - name: "Java XLAM Viewer"
          link: "https://products.groupdocs.com/viewer/java/xlam/"
          description: "Microsoft Excel Macro-Enabled Add-In"

        # format loop
        - name: "Java CSV Viewer"
          link: "https://products.groupdocs.com/viewer/java/csv/"
          description: "Comma Separated Values File"

        # format loop
        - name: "Java PPT Viewer"
          link: "https://products.groupdocs.com/viewer/java/ppt/"
          description: "PowerPoint Presentation"

        # format loop
        - name: "Java PPS Viewer"
          link: "https://products.groupdocs.com/viewer/java/pps/"
          description: "Microsoft PowerPoint Slide Show"

        # format loop
        - name: "Java PPTX Viewer"
          link: "https://products.groupdocs.com/viewer/java/pptx/"
          description: "PowerPoint Open XML Presentation"

        # format loop
        - name: "Java PPSX Viewer"
          link: "https://products.groupdocs.com/viewer/java/ppsx/"
          description: "PowerPoint Open XML Slide Show"

        # format loop
        - name: "Java POTX Viewer"
          link: "https://products.groupdocs.com/viewer/java/potx/"
          description: "Microsoft PowerPoint Open XML Template"

        # format loop
        - name: "Java POTM Viewer"
          link: "https://products.groupdocs.com/viewer/java/potm/"
          description: "Microsoft PowerPoint Template"

        # format loop
        - name: "Java PPTM Viewer"
          link: "https://products.groupdocs.com/viewer/java/pptm/"
          description: "Microsoft PowerPoint Presentation"

        # format loop
        - name: "Java PPSM Viewer"
          link: "https://products.groupdocs.com/viewer/java/ppsm/"
          description: "Microsoft PowerPoint Slide Show"

        # format loop
        - name: "Java PDF Viewer"
          link: "https://products.groupdocs.com/viewer/java/pdf/"
          description: "Adobe Portable Document Format"

        # format loop
        - name: "Java XPS Viewer"
          link: "https://products.groupdocs.com/viewer/java/xps/"
          description: "Open XML Paper Specification"

        # format loop
        - name: "Java TEX Viewer"
          link: "https://products.groupdocs.com/viewer/java/tex/"
          description: "LaTeX Source Document"

        # format loop
        - name: "Java ODS Viewer"
          link: "https://products.groupdocs.com/viewer/java/ods/"
          description: "Open Document Spreadsheet"

        # format loop
        - name: "Java ODP Viewer"
          link: "https://products.groupdocs.com/viewer/java/odp/"
          description: "OpenDocument Presentation File Format"

        # format loop
        - name: "Java OTP Viewer"
          link: "https://products.groupdocs.com/viewer/java/otp/"
          description: "Origin Graph Template"

        # format loop
        - name: "Java ODT Viewer"
          link: "https://products.groupdocs.com/viewer/java/odt/"
          description: "Open Document Text"

        # format loop
        - name: "Java OTT Viewer"
          link: "https://products.groupdocs.com/viewer/java/ott/"
          description: "Open Document Template"

        # format loop
        - name: "Java VST Viewer"
          link: "https://products.groupdocs.com/viewer/java/vst/"
          description: "Microsoft Visio 2003-2010 XML Drawing"

        # format loop
        - name: "Java TIFF Viewer"
          link: "https://products.groupdocs.com/viewer/java/tiff/"
          description: "Tagged Image File Format"

        # format loop
        - name: "Java JPEG Viewer"
          link: "https://products.groupdocs.com/viewer/java/jpeg/"
          description: "JPEG Image"

        # format loop
        - name: "Java PNG Viewer"
          link: "https://products.groupdocs.com/viewer/java/png/"
          description: "Portable Network Graphic"

        # format loop
        - name: "Java GIF Viewer"
          link: "https://products.groupdocs.com/viewer/java/gif/"
          description: "Graphical Interchange Format File"

        # format loop
        - name: "Java BMP Viewer"
          link: "https://products.groupdocs.com/viewer/java/bmp/"
          description: "Bitmap File Format"

        # format loop
        - name: "Java ICO Viewer"
          link: "https://products.groupdocs.com/viewer/java/ico/"
          description: "Microsoft Icon File"

        # format loop
        - name: "Java PSD Viewer"
          link: "https://products.groupdocs.com/viewer/java/psd/"
          description: "Adobe Photoshop Document"

        # format loop
        - name: "Java WMF Viewer"
          link: "https://products.groupdocs.com/viewer/java/wmf/"
          description: "Windows Metafile"

        # format loop
        - name: "Java EMF Viewer"
          link: "https://products.groupdocs.com/viewer/java/emf/"
          description: "Enhanced Metafile Format"

        # format loop
        - name: "Java WEBP Viewer"
          link: "https://products.groupdocs.com/viewer/java/webp/"
          description: "Raster Web Image File Format"

        # format loop
        - name: "Java SVG Viewer"
          link: "https://products.groupdocs.com/viewer/java/svg/"
          description: "Scalable Vector Graphics File"

        # format loop
        - name: "Java JP2 Viewer"
          link: "https://products.groupdocs.com/viewer/java/jp2/"
          description: "JPEG 2000 Core Image File"

        # format loop
        - name: "Java MPP Viewer"
          link: "https://products.groupdocs.com/viewer/java/emz/"
          description: "Microsoft Project Document"

        # format loop
        - name: "Java MPT Viewer"
          link: "https://products.groupdocs.com/viewer/java/wmz/"
          description: "Microsoft Project Template"

        # format loop
        - name: "Java HTML Viewer"
          link: "https://products.groupdocs.com/viewer/java/html/"
          description: "Hyper Text Markup Language"

        # format loop
        - name: "Java MHT Viewer"
          link: "https://products.groupdocs.com/viewer/java/mht/"
          description: "MIME Encapsulation of Aggregate HTML"

        # format loop
        - name: "Java MHTML Viewer"
          link: "https://products.groupdocs.com/viewer/java/mhtml/"
          description: "MIME Encapsulation of Aggregate HTML"

        # format loop
        - name: "Java MSG Viewer"
          link: "https://products.groupdocs.com/viewer/java/msg/"
          description: "Microsoft Outlook E-mail Message"

        # format loop
        - name: "Java EML Viewer"
          link: "https://products.groupdocs.com/viewer/java/eml/"
          description: "E-mail Message"

        # format loop
        - name: "Java ONE Viewer"
          link: "https://products.groupdocs.com/viewer/java/one/"
          description: "Microsoft OneNote"

        # format loop
        - name: "Java WMF Viewer"
          link: "https://products.groupdocs.com/viewer/java/wmf/"
          description: "Windows Metafile"

        # format loop
        - name: "Java EMF Viewer"
          link: "https://products.groupdocs.com/viewer/java/emf/"
          description: "Windows Enhanced Metafile"

        # format loop
        - name: "Java PSD Viewer"
          link: "https://products.groupdocs.com/viewer/java/psd/"
          description: "Adobe Photoshop Document"

        # format loop
        - name: "Java VSD Viewer"
          link: "https://products.groupdocs.com/viewer/java/vsd/"
          description: "Microsoft Visio 2003-2010 Drawing"

        # format loop
        - name: "Java VSDX Viewer"
          link: "https://products.groupdocs.com/viewer/java/vsdx/"
          description: "Microsoft Visio Drawing"

        # format loop
        - name: "Java VSS Viewer"
          link: "https://products.groupdocs.com/viewer/java/vss/"
          description: "Microsoft Visio 2003-2010 Stencil"

        # format loop
        - name: "Java VDX Viewer"
          link: "https://products.groupdocs.com/viewer/java/vdx/"
          description: "Microsoft Visio 2003-2010 XML Drawing"

        # format loop
        - name: "Java VDW Viewer"
          link: "https://products.groupdocs.com/viewer/java/vdw/"
          description: "Microsoft Visio 2010 Web Drawing"

        # format loop
        - name: "Java EPUB Viewer"
          link: "https://products.groupdocs.com/viewer/java/epub/"
          description: "Digital E-Book File Format"


############################# Back to top ###############################
back_to_top:
    enable: true
---