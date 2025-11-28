---
############################# Static ##########################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: it
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

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
head_title: "API per visualizzatore di documenti .NET, rendering di PDF Word Excel Immagine HTML Diagramma"
head_description: "Visualizzatore di file C# ASP.NET e API di rendering. Aggiungi funzionalità di visualizzatore PDF, visualizzatore Word, visualizzatore Excel, visualizzatore immagini, visualizzatore HTML, visualizzatore e-mail nelle app .NET."

############################# Header ##########################
title: "Rendering e visualizzazione di documenti<br>utilizzando l'API .NET"
description: "Potente API visualizzatore per eseguire il rendering di oltre 180 formati di documenti in PDF, HTML e immagini con opzioni di configurazione versatili."
words:
  for: "for"

actions:
  viewer_demo: true
  viewer_demo_file_name: "quarterly-report.docx"
  main: "Download gratuito di NuGet"
  main_link: "https://www.nuget.org/packages/GroupDocs.Viewer"
  alt: "Licenza"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/net"
  title: "Pronto per iniziare?"
  description: "Prova gratuitamente le funzionalità di GroupDocs.Viewer o richiedi una licenza"

release:
  title: "Versione {0} rilasciata"
  notes: "Scopri le novità"
  downloads: "Download"
  link: "https://releases.groupdocs.com/viewer/net/release-notes/latest/"

code:
  title: "Rendering di file PDF in C#"
  more: "Altri esempi"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
  install: "dotnet add package GroupDocs.Viewer"
  content: |
    ```csharp {style=abap}   
    // Carica il file PDF di origine
    using (var viewer = new Viewer("resume.pdf"))
    {
        // Imposta le opzioni HTML di output, un file per pagina
        var viewOptions = 
        HtmlViewOptions.ForEmbeddedResources("page{0}.html");
        
        // Renderizza PDF in HTML con risorse incorporate        
        viewer.View(viewOptions);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Viewer in breve"
  description: "API per eseguire il rendering, visualizzare, convertire documenti, diapositive, diagrammi e molti altri tipi di documenti nelle applicazioni .NET"
  features:
    # feature loop
    - title: "Visualizza i documenti in modo efficiente e affidabile"
      content: "Con l'API GroupDocs.Viewer è possibile rendere in modo efficiente documenti di qualsiasi formato supportato in [HTML](https://docs.groupdocs.com/viewer/net/rendering-to-html/), [JPEG, PNG](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/), e [PDF](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/) grazie a opzioni flessibili e potenti, preservando l'integrità del contenuto e della struttura del documento. GroupDocs.Viewer è compatibile con .NET Framework 4.6.2 e .NET 6.0 e funziona su piattaforme Windows e Linux."

    # feature loop
    - title: "Sono supportati i formati di file e documenti più diffusi"
      content: "Supportiamo il rendering di oltre 180 formati di file e documenti più diffusi, tra cui [Word](https://docs.groupdocs.com/viewer/net/render-word-documents/), [Excel](https://blog.groupdocs.com/viewer/working-with-spreadsheets/), [PDF](https://docs.groupdocs.com/viewer/net/render-pdf-documents/), [PowerPoint](https://blog.groupdocs.com/viewer/view-powerpoint-presentations/), la famiglia di formati OpenDocument, archivi, immagini raster e vettoriali, e‑Book, linguaggi di programmazione e markup, oltre a numerosi altri tipi di file, comprese le versioni crittografate protette da password."

    # feature loop
    - title: "Uscita personalizzabile"
      content: "GroupDocs.Viewer consente non solo di eseguire il rendering del documento, ma anche di controllare come esattamente, quali parti del documento dovrebbero essere renderizzate o ora, come dovrebbero essere renderizzate e di applicare diverse trasformazioni all'output renderizzato."

    # feature loop
    - title: "Interfaccia utente per ASP.NET Core"
      content: "Forniamo un pacchetto di interfaccia utente open source per ASP.NET Core che può essere aggiunto al tuo progetto in un paio di minuti. Il pacchetto Viewer.UI contiene un'interfaccia utente Web basata su Angular e fornisce una serie di API utili e provider di archiviazione dati."

############################# Platforms ############################
platforms:
  enable: true
  title: "Supporto delle piattaforme"
  description: "GroupDocs.Viewer per .NET supporta i seguenti sistemi operativi, framework e gestori di pacchetti"
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
    - title: "VS Code"
      image: "vs_code"
    # platform loop
    - title: "ReSharper"
      image: "resharper"
    # platform loop
    - title: "macOS"
      image: "finder"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "NuGet"
      image: "nuget"
  packages:
    # packages loop
    - title: "Pacchetto specifico per Windows"
      content: |
        * Supporta .NET Framework 4.6.2+ e .NET 6.0
        * Il supporto dei formati di file più completo
        * Dipende da System.Drawing e System.Drawing.Common 
      action: "Scarica NuGet"
      action_link: "https://www.nuget.org/packages/GroupDocs.Viewer"
    # packages loop
    - title: "Pacchetto multipiattaforma" 
      content: |
        * Supporta .NET 6.0 e versioni successive 
        * Supporto di formati di file limitati 
        * Funziona su Windows, Linux e macOS 
      action: "Scarica NuGet" 
      action_link: "https://www.nuget.org/packages/GroupDocs.Viewer.CrossPlatform" 

############################# File formats ############################
formats:
  enable: true
  title: "Formati di file supportati"
  description: |
    GroupDocs.Viewer per .NET supporta operazioni con i seguenti [formati di file](https://docs.groupdocs.com/viewer/net/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office, OpenDocument e formati di testo
        * **Word:** DOC, DOCX, DOCM, DOT, DOTX, DOTM, RTF, TXT
        * **Excel:** XLS, XLSX, XLSM, XLSB, XLTM, XLT, XLTM, XLTX
        * **PowerPoint:** PPT, PPTX, PPS, PPSX, PPSM, POT, POTM, POTX, PPTM        
        * **Project:** MPP, MPT, MPX {{< landing/tooltip icon="windows" title="Supportato dal pacchetto specifico di Windows" >}}
        * **Outlook:** MSG, EML, EMLX, PST, OST
        * **OneNote:** ONE {{< landing/tooltip icon="windows" title="Supportato dal pacchetto specifico di Windows" >}}
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
        * **Adobe Photoshop:** PSD, PSB {{< landing/tooltip icon="windows" title="Supportato dal pacchetto specifico di Windows" >}}       
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
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM {{< landing/tooltip icon="windows" title="Supportato dal pacchetto specifico di Windows" >}}
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
      title: "[Visualizza i documenti in HTML](https://blog.groupdocs.com/viewer/view-word-documents-as-html-responsive-page-using-csharp/)"
      content: "Converti documenti di qualsiasi tipo in un documento HTML con CSS e SVG, che può essere visualizzato in qualsiasi browser web moderno."

    # feature loop
    - icon: "rasterize"
      title: "[Rasterizzare i documenti](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/)"
      content: "Rasterizza qualsiasi formato di documento supportabile nell'immagine raster, con formato immagine e qualità di compressione regolabili."

    # feature loop
    - icon: "font"
      title: "[Controlla i caratteri del documento](https://blog.groupdocs.com/viewer/working-with-fonts/)"
      content: "Identifica i caratteri usati in un documento. Gestisci i caratteri mancanti sostituendoli o escludendoli dall'output."

    # feature loop
    - icon: "convertpdf"
      title: "[Converti in PDF](https://blog.groupdocs.com/viewer/rendering-documents-as-pdf/)"
      content: "I documenti di qualsiasi formato supportato possono essere facilmente convertiti e salvati nel PDF con opzioni regolabili."

    # feature loop
    - icon: "transform"
      title: "[Applicare trasformazioni](https://blog.groupdocs.com/viewer/protect-your-documents-with-watermarks-in-groupdocs-viewer-for-dot-net/)"
      content: "Il documento di output può essere trasformato durante il rendering: le pagine possono essere ruotate e/o riorganizzate e la filigrana di testo può essere posizionata sopra di esse."

    # feature loop
    - icon: "adjustment"
      title: "[Regolazione dell'output HTML](https://blog.groupdocs.com/viewer/render-word-documents-as-clean-html-using-csharp/)"
      content: "I documenti HTML di output, generati da GroupDocs.Viewer, possono essere ottimizzati in modo molto preciso: è consentito salvare nello stream o nel file, con risorse esterne o incorporate, callback e così via."

    # feature loop
    - icon: "complex"
      title: "[Supporto di strutture documentali complesse](https://blog.groupdocs.com/viewer/process-microsoft-outlook-email-attachments-in-a-.net-viewer-application/)"
      content: "GroupDocs.Viewer supporta non solo i singoli documenti, ma anche i file che contengono internamente un elenco o una struttura gerarchica di documenti, come messaggi di posta elettronica con allegati, archivi ZIP con file interni all'interno di cartelle, immagini TIFF multipagina e così via."

    # feature loop
    - icon: "optimization"
      title: "[Opzioni di ottimizzazione](https://blog.groupdocs.com/viewer/exclude-specific-fonts-from-output-html-using-groupdocs.viewer-for-.net-18.10/)"
      content: "GroupDocs.Viewer contiene un sottosistema di cache regolabile, che può ridurre i tempi di caricamento utilizzando le versioni dei documenti memorizzate nella cache. Inoltre una serie di diverse opzioni per diversi formati consente di escludere alcune parti o aspetti non necessari dei documenti dal rendering (caratteri, fogli di lavoro nascosti, allegati e-mail) per ottimizzare le prestazioni complessive"

    # feature loop
    - icon: "passwordprotected"
      title: "[Supporto di documenti protetti da password](https://docs.groupdocs.com/viewer/net/load-password-protected-document/)"
      content: "GroupDocs.Viewer consente di aprire documenti crittografati di diversi tipi: PDF, elaborazione testi, fogli di calcolo, presentazioni e altri, specificando una password nelle opzioni di caricamento."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Esempi di codici"
  description: "Alcuni casi d'uso tipici di GroupDocs.Viewer per operazioni .NET"
  items:
    # code sample loop
    - title: "Rendere DOCX in HTML"
      content: |
        Le proprietà della classe [HtmlViewOptions](https://reference.groupdocs.com/viewer/net/groupdocs.viewer.options/htmlviewoptions/) ti consentono di controllare il processo di conversione, maggiori informazioni [qui](https://docs.groupdocs.com/viewer/net/rendering-to-html/). Ad esempio, puoi incorporare tutte le risorse esterne nel file HTML di output, minimizzare il file di output e ottimizzarlo per la stampa.
        {{< landing/code title="C#">}}
        ```csharp {style=abap}
        using GroupDocs.Viewer;
        using GroupDocs.Viewer.Options;
        
        // Visualizzatore di istanze
        using (Viewer viewer = new Viewer("resume.docx"))
        {
            // Imposta le opzioni HTML di output
            HtmlViewOptions options = HtmlViewOptions.ForEmbeddedResources();
            
            // Renderizza DOCX in HTML con risorse incorporate
            viewer.View(options);
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Esporta PPTX in PDF"
      content: |
        Crea un'istanza della classe [PdfViewOptions](https://reference.groupdocs.com/viewer/net/groupdocs.viewer.options/pdfviewoptions/) e passala al file [Viewer.View](https://reference.groupdocs.com/viewer/net/groupdocs.viewer/viewer/view/#view) per convertire un file PowerPoint PPTX in PDF. Le proprietà della classe PdfViewOptions consentono di controllare il processo di conversione. Ad esempio, puoi proteggere il file PDF di output, riordinarne le pagine e specificare la qualità delle immagini del documento. Fare riferimento alla [seguente sezione della documentazione](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/) per i dettagli.
        {{< landing/code title="C#">}}
        ```csharp {style=abap}   
        using GroupDocs.Viewer;
        using GroupDocs.Viewer.Options;
        
        using (var viewer = new Viewer("presentation.pptx"))
        {
            // Imposta le opzioni PDF di output       
            var viewOptions = new PdfViewOptions("presentation.pdf");
            
            // Esporta PPTX in PDF       
            viewer.View(viewOptions);
        }
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