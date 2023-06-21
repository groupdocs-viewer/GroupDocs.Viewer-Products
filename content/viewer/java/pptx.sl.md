---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: sl

############################# Head #############################
head_title: "Java PPTX Viewer API - upodabljanje in prikaz PPTX v aplikacijah Java"
head_description: "Oglejte si datoteke PPTX v aplikacijah Java, J2EE, J2SE. Podpira ogled več kot 170 formatov dokumentov in slikovnih datotek v HTML, PDF ali slikovnem načinu z naprednimi funkcijami za upravljanje možnosti ogledovanja dokumentov."

############################# Header ############################
title: "Upodabljanje in ogled PPTX v Javi" 
description: "Izvorni in visoko zmogljiv API pregledovalnika datotek PPTX za aplikacije, ki temeljijo na Javi, J2EE in J2SE, podpira širok nabor dodatnih funkcij za prilagajanje videza oblike izhodnega dokumenta." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Prenesite brezplačno preskusno različico"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "O GroupDocs.Viewer for Java API" 
    content: |
        Omogočite, da vaše aplikacije Java prikažejo več kot 170+ formatov datotek v HTML, PDF ali slikovnih načinih z API-ji GroupDocs.Viewer za Java brez nameščene dodatne programske opreme; kot so Microsoft Office, Apache Open Office, Adobe Acrobat Reader itd. Razvijalci si lahko preprosto ogledajo vse priljubljene slike in vrste dokumentov, vključno z Microsoft Office, OpenDocument, HTML, PDF, arhiv, diagrami, Photoshop, AutoCAD in formati programskih jezikov v aplikacijah Java z hitro in kakovostno upodabljanje.

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
              text: "API Reference"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Primeri kod"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Predstavitve v živo"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Cenitev"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "Koraki za upodabljanje datoteke PPTX v Java" 
    content_left: |
        Z [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/) lahko v nekaj korakih upodobite PPTX v HTML, JPEG, PNG ali PDF.

        * Dodajte [GroupDocs.Viewer for Java](https://releases.groupdocs.com/viewer/java/) kot odvisnost od svojega projekta. 
        * Ustvarite primerek razreda Viewer in naložite datoteko PPTX s celotno potjo. 
        * Nastavite možnosti za upodabljanje datoteke PPTX v formatu HTML, PNG, JPEG ali PDF. 
        * Upodobi datoteko in preveri izpis v trenutnem imeniku. 
        
    title_right: "Sistemske zahteve" 
    content_right: |
        API-ji GroupDocs.Viewer za Java so podprti na vseh večjih platformah in operacijskih sistemih. Preden izvedete spodnjo kodo, se prepričajte, da imate v sistemu nameščene naslednje predpogoje.

        * Operacijski sistemi: Microsoft Windows, Linux, MacOS 
        * Razvojna okolja: NetBeans, IntelliJ IDEA, Eclipse itd. 
        * Ogrodja: J2SE 8.0 (1.8) ali novejši (na primer Java 17) 
    code: |
        ```java
                        
            // Set up input PPTX file
            String filePath = "input.pptx";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render PPTX file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "PPTX Viewer Live Demo"
    content: |
        Takoj si oglejte datoteko PPTX tako, da obiščete spletno mesto [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/pptx).
    lang: "sl"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Upodabljanje in ogled drugih formatov datotek z Java"
    exclude: "PPTX"
    content: |
        API pregledovalnika dokumentov in slik za več formatov za Javo. Spodaj si oglejte nekaj priljubljenih formatov datotek brez zunanjih pregledovalnikov.
    format: 
        # format loop 1
        - name: "Upodobi DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Dokument Microsoft Word Open XML" 

        # format loop 2
        - name: "Upodabljanje CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "Datoteka CorelDRAW" 

        # format loop 3
        - name: "Upodabljanje PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "Predstavitev PowerPoint Open XML" 

        # format loop 4
        - name: "Upodabljanje XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Preglednica Microsoft Excel Open XML" 

        # format loop 5
        - name: "Upodabljanje DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "Risanje AutoCAD"

        # format loop 6
        - name: "Upodabljanje XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "Datoteka XML"

        # format loop 7
        - name: "Upodabljanje PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Adobe Photoshop dokument"

        # format loop 8
        - name: "Upodobi datoteko Adobe Illustrator"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Umetniško delo Adobe Illustrator"

        # format loop 9
        - name: "Upodobi DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Dokument Microsoft Word" 

        # format loop 10
        - name: "Upodabljanje TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Datoteka z navadnim besedilom" 

        # format loop 11
        - name: "Upodabljanje DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Datoteka izmenjave risb"  
          
        # format loop 12
        - name: "Upodabljanje VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "Datoteka vCard"  
              
        # format loop 13
        - name: "Upodabljanje SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Razširljiva vektorska grafika" 
          
        # format loop 14
        - name: "Upodobi HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Jezikovna datoteka za označevanje hiperteksta" 
          
        # format loop 15
        - name: "Upodobi PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Prenosna datoteka formata dokumenta"
          
        # format loop 16
        - name: "Upodabljanje JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "Slika JPEG"
          
        # format loop 17
        - name: "Upodabljanje PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Prenosna omrežna grafika" 
          
        # format loop 18
        - name: "Upodabljanje EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "E-poštno sporočilo" 
          
        # format loop 19
        - name: "Upodabljanje RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Datoteka z obogatenim besedilom" 
          
        # format loop 20
        - name: "Upodabljanje ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "Besedilni dokument OpenDocument" 
          
        # format loop 21
        - name: "Upodabljanje CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Datoteka z vrednostmi, ločenimi z vejicami" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
