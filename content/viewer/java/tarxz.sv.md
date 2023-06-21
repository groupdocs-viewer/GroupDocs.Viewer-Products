---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: sv

############################# Head #############################
head_title: "Java TARXZ Viewer API - Rendera och visa TARXZ i Java Apps"
head_description: "Visa TARXZ-filer i Java-, J2EE-, J2SE-applikationer. Stöder visning av 170+ dokument- och bildfilformat i HTML-, PDF- eller bildläge med avancerade funktioner för att hantera dokumentvisningsalternativ."

############################# Header ############################
title: "Rendera och visa TARXZ i Java" 
description: "Inbyggt och högpresterande TARXZ filvisar-API för Java-, J2EE- och J2SE-baserade applikationer, som stöder ett brett utbud av ytterligare funktioner för att anpassa utseendet på utdatadokumentformatet." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Ladda ner gratis provversion"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Om GroupDocs.Viewer för Java API" 
    content: |
        Aktivera dina Java-applikationer att visa över 170 filformat i HTML-, PDF- eller bildlägen med hjälp av GroupDocs.Viewer för Java API:er utan att någon extra programvara installerad; som Microsoft Office, Apache Open Office, Adobe Acrobat Reader etc. Utvecklare kan enkelt visa alla populära bilder och dokumenttyper inklusive Microsoft Office, OpenDocument, HTML, PDF, Arkiv, Diagram, Photoshop, AutoCAD och programmeringsspråksformat inuti Java-applikationerna med snabb och högsta kvalitet rendering.

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
              text: "API-referens"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Kodexempel"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Live Demos"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Prissättning"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "Steg för att rendera filen TARXZ i Java" 
    content_left: |
        Med [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/) kan du rendera TARXZ till HTML, JPEG, PNG eller PDF i några få steg.

        * Lägg till [GroupDocs.Viewer for Java](https://releases.groupdocs.com/viewer/java/) som ett beroende till ditt projekt. 
        * Skapa en instans av Viewer-klassen och ladda TARXZ-filen med fullständig sökväg. 
        * Ställ in alternativ för att rendera filen TARXZ till HTML-, PNG-, JPEG- eller PDF-format. 
        * Rendera filen och kontrollera utdata i den aktuella katalogen. 
        
    title_right: "Systemkrav" 
    content_right: |
        GroupDocs.Viewer för Java API:er stöds på alla större plattformar och operativsystem. Innan du kör koden nedan, se till att du har följande förutsättningar installerade på ditt system.

        * Operativsystem: Microsoft Windows, Linux, MacOS 
        * Utvecklingsmiljöer: NetBeans, IntelliJ IDEA, Eclipse etc. 
        * Ramverk: J2SE 8.0 (1.8) eller högre (till exempel Java 17) 
    code: |
        ```java
                        
            // Set up input TARXZ file
            String filePath = "input.tarxz";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render TARXZ file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "Tarxz Viewer Live Demo"
    content: |
        Visa filen TARXZ just nu genom att besöka webbplatsen [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/tarxz).
    lang: "sv"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Andra filformat Rendering och visning med Java"
    exclude: "TARXZ"
    content: |
        Flerformatsdokument och bildvisare API för Java. Se några av de populära filformaten nedan utan några externa tittare.
    format: 
        # format loop 1
        - name: "Rendera DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Open XML-dokument" 

        # format loop 2
        - name: "Gör CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "CorelDRAW-fil" 

        # format loop 3
        - name: "Gör PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint Open XML-presentation" 

        # format loop 4
        - name: "Rendera XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Öppna XML-kalkylblad" 

        # format loop 5
        - name: "Gör DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "AutoCAD-ritning"

        # format loop 6
        - name: "Rendera XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "XML-fil"

        # format loop 7
        - name: "Gör PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Adobe Photoshop-dokument"

        # format loop 8
        - name: "Rendera Adobe Illustrator-fil"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Konstverk från Adobe Illustrator"

        # format loop 9
        - name: "Gör DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Microsoft Word-dokument" 

        # format loop 10
        - name: "Återge TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Vanlig textfil" 

        # format loop 11
        - name: "Gör DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Rita Exchange Format-fil"  
          
        # format loop 12
        - name: "Gör VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "vCard-fil"  
              
        # format loop 13
        - name: "Rendera SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Skalbar vektorgrafik" 
          
        # format loop 14
        - name: "Återge HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "Gör PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Fil i bärbar dokumentformat"
          
        # format loop 16
        - name: "Återge JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "JPEG-bild"
          
        # format loop 17
        - name: "Återge PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Bärbar nätverksgrafik" 
          
        # format loop 18
        - name: "Gör EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "E-postmeddelande" 
          
        # format loop 19
        - name: "Gör RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "RTF-fil" 
          
        # format loop 20
        - name: "Rendera ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "OpenDocument-textdokument" 
          
        # format loop 21
        - name: "Återge CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Kommaseparerade värdefil" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
