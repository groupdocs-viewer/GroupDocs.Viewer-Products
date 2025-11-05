---
############################# Static ##########################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: en
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

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
head_title: ".NET document viewer API, render PDF Word Excel Image HTML Diagram"
head_description: "C# ASP.NET file viewer & rendering API. Add PDF viewer, Word viewer, Excel viewer, Image viewer, HTML viewer, Email viewer features in .NET apps."

############################# Header ##########################
title: "Render & display documents<br>using .NET API"
description: "Powerful Viewer API to render 180+ document formats into PDF, HTML, and Image with versatile configuration options."
words:
  for: "for"

actions:
  viewer_demo: true
  viewer_demo_file_name: "quarterly-report.docx"
  main: "Free NuGet Download"
  main_link: "https://www.nuget.org/packages/GroupDocs.Viewer"
  alt: "Licensing"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/net"
  title: "Ready to get started?"
  description: "Try GroupDocs.Viewer features for free or request a license"

release:
  title: "Version {0}&nbsp;released"
  notes: "See what’s new"
  downloads: "Downloads"
  link: "https://releases.groupdocs.com/viewer/net/release-notes/latest/"

code:
  title: "Render PDF files in C#"
  more: "More examples"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
  install: "dotnet add package GroupDocs.Viewer"
  content: |
    ```csharp {style=abap}   
    // Load the source PDF file
    using (var viewer = new Viewer("resume.pdf"))
    {
        // Set output HTML options, one file per page
        var viewOptions = 
        HtmlViewOptions.ForEmbeddedResources("page{0}.html");
        
        // Render PDF to HTML with embedded resources        
        viewer.View(viewOptions);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Viewer at a glance"
  description: "API to render, display, convert documents, slides, diagrams, and many other document types in .NET applications"
  features:
    # feature loop
    - title: "View documents efficiently & reliably"
      content: "With GroupDocs.Viewer API you can efficiently render documents of any supportable formats to HTML, JPEG, PNG, and [PDF](https://blog.groupdocs.com/viewer/view-word-documents-as-pdf-using-csharp/) with flexible and powerful options while maintaining content and document structure integrity. GroupDocs.Viewer supports .NET Framework 4.6.2 and .NET 6.0, it works on Windows and Linux platforms."

    # feature loop
    - title: "Most popular file and document formats are supported"
      content: "We support rendering over the 180 most popular file and document formats that include Word, [Excel](https://blog.groupdocs.com/viewer/working-with-spreadsheets/), PDF, [PowerPoint](https://blog.groupdocs.com/viewer/view-powerpoint-presentations/), OpenDocument formats family, Archives, Raster and Vector images, e-Books, programming languages and markups, and many other file types, including encrypted files with password protection."

    # feature loop
    - title: "Customizable output"
      content: "GroupDocs.Viewer allows not only to render the document, but also to control how exactly, which parts of the document should be rendered or now, how they should be rendered, and to apply different transformations to the rendered output."

    # feature loop
    - title: "UI for ASP.NET Core"
      content: "We provide an open source UI package for ASP.NET Core that can be added to your project in a couple of minutes. The Viewer.UI package contains an Angular-based web-UI and delivers a set of useful APIs and data storage providers."

############################# Platforms ############################
platforms:
  enable: true
  title: "Platforms support"
  description: "GroupDocs.Viewer for .NET supports the following operating systems, frameworks and package managers"
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
    - title: "VS Code"
      image: "vs_code"
    # platform loop
    - title: "ReSharper"
      image: "resharper"
    # platform loop
    - title: "macOS"
      image: "finder"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "NuGet"
      image: "nuget"
  packages:
    # packages loop
    - title: "Windows-specific package"
      content: |
        * Supports .NET Framework 4.6.2+ and .NET 6.0
        * The most comprehensive file formats support
        * Depends on System.Drawing and System.Drawing.Common 
      action: "NuGet download"
      action_link: "https://www.nuget.org/packages/GroupDocs.Viewer"
    # packages loop
    - title: "Cross-platform package" 
      content: |
        * Supports .NET 6.0 and higher versions 
        * Limited file formats support 
        * Works on Windows, Linux and macOS 
      action: "NuGet download" 
      action_link: "https://www.nuget.org/packages/GroupDocs.Viewer.CrossPlatform" 

############################# File formats ############################
formats:
  enable: true
  title: "Supported file formats"
  description: |
    GroupDocs.Viewer for .NET supports operations with the following [file formats](https://docs.groupdocs.com/viewer/net/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office, OpenDocument and text formats
        * **Word:** DOC, DOCX, DOCM, DOT, DOTX, DOTM, RTF, TXT
        * **Excel:** XLS, XLSX, XLSM, XLSB, XLTM, XLT, XLTM, XLTX
        * **PowerPoint:** PPT, PPTX, PPS, PPSX, PPSM, POT, POTM, POTX, PPTM        
        * **Project:** MPP, MPT, MPX {{< landing/tooltip icon="windows" title="Supported by Windows-specific package" >}}
        * **Outlook:** MSG, EML, EMLX, PST, OST
        * **OneNote:** ONE {{< landing/tooltip icon="windows" title="Supported by Windows-specific package" >}}
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
        * **Adobe Photoshop:** PSD, PSB {{< landing/tooltip icon="windows" title="Supported by Windows-specific package" >}}       
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
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM {{< landing/tooltip icon="windows" title="Supported by Windows-specific package" >}}
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
      title: "[View documents in HTML](https://blog.groupdocs.com/viewer/view-word-documents-as-html-responsive-page-using-csharp/)"
      content: "Convert document of any type into a HTML document with CSS and SVG, which can be displayed in any modern web-browser."

    # feature loop
    - icon: "rasterize"
      title: "Rasterize documents"
      content: "Rasterize any supportable document format to the raster image, with adjustable image format and compression quality."

    # feature loop
    - icon: "font"
      title: "[Control document fonts](https://blog.groupdocs.com/viewer/working-with-fonts/)"
      content: "Identify which fonts are used in a document. Manage missing fonts by replacing them or excluding them from the output."

    # feature loop
    - icon: "convertpdf"
      title: "[Convert to PDF](https://blog.groupdocs.com/viewer/rendering-documents-as-pdf/)"
      content: "Document of any supportable format can be easily converted and saved to the PDF with adjustable options."

    # feature loop
    - icon: "transform"
      title: "[Apply transformations](https://blog.groupdocs.com/viewer/protect-your-documents-with-watermarks-in-groupdocs-viewer-for-dot-net/)"
      content: "Output document can be transformed during rendering - pages can be rotated and/or rearranged, and text watermark may be placed atop of them."

    # feature loop
    - icon: "adjustment"
      title: "[HTML output adjustment](https://blog.groupdocs.com/viewer/render-word-documents-as-clean-html-using-csharp/)"
      content: "Output HTML documents, generated by the GroupDocs.Viewer, can be tuned very finely: it is allowed to save to the stream or file, with external or embedded resources, callbacks and so on."

    # feature loop
    - icon: "complex"
      title: "[Support of complex document structures](https://blog.groupdocs.com/viewer/process-microsoft-outlook-email-attachments-in-a-.net-viewer-application/)"
      content: "GroupDocs.Viewer supports not only the single documents, but also files, which internally contain a list or hierarchical structure of documents, like email messages with attachments, ZIP archives with internal files within folders, multi-page TIFF images, and so on."

    # feature loop
    - icon: "optimization"
      title: "[Optimization options](https://blog.groupdocs.com/viewer/exclude-specific-fonts-from-output-html-using-groupdocs.viewer-for-.net-18.10/)"
      content: "GroupDocs.Viewer contains an adjustable cache subsystem, which can fasten the loading time by using the cached versions of the documents. Also a set of different options for different formats allows to exclude some unnecessary parts or aspects of documents from the rendering (fonts, hidded worksheets, email attachments) to optimize the overall performance"

    # feature loop
    - icon: "passwordprotected"
      title: "[Support of password-protected documents](https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET/blob/master/Examples/GroupDocs.Viewer.Examples.CSharp/AdvancedUsage/Loading/LoadPasswordProtectedDocument.cs)"
      content: "GroupDocs.Viewer allows to open the encrypted documents of different types: PDF, WordProcessing, Spreadsheet, Presentation, and other, by specifying a password in the loading options."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Code samples"
  description: "Some use cases of typical GroupDocs.Viewer for .NET operations"
  items:
    # code sample loop
    - title: "Render DOCX to HTML"
      content: |
        The [HtmlViewOptions](https://reference.groupdocs.com/viewer/net/groupdocs.viewer.options/htmlviewoptions/) class properties allow you to control the conversion process, more on that [here](https://docs.groupdocs.com/viewer/net/rendering-to-html/). For instance, you can embed all external resources in the output HTML file, minify the output file, and optimize it for printing.
        {{< landing/code title="C#">}}
        ```csharp {style=abap}
        using GroupDocs.Viewer;
        using GroupDocs.Viewer.Options;
        
        // Instantiate viewer
        using (Viewer viewer = new Viewer("resume.docx"))
        {
            // Set output HTML options
            HtmlViewOptions options = HtmlViewOptions.ForEmbeddedResources();
            
            // Render DOCX to HTML with embedded resources
            viewer.View(options);
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Export PPTX to PDF"
      content: |
        Create a [PdfViewOptions](https://reference.groupdocs.com/viewer/net/groupdocs.viewer.options/pdfviewoptions/) class instance and pass it to the [Viewer.View](https://reference.groupdocs.com/viewer/net/groupdocs.viewer/viewer/view/#view) method to convert a PowerPoint PPTX file to PDF. The PdfViewOptions class properties allow you to control the conversion process. For instance, you can protect the output PDF file, reorder its pages, and specify the quality of document images. Refer to the [following documentation section](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/) for details.
        {{< landing/code title="C#">}}
        ```csharp {style=abap}   
        using GroupDocs.Viewer;
        using GroupDocs.Viewer.Options;
        
        using (var viewer = new Viewer("presentation.pptx"))
        {
            // Set output PDF options       
            var viewOptions = new PdfViewOptions("presentation.pdf");
            
            // Export PPTX to PDF       
            viewer.View(viewOptions);
        }
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