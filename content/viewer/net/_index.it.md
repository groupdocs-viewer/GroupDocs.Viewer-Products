---
############################# Static ##########################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

lang: it
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: ".NET Document Viewer API, Render PDF Word Excel Immagine Diagramma HTML"
head_description: "Visualizzatore di file C# ASP.NET e API di rendering. Aggiungi funzionalità di visualizzatore PDF, visualizzatore Word, visualizzatore Excel, visualizzatore immagini, visualizzatore HTML, visualizzatore e-mail nelle app .NET."

############################# Header ##########################
title: "Rendering e visualizzazione di documenti tramite l'API .NET"
description: ".NET Document Viewer API per il rendering di oltre 190 formati di documenti in PDF, HTML e immagini con potenti opzioni di configurazione."
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
              text: "Panoramica"

            # button loop
            - link: "#features"
              text: "Caratteristiche"

            # button loop
            - link: "#support"
              text: "Supporto"

            # button loop
            - link: "https://products.groupdocs.app/viewer/total"
              text: "Dimostrazione dal vivo"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Prezzi"

    right:
        link_download: "https://www.nuget.org/packages/GroupDocs.Viewer"
        link_learn: "https://docs.groupdocs.com/viewer/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    content: |
      GroupDocs.Viewer per le API .NET ti aiuta a creare potenti applicazioni in C#, ASP.NET e altre tecnologie basate su .NET, che possono eseguire il rendering e visualizzare documenti e immagini di oltre 190 formati di file senza installare alcun software esterno. La libreria del visualizzatore di file rasterizza i documenti e li converte in SVG+HTML+CSS per ottimizzare l'esperienza complessiva di rendering dei documenti per la visualizzazione di documenti aziendali, immagini, file di testo, diagrammi, grafici, allegati e-mail e file PDF con velocità, true-text e alta fedeltà all'interno delle tue applicazioni. Hai la possibilità di aggiungere funzionalità di visualizzazione e lettura dei documenti nelle tue applicazioni per visualizzare l'intero documento, un documento parziale, un intervallo di pagine/celle specifico, un singolo livello di documento, con o senza annotazioni e commenti per i formati di file supportati.
       
      Per impostazione predefinita, GroupDocs.Viewer per .NET memorizza nella cache l'output dei documenti sottoposti a rendering sul disco locale. Qualsiasi tipo di archiviazione cache esterna è supportata anche implementando interfacce appropriate: Amazon S3, Dropbox, Google Drive, Windows Azure, Redis o qualsiasi altro.
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          Di seguito è riportata una panoramica di GroupDocs.Viewer per .NET:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Panoramica"
          content: |
            * Visualizza oltre 190 tipi di documenti 
            * Ottieni un file in formato HTML, Immagine, PDF 
            * Ruota e riordina 
            * Applica filigrana 
            * Cache per processi veloci 
            * Aggiungi caratteri personalizzati 
            * Applicare gli standard di codifica 
            * Gestore dati di input personalizzato 
            * Rendering con modifiche alla traccia 
            * Visualizza come HTML reattivo 
            * Rendering di livelli PDF e CAD 
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Viewer per .NET supporta la visualizzazione di tutti i formati di file di documenti più diffusi. Con poche righe di codice, aggiungi visualizzatore PDF, Microsoft Office Word, foglio di calcolo Excel, immagini, HTML, e-mail di Outlook, OneNote, progetti e funzionalità di visualizzazione grafica nelle tue applicazioni .NET.

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
                * **File di layout di pagina:** PDF, TEX, XPS, OXPS
                * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG, OTG, FODP, FODG
                * **Valori separati da delimitatore:** CSV, TSV
                * **ragnatela:** HTML, MHT, MHTML
                * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
                * **PostScript:** PS, EPS
                * **Archivi:** ZIP, TAR, BZ2, GZ, RAR, RAR5
                * **Vari:** OBJ, EPUB, MOBI, DjVu, XML, VCF, VCARD, NUMBERS, NSF

        right:
          enable: true
          table:
            # table loop
            - title: "Immagini, grafici e diagrammi"
              content: |
                * **immagini:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB
                * **Icona di Windows:** ICO
                * **Grafica vettoriale scalabile:** SVG, CDR, CMX, IGS, SVGZ
                * **JPEG2000:** JP2, J2C, J2K, JPC, JPF, JPX, JPM
                * **Adobe Photoshop:** PSD, PSB
                * **Linguaggio dei comandi della stampante:** PCL
                * **Litografia stereo (stampa 3D):** STL
                * **Corsi di fondazione del settore:** IFC
                * **Imaging medico:** DICOM
                * **Documenti plotter:** PLT, HPG
                * **Formati Web di Autodesk Design:** DWF, DWG
                * **Disegno autocad:** DWT, IFC, STL, CF2
                * **DGN basato su ISFF (V7):** DGN

            # table loop
            - title: "Formati dei linguaggi di programmazione"
              content: |
                * **File C/C++/C#:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
                * **File Java/JavaScript:** JAVA, JS, JSON, PROPERTIES
                * **Vari:** VB, PHP, SQL, PL, PY, PV, RB, RST, SASS, SCALA, SCM, SCRIPT, AS, AS3, ASM, BAT, CMAKE, CSS, DIFF, ERB, GROOVY, HAML, LESS, LOG, M, MAKE, MD, ML, MM, SH, SML, VIM, YAML

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Viewer per .NET supporta i seguenti sistemi operativi, framework e gestori di pacchetti:
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Sistemi operativi"
              content: |
                * Microsoft Windows Server 2003 e versioni successive 
                * Microsoft Windows XP e versioni successive 
                * Microsoft Windows 10 e 11 
                * Linux (Ubuntu, OpenSUSE, CentOS e altri) 
                * MacOSX 

            # table loop
            - icon: "fas fa-code"
              title: "Framework supportati"
              content: |
                * .NET Framework 2.0 o versioni successive 
                * .NET Nucleo 3.1 
                * .NET 5 o superiore 

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-box"
              title: "Gestore dei pacchetti"
              content: |
                * NuGet

            # table loop
            - icon: "fas fa-tools"
              title: "Ambienti di sviluppo"
              content: |
                * Microsoft Visual Studio
                * Visual Studio Code
                * .NET CLI

############################# Features ############################
features:
    enable: true
    title: "GroupDocs.Viewer per le funzionalità .NET"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "Rasterizza i documenti e convertili in SVG, HTML e CSS"

      # feature loop
      - icon: "fas fa-eye"
        content: "Converti testo in HTML e visualizza documenti per ottenere una rappresentazione HTML, immagine o PDF"

      # feature loop
      - icon: "fas fa-bolt"
        content: "Tempi di caricamento più rapidi utilizzando le versioni memorizzate nella cache dei documenti"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "Converti presentazioni con forme e testo con effetti 3D"

      # feature loop
      - icon: "fas fa-code"
        content: "Codifica documenti Word, Excel ed e-mail secondo lo standard di codifica desiderato"

      # feature loop
      - icon: "fas fa-cloud"
        content: "Renderizza i documenti che si trovano in posizioni FTP o di archiviazione cloud"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "Esclusione dei caratteri durante il rendering in HTML per ridurre la dimensione del file risultante"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "Minimizza l'output CSS e HTML rimuovendo commenti, spazi bianchi extra ecc."

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "Leggi il testo contenuto in un documento sorgente attraverso le sue coordinate"

      # feature loop
      - icon: "fas fa-border-all"
        content: "Mostra/Nascondi le linee della griglia dei fogli Excel nella rappresentazione dell'output"

      # feature loop
      - icon: "fas fa-wrench"
        content: "Specificare il numero di righe in un foglio Excel da visualizzare su ogni pagina"

      # feature loop
      - icon: "fas fa-columns"
        content: "Ignora le colonne vuote durante il rendering dei documenti del foglio di calcolo"

      # feature loop
      - icon: "fas fa-file-word"
        content: "Renderizza i documenti Word in pagine HTML, immagini o PDF, con traccia delle modifiche"

      # feature loop
      - icon: "fas fa-envelope"
        content: "Renderizza gli allegati e-mail come file originali, immagini o in rappresentazione HTML"

      # feature loop
      - icon: "fas fa-print"
        content: "Imposta le restrizioni di stampa sui documenti PDF"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "Renderizza i contenuti/file contenuti negli archivi ZIP come allegati"

      # feature loop
      - icon: "fas fa-lock"
        content: "Ottenere allegati da documenti protetti da password"

      # feature loop
      - icon: "fas fa-file-code"
        content: "Renderizza i formati di file dei linguaggi di programmazione come testo normale"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "Regola i colori di sfondo durante la visualizzazione dei disegni CAD"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "Visualizza documenti Excel e converti in PDF, HTML, JPG e PNG"

      # feature loop
      - icon: "fas fa-heading"
        content: "Ottieni i nomi dei fogli di lavoro dal file Excel: visualizza le intestazioni delle colonne del foglio di calcolo e i numeri delle righe"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "Visualizza e converti documenti Microsoft Project con le note"

      # feature loop
      - icon: "fas fa-cube"
        content: "Converti i disegni CAD in SVG per una migliore esperienza di visualizzazione e zoom"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "Scegli di eseguire il rendering delle figure di Visio senza schema"

    more_feature:
      # more_feature_loop
      - title: "Visualizza i documenti in modo efficiente e affidabile"
        content: |
          Utilizzando l'API GroupDocs.Viewer è possibile visualizzare più di 190 formati di documenti in modo efficiente e affidabile con l'integrità del contenuto e della struttura del documento intatta. Il seguente codice di esempio mostra quanto sia facile visualizzare la rappresentazione HTML di un documento DOCX:

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
      - title: "Applica trasformazione all'output sottoposto a rendering"
        content: "È possibile eseguire varie trasformazioni nel documento di output sottoposto a rendering utilizzando GroupDocs.Viewer per l'API .NET. Queste opzioni di trasformazione ti danno il controllo sul modo in cui presenti l'output di rendering per la visualizzazione. Le trasformazioni disponibili sono l'opzione di rotazione della pagina, l'opzione di riordino della pagina e l'applicazione della filigrana di testo."

      # more_feature_loop
      - title: "Lavorare con i file di dati di Outlook"
        content: "GroupDocs.Viewer per .NET API può eseguire il rendering degli elementi nei file di dati di Outlook (OST/PST) come file PDF, HTML e immagine. La nostra API Viewer ha anche la capacità di ottenere l'elenco delle cartelle contenute nei file di dati di Outlook. Utilizzando GroupDocs.Viewer per l'API .NET, è possibile specificare la cartella di cui eseguire il rendering dai file di dati di Outlook. Allo stesso modo, puoi anche ottenere messaggi di posta elettronica contenuti nei formati OST/PST come allegati. GroupDocs.Viewer per .NET consente inoltre di filtrare i messaggi dai formati OST/PST in base all'oggetto, al contenuto o al mittente."

      # more_feature_loop
      - title: "Lavorare con documenti CAD"
        content: "GroupDocs.Viewer per l'API .NET può eseguire il rendering del modello e di tutti i layout non vuoti o eseguire il rendering di un layout specifico di un file CAD. GroupDocs.Viewer per .NET API supporta anche il rendering affiancato o il rendering in base alle coordinate dei documenti CAD in immagine, HTML o PDF. È inoltre possibile ottenere gli stati dei layer per i documenti CAD."

############################# Testimonials ###############################
testimonials:
  enable: true

  testimonial:
    # testimonial item loop
    - name: "Margot Baill"
      designation: "Direttore dello sviluppo del prodotto presso Hireology"
      content: "L'integrazione di GroupDocs.Viewer for Cloud API è stata semplice con il loro fantastico Ruby SDK. Non ci sono molte aziende là fuori che sono disposte a lavorare con noi su ciò che vogliamo. È una grande collaborazione."

    # testimonial item loop
    - name: "Mats Oustad"
      designation: "Senior Consultant/Partner presso Novanet AS"
      content: "Dopo aver implementato e utilizzato GroupDocs.Viewer per .NET nel progetto, sembra funzionare molto bene. Ho testato con molti documenti e finora tutto bene. Tutto ciò che ho lanciato viene riprodotto bene e ha un bell'aspetto come in un visualizzatore di PDF o MS Word."
              
    # testimonial item loop
    - name: "Martin Lasarga"
      designation: "Product Manager presso Axentria ECM di G.S.I."
      content: "Ottimo servizio e ottimi prodotti. Sono stati estremamente utili e reattivi durante il processo di implementazione di GroupDocs.Viewer per .NET, non posso raccomandarli abbastanza bene."

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Viewer offre API di visualizzazione dei documenti per altri ambienti di sviluppo popolari"

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
