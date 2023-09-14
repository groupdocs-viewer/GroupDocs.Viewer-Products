---
############################# Static ##########################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

lang: hu
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: ".NET Document Viewer API, Render PDF Word Excel Image HTML Diagram"
head_description: "C# ASP.NET fájlnézegető és renderelő API. PDF-nézegető, Word-nézegető, Excel-nézegető, Képnézegető, HTML-nézegető és E-mail-nézegető funkciók hozzáadása a .NET-alkalmazásokhoz."

############################# Header ##########################
title: "Rendereljen és jelenítsen meg dokumentumokat .NET API-n keresztül"
description: ".NET Document Viewer API több mint 190 dokumentumformátum renderelésére PDF, HTML és kép formátumban, hatékony konfigurációs lehetőségekkel."
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
              text: "Áttekintés"

            # button loop
            - link: "#features"
              text: "Jellemzők"

            # button loop
            - link: "#support"
              text: "Támogatás"

            # button loop
            - link: "https://products.groupdocs.app/viewer/total"
              text: "Élő Demo"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Árazás"

    right:
        link_download: "https://www.nuget.org/packages/GroupDocs.Viewer"
        link_learn: "https://docs.groupdocs.com/viewer/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    content: |
      A GroupDocs.Viewer for .NET API-k segítségével hatékony alkalmazásokat hozhat létre C#-ban, ASP.NET-ben és más .NET-alapú technológiákban, amelyek külső szoftver telepítése nélkül is képesek megjeleníteni és megjeleníteni több mint 190 fájlformátum dokumentumait és képeit. A fájlnézegető könyvtár raszterizálja a dokumentumokat, majd SVG+HTML+CSS formátumba konvertálja azokat, hogy optimalizálja az általános dokumentummegjelenítési élményt az üzleti dokumentumok, képek, szöveges fájlok, diagramok, grafikák, e-mail mellékletek és PDF fájlok gyors, valódi szöveges és nagy pontosság az alkalmazásokon belül. Lehetősége van arra, hogy az alkalmazásokban dokumentummegtekintési és -olvasási funkciókat adjon hozzá a teljes dokumentum, részdokumentum, adott oldal/cellatartomány, egyedi dokumentumréteg megjelenítéséhez, megjegyzésekkel és megjegyzésekkel vagy anélkül a támogatott fájlformátumokhoz.
       
      A GroupDocs.Viewer for .NET alapértelmezés szerint gyorsítótárazza a megjelenített dokumentumok kimenetét a helyi lemezre. Bármilyen típusú külső gyorsítótárat is támogat a megfelelő interfészek megvalósítása – Amazon S3, Dropbox, Google Drive, Windows Azure, Redis vagy bármely más.
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          Az alábbiakban a GroupDocs.Viewer for .NET áttekintése látható:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Áttekintés"
          content: |
            * 190+ dokumentumtípus megjelenítése 
            * Szerezzen be egy fájlt HTML, kép vagy PDF formátumban 
            * Forgatás és átrendezés 
            * Vízjel alkalmazása 
            * Gyorsítótár a gyors folyamatokhoz 
            * Egyéni betűtípusok hozzáadása 
            * Alkalmazza a kódolási szabványokat 
            * Egyedi bemeneti adatkezelő 
            * Renderelje meg a Változások követésével 
            * Rendereljen reszponzív HTML-ként 
            * Rendereljen PDF és CAD rétegeket 
      
      ## TAB TWO ##
      tab_two:
        description: |
          A GroupDocs.Viewer for .NET támogatja az összes népszerű dokumentumfájl-formátum megtekintését. Néhány sornyi kóddal PDF-megtekintőt, Microsoft Office Word-t, Excel-táblázatot, képet, HTML-t, Outlook-e-mailt, OneNote-ot, projekt- és grafikamegtekintési lehetőségeket ad hozzá .NET-alkalmazásaihoz.

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
                * **Oldalelrendezés fájlok:** PDF, TEX, XPS, OXPS
                * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG, OTG, FODP, FODG
                * **Határolójelekkel elválasztott értékek:** CSV, TSV
                * **Web:** HTML, MHT, MHTML
                * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
                * **PostScript:** PS, EPS
                * **Levéltár:** ZIP, TAR, BZ2, GZ, RAR, RAR5
                * **Különféle:** OBJ, EPUB, MOBI, DjVu, XML, VCF, VCARD, NUMBERS, NSF

        right:
          enable: true
          table:
            # table loop
            - title: "Képek, grafika és diagramok"
              content: |
                * **Képek:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB
                * **Windows ikon:** ICO
                * **Skálázható vektorgrafika:** SVG, CDR, CMX, IGS, SVGZ
                * **Jpeg 2000:** JP2, J2C, J2K, JPC, JPF, JPX, JPM
                * **Adobe Photoshop:** PSD, PSB
                * **Nyomtató parancsnyelve:** PCL
                * **Sztereó litográfia (3D nyomtatás):** STL
                * **Ipari alapozó órák:** IFC
                * **Orvosi képalkotás:** DICOM
                * **Plotter dokumentumok:** PLT, HPG
                * **Autodesk Design webformátumok:** DWF, DWG
                * **AutoCAD rajz:** DWT, IFC, STL, CF2
                * **ISFF-alapú DGN (V7):** DGN

            # table loop
            - title: "Programozási nyelvek formátumai"
              content: |
                * **C/C++/C# fájlok:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
                * **Java/JavaScript fájlok:** JAVA, JS, JSON, PROPERTIES
                * **Különféle:** VB, PHP, SQL, PL, PY, PV, RB, RST, SASS, SCALA, SCM, SCRIPT, AS, AS3, ASM, BAT, CMAKE, CSS, DIFF, ERB, GROOVY, HAML, LESS, LOG, M, MAKE, MD, ML, MM, SH, SML, VIM, YAML

      ## TAB THREE ##
      tab_three:
        description: |
          A GroupDocs.Viewer for .NET a következő operációs rendszereket, keretrendszereket és csomagkezelőket támogatja:
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Operációs rendszer"
              content: |
                * Microsoft Windows Server 2003 és újabb 
                * Microsoft Windows XP és újabb 
                * Microsoft Windows 10 és 11 
                * Linux (Ubuntu, OpenSUSE, CentOS és mások) 
                * Mac OS X 

            # table loop
            - icon: "fas fa-code"
              title: "Támogatott keretrendszerek"
              content: |
                * .NET Framework 2.0 vagy újabb 
                * .NET Core 3.1 
                * .NET 5 vagy újabb 

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-box"
              title: "Csomagkezelő"
              content: |
                * NuGet

            # table loop
            - icon: "fas fa-tools"
              title: "Fejlesztési környezetek"
              content: |
                * Microsoft Visual Studio
                * Visual Studio Code
                * .NET CLI

############################# Features ############################
features:
    enable: true
    title: "GroupDocs.Viewer .NET-szolgáltatásokhoz"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "Raszterizálja a dokumentumokat, és konvertálja őket SVG, HTML és CSS formátumba"

      # feature loop
      - icon: "fas fa-eye"
        content: "Konvertálja a szöveget HTML-be, és renderelje le a dokumentumokat HTML, kép vagy PDF megjelenítéshez"

      # feature loop
      - icon: "fas fa-bolt"
        content: "Gyorsabb betöltési idő a dokumentumok gyorsítótárazott verzióinak használatával"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "Konvertálja a prezentációkat alakzatokkal és szöveggel 3D effektusokkal"

      # feature loop
      - icon: "fas fa-code"
        content: "Word, Excel és e-mail dokumentumok kódolása a kívánt kódolási szabvány szerint"

      # feature loop
      - icon: "fas fa-cloud"
        content: "Rendereljen le FTP- vagy felhőtárhelyen található dokumentumokat"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "Betűtípusok kizárása HTML-be való rendereléskor az eredményfájl méretének csökkentése érdekében"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "CSS- és HTML-kimenet csökkentése megjegyzések, extra szóközök stb. eltávolításával."

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "Olvassa el a forrásdokumentumban található szöveget a koordinátáin keresztül"

      # feature loop
      - icon: "fas fa-border-all"
        content: "Excel-lapok rácsvonalainak megjelenítése/elrejtése a kimeneti megjelenítésben"

      # feature loop
      - icon: "fas fa-wrench"
        content: "Adja meg az egyes oldalakon megjelenítendő sorok számát egy Excel-lapon"

      # feature loop
      - icon: "fas fa-columns"
        content: "Az üres oszlopok figyelmen kívül hagyása a táblázatos dokumentumok megjelenítése közben"

      # feature loop
      - icon: "fas fa-file-word"
        content: "Renderelje le a Word-dokumentumokat HTML-oldalakká, képekké vagy PDF-formátumba a Változások követésével"

      # feature loop
      - icon: "fas fa-envelope"
        content: "Renderelje le az e-mail mellékleteket eredeti fájlként, képként vagy HTML-formátumban"

      # feature loop
      - icon: "fas fa-print"
        content: "Nyomtatási korlátozások beállítása PDF dokumentumokra"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "A ZIP-archívumban található tartalmat/fájlokat csatolmányként jelenítse meg"

      # feature loop
      - icon: "fas fa-lock"
        content: "Mellékletek beszerzése jelszóval védett dokumentumokból"

      # feature loop
      - icon: "fas fa-file-code"
        content: "A programozási nyelvek fájlformátumainak megjelenítése egyszerű szövegként"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "Állítsa be a háttérszíneket CAD-rajzok megtekintésekor"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "Tekintse meg az Excel dokumentumokat, és konvertálja PDF, HTML, JPG és PNG formátumba"

      # feature loop
      - icon: "fas fa-heading"
        content: "Munkalapnevek lekérése Excel fájlból – Táblázat oszlopfejléceinek és sorszámainak megjelenítése"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "Microsoft Project dokumentumok megtekintése és konvertálása a jegyzetekkel"

      # feature loop
      - icon: "fas fa-cube"
        content: "Konvertálja a CAD-rajzokat SVG-vé a jobb megtekintési és nagyítási élmény érdekében"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "Válassza a Visio-figurák séma nélküli renderelését"

    more_feature:
      # more_feature_loop
      - title: "Tekintse meg a dokumentumokat hatékonyan és megbízhatóan"
        content: |
          A GroupDocs.Viewer API használatával több mint 190 dokumentumformátumot jeleníthet meg hatékonyan és megbízhatóan, a tartalom és a dokumentumstruktúra sértetlensége mellett. A következő mintakód megmutatja, hogy milyen egyszerű egy DOCX-dokumentum HTML-ábrázolása:

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
      - title: "Alkalmazza az átalakítást a renderelt kimenetre"
        content: "Különféle átalakításokat hajthat végre a megjelenített kimeneti dokumentumon a GroupDocs.Viewer for .NET API használatával. Ezekkel az átalakítási beállításokkal szabályozhatja a renderelt kimenet megjelenítési módját. A rendelkezésre álló átalakítások a következők: oldalforgatás, oldal-újrarendezési lehetőség és szöveges vízjel alkalmazása."

      # more_feature_loop
      - title: "Outlook Data Files használata"
        content: "A GroupDocs.Viewer for .NET API képes megjeleníteni az Outlook Data Files (OST/PST) elemeit PDF, HTML és képfájlokként. A Viewer API-nk emellett képes lekérni az Outlook Data Files-ban található mappák listáját. A GroupDocs.Viewer for .NET API használatával megadhatja az Outlook adatfájlokból megjelenítendő mappát. Hasonlóképpen, az OST/PST formátumú e-mail üzeneteket is megkaphatja mellékletként. A GroupDocs.Viewer for .NET lehetővé teszi az üzenetek szűrését OST/PST formátumokból tárgy, tartalom vagy feladó alapján."

      # more_feature_loop
      - title: "Munka CAD dokumentumokkal"
        content: "A GroupDocs.Viewer for .NET API képes megjeleníteni a modellt és az összes nem üres elrendezést, vagy egy adott CAD-fájl elrendezését. A GroupDocs.Viewer for .NET API támogatja a csempézett renderelést vagy a CAD-dokumentumok koordinátái alapján történő megjelenítését képpé, HTML-be vagy PDF-be. A CAD-dokumentumok rétegállapotait is lekérheti."

############################# Testimonials ###############################
testimonials:
  enable: true

  testimonial:
    # testimonial item loop
    - name: "Margot Baill"
      designation: "A Hireology termékfejlesztési igazgatója"
      content: "A GroupDocs.Viewer for Cloud API integrálása egyszerű volt a fantasztikus Ruby SDK segítségével. Nincs olyan sok cég, amely hajlandó lenne velünk dolgozni azon, amit szeretnénk. Ez egy nagyszerű partnerség."

    # testimonial item loop
    - name: "Mats Oustad"
      designation: "A Novanet AS vezető tanácsadója/partnere"
      content: "A GroupDocs.Viewer for .NET projektben történő megvalósítása és használata után úgy tűnik, hogy nagyon jól működik. Rengeteg dokumentummal teszteltem és eddig jó. Minden, amit rádobtam, szépen renderel, és ugyanolyan jól néz ki, mint egy PDF-nézegetőben vagy MS Word-ben."
              
    # testimonial item loop
    - name: "Martin Lasarga"
      designation: "Az Axentria ECM termékmenedzsere, G.S.I."
      content: "Kiváló kiszolgálás és kiváló termékek. Rendkívül segítőkészek és készségesek voltak a GroupDocs.Viewer for .NET megvalósítási folyamata során, nem tudom őket eléggé ajánlani."

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "A GroupDocs.Viewer dokumentummegtekintési API-kat kínál más népszerű fejlesztői környezetekhez"

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
