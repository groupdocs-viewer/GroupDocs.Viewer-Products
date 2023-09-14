---
############################# Static ##########################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

lang: de
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: ".NET Document Viewer API, Rendern von PDF-Word-Excel-Bild-HTML-Diagrammen"
head_description: "C# ASP.NET-Dateibetrachter und Rendering-API. Fügen Sie PDF-Viewer, Word-Viewer, Excel-Viewer, Bild-Viewer, HTML-Viewer und E-Mail-Viewer-Funktionen in .NET-Apps hinzu."

############################# Header ##########################
title: "Rendern und Anzeigen von Dokumenten über die .NET-API"
description: ".NET Document Viewer API zum Rendern von über 190 Dokumentformaten in PDF, HTML und Bild mit leistungsstarken Konfigurationsoptionen."
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Download Free Trial"
    link: "https://downloads.groupdocs.com/viewer/net"

############################# SubMenu #########################
submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Viewer for .NET"
        image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-viewer-net.png"
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
              text: "Unterstützung"

            # button loop
            - link: "https://products.groupdocs.app/viewer/total"
              text: "Live-Demo"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Preisgestaltung"

    right:
        link_download: "https://www.nuget.org/packages/GroupDocs.Viewer"
        link_learn: "https://docs.groupdocs.com/viewer/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    content: |
      Mit GroupDocs.Viewer für .NET-APIs können Sie leistungsstarke Anwendungen in C#, ASP.NET und anderen .NET-basierten Technologien erstellen, die Dokumente und Bilder in über 190 Dateiformaten rendern und anzeigen können, ohne dass externe Software installiert werden muss. Die Datei-Viewer-Bibliothek rastert die Dokumente und konvertiert sie dann in SVG+HTML+CSS, um das gesamte Dokument-Rendering-Erlebnis für die schnelle, textgetreue Anzeige von Geschäftsdokumenten, Bildern, Textdateien, Diagrammen, Grafiken, E-Mail-Anhängen und PDF-Dateien zu optimieren High-Fidelity in Ihren Anwendungen. Sie haben die Möglichkeit, Ihren Anwendungen Funktionen zum Anzeigen und Lesen von Dokumenten hinzuzufügen, um das gesamte Dokument, Teildokumente, bestimmte Seiten-/Zellbereiche oder einzelne Dokumentebenen mit oder ohne Anmerkungen und Kommentare für die unterstützten Dateiformate anzuzeigen.
       
      GroupDocs.Viewer für .NET speichert die gerenderten Dokumentausgaben standardmäßig auf der lokalen Festplatte zwischen. Auch jede Art von externem Cache-Speicher wird durch die Implementierung entsprechender Schnittstellen unterstützt – Amazon S3, Dropbox, Google Drive, Windows Azure, Redis oder andere.
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          Im Folgenden finden Sie eine Übersicht über GroupDocs.Viewer für .NET:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Überblick"
          content: |
            * Zeigen Sie über 190 Dokumenttypen an 
            * Holen Sie sich eine Datei im HTML-, Bild- oder PDF-Format 
            * Drehen und neu anordnen 
            * Wasserzeichen anwenden 
            * Cache für schnellen Prozess 
            * Fügen Sie benutzerdefinierte Schriftarten hinzu 
            * Anwenden von Codierungsstandards 
            * Benutzerdefinierter Eingabedatenhandler 
            * Rendern mit Änderungen verfolgen 
            * Als Responsive HTML rendern 
            * Rendern Sie PDF- und CAD-Ebenen 
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Viewer für .NET unterstützt die Anzeige aller gängigen Dokumentdateiformate. Fügen Sie mit nur wenigen Codezeilen PDF-Viewer, Microsoft Office Word, Excel-Tabellen, Bild-, HTML-, Outlook-E-Mail-, OneNote-, Projekt- und Grafikanzeigefunktionen in Ihre .NET-Anwendungen ein.

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
            - title: "Other Formats"
              content: |
                * **Seitenlayoutdateien:** PDF, TEX, XPS, OXPS
                * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG, OTG, FODP, FODG
                * **Durch Trennzeichen getrennte Werte:** CSV, TSV
                * **Netz:** HTML, MHT, MHTML
                * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
                * **PostScript:** PS, EPS
                * **Archiv:** ZIP, TAR, BZ2, GZ, RAR, RAR5
                * **Verschieden:** OBJ, EPUB, MOBI, DjVu, XML, VCF, VCARD, NUMBERS, NSF

        right:
          enable: true
          table:
            # table loop
            - title: "Bilder, Grafiken und Diagramme"
              content: |
                * **Bilder:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB
                * **Windows-Symbol:** ICO
                * **Skalierbare Vektorgrafiken:** SVG, CDR, CMX, IGS, SVGZ
                * **JPEG2000:** JP2, J2C, J2K, JPC, JPF, JPX, JPM
                * **Adobe Photoshop:** PSD, PSB
                * **Druckerbefehlssprache:** PCL
                * **Stereolithographie (3D-Druck):** STL
                * **Industry Foundation-Kurse:** IFC
                * **Medizinische Bildgebung:** DICOM
                * **Plotterunterlagen:** PLT, HPG
                * **Autodesk Design-Webformate:** DWF, DWG
                * **AutoCAD-Zeichnung:** DWT, IFC, STL, CF2
                * **ISFF-basiertes DGN (V7):** DGN

            # table loop
            - title: "Programmiersprachenformate"
              content: |
                * **C/C++/C#-Dateien:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
                * **Java/JavaScript-Dateien:** JAVA, JS, JSON, PROPERTIES
                * **Verschieden:** VB, PHP, SQL, PL, PY, PV, RB, RST, SASS, SCALA, SCM, SCRIPT, AS, AS3, ASM, BAT, CMAKE, CSS, DIFF, ERB, GROOVY, HAML, LESS, LOG, M, MAKE, MD, ML, MM, SH, SML, VIM, YAML

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Viewer für .NET unterstützt folgende Betriebssysteme, Frameworks und Paketmanager:
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Betriebssysteme"
              content: |
                * Microsoft Windows Server 2003 und höher 
                * Microsoft Windows XP und höher 
                * Microsoft Windows 10 und 11 
                * Linux (Ubuntu, OpenSUSE, CentOS und andere) 
                * Mac OS X 

            # table loop
            - icon: "fas fa-code"
              title: "Unterstützte Frameworks"
              content: |
                * .NET Framework 2.0 oder höher 
                * .NET Core 3.1 
                * .NET 5 oder höher 

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

############################# Features ############################
features:
    enable: true
    title: "GroupDocs.Viewer für .NET-Funktionen"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "Rasterisieren Sie Dokumente und konvertieren Sie sie in SVG, HTML und CSS"

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
        content: "Reduzieren Sie die CSS- und HTML-Ausgabe durch Entfernen von Kommentaren, zusätzlichen Leerzeichen usw."

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "Lesen Sie den in einem Quelldokument enthaltenen Text anhand seiner Koordinaten"

      # feature loop
      - icon: "fas fa-border-all"
        content: "Gitterlinien von Excel-Tabellen in der Ausgabedarstellung ein-/ausblenden"

      # feature loop
      - icon: "fas fa-wrench"
        content: "Geben Sie die Anzahl der Zeilen in einer Excel-Tabelle an, die auf jeder Seite gerendert werden sollen"

      # feature loop
      - icon: "fas fa-columns"
        content: "Ignorieren Sie leere Spalten beim Rendern von Tabellenkalkulationsdokumenten"

      # feature loop
      - icon: "fas fa-file-word"
        content: "Rendern Sie Word-Dokumente in HTML-Seiten, Bilder oder PDFs und verfolgen Sie Änderungen"

      # feature loop
      - icon: "fas fa-envelope"
        content: "Rendern Sie E-Mail-Anhänge als Originaldateien, Bilder oder in HTML-Darstellung"

      # feature loop
      - icon: "fas fa-print"
        content: "Legen Sie Druckbeschränkungen für PDF-Dokumente fest"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "Rendern Sie in ZIP-Archiven enthaltene Inhalte/Dateien als Anhänge"

      # feature loop
      - icon: "fas fa-lock"
        content: "Erhalten Sie Anhänge aus passwortgeschützten Dokumenten"

      # feature loop
      - icon: "fas fa-file-code"
        content: "Rendern Sie Dateiformate von Programmiersprachen als einfachen Text"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "Passen Sie die Hintergrundfarben beim Anzeigen von CAD-Zeichnungen an"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "Excel-Dokumente anzeigen und in PDF, HTML, JPG und PNG konvertieren"

      # feature loop
      - icon: "fas fa-heading"
        content: "Arbeitsblattnamen aus Excel-Datei abrufen – Tabellenspaltenüberschriften und Zeilennummern anzeigen"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "Anzeigen und Konvertieren von Microsoft Project-Dokumenten mit Notizen"

      # feature loop
      - icon: "fas fa-cube"
        content: "Konvertieren Sie CAD-Zeichnungen in SVG für ein besseres Anzeige- und Zoomerlebnis"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "Wählen Sie „Visio-Figuren ohne Schema rendern“."

    more_feature:
      # more_feature_loop
      - title: "Dokumente effizient und zuverlässig anzeigen"
        content: |
          Mit der GroupDocs.Viewer-API können Sie mehr als 190 Dokumentformate effizient und zuverlässig anzeigen, wobei die Integrität von Inhalt und Dokumentstruktur erhalten bleibt. Der folgende Beispielcode zeigt, wie einfach es ist, die HTML-Darstellung eines DOCX-Dokuments anzuzeigen:

          ```cs
          // Instantiate viewer
          using (Viewer viewer = new Viewer("invoice.docx"))
          {
              // Set view options
              HtmlViewOptions options = HtmlViewOptions.ForEmbeddedResources();
              // Convert file to HTML with embedded resources
              viewer.View(options);
          }
          ```
      # more_feature_loop
      - title: "Wenden Sie die Transformation auf die gerenderte Ausgabe an"
        content: "Mit der GroupDocs.Viewer für .NET-API können Sie verschiedene Transformationen am gerenderten Ausgabedokument durchführen. Mit diesen Transformationsoptionen können Sie steuern, wie Sie die gerenderte Ausgabe zur Anzeige präsentieren. Die verfügbaren Transformationen sind die Option zum Drehen der Seite, die Option zum Neuordnen der Seite und das Anwenden von Textwasserzeichen."

      # more_feature_loop
      - title: "Arbeiten mit Outlook-Datendateien"
        content: "GroupDocs.Viewer für .NET API kann die Elemente in Outlook-Datendateien (OST/PST) als PDF-, HTML- und Bilddateien rendern. Unsere Viewer-API bietet auch die Möglichkeit, die Liste der in Outlook-Datendateien enthaltenen Ordner abzurufen. Mithilfe der GroupDocs.Viewer für .NET-API können Sie den Ordner angeben, der aus Outlook-Datendateien gerendert werden soll. Ebenso können Sie E-Mail-Nachrichten im OST-/PST-Format als Anhang erhalten. Mit GroupDocs.Viewer für .NET können Sie außerdem Nachrichten aus OST/PST-Formaten nach Betreff, Inhalt oder Absender filtern."

      # more_feature_loop
      - title: "Arbeiten mit CAD-Dokumenten"
        content: "GroupDocs.Viewer für die .NET-API kann Modelle und alle nicht leeren Layouts rendern oder ein bestimmtes Layout einer CAD-Datei rendern. GroupDocs.Viewer für die .NET-API unterstützt auch das gekachelte Rendern oder das Rendern nach Koordinaten von CAD-Dokumenten in Bild, HTML oder PDF. Sie können auch Layerstatus für CAD-Dokumente abrufen."

############################# Testimonials ###############################
testimonials:
  enable: true

  testimonial:
    # testimonial item loop
    - name: "Margot Baill"
      designation: "Produktentwicklungsdirektor bei Hireology"
      content: "Die Integration von GroupDocs.Viewer für die Cloud-API war mit ihrem fantastischen Ruby SDK einfach. Es gibt nicht viele Unternehmen, die bereit sind, mit uns an unseren Wünschen zu arbeiten. Es ist eine tolle Partnerschaft."

    # testimonial item loop
    - name: "Mats Oustad"
      designation: "Senior Consultant/Partner bei Novanet AS"
      content: "Nach der Implementierung und Verwendung von GroupDocs.Viewer für .NET im Projekt scheint es sehr gut zu funktionieren. Ich habe es mit vielen Dokumenten getestet und bisher so gut. Alles, was ich darauf geworfen habe, wird gut gerendert und sieht genauso gut aus wie in einem PDF-Viewer oder MS Word."
              
    # testimonial item loop
    - name: "Martin Lasarga"
      designation: "Produktmanager bei Axentria ECM von G.S.I."
      content: "Exzellenter Service und hervorragende Produkte. Sie waren während des GroupDocs.Viewer für .NET-Implementierungsprozesses äußerst hilfsbereit und reaktionsschnell und können sie nur wärmstens empfehlen."

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Viewer bietet APIs zum Anzeigen von Dokumenten für andere gängige Entwicklungsumgebungen"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Viewer for Java"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-viewer-java.png"
          product: "GroupDocs.Viewer"
          platform: "Java"
          link: "/viewer/java/"

############################# Back to top ###############################
back_to_top:
  enable: true
---
