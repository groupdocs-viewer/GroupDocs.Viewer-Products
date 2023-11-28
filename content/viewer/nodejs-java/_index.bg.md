---
############################# Static ############################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: bg
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
head_title: "Node.js API за преглед на документи за PDF Word Excel HTML изображения и имейли"
head_description: "Node.js преглед на документи и API за изобразяване на файлове. Добавете програма за преглед на PDF, програма за преглед на Word, програма за преглед на Excel, програма за преглед на изображения, програма за преглед на HTML, програма за преглед на имейли в приложения на JavaScript."

############################# Header ############################
title: "Node.js API за изобразяване и показване на документи"
description: "Библиотека за преглед на документи за разработване на JavaScript приложения, които естествено изобразяват, преглеждат и манипулират многоформатни документи, поддържащи 180+ файлови формата."
words:
  for: "for"

actions:
  main: "Безплатно изтегляне на NPM"
  main_link: "https://www.npmjs.com/package/@groupdocs/groupdocs.viewer"
  alt: "Лицензиране"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/nodejs-java"
  title: "Готови ли сте да започнете?"
  description: "Изпробвайте функциите на GroupDocs.Viewer безплатно или поискайте лиценз"

release:
  title: "Версия {0} издадена"
  notes: "Вижте какво ново"
  downloads: "Изтегляния"
  link: "https://releases.groupdocs.com/viewer/nodejs-java/release-notes/latest/"

code:
  title: "Рендирайте PDF файлове в JavaScript"
  more: "Още примери"
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
  title: "GroupDocs.Viewer с един поглед"
  description: "API за изобразяване, показване, конвертиране на документи, слайдове, диаграми и много други типове документи в приложения на Node.js"
  features:
    # feature loop
    - title: "Преглеждайте документи ефективно и надеждно"
      content: "С API на GroupDocs.Viewer можете ефективно да изобразявате документи от всякакви поддържани формати в HTML, JPEG, PNG и PDF с гъвкави и мощни опции, като същевременно поддържате целостта на съдържанието и структурата на документа. GroupDocs.Viewer за Node.js работи на Windows и Linux платформи."

    # feature loop
    - title: "Поддържат се повечето популярни формати на файлове и документи"
      content: "Ние поддържаме изобразяване на над 180 най-популярни файлови и документни формати, които включват Word, Excel, PDF, PowerPoint, семейство формати OpenDocument, архиви, растерни и векторни изображения, електронни книги, езици за програмиране и маркиране и много други типове файлове, включително криптирани файлове със защита с парола."

    # feature loop
    - title: "Изход с възможност за персонализиране"
      content: "GroupDocs.Viewer позволява не само рендиране на документа, но и контрол как точно, кои части от документа трябва да бъдат рендирани или сега, как те трябва да бъдат рендирани и да се прилагат различни трансформации към рендирания изход."

############################# Platforms ############################
platforms:
  enable: true
  title: "Независимост на платформата"
  description: "GroupDocs.Viewer за Node.js поддържа следните операционни системи, рамки и мениджъри на пакети"
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
  title: "Поддържани файлови формати"
  description: |
    GroupDocs.Viewer за Node.js чрез Java поддържа операции със следните [файлови формати](https://docs.groupdocs.com/viewer/nodejs-java/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office, OpenDocument и текстови формати
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
        ### Изображения, графики и диаграми
        * **Растерни изображения:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
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
        ### други        
        * **Мрежа:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **Архив:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **други:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "Функции на GroupDocs.Viewer"
  description: "Безпроблемно изобразявайте, показвайте и конвертирайте PDF и Office документи"

  items:
    # feature loop
    - icon: "viewhtml"
      title: "Преглед на документи в HTML"
      content: "Конвертирайте документ от всякакъв тип в HTML документ с CSS и SVG, който може да се показва във всеки модерен уеб браузър."

    # feature loop
    - icon: "rasterize"
      title: "Растеризиране на документи"
      content: "Растеризирайте всеки поддържан формат на документ към растерното изображение с регулируем формат на изображението и качество на компресия."

    # feature loop
    - icon: "sourcecode"
      title: "Изобразяване и осветяване на програмни кодове"
      content: "Поддръжка на всички популярни езици за програмиране, скриптове и маркиране, с възможност за анализиране и подчертаване на техния синтаксис."

    # feature loop
    - icon: "convertpdf"
      title: "Конвертиране в PDF"
      content: "Документ от всеки поддържан формат може лесно да бъде конвертиран и записан в PDF с регулируеми опции."

    # feature loop
    - icon: "transform"
      title: "Прилагане на трансформации"
      content: "Изходният документ може да се трансформира по време на изобразяване - страниците могат да се завъртат и/или пренареждат, а над тях може да се поставя текстов воден знак."

    # feature loop
    - icon: "adjustment"
      title: "Корекция на HTML изхода"
      content: "Изходните HTML документи, генерирани от GroupDocs.Viewer, могат да бъдат настроени много фино: разрешено е да се записват в поток или файл, с външни или вградени ресурси, обратни извиквания и т.н."

    # feature loop
    - icon: "complex"
      title: "Поддръжка на сложни структури на документи"
      content: "GroupDocs.Viewer поддържа не само единични документи, но и файлове, които вътрешно съдържат списък или йерархична структура от документи, като имейл съобщения с прикачени файлове, ZIP архиви с вътрешни файлове в папки, многостранични TIFF изображения и т.н."

    # feature loop
    - icon: "optimization"
      title: "Опции за оптимизация"
      content: "GroupDocs.Viewer съдържа регулируема кеш подсистема, която може да ускори времето за зареждане чрез използване на кешираните версии на документите. Също така набор от различни опции за различни формати позволява да се изключат някои ненужни части или аспекти на документи от изобразяването (шрифтове, скрити работни листове, прикачени файлове към имейл), за да се оптимизира цялостната производителност"

    # feature loop
    - icon: "passwordprotected"
      title: "Поддръжка на документи, защитени с парола"
      content: "GroupDocs.Viewer позволява отваряне на криптирани документи от различни типове: PDF, WordProcessing, Spreadsheet, Presentation и други, като зададете парола в опциите за зареждане."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Примерни кодове"
  description: "Някои случаи на използване на типичен GroupDocs.Viewer за Node.js чрез Java операции"
  items:
    # code sample loop
    - title: "Рендирайте DOCX в HTML"
      content: |
        Свойствата на класа `HtmlViewOptions` ви позволяват да контролирате процеса на преобразуване, повече за това [тук](https://docs.groupdocs.com/viewer/nodejs-java/rendering-to-html/). Например, можете да вградите всички външни ресурси в изходния HTML файл, да минимизирате изходния файл и да го оптимизирате за печат.
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
    - title: "Експортирайте PPTX в PDF"
      content: |
        Създайте екземпляр на клас `PdfViewOptions` и го предайте на метода `Viewer.view`, за да конвертирате PPTX файл на PowerPoint в PDF. Свойствата на класа `PdfViewOptions` ви позволяват да контролирате процеса на конвертиране. Например, можете да защитите изходния PDF файл, да пренаредите страниците му и да определите качеството на изображенията на документа. Обърнете се към [следващата секция с документация](https://docs.groupdocs.com/viewer/nodejs-java/rendering-to-pdf/) за подробности.
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
# title: "Отзиви за продукти на GroupDocs"
# description: "Не ни вярвайте просто на думата. Вижте какво казват други разработчици за нашите API"

# items:
#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "Отлично обслужване и отлични продукти. Те бяха изключително полезни и отзивчиви по време на процеса на внедряване на GroupDocs.Viewer за .NET, не мога да ги препоръчам достатъчно силно."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "След внедряване и използване на GroupDocs.Viewer за .NET в проекта изглежда, че работи много добре. Тествах с много документи и засега добре. Всичко, което съм хвърлил върху него, се изобразява добре и изглежда също толкова добре, колкото би било в PDF Viewer или MS Word."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---
