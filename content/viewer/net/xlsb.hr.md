---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: hr

############################# Head #############################
head_title: ".NET XLSB Viewer API - čitanje, gledanje, prikaz u C# VB.NET"
head_description: "API preglednika .NET dokumenata za čitanje, renderiranje i prikaz XLSB u bilo kojoj vrsti C#, ASP.NET, VB.NET i .NET Core aplikacija."

############################# Header ############################
title: "XLSB Preglednik datoteka za C# .NET aplikacije" 
description: "API preglednika .NET dokumenata za čitanje, prikaz i prikaz XLSB datoteke u bilo kojoj vrsti C#, ASP.NET, VB.NET i .NET Core aplikacija. Pregledajte prikazane datoteke s pravim oblikovanjem i izgledom u HTML5, PDF-u ili kao sliku pomoću nekoliko redaka koda." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Preuzmite besplatnu probnu verziju"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "O GroupDocs.Viewer za .NET API" 
    content: |
        Započnite pregledavati 190+ popularnih formata dokumenata u svojim .NET aplikacijama koristeći GroupDocs.Viewer za .NET API-je dodavanjem nekoliko redaka koda. Programeri mogu jednostavno prikazati PDF, Word Processing, Excel proračunsku tablicu, Presentation, Visio, Project, Outlook i mnoge druge popularne formate dokumenata u HTML5, slikovnom ili PDF načinu rada. Renderiranje dokumenta je brzo, identično originalnoj izvornoj datoteci i ne zahtijeva instaliranje dodatnog softvera ili bilo koje druge vanjske biblioteke.

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
    title_left: "Koraci za prikaz XLSB datoteke u C#" 
    content_left: |
        Pomoću [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/) možete prikazati XLSB u HTML, JPEG, PNG ili PDF u nekoliko koraka.

        * Instalirajte [GroupDocs.Viewer za .NET](https://www.nuget.org/packages/groupdocs.viewer) koristeći svoj omiljeni upravitelj paketa. 
        * Napravite instancu klase Viewer i učitajte datoteku XLSB s punim putem. 
        * Postavite opcije za prikaz datoteke XLSB u HTML, PNG, JPEG ili PDF formatu. 
        * Renderirajte datoteku i provjerite izlaz u trenutnom direktoriju. 
        
    title_right: "Zahtjevi sustava" 
    content_right: |
        API-ji GroupDocs.Viewer za .NET podržani su na svim glavnim platformama i operativnim sustavima. Prije izvršavanja koda u nastavku, provjerite imate li sljedeće preduvjete instalirane na vašem sustavu.

        * Operativni sustavi: Microsoft Windows, Linux, MacOS 
        * Razvojna okruženja: Microsoft Visual Studio, Visual Studio Code, .NET CLI 
        * Okviri: .NET Framework, .NET Standard, .NET Core, .NET 
    code: |
        ```cs
                        
            // Set up input XLSB file
            string filePath = "input.xlsb";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render XLSB file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "XLSB Demo gledatelja uživo"
    content: |
        Pogledajte XLSB datoteku upravo sada tako da posjetite [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/xlsb) web mjesto.
    lang: "hr"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Renderiranje i gledanje drugih formata datoteka pomoću C#"
    exclude: "XLSB"
    content: |
        API za pregledavanje dokumenata i slika u više formata za .NET. U nastavku pogledajte neke od popularnih formata datoteka bez vanjskih preglednika.
    format: 
        # format loop 1
        - name: "Renderirajte DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word Open XML dokument" 

        # format loop 2
        - name: "Renderiraj CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "CorelDRAW datoteka" 

        # format loop 3
        - name: "Renderirati PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint Open XML prezentacija" 

        # format loop 4
        - name: "Render XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Open XML proračunska tablica" 

        # format loop 5
        - name: "Render DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "AutoCAD Crtanje"

        # format loop 6
        - name: "Prikaz XML-a"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "XML datoteka"

        # format loop 7
        - name: "Renderirajte PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Adobe Photoshop dokument"

        # format loop 8
        - name: "Renderirajte Adobe Illustrator datoteku"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Adobe Illustrator umjetničko djelo"

        # format loop 9
        - name: "Renderirati DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Microsoft Word dokument" 

        # format loop 10
        - name: "Renderiraj TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Obična tekstualna datoteka" 

        # format loop 11
        - name: "Render DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Datoteka formata razmjene crteža"  
          
        # format loop 12
        - name: "Renderiraj VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "vCard datoteka"  
              
        # format loop 13
        - name: "Renderiraj SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Skalabilna vektorska grafika" 
          
        # format loop 14
        - name: "Renderiraj HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Jezična datoteka za označavanje hiperteksta" 
          
        # format loop 15
        - name: "Renderiraj PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Datoteka prijenosnog formata dokumenta"
          
        # format loop 16
        - name: "Renderiraj JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "JPEG slika"
          
        # format loop 17
        - name: "Renderiraj PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Prijenosna mrežna grafika" 
          
        # format loop 18
        - name: "Renderiraj EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "E-mail poruka" 
          
        # format loop 19
        - name: "Renderiraj RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Datoteka obogaćenog teksta" 
          
        # format loop 20
        - name: "Renderiraj ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "OpenDocument tekstualni dokument" 
          
        # format loop 21
        - name: "Renderiraj CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Datoteka s vrijednostima odvojenim zarezima" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
