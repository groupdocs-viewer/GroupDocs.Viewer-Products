---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: sk

############################# Head #############################
head_title: ".NET IFC Viewer API – čítanie, zobrazenie, vykreslenie v C# VB.NET"
head_description: "API prehliadača dokumentov .NET na čítanie, vykresľovanie a zobrazovanie IFC v akomkoľvek type aplikácií C#, ASP.NET, VB.NET a .NET Core."

############################# Header ############################
title: "IFC Prehliadač súborov pre aplikácie C# .NET" 
description: "API prehliadača dokumentov .NET na čítanie, vykresľovanie a zobrazovanie súboru IFC v akomkoľvek type aplikácií C#, ASP.NET, VB.NET a .NET Core. Zobrazte vykreslené súbory so skutočným formátovaním a rozložením v HTML5, PDF alebo ako obrázok pomocou niekoľkých riadkov kódu." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Stiahnite si bezplatnú skúšobnú verziu"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "O GroupDocs.Viewer pre .NET API" 
    content: |
        Začnite prezerať 190+ populárnych formátov dokumentov vo svojich .NET aplikáciách pomocou GroupDocs.Viewer for .NET API pridaním niekoľkých riadkov kódu. Vývojári môžu jednoducho zobraziť PDF, Word Processing, Excel Spreadsheet, Presentation, Visio, Project, Outlook a mnoho ďalších populárnych formátov dokumentov v HTML5, obrázkových alebo PDF režimoch. Vykresľovanie dokumentu je rýchle, identické s pôvodným zdrojovým súborom a nevyžaduje inštaláciu dodatočného softvéru ani iných externých knižníc.

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
    title_left: "Kroky na vykreslenie súboru IFC v C#" 
    content_left: |
        Pomocou [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/) môžete vykresliť IFC do HTML, JPEG, PNG alebo PDF v niekoľkých krokoch.

        * Nainštalujte si [GroupDocs.Viewer for .NET](https://www.nuget.org/packages/groupdocs.viewer) pomocou svojho obľúbeného správcu balíkov. 
        * Vytvorte inštanciu triedy Viewer a načítajte súbor IFC s úplnou cestou. 
        * Nastavte možnosti na vykreslenie súboru IFC do formátu HTML, PNG, JPEG alebo PDF. 
        * Vyrenderujte súbor a skontrolujte výstup v aktuálnom adresári. 
        
    title_right: "Požiadavky na systém" 
    content_right: |
        GroupDocs.Viewer for .NET API sú podporované na všetkých hlavných platformách a operačných systémoch. Pred spustením nižšie uvedeného kódu sa uistite, že máte vo svojom systéme nainštalované nasledujúce predpoklady.

        * Operačné systémy: Microsoft Windows, Linux, MacOS 
        * Vývojové prostredia: Microsoft Visual Studio, Visual Studio Code, .NET CLI 
        * Rámce: .NET Framework, .NET Standard, .NET Core, .NET 
    code: |
        ```cs
                        
            // Set up input IFC file
            string filePath = "input.ifc";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render IFC file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "Živá ukážka prehliadača IFC"
    content: |
        Ak chcete zobraziť súbor IFC, navštívte webovú stránku [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/ifc).
    lang: "sk"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Iné formáty súborov vykresľovanie a zobrazovanie pomocou C#"
    exclude: "IFC"
    content: |
        Viacformátové rozhranie API prehliadača dokumentov a obrázkov pre .NET. Pozrite si niektoré z populárnych formátov súborov nižšie bez akýchkoľvek externých prehliadačov.
    format: 
        # format loop 1
        - name: "Render DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word Otvoriť dokument XML" 

        # format loop 2
        - name: "Render CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "Súbor CorelDRAW" 

        # format loop 3
        - name: "Vykresliť PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint Open XML prezentácia" 

        # format loop 4
        - name: "Render XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Otvorená tabuľka XML v programe Microsoft Excel" 

        # format loop 5
        - name: "Render DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "Výkres AutoCAD"

        # format loop 6
        - name: "Render XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "XML súbor"

        # format loop 7
        - name: "Vykresliť PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Dokument Adobe Photoshop"

        # format loop 8
        - name: "Vykreslite súbor Adobe Illustrator"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Umelecké dielo Adobe Illustrator"

        # format loop 9
        - name: "Vykresliť DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Dokument Microsoft Word" 

        # format loop 10
        - name: "Vykresliť TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Súbor obyčajného textu" 

        # format loop 11
        - name: "Vykresliť DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Súbor formátu výmeny výkresov"  
          
        # format loop 12
        - name: "Vykresliť VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "Súbor vCard"  
              
        # format loop 13
        - name: "Render SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Škálovateľná vektorová grafika" 
          
        # format loop 14
        - name: "Vykresliť HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "Vykresliť PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Súbor vo formáte prenosného dokumentu"
          
        # format loop 16
        - name: "Vykresliť JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "Obrázok JPEG"
          
        # format loop 17
        - name: "Vykresliť PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Prenosná sieťová grafika" 
          
        # format loop 18
        - name: "Render EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "E-mailová správa" 
          
        # format loop 19
        - name: "Render RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Súbor RTF" 
          
        # format loop 20
        - name: "Vykresliť ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "Textový dokument OpenDocument" 
          
        # format loop 21
        - name: "Vykresliť CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Súbor hodnôt oddelených čiarkami" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
