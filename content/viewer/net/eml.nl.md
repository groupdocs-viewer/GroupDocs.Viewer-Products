---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: nl

############################# Head #############################
head_title: ".NET EML Viewer API - Lezen, bekijken, renderen in C# VB.NET"
head_description: ".NET-documentviewer-API om EML te lezen, weer te geven en weer te geven in elk type C#-, ASP.NET-, VB.NET- en .NET Core-applicaties."

############################# Header ############################
title: "EML Bestandsviewer voor C# .NET-toepassingen" 
description: ".NET-documentviewer-API om EML-bestanden te lezen, weer te geven en weer te geven in elk type C#-, ASP.NET-, VB.NET- en .NET Core-applicaties. Bekijk de gerenderde bestanden met ware opmaak en lay-out in HTML5, PDF of als een afbeelding met een paar regels code." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Download gratis proefversie"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Over GroupDocs.Viewer voor .NET API" 
    content: |
        Begin met het bekijken van meer dan 190 populaire documentindelingen in uw .NET-toepassingen met behulp van GroupDocs.Viewer voor .NET API's door een paar regels code toe te voegen. Ontwikkelaars kunnen PDF, tekstverwerking, Excel-spreadsheet, presentatie, Visio, project, Outlook en vele andere populaire documentindelingen eenvoudig weergeven in HTML5-, afbeeldings- of pdf-modus. De documentweergave is snel, identiek aan het originele bronbestand en vereist geen installatie van extra software of andere externe bibliotheken.

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
              text: "API-referentie"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Codevoorbeelden"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Live demo's"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Prijzen"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "Stappen om EML bestand weer te geven in C#" 
    content_left: |
        Met [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/) kun je in een paar stappen EML naar HTML, JPEG, PNG of PDF renderen.

        * Installeer [GroupDocs.Viewer for .NET](https://www.nuget.org/packages/groupdocs.viewer) met uw favoriete pakketbeheerder. 
        * Maak een instantie van de klasse Viewer en laad het bestand EML met het volledige pad. 
        * Stel opties in om EML-bestanden weer te geven in HTML-, PNG-, JPEG- of PDF-indeling. 
        * Geef het bestand weer en controleer de uitvoer in de huidige map. 
        
    title_right: "systeem vereisten" 
    content_right: |
        GroupDocs.Viewer voor .NET API's worden ondersteund op alle belangrijke platforms en besturingssystemen. Voordat u de onderstaande code uitvoert, moet u ervoor zorgen dat de volgende vereisten op uw systeem zijn geïnstalleerd.

        * Besturingssystemen: Microsoft Windows, Linux, MacOS 
        * Ontwikkelomgevingen: Microsoft Visual Studio, Visual Studio Code, .NET CLI 
        * Kaders: .NET Framework, .NET Standaard, .NET Core, .NET 
    code: |
        ```cs
                        
            // Set up input EML file
            string filePath = "input.eml";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render EML file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "EML Viewer live demo"
    content: |
        Bekijk het EML-bestand nu door naar de website [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/eml) te gaan.
    lang: "nl"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Andere bestandsindelingen Renderen en bekijken met C#"
    exclude: "EML"
    content: |
        API voor documentweergave in meerdere formaten en afbeeldingen voor .NET. Bekijk hieronder enkele van de populaire bestandsindelingen zonder externe kijkers.
    format: 
        # format loop 1
        - name: "DOCX weergeven"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word Open XML-document" 

        # format loop 2
        - name: "CDR renderen" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "CorelDRAW-bestand" 

        # format loop 3
        - name: "PPTX weergeven"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint Open XML-presentatie" 

        # format loop 4
        - name: "Geef XLSX weer"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Open XML-werkblad" 

        # format loop 5
        - name: "DWG renderen"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "AutoCAD-tekening"

        # format loop 6
        - name: "XML weergeven"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "XML-bestand"

        # format loop 7
        - name: "Geef PSD weer"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Adobe Photoshop-document"

        # format loop 8
        - name: "Render Adobe Illustrator-bestand"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Adobe Illustrator-kunstwerk"

        # format loop 9
        - name: "DOC weergeven"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Microsoft Word-document" 

        # format loop 10
        - name: "TXT weergeven" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Bestand met platte tekst" 

        # format loop 11
        - name: "DXF renderen" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Tekening Exchange-formaatbestand"  
          
        # format loop 12
        - name: "Geef VCF weer"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "vCard-bestand"  
              
        # format loop 13
        - name: "Geef SVG weer"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Schaalbare vectorafbeelding" 
          
        # format loop 14
        - name: "Geef HTML weer"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Hypertext Markup Language-bestand" 
          
        # format loop 15
        - name: "Pdf renderen"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Draagbaar documentformaatbestand"
          
        # format loop 16
        - name: "JPEG renderen"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "JPEG-afbeelding"
          
        # format loop 17
        - name: "PNG weergeven"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Draagbare netwerkafbeelding" 
          
        # format loop 18
        - name: "Geef EML weer"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "Email bericht" 
          
        # format loop 19
        - name: "Geef RTF weer"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Rich Text Format-bestand" 
          
        # format loop 20
        - name: "Geef ODT weer"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "OpenDocument-tekstdocument" 
          
        # format loop 21
        - name: "Csv weergeven"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Bestand met door komma's gescheiden waarden" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
