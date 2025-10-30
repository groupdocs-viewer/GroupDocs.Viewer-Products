---
############################# Static ############################
layout: "format"
date: <% date "utcnow" %>
draft: false
lang: <% lower (get "lang") %>
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head #############################
head_title: "<% "{format-content-net.meta_title}" %>"
head_description: "<% "{format-content-net.meta_description}" %>"

############################# Header ############################
title: "<% "{format-content-net.title}" %>" 
description: "<% "{format-content-net.description}" %>" 
subtitle: "<% "{format-content-net.subtitle}" %>" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "<% "{format-content-net.download_button_label}" %>"
      link: "https://nuget.org/packages/GroupDocs.Viewer"



############################# About ############################
about:
    enable: true
    title: "<% "{format-content-net.about_title}" %>"
    link: "/viewer/net/"
    link_title: "<% "{format-content-net.about_link_title}" %>"
    picture: "about_viewer.svg" # 480 X 400
    content: |
      <% "{format-content-net.about_content}" %>



############################# Steps ############################
steps:
    enable: true
    title: "<% "{format-content-net.steps_title}" %>" 
    content: |
      <% "{format-content-net.steps_content}" %>
      
      1. <% "{format-content-net.steps_content_step_1}" %> 
      2. <% "{format-content-net.steps_content_step_2}" %>  
      3. <% "{format-content-net.steps_content_step_3}" %> 
      4. <% "{format-content-net.steps_content_step_4}" %> 
   
    code:
      platform: "net"
      copy_title: "<% "{format-content-net.steps_copy_title}" %>"
      install:
        command: "dotnet add package GroupDocs.Viewer"
        copy_tip: "<% "{format-content-net.steps_copy_tip}" %>"
        copy_done: "<% "{format-content-net.steps_copy_done}" %>"
      links:
        #  loop
        - title: "<% "{format-content-net.steps_link_examples}" %>"
          link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
        #  loop
        - title: "<% "{format-content-net.steps_link_documentation}" %>"
          link: "https://docs.groupdocs.com/viewer/net/"
          
      content: |
<% include "..\\..\\examples\\view\\_render_file_to_html_net.md" %>



############################# Actions ############################

actions:
  enable: true
  title: "<% "{format-content-net.actions_title}" %>"
  description: "<% "{format-content-net.actions_description}" %>"
  items:
    #  loop
    - title: "<% "{format-content-net.actions_install}" %>"
      link: "https://nuget.org/packages/GroupDocs.Viewer"
      color: "red"
        #  loop
    - title: "<% "{format-content-net.actions_licensing}" %>"
      link: "https://purchase.groupdocs.com/pricing/viewer/net/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "<% "{format-content-net.more_formats_title}" %>"
    exclude: "<% get "FILEFORMAT" %>"
    description: "<% "{format-content-net.more_formats_description}" %>"
    items: 
        # format loop 1
        - name: "<% "{format-content-net.more_formats_name_docx}" %>"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word Open XML Document" 

        # format loop 2
        - name: "<% "{format-content-net.more_formats_name_cdr}" %>" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "CorelDRAW File" 

        # format loop 3
        - name: "<% "{format-content-net.more_formats_name_pptx}" %>"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint Open XML Presentation" 

        # format loop 4
        - name: "<% "{format-content-net.more_formats_name_xlsx}" %>"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet" 

        # format loop 5
        - name: "<% "{format-content-net.more_formats_name_dwg}" %>"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "AutoCAD Drawing"

        # format loop 6
        - name: "<% "{format-content-net.more_formats_name_xml}" %>"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "XML File"

        # format loop 7
        - name: "<% "{format-content-net.more_formats_name_psd}" %>"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Adobe Photoshop Document"

        # format loop 8
        - name: "<% "{format-content-net.more_formats_name_ai}" %>"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Adobe Illustrator Artwork"

        # format loop 9
        - name: "<% "{format-content-net.more_formats_name_doc}" %>"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Microsoft Word Document" 

        # format loop 10
        - name: "<% "{format-content-net.more_formats_name_txt}" %>" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Plain Text File" 

        # format loop 11
        - name: "<% "{format-content-net.more_formats_name_dxf}" %>" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Drawing Exchange Format File"  
          
        # format loop 12
        - name: "<% "{format-content-net.more_formats_name_vcf}" %>"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "vCard File"  
              
        # format loop 13
        - name: "<% "{format-content-net.more_formats_name_svg}" %>"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Scalable Vector Graphic" 
          
        # format loop 14
        - name: "<% "{format-content-net.more_formats_name_html}" %>"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "<% "{format-content-net.more_formats_name_pdf}" %>"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Portable Document Format File"
          
        # format loop 16
        - name: "<% "{format-content-net.more_formats_name_jpg}" %>"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "JPEG Image"
          
        # format loop 17
        - name: "<% "{format-content-net.more_formats_name_png}" %>"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Portable Network Graphic" 
          
        # format loop 18
        - name: "<% "{format-content-net.more_formats_name_eml}" %>"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "E-Mail Message" 
          
        # format loop 19
        - name: "<% "{format-content-net.more_formats_name_rtf}" %>"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Rich Text Format File" 
          
        # format loop 20
        - name: "<% "{format-content-net.more_formats_name_odt}" %>"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "OpenDocument Text Document" 
          
        # format loop 21
        - name: "<% "{format-content-net.more_formats_name_csv}" %>"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Comma-Separated Values File" 



---
