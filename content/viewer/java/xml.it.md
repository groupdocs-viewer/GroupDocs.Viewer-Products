---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: it

############################# Head #############################
head_title: "Java XML Viewer API - Rendering e visualizzazione XML nelle app Java"
head_description: "Visualizza XML file nelle applicazioni Java, J2EE, J2SE. Supporta la visualizzazione di oltre 170 formati di documenti e file immagine in modalità HTML, PDF o immagine con funzionalità avanzate per gestire le opzioni di visualizzazione dei documenti."

############################# Header ############################
title: "Visualizza e visualizza XML in Java" 
description: "API del visualizzatore di file XML nativa e ad alte prestazioni per applicazioni basate su Java, J2EE e J2SE, che supporta un'ampia gamma di funzionalità aggiuntive per personalizzare l'aspetto del formato del documento di output." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Scarica la prova gratuita"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Informazioni su GroupDocs.Viewer per l'API Java" 
    content: |
        Consenti alle tue applicazioni Java di visualizzare oltre 170 formati di file in modalità HTML, PDF o immagine utilizzando GroupDocs.Viewer per le API Java senza alcun software aggiuntivo installato; come Microsoft Office, Apache Open Office, Adobe Acrobat Reader ecc. Gli sviluppatori possono visualizzare facilmente tutte le immagini e i tipi di documenti più diffusi, inclusi Microsoft Office, OpenDocument, HTML, PDF, Archive, Diagrams, Photoshop, AutoCAD e i formati dei linguaggi di programmazione all'interno delle applicazioni Java con rendering veloce e di altissima qualità.

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
              text: "Riferimento API"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Esempi di codice"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Dimostrazioni dal vivo"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Prezzi"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "Passaggi per eseguire il rendering del file XML in Java" 
    content_left: |
        Con [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/) puoi eseguire il rendering di XML in HTML, JPEG, PNG o PDF in pochi passaggi.

        * Aggiungi [GroupDocs.Viewer per Java](https://releases.groupdocs.com/viewer/java/) come dipendenza al tuo progetto. 
        * Crea un'istanza della classe Viewer e carica il file XML con il percorso completo. 
        * Imposta le opzioni per rendere il file XML in formato HTML, PNG, JPEG o PDF. 
        * Renderizza il file e controlla l'output nella directory corrente. 
        
    title_right: "Requisiti di sistema" 
    content_right: |
        Le API di GroupDocs.Viewer per Java sono supportate su tutte le principali piattaforme e sistemi operativi. Prima di eseguire il codice seguente, assicurati di avere i seguenti prerequisiti installati sul tuo sistema.

        * Sistemi operativi: Microsoft Windows, Linux, MacOS 
        * Ambienti di sviluppo: NetBeans, IntelliJ IDEA, Eclipse ecc. 
        * Framework: J2SE 8.0 (1.8) o superiore (ad esempio Java 17) 
    code: |
        ```java
                        
            // Set up input XML file
            String filePath = "input.xml";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render XML file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "XML Demo dal vivo dello spettatore"
    content: |
        Visualizza subito il file XML visitando il sito web di [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/xml).
    lang: "it"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Altri formati di file Rendering e visualizzazione utilizzando Java"
    exclude: "XML"
    content: |
        API visualizzatore di documenti e immagini multiformato per Java. Visualizza alcuni dei formati di file più diffusi di seguito senza visualizzatori esterni.
    format: 
        # format loop 1
        - name: "Renderizza DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Apri documento XML" 

        # format loop 2
        - name: "Render CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "File CorelDRAW" 

        # format loop 3
        - name: "Renderizza PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint Apri presentazione XML" 

        # format loop 4
        - name: "Renderizza XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Apri foglio di calcolo XML" 

        # format loop 5
        - name: "Rendering DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "Disegno autocad"

        # format loop 6
        - name: "Render XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "FileXML"

        # format loop 7
        - name: "Rendering PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Documento Adobe Photoshop"

        # format loop 8
        - name: "Renderizza il file Adobe Illustrator"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Opere d'arte di Adobe Illustrator"

        # format loop 9
        - name: "Rendi DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Documento Microsoft Word" 

        # format loop 10
        - name: "Renderizza TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "File di testo normale" 

        # format loop 11
        - name: "Rendering DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "File in formato di scambio di disegni"  
          
        # format loop 12
        - name: "Renderizza VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "File vCard"  
              
        # format loop 13
        - name: "Rendering SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Grafica vettoriale scalabile" 
          
        # format loop 14
        - name: "Renderizza HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "File Hypertext Markup Language" 
          
        # format loop 15
        - name: "Rendi PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "File in formato documento portatile"
          
        # format loop 16
        - name: "Rendering JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "Immagine JPEG"
          
        # format loop 17
        - name: "Rendering PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Grafica di rete portatile" 
          
        # format loop 18
        - name: "Render EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "Messaggio email" 
          
        # format loop 19
        - name: "Renderizza RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "File in formato RTF" 
          
        # format loop 20
        - name: "Rendering ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "OpenDocument Documento di testo" 
          
        # format loop 21
        - name: "Rendi CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "File con valori separati da virgole" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
