---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: pl

############################# Head #############################
head_title: ".NET HH Viewer API — odczyt, przeglądanie, renderowanie w C# VB.NET"
head_description: "Interfejs API przeglądarki dokumentów .NET do odczytu, renderowania i wyświetlania HH w aplikacjach dowolnego typu C#, ASP.NET, VB.NET i .NET Core."

############################# Header ############################
title: "HH Przeglądarka plików dla aplikacji C# .NET" 
description: "Interfejs API przeglądarki dokumentów .NET do odczytu, renderowania i wyświetlania pliku HH w aplikacjach dowolnego typu C#, ASP.NET, VB.NET i .NET Core. Wyświetl renderowane pliki z prawdziwym formatowaniem i układem w formacie HTML5, PDF lub jako obraz przy użyciu kilku wierszy kodu." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Pobierz darmową wersję próbną"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Informacje o GroupDocs.Viewer dla interfejsu API platformy .NET" 
    content: |
        Zacznij przeglądać ponad 190 popularnych formatów dokumentów w swoich aplikacjach .NET, używając GroupDocs.Viewer for .NET API, dodając kilka wierszy kodu. Programiści mogą z łatwością wyświetlać pliki PDF, edytory tekstu, arkusze kalkulacyjne Excel, prezentacje, Visio, Project, Outlook i wiele innych popularnych formatów dokumentów w trybach HTML5, obrazu lub PDF. Renderowanie dokumentu jest szybkie, identyczne z oryginalnym plikiem źródłowym i nie wymaga instalowania dodatkowego oprogramowania ani innych zewnętrznych bibliotek.

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
    title_left: "Kroki renderowania pliku HH w C#" 
    content_left: |
        Dzięki [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/) możesz w kilku krokach wyrenderować HH do formatu HTML, JPEG, PNG lub PDF.

        * Zainstaluj [GroupDocs.Viewer for .NET](https://www.nuget.org/packages/groupdocs.viewer) za pomocą swojego ulubionego menedżera pakietów. 
        * Utwórz instancję klasy Viewer i załaduj plik HH z pełną ścieżką. 
        * Ustaw opcje renderowania pliku HH do formatu HTML, PNG, JPEG lub PDF. 
        * Renderuj plik i sprawdź dane wyjściowe w bieżącym katalogu. 
        
    title_right: "wymagania systemowe" 
    content_right: |
        Interfejsy API GroupDocs.Viewer for .NET są obsługiwane na wszystkich głównych platformach i systemach operacyjnych. Przed wykonaniem poniższego kodu upewnij się, że w systemie są zainstalowane następujące wymagania wstępne.

        * Systemy operacyjne: Microsoft Windows, Linux, MacOS 
        * Środowiska programistyczne: Microsoft Visual Studio, Visual Studio Code, .NET CLI 
        * Frameworki: .NET Framework, .NET Standard, .NET Core, .NET 
    code: |
        ```cs
                        
            // Set up input HH file
            string filePath = "input.hh";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render HH file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "HH Przeglądarka Demo na żywo"
    content: |
        Wyświetl teraz plik HH, odwiedzając witrynę [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/hh).
    lang: "pl"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Inne formaty plików Renderowanie i wyświetlanie przy użyciu C#"
    exclude: "HH"
    content: |
        Interfejs API przeglądarki wielu formatów dokumentów i obrazów dla platformy .NET. Zobacz niektóre z popularnych formatów plików poniżej bez zewnętrznych przeglądarek.
    format: 
        # format loop 1
        - name: "Renderuj DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word Otwarty dokument XML" 

        # format loop 2
        - name: "Renderuj CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "Plik CorelDRAW" 

        # format loop 3
        - name: "Renderuj PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "Prezentacja PowerPoint Open XML" 

        # format loop 4
        - name: "Renderuj XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Arkusz kalkulacyjny Microsoft Excel Open XML" 

        # format loop 5
        - name: "Renderuj DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "Rysunek AutoCAD"

        # format loop 6
        - name: "Renderuj XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "Plik XML"

        # format loop 7
        - name: "Renderuj PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Dokument Adobe Photoshop"

        # format loop 8
        - name: "Renderuj plik Adobe Illustrator"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Grafika Adobe Illustrator"

        # format loop 9
        - name: "Renderuj DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Dokument Microsoft Word" 

        # format loop 10
        - name: "Renderuj TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Zwykły plik tekstowy" 

        # format loop 11
        - name: "Renderuj DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Plik formatu wymiany rysunków"  
          
        # format loop 12
        - name: "Renderuj VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "plik vCard"  
              
        # format loop 13
        - name: "Renderuj SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Skalowalna grafika wektorowa" 
          
        # format loop 14
        - name: "Renderuj HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Plik hipertekstowego języka znaczników" 
          
        # format loop 15
        - name: "Renderuj PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Przenośny plik formatu dokumentu"
          
        # format loop 16
        - name: "Renderuj JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "Obraz JPEG"
          
        # format loop 17
        - name: "Renderuj PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Przenośna grafika sieciowa" 
          
        # format loop 18
        - name: "Renderuj EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "Wiadomość e-mail" 
          
        # format loop 19
        - name: "Renderuj plik RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Plik w formacie tekstu sformatowanego" 
          
        # format loop 20
        - name: "Renderuj ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "Dokument tekstowy OpenDocument" 
          
        # format loop 21
        - name: "Renderuj plik CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Plik wartości oddzielonych przecinkami" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
