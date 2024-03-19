---
############################# Static ############################
layout: "format"
date: 2024-03-19T07:00:44
draft: false
lang: en
product: "Viewer"
product_tag: "viewer"
platform: "Java"
platform_tag: "java"

############################# Head #############################
head_title: "Java SCALA Viewer API - render & display SCALA in Java apps"
head_description: "View SCALA files in Java, J2EE, J2SE applications. Supports viewing 180+ document and image file formats in HTML, PDF or image mode with advanced features to manage document viewing options."

############################# Header ############################
title: "Render & view SCALA in Java" 
description: "Native and high performance SCALA file viewer API for Java, J2EE and J2SE based applications, supporting a wide range of additional features to customize the appearance of the output document format." 
subtitle: "Document rendering solution" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "Free Maven download"
      link: "https://releases.groupdocs.com/viewer/java/"



############################# About ############################
about:
    enable: true
    title: "About GroupDocs.Viewer for Java API"
    link: "/viewer/java/"
    link_title: "Learn more"
    picture: "about_viewer.svg" # 480 X 400
    content: |
      Enable your Java applications to display over 180+ file formats in HTML, PDF or image modes using GroupDocs.Viewer for Java APIs without any additional software installed; such as Microsoft Office, Apache Open Office, Adobe Acrobat Reader etc. Developers can easily view all popular images and document types including Microsoft Office, OpenDocument, HTML, PDF, Archive, Diagrams, Photoshop, AutoCAD and programming language formats inside the Java applications with fast and highest quality rendering.



############################# Steps ############################
steps:
    enable: true
    title: "Steps to render SCALA file in Java" 
    content: |
      With <a href='https://products.groupdocs.com/viewer/java/'>GroupDocs.Viewer</a> you can render SCALA to HTML, JPEG, PNG or PDF in a few steps.
      
      1. Add <a href='https://releases.groupdocs.com/viewer/java/'>GroupDocs.Viewer for Java</a> as a dependency to your project. 
      2. Create an instance of Viewer class and load the SCALA file with full path.  
      3. Set options to render SCALA file into HTML, PNG, JPEG or PDF format. 
      4. Render file and check output in the current directory. 
   
    code:
      platform: "java"
      copy_title: "Copy"
      install:
        command: |
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
        copy_tip: "click to copy"
        copy_done: "copied"
      links:
        #  loop
        - title: "More examples"
          link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Java"
        #  loop
        - title: "Documentation"
          link: "https://docs.groupdocs.com/viewer/java/"
          
      content: |
        ```java {style=abap}

        // Set up input SCALA file
        String filePath = "input.scala";

        // Instantiate GroupDocs.Viewer
        try (Viewer viewer = new Viewer(filePath))
        {
            // Set view options
            HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                
            // Render SCALA file to HTML with embedded resources
            viewer.view(viewOptions);
        }

        ```
            

############################# Actions ############################

actions:
  enable: true
  title: "Ready to get started?"
  description: "Try GroupDocs.Viewer features for free or request a license"
  items:
    #  loop
    - title: "Maven download"
      link: "https://releases.groupdocs.com/viewer/java/"
      color: "red"
        #  loop
    - title: "Licensing"
      link: "https://purchase.groupdocs.com/pricing/viewer/java/"
      color: "light"



############################# More Formats #####################
more_formats:
    enable: true
    title: "Render other file formats using Java"
    exclude: "SCALA"
    description: "Multi-format documents and images viewer API for Java. View some of the popular file formats below without any external viewers."
    items: 
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
        - name: "Render AI"
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


---
