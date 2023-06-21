---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: cs

############################# Head #############################
head_title: ".NET TARXZ Viewer API – čtení, prohlížení, vykreslování v C# VB.NET"
head_description: "API prohlížeče dokumentů .NET pro čtení, vykreslování a zobrazování TARXZ v jakémkoli typu aplikací C#, ASP.NET, VB.NET a .NET Core."

############################# Header ############################
title: "TARXZ Prohlížeč souborů pro aplikace C# .NET" 
description: "API prohlížeče dokumentů .NET pro čtení, vykreslování a zobrazení souboru TARXZ v jakémkoli typu aplikací C#, ASP.NET, VB.NET a .NET Core. Zobrazte vykreslené soubory se skutečným formátováním a rozložením v HTML5, PDF nebo jako obrázek pomocí několika řádků kódu." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Stáhněte si zkušební verzi zdarma"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "O GroupDocs.Viewer for .NET API" 
    content: |
        Začněte prohlížet 190+ populárních formátů dokumentů ve svých aplikacích .NET pomocí rozhraní API GroupDocs.Viewer for .NET přidáním několika řádků kódu. Vývojáři mohou snadno zobrazit PDF, textový editor, tabulku Excel, prezentace, Visio, Project, Outlook a mnoho dalších oblíbených formátů dokumentů v HTML5, obrázkových nebo PDF režimech. Vykreslování dokumentu je rychlé, identické s původním zdrojovým souborem a nevyžaduje instalaci dalšího softwaru ani jiných externích knihoven.

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
    title_left: "Kroky k vykreslení souboru TARXZ v C#" 
    content_left: |
        Pomocí [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/) můžete vykreslit TARXZ do HTML, JPEG, PNG nebo PDF v několika krocích.

        * Nainstalujte [GroupDocs.Viewer for .NET](https://www.nuget.org/packages/groupdocs.viewer) pomocí svého oblíbeného správce balíčků. 
        * Vytvořte instanci třídy Viewer a načtěte soubor TARXZ s úplnou cestou. 
        * Nastavte možnosti pro vykreslení souboru TARXZ do formátu HTML, PNG, JPEG nebo PDF. 
        * Renderujte soubor a zkontrolujte výstup v aktuálním adresáři. 
        
    title_right: "Požadavky na systém" 
    content_right: |
        GroupDocs.Viewer for .NET API jsou podporována na všech hlavních platformách a operačních systémech. Před spuštěním níže uvedeného kódu se prosím ujistěte, že máte na svém systému nainstalovány následující předpoklady.

        * Operační systémy: Microsoft Windows, Linux, MacOS 
        * Vývojová prostředí: Microsoft Visual Studio, Visual Studio Code, .NET CLI 
        * Frameworky: .NET Framework, .NET Standard, .NET Core, .NET 
    code: |
        ```cs
                        
            // Set up input TARXZ file
            string filePath = "input.tarxz";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render TARXZ file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "Živá ukázka prohlížeče TARXZ"
    content: |
        Prohlédněte si soubor TARXZ právě teď na webu [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/tarxz).
    lang: "cs"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Další formáty souborů Vykreslování a zobrazení pomocí C#"
    exclude: "TARXZ"
    content: |
        Víceformátové rozhraní API prohlížeče dokumentů a obrázků pro .NET. Prohlédněte si některé z oblíbených formátů souborů níže bez jakýchkoli externích prohlížečů.
    format: 
        # format loop 1
        - name: "Vykreslit DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word Otevřete dokument XML" 

        # format loop 2
        - name: "Vykreslit CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "Soubor CorelDRAW" 

        # format loop 3
        - name: "Vykreslit PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint Open XML prezentace" 

        # format loop 4
        - name: "Render XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Otevřít tabulku XML" 

        # format loop 5
        - name: "Vykreslit DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "Výkres AutoCAD"

        # format loop 6
        - name: "Vykreslit XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "Soubor XML"

        # format loop 7
        - name: "Vykreslit PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Dokument Adobe Photoshop"

        # format loop 8
        - name: "Vykreslit soubor Adobe Illustrator"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Umělecké dílo Adobe Illustrator"

        # format loop 9
        - name: "Vykreslit DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Dokument Microsoft Word" 

        # format loop 10
        - name: "Vykreslit TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Soubor prostého textu" 

        # format loop 11
        - name: "Vykreslit DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Soubor formátu výměny výkresů"  
          
        # format loop 12
        - name: "Vykreslit VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "Soubor vCard"  
              
        # format loop 13
        - name: "Vykreslit SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Škálovatelná vektorová grafika" 
          
        # format loop 14
        - name: "Vykreslit HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "Vykreslit PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Soubor ve formátu přenosného dokumentu"
          
        # format loop 16
        - name: "Vykreslit JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "Obrázek JPEG"
          
        # format loop 17
        - name: "Vykreslit PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Přenosná síťová grafika" 
          
        # format loop 18
        - name: "Vykreslit EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "E-mailová zpráva" 
          
        # format loop 19
        - name: "Render RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Soubor RTF" 
          
        # format loop 20
        - name: "Vykreslit ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "Textový dokument OpenDocument" 
          
        # format loop 21
        - name: "Vykreslit CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Soubor hodnot oddělených čárkami" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
