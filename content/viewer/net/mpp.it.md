---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: it

############################# Head #############################
head_title: ".NET MPP API visualizzatore: lettura, visualizzazione, rendering in C# VB.NET"
head_description: "API del visualizzatore di documenti .NET per leggere, eseguire il rendering e visualizzare MPP in qualsiasi tipo di applicazione C#, ASP.NET, VB.NET e .NET Core."

############################# Header ############################
title: "MPP Visualizzatore file per applicazioni C# .NET" 
description: "API del visualizzatore di documenti .NET per leggere, eseguire il rendering e visualizzare il file MPP in qualsiasi tipo di applicazione C#, ASP.NET, VB.NET e .NET Core. Visualizza i file renderizzati con formattazione e layout reali in HTML5, PDF o come immagine utilizzando poche righe di codice." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Scarica la prova gratuita"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Informazioni su GroupDocs.Viewer per l'API .NET" 
    content: |
        Inizia a visualizzare oltre 190 formati di documenti popolari nelle tue applicazioni .NET utilizzando GroupDocs.Viewer per le API .NET aggiungendo alcune righe di codice. Gli sviluppatori possono visualizzare facilmente PDF, Elaborazione testi, Foglio di calcolo Excel, Presentazione, Visio, Progetto, Outlook e molti altri formati di documenti popolari in modalità HTML5, immagine o PDF. Il rendering del documento è veloce, identico al file sorgente originale e non richiede l'installazione di software aggiuntivo o altre librerie esterne.

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
    title_left: "Passaggi per eseguire il rendering del file MPP in C#" 
    content_left: |
        Con [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/) puoi eseguire il rendering di MPP in HTML, JPEG, PNG o PDF in pochi passaggi.

        * Installa [GroupDocs.Viewer per .NET](https://www.nuget.org/packages/groupdocs.viewer) utilizzando il tuo gestore di pacchetti preferito. 
        * Crea un'istanza della classe Viewer e carica il file MPP con il percorso completo. 
        * Imposta le opzioni per rendere il file MPP in formato HTML, PNG, JPEG o PDF. 
        * Renderizza il file e controlla l'output nella directory corrente. 
        
    title_right: "Requisiti di sistema" 
    content_right: |
        Le API di GroupDocs.Viewer per .NET sono supportate su tutte le principali piattaforme e sistemi operativi. Prima di eseguire il codice seguente, assicurati di avere i seguenti prerequisiti installati sul tuo sistema.

        * Sistemi operativi: Microsoft Windows, Linux, MacOS 
        * Ambienti di sviluppo: Microsoft Visual Studio, Visual Studio Code, .NET CLI 
        * Framework: .NET Framework, .NET Standard, .NET Core, .NET 
    code: |
        ```cs
                        
            // Set up input MPP file
            string filePath = "input.mpp";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render MPP file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "MPP Demo dal vivo dello spettatore"
    content: |
        Visualizza subito il file MPP visitando il sito web di [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/mpp).
    lang: "it"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Altri formati di file Rendering e visualizzazione utilizzando C#"
    exclude: "MPP"
    content: |
        API visualizzatore di documenti e immagini multiformato per .NET. Visualizza alcuni dei formati di file più diffusi di seguito senza visualizzatori esterni.
    format: 
        # format loop 1
        - name: "Renderizza DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word Apri documento XML" 

        # format loop 2
        - name: "Render CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "File CorelDRAW" 

        # format loop 3
        - name: "Renderizza PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint Apri presentazione XML" 

        # format loop 4
        - name: "Renderizza XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Apri foglio di calcolo XML" 

        # format loop 5
        - name: "Rendering DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "Disegno autocad"

        # format loop 6
        - name: "Render XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "FileXML"

        # format loop 7
        - name: "Rendering PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Documento Adobe Photoshop"

        # format loop 8
        - name: "Renderizza il file Adobe Illustrator"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Opere d'arte di Adobe Illustrator"

        # format loop 9
        - name: "Rendi DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Documento Microsoft Word" 

        # format loop 10
        - name: "Renderizza TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "File di testo normale" 

        # format loop 11
        - name: "Rendering DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "File in formato di scambio di disegni"  
          
        # format loop 12
        - name: "Renderizza VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "File vCard"  
              
        # format loop 13
        - name: "Rendering SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Grafica vettoriale scalabile" 
          
        # format loop 14
        - name: "Renderizza HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "File Hypertext Markup Language" 
          
        # format loop 15
        - name: "Rendi PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "File in formato documento portatile"
          
        # format loop 16
        - name: "Rendering JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "Immagine JPEG"
          
        # format loop 17
        - name: "Rendering PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Grafica di rete portatile" 
          
        # format loop 18
        - name: "Render EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "Messaggio email" 
          
        # format loop 19
        - name: "Renderizza RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "File in formato RTF" 
          
        # format loop 20
        - name: "Rendering ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "OpenDocument Documento di testo" 
          
        # format loop 21
        - name: "Rendi CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "File con valori separati da virgole" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
