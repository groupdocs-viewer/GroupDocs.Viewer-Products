---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: ro

############################# Head #############################
head_title: "Java RST Viewer API - Redare și afișare RST în aplicațiile Java"
head_description: "Vizualizați fișiere RST în aplicații Java, J2EE, J2SE. Acceptă vizualizarea a peste 170 de formate de documente și fișiere imagine în HTML, PDF sau în modul imagine cu funcții avansate pentru a gestiona opțiunile de vizualizare a documentelor."

############################# Header ############################
title: "Redați și vizualizați RST în Java" 
description: "API nativ și de înaltă performanță pentru vizualizarea fișierelor RST pentru aplicații bazate pe Java, J2EE și J2SE, care acceptă o gamă largă de caracteristici suplimentare pentru a personaliza aspectul formatului documentului de ieșire." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Descarcare varianta scurta de prezentare gratuita"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Despre GroupDocs.Viewer for Java API" 
    content: |
        Permiteți aplicațiilor dvs. Java să afișeze peste 170 de formate de fișiere în moduri HTML, PDF sau imagine utilizând GroupDocs.Viewer pentru API-urile Java fără niciun software suplimentar instalat; cum ar fi Microsoft Office, Apache Open Office, Adobe Acrobat Reader etc. Dezvoltatorii pot vizualiza cu ușurință toate imaginile și tipurile de documente populare, inclusiv Microsoft Office, OpenDocument, HTML, PDF, Archive, Diagrame, Photoshop, AutoCAD și formatele de limbaj de programare în cadrul aplicațiilor Java cu redare rapidă și de cea mai înaltă calitate.

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
              text: "Referință API"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Exemple de coduri"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Demo live"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Prețuri"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "Pași pentru redarea fișierului RST în Java" 
    content_left: |
        Cu [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/) puteți reda RST în HTML, JPEG, PNG sau PDF în câțiva pași.

        * Adăugați [GroupDocs.Viewer for Java](https://releases.groupdocs.com/viewer/java/) ca dependență pentru proiectul dvs. 
        * Creați o instanță a clasei Viewer și încărcați fișierul RST cu calea completă. 
        * Setați opțiunile de redare a fișierului RST în format HTML, PNG, JPEG sau PDF. 
        * Redați fișierul și verificați rezultatul în directorul curent. 
        
    title_right: "Cerințe de sistem" 
    content_right: |
        API-urile GroupDocs.Viewer pentru Java sunt acceptate pe toate platformele și sistemele de operare majore. Înainte de a executa codul de mai jos, vă rugăm să vă asigurați că aveți următoarele cerințe preliminare instalate pe sistemul dumneavoastră.

        * Sisteme de operare: Microsoft Windows, Linux, MacOS 
        * Medii de dezvoltare: NetBeans, IntelliJ IDEA, Eclipse etc. 
        * Framework: J2SE 8.0 (1.8) sau mai recent (de exemplu Java 17) 
    code: |
        ```java
                        
            // Set up input RST file
            String filePath = "input.rst";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render RST file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "RST Viewer Live Demo"
    content: |
        Vizualizați fișierul RST chiar acum, vizitând site-ul web [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/rst).
    lang: "ro"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Redarea și vizualizarea altor formate de fișiere folosind Java"
    exclude: "RST"
    content: |
        API de vizualizare a documentelor și imaginilor multiformat pentru Java. Vizualizați câteva dintre formatele de fișiere populare de mai jos, fără niciun vizualizator extern.
    format: 
        # format loop 1
        - name: "Redați DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Document Microsoft Word Open XML" 

        # format loop 2
        - name: "Redați CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "Fișierul CorelDRAW" 

        # format loop 3
        - name: "Redați PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "Prezentare PowerPoint Open XML" 

        # format loop 4
        - name: "Redați XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet" 

        # format loop 5
        - name: "Redați DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "Desen AutoCAD"

        # format loop 6
        - name: "Redați XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "Fișier XML"

        # format loop 7
        - name: "Redați PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Document Adobe Photoshop"

        # format loop 8
        - name: "Redați fișierul Adobe Illustrator"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Opera de artă Adobe Illustrator"

        # format loop 9
        - name: "Redați DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Document Microsoft Word" 

        # format loop 10
        - name: "Redați TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Fișier text simplu" 

        # format loop 11
        - name: "Redați DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Fișier în format Schimb de desene"  
          
        # format loop 12
        - name: "Redați VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "Fișier vCard"  
              
        # format loop 13
        - name: "Redați SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Grafic vectorial scalabil" 
          
        # format loop 14
        - name: "Redați HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Fișier limbaj de marcare hipertext" 
          
        # format loop 15
        - name: "Redați PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Fișier în format de document portabil"
          
        # format loop 16
        - name: "Redați JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "Imagine JPEG"
          
        # format loop 17
        - name: "Redați PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Grafică de rețea portabilă" 
          
        # format loop 18
        - name: "Redați EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "Mesaj e-mail" 
          
        # format loop 19
        - name: "Redați RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Fișier cu format text îmbogățit" 
          
        # format loop 20
        - name: "Reda ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "Document text OpenDocument" 
          
        # format loop 21
        - name: "Redați CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Fișier cu valori separate prin virgulă" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
