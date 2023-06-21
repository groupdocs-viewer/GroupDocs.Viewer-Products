---
############################# Static ##########################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

lang: no
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: ".NET Document Viewer API, Render PDF Word Excel Image HTML Diagram"
head_description: "C# ASP.NET filviser og gjengivelses-API. Legg til funksjoner for PDF-visning, Word-visning, Excel-visning, bildeviser, HTML-visning, e-postvisning i .NET-apper."

############################# Header ##########################
title: "Gjengi og vis dokumenter via .NET API"
description: ".NET Document Viewer API for å gjengi 190+ dokumentformater til PDF, HTML og bilde med kraftige konfigurasjonsalternativer."
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
              text: "Oversikt"

            # button loop
            - link: "#features"
              text: "Egenskaper"

            # button loop
            - link: "#support"
              text: "Brukerstøtte"

            # button loop
            - link: "https://products.groupdocs.app/viewer/total"
              text: "Live Demo"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Prissetting"

    right:
        link_download: "https://releases.groupdocs.com/viewer/net/"
        link_learn: "https://docs.groupdocs.com/viewer/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    content: |
      GroupDocs.Viewer for .NET APIer hjelper deg med å lage kraftige applikasjoner i C#, ASP.NET og andre .NET-baserte teknologier, som kan gjengi og vise dokumenter og bilder av 190+ filformater uten å installere ekstern programvare. Filvisningsbiblioteket rastrerer dokumentene og konverterer dem deretter til SVG+HTML+CSS for å optimere den generelle dokumentgjengivelsesopplevelsen for visning av forretningsdokumenter, bilder, tekstfiler, diagrammer, grafikk, e-postvedlegg og PDF-filer med hastighet, sann tekst og high-fidelity i applikasjonene dine. Du har muligheten til å legge til dokumentvisnings- og lesefunksjoner i applikasjonene dine for å vise hele dokumentet, delvis dokument, spesifikt side-/celleområde, individuelt dokumentlag, med eller uten merknader og kommentarer for de støttede filformatene.
       
      GroupDocs.Viewer for .NET bufrer de gjengitte dokumentene som sendes ut til den lokale disken som standard. Enhver type ekstern cache-lagring støttes også ved å implementere passende grensesnitt – Amazon S3, Dropbox, Google Drive, Windows Azure, Redis eller andre.
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          Følgende er en oversikt over GroupDocs.Viewer for .NET:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Oversikt"
          content: |
            * Vis 190+ dokumenttyper 
            * Få en fil i HTML, Bilde, PDF-format 
            * Roter og omorganiser 
            * Påfør vannmerke 
            * Cache for rask prosess 
            * Legg til egendefinerte skrifter 
            * Bruk kodingsstandarder 
            * Custom Input Data Handler 
            * Gjengi med sporendringer 
            * Gjengi som responsiv HTML 
            * Gjengi PDF- og CAD-lag 
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Viewer for .NET støtter visning av alle populære dokumentfilformater. Med bare noen få linjer med kode kan du legge til PDF-visningsprogram, Microsoft Office Word, Excel-regneark, bilde, HTML, Outlook-e-post, OneNote, Project og grafikkvisning i .NET-applikasjonene dine.

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
                * **Sideoppsettfiler:** PDF, TEX, XPS, OXPS
                * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG, OTG, FODP, FODG
                * **Skilletegn-separerte verdier:** CSV, TSV
                * **Web:** HTML, MHT, MHTML
                * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
                * **PostScript:** PS, EPS
                * **Arkiv:** ZIP, TAR, BZ2, GZ, RAR, RAR5
                * **Diverse:** OBJ, EPUB, MOBI, DjVu, XML, VCF, VCARD, NUMBERS, NSF

        right:
          enable: true
          table:
            # table loop
            - title: "Bilder, grafikk og diagrammer"
              content: |
                * **Bilder:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB
                * **Windows-ikon:** ICO
                * **Skalerbar vektorgrafikk:** SVG, CDR, CMX, IGS, SVGZ
                * **Jpeg2000:** JP2, J2C, J2K, JPC, JPF, JPX, JPM
                * **Adobe Photoshop:** PSD, PSB
                * **Skriverkommandospråk:** PCL
                * **Stereolitografi (3D-utskrift):** STL
                * **Industry Foundation-klasser:** IFC
                * **Medisinsk bildebehandling:** DICOM
                * **Plotterdokumenter:** PLT, HPG
                * **Autodesk Design Web Formater:** DWF, DWG
                * **AutoCAD-tegning:** DWT, IFC, STL, CF2
                * **ISFF-basert DGN (V7):** DGN

            # table loop
            - title: "Programmeringsspråk formater"
              content: |
                * **C/C++/C# filer:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
                * **Java/JavaScript-filer:** JAVA, JS, JSON, PROPERTIES
                * **Diverse:** VB, PHP, SQL, PL, PY, PV, RB, RST, SASS, SCALA, SCM, SCRIPT, AS, AS3, ASM, BAT, CMAKE, CSS, DIFF, ERB, GROOVY, HAML, LESS, LOG, M, MAKE, MD, ML, MM, SH, SML, VIM, YAML

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Viewer for .NET støtter følgende operativsystemer, rammeverk og pakkeadministratorer:
        
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
              title: "Støttede rammer"
              content: |
                * .NET Framework 2.0 eller høyere 
                * .NET Core 3.1 
                * .NET 5 eller høyere 

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-box"
              title: "Pakkebehandler"
              content: |
                * NuGet

            # table loop
            - icon: "fas fa-tools"
              title: "Utviklingsmiljøer"
              content: |
                * Microsoft Visual Studio
                * Visual Studio Code
                * .NET CLI

############################# Features ############################
features:
    enable: true
    title: "GroupDocs.Viewer for .NET-funksjoner"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "Rasteriser dokumenter og konverter dem til SVG, HTML og CSS"

      # feature loop
      - icon: "fas fa-eye"
        content: "Konverter tekst til HTML og gjengi dokumenter for å få HTML-, bilde- eller PDF-representasjon"

      # feature loop
      - icon: "fas fa-bolt"
        content: "Raskere innlastingstid ved å bruke bufrede versjoner av dokumenter"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "Konverter presentasjoner med former og tekst med 3D-effekter"

      # feature loop
      - icon: "fas fa-code"
        content: "Kod Word-, Excel- og e-postdokumenter til ønsket kodingsstandard"

      # feature loop
      - icon: "fas fa-cloud"
        content: "Gjengi dokumenter plassert på FTP- eller skylagringssteder"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "Ekskludering av skrifter ved gjengivelse til HTML for å redusere resulterende filstørrelse"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "Reduser CSS- og HTML-utdata ved å fjerne kommentarer, ekstra mellomrom osv."

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "Les teksten i et kildedokument gjennom koordinatene"

      # feature loop
      - icon: "fas fa-border-all"
        content: "Vis/skjul rutenettlinjene til Excel-ark i utdatarepresentasjon"

      # feature loop
      - icon: "fas fa-wrench"
        content: "Angi antall rader i et Excel-ark som skal gjengis på hver side"

      # feature loop
      - icon: "fas fa-columns"
        content: "Ignorer tomme kolonner mens du gjengir regnearkdokumenter"

      # feature loop
      - icon: "fas fa-file-word"
        content: "Gjengi Word-dokumenter til HTML-sider, bilder eller PDF, med spor endringer"

      # feature loop
      - icon: "fas fa-envelope"
        content: "Gjengi e-postvedlegg som originalfiler, bilder eller i HTML-representasjon"

      # feature loop
      - icon: "fas fa-print"
        content: "Angi utskriftsbegrensninger på PDF-dokumenter"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "Gjengi innhold/filer i ZIP-arkiver som vedlegg"

      # feature loop
      - icon: "fas fa-lock"
        content: "Skaff vedlegg fra passordbeskyttede dokumenter"

      # feature loop
      - icon: "fas fa-file-code"
        content: "Gjengi filformater for programmeringsspråk som ren tekst"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "Juster bakgrunnsfarger når du ser på CAD-tegninger"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "Se Excel-dokumenter og konverter til PDF, HTML, JPG og PNG"

      # feature loop
      - icon: "fas fa-heading"
        content: "Få regnearknavn fra Excel-fil – Vis regnearkkolonneoverskrifter og radnummer"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "Vis og konverter Microsoft Project-dokumenter med notater"

      # feature loop
      - icon: "fas fa-cube"
        content: "Konverter CAD-tegninger til SVG for bedre visnings- og zoomopplevelse"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "Velg å gjengi Visio-figurer uten skjema"

    more_feature:
      # more_feature_loop
      - title: "Se dokumenter effektivt og pålitelig"
        content: |
          Ved å bruke GroupDocs.Viewer API kan du vise mer enn 190 dokumentformater effektivt og pålitelig med innhold og dokumentstruktur intakt. Følgende eksempelkode viser hvor enkelt det er å se HTML-representasjon av et DOCX-dokument:

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
      - title: "Bruk transformasjon på gjengitt utgang"
        content: "Du kan utføre ulike transformasjoner til det gjengitte utdatadokumentet ved å bruke GroupDocs.Viewer for .NET API. Disse transformasjonsalternativene gir deg kontroll over måten du presenterer det gjengitte resultatet for visning. De tilgjengelige transformasjonene er alternativ for siderotering, alternativ for siderekkefølge og bruk av tekstvannmerke."

      # more_feature_loop
      - title: "Arbeide med Outlook-datafiler"
        content: "GroupDocs.Viewer for .NET API kan gjengi elementene i Outlook-datafiler (OST/PST) som PDF-, HTML- og bildefiler. Vår Viewer API har også muligheten til å hente listen over mapper som finnes i Outlook-datafiler. Ved å bruke GroupDocs.Viewer for .NET API kan du spesifisere mappen som skal gjengis fra Outlook-datafiler. På samme måte kan du også få e-postmeldinger i OST/PST-formater som vedlegg. GroupDocs.Viewer for .NET lar deg også filtrere meldinger fra OST/PST-formater basert på emne, innhold eller avsender."

      # more_feature_loop
      - title: "Arbeid med CAD-dokumenter"
        content: "GroupDocs.Viewer for .NET API kan gjengi modell og alle ikke-tomme oppsett eller gjengi et spesifikt oppsett av en CAD-fil. GroupDocs.Viewer for .NET API støtter også flislagt gjengivelse eller gjengivelse av koordinater av CAD-dokumenter til bilde, HTML eller PDF. Du kan også få lagstatuser for CAD-dokumenter."

############################# Testimonials ###############################
testimonials:
  enable: true

  testimonial:
    # testimonial item loop
    - name: "Margot Baill"
      designation: "Produktutviklingsdirektør i Hireology"
      content: "Det var enkelt å integrere GroupDocs.Viewer for Cloud API med deres fantastiske Ruby SDK. Det er ikke så mange bedrifter der ute som er villige til å samarbeide med oss ​​om det vi ønsker. Det er et flott partnerskap."

    # testimonial item loop
    - name: "Mats Oustad"
      designation: "Seniorkonsulent/Partner i Novanet AS"
      content: "Etter å ha implementert og brukt GroupDocs.Viewer for .NET i prosjektet ser det ut til å fungere veldig bra. Jeg har testet med mange dokumenter og så langt så bra. Alt jeg har kastet på den, gjengis pent og ser like bra ut som i en PDF-visning eller MS Word."
              
    # testimonial item loop
    - name: "Martin Lasarga"
      designation: "Produktsjef hos Axentria ECM av G.S.I."
      content: "Utmerket service og gode produkter. De var ekstremt hjelpsomme og lydhøre under implementeringsprosessen for GroupDocs.Viewer for .NET, kan ikke anbefale dem høyt nok."

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Viewer tilbyr API-er for dokumentvisning for andre populære utviklingsmiljøer"

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
