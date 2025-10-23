---
############################# Static ############################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: ru
product: "Viewer"
product_tag: "viewer"
platform: "Python via .NET"
platform_tag: "python-net"

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
head_title: "Python API для просмотра документов (PDF, Word, Excel, HTML, Изображения и электронная почта)"
head_description: "Python API для просмотра и рендеринга файловых документов. Добавьте средства просмотра PDF, Word, Excel, Изображений, HTML и электронной почты(Email) в Python приложения."

############################# Header ############################
title: "Мощный Python API для оптимизированного рендеринга документов"
description: "Просматривайте и выполняйте рендеринг более 180 форматов документов (PDF, HTML, Изображения) с помощью мощных API и гибких параметров конфигурации для разработки приложений на Python."
words:
  for: "for"

actions:
  viewer_demo: true
  viewer_demo_file_name: "quarterly-report.docx"
  main: "Бесплатная загрузка с PyPI"
  main_link: "https://pypi.org/project/groupdocs-viewer-net/"
  alt: "Лицензирование"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/python-net"
  title: "Готовы начать?"
  description: "Попробуйте функции GroupDocs.Viewer бесплатно или запросите лицензию."

release:
  title: "Версия {0} выпущена"
  notes: "Что нового"
  downloads: "Загрузки"
  link: "https://releases.groupdocs.com/viewer/python-net/release-notes/latest/"

code:
  title: "Рендеринг PDF-файла на Python"
  more: "Больше примеров"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Python-via-.NET"
  install: "pip install groupdocs-viewer-net"
  content: |
    ```python {style=abap}
    import groupdocs.viewer as gv
    import groupdocs.viewer.options as gvo
    hvo = gvo.HtmlViewOptions  
  
    // Назначьте параметры вывода HTML-файла (one file per page)
    with gv.Viewer("resume.docx") as viewer:
      // Создайте экземпляр Viewer
      opts = hvo.for_embedded_resources("page_{0}.html")

      // Рендеринг PDF в HTML с параметрами (embedded resources)
      viewer.view(opts)
    ```
############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Viewer вкратце"
  description: "API для рендеринга, просмотра и преобразования документов, слайдов, диаграмм и многих других типов документов в Python приложениях"
  features:
    # feature loop
    - title: "Эффективное и надежное отображение документов"
      content: "С помощью API GroupDocs.Viewer вы можете эффективно выполнять рендеринг любых поддерживаемых форматов в HTML, JPEG, PNG и PDF с гибкими и мощными параметрами, сохраняя целостность содержимого и структуры документа. GroupDocs.Viewer для Python работает на платформах Windows и Linux."

    # feature loop
    - title: "Поддерживаются самые популярные форматы файлов и документов"
      content: "Мы поддерживаем рендеринг более 180 самых популярных форматов файлов и документов, включая Word, Excel, PDF, PowerPoint, семейство форматов OpenDocument, Архивы, Растровые и Векторные Изображения, Электронные Книги, Языки Программирования и Разметки, а также многие другие типы файлов, включая зашифрованные файлы с защитой паролем."

    # feature loop
    - title: "Настраиваемый вывод"
      content: "GroupDocs.Viewer позволяет не только выполнять рендеринг документа, но и точно контролировать, какие части документа должны быть отрисованы, а какие нет, как они должны быть отрисованы, и применять различные преобразования к отрисованному выводу."

############################# Platforms ############################
platforms:
  enable: true
  title: "Независимость от платформы"
  description: "GroupDocs.Viewer для Python поддерживает следующие операционные системы, фреймворки и менеджеры пакетов"
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
    - title: "PyPI"
      image: "pypi"

############################# File formats ############################
formats:
  enable: true
  title: "Поддерживаемые форматы файлов"
  description: |
    GroupDocs.Viewer для Python (через .NET) поддерживает операции с следующими форматами файлов: [поддерживаемые форматы файлов](https://docs.groupdocs.com/viewer/python-net/supported-document-formats/).
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
      title: "Просмотр документов в формате HTML"
      content: "Конвертируйте документ любого типа в документ HTML с помощью CSS и SVG, который можно отобразить в любом современном веб-браузере."

    # feature loop
    - icon: "rasterize"
      title: "Растеризация документов"
      content: "Преобразуйте любой поддерживаемый формат документа в растровое изображение с настраиваемым форматом изображения и качеством сжатия."

    # feature loop
    - icon: "sourcecode"
      title: "Рендеринг и выделение программных кодов"
      content: "Поддержка всех популярных языков программирования, сценариев и разметки с возможностью анализа и выделения их синтаксиса."

    # feature loop
    - icon: "convertpdf"
      title: "Конвертировать в PDF"
      content: "Документ любого поддерживаемого формата можно легко преобразовать и сохранить в PDF с настраиваемыми параметрами."

    # feature loop
    - icon: "transform"
      title: "Применить преобразования"
      content: "Выходной документ можно трансформировать во время рендеринга — страницы можно поворачивать и/или переставлять, а поверх них можно размещать текстовый водяной знак."

    # feature loop
    - icon: "adjustment"
      title: "Настройка вывода HTML"
      content: "Выходные HTML-документы, генерируемые GroupDocs.Viewer, можно очень тонко настроить: разрешено сохранение в поток или файл, с внешними или встроенными ресурсами, обратными вызовами и так далее."

    # feature loop
    - icon: "complex"
      title: "Поддержка сложных структур документов"
      content: "GroupDocs.Viewer поддерживает не только отдельные документы, но и файлы, которые внутри содержат список или иерархическую структуру документов, например, сообщения электронной почты с вложениями, ZIP-архивы с внутренними файлами в папках, многостраничные изображения TIFF и т. д."

    # feature loop
    - icon: "optimization"
      title: "Варианты оптимизации"
      content: "GroupDocs.Viewer содержит настраиваемую подсистему кэширования, которая может сократить время загрузки за счет использования кэшированных версий документов. Также набор различных опций для разных форматов позволяет исключить из рендеринга некоторые ненужные части или аспекты документов (шрифты, скрытые листы, вложения электронной почты) для оптимизации общей производительности."

    # feature loop
    - icon: "passwordprotected"
      title: "Поддержка документов, защищенных паролем"
      content: "GroupDocs.Viewer позволяет открывать зашифрованные документы разных типов: PDF, WordProcessing, Spreadsheet, Presentation и другие, указав пароль в параметрах загрузки."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Примеры кода"
  description: "Некоторые случаи использования типичных операций GroupDocs.Viewer для Python через .NET"
  items:
    # code sample loop
    - title: "Преобразование DOCX в HTML"
      content: |
        Свойства класса `HtmlViewOptions` позволяют управлять процессом конвертации. Дополнительные сведения см. [здесь](https://docs.groupdocs.com/viewer/python-net/rendering-to-html/). Например, вы можете внедрить все внешние ресурсы во выходной HTML-файл, сжать выходной файл и оптимизировать его для печати.
        {{< landing/code title="Python">}}
        ```python {style=abap}
        import groupdocs.viewer as gv
        import groupdocs.viewer.options as gvo 

        // Создать экземпляр средства просмотра
        with gv.Viewer("resume.docx") as viewer:
          // Установить параметры выходного HTML (один файл на страницу)
          viewOptions = gvo.HtmlViewOptions.for_embedded_resources("page_{0}.html")
          // Рендеринг PDF в HTML со встроенными ресурсами
          viewer.view(viewOptions)
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Экспорт PPTX в PDF"
      content: |
        Создайте экземпляр класса `PdfViewOptions` и передайте его методу `Viewer.view` для преобразования файла PowerPoint PPTX в PDF. Свойства класса `PdfViewOptions` позволяют управлять процессом конвертации. Например, вы можете защитить выходной PDF-файл, изменить порядок его страниц и указать качество изображений документа. Дополнительные сведения см. в [следующем разделе документации](https://docs.groupdocs.com/viewer/python-net/rendering-to-pdf/).
        {{< landing/code title="Python">}}
        ```python {style=abap}
        import groupdocs.viewer as gv
        import groupdocs.viewer.options as gvo  

        // Создать экземпляр средства просмотра
        with gv.Viewer("presentation.pptx") as viewer:
          // Установить параметры выходного PDF (Set output PDF options)
          viewOptions = gvo.PdfViewOptions("presentation.pdf")
          // Экспортировать PPTX в PDF (Export PPTX to PDF)
          viewer.view(viewOptions)
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
