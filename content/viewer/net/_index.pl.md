---
############################# Static ##########################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

lang: pl
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: "Interfejs API przeglądarki dokumentów .NET, renderowanie diagramu HTML obrazu PDF Word Excel"
head_description: "Przeglądarka plików C# ASP.NET i interfejs API renderowania. Dodaj przeglądarkę PDF, przeglądarkę Word, przeglądarkę Excel, przeglądarkę obrazów, przeglądarkę HTML, przeglądarkę poczty e-mail w aplikacjach .NET."

############################# Header ##########################
title: "Renderuj i wyświetlaj dokumenty poprzez .NET API"
description: "Interfejs API przeglądarki dokumentów .NET do renderowania ponad 190 formatów dokumentów do formatu PDF, HTML i obrazu z zaawansowanymi opcjami konfiguracji."
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
              text: "Przegląd"

            # button loop
            - link: "#features"
              text: "Cechy"

            # button loop
            - link: "#support"
              text: "Wsparcie"

            # button loop
            - link: "https://products.groupdocs.app/viewer/total"
              text: "Demo na żywo"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "cennik"

    right:
        link_download: "https://www.nuget.org/packages/GroupDocs.Viewer"
        link_learn: "https://docs.groupdocs.com/viewer/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    content: |
      GroupDocs.Viewer for .NET API pomaga tworzyć zaawansowane aplikacje w C#, ASP.NET i innych technologiach opartych na .NET, które mogą renderować i wyświetlać dokumenty i obrazy w ponad 190 formatach plików bez instalowania jakiegokolwiek zewnętrznego oprogramowania. Biblioteka przeglądarki plików rasteryzuje dokumenty, a następnie konwertuje je do formatu SVG+HTML+CSS, aby zoptymalizować ogólne renderowanie dokumentów w celu przeglądania dokumentów biznesowych, obrazów, plików tekstowych, diagramów, grafiki, załączników do wiadomości e-mail i plików PDF z szybkością, prawdziwym tekstem i wysoka wierność wewnątrz aplikacji. Masz możliwość dodania funkcji przeglądania i czytania dokumentów w swoich aplikacjach, aby wyświetlić cały dokument, dokument częściowy, określony zakres stron/komórek, pojedynczą warstwę dokumentu, z adnotacjami i komentarzami lub bez nich dla obsługiwanych formatów plików.
       
      GroupDocs.Viewer for .NET domyślnie buforuje wyrenderowane dokumenty na dysk lokalny. Każdy rodzaj zewnętrznej pamięci podręcznej jest również obsługiwany poprzez implementację odpowiednich interfejsów – Amazon S3, Dropbox, Google Drive, Windows Azure, Redis lub dowolny inny.
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          Poniżej znajduje się omówienie GroupDocs.Viewer dla platformy .NET:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Przegląd"
          content: |
            * Wyświetl ponad 190 typów dokumentów 
            * Pobierz plik w formacie HTML, Obraz, PDF 
            * Obróć i zmień kolejność 
            * Zastosuj znak wodny 
            * Pamięć podręczna dla szybkiego procesu 
            * Dodaj niestandardowe czcionki 
            * Zastosuj standardy kodowania 
            * Niestandardowy program obsługi danych wejściowych 
            * Renderuj ze śledzeniem zmian 
            * Renderuj jako responsywny HTML 
            * Renderuj warstwy PDF i CAD 
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Viewer dla .NET obsługuje przeglądanie wszystkich popularnych formatów plików dokumentów. Wystarczy kilka wierszy kodu, aby dodać przeglądarkę plików PDF, program Microsoft Office Word, arkusz kalkulacyjny Excel, obraz, kod HTML, pocztę e-mail programu Outlook, program OneNote, wyświetlanie projektów i grafiki w aplikacjach .NET.

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
                * **Pliki układu strony:** PDF, TEX, XPS, OXPS
                * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG, OTG, FODP, FODG
                * **Wartości oddzielone ogranicznikami:** CSV, TSV
                * **Sieć:** HTML, MHT, MHTML
                * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
                * **PostScript:** PS, EPS
                * **Archiwa:** ZIP, TAR, BZ2, GZ, RAR, RAR5
                * **Różny:** OBJ, EPUB, MOBI, DjVu, XML, VCF, VCARD, NUMBERS, NSF

        right:
          enable: true
          table:
            # table loop
            - title: "Obrazy, grafika i diagramy"
              content: |
                * **Obrazy:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB
                * **Ikona Windowsa:** ICO
                * **Skalowalna Grafika wektorowa:** SVG, CDR, CMX, IGS, SVGZ
                * **JPEG2000:** JP2, J2C, J2K, JPC, JPF, JPX, JPM
                * **Adobe Photoshop:** PSD, PSB
                * **Język poleceń drukarki:** PCL
                * **Litografia stereoskopowa (drukowanie 3D):** STL
                * **Zajęcia z podstaw przemysłu:** IFC
                * **Obrazowanie medyczne:** DICOM
                * **Dokumenty plotera:** PLT, HPG
                * **Formaty internetowe Autodesk Design:** DWF, DWG
                * **Rysunek AutoCAD:** DWT, IFC, STL, CF2
                * **DGN oparty na ISFF (V7):** DGN

            # table loop
            - title: "Formaty języków programowania"
              content: |
                * **Pliki C/C++/C#:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
                * **Pliki Java/JavaScript:** JAVA, JS, JSON, PROPERTIES
                * **Różny:** VB, PHP, SQL, PL, PY, PV, RB, RST, SASS, SCALA, SCM, SCRIPT, AS, AS3, ASM, BAT, CMAKE, CSS, DIFF, ERB, GROOVY, HAML, LESS, LOG, M, MAKE, MD, ML, MM, SH, SML, VIM, YAML

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Viewer for .NET obsługuje następujące systemy operacyjne, frameworki i menedżery pakietów:
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "System operacyjny"
              content: |
                * Microsoft Windows Server 2003 i nowsze 
                * Microsoft Windows XP i nowsze 
                * Microsoft Windows 10 i 11 
                * Linux (Ubuntu, OpenSUSE, CentOS i inne) 
                * Mac OS X 

            # table loop
            - icon: "fas fa-code"
              title: "Obsługiwane frameworki"
              content: |
                * .NET Framework 2.0 lub nowszy 
                * .NET Core 3.1 
                * .NET 5 lub nowszy 

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-box"
              title: "Menedżer pakietów"
              content: |
                * NuGet

            # table loop
            - icon: "fas fa-tools"
              title: "Środowiska programistyczne"
              content: |
                * Microsoft Visual Studio
                * Visual Studio Code
                * .NET CLI

############################# Features ############################
features:
    enable: true
    title: "GroupDocs.Viewer dla funkcji platformy .NET"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "Rasteryzuj dokumenty i konwertuj je do SVG, HTML i CSS"

      # feature loop
      - icon: "fas fa-eye"
        content: "Konwertuj tekst na HTML i renderuj dokumenty, aby uzyskać reprezentację HTML, obrazu lub PDF"

      # feature loop
      - icon: "fas fa-bolt"
        content: "Krótszy czas ładowania przy użyciu buforowanych wersji dokumentów"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "Konwertuj prezentacje z kształtami i tekstem z efektami 3D"

      # feature loop
      - icon: "fas fa-code"
        content: "Koduj dokumenty Word, Excel i e-mail do żądanego standardu kodowania"

      # feature loop
      - icon: "fas fa-cloud"
        content: "Renderuj dokumenty znajdujące się w lokalizacjach FTP lub Cloud Storage"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "Wykluczanie czcionek podczas renderowania do formatu HTML w celu zmniejszenia rozmiaru pliku wynikowego"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "Zminimalizuj dane wyjściowe CSS i HTML, usuwając komentarze, dodatkowe białe spacje itp."

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "Przeczytaj tekst zawarty w dokumencie źródłowym poprzez jego współrzędne"

      # feature loop
      - icon: "fas fa-border-all"
        content: "Pokaż/ukryj linie siatki arkuszy Excel w reprezentacji wyników"

      # feature loop
      - icon: "fas fa-wrench"
        content: "Określ liczbę wierszy w arkuszu programu Excel, które mają być renderowane na każdej stronie"

      # feature loop
      - icon: "fas fa-columns"
        content: "Ignoruj ​​puste kolumny podczas renderowania dokumentów arkusza kalkulacyjnego"

      # feature loop
      - icon: "fas fa-file-word"
        content: "Renderuj dokumenty programu Word na strony HTML, obrazy lub pliki PDF ze śledzeniem zmian"

      # feature loop
      - icon: "fas fa-envelope"
        content: "Renderuj załączniki wiadomości e-mail jako oryginalne pliki, obrazy lub w formacie HTML"

      # feature loop
      - icon: "fas fa-print"
        content: "Ustaw ograniczenia drukowania dla dokumentów PDF"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "Renderuj zawartość/pliki zawarte w archiwach ZIP jako załączniki"

      # feature loop
      - icon: "fas fa-lock"
        content: "Uzyskaj załączniki z dokumentów chronionych hasłem"

      # feature loop
      - icon: "fas fa-file-code"
        content: "Renderuj formaty plików języków programowania jako zwykły tekst"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "Dostosuj kolory tła podczas przeglądania rysunków CAD"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "Przeglądaj dokumenty programu Excel i konwertuj do formatu PDF, HTML, JPG i PNG"

      # feature loop
      - icon: "fas fa-heading"
        content: "Pobierz nazwy arkuszy z pliku Excel - Wyświetl nagłówki kolumn arkusza kalkulacyjnego i numery wierszy"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "Przeglądaj i konwertuj dokumenty Microsoft Project za pomocą notatek"

      # feature loop
      - icon: "fas fa-cube"
        content: "Konwertuj rysunki CAD na format SVG, aby uzyskać lepsze wrażenia podczas przeglądania i powiększania"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "Wybierz opcję Renderuj figury programu Visio bez schematu"

    more_feature:
      # more_feature_loop
      - title: "Przeglądaj dokumenty wydajnie i niezawodnie"
        content: |
          Korzystając z API GroupDocs.Viewer, możesz wydajnie i niezawodnie wyświetlać ponad 190 formatów dokumentów z nienaruszoną integralnością treści i struktury dokumentu. Poniższy przykładowy kod pokazuje, jak łatwo jest wyświetlić reprezentację HTML dokumentu DOCX:

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
      - title: "Zastosuj transformację do renderowanego wyjścia"
        content: "Możesz wykonać różne przekształcenia renderowanego dokumentu wyjściowego przy użyciu GroupDocs.Viewer for .NET API. Te opcje transformacji zapewniają kontrolę nad sposobem prezentacji renderowanego wyniku do wyświetlenia. Dostępne przekształcenia to opcja obracania strony, opcja zmiany kolejności stron oraz zastosowanie tekstowego znaku wodnego."

      # more_feature_loop
      - title: "Praca z plikami danych programu Outlook"
        content: "GroupDocs.Viewer for .NET API może renderować elementy w plikach danych programu Outlook (OST/PST) jako pliki PDF, HTML i obrazy. Nasz Viewer API ma również możliwość uzyskania listy folderów zawartych w plikach danych programu Outlook. Korzystając z GroupDocs.Viewer for .NET API, możesz określić folder do renderowania z plików danych programu Outlook. Podobnie, możesz również otrzymywać wiadomości e-mail zawarte w formatach OST/PST jako załączniki. GroupDocs.Viewer for .NET umożliwia także filtrowanie wiadomości z formatów OST/PST na podstawie tematu, treści lub nadawcy."

      # more_feature_loop
      - title: "Praca z dokumentami CAD"
        content: "GroupDocs.Viewer for .NET API może renderować model i wszystkie niepuste układy lub renderować określony układ pliku CAD. GroupDocs.Viewer for .NET API obsługuje również renderowanie kafelkowe lub renderowanie według współrzędnych dokumentów CAD do obrazu, HTML lub PDF. Można również uzyskiwać statusy warstw dla dokumentów CAD."

############################# Testimonials ###############################
testimonials:
  enable: true

  testimonial:
    # testimonial item loop
    - name: "Margot Baill"
      designation: "Dyrektor ds. Rozwoju Produktu w Hireology"
      content: "Integracja GroupDocs.Viewer for Cloud API była prosta dzięki ich fantastycznemu Ruby SDK. Nie ma tak wielu firm, które chcą z nami pracować nad tym, czego chcemy. To świetne partnerstwo."

    # testimonial item loop
    - name: "Mats Oustad"
      designation: "Starszy Konsultant/Partner w Novanet AS"
      content: "Po zaimplementowaniu i użyciu GroupDocs.Viewer dla .NET w projekcie wygląda na to, że działa bardzo dobrze. Testowałem z wieloma dokumentami i jak dotąd tak dobrze. Wszystko, co na niego rzuciłem, renderuje się ładnie i wygląda tak samo dobrze, jak w przeglądarce plików PDF lub MS Word."
              
    # testimonial item loop
    - name: "Martin Lasarga"
      designation: "Product Manager w Axentria ECM by G.S.I."
      content: "Doskonała obsługa i doskonałe produkty. Byli niezwykle pomocni i responsywni podczas procesu implementacji GroupDocs.Viewer for .NET, nie mogę ich wystarczająco polecić."

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Viewer oferuje interfejsy API przeglądania dokumentów dla innych popularnych środowisk programistycznych"

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
