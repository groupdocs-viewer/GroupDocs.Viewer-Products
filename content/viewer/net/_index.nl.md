---
############################# Static ##########################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

lang: nl
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: ".NET Document Viewer API, PDF Word Excel Afbeelding HTML-diagram weergeven"
head_description: "C# ASP.NET-bestandsviewer en rendering-API. Voeg functies voor PDF-viewer, Word-viewer, Excel-viewer, Image-viewer, HTML-viewer en e-mailviewer toe aan .NET-apps."

############################# Header ##########################
title: "Documenten weergeven en weergeven via .NET API"
description: ".NET Document Viewer API om meer dan 190 documentformaten om te zetten in PDF, HTML en afbeelding met krachtige configuratie-opties."
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
              text: "Overzicht"

            # button loop
            - link: "#features"
              text: "Functies"

            # button loop
            - link: "#support"
              text: "Steun"

            # button loop
            - link: "https://products.groupdocs.app/viewer/total"
              text: "Live demonstratie"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Prijzen"

    right:
        link_download: "https://www.nuget.org/packages/GroupDocs.Viewer"
        link_learn: "https://docs.groupdocs.com/viewer/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    content: |
      GroupDocs.Viewer voor .NET API's helpen u bij het maken van krachtige toepassingen in C#, ASP.NET en andere op .NET gebaseerde technologieën, die documenten en afbeeldingen van meer dan 190 bestandsindelingen kunnen renderen en weergeven zonder externe software te installeren. De bestandsviewerbibliotheek rastert de documenten en converteert ze vervolgens naar SVG+HTML+CSS om de algehele weergave van documenten te optimaliseren voor het snel bekijken van zakelijke documenten, afbeeldingen, tekstbestanden, diagrammen, afbeeldingen, e-mailbijlagen en PDF-bestanden met snelheid, ware tekst en high-fidelity binnen uw toepassingen. U hebt de mogelijkheid om functionaliteiten voor het bekijken en lezen van documenten toe te voegen aan uw toepassingen om het hele document, gedeeltelijk document, specifiek pagina-/celbereik, individuele documentlaag, met of zonder annotaties en opmerkingen voor de ondersteunde bestandsindelingen weer te geven.
       
      GroupDocs.Viewer voor .NET slaat de gerenderde documenten standaard op in de cache op de lokale schijf. Elk type externe cache-opslag wordt ook ondersteund door de juiste interfaces te implementeren: Amazon S3, Dropbox, Google Drive, Windows Azure, Redis of andere.
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          Hieronder volgt een overzicht van GroupDocs.Viewer voor .NET:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Overzicht"
          content: |
            * Geef meer dan 190 documenttypen weer 
            * Download een bestand in HTML-, Image-, PDF-indeling 
            * Roteren en opnieuw ordenen 
            * Watermerk toepassen 
            * Cache voor snel proces 
            * Voeg aangepaste lettertypen toe 
            * Pas coderingsstandaarden toe 
            * Aangepaste invoergegevensverwerker 
            * Renderen met wijzigingen bijhouden 
            * Renderen als responsieve HTML 
            * Render PDF- en CAD-lagen 
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Viewer voor .NET ondersteunt het bekijken van alle populaire documentbestandsindelingen. Voeg met slechts een paar regels code PDF-viewer, Microsoft Office Word, Excel-spreadsheet, afbeelding, HTML, Outlook e-mail, OneNote, Project en grafische weergavemogelijkheden toe aan uw .NET-toepassingen.

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
                * **Pagina-indelingsbestanden:** PDF, TEX, XPS, OXPS
                * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG, OTG, FODP, FODG
                * **Door scheidingstekens gescheiden waarden:** CSV, TSV
                * **Web:** HTML, MHT, MHTML
                * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
                * **PostScript:** PS, EPS
                * **archieven:** ZIP, TAR, BZ2, GZ, RAR, RAR5
                * **Verscheidene:** OBJ, EPUB, MOBI, DjVu, XML, VCF, VCARD, NUMBERS, NSF

        right:
          enable: true
          table:
            # table loop
            - title: "Afbeeldingen, afbeeldingen en diagrammen"
              content: |
                * **Afbeeldingen:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB
                * **Windows-pictogram:** ICO
                * **Schaalbare vectorafbeeldingen:** SVG, CDR, CMX, IGS, SVGZ
                * **Jpeg2000:** JP2, J2C, J2K, JPC, JPF, JPX, JPM
                * **Adobe Photoshop:** PSD, PSB
                * **Printeropdrachttaal:** PCL
                * **Stereolithografie (3D-printen):** STL
                * **Industrie Basisklassen:** IFC
                * **Medische beeldvorming:** DICOM
                * **Plotter-documenten:** PLT, HPG
                * **Autodesk Design webformaten:** DWF, DWG
                * **AutoCAD-tekening:** DWT, IFC, STL, CF2
                * **ISFF-gebaseerd DGN (V7):** DGN

            # table loop
            - title: "Programmeertalen Formaten"
              content: |
                * **C/C++/C#-bestanden:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
                * **Java/JavaScript-bestanden:** JAVA, JS, JSON, PROPERTIES
                * **Verscheidene:** VB, PHP, SQL, PL, PY, PV, RB, RST, SASS, SCALA, SCM, SCRIPT, AS, AS3, ASM, BAT, CMAKE, CSS, DIFF, ERB, GROOVY, HAML, LESS, LOG, M, MAKE, MD, ML, MM, SH, SML, VIM, YAML

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Viewer voor .NET ondersteunt de volgende besturingssystemen, frameworks en pakketbeheerders:
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Besturingssystemen"
              content: |
                * Microsoft Windows Server 2003 en hoger 
                * Microsoft Windows XP en hoger 
                * Microsoft Windows 10 & 11 
                * Linux (Ubuntu, OpenSUSE, CentOS en anderen) 
                * Mac OS X 

            # table loop
            - icon: "fas fa-code"
              title: "Ondersteunde kaders"
              content: |
                * .NET Framework 2.0 of hoger 
                * .NET Kern 3.1 
                * .NET 5 of hoger 

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-box"
              title: "Pakket manager"
              content: |
                * NuGet

            # table loop
            - icon: "fas fa-tools"
              title: "Ontwikkelomgevingen"
              content: |
                * Microsoft Visual Studio
                * Visual Studio Code
                * .NET CLI

############################# Features ############################
features:
    enable: true
    title: "GroupDocs.Viewer voor .NET-functies"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "Raster documenten en converteer ze naar SVG, HTML en CSS"

      # feature loop
      - icon: "fas fa-eye"
        content: "Converteer tekst naar HTML en geef documenten weer om HTML-, afbeeldings- of PDF-weergave te krijgen"

      # feature loop
      - icon: "fas fa-bolt"
        content: "Snellere laadtijd met behulp van gecachte versies van documenten"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "Converteer presentaties met vormen en tekst met 3D-effecten"

      # feature loop
      - icon: "fas fa-code"
        content: "Codeer Word-, Excel- en e-maildocumenten naar de gewenste coderingsstandaard"

      # feature loop
      - icon: "fas fa-cloud"
        content: "Geef documenten weer die zich op FTP- of cloudopslaglocaties bevinden"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "Lettertypen uitsluiten bij weergave naar HTML om de resulterende bestandsgrootte te verkleinen"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "Verklein CSS- en HTML-uitvoer door opmerkingen, extra witruimten enz. te verwijderen."

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "Lees de tekst in een brondocument via de coördinaten"

      # feature loop
      - icon: "fas fa-border-all"
        content: "Toon/verberg de rasterlijnen van Excel-bladen in uitvoerweergave"

      # feature loop
      - icon: "fas fa-wrench"
        content: "Geef het aantal rijen in een Excel-blad op dat op elke pagina moet worden weergegeven"

      # feature loop
      - icon: "fas fa-columns"
        content: "Negeer lege kolommen bij het weergeven van spreadsheetdocumenten"

      # feature loop
      - icon: "fas fa-file-word"
        content: "Render Word-documenten in HTML-pagina's, afbeeldingen of PDF, met Track Changes"

      # feature loop
      - icon: "fas fa-envelope"
        content: "Geef e-mailbijlagen weer als originele bestanden, afbeeldingen of in HTML-weergave"

      # feature loop
      - icon: "fas fa-print"
        content: "Stel afdrukbeperkingen in voor PDF-documenten"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "Geef inhoud/bestanden in ZIP-archieven weer als bijlagen"

      # feature loop
      - icon: "fas fa-lock"
        content: "Verkrijg bijlagen van met een wachtwoord beveiligde documenten"

      # feature loop
      - icon: "fas fa-file-code"
        content: "Geef bestandsindelingen van programmeertalen weer als platte tekst"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "Pas achtergrondkleuren aan bij het bekijken van CAD-tekeningen"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "Bekijk Excel-documenten en converteer ze naar PDF, HTML, JPG en PNG"

      # feature loop
      - icon: "fas fa-heading"
        content: "Werkbladnamen ophalen uit Excel-bestand - Geef spreadsheetkolomkoppen en rijnummers weer"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "Bekijk en converteer Microsoft Project-documenten met notities"

      # feature loop
      - icon: "fas fa-cube"
        content: "Converteer CAD-tekeningen naar SVG voor een betere kijk- en zoomervaring"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "Kies ervoor om Visio-figuren zonder schema weer te geven"

    more_feature:
      # more_feature_loop
      - title: "Bekijk documenten efficiënt en betrouwbaar"
        content: |
          Met de GroupDocs.Viewer API kunt u meer dan 190 documentindelingen efficiënt en betrouwbaar weergeven met intacte inhoud en documentstructuur. De volgende voorbeeldcode laat zien hoe gemakkelijk het is om de HTML-representatie van een DOCX-document te bekijken:

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
      - title: "Transformatie toepassen op gerenderde uitvoer"
        content: "Met GroupDocs.Viewer for .NET API kunt u verschillende transformaties uitvoeren naar het gerenderde uitvoerdocument. Deze transformatie-opties geven u controle over de manier waarop u de gerenderde uitvoer presenteert voor weergave. De beschikbare transformaties zijn de optie voor het roteren van pagina's, de optie voor opnieuw ordenen van pagina's en het toepassen van tekstwatermerk."

      # more_feature_loop
      - title: "Werken met Outlook-gegevensbestanden"
        content: "GroupDocs.Viewer voor .NET API kan de items in Outlook-gegevensbestanden (OST/PST) weergeven als PDF-, HTML- en afbeeldingsbestanden. Onze Viewer API heeft ook de mogelijkheid om de lijst met mappen in Outlook-gegevensbestanden te verkrijgen. Met GroupDocs.Viewer voor .NET API kunt u de map specificeren die moet worden weergegeven vanuit Outlook-gegevensbestanden. Evenzo kunt u ook e-mailberichten in OST/PST-indeling als bijlagen ontvangen. Met GroupDocs.Viewer voor .NET kunt u ook berichten uit OST/PST-formaten filteren op basis van onderwerp, inhoud of afzender."

      # more_feature_loop
      - title: "Werken met CAD-documenten"
        content: "GroupDocs.Viewer voor .NET API kan modellen en alle niet-lege lay-outs renderen of een specifieke lay-out van een CAD-bestand renderen. GroupDocs.Viewer voor .NET API ondersteunt ook tegelweergave of weergave op coördinaten van CAD-documenten in afbeelding, HTML of PDF. U kunt ook laagstatussen voor CAD-documenten opvragen."

############################# Testimonials ###############################
testimonials:
  enable: true

  testimonial:
    # testimonial item loop
    - name: "Margot Baill"
      designation: "Directeur productontwikkeling bij Hireology"
      content: "Het integreren van GroupDocs.Viewer voor Cloud API was eenvoudig met hun fantastische Ruby SDK. Er zijn niet zoveel bedrijven die bereid zijn om met ons samen te werken aan wat we willen. Het is een geweldige samenwerking."

    # testimonial item loop
    - name: "Mats Oustad"
      designation: "Senior adviseur/partner bij Novanet AS"
      content: "Na het implementeren en gebruiken van GroupDocs.Viewer voor .NET in het project lijkt het erg goed te werken. Ik heb getest met veel documenten en tot nu toe zo goed. Alles wat ik erop heb gegooid, wordt goed weergegeven en ziet er net zo goed uit als in een pdf-viewer of MS Word."
              
    # testimonial item loop
    - name: "Martin Lasarga"
      designation: "Productmanager bij Axentria ECM by G.S.I."
      content: "Prima service en prima producten. Ze waren buitengewoon behulpzaam en reageerden snel tijdens het implementatieproces van GroupDocs.Viewer voor .NET, en kunnen ze niet sterk genoeg aanbevelen."

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Viewer biedt API's voor het bekijken van documenten voor andere populaire ontwikkelomgevingen"

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
