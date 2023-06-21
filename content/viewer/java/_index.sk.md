---
############################# Static ############################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

lang: sk
product: "Viewer"
product_tag: "viewer"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "Java Document Viewer API pre PDF Word Excel HTML obrázky a e-maily"
head_description: "Prehliadač dokumentov Java a rozhranie API na vykresľovanie súborov. Pridajte prehliadač PDF, prehliadač Word, prehliadač Excel, prehliadač obrázkov, prehliadač HTML, prehliadač e-mailov v aplikáciách Java."

############################# Header ############################
title: "Java API na vykreslenie a zobrazenie dokumentov"
description: "Knižnica prehliadača dokumentov na vývoj aplikácií Java, ktoré natívne vykresľujú, prezerajú a manipulujú s viacformátovými dokumentmi s podporou 170+ formátov súborov."
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Download Free Trial"
    link: "https://downloads.groupdocs.com/viewer/java"

############################# SubMenu ############################
submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Viewer for Java"
        image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-viewer-java.png"
        product: "GroupDocs.Viewer"
        platform: "Java"

    middle:
        button:
            # button loop
            - link: "#overview"
              text: "Prehľad"

            # button loop
            - link: "#features"
              text: "Vlastnosti"

            # button loop
            - link: "#support"
              text: "podpora"

            # button loop
            - link: "https://products.groupdocs.app/viewer/total"
              text: "Živá ukážka"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/java"
              text: "Stanovenie cien"

    right:
        link_download: "https://releases.groupdocs.com/viewer/java/"
        link_learn: "https://docs.groupdocs.com/viewer/java/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    content: |
      GroupDocs.Viewer for Java kombinuje výkonnú sadu rozhraní API na zobrazovanie dokumentov na zobrazenie obrázkov a formátov dokumentov vo vašich aplikáciách Java bez potreby inštalácie ďalšieho softvéru. Natívne rastruje dokumenty a konvertuje ich do formátu SVG+HTML+CSS, čím zvyšuje kvalitu prezerania dokumentov a zároveň poskytuje výstup s vysokou vernosťou textu. Pomocou rozhrania API na vykresľovanie dokumentov – rýchlo si prezerajte PDF, HTML, XML, Microsoft Office Word, pracovné hárky programu Excel, prezentácie programu PowerPoint, e-maily programu Outlook, diagramy Visio, projekt, metasúbory, obrázky a rôzne ďalšie formáty súborov s ľahkosťou a menším rizikom programovania. Môže tiež zobraziť súbory chránené heslom a po vykreslení umožňuje získať reprezentáciu dokumentu ako HTML, obrázok alebo PDF. Naša knižnica prehliadača súborov je celkom prispôsobiteľná, pretože vám umožňuje zobraziť celý dokument alebo ho čiastočne vykresliť, aby sa proces urýchlil. Prostredníctvom GroupDocs.Viewer for Java API si môžete prezerať stránky, konkrétny rozsah buniek v tabuľkovom procesore alebo dokonca vykresliť jednotlivé vrstvy dokumentu vo formátoch, ako sú PDF a CAD.  

      GroupDocs.Viewer for Java API vám umožňuje vykresľovať dokumenty s/bez anotácií alebo komentárov pre podporované formáty súborov. Umožňuje vám tiež pridávať vlastné adresáre písiem a extrahovať základné informácie o dokumente, ako sú FileType, Extension, Name, PageCount atď.  

      GroupDocs.Viewer for Java je kompatibilný so všetkými verziami Java a podporuje populárne operačné systémy (Windows, Linux, macOS), ktoré sú schopné spúšťať Java runtime.
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          Nasleduje prehľad GroupDocs.Viewer pre Java:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Prehľad"
          content: |
            * Zobraziť viac ako 170 typov dokumentov 
            * Získajte verziu HTML, obrázok, PDF 
            * Otočiť a zmeniť poradie 
            * Použiť vodoznak 
            * Cache pre rýchly proces 
            * Pridať vlastné písma 
            * Použiť kódovacie štandardy 
            * Custom Input Data Handler 
            * Render so sledovaním zmien 
            * Vykreslenie ako responzívne HTML 
            * Renderovanie vrstiev PDF a CAD 
            * Vykreslenie chránených súborov 
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Viewer pre Java podporuje všetky populárne formáty súborov dokumentov vrátane: Microsoft Office, obrázkov, diagramov a mnohých ďalších.

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
            - title: "Iné formáty"
              content: |
                * **Súbory rozloženia stránky:** PDF, TEX, XPS, OXPS
                * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG, OTG, FODP, FODG
                * **Hodnoty oddelené oddeľovačom:** CSV, TSV
                * **Web:** HTML, MHT, MHTML
                * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
                * **PostScript:** PS, EPS
                * **Archívy:** ZIP, TAR, BZ2, GZ, RAR, RAR5
                * **Rôzne:** OBJ, EPUB, MOBI, DjVu, XML, VCF, VCARD, NUMBERS, NSF

        right:
          enable: true
          table:
            # table loop
            - title: "Obrázky, grafika a diagramy"
              content: |
                * **snímky:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB
                * **Ikona systému Windows:** ICO
                * **Škálovateľná vektorová grafika:** SVG, CDR, CMX, IGS, SVGZ
                * **Jpeg2000:** JP2, J2C, J2K, JPC, JPF, JPX, JPM
                * **Adobe Photoshop:** PSD, PSB
                * **Príkazový jazyk tlačiarne:** PCL
                * **Stereo litografia (3D tlač):** STL
                * **Triedy priemyselných základov:** IFC
                * **Lekárske zobrazovanie:** DICOM
                * **Dokumenty plotra:** PLT, HPG
                * **Webové formáty Autodesk Design:** DWF, DWG
                * **Výkres AutoCAD:** DWT, IFC, STL, CF2
                * **DGN založené na ISFF (V7):** DGN

            # table loop
            - title: "Formáty programovacích jazykov"
              content: |
                * **Súbory C/C++/C#:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
                * **Súbory Java/JavaScript:** JAVA, JS, JSON, PROPERTIES
                * **Rôzne:** VB, PHP, SQL, PL, PY, PV, RB, RST, SASS, SCALA, SCM, SCRIPT, AS, AS3, ASM, BAT, CMAKE, CSS, DIFF, ERB, GROOVY, HAML, LESS, LOG, M, MAKE, MD, ML, MM, SH, SML, VIM, YAML

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Viewer pre Java podporuje nasledujúce operačné systémy, rámce a správcov balíkov:
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Operačné systémy"
              content: |
                * Microsoft Windows Server 2003 a novší 
                * Microsoft Windows XP a novší 
                * Microsoft Windows 10 a 11 
                * Linux (Ubuntu, OpenSUSE, CentOS a ďalšie) 
                * Mac OS X 

            # table loop
            - icon: "fas fa-code"
              title: "Podporované rámce"
              content: |
                * J2SE 8.0 (1.8) alebo vyšší (napríklad Java 17) 

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-cogs"
              title: "Vývojové prostredia"
              content: |
                * NetBeans
                * IntelliJ IDEA
                * Eclipse

            # table loop
            - icon: "fas fa-tools"
              title: "Nástroj Build Automation Tool"
              content: |
                * Maven
                * Gradle

############################# Features ############################
features:
    enable: true
    title: "GroupDocs.Viewer pre funkcie Java"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "Prehliadač pre HTML, PDF, obrázky, Word, Excel a ďalšie formáty dokumentov"

      # feature loop
      - icon: "fas fa-eye"
        content: "Renderujte súbory AutoCAD Drawings (DWG) do formátu SVG"

      # feature loop
      - icon: "fas fa-bolt"
        content: "Upravte farbu pozadia konvertovaného súboru"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "Rastrujte a konvertujte dokumenty do SVG, HTML a CSS"

      # feature loop
      - icon: "fas fa-code"
        content: "Získajte HTML, obrázok alebo PDF reprezentáciu dokumentov prostredníctvom vykresľovania"

      # feature loop
      - icon: "fas fa-cloud"
        content: "Verzie dokumentov uložené vo vyrovnávacej pamäti na zrýchlenie času načítania"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "Konfigurácia vlastných adresárov písiem"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "Použite štandardy kódovania na dokumenty Word, Excel a e-mail"

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "Vzdialene vykresľujte dokumenty na FTP alebo cloudovom úložisku"

      # feature loop
      - icon: "fas fa-border-all"
        content: "Odstráňte alebo ponechajte anotácie a komentáre počas vykresľovania"

      # feature loop
      - icon: "fas fa-wrench"
        content: "Vykreslite stránky dokumentu ako samostatné stránky HTML"

      # feature loop
      - icon: "fas fa-columns"
        content: "Vykreslite skryté snímky a strany a použite zmenu poradia strán na vykreslený dokument"

      # feature loop
      - icon: "fas fa-file-word"
        content: "Vykreslenie rozsahu stránok, konkrétnych stránok alebo všetkých stránok do HTML"

      # feature loop
      - icon: "fas fa-envelope"
        content: "Vykreslite alebo skryte komentáre dokumentu"

      # feature loop
      - icon: "fas fa-print"
        content: "Vytvorte responzívny HTML pre niektoré formáty dokumentov pomocou vykresľovania"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "Znížte výslednú veľkosť súboru vykresleného kódu HTML vylúčením písiem"

      # feature loop
      - icon: "fas fa-lock"
        content: "Odstráňte komentáre, nadbytočné biele miesta atď., aby sa minimalizoval výstup HTML a CSS"

      # feature loop
      - icon: "fas fa-file-code"
        content: "Na čítanie obsiahnutého textu použite súradnice zdrojového dokumentu"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "Zobraziť/skryť orámovanie bunky v excelových hárkoch vykresleného výstupu"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "Vykreslenie určitého počtu riadkov každej strany v hárku programu Excel"

      # feature loop
      - icon: "fas fa-heading"
        content: "Vykresliť model a všetky neprázdne rozloženia alebo konkrétne rozloženie súboru CAD"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "Vykreslite položky v dátových súboroch programu Outlook (OST/PST) ako PDF"

      # feature loop
      - icon: "fas fa-cube"
        content: "Vykresľovanie dlaždíc alebo vykresľovanie podľa súradníc dokumentov CAD ako obrázok, HTML alebo PDF"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "Nastavte obmedzenia tlače pri vykresľovaní do PDF"

    more_feature:
      # more_feature_loop
      - title: "Efektívne a spoľahlivé rozhranie API na prezeranie dokumentov"
        content: |
          GroupDocs.Viewer for Java API možno použiť na zobrazenie, vykreslenie a zobrazenie dokumentov vo viac ako 150 rôznych formátoch súborov. Robí sa to spoľahlivo a efektívne pri zachovaní obsahu, ako aj štruktúry dokumentu. Nasledujúci príklad ukazuje úroveň jednoduchosti, s ktorou GroupDocs.Viewer for Java API vykresľuje súbor DOCX ako obrazový súbor pomocou Java:

          ```java
          // Initialize Viewer
          Viewer viewer = new Viewer("invoice.docx");
          // Create view options
          PdfViewOptions viewOptions = new PdfViewOptions();
          // Convert file to PDF and check the output in the current directory
          viewer.view(viewOptions);
          ```
      # more_feature_loop
      - title: "Vykonávajte transformácie pri vykresľovaní dokumentov"
        content: "GroupDocs.Viewer for Java API vám ponúka rôzne možnosti transformácie, ktoré sa majú použiť na vykreslený dokument pre prispôsobenejšie zobrazenie a zobrazenie. Stránky môžete otáčať zadaním uhla. Môžete si poradie vykreslených stránok. Použite špecifický text ako vodoznak na vykreslené stránky alebo obrázky. Prostredníctvom GroupDocs.Viewer for Java API máte tiež možnosť pridať vlastné fonty do vykresľovaného dokumentu."

      # more_feature_loop
      - title: "Práca s e-mailovými prílohami"
        content: "GroupDocs.Viewer for Java API vám umožňuje načítať konkrétne alebo všetky prílohy e-mailu. Po získaní požadovaných e-mailových príloh môžete tieto pripojené súbory vykresliť ako obrázky alebo HTML."

############################# Support ############################
support:
    enable: true

############################# Solutions ##########################
solutions:
    enable: true
    title: "GroupDocs.Viewer ponúka rozhrania API na prezeranie dokumentov pre ďalšie populárne vývojové prostredia"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Viewer for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-viewer-net.png"
          product: "GroupDocs.Viewer"
          platform: ".NET"
          link: "/viewer/net/"

############################# Back to top ##########################
back_to_top:
  enable: true
---