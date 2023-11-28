---
############################# Static ############################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: hu
product: "Viewer"
product_tag: "viewer"
platform: "Node.js via Java"
platform_tag: "nodejs-java"

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
head_title: "Node.js Document Viewer API PDF Word Excel HTML képekhez és e-mailekhez"
head_description: "Node.js dokumentummegjelenítő és fájlmegjelenítő API. PDF-nézegető, Word-nézegető, Excel-nézegető, Képnézegető, HTML-nézegető, E-mail-nézegető hozzáadása JavaScript-alkalmazásokhoz."

############################# Header ############################
title: "Node.js API a dokumentumok rendereléséhez és megjelenítéséhez"
description: "Document Viewer könyvtár JavaScript alkalmazások fejlesztésére, amelyek natív módon jelenítenek meg, tekintenek meg és kezelnek több formátumú dokumentumokat, amelyek több mint 180 fájlformátumot támogatnak."
words:
  for: "for"

actions:
  main: "Ingyenes NPM letöltés"
  main_link: "https://www.npmjs.com/package/@groupdocs/groupdocs.viewer"
  alt: "Engedélyezés"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/nodejs-java"
  title: "Készen áll az indulásra?"
  description: "Próbálja ki ingyenesen a GroupDocs.Viewer funkcióit, vagy kérjen licencet"

release:
  title: "A(z) {0} verzió megjelent"
  notes: "Tekintse meg az újdonságokat"
  downloads: "Letöltések"
  link: "https://releases.groupdocs.com/viewer/nodejs-java/release-notes/latest/"

code:
  title: "PDF-fájlok megjelenítése JavaScriptben"
  more: "További példák"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Node.js-via-Java"
  install: "npm i @groupdocs/groupdocs.viewer"
  content: |
    ```javascript {style=abap}   
    //Set output HTML options, one file per page
    const viewOptions = HtmlViewOptions.forEmbeddedResources()

    // Instantiate Viewer
    const viewer = new Viewer("resume.pdf")

    // Render PDF to HTML with embedded resources
    viewer.view(viewOptions)
    viewer.close()
    ```
############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Viewer egy pillanat alatt"
  description: "API dokumentumok, diák, diagramok és sok más dokumentumtípus megjelenítéséhez, megjelenítéséhez, konvertálásához a Node.js alkalmazásokban"
  features:
    # feature loop
    - title: "Tekintse meg a dokumentumokat hatékonyan és megbízhatóan"
      content: "A GroupDocs.Viewer API segítségével bármilyen támogatott formátumú dokumentumokat hatékonyan renderelhet HTML, JPEG, PNG és PDF formátumba, rugalmas és hatékony opciókkal, miközben megőrzi a tartalom és a dokumentumstruktúra integritását. A GroupDocs.Viewer for Node.js Windows és Linux platformokon működik."

    # feature loop
    - title: "A legtöbb népszerű fájl- és dokumentumformátum támogatott"
      content: "Támogatjuk a több mint 180 legnépszerűbb fájl- és dokumentumformátum renderelését, beleértve a Word, Excel, PDF, PowerPoint, OpenDocument formátumcsaládot, archívumokat, raszteres és vektorképeket, e-könyveket, programozási nyelveket és jelöléseket, valamint sok más fájltípust, beleértve a titkosított fájlokat is. jelszavas védelemmel ellátott fájlokat."

    # feature loop
    - title: "Testreszabható kimenet"
      content: "A GroupDocs.Viewer nem csak a dokumentum megjelenítését teszi lehetővé, hanem annak szabályozását is, hogy pontosan hogyan, a dokumentum mely részei jelenjenek meg vagy most, hogyan jelenjenek meg, és különböző átalakításokat alkalmazzon a renderelt kimenetre."

############################# Platforms ############################
platforms:
  enable: true
  title: "Platformfüggetlenség"
  description: "A GroupDocs.Viewer for Node.js a következő operációs rendszereket, keretrendszereket és csomagkezelőket támogatja"
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
    - title: "NPM"
      image: "npm"

############################# File formats ############################
formats:
  enable: true
  title: "Támogatott fájlformátumok"
  description: |
    A GroupDocs.Viewer for Node.js Java-n keresztül a következő [fájlformátumokkal] (https://docs.groupdocs.com/viewer/nodejs-java/supported-document-formats/) támogatja a műveleteket.
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
  description: "Egyes esetekben a tipikus GroupDocs.Viewer for Node.js Java műveleteket használ"
  items:
    # code sample loop
    - title: "A DOCX renderelése HTML-be"
      content: |
        A „HtmlViewOptions” osztálytulajdonságok lehetővé teszik a konverziós folyamat vezérlését, erről bővebben [itt](https://docs.groupdocs.com/viewer/nodejs-java/rendering-to-html/). Például beágyazhat minden külső erőforrást a kimeneti HTML-fájlba, kicsinyítheti a kimeneti fájlt, és optimalizálhatja a nyomtatáshoz.
        {{< landing/code title="JavaScript">}}
        ```javascript {style=abap}
        import { Viewer, HtmlViewOptions } from '@groupdocs/groupdocs.viewer'

        //Set output HTML options, one file per page
        const viewOptions = HtmlViewOptions.forEmbeddedResources()

        // Instantiate Viewer
        const viewer = new Viewer("resume.docx")

        // Render PDF to HTML with embedded resources
        viewer.view(viewOptions)
        viewer.close()
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "PPTX exportálása PDF-be"
      content: |
        Hozzon létre egy „PdfViewOptions” osztálypéldányt, és adja át a „Viewer.view” metódusnak, hogy egy PowerPoint PPTX fájlt PDF formátumba konvertáljon. A `PdfViewOptions` osztálytulajdonságok lehetővé teszik az átalakítási folyamat vezérlését. Például védheti a kimeneti PDF-fájlt, átrendezheti az oldalait, és megadhatja a dokumentumképek minőségét. A részletekért tekintse meg a [következő dokumentációs részt](https://docs.groupdocs.com/viewer/nodejs-java/rendering-to-pdf/).
        {{< landing/code title="JavaScript">}}
        ```javascript {style=abap}   
        import { Viewer, PdfViewOptions } from '@groupdocs/groupdocs.viewer'

        //Set output PDF options
        const viewOptions = new PdfViewOptions("presentation.pdf")

        // Instantiate Viewer
        const viewer = new Viewer("presentation.pptx")

        // Render PDF to HTML with embedded resources
        viewer.view(viewOptions)
        viewer.close()
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
