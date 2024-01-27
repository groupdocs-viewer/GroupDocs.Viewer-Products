---
############################# Static ############################
layout: "family"
date: 2023-12-20T06:39:57
draft: false

product: "Viewer"
product_tag: "viewer"

############################# Head ############################
head_title: "Render and View Documents API | On Premise API and online service"
head_description: "Render & view Word, PDF, Excel, Powerpoint or Image files easily and free"

############################# Header ############################
title: "Render and view documents with ease"
description: |
  Powerful Viewer API to Render different files to PDF, HTML, and Image.

  Load documents from various sources, including files, streams, URLs, FTP servers, Amazon S3, Azure Blob Storage, and more.

  Generate responsive HTML pages, protect the output PDF files and reorder their pages, rotate pages, render notes and comments if needed.
  

############################# Platforms ############################
supported_platforms:
  enable: true  
  head_title: "Choose your platform"
  title: "Supported platforms"
  description: "GroupDocs.Viewer library supports the following operating systems and frameworks"
  details_link_title: "Learn more"
  items:
    # supported_platforms loop
    - title: ".NET"
      description: "GroupDocs.Viewer for .NET"
      color: "blue"
      tag: "net"
      link: "/viewer/net/"
      features_link: "https://docs.groupdocs.com/viewer/net/system-requirements/"
      features:
        # features loop
        - content: ".NET Framework 4.6.2+  <br>  .NET Core 3.1  <br>  .NET 6+"
          rows: "3"
        # features loop
        - content: "Windows, Linux"
          rows: "1"
        # features loop
        - content: "180+ file formats"
          rows: "1"
        # features loop
        - content: "UI package for ASP.NET Core"
          rows: "1"
        # features loop
        - content: "ASP.NET WebForms Demo  <br>  ASP.NET MVC Demo  <br>  ASP.NET Core Demo"
          rows: "3"
    
    # supported_platforms loop
    - title: "Java"
      description: "GroupDocs.Viewer for Java"
      color: "red"
      tag: "java"
      link: "/viewer/java/"
      features_link: "https://docs.groupdocs.com/viewer/java/system-requirements/"
      features:
        # features loop
        - content: "J2SE 8.0 (1.8)+"
          rows: "3"
        # features loop
        - content:  "Windows, Linux, macOS"
          rows: "1"       
        # features loop
        - content:  "180+ file formats"
          rows: "1"
        # features loop
        - content:  "UI package for Spring and Dropwizard"
          rows: "1"
        # features loop
        - content:  "Spring Demo  <br>  Dropwizard demo"
          rows: "3"

    # supported_platforms loop
    - title: "Node.js"
      description: "GroupDocs.Viewer for Node.js"
      color: "green"
      tag: "nodejs-java"
      link: "/viewer/nodejs-java/"
      features_link: "https://docs.groupdocs.com/viewer/nodejs-java/system-requirements/"
      features:
        # features loop
        - content: "Node.js 16+  <br>  and J2SE 8.0 (1.8)+"
          rows: "3"
        # features loop
        - content:  "Windows, Linux, macOS"
          rows: "1"
        # features loop
        - content:  "180+ file formats"
          rows: "1"
        # features loop
        - content:  "UI package - coming soon "
          rows: "1" 
        # features loop
        - content:  "Demo - coming soon "
          rows: "3" 



############################# Features ############################

features:
  enable: true
  title: "GroupDocs.Viewer's feature set"
  description: "API to render files of different types as HTML, PDF, PNG, and JPEG in applications to view them without third-party software."

  items:
    # feature loop
    - icon: "view"
      title: "View documents and images"
      content: "View documents by rendering them as HTML, PDF, PNG, and JPEG files."
    # feature loop
    - icon: "password"
      title: "Open secured documents"
      content: "Specify a password to open encrypted documents."

    # feature loop
    - icon: "load"
      title: "Load files from anywhere"
      content: "Load documents from various files, URLs, FTP servers, Amazon S3, and more."
    
    # feature loop
    - icon: "pages"
      title: "Render all or specific pages"
      content: "Specify a range of page numbers to be rendered."


############################# Code samples ############################
code_samples:
  enable: true
  title: "GroupDocs.Viewer code samples"
  description: "Some use cases of typical GroupDocs.Viewer operations in C#, Java, TypeScript"
  items:
    # code sample loop
    - title: "How to render DOCX files to PDF"
      content: |
        Render DOCX documents to PDF without Microsoft Word or other software installed. Easily load and view DOCX files within your .NET application, whether it is a web or desktop application. Here is an example of how to render a DOCX file to PDF: 
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Load DOCX file to render
            using (Viewer viewer = new Viewer("sample.docx"))
            {
              // Render DOCX to a PDF file
              PdfViewOptions viewOptions = new PdfViewOptions();
              viewer.View(viewOptions);
            }
            ```
        - language: "Java"
          color: "red"
          content: |
            ```java {style=abap}   
            import com.groupdocs.viewer.Viewer;
            import com.groupdocs.viewer.options.PdfViewOptions;
            // ...
            // Load DOCX file to render
            try (Viewer viewer = new Viewer("sample.docx")) {
                // Render DOCX to a PDF file
                PdfViewOptions viewOptions = new PdfViewOptions();
                viewer.view(viewOptions);
            }
            ```
        - language: "TypeScript"
          color: "green"
          content: |
            ```javascript {style=abap}  
            // Load DOCX file to render
            const viewer = new groupdocs.viewer.Viewer("sample.docx")
            
            // Render DOCX to a PDF file
            const viewOptions = groupdocs.viewer.PdfViewOptions(output.pdf)
            viewer.view(viewOptions)
            ```


############################# Formats ############################
formats:
  enable: true
  title:  "180+ file formats supported"
  description: "GroupDocs.Viewer supports operations with the most popular [file formats](https://docs.groupdocs.com/viewer/net/supported-document-formats/)" 



############################# Metrics ############################

metrics:
  enable: true
  title: "In-depth metrics and statistical insights"
  description: "Dive into a detailed breakdown of our key figures, providing comprehensive metrics and statistical insights into our achievements, impact, and growth."

  items:
    # metrics loop
    - number: "180+"
      title: "Supported formats"
      content: "Easily view over 180 file formats including documents, images, and CAD drawings hassle-free. Break compatibility barriers and access diverse files effortlessly with our comprehensive viewing solution."

    # metrics loop
    - number: "1.0M"
      title: "NuGet downloads"
      content: "Our NuGet package solution has become a trusted and widely adopted resource in the developer community, providing seamless integration and valuable functionality for countless projects."

    # metrics loop
    - number: "10+"
      title: "Libraries"
      content: "Our product includes 10+ libraries, offering advanced features to optimize performance. These libraries are designed to fulfill different development needs with unparalleled capabilities."
    
    # metrics loop
    - number: "100+"
      title: "Happy customers"
      content: "Serving the most iconic brands around the globe. Discover why hundreds love GroupDocs.Viewer! Explore seamless navigation, convenient collaboration, and unparalleled ease of use. Join now!"



############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "Our happy customers"
  description: "GroupDocs libraries are employed by globally renowned and distinguished brands across the world."

  items:
    # customers loop
    - title: "BenQ Corporation"
      logo: "benq"
    # customers loop
    - title: "Nasdaq Stock Market"
      logo: "nasdaq"
    # customers loop
    - title: "AT&T Inc."
      logo: "att"
    # customers loop
    - title: "AstraZeneca"
      logo: "astrazeneca"
    # customers loop
    - title: "Central Bank of Argentina"
      logo: "argentinacentralbank"
    # customers loop
    - title: "Roche Holding AG"
      logo: "roche"
    # customers loop
    - title: "Capita"
      logo: "capita"
    # customers loop
    - title: "Axa S.A."
      logo: "axa"
    # customers loop
    - title: "Instructure Inc."
      logo: "instructure"
     # customers loop
    - title: "Wipro"
      logo: "wipro"



############################# Actions ############################

actions:
  enable: true
  title: "Ready to get started?"
  description: "Try GroupDocs.Viewer features for free or request a license"
  items:
    #  loop
    - title: ".NET"
      link: "/viewer/net/"
      color: "blue"
        #  loop
    - title: "Java"
      link: "/viewer/java/"
      color: "red"
        #  loop
    - title: "Node.js"
      link: "/viewer/nodejs-java/"
      color: "green"


############################# Faq ############################

faq:
  enable: true
  title:  "Common questions and concerns"
  description:  "Find answers to common inquiries in our FAQ section to quickly address your queries and concerns."
  items:
    #  loop
    - question: "Can I evaluate GroupDocs products prior to purchasing?"
      answer: |
        Yes! All GroupDocs products have a risk-free, evaluation version available. We strongly encourage developers to download and try our APIs before purchasing to ensure that they will fill your needs 100%.
    #  loop
    - question: "Does GroupDocs do product demonstrations?"
      answer: |
        No, our focus is on our APIs and making the most functional and stable products possible. We do offer fully functional and free trials in the form of a [temporary license](https://purchase.groupdocs.com/temporary-license/) so you can test out the product for yourself.    
    #  loop
    - question: "Where can I download the product?"
      answer: |
        All products are available to download from the [website](https://releases.groupdocs.com). We do not send physical copies of our software by mail.
    #  loop
    - question: "Are GroupDocs developer licenses per user, or per named user?"
      answer: |
        GroupDocs Developer licenses are per user, not per named user. We understand that members of a coding team may change over time and that it is not practical to have to update licensing each time that occurs.
    #  loop
    - question: "Do we need licensing for only active developers? For example, we have a team of two developers working on shift A and a second team of two developers working on shift B … in this situation, do we need two or four licenses?"
      answer: |
        All developers who are working on the project need to be licensed. In this situation, GroupDocs sees your team as having four members (even though they work at different times). 


############################# Cloud ############################

cloud_links:
  enable: true
  title: "GroupDocs.Viewer low code APIs"
  description: "Accelerate document or image viewing in any type of application with our cloud-based REST API"

  items:
    #  loop
    - icon: "groupdocs_viewer-for-curl"
      title: "GroupDocs.Viewer Cloud for cURL"
      link: "https://products.groupdocs.cloud/viewer/curl"
      content: "Use the cURL RESTful document viewer API to efficiently render and showcase Microsoft Office, PDF, and various other standard file formats in your applications."

    #  loop
    - icon: "groupdocs_viewer-for-net"
      title: "GroupDocs.Viewer Cloud for .NET"
      link: "https://products.groupdocs.cloud/viewer/net"
      content: "Enhance document viewing capabilities in .NET applications with Cloud SDK for .NET. View documents seamlessly in HTML, PDF, or image formats."

    #  loop
    - icon: "groupdocs_viewer-for-java"
      title: "GroupDocs.Viewer Cloud for Java"
      link: "https://products.groupdocs.cloud/viewer/java"
      content: "Integrate advanced document rendering capabilities into your Java applications using a purpose-built Document Viewer SDK for Java."
    

############################# Apps ############################

app_links:
  enable: true
  title: "GroupDocs.Viewer NoCode apps"
  description: "Online application allowing you to view 180+ popular file formats in browser"

  items:
    #  loop
    - icon: "groupdocs_viewer-app"
      title: "GroupDocs.Viewer Total"
      link: "https://products.groupdocs.app/viewer/total"
      content: "Explore a free online application to view over 180 file formats directly from your preferred web browser."

    #  loop
    - icon: "groupdocs_words-app"
      title:  "GroupDocs.Viewer DOCX"
      link: "https://products.groupdocs.app/viewer/docx"
      content: "Web-based tool for viewing Microsoft Word files effortlessly across various devices."

    #  loop
    - icon: "groupdocs_pdf-app"
      title:  "GroupDocs.Viewer PDF"
      link: "https://products.groupdocs.app/viewer/pdf"
      content: "Open and view PDF files online with free PDF viewer."
    



---