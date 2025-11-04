---
############################# Static ############################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

product: "Viewer"
product_tag: "viewer"
platform: "Java"
platform_tag: "java"

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
head_title: "<% "{index-content-java.head_title}" %>"
head_description: "<% "{index-content-java.head_description}" %>"

############################# Header ############################
title: "<% "{index-content-java.header_title}" %>"
description: "<% "{index-content-java.header_description}" %>"
words:
  for: "for"

actions:
  viewer_demo: true
  viewer_demo_file_name: "quarterly-report.docx"
  main: "<% "{index-content-java.actions_main}" %>"
  main_link: "https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-viewer/"
  alt: "<% "{index-content-common.actions_alt}" %>"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/java"
  title: "<% "{index-content-common.actions_title}" %>"
  description: "<% "{index-content-common.actions_description}" %>"

release:
  title: "<% "{index-content-common.release_title}" %>"
  notes: "<% "{index-content-common.release_notes}" %>"
  downloads: "<% "{index-content-common.release_downloads}" %>"
  link: "https://releases.groupdocs.com/viewer/java/release-notes/latest/"

code:
  title: "<% "{index-content-java.code_title}" %>"
  more: "<% "{index-content-common.code_more}" %>"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Java"
  install: |
    <dependencies>
      <dependency>
        <groupId>com.groupdocs</groupId>
        <artifactId>groupdocs-viewer</artifactId>
        <version>{0}</version>
      </dependency>
    </dependencies>

    <repositories>
      <repository>
        <id>repository.groupdocs.com</id>
        <name>GroupDocs Repository</name>
        <url>https://repository.groupdocs.com/repo/</url>
      </repository>
    </repositories>
  content: |
    ```java {style=abap}
    // <% "{index-content-java.code_comment_1}" %> 
    try (Viewer viewer = new Viewer("resume.pdf"))
    {
        // <% "{index-content-java.code_comment_2}" %>  
        HtmlViewOptions viewOptions = 
        HtmlViewOptions.forEmbeddedResources();

        // <% "{index-content-java.code_comment_3}" %>
        viewer.view(viewOptions);
    }
    ```
############################# Overview ############################
overview:
  enable: true
  title: "<% "{index-content-java.overview_title}" %>"
  description: "<% "{index-content-java.overview_description}" %>"
  features:
    # feature loop
    - title: "<% "{index-content-java.overview_features.feature1_title}" %>"
      content: "<% "{index-content-java.overview_features.feature1_content}" %>"

    # feature loop
    - title: "<% "{index-content-java.overview_features.feature2_title}" %>"
      content: "<% "{index-content-java.overview_features.feature2_content}" %>"

    # feature loop
    - title: "<% "{index-content-java.overview_features.feature3_title}" %>"
      content: "<% "{index-content-java.overview_features.feature3_content}" %>"

    # feature loop
    - title: "<% "{index-content-java.overview_features.feature4_title}" %>"
      content: "<% "{index-content-java.overview_features.feature4_content}" %>"

############################# Platforms ############################
platforms:
  enable: true
  title: "<% "{index-content-java.platforms_title}" %>"
  description: "<% "{index-content-java.platforms_description}" %>"
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
    - title: "Eclipse"
      image: "eclipse"
    # platform loop
    - title: "IntelliJ"
      image: "intellij"
    # platform loop
    - title: "Windows"
      image: "windows"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "Maven"
      image: "maven"


############################# File formats ############################
formats:
  enable: true
  title: "<% "{index-content-common.formats.title}" %>"
  description: |
    <% "{index-content-java.formats.description}" %>
  groups:
    # group loop
    - color: "green"
      content: |
        ### <% "{index-content-common.formats.group1}" %>
        * **Word:** DOC, DOCX, DOCM, DOT, DOTX, DOTM, RTF, TXT
        * **Excel:** XLS, XLSX, XLSM, XLSB, XLTM, XLT, XLTM, XLTX
        * **PowerPoint:** PPT, PPTX, PPS, PPSX, PPSM, POT, POTM, POTX, PPTM        
        * **Project:** MPP, MPT, MPX
        * **Outlook:** MSG, EML, EMLX, PST, OST
        * **OneNote:** ONE
        * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG
        * **Fixed Page Layout:** PDF, TEX, XPS, OXPS
        * **e-Books:** EPUB, MOBI, DjVu
        * **Delimiter-Separated Values:** CSV, TSV
    # group loop
    - color: "blue"
      content: |
        ### <% "{index-content-common.formats.group2}" %>
        * **<% "{index-content-common.formats.raster}" %>:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
        * **Windows Icon:** ICO
        * **Scalable Vector Graphics:** SVG, CDR, CMX, IGS, SVGZ        
        * **Adobe Photoshop:** PSD, PSB        
        * **Stereo Lithography (3D Printing):** STL        
        * **Medical Imaging:** DICOM
        * **Plotter Documents:** PLT, HPG
        * **Autodesk Design Web Formats:** DWF, DWG
        * **AutoCAD Drawing:** DWT, IFC, STL, CF2        
      # group loop
    - color: "red"
      content: |
        ### <% "{index-content-common.formats.group3}" %>        
        * **<% "{index-content-common.formats.web}" %>:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **<% "{index-content-common.formats.archives}" %>:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **<% "{index-content-common.formats.group3}" %>:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "<% "{index-content-common.features.title}" %>"
  description: "<% "{index-content-common.features.description}" %>"

  items:
    # feature loop
    - icon: "viewhtml"
      title: "<% "{index-content-common.features.feature1_title}" %>"
      content: "<% "{index-content-common.features.feature1_content}" %>"

    # feature loop
    - icon: "rasterize"
      title: "<% "{index-content-common.features.feature2_title}" %>"
      content: "<% "{index-content-common.features.feature2_content}" %>"

    # feature loop
    - icon: "font"
      title: "<% "{index-content-common.features.feature3_title}" %>"
      content: "<% "{index-content-common.features.feature3_content}" %>"

    # feature loop
    - icon: "convertpdf"
      title: "<% "[{index-content-common.features.feature4_title}](https://blog.groupdocs.com/viewer/rendering-documents-as-pdf/)" %>"
      content: "<% "{index-content-common.features.feature4_content}" %>"

    # feature loop
    - icon: "transform"
      title: "<% "{index-content-common.features.feature5_title}" %>"
      content: "<% "{index-content-common.features.feature5_content}" %>"

    # feature loop
    - icon: "adjustment"
      title: "<% "[{index-content-common.features.feature6_title}](https://blog.groupdocs.com/viewer/render-word-documents-as-minified-html-in-java/)" %>"
      content: "<% "{index-content-common.features.feature6_content}" %>"

    # feature loop
    - icon: "complex"
      title: "<% "[{index-content-common.features.feature7_title}" %>](https://blog.groupdocs.com/viewer/view-files-and-folders-in-zip-and-tar-archives-using-java-api/)"
      content: "<% "{index-content-common.features.feature7_content}" %>"

    # feature loop
    - icon: "optimization"
      title: "<% "{index-content-common.features.feature8_title}" %>"
      content: "<% "{index-content-common.features.feature8_content}" %>"

    # feature loop
    - icon: "passwordprotected"
      title: "<% "{index-content-common.features.feature9_title}" %>"
      content: "<% "{index-content-common.features.feature9_content}" %>"

############################# Code samples ############################
code_samples:
  enable: true
  title: "<% "{index-content-java.code_samples.title}" %>"
  description: "<% "{index-content-java.code_samples.description}" %>"
  items:
    # code sample loop
    - title: "<% "{index-content-java.code_samples.sample1_title}" %>"
      content: |
        <% "{index-content-java.code_samples.sample1_content1}" %> <% "{index-content-java.code_samples.sample1_content2}" %>
        {{< landing/code title="Java">}}
        ```java {style=abap}
        import com.groupdocs.viewer.Viewer;
        import com.groupdocs.viewer.options.HtmlViewOptions;

        // <% "{index-content-java.code_samples.sample1_comment_1}" %>
        try (Viewer viewer = new Viewer("resume.docx"))
        {
            // <% "{index-content-java.code_samples.sample1_comment_2}" %>
            HtmlViewOptions options = 
            HtmlViewOptions.forEmbeddedResources();

            // <% "{index-content-java.code_samples.sample1_comment_3}" %>
            viewer.view(options);
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "<% "{index-content-java.code_samples.sample2_title}" %>"
      content: |
        <% "{index-content-java.code_samples.sample2_content1}" %> <% "{index-content-java.code_samples.sample2_content2}" %>
        {{< landing/code title="Java">}}
        ```java {style=abap}   
        import com.groupdocs.viewer.Viewer;
        import com.groupdocs.viewer.options.PdfViewOptions;

        // <% "{index-content-java.code_samples.sample2_comment_1}" %>
        try (Viewer viewer = new Viewer("presentation.pptx"))
        {            
            // <% "{index-content-java.code_samples.sample2_comment_2}" %>
            PdfViewOptions viewOptions = new PdfViewOptions();

            // <% "{index-content-java.code_samples.sample2_comment_3}" %>
            viewer.view(viewOptions);
        }
        ```
        {{< /landing/code >}}
############################# Reviews ############################
# reviews:
# enable: true
# title: "<% "{index-content-common.reviews.title}" %>"
# description: "<% "{index-content-common.reviews.description}" %>"

# items:
#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "<% "{index-content-common.reviews.content1}" %>"
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "<% "{index-content-common.reviews.content2}" %>"
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---