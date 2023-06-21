---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: en

############################# Head #############################
head_title: "Java VSTX Viewer API - Render & Display VSTX in Java Apps"
head_description: "View VSTX files in Java, J2EE, J2SE applications. Supports viewing 170+ document and image file formats in HTML, PDF or image mode with advanced features to manage document viewing options."

############################# Header ############################
title: "Render & View VSTX In Java" 
description: "Native and high performance VSTX file viewer API for Java, J2EE and J2SE based applications, supporting a wide range of additional features to customize the appearance of the output document format." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Download Free Trial"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "About GroupDocs.Viewer for Java API" 
    content: |
        Enable your Java applications to display over 170+ file formats in HTML, PDF or image modes using GroupDocs.Viewer for Java APIs without any additional software installed; such as Microsoft Office, Apache Open Office, Adobe Acrobat Reader etc. Developers can easily view all popular images and document types including Microsoft Office, OpenDocument, HTML, PDF, Archive, Diagrams, Photoshop, AutoCAD and programming language formats inside the Java applications with fast and highest quality rendering.

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

############################# Steps ############################
steps:
    enable: true
    title_left: "Steps to Render VSTX file in Java" 
    content_left: |
        With [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/) you can render VSTX to HTML, JPEG, PNG or PDF in a few steps.

        * Add [GroupDocs.Viewer for Java](https://releases.groupdocs.com/viewer/java/) as a dependency to your project. 
        * Create an instance of Viewer class and load the VSTX file with full path. 
        * Set options to render VSTX file into HTML, PNG, JPEG or PDF format. 
        * Render file and check output in the current directory. 
        
    title_right: "System Requirements" 
    content_right: |
        GroupDocs.Viewer for Java APIs are supported on all major platforms and operating systems. Before executing the code below, please make sure that you have the following prerequisites installed on your system.

        * Operating Systems: Microsoft Windows, Linux, MacOS 
        * Development Environments: NetBeans, IntelliJ IDEA, Eclipse etc. 
        * Frameworks: J2SE 8.0 (1.8) or above (for example Java 17) 
    code: |
        ```java
                        
            // Set up input VSTX file
            String filePath = "input.vstx";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render VSTX file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "VSTX Viewer Live Demo"
    content: |
        View VSTX file right now by visiting [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/vstx) website.
    lang: "en"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Other File Formats Rendering & Viewing using Java"
    exclude: "VSTX"
    content: |
        Multi-format documents and images viewer API for Java. View some of the popular file formats below without any external viewers.
    format: 
        # format loop 1
        - name: "Render DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Open XML Document" 

        # format loop 2
        - name: "Render CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "CorelDRAW File" 

        # format loop 3
        - name: "Render PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint Open XML Presentation" 

        # format loop 4
        - name: "Render XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet" 

        # format loop 5
        - name: "Render DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "AutoCAD Drawing"

        # format loop 6
        - name: "Render XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "XML File"

        # format loop 7
        - name: "Render PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Adobe Photoshop Document"

        # format loop 8
        - name: "Render Adobe Illustrator file"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Adobe Illustrator Artwork"

        # format loop 9
        - name: "Render DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Microsoft Word Document" 

        # format loop 10
        - name: "Render TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Plain Text File" 

        # format loop 11
        - name: "Render DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Drawing Exchange Format File"  
          
        # format loop 12
        - name: "Render VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "vCard File"  
              
        # format loop 13
        - name: "Render SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Scalable Vector Graphic" 
          
        # format loop 14
        - name: "Render HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "Render PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Portable Document Format File"
          
        # format loop 16
        - name: "Render JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "JPEG Image"
          
        # format loop 17
        - name: "Render PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Portable Network Graphic" 
          
        # format loop 18
        - name: "Render EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "E-Mail Message" 
          
        # format loop 19
        - name: "Render RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Rich Text Format File" 
          
        # format loop 20
        - name: "Render ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "OpenDocument Text Document" 
          
        # format loop 21
        - name: "Render CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Comma-Separated Values File" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
