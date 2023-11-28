---
############################# Static ############################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: hr
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
head_title: "Node.js Document Viewer API za PDF Word Excel HTML slike i e-poštu"
head_description: "Node.js preglednik dokumenata i API za renderiranje datoteka. Dodajte PDF preglednik, Word preglednik, Excel preglednik, preglednik slika, HTML preglednik, preglednik e-pošte u JavaScript aplikacijama."

############################# Header ############################
title: "Node.js API za renderiranje i prikaz dokumenata"
description: "Biblioteka preglednika dokumenata za razvoj JavaScript aplikacija koje nativno prikazuju, pregledavaju i manipuliraju dokumentima u više formata koji podržavaju više od 180 formata datoteka."
words:
  for: "for"

actions:
  main: "Besplatno preuzimanje NPM-a"
  main_link: "https://www.npmjs.com/package/@groupdocs/groupdocs.viewer"
  alt: "Licenciranje"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/nodejs-java"
  title: "Jeste li spremni za početak?"
  description: "Isprobajte značajke GroupDocs.Viewer besplatno ili zatražite licencu"

release:
  title: "Verzija {0} izdana"
  notes: "Pogledajte što je novo"
  downloads: "Preuzimanja"
  link: "https://releases.groupdocs.com/viewer/nodejs-java/release-notes/latest/"

code:
  title: "Prikaz PDF datoteka u JavaScriptu"
  more: "Više primjera"
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
  title: "GroupDocs.Viewer na prvi pogled"
  description: "API za renderiranje, prikaz, pretvaranje dokumenata, slajdova, dijagrama i mnogih drugih vrsta dokumenata u Node.js aplikacijama"
  features:
    # feature loop
    - title: "Pregledajte dokumente učinkovito i pouzdano"
      content: "S API-jem GroupDocs.Viewer možete učinkovito renderirati dokumente bilo kojeg podržanog formata u HTML, JPEG, PNG i PDF s fleksibilnim i moćnim opcijama uz održavanje integriteta sadržaja i strukture dokumenta. GroupDocs.Viewer za Node.js radi na Windows i Linux platformama."

    # feature loop
    - title: "Podržani su najpopularniji formati datoteka i dokumenata"
      content: "Podržavamo iscrtavanje preko 180 najpopularnijih formata datoteka i dokumenata koji uključuju Word, Excel, PDF, PowerPoint, obitelj OpenDocument formata, arhive, rasterske i vektorske slike, e-knjige, programske jezike i oznake te mnoge druge vrste datoteka, uključujući šifrirane datoteke sa zaštitom lozinkom."

    # feature loop
    - title: "Prilagodljiv izlaz"
      content: "GroupDocs.Viewer omogućuje ne samo renderiranje dokumenta, već i kontrolu kako točno, koji dijelovi dokumenta trebaju biti renderirani ili sada, kako bi se trebali renderirati, te primjenu različitih transformacija na renderirani izlaz."

############################# Platforms ############################
platforms:
  enable: true
  title: "Neovisnost o platformi"
  description: "GroupDocs.Viewer za Node.js podržava sljedeće operativne sustave, okvire i upravitelje paketa"
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
  title: "Podržani formati datoteka"
  description: |
    GroupDocs.Viewer za Node.js putem Jave podržava operacije sa sljedećim [formatima datoteka](https://docs.groupdocs.com/viewer/nodejs-java/supported-document-formats/).
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
  description: "Neki slučajevi upotrebe tipičnog GroupDocs.Viewera za Node.js putem Java operacija"
  items:
    # code sample loop
    - title: "Renderirajte DOCX u HTML"
      content: |
        Svojstva klase `HtmlViewOptions` omogućuju vam kontrolu procesa konverzije, više o tome [ovdje](https://docs.groupdocs.com/viewer/nodejs-java/rendering-to-html/). Na primjer, možete ugraditi sve vanjske resurse u izlaznu HTML datoteku, minimizirati izlaznu datoteku i optimizirati je za ispis.
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
    - title: "Izvezi PPTX u PDF"
      content: |
        Stvorite instancu klase `PdfViewOptions` i proslijedite je metodi `Viewer.view` da pretvorite PowerPoint PPTX datoteku u PDF. Svojstva klase `PdfViewOptions` omogućuju vam kontrolu procesa pretvorbe. Na primjer, možete zaštititi izlaznu PDF datoteku, promijeniti redoslijed njezinih stranica i odrediti kvalitetu slika dokumenta. Pojedinosti potražite u [odjeljku sljedeće dokumentacije](https://docs.groupdocs.com/viewer/nodejs-java/rendering-to-pdf/).
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
