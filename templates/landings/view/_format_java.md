---
############################# Static ############################
layout: "format"
date: <% date "utcnow" %>
draft: false
lang: <% lower (get "lang") %>
product: "Viewer"
product_tag: "viewer"
platform: "Java"
platform_tag: "java"

############################# Head #############################
head_title: "<% "{format-content-java.meta_title}" %>"
head_description: "<% "{format-content-java.meta_description}" %>"

############################# Header ############################
title: "<% "{format-content-java.title}" %>" 
description: "<% "{format-content-java.description}" %>" 
subtitle: "<% "{format-content-java.subtitle}" %>" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "<% "{format-content-java.download_button_label}" %>"
      link: "https://releases.groupdocs.com/viewer/java/"



############################# About ############################
about:
    enable: true
    title: "<% "{format-content-java.about_title}" %>"
    link: "/viewer/java/"
    link_title: "<% "{format-content-java.about_link_title}" %>"
    picture: "about_viewer.svg" # 480 X 400
    content: |
      <% "{format-content-java.about_content}" %>



############################# Steps ############################
steps:
    enable: true
    title: "<% "{format-content-java.steps_title}" %>" 
    content: |
      <% "{format-content-java.steps_content}" %>
      
      1. <% "{format-content-java.steps_content_step_1}" %> 
      2. <% "{format-content-java.steps_content_step_2}" %>  
      3. <% "{format-content-java.steps_content_step_3}" %> 
      4. <% "{format-content-java.steps_content_step_4}" %> 
   
    code:
      platform: "java"
      copy_title: "<% "{format-content-java.steps_copy_title}" %>"
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
        copy_tip: "<% "{format-content-java.steps_copy_tip}" %>"
        copy_done: "<% "{format-content-java.steps_copy_done}" %>"
      links:
        #  loop
        - title: "<% "{format-content-java.steps_link_examples}" %>"
          link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Java"
        #  loop
        - title: "<% "{format-content-java.steps_link_documentation}" %>"
          link: "https://docs.groupdocs.com/viewer/java/"
          
      content: |
<% include "..\\..\\examples\\view\\_render_file_to_html_java.md" %>


############################# Actions ############################

actions:
  enable: true
  title: "<% "{format-content-java.actions_title}" %>"
  description: "<% "{format-content-java.actions_description}" %>"
  items:
    #  loop
    - title: "<% "{format-content-java.actions_install}" %>"
      link: "https://releases.groupdocs.com/viewer/java/"
      color: "red"
        #  loop
    - title: "<% "{format-content-java.actions_licensing}" %>"
      link: "https://purchase.groupdocs.com/pricing/viewer/java/"
      color: "light"



############################# More Formats #####################
more_formats:
    enable: true
    title: "<% "{format-content-java.more_formats_title}" %>"
    exclude: "<% get "FILEFORMAT" %>"
    description: "<% "{format-content-java.more_formats_description}" %>"
    items: 
        # format loop 1
        - name: "<% "{format-content-java.more_formats_name_docx}" %>"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Open XML Document" 

        # format loop 2
        - name: "<% "{format-content-java.more_formats_name_cdr}" %>" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "CorelDRAW File" 

        # format loop 3
        - name: "<% "{format-content-java.more_formats_name_pptx}" %>"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint Open XML Presentation" 

        # format loop 4
        - name: "<% "{format-content-java.more_formats_name_xlsx}" %>"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet" 

        # format loop 5
        - name: "<% "{format-content-java.more_formats_name_dwg}" %>"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "AutoCAD Drawing"

        # format loop 6
        - name: "<% "{format-content-java.more_formats_name_xml}" %>"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "XML File"

        # format loop 7
        - name: "<% "{format-content-java.more_formats_name_psd}" %>"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Adobe Photoshop Document"

        # format loop 8
        - name: "<% "{format-content-java.more_formats_name_ai}" %>"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Adobe Illustrator Artwork"

        # format loop 9
        - name: "<% "{format-content-java.more_formats_name_doc}" %>"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Microsoft Word Document" 

        # format loop 10
        - name: "<% "{format-content-java.more_formats_name_txt}" %>" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Plain Text File" 

        # format loop 11
        - name: "<% "{format-content-java.more_formats_name_dxf}" %>" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Drawing Exchange Format File"  
          
        # format loop 12
        - name: "<% "{format-content-java.more_formats_name_vcf}" %>"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "vCard File"  
              
        # format loop 13
        - name: "<% "{format-content-java.more_formats_name_svg}" %>"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Scalable Vector Graphic" 
          
        # format loop 14
        - name: "<% "{format-content-java.more_formats_name_html}" %>"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "<% "{format-content-java.more_formats_name_pdf}" %>"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Portable Document Format File"
          
        # format loop 16
        - name: "<% "{format-content-java.more_formats_name_jpg}" %>"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "JPEG Image"
          
        # format loop 17
        - name: "<% "{format-content-java.more_formats_name_png}" %>"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Portable Network Graphic" 
          
        # format loop 18
        - name: "<% "{format-content-java.more_formats_name_eml}" %>"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "E-Mail Message" 
          
        # format loop 19
        - name: "<% "{format-content-java.more_formats_name_rtf}" %>"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Rich Text Format File" 
          
        # format loop 20
        - name: "<% "{format-content-java.more_formats_name_odt}" %>"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "OpenDocument Text Document" 
          
        # format loop 21
        - name: "<% "{format-content-java.more_formats_name_csv}" %>"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Comma-Separated Values File" 


---
