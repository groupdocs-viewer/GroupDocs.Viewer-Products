---
############################# Static ##########################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: <% lower (get "lang") %>
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
head_title: "<% "{index-content-net.head_title}" %>"
head_description: "<% "{index-content-net.head_description}" %>"

############################# Header ##########################
title: "<% "{index-content-net.header_title}" %>"
description: "<% "{index-content-net.header_description}" %>"
words:
  for: "for"

actions:
  viewer_demo: true
  viewer_demo_file_name: "quarterly-report.docx"
  main: "<% "{index-content-net.actions_main}" %>"
  main_link: "https://www.nuget.org/packages/GroupDocs.Viewer"
  alt: "<% "{index-content-common.actions_alt}" %>"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/net"
  title: "<% "{index-content-common.actions_title}" %>"
  description: "<% "{index-content-common.actions_description}" %>"

release:
  title: "<% "{index-content-common.release_title}" %>"
  notes: "<% "{index-content-common.release_notes}" %>"
  downloads: "<% "{index-content-common.release_downloads}" %>"
  link: "https://releases.groupdocs.com/viewer/net/release-notes/latest/"

code:
  title: "<% "{index-content-net.code_title}" %>"
  more: "<% "{index-content-common.code_more}" %>"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
  install: "dotnet add package GroupDocs.Viewer"
  content: |
    ```csharp {style=abap}   
    // <% "{index-content-net.code_comment_1}" %>
    using (var viewer = new Viewer("resume.pdf"))
    {
        // <% "{index-content-net.code_comment_2}" %>
        var viewOptions = 
        HtmlViewOptions.ForEmbeddedResources("page{0}.html");
        
        // <% "{index-content-net.code_comment_3}" %>        
        viewer.View(viewOptions);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "<% "{index-content-net.overview_title}" %>"
  description: "<% "{index-content-net.overview_description}" %>"
  features:
    # feature loop
    - title: "<% "{index-content-net.overview_features.feature1_title}" %>"
      content: "<% "{index-content-net.overview_features.feature1_content}" %>"

    # feature loop
    - title: "<% "{index-content-net.overview_features.feature2_title}" %>"
      content: "<% "{index-content-net.overview_features.feature2_content}" %>"

    # feature loop
    - title: "<% "{index-content-net.overview_features.feature3_title}" %>"
      content: "<% "{index-content-net.overview_features.feature3_content}" %>"

    # feature loop
    - title: "<% "{index-content-net.overview_features.feature4_title}" %>"
      content: "<% "{index-content-net.overview_features.feature4_content}" %>"

############################# Platforms ############################
platforms:
  enable: true
  title: "<% "{index-content-net.platforms_title}" %>"
  description: "<% "{index-content-net.platforms_description}" %>"
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
    - title: "<% "{index-content-net.platforms_packages_windows_title}" %>"
      content: |
        * <% "{index-content-net.platforms_packages_windows_content_1}" %>
        * <% "{index-content-net.platforms_packages_windows_content_2}" %>
        * <% "{index-content-net.platforms_packages_windows_content_3}" %> 
      action: "<% "{index-content-net.platforms_packages_windows_action}" %>"
      action_link: "https://www.nuget.org/packages/GroupDocs.Viewer"
    # packages loop
    - title: "<% "{index-content-net.platforms_packages_cross_platform_title}" %>" 
      content: |
        * <% "{index-content-net.platforms_packages_cross_platform_content_1}" %> 
        * <% "{index-content-net.platforms_packages_cross_platform_content_2}" %> 
        * <% "{index-content-net.platforms_packages_cross_platform_content_3}" %> 
      action: "<% "{index-content-net.platforms_packages_cross_platform_action}" %>" 
      action_link: "https://www.nuget.org/packages/GroupDocs.Viewer.CrossPlatform" 

############################# File formats ############################
formats:
  enable: true
  title: "<% "{index-content-common.formats.title}" %>"
  description: |
    <% "{index-content-net.formats.description}" %>
  groups:
    # group loop
    - color: "green"
      content: |
        ### <% "{index-content-common.formats.group1}" %>
        * **Word:** DOC, DOCX, DOCM, DOT, DOTX, DOTM, RTF, TXT
        * **Excel:** XLS, XLSX, XLSM, XLSB, XLTM, XLT, XLTM, XLTX
        * **PowerPoint:** PPT, PPTX, PPS, PPSX, PPSM, POT, POTM, POTX, PPTM        
        * **Project:** MPP, MPT, MPX {{< landing/tooltip icon="windows" title="<% "{index-content-common.formats.supported_by_windows_specific_package}" %>" >}}
        * **Outlook:** MSG, EML, EMLX, PST, OST
        * **OneNote:** ONE {{< landing/tooltip icon="windows" title="<% "{index-content-common.formats.supported_by_windows_specific_package}" %>" >}}
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
        * **Adobe Photoshop:** PSD, PSB {{< landing/tooltip icon="windows" title="<% "{index-content-common.formats.supported_by_windows_specific_package}" %>" >}}       
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
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM {{< landing/tooltip icon="windows" title="<% "{index-content-common.formats.supported_by_windows_specific_package}" %>" >}}
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
      title: "<% "[{index-content-common.features.feature1_title}](https://blog.groupdocs.com/viewer/view-word-documents-as-html-responsive-page-using-csharp/)" %>"
      content: "<% "{index-content-common.features.feature1_content}" %>"

    # feature loop
    - icon: "rasterize"
      title: "<% "{index-content-common.features.feature2_title}" %>"
      content: "<% "{index-content-common.features.feature2_content}" %>"

    # feature loop
    - icon: "font"
      title: "<% "[{index-content-common.features.feature3_title}](https://blog.groupdocs.com/viewer/working-with-fonts/)" %>"
      content: "<% "{index-content-common.features.feature3_content}" %>"

    # feature loop
    - icon: "convertpdf"
      title: "<% "[{index-content-common.features.feature4_title}](https://blog.groupdocs.com/viewer/rendering-documents-as-pdf/)" %>"
      content: "<% "{index-content-common.features.feature4_content}" %>"

    # feature loop
    - icon: "transform"
      title: "<% "[{index-content-common.features.feature5_title}](https://blog.groupdocs.com/viewer/protect-your-documents-with-watermarks-in-groupdocs-viewer-for-dot-net/)" %>"
      content: "<% "{index-content-common.features.feature5_content}" %>"

    # feature loop
    - icon: "adjustment"
      title: "<% "[{index-content-common.features.feature6_title}](https://blog.groupdocs.com/viewer/render-word-documents-as-clean-html-using-csharp/)"%>"
      content: "<% "{index-content-common.features.feature6_content}" %>"

    # feature loop
    - icon: "complex"
      title: "<% "[{index-content-common.features.feature7_title}](https://blog.groupdocs.com/viewer/process-microsoft-outlook-email-attachments-in-a-.net-viewer-application/)" %>"
      content: "<% "{index-content-common.features.feature7_content}" %>"

    # feature loop
    - icon: "optimization"
      title: "<% "[{index-content-common.features.feature8_title}](https://blog.groupdocs.com/viewer/exclude-specific-fonts-from-output-html-using-groupdocs.viewer-for-.net-18.10/)" %>"
      content: "<% "{index-content-common.features.feature8_content}" %>"

    # feature loop
    - icon: "passwordprotected"
      title: "<% "[{index-content-common.features.feature9_title}](https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET/blob/master/Examples/GroupDocs.Viewer.Examples.CSharp/AdvancedUsage/Loading/LoadPasswordProtectedDocument.cs)" %>"
      content: "<% "{index-content-common.features.feature9_content}" %>"

############################# Code samples ############################
code_samples:
  enable: true
  title: "<% "{index-content-net.code_samples.title}" %>"
  description: "<% "{index-content-net.code_samples.description}" %>"
  items:
    # code sample loop
    - title: "<% "{index-content-net.code_samples.sample1_title}" %>"
      content: |
        <% "{index-content-net.code_samples.sample1_content1}" %> <% "{index-content-net.code_samples.sample1_content2}" %>
        {{< landing/code title="C#">}}
        ```csharp {style=abap}
        using GroupDocs.Viewer;
        using GroupDocs.Viewer.Options;
        
        // <% "{index-content-net.code_samples.sample1_comment_1}" %>
        using (Viewer viewer = new Viewer("resume.docx"))
        {
            // <% "{index-content-net.code_samples.sample1_comment_2}" %>
            HtmlViewOptions options = HtmlViewOptions.ForEmbeddedResources();
            
            // <% "{index-content-net.code_samples.sample1_comment_3}" %>
            viewer.View(options);
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "<% "{index-content-net.code_samples.sample2_title}" %>"
      content: |
        <% "{index-content-net.code_samples.sample2_content1}" %> <% "{index-content-net.code_samples.sample2_content2}" %>
        {{< landing/code title="C#">}}
        ```csharp {style=abap}   
        using GroupDocs.Viewer;
        using GroupDocs.Viewer.Options;
        
        using (var viewer = new Viewer("presentation.pptx"))
        {
            // <% "{index-content-net.code_samples.sample2_comment_1}" %>       
            var viewOptions = new PdfViewOptions("presentation.pdf");
            
            // <% "{index-content-net.code_samples.sample2_comment_2}" %>       
            viewer.View(viewOptions);
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