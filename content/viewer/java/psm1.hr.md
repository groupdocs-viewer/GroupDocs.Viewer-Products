---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: hr

############################# Head #############################
head_title: "Java PSM1 Viewer API - Render & Display PSM1 u Java aplikacijama"
head_description: "Pogledajte PSM1 datoteke u Java, J2EE, J2SE aplikacijama. Podržava pregledavanje više od 170 formata dokumenata i slikovnih datoteka u HTML, PDF ili slikovnom načinu s naprednim značajkama za upravljanje opcijama pregledavanja dokumenata."

############################# Header ############################
title: "Renderirajte i pogledajte PSM1 u Javi" 
description: "Nativni i visokoučinkoviti PSM1 API za preglednik datoteka za aplikacije temeljene na Javi, J2EE i J2SE, podržavajući širok raspon dodatnih značajki za prilagodbu izgleda formata izlaznog dokumenta." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Preuzmite besplatnu probnu verziju"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "O GroupDocs.Viewer za Java API" 
    content: |
        Omogućite svojim Java aplikacijama prikaz preko 170+ formata datoteka u HTML, PDF ili slikovnim načinima koristeći GroupDocs.Viewer za Java API bez instaliranja dodatnog softvera; kao što su Microsoft Office, Apache Open Office, Adobe Acrobat Reader itd. Programeri mogu lako pregledavati sve popularne slike i vrste dokumenata uključujući Microsoft Office, OpenDocument, HTML, PDF, arhivu, dijagrame, Photoshop, AutoCAD i formate programskih jezika unutar Java aplikacija s brzo i najkvalitetnije renderiranje.

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
              text: "API Referenca"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Primjeri koda"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Demo snimke uživo"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Cijene"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "Koraci za prikaz PSM1 datoteke u Java" 
    content_left: |
        Pomoću [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/) možete prikazati PSM1 u HTML, JPEG, PNG ili PDF u nekoliko koraka.

        * Dodajte [GroupDocs.Viewer za Javu](https://releases.groupdocs.com/viewer/java/) kao ovisnost svom projektu. 
        * Napravite instancu klase Viewer i učitajte datoteku PSM1 s punim putem. 
        * Postavite opcije za prikaz datoteke PSM1 u HTML, PNG, JPEG ili PDF formatu. 
        * Renderirajte datoteku i provjerite izlaz u trenutnom direktoriju. 
        
    title_right: "Zahtjevi sustava" 
    content_right: |
        API-ji GroupDocs.Viewer za Java podržani su na svim glavnim platformama i operativnim sustavima. Prije izvršavanja koda u nastavku, provjerite imate li sljedeće preduvjete instalirane na vašem sustavu.

        * Operativni sustavi: Microsoft Windows, Linux, MacOS 
        * Razvojna okruženja: NetBeans, IntelliJ IDEA, Eclipse itd. 
        * Okviri: J2SE 8.0 (1.8) ili noviji (na primjer Java 17) 
    code: |
        ```java
                        
            // Set up input PSM1 file
            String filePath = "input.psm1";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render PSM1 file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "PSM1 Demo gledatelja uživo"
    content: |
        Pogledajte PSM1 datoteku upravo sada tako da posjetite [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/psm1) web mjesto.
    lang: "hr"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Renderiranje i pregledavanje drugih formata datoteka pomoću Java"
    exclude: "PSM1"
    content: |
        API za pregledavanje dokumenata i slika u više formata za Javu. U nastavku pogledajte neke od popularnih formata datoteka bez vanjskih preglednika.
    format: 
        # format loop 1
        - name: "Renderirajte DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Open XML dokument" 

        # format loop 2
        - name: "Renderiraj CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "CorelDRAW datoteka" 

        # format loop 3
        - name: "Renderirati PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint Open XML prezentacija" 

        # format loop 4
        - name: "Render XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Open XML proračunska tablica" 

        # format loop 5
        - name: "Render DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "AutoCAD Crtanje"

        # format loop 6
        - name: "Prikaz XML-a"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "XML datoteka"

        # format loop 7
        - name: "Renderirajte PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Adobe Photoshop dokument"

        # format loop 8
        - name: "Renderirajte Adobe Illustrator datoteku"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Adobe Illustrator umjetničko djelo"

        # format loop 9
        - name: "Renderirati DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Microsoft Word dokument" 

        # format loop 10
        - name: "Renderiraj TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Obična tekstualna datoteka" 

        # format loop 11
        - name: "Render DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Datoteka formata razmjene crteža"  
          
        # format loop 12
        - name: "Renderiraj VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "vCard datoteka"  
              
        # format loop 13
        - name: "Renderiraj SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Skalabilna vektorska grafika" 
          
        # format loop 14
        - name: "Renderiraj HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Jezična datoteka za označavanje hiperteksta" 
          
        # format loop 15
        - name: "Renderiraj PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Datoteka prijenosnog formata dokumenta"
          
        # format loop 16
        - name: "Renderiraj JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "JPEG slika"
          
        # format loop 17
        - name: "Renderiraj PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Prijenosna mrežna grafika" 
          
        # format loop 18
        - name: "Renderiraj EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "E-mail poruka" 
          
        # format loop 19
        - name: "Renderiraj RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Datoteka obogaćenog teksta" 
          
        # format loop 20
        - name: "Renderiraj ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "OpenDocument tekstualni dokument" 
          
        # format loop 21
        - name: "Renderiraj CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Datoteka s vrijednostima odvojenim zarezima" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---