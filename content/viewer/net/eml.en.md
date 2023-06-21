---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: en

############################# Head #############################
head_title: ".NET EML Viewer API - Read, View, Render in C# VB.NET"
head_description: ".NET document viewer API to read, render and display EML in any type of C#, ASP.NET, VB.NET & .NET Core applications."

############################# Header ############################
title: "EML File Viewer For C# .NET Applications" 
description: ".NET document viewer API to read, render and display EML file in any type of C#, ASP.NET, VB.NET & .NET Core applications. View the rendered files with true formatting & layout in HTML5, PDF or as an image using a few lines of the code." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Download Free Trial"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "About GroupDocs.Viewer for .NET API" 
    content: |
        Start viewing 190+ popular document formats in your .NET applications using GroupDocs.Viewer for .NET APIs by adding a few lines of code. Developers can easily display PDF, Word Processing, Excel Spreadsheet, Presentation, Visio, Project, Outlook and many other popular document formats in HTML5, image or PDF modes. The document rendering is fast, identical to the original source file, and it does not require installing additional software or any other external libraries.

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
    title_left: "Steps to Render EML file in C#" 
    content_left: |
        With [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/) you can render EML to HTML, JPEG, PNG or PDF in a few steps.

        * Install [GroupDocs.Viewer for .NET](https://www.nuget.org/packages/groupdocs.viewer) using your favorite package manager. 
        * Create an instance of Viewer class and load the EML file with full path. 
        * Set options to render EML file into HTML, PNG, JPEG or PDF format. 
        * Render file and check output in the current directory. 
        
    title_right: "System Requirements" 
    content_right: |
        GroupDocs.Viewer for .NET APIs are supported on all major platforms and operating systems. Before executing the code below, please make sure that you have the following prerequisites installed on your system.

        * Operating Systems: Microsoft Windows, Linux, MacOS 
        * Development Environments: Microsoft Visual Studio, Visual Studio Code, .NET CLI 
        * Frameworks: .NET Framework, .NET Standard, .NET Core, .NET 
    code: |
        ```cs
                        
            // Set up input EML file
            string filePath = "input.eml";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render EML file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "EML Viewer Live Demo"
    content: |
        View EML file right now by visiting [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/eml) website.
    lang: "en"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Other File Formats Rendering & Viewing using C#"
    exclude: "EML"
    content: |
        Multi-format documents and images viewer API for .NET. View some of the popular file formats below without any external viewers.
    format: 
        # format loop 1
        - name: "Render DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word Open XML Document" 

        # format loop 2
        - name: "Render CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "CorelDRAW File" 

        # format loop 3
        - name: "Render PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint Open XML Presentation" 

        # format loop 4
        - name: "Render XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet" 

        # format loop 5
        - name: "Render DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "AutoCAD Drawing"

        # format loop 6
        - name: "Render XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "XML File"

        # format loop 7
        - name: "Render PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Adobe Photoshop Document"

        # format loop 8
        - name: "Render Adobe Illustrator file"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Adobe Illustrator Artwork"

        # format loop 9
        - name: "Render DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Microsoft Word Document" 

        # format loop 10
        - name: "Render TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Plain Text File" 

        # format loop 11
        - name: "Render DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Drawing Exchange Format File"  
          
        # format loop 12
        - name: "Render VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "vCard File"  
              
        # format loop 13
        - name: "Render SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Scalable Vector Graphic" 
          
        # format loop 14
        - name: "Render HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "Render PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Portable Document Format File"
          
        # format loop 16
        - name: "Render JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "JPEG Image"
          
        # format loop 17
        - name: "Render PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Portable Network Graphic" 
          
        # format loop 18
        - name: "Render EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "E-Mail Message" 
          
        # format loop 19
        - name: "Render RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Rich Text Format File" 
          
        # format loop 20
        - name: "Render ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "OpenDocument Text Document" 
          
        # format loop 21
        - name: "Render CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Comma-Separated Values File" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
