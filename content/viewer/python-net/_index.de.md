---
############################# Static ############################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: de
product: "Viewer"
product_tag: "viewer"
platform: "Python via .NET"
platform_tag: "python-net"

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
    # supported_platforms loop
    - title: "Python"
      tag: "python-net" 


############################# Head ############################
head_title: "Python Dokumentenviewer-API für PDF, Word, Excel, HTML, Bilder & E-Mails"
head_description: "Python Dokumentenviewer- und Dateirendering-API. Fügen Sie PDF-Viewer, Word-Viewer, Excel-Viewer, Bildbetrachter, HTML-Viewer und E-Mail-Viewer in Python-Anwendungen hinzu."

############################# Header ############################
title: "Eine leistungsstarke Python-API für die optimierte Dokumentenwiedergabe"
description: "Rendern und Anzeigen von über 180 Dokumentformaten (PDF, HTML, Bild) mit leistungsstarken APIs und vielfältigen Konfigurationsoptionen zum Entwickeln von Python-Anwendungen."
words:
  for: "for"

actions:
  main: "Kostenloser PyPI-Download"
  main_link: "https://pypi.org/project/groupdocs-viewer-net/"
  alt: "Lizenzierung"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/python-net"
  title: "Bereit anzufangen?"
  description: "Testen Sie die Funktionen von GroupDocs.Viewer kostenlos oder fordern Sie eine Lizenz an"

release:
  title: "Version {0} veröffentlicht"
  notes: "Schau was neu ist"
  downloads: "Downloads"
  link: "https://releases.groupdocs.com/viewer/python-net/release-notes/latest/"

code:
  title: "PDF-Dateien in Python rendern"
  more: "Mehr Beispiele"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Python-via-.NET"
  install: "pip install groupdocs-viewer-net"
  content: |
    ```python {style=abap}
    import groupdocs.viewer as gv
    import groupdocs.viewer.options as gvo
    hvo = gvo.HtmlViewOptions  
  
    // Ausgabe-HTML-Optionen festlegen, eine Datei pro Seite
    with gv.Viewer("resume.docx") as viewer:
      // Viewer instanziieren
      opts = hvo.for_embedded_resources("page_{0}.html")

      // PDF mit eingebetteten Ressourcen in HTML rendern
      viewer.view(opts)
    ```
############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Viewer auf einen Blick"
  description: "API zum Rendern, Anzeigen, Konvertieren von Dokumenten, Folien, Diagrammen und vielen anderen Dokumenttypen in Python-Anwendungen"
  features:
    # feature loop
    - title: "Dokumente effizient und zuverlässig anzeigen"
      content: "Mit der GroupDocs.Viewer-API können Sie Dokumente aller unterstützten Formate effizient in HTML, JPEG, PNG und PDF mit flexiblen und leistungsstarken Optionen rendern, während die Integrität von Inhalt und Dokumentstruktur erhalten bleibt. GroupDocs.Viewer für Python funktioniert auf Windows- und Linux-Plattformen."

    # feature loop
    - title: "Die meisten populären Datei- und Dokumentformate werden unterstützt"
      content: "Wir unterstützen das Rendern von über 180 der beliebtesten Datei- und Dokumentformate, darunter Word, Excel, PDF, PowerPoint, OpenDocument-Formate, Archive, Raster- und Vektorbilder, E-Books, Programmiersprachen und Markups sowie viele andere Dateitypen, einschließlich verschlüsselter Dateien mit Passwortschutz."

    # feature loop
    - title: "Anpassbare Ausgabe"
      content: "GroupDocs.Viewer ermöglicht nicht nur das Rendern des Dokuments, sondern auch die Steuerung, wie genau, welche Teile des Dokuments gerendert werden sollen oder nicht, wie sie gerendert werden sollen und verschiedene Transformationen auf die gerenderte Ausgabe angewendet werden können."

############################# Platforms ############################
platforms:
  enable: true
  title: "Plattformunabhängigkeit"
  description: "GroupDocs.Viewer für Python unterstützt die folgenden Betriebssysteme, Frameworks und Paketmanager"
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
    - title: "PyPI"
      image: "pypi"

############################# File formats ############################
formats:
  enable: true
  title: "Unterstützte Dateiformate"
  description: |
    GroupDocs.Viewer für Python via .NET unterstützt Operationen mit den folgenden Dateiformaten: [https://docs.groupdocs.com/viewer/python-net/supported-document-formats/](https://docs.groupdocs.com/viewer/python-net/supported-document-formats/).
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
  description: "Einige Anwendungsfälle typischer GroupDocs.Viewer für Python via Java-Operationen"
  items:
    # code sample loop
    - title: "DOCX in HTML rendern"
      content: |
        Die Eigenschaften der `HtmlViewOptions`-Klasse ermöglichen die Steuerung des Konvertierungsprozesses. Mehr dazu hier: [https://docs.groupdocs.com/viewer/python-net/rendering-to-html/](https://docs.groupdocs.com/viewer/python-net/rendering-to-html/). Sie können beispielsweise alle externen Ressourcen in die HTML-Ausgabedatei einbetten, die Ausgabedatei minimieren und für den Druck optimieren.
        {{< landing/code title="Python">}}
        ```python {style=abap}
        import groupdocs.viewer as gv
        import groupdocs.viewer.options as gvo 

        // Viewer instanziieren
        with gv.Viewer("resume.docx") as viewer:
          // Ausgabe-HTML-Optionen festlegen, eine Datei pro Seite
          viewOptions = gvo.HtmlViewOptions.for_embedded_resources("page_{0}.html")
          // DOCX mit eingebetteten Ressourcen in HTML rendern
          viewer.view(viewOptions)
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "PPTX in PDF exportieren"
      content: |
        Erstellen Sie eine Instanz der `PdfViewOptions`-Klasse und übergeben Sie sie an die `Viewer.view`-Methode, um eine PowerPoint-PPTX-Datei in PDF zu konvertieren. Die Eigenschaften der `PdfViewOptions`-Klasse ermöglichen die Steuerung des Konvertierungsprozesses. Details finden Sie im folgenden Abschnitt der Dokumentation: [https://docs.groupdocs.com/viewer/python-net/rendering-to-pdf/](https://docs.groupdocs.com/viewer/python-net/rendering-to-pdf/).
        {{< landing/code title="Python">}}
        ```python {style=abap}
        import groupdocs.viewer as gv
        import groupdocs.viewer.options as gvo  

        // Viewer instanziieren
        with gv.Viewer("presentation.pptx") as viewer:
          // Ausgabe-PDF-Optionen festlegen
          viewOptions = gvo.PdfViewOptions("presentation.pdf")
          // PPTX in PDF exportieren
          viewer.view(viewOptions)
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
