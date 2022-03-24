---
############################# Static ############################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: ".NET Document Viewer API, Render PDF Word Excel Bild HTML-Diagramm"
head_description: "C# ASP.NET-Dateibetrachter und Rendering-API. Fügen Sie PDF-Viewer, Word-Viewer, Excel-Viewer, Bild-Viewer, HTML-Viewer, E-Mail-Viewer-Funktionen in .NET-Apps hinzu."

############################# Header ############################
title: "Rendern und Anzeigen von Dokumenten über die .NET-API"
description: ".NET Document Viewer API zum Rendern von mehr als 170 Dokumentformaten in PDF, HTML und Bild mit leistungsstarken Konfigurationsoptionen."
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Download kostenlose Testversion"
    link: "https://downloads.groupdocs.com/viewer/net"

############################# SubMenu ############################
submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Viewer for .NET"
        image: "/border/groupdocs-viewer-net.svg"
        product: "GroupDocs.Viewer"
        platform: ".NET"

    middle:
        button:
            # button loop
            - link: "#overview"
              text: "Überblick"

            # button loop
            - link: "#features"
              text: "Merkmale"

            # button loop
            - link: "#support"
              text: "Support"

            # button loop
            - link: "https://products.groupdocs.app/viewer"
              text: "Live Demo"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Preisgestaltung"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# Überblick ############################
overview:
    enable: true
    content: |
      GroupDocs.Viewer für .NET-APIs helfen Ihnen, leistungsstarke Anwendungen in C#, ASP.NET und anderen .NET-basierten Technologien zu erstellen, die Dokumente und Bilder in über 170 Dateiformaten rendern und anzeigen können, ohne externe Software installieren zu müssen. Die Datei-Viewer-Bibliothek rastert die Dokumente und konvertiert sie dann in SVG+HTML+CSS, um das gesamte Dokument-Rendering-Erlebnis für die Anzeige von Geschäftsdokumenten, Bildern, Textdateien, Diagrammen, Grafiken, E-Mail-Anhängen und PDF-Dateien mit Geschwindigkeit, Echttext und High-Fidelity in Ihren Anwendungen. Sie haben die Möglichkeit, Funktionen zum Anzeigen und Lesen von Dokumenten in Ihren Anwendungen hinzuzufügen, um ganze Dokumente, Teildokumente, bestimmte Seiten/Zellbereiche, einzelne Dokumentebenen mit oder ohne Anmerkungen und Kommentare für die unterstützten Dateiformate anzuzeigen.

      GroupDocs.Viewer für .NET speichert die ausgegebenen gerenderten Dokumente standardmäßig auf der lokalen Festplatte. Jede Art von externem Cache-Speicher wird ebenfalls unterstützt, indem entsprechende Schnittstellen implementiert werden – Amazon S3, Dropbox, Google Drive, Windows Azure, Redis oder andere.
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          Nachfolgend finden Sie eine Übersicht über GroupDocs.Viewer für .NET:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Überblick"
          content: |
            * Zeigen Sie über 170 Dokumenttypen an
            * Holen Sie sich HTML, Bild, PDF-Version
            * Rotate &amp; Reorder
            * Wasserzeichen anwenden
            * Cache für schnellen Prozess
            * Fügen Sie benutzerdefinierte Schriftarten hinzu
            * Wenden Sie Codierungsstandards an
            * Benutzerdefinierter Eingabedaten-Handler
            * Rendern mit Änderungen nachverfolgen
            * Rendern als Responsive HTML
            * Render PDF &amp; CAD Layers
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Viewer für .NET unterstützt die Anzeige aller gängigen [Dokumentdateiformate](https://docs.groupdocs.com/viewer/net/supported-document-formats/). Mit nur wenigen Codezeilen fügen Sie Ihren .NET-Anwendungen PDF-Viewer, Microsoft Office Word, Excel-Tabellen, Bilder, HTML, Outlook-E-Mail, OneNote, Project und Grafikanzeigefunktionen hinzu.

        left:
          enable: true
          table:
            # table loop
            - title: "Microsoft Office"
              content: |
                * **Word:** DOC, DOCX, DOCM, DOT, DOTX, DOTM, RTF, TXT
                * **Excel:** XLS, XLSX, XLSM, XLSB, XLTM, XLT, XLTM, XLTX, XLAM, SXC, SpreadsheetML
                * **PowerPoint:** PPT, PPTX, PPS, PPSX, PPSM, POT, POTM, POTX, PPTM
                * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
                * **Project:** MPP, MPT, MPX
                * **Outlook:** MSG, EML, EMLX, PST, OST
                * **OneNote:** ONE

            # table loop
            - title: "Andere Formate"
              content: |
                * **PDF Formats:** PDF, TEX, XPS, OXPS
                * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG, OTG, FODP, FODG
                * **Delimiter-Separated Values:** CSV, TSV
                * **Web:** HTML, MHT, MHTML
                * **Metafile:** WMF, EMF, CGM, WMZ, EMZ
                * **PostScript:** PS, EPS
                * **Archives:** ZIP, TAR, BZ2, GZ, RAR, RAR5
                * **Various:** OBJ, EPUB, MOBI, DjVu, XML, VCF, VCARD, NUMBER, NSF

        right:
          enable: true
          table:
            # table loop
            - title: "Bilder, Grafiken & Diagramme"
              content: |
                * **Images:** BMP, GIF, JPG, PNG, TIFF, multi-page TIFF, WebP, DNG, DIB, DCM
                * **Windows Icon:** ICO
                * **Scalable Vector Graphics:** SVG, CDR, CMX, IGS, SVGZ
                * **Jpeg2000:** JP2, J2C, J2K, JPC, JPF, JPX, JPM
                * **Adobe Photoshop:** PSD, PSB
                * **Printer Command Language:** PCL
                * **Stereo Lithography (3D Printing):** STL
                * **Industry Foundation Classes:** IFC
                * **Medical Imaging:** DICOM
                * **Plotter Documents:** PLT, HPG
                * **Autodesk Design Web Formats:** DWF, DWG
                * **AutoCAD Drawing:** DGN, DWT, IFC, STL, CF2
                * **ISFF-based DGN (V7):** DGN

            # table loop
            - title: "Programmiersprachenformate"
              content: |
                * **C/C++/C# Files:** C, CC, CS, CPP, CXX, C#, H, HH, M, MM
                * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES
                * **Various:** VB, PHP, SQL, PL, PY, PV, RB, RST, SASS, SCALA, SCM, SCRIPT, AS, AS3, ASM, BAT, CMAKE, CSS, DIFF, ERB, GROOVY, HAML, LESS, LOG, M, MAKE, MD, ML, MM, SH, SML, VIM, YAML

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Viewer for .NET unterstützt das Folgen Betriebssysteme, Frameworks & Paket-Managers:
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Betriebssysteme"
              content: |
                * Windows Desktop
                * Windows Server
                * Microsoft Azure
                * Linux

            # table loop
            - icon: "fas fa-code"
              title: "Unterstützte Frameworks"
              content: |
                * .NET Framework 2.0 oder höher
                * .NET Core 3.1
                * .NET 5 or higher

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-box"
              title: "Paket-Manager"
              content: |
                * NuGet

            # table loop
            - icon: "fas fa-tools"
              title: "Entwicklungsumgebungen"
              content: |
                * Microsoft Visual Studio
                * Visual Studio Code
                * .NET CLI

############################# Merkmale ############################
features:
    enable: true
    title: "GroupDocs.Viewer for .NET Merkmale"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "Rastern Sie Dokumente und konvertieren Sie sie in SVG, HTML und CSS"

      # feature loop
      - icon: "fas fa-eye"
        content: "Konvertieren Sie Text in HTML und rendern Sie Dokumente, um eine HTML-, Bild- oder PDF-Darstellung zu erhalten"

      # feature loop
      - icon: "fas fa-bolt"
        content: "Schnellere Ladezeit durch zwischengespeicherte Versionen von Dokumenten"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "Konvertieren Sie Präsentationen mit Formen und Text mit 3D-Effekten"

      # feature loop
      - icon: "fas fa-code"
        content: "Kodieren Sie Word-, Excel- und E-Mail-Dokumente nach dem gewünschten Kodierungsstandard"

      # feature loop
      - icon: "fas fa-cloud"
        content: "Rendern Sie Dokumente, die sich an FTP- oder Cloud-Speicherorten befinden"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "Ausschließen von Schriftarten beim Rendern in HTML, um die resultierende Dateigröße zu reduzieren"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "Minimieren Sie die CSS- und HTML-Ausgabe, indem Sie Kommentare, zusätzliche Leerzeichen usw. entfernen."

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "Lesen Sie den in einem Quelldokument enthaltenen Text anhand seiner Koordinaten"

      # feature loop
      - icon: "fas fa-border-all"
        content: "Ein-/Ausblenden der Gitterlinien von Excel-Tabellen in der Ausgabedarstellung"

      # feature loop
      - icon: "fas fa-wrench"
        content: "Geben Sie die Anzahl der Zeilen in einem Excel-Blatt an, die auf jeder Seite gerendert werden sollen"

      # feature loop
      - icon: "fas fa-columns"
        content: "Leere Spalten beim Rendern von Tabellenkalkulationsdokumenten ignorieren"

      # feature loop
      - icon: "fas fa-file-word"
        content: "Rendern Sie Word-Dokumente in HTML-Seiten, Bilder oder PDFs mit Nachverfolgung von Änderungen"

      # feature loop
      - icon: "fas fa-envelope"
        content: "Rendern Sie E-Mail-Anhänge als Originaldateien, Bilder oder in HTML-Darstellung"

      # feature loop
      - icon: "fas fa-print"
        content: "Legen Sie Druckbeschränkungen für PDF-Dokumente fest"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "Rendern Sie Inhalte/Dateien, die in ZIP-Archiven enthalten sind, als Anhänge"

      # feature loop
      - icon: "fas fa-lock"
        content: "Abrufen von Anhängen aus passwortgeschützten Dokumenten"

      # feature loop
      - icon: "fas fa-file-code"
        content: "Rendert Dateiformate von Programmiersprachen als reinen Text"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "Passen Sie die Hintergrundfarben beim Anzeigen von CAD-Zeichnungen an"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "Zeigen Sie Excel-Dokumente an und konvertieren Sie sie in PDF, HTML, JPG und PNG"

      # feature loop
      - icon: "fas fa-heading"
        content: "Arbeitsblattnamen aus Excel-Datei abrufen – Spaltenüberschriften und Zeilennummern der Tabellenkalkulation anzeigen"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "Anzeigen und Konvertieren von Microsoft Project-Dokumenten mit Notizen"

      # feature loop
      - icon: "fas fa-cube"
        content: "Konvertieren Sie CAD-Zeichnungen in SVG für ein besseres Anzeige- und Zoomerlebnis"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "Wählen Sie Visio-Figuren ohne Schema rendern"

    more_feature:
      # more_feature_loop
      - title: "Dokumente effizient und zuverlässig anzeigen"
        content: |
          Mit der GroupDocs.Viewer-API können Sie mehr als 170 Dokumentformate effizient und zuverlässig anzeigen, wobei die Integrität von Inhalt und Dokumentstruktur intakt bleibt. Der folgende Beispielcode zeigt, wie einfach es ist, die HTML-Darstellung eines DOCX-Dokuments anzuzeigen:

          ```cs
          // Betrachter instanziieren
          using (Viewer viewer = new Viewer("sample.docx")
          {
              // Ansichtsoptionen festlegen
              HtmlViewOptions options = HtmlViewOptions.ForEmbeddedResources();
              // Datei mit eingebetteten Ressourcen in HTML konvertieren
              viewer.View(options);
          }
          ```
      # more_feature_loop
      - title: "Transformation auf die gerenderte Ausgabe anwenden"
        content: "Mit GroupDocs.Viewer für die .NET-API können Sie verschiedene Transformationen am gerenderten Ausgabedokument durchführen. Diese Transformationsoptionen geben Ihnen die Kontrolle darüber, wie Sie die gerenderte Ausgabe für die Anzeige präsentieren. Die verfügbaren Transformationen sind die Seitenrotationsoption, die Seitenneuordnungsoption und das Anwenden von Textwasserzeichen."

      # more_feature_loop
      - title: "Arbeiten mit Outlook-Datendateien"
        content: "GroupDocs.Viewer für die .NET-API kann die Elemente in Outlook-Datendateien (OST/PST) als PDF-, HTML- und Bilddateien darstellen. Unsere Viewer-API kann auch die Liste der Ordner abrufen, die in Outlook-Datendateien enthalten sind. Mit GroupDocs.Viewer für die .NET-API können Sie den Ordner angeben, der aus Outlook-Datendateien gerendert werden soll. Ebenso können Sie E-Mail-Nachrichten im OST/PST-Format als Anhänge erhalten. Mit GroupDocs.Viewer für .NET können Sie auch Nachrichten aus OST/PST-Formaten basierend auf Betreff, Inhalt oder Absender filtern."

      # more_feature_loop
      - title: "Arbeiten mit CAD-Dokumenten"
        content: "GroupDocs.Viewer für die .NET-API kann Modelle und alle nicht leeren Layouts rendern oder ein bestimmtes Layout einer CAD-Datei rendern. GroupDocs.Viewer für die .NET-API unterstützt auch das Kachel-Rendering oder das Rendern von CAD-Dokumenten anhand von Koordinaten in Bild, HTML oder PDF. Sie können auch Layerstatus für CAD-Dokumente abrufen."

############################# Testimonials ###############################
testimonials:
  enable: true

  testimonial:
    # testimonial item loop
    - name: "Mats Oustad"
      designation: "Senior Consultant/Partner at Novanet AS"
      content: "Nach der Implementierung und Verwendung von GroupDocs.Viewer für .NET im Projekt scheint es sehr gut zu funktionieren. Ich habe mit vielen Dokumenten getestet und bisher so gut. Alles, was ich darauf geworfen habe, wird gut gerendert und sieht genauso gut aus wie in einem PDF-Viewer oder MS Word."
              
    # testimonial item loop
    - name: "Martin Lasarga"
      designation: "Product Manager at Axentria ECM by G.S.I."
      content: "Exzellenter Service und hervorragende Produkte. Sie waren während des Implementierungsprozesses von GroupDocs.Viewer für .NET äußerst hilfreich und reaktionsschnell und können sie nicht genug empfehlen."

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Viewer bietet APIs zum Anzeigen von Dokumenten für andere beliebte Entwicklungsumgebungen"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Viewer for Java"
          image: "/border/groupdocs-viewer-java.svg"
          product: "GroupDocs.Viewer"
          platform: "Java"
          link: "/viewer/java/"

############################# Back to top ###############################
back_to_top:
  enable: true
---
