---
############################# Static ############################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: ru
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
    # supported_platforms loop
    - title: "Python"
      tag: "python-net"


############################# Head ############################
head_title: "API просмотра документов Node.js для изображений PDF Word Excel HTML и электронных писем"
head_description: "Средство просмотра документов Node.js и API рендеринга файлов. Добавьте программу просмотра PDF, программу просмотра Word, программу просмотра Excel, программу просмотра изображений, программу просмотра HTML, программу просмотра электронной почты в приложениях JavaScript."

############################# Header ############################
title: "Node.js API для рендеринга и отображения документов"
description: "Библиотека средства просмотра документов для разработки приложений JavaScript, которые естественным образом отображают, просматривают и манипулируют многоформатными документами, поддерживающими более 180 форматов файлов."
words:
  for: "for"

actions:
  viewer_demo: true
  viewer_demo_file_name: "quarterly-report.docx"
  main: "Бесплатная загрузка НПМ"
  main_link: "https://www.npmjs.com/package/@groupdocs/groupdocs.viewer"
  alt: "Лицензирование"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/nodejs-java"
  title: "Готовы начать?"
  description: "Попробуйте функции GroupDocs.Viewer бесплатно или запросите лицензию."

release:
  title: "Версия {0} выпущена"
  notes: "Что нового"
  downloads: "Загрузки"
  link: "https://releases.groupdocs.com/viewer/nodejs-java/release-notes/latest/"

code:
  title: "Рендеринг PDF-файлов в JavaScript"
  more: "Больше примеров"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Node.js-via-Java"
  install: "npm i @groupdocs/groupdocs.viewer"
  content: |
    ```javascript {style=abap}       
    // Установите параметры вывода HTML
    const viewOptions = HtmlViewOptions.forEmbeddedResources()
    
    // Создать экземпляр средства просмотра
    const viewer = new Viewer("resume.pdf")

    // Преобразование PDF в HTML
    viewer.view(viewOptions)
    viewer.close()
    ```
############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Viewer: краткий обзор"
  description: "API для рендеринга, отображения и преобразования документов, слайдов, диаграмм и многих других типов документов в приложениях Node.js."
  features:
    # feature loop
    - title: "Просматривайте документы эффективно и надежно"
      content: "С помощью API GroupDocs.Viewer вы можете эффективно рендерить документы любых поддерживаемых форматов в [HTML](https://docs.groupdocs.com/viewer/nodejs-java/rendering-to-html/), JPEG, PNG и [PDF](https://docs.groupdocs.com/viewer/nodejs-java/rendering-to-pdf/) с гибкими и мощными параметрами, сохраняющими целостность содержимого и структуры документа. GroupDocs.Viewer for Node.js работает в Windows и Linux."

    # feature loop
    - title: "Поддерживаются большинство популярных форматов файлов и документов."
      content: "Мы поддерживаем рендеринг более 180 самых популярных форматов файлов и документов, включая [Word](https://docs.groupdocs.com/viewer/nodejs-java/render-word-documents/), [Excel](https://docs.groupdocs.com/viewer/nodejs-java/render-excel-and-apple-numbers-spreadsheets/), [PDF](https://docs.groupdocs.com/viewer/nodejs-java/render-pdf-documents/), [PowerPoint](https://docs.groupdocs.com/viewer/nodejs-java/render-presentations/), семейство форматов OpenDocument, архивы, растровые и векторные изображения, электронные книги, языки программирования и разметки, а также множество других типов файлов, в том числе зашифрованные файлы с паролем."

    # feature loop
    - title: "Настраиваемый вывод"
      content: "GroupDocs.Viewer позволяет не только визуализировать документ, но и контролировать, как именно, какие части документа должны быть визуализированы или сейчас, как они должны отображаться, а также применять различные преобразования к визуализированному выводу."

############################# Platforms ############################
platforms:
  enable: true
  title: "Независимость от платформы"
  description: "GroupDocs.Viewer для Node.js поддерживает следующие операционные системы, платформы и менеджеры пакетов."
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
  title: "Поддерживаемые форматы файлов"
  description: |
    GroupDocs.Viewer для Node.js через Java поддерживает операции со следующими [форматами файлов](https://docs.groupdocs.com/viewer/nodejs-java/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office, OpenDocument и текстовые форматы
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
        ### Изображения, графика и диаграммы
        * **Растровые изображения:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
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
        ### Другой        
        * **Интернет:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **Архивы:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **Другой:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "Возможности GroupDocs.Viewer"
  description: "Легко визуализируйте, отображайте и конвертируйте документы PDF и Office."

  items:
    # feature loop
    - icon: "viewhtml"
      title: "[Просмотр документов в формате HTML](https://docs.groupdocs.com/viewer/nodejs-java/rendering-to-html/)"
      content: "Конвертируйте документ любого типа в документ HTML с помощью CSS и SVG, который можно отобразить в любом современном веб-браузере."

    # feature loop
    - icon: "rasterize"
      title: "[Растеризация документов](https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Node.js-via-Java/blob/master/Examples/BasicUsage/RenderDocumentToImage/renderToJpg.js)"
      content: "Преобразуйте любой поддерживаемый формат документа в растровое изображение с настраиваемым форматом изображения и качеством сжатия."

    # feature loop
    - icon: "font"
      title: "[Управление шрифтами документа](https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Node.js-via-Java/blob/master/Examples/AdvancedUsage/Rendering/CommonRenderingOptions/replaceMissingFont.js)"
      content: "Определяйте, какие шрифты использованы в документе. Управляйте отсутствующими шрифтами, заменяя их или исключая из вывода."

    # feature loop
    - icon: "convertpdf"
      title: "[Конвертировать в PDF](https://docs.groupdocs.com/viewer/nodejs-java/rendering-to-pdf/)"
      content: "Документ любого поддерживаемого формата можно легко преобразовать и сохранить в PDF с настраиваемыми параметрами."

    # feature loop
    - icon: "transform"
      title: "[Применить преобразования](https://docs.groupdocs.com/viewer/nodejs-java/add-text-watermark/)"
      content: "Выходной документ можно трансформировать во время рендеринга — страницы можно поворачивать и/или переставлять, а поверх них можно размещать текстовый водяной знак."

    # feature loop
    - icon: "adjustment"
      title: "[Настройка вывода HTML](https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Node.js-via-Java/blob/master/Examples/BasicUsage/RenderDocumentToHtml/renderToHtmlWithExternalResources.js)"
      content: "Выходные HTML-документы, генерируемые GroupDocs.Viewer, можно очень тонко настроить: разрешено сохранение в поток или файл, с внешними или встроенными ресурсами, обратными вызовами и так далее."

    # feature loop
    - icon: "complex"
      title: "[Поддержка сложных структур документов](https://docs.groupdocs.com/viewer/nodejs-java/how-to-extract-and-save-attachments/)"
      content: "GroupDocs.Viewer поддерживает не только отдельные документы, но и файлы, которые внутри содержат список или иерархическую структуру документов, например, сообщения электронной почты с вложениями, ZIP-архивы с внутренними файлами в папках, многостраничные изображения TIFF и т. д."

    # feature loop
    - icon: "optimization"
      title: "[Варианты оптимизации](https://docs.groupdocs.com/viewer/nodejs-java/caching-results/)"
      content: "GroupDocs.Viewer содержит настраиваемую подсистему кэширования, которая может сократить время загрузки за счет использования кэшированных версий документов. Также набор различных опций для разных форматов позволяет исключить из рендеринга некоторые ненужные части или аспекты документов (шрифты, скрытые листы, вложения электронной почты) для оптимизации общей производительности."

    # feature loop
    - icon: "passwordprotected"
      title: "[Поддержка документов, защищенных паролем](https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Node.js-via-Java/blob/master/Examples/AdvancedUsage/Loading/loadPasswordProtectedDocument.js)"
      content: "GroupDocs.Viewer позволяет открывать зашифрованные документы разных типов: PDF, WordProcessing, Spreadsheet, Presentation и другие, указав пароль в параметрах загрузки."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Примеры кода"
  description: "Некоторые варианты использования типичного GroupDocs.Viewer для Node.js с помощью операций Java"
  items:
    # code sample loop
    - title: "Преобразование DOCX в HTML"
      content: |
        Свойства класса HtmlViewOptions позволяют вам управлять процессом преобразования, подробнее об этом [здесь](https://docs.groupdocs.com/viewer/nodejs-java/rendering-to-html/). Например, вы можете встроить все внешние ресурсы в выходной HTML-файл, минимизировать выходной файл и оптимизировать его для печати.
        {{< landing/code title="JavaScript">}}
        ```javascript {style=abap}
        import { Viewer, HtmlViewOptions } from '@groupdocs/groupdocs.viewer'

        // Установите параметры вывода HTML
        const viewOptions = HtmlViewOptions.forEmbeddedResources()

        // Создать экземпляр средства просмотра
        const viewer = new Viewer("resume.docx")

        // Преобразование DOCX в HTML со встроенными ресурсами
        viewer.view(viewOptions)
        viewer.close()
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Экспорт PPTX в PDF"
      content: |
        Создайте экземпляр класса PdfViewOptions и передайте его методу Viewer.view, чтобы преобразовать файл PowerPoint PPTX в PDF. Свойства класса PdfViewOptions позволяют вам управлять процессом преобразования. Например, вы можете защитить выходной PDF-файл, изменить порядок его страниц и указать качество изображений документа. Подробности см. в [следующем разделе документации](https://docs.groupdocs.com/viewer/nodejs-java/rendering-to-pdf/).
        {{< landing/code title="JavaScript">}}
        ```javascript {style=abap}   
        import { Viewer, PdfViewOptions } from '@groupdocs/groupdocs.viewer'

        // Установите параметры вывода PDF
        const viewOptions = new PdfViewOptions("presentation.pdf")

        // Создать экземпляр средства просмотра
        const viewer = new Viewer("presentation.pptx")

        // Экспорт PPTX в PDF
        viewer.view(viewOptions)
        viewer.close()
        ```
        {{< /landing/code >}}
############################# Reviews ############################
# reviews:
# enable: true
# title: "Обзоры продуктов GroupDocs"
# description: "Не верьте нам на слово. Посмотрите, что другие разработчики говорят о наших API"

# items:
#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "Отличный сервис и отличная продукция. Они были чрезвычайно полезны и отзывчивы в процессе внедрения GroupDocs.Viewer для .NET, поэтому не могу не рекомендовать их достаточно высоко."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "После реализации и использования GroupDocs.Viewer для .NET в проекте он работает очень хорошо. Я проверил множество документов и пока все хорошо. Все, что я в него добавил, прекрасно визуализируется и выглядит так же хорошо, как в программе просмотра PDF или MS Word."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---
