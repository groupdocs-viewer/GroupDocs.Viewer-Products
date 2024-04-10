---
############################# Static ############################
layout: "format"
date: 2024-04-10T11:55:55
draft: false
lang: de
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head #############################
head_title: ".NET DNG Viewer-API – Lesen, Anzeigen, Rendern in C# VB.NET"
head_description: ".NET-Dokument-Viewer-API zum Lesen, Rendern und Anzeigen von DNG in allen Arten von C#-, ASP.NET-, VB.NET- und .NET Core-Anwendungen."

############################# Header ############################
title: "DNG Dateibetrachter für C# .NET-Anwendungen" 
description: ".NET-Dokument-Viewer-API zum Lesen, Rendern und Anzeigen von DNG-Dateien in allen Arten von C#-, ASP.NET-, VB.NET- und .NET Core-Anwendungen. Zeigen Sie die gerenderten Dateien mit echter Formatierung und echtem Layout in HTML5, PDF oder als Bild an, indem Sie ein paar Codezeilen verwenden." 
subtitle: "Lösung zum Rendern von Dokumenten" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "Kostenloser Nuget-Download"
      link: "https://nuget.org/packages/GroupDocs.Viewer"



############################# About ############################
about:
    enable: true
    title: "Über GroupDocs.Viewer für die .NET-API"
    link: "/viewer/net/"
    link_title: "Erfahren Sie mehr"
    picture: "about_viewer.svg" # 480 X 400
    content: |
      Beginnen Sie mit der Anzeige von über 190 gängigen Dokumentformaten in Ihren .NET-Anwendungen mit GroupDocs.Viewer für .NET-APIs, indem Sie ein paar Codezeilen hinzufügen. Entwickler können problemlos PDF-, Textverarbeitungs-, Excel-Tabellen-, Präsentations-, Visio-, Projekt-, Outlook- und viele andere gängige Dokumentformate im HTML5-, Bild- oder PDF-Modus anzeigen. Die Dokumentwiedergabe ist schnell, identisch mit der Originalquelldatei und erfordert keine Installation zusätzlicher Software oder anderer externer Bibliotheken.



############################# Steps ############################
steps:
    enable: true
    title: "Schritte zum Rendern der DNG-Datei in C#" 
    content: |
      Mit <a href='https://products.groupdocs.com/viewer/net/'>GroupDocs.Viewer</a> können Sie DNG in wenigen Schritten in HTML, JPEG, PNG oder PDF rendern.
      
      1. Installieren Sie <a href='https://www.nuget.org/packages/groupdocs.viewer'>GroupDocs.Viewer für .NET</a> mit Ihrem bevorzugten Paketmanager. 
      2. Erstellen Sie eine Instanz der Viewer-Klasse und laden Sie die Datei DNG mit dem vollständigen Pfad.  
      3. Legen Sie Optionen fest, um die Datei DNG im HTML-, PNG-, JPEG- oder PDF-Format zu rendern. 
      4. Rendern Sie die Datei und überprüfen Sie die Ausgabe im aktuellen Verzeichnis. 
   
    code:
      platform: "net"
      copy_title: "Kopieren"
      install:
        command: "dotnet add package GroupDocs.Viewer"
        copy_tip: "Klicken Sie zum Kopieren"
        copy_done: "kopiert"
      links:
        #  loop
        - title: "Mehr Beispiele"
          link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
        #  loop
        - title: "Dokumentation"
          link: "https://docs.groupdocs.com/viewer/net/"
          
      content: |
        ```csharp {style=abap}

        // Richten Sie die Eingabedatei DNG ein
        string filePath = "input.dng";

        // Instanziieren Sie GroupDocs.Viewer
        using (Viewer viewer = new Viewer(filePath))
        {
            // Ansichtsoptionen festlegen
            HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                
            // Rendern Sie die Datei DNG mit eingebetteten Ressourcen in HTML
            viewer.View(viewOptions);
        }

        ```            


############################# Actions ############################

actions:
  enable: true
  title: "Bereit anzufangen?"
  description: "Testen Sie die Funktionen von GroupDocs.Viewer kostenlos oder fordern Sie eine Lizenz an"
  items:
    #  loop
    - title: "Nuget-Download"
      link: "https://releases.groupdocs.com/viewer/net/"
      color: "red"
        #  loop
    - title: "Lizenzierung"
      link: "https://purchase.groupdocs.com/pricing/viewer/net/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "Rendern Sie andere Dateiformate mit C#"
    exclude: "DNG"
    description: "Multiformat-Dokument- und Bild-Viewer-API für .NET. Sehen Sie sich unten einige der beliebtesten Dateiformate ohne externe Viewer an."
    items: 
        # format loop 1
        - name: "Rendern Sie DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word Open XML Document" 

        # format loop 2
        - name: "CDR rendern" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "CorelDRAW File" 

        # format loop 3
        - name: "PPTX rendern"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint Open XML Presentation" 

        # format loop 4
        - name: "Rendern Sie XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet" 

        # format loop 5
        - name: "DWG rendern"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "AutoCAD Drawing"

        # format loop 6
        - name: "XML rendern"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "XML File"

        # format loop 7
        - name: "PSD rendern"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Adobe Photoshop Document"

        # format loop 8
        - name: "AI rendern"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Adobe Illustrator Artwork"

        # format loop 9
        - name: "DOC rendern"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Microsoft Word Document" 

        # format loop 10
        - name: "TXT rendern" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Plain Text File" 

        # format loop 11
        - name: "DXF rendern" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Drawing Exchange Format File"  
          
        # format loop 12
        - name: "VCF rendern"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "vCard File"  
              
        # format loop 13
        - name: "SVG rendern"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Scalable Vector Graphic" 
          
        # format loop 14
        - name: "HTML rendern"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "PDF rendern"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Portable Document Format File"
          
        # format loop 16
        - name: "JPEG rendern"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "JPEG Image"
          
        # format loop 17
        - name: "Rendern Sie PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Portable Network Graphic" 
          
        # format loop 18
        - name: "Rendern Sie EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "E-Mail Message" 
          
        # format loop 19
        - name: "RTF rendern"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Rich Text Format File" 
          
        # format loop 20
        - name: "ODT rendern"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "OpenDocument Text Document" 
          
        # format loop 21
        - name: "CSV rendern"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Comma-Separated Values File" 



---
