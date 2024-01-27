---
############################# Static ############################
layout: "family"
date: 2023-12-20T06:39:57
draft: false

product: "Viewer"
product_tag: "viewer"

############################# Head ############################
head_title: "API zum Rendern und Anzeigen von Dokumenten | On-Premise-API und Online-Service"
head_description: "Rendern und betrachten Sie Word-, PDF-, Excel-, Powerpoint- oder Bilddateien einfach und kostenlos"

############################# Header ############################
title: "Einfaches Rendern und Anzeigen von Dokumenten"
description: |
  Leistungsstarke Viewer-API zum Rendern verschiedener Dateien in PDF, HTML und Bild.

  Laden Sie Dokumente aus verschiedenen Quellen, einschließlich Dateien, Streams, URLs, FTP-Servern, Amazon S3, Azure Blob Storage und mehr.

  Generieren Sie reaktionsfähige HTML-Seiten, schützen Sie die ausgegebenen PDF-Dateien und ordnen Sie ihre Seiten neu an, drehen Sie Seiten, rendern Sie bei Bedarf Notizen und Kommentare.
  

############################# Platforms ############################
supported_platforms:
  enable: true  
  head_title: "Wählen Sie Ihre Plattform"
  title: "Unterstützte Plattformen"
  description: "Die GroupDocs.Viewer-Bibliothek unterstützt die folgenden Betriebssysteme und Frameworks"
  details_link_title: "Erfahren Sie mehr"
  items:
    # supported_platforms loop
    - title: ".NET"
      description: "GroupDocs.Viewer for .NET"
      color: "blue"
      tag: "net"
      link: "/viewer/net/"
      features_link: "https://docs.groupdocs.com/viewer/net/system-requirements/"
      features:
        # features loop
        - content: ".NET Framework 4.6.2+  <br>  .NET Core 3.1  <br>  .NET 6+"
          rows: "3"
        # features loop
        - content: "Windows, Linux"
          rows: "1"
        # features loop
        - content: "180+ file formats"
          rows: "1"
        # features loop
        - content: "UI package for ASP.NET Core"
          rows: "1"
        # features loop
        - content: "ASP.NET WebForms Demo  <br>  ASP.NET MVC Demo  <br>  ASP.NET Core Demo"
          rows: "3"
    
    # supported_platforms loop
    - title: "Java"
      description: "GroupDocs.Viewer for Java"
      color: "red"
      tag: "java"
      link: "/viewer/java/"
      features_link: "https://docs.groupdocs.com/viewer/java/system-requirements/"
      features:
        # features loop
        - content: "J2SE 8.0 (1.8)+"
          rows: "3"
        # features loop
        - content:  "Windows, Linux, macOS"
          rows: "1"       
        # features loop
        - content:  "180+ file formats"
          rows: "1"
        # features loop
        - content:  "UI package for Spring and Dropwizard"
          rows: "1"
        # features loop
        - content:  "Spring Demo  <br>  Dropwizard demo"
          rows: "3"

    # supported_platforms loop
    - title: "Node.js"
      description: "GroupDocs.Viewer for Node.js"
      color: "green"
      tag: "nodejs-java"
      link: "/viewer/nodejs-java/"
      features_link: "https://docs.groupdocs.com/viewer/nodejs-java/system-requirements/"
      features:
        # features loop
        - content: "Node.js 16+  <br>  and J2SE 8.0 (1.8)+"
          rows: "3"
        # features loop
        - content:  "Windows, Linux, macOS"
          rows: "1"
        # features loop
        - content:  "180+ file formats"
          rows: "1"
        # features loop
        - content:  "UI package - coming soon "
          rows: "1" 
        # features loop
        - content:  "Demo - coming soon "
          rows: "3" 



############################# Features ############################

features:
  enable: true
  title: "Funktionsumfang von GroupDocs.Viewer"
  description: "API zum Rendern von Dateien verschiedener Typen wie HTML, PDF, PNG und JPEG in Anwendungen, um sie ohne Software von Drittanbietern anzuzeigen."

  items:
    # feature loop
    - icon: "view"
      title: "Dokumente und Bilder ansehen"
      content: "Zeigen Sie Dokumente an, indem Sie sie als HTML-, PDF-, PNG- und JPEG-Dateien rendern."
    # feature loop
    - icon: "password"
      title: "Öffnen Sie geschützte Dokumente"
      content: "Geben Sie ein Passwort an, um verschlüsselte Dokumente zu öffnen."

    # feature loop
    - icon: "load"
      title: "Laden Sie Dateien von überall"
      content: "Laden Sie Dokumente aus verschiedenen Dateien, URLs, FTP-Servern, Amazon S3 und mehr."
    
    # feature loop
    - icon: "pages"
      title: "Rendern Sie alle oder bestimmte Seiten"
      content: "Geben Sie einen Bereich von Seitenzahlen an, die gerendert werden sollen."


############################# Code samples ############################
code_samples:
  enable: true
  title: "GroupDocs.Viewer-Codebeispiele"
  description: "Einige Anwendungsfälle typischer GroupDocs.Viewer-Vorgänge in C#, Java, TypeScript"
  items:
    # code sample loop
    - title: "So rendern Sie DOCX-Dateien in PDF"
      content: |
        Rendern Sie DOCX-Dokumente in PDF, ohne dass Microsoft Word oder andere Software installiert ist. Laden Sie einfach DOCX-Dateien in Ihre .NET-Anwendung und zeigen Sie sie an, unabhängig davon, ob es sich um eine Web- oder Desktop-Anwendung handelt. Hier ist ein Beispiel für das Rendern einer DOCX-Datei in PDF: 
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Laden Sie die DOCX-Datei zum Rendern
            using (Viewer viewer = new Viewer("sample.docx"))
            {
              // Rendern Sie DOCX in eine PDF-Datei
              PdfViewOptions viewOptions = new PdfViewOptions();
              viewer.View(viewOptions);
            }
            ```
        - language: "Java"
          color: "red"
          content: |
            ```java {style=abap}   
            import com.groupdocs.viewer.Viewer;
            import com.groupdocs.viewer.options.PdfViewOptions;
            // ...
            // Laden Sie die DOCX-Datei zum Rendern
            try (Viewer viewer = new Viewer("sample.docx")) {
                // Rendern Sie DOCX in eine PDF-Datei
                PdfViewOptions viewOptions = new PdfViewOptions();
                viewer.view(viewOptions);
            }
            ```
        - language: "TypeScript"
          color: "green"
          content: |
            ```javascript {style=abap}  
            // Laden Sie die DOCX-Datei zum Rendern
            const viewer = new groupdocs.viewer.Viewer("sample.docx")
            
            // Rendern Sie DOCX in eine PDF-Datei
            const viewOptions = groupdocs.viewer.PdfViewOptions(output.pdf)
            viewer.view(viewOptions)
            ```


############################# Formats ############################
formats:
  enable: true
  title:  "Über 180 Dateiformate werden unterstützt"
  description: "GroupDocs.Viewer unterstützt Vorgänge mit den gängigsten [Dateiformaten](https://docs.groupdocs.com/viewer/net/supported-document-formats/)" 



############################# Metrics ############################

metrics:
  enable: true
  title: "Detaillierte Kennzahlen und statistische Erkenntnisse"
  description: "Tauchen Sie ein in eine detaillierte Aufschlüsselung unserer Schlüsselzahlen und bieten Sie umfassende Kennzahlen und statistische Einblicke in unsere Erfolge, Auswirkungen und unser Wachstum."

  items:
    # metrics loop
    - number: "180+"
      title: "Unterstützte Formate"
      content: "Sehen Sie sich problemlos über 180 Dateiformate an, darunter Dokumente, Bilder und CAD-Zeichnungen. Überwinden Sie Kompatibilitätsbarrieren und greifen Sie mit unserer umfassenden Anzeigelösung mühelos auf verschiedene Dateien zu."

    # metrics loop
    - number: "1.0M"
      title: "NuGet-Downloads"
      content: "Unsere NuGet-Paketlösung hat sich zu einer vertrauenswürdigen und weit verbreiteten Ressource in der Entwicklergemeinschaft entwickelt und bietet nahtlose Integration und wertvolle Funktionalität für unzählige Projekte."

    # metrics loop
    - number: "10+"
      title: "Bibliotheken"
      content: "Unser Produkt umfasst mehr als 10 Bibliotheken und bietet erweiterte Funktionen zur Optimierung der Leistung. Diese Bibliotheken sind darauf ausgelegt, unterschiedliche Entwicklungsanforderungen mit beispiellosen Fähigkeiten zu erfüllen."
    
    # metrics loop
    - number: "100+"
      title: "Zufriedene Kunden"
      content: "Wir beliefern die bekanntesten Marken rund um den Globus. Entdecken Sie, warum Hunderte GroupDocs.Viewer lieben! Entdecken Sie nahtlose Navigation, bequeme Zusammenarbeit und beispiellose Benutzerfreundlichkeit. Jetzt beitreten!"



############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "Unsere zufriedenen Kunden"
  description: "GroupDocs-Bibliotheken werden von weltweit bekannten und angesehenen Marken auf der ganzen Welt eingesetzt."

  items:
    # customers loop
    - title: "BenQ Corporation"
      logo: "benq"
    # customers loop
    - title: "Nasdaq Stock Market"
      logo: "nasdaq"
    # customers loop
    - title: "AT&T Inc."
      logo: "att"
    # customers loop
    - title: "AstraZeneca"
      logo: "astrazeneca"
    # customers loop
    - title: "Central Bank of Argentina"
      logo: "argentinacentralbank"
    # customers loop
    - title: "Roche Holding AG"
      logo: "roche"
    # customers loop
    - title: "Capita"
      logo: "capita"
    # customers loop
    - title: "Axa S.A."
      logo: "axa"
    # customers loop
    - title: "Instructure Inc."
      logo: "instructure"
     # customers loop
    - title: "Wipro"
      logo: "wipro"



############################# Actions ############################

actions:
  enable: true
  title: "Bereit anzufangen?"
  description: "Testen Sie die Funktionen von GroupDocs.Viewer kostenlos oder fordern Sie eine Lizenz an"
  items:
    #  loop
    - title: ".NET"
      link: "/viewer/net/"
      color: "blue"
        #  loop
    - title: "Java"
      link: "/viewer/java/"
      color: "red"
        #  loop
    - title: "Node.js"
      link: "/viewer/nodejs-java/"
      color: "green"


############################# Faq ############################

faq:
  enable: true
  title:  "Häufige Fragen und Bedenken"
  description:  "In unserem FAQ-Bereich finden Sie Antworten auf häufig gestellte Fragen, um schnell auf Ihre Fragen und Bedenken einzugehen."
  items:
    #  loop
    - question: "Kann ich GroupDocs-Produkte vor dem Kauf testen?"
      answer: |
        Ja! Für alle GroupDocs-Produkte ist eine risikofreie Testversion verfügbar. Wir empfehlen Entwicklern dringend, unsere APIs vor dem Kauf herunterzuladen und auszuprobieren, um sicherzustellen, dass sie Ihre Anforderungen zu 100 % erfüllen.
    #  loop
    - question: "Führt GroupDocs Produktvorführungen durch?"
      answer: |
        Nein, unser Fokus liegt auf unseren APIs und der Herstellung möglichst funktionaler und stabiler Produkte. Wir bieten voll funktionsfähige und kostenlose Testversionen in Form einer [temporären Lizenz](https://purchase.groupdocs.com/temporary-license/) an, damit Sie das Produkt selbst testen können.    
    #  loop
    - question: "Wo kann ich das Produkt herunterladen?"
      answer: |
        Alle Produkte können von der [Website](https://releases.groupdocs.com) heruntergeladen werden. Wir versenden keine physischen Kopien unserer Software per Post.
    #  loop
    - question: "Gelten GroupDocs-Entwicklerlizenzen pro Benutzer oder pro benanntem Benutzer?"
      answer: |
        GroupDocs Developer-Lizenzen gelten pro Benutzer, nicht pro benanntem Benutzer. Wir verstehen, dass sich die Mitglieder eines Codierungsteams im Laufe der Zeit ändern können und dass es nicht praktikabel ist, die Lizenz jedes Mal aktualisieren zu müssen.
    #  loop
    - question: "Benötigen wir eine Lizenz nur für aktive Entwickler? Wir haben zum Beispiel ein Team aus zwei Entwicklern, die in Schicht A arbeiten, und ein zweites Team aus zwei Entwicklern, die in Schicht B arbeiten. Brauchen wir in dieser Situation zwei oder vier Lizenzen?"
      answer: |
        Alle Entwickler, die an dem Projekt arbeiten, müssen lizenziert sein. In dieser Situation geht GroupDocs davon aus, dass Ihr Team aus vier Mitgliedern besteht (auch wenn diese zu unterschiedlichen Zeiten arbeiten). 


############################# Cloud ############################

cloud_links:
  enable: true
  title: "GroupDocs.Viewer Low-Code-APIs"
  description: "Beschleunigen Sie die Anzeige von Dokumenten oder Bildern in jeder Art von Anwendung mit unserer cloudbasierten REST-API"

  items:
    #  loop
    - icon: "groupdocs_viewer-for-curl"
      title: "GroupDocs.Viewer Cloud for cURL"
      link: "https://products.groupdocs.cloud/viewer/curl"
      content: "Verwenden Sie die cURL RESTful Document Viewer-API, um Microsoft Office, PDF und verschiedene andere Standarddateiformate in Ihren Anwendungen effizient darzustellen und darzustellen."

    #  loop
    - icon: "groupdocs_viewer-for-net"
      title: "GroupDocs.Viewer Cloud for .NET"
      link: "https://products.groupdocs.cloud/viewer/net"
      content: "Verbessern Sie die Anzeigefunktionen für Dokumente in .NET-Anwendungen mit dem Cloud SDK für .NET. Zeigen Sie Dokumente nahtlos in den Formaten HTML, PDF oder Bild an."

    #  loop
    - icon: "groupdocs_viewer-for-java"
      title: "GroupDocs.Viewer Cloud for Java"
      link: "https://products.groupdocs.cloud/viewer/java"
      content: "Integrieren Sie erweiterte Dokument-Rendering-Funktionen in Ihre Java-Anwendungen mit einem speziell entwickelten Document Viewer SDK für Java."
    

############################# Apps ############################

app_links:
  enable: true
  title: "GroupDocs.Viewer NoCode-Apps"
  description: "Online-Anwendung, mit der Sie über 180 gängige Dateiformate im Browser anzeigen können"

  items:
    #  loop
    - icon: "groupdocs_viewer-app"
      title: "GroupDocs.Viewer Total"
      link: "https://products.groupdocs.app/viewer/total"
      content: "Entdecken Sie eine kostenlose Online-Anwendung, um über 180 Dateiformate direkt in Ihrem bevorzugten Webbrowser anzuzeigen."

    #  loop
    - icon: "groupdocs_words-app"
      title:  "GroupDocs.Viewer DOCX"
      link: "https://products.groupdocs.app/viewer/docx"
      content: "Webbasiertes Tool zum mühelosen Anzeigen von Microsoft Word-Dateien auf verschiedenen Geräten."

    #  loop
    - icon: "groupdocs_pdf-app"
      title:  "GroupDocs.Viewer PDF"
      link: "https://products.groupdocs.app/viewer/pdf"
      content: "Öffnen und betrachten Sie PDF-Dateien online mit dem kostenlosen PDF-Viewer."
    



---