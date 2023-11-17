---
############################# Static ############################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

product: "Viewer"
product_tag: "viewer"
platform: "Java"
platform_tag: "java"

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
head_title: "Interfejs API przeglądarki dokumentów Java, renderowanie diagramu HTML obrazu PDF Word Excel"
head_description: "Biblioteka Document Viewer do tworzenia aplikacji Java, które natywnie renderują, przeglądają i manipulują wieloformatowymi dokumentami obsługującymi ponad 180 formatów plików."

############################# Header ############################
title: "Renderuj i wyświetlaj dokumenty<br>przy użyciu interfejsu Java API"
description: "Potężny interfejs API przeglądarki umożliwiający renderowanie ponad 180 formatów dokumentów do formatu PDF, HTML i obrazu z wszechstronnymi opcjami konfiguracji."
words:
  for: "for"

actions:
  main: "Bezpłatne pobieranie Mavena"
  main_link: "https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-viewer/"
  alt: "Koncesjonowanie"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/java"
  title: "Gotowy żeby zacząć?"
  description: "Wypróbuj bezpłatnie funkcje GroupDocs.Viewer lub poproś o licencję"

release:
  title: "Wydano wersję {0}"
  notes: "Zobacz co nowego"
  downloads: "Pliki do pobrania"
  link: "https://releases.groupdocs.com/viewer/java/release-notes/latest/"

code:
  title: "Renderuj pliki PDF w Javie"
  more: "Więcej przykładów"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Java"
  install: |
    <dependencies>
      <dependency>
        <groupId>com.groupdocs</groupId>
        <artifactId>groupdocs-viewer</artifactId>
        <version>{0}</version>
      </dependency>
    </dependencies>

    <repositories>
      <repository>
        <id>repository.groupdocs.com</id>
        <name>GroupDocs Repository</name>
        <url>https://repository.groupdocs.com/repo/</url>
      </repository>
    </repositories>
  content: |
    ```java {style=abap}
    // Instantiate Viewer
    try (Viewer viewer = new Viewer("resume.pdf"))
    {
        // Set output HTML options, one file per page
        HtmlViewOptions viewOptions = 
            HtmlViewOptions.forEmbeddedResources();

        // Render PDF to HTML with embedded resources
        viewer.view(viewOptions);
    }
    ```
############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Viewer w skrócie"
  description: "API do renderowania, wyświetlania, konwertowania dokumentów, slajdów, diagramów i wielu innych typów dokumentów w aplikacjach Java"
  features:
    # feature loop
    - title: "Przeglądaj dokumenty wydajnie i niezawodnie"
      content: "Dzięki interfejsowi API GroupDocs.Viewer możesz efektywnie renderować dokumenty we wszystkich obsługiwanych formatach do formatów HTML, JPEG, PNG i PDF, korzystając z elastycznych i wydajnych opcji, zachowując jednocześnie integralność zawartości i struktury dokumentu. GroupDocs.Viewer działa na platformach Windows i Linux."

    # feature loop
    - title: "Obsługiwane są najpopularniejsze formaty plików i dokumentów"
      content: "Obsługujemy renderowanie w ponad 180 najpopularniejszych formatach plików i dokumentów, w tym Word, Excel, PDF, PowerPoint, rodzina formatów OpenDocument, archiwa, obrazy rastrowe i wektorowe, e-książki, języki programowania i znaczniki oraz wiele innych typów plików, w tym pliki zaszyfrowane pliki zabezpieczone hasłem."

    # feature loop
    - title: "Konfigurowalne wyjście"
      content: "GroupDocs.Viewer pozwala nie tylko renderować dokument, ale także kontrolować, jak dokładnie, które części dokumentu powinny zostać wyrenderowane lub teraz, w jaki sposób powinny być renderowane, a także zastosować różne transformacje do wyrenderowanego wyniku."

    # feature loop
    - title: "Interfejs sieciowy dla frameworka Spring"
      content: "Zapewniamy pakiet interfejsu użytkownika typu open source dla platformy Spring, który można dodać do swojego projektu w ciągu kilku minut. Pakiet Viewer.UI zawiera internetowy interfejs użytkownika oparty na Angularze i dostarcza zestaw przydatnych interfejsów API i dostawców przechowywania danych."

############################# Platforms ############################
platforms:
  enable: true
  title: "Niezależność platformy"
  description: "GroupDocs.Viewer for Java obsługuje następujące systemy operacyjne, struktury i menedżery pakietów"
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
    - title: "Maven"
      image: "maven"


############################# File formats ############################
formats:
  enable: true
  title: "Obsługiwane formaty plików"
  description: |
    GroupDocs.Viewer for Java obsługuje operacje na następujących [formatach plików](https://docs.groupdocs.com/viewer/java/supported-document-formats/).
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
  description: "Niektóre przypadki użycia typowych operacji GroupDocs.Viewer dla operacji Java"
  items:
    # code sample loop
    - title: "Renderuj DOCX do HTML"
      content: |
        Właściwości klasy [HtmlViewOptions](https://reference.groupdocs.com/viewer/java/com.groupdocs.viewer.options/htmlviewoptions/) pozwalają kontrolować proces konwersji, więcej na ten temat [tutaj](https:/ /docs.groupdocs.com/viewer/Java/rendering-to-html/). Na przykład możesz osadzić wszystkie zasoby zewnętrzne w wyjściowym pliku HTML, zminimalizować plik wyjściowy i zoptymalizować go pod kątem drukowania.
        {{< landing/code title="Java">}}
        ```java {style=abap}
        import com.groupdocs.viewer.Viewer;
        import com.groupdocs.viewer.options.HtmlViewOptions;

        // Instantiate Viewer
        try (Viewer viewer = new Viewer("resume.docx"))
        {
            // Set output HTML options
            HtmlViewOptions options = 
                HtmlViewOptions.forEmbeddedResources();

            // Render DOCX to HTML with embedded resources
            viewer.view(options);
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Eksportuj PPTX do formatu PDF"
      content: |
        Utwórz instancję klasy [PdfViewOptions](https://reference.groupdocs.com/viewer/java/com.groupdocs.viewer.options/pdfviewoptions/) i przekaż ją do [Viewer.View](https://reference. groupdocs.com/viewer/java/com.groupdocs.viewer/viewer/#view-com.groupdocs.viewer.options.ViewOptions-) metoda konwersji pliku PowerPoint PPTX na format PDF. Właściwości klasy PdfViewOptions pozwalają kontrolować proces konwersji. Można na przykład chronić wyjściowy plik PDF, zmieniać kolejność jego stron i określać jakość obrazów dokumentów. Aby uzyskać szczegółowe informacje, zobacz [poniższą sekcję dokumentacji](https://docs.groupdocs.com/viewer/java/rendering-to-pdf/).
        {{< landing/code title="Java">}}
        ```java {style=abap}   
        import com.groupdocs.viewer.Viewer;
        import com.groupdocs.viewer.options.PdfViewOptions;

        // Instantiate Viewer
        try (Viewer viewer = new Viewer("presentation.pptx"))
        {
            // Set output PDF options
            PdfViewOptions viewOptions = new PdfViewOptions();

            // Export PPTX to PDF
            viewer.view(viewOptions);
        }
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