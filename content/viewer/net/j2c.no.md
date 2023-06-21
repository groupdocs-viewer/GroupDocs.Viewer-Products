---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: no

############################# Head #############################
head_title: ".NET J2C Viewer API - Les, se, gjengi i C# VB.NET"
head_description: ".NET Document Viewer API for å lese, gjengi og vise J2C i alle typer C#, ASP.NET, VB.NET og .NET Core-applikasjoner."

############################# Header ############################
title: "J2C Filviser for C# .NET-applikasjoner" 
description: ".NET Document Viewer API for å lese, gjengi og vise J2C-fil i alle typer C#, ASP.NET, VB.NET og .NET Core-applikasjoner. Se de gjengitte filene med ekte formatering og layout i HTML5, PDF eller som et bilde ved å bruke noen få linjer med koden." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Last ned gratis prøveversjon"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Om GroupDocs.Viewer for .NET API" 
    content: |
        Begynn å se 190+ populære dokumentformater i .NET-applikasjonene dine ved å bruke GroupDocs.Viewer for .NET APIer ved å legge til noen få linjer med kode. Utviklere kan enkelt vise PDF, tekstbehandling, Excel-regneark, presentasjon, Visio, Project, Outlook og mange andre populære dokumentformater i HTML5-, bilde- eller PDF-modus. Dokumentgjengivelsen er rask, identisk med den originale kildefilen, og den krever ikke installasjon av tilleggsprogramvare eller andre eksterne biblioteker.

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
              text: "API-referanse"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Kodeeksempler"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Live-demoer"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Prissetting"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "Trinn for å gjengi J2C-filen i C#" 
    content_left: |
        Med [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/) kan du gjengi J2C til HTML, JPEG, PNG eller PDF i noen få trinn.

        * Installer [GroupDocs.Viewer for .NET](https://www.nuget.org/packages/groupdocs.viewer) ved å bruke din favorittpakkebehandling. 
        * Opprett en forekomst av Viewer-klassen og last inn J2C-filen med full bane. 
        * Angi alternativer for å gjengi J2C-filen til HTML-, PNG-, JPEG- eller PDF-format. 
        * Gjengi filen og sjekk utdata i gjeldende katalog. 
        
    title_right: "Systemkrav" 
    content_right: |
        GroupDocs.Viewer for .NET APIer støttes på alle større plattformer og operativsystemer. Før du utfører koden nedenfor, sørg for at du har følgende forutsetninger installert på systemet ditt.

        * Operativsystemer: Microsoft Windows, Linux, MacOS 
        * Utviklingsmiljøer: Microsoft Visual Studio, Visual Studio Code, .NET CLI 
        * Frameworks: .NET Framework, .NET Standard, .NET Core, .NET 
    code: |
        ```cs
                        
            // Set up input J2C file
            string filePath = "input.j2c";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render J2C file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "J2C Live-demo"
    content: |
        Se J2C-filen akkurat nå ved å besøke nettstedet til [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/j2c).
    lang: "nb"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Andre filformater gjengivelse og visning med C#"
    exclude: "J2C"
    content: |
        Multi-format dokumenter og bilder viewer API for .NET. Se noen av de populære filformatene nedenfor uten eksterne seere.
    format: 
        # format loop 1
        - name: "Gjengi DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word Open XML-dokument" 

        # format loop 2
        - name: "Gjengi CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "CorelDRAW-fil" 

        # format loop 3
        - name: "Gjengi PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint åpen XML-presentasjon" 

        # format loop 4
        - name: "Gjengi XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Åpent XML-regneark" 

        # format loop 5
        - name: "Gjengi DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "AutoCAD-tegning"

        # format loop 6
        - name: "Gjengi XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "XML-fil"

        # format loop 7
        - name: "Gjengi PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Adobe Photoshop-dokument"

        # format loop 8
        - name: "Gjengi Adobe Illustrator-fil"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Adobe Illustrator-kunstverk"

        # format loop 9
        - name: "Gjengi DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Microsoft Word-dokument" 

        # format loop 10
        - name: "Gjengi TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Ren tekstfil" 

        # format loop 11
        - name: "Gjengi DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Tegning av Exchange-formatfil"  
          
        # format loop 12
        - name: "Gjengi VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "vCard-fil"  
              
        # format loop 13
        - name: "Gjengi SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Skalerbar vektorgrafikk" 
          
        # format loop 14
        - name: "Gjengi HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "Gjengi PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Bærbar dokumentformatfil"
          
        # format loop 16
        - name: "Gjengi JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "JPEG-bilde"
          
        # format loop 17
        - name: "Gjengi PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Bærbar nettverksgrafikk" 
          
        # format loop 18
        - name: "Gjengi EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "E-postmelding" 
          
        # format loop 19
        - name: "Gjengi RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Rik tekstformatfil" 
          
        # format loop 20
        - name: "Gjengi ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "OpenDocument Tekstdokument" 
          
        # format loop 21
        - name: "Gjengi CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Kommadelte verdifil" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
