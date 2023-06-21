---
############################# Static ############################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

lang: cs
product: "Viewer"
product_tag: "viewer"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "Java Document Viewer API pro PDF Word Excel HTML obrázky a e-maily"
head_description: "Prohlížeč dokumentů Java a rozhraní API pro vykreslování souborů. Přidejte prohlížeč PDF, prohlížeč Word, prohlížeč Excel, prohlížeč obrázků, prohlížeč HTML, prohlížeč e-mailů v aplikacích Java."

############################# Header ############################
title: "Java API pro vykreslování a zobrazování dokumentů"
description: "Knihovna prohlížeče dokumentů pro vývoj aplikací Java, které nativně vykreslují, prohlížejí a manipulují s dokumenty ve více formátech podporujících více než 170 formátů souborů."
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
            - link: "https://purchase.groupdocs.com/pricing/viewer/java"
              text: "Ceny"

    right:
        link_download: "https://releases.groupdocs.com/viewer/java/"
        link_learn: "https://docs.groupdocs.com/viewer/java/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    content: |
      GroupDocs.Viewer for Java kombinuje výkonnou sadu rozhraní API pro prohlížení dokumentů pro zobrazení obrázků a formátů dokumentů ve vašich aplikacích Java bez nutnosti instalace dalšího softwaru. Nativně rastruje dokumenty a převádí je do formátu SVG+HTML+CSS pro zvýšení kvality prohlížení dokumentů a zároveň poskytuje věrný text s vysokou věrností výstupu. Pomocí rozhraní API pro vykreslování dokumentů – rychle prohlížejte PDF, HTML, XML, Microsoft Office Word, pracovní listy Excelu, prezentace PowerPoint, e-maily z Outlooku, diagramy Visio, Project, metasoubory, obrázky a různé další formáty souborů s lehkostí a menším nebezpečím programování. Může také zobrazovat soubory chráněné heslem a po vykreslení umožňuje získat reprezentaci dokumentu jako HTML, obrázek nebo PDF. Naše knihovna prohlížeče souborů je docela přizpůsobitelná, protože vám umožňuje zobrazit celý dokument nebo jej částečně vykreslit, aby se proces urychlil. Prostřednictvím GroupDocs.Viewer for Java API můžete prohlížet stránky, konkrétní rozsah buněk v tabulce nebo dokonce vykreslovat jednotlivé vrstvy dokumentu ve formátech, jako je PDF a CAD.  

      GroupDocs.Viewer for Java API umožňuje vykreslovat dokumenty s/bez anotací nebo komentářů pro podporované formáty souborů. Umožňuje také přidávat vlastní adresáře písem a extrahovat základní informace o dokumentu, jako je FileType, Extension, Name, PageCount atd.  

      GroupDocs.Viewer for Java je kompatibilní se všemi verzemi Java a podporuje oblíbené operační systémy (Windows, Linux, macOS), které jsou schopny spouštět Java runtime.
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          Následuje přehled GroupDocs.Viewer pro Java:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Přehled"
          content: |
            * Zobrazit více než 170 typů dokumentů 
            * Získejte HTML, obrázek, PDF verzi 
            * Otočit a změnit pořadí 
            * Použít vodoznak 
            * Mezipaměť pro rychlý proces 
            * Přidat vlastní písma 
            * Použít standardy kódování 
            * Vlastní popisovač vstupních dat 
            * Render se sledováním změn 
            * Vykreslit jako responzivní HTML 
            * Vykreslování vrstev PDF a CAD 
            * Vykreslit chráněné soubory 
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Viewer for Java podporuje všechny oblíbené formáty souborů dokumentů včetně: Microsoft Office, obrázků, diagramů a mnoha dalších.

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
            - title: "Jiné formáty"
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
          GroupDocs.Viewer for Java podporuje následující operační systémy, rámce a správce balíčků:
        
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
                * J2SE 8.0 (1.8) nebo vyšší (například Java 17) 

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-cogs"
              title: "Vývojová prostředí"
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
    title: "GroupDocs.Viewer pro funkce Java"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "Prohlížeč pro HTML, PDF, obrázky, Word, Excel a další formáty dokumentů"

      # feature loop
      - icon: "fas fa-eye"
        content: "Renderujte soubory výkresů AutoCAD (DWG) do formátu SVG"

      # feature loop
      - icon: "fas fa-bolt"
        content: "Upravte barvu pozadí převedeného souboru"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "Rastrujte a převádějte dokumenty do SVG, HTML a CSS"

      # feature loop
      - icon: "fas fa-code"
        content: "Získejte HTML, obrázek nebo PDF reprezentaci dokumentů prostřednictvím vykreslování"

      # feature loop
      - icon: "fas fa-cloud"
        content: "Verze dokumentů uložené v mezipaměti pro rychlejší načítání"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "Konfigurace vlastních adresářů písem"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "Použijte standardy kódování na dokumenty Word, Excel a e-mail"

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "Vzdáleně vykreslovat dokumenty na FTP nebo Cloud Storage"

      # feature loop
      - icon: "fas fa-border-all"
        content: "Odebrat nebo ponechat poznámky a komentáře při vykreslování"

      # feature loop
      - icon: "fas fa-wrench"
        content: "Vykreslit stránky dokumentu jako samostatné stránky HTML"

      # feature loop
      - icon: "fas fa-columns"
        content: "Vykreslit skryté snímky a stránky a použít změnu pořadí stránek na vykreslený dokument"

      # feature loop
      - icon: "fas fa-file-word"
        content: "Vykreslení rozsahu stránek, konkrétních stránek nebo všech stránek do HTML"

      # feature loop
      - icon: "fas fa-envelope"
        content: "Vykreslit nebo skrýt komentáře dokumentu"

      # feature loop
      - icon: "fas fa-print"
        content: "Vytvořte responzivní HTML pro některé formáty dokumentů pomocí vykreslování"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "Snižte velikost výsledného souboru vykresleného HTML vyloučením písem"

      # feature loop
      - icon: "fas fa-lock"
        content: "Odstraňte komentáře, bílé mezery atd., abyste minimalizovali výstupní HTML a CSS"

      # feature loop
      - icon: "fas fa-file-code"
        content: "Ke čtení obsaženého textu použijte souřadnice zdrojového dokumentu"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "Zobrazit/skrýt ohraničení buňky v listech Excelu vykresleného výstupu"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "Vykreslení určitého počtu řádků každé stránky v listu aplikace Excel"

      # feature loop
      - icon: "fas fa-heading"
        content: "Vykreslit model a všechna neprázdná rozvržení nebo konkrétní rozvržení souboru CAD"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "Vykreslete položky v datových souborech aplikace Outlook (OST/PST) jako PDF"

      # feature loop
      - icon: "fas fa-cube"
        content: "Vykreslování dlaždic nebo vykreslování podle souřadnic CAD dokumentů jako obrázek, HTML nebo PDF"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "Nastavte omezení tisku při vykreslování do PDF"

    more_feature:
      # more_feature_loop
      - title: "Efektivní a spolehlivé API pro prohlížení dokumentů"
        content: |
          GroupDocs.Viewer for Java API lze použít k prohlížení, vykreslování a zobrazování dokumentů více než 150 různých formátů souborů. Provádí se spolehlivě a efektivně při zachování obsahu i struktury dokumentu. Následující příklad ukazuje úroveň snadnosti, s jakou GroupDocs.Viewer for Java API vykresluje soubor DOCX jako obrazový soubor pomocí Java:

          ```java
          // Initialize Viewer
          Viewer viewer = new Viewer("invoice.docx");
          // Create view options
          PdfViewOptions viewOptions = new PdfViewOptions();
          // Convert file to PDF and check the output in the current directory
          viewer.view(viewOptions);
          ```
      # more_feature_loop
      - title: "Provádějte transformace při vykreslování dokumentů"
        content: "GroupDocs.Viewer for Java API vám nabízí různé možnosti transformace, které lze použít na vykreslený dokument pro přizpůsobení zobrazení a zobrazení. Stránky můžete otáčet zadáním úhlu. Můžete si pořadí vykreslených stránek. Použijte konkrétní text jako vodoznak na vykreslené stránky nebo obrázky. Prostřednictvím GroupDocs.Viewer for Java API máte také možnost přidávat do vykreslovaného dokumentu vlastní písma."

      # more_feature_loop
      - title: "Práce s e-mailovými přílohami"
        content: "GroupDocs.Viewer for Java API umožňuje načíst konkrétní nebo všechny přílohy e-mailu. Jakmile získáte požadované přílohy e-mailu, můžete tyto připojené soubory vykreslit jako obrázky nebo HTML."

############################# Support ############################
support:
    enable: true

############################# Solutions ##########################
solutions:
    enable: true
    title: "GroupDocs.Viewer nabízí rozhraní API pro prohlížení dokumentů pro další populární vývojová prostředí"

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