---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: nl

############################# Head #############################
head_title: "Java JLS Viewer-API - JLS weergeven en weergeven in Java-apps"
head_description: "Bekijk JLS bestanden in Java-, J2EE-, J2SE-applicaties. Ondersteunt het bekijken van meer dan 170 document- en afbeeldingsbestandsindelingen in HTML-, PDF- of afbeeldingsmodus met geavanceerde functies om opties voor het bekijken van documenten te beheren."

############################# Header ############################
title: "Render en bekijk JLS in Java" 
description: "Native en krachtige JLS API voor bestandsviewer voor op Java, J2EE en J2SE gebaseerde applicaties, die een breed scala aan extra functies ondersteunt om het uiterlijk van het uitvoerdocumentformaat aan te passen." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Download gratis proefversie"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Over GroupDocs.Viewer voor Java API" 
    content: |
        Stel uw Java-toepassingen in staat om meer dan 170 bestandsindelingen weer te geven in HTML-, PDF- of afbeeldingsmodus met behulp van GroupDocs.Viewer voor Java API's zonder dat er extra software is geïnstalleerd; zoals Microsoft Office, Apache Open Office, Adobe Acrobat Reader enz. Ontwikkelaars kunnen eenvoudig alle populaire afbeeldingen en documenttypen bekijken, waaronder Microsoft Office, OpenDocument, HTML, PDF, Archief, Diagrammen, Photoshop, AutoCAD en programmeertaalformaten in de Java-toepassingen met snelle weergave van de hoogste kwaliteit.

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
    title_left: "Stappen om JLS bestand weer te geven in Java" 
    content_left: |
        Met [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/) kun je in een paar stappen JLS renderen naar HTML, JPEG, PNG of PDF.

        * Voeg [GroupDocs.Viewer for Java](https://releases.groupdocs.com/viewer/java/) toe als afhankelijkheid van uw project. 
        * Maak een instantie van de klasse Viewer en laad het bestand JLS met het volledige pad. 
        * Stel opties in om JLS-bestanden weer te geven in HTML-, PNG-, JPEG- of PDF-indeling. 
        * Geef het bestand weer en controleer de uitvoer in de huidige map. 
        
    title_right: "systeem vereisten" 
    content_right: |
        GroupDocs.Viewer voor Java API's worden ondersteund op alle belangrijke platforms en besturingssystemen. Voordat u de onderstaande code uitvoert, moet u ervoor zorgen dat de volgende vereisten op uw systeem zijn geïnstalleerd.

        * Besturingssystemen: Microsoft Windows, Linux, MacOS 
        * Ontwikkelomgevingen: NetBeans, IntelliJ IDEA, Eclipse etc. 
        * Frameworks: J2SE 8.0 (1.8) of hoger (bijvoorbeeld Java 17) 
    code: |
        ```java
                        
            // Set up input JLS file
            String filePath = "input.jls";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render JLS file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "JLS Viewer live demo"
    content: |
        Bekijk het JLS-bestand nu door naar de website [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/jls) te gaan.
    lang: "nl"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Andere bestandsindelingen Renderen en bekijken met Java"
    exclude: "JLS"
    content: |
        API voor documenten en afbeeldingen in meerdere indelingen voor Java. Bekijk hieronder enkele van de populaire bestandsindelingen zonder externe kijkers.
    format: 
        # format loop 1
        - name: "DOCX weergeven"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Open XML-document" 

        # format loop 2
        - name: "CDR renderen" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "CorelDRAW-bestand" 

        # format loop 3
        - name: "PPTX weergeven"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint Open XML-presentatie" 

        # format loop 4
        - name: "Geef XLSX weer"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Open XML-werkblad" 

        # format loop 5
        - name: "DWG renderen"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "AutoCAD-tekening"

        # format loop 6
        - name: "XML weergeven"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "XML-bestand"

        # format loop 7
        - name: "Geef PSD weer"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Adobe Photoshop-document"

        # format loop 8
        - name: "Render Adobe Illustrator-bestand"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Adobe Illustrator-kunstwerk"

        # format loop 9
        - name: "DOC weergeven"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Microsoft Word-document" 

        # format loop 10
        - name: "TXT weergeven" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Bestand met platte tekst" 

        # format loop 11
        - name: "DXF renderen" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Tekening Exchange-formaatbestand"  
          
        # format loop 12
        - name: "Geef VCF weer"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "vCard-bestand"  
              
        # format loop 13
        - name: "Geef SVG weer"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Schaalbare vectorafbeelding" 
          
        # format loop 14
        - name: "Geef HTML weer"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Hypertext Markup Language-bestand" 
          
        # format loop 15
        - name: "Pdf renderen"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Draagbaar documentformaatbestand"
          
        # format loop 16
        - name: "JPEG renderen"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "JPEG-afbeelding"
          
        # format loop 17
        - name: "PNG weergeven"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Draagbare netwerkafbeelding" 
          
        # format loop 18
        - name: "Geef EML weer"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "Email bericht" 
          
        # format loop 19
        - name: "Geef RTF weer"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Rich Text Format-bestand" 
          
        # format loop 20
        - name: "Geef ODT weer"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "OpenDocument-tekstdocument" 
          
        # format loop 21
        - name: "Csv weergeven"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Bestand met door komma's gescheiden waarden" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
