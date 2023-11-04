---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: cy

############################# Head #############################
head_title: "Java YAML Viewer API - Render & Display YAML mewn Java Apps"
head_description: "Gweld YAML ffeil mewn rhaglenni Java, J2EE, J2SE. Yn cefnogi gwylio dros 170 o fformatau ffeil dogfen a delwedd mewn modd HTML, PDF neu ddelwedd gyda nodweddion uwch i reoli opsiynau gwylio dogfennau."

############################# Header ############################
title: "Rendro a Gweld YAML Yn Java" 
description: "API gwyliwr ffeil YAML brodorol a pherfformiad uchel ar gyfer cymwysiadau seiliedig ar Java, J2EE a J2SE, gan gefnogi ystod eang o nodweddion ychwanegol i addasu ymddangosiad fformat y ddogfen allbwn." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Download Treial Am Ddim"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Ynglŷn â GroupDocs.Viewer ar gyfer Java API" 
    content: |
        Galluogi eich cymwysiadau Java i arddangos dros 170+ o fformatau ffeil mewn moddau HTML, PDF neu ddelwedd gan ddefnyddio GroupDocs.Viewer ar gyfer Java APIs heb unrhyw feddalwedd ychwanegol wedi'i gosod; megis Microsoft Office, Apache Open Office, Adobe Acrobat Reader ac ati. Gall datblygwyr weld yr holl ddelweddau poblogaidd a mathau o ddogfen yn hawdd gan gynnwys Microsoft Office, OpenDocument, HTML, PDF, Archif, Diagramau, Photoshop, AutoCAD a fformatau iaith raglennu y tu mewn i'r rhaglenni Java gyda rendrad cyflym ac o'r ansawdd uchaf.

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
              text: "Cyfeirnod API"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Enghreifftiau Cod"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Demos Byw"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Prisio"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "Camau i Rendro ffeil YAML yn Java" 
    content_left: |
        Gyda [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/) gallwch rendro YAML i HTML, JPEG, PNG neu PDF mewn ychydig o gamau.

        * Ychwanegu [GroupDocs.Viewer ar gyfer Java](https://releases.groupdocs.com/viewer/java/) fel dibyniaeth i'ch prosiect. 
        * Creu enghraifft o ddosbarth Gwyliwr a llwytho'r ffeil YAML gyda llwybr llawn. 
        * Gosod opsiynau i rendr ffeil YAML i fformat HTML, PNG, JPEG neu PDF. 
        * Rendro ffeil a gwirio allbwn yn y cyfeiriadur cyfredol. 
        
    title_right: "Gofynion y System" 
    content_right: |
        Cefnogir GroupDocs.Viewer ar gyfer API Java ar bob prif lwyfan a system weithredu. Cyn gweithredu'r cod isod, gwnewch yn siŵr bod gennych y rhagofynion canlynol wedi'u gosod ar eich system.

        * Systemau Gweithredu: Microsoft Windows, Linux, MacOS 
        * Amgylcheddau Datblygu: NetBeans, IntelliJ IDEA, Eclipse ac ati. 
        * Fframweithiau: J2SE 8.0 (1.8) neu uwch (er enghraifft Java 17) 
    code: |
        ```java
                        
            // Set up input YAML file
            String filePath = "input.yaml";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render YAML file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "YAML Viewer Live Demo"
    content: |
        Gweld YAML ffeil ar hyn o bryd drwy ymweld â gwefan [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/yaml).
    lang: "cy"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Fformatau Ffeil Eraill Rendro a Gweld gan ddefnyddio Java"
    exclude: "YAML"
    content: |
        API gwyliwr dogfennau a delweddau aml-fformat ar gyfer Java. Gweld rhai o'r fformatau ffeil poblogaidd isod heb unrhyw wylwyr allanol.
    format: 
        # format loop 1
        - name: "Rendro DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Dogfen XML Agored" 

        # format loop 2
        - name: "Rendro CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "Ffeil CorelDRAW" 

        # format loop 3
        - name: "Rendro PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint Open XML Presentation" 

        # format loop 4
        - name: "Rendro XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Agor Taenlen XML" 

        # format loop 5
        - name: "Rendro DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "Lluniadu AutoCAD"

        # format loop 6
        - name: "Rendro XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "Ffeil XML"

        # format loop 7
        - name: "Rendro PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Dogfen Adobe Photoshop"

        # format loop 8
        - name: "Rendro ffeil Adobe Illustrator"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Gwaith Celf Adobe Illustrator"

        # format loop 9
        - name: "Rendro DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Dogfen Microsoft Word" 

        # format loop 10
        - name: "Rendro TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Ffeil Testun Plaen" 

        # format loop 11
        - name: "Rendro DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Arlunio Ffeil Fformat Cyfnewid"  
          
        # format loop 12
        - name: "Rendro VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "Ffeil vCard"  
              
        # format loop 13
        - name: "Rendro SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Graffeg Fector Graddadwy" 
          
        # format loop 14
        - name: "Rendro HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Ffeil Iaith Marcio Hyperdestun" 
          
        # format loop 15
        - name: "Rendro PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Ffeil Fformat Dogfen Gludadwy"
          
        # format loop 16
        - name: "Rendro JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "Delwedd JPEG"
          
        # format loop 17
        - name: "Rendro PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Graffeg Rhwydwaith Cludadwy" 
          
        # format loop 18
        - name: "Rendro EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "Neges E-bost" 
          
        # format loop 19
        - name: "Rendro RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Ffeil Fformat Testun Cyfoethog" 
          
        # format loop 20
        - name: "Rendro ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "Dogfen Testun OpenDocument" 
          
        # format loop 21
        - name: "Rendro CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Ffeil Gwerthoedd Wedi'u Gwahanu gan Goma" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
