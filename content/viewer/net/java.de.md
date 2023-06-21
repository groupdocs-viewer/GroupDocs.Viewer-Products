---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: de

############################# Head #############################
head_title: ".NET JAVA Viewer-API – Lesen, Anzeigen, Rendern in C# VB.NET"
head_description: ".NET-Dokument-Viewer-API zum Lesen, Rendern und Anzeigen von JAVA in allen Arten von C#-, ASP.NET-, VB.NET- und .NET Core-Anwendungen."

############################# Header ############################
title: "JAVA Dateibetrachter für C# .NET-Anwendungen" 
description: ".NET-Dokument-Viewer-API zum Lesen, Rendern und Anzeigen von JAVA-Dateien in allen Arten von C#-, ASP.NET-, VB.NET- und .NET Core-Anwendungen. Zeigen Sie die gerenderten Dateien mit echter Formatierung und echtem Layout in HTML5, PDF oder als Bild an, indem Sie ein paar Codezeilen verwenden." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Download kostenlose Testversion"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Über GroupDocs.Viewer für die .NET-API" 
    content: |
        Beginnen Sie mit der Anzeige von über 190 gängigen Dokumentformaten in Ihren .NET-Anwendungen mit GroupDocs.Viewer für .NET-APIs, indem Sie ein paar Codezeilen hinzufügen. Entwickler können problemlos PDF-, Textverarbeitungs-, Excel-Tabellen-, Präsentations-, Visio-, Projekt-, Outlook- und viele andere gängige Dokumentformate im HTML5-, Bild- oder PDF-Modus anzeigen. Die Dokumentwiedergabe ist schnell, identisch mit der Originalquelldatei und erfordert keine Installation zusätzlicher Software oder anderer externer Bibliotheken.

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
    title_left: "Schritte zum Rendern der JAVA-Datei in C#" 
    content_left: |
        Mit [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/) können Sie JAVA in wenigen Schritten in HTML, JPEG, PNG oder PDF rendern.

        * Installieren Sie [GroupDocs.Viewer für .NET](https://www.nuget.org/packages/groupdocs.viewer) mit Ihrem bevorzugten Paketmanager. 
        * Erstellen Sie eine Instanz der Viewer-Klasse und laden Sie die Datei JAVA mit dem vollständigen Pfad. 
        * Legen Sie Optionen fest, um die Datei JAVA im HTML-, PNG-, JPEG- oder PDF-Format zu rendern. 
        * Rendern Sie die Datei und überprüfen Sie die Ausgabe im aktuellen Verzeichnis. 
        
    title_right: "System Anforderungen" 
    content_right: |
        GroupDocs.Viewer für .NET-APIs werden auf allen wichtigen Plattformen und Betriebssystemen unterstützt. Bevor Sie den folgenden Code ausführen, stellen Sie bitte sicher, dass die folgenden Voraussetzungen auf Ihrem System installiert sind.

        * Betriebssysteme: Microsoft Windows, Linux, MacOS 
        * Entwicklungsumgebungen: Microsoft Visual Studio, Visual Studio Code, .NET CLI 
        * Frameworks: .NET Framework, .NET Standard, .NET Core, .NET 
    code: |
        ```cs
                        
            // Set up input JAVA file
            string filePath = "input.java";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render JAVA file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "JAVA Viewer-Live-Demo"
    content: |
        Sehen Sie sich die Datei JAVA jetzt auf der Website von [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/java) an.
    lang: "de"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Andere Dateiformate Rendern und Anzeigen mit C#"
    exclude: "JAVA"
    content: |
        Multiformat-Dokument- und Bild-Viewer-API für .NET. Sehen Sie sich unten einige der beliebtesten Dateiformate ohne externe Viewer an.
    format: 
        # format loop 1
        - name: "Rendern Sie DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word Open XML-Dokument" 

        # format loop 2
        - name: "CDR rendern" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "CorelDRAW-Datei" 

        # format loop 3
        - name: "PPTX rendern"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint Open XML-Präsentation" 

        # format loop 4
        - name: "Rendern Sie XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Open XML-Tabelle" 

        # format loop 5
        - name: "DWG rendern"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "AutoCAD-Zeichnung"

        # format loop 6
        - name: "XML rendern"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "XML-Datei"

        # format loop 7
        - name: "PSD rendern"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Adobe Photoshop-Dokument"

        # format loop 8
        - name: "Rendern Sie die Adobe Illustrator-Datei"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Adobe Illustrator-Grafik"

        # format loop 9
        - name: "DOC rendern"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Microsoft Word-Dokument" 

        # format loop 10
        - name: "TXT rendern" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Nur-Text-Datei" 

        # format loop 11
        - name: "DXF rendern" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Zeichnungsaustauschformatdatei"  
          
        # format loop 12
        - name: "VCF rendern"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "vCard-Datei"  
              
        # format loop 13
        - name: "SVG rendern"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Skalierbare Vektorgrafik" 
          
        # format loop 14
        - name: "HTML rendern"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Hypertext Markup Language-Datei" 
          
        # format loop 15
        - name: "PDF rendern"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Tragbare Dokumentformatdatei"
          
        # format loop 16
        - name: "JPEG rendern"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "JPEG-Bild"
          
        # format loop 17
        - name: "Rendern Sie PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Tragbare Netzwerkgrafik" 
          
        # format loop 18
        - name: "Rendern Sie EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "E-Mail Nachricht" 
          
        # format loop 19
        - name: "RTF rendern"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Rich-Text-Formatdatei" 
          
        # format loop 20
        - name: "ODT rendern"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "OpenDocument-Textdokument" 
          
        # format loop 21
        - name: "CSV rendern"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Datei mit durch Kommas getrennten Werten" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
