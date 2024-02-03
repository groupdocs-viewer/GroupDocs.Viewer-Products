---
############################# Static ##########################
layout: "family"
date: 2023-12-20T06:39:57
draft: false

product: "Viewer"
product_tag: "viewer"

############################# Head ############################
head_title: "Render and View Documents API | On Premise API a online služba"
head_description: "Snadno a zdarma vykreslujte a zobrazujte soubory Word, PDF, Excel, Powerpoint nebo Image"

############################# Header ##########################
title: "Snadno vykreslujte a prohlížejte dokumenty"
description: |
  Výkonné rozhraní Viewer API pro vykreslování různých souborů do PDF, HTML a obrázků.

  Načtěte dokumenty z různých zdrojů, včetně souborů, streamů, adres URL, FTP serverů, Amazon S3, Azure Blob Storage a dalších.

  Vytvářejte responzivní stránky HTML, chraňte výstupní soubory PDF a změňte pořadí jejich stránek, otáčejte stránky, vykreslujte poznámky a komentáře, pokud je to potřeba.

############################# Platforms ############################
supported_platforms:
  enable: true  
  head_title: "Vyberte si svou platformu"
  title: "Podporované platformy"
  description: "Knihovna GroupDocs.Viewer podporuje následující operační systémy a rámce"
  details_link_title: "Zjistěte více"
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
        - content: "180+ formátů souborů"
          rows: "1"
        # features loop
        - content: "Balíček uživatelského rozhraní pro ASP.NET Core"
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
        - content: "180+ formátů souborů"
          rows: "1"
        # features loop
        - content:  "Balíček uživatelského rozhraní pro Spring a Dropwizard"
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
        - content:  "180+ formátů souborů"
          rows: "1"
        # features loop
        - content:  "Balíček uživatelského rozhraní – již brzy"
          rows: "1" 
        # features loop
        - content:  "Demo - již brzy"
          rows: "3" 


############################# Features ############################

features:
  enable: true
  title: "Sada funkcí GroupDocs.Viewer"
  description: "API pro vykreslování souborů různých typů jako HTML, PDF, PNG a JPEG v aplikacích pro jejich zobrazení bez softwaru třetích stran."

  items:
    # feature loop
    - icon: "view"
      title: "Zobrazení dokumentů a obrázků"
      content: "Prohlížejte si dokumenty vykreslováním jako soubory HTML, PDF, PNG a JPEG."

    # feature loop
    - icon: "password"
      title: "Otevřete zabezpečené dokumenty"
      content: "Zadejte heslo pro otevírání zašifrovaných dokumentů."

    # feature loop
    - icon: "load"
      title: "Načtěte soubory odkudkoli"
      content: "Načtěte dokumenty z různých souborů, adres URL, serverů FTP, Amazon S3 a dalších."
    
    # feature loop
    - icon: "pages"
      title: "Vykreslit všechny nebo konkrétní stránky"
      content: "Zadejte rozsah čísel stránek, které se mají vykreslit."


############################# Code samples ############################
code_samples:
  enable: true
  title: "Ukázky kódu GroupDocs.Viewer"
  description: "Některé případy použití typických operací GroupDocs.Viewer v C#, Java, TypeScript"
  items:
    # code sample loop
    - title: "Jak vykreslit soubory DOCX do PDF"
      content: |
       Vykreslujte dokumenty DOCX do formátu PDF bez nainstalovaného programu Microsoft Word nebo jiného softwaru. Snadno načtěte a prohlížejte soubory DOCX ve své aplikaci .NET, ať už se jedná o webovou nebo desktopovou aplikaci. Zde je příklad, jak vykreslit soubor DOCX do PDF:
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Pro vykreslení načtěte soubor DOCX
            using (Viewer viewer = new Viewer("sample.docx"))
            {
              // Vykreslete DOCX do souboru PDF
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
            // Pro vykreslení načtěte soubor DOCX
            try (Viewer viewer = new Viewer("sample.docx")) {
                // Vykreslete DOCX do souboru PDF
                PdfViewOptions viewOptions = new PdfViewOptions();
                viewer.view(viewOptions);
            }
            ```
        - language: "TypeScript"
          color: "green"
          content: |
            ```javascript {style=abap}  
            // Pro vykreslení načtěte soubor DOCX
            const viewer = new groupdocs.viewer.Viewer("sample.docx")
            
            // Vykreslete DOCX do souboru PDF
            const viewOptions = groupdocs.viewer.PdfViewOptions(output.pdf)
            viewer.view(viewOptions)
            ```


############################# Formats ############################
formats:
  enable: true
  title:  "Podporováno více než 180 formátů souborů"
  description: "GroupDocs.Viewer podporuje operace s nejoblíbenějšími [formáty souborů](https://docs.groupdocs.com/viewer/net/supported-document-formats/)"


############################# Metrics ############################

metrics:
  enable: true
  title: "Podrobné metriky a statistické přehledy"
  description: "Ponořte se do podrobného rozpisu našich klíčových údajů a poskytněte komplexní metriky a statistické pohledy na naše úspěchy, dopad a růst."

  items:
    # metrics loop
    - number: "180+"
      title: "Podporované formáty"
      content: "Snadno a bezproblémově prohlížejte více než 180 formátů souborů včetně dokumentů, obrázků a výkresů CAD. Prolomte bariéry kompatibility a přistupujte bez námahy k různým souborům s naším komplexním řešením pro prohlížení."
    # metrics loop
    - number: "1.0M"
      title: "NuGet ke stažení"
      content: "Naše řešení balíčku NuGet se stalo důvěryhodným a široce přijímaným zdrojem v komunitě vývojářů a poskytuje bezproblémovou integraci a cenné funkce pro nespočet projektů."

    # metrics loop
    - number: "10+"
      title: "Knihovny"
      content: "Náš produkt obsahuje více než 10 knihoven, které nabízejí pokročilé funkce pro optimalizaci výkonu. Tyto knihovny jsou navrženy tak, aby splňovaly různé vývojové potřeby s jedinečnými schopnostmi."
    
    # metrics loop
    - number: "100+"
      title: "spokojení zákazníci"
      content: "Obsluhování nejznámějších značek po celém světě. Zjistěte, proč stovky lidí milují GroupDocs.Viewer! Prozkoumejte bezproblémovou navigaci, pohodlnou spolupráci a nesrovnatelně snadné použití. Přidej se teď!"


############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "Naši spokojení zákazníci"
  description: "Knihovny GroupDocs využívají celosvětově renomované a uznávané značky po celém světě."

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
  title: "Jste připraveni začít?"
  description: "Vyzkoušejte funkce GroupDocs.Viewer zdarma nebo si vyžádejte licenci"

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
  title: "Běžné otázky a obavy"
  description: "Najděte odpovědi na běžné dotazy v naší sekci FAQ, abyste mohli rychle řešit své dotazy a obavy."

  items:
    #  loop
    - question: "Mohu ohodnotit produkty GroupDocs před nákupem?"
      answer: |
        Ano! Všechny produkty GroupDocs mají k dispozici zkušební verzi bez rizika. Důrazně doporučujeme vývojářům, aby si před nákupem stáhli a vyzkoušeli naše API, aby bylo zajištěno, že 100% splní vaše potřeby.
    #  loop
    - question: "Dělá GroupDocs předvádění produktů?"
      answer: |
        Ne, zaměřujeme se na naše API a vytváření co nejfunkčnějších a nejstabilnějších produktů. Nabízíme plně funkční a bezplatné zkušební verze ve formě [dočasné licence](https://purchase.groupdocs.com/temporary-license/), abyste si mohli produkt sami vyzkoušet.
    #  loop
    - question: "Kde si mohu produkt stáhnout?"
      answer: |
        Všechny produkty jsou k dispozici ke stažení z [webu](https://releases.groupdocs.com). Neposíláme fyzické kopie našeho softwaru poštou.    
    #  loop
    - question: "Jsou licence pro vývojáře GroupDocs na uživatele nebo na pojmenovaného uživatele?"
      answer: |
        Licence GroupDocs Developer jsou na uživatele, nikoli na pojmenovaného uživatele. Chápeme, že členové kódovacího týmu se mohou v průběhu času měnit a že není praktické pokaždé, když k tomu dojde, aktualizovat licencování.
    #  loop
    - question: "Potřebujeme licencování pouze pro aktivní vývojáře? Například máme tým dvou vývojářů pracujících na směně A a druhý tým dvou vývojářů pracujících na směně B … v této situaci potřebujeme dvě nebo čtyři licence?"
      answer: |
        Všichni vývojáři, kteří na projektu pracují, musí mít licenci. V této situaci GroupDocs vidí váš tým jako čtyřčlenný (i když pracují v různé době).

############################# Cloud ############################

cloud_links:
  enable: true
  title: "GroupDocs.Viewer s nízkým kódem API"
  description: "Zrychlete prohlížení dokumentů nebo obrázků v jakémkoli typu aplikace pomocí našeho cloudového REST API"

  items:
    #  loop
    - icon: "groupdocs_viewer-for-curl"
      title: "GroupDocs.Viewer Cloud for cURL"
      link: "https://products.groupdocs.cloud/viewer/curl"
      content: "Použijte cURL RESTful document viewer API k efektivnímu vykreslování a předvádění Microsoft Office, PDF a různých dalších standardních formátů souborů ve vašich aplikacích."

    #  loop
    - icon: "groupdocs_viewer-for-net"
      title: "GroupDocs.Viewer Cloud for .NET"
      link: "https://products.groupdocs.cloud/viewer/net"
      content: "Vylepšete možnosti prohlížení dokumentů v aplikacích .NET pomocí Cloud SDK pro .NET. Bezproblémově prohlížejte dokumenty ve formátech HTML, PDF nebo obrázků."
    #  loop
    - icon: "groupdocs_viewer-for-java"
      title: "GroupDocs.Viewer Cloud for Java"
      link: "https://products.groupdocs.cloud/viewer/java"
      content: "Integrujte pokročilé možnosti vykreslování dokumentů do svých aplikací Java pomocí účelově vytvořené sady Document Viewer SDK pro Java."

############################# Apps ############################

app_links:
  enable: true
  title: "Aplikace GroupDocs.Viewer NoCode"
  description: "Online aplikace, která vám umožní zobrazit 180+ populárních formátů souborů v prohlížeči"

  items:
    #  loop
    - icon: "groupdocs_viewer-app"
      title: "GroupDocs.Viewer Total"
      link: "https://products.groupdocs.app/viewer/total"
      content: "Prozkoumejte bezplatnou online aplikaci pro zobrazení více než 180 formátů souborů přímo z vašeho preferovaného webového prohlížeče."

    #  loop
    - icon: "groupdocs_words-app"
      title:  "GroupDocs.Viewer DOCX"
      link: "https://products.groupdocs.app/viewer/docx"
      content: "Webový nástroj pro snadné prohlížení souborů Microsoft Word na různých zařízeních."

    #  loop
    - icon: "groupdocs_pdf-app"
      title:  "GroupDocs.Viewer PDF"
      link: "https://products.groupdocs.app/viewer/pdf"
      content: "Otevírejte a prohlížejte soubory PDF online pomocí bezplatného prohlížeče PDF."
    

---