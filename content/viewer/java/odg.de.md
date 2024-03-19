---
############################# Static ############################
layout: "format"
date: 2024-03-19T07:00:44
draft: false
lang: de
product: "Viewer"
product_tag: "viewer"
platform: "Java"
platform_tag: "java"

############################# Head #############################
head_title: "Java ODG Viewer API – Rendern und Anzeigen von ODG in Java-Apps"
head_description: "Sehen Sie sich ODG-Dateien in Java-, J2EE- und J2SE-Anwendungen an. Unterstützt die Anzeige von über 180 Dokument- und Bilddateiformaten im HTML-, PDF- oder Bildmodus mit erweiterten Funktionen zur Verwaltung der Dokumentanzeigeoptionen."

############################# Header ############################
title: "Rendern und Anzeigen von ODG in Java" 
description: "Native und leistungsstarke ODG-Dateibetrachter-API für Java-, J2EE- und J2SE-basierte Anwendungen, die eine Vielzahl zusätzlicher Funktionen unterstützt, um das Erscheinungsbild des Ausgabedokumentformats anzupassen." 
subtitle: "Lösung zum Rendern von Dokumenten" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "Kostenloser Maven-Download"
      link: "https://releases.groupdocs.com/viewer/java/"



############################# About ############################
about:
    enable: true
    title: "Über GroupDocs.Viewer für Java API"
    link: "/viewer/java/"
    link_title: "Erfahren Sie mehr"
    picture: "about_viewer.svg" # 480 X 400
    content: |
      Ermöglichen Sie Ihren Java-Anwendungen die Anzeige von über 180 Dateiformaten im HTML-, PDF- oder Bildmodus mit GroupDocs.Viewer für Java-APIs, ohne dass zusätzliche Software installiert werden muss; wie Microsoft Office, Apache Open Office, Adobe Acrobat Reader usw. Entwickler können problemlos alle gängigen Bilder und Dokumenttypen anzeigen, einschließlich Microsoft Office, OpenDocument, HTML, PDF, Archiv, Diagramme, Photoshop, AutoCAD und Programmiersprachenformate in den Java-Anwendungen mit schnelles und qualitativ hochwertiges Rendering.



############################# Steps ############################
steps:
    enable: true
    title: "Schritte zum Rendern der Datei ODG in Java" 
    content: |
      Mit <a href='https://products.groupdocs.com/viewer/java/'>GroupDocs.Viewer</a> können Sie ODG in wenigen Schritten in HTML, JPEG, PNG oder PDF rendern.
      
      1. Fügen Sie <a href='https://releases.groupdocs.com/viewer/java/'>GroupDocs.Viewer für Java</a> als Abhängigkeit zu Ihrem Projekt hinzu. 
      2. Erstellen Sie eine Instanz der Viewer-Klasse und laden Sie die Datei ODG mit dem vollständigen Pfad.  
      3. Legen Sie Optionen fest, um die Datei ODG im HTML-, PNG-, JPEG- oder PDF-Format zu rendern. 
      4. Rendern Sie die Datei und überprüfen Sie die Ausgabe im aktuellen Verzeichnis. 
   
    code:
      platform: "java"
      copy_title: "Kopieren"
      install:
        command: |
          <dependencies>
            <dependency>
              <groupId>com.groupdocs</groupId>
              <artifactId>groupdocs-viewer</artifactId>
              <version>{0}</version>
            </dependency>
          </dependencies>

          <repositories>
            <repository>
              <id>repository.groupdocs.com</id>
              <name>GroupDocs Repository</name>
              <url>https://repository.groupdocs.com/repo/</url>
            </repository>
          </repositories>
        copy_tip: "Klicken Sie zum Kopieren"
        copy_done: "kopiert"
      links:
        #  loop
        - title: "Mehr Beispiele"
          link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Java"
        #  loop
        - title: "Dokumentation"
          link: "https://docs.groupdocs.com/viewer/java/"
          
      content: |
        ```java {style=abap}

        // Richten Sie die Eingabedatei ODG ein
        String filePath = "input.odg";

        // Instanziieren Sie GroupDocs.Viewer
        try (Viewer viewer = new Viewer(filePath))
        {
            // Ansichtsoptionen festlegen
            HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                
            // Rendern Sie die Datei ODG mit eingebetteten Ressourcen in HTML
            viewer.view(viewOptions);
        }

        ```
            

############################# Actions ############################

actions:
  enable: true
  title: "Bereit anzufangen?"
  description: "Testen Sie die Funktionen von GroupDocs.Viewer kostenlos oder fordern Sie eine Lizenz an"
  items:
    #  loop
    - title: "Maven-Download"
      link: "https://releases.groupdocs.com/viewer/java/"
      color: "red"
        #  loop
    - title: "Lizenzierung"
      link: "https://purchase.groupdocs.com/pricing/viewer/java/"
      color: "light"



############################# More Formats #####################
more_formats:
    enable: true
    title: "Rendern Sie andere Dateiformate mit Java"
    exclude: "ODG"
    description: "Multiformat-Dokument- und Bild-Viewer-API für Java. Sehen Sie sich unten einige der beliebtesten Dateiformate ohne externe Viewer an."
    items: 
        # format loop 1
        - name: "Rendern Sie DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Open XML Document" 

        # format loop 2
        - name: "CDR rendern" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "CorelDRAW File" 

        # format loop 3
        - name: "PPTX rendern"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint Open XML Presentation" 

        # format loop 4
        - name: "Rendern Sie XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet" 

        # format loop 5
        - name: "DWG rendern"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "AutoCAD Drawing"

        # format loop 6
        - name: "XML rendern"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "XML File"

        # format loop 7
        - name: "PSD rendern"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Adobe Photoshop Document"

        # format loop 8
        - name: "AI rendern"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Adobe Illustrator Artwork"

        # format loop 9
        - name: "DOC rendern"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Microsoft Word Document" 

        # format loop 10
        - name: "TXT rendern" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Plain Text File" 

        # format loop 11
        - name: "DXF rendern" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Drawing Exchange Format File"  
          
        # format loop 12
        - name: "VCF rendern"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "vCard File"  
              
        # format loop 13
        - name: "SVG rendern"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Scalable Vector Graphic" 
          
        # format loop 14
        - name: "HTML rendern"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "PDF rendern"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Portable Document Format File"
          
        # format loop 16
        - name: "JPEG rendern"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "JPEG Image"
          
        # format loop 17
        - name: "Rendern Sie PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Portable Network Graphic" 
          
        # format loop 18
        - name: "Rendern Sie EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "E-Mail Message" 
          
        # format loop 19
        - name: "RTF rendern"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Rich Text Format File" 
          
        # format loop 20
        - name: "ODT rendern"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "OpenDocument Text Document" 
          
        # format loop 21
        - name: "CSV rendern"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Comma-Separated Values File" 


---
