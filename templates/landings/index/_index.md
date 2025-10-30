---
############################# Static ##########################
layout: "family"
date: 2023-12-20T06:39:57
draft: false

product: "Viewer"
product_tag: "viewer"

############################# Head ############################
head_title: "<% "{index-content.head_title}" %>"
head_description: "<% "{index-content.head_description}" %>"

############################# Header ##########################
title: "<% "{index-content.title}" %>"
description: |
  <% "{index-content.description_1}" %>

  <% "{index-content.description_2}" %>

  <% "{index-content.description_3}" %>

############################# Platforms ############################
supported_platforms:
  enable: true  
  head_title: "<% "{index-content.supported_platforms.head_title}" %>"
  title: "<% "{index-content.supported_platforms.title}" %>"
  description: "<% "{index-content.supported_platforms.description}" %>"
  details_link_title: "<% "{index-content.supported_platforms.details_link_title}" %>"
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
        - content: "<% "{index-content.supported_platforms.item_1_formats_count}" %>"
          rows: "1"
        # features loop
        - content: "<% "{index-content.supported_platforms.item_1_ui_package}" %>"
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
        - content: "<% "{index-content.supported_platforms.item_1_formats_count}" %>"
          rows: "1"
        # features loop
        - content:  "<% "{index-content.supported_platforms.item_2_ui_package}" %>"
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
        - content:  "<% "{index-content.supported_platforms.item_1_formats_count}" %>"
          rows: "1"
        # features loop
        - content:  "<% "{index-content.supported_platforms.item_3_ui_package}" %>"
          rows: "1" 
        # features loop
        - content:  "<% "{index-content.supported_platforms.item_3_demo}" %>"
          rows: "3" 

    # supported_platforms loop
    - title: "Python"
      description: "GroupDocs.Viewer for Python"
      color: "yellow"
      tag: "python-net"
      link: "/viewer/python-net/"
      features_link: "https://docs.groupdocs.com/viewer/python-net/system-requirements/"
      features:
        # features loop
        - content: "Python 3.9+  <br>  and .Net 6+"
          rows: "3"
        # features loop
        - content:  "Windows, Linux, macOS"
          rows: "1"
        # features loop
        - content:  "<% "{index-content.supported_platforms.item_1_formats_count}" %>"
          rows: "1"
        # features loop
        - content:  "<% "{index-content.supported_platforms.item_3_ui_package}" %>"
          rows: "1" 
        # features loop
        - content:  "<% "{index-content.supported_platforms.item_3_demo}" %>"
          rows: "3" 

############################# Features ############################

features:
  enable: true
  title: "<% "{index-content.features.title}" %>"
  description: "<% "{index-content.features.description}" %>"

  items:
    # feature loop
    - icon: "view"
      title: "<% "{index-content.features.item_1_title}" %>"
      content: "<% "{index-content.features.item_1_content}" %>"

    # feature loop
    - icon: "password"
      title: "<% "{index-content.features.item_2_title}" %>"
      content: "<% "{index-content.features.item_2_content}" %>"

    # feature loop
    - icon: "load"
      title: "<% "{index-content.features.item_3_title}" %>"
      content: "<% "{index-content.features.item_3_content}" %>"
    
    # feature loop
    - icon: "pages"
      title: "<% "{index-content.features.item_4_title}" %>"
      content: "<% "{index-content.features.item_4_content}" %>"


############################# Code samples ############################
code_samples:
  enable: true
  title: "<% "{index-content.code_samples.title}" %>"
  description: "<% "{index-content.code_samples.description}" %>"
  items:
    # code sample loop
    - title: "<% "{index-content.code_samples.item_1.title}" %>"
      content: |
       <% "{index-content.code_samples.item_1.content}" %>
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // <% "{index-content.code_samples.item_1.comment_1}" %>
            using (Viewer viewer = new Viewer("sample.docx"))
            {
              // <% "{index-content.code_samples.item_1.comment_2}" %>
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
            // <% "{index-content.code_samples.item_1.comment_1}" %>
            try (Viewer viewer = new Viewer("sample.docx")) {
                // <% "{index-content.code_samples.item_1.comment_2}" %>
                PdfViewOptions viewOptions = new PdfViewOptions();
                viewer.view(viewOptions);
            }
            ```
        - language: "TypeScript"
          color: "green"
          content: |
            ```javascript {style=abap}  
            // <% "{index-content.code_samples.item_1.comment_1}" %>
            const viewer = new groupdocs.viewer.Viewer("sample.docx")
            
            // <% "{index-content.code_samples.item_1.comment_2}" %>
            const viewOptions = groupdocs.viewer.PdfViewOptions(output.pdf)
            viewer.view(viewOptions)
            ```

        - language: "Python"
          color: "yellow"
          content: |
            ```python {style=abap} 
            import groupdocs.viewer as gv
            import groupdocs.viewer.options as gvo   
            // <% "{index-content.code_samples.item_1.comment_1}" %>
            with gv.Viewer("sample.docx") as viewer:
            
                // <% "{index-content.code_samples.item_1.comment_2}" %>
                viewOptions = gvo.PdfViewOptions("output.pdf")
                viewer.view(viewOptions)
            ```

############################# Formats ############################
formats:
  enable: true
  title:  "<% "{index-content.formats.title}" %>"
  description: "<% "{index-content.formats.description}" %>"


############################# Metrics ############################

metrics:
  enable: true
  title: "<% "{index-content.metrics.title}" %>"
  description: "<% "{index-content.metrics.description}" %>"

  items:
    # metrics loop
    - number: "180+"
      title: "<% "{index-content.metrics.item_1.title}" %>"
      content: "<% "{index-content.metrics.item_1.content}" %>"
    # metrics loop
    - number: "1.0M"
      title: "<% "{index-content.metrics.item_2.title}" %>"
      content: "<% "{index-content.metrics.item_2.content}" %>"

    # metrics loop
    - number: "10+"
      title: "<% "{index-content.metrics.item_3.title}" %>"
      content: "<% "{index-content.metrics.item_3.content}" %>"
    
    # metrics loop
    - number: "100+"
      title: "<% "{index-content.metrics.item_4.title}" %>"
      content: "<% "{index-content.metrics.item_4.content}" %>"


############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "<% "{index-content.customers.title}" %>"
  description: "<% "{index-content.customers.description}" %>"

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
  title: "<% "{index-content.actions.title}" %>"
  description: "<% "{index-content.actions.description}" %>"

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
        #  loop
    - title: "Python"
      link: "/viewer/python-net/"
      color: "yellow"

############################# Faq ############################

faq:
  enable: true
  title: "<% "{index-content.faq.title}" %>"
  description: "<% "{index-content.faq.description}" %>"

  items:
    #  loop
    - question: "<% "{index-content.faq.question_1}" %>"
      answer: |
        <% "{index-content.faq.answer_1}" %>
    #  loop
    - question: "<% "{index-content.faq.question_2}" %>"
      answer: |
        <% "{index-content.faq.answer_2}" %>
    #  loop
    - question: "<% "{index-content.faq.question_3}" %>"
      answer: |
        <% "{index-content.faq.answer_3}" %>    
    #  loop
    - question: "<% "{index-content.faq.question_4}" %>"
      answer: |
        <% "{index-content.faq.answer_4}" %>
    #  loop
    - question: "<% "{index-content.faq.question_5}" %>"
      answer: |
        <% "{index-content.faq.answer_5}" %>

############################# Cloud ############################

cloud_links:
  enable: true
  title: "<% "{index-content.cloud_links.title}" %>"
  description: "<% "{index-content.cloud_links.description}" %>"

  items:
    #  loop
    - icon: "groupdocs_viewer-for-curl"
      title: "GroupDocs.Viewer Cloud for cURL"
      link: "https://products.groupdocs.cloud/viewer/curl"
      content: "<% "{index-content.cloud_links.item_1_content}" %>"

    #  loop
    - icon: "groupdocs_viewer-for-net"
      title: "GroupDocs.Viewer Cloud for .NET"
      link: "https://products.groupdocs.cloud/viewer/net"
      content: "<% "{index-content.cloud_links.item_2_content}" %>"
    #  loop
    - icon: "groupdocs_viewer-for-java"
      title: "GroupDocs.Viewer Cloud for Java"
      link: "https://products.groupdocs.cloud/viewer/java"
      content: "<% "{index-content.cloud_links.item_3_content}" %>"

############################# Apps ############################

app_links:
  enable: true
  title: "<% "{index-content.app_links.title}" %>"
  description: "<% "{index-content.app_links.description}" %>"

  items:
    #  loop
    - icon: "groupdocs_viewer-app"
      title: "GroupDocs.Viewer Total"
      link: "https://products.groupdocs.app/viewer/total"
      content: "<% "{index-content.app_links.item_1_content}" %>"

    #  loop
    - icon: "groupdocs_words-app"
      title:  "GroupDocs.Viewer DOCX"
      link: "https://products.groupdocs.app/viewer/docx"
      content: "<% "{index-content.app_links.item_2_content}" %>"

    #  loop
    - icon: "groupdocs_pdf-app"
      title:  "GroupDocs.Viewer PDF"
      link: "https://products.groupdocs.app/viewer/pdf"
      content: "<% "{index-content.app_links.item_3_content}" %>"
    

---