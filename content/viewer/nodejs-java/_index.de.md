---
############################# Static ############################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: de
product: "Viewer"
product_tag: "viewer"
platform: "Node.js via Java"
platform_tag: "nodejs-java"

############################# Drop-down ############################
supported_platforms:
  items:
    # supported_platforms loop
    - title: ".NET"
      tag: "net"
    # supported_platforms loop
    - title: "Java"
      tag: "java"
    # supported_platforms loop
    - title: "Node.js"
      tag: "nodejs-java" 


############################# Head ############################
head_title: "Node.js Document Viewer API für PDF Word Excel HTML Bilder und E-Mails"
head_description: "Node.js Dokumentbetrachter und Datei-Rendering-API. Fügen Sie PDF-Viewer, Word-Viewer, Excel-Viewer, Bild-Viewer, HTML-Viewer und E-Mail-Viewer in JavaScript-Anwendungen hinzu."

############################# Header ############################
title: "Node.js-API zum Rendern und Anzeigen von Dokumenten"
description: "Document Viewer-Bibliothek zur Entwicklung von JavaScript-Anwendungen, die Multiformatdokumente nativ rendern, anzeigen und bearbeiten und über 180 Dateiformate unterstützen."
words:
  for: "for"

actions:
  main: "Kostenloser NPM-Download"
  main_link: "https://www.npmjs.com/package/@groupdocs/groupdocs.viewer"
  alt: "Lizenzierung"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/nodejs-java"
  title: "Bereit anzufangen?"
  description: "Testen Sie die Funktionen von GroupDocs.Viewer kostenlos oder fordern Sie eine Lizenz an"

release:
  title: "Version {0} veröffentlicht"
  notes: "Schau was neu ist"
  downloads: "Downloads"
  link: "https://releases.groupdocs.com/viewer/nodejs-java/release-notes/latest/"

code:
  title: "Rendern Sie PDF-Dateien in JavaScript"
  more: "Mehr Beispiele"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Node.js-via-Java"
  install: "npm i @groupdocs/groupdocs.viewer"
  content: |
    ```javascript {style=abap}   
    //Set output HTML options, one file per page
    const viewOptions = HtmlViewOptions.forEmbeddedResources()

    // Instantiate Viewer
    const viewer = new Viewer("resume.pdf")

    // Render PDF to HTML with embedded resources
    viewer.view(viewOptions)
    viewer.close()
    ```
############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Viewer auf einen Blick"
  description: "API zum Rendern, Anzeigen und Konvertieren von Dokumenten, Folien, Diagrammen und vielen anderen Dokumenttypen in Node.js-Anwendungen"
  features:
    # feature loop
    - title: "Dokumente effizient und zuverlässig einsehen"
      content: "Mit der GroupDocs.Viewer-API können Sie Dokumente aller unterstützten Formate mit flexiblen und leistungsstarken Optionen effizient in HTML, JPEG, PNG und PDF rendern und dabei die Integrität von Inhalt und Dokumentstruktur bewahren. GroupDocs.Viewer für Node.js funktioniert auf Windows- und Linux-Plattformen."

    # feature loop
    - title: "Die gängigsten Datei- und Dokumentformate werden unterstützt"
      content: "Wir unterstützen das Rendern der 180 gängigsten Datei- und Dokumentformate, darunter Word, Excel, PDF, PowerPoint, die OpenDocument-Formatfamilie, Archive, Raster- und Vektorbilder, E-Books, Programmiersprachen und Markups sowie viele andere Dateitypen, einschließlich verschlüsselter Dateien Dateien mit Passwortschutz."

    # feature loop
    - title: "Anpassbare Ausgabe"
      content: "GroupDocs.Viewer ermöglicht nicht nur das Rendern des Dokuments, sondern auch die Steuerung, wie genau, welche Teile des Dokuments gerendert werden sollen oder jetzt, wie sie gerendert werden sollen, und verschiedene Transformationen auf die gerenderte Ausgabe anzuwenden."

############################# Platforms ############################
platforms:
  enable: true
  title: "Plattformunabhängigkeit"
  description: "GroupDocs.Viewer für Node.js unterstützt die folgenden Betriebssysteme, Frameworks und Paketmanager"
  items:
    # platform loop
    - title: "Amazon"
      image: "amazon"
    # platform loop
    - title: "Docker"
      image: "docker"
    # platform loop
    - title: "Azure"
      image: "azure"
    # platform loop
    - title: "Eclipse"
      image: "eclipse"
    # platform loop
    - title: "IntelliJ"
      image: "intellij"
    # platform loop
    - title: "Windows"
      image: "windows"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "NPM"
      image: "npm"

############################# File formats ############################
formats:
  enable: true
  title: "Unterstützte Dateiformate"
  description: |
    GroupDocs.Viewer für Node.js über Java unterstützt Vorgänge mit den folgenden [Dateiformaten](https://docs.groupdocs.com/viewer/nodejs-java/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office, OpenDocument und Textformate
        * **Word:** DOC, DOCX, DOCM, DOT, DOTX, DOTM, RTF, TXT
        * **Excel:** XLS, XLSX, XLSM, XLSB, XLTM, XLT, XLTM, XLTX
        * **PowerPoint:** PPT, PPTX, PPS, PPSX, PPSM, POT, POTM, POTX, PPTM        
        * **Project:** MPP, MPT, MPX
        * **Outlook:** MSG, EML, EMLX, PST, OST
        * **OneNote:** ONE
        * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG
        * **Fixed Page Layout:** PDF, TEX, XPS, OXPS
        * **e-Books:** EPUB, MOBI, DjVu
        * **Delimiter-Separated Values:** CSV, TSV
    # group loop
    - color: "blue"
      content: |
        ### Bilder, Grafiken und Diagramme
        * **Rasterbilder:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
        * **Windows Icon:** ICO
        * **Scalable Vector Graphics:** SVG, CDR, CMX, IGS, SVGZ        
        * **Adobe Photoshop:** PSD, PSB        
        * **Stereo Lithography (3D Printing):** STL        
        * **Medical Imaging:** DICOM
        * **Plotter Documents:** PLT, HPG
        * **Autodesk Design Web Formats:** DWF, DWG
        * **AutoCAD Drawing:** DWT, IFC, STL, CF2        
      # group loop
    - color: "red"
      content: |
        ### Andere        
        * **Netz:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **Archiv:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **Andere:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "GroupDocs.Viewer-Funktionen"
  description: "PDF- und Office-Dokumente nahtlos rendern, anzeigen und konvertieren"

  items:
    # feature loop
    - icon: "viewhtml"
      title: "Dokumente in HTML anzeigen"
      content: "Konvertieren Sie Dokumente jeglicher Art mit CSS und SVG in ein HTML-Dokument, das in jedem modernen Webbrowser angezeigt werden kann."

    # feature loop
    - icon: "rasterize"
      title: "Dokumente rastern"
      content: "Rastern Sie jedes unterstützte Dokumentformat in ein Rasterbild, mit anpassbarem Bildformat und Komprimierungsqualität."

    # feature loop
    - icon: "sourcecode"
      title: "Programmiercodes rendern und hervorheben"
      content: "Unterstützung aller gängigen Programmier-, Skript- und Auszeichnungssprachen mit der Möglichkeit, deren Syntax zu analysieren und hervorzuheben."

    # feature loop
    - icon: "convertpdf"
      title: "In PDF konvertieren"
      content: "Dokumente in jedem unterstützten Format können mit anpassbaren Optionen einfach konvertiert und im PDF-Format gespeichert werden."

    # feature loop
    - icon: "transform"
      title: "Wenden Sie Transformationen an"
      content: "Das Ausgabedokument kann während des Renderns transformiert werden – Seiten können gedreht und/oder neu angeordnet werden und Textwasserzeichen können darüber platziert werden."

    # feature loop
    - icon: "adjustment"
      title: "Anpassung der HTML-Ausgabe"
      content: "Ausgabe-HTML-Dokumente, die vom GroupDocs.Viewer generiert werden, können sehr fein abgestimmt werden: Sie können im Stream oder in der Datei gespeichert werden, mit externen oder eingebetteten Ressourcen, Rückrufen usw."

    # feature loop
    - icon: "complex"
      title: "Unterstützung komplexer Dokumentenstrukturen"
      content: "GroupDocs.Viewer unterstützt nicht nur einzelne Dokumente, sondern auch Dateien, die intern eine Liste oder hierarchische Struktur von Dokumenten enthalten, wie E-Mail-Nachrichten mit Anhängen, ZIP-Archive mit internen Dateien in Ordnern, mehrseitige TIFF-Bilder usw."

    # feature loop
    - icon: "optimization"
      title: "Optimierungsmöglichkeiten"
      content: "GroupDocs.Viewer enthält ein anpassbares Cache-Subsystem, das die Ladezeit durch die Verwendung der zwischengespeicherten Versionen der Dokumente verkürzen kann. Außerdem ermöglicht eine Reihe verschiedener Optionen für verschiedene Formate, einige unnötige Teile oder Aspekte von Dokumenten aus der Darstellung auszuschließen (Schriftarten, ausgeblendete Arbeitsblätter, E-Mail-Anhänge), um die Gesamtleistung zu optimieren"

    # feature loop
    - icon: "passwordprotected"
      title: "Unterstützung passwortgeschützter Dokumente"
      content: "GroupDocs.Viewer ermöglicht das Öffnen verschlüsselter Dokumente verschiedener Typen: PDF, WordProcessing, Tabellenkalkulation, Präsentation und andere, indem in den Ladeoptionen ein Passwort angegeben wird."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Codebeispiele"
  description: "Einige Anwendungsfälle typischer GroupDocs.Viewer für Node.js über Java-Operationen"
  items:
    # code sample loop
    - title: "Rendern Sie DOCX in HTML"
      content: |
        Mit den Eigenschaften der Klasse „HtmlViewOptions“ können Sie den Konvertierungsprozess steuern, mehr dazu [hier](https://docs.groupdocs.com/viewer/nodejs-java/rendering-to-html/). Sie können beispielsweise alle externen Ressourcen in die Ausgabe-HTML-Datei einbetten, die Ausgabedatei verkleinern und für den Druck optimieren.
        {{< landing/code title="JavaScript">}}
        ```javascript {style=abap}
        import { Viewer, HtmlViewOptions } from '@groupdocs/groupdocs.viewer'

        //Set output HTML options, one file per page
        const viewOptions = HtmlViewOptions.forEmbeddedResources()

        // Instantiate Viewer
        const viewer = new Viewer("resume.docx")

        // Render PDF to HTML with embedded resources
        viewer.view(viewOptions)
        viewer.close()
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Exportieren Sie PPTX in PDF"
      content: |
        Erstellen Sie eine „PdfViewOptions“-Klasseninstanz und übergeben Sie sie an die „Viewer.view“-Methode, um eine PowerPoint PPTX-Datei in PDF zu konvertieren. Mit den Eigenschaften der Klasse „PdfViewOptions“ können Sie den Konvertierungsprozess steuern. Sie können beispielsweise die ausgegebene PDF-Datei schützen, ihre Seiten neu anordnen und die Qualität der Dokumentbilder festlegen. Einzelheiten finden Sie im [folgenden Dokumentationsabschnitt](https://docs.groupdocs.com/viewer/nodejs-java/rendering-to-pdf/).
        {{< landing/code title="JavaScript">}}
        ```javascript {style=abap}   
        import { Viewer, PdfViewOptions } from '@groupdocs/groupdocs.viewer'

        //Set output PDF options
        const viewOptions = new PdfViewOptions("presentation.pdf")

        // Instantiate Viewer
        const viewer = new Viewer("presentation.pptx")

        // Render PDF to HTML with embedded resources
        viewer.view(viewOptions)
        viewer.close()
        ```
        {{< /landing/code >}}
############################# Reviews ############################
# reviews:
# enable: true
# title: "GroupDocs-Produktbewertungen"
# description: "Verlassen Sie sich nicht nur auf unser Wort. Sehen Sie, was andere Entwickler über unsere APIs sagen"

# items:
#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "Exzellenter Service und hervorragende Produkte. Sie waren während des GroupDocs.Viewer für .NET-Implementierungsprozesses äußerst hilfsbereit und reaktionsschnell und können sie nur wärmstens empfehlen."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "Nach der Implementierung und Verwendung von GroupDocs.Viewer für .NET im Projekt scheint es sehr gut zu funktionieren. Ich habe es mit vielen Dokumenten getestet und bisher so gut. Alles, was ich darauf geworfen habe, wird gut gerendert und sieht genauso gut aus wie in einem PDF-Viewer oder MS Word."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---
