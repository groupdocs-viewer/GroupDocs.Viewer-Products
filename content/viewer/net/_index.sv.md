---
############################# Static ##########################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

lang: sv
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: ".NET Document Viewer API, Render PDF Word Excel Image HTML Diagram"
head_description: "C# ASP.NET filvisare och renderings-API. Lägg till PDF-visare, Word-visare, Excel-läsare, bildvisare, HTML-visare, e-postvisare i .NET-appar."

############################# Header ##########################
title: "Rendera och visa dokument via .NET API"
description: ".NET Document Viewer API för att återge 190+ dokumentformat till PDF, HTML och bild med kraftfulla konfigurationsalternativ."
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
              text: "Översikt"

            # button loop
            - link: "#features"
              text: "Funktioner"

            # button loop
            - link: "#support"
              text: "Stöd"

            # button loop
            - link: "https://products.groupdocs.app/viewer/total"
              text: "Live-demo"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Prissättning"

    right:
        link_download: "https://www.nuget.org/packages/GroupDocs.Viewer"
        link_learn: "https://docs.groupdocs.com/viewer/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    content: |
      GroupDocs.Viewer för .NET API:er hjälper dig att skapa kraftfulla applikationer i C#, ASP.NET och andra .NET-baserade teknologier, som kan rendera och visa dokument och bilder av 190+ filformat utan att installera någon extern programvara. Filvisningsbiblioteket rastrar dokumenten och konverterar dem sedan till SVG+HTML+CSS för att optimera den övergripande dokumentåtergivningsupplevelsen för visning av affärsdokument, bilder, textfiler, diagram, grafik, e-postbilagor och PDF-filer med snabbhet, sann text och högtrohet i dina applikationer. Du har möjlighet att lägga till dokumentvisnings- och läsfunktioner i dina applikationer för att visa hela dokumentet, deldokument, specifikt sid-/cellintervall, individuellt dokumentlager, med eller utan anteckningar och kommentarer för de filformat som stöds.
       
      GroupDocs.Viewer för .NET cachar de renderade dokumenten som matas ut till den lokala disken som standard. Alla typer av extern cachelagring stöds också genom att implementera lämpliga gränssnitt – Amazon S3, Dropbox, Google Drive, Windows Azure, Redis eller något annat.
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          Följande är en översikt över GroupDocs.Viewer för .NET:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Översikt"
          content: |
            * Visa 190+ dokumenttyper 
            * Hämta en fil i HTML, Bild, PDF-format 
            * Rotera och ändra ordning 
            * Applicera vattenstämpel 
            * Cache för snabb process 
            * Lägg till anpassade teckensnitt 
            * Tillämpa kodningsstandarder 
            * Anpassad indatahanterare 
            * Rendera med spårändringar 
            * Rendera som responsiv HTML 
            * Återge PDF- och CAD-lager 
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Viewer för .NET stöder visning av alla populära dokumentfilformat. Med bara några rader kod kan du lägga till PDF-läsare, Microsoft Office Word, Excel-kalkylblad, bild, HTML, e-post i Outlook, OneNote, projekt och grafikvisning i dina .NET-program.

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
                * **Sidlayoutfiler:** PDF, TEX, XPS, OXPS
                * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG, OTG, FODP, FODG
                * **Avgränsare-separerade värden:** CSV, TSV
                * **webb:** HTML, MHT, MHTML
                * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
                * **PostScript:** PS, EPS
                * **Arkiv:** ZIP, TAR, BZ2, GZ, RAR, RAR5
                * **Olika:** OBJ, EPUB, MOBI, DjVu, XML, VCF, VCARD, NUMBERS, NSF

        right:
          enable: true
          table:
            # table loop
            - title: "Bilder, grafik & diagram"
              content: |
                * **Bilder:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB
                * **Windows-ikon:** ICO
                * **Skalbar vektorgrafik:** SVG, CDR, CMX, IGS, SVGZ
                * **Jpeg2000:** JP2, J2C, J2K, JPC, JPF, JPX, JPM
                * **Adobe Photoshop:** PSD, PSB
                * **Skrivarkommandospråk:** PCL
                * **Stereolitografi (3D-utskrift):** STL
                * **Industry Foundation-klasser:** IFC
                * **Medicinsk bildbehandling:** DICOM
                * **Plotterdokument:** PLT, HPG
                * **Autodesk Design webbformat:** DWF, DWG
                * **AutoCAD-ritning:** DWT, IFC, STL, CF2
                * **ISFF-baserad DGN (V7):** DGN

            # table loop
            - title: "Programmeringsspråksformat"
              content: |
                * **C/C++/C#-filer:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
                * **Java/JavaScript-filer:** JAVA, JS, JSON, PROPERTIES
                * **Olika:** VB, PHP, SQL, PL, PY, PV, RB, RST, SASS, SCALA, SCM, SCRIPT, AS, AS3, ASM, BAT, CMAKE, CSS, DIFF, ERB, GROOVY, HAML, LESS, LOG, M, MAKE, MD, ML, MM, SH, SML, VIM, YAML

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Viewer för .NET stöder följande operativsystem, ramverk och pakethanterare:
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Operativsystem"
              content: |
                * Microsoft Windows Server 2003 och senare 
                * Microsoft Windows XP och senare 
                * Microsoft Windows 10 och 11 
                * Linux (Ubuntu, OpenSUSE, CentOS och andra) 
                * Mac OS X 

            # table loop
            - icon: "fas fa-code"
              title: "Ramar som stöds"
              content: |
                * .NET Framework 2.0 eller senare 
                * .NET Core 3.1 
                * .NET 5 eller högre 

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-box"
              title: "Pakethanterare"
              content: |
                * NuGet

            # table loop
            - icon: "fas fa-tools"
              title: "Utvecklingsmiljöer"
              content: |
                * Microsoft Visual Studio
                * Visual Studio Code
                * .NET CLI

############################# Features ############################
features:
    enable: true
    title: "GroupDocs.Viewer för .NET-funktioner"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "Rasterisera dokument och konvertera dem till SVG, HTML och CSS"

      # feature loop
      - icon: "fas fa-eye"
        content: "Konvertera text till HTML och rendera dokument för att få HTML-, bild- eller PDF-representation"

      # feature loop
      - icon: "fas fa-bolt"
        content: "Snabbare laddningstid med hjälp av cachade versioner av dokument"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "Konvertera presentationer med former och text med 3D-effekter"

      # feature loop
      - icon: "fas fa-code"
        content: "Koda Word, Excel och e-postdokument till önskad kodningsstandard"

      # feature loop
      - icon: "fas fa-cloud"
        content: "Återge dokument som finns på FTP- eller molnlagringsplatser"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "Uteslut teckensnitt vid rendering till HTML för att minska den resulterande filstorleken"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "Förminska CSS- och HTML-utdata genom att ta bort kommentarer, extra blanksteg etc."

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "Läs texten i ett källdokument genom dess koordinater"

      # feature loop
      - icon: "fas fa-border-all"
        content: "Visa/dölj rutnätslinjerna i Excel-ark i utdatarepresentation"

      # feature loop
      - icon: "fas fa-wrench"
        content: "Ange antalet rader i ett Excel-ark som ska renderas på varje sida"

      # feature loop
      - icon: "fas fa-columns"
        content: "Ignorera tomma kolumner när du renderar kalkylarksdokument"

      # feature loop
      - icon: "fas fa-file-word"
        content: "Återge Word-dokument till HTML-sidor, bilder eller PDF, med spåra ändringar"

      # feature loop
      - icon: "fas fa-envelope"
        content: "Återge e-postbilagor som originalfiler, bilder eller i HTML-representation"

      # feature loop
      - icon: "fas fa-print"
        content: "Ställ in utskriftsbegränsningar för PDF-dokument"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "Återge innehåll/filer som finns i ZIP-arkiv som bilagor"

      # feature loop
      - icon: "fas fa-lock"
        content: "Skaffa bilagor från lösenordsskyddade dokument"

      # feature loop
      - icon: "fas fa-file-code"
        content: "Återge filformat för programmeringsspråk som vanlig text"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "Justera bakgrundsfärger när du tittar på CAD-ritningar"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "Visa Excel-dokument och konvertera till PDF, HTML, JPG och PNG"

      # feature loop
      - icon: "fas fa-heading"
        content: "Hämta kalkylbladsnamn från Excel-fil – Visa kalkylbladskolumnrubriker och radnummer"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "Visa och konvertera Microsoft Project-dokument med anteckningar"

      # feature loop
      - icon: "fas fa-cube"
        content: "Konvertera CAD-ritningar till SVG för bättre visnings- och zoomupplevelse"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "Välj att rendera Visio-figurer utan schema"

    more_feature:
      # more_feature_loop
      - title: "Visa dokument effektivt och tillförlitligt"
        content: |
          Med hjälp av GroupDocs.Viewer API kan du visa mer än 190 dokumentformat effektivt och tillförlitligt med innehåll och dokumentstruktur intakt. Följande exempelkod visar hur lätt det är att se HTML-representation av ett DOCX-dokument:

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
      - title: "Tillämpa transformation på renderad utdata"
        content: "Du kan utföra olika transformationer av det renderade utdatadokumentet med hjälp av GroupDocs.Viewer för .NET API. Dessa transformationsalternativ ger dig kontroll över hur du presenterar den renderade utdata för visning. De tillgängliga transformationerna är alternativ för sidrotation, alternativ för omordning av sidor och applicering av textvattenstämpel."

      # more_feature_loop
      - title: "Arbeta med Outlook-datafiler"
        content: "GroupDocs.Viewer för .NET API kan rendera objekten i Outlook-datafiler (OST/PST) som PDF-, HTML- och bildfiler. Vårt Viewer API har också möjlighet att få listan över mappar som finns i Outlook-datafiler. Med GroupDocs.Viewer för .NET API kan du ange vilken mapp som ska renderas från Outlook-datafiler. På samma sätt kan du också få e-postmeddelanden i OST/PST-format som bilagor. Med GroupDocs.Viewer för .NET kan du också filtrera meddelanden från OST/PST-format baserat på ämne, innehåll eller avsändare."

      # more_feature_loop
      - title: "Arbeta med CAD-dokument"
        content: "GroupDocs.Viewer för .NET API kan rendera modell och alla icke-tomma layouter eller rendera en specifik layout av en CAD-fil. GroupDocs.Viewer för .NET API stöder också sida vid rendering eller rendering av koordinater för CAD-dokument till bild, HTML eller PDF. Du kan också få lagerstatus för CAD-dokument."

############################# Testimonials ###############################
testimonials:
  enable: true

  testimonial:
    # testimonial item loop
    - name: "Margot Baill"
      designation: "Produktutvecklingschef på Hireology"
      content: "Att integrera GroupDocs.Viewer för Cloud API var enkelt med deras fantastiska Ruby SDK. Det finns inte så många företag där ute som är villiga att jobba med oss ​​på det vi vill. Det är ett fantastiskt samarbete."

    # testimonial item loop
    - name: "Mats Oustad"
      designation: "Seniorkonsult/Partner på Novanet AS"
      content: "Efter att ha implementerat och använt GroupDocs.Viewer för .NET i projektet ser det ut att fungera mycket bra. Jag har testat med en hel del dokument och än så länge så bra. Allt jag har kastat på den återges snyggt och ser lika bra ut som det skulle göra i en PDF-visare eller MS Word."
              
    # testimonial item loop
    - name: "Martin Lasarga"
      designation: "Produktchef på Axentria ECM by G.S.I."
      content: "Utmärkt service och utmärkta produkter. De var extremt hjälpsamma och lyhörda under implementeringsprocessen för GroupDocs.Viewer för .NET, kan inte rekommendera dem tillräckligt starkt."

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Viewer erbjuder API:er för dokumentvisning för andra populära utvecklingsmiljöer"

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
