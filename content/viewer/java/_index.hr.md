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
head_title: "Java Document Viewer API, render PDF Word Excel Slika HTML dijagram"
head_description: "Biblioteka preglednika dokumenata za razvoj Java aplikacija koje nativno prikazuju, pregledavaju i manipuliraju dokumentima u više formata koji podržavaju više od 180 formata datoteka."

############################# Header ############################
title: "Renderirajte i prikažite dokumente<br>pomoću Java API-ja"
description: "Snažni API preglednika za prikaz više od 180 formata dokumenata u PDF, HTML i slike sa raznovrsnim opcijama konfiguracije."
words:
  for: "for"

actions:
  main: "Besplatno preuzimanje Mavena"
  main_link: "https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-viewer/"
  alt: "Licenciranje"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/java"
  title: "Jeste li spremni za početak?"
  description: "Isprobajte značajke GroupDocs.Viewer besplatno ili zatražite licencu"

release:
  title: "Verzija {0} izdana"
  notes: "Pogledajte što je novo"
  downloads: "Preuzimanja"
  link: "https://releases.groupdocs.com/viewer/java/release-notes/latest/"

code:
  title: "Prikaz PDF datoteka u Javi"
  more: "Više primjera"
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
  title: "GroupDocs.Viewer na prvi pogled"
  description: "API za renderiranje, prikaz, pretvaranje dokumenata, slajdova, dijagrama i mnogih drugih vrsta dokumenata u Java aplikacijama"
  features:
    # feature loop
    - title: "Pregledajte dokumente učinkovito i pouzdano"
      content: "S API-jem GroupDocs.Viewer možete učinkovito renderirati dokumente bilo kojeg podržanog formata u HTML, JPEG, PNG i PDF s fleksibilnim i moćnim opcijama uz održavanje integriteta sadržaja i strukture dokumenta. GroupDocs.Viewer radi na Windows i Linux platformama."

    # feature loop
    - title: "Podržani su najpopularniji formati datoteka i dokumenata"
      content: "Podržavamo iscrtavanje preko 180 najpopularnijih formata datoteka i dokumenata koji uključuju Word, Excel, PDF, PowerPoint, obitelj OpenDocument formata, arhive, rasterske i vektorske slike, e-knjige, programske jezike i oznake te mnoge druge vrste datoteka, uključujući šifrirane datoteke sa zaštitom lozinkom."

    # feature loop
    - title: "Prilagodljiv izlaz"
      content: "GroupDocs.Viewer omogućuje ne samo renderiranje dokumenta, već i kontrolu kako točno, koji dijelovi dokumenta trebaju biti renderirani ili sada, kako bi se trebali renderirati, te primjenu različitih transformacija na renderirani izlaz."

    # feature loop
    - title: "Web sučelje za Spring framework"
      content: "Nudimo UI paket otvorenog koda za Spring okvir koji se može dodati vašem projektu u nekoliko minuta. Paket Viewer.UI sadrži web-UI temeljen na Angularu i donosi skup korisnih API-ja i pružatelja usluga pohrane podataka."

############################# Platforms ############################
platforms:
  enable: true
  title: "Neovisnost o platformi"
  description: "GroupDocs.Viewer za Javu podržava sljedeće operativne sustave, okvire i upravitelje paketa"
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
  title: "Podržani formati datoteka"
  description: |
    GroupDocs.Viewer za Javu podržava rad sa sljedećim [formatima datoteka](https://docs.groupdocs.com/viewer/java/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office, OpenDocument i tekstualni formati
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
        ### Slike, grafike i dijagrami
        * **Rasterske slike:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
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
        ### ostalo        
        * **mreža:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **Arhiva:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **ostalo:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "Značajke GroupDocs.Viewer"
  description: "Besprijekorno renderirajte, prikazujte i pretvarajte PDF i Office dokumente"

  items:
    # feature loop
    - icon: "viewhtml"
      title: "Pregledajte dokumente u HTML-u"
      content: "Pretvorite dokument bilo koje vrste u HTML dokument s CSS-om i SVG-om, koji se može prikazati u bilo kojem modernom web-pregledniku."

    # feature loop
    - icon: "rasterize"
      title: "Rasterizirajte dokumente"
      content: "Rasterizirajte bilo koji podržani format dokumenta u rastersku sliku, s podesivim formatom slike i kvalitetom kompresije."

    # feature loop
    - icon: "sourcecode"
      title: "Prikaz i označavanje programskih kodova"
      content: "Podrška za sve popularne programerske, skriptne i označne jezike, s mogućnošću analiziranja i isticanja njihove sintakse."

    # feature loop
    - icon: "convertpdf"
      title: "Pretvori u PDF"
      content: "Dokument bilo kojeg podržanog formata može se jednostavno pretvoriti i spremiti u PDF s podesivim opcijama."

    # feature loop
    - icon: "transform"
      title: "Primijeni transformacije"
      content: "Izlazni dokument može se transformirati tijekom renderiranja - stranice se mogu rotirati i/ili preuređivati, a tekstualni vodeni žig može se postaviti na njih."

    # feature loop
    - icon: "adjustment"
      title: "Podešavanje HTML izlaza"
      content: "Izlazni HTML dokumenti, koje generira GroupDocs.Viewer, mogu se vrlo fino podesiti: dopušteno je spremanje u tok ili datoteku, s vanjskim ili ugrađenim resursima, povratnim pozivima i tako dalje."

    # feature loop
    - icon: "complex"
      title: "Podrška za složene strukture dokumenata"
      content: "GroupDocs.Viewer podržava ne samo pojedinačne dokumente, već i datoteke koje interno sadrže popis ili hijerarhijsku strukturu dokumenata, kao što su poruke e-pošte s privicima, ZIP arhive s internim datotekama unutar mapa, TIFF slike s više stranica i tako dalje."

    # feature loop
    - icon: "optimization"
      title: "Mogućnosti optimizacije"
      content: "GroupDocs.Viewer sadrži prilagodljivi podsustav predmemorije koji može ubrzati vrijeme učitavanja korištenjem predmemoriranih verzija dokumenata. Također skup različitih opcija za različite formate omogućuje isključivanje nekih nepotrebnih dijelova ili aspekata dokumenata iz renderiranja (fontovi, skriveni radni listovi, privici e-pošte) kako bi se optimizirala ukupna izvedba"

    # feature loop
    - icon: "passwordprotected"
      title: "Podrška za dokumente zaštićene lozinkom"
      content: "GroupDocs.Viewer omogućuje otvaranje šifriranih dokumenata različitih vrsta: PDF, WordProcessing, Spreadsheet, Presentation i drugi, određivanjem lozinke u opcijama učitavanja."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Uzorci kodova"
  description: "Neki slučajevi upotrebe tipičnih GroupDocs.Viewer za Java operacije"
  items:
    # code sample loop
    - title: "Renderirajte DOCX u HTML"
      content: |
        Svojstva klase [HtmlViewOptions](https://reference.groupdocs.com/viewer/java/com.groupdocs.viewer.options/htmlviewoptions/) omogućuju vam kontrolu procesa konverzije, više o tome [ovdje](https:/ /docs.groupdocs.com/viewer/java/rendering-to-html/). Na primjer, možete ugraditi sve vanjske resurse u izlaznu HTML datoteku, minimizirati izlaznu datoteku i optimizirati je za ispis.
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
    - title: "Izvezi PPTX u PDF"
      content: |
        Stvorite instancu klase [PdfViewOptions](https://reference.groupdocs.com/viewer/java/com.groupdocs.viewer.options/pdfviewoptions/) i proslijedite je u [Viewer.View](https://reference. groupdocs.com/viewer/java/com.groupdocs.viewer/viewer/#view-com.groupdocs.viewer.options.ViewOptions-) metoda za pretvaranje PowerPoint PPTX datoteke u PDF. Svojstva klase PdfViewOptions omogućuju kontrolu procesa konverzije. Na primjer, možete zaštititi izlaznu PDF datoteku, promijeniti redoslijed njezinih stranica i odrediti kvalitetu slika dokumenta. Pojedinosti potražite u [odjeljku sljedeće dokumentacije](https://docs.groupdocs.com/viewer/java/rendering-to-pdf/).
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
# title: "GroupDocs recenzije proizvoda"
# description: "Nemojte nam samo vjerovati na riječ. Pogledajte što drugi programeri kažu o našim API-jima"

# items:
#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "Izvrsna usluga i izvrsni proizvodi. Bili su izuzetno korisni i osjetljivi tijekom procesa implementacije GroupDocs.Viewera za .NET, ne mogu ih dovoljno preporučiti."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "Nakon implementacije i korištenja GroupDocs.Viewer za .NET u projektu, čini se da radi vrlo dobro. Testirao sam s mnogo dokumenata i za sada je dobro. Sve što sam bacio na njega lijepo se prikazuje i izgleda jednako dobro kao što bi izgledalo u PDF pregledniku ili MS Wordu."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---