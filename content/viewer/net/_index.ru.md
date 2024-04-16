---
############################# Static ##########################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: ru
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

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
head_title: "API просмотра документов .NET, рендеринг PDF-изображения Word Excel в HTML-диаграмме"
head_description: "Средство просмотра файлов C# ASP.NET и API рендеринга. Добавьте средства просмотра PDF-файлов, средства просмотра Word, средства просмотра Excel, средства просмотра изображений, средства просмотра HTML и функции просмотра электронной почты в приложениях .NET."

############################# Header ##########################
title: "Рендеринг и отображение документов<br>с использованием .NET API"
description: "Мощный API-интерфейс Viewer для преобразования более 180 форматов документов в PDF, HTML и изображения с универсальными параметрами конфигурации."
words:
  for: "for"

actions:
  main: "Бесплатная загрузка NuGet"
  main_link: "https://www.nuget.org/packages/GroupDocs.Viewer"
  alt: "Лицензирование"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/net"
  title: "Готовы начать?"
  description: "Попробуйте функции GroupDocs.Viewer бесплатно или запросите лицензию."

release:
  title: "Версия {0} выпущена"
  notes: "Что нового"
  downloads: "Загрузки"
  link: "https://releases.groupdocs.com/viewer/net/release-notes/latest/"

code:
  title: "Рендеринг PDF-файлов на C#"
  more: "Больше примеров"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
  install: "dotnet add package GroupDocs.Viewer"
  content: |
    ```csharp {style=abap}   
    // Загрузите исходный PDF-файл
    using (var viewer = new Viewer("resume.pdf"))
    {
        // Установите параметры вывода HTML
        var viewOptions = 
        HtmlViewOptions.ForEmbeddedResources("page{0}.html");
        
        // Преобразование PDF в HTML        
        viewer.View(viewOptions);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Viewer: краткий обзор"
  description: "API для рендеринга, отображения и преобразования документов, слайдов, диаграмм и многих других типов документов в приложениях .NET."
  features:
    # feature loop
    - title: "Просматривайте документы эффективно и надежно"
      content: "С помощью API GroupDocs.Viewer вы можете эффективно отображать документы любых поддерживаемых форматов в HTML, JPEG, PNG и PDF с помощью гибких и мощных функций, сохраняя при этом целостность содержимого и структуры документа. GroupDocs.Viewer поддерживает .NET Framework 4.6.2 и .NET 6.0, работает на платформах Windows и Linux."

    # feature loop
    - title: "Поддерживаются большинство популярных форматов файлов и документов."
      content: "Мы поддерживаем рендеринг более 180 наиболее популярных форматов файлов и документов, включая Word, Excel, PDF, PowerPoint, семейство форматов OpenDocument, архивы, растровые и векторные изображения, электронные книги, языки программирования и разметки, а также многие другие типы файлов, включая зашифрованные. файлы с защитой паролем."

    # feature loop
    - title: "Настраиваемый вывод"
      content: "GroupDocs.Viewer позволяет не только визуализировать документ, но и контролировать, как именно, какие части документа должны быть визуализированы или сейчас, как они должны отображаться, а также применять различные преобразования к визуализированному выводу."

    # feature loop
    - title: "Пользовательский интерфейс для ASP.NET Core"
      content: "Мы предоставляем пакет пользовательского интерфейса с открытым исходным кодом для ASP.NET Core, который можно добавить в ваш проект за пару минут. Пакет Viewer.UI содержит веб-интерфейс на основе Angular и предоставляет набор полезных API и поставщиков хранилищ данных."

############################# Platforms ############################
platforms:
  enable: true
  title: "Поддержка платформ"
  description: "GroupDocs.Viewer для .NET поддерживает следующие операционные системы, платформы и менеджеры пакетов."
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
    - title: "VS Code"
      image: "vs_code"
    # platform loop
    - title: "ReSharper"
      image: "resharper"
    # platform loop
    - title: "macOS"
      image: "finder"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "NuGet"
      image: "nuget"
  packages:
    # packages loop
    - title: "Пакет для Windows"
      content: |
        * Поддерживает .NET Framework 4.6.2+ и .NET 6.0.
        * Наиболее полная поддержка форматов файлов
        * Зависит от System.Drawing и System.Drawing.Common 
      action: "Загрузка NuGet"
      action_link: "https://www.nuget.org/packages/GroupDocs.Viewer"
    # packages loop
    - title: "Кроссплатформенный пакет" 
      content: |
        * Поддерживает .NET 6.0 и более поздние версии. 
        * Ограниченная поддержка форматов файлов 
        * Работает на Windows, Linux и macOS 
      action: "Загрузка NuGet" 
      action_link: "https://www.nuget.org/packages/GroupDocs.Viewer.CrossPlatform" 

############################# File formats ############################
formats:
  enable: true
  title: "Поддерживаемые форматы файлов"
  description: |
    GroupDocs.Viewer для .NET поддерживает операции со следующими [форматами файлов](https://docs.groupdocs.com/viewer/net/supported-document-formats/).
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
  description: "Некоторые варианты использования типичных операций GroupDocs.Viewer для .NET"
  items:
    # code sample loop
    - title: "Преобразование DOCX в HTML"
      content: |
        Свойства класса [HtmlViewOptions](https://reference.groupdocs.com/viewer/net/groupdocs.viewer.options/htmlviewoptions/) позволяют вам управлять процессом преобразования, подробнее об этом [здесь](https://docs.groupdocs.com/viewer/net/rendering-to-html/). Например, вы можете встроить все внешние ресурсы в выходной HTML-файл, минимизировать выходной файл и оптимизировать его для печати.
        {{< landing/code title="C#">}}
        ```csharp {style=abap}
        using GroupDocs.Viewer;
        using GroupDocs.Viewer.Options;
        
        // Создать экземпляр просмотра
        using (Viewer viewer = new Viewer("resume.docx"))
        {
            // Установите параметры вывода HTML
            HtmlViewOptions options = HtmlViewOptions.ForEmbeddedResources();
            
            // Преобразование DOCX в HTML со встроенными ресурсами
            viewer.View(options);
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Экспорт PPTX в PDF"
      content: |
        Создайте экземпляр класса [PdfViewOptions](https://reference.groupdocs.com/viewer/net/groupdocs.viewer.options/pdfviewoptions/) и передайте его в [Viewer.View](https://reference.groupdocs.com/viewer/net/groupdocs.viewer/viewer/view/#view) для преобразования файла PowerPoint PPTX в PDF. Свойства класса PdfViewOptions позволяют управлять процессом преобразования. Например, вы можете защитить выходной PDF-файл, изменить порядок его страниц и указать качество изображений документа. Подробности см. в [следующем разделе документации](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).
        {{< landing/code title="C#">}}
        ```csharp {style=abap}   
        using GroupDocs.Viewer;
        using GroupDocs.Viewer.Options;
        
        using (var viewer = new Viewer("presentation.pptx"))
        {
            // Установите параметры вывода PDF       
            var viewOptions = new PdfViewOptions("presentation.pdf");
            
            // Экспорт PPTX в PDF       
            viewer.View(viewOptions);
        }
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