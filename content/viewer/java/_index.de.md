---
############################# Static ############################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

product: "Viewer"
product_tag: "viewer"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "Java Document Viewer API für PDF, Word, Excel, HTML, Bilder und E-Mails"
head_description: "API zum Betrachten von Java-Dokumenten und zum Rendern von Dateien. Fügen Sie PDF-Viewer, Word-Viewer, Excel-Viewer, Bild-Viewer, HTML-Viewer, E-Mail-Viewer in Java-Anwendungen hinzu."

############################# Header ############################
title: "Java-API zum Rendern und Anzeigen von Dokumenten"
description: "Document Viewer-Bibliothek zur Entwicklung von Java-Anwendungen, die Dokumente in mehreren Formaten nativ rendern, anzeigen und bearbeiten und mehr als 170 Dateiformate unterstützen."
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Download kostenlose Testversion"
    link: "https://downloads.groupdocs.com/viewer/java"

############################# SubMenu ############################
submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Viewer for Java"
        image: "/border/groupdocs-viewer-java.svg"
        product: "GroupDocs.Viewer"
        platform: "Java"

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
            - link: "https://purchase.groupdocs.com/pricing/viewer/java"
              text: "Preisgestaltung"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/java"
        link_learn: "https://docs.groupdocs.com/viewer/java/"
        link_buy: "https://purchase.groupdocs.com"

############################# Überblick ############################
overview:
    enable: true
    content: |
      GroupDocs.Viewer für Java kombiniert einen leistungsstarken Satz von Dokument-Viewer-APIs, um Bilder und Dokumentformate in Ihren Java-Anwendungen anzuzeigen, ohne dass zusätzliche Software installiert werden muss. Es rastert die Dokumente nativ und konvertiert sie in SVG+HTML+CSS, um die Qualität der Dokumentenanzeige zu verbessern und gleichzeitig eine High-Fidelity-Ausgabe in Echttext zu liefern. Verwenden der Dokument-Rendering-API – schnelles Anzeigen von PDF-, HTML-, XML-, Microsoft Office Word-, Excel-Arbeitsblättern, PowerPoint-Präsentationen, Outlook-E-Mails, Visio-Diagrammen, Project, Metadateien, Bildern und verschiedenen anderen Dateiformaten mit Leichtigkeit und weniger Programmierrisiken. Es kann auch passwortgeschützte Dateien anzeigen und nach dem Rendern die Dokumentdarstellung als HTML-, Bild- oder PDF-Formular erhalten. Unsere Datei-Viewer-Bibliothek ist sehr anpassbar, da Sie damit das gesamte Dokument anzeigen oder teilweise rendern können, um den Prozess zu beschleunigen. Über GroupDocs.Viewer for Java API können Sie Seiten oder bestimmte Zellbereiche in einer Tabelle anzeigen oder sogar eine einzelne Dokumentebene in Formaten wie PDF und CAD rendern.
        
      GroupDocs.Viewer for Java API ermöglicht Ihnen das Rendern von Dokumenten mit/ohne Anmerkungen oder Kommentaren für unterstützte Dateiformate. Außerdem können Sie benutzerdefinierte Schriftartenverzeichnisse hinzufügen und grundlegende Dokumentinformationen wie Dateityp, Erweiterung, Name, Seitenzahl usw. extrahieren.
        
      GroupDocs.Viewer für Java ist mit allen Java-Versionen kompatibel und unterstützt gängige Betriebssysteme (Windows, Linux, macOS), die Java-Runtime ausführen können.
    tabs:
      enable: true     
      
      ## TAB ONE ##
      tab_one:
        description: |
          Nachfolgend finden Sie eine Übersicht über GroupDocs.Viewer für Java:

        right:
          enable: true
          icon: "fab fa-html5"
          title: "Überblick"
          content: |
            * Zeigen Sie über 50 Dokumenttypen an
            * Holen Sie sich HTML, Bild, PDF-Version
            * Drehen und neu anordnen
            * Wasserzeichen anwenden
            * Cache für schnellen Prozess
            * Fügen Sie benutzerdefinierte Schriftarten hinzu
            * Wenden Sie Codierungsstandards an
            * Benutzerdefinierter Eingabedaten-Handler
            * Rendern mit Änderungen nachverfolgen
            * Rendern als Responsive HTML
            * Rendern Sie PDF- und CAD-Ebenen
            * Geschützte Dateien rendern
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Viewer für Java unterstützt alle gängigen [Dokumentdateiformate](https://docs.groupdocs.com/viewer/java/supported-document-formats/) einschließlich: Microsoft Office, Bilder, Diagramme und viele andere.

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
          GroupDocs.Viewer for Java unterstützt das Folgen Betriebssysteme, Frameworks & Paket-Managers:
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Betriebssysteme"
              content: |
                * Microsoft Windows Desktop
                * Microsoft Windows Server
                * Linux
                * MacOS

            # table loop
            - icon: "fas fa-code"
              title: "Unterstützte Frameworks"
              content: |
                * Java 7 (1.7) und höher

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-cogs"
              title: "Entwicklungsumgebungen"
              content: |
                * NetBeans
                * IntelliJ IDEA
                * Eclipse
            # table loop
            - icon: "fas fa-tools"
              title: "Build-Automatisierungstool"
              content: |
                * Maven

############################# Merkmale ############################
features:
    enable: true
    title: "GroupDocs.Viewer for Java Merkmale"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "Viewer für HTML, PDF, Bilder, Word, Excel und andere Dokumentformate"

      # feature loop
      - icon: "fas fa-eye"
        content: "Rendern Sie AutoCAD-Zeichnungsdateien (DWG) in das SVG-Format"

      # feature loop
      - icon: "fas fa-bolt"
        content: "Passen Sie die Hintergrundfarbe der konvertierten Datei an"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "Rasterize and Dokumente konvertieren into SVG, HTML & CSS"

      # feature loop
      - icon: "fas fa-code"
        content: "Holen Sie sich eine HTML-, Bild- oder PDF-Darstellung von Dokumenten durch Rendern"

      # feature loop
      - icon: "fas fa-cloud"
        content: "Zwischengespeicherte Versionen von Dokumenten, um die Ladezeit zu verkürzen"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "Konfigurieren Sie benutzerdefinierte Schriftartenverzeichnisse"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "Wenden Sie Codierungsstandards zu Word-, Excel- und E-Mail-Dokumenten"

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "Rendern Sie Dokumente remote auf FTP oder im Cloud-Speicher"

      # feature loop
      - icon: "fas fa-border-all"
        content: "Anmerkungen und Kommentare beim Rendern entfernen oder beibehalten"

      # feature loop
      - icon: "fas fa-wrench"
        content: "Dokumentseiten als separate HTML-Seiten rendern"

      # feature loop
      - icon: "fas fa-columns"
        content: "Rendern Sie ausgeblendete Folien und Seiten und wenden Sie die Seitenneuordnung auf das gerenderte Dokument an"

      # feature loop
      - icon: "fas fa-file-word"
        content: "Seitenbereich, bestimmte Seiten oder alle Seiten in HTML rendern"

      # feature loop
      - icon: "fas fa-envelope"
        content: "Dokumentkommentare rendern oder ausblenden"

      # feature loop
      - icon: "fas fa-print"
        content: "Responsives HTML für einige Dokumentformate durch Rendern erstellen"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "Reduzieren Sie die resultierende Dateigröße von gerendertem HTML, indem Sie Schriftarten ausschließen"

      # feature loop
      - icon: "fas fa-lock"
        content: "Entfernen Sie Kommentare, zusätzliche Leerzeichen usw., um Ausgabe-HTML und -CSS zu minimieren"

      # feature loop
      - icon: "fas fa-file-code"
        content: "Verwenden Sie die Koordinaten des Quelldokuments, um den enthaltenen Text zu lesen"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "Zellrahmen in Excel-Tabellen der gerenderten Ausgabe anzeigen/ausblenden"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "Rendern Sie eine bestimmte Anzahl von Zeilen jeder Seite in einer Excel-Tabelle"

      # feature loop
      - icon: "fas fa-heading"
        content: "Rendermodell und alle nicht leeren Layouts oder ein bestimmtes Layout einer CAD-Datei"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "Rendern Sie die Elemente in Outlook-Datendateien (OST/PST) als PDF"

      # feature loop
      - icon: "fas fa-cube"
        content: "Kachel-Rendering oder Rendern nach Koordinaten von CAD-Dokumenten als Bild, HTML oder PDF"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "Legen Sie Druckeinschränkungen beim Rendern in PDF fest"

    more_feature:
      # more_feature_loop
      - title: "Effiziente und zuverlässige API zum Anzeigen von Dokumenten"
        content: |
          GroupDocs.Viewer for Java API kann zum Anzeigen, Rendern und Anzeigen von Dokumenten in mehr als 150 verschiedenen Dateiformaten verwendet werden. Dies geschieht zuverlässig und effizient, wobei sowohl der Inhalt als auch die Struktur des Dokuments intakt bleiben. Das folgende Beispiel zeigt, wie einfach GroupDocs.Viewer für die Java-API eine DOCX-Datei mit Java als Bilddatei rendert:
          
          ```java
          // Viewer initialisieren
          Viewer viewer = new Viewer("sample.docx");
          // Ansichtsoptionen erstellen
          PdfViewOptions viewOptions = new PdfViewOptions();
          // Datei in PDF konvertieren und Ausgabe im aktuellen Verzeichnis prüfen
          viewer.view(viewOptions);
          ```
      # more_feature_loop
      - title: "Transformationen beim Rendern von Dokumenten durchführen"
        content: "GroupDocs.Viewer for Java API bietet Ihnen verschiedene Transformationsoptionen, die auf das gerenderte Dokument angewendet werden können, um eine individuellere Ansicht und Anzeige zu erhalten. Sie können Seiten drehen, indem Sie den Winkel angeben. Sie können die Reihenfolge der gerenderten Seiten festlegen. Wenden Sie bestimmten Text als Wasserzeichen auf gerenderte Seiten oder Bilder an. Über die GroupDocs.Viewer for Java-API haben Sie auch die Möglichkeit, benutzerdefinierte Schriftarten zum wiedergegebenen Dokument hinzuzufügen."

      # more_feature_loop
      - title: "Arbeiten mit E-Mail-Anhängen"
        content: "Mit GroupDocs.Viewer for Java API können Sie bestimmte oder alle Anhänge einer E-Mail abrufen. Sobald Sie die erforderlichen E-Mail-Anhänge erhalten haben, können Sie diese angehängten Dateien in Bilder oder HTML umwandeln."

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Viewer bietet APIs zum Anzeigen von Dokumenten für andere beliebte Entwicklungsumgebungen"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Viewer for .NET"
          image: "/border/groupdocs-viewer-net.svg"
          product: "GroupDocs.Viewer"
          platform: ".NET"
          link: "/viewer/net/"

############################# Back to top ###############################
back_to_top:
  enable: true
---