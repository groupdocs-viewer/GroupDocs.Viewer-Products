---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: no

############################# Head #############################
head_title: "Java MPT Viewer API - Gjengivelse og visning MPT i Java-apper"
head_description: "Vis MPT-filer i Java-, J2EE-, J2SE-applikasjoner. Støtter visning av 170+ dokument- og bildefilformater i HTML-, PDF- eller bildemodus med avanserte funksjoner for å administrere alternativer for dokumentvisning."

############################# Header ############################
title: "Gjengi og se MPT i Java" 
description: "Innebygd og høyytelses MPT filvisnings-API for Java-, J2EE- og J2SE-baserte applikasjoner, som støtter et bredt spekter av tilleggsfunksjoner for å tilpasse utseendet til utdatadokumentformatet." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Last ned gratis prøveversjon"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Om GroupDocs.Viewer for Java API" 
    content: |
        Aktiver Java-applikasjonene dine til å vise over 170 filformater i HTML-, PDF- eller bildemodus ved å bruke GroupDocs.Viewer for Java API-er uten ekstra programvare installert; som Microsoft Office, Apache Open Office, Adobe Acrobat Reader osv. Utviklere kan enkelt se alle populære bilder og dokumenttyper inkludert Microsoft Office, OpenDocument, HTML, PDF, Arkiv, Diagrammer, Photoshop, AutoCAD og programmeringsspråkformater inne i Java-applikasjonene med rask gjengivelse av høyeste kvalitet.

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
    title_left: "Trinn for å gjengi MPT-filen i Java" 
    content_left: |
        Med [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/) kan du gjengi MPT til HTML, JPEG, PNG eller PDF i noen få trinn.

        * Legg til [GroupDocs.Viewer for Java](https://releases.groupdocs.com/viewer/java/) som en avhengighet til prosjektet ditt. 
        * Opprett en forekomst av Viewer-klassen og last inn MPT-filen med full bane. 
        * Angi alternativer for å gjengi MPT-filen til HTML-, PNG-, JPEG- eller PDF-format. 
        * Gjengi filen og sjekk utdata i gjeldende katalog. 
        
    title_right: "Systemkrav" 
    content_right: |
        GroupDocs.Viewer for Java APIer støttes på alle større plattformer og operativsystemer. Før du utfører koden nedenfor, sørg for at du har følgende forutsetninger installert på systemet ditt.

        * Operativsystemer: Microsoft Windows, Linux, MacOS 
        * Utviklingsmiljøer: NetBeans, IntelliJ IDEA, Eclipse etc. 
        * Rammer: J2SE 8.0 (1.8) eller nyere (for eksempel Java 17) 
    code: |
        ```java
                        
            // Set up input MPT file
            String filePath = "input.mpt";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render MPT file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "MPT Live-demo"
    content: |
        Se MPT-filen akkurat nå ved å besøke nettstedet til [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/mpt).
    lang: "nb"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Andre filformater gjengivelse og visning med Java"
    exclude: "MPT"
    content: |
        Multi-format dokumenter og bilder viewer API for Java. Se noen av de populære filformatene nedenfor uten eksterne seere.
    format: 
        # format loop 1
        - name: "Gjengi DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Open XML-dokument" 

        # format loop 2
        - name: "Gjengi CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "CorelDRAW-fil" 

        # format loop 3
        - name: "Gjengi PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint åpen XML-presentasjon" 

        # format loop 4
        - name: "Gjengi XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Åpent XML-regneark" 

        # format loop 5
        - name: "Gjengi DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "AutoCAD-tegning"

        # format loop 6
        - name: "Gjengi XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "XML-fil"

        # format loop 7
        - name: "Gjengi PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Adobe Photoshop-dokument"

        # format loop 8
        - name: "Gjengi Adobe Illustrator-fil"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Adobe Illustrator-kunstverk"

        # format loop 9
        - name: "Gjengi DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Microsoft Word-dokument" 

        # format loop 10
        - name: "Gjengi TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Ren tekstfil" 

        # format loop 11
        - name: "Gjengi DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Tegning av Exchange-formatfil"  
          
        # format loop 12
        - name: "Gjengi VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "vCard-fil"  
              
        # format loop 13
        - name: "Gjengi SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Skalerbar vektorgrafikk" 
          
        # format loop 14
        - name: "Gjengi HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "Gjengi PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Bærbar dokumentformatfil"
          
        # format loop 16
        - name: "Gjengi JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "JPEG-bilde"
          
        # format loop 17
        - name: "Gjengi PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Bærbar nettverksgrafikk" 
          
        # format loop 18
        - name: "Gjengi EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "E-postmelding" 
          
        # format loop 19
        - name: "Gjengi RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Rik tekstformatfil" 
          
        # format loop 20
        - name: "Gjengi ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "OpenDocument Tekstdokument" 
          
        # format loop 21
        - name: "Gjengi CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Kommadelte verdifil" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
