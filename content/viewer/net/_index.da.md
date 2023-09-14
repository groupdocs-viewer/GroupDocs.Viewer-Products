---
############################# Static ##########################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

lang: da
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: ".NET Document Viewer API, Render PDF Word Excel Billede HTML Diagram"
head_description: "C# ASP.NET filfremviser og gengivelses-API. Tilføj PDF-fremviser, Word-fremviser, Excel-fremviser, Billedfremviser, HTML-fremviser, E-mail-fremviserfunktioner i .NET-apps."

############################# Header ##########################
title: "Gengiv og vis dokumenter via .NET API"
description: ".NET Document Viewer API til at gengive 190+ dokumentformater til PDF, HTML og billede med kraftfulde konfigurationsmuligheder."
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
              text: "Oversigt"

            # button loop
            - link: "#features"
              text: "Funktioner"

            # button loop
            - link: "#support"
              text: "Support"

            # button loop
            - link: "https://products.groupdocs.app/viewer/total"
              text: "Live demo"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Prissætning"

    right:
        link_download: "https://www.nuget.org/packages/GroupDocs.Viewer"
        link_learn: "https://docs.groupdocs.com/viewer/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    content: |
      GroupDocs.Viewer til .NET API'er hjælper dig med at skabe kraftfulde applikationer i C#, ASP.NET og andre .NET-baserede teknologier, som kan gengive og vise dokumenter og billeder af 190+ filformater uden at installere ekstern software. Filfremviserbiblioteket rasteriserer dokumenterne og konverterer dem derefter til SVG+HTML+CSS for at optimere den overordnede dokumentgengivelsesoplevelse til visning af forretningsdokumenter, billeder, tekstfiler, diagrammer, grafik, e-mailvedhæftede filer og PDF-filer med hastighed, ægte tekst og high-fidelity i dine applikationer. Du har mulighed for at tilføje dokumentvisnings- og læsefunktioner i dine applikationer for at vise hele dokumentet, delvist dokument, specifikt side-/celleområde, individuelt dokumentlag, med eller uden anmærkninger og kommentarer til de understøttede filformater.
       
      GroupDocs.Viewer til .NET cacherer de gengivede dokumenter, der er outputtet til den lokale disk som standard. Enhver form for ekstern cachelagring understøttes også ved at implementere passende grænseflader - Amazon S3, Dropbox, Google Drive, Windows Azure, Redis eller andre.
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          Følgende er en oversigt over GroupDocs.Viewer til .NET:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Oversigt"
          content: |
            * Vis mere end 190 dokumenttyper 
            * Hent en fil i HTML, Billede, PDF-format 
            * Roter og omarranger 
            * Påfør vandmærke 
            * Cache til hurtig proces 
            * Tilføj brugerdefinerede skrifttyper 
            * Anvend kodningsstandarder 
            * Custom Input Data Handler 
            * Render med sporændringer 
            * Gengiv som responsiv HTML 
            * Gengiv PDF- og CAD-lag 
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Viewer til .NET understøtter visning af alle populære dokumentfilformater. Med blot et par linjer kode kan du tilføje PDF-fremviser, Microsoft Office Word, Excel-regneark, Billede, HTML, Outlook-e-mail, OneNote, Projekt- og grafikvisningsmuligheder i dine .NET-applikationer.

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
                * **Sidelayoutfiler:** PDF, TEX, XPS, OXPS
                * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG, OTG, FODP, FODG
                * **Skilletegn-separerede værdier:** CSV, TSV
                * **Web:** HTML, MHT, MHTML
                * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
                * **PostScript:** PS, EPS
                * **Arkiv:** ZIP, TAR, BZ2, GZ, RAR, RAR5
                * **Forskellige:** OBJ, EPUB, MOBI, DjVu, XML, VCF, VCARD, NUMBERS, NSF

        right:
          enable: true
          table:
            # table loop
            - title: "Billeder, grafik og diagrammer"
              content: |
                * **Billeder:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB
                * **Windows ikon:** ICO
                * **Skalerbar vektorgrafik:** SVG, CDR, CMX, IGS, SVGZ
                * **Jpeg2000:** JP2, J2C, J2K, JPC, JPF, JPX, JPM
                * **Adobe Photoshop:** PSD, PSB
                * **Printerkommandosprog:** PCL
                * **Stereolitografi (3D-print):** STL
                * **Industrifondens klasser:** IFC
                * **Medicinsk billeddannelse:** DICOM
                * **Plotterdokumenter:** PLT, HPG
                * **Autodesk Design webformater:** DWF, DWG
                * **AutoCAD tegning:** DWT, IFC, STL, CF2
                * **ISFF-baseret DGN (V7):** DGN

            # table loop
            - title: "Programmeringssprog formater"
              content: |
                * **C/C++/C# filer:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
                * **Java/JavaScript-filer:** JAVA, JS, JSON, PROPERTIES
                * **Forskellige:** VB, PHP, SQL, PL, PY, PV, RB, RST, SASS, SCALA, SCM, SCRIPT, AS, AS3, ASM, BAT, CMAKE, CSS, DIFF, ERB, GROOVY, HAML, LESS, LOG, M, MAKE, MD, ML, MM, SH, SML, VIM, YAML

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Viewer til .NET understøtter følgende operativsystemer, rammer og pakkeadministratorer:
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Operativsystemer"
              content: |
                * Microsoft Windows Server 2003 og nyere 
                * Microsoft Windows XP og nyere 
                * Microsoft Windows 10 og 11 
                * Linux (Ubuntu, OpenSUSE, CentOS og andre) 
                * Mac OS X 

            # table loop
            - icon: "fas fa-code"
              title: "Understøttede rammer"
              content: |
                * .NET Framework 2.0 eller nyere 
                * .NET Core 3.1 
                * .NET 5 eller højere 

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-box"
              title: "Pakkeadministrator"
              content: |
                * NuGet

            # table loop
            - icon: "fas fa-tools"
              title: "Udviklingsmiljøer"
              content: |
                * Microsoft Visual Studio
                * Visual Studio Code
                * .NET CLI

############################# Features ############################
features:
    enable: true
    title: "GroupDocs.Viewer til .NET-funktioner"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "Rasteriser dokumenter og konverter dem til SVG, HTML og CSS"

      # feature loop
      - icon: "fas fa-eye"
        content: "Konverter tekst til HTML og gengiv dokumenter for at få HTML-, billed- eller PDF-repræsentation"

      # feature loop
      - icon: "fas fa-bolt"
        content: "Hurtigere indlæsningstid ved hjælp af cachelagrede versioner af dokumenter"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "Konverter præsentationer med former og tekst med 3D-effekter"

      # feature loop
      - icon: "fas fa-code"
        content: "Kod Word-, Excel- og e-mail-dokumenter til den ønskede kodningsstandard"

      # feature loop
      - icon: "fas fa-cloud"
        content: "Gengiv dokumenter placeret på FTP eller Cloud Storage Locations"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "Ekskludering af skrifttyper ved gengivelse til HTML for at reducere den resulterende filstørrelse"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "Formindsk CSS- og HTML-output ved at fjerne kommentarer, ekstra hvide mellemrum osv."

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "Læs teksten indeholdt i et kildedokument gennem dets koordinater"

      # feature loop
      - icon: "fas fa-border-all"
        content: "Vis/skjul gitterlinjerne i Excel-ark i outputrepræsentation"

      # feature loop
      - icon: "fas fa-wrench"
        content: "Angiv antallet af rækker i et Excel-ark, der skal gengives på hver side"

      # feature loop
      - icon: "fas fa-columns"
        content: "Ignorer tomme kolonner under gengivelse af regnearksdokumenter"

      # feature loop
      - icon: "fas fa-file-word"
        content: "Gengiv Word-dokumenter til HTML-sider, billeder eller PDF med spor ændringer"

      # feature loop
      - icon: "fas fa-envelope"
        content: "Gengiv e-mail-vedhæftede filer som originale filer, billeder eller i HTML-repræsentation"

      # feature loop
      - icon: "fas fa-print"
        content: "Indstil udskrivningsbegrænsninger på PDF-dokumenter"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "Gengiv indhold/filer indeholdt i ZIP-arkiver som vedhæftede filer"

      # feature loop
      - icon: "fas fa-lock"
        content: "Hent vedhæftede filer fra adgangskodebeskyttede dokumenter"

      # feature loop
      - icon: "fas fa-file-code"
        content: "Gengiv programmeringssprog filformater som almindelig tekst"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "Juster baggrundsfarver, når du ser CAD-tegninger"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "Se Excel-dokumenter og konverter til PDF, HTML, JPG og PNG"

      # feature loop
      - icon: "fas fa-heading"
        content: "Få regnearksnavne fra Excel-fil – Vis regnearks kolonneoverskrifter og rækkenumre"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "Se og konverter Microsoft Project-dokumenter med noter"

      # feature loop
      - icon: "fas fa-cube"
        content: "Konverter CAD-tegninger til SVG for bedre visnings- og zoomoplevelse"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "Vælg at gengive Visio-figurer uden skema"

    more_feature:
      # more_feature_loop
      - title: "Se dokumenter effektivt og pålideligt"
        content: |
          Ved at bruge GroupDocs.Viewer API kan du vise mere end 190 dokumentformater effektivt og pålideligt med intakt indhold og dokumentstruktur. Følgende eksempelkode viser, hvor nemt det er at se HTML-repræsentation af et DOCX-dokument:

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
      - title: "Anvend transformation på gengivet output"
        content: "Du kan udføre forskellige transformationer til det gengivne outputdokument ved hjælp af GroupDocs.Viewer til .NET API. Disse transformationsmuligheder giver dig kontrol over den måde, du præsenterer det gengivede output på til visning. De tilgængelige transformationer er, siderotationsindstilling, sidegenkendelsesindstilling og anvendelse af tekstvandmærke."

      # more_feature_loop
      - title: "Arbejde med Outlook-datafiler"
        content: "GroupDocs.Viewer for .NET API kan gengive elementerne i Outlook-datafiler (OST/PST) som PDF-, HTML- og billedfiler. Vores Viewer API har også mulighed for at hente listen over mapper indeholdt i Outlook-datafiler. Ved at bruge GroupDocs.Viewer til .NET API kan du angive den mappe, der skal gengives fra Outlook-datafiler. Ligeledes kan du også få e-mail-beskeder indeholdt i OST/PST-formater som vedhæftede filer. GroupDocs.Viewer for .NET giver dig også mulighed for at filtrere beskeder fra OST/PST-formater baseret på emne, indhold eller afsender."

      # more_feature_loop
      - title: "Arbejde med CAD-dokumenter"
        content: "GroupDocs.Viewer for .NET API kan gengive model og alle ikke-tomme layouts eller gengive et specifikt layout af en CAD-fil. GroupDocs.Viewer til .NET API understøtter også flisebelagt gengivelse eller gengivelse af koordinater af CAD-dokumenter til billede, HTML eller PDF. Du kan også få lagstatusser for CAD-dokumenter."

############################# Testimonials ###############################
testimonials:
  enable: true

  testimonial:
    # testimonial item loop
    - name: "Margot Baill"
      designation: "Produktudviklingsdirektør hos Hireology"
      content: "Det var enkelt at integrere GroupDocs.Viewer til Cloud API med deres fantastiske Ruby SDK. Der er ikke så mange virksomheder derude, som er villige til at arbejde sammen med os om det, vi ønsker. Det er et godt partnerskab."

    # testimonial item loop
    - name: "Mats Oustad"
      designation: "Seniorkonsulent/Partner hos Novanet AS"
      content: "Efter implementering og brug af GroupDocs.Viewer til .NET i projektet ser det ud til at fungere meget godt. Jeg har testet med en masse dokumenter og indtil videre så godt. Alt, hvad jeg har kastet efter det, gengives pænt og ser lige så godt ud, som det ville gøre i en PDF-fremviser eller MS Word."
              
    # testimonial item loop
    - name: "Martin Lasarga"
      designation: "Product Manager hos Axentria ECM by G.S.I."
      content: "Fremragende service og fremragende produkter. De var ekstremt hjælpsomme og lydhøre under GroupDocs.Viewer til .NET implementeringsprocessen, kan ikke anbefale dem stærkt nok."

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Viewer tilbyder API'er til dokumentvisning til andre populære udviklingsmiljøer"

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
