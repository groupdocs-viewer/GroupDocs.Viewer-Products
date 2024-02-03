---
############################# Static ##########################
layout: "family"
date: 2023-12-20T06:39:57
draft: false

product: "Viewer"
product_tag: "viewer"

############################# Head ############################
head_title: "Pateikti ir peržiūrėti dokumentus API | On Premise API ir internetinė paslauga"
head_description: "Pateikite ir peržiūrėkite Word, PDF, Excel, Powerpoint ar vaizdo failus lengvai ir nemokamai"

############################# Header ##########################
title: "Lengvai atvaizduokite ir peržiūrėkite dokumentus"
description: |
  Galinga peržiūros API, skirta įvairiems failams pateikti PDF, HTML ir vaizdo formatais.

  Įkelkite dokumentus iš įvairių šaltinių, įskaitant failus, srautus, URL, FTP serverius, Amazon S3, Azure Blob Storage ir kt.

  Generuokite reaguojančius HTML puslapius, apsaugokite išvesties PDF failus ir pertvarkykite jų puslapius, pasukite puslapius, prireikus pateikite pastabas ir komentarus.

############################# Platforms ############################
supported_platforms:
  enable: true  
  head_title: "Pasirinkite savo platformą"
  title: "Palaikomos platformos"
  description: "GroupDocs.Viewer biblioteka palaiko šias operacines sistemas ir sistemas"
  details_link_title: "Sužinokite daugiau"
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
        - content: "180 ir daugiau failų formatų"
          rows: "1"
        # features loop
        - content: "UI paketas, skirtas ASP.NET Core"
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
        - content: "180 ir daugiau failų formatų"
          rows: "1"
        # features loop
        - content:  "UI paketas, skirtas „Spring“ ir „Dropwizard“."
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
        - content:  "180 ir daugiau failų formatų"
          rows: "1"
        # features loop
        - content:  "UI paketas – netrukus"
          rows: "1" 
        # features loop
        - content:  "Demo – netrukus"
          rows: "3" 


############################# Features ############################

features:
  enable: true
  title: "GroupDocs.Viewer funkcijų rinkinys"
  description: "API, skirta įvairių tipų failams, pvz., HTML, PDF, PNG ir JPEG, pateikti programose ir peržiūrėti juos be trečiosios šalies programinės įrangos."

  items:
    # feature loop
    - icon: "view"
      title: "Peržiūrėkite dokumentus ir vaizdus"
      content: "Peržiūrėkite dokumentus pateikdami juos kaip HTML, PDF, PNG ir JPEG failus."

    # feature loop
    - icon: "password"
      title: "Atidarykite saugius dokumentus"
      content: "Nurodykite slaptažodį, kad atidarytumėte šifruotus dokumentus."

    # feature loop
    - icon: "load"
      title: "Įkelkite failus iš bet kurios vietos"
      content: "Įkelkite dokumentus iš įvairių failų, URL, FTP serverių, Amazon S3 ir kt."
    
    # feature loop
    - icon: "pages"
      title: "Pateikite visus arba konkrečius puslapius"
      content: "Nurodykite pateikiamų puslapių numerių diapazoną."


############################# Code samples ############################
code_samples:
  enable: true
  title: "GroupDocs.Viewer kodo pavyzdžiai"
  description: "Kai kurie naudoja tipiškų GroupDocs.Viewer operacijų atvejus C#, Java, TypeScript"
  items:
    # code sample loop
    - title: "Kaip paversti DOCX failus į PDF"
      content: |
       Pateikite DOCX dokumentus į PDF neįdiegę „Microsoft Word“ ar kitos programinės įrangos. Lengvai įkelkite ir peržiūrėkite DOCX failus savo .NET programoje, nesvarbu, ar tai žiniatinklio, ar darbalaukio programa. Štai pavyzdys, kaip pateikti DOCX failą į PDF:
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Įkelkite DOCX failą, kad būtų pateiktas
            using (Viewer viewer = new Viewer("sample.docx"))
            {
              // Pateikite DOCX į PDF failą
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
            // Įkelkite DOCX failą, kad būtų pateiktas
            try (Viewer viewer = new Viewer("sample.docx")) {
                // Pateikite DOCX į PDF failą
                PdfViewOptions viewOptions = new PdfViewOptions();
                viewer.view(viewOptions);
            }
            ```
        - language: "TypeScript"
          color: "green"
          content: |
            ```javascript {style=abap}  
            // Įkelkite DOCX failą, kad būtų pateiktas
            const viewer = new groupdocs.viewer.Viewer("sample.docx")
            
            // Pateikite DOCX į PDF failą
            const viewOptions = groupdocs.viewer.PdfViewOptions(output.pdf)
            viewer.view(viewOptions)
            ```


############################# Formats ############################
formats:
  enable: true
  title:  "Palaikoma daugiau nei 180 failų formatų"
  description: "GroupDocs.Viewer palaiko operacijas su populiariausiais [failų formatais](https://docs.groupdocs.com/viewer/net/supported-document-formats/)"


############################# Metrics ############################

metrics:
  enable: true
  title: "Išsamios metrikos ir statistinės įžvalgos"
  description: "Pasinerkite į išsamų mūsų pagrindinių skaičių suskirstymą, pateikdami išsamią metriką ir statistines įžvalgas apie mūsų pasiekimus, poveikį ir augimą."

  items:
    # metrics loop
    - number: "180+"
      title: "Palaikomi formatai"
      content: "Lengvai ir be vargo peržiūrėkite daugiau nei 180 failų formatų, įskaitant dokumentus, vaizdus ir CAD brėžinius. Sulaužykite suderinamumo kliūtis ir lengvai pasiekite įvairius failus naudodami mūsų visapusišką peržiūros sprendimą."
    # metrics loop
    - number: "1.0M"
      title: "NuGet atsisiuntimai"
      content: "Mūsų „NuGet“ paketo sprendimas tapo patikimu ir plačiai naudojamu šaltiniu kūrėjų bendruomenėje, užtikrinančiu sklandžią integraciją ir vertingas daugybę projektų."

    # metrics loop
    - number: "10+"
      title: "Bibliotekos"
      content: "Mūsų gaminyje yra daugiau nei 10 bibliotekų, siūlančių pažangias funkcijas, skirtas našumui optimizuoti. Šios bibliotekos sukurtos taip, kad atitiktų skirtingus plėtros poreikius ir turi neprilygstamų galimybių."
    
    # metrics loop
    - number: "100+"
      title: "Laimingi klientai"
      content: "Aptarnauja garsiausius prekės ženklus visame pasaulyje. Sužinokite, kodėl šimtai mėgsta GroupDocs.Viewer! Išbandykite sklandžią naršymą, patogų bendradarbiavimą ir neprilygstamą naudojimo paprastumą. Prisijunk dabar!"


############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "Mūsų laimingi klientai"
  description: "GroupDocs bibliotekose dirba visame pasaulyje žinomi ir išskirtiniai prekių ženklai visame pasaulyje."

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
  title: "Pasiruošę pradėti?"
  description: "Išbandykite GroupDocs.Viewer funkcijas nemokamai arba paprašykite licencijos"

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
  title: "Dažni klausimai ir rūpesčiai"
  description: "Raskite atsakymus į dažniausiai užduodamus klausimus mūsų DUK skiltyje, kad greitai išspręstumėte savo užklausas ir problemas."

  items:
    #  loop
    - question: "Ar galiu įvertinti GroupDocs produktus prieš pirkdamas?"
      answer: |
        Taip! Visi GroupDocs produktai turi nerizikingą įvertinimo versiją. Primygtinai raginame kūrėjus prieš perkant atsisiųsti ir išbandyti mūsų API, kad įsitikintumėte, jog jos patenkins jūsų poreikius 100%.
    #  loop
    - question: "Ar GroupDocs demonstruoja produktus?"
      answer: |
        Ne, daugiausia dėmesio skiriame API ir funkcionaliausių bei stabiliausių produktų kūrimui. Siūlome visiškai veikiančias ir nemokamas bandomąsias versijas [laikinosios licencijos](https://purchase.groupdocs.com/temporary-license/) forma, kad galėtumėte patys išbandyti produktą.
    #  loop
    - question: "Kur galiu atsisiųsti produktą?"
      answer: |
        Visus produktus galima atsisiųsti iš [svetainės](https://releases.groupdocs.com). Mes nesiunčiame fizinių programinės įrangos kopijų paštu.    
    #  loop
    - question: "Ar „GroupDocs“ kūrėjo licencijos suteikiamos vienam vartotojui, ar nurodytam naudotojui?"
      answer: |
        GroupDocs kūrėjo licencijos yra vienam vartotojui, o ne nurodytam vartotojui. Suprantame, kad kodavimo komandos nariai laikui bėgant gali keistis ir kad nepraktiška kiekvieną kartą atnaujinti licenciją.
    #  loop
    - question: "Ar mums reikia licencijų tik aktyviems kūrėjams? Pavyzdžiui, mes turime dviejų kūrėjų komandą, dirbančią A pamainoje, ir antrą dviejų kūrėjų komandą, dirbančią B pamainoje... ar šioje situacijoje mums reikia dviejų ar keturių licencijų?"
      answer: |
        Visi kūrėjai, kurie dirba su projektu, turi turėti licenciją. Esant tokiai situacijai, GroupDocs mano, kad jūsų komandą sudaro keturi nariai (net jei jie dirba skirtingu laiku).

############################# Cloud ############################

cloud_links:
  enable: true
  title: "GroupDocs.Viewer žemo kodo API"
  description: "Paspartinkite dokumentų ar vaizdų peržiūrą bet kokio tipo programoje naudodami debesyje pagrįstą REST API"

  items:
    #  loop
    - icon: "groupdocs_viewer-for-curl"
      title: "GroupDocs.Viewer Cloud for cURL"
      link: "https://products.groupdocs.cloud/viewer/curl"
      content: "Naudokite cURL RESTful dokumentų peržiūros programos API, kad savo programose efektyviai pateiktumėte ir demonstruotumėte Microsoft Office, PDF ir įvairius kitus standartinius failų formatus."

    #  loop
    - icon: "groupdocs_viewer-for-net"
      title: "GroupDocs.Viewer Cloud for .NET"
      link: "https://products.groupdocs.cloud/viewer/net"
      content: "Pagerinkite dokumentų peržiūros galimybes .NET programose naudodami debesies SDK, skirtą .NET. Sklandžiai peržiūrėkite dokumentus HTML, PDF arba vaizdo formatais."
    #  loop
    - icon: "groupdocs_viewer-for-java"
      title: "GroupDocs.Viewer Cloud for Java"
      link: "https://products.groupdocs.cloud/viewer/java"
      content: "Integruokite pažangias dokumentų atvaizdavimo galimybes į savo „Java“ programas naudodami specialiai sukurtą „Java“ skirtą Document Viewer SDK."

############################# Apps ############################

app_links:
  enable: true
  title: "GroupDocs.Viewer NoCode programos"
  description: "Internetinė programa, leidžianti naršyklėje peržiūrėti daugiau nei 180 populiarių failų formatų"

  items:
    #  loop
    - icon: "groupdocs_viewer-app"
      title: "GroupDocs.Viewer Total"
      link: "https://products.groupdocs.app/viewer/total"
      content: "Naršykite nemokamą internetinę programą, kad peržiūrėtumėte daugiau nei 180 failų formatų tiesiai iš pageidaujamos žiniatinklio naršyklės."

    #  loop
    - icon: "groupdocs_words-app"
      title:  "GroupDocs.Viewer DOCX"
      link: "https://products.groupdocs.app/viewer/docx"
      content: "Internetinis įrankis, leidžiantis lengvai peržiūrėti „Microsoft Word“ failus įvairiuose įrenginiuose."

    #  loop
    - icon: "groupdocs_pdf-app"
      title:  "GroupDocs.Viewer PDF"
      link: "https://products.groupdocs.app/viewer/pdf"
      content: "Atidarykite ir peržiūrėkite PDF failus internete naudodami nemokamą PDF peržiūros programą."
    

---