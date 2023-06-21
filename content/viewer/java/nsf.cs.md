---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: cs

############################# Head #############################
head_title: "Java NSF Viewer API – Render & Display NSF v Java Apps"
head_description: "Zobrazit soubory NSF v aplikacích Java, J2EE, J2SE. Podporuje zobrazení více než 170 formátů dokumentů a obrázků v režimu HTML, PDF nebo obrázků s pokročilými funkcemi pro správu možností zobrazení dokumentů."

############################# Header ############################
title: "Vykreslit a zobrazit NSF v Javě" 
description: "Nativní a vysoce výkonné rozhraní API prohlížeče souborů NSF pro aplikace založené na Javě, J2EE a J2SE, které podporuje širokou škálu dalších funkcí pro přizpůsobení vzhledu výstupního formátu dokumentu." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Stáhněte si zkušební verzi zdarma"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "O aplikaci GroupDocs.Viewer for Java API" 
    content: |
        Umožněte svým aplikacím Java zobrazovat více než 170 formátů souborů v režimech HTML, PDF nebo obrázků pomocí rozhraní GroupDocs.Viewer for Java API bez instalovaného dalšího softwaru; jako je Microsoft Office, Apache Open Office, Adobe Acrobat Reader atd. Vývojáři mohou snadno prohlížet všechny oblíbené obrázky a typy dokumentů včetně Microsoft Office, OpenDocument, HTML, PDF, Archive, Diagrams, Photoshop, AutoCAD a formáty programovacích jazyků uvnitř aplikací Java s rychlé a kvalitní vykreslování.

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
              text: "Reference API"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Příklady kódu"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Živá ukázka"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Ceny"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "Kroky k vykreslení souboru NSF v Java" 
    content_left: |
        Pomocí [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/) můžete vykreslit NSF do HTML, JPEG, PNG nebo PDF v několika krocích.

        * Přidejte [GroupDocs.Viewer for Java](https://releases.groupdocs.com/viewer/java/) jako závislost svého projektu. 
        * Vytvořte instanci třídy Viewer a načtěte soubor NSF s úplnou cestou. 
        * Nastavte možnosti pro vykreslení souboru NSF do formátu HTML, PNG, JPEG nebo PDF. 
        * Renderujte soubor a zkontrolujte výstup v aktuálním adresáři. 
        
    title_right: "Požadavky na systém" 
    content_right: |
        GroupDocs.Viewer for Java API jsou podporována na všech hlavních platformách a operačních systémech. Před spuštěním níže uvedeného kódu se prosím ujistěte, že máte na svém systému nainstalovány následující předpoklady.

        * Operační systémy: Microsoft Windows, Linux, MacOS 
        * Vývojová prostředí: NetBeans, IntelliJ IDEA, Eclipse atd. 
        * Rámce: J2SE 8.0 (1.8) nebo vyšší (například Java 17) 
    code: |
        ```java
                        
            // Set up input NSF file
            String filePath = "input.nsf";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render NSF file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "Živá ukázka prohlížeče NSF"
    content: |
        Prohlédněte si soubor NSF právě teď na webu [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/nsf).
    lang: "cs"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Další formáty souborů Vykreslování a zobrazení pomocí Java"
    exclude: "NSF"
    content: |
        Víceformátové rozhraní API prohlížeče dokumentů a obrázků pro Javu. Prohlédněte si některé z oblíbených formátů souborů níže bez jakýchkoli externích prohlížečů.
    format: 
        # format loop 1
        - name: "Vykreslit DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Otevřete dokument XML" 

        # format loop 2
        - name: "Vykreslit CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "Soubor CorelDRAW" 

        # format loop 3
        - name: "Vykreslit PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint Open XML prezentace" 

        # format loop 4
        - name: "Render XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Otevřít tabulku XML" 

        # format loop 5
        - name: "Vykreslit DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "Výkres AutoCAD"

        # format loop 6
        - name: "Vykreslit XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "Soubor XML"

        # format loop 7
        - name: "Vykreslit PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Dokument Adobe Photoshop"

        # format loop 8
        - name: "Vykreslit soubor Adobe Illustrator"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Umělecké dílo Adobe Illustrator"

        # format loop 9
        - name: "Vykreslit DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Dokument Microsoft Word" 

        # format loop 10
        - name: "Vykreslit TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Soubor prostého textu" 

        # format loop 11
        - name: "Vykreslit DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Soubor formátu výměny výkresů"  
          
        # format loop 12
        - name: "Vykreslit VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "Soubor vCard"  
              
        # format loop 13
        - name: "Vykreslit SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Škálovatelná vektorová grafika" 
          
        # format loop 14
        - name: "Vykreslit HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "Vykreslit PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Soubor ve formátu přenosného dokumentu"
          
        # format loop 16
        - name: "Vykreslit JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "Obrázek JPEG"
          
        # format loop 17
        - name: "Vykreslit PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Přenosná síťová grafika" 
          
        # format loop 18
        - name: "Vykreslit EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "E-mailová zpráva" 
          
        # format loop 19
        - name: "Render RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Soubor RTF" 
          
        # format loop 20
        - name: "Vykreslit ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "Textový dokument OpenDocument" 
          
        # format loop 21
        - name: "Vykreslit CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Soubor hodnot oddělených čárkami" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
