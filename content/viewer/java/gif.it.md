---
############################# Static ############################
layout: "format"
date: 2024-05-13T10:14:34
draft: false
lang: it
product: "Viewer"
product_tag: "viewer"
platform: "Java"
platform_tag: "java"

############################# Head #############################
head_title: "API visualizzatore Java GIF: rendering e visualizzazione di GIF nelle app Java"
head_description: "Visualizza file GIF nelle applicazioni Java, J2EE, J2SE. Supporta la visualizzazione di oltre 180 formati di documenti e file immagine in modalità HTML, PDF o immagine con funzionalità avanzate per gestire le opzioni di visualizzazione dei documenti."

############################# Header ############################
title: "Esegui il rendering e visualizza GIF in Java" 
description: "API di visualizzazione file GIF nativa e ad alte prestazioni per applicazioni basate su Java, J2EE e J2SE, che supporta un'ampia gamma di funzionalità aggiuntive per personalizzare l'aspetto del formato del documento di output." 
subtitle: "Soluzione per il rendering dei documenti" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "Scarica gratis Maven"
      link: "https://releases.groupdocs.com/viewer/java/"



############################# About ############################
about:
    enable: true
    title: "Informazioni su GroupDocs.Viewer per l'API Java"
    link: "/viewer/java/"
    link_title: "Saperne di più"
    picture: "about_viewer.svg" # 480 X 400
    content: |
      Abilita le tue applicazioni Java a visualizzare oltre 180 formati di file in modalità HTML, PDF o immagine utilizzando GroupDocs.Viewer per API Java senza alcun software aggiuntivo installato; come Microsoft Office, Apache Open Office, Adobe Acrobat Reader ecc. Gli sviluppatori possono visualizzare facilmente tutte le immagini e i tipi di documenti più diffusi tra cui Microsoft Office, OpenDocument, HTML, PDF, Archive, Diagrams, Photoshop, AutoCAD e i formati del linguaggio di programmazione all'interno delle applicazioni Java con rendering veloce e di altissima qualità.



############################# Steps ############################
steps:
    enable: true
    title: "Passaggi per eseguire il rendering del file GIF in Java" 
    content: |
      Con <a href='https://products.groupdocs.com/viewer/java/'>GroupDocs.Viewer</a> puoi eseguire il rendering di GIF in HTML, JPEG, PNG o PDF in pochi passaggi.
      
      1. Aggiungi <a href='https://releases.groupdocs.com/viewer/java/'>GroupDocs.Viewer for Java</a> come dipendenza al tuo progetto. 
      2. Crea un'istanza della classe Viewer e carica il file GIF con il percorso completo.  
      3. Imposta le opzioni per eseguire il rendering del file GIF nel formato HTML, PNG, JPEG o PDF. 
      4. Renderizza il file e controlla l'output nella directory corrente. 
   
    code:
      platform: "java"
      copy_title: "copia"
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
        copy_tip: "fare clic per copiare"
        copy_done: "copiato"
      links:
        #  loop
        - title: "Altri esempi"
          link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Java"
        #  loop
        - title: "Documentazione"
          link: "https://docs.groupdocs.com/viewer/java/"
          
      content: |
        ```java {style=abap}

        // Configura il file di input GIF
        String filePath = "input.gif";

        // Crea un'istanza di GroupDocs.Viewer
        try (Viewer viewer = new Viewer(filePath))
        {
            // Imposta le opzioni di visualizzazione
            HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                
            // Visualizza il file GIF in HTML con risorse incorporate
            viewer.view(viewOptions);
        }

        ```
            

############################# Actions ############################

actions:
  enable: true
  title: "Pronti per iniziare?"
  description: "Prova gratuitamente le funzionalità di GroupDocs.Viewer o richiedi una licenza"
  items:
    #  loop
    - title: "Scarica Maven"
      link: "https://releases.groupdocs.com/viewer/java/"
      color: "red"
        #  loop
    - title: "Licenza"
      link: "https://purchase.groupdocs.com/pricing/viewer/java/"
      color: "light"



############################# More Formats #####################
more_formats:
    enable: true
    title: "Esegui il rendering di altri formati di file utilizzando Java"
    exclude: "GIF"
    description: "API per visualizzatore di documenti e immagini multiformato per Java. Visualizza alcuni dei formati di file più diffusi di seguito senza visualizzatori esterni."
    items: 
        # format loop 1
        - name: "Renderizza DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Open XML Document" 

        # format loop 2
        - name: "Eseguire il rendering del CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "CorelDRAW File" 

        # format loop 3
        - name: "Renderizza PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint Open XML Presentation" 

        # format loop 4
        - name: "Renderizza XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet" 

        # format loop 5
        - name: "Rendering DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "AutoCAD Drawing"

        # format loop 6
        - name: "Rendering XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "XML File"

        # format loop 7
        - name: "Rendering PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Adobe Photoshop Document"

        # format loop 8
        - name: "Rendering dell'intelligenza artificiale"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Adobe Illustrator Artwork"

        # format loop 9
        - name: "Renderizza DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Microsoft Word Document" 

        # format loop 10
        - name: "Renderizza TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Plain Text File" 

        # format loop 11
        - name: "Rendering DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Drawing Exchange Format File"  
          
        # format loop 12
        - name: "Rendering VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "vCard File"  
              
        # format loop 13
        - name: "Rendering SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Scalable Vector Graphic" 
          
        # format loop 14
        - name: "Rendering HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "Visualizza PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Portable Document Format File"
          
        # format loop 16
        - name: "Rendering JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "JPEG Image"
          
        # format loop 17
        - name: "Visualizza PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Portable Network Graphic" 
          
        # format loop 18
        - name: "Rendering EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "E-Mail Message" 
          
        # format loop 19
        - name: "Renderizza RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Rich Text Format File" 
          
        # format loop 20
        - name: "Renderizza ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "OpenDocument Text Document" 
          
        # format loop 21
        - name: "Visualizza CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Comma-Separated Values File" 


---
