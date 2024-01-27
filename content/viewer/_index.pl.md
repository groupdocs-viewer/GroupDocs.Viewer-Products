---
############################# Static ############################
layout: "family"
date: 2023-12-20T06:39:57
draft: false

product: "Viewer"
product_tag: "viewer"

############################# Head ############################
head_title: "Interfejs API renderowania i przeglądania dokumentów | Lokalne API i usługa online"
head_description: "Renderuj i przeglądaj pliki Word, PDF, Excel, Powerpoint lub obrazy łatwo i bezpłatnie"

############################# Header ############################
title: "Z łatwością renderuj i przeglądaj dokumenty"
description: |
  Potężny interfejs API przeglądarki do renderowania różnych plików do formatu PDF, HTML i obrazu.

  Ładuj dokumenty z różnych źródeł, w tym plików, strumieni, adresów URL, serwerów FTP, Amazon S3, Azure Blob Storage i innych.

  Generuj responsywne strony HTML, chroń wyjściowe pliki PDF i zmieniaj kolejność ich stron, obracaj strony, renderuj notatki i komentarze, jeśli to konieczne.
  

############################# Platforms ############################
supported_platforms:
  enable: true  
  head_title: "Wybierz swoją platformę"
  title: "Obsługiwane platformy"
  description: "Biblioteka GroupDocs.Viewer obsługuje następujące systemy operacyjne i struktury"
  details_link_title: "Ucz się więcej"
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
  title: "Zestaw funkcji GroupDocs.Viewer"
  description: "API do renderowania plików różnych typów jako HTML, PDF, PNG i JPEG w aplikacjach w celu przeglądania ich bez oprogramowania innych firm."

  items:
    # feature loop
    - icon: "view"
      title: "Przeglądaj dokumenty i obrazy"
      content: "Przeglądaj dokumenty, renderując je jako pliki HTML, PDF, PNG i JPEG."
    # feature loop
    - icon: "password"
      title: "Otwórz zabezpieczone dokumenty"
      content: "Określ hasło, aby otwierać zaszyfrowane dokumenty."

    # feature loop
    - icon: "load"
      title: "Ładuj pliki z dowolnego miejsca"
      content: "Ładuj dokumenty z różnych plików, adresów URL, serwerów FTP, Amazon S3 i innych."
    
    # feature loop
    - icon: "pages"
      title: "Renderuj wszystkie lub wybrane strony"
      content: "Określ zakres numerów stron, które mają być renderowane."


############################# Code samples ############################
code_samples:
  enable: true
  title: "Przykłady kodu GroupDocs.Viewer"
  description: "Niektóre przypadki użycia typowych operacji GroupDocs.Viewer w językach C#, Java, TypeScript"
  items:
    # code sample loop
    - title: "Jak renderować pliki DOCX do formatu PDF"
      content: |
        Renderuj dokumenty DOCX do formatu PDF bez instalowania programu Microsoft Word lub innego oprogramowania. Z łatwością ładuj i przeglądaj pliki DOCX w aplikacji .NET, niezależnie od tego, czy jest to aplikacja internetowa, czy komputerowa. Oto przykład renderowania pliku DOCX do formatu PDF: 
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Załaduj plik DOCX do renderowania
            using (Viewer viewer = new Viewer("sample.docx"))
            {
              // Renderuj DOCX do pliku PDF
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
            // Załaduj plik DOCX do renderowania
            try (Viewer viewer = new Viewer("sample.docx")) {
                // Renderuj DOCX do pliku PDF
                PdfViewOptions viewOptions = new PdfViewOptions();
                viewer.view(viewOptions);
            }
            ```
        - language: "TypeScript"
          color: "green"
          content: |
            ```javascript {style=abap}  
            // Załaduj plik DOCX do renderowania
            const viewer = new groupdocs.viewer.Viewer("sample.docx")
            
            // Renderuj DOCX do pliku PDF
            const viewOptions = groupdocs.viewer.PdfViewOptions(output.pdf)
            viewer.view(viewOptions)
            ```


############################# Formats ############################
formats:
  enable: true
  title:  "Obsługiwanych jest ponad 180 formatów plików"
  description: "GroupDocs.Viewer obsługuje operacje na najpopularniejszych [formatach plików](https://docs.groupdocs.com/viewer/net/supported-document-formats/)" 



############################# Metrics ############################

metrics:
  enable: true
  title: "Dogłębne metryki i spostrzeżenia statystyczne"
  description: "Zapoznaj się ze szczegółowym zestawieniem naszych kluczowych danych liczbowych, dostarczając kompleksowych wskaźników i wglądu statystycznego w nasze osiągnięcia, wpływ i rozwój."

  items:
    # metrics loop
    - number: "180+"
      title: "Obsługiwane formaty"
      content: "Z łatwością przeglądaj ponad 180 formatów plików, w tym dokumenty, obrazy i rysunki CAD. Przełam bariery kompatybilności i uzyskaj łatwy dostęp do różnorodnych plików dzięki naszemu kompleksowemu rozwiązaniu do przeglądania."

    # metrics loop
    - number: "1.0M"
      title: "Pobieranie NuGeta"
      content: "Nasze rozwiązanie pakietowe NuGet stało się zaufanym i powszechnie stosowanym zasobem w społeczności programistów, zapewniając bezproblemową integrację i cenną funkcjonalność dla niezliczonych projektów."

    # metrics loop
    - number: "10+"
      title: "Biblioteki"
      content: "Nasz produkt zawiera ponad 10 bibliotek oferujących zaawansowane funkcje optymalizujące wydajność. Biblioteki te zaprojektowano tak, aby spełniały różne potrzeby programistyczne i zapewniały niezrównane możliwości."
    
    # metrics loop
    - number: "100+"
      title: "Szczęśliwi klienci"
      content: "Obsługujemy najbardziej kultowe marki na całym świecie. Odkryj, dlaczego setki osób uwielbiają GroupDocs.Viewer! Poznaj płynną nawigację, wygodną współpracę i niezrównaną łatwość obsługi. Dołącz teraz!"



############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "Nasi zadowoleni klienci"
  description: "Z bibliotek GroupDocs korzystają znane i cenione na całym świecie marki."

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
  title: "Gotowy żeby zacząć?"
  description: "Wypróbuj bezpłatnie funkcje GroupDocs.Viewer lub poproś o licencję"
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
  title:  "Często zadawane pytania i wątpliwości"
  description:  "Znajdź odpowiedzi na często zadawane pytania w naszej sekcji FAQ, aby szybko odpowiedzieć na swoje pytania i wątpliwości."
  items:
    #  loop
    - question: "Czy mogę ocenić produkty GroupDocs przed zakupem?"
      answer: |
        Tak! Wszystkie produkty GroupDocs są dostępne w wersji próbnej pozbawionej ryzyka. Gorąco zachęcamy programistów do pobrania i wypróbowania naszych interfejsów API przed zakupem, aby mieć pewność, że w 100% zaspokoją Twoje potrzeby.
    #  loop
    - question: "Czy GroupDocs przeprowadza demonstracje produktów?"
      answer: |
        Nie, skupiamy się na naszych interfejsach API i tworzeniu jak najbardziej funkcjonalnych i stabilnych produktów. Oferujemy w pełni funkcjonalne i bezpłatne wersje próbne w formie [licencji tymczasowej](https://purchase.groupdocs.com/temporary-license/), dzięki czemu możesz samodzielnie przetestować produkt.    
    #  loop
    - question: "Gdzie mogę pobrać produkt?"
      answer: |
        Wszystkie produkty można pobrać z [strony internetowej](https://releases.groupdocs.com). Nie wysyłamy fizycznych kopii naszego oprogramowania pocztą.
    #  loop
    - question: "Czy licencje programistyczne GroupDocs są na użytkownika czy na nazwanego użytkownika?"
      answer: |
        Licencje GroupDocs Developer są przydzielane na użytkownika, a nie na nazwanego użytkownika. Rozumiemy, że członkowie zespołu programistycznego mogą zmieniać się z biegiem czasu i że konieczność aktualizowania licencji za każdym razem jest niepraktyczna.
    #  loop
    - question: "Czy potrzebujemy licencji tylko dla aktywnych programistów? Przykładowo mamy zespół dwóch programistów pracujących na zmianie A i drugi zespół dwóch programistów pracujących na zmianie B… w tej sytuacji potrzebujemy dwóch czy czterech licencji?"
      answer: |
        Wszyscy programiści pracujący nad projektem muszą posiadać licencję. W tej sytuacji GroupDocs postrzega Twój zespół jako składający się z czterech członków (mimo że pracują oni w różnych godzinach). 


############################# Cloud ############################

cloud_links:
  enable: true
  title: "Interfejsy API o niskim kodzie GroupDocs.Viewer"
  description: "Przyspiesz przeglądanie dokumentów lub obrazów w dowolnej aplikacji dzięki naszemu opartemu na chmurze interfejsowi API REST"

  items:
    #  loop
    - icon: "groupdocs_viewer-for-curl"
      title: "GroupDocs.Viewer Cloud for cURL"
      link: "https://products.groupdocs.cloud/viewer/curl"
      content: "Użyj interfejsu API przeglądarki dokumentów cURL RESTful, aby efektywnie renderować i prezentować pliki Microsoft Office, PDF i różne inne standardowe formaty plików w swoich aplikacjach."

    #  loop
    - icon: "groupdocs_viewer-for-net"
      title: "GroupDocs.Viewer Cloud for .NET"
      link: "https://products.groupdocs.cloud/viewer/net"
      content: "Zwiększ możliwości przeglądania dokumentów w aplikacjach .NET dzięki Cloud SDK dla .NET. Bezproblemowo przeglądaj dokumenty w formatach HTML, PDF lub obrazów."

    #  loop
    - icon: "groupdocs_viewer-for-java"
      title: "GroupDocs.Viewer Cloud for Java"
      link: "https://products.groupdocs.cloud/viewer/java"
      content: "Zintegruj zaawansowane możliwości renderowania dokumentów z aplikacjami Java, korzystając ze specjalnie zaprojektowanego pakietu SDK przeglądarki dokumentów dla języka Java."
    

############################# Apps ############################

app_links:
  enable: true
  title: "Aplikacje GroupDocs.Viewer NoCode"
  description: "Aplikacja internetowa umożliwiająca przeglądanie ponad 180 popularnych formatów plików w przeglądarce"

  items:
    #  loop
    - icon: "groupdocs_viewer-app"
      title: "GroupDocs.Viewer Total"
      link: "https://products.groupdocs.app/viewer/total"
      content: "Poznaj bezpłatną aplikację online, która umożliwia przeglądanie ponad 180 formatów plików bezpośrednio w preferowanej przeglądarce internetowej."

    #  loop
    - icon: "groupdocs_words-app"
      title:  "GroupDocs.Viewer DOCX"
      link: "https://products.groupdocs.app/viewer/docx"
      content: "Narzędzie internetowe umożliwiające łatwe przeglądanie plików Microsoft Word na różnych urządzeniach."

    #  loop
    - icon: "groupdocs_pdf-app"
      title:  "GroupDocs.Viewer PDF"
      link: "https://products.groupdocs.app/viewer/pdf"
      content: "Otwieraj i przeglądaj pliki PDF online za pomocą bezpłatnej przeglądarki plików PDF."
    



---