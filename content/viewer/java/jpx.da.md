---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: da

############################# Head #############################
head_title: "Java JPX Viewer API - Gengivelse og visning JPX i Java Apps"
head_description: "Se JPX filer i Java, J2EE, J2SE applikationer. Understøtter visning af mere end 170 dokument- og billedfilformater i HTML-, PDF- eller billedtilstand med avancerede funktioner til at administrere dokumentvisningsmuligheder."

############################# Header ############################
title: "Gengiv og vis JPX i Java" 
description: "Indbygget og højtydende JPX-filfremviser-API til Java-, J2EE- og J2SE-baserede applikationer, der understøtter en lang række yderligere funktioner til at tilpasse udseendet af outputdokumentformatet." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Download gratis prøveversion"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Om GroupDocs.Viewer til Java API" 
    content: |
        Aktiver dine Java-applikationer til at vise over 170 filformater i HTML-, PDF- eller billedtilstande ved hjælp af GroupDocs.Viewer til Java API'er uden yderligere software installeret; såsom Microsoft Office, Apache Open Office, Adobe Acrobat Reader osv. Udviklere kan nemt se alle populære billeder og dokumenttyper inklusive Microsoft Office, OpenDocument, HTML, PDF, Arkiv, Diagrammer, Photoshop, AutoCAD og programmeringssprogformater inde i Java-applikationerne med hurtig gengivelse af højeste kvalitet.

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
              text: "API-reference"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Kode eksempler"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Live demoer"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Prissætning"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "Trin til gengivelse af JPX-fil i Java" 
    content_left: |
        Med [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/) kan du gengive JPX til HTML, JPEG, PNG eller PDF i nogle få trin.

        * Tilføj [GroupDocs.Viewer til Java](https://releases.groupdocs.com/viewer/java/) som en afhængighed til dit projekt. 
        * Opret en forekomst af Viewer-klassen og indlæs JPX-filen med fuld sti. 
        * Indstil muligheder for at gengive filen JPX til HTML-, PNG-, JPEG- eller PDF-format. 
        * Gengiv filen og kontroller output i den aktuelle mappe. 
        
    title_right: "Systemkrav" 
    content_right: |
        GroupDocs.Viewer til Java API'er understøttes på alle større platforme og operativsystemer. Før du udfører koden nedenfor, skal du sørge for, at du har følgende forudsætninger installeret på dit system.

        * Operativsystemer: Microsoft Windows, Linux, MacOS 
        * Udviklingsmiljøer: NetBeans, IntelliJ IDEA, Eclipse osv. 
        * Rammer: J2SE 8.0 (1.8) eller nyere (for eksempel Java 17) 
    code: |
        ```java
                        
            // Set up input JPX file
            String filePath = "input.jpx";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render JPX file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "JPX Live-demo"
    content: |
        Se filen JPX lige nu ved at besøge webstedet [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/jpx).
    lang: "da"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Andre filformater Gengivelse og visning ved hjælp af Java"
    exclude: "JPX"
    content: |
        Multi-format dokumenter og billeder viewer API til Java. Se nogle af de populære filformater nedenfor uden eksterne seere.
    format: 
        # format loop 1
        - name: "Render DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Open XML-dokument" 

        # format loop 2
        - name: "Gengiv CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "CorelDRAW-fil" 

        # format loop 3
        - name: "Gengiv PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint Open XML-præsentation" 

        # format loop 4
        - name: "Gengiv XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Open XML-regneark" 

        # format loop 5
        - name: "Gengiv DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "AutoCAD tegning"

        # format loop 6
        - name: "Gengiv XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "XML-fil"

        # format loop 7
        - name: "Gengiv PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Adobe Photoshop-dokument"

        # format loop 8
        - name: "Gengiv Adobe Illustrator-fil"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Adobe Illustrator kunstværk"

        # format loop 9
        - name: "Gengiv DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Microsoft Word-dokument" 

        # format loop 10
        - name: "Gengiv TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Almindelig tekstfil" 

        # format loop 11
        - name: "Render DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Tegning af Exchange-formatfil"  
          
        # format loop 12
        - name: "Render VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "vCard-fil"  
              
        # format loop 13
        - name: "Gengiv SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Skalerbar vektorgrafik" 
          
        # format loop 14
        - name: "Gengiv HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "Gengiv PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Fil i bærbart dokumentformat"
          
        # format loop 16
        - name: "Gengiv JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "JPEG billede"
          
        # format loop 17
        - name: "Gengiv PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Bærbar netværksgrafik" 
          
        # format loop 18
        - name: "Gør EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "E-mail besked" 
          
        # format loop 19
        - name: "Gengiv RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Rich Text Format fil" 
          
        # format loop 20
        - name: "Render ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "OpenDocument tekstdokument" 
          
        # format loop 21
        - name: "Gengiv CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Kommaseparerede værdier fil" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
