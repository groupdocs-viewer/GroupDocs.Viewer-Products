---
############################# Static ##########################
layout: "family"
date: 2023-12-20T06:39:57
draft: false

product: "Viewer"
product_tag: "viewer"

############################# Head ############################
head_title: "API di rendering e visualizzazione dei documenti | API on-premise e servizio online"
head_description: "Esegui il rendering e visualizza file Word, PDF, Excel, Powerpoint o immagini in modo semplice e gratuito"

############################# Header ##########################
title: "Esegui il rendering e visualizza i documenti con facilità"
description: |
  Potente API visualizzatore per eseguire il rendering di file diversi in PDF, HTML e immagini.

  Carica documenti da varie origini, inclusi file, flussi, URL, server FTP, Amazon S3, archiviazione BLOB di Azure e altro ancora.

  Genera pagine HTML reattive, proteggi i file PDF di output e riordina le loro pagine, ruota le pagine, visualizza note e commenti se necessario.

############################# Platforms ############################
supported_platforms:
  enable: true  
  head_title: "Scegli la tua piattaforma"
  title: "Piattaforme supportate"
  description: "La libreria GroupDocs.Viewer supporta i seguenti sistemi operativi e framework"
  details_link_title: "Saperne di più"
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
        - content: "Oltre 180 formati di file"
          rows: "1"
        # features loop
        - content: "Pacchetto dell'interfaccia utente per ASP.NET Core"
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
        - content: "Oltre 180 formati di file"
          rows: "1"
        # features loop
        - content:  "Pacchetto interfaccia utente per Spring e Dropwizard"
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
        - content:  "Oltre 180 formati di file"
          rows: "1"
        # features loop
        - content:  "Pacchetto UI: disponibile a breve"
          rows: "1" 
        # features loop
        - content:  "Demo - in arrivo"
          rows: "3" 

    # supported_platforms loop
    - title: "Python"
      description: "GroupDocs.Viewer for Python"
      color: "yellow"
      tag: "python-net"
      link: "/viewer/python-net/"
      features_link: "https://docs.groupdocs.com/viewer/python-net/system-requirements/"
      features:
        # features loop
        - content: "Python 3.9+  <br>  and .Net 6+"
          rows: "3"
        # features loop
        - content:  "Windows, Linux, macOS"
          rows: "1"
        # features loop
        - content:  "Oltre 180 formati di file"
          rows: "1"
        # features loop
        - content:  "Pacchetto UI: disponibile a breve"
          rows: "1" 
        # features loop
        - content:  "Demo - in arrivo"
          rows: "3" 

############################# Features ############################

features:
  enable: true
  title: "Set di funzionalità di GroupDocs.Viewer"
  description: "API per eseguire il rendering di file di diversi tipi come HTML, PDF, PNG e JPEG nelle applicazioni per visualizzarli senza software di terze parti."

  items:
    # feature loop
    - icon: "view"
      title: "Visualizza documenti e immagini"
      content: "Visualizza i documenti visualizzandoli come file HTML, PDF, PNG e JPEG."

    # feature loop
    - icon: "password"
      title: "Apri documenti protetti"
      content: "Specificare una password per aprire i documenti crittografati."

    # feature loop
    - icon: "load"
      title: "Carica file da qualsiasi luogo"
      content: "Carica documenti da vari file, URL, server FTP, Amazon S3 e altro ancora."
    
    # feature loop
    - icon: "pages"
      title: "Visualizza tutte le pagine o pagine specifiche"
      content: "Specificare un intervallo di numeri di pagina di cui eseguire il rendering."


############################# Code samples ############################
code_samples:
  enable: true
  title: "Esempi di codice GroupDocs.Viewer"
  description: "Alcuni casi d'uso delle tipiche operazioni GroupDocs.Viewer in C#, Java, TypeScript"
  items:
    # code sample loop
    - title: "Come convertire i file DOCX in PDF"
      content: |
       Trasforma i documenti DOCX in PDF senza Microsoft Word o altri software installati. Carica e visualizza facilmente i file DOCX all'interno della tua applicazione .NET, sia che si tratti di un'applicazione Web o desktop. Ecco un esempio di come convertire un file DOCX in PDF:
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Carica il file DOCX da renderizzare
            using (Viewer viewer = new Viewer("sample.docx"))
            {
              // Renderizza DOCX in un file PDF
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
            // Carica il file DOCX da renderizzare
            try (Viewer viewer = new Viewer("sample.docx")) {
                // Renderizza DOCX in un file PDF
                PdfViewOptions viewOptions = new PdfViewOptions();
                viewer.view(viewOptions);
            }
            ```
        - language: "TypeScript"
          color: "green"
          content: |
            ```javascript {style=abap}  
            // Carica il file DOCX da renderizzare
            const viewer = new groupdocs.viewer.Viewer("sample.docx")
            
            // Renderizza DOCX in un file PDF
            const viewOptions = groupdocs.viewer.PdfViewOptions(output.pdf)
            viewer.view(viewOptions)
            ```

        - language: "Python"
          color: "yellow"
          content: |
            ```python {style=abap} 
            import groupdocs.viewer as gv
            import groupdocs.viewer.options as gvo   
            // Carica il file DOCX da renderizzare
            with gv.Viewer("sample.docx") as viewer:
            
                // Renderizza DOCX in un file PDF
                viewOptions = gvo.PdfViewOptions("output.pdf")
                viewer.view(viewOptions)
            ```

############################# Formats ############################
formats:
  enable: true
  title:  "Sono supportati oltre 180 formati di file"
  description: "GroupDocs.Viewer supporta le operazioni con i più popolari [formati di file](https://docs.groupdocs.com/viewer/net/supported-document-formats/)"


############################# Metrics ############################

metrics:
  enable: true
  title: "Metriche approfondite e approfondimenti statistici"
  description: "Immergiti in un'analisi dettagliata delle nostre cifre chiave, fornendo metriche complete e approfondimenti statistici sui nostri risultati, impatto e crescita."

  items:
    # metrics loop
    - number: "180+"
      title: "Formati supportati"
      content: "Visualizza facilmente oltre 180 formati di file inclusi documenti, immagini e disegni CAD senza problemi. Supera le barriere di compatibilità e accedi facilmente a file diversi con la nostra soluzione di visualizzazione completa."
    # metrics loop
    - number: "1.0M"
      title: "Download di NuGet"
      content: "La nostra soluzione di pacchetto NuGet è diventata una risorsa affidabile e ampiamente adottata nella comunità degli sviluppatori, fornendo un'integrazione perfetta e funzionalità preziose per innumerevoli progetti."

    # metrics loop
    - number: "10+"
      title: "Biblioteche"
      content: "Il nostro prodotto include oltre 10 librerie che offrono funzionalità avanzate per ottimizzare le prestazioni. Queste librerie sono progettate per soddisfare diverse esigenze di sviluppo con capacità senza precedenti."
    
    # metrics loop
    - number: "100+"
      title: "Clienti felici"
      content: "Al servizio dei marchi più iconici in tutto il mondo. Scopri perché centinaia di persone adorano GroupDocs.Viewer! Esplora la navigazione fluida, la collaborazione conveniente e la facilità d'uso senza precedenti. Iscriviti adesso!"


############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "I nostri clienti felici"
  description: "Le librerie GroupDocs sono utilizzate da marchi distinti e rinomati a livello globale in tutto il mondo."

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
  title: "Pronti per iniziare?"
  description: "Prova gratuitamente le funzionalità di GroupDocs.Viewer o richiedi una licenza"

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
        #  loop
    - title: "Python"
      link: "/viewer/python-net/"
      color: "yellow"

############################# Faq ############################

faq:
  enable: true
  title: "Domande e preoccupazioni comuni"
  description: "Trova le risposte alle domande più comuni nella nostra sezione FAQ per rispondere rapidamente alle tue domande e preoccupazioni."

  items:
    #  loop
    - question: "Posso valutare i prodotti GroupDocs prima dell'acquisto?"
      answer: |
        SÌ! Per tutti i prodotti GroupDocs è disponibile una versione di valutazione priva di rischi. Incoraggiamo vivamente gli sviluppatori a scaricare e provare le nostre API prima dell'acquisto per garantire che soddisfino le tue esigenze al 100%.
    #  loop
    - question: "GroupDocs esegue dimostrazioni dei prodotti?"
      answer: |
        No, il nostro focus è sulle nostre API e sulla realizzazione dei prodotti più funzionali e stabili possibili. Offriamo prove completamente funzionali e gratuite sotto forma di [licenza temporanea](https://purchase.groupdocs.com/temporary-license/) in modo che tu possa testare il prodotto tu stesso.
    #  loop
    - question: "Dove posso scaricare il prodotto?"
      answer: |
        Tutti i prodotti sono disponibili per il download dal [sito Web](https://releases.groupdocs.com). Non inviamo copie fisiche del nostro software tramite posta.    
    #  loop
    - question: "Le licenze per sviluppatori di GroupDocs sono per utente o per utente nominato?"
      answer: |
        Le licenze per sviluppatori GroupDocs sono per utente, non per utente nominato. Comprendiamo che i membri di un team di codifica possono cambiare nel tempo e che non è pratico dover aggiornare la licenza ogni volta che ciò accade.
    #  loop
    - question: "Abbiamo bisogno di licenze solo per gli sviluppatori attivi? Ad esempio, abbiamo un team di due sviluppatori che lavorano nel turno A e un secondo team di due sviluppatori che lavorano nel turno B… in questa situazione, abbiamo bisogno di due o quattro licenze?"
      answer: |
        Tutti gli sviluppatori che stanno lavorando al progetto devono avere una licenza. In questa situazione, GroupDocs vede il tuo team come composto da quattro membri (anche se lavorano in momenti diversi).

############################# Cloud ############################

cloud_links:
  enable: true
  title: "API a basso codice GroupDocs.Viewer"
  description: "Accelera la visualizzazione di documenti o immagini in qualsiasi tipo di applicazione con la nostra API REST basata su cloud"

  items:
    #  loop
    - icon: "groupdocs_viewer-for-curl"
      title: "GroupDocs.Viewer Cloud for cURL"
      link: "https://products.groupdocs.cloud/viewer/curl"
      content: "Utilizza l'API di visualizzazione documenti RESTful di cURL per eseguire il rendering e mostrare in modo efficiente Microsoft Office, PDF e vari altri formati di file standard nelle tue applicazioni."

    #  loop
    - icon: "groupdocs_viewer-for-net"
      title: "GroupDocs.Viewer Cloud for .NET"
      link: "https://products.groupdocs.cloud/viewer/net"
      content: "Migliora le funzionalità di visualizzazione dei documenti nelle applicazioni .NET con Cloud SDK per .NET. Visualizza documenti senza problemi nei formati HTML, PDF o immagine."
    #  loop
    - icon: "groupdocs_viewer-for-java"
      title: "GroupDocs.Viewer Cloud for Java"
      link: "https://products.groupdocs.cloud/viewer/java"
      content: "Integra funzionalità avanzate di rendering dei documenti nelle tue applicazioni Java utilizzando un SDK per visualizzatore di documenti appositamente creato per Java."

############################# Apps ############################

app_links:
  enable: true
  title: "App GroupDocs.Viewer NoCode"
  description: "Applicazione online che ti consente di visualizzare oltre 180 formati di file popolari nel browser"

  items:
    #  loop
    - icon: "groupdocs_viewer-app"
      title: "GroupDocs.Viewer Total"
      link: "https://products.groupdocs.app/viewer/total"
      content: "Esplora un'applicazione online gratuita per visualizzare oltre 180 formati di file direttamente dal tuo browser Web preferito."

    #  loop
    - icon: "groupdocs_words-app"
      title:  "GroupDocs.Viewer DOCX"
      link: "https://products.groupdocs.app/viewer/docx"
      content: "Strumento basato sul Web per visualizzare facilmente file Microsoft Word su vari dispositivi."

    #  loop
    - icon: "groupdocs_pdf-app"
      title:  "GroupDocs.Viewer PDF"
      link: "https://products.groupdocs.app/viewer/pdf"
      content: "Apri e visualizza file PDF online con il visualizzatore PDF gratuito."
    

---