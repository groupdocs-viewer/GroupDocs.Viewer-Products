---
############################# Static ############################
layout: "family"
date: 2023-12-20T06:39:57
draft: false

product: "Viewer"
product_tag: "viewer"

############################# Head ############################
head_title: "Rendera och visa dokument API | On Premise API och onlinetjänst"
head_description: "Återge och visa Word-, PDF-, Excel-, Powerpoint- eller bildfiler enkelt och gratis"

############################# Header ############################
title: "Återge och visa dokument med lätthet"
description: |
  Kraftfullt Viewer API för att rendera olika filer till PDF, HTML och bild.

  Ladda dokument från olika källor, inklusive filer, strömmar, URL:er, FTP-servrar, Amazon S3, Azure Blob Storage och mer.

  Skapa responsiva HTML-sidor, skydda de utgående PDF-filerna och ordna om deras sidor, rotera sidor, rendera anteckningar och kommentarer om det behövs.
  

############################# Platforms ############################
supported_platforms:
  enable: true  
  head_title: "Välj din plattform"
  title: "Plattformar som stöds"
  description: "GroupDocs.Viewer-biblioteket stöder följande operativsystem och ramverk"
  details_link_title: "Läs mer"
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
        - content: "180+ file formats"
          rows: "1"
        # features loop
        - content: "UI package for ASP.NET Core"
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
        - content:  "180+ file formats"
          rows: "1"
        # features loop
        - content:  "UI package for Spring and Dropwizard"
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
        - content:  "180+ file formats"
          rows: "1"
        # features loop
        - content:  "UI package - coming soon "
          rows: "1" 
        # features loop
        - content:  "Demo - coming soon "
          rows: "3" 



############################# Features ############################

features:
  enable: true
  title: "GroupDocs.Viewers funktionsuppsättning"
  description: "API för att rendera filer av olika typer som HTML, PDF, PNG och JPEG i applikationer för att visa dem utan programvara från tredje part."

  items:
    # feature loop
    - icon: "view"
      title: "Visa dokument och bilder"
      content: "Visa dokument genom att rendera dem som HTML-, PDF-, PNG- och JPEG-filer."
    # feature loop
    - icon: "password"
      title: "Öppna säkrade dokument"
      content: "Ange ett lösenord för att öppna krypterade dokument."

    # feature loop
    - icon: "load"
      title: "Ladda filer var som helst"
      content: "Ladda dokument från olika filer, URL:er, FTP-servrar, Amazon S3 och mer."
    
    # feature loop
    - icon: "pages"
      title: "Rendera alla eller specifika sidor"
      content: "Ange ett intervall av sidnummer som ska renderas."


############################# Code samples ############################
code_samples:
  enable: true
  title: "GroupDocs.Viewer-kodexempel"
  description: "Vissa använder fall av typiska GroupDocs.Viewer-operationer i C#, Java, TypeScript"
  items:
    # code sample loop
    - title: "Hur man renderar DOCX-filer till PDF"
      content: |
        Återge DOCX-dokument till PDF utan Microsoft Word eller annan programvara installerad. Ladda enkelt och visa DOCX-filer i din .NET-applikation, oavsett om det är ett webb- eller skrivbordsprogram. Här är ett exempel på hur man renderar en DOCX-fil till PDF: 
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Ladda DOCX-fil för att rendera
            using (Viewer viewer = new Viewer("sample.docx"))
            {
              // Rendera DOCX till en PDF-fil
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
            // Ladda DOCX-fil för att rendera
            try (Viewer viewer = new Viewer("sample.docx")) {
                // Rendera DOCX till en PDF-fil
                PdfViewOptions viewOptions = new PdfViewOptions();
                viewer.view(viewOptions);
            }
            ```
        - language: "TypeScript"
          color: "green"
          content: |
            ```javascript {style=abap}  
            // Ladda DOCX-fil för att rendera
            const viewer = new groupdocs.viewer.Viewer("sample.docx")
            
            // Rendera DOCX till en PDF-fil
            const viewOptions = groupdocs.viewer.PdfViewOptions(output.pdf)
            viewer.view(viewOptions)
            ```


############################# Formats ############################
formats:
  enable: true
  title:  "180+ filformat stöds"
  description: "GroupDocs.Viewer stöder operationer med de mest populära [filformaten](https://docs.groupdocs.com/viewer/net/supported-document-formats/)" 



############################# Metrics ############################

metrics:
  enable: true
  title: "Fördjupade mätvärden och statistiska insikter"
  description: "Dyk in i en detaljerad uppdelning av våra nyckeltal, som ger omfattande mätvärden och statistiska insikter om våra prestationer, påverkan och tillväxt."

  items:
    # metrics loop
    - number: "180+"
      title: "Format som stöds"
      content: "Visa enkelt över 180 filformat inklusive dokument, bilder och CAD-ritningar utan problem. Bryt kompatibilitetsbarriärer och få tillgång till olika filer utan ansträngning med vår omfattande visningslösning."

    # metrics loop
    - number: "1.0M"
      title: "NuGet-nedladdningar"
      content: "Vår NuGet-paketlösning har blivit en pålitlig och allmänt använd resurs i utvecklargemenskapen, som ger sömlös integration och värdefull funktionalitet för otaliga projekt."

    # metrics loop
    - number: "10+"
      title: "Bibliotek"
      content: "Vår produkt inkluderar 10+ bibliotek, som erbjuder avancerade funktioner för att optimera prestanda. Dessa bibliotek är designade för att uppfylla olika utvecklingsbehov med oöverträffade möjligheter."
    
    # metrics loop
    - number: "100+"
      title: "Nöjda kunder"
      content: "Serverar de mest ikoniska varumärkena runt om i världen. Upptäck varför hundratals älskar GroupDocs.Viewer! Utforska sömlös navigering, bekvämt samarbete och oöverträffad användarvänlighet. Gå med nu!"



############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "Våra nöjda kunder"
  description: "GroupDocs-bibliotek är anställda av globalt kända och framstående varumärken över hela världen."

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
  title: "Redo att komma igång?"
  description: "Prova GroupDocs.Viewer-funktioner gratis eller begär en licens"
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
  title:  "Vanliga frågor och funderingar"
  description:  "Hitta svar på vanliga frågor i vår FAQ-sektion för att snabbt lösa dina frågor och funderingar."
  items:
    #  loop
    - question: "Kan jag utvärdera GroupDocs-produkter innan jag köper dem?"
      answer: |
        Ja! Alla GroupDocs-produkter har en riskfri utvärderingsversion tillgänglig. Vi uppmuntrar starkt utvecklare att ladda ner och prova våra API:er innan de köper för att säkerställa att de uppfyller dina behov till 100 %.
    #  loop
    - question: "Gör GroupDocs produktdemonstrationer?"
      answer: |
        Nej, vårt fokus ligger på våra API:er och att göra så funktionella och stabila produkter som möjligt. Vi erbjuder fullt fungerande och kostnadsfria testversioner i form av en [tillfällig licens](https://purchase.groupdocs.com/temporary-license/) så att du kan testa produkten själv.    
    #  loop
    - question: "Var kan jag ladda ner produkten?"
      answer: |
        Alla produkter är tillgängliga att ladda ner från [webbplatsen](https://releases.groupdocs.com). Vi skickar inte fysiska kopior av vår programvara via post.
    #  loop
    - question: "Är GroupDocs utvecklarlicenser per användare eller per namngiven användare?"
      answer: |
        GroupDocs-utvecklarlicenser är per användare, inte per namngiven användare. Vi förstår att medlemmar i ett kodningsteam kan förändras med tiden och att det inte är praktiskt att behöva uppdatera licenserna varje gång det inträffar.
    #  loop
    - question: "Behöver vi licensiering endast för aktiva utvecklare? Till exempel har vi ett team med två utvecklare som arbetar på skift A och ett andra team på två utvecklare som arbetar på skift B … i den här situationen, behöver vi två eller fyra licenser?"
      answer: |
        Alla utvecklare som arbetar med projektet måste vara licensierade. I den här situationen ser GroupDocs att ditt team har fyra medlemmar (även om de arbetar vid olika tidpunkter). 


############################# Cloud ############################

cloud_links:
  enable: true
  title: "GroupDocs.Viewer API:er med låg kod"
  description: "Accelerera dokument- eller bildvisning i alla typer av applikationer med vårt molnbaserade REST API"

  items:
    #  loop
    - icon: "groupdocs_viewer-for-curl"
      title: "GroupDocs.Viewer Cloud for cURL"
      link: "https://products.groupdocs.cloud/viewer/curl"
      content: "Använd cURL RESTful document viewer API för att effektivt rendera och visa upp Microsoft Office, PDF och olika andra standardfilformat i dina applikationer."

    #  loop
    - icon: "groupdocs_viewer-for-net"
      title: "GroupDocs.Viewer Cloud for .NET"
      link: "https://products.groupdocs.cloud/viewer/net"
      content: "Förbättra dokumentvisningsmöjligheterna i .NET-applikationer med Cloud SDK för .NET. Visa dokument sömlöst i HTML-, PDF- eller bildformat."

    #  loop
    - icon: "groupdocs_viewer-for-java"
      title: "GroupDocs.Viewer Cloud for Java"
      link: "https://products.groupdocs.cloud/viewer/java"
      content: "Integrera avancerade dokumentåtergivningsmöjligheter i dina Java-applikationer med hjälp av en specialbyggd Document Viewer SDK för Java."
    

############################# Apps ############################

app_links:
  enable: true
  title: "GroupDocs.Viewer NoCode-appar"
  description: "Onlineapplikation som låter dig se 180+ populära filformat i webbläsaren"

  items:
    #  loop
    - icon: "groupdocs_viewer-app"
      title: "GroupDocs.Viewer Total"
      link: "https://products.groupdocs.app/viewer/total"
      content: "Utforska ett gratis onlineprogram för att se över 180 filformat direkt från din favoritwebbläsare."

    #  loop
    - icon: "groupdocs_words-app"
      title:  "GroupDocs.Viewer DOCX"
      link: "https://products.groupdocs.app/viewer/docx"
      content: "Webbaserat verktyg för att enkelt visa Microsoft Word-filer på olika enheter."

    #  loop
    - icon: "groupdocs_pdf-app"
      title:  "GroupDocs.Viewer PDF"
      link: "https://products.groupdocs.app/viewer/pdf"
      content: "Öppna och visa PDF-filer online med gratis PDF-visare."
    



---