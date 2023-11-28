---
############################# Static ############################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: ro
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
head_title: "Node.js Document Viewer API pentru PDF Word Excel HTML Imagini și e-mailuri"
head_description: "Vizualizatorul de documente Node.js și API-ul de randare a fișierelor. Adăugați vizualizator PDF, vizualizator Word, vizualizator Excel, vizualizator de imagini, vizualizator HTML, vizualizator de e-mail în aplicațiile JavaScript."

############################# Header ############################
title: "API-ul Node.js pentru a reda și afișa documente"
description: "Bibliotecă Document Viewer pentru a dezvolta aplicații JavaScript care redă, vizualizează și manipulează în mod nativ documente multi-formate care acceptă peste 180 de formate de fișiere."
words:
  for: "for"

actions:
  main: "Descărcare gratuită NPM"
  main_link: "https://www.npmjs.com/package/@groupdocs/groupdocs.viewer"
  alt: "Licențiere"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/nodejs-java"
  title: "Sunteți gata să începeți?"
  description: "Încercați gratuit funcțiile GroupDocs.Viewer sau solicitați o licență"

release:
  title: "Versiunea {0} a fost lansată"
  notes: "Vezi ce este nou"
  downloads: "Descărcări"
  link: "https://releases.groupdocs.com/viewer/nodejs-java/release-notes/latest/"

code:
  title: "Redați fișierele PDF în JavaScript"
  more: "Mai multe exemple"
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
  title: "GroupDocs.Viewer dintr-o privire"
  description: "API pentru a randa, afișa, converti documente, diapozitive, diagrame și multe alte tipuri de documente în aplicațiile Node.js"
  features:
    # feature loop
    - title: "Vizualizați documentele eficient și fiabil"
      content: "Cu GroupDocs.Viewer API puteți reda eficient documentele din orice formate acceptabile în HTML, JPEG, PNG și PDF cu opțiuni flexibile și puternice, menținând în același timp integritatea conținutului și a structurii documentului. GroupDocs.Viewer pentru Node.js funcționează pe platformele Windows și Linux."

    # feature loop
    - title: "Cele mai populare formate de fișiere și documente sunt acceptate"
      content: "Acceptăm randarea celor mai populare 180 de formate de fișiere și documente, care includ familia de formate Word, Excel, PDF, PowerPoint, OpenDocument, arhive, imagini raster și vectoriale, cărți electronice, limbaje de programare și markupuri și multe alte tipuri de fișiere, inclusiv criptate. fișiere cu protecție prin parolă."

    # feature loop
    - title: "Ieșire personalizabilă"
      content: "GroupDocs.Viewer permite nu numai să randeze documentul, ci și să controleze cum exact, ce părți ale documentului ar trebui să fie redate sau acum, cum ar trebui să fie redate și să aplice diferite transformări la rezultatul randat."

############################# Platforms ############################
platforms:
  enable: true
  title: "Independenta platformei"
  description: "GroupDocs.Viewer pentru Node.js acceptă următoarele sisteme de operare, cadre și manageri de pachete"
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
  title: "Formate de fișiere acceptate"
  description: |
    GroupDocs.Viewer pentru Node.js prin Java acceptă operațiuni cu următoarele [formate de fișiere](https://docs.groupdocs.com/viewer/nodejs-java/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office, OpenDocument și formate text
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
        ### Imagini, grafice și diagrame
        * **Imagini raster:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
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
        ### Alte        
        * **Web:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **Arhive:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **Alte:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "Funcții GroupDocs.Viewer"
  description: "Redați, afișați și convertiți fără probleme PDF și documente Office"

  items:
    # feature loop
    - icon: "viewhtml"
      title: "Vizualizați documentele în HTML"
      content: "Convertiți documentul de orice tip într-un document HTML cu CSS și SVG, care poate fi afișat în orice browser web modern."

    # feature loop
    - icon: "rasterize"
      title: "Rasterizați documentele"
      content: "Rasterizați orice format de document acceptabil la imaginea raster, cu formatul de imagine reglabil și calitatea compresiei."

    # feature loop
    - icon: "sourcecode"
      title: "Redați și evidențiați codurile de programare"
      content: "Suport pentru toate limbajele populare de programare, scripting și marcare, cu capacitatea de a analiza și evidenția sintaxa acestora."

    # feature loop
    - icon: "convertpdf"
      title: "Convertiți în PDF"
      content: "Documentul de orice format acceptabil poate fi ușor convertit și salvat în PDF cu opțiuni ajustabile."

    # feature loop
    - icon: "transform"
      title: "Aplicați transformări"
      content: "Documentul de ieșire poate fi transformat în timpul redării - paginile pot fi rotite și/sau rearanjate, iar filigranul textului poate fi plasat deasupra acestora."

    # feature loop
    - icon: "adjustment"
      title: "Ajustarea ieșirii HTML"
      content: "Documentele HTML de ieșire, generate de GroupDocs.Viewer, pot fi reglate foarte fin: este permisă salvarea în flux sau fișier, cu resurse externe sau încorporate, apeluri înapoi și așa mai departe."

    # feature loop
    - icon: "complex"
      title: "Sprijin pentru structuri complexe de documente"
      content: "GroupDocs.Viewer acceptă nu numai documentele individuale, ci și fișierele, care conțin intern o listă sau o structură ierarhică a documentelor, cum ar fi mesaje de e-mail cu atașamente, arhive ZIP cu fișiere interne în foldere, imagini TIFF cu mai multe pagini și așa mai departe."

    # feature loop
    - icon: "optimization"
      title: "Opțiuni de optimizare"
      content: "GroupDocs.Viewer conține un subsistem cache reglabil, care poate scurta timpul de încărcare utilizând versiunile stocate în cache ale documentelor. De asemenea, un set de opțiuni diferite pentru diferite formate permite excluderea unor părți sau aspecte inutile ale documentelor din randare (fonturi, foi de lucru ascunse, atașamente de e-mail) pentru a optimiza performanța generală"

    # feature loop
    - icon: "passwordprotected"
      title: "Suport pentru documente protejate prin parolă"
      content: "GroupDocs.Viewer permite deschiderea documentelor criptate de diferite tipuri: PDF, WordProcessing, Spreadsheet, Prezentare și altele, prin specificarea unei parole în opțiunile de încărcare."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Exemple de cod"
  description: "Unele cazuri de utilizare tipice ale GroupDocs.Viewer pentru Node.js prin operațiuni Java"
  items:
    # code sample loop
    - title: "Redați DOCX în HTML"
      content: |
        Proprietățile clasei `HtmlViewOptions` vă permit să controlați procesul de conversie, mai multe despre asta [aici](https://docs.groupdocs.com/viewer/nodejs-java/rendering-to-html/). De exemplu, puteți încorpora toate resursele externe în fișierul HTML de ieșire, puteți reduce fișierul de ieșire și îl puteți optimiza pentru imprimare.
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
    - title: "Exportați PPTX în PDF"
      content: |
        Creați o instanță de clasă `PdfViewOptions` și transmiteți-o metodei `Viewer.view` pentru a converti un fișier PowerPoint PPTX în PDF. Proprietățile clasei `PdfViewOptions` vă permit să controlați procesul de conversie. De exemplu, puteți proteja fișierul PDF de ieșire, puteți reordona paginile acestuia și puteți specifica calitatea imaginilor documentului. Consultați [următoarea secțiune de documentație](https://docs.groupdocs.com/viewer/nodejs-java/rendering-to-pdf/) pentru detalii.
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
# title: "Recenzii ale produselor GroupDocs"
# description: "Nu ne credeți pe cuvânt. Vedeți ce spun alți dezvoltatori despre API-urile noastre"

# items:
#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "Servicii excelente și produse excelente. Au fost extrem de utile și receptivi în timpul procesului de implementare GroupDocs.Viewer pentru .NET, nu le pot recomanda suficient."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "După implementarea și utilizarea GroupDocs.Viewer pentru .NET în proiect, se pare că funcționează foarte bine. Am testat cu multe documente și până acum e bine. Tot ceea ce am aruncat la el se redă frumos și arată la fel de bine ca într-un vizualizator PDF sau MS Word."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---
