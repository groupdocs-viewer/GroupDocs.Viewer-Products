---
############################# Static ############################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

product: "Viewer"
product_tag: "viewer"
platform: "Java"
platform_tag: "java"

############################# Drop-down ############################
supported_platforms:
  items:
    # supported_platforms loop
    - title: ".NET"
      tag: "net"
    # supported_platforms loop
    - title: "Java"
      tag: "java"
    # supported_platforms loop
    - title: "Node.js"
      tag: "nodejs-java" 


############################# Head ############################
head_title: "Java Document Viewer API, PDF Word Excel kép HTML diagram megjelenítése"
head_description: "Document Viewer könyvtár Java alkalmazások fejlesztéséhez, amelyek natív módon jelenítenek meg, tekintenek meg és kezelnek több formátumú dokumentumokat, amelyek több mint 180 fájlformátumot támogatnak."

############################# Header ############################
title: "Rendereljen és jelenítsen meg dokumentumokat<br>Java API használatával"
description: "Hatékony Viewer API több mint 180 dokumentumformátum megjelenítéséhez PDF, HTML és kép formátumban, sokoldalú konfigurációs lehetőségekkel."
words:
  for: "for"

actions:
  main: "Ingyenes Maven letöltés"
  main_link: "https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-viewer/"
  alt: "Engedélyezés"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/java"
  title: "Készen áll az indulásra?"
  description: "Próbálja ki ingyenesen a GroupDocs.Viewer funkcióit, vagy kérjen licencet"

release:
  title: "{0} verzió megjelent"
  notes: "Tekintse újdonságokat"
  downloads: "Letöltések"
  link: "https://releases.groupdocs.com/viewer/java/release-notes/latest/"

code:
  title: "PDF fájlok renderelése Java nyelven"
  more: "További példák"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Java"
  install: |
    <dependencies>
      <dependency>
        <groupId>com.groupdocs</groupId>
        <artifactId>groupdocs-viewer</artifactId>
        <version>{0}</version>
      </dependency>
    </dependencies>

    <repositories>
      <repository>
        <id>repository.groupdocs.com</id>
        <name>GroupDocs Repository</name>
        <url>https://repository.groupdocs.com/repo/</url>
      </repository>
    </repositories>
  content: |
    ```java {style=abap}
    // Példányos megjelenítő 
    try (Viewer viewer = new Viewer("resume.pdf"))
    {
        // Állítsa be a kimeneti HTML-beállításokat  
        HtmlViewOptions viewOptions = 
        HtmlViewOptions.forEmbeddedResources();

        // Rendereljen PDF-et HTML-be
        viewer.view(viewOptions);
    }
    ```
############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Viewer egy pillanat alatt"
  description: "API dokumentumok, diák, diagramok és sok más dokumentumtípus megjelenítéséhez, megjelenítéséhez, konvertálásához Java alkalmazásokban"
  features:
    # feature loop
    - title: "Tekintse meg a dokumentumokat hatékonyan és megbízhatóan"
      content: "A GroupDocs.Viewer API segítségével bármilyen támogatott formátumú dokumentumokat hatékonyan renderelhet HTML, JPEG, PNG és PDF formátumba, rugalmas és hatékony opciókkal, miközben megőrzi a tartalom és a dokumentumstruktúra integritását. A GroupDocs.Viewer Windows és Linux platformokon működik."

    # feature loop
    - title: "A legtöbb népszerű fájl- és dokumentumformátum támogatott"
      content: "Támogatjuk a több mint 180 legnépszerűbb fájl- és dokumentumformátum renderelését, beleértve a Word, Excel, PDF, PowerPoint, OpenDocument formátumcsaládot, archívumokat, raszteres és vektorképeket, e-könyveket, programozási nyelveket és jelöléseket, valamint sok más fájltípust, beleértve a titkosított fájlokat is. jelszavas védelemmel ellátott fájlokat."

    # feature loop
    - title: "Testreszabható kimenet"
      content: "A GroupDocs.Viewer nem csak a dokumentum megjelenítését teszi lehetővé, hanem annak szabályozását is, hogy pontosan hogyan, a dokumentum mely részei jelenjenek meg vagy most, hogyan jelenjenek meg, és különböző átalakításokat alkalmazzon a renderelt kimenetre."

    # feature loop
    - title: "Webes felhasználói felület a tavaszi keretrendszerhez"
      content: "Nyílt forráskódú UI csomagot biztosítunk a Spring keretrendszerhez, amelyet néhány perc alatt hozzáadhat a projekthez. A Viewer.UI csomag egy Angular alapú webes felhasználói felületet tartalmaz, és hasznos API-kat és adattárolási szolgáltatókat biztosít."

############################# Platforms ############################
platforms:
  enable: true
  title: "Platformfüggetlenség"
  description: "A GroupDocs.Viewer for Java a következő operációs rendszereket, keretrendszereket és csomagkezelőket támogatja"
  items:
    # platform loop
    - title: "Amazon"
      image: "amazon"
    # platform loop
    - title: "Docker"
      image: "docker"
    # platform loop
    - title: "Azure"
      image: "azure"
    # platform loop
    - title: "Eclipse"
      image: "eclipse"
    # platform loop
    - title: "IntelliJ"
      image: "intellij"
    # platform loop
    - title: "Windows"
      image: "windows"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "Maven"
      image: "maven"


############################# File formats ############################
formats:
  enable: true
  title: "Támogatott fájlformátumok"
  description: |
    A GroupDocs.Viewer for Java a következő [fájlformátumokkal](https://docs.groupdocs.com/viewer/java/supported-document-formats/) támogatja a műveleteket.
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office, OpenDocument és szöveges formátumok
        * **Word:** DOC, DOCX, DOCM, DOT, DOTX, DOTM, RTF, TXT
        * **Excel:** XLS, XLSX, XLSM, XLSB, XLTM, XLT, XLTM, XLTX
        * **PowerPoint:** PPT, PPTX, PPS, PPSX, PPSM, POT, POTM, POTX, PPTM        
        * **Project:** MPP, MPT, MPX
        * **Outlook:** MSG, EML, EMLX, PST, OST
        * **OneNote:** ONE
        * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG
        * **Fixed Page Layout:** PDF, TEX, XPS, OXPS
        * **e-Books:** EPUB, MOBI, DjVu
        * **Delimiter-Separated Values:** CSV, TSV
    # group loop
    - color: "blue"
      content: |
        ### Képek, grafika és diagramok
        * **Raszteres képek:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
        * **Windows Icon:** ICO
        * **Scalable Vector Graphics:** SVG, CDR, CMX, IGS, SVGZ        
        * **Adobe Photoshop:** PSD, PSB        
        * **Stereo Lithography (3D Printing):** STL        
        * **Medical Imaging:** DICOM
        * **Plotter Documents:** PLT, HPG
        * **Autodesk Design Web Formats:** DWF, DWG
        * **AutoCAD Drawing:** DWT, IFC, STL, CF2        
      # group loop
    - color: "red"
      content: |
        ### Egyéb        
        * **Web:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **Levéltár:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **Egyéb:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "GroupDocs.Viewer funkciók"
  description: "Zökkenőmentesen renderelhet, jeleníthet meg és konvertálhat PDF és Office dokumentumokat"

  items:
    # feature loop
    - icon: "viewhtml"
      title: "Dokumentumok megtekintése HTML-ben"
      content: "Bármilyen típusú dokumentumot konvertálhat HTML dokumentummá CSS és SVG segítségével, amely bármely modern webböngészőben megjeleníthető."

    # feature loop
    - icon: "rasterize"
      title: "Raszterizálja a dokumentumokat"
      content: "Raszterezzen bármilyen támogatott dokumentumformátumot a raszterképhez, állítható képformátummal és tömörítési minőséggel."

    # feature loop
    - icon: "sourcecode"
      title: "Rendereljen és jelöljön ki programozási kódokat"
      content: "Az összes népszerű programozási, szkript- és jelölőnyelv támogatása, szintaxisuk elemzésének és kiemelésének képességével."

    # feature loop
    - icon: "convertpdf"
      title: "Konvertálás PDF-be"
      content: "Bármilyen támogatott formátumú dokumentum könnyen konvertálható és PDF-be menthető a beállítható opciókkal."

    # feature loop
    - icon: "transform"
      title: "Transzformációk alkalmazása"
      content: "A kimeneti dokumentum a renderelés során átalakítható - az oldalak elforgathatók és/vagy átrendezhetők, és szöveges vízjel helyezhető el rájuk."

    # feature loop
    - icon: "adjustment"
      title: "HTML kimenet beállítása"
      content: "A GroupDocs.Viewer által generált kimeneti HTML dokumentumok nagyon finoman hangolhatók: adatfolyamba vagy fájlba menthető, külső vagy beágyazott erőforrásokkal, visszahívásokkal és így tovább."

    # feature loop
    - icon: "complex"
      title: "Komplex dokumentumszerkezetek támogatása"
      content: "A GroupDocs.Viewer nem csak az egyes dokumentumokat támogatja, hanem olyan fájlokat is, amelyek belsőleg tartalmazzák a dokumentumok listáját vagy hierarchikus szerkezetét, mint például az e-mail üzenetek mellékletekkel, ZIP archívumok mappákban lévő belső fájlokkal, többoldalas TIFF-képek és így tovább."

    # feature loop
    - icon: "optimization"
      title: "Optimalizálási lehetőségek"
      content: "A GroupDocs.Viewer tartalmaz egy állítható gyorsítótár alrendszert, amely a dokumentumok gyorsítótárazott verzióinak használatával le tudja gyorsítani a betöltési időt. Ezenkívül a különböző formátumokhoz tartozó különféle beállítások lehetővé teszik a dokumentumok bizonyos szükségtelen részeinek vagy aspektusainak kizárását a renderelésből (betűtípusok, rejtett munkalapok, e-mail mellékletek), az általános teljesítmény optimalizálása érdekében"

    # feature loop
    - icon: "passwordprotected"
      title: "Jelszóval védett dokumentumok támogatása"
      content: "A GroupDocs.Viewer lehetővé teszi a különböző típusú titkosított dokumentumok megnyitását: PDF, WordProcessing, Spreadsheet, Presentation és egyéb, jelszó megadásával a betöltési lehetőségek között."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Kódminták"
  description: "Egyes esetekben a tipikus GroupDocs.Viewer Java műveleteket használják"
  items:
    # code sample loop
    - title: "A DOCX renderelése HTML-be"
      content: |
        A [HtmlViewOptions](https://reference.groupdocs.com/viewer/java/com.groupdocs.viewer.options/htmlviewoptions/) osztálytulajdonságok lehetővé teszik az átalakítási folyamat vezérlését, erről bővebben [itt](https://docs.groupdocs.com/viewer/java/rendering-to-html/). Például beágyazhat minden külső erőforrást a kimeneti HTML-fájlba, kicsinyítheti a kimeneti fájlt, és optimalizálhatja a nyomtatáshoz.
        {{< landing/code title="Java">}}
        ```java {style=abap}
        import com.groupdocs.viewer.Viewer;
        import com.groupdocs.viewer.options.HtmlViewOptions;

        // Példányos megjelenítő
        try (Viewer viewer = new Viewer("resume.docx"))
        {
            // Állítsa be a kimeneti HTML-beállításokat
            HtmlViewOptions options = 
            HtmlViewOptions.forEmbeddedResources();

            // A DOCX renderelése HTML formátumban beágyazott erőforrásokkal
            viewer.view(options);
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "PPTX exportálása PDF-be"
      content: |
        Hozzon létre egy [PdfViewOptions](https://reference.groupdocs.com/viewer/java/com.groupdocs.viewer.options/pdfviewoptions/) osztálypéldányt, és adja át a [Viewer.View](https://reference.groupdocs.com/viewer/java/com.groupdocs.viewer/viewer/#view-com.groupdocs.viewer.options.ViewOptions-) módszerrel konvertálhat egy PowerPoint PPTX fájlt PDF formátumba. A PdfViewOptions osztály tulajdonságai lehetővé teszik az átalakítási folyamat vezérlését. Például védheti a kimeneti PDF-fájlt, átrendezheti az oldalait, és megadhatja a dokumentumképek minőségét. A részletekért tekintse meg a [következő dokumentációs részt](https://docs.groupdocs.com/viewer/java/rendering-to-pdf/).
        {{< landing/code title="Java">}}
        ```java {style=abap}   
        import com.groupdocs.viewer.Viewer;
        import com.groupdocs.viewer.options.PdfViewOptions;

        // Példányos megjelenítő
        try (Viewer viewer = new Viewer("presentation.pptx"))
        {            
            // Állítsa be a kimeneti PDF-beállításokat
            PdfViewOptions viewOptions = new PdfViewOptions();

            // PPTX exportálása PDF-be
            viewer.view(viewOptions);
        }
        ```
        {{< /landing/code >}}
############################# Reviews ############################
# reviews:
# enable: true
# title: "GroupDocs termékértékelések"
# description: "Ne csak szót fogadjon. Tekintse meg, mit mondanak más fejlesztők az API-inkról"

# items:
#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "Kiváló kiszolgálás és kiváló termékek. Rendkívül segítőkészek és készségesek voltak a GroupDocs.Viewer for .NET megvalósítási folyamata során, nem tudom őket eléggé ajánlani."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "A GroupDocs.Viewer for .NET projektben történő megvalósítása és használata után úgy tűnik, hogy nagyon jól működik. Rengeteg dokumentummal teszteltem, és eddig jó. Minden, amit rádobtam, szépen megjelenik, és ugyanolyan jól néz ki, mint egy PDF-nézegetőben vagy MS Word-ben."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---