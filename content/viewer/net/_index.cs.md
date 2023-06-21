---
############################# Static ##########################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

lang: cs
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: ".NET Document Viewer API, Render PDF Word Excel Obrázek HTML Diagram"
head_description: "C# ASP.NET prohlížeč souborů a vykreslovací API. Přidejte prohlížeč PDF, prohlížeč Word, prohlížeč Excel, prohlížeč obrázků, prohlížeč HTML a funkce prohlížeče e-mailů v aplikacích .NET."

############################# Header ##########################
title: "Vykreslování a zobrazování dokumentů prostřednictvím rozhraní .NET API"
description: ".NET Document Viewer API pro vykreslování 190+ formátů dokumentů do PDF, HTML a obrázků s výkonnými možnostmi konfigurace."
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
              text: "Přehled"

            # button loop
            - link: "#features"
              text: "Funkce"

            # button loop
            - link: "#support"
              text: "Podpěra, podpora"

            # button loop
            - link: "https://products.groupdocs.app/viewer/total"
              text: "Živá ukázka"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Ceny"

    right:
        link_download: "https://releases.groupdocs.com/viewer/net/"
        link_learn: "https://docs.groupdocs.com/viewer/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    content: |
      GroupDocs.Viewer for .NET API vám pomůže vytvářet výkonné aplikace v C#, ASP.NET a dalších technologiích založených na .NET, které dokážou vykreslovat a zobrazovat dokumenty a obrázky ve více než 190 formátech souborů bez instalace jakéhokoli externího softwaru. Knihovna prohlížeče souborů rastruje dokumenty a poté je převádí do formátu SVG+HTML+CSS, aby se optimalizovalo celkové vykreslování dokumentů pro prohlížení obchodních dokumentů, obrázků, textových souborů, diagramů, grafiky, e-mailových příloh a souborů PDF s rychlostí, skutečným textem a vysoká věrnost ve vašich aplikacích. Máte možnost přidat do svých aplikací funkce pro prohlížení a čtení dokumentů, abyste zobrazili celý dokument, částečný dokument, konkrétní rozsah stránek/buněk, jednotlivé vrstvy dokumentu, s nebo bez anotací a komentářů pro podporované formáty souborů.
       
      GroupDocs.Viewer for .NET standardně ukládá výstup vykreslených dokumentů na místní disk. Jakýkoli typ externího mezipaměti je podporován také implementací vhodných rozhraní – Amazon S3, Dropbox, Google Drive, Windows Azure, Redis nebo jakékoli jiné.
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          Následuje přehled GroupDocs.Viewer pro .NET:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Přehled"
          content: |
            * Zobrazit více než 190 typů dokumentů 
            * Získejte soubor ve formátu HTML, Obrázek, PDF 
            * Otočit a změnit pořadí 
            * Použít vodoznak 
            * Mezipaměť pro rychlý proces 
            * Přidat vlastní písma 
            * Použít standardy kódování 
            * Vlastní popisovač vstupních dat 
            * Render se sledováním změn 
            * Vykreslit jako responzivní HTML 
            * Vykreslování vrstev PDF a CAD 
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Viewer for .NET podporuje prohlížení všech oblíbených formátů souborů dokumentů. Pomocí několika řádků kódu přidejte do svých aplikací .NET prohlížeč PDF, Microsoft Office Word, tabulku Excel, obrázek, HTML, e-mail Outlook, OneNote, Project a možnosti prohlížení grafiky.

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
                * **Soubory rozvržení stránky:** PDF, TEX, XPS, OXPS
                * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG, OTG, FODP, FODG
                * **Hodnoty oddělené oddělovačem:** CSV, TSV
                * **Web:** HTML, MHT, MHTML
                * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
                * **PostScript:** PS, EPS
                * **Archiv:** ZIP, TAR, BZ2, GZ, RAR, RAR5
                * **Rozličný:** OBJ, EPUB, MOBI, DjVu, XML, VCF, VCARD, NUMBERS, NSF

        right:
          enable: true
          table:
            # table loop
            - title: "Obrázky, grafika a diagramy"
              content: |
                * **snímky:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB
                * **Ikona Windows:** ICO
                * **Škálovatelná vektorová grafika:** SVG, CDR, CMX, IGS, SVGZ
                * **Jpeg2000:** JP2, J2C, J2K, JPC, JPF, JPX, JPM
                * **Adobe Photoshop:** PSD, PSB
                * **Příkazový jazyk tiskárny:** PCL
                * **Stereo litografie (3D tisk):** STL
                * **Průmyslové základní třídy:** IFC
                * **Lékařské zobrazování:** DICOM
                * **Dokumenty plotru:** PLT, HPG
                * **Webové formáty Autodesk Design:** DWF, DWG
                * **Výkres AutoCAD:** DWT, IFC, STL, CF2
                * **DGN založené na ISFF (V7):** DGN

            # table loop
            - title: "Formáty programovacích jazyků"
              content: |
                * **Soubory C/C++/C#:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
                * **Soubory Java/JavaScript:** JAVA, JS, JSON, PROPERTIES
                * **Rozličný:** VB, PHP, SQL, PL, PY, PV, RB, RST, SASS, SCALA, SCM, SCRIPT, AS, AS3, ASM, BAT, CMAKE, CSS, DIFF, ERB, GROOVY, HAML, LESS, LOG, M, MAKE, MD, ML, MM, SH, SML, VIM, YAML

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Viewer for .NET podporuje následující operační systémy, rámce a správce balíčků:
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Operační systémy"
              content: |
                * Microsoft Windows Server 2003 a novější 
                * Microsoft Windows XP a novější 
                * Microsoft Windows 10 a 11 
                * Linux (Ubuntu, OpenSUSE, CentOS a další) 
                * Mac OS X 

            # table loop
            - icon: "fas fa-code"
              title: "Podporované rámce"
              content: |
                * .NET Framework 2.0 nebo vyšší 
                * .NET Core 3.1 
                * .NET 5 nebo vyšší 

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-box"
              title: "Správce balíčků"
              content: |
                * NuGet

            # table loop
            - icon: "fas fa-tools"
              title: "Vývojová prostředí"
              content: |
                * Microsoft Visual Studio
                * Visual Studio Code
                * .NET CLI

############################# Features ############################
features:
    enable: true
    title: "Funkce GroupDocs.Viewer for .NET"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "Rastrujte dokumenty a převádějte je do SVG, HTML a CSS"

      # feature loop
      - icon: "fas fa-eye"
        content: "Převeďte text do HTML a vykreslete dokumenty, abyste získali reprezentaci HTML, obrázek nebo PDF"

      # feature loop
      - icon: "fas fa-bolt"
        content: "Rychlejší načítání pomocí verzí dokumentů uložených v mezipaměti"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "Převádějte prezentace s tvary a textem s 3D efekty"

      # feature loop
      - icon: "fas fa-code"
        content: "Kódujte dokumenty Word, Excel a e-mail do požadovaného standardu kódování"

      # feature loop
      - icon: "fas fa-cloud"
        content: "Vykreslovat dokumenty umístěné v umístěních FTP nebo cloudových úložišť"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "Vyloučení písem při vykreslování do HTML, aby se zmenšila výsledná velikost souboru"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "Minimalizujte výstup CSS a HTML odstraněním komentářů, nadbytečných bílých míst atd."

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "Přečtěte si text obsažený ve zdrojovém dokumentu prostřednictvím jeho souřadnic"

      # feature loop
      - icon: "fas fa-border-all"
        content: "Zobrazit/skrýt čáry mřížky listů aplikace Excel ve výstupní reprezentaci"

      # feature loop
      - icon: "fas fa-wrench"
        content: "Zadejte počet řádků v listu aplikace Excel, které se mají vykreslit na každé stránce"

      # feature loop
      - icon: "fas fa-columns"
        content: "Ignorujte prázdné sloupce při vykreslování tabulkových dokumentů"

      # feature loop
      - icon: "fas fa-file-word"
        content: "Vykreslujte dokumenty aplikace Word do stránek HTML, obrázků nebo PDF se sledováním změn"

      # feature loop
      - icon: "fas fa-envelope"
        content: "Renderujte e-mailové přílohy jako původní soubory, obrázky nebo v reprezentaci HTML"

      # feature loop
      - icon: "fas fa-print"
        content: "Nastavte omezení tisku na dokumenty PDF"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "Vykreslit obsah/soubory obsažené v archivech ZIP jako přílohy"

      # feature loop
      - icon: "fas fa-lock"
        content: "Získejte přílohy z dokumentů chráněných heslem"

      # feature loop
      - icon: "fas fa-file-code"
        content: "Vykreslit formáty souborů programovacích jazyků jako prostý text"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "Upravte barvy pozadí při prohlížení výkresů CAD"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "Prohlížejte si dokumenty Excelu a převádějte je do PDF, HTML, JPG a PNG"

      # feature loop
      - icon: "fas fa-heading"
        content: "Získejte názvy listů ze souboru aplikace Excel – Zobrazte záhlaví sloupců tabulky a čísla řádků"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "Zobrazení a převod dokumentů Microsoft Project pomocí poznámek"

      # feature loop
      - icon: "fas fa-cube"
        content: "Převeďte výkresy CAD do formátu SVG pro lepší prohlížení a přiblížení"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "Zvolte vykreslení obrázků aplikace Visio bez schématu"

    more_feature:
      # more_feature_loop
      - title: "Prohlížejte dokumenty efektivně a spolehlivě"
        content: |
          Pomocí GroupDocs.Viewer API můžete efektivně a spolehlivě zobrazit více než 190 formátů dokumentů s neporušenou integritou obsahu a struktury dokumentu. Následující ukázkový kód ukazuje, jak snadné je zobrazit HTML reprezentaci dokumentu DOCX:

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
      - title: "Použít transformaci na vykreslený výstup"
        content: "Pomocí GroupDocs.Viewer for .NET API můžete provádět různé transformace vykresleného výstupního dokumentu. Tyto možnosti transformace vám dávají kontrolu nad způsobem, jakým prezentujete vykreslený výstup pro zobrazení. Dostupné transformace jsou možnost otočení stránky, možnost změny pořadí stránky a použití vodoznaku textu."

      # more_feature_loop
      - title: "Práce s datovými soubory aplikace Outlook"
        content: "GroupDocs.Viewer for .NET API dokáže vykreslit položky v datových souborech aplikace Outlook (OST/PST) jako soubory PDF, HTML a soubory obrázků. Naše rozhraní API prohlížeče také umožňuje získat seznam složek obsažených v datových souborech aplikace Outlook. Pomocí GroupDocs.Viewer for .NET API můžete určit složku, která se má vykreslit z datových souborů aplikace Outlook. Podobně můžete také získat e-mailové zprávy obsažené ve formátech OST/PST jako přílohy. GroupDocs.Viewer for .NET také umožňuje filtrovat zprávy z formátů OST/PST na základě předmětu, obsahu nebo odesílatele."

      # more_feature_loop
      - title: "Práce s CAD dokumenty"
        content: "GroupDocs.Viewer for .NET API dokáže vykreslit model a všechna neprázdná rozvržení nebo vykreslit konkrétní rozvržení souboru CAD. GroupDocs.Viewer for .NET API také podporuje dlaždicové vykreslování nebo vykreslování podle souřadnic CAD dokumentů do obrázku, HTML nebo PDF. Můžete také získat stavy vrstev pro CAD dokumenty."

############################# Testimonials ###############################
testimonials:
  enable: true

  testimonial:
    # testimonial item loop
    - name: "Margot Baill"
      designation: "Product Development Director ve společnosti Hireology"
      content: "Integrace GroupDocs.Viewer pro Cloud API byla jednoduchá s jejich fantastickým Ruby SDK. Není tam tolik společností, které jsou ochotné s námi spolupracovat na tom, co chceme. Je to skvělé partnerství."

    # testimonial item loop
    - name: "Mats Oustad"
      designation: "Senior Consultant/Partner ve společnosti Novanet AS"
      content: "Po implementaci a použití GroupDocs.Viewer pro .NET v projektu to vypadá, že funguje velmi dobře. Testoval jsem se spoustou dokumentů a zatím dobrý. Všechno, co jsem na něj hodil, se pěkně vykresluje a vypadá stejně dobře, jako by to vypadalo v prohlížeči PDF nebo MS Word."
              
    # testimonial item loop
    - name: "Martin Lasarga"
      designation: "Product Manager ve společnosti Axentria ECM by G.S.I."
      content: "Vynikající služby a skvělé produkty. Během procesu implementace GroupDocs.Viewer for .NET byli extrémně nápomocní a reagovali, nelze je dostatečně doporučit."

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Viewer nabízí rozhraní API pro prohlížení dokumentů pro další populární vývojová prostředí"

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
