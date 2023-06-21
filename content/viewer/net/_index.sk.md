---
############################# Static ##########################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

lang: sk
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: ".NET Document Viewer API, vykresľovanie PDF Word Excel obrázku HTML diagramu"
head_description: "C# ASP.NET prehliadač súborov a vykresľovacie API. Pridajte funkcie prehliadača PDF, prehliadača Word, prehliadača Excelu, prehliadača obrázkov, prehliadača HTML a prehliadača e-mailov do aplikácií .NET."

############################# Header ##########################
title: "Render & Display Documents cez .NET API"
description: ".NET Document Viewer API na vykresľovanie 190+ formátov dokumentov do PDF, HTML a obrázkov s výkonnými možnosťami konfigurácie."
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
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Stanovenie cien"

    right:
        link_download: "https://releases.groupdocs.com/viewer/net/"
        link_learn: "https://docs.groupdocs.com/viewer/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    content: |
      GroupDocs.Viewer for .NET API vám pomôže vytvárať výkonné aplikácie v C#, ASP.NET a ďalších technológiách založených na .NET, ktoré dokážu vykresľovať a zobrazovať dokumenty a obrázky vo viac ako 190 formátoch súborov bez inštalácie akéhokoľvek externého softvéru. Knižnica prehliadača súborov rastruje dokumenty a potom ich konvertuje na SVG+HTML+CSS, aby sa optimalizoval celkový zážitok z vykresľovania dokumentov na prezeranie obchodných dokumentov, obrázkov, textových súborov, diagramov, grafiky, e-mailových príloh a súborov PDF s rýchlosťou, skutočným textom a vysoká vernosť vo vašich aplikáciách. Vo svojich aplikáciách máte možnosť pridať funkcie na prezeranie a čítanie dokumentov na zobrazenie celého dokumentu, čiastočného dokumentu, konkrétneho rozsahu strán/buniek, jednotlivých vrstiev dokumentu, s alebo bez anotácií a komentárov pre podporované formáty súborov.
       
      GroupDocs.Viewer for .NET štandardne ukladá výstup vykreslených dokumentov na lokálny disk. Akýkoľvek typ externého vyrovnávacieho úložiska je podporovaný aj implementáciou vhodných rozhraní – Amazon S3, Dropbox, Google Drive, Windows Azure, Redis alebo akékoľvek iné.
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          Nasleduje prehľad GroupDocs.Viewer pre .NET:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Prehľad"
          content: |
            * Zobraziť viac ako 190 typov dokumentov 
            * Získajte súbor vo formáte HTML, Obrázok, PDF 
            * Otočiť a zmeniť poradie 
            * Použiť vodoznak 
            * Cache pre rýchly proces 
            * Pridať vlastné písma 
            * Použiť kódovacie štandardy 
            * Custom Input Data Handler 
            * Render so sledovaním zmien 
            * Vykreslenie ako responzívne HTML 
            * Renderovanie vrstiev PDF a CAD 
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Viewer for .NET podporuje prezeranie všetkých populárnych formátov súborov dokumentov. Pomocou niekoľkých riadkov kódu pridajte do svojich aplikácií .NET prehliadač PDF, Microsoft Office Word, tabuľku Excel, obrázok, HTML, Outlook e-mail, OneNote, Project a možnosti prezerania grafiky.

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
          GroupDocs.Viewer pre .NET podporuje nasledujúce operačné systémy, rámce a správcov balíkov:
        
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
                * .NET Framework 2.0 alebo vyšší 
                * .NET Core 3.1 
                * .NET 5 alebo vyšší 

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-box"
              title: "Správca balíkov"
              content: |
                * NuGet

            # table loop
            - icon: "fas fa-tools"
              title: "Vývojové prostredia"
              content: |
                * Microsoft Visual Studio
                * Visual Studio Code
                * .NET CLI

############################# Features ############################
features:
    enable: true
    title: "GroupDocs.Viewer pre funkcie .NET"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "Rasterizujte dokumenty a konvertujte ich na SVG, HTML a CSS"

      # feature loop
      - icon: "fas fa-eye"
        content: "Preveďte text do HTML a vykreslite dokumenty, aby ste získali reprezentáciu HTML, obrázok alebo PDF"

      # feature loop
      - icon: "fas fa-bolt"
        content: "Rýchlejšie načítanie pomocou verzií dokumentov uložených vo vyrovnávacej pamäti"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "Konvertujte prezentácie s tvarmi a textom s 3D efektmi"

      # feature loop
      - icon: "fas fa-code"
        content: "Kódujte dokumenty Word, Excel a e-mail do požadovaného štandardu kódovania"

      # feature loop
      - icon: "fas fa-cloud"
        content: "Renderujte dokumenty umiestnené na FTP alebo cloudových úložiskách"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "Vylúčenie písiem pri vykresľovaní do HTML na zníženie výslednej veľkosti súboru"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "Minimalizujte výstup CSS a HTML odstránením komentárov, nadbytočných bielych miest atď."

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "Prečítajte si text obsiahnutý v zdrojovom dokumente prostredníctvom jeho súradníc"

      # feature loop
      - icon: "fas fa-border-all"
        content: "Zobraziť/skryť čiary mriežky hárkov programu Excel vo výstupnom zobrazení"

      # feature loop
      - icon: "fas fa-wrench"
        content: "Zadajte počet riadkov v hárku programu Excel, ktoré sa majú vykresliť na každej strane"

      # feature loop
      - icon: "fas fa-columns"
        content: "Pri vykresľovaní tabuľkových dokumentov ignorujte prázdne stĺpce"

      # feature loop
      - icon: "fas fa-file-word"
        content: "Renderujte dokumenty programu Word do stránok HTML, obrázkov alebo PDF so sledovaním zmien"

      # feature loop
      - icon: "fas fa-envelope"
        content: "Renderujte e-mailové prílohy ako pôvodné súbory, obrázky alebo vo forme HTML"

      # feature loop
      - icon: "fas fa-print"
        content: "Nastavte obmedzenia tlače na dokumenty PDF"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "Vykreslite obsah/súbory obsiahnuté v archívoch ZIP ako prílohy"

      # feature loop
      - icon: "fas fa-lock"
        content: "Získajte prílohy z dokumentov chránených heslom"

      # feature loop
      - icon: "fas fa-file-code"
        content: "Renderujte formáty súborov programovacích jazykov ako obyčajný text"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "Upravte farby pozadia pri prezeraní výkresov CAD"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "Prezerajte si dokumenty Excel a prevádzajte ich do PDF, HTML, JPG a PNG"

      # feature loop
      - icon: "fas fa-heading"
        content: "Získajte názvy pracovných hárkov zo súboru Excel – Zobrazte nadpisy stĺpcov tabuľky a čísla riadkov"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "Zobrazte a konvertujte dokumenty Microsoft Project pomocou poznámok"

      # feature loop
      - icon: "fas fa-cube"
        content: "Preveďte výkresy CAD do formátu SVG pre lepšie prezeranie a približovanie"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "Vyberte vykreslenie obrázkov Visia bez schémy"

    more_feature:
      # more_feature_loop
      - title: "Zobrazujte dokumenty efektívne a spoľahlivo"
        content: |
          Pomocou GroupDocs.Viewer API môžete efektívne a spoľahlivo zobraziť viac ako 190 formátov dokumentov s neporušenou integritou obsahu a štruktúry dokumentu. Nasledujúci vzorový kód ukazuje, aké ľahké je zobraziť HTML reprezentáciu dokumentu DOCX:

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
      - title: "Použiť transformáciu na vykreslený výstup"
        content: "Pomocou GroupDocs.Viewer for .NET API môžete vykonať rôzne transformácie vykresleného výstupného dokumentu. Tieto možnosti transformácie vám poskytujú kontrolu nad spôsobom, akým prezentujete vykreslený výstup na zobrazenie. Dostupné transformácie sú možnosť otáčania strany, možnosť zmeny poradia strany a aplikovanie textového vodoznaku."

      # more_feature_loop
      - title: "Práca s dátovými súbormi programu Outlook"
        content: "GroupDocs.Viewer for .NET API dokáže vykresliť položky v dátových súboroch programu Outlook (OST/PST) ako súbory PDF, HTML a obrázkové súbory. Naše rozhranie Viewer API má tiež schopnosť získať zoznam priečinkov obsiahnutých v dátových súboroch programu Outlook. Pomocou rozhrania GroupDocs.Viewer for .NET API môžete určiť priečinok, ktorý sa má vykresliť z údajových súborov programu Outlook. Podobne môžete ako prílohy získať aj e-mailové správy obsiahnuté vo formátoch OST/PST. GroupDocs.Viewer for .NET vám tiež umožňuje filtrovať správy z formátov OST/PST na základe predmetu, obsahu alebo odosielateľa."

      # more_feature_loop
      - title: "Práca s CAD dokumentmi"
        content: "GroupDocs.Viewer for .NET API dokáže vykresliť model a všetky neprázdne rozloženia alebo vykresliť špecifické rozloženie súboru CAD. GroupDocs.Viewer for .NET API tiež podporuje dlaždicové vykresľovanie alebo vykresľovanie podľa súradníc CAD dokumentov do obrázkov, HTML alebo PDF. Môžete tiež získať stavy vrstiev pre CAD dokumenty."

############################# Testimonials ###############################
testimonials:
  enable: true

  testimonial:
    # testimonial item loop
    - name: "Margot Baill"
      designation: "Riaditeľ vývoja produktov v Hireology"
      content: "Integrácia GroupDocs.Viewer pre Cloud API bola jednoduchá s ich fantastickou súpravou Ruby SDK. Nie je tam až tak veľa spoločností, ktoré sú ochotné s nami spolupracovať na tom, čo chceme. Je to skvelé partnerstvo."

    # testimonial item loop
    - name: "Mats Oustad"
      designation: "Senior Consultant/Partner v Novanet AS"
      content: "Po implementácii a použití GroupDocs.Viewer pre .NET v projekte to vyzerá, že funguje veľmi dobre. Testoval som s množstvom dokumentov a zatiaľ je to dobré. Všetko, čo som naň hodil, sa pekne vykresľuje a vyzerá rovnako dobre ako v prehliadači PDF alebo MS Word."
              
    # testimonial item loop
    - name: "Martin Lasarga"
      designation: "Product Manager v spoločnosti Axentria ECM by G.S.I."
      content: "Vynikajúce služby a vynikajúce produkty. Počas procesu implementácie GroupDocs.Viewer pre .NET boli mimoriadne nápomocní a pohotoví, nemôžeme ich dostatočne odporučiť."

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Viewer ponúka rozhrania API na prezeranie dokumentov pre ďalšie populárne vývojové prostredia"

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
