---
############################# Static ##########################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

lang: en
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: ".NET Document Viewer API, Render PDF Word Excel Image HTML Diagram"
head_description: "C# ASP.NET file viewer & rendering API. Add PDF viewer, Word viewer, Excel viewer, Image viewer, HTML viewer, Email viewer features in .NET apps."

############################# Header ##########################
title: "Render & Display Documents via .NET API"
description: ".NET Document Viewer API to Render 190+ document formats into PDF, HTML and Image with Powerful Configuration Options."
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Download Free Trial"
    link: "https://downloads.groupdocs.com/viewer/net"

############################# SubMenu #########################
submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Viewer for .NET"
        image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-viewer-net.png"
        product: "GroupDocs.Viewer"
        platform: ".NET"

    middle:
        button:
            # button loop
            - link: "#overview"
              text: "Overview"

            # button loop
            - link: "#features"
              text: "Features"

            # button loop
            - link: "#support"
              text: "Support"

            # button loop
            - link: "https://products.groupdocs.app/viewer/total"
              text: "Live Demo"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Pricing"

    right:
        link_download: "https://www.nuget.org/packages/GroupDocs.Viewer"
        link_learn: "https://docs.groupdocs.com/viewer/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    content: |
      GroupDocs.Viewer for .NET APIs help you create powerful applications in C#, ASP.NET and other .NET-based technologies, which can render and display documents and images of 190+ file formats without installing any external software. The file viewer library rasterizes the documents and then converts them into SVG+HTML+CSS to optimize the overall document rendering experience for viewing business documents, images, text files, diagrams, graphics, email attachments and PDF files with speed, true-text and high-fidelity inside your applications. You have the option to add document viewing and reading functionalities in your applications to display whole document, partial document, specific page/cell range, individual document layer, with or without annotations and comments for the supported file formats.
       
      GroupDocs.Viewer for .NET caches the rendered documents output to the local disk by default. Any type of external cache storage is also supported by implementing appropriate interfaces – Amazon S3, Dropbox, Google Drive, Windows Azure, Redis or any other.
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          Following is an overview of GroupDocs.Viewer for .NET:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Overview"
          content: |
            * Display 190+ Document Types 
            * Get a file in HTML, Image, PDF format 
            * Rotate &amp; Reorder 
            * Apply Watermark 
            * Cache for Fast Process 
            * Add Custom Fonts 
            * Apply Encoding Standards 
            * Custom Input Data Handler 
            * Render with Track Changes 
            * Render as Responsive HTML 
            * Render PDF &amp; CAD Layers 
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Viewer for .NET supports viewing all popular document file formats. With just a few lines of code, add PDF viewer, Microsoft Office Word, Excel spreadsheet, Image, HTML, Outlook email, OneNote, Project and graphics viewing capabilities in your .NET applications.

        left:
          enable: true
          table:
            # table loop
            - title: "Microsoft Office"
              content: |
                * **Word:** DOC, DOCX, DOCM, DOT, DOTX, DOTM, RTF, TXT
                * **Excel:** XLS, XLSX, XLSM, XLSB, XLTM, XLT, XLTM, XLTX, XLAM, SXC, SpreadsheetML
                * **PowerPoint:** PPT, PPTX, PPS, PPSX, PPSM, POT, POTM, POTX, PPTM
                * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
                * **Project:** MPP, MPT, MPX
                * **Outlook:** MSG, EML, EMLX, PST, OST
                * **OneNote:** ONE

            # table loop
            - title: "Other Formats"
              content: |
                * **Page Layout Files:** PDF, TEX, XPS, OXPS
                * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG, OTG, FODP, FODG
                * **Delimiter-Separated Values:** CSV, TSV
                * **Web:** HTML, MHT, MHTML
                * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
                * **PostScript:** PS, EPS
                * **Archives:** ZIP, TAR, BZ2, GZ, RAR, RAR5
                * **Various:** OBJ, EPUB, MOBI, DjVu, XML, VCF, VCARD, NUMBERS, NSF

        right:
          enable: true
          table:
            # table loop
            - title: "Images, Graphics & Diagrams"
              content: |
                * **Images:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB
                * **Windows Icon:** ICO
                * **Scalable Vector Graphics:** SVG, CDR, CMX, IGS, SVGZ
                * **Jpeg2000:** JP2, J2C, J2K, JPC, JPF, JPX, JPM
                * **Adobe Photoshop:** PSD, PSB
                * **Printer Command Language:** PCL
                * **Stereo Lithography (3D Printing):** STL
                * **Industry Foundation Classes:** IFC
                * **Medical Imaging:** DICOM
                * **Plotter Documents:** PLT, HPG
                * **Autodesk Design Web Formats:** DWF, DWG
                * **AutoCAD Drawing:** DWT, IFC, STL, CF2
                * **ISFF-based DGN (V7):** DGN

            # table loop
            - title: "Programming Languages Formats"
              content: |
                * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
                * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES
                * **Various:** VB, PHP, SQL, PL, PY, PV, RB, RST, SASS, SCALA, SCM, SCRIPT, AS, AS3, ASM, BAT, CMAKE, CSS, DIFF, ERB, GROOVY, HAML, LESS, LOG, M, MAKE, MD, ML, MM, SH, SML, VIM, YAML

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Viewer for .NET supports following Operating Systems, Frameworks & Package Managers:
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Operating Systems"
              content: |
                * Microsoft Windows Server 2003 and later 
                * Microsoft Windows XP and later 
                * Microsoft Windows 10 & 11 
                * Linux (Ubuntu, OpenSUSE, CentOS and others) 
                * Mac OS X 

            # table loop
            - icon: "fas fa-code"
              title: "Supported Frameworks"
              content: |
                * .NET Framework 2.0 or higher 
                * .NET Core 3.1 
                * .NET 5 or higher 

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-box"
              title: "Package Manager"
              content: |
                * NuGet

            # table loop
            - icon: "fas fa-tools"
              title: "Development Environments"
              content: |
                * Microsoft Visual Studio
                * Visual Studio Code
                * .NET CLI

############################# Features ############################
features:
    enable: true
    title: "GroupDocs.Viewer for .NET Features"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "Rasterize Documents and Convert them into SVG, HTML & CSS"

      # feature loop
      - icon: "fas fa-eye"
        content: "Convert Text to HTML and Render Documents to get HTML, Image or PDF Representation"

      # feature loop
      - icon: "fas fa-bolt"
        content: "Faster Loading Time using Cached Versions of Documents"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "Convert Presentations with Shapes and Text with 3D Effects"

      # feature loop
      - icon: "fas fa-code"
        content: "Encode Word, Excel and Email Documents to Desired Encoding Standard"

      # feature loop
      - icon: "fas fa-cloud"
        content: "Render Documents located at FTP or Cloud Storage Locations"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "Excluding Fonts when Rendering to HTML to reduce Resultant File Size"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "Minify CSS & HTML Output by Removing Comments, Extra White-Spaces etc."

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "Read the Text Contained in a Source Document through its Coordinates"

      # feature loop
      - icon: "fas fa-border-all"
        content: "Show/Hide the Grid Lines of Excel Sheets in Output Representation"

      # feature loop
      - icon: "fas fa-wrench"
        content: "Specify the Number of Rows in an Excel sheet to be rendered on Each Page"

      # feature loop
      - icon: "fas fa-columns"
        content: "Ignore Empty Columns while Rendering Spreadsheet Documents"

      # feature loop
      - icon: "fas fa-file-word"
        content: "Render Word Documents into HTML Pages, Images or PDF, with Track Changes"

      # feature loop
      - icon: "fas fa-envelope"
        content: "Render Email Attachments as Original Files, Images or in HTML representation"

      # feature loop
      - icon: "fas fa-print"
        content: "Set printing restrictions on PDF documents"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "Render Content/Files contained in ZIP Archives as Attachments"

      # feature loop
      - icon: "fas fa-lock"
        content: "Obtain Attachments from Password Protected Documents"

      # feature loop
      - icon: "fas fa-file-code"
        content: "Render Programming Languages File Formats as Plain Text"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "Adjust Background Colors when Viewing CAD Drawings"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "View Excel documents and Convert to PDF, HTML, JPG & PNG"

      # feature loop
      - icon: "fas fa-heading"
        content: "Get Worksheet Names from Excel file – Display Spreadsheet Column Headings and Row numbers"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "View & Convert Microsoft Project Documents with Notes"

      # feature loop
      - icon: "fas fa-cube"
        content: "Convert CAD Drawings to SVG for better Viewing & Zooming Experience"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "Choose to Render Visio Figures without Scheme"

    more_feature:
      # more_feature_loop
      - title: "View Documents Efficiently & Reliably"
        content: |
          Using GroupDocs.Viewer API you can display more than 190 document formats efficiently and reliably with content and document structure integrity intact. Following sample code shows that how easy it is to view HTML representation of a DOCX document:

          ```cs
          // Instantiate viewer
          using (Viewer viewer = new Viewer("invoice.docx"))
          {
              // Set view options
              HtmlViewOptions options = HtmlViewOptions.ForEmbeddedResources();
              // Convert file to HTML with embedded resources
              viewer.View(options);
          }
          ```
      # more_feature_loop
      - title: "Apply Transformation to Rendered Output"
        content: "You can perform various transformations to the rendered output document using GroupDocs.Viewer for .NET API. These transformation options give you control on the way you present the rendered output for display. The available transformations are, page rotation option, page reorder option and applying text watermark."

      # more_feature_loop
      - title: "Working with Outlook Data Files"
        content: "GroupDocs.Viewer for .NET API can render the items in Outlook Data Files (OST/PST) as PDF, HTML and Image Files. Our Viewer API also has the ability to obtain the list of folders contained in Outlook Data Files. Using GroupDocs.Viewer for .NET API, you can specify the folder to render from Outlook Data Files. Likewise, you can also obtain email messages contained in OST/PST formats as attachments. GroupDocs.Viewer for .NET also enables you to filter messages from OST/PST formats based on subject, content or sender."

      # more_feature_loop
      - title: "Working with CAD Documents"
        content: "GroupDocs.Viewer for .NET API can render model and all non-empty layouts or render a specific layout of a CAD file. GroupDocs.Viewer for .NET API also supports tiled rendering or rendering by coordinates of CAD documents into image, HTML or PDF. You can also obtain layer statuses for CAD documents."

############################# Testimonials ###############################
testimonials:
  enable: true

  testimonial:
    # testimonial item loop
    - name: "Margot Baill"
      designation: "Product Development Director at Hireology"
      content: "Integrating GroupDocs.Viewer for Cloud API was simple with their fantastic Ruby SDK. There aren't that many companies out there who are willing to work with us on what we want. It's a great partnership."

    # testimonial item loop
    - name: "Mats Oustad"
      designation: "Senior Consultant/Partner at Novanet AS"
      content: "After implementing and using GroupDocs.Viewer for .NET in the project it looks to be working very well. I have tested with a lot of documents and so far so good. Everything I've thrown at it renders nicely and looks just as good as it would in a PDF viewer or MS Word."
              
    # testimonial item loop
    - name: "Martin Lasarga"
      designation: "Product Manager at Axentria ECM by G.S.I."
      content: "Excellent service and excellent products. They were extremely helpful and responsive during the GroupDocs.Viewer for .NET implementation process, can't recommend them highly enough."

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Viewer offers document viewing APIs for other popular development environments"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Viewer for Java"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-viewer-java.png"
          product: "GroupDocs.Viewer"
          platform: "Java"
          link: "/viewer/java/"

############################# Back to top ###############################
back_to_top:
  enable: true
---
