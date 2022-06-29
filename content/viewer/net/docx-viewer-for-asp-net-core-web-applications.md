---
############################# Static ############################
layout: "auto-gen-viewer-ui"
date: 2022-06-23T12:00:00+02:00
draft: false

############################# Head ############################
head_title: "DOCX viewer library for ASP.NET Core Web Applications"
head_description: "View DOCX, navigate between pages, and export DOCX to PDF in ASP.NET Core Web Applications using your preferred .NET language - C# or VB.NET."

############################# Breadcrumb ############################
breadcrumb: "View DOCX in ASP.NET Core Web Apps"

############################# Header ############################
title: "View DOCX in ASP.NET Core Web Apps"
description: "File viewer library for DOCX files. Open and view DOCX files in ASP.NET Core Web Apps."

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

########################### Overview ###########################

overview:
    enable: true
    content: |
      Microsoft Word Document (DOCX) file format is one of the most popular document formats that was introduced with Microsoft Office 2007 and replaced the legacy DOC file format. The most popular application for opening and editing DOCX files is Microsoft Word. The unlicensed version of Microsoft Word can be used as a viewer for DOCX files, but you won't be able to edit a file without a license. Also, there are number of free applications that can be used to open DOCX files like LibreOffice and Apache OpenOffice.

      In case you're planning to build your own application that will enable users to open and view DOCX files you'll probably decide to use 3-d party library or API instead of developing your own solution due to time and resources savings.    

      GroupDocs.Viewer is a .NET library that supports more than 170 of the most popular file formats including DOCX. With just basic knowledge in development, you can quickly build DOCX viewer applications for mobile, web, or desktop platforms targeting .NET Framework, .NET Core, and .NET. In this tutorial, we’ll show you how to build your own ASP.NET Core Web Application that you can use to open and view DOCX files.

      We will develop DOCX file viewer application that will enable users to open DOCX files, navigate through pages using thumbnails or controls, search, zoom, and print PDF.

      The application that we’ll build can be run on Windows or Linux operation systems.

############################# HowTo ############################
howto:
    enable: true
    title: "How to add DOCX Viewer to ASP.NET Core Web App"
    content: |
      In this tutorial, we'll step through configuring and running the sample viewer application. You'll need a basic knowledge of the C# programming language and ASP.NET Core framework for building web applications.

      Let's get started with adding the required packages to your ASP.NET Core Web Application.

      {{% viewer/note "Learn how to create ASP.NET Core Web App" %}}
      To learn how to create and run ASP.NET Core Web App, see [Get started with ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core/getting-started/) and [Get started with C# and ASP.NET Core in Visual Studio](https://docs.microsoft.com/en-us/visualstudio/get-started/csharp/tutorial-aspnet-core) tutorials. 
      {{% /viewer/note %}}

      We're going to add three packages to our project:
      * [GroupDocs.Viewer.UI](https://www.nuget.org/packages/groupdocs.viewer.ui) - contains the middleware that serves Angular application that enables you to open and view DOCX files.
      * [GroupDocs.Viewer.UI.SelfHost.Api](https://www.nuget.org/packages/groupdocs.viewer.ui.selfhost.api) - backend API which serves the data, like information about the document, document pages, and etc. to UI. The backend is using [GroupDocs.Viewer](https://www.nuget.org/packages/groupdocs.viewer) as a rendering engine. By default, document pages are converted to HTML, you can also configure rendering to PNG or JPEG. 
      * [GroupDocs.Viewer.UI.Api.Local.Storage](https://www.nuget.org/packages/groupdocs.viewer.ui.api.local.storage) - local file storage that is responsible for reading and writing files.

      <br/>

      Depending on which development tools you're using you can add packages with help of Package Manager in Visual Studio, from the command line with .NET CLI, and by copying and pasting package references to your `.csproj` file.

      {{< viewer/additional-styles >}}
      {{< viewer/install-viewer-ui >}}
    
      <br>

      After we've added the packages let's open `Startup.cs` file register and configure middlewares. In case you’re using the new [program style](https://docs.microsoft.com/en-us/dotnet/core/tutorials/top-level-templates) with top-level statements, global using directives, and implicit using directives the `Startup` will be a bit shorter. 

      {{< viewer/configure-viewer-ui >}}

      The code above registers `/viewer` (UI) middleware and `/viewer-api` (API) middleware. We've also added local storage to read and write files. Please note that `Files` folder won't be created automatically, please make sure to create `Files` folder manually before running the application.

      At this point, we're ready to run our application and open DOCX file for view. After you run the application the UI will be available at the `/viewer` path.

      {{% viewer/note "Note about default port provided by the development web server" %}}
      Your application may be available at a different port. You can find environment settings for the local machine development in `Properties\launchSettings.json` file. Learn more about `launchSettings.json` at [Development and launchSettings.json](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/environments#development-and-launchsettingsjson).
      {{% /viewer/note %}}

      {{< figure src="/viewer/media/viewer-ui.png" alt="Viewer UI" >}}

      &nbsp;

      Let's upload a sample file and open it using Viewer:
        
        1. Click the folder icon to open a file browser.
        2. Upload a file using `Upload File` button.
        3. Click on a file in the list of the available files.
      
      &nbsp;

      {{< figure src="/viewer/media/viewer-ui-browse-files-docx.png" alt="Upload and open file" >}}

      &nbsp;

      After the file is processed by GroupDocs.Viewer you'll see a sample file in your browser. You can navigate between pages, zoom in or zoom out pages, download the source file, search and print a document as PDF using the controls in the menu bar.

      &nbsp;

      {{< figure src="/viewer/media/viewer-ui-view-file-docx.png" alt="View file" >}}

      {{% viewer/note "Note about default port provided by the development web server" %}}
      By default, GroupDocs.Viewer works in trial mode, learn more about limitations at [Licensing and Subscription](https://docs.groupdocs.com/viewer/net/licensing-and-subscription/). To get started and evaluate the product you can get a temporary license at [Get a Temporary License](https://purchase.groupdocs.com/temporary-license). 
      {{% /viewer/note %}}

      We hope that you've found this tutorial useful. In case of any questions or issues, please [contact us](https://about.groupdocs.com/contact/) and we'll be glad to assist you.

############################# DEMO Viewer App #########################
demoApp:
    enable: true
    title: "DOCX File Viewer Demo"
    format: "docx"

############################# More Viewers ############################
more_formats:
    enable: true
    title: "Build you own Viewer App for the most popular file formats"
    content: |
       Build a production-ready application and view the most popular file formats that include DOCX, PPTX, XLSX, PDF and many more.  
    format: 
        # format loop
        - name: "XLSX File Viewer"
          #link: "/xlsx-viewer-for-asp-net-core-web-applications"
          description: "Microsoft Excel Open XML Spreadsheet Viewer for ASP.NET Core Web Applications"

        # format loop
        - name: "CDR File Viewer"
          #link: "/cdr-viewer-for-asp-net-core-web-applications"
          description: "CorelDRAW Image File Viewer for ASP.NET Core Web Applications"

        # format loop
        - name: "PPTX File Viewer"
          #link: "/cdr-viewer-for-asp-net-core-web-applications"
          description: "PowerPoint Open XML Presentation Viewer for ASP.NET Core Web Applications"

        # format loop
        - name: "DWF File Viewer"
          #link: "/dwg-viewer-for-asp-net-core-web-applications"
          description: "AutoCAD Drawing Viewer for ASP.NET Core Web Applications"

        # format loop
        - name: "Excel File Viewer"
          #link: "/excel-viewer-for-asp-net-core-web-applications"
          description: "Excel Viewer for ASP.NET Core Web Applications"

        # format loop
        - name: "AI File Viewer"
          #link: "/ai-viewer-for-asp-net-core-web-applications"
          description: "Adobe Illustrator Artwork Viewer for ASP.NET Core Web Applications"

        # format loop
        - name: "PSD File Viewer"
          #link: "/psd-viewer-for-asp-net-core-web-applications"
          description: "Adobe Photoshop Document Viewer for ASP.NET Core Web Applications"

        # format loop
        - name: "DOC File Viewer"
          #link: "/doc-viewer-for-asp-net-core-web-applications"
          description: "Microsoft Word Document Viewer for ASP.NET Core Web Applications"

        # format loop
        - name: "XML File Viewer"
          #link: "/xml-viewer-for-asp-net-core-web-applications"
          description: "XML File Viewer for ASP.NET Core Web Applications"

        # format loop
        - name: "DXF File Viewer"
          #link: "/dxf-viewer-for-asp-net-core-web-applications"
          description: "Drawing Exchange Format File Viewer for ASP.NET Core Web Applications"

        # format loop
        - name: "TXT File Viewer"
          #link: "/txt-viewer-for-asp-net-core-web-applications"
          description: "Plain Text File Viewer for ASP.NET Core Web Applications"

        # format loop
        - name: "SVG File Viewer"
          #link: "/svg-viewer-for-asp-net-core-web-applications"
          description: "Scalable Vector Graphics File Viewer for ASP.NET Core Web Applications"

        # format loop
        - name: "DWF File Viewer"
          #link: "/dwf-viewer-for-asp-net-core-web-applications"
          description: "Design Web Format File Viewer for ASP.NET Core Web Applications"

        # format loop
        - name: "VCF File Viewer"
          #link: "/vcf-viewer-for-asp-net-core-web-applications"
          description: "vCard File Viewer for ASP.NET Core Web Applications"

        # format loop
        - name: "MPP File Viewer"
          #link: "/mpp-viewer-for-asp-net-core-web-applications"
          description: "Microsoft Project File Viewer for ASP.NET Core Web Applications"

        # format loop
        - name: "EPS File Viewer"
          #link: "/eps-viewer-for-asp-net-core-web-applications"
          description: "Encapsulated PostScript File Viewer for ASP.NET Core Web Applications"

        # format loop
        - name: "SQL File Viewer"
          #link: "/sql-viewer-for-asp-net-core-web-applications"
          description: "Structured Query Language Data File Viewer for ASP.NET Core Web Applications"

        # format loop
        - name: "ODT File Viewer"
          #link: "/odt-viewer-for-asp-net-core-web-applications"
          description: "OpenDocument Text Document File Viewer for ASP.NET Core Web Applications"

        # format loop
        - name: "MSG File Viewer"
          #link: "/msg-viewer-for-asp-net-core-web-applications"
          description: "Outlook Message Item File Viewer for ASP.NET Core Web Applications"

############################# Back to top ###############################
back_to_top:
    enable: true
---