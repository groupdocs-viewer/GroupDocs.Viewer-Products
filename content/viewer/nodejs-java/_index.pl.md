---
############################# Static ############################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: pl
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


############################# Head ############################
head_title: "Interfejs API przeglądarki dokumentów Node.js dla obrazów HTML i wiadomości e-mail w formacie PDF Word Excel"
head_description: "Przeglądarka dokumentów Node.js i interfejs API renderowania plików. Dodaj przeglądarkę plików PDF, przeglądarkę Word, przeglądarkę Excel, przeglądarkę obrazów, przeglądarkę HTML, przeglądarkę e-mail w aplikacjach JavaScript."

############################# Header ############################
title: "API Node.js do renderowania i wyświetlania dokumentów"
description: "Biblioteka Document Viewer do tworzenia aplikacji JavaScript, które natywnie renderują, przeglądają i manipulują wieloformatowymi dokumentami obsługującymi ponad 180 formatów plików."
words:
  for: "for"

actions:
  main: "Bezpłatne pobieranie NPM"
  main_link: "https://www.npmjs.com/package/@groupdocs/groupdocs.viewer"
  alt: "Koncesjonowanie"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/nodejs-java"
  title: "Gotowy żeby zacząć?"
  description: "Wypróbuj bezpłatnie funkcje GroupDocs.Viewer lub poproś o licencję"

release:
  title: "Wydano wersję {0}"
  notes: "Zobacz co nowego"
  downloads: "Pliki do pobrania"
  link: "https://releases.groupdocs.com/viewer/nodejs-java/release-notes/latest/"

code:
  title: "Renderuj pliki PDF w JavaScript"
  more: "Więcej przykładów"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Node.js-via-Java"
  install: "npm i @groupdocs/groupdocs.viewer"
  content: |
    ```javascript {style=abap}   
    //Set output HTML options, one file per page
    const viewOptions = HtmlViewOptions.forEmbeddedResources()

    // Instantiate Viewer
    const viewer = new Viewer("resume.pdf")

    // Render PDF to HTML with embedded resources
    viewer.view(viewOptions)
    viewer.close()
    ```
############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Viewer w skrócie"
  description: "API do renderowania, wyświetlania, konwertowania dokumentów, slajdów, diagramów i wielu innych typów dokumentów w aplikacjach Node.js"
  features:
    # feature loop
    - title: "Przeglądaj dokumenty wydajnie i niezawodnie"
      content: "Dzięki interfejsowi API GroupDocs.Viewer możesz efektywnie renderować dokumenty we wszystkich obsługiwanych formatach do formatów HTML, JPEG, PNG i PDF, korzystając z elastycznych i wydajnych opcji, zachowując jednocześnie integralność zawartości i struktury dokumentu. GroupDocs.Viewer dla Node.js działa na platformach Windows i Linux."

    # feature loop
    - title: "Obsługiwane są najpopularniejsze formaty plików i dokumentów"
      content: "Obsługujemy renderowanie w ponad 180 najpopularniejszych formatach plików i dokumentów, w tym Word, Excel, PDF, PowerPoint, rodzina formatów OpenDocument, archiwa, obrazy rastrowe i wektorowe, e-książki, języki programowania i znaczniki oraz wiele innych typów plików, w tym pliki zaszyfrowane pliki zabezpieczone hasłem."

    # feature loop
    - title: "Konfigurowalne wyjście"
      content: "GroupDocs.Viewer pozwala nie tylko renderować dokument, ale także kontrolować, jak dokładnie, które części dokumentu powinny zostać wyrenderowane lub teraz, w jaki sposób powinny być renderowane, a także zastosować różne transformacje do wyrenderowanego wyniku."

############################# Platforms ############################
platforms:
  enable: true
  title: "Niezależność platformy"
  description: "GroupDocs.Viewer dla Node.js obsługuje następujące systemy operacyjne, struktury i menedżery pakietów"
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
  title: "Obsługiwane formaty plików"
  description: |
    GroupDocs.Viewer dla Node.js za pośrednictwem Java obsługuje operacje na następujących [formatach plików](https://docs.groupdocs.com/viewer/nodejs-java/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office, OpenDocument i formaty tekstowe
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
        ### Obrazy, grafika i diagramy
        * **Obrazy rastrowe:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
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
        ### Inny        
        * **Sieć:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **Archiwa:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **Inny:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "Funkcje GroupDocs.Viewer"
  description: "Bezproblemowo renderuj, wyświetlaj i konwertuj dokumenty PDF i dokumenty pakietu Office"

  items:
    # feature loop
    - icon: "viewhtml"
      title: "Przeglądaj dokumenty w formacie HTML"
      content: "Konwertuj dokument dowolnego typu na dokument HTML za pomocą CSS i SVG, który można wyświetlić w dowolnej nowoczesnej przeglądarce internetowej."

    # feature loop
    - icon: "rasterize"
      title: "Rasteryzacja dokumentów"
      content: "Rasteryzuj dowolny obsługiwany format dokumentu do obrazu rastrowego, z możliwością dostosowania formatu obrazu i jakości kompresji."

    # feature loop
    - icon: "sourcecode"
      title: "Renderuj i podświetlaj kody programowania"
      content: "Obsługa wszystkich popularnych języków programowania, skryptów i znaczników, z możliwością analizowania i wyróżniania ich składni."

    # feature loop
    - icon: "convertpdf"
      title: "Konwertuj do formatu PDF"
      content: "Dokument w dowolnym obsługiwanym formacie można łatwo przekonwertować i zapisać w formacie PDF za pomocą regulowanych opcji."

    # feature loop
    - icon: "transform"
      title: "Zastosuj przekształcenia"
      content: "Dokument wyjściowy można przekształcać podczas renderowania – strony można obracać i/lub zmieniać układ, a na nich można umieszczać tekstowy znak wodny."

    # feature loop
    - icon: "adjustment"
      title: "Regulacja wyjścia HTML"
      content: "Wyjściowe dokumenty HTML, generowane przez GroupDocs.Viewer, można bardzo precyzyjnie dostroić: można zapisywać w strumieniu lub pliku, z zasobami zewnętrznymi lub osadzonymi, wywołaniami zwrotnymi i tak dalej."

    # feature loop
    - icon: "complex"
      title: "Obsługa złożonych struktur dokumentów"
      content: "GroupDocs.Viewer obsługuje nie tylko pojedyncze dokumenty, ale także pliki, które wewnętrznie zawierają listę lub hierarchiczną strukturę dokumentów, takie jak wiadomości e-mail z załącznikami, archiwa ZIP z plikami wewnętrznymi w folderach, wielostronicowe obrazy TIFF i tak dalej."

    # feature loop
    - icon: "optimization"
      title: "Opcje optymalizacji"
      content: "GroupDocs.Viewer zawiera regulowany podsystem pamięci podręcznej, który może skrócić czas ładowania, korzystając z wersji dokumentów przechowywanych w pamięci podręcznej. Również zestaw różnych opcji dla różnych formatów pozwala wykluczyć z renderowania niektóre niepotrzebne części lub aspekty dokumentów (czcionki, ukryte arkusze, załączniki do wiadomości e-mail) w celu optymalizacji ogólnej wydajności"

    # feature loop
    - icon: "passwordprotected"
      title: "Obsługa dokumentów chronionych hasłem"
      content: "GroupDocs.Viewer umożliwia otwieranie zaszyfrowanych dokumentów różnych typów: PDF, WordProcessing, Arkusz kalkulacyjny, Prezentacja i inne, po podaniu hasła w opcjach ładowania."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Próbki kodu"
  description: "Niektóre przypadki użycia typowego GroupDocs.Viewer dla Node.js za pomocą operacji Java"
  items:
    # code sample loop
    - title: "Renderuj DOCX do HTML"
      content: |
        Właściwości klasy `HtmlViewOptions` pozwalają kontrolować proces konwersji, więcej na ten temat [tutaj](https://docs.groupdocs.com/viewer/nodejs-java/rendering-to-html/). Na przykład możesz osadzić wszystkie zasoby zewnętrzne w wyjściowym pliku HTML, zminimalizować plik wyjściowy i zoptymalizować go pod kątem drukowania.
        {{< landing/code title="JavaScript">}}
        ```javascript {style=abap}
        import { Viewer, HtmlViewOptions } from '@groupdocs/groupdocs.viewer'

        //Set output HTML options, one file per page
        const viewOptions = HtmlViewOptions.forEmbeddedResources()

        // Instantiate Viewer
        const viewer = new Viewer("resume.docx")

        // Render PDF to HTML with embedded resources
        viewer.view(viewOptions)
        viewer.close()
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Eksportuj PPTX do formatu PDF"
      content: |
        Utwórz instancję klasy `PdfViewOptions` i przekaż ją do metody `Viewer.view`, aby przekonwertować plik PowerPoint PPTX na format PDF. Właściwości klasy `PdfViewOptions` pozwalają kontrolować proces konwersji. Można na przykład chronić wyjściowy plik PDF, zmieniać kolejność jego stron i określać jakość obrazów dokumentów. Aby uzyskać szczegółowe informacje, zobacz [poniższą sekcję dokumentacji](https://docs.groupdocs.com/viewer/nodejs-java/rendering-to-pdf/).
        {{< landing/code title="JavaScript">}}
        ```javascript {style=abap}   
        import { Viewer, PdfViewOptions } from '@groupdocs/groupdocs.viewer'

        //Set output PDF options
        const viewOptions = new PdfViewOptions("presentation.pdf")

        // Instantiate Viewer
        const viewer = new Viewer("presentation.pptx")

        // Render PDF to HTML with embedded resources
        viewer.view(viewOptions)
        viewer.close()
        ```
        {{< /landing/code >}}
############################# Reviews ############################
# reviews:
# enable: true
# title: "Recenzje produktów GroupDocs"
# description: "Nie wierz nam tylko na słowo. Zobacz, co inni programiści mówią o naszych API"

# items:
#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "Doskonała obsługa i doskonałe produkty. Byli niezwykle pomocni i szybko reagowali podczas procesu wdrażania GroupDocs.Viewer for .NET, nie mogę ich wystarczająco polecić."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "Po zaimplementowaniu i użyciu GroupDocs.Viewer for .NET w projekcie wygląda na to, że działa bardzo dobrze. Testowałem z wieloma dokumentami i jak dotąd wszystko jest w porządku. Wszystko, co na niego rzuciłem, renderuje się ładnie i wygląda tak samo dobrze, jak w przeglądarce plików PDF lub MS Word."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---
