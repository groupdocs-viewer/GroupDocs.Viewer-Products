---
############################# Static ############################
layout: "format"
date: 2024-05-14T11:12:50
draft: false
lang: it
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head #############################
head_title: "API visualizzatore .NET RB: lettura, visualizzazione, rendering in C# VB.NET"
head_description: "API per visualizzatore di documenti .NET per leggere, eseguire il rendering e visualizzare RB in qualsiasi tipo di applicazioni C#, ASP.NET, VB.NET e .NET Core."

############################# Header ############################
title: "Visualizzatore di file RB per applicazioni C# .NET" 
description: "API per visualizzatore di documenti .NET per leggere, eseguire il rendering e visualizzare file RB in qualsiasi tipo di applicazioni C#, ASP.NET, VB.NET e .NET Core. Visualizza i file renderizzati con formattazione e layout reali in HTML5, PDF o come immagine utilizzando poche righe di codice." 
subtitle: "Soluzione per il rendering dei documenti" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "Scarica gratis Nuget"
      link: "https://nuget.org/packages/GroupDocs.Viewer"



############################# About ############################
about:
    enable: true
    title: "Informazioni su GroupDocs.Viewer per l'API .NET"
    link: "/viewer/net/"
    link_title: "Saperne di più"
    picture: "about_viewer.svg" # 480 X 400
    content: |
      Inizia a visualizzare oltre 190 formati di documenti popolari nelle tue applicazioni .NET utilizzando GroupDocs.Viewer per le API .NET aggiungendo poche righe di codice. Gli sviluppatori possono visualizzare facilmente PDF, elaborazione testi, fogli di calcolo Excel, presentazioni, Visio, Project, Outlook e molti altri formati di documenti popolari in modalità HTML5, immagine o PDF. Il rendering del documento è veloce, identico al file sorgente originale e non richiede l'installazione di software aggiuntivo o altre librerie esterne.



############################# Steps ############################
steps:
    enable: true
    title: "Passaggi per eseguire il rendering del file RB in C#" 
    content: |
      Con <a href='https://products.groupdocs.com/viewer/net/'>GroupDocs.Viewer</a> puoi eseguire il rendering di RB in HTML, JPEG, PNG o PDF in pochi passaggi.
      
      1. Installa <a href='https://www.nuget.org/packages/groupdocs.viewer'>GroupDocs.Viewer for .NET</a> utilizzando il tuo gestore di pacchetti preferito. 
      2. Crea un'istanza della classe Viewer e carica il file RB con il percorso completo.  
      3. Imposta le opzioni per eseguire il rendering del file RB nel formato HTML, PNG, JPEG o PDF. 
      4. Renderizza il file e controlla l'output nella directory corrente. 
   
    code:
      platform: "net"
      copy_title: "copia"
      install:
        command: "dotnet add package GroupDocs.Viewer"
        copy_tip: "fare clic per copiare"
        copy_done: "copiato"
      links:
        #  loop
        - title: "Altri esempi"
          link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
        #  loop
        - title: "Documentazione"
          link: "https://docs.groupdocs.com/viewer/net/"
          
      content: |
        ```csharp {style=abap}

        // Configura il file di input RB
        string filePath = "input.rb";

        // Crea un'istanza di GroupDocs.Viewer
        using (Viewer viewer = new Viewer(filePath))
        {
            // Imposta le opzioni di visualizzazione
            HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                
            // Visualizza il file RB in HTML con risorse incorporate
            viewer.View(viewOptions);
        }

        ```            


############################# Actions ############################

actions:
  enable: true
  title: "Pronti per iniziare?"
  description: "Prova gratuitamente le funzionalità di GroupDocs.Viewer o richiedi una licenza"
  items:
    #  loop
    - title: "Scarica Nuget"
      link: "https://nuget.org/packages/GroupDocs.Viewer"
      color: "red"
        #  loop
    - title: "Licenza"
      link: "https://purchase.groupdocs.com/pricing/viewer/net/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "Esegui il rendering di altri formati di file utilizzando C#"
    exclude: "RB"
    description: "API per visualizzatori di immagini e documenti multiformato per .NET. Visualizza alcuni dei formati di file più diffusi di seguito senza visualizzatori esterni."
    items: 
        # format loop 1
        - name: "Renderizza DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word Open XML Document" 

        # format loop 2
        - name: "Eseguire il rendering del CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "CorelDRAW File" 

        # format loop 3
        - name: "Renderizza PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint Open XML Presentation" 

        # format loop 4
        - name: "Renderizza XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet" 

        # format loop 5
        - name: "Rendering DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "AutoCAD Drawing"

        # format loop 6
        - name: "Rendering XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "XML File"

        # format loop 7
        - name: "Rendering PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Adobe Photoshop Document"

        # format loop 8
        - name: "Rendering dell'intelligenza artificiale"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Adobe Illustrator Artwork"

        # format loop 9
        - name: "Renderizza DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Microsoft Word Document" 

        # format loop 10
        - name: "Renderizza TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Plain Text File" 

        # format loop 11
        - name: "Rendering DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Drawing Exchange Format File"  
          
        # format loop 12
        - name: "Rendering VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "vCard File"  
              
        # format loop 13
        - name: "Rendering SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Scalable Vector Graphic" 
          
        # format loop 14
        - name: "Rendering HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "Visualizza PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Portable Document Format File"
          
        # format loop 16
        - name: "Rendering JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "JPEG Image"
          
        # format loop 17
        - name: "Visualizza PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Portable Network Graphic" 
          
        # format loop 18
        - name: "Rendering EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "E-Mail Message" 
          
        # format loop 19
        - name: "Renderizza RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Rich Text Format File" 
          
        # format loop 20
        - name: "Renderizza ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "OpenDocument Text Document" 
          
        # format loop 21
        - name: "Visualizza CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Comma-Separated Values File" 



---
