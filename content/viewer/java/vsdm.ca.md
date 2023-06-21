---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: ca

############################# Head #############################
head_title: "API de visualització de Java VSDM: renderitza i mostra VSDM a les aplicacions de Java"
head_description: "Veure fitxers VSDM en aplicacions Java, J2EE, J2SE. Admet la visualització de més de 170 formats de documents i fitxers d'imatge en mode HTML, PDF o imatge amb funcions avançades per gestionar les opcions de visualització de documents."

############################# Header ############################
title: "Renderitza i visualitza VSDM a Java" 
description: "API de visualització de fitxers VSDM nativa i d'alt rendiment per a aplicacions basades en Java, J2EE i J2SE, que admet una àmplia gamma de funcions addicionals per personalitzar l'aparença del format del document de sortida." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Baixeu la prova gratuïta"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Quant a l'API de GroupDocs.Viewer per a Java" 
    content: |
        Habiliteu les vostres aplicacions Java per mostrar més de 170 formats de fitxer en modes HTML, PDF o imatge mitjançant GroupDocs.Viewer per a les API Java sense cap programari addicional instal·lat; com ara Microsoft Office, Apache Open Office, Adobe Acrobat Reader, etc. Els desenvolupadors poden veure fàcilment totes les imatges i tipus de documents populars, com ara Microsoft Office, OpenDocument, HTML, PDF, Archive, Diagrams, Photoshop, AutoCAD i formats de llenguatge de programació dins de les aplicacions Java amb renderització ràpida i de màxima qualitat.

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
              text: "Referència de l'API"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Exemples de codi"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Demostracions en directe"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Preus"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "Passos per renderitzar el fitxer VSDM a Java" 
    content_left: |
        Amb [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/) podeu renderitzar VSDM a HTML, JPEG, PNG o PDF en uns quants passos.

        * Afegiu [GroupDocs.Viewer per Java](https://releases.groupdocs.com/viewer/java/) com a dependència al vostre projecte. 
        * Creeu una instància de la classe Viewer i carregueu el fitxer VSDM amb el camí complet. 
        * Estableix les opcions per renderitzar el fitxer VSDM en format HTML, PNG, JPEG o PDF. 
        * Renderitzar el fitxer i comprovar la sortida al directori actual. 
        
    title_right: "Requisits del sistema" 
    content_right: |
        Les API de GroupDocs.Viewer per a Java són compatibles amb totes les plataformes i sistemes operatius principals. Abans d'executar el codi següent, assegureu-vos que teniu els següents requisits previs instal·lats al vostre sistema.

        * Sistemes operatius: Microsoft Windows, Linux, MacOS 
        * Entorns de desenvolupament: NetBeans, IntelliJ IDEA, Eclipse, etc. 
        * Frameworks: J2SE 8.0 (1.8) o superior (per exemple Java 17) 
    code: |
        ```java
                        
            // Set up input VSDM file
            String filePath = "input.vsdm";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render VSDM file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "VSDM Visualitzador de demostració en directe"
    content: |
        Consulteu el fitxer VSDM ara mateix visitant el lloc web [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/vsdm).
    lang: "ca"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Renderització i visualització d'altres formats de fitxer amb Java"
    exclude: "VSDM"
    content: |
        API de visualització de documents i imatges multiformat per a Java. Vegeu alguns dels formats de fitxer populars a continuació sense cap visor extern.
    format: 
        # format loop 1
        - name: "Renderitza DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Document XML obert de Microsoft Word" 

        # format loop 2
        - name: "Renderitza CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "Fitxer CorelDRAW" 

        # format loop 3
        - name: "Renderitza PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "Presentació de PowerPoint Open XML" 

        # format loop 4
        - name: "Renderitza XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Full de càlcul XML obert de Microsoft Excel" 

        # format loop 5
        - name: "Renderitza DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "Dibuix d'AutoCAD"

        # format loop 6
        - name: "Renderitza XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "Fitxer XML"

        # format loop 7
        - name: "Renderitza PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Document d'Adobe Photoshop"

        # format loop 8
        - name: "Renderitza el fitxer Adobe Illustrator"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Il·lustració d'Adobe Illustrator"

        # format loop 9
        - name: "Renderitza DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Document de Microsoft Word" 

        # format loop 10
        - name: "Renderitza TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Fitxer de text senzill" 

        # format loop 11
        - name: "Renderitza DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Fitxer de format d'intercanvi de dibuixos"  
          
        # format loop 12
        - name: "Renderitza VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "Fitxer vCard"  
              
        # format loop 13
        - name: "Renderitza SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Gràfic vectorial escalable" 
          
        # format loop 14
        - name: "Renderitza HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Fitxer de llenguatge de marques d'hipertext" 
          
        # format loop 15
        - name: "Renderitza PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Fitxer de format de document portàtil"
          
        # format loop 16
        - name: "Renderitza JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "Imatge JPEG"
          
        # format loop 17
        - name: "Renderitza PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Gràfic de xarxa portàtil" 
          
        # format loop 18
        - name: "Renderitza EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "Missatge de correu electrònic" 
          
        # format loop 19
        - name: "Renderitza RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Fitxer de format de text enriquit" 
          
        # format loop 20
        - name: "Renderitza ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "Document de text OpenDocument" 
          
        # format loop 21
        - name: "Renderitza CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Fitxer de valors separats per comes" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
