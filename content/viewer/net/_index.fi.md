---
############################# Static ##########################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

lang: fi
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: ".NET Document Viewer API, renderöi PDF Word Excel Image HTML Diagram"
head_description: "C# ASP.NET-tiedostojen katseluohjelma ja renderöintisovellusliittymä. Lisää PDF-katseluohjelma, Word-katseluohjelma, Excel-katseluohjelma, kuvien katseluohjelma, HTML-katseluohjelma ja sähköpostin katseluohjelma .NET-sovelluksiin."

############################# Header ##########################
title: "Renderöi ja näytä asiakirjoja .NET API:n kautta"
description: ".NET Document Viewer API renderöi yli 190 asiakirjamuotoa PDF-, HTML- ja kuvatiedostoiksi tehokkailla määritysvaihtoehdoilla."
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
              text: "Yleiskatsaus"

            # button loop
            - link: "#features"
              text: "ominaisuudet"

            # button loop
            - link: "#support"
              text: "Tuki"

            # button loop
            - link: "https://products.groupdocs.app/viewer/total"
              text: "Live-demo"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Hinnoittelu"

    right:
        link_download: "https://www.nuget.org/packages/GroupDocs.Viewer"
        link_learn: "https://docs.groupdocs.com/viewer/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    content: |
      GroupDocs.Viewer for .NET API auttaa sinua luomaan tehokkaita C#-, ASP.NET- ja muiden .NET-pohjaisten tekniikoiden sovelluksia, jotka voivat hahmontaa ja näyttää asiakirjoja ja kuvia yli 190 tiedostomuodosta ilman ulkoisten ohjelmistojen asentamista. Tiedostojen katselukirjasto rasteroi asiakirjat ja muuntaa ne sitten SVG+HTML+CSS-muotoon optimoidakseen yleisen asiakirjojen renderöintikokemuksen yritysasiakirjojen, kuvien, tekstitiedostojen, kaavioiden, grafiikan, sähköpostin liitteiden ja PDF-tiedostojen katseluun nopeasti, tositeksti- ja korkean tarkkuuden sovelluksissasi. Voit lisätä sovelluksiisi asiakirjan katselu- ja lukutoimintoja, jotka näyttävät koko asiakirjan, osittaisen asiakirjan, tietyn sivu-/solualueen, yksittäisen asiakirjakerroksen, merkinnöillä ja kommenteilla tai ilman niitä tuetuille tiedostomuodoille.
       
      GroupDocs.Viewer for .NET tallentaa renderoidut asiakirjat oletusarvoisesti paikalliselle levylle. Kaiken tyyppistä ulkoista välimuistia tuetaan myös asianmukaisilla käyttöliittymillä - Amazon S3, Dropbox, Google Drive, Windows Azure, Redis tai mikä tahansa muu.
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          Seuraavassa on yleiskatsaus GroupDocs.Viewer for .NET:iin:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Yleiskatsaus"
          content: |
            * Näytä yli 190 asiakirjatyyppiä 
            * Hanki tiedosto HTML-, kuva- tai PDF-muodossa 
            * Kierrä & Järjestä uudelleen 
            * Käytä vesileimaa 
            * Välimuisti nopeaa prosessia varten 
            * Lisää mukautettuja kirjasimia 
            * Käytä koodausstandardeja 
            * Custom Input Data Handler 
            * Renderöi muutoksilla 
            * Renderöi responsiivisena HTML-muotona 
            * Renderöi PDF- ja CAD-tasot 
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Viewer for .NET tukee kaikkien suosittujen asiakirjatiedostomuotojen katselua. Muutamalla koodirivillä voit lisätä PDF-katseluohjelman, Microsoft Office Wordin, Excel-laskentataulukon, kuvan, HTML:n, Outlook-sähköpostin, OneNoten, projektin ja grafiikan katseluominaisuudet .NET-sovelluksiin.

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
                * **Sivun asettelutiedostot:** PDF, TEX, XPS, OXPS
                * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG, OTG, FODP, FODG
                * **Erotinmerkityt arvot:** CSV, TSV
                * **Web:** HTML, MHT, MHTML
                * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
                * **PostScript:** PS, EPS
                * **Arkistot:** ZIP, TAR, BZ2, GZ, RAR, RAR5
                * **Eri:** OBJ, EPUB, MOBI, DjVu, XML, VCF, VCARD, NUMBERS, NSF

        right:
          enable: true
          table:
            # table loop
            - title: "Kuvia, grafiikkaa ja kaavioita"
              content: |
                * **Kuvat:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB
                * **Windows-kuvake:** ICO
                * **Skaalautuva vektorigrafiikka:** SVG, CDR, CMX, IGS, SVGZ
                * **Jpeg 2000:** JP2, J2C, J2K, JPC, JPF, JPX, JPM
                * **Adobe Photoshop:** PSD, PSB
                * **Tulostimen komentokieli:** PCL
                * **Stereolitografia (3D-tulostus):** STL
                * **Teollisuuden peruskurssit:** IFC
                * **Lääketieteellinen kuvantaminen:** DICOM
                * **Piirturi-asiakirjat:** PLT, HPG
                * **Autodesk Design Web Formats:** DWF, DWG
                * **AutoCAD-piirustus:** DWT, IFC, STL, CF2
                * **ISFF-pohjainen DGN (V7):** DGN

            # table loop
            - title: "Ohjelmointikielen muodot"
              content: |
                * **C/C++/C#-tiedostot:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
                * **Java/JavaScript-tiedostot:** JAVA, JS, JSON, PROPERTIES
                * **Eri:** VB, PHP, SQL, PL, PY, PV, RB, RST, SASS, SCALA, SCM, SCRIPT, AS, AS3, ASM, BAT, CMAKE, CSS, DIFF, ERB, GROOVY, HAML, LESS, LOG, M, MAKE, MD, ML, MM, SH, SML, VIM, YAML

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Viewer for .NET tukee seuraavia käyttöjärjestelmiä, kehyksiä ja paketinhallintaohjelmia:
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Käyttöjärjestelmät"
              content: |
                * Microsoft Windows Server 2003 ja uudemmat 
                * Microsoft Windows XP ja uudemmat 
                * Microsoft Windows 10 ja 11 
                * Linux (Ubuntu, OpenSUSE, CentOS ja muut) 
                * Mac-käyttöjärjestelmän kymmenes versio 

            # table loop
            - icon: "fas fa-code"
              title: "Tuetut puitteet"
              content: |
                * .NET Framework 2.0 tai uudempi 
                * .NET Core 3.1 
                * .NET 5 tai uudempi 

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-box"
              title: "Paketinhallinta"
              content: |
                * NuGet

            # table loop
            - icon: "fas fa-tools"
              title: "Kehitysympäristöt"
              content: |
                * Microsoft Visual Studio
                * Visual Studio Code
                * .NET CLI

############################# Features ############################
features:
    enable: true
    title: "GroupDocs.Viewer .NET-ominaisuuksille"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "Rasteroi asiakirjat ja muunna ne SVG-, HTML- ja CSS-muotoon"

      # feature loop
      - icon: "fas fa-eye"
        content: "Muunna teksti HTML-muotoon ja renderöi asiakirjoja saadaksesi HTML-, kuva- tai PDF-esityksen"

      # feature loop
      - icon: "fas fa-bolt"
        content: "Nopeampi latausaika asiakirjojen välimuistiversioiden avulla"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "Muunna esityksiä muodoilla ja tekstillä 3D-tehosteilla"

      # feature loop
      - icon: "fas fa-code"
        content: "Koodaa Word-, Excel- ja sähköpostiasiakirjat haluttuun koodausstandardiin"

      # feature loop
      - icon: "fas fa-cloud"
        content: "Renderöi FTP- tai pilvitallennuspaikoissa sijaitsevat asiakirjat"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "Kirjasimien poissulkeminen HTML-muodossa renderöidessään tuloksena olevan tiedoston koon pienentämiseksi"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "Pienennä CSS- ja HTML-ulostuloa poistamalla kommentit, ylimääräiset välilyönnit jne."

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "Lue lähdeasiakirjassa oleva teksti sen koordinaattien kautta"

      # feature loop
      - icon: "fas fa-border-all"
        content: "Näytä/piilota Excel-arkkien ruudukkoviivat tulosteen esityksessä"

      # feature loop
      - icon: "fas fa-wrench"
        content: "Määritä kullekin sivulle hahmonnettavien Excel-taulukon rivien määrä"

      # feature loop
      - icon: "fas fa-columns"
        content: "Ohita tyhjät sarakkeet renderöidessäsi laskentataulukkoasiakirjoja"

      # feature loop
      - icon: "fas fa-file-word"
        content: "Renderöi Word-asiakirjat HTML-sivuiksi, kuviksi tai PDF-tiedostoiksi seuraamalla muutoksia"

      # feature loop
      - icon: "fas fa-envelope"
        content: "Renderöi sähköpostin liitteet alkuperäisinä tiedostoina, kuvina tai HTML-muodossa"

      # feature loop
      - icon: "fas fa-print"
        content: "Aseta tulostusrajoitukset PDF-dokumenteille"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "Renderöi ZIP-arkistojen sisältö/tiedostot liitteinä"

      # feature loop
      - icon: "fas fa-lock"
        content: "Hanki liitteitä salasanalla suojatuista asiakirjoista"

      # feature loop
      - icon: "fas fa-file-code"
        content: "Renderöi ohjelmointikielten tiedostomuodot pelkkänä tekstinä"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "Säädä taustavärejä katsellessasi CAD-piirustuksia"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "Tarkastele Excel-dokumentteja ja muunna PDF-, HTML-, JPG- ja PNG-muotoon"

      # feature loop
      - icon: "fas fa-heading"
        content: "Hanki laskentataulukoiden nimet Excel-tiedostosta – Näytä laskentataulukon sarakkeiden otsikot ja rivinumerot"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "Tarkastele ja muunna Microsoft Project -asiakirjoja muistiinpanojen avulla"

      # feature loop
      - icon: "fas fa-cube"
        content: "Muunna CAD-piirustukset SVG-muotoon parantaaksesi katselu- ja zoomauskokemusta"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "Valitse renderöidä Visio-kuviot ilman kaaviota"

    more_feature:
      # more_feature_loop
      - title: "Tarkastele asiakirjoja tehokkaasti ja luotettavasti"
        content: |
          GroupDocs.Viewer API:n avulla voit näyttää yli 190 asiakirjamuotoa tehokkaasti ja luotettavasti sisällön ja dokumenttirakenteen eheyden ollessa ennallaan. Seuraava esimerkkikoodi osoittaa, kuinka helppoa on tarkastella DOCX-asiakirjan HTML-esitystä:

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
      - title: "Käytä muunnosta renderöityyn ulostuloon"
        content: "Voit tehdä erilaisia ​​muunnoksia renderoidulle tulosteasiakirjalle GroupDocs.Viewer for .NET API:n avulla. Nämä muunnosvaihtoehdot antavat sinun hallita tapaa, jolla esität renderoidun tulosteen näyttöä varten. Käytettävissä olevat muunnokset ovat sivun kiertovaihtoehto, sivujen uudelleenjärjestelyvaihtoehto ja tekstin vesileiman käyttö."

      # more_feature_loop
      - title: "Työskentely Outlookin datatiedostojen kanssa"
        content: "GroupDocs.Viewer for .NET API voi hahmontaa Outlook Data Files (OST/PST) -tiedostot PDF-, HTML- ja kuvatiedostoina. Viewer-sovellusliittymällämme on myös mahdollisuus hankkia Outlook Data Files -tiedostojen sisältämät kansiot. GroupDocs.Viewer for .NET API:n avulla voit määrittää kansion, joka hahmonnetaan Outlook Data Files -tiedostoista. Voit myös saada liitteinä OST/PST-muodossa olevia sähköpostiviestejä. GroupDocs.Viewer for .NET mahdollistaa myös viestien suodattamisen OST/PST-muodoista aiheen, sisällön tai lähettäjän perusteella."

      # more_feature_loop
      - title: "Työskentely CAD-dokumenttien kanssa"
        content: "GroupDocs.Viewer for .NET API voi renderöidä mallin ja kaikki ei-tyhjät asettelut tai tehdä tietyn asettelun CAD-tiedostosta. GroupDocs.Viewer for .NET API tukee myös laatoitettua renderöintiä tai CAD-asiakirjojen koordinaattien hahmontamista kuvaksi, HTML- tai PDF-muotoon. Voit myös saada CAD-dokumenttien tasotilat."

############################# Testimonials ###############################
testimonials:
  enable: true

  testimonial:
    # testimonial item loop
    - name: "Margot Baill"
      designation: "Hireologyn tuotekehitysjohtaja"
      content: "GroupDocs.Viewer for Cloud API -sovellusliittymän integrointi oli helppoa heidän fantastisella Ruby SDK:lla. Siellä ei ole niin monia yrityksiä, jotka ovat valmiita työskentelemään kanssamme sen suhteen, mitä haluamme. Se on hieno kumppanuus."

    # testimonial item loop
    - name: "Mats Oustad"
      designation: "Novanet AS:n vanhempi konsultti/kumppani"
      content: "Kun GroupDocs.Viewer for .NET on otettu käyttöön ja käytetty projektissa, se näyttää toimivan erittäin hyvin. Olen testannut monilla asiakirjoilla ja toistaiseksi hyvin. Kaikki, mitä olen heittänyt siihen, näkyy kauniisti ja näyttää yhtä hyvältä kuin PDF-katseluohjelmassa tai MS Wordissa."
              
    # testimonial item loop
    - name: "Martin Lasarga"
      designation: "Axentria ECM:n tuotepäällikkö, G.S.I."
      content: "Erinomainen palvelu ja erinomaiset tuotteet. He olivat erittäin avuliaita ja reagoivia GroupDocs.Viewer for .NET -toteutusprosessin aikana, en voi suositella niitä tarpeeksi."

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Viewer tarjoaa asiakirjojen katselusovellusliittymiä muihin suosittuihin kehitysympäristöihin"

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
