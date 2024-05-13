---
############################# Static ############################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: it
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
    # supported_platforms loop
    - title: "Python"
      tag: "python-net"


############################# Head ############################
head_title: "API del visualizzatore di documenti Node.js per immagini ed e-mail PDF Word Excel HTML"
head_description: "Visualizzatore di documenti Node.js e API di rendering dei file. Aggiungi visualizzatore PDF, visualizzatore Word, visualizzatore Excel, visualizzatore immagini, visualizzatore HTML, visualizzatore e-mail nelle applicazioni JavaScript."

############################# Header ############################
title: "API Node.js per eseguire il rendering e visualizzare i documenti"
description: "Libreria Document Viewer per sviluppare applicazioni JavaScript in grado di eseguire il rendering, visualizzare e manipolare in modo nativo documenti multiformato che supportano oltre 180 formati di file."
words:
  for: "for"

actions:
  main: "Download gratuito di NPM"
  main_link: "https://www.npmjs.com/package/@groupdocs/groupdocs.viewer"
  alt: "Licenza"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/nodejs-java"
  title: "Pronto per iniziare?"
  description: "Prova gratuitamente le funzionalità di GroupDocs.Viewer o richiedi una licenza"

release:
  title: "Versione {0} rilasciata"
  notes: "Scopri le novità"
  downloads: "Download"
  link: "https://releases.groupdocs.com/viewer/nodejs-java/release-notes/latest/"

code:
  title: "Rendering di file PDF in JavaScript"
  more: "Altri esempi"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Node.js-via-Java"
  install: "npm i @groupdocs/groupdocs.viewer"
  content: |
    ```javascript {style=abap}       
    // Imposta le opzioni HTML di output, un file per pagina
    const viewOptions = HtmlViewOptions.forEmbeddedResources()
    
    // Visualizzatore di istanze
    const viewer = new Viewer("resume.pdf")

    // Renderizza PDF in HTML con risorse incorporate
    viewer.view(viewOptions)
    viewer.close()
    ```
############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Viewer in breve"
  description: "API per eseguire il rendering, visualizzare, convertire documenti, diapositive, diagrammi e molti altri tipi di documenti nelle applicazioni Node.js"
  features:
    # feature loop
    - title: "Visualizza i documenti in modo efficiente e affidabile"
      content: "Con l'API GroupDocs.Viewer puoi eseguire il rendering efficiente di documenti di qualsiasi formato supportato in HTML, JPEG, PNG e PDF con opzioni flessibili e potenti mantenendo l'integrità del contenuto e della struttura del documento. GroupDocs.Viewer per Node.js funziona su piattaforme Windows e Linux."

    # feature loop
    - title: "Sono supportati i formati di file e documenti più diffusi"
      content: "Supportiamo il rendering dei 180 formati di file e documenti più diffusi tra cui Word, Excel, PDF, PowerPoint, la famiglia di formati OpenDocument, archivi, immagini raster e vettoriali, e-book, linguaggi di programmazione e markup e molti altri tipi di file, inclusi quelli crittografati file protetti da password."

    # feature loop
    - title: "Uscita personalizzabile"
      content: "GroupDocs.Viewer consente non solo di eseguire il rendering del documento, ma anche di controllare come esattamente, quali parti del documento dovrebbero essere renderizzate o ora, come dovrebbero essere renderizzate e di applicare diverse trasformazioni all'output renderizzato."

############################# Platforms ############################
platforms:
  enable: true
  title: "Indipendenza dalla piattaforma"
  description: "GroupDocs.Viewer per Node.js supporta i seguenti sistemi operativi, framework e gestori di pacchetti"
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
  title: "Formati di file supportati"
  description: |
    GroupDocs.Viewer per Node.js tramite Java supporta operazioni con i seguenti [formati di file](https://docs.groupdocs.com/viewer/nodejs-java/supported-document-formats/).
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
  title: "Esempi di codici"
  description: "Alcuni casi d'uso tipici di GroupDocs.Viewer per Node.js tramite operazioni Java"
  items:
    # code sample loop
    - title: "Rendere DOCX in HTML"
      content: |
        Le proprietà della classe `HtmlViewOptions` ti consentono di controllare il processo di conversione, maggiori informazioni [qui](https://docs.groupdocs.com/viewer/nodejs-java/rendering-to-html/). Ad esempio, puoi incorporare tutte le risorse esterne nel file HTML di output, minimizzare il file di output e ottimizzarlo per la stampa.
        {{< landing/code title="JavaScript">}}
        ```javascript {style=abap}
        import { Viewer, HtmlViewOptions } from '@groupdocs/groupdocs.viewer'

        // Imposta le opzioni HTML di output, un file per pagina
        const viewOptions = HtmlViewOptions.forEmbeddedResources()

        // Visualizzatore di istanze
        const viewer = new Viewer("resume.docx")

        // Renderizza DOCX in HTML con risorse incorporate
        viewer.view(viewOptions)
        viewer.close()
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Esporta PPTX in PDF"
      content: |
        Crea un'istanza della classe PdfViewOptions e passala al metodo Viewer.view per convertire un file PowerPoint PPTX in PDF. Le proprietà della classe PdfViewOptions ti consentono di controllare il processo di conversione. Ad esempio, puoi proteggere il file PDF di output, riordinarne le pagine e specificare la qualità delle immagini del documento. Fare riferimento alla [sezione della documentazione seguente](https://docs.groupdocs.com/viewer/nodejs-java/rendering-to-pdf/) per i dettagli.
        {{< landing/code title="JavaScript">}}
        ```javascript {style=abap}   
        import { Viewer, PdfViewOptions } from '@groupdocs/groupdocs.viewer'

        // Imposta le opzioni PDF di output
        const viewOptions = new PdfViewOptions("presentation.pdf")

        // Visualizzatore di istanze
        const viewer = new Viewer("presentation.pptx")

        // Esporta PPTX in PDF
        viewer.view(viewOptions)
        viewer.close()
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
