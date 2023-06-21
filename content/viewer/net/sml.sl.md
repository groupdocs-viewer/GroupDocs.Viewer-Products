---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: sl

############################# Head #############################
head_title: ".NET SML Viewer API - branje, ogled, upodabljanje v C# VB.NET"
head_description: "API pregledovalnika dokumentov .NET za branje, upodabljanje in prikaz SML v kateri koli vrsti aplikacij C#, ASP.NET, VB.NET in .NET Core."

############################# Header ############################
title: "SML Pregledovalnik datotek za aplikacije C# .NET" 
description: "API pregledovalnika dokumentov .NET za branje, upodabljanje in prikaz datoteke SML v kateri koli vrsti aplikacij C#, ASP.NET, VB.NET in .NET Core. Oglejte si upodobljene datoteke s pravim oblikovanjem in postavitvijo v HTML5, PDF ali kot sliko z nekaj vrsticami kode." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Prenesite brezplačno preskusno različico"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "O GroupDocs.Viewer za .NET API" 
    content: |
        Začnite si ogledovati več kot 190 priljubljenih formatov dokumentov v svojih aplikacijah .NET z API-ji GroupDocs.Viewer za .NET, tako da dodate nekaj vrstic kode. Razvijalci lahko preprosto prikažejo PDF, Word Processing, Excel Spreadsheet, Presentation, Visio, Project, Outlook in številne druge priljubljene formate dokumentov v HTML5, slikovnih ali PDF načinih. Upodabljanje dokumenta je hitro, identično izvirni izvorni datoteki in ne zahteva nameščanja dodatne programske opreme ali drugih zunanjih knjižnic.

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
    title_left: "Koraki za upodobitev datoteke SML v C#" 
    content_left: |
        Z [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/) lahko v nekaj korakih upodobite SML v HTML, JPEG, PNG ali PDF.

        * Namestite [GroupDocs.Viewer za .NET](https://www.nuget.org/packages/groupdocs.viewer) s svojim najljubšim upraviteljem paketov. 
        * Ustvarite primerek razreda Viewer in naložite datoteko SML s celotno potjo. 
        * Nastavite možnosti za upodabljanje datoteke SML v formatu HTML, PNG, JPEG ali PDF. 
        * Upodobi datoteko in preveri izpis v trenutnem imeniku. 
        
    title_right: "Sistemske zahteve" 
    content_right: |
        API-ji GroupDocs.Viewer za .NET so podprti na vseh večjih platformah in operacijskih sistemih. Preden izvedete spodnjo kodo, se prepričajte, da imate v sistemu nameščene naslednje predpogoje.

        * Operacijski sistemi: Microsoft Windows, Linux, MacOS 
        * Razvojna okolja: Microsoft Visual Studio, Visual Studio Code, .NET CLI 
        * Ogrodja: .NET Framework, .NET Standard, .NET Core, .NET 
    code: |
        ```cs
                        
            // Set up input SML file
            string filePath = "input.sml";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render SML file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "SML Viewer Live Demo"
    content: |
        Takoj si oglejte datoteko SML tako, da obiščete spletno mesto [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/sml).
    lang: "sl"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Upodabljanje in ogled drugih formatov datotek z uporabo C#"
    exclude: "SML"
    content: |
        API pregledovalnika dokumentov in slik v več formatih za .NET. Spodaj si oglejte nekaj priljubljenih formatov datotek brez zunanjih pregledovalnikov.
    format: 
        # format loop 1
        - name: "Upodobi DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Dokument Microsoft Word Open XML" 

        # format loop 2
        - name: "Upodabljanje CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "Datoteka CorelDRAW" 

        # format loop 3
        - name: "Upodabljanje PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "Predstavitev PowerPoint Open XML" 

        # format loop 4
        - name: "Upodabljanje XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Preglednica Microsoft Excel Open XML" 

        # format loop 5
        - name: "Upodabljanje DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "Risanje AutoCAD"

        # format loop 6
        - name: "Upodabljanje XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "Datoteka XML"

        # format loop 7
        - name: "Upodabljanje PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Adobe Photoshop dokument"

        # format loop 8
        - name: "Upodobi datoteko Adobe Illustrator"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Umetniško delo Adobe Illustrator"

        # format loop 9
        - name: "Upodobi DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Dokument Microsoft Word" 

        # format loop 10
        - name: "Upodabljanje TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Datoteka z navadnim besedilom" 

        # format loop 11
        - name: "Upodabljanje DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Datoteka izmenjave risb"  
          
        # format loop 12
        - name: "Upodabljanje VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "Datoteka vCard"  
              
        # format loop 13
        - name: "Upodabljanje SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Razširljiva vektorska grafika" 
          
        # format loop 14
        - name: "Upodobi HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Jezikovna datoteka za označevanje hiperteksta" 
          
        # format loop 15
        - name: "Upodobi PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Prenosna datoteka formata dokumenta"
          
        # format loop 16
        - name: "Upodabljanje JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "Slika JPEG"
          
        # format loop 17
        - name: "Upodabljanje PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Prenosna omrežna grafika" 
          
        # format loop 18
        - name: "Upodabljanje EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "E-poštno sporočilo" 
          
        # format loop 19
        - name: "Upodabljanje RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Datoteka z obogatenim besedilom" 
          
        # format loop 20
        - name: "Upodabljanje ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "Besedilni dokument OpenDocument" 
          
        # format loop 21
        - name: "Upodabljanje CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Datoteka z vrednostmi, ločenimi z vejicami" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
