---
############################# Static ############################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: it
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
head_title: "API di visualizzazione di documenti Python per PDF Word Excel HTML Immagini ed e-mail"
head_description: "API di rendering file e visualizzatore documenti Python. Aggiungi visualizzatore PDF, visualizzatore Word, visualizzatore Excel, visualizzatore immagini, visualizzatore HTML e visualizzatore email alle applicazioni Python."

############################# Header ############################
title: "Una potente API Python per il rendering ottimizzato dei documenti"
description: "Esegui il rendering e visualizza oltre 180 formati di documento (PDF, HTML, immagine) con potenti API e opzioni di configurazione versatili per lo sviluppo di applicazioni Python."
words:
  for: "for"

actions:
  viewer_demo: true
  viewer_demo_file_name: "quarterly-report.docx"
  main: "Download gratuito da PyPI"
  main_link: "https://pypi.org/project/groupdocs-viewer-net/"
  alt: "Licenza"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/python-net"
  title: "Pronto per iniziare?"
  description: "Prova gratuitamente le funzionalità di GroupDocs.Viewer o richiedi una licenza"

release:
  title: "Versione {0} rilasciata"
  notes: "Scopri le novità"
  downloads: "Download"
  link: "https://releases.groupdocs.com/viewer/python-net/release-notes/latest/"

code:
  title: "Rendering di file PDF in Python"
  more: "Altri esempi"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Python-via-.NET"
  install: "pip install groupdocs-viewer-net"
  content: |
    ```python {style=abap}
    import groupdocs.viewer as gv
    import groupdocs.viewer.options as gvo
    hvo = gvo.HtmlViewOptions  
  
    // Imposta le opzioni HTML di output, un file per pagina
    with gv.Viewer("resume.docx") as viewer:
      // Crea un'istanza del visualizzatore
      opts = hvo.for_embedded_resources("page_{0}.html")

      // Rendering di PDF in HTML con risorse incorporate
      viewer.view(opts)
    ```
############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Viewer in sintesi"
  description: "API per il rendering, la visualizzazione e la conversione di documenti, diapositive, diagrammi e molti altri tipi di documenti nelle applicazioni Python"
  features:
    # feature loop
    - title: "Visualizza i documenti in modo efficiente e affidabile"
      content: "Con GroupDocs.Viewer API, puoi eseguire in modo efficiente il rendering di documenti di qualsiasi formato supportato in HTML, JPEG, PNG e PDF con opzioni flessibili e potenti, mantenendo al contempo l'integrità del contenuto e della struttura del documento. GroupDocs.Viewer per Python funziona su piattaforme Windows e Linux."

    # feature loop
    - title: "Supporta la maggior parte dei formati di file e documenti comuni"
      content: "Supportiamo il rendering di oltre 180 formati di file e documenti più diffusi, inclusi Word, Excel, PDF, PowerPoint, la famiglia di formati OpenDocument, archivi, immagini raster e vettoriali, eBook, linguaggi di programmazione e markup e molti altri tipi di file, inclusi file crittografati con protezione tramite password."

    # feature loop
    - title: "Output personalizzabile"
      content: "GroupDocs.Viewer consente non solo di eseguire il rendering del documento, ma anche di controllare come esattamente, quali parti del documento devono essere renderizzate o meno, come devono essere renderizzate e di applicare diverse trasformazioni all'output renderizzato."

############################# Platforms ############################
platforms:
  enable: true
  title: "Indipendenza dalla piattaforma"
  description: "GroupDocs.Viewer per Python supporta i seguenti sistemi operativi, framework e gestori pacchetti"
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
  title: "Formati di file supportati"
  description: |
    GroupDocs.Viewer per Python tramite .NET supporta le operazioni con i seguenti formati di file: [formati di file supportati](https://docs.groupdocs.com/viewer/python-net/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office, OpenDocument e formati di testo
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
        ### Immagini, grafica e diagrammi
        * **Immagini raster:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
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
        ### Altro        
        * **ragnatela:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **Archivi:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **Altro:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "Funzionalità di GroupDocs.Viewer"
  description: "Esegue il rendering, la visualizzazione e la conversione di documenti PDF e Office senza problemi"

  items:
    # feature loop
    - icon: "viewhtml"
      title: "Visualizza i documenti in HTML"
      content: "Converti documenti di qualsiasi tipo in un documento HTML con CSS e SVG, che può essere visualizzato in qualsiasi browser web moderno."

    # feature loop
    - icon: "rasterize"
      title: "Rasterizzare i documenti"
      content: "Rasterizza qualsiasi formato di documento supportabile nell'immagine raster, con formato immagine e qualità di compressione regolabili."

    # feature loop
    - icon: "sourcecode"
      title: "Restituisci ed evidenzia i codici di programmazione"
      content: "Supporto di tutti i linguaggi di programmazione, scripting e markup più diffusi, con capacità di analizzare ed evidenziare la loro sintassi."

    # feature loop
    - icon: "convertpdf"
      title: "Converti in PDF"
      content: "I documenti di qualsiasi formato supportato possono essere facilmente convertiti e salvati nel PDF con opzioni regolabili."

    # feature loop
    - icon: "transform"
      title: "Applicare trasformazioni"
      content: "Il documento di output può essere trasformato durante il rendering: le pagine possono essere ruotate e/o riorganizzate e la filigrana di testo può essere posizionata sopra di esse."

    # feature loop
    - icon: "adjustment"
      title: "Regolazione dell'output HTML"
      content: "I documenti HTML di output, generati da GroupDocs.Viewer, possono essere ottimizzati in modo molto preciso: è consentito salvare nello stream o nel file, con risorse esterne o incorporate, callback e così via."

    # feature loop
    - icon: "complex"
      title: "Supporto di strutture documentali complesse"
      content: "GroupDocs.Viewer supporta non solo i singoli documenti, ma anche i file che contengono internamente un elenco o una struttura gerarchica di documenti, come messaggi di posta elettronica con allegati, archivi ZIP con file interni all'interno di cartelle, immagini TIFF multipagina e così via."

    # feature loop
    - icon: "optimization"
      title: "Opzioni di ottimizzazione"
      content: "GroupDocs.Viewer contiene un sottosistema di cache regolabile, che può ridurre i tempi di caricamento utilizzando le versioni dei documenti memorizzate nella cache. Inoltre una serie di diverse opzioni per diversi formati consente di escludere alcune parti o aspetti non necessari dei documenti dal rendering (caratteri, fogli di lavoro nascosti, allegati e-mail) per ottimizzare le prestazioni complessive"

    # feature loop
    - icon: "passwordprotected"
      title: "Supporto di documenti protetti da password"
      content: "GroupDocs.Viewer consente di aprire documenti crittografati di diversi tipi: PDF, elaborazione testi, fogli di calcolo, presentazioni e altri, specificando una password nelle opzioni di caricamento."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Esempi di codice"
  description: "Alcuni casi d'uso tipici delle operazioni di GroupDocs.Viewer per Python tramite .NET"
  items:
    # code sample loop
    - title: "Rendering di DOCX in HTML"
      content: |
        Le proprietà della classe `HtmlViewOptions` consentono di controllare il processo di conversione. Per ulteriori informazioni, consulta [qui](https://docs.groupdocs.com/viewer/python-net/rendering-to-html/). Ad esempio, è possibile incorporare tutte le risorse esterne nel file HTML di output, ridurre le dimensioni del file e ottimizzarlo per la stampa.
        {{< landing/code title="Python">}}
        ```python {style=abap}
        import groupdocs.viewer as gv
        import groupdocs.viewer.options as gvo 

        // Crea un'istanza del visualizzatore
        with gv.Viewer("resume.docx") as viewer:
          // Imposta le opzioni HTML di output, un file per pagina
          viewOptions = gvo.HtmlViewOptions.for_embedded_resources("page_{0}.html")
          // Rendering di PDF in HTML con risorse incorporate
          viewer.view(viewOptions)
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Esportazione di PPTX in PDF"
      content: |
        Creare un'istanza della classe `PdfViewOptions` e passarla al metodo `Viewer.view` per convertire un file PowerPoint PPTX in PDF. Le proprietà della classe `PdfViewOptions` consentono di controllare il processo di conversione. Ad esempio, è possibile proteggere il file PDF di output, riordinarne le pagine e specificare la qualità delle immagini del documento. Consulta la [seguente sezione della documentazione](https://docs.groupdocs.com/viewer/python-net/rendering-to-pdf/) per i dettagli.
        {{< landing/code title="Python">}}
        ```python {style=abap}
        import groupdocs.viewer as gv
        import groupdocs.viewer.options as gvo  

        // Crea un'istanza del visualizzatore
        with gv.Viewer("presentation.pptx") as viewer:
          // Imposta le opzioni di output PDF (Set output PDF options)
          viewOptions = gvo.PdfViewOptions("presentation.pdf")
          // Esporta PPTX in PDF (Export PPTX to PDF)
          viewer.view(viewOptions)
        ```
        {{< /landing/code >}}
############################# Reviews ############################
# reviews:
# enable: true
# title: "Recensioni dei prodotti GroupDocs"
# description: "Non limitarti a crederci sulla parola. Scopri cosa dicono gli altri sviluppatori sulle nostre API"

# items:
#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "Servizio eccellente e prodotti eccellenti. Si sono rivelati estremamente utili e reattivi durante il processo di implementazione di GroupDocs.Viewer per .NET, non posso che consigliarli vivamente."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "Dopo aver implementato e utilizzato GroupDocs.Viewer for .NET nel progetto sembra funzionare molto bene. Ho testato con molti documenti e finora tutto bene. Tutto ciò che ho inserito viene visualizzato bene e ha lo stesso aspetto di un visualizzatore PDF o MS Word."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---
