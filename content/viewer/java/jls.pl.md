---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: pl

############################# Head #############################
head_title: "Java JLS Viewer API — renderowanie i wyświetlanie JLS w aplikacjach Java"
head_description: "Zobacz pliki JLS w aplikacjach Java, J2EE, J2SE. Obsługuje przeglądanie ponad 170 formatów dokumentów i plików obrazów w trybie HTML, PDF lub obrazu z zaawansowanymi funkcjami do zarządzania opcjami przeglądania dokumentów."

############################# Header ############################
title: "Renderuj i przeglądaj DOCX JLS w Javie" 
description: "Natywny i wydajny interfejs API przeglądarki plików JLS dla aplikacji opartych na językach Java, J2EE i J2SE, obsługujący szeroki zakres dodatkowych funkcji umożliwiających dostosowanie wyglądu formatu dokumentu wyjściowego." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Pobierz darmową wersję próbną"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Informacje o GroupDocs.Viewer for Java API" 
    content: |
        Włącz w aplikacjach Java wyświetlanie ponad 170 formatów plików w trybach HTML, PDF lub graficznych za pomocą interfejsów API GroupDocs.Viewer for Java bez instalowania dodatkowego oprogramowania; takich jak Microsoft Office, Apache Open Office, Adobe Acrobat Reader itp. Programiści mogą łatwo przeglądać wszystkie popularne obrazy i typy dokumentów, w tym Microsoft Office, OpenDocument, HTML, PDF, Archive, Diagrams, Photoshop, AutoCAD i formaty języków programowania wewnątrz aplikacji Java za pomocą szybkie i najwyższej jakości renderowanie.

############################# SubMenu ############################
submenu:
    enable: true

    left:
        img_alt: "GroupDocs.Viewer for .NET"
        image: "https://cms.admin.containerize.com/templates/groupdocs/images/product-logos/90x90-noborder/groupdocs-viewer-net.png"
        product: "GroupDocs.Viewer"
        platform: ".NET"

    middle:
        button:

            # button loop
            - link: "https://apireference.groupdocs.com/viewer/net"
              text: "Odniesienie do interfejsu API"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Przykłady kodu"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Demo na żywo"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "cennik"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "Kroki renderowania pliku JLS w Java" 
    content_left: |
        Dzięki [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/) możesz w kilku krokach wyrenderować JLS do formatu HTML, JPEG, PNG lub PDF.

        * Dodaj [GroupDocs.Viewer for Java](https://releases.groupdocs.com/viewer/java/) jako zależność do swojego projektu. 
        * Utwórz instancję klasy Viewer i załaduj plik JLS z pełną ścieżką. 
        * Ustaw opcje renderowania pliku JLS do formatu HTML, PNG, JPEG lub PDF. 
        * Renderuj plik i sprawdź dane wyjściowe w bieżącym katalogu. 
        
    title_right: "wymagania systemowe" 
    content_right: |
        Interfejsy API GroupDocs.Viewer for Java są obsługiwane na wszystkich głównych platformach i systemach operacyjnych. Przed wykonaniem poniższego kodu upewnij się, że w systemie są zainstalowane następujące wymagania wstępne.

        * Systemy operacyjne: Microsoft Windows, Linux, MacOS 
        * Środowiska programistyczne: NetBeans, IntelliJ IDEA, Eclipse itp. 
        * Ramy: J2SE 8.0 (1.8) lub nowszy (na przykład Java 17) 
    code: |
        ```java
                        
            // Set up input JLS file
            String filePath = "input.jls";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render JLS file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "JLS Przeglądarka Demo na żywo"
    content: |
        Wyświetl teraz plik JLS, odwiedzając witrynę [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/jls).
    lang: "pl"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Inne formaty plików Renderowanie i przeglądanie przy użyciu Java"
    exclude: "JLS"
    content: |
        Wieloformatowe API przeglądarki dokumentów i obrazów dla języka Java. Zobacz niektóre z popularnych formatów plików poniżej bez zewnętrznych przeglądarek.
    format: 
        # format loop 1
        - name: "Renderuj DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Otwarty dokument XML" 

        # format loop 2
        - name: "Renderuj CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "Plik CorelDRAW" 

        # format loop 3
        - name: "Renderuj PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "Prezentacja PowerPoint Open XML" 

        # format loop 4
        - name: "Renderuj XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Arkusz kalkulacyjny Microsoft Excel Open XML" 

        # format loop 5
        - name: "Renderuj DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "Rysunek AutoCAD"

        # format loop 6
        - name: "Renderuj XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "Plik XML"

        # format loop 7
        - name: "Renderuj PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Dokument Adobe Photoshop"

        # format loop 8
        - name: "Renderuj plik Adobe Illustrator"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Grafika Adobe Illustrator"

        # format loop 9
        - name: "Renderuj DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Dokument Microsoft Word" 

        # format loop 10
        - name: "Renderuj TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Zwykły plik tekstowy" 

        # format loop 11
        - name: "Renderuj DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Plik formatu wymiany rysunków"  
          
        # format loop 12
        - name: "Renderuj VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "plik vCard"  
              
        # format loop 13
        - name: "Renderuj SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Skalowalna grafika wektorowa" 
          
        # format loop 14
        - name: "Renderuj HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Plik hipertekstowego języka znaczników" 
          
        # format loop 15
        - name: "Renderuj PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Przenośny plik formatu dokumentu"
          
        # format loop 16
        - name: "Renderuj JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "Obraz JPEG"
          
        # format loop 17
        - name: "Renderuj PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Przenośna grafika sieciowa" 
          
        # format loop 18
        - name: "Renderuj EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "Wiadomość e-mail" 
          
        # format loop 19
        - name: "Renderuj plik RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Plik w formacie tekstu sformatowanego" 
          
        # format loop 20
        - name: "Renderuj ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "Dokument tekstowy OpenDocument" 
          
        # format loop 21
        - name: "Renderuj plik CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Plik wartości oddzielonych przecinkami" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
