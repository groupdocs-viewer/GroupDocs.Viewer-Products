---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: de

############################# Head #############################
head_title: "Java WEBP Viewer API – Rendern und Anzeigen von WEBP in Java-Apps"
head_description: "Sehen Sie sich WEBP-Dateien in Java-, J2EE- und J2SE-Anwendungen an. Unterstützt die Anzeige von über 170 Dokument- und Bilddateiformaten im HTML-, PDF- oder Bildmodus mit erweiterten Funktionen zur Verwaltung der Dokumentanzeigeoptionen."

############################# Header ############################
title: "Rendern und Anzeigen von WEBP in Java" 
description: "Native und leistungsstarke WEBP-Dateibetrachter-API für Java-, J2EE- und J2SE-basierte Anwendungen, die eine Vielzahl zusätzlicher Funktionen unterstützt, um das Erscheinungsbild des Ausgabedokumentformats anzupassen." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Download kostenlose Testversion"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Über GroupDocs.Viewer für Java API" 
    content: |
        Ermöglichen Sie Ihren Java-Anwendungen die Anzeige von über 170 Dateiformaten im HTML-, PDF- oder Bildmodus mit GroupDocs.Viewer für Java-APIs, ohne dass zusätzliche Software installiert werden muss; wie Microsoft Office, Apache Open Office, Adobe Acrobat Reader usw. Entwickler können problemlos alle gängigen Bilder und Dokumenttypen anzeigen, einschließlich Microsoft Office, OpenDocument, HTML, PDF, Archiv, Diagramme, Photoshop, AutoCAD und Programmiersprachenformate in den Java-Anwendungen mit schnelles und qualitativ hochwertiges Rendering.

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
              text: "API-Referenz"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Codebeispiele"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Live-Demos"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Preisgestaltung"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "Schritte zum Rendern der WEBP-Datei in Java" 
    content_left: |
        Mit [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/) können Sie WEBP in wenigen Schritten in HTML, JPEG, PNG oder PDF rendern.

        * Fügen Sie [GroupDocs.Viewer für Java](https://releases.groupdocs.com/viewer/java/) als Abhängigkeit zu Ihrem Projekt hinzu. 
        * Erstellen Sie eine Instanz der Viewer-Klasse und laden Sie die Datei WEBP mit dem vollständigen Pfad. 
        * Legen Sie Optionen fest, um die Datei WEBP im HTML-, PNG-, JPEG- oder PDF-Format zu rendern. 
        * Rendern Sie die Datei und überprüfen Sie die Ausgabe im aktuellen Verzeichnis. 
        
    title_right: "System Anforderungen" 
    content_right: |
        GroupDocs.Viewer für Java-APIs werden auf allen wichtigen Plattformen und Betriebssystemen unterstützt. Bevor Sie den folgenden Code ausführen, stellen Sie bitte sicher, dass die folgenden Voraussetzungen auf Ihrem System installiert sind.

        * Betriebssysteme: Microsoft Windows, Linux, MacOS 
        * Entwicklungsumgebungen: NetBeans, IntelliJ IDEA, Eclipse usw. 
        * Frameworks: J2SE 8.0 (1.8) oder höher (zum Beispiel Java 17) 
    code: |
        ```java
                        
            // Set up input WEBP file
            String filePath = "input.webp";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render WEBP file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "WEBP Viewer-Live-Demo"
    content: |
        Sehen Sie sich die Datei WEBP jetzt auf der Website von [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/webp) an.
    lang: "de"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Andere Dateiformate Rendern und Anzeigen mit Java"
    exclude: "WEBP"
    content: |
        Multiformat-Dokument- und Bild-Viewer-API für Java. Sehen Sie sich unten einige der beliebtesten Dateiformate ohne externe Viewer an.
    format: 
        # format loop 1
        - name: "Rendern Sie DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Open XML-Dokument" 

        # format loop 2
        - name: "CDR rendern" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "CorelDRAW-Datei" 

        # format loop 3
        - name: "PPTX rendern"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint Open XML-Präsentation" 

        # format loop 4
        - name: "Rendern Sie XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Open XML-Tabelle" 

        # format loop 5
        - name: "DWG rendern"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "AutoCAD-Zeichnung"

        # format loop 6
        - name: "XML rendern"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "XML-Datei"

        # format loop 7
        - name: "PSD rendern"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Adobe Photoshop-Dokument"

        # format loop 8
        - name: "Rendern Sie die Adobe Illustrator-Datei"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Adobe Illustrator-Grafik"

        # format loop 9
        - name: "DOC rendern"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Microsoft Word-Dokument" 

        # format loop 10
        - name: "TXT rendern" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Nur-Text-Datei" 

        # format loop 11
        - name: "DXF rendern" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Zeichnungsaustauschformatdatei"  
          
        # format loop 12
        - name: "VCF rendern"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "vCard-Datei"  
              
        # format loop 13
        - name: "SVG rendern"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Skalierbare Vektorgrafik" 
          
        # format loop 14
        - name: "HTML rendern"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Hypertext Markup Language-Datei" 
          
        # format loop 15
        - name: "PDF rendern"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Tragbare Dokumentformatdatei"
          
        # format loop 16
        - name: "JPEG rendern"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "JPEG-Bild"
          
        # format loop 17
        - name: "Rendern Sie PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Tragbare Netzwerkgrafik" 
          
        # format loop 18
        - name: "Rendern Sie EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "E-Mail Nachricht" 
          
        # format loop 19
        - name: "RTF rendern"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Rich-Text-Formatdatei" 
          
        # format loop 20
        - name: "ODT rendern"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "OpenDocument-Textdokument" 
          
        # format loop 21
        - name: "CSV rendern"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Datei mit durch Kommas getrennten Werten" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
