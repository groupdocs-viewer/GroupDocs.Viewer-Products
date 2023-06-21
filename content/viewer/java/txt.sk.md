---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: sk

############################# Head #############################
head_title: "Java TXT Viewer API – Render & Display TXT v Java Apps"
head_description: "Zobraziť súbory TXT v aplikáciách Java, J2EE, J2SE. Podporuje prezeranie 170+ formátov dokumentov a obrázkov v režime HTML, PDF alebo obrázkov s pokročilými funkciami na správu možností zobrazenia dokumentov."

############################# Header ############################
title: "Vykresliť a zobraziť TXT v jazyku Java" 
description: "Natívne a vysokovýkonné rozhranie API prehliadača súborov TXT pre aplikácie založené na Java, J2EE a J2SE, ktoré podporuje širokú škálu ďalších funkcií na prispôsobenie vzhľadu formátu výstupného dokumentu." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Stiahnite si bezplatnú skúšobnú verziu"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "O aplikácii GroupDocs.Viewer for Java API" 
    content: |
        Umožnite svojim aplikáciám Java zobrazovať viac ako 170+ súborových formátov v HTML, PDF alebo obrázkových režimoch pomocou GroupDocs.Viewer pre Java API bez akéhokoľvek ďalšieho nainštalovaného softvéru; ako je Microsoft Office, Apache Open Office, Adobe Acrobat Reader atď. Vývojári môžu jednoducho prezerať všetky populárne obrázky a typy dokumentov vrátane Microsoft Office, OpenDocument, HTML, PDF, Archive, Diagrams, Photoshop, AutoCAD a formáty programovacích jazykov v rámci aplikácií Java s rýchle a najkvalitnejšie vykresľovanie.

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
              text: "Referencia API"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Príklady kódov"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Živé ukážky"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Stanovenie cien"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "Kroky na vykreslenie súboru TXT v Java" 
    content_left: |
        Pomocou [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/) môžete vykresliť TXT do HTML, JPEG, PNG alebo PDF v niekoľkých krokoch.

        * Pridajte [GroupDocs.Viewer for Java](https://releases.groupdocs.com/viewer/java/) ako závislosť k svojmu projektu. 
        * Vytvorte inštanciu triedy Viewer a načítajte súbor TXT s úplnou cestou. 
        * Nastavte možnosti na vykreslenie súboru TXT do formátu HTML, PNG, JPEG alebo PDF. 
        * Vyrenderujte súbor a skontrolujte výstup v aktuálnom adresári. 
        
    title_right: "Požiadavky na systém" 
    content_right: |
        GroupDocs.Viewer for Java API sú podporované na všetkých hlavných platformách a operačných systémoch. Pred spustením nižšie uvedeného kódu sa uistite, že máte vo svojom systéme nainštalované nasledujúce predpoklady.

        * Operačné systémy: Microsoft Windows, Linux, MacOS 
        * Vývojové prostredia: NetBeans, IntelliJ IDEA, Eclipse atď. 
        * Rámce: J2SE 8.0 (1.8) alebo vyššie (napríklad Java 17) 
    code: |
        ```java
                        
            // Set up input TXT file
            String filePath = "input.txt";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render TXT file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "Živá ukážka prehliadača TXT"
    content: |
        Ak chcete zobraziť súbor TXT, navštívte webovú stránku [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/txt).
    lang: "sk"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Ďalšie formáty súborov vykresľovanie a zobrazovanie pomocou Java"
    exclude: "TXT"
    content: |
        Viacformátové rozhranie API prehliadača dokumentov a obrázkov pre Java. Pozrite si niektoré z populárnych formátov súborov nižšie bez akýchkoľvek externých prehliadačov.
    format: 
        # format loop 1
        - name: "Render DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Otvoriť dokument XML" 

        # format loop 2
        - name: "Render CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "Súbor CorelDRAW" 

        # format loop 3
        - name: "Vykresliť PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint Open XML prezentácia" 

        # format loop 4
        - name: "Render XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Otvorená tabuľka XML v programe Microsoft Excel" 

        # format loop 5
        - name: "Render DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "Výkres AutoCAD"

        # format loop 6
        - name: "Render XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "XML súbor"

        # format loop 7
        - name: "Vykresliť PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Dokument Adobe Photoshop"

        # format loop 8
        - name: "Vykreslite súbor Adobe Illustrator"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Umelecké dielo Adobe Illustrator"

        # format loop 9
        - name: "Vykresliť DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Dokument Microsoft Word" 

        # format loop 10
        - name: "Vykresliť TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Súbor obyčajného textu" 

        # format loop 11
        - name: "Vykresliť DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Súbor formátu výmeny výkresov"  
          
        # format loop 12
        - name: "Vykresliť VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "Súbor vCard"  
              
        # format loop 13
        - name: "Render SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Škálovateľná vektorová grafika" 
          
        # format loop 14
        - name: "Vykresliť HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "Vykresliť PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Súbor vo formáte prenosného dokumentu"
          
        # format loop 16
        - name: "Vykresliť JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "Obrázok JPEG"
          
        # format loop 17
        - name: "Vykresliť PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Prenosná sieťová grafika" 
          
        # format loop 18
        - name: "Render EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "E-mailová správa" 
          
        # format loop 19
        - name: "Render RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Súbor RTF" 
          
        # format loop 20
        - name: "Vykresliť ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "Textový dokument OpenDocument" 
          
        # format loop 21
        - name: "Vykresliť CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Súbor hodnôt oddelených čiarkami" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
