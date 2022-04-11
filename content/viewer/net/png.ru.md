---
############################# Static ############################
layout: "auto-gen"
date: 2022-02-23T12:00:00+02:00
draft: false
############################# Head ############################
head_title: ".NET PNG Viewer API — чтение, просмотр, рендеринг на C# VB.NET"
head_description: ".NET для просмотра документов для чтения, рендеринга и отображения PNG в приложениях C#, ASP.NET, VB.NET и .NET Core любого типа."
############################# Header ############################
title: "Средство просмотра файлов PNG для приложений C# .NET"
description: ".NET для просмотра документов для чтения, рендеринга и отображения файлов PNG в приложениях C#, ASP.NET, VB.NET и .NET Core любого типа. Просматривайте визуализированные файлы с истинным форматированием и макетом в формате HTML5, PDF или в виде изображения, используя несколько строк кода."
bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Скачать бесплатную пробную версию"
    link: "https://downloads.groupdocs.com/viewer/net"
############################# SubMenu ############################
submenu:
    enable: true
    left:
        img_alt: "GroupDocs.Viewer for .NET"
        image: "https://cms.admin.containerize.com/templates/groupdocs/images/product-logos/90x90-noborder/groupdocs-viewer-net.png"
        product: "GroupDocs.Viewer"
        platform: ".NET"
    middle:
        button:
            # button loop
            - link: "https://apireference.groupdocs.com/viewer/net"
              text: "Справочник по API"
            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Примеры кода"
            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Живые демонстрации"
            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Цены"
    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"
############################# About ############################
about:
    enable: true
    title: "О GroupDocs.Viewer для .NET API"
    content: |
        Начните просматривать более 170 популярных форматов документов в своих приложениях .NET с помощью GroupDocs.Viewer для API .NET, добавив несколько строк кода. Разработчики могут легко отображать PDF, Word Processing, электронные таблицы Excel, презентации, Visio, Project, Outlook и многие другие популярные форматы документов в режимах HTML5, изображений или PDF. Рендеринг документа происходит быстро, идентично исходному файлу и не требует установки Microsoft Office или каких-либо других внешних библиотек.
############################# Steps ############################
steps:
    enable: true
    title_left: "Шаги для просмотра файла PNG в C #"
    content_left: |
        [GroupDocs.Viewer](/ru/viewer/net/) позволяет разработчикам .NET легко добавлять функцию просмотра файлов PNG в свои приложения, выполняя несколько простых шагов.
        * Создайте экземпляр класса Viewer и загрузите файл PNG с полным путем.
        * Установите параметры для преобразования файла PNG в формат PNG.
        * Преобразование файла и проверка вывода в текущем каталоге.
    title_right: "Системные Требования"
    content_right: |
        API GroupDocs.Viewer для .NET поддерживаются на всех основных платформах и операционных системах. Перед выполнением приведенного ниже кода убедитесь, что в вашей системе установлены следующие предварительные компоненты.
        * Операционные системы: Microsoft Windows, Linux, MacOS
        * Среды разработки: Microsoft Visual Studio, Visual Studio Code, .NET CLI
        * Фреймворки: .NET Framework, .NET Standard, .NET Core, .NET
        * Получите последнюю версию GroupDocs.Viewer для .NET из [NuGet](https://www.nuget.org/packages/groupdocs.viewer)
    code: |
        ```cs
        // Создаем средство просмотра
        using (Viewer viewer = new Viewer("sample.png"))
        {
        	// Установить параметры просмотра 
        	ViewOptions viewOptions = new PngViewOptions();
        	// Преобразуйте файл в PNG и проверьте вывод в текущем каталоге
        	viewer.View(viewOptions);
        }
        ```
############################# Demos ############################
demos:
    enable: true
    title: "Демонстрации в режиме реального времени для просмотра в формате PNG"
    content: |
       Отобразите файл PNG прямо сейчас, посетив веб-сайт [GroupDocs.Viewer Живые волнения](https://products.groupdocs.app/viewer/PNG).
############################# About Formats ############################
about_formats:
    enable: true
    format:
        # format loop
        - icon: "far fa-file-png"
          title: "О формате файла PNG"
          content: |
            PNG, переносимая сетевая графика, относится к типу формата файла растрового изображения, в котором используется сжатие без потерь. Этот формат файла был создан в качестве замены формата обмена графикой (GIF) и не имеет ограничений авторского права. Однако формат файла PNG не поддерживает анимацию. Формат файлов PNG поддерживает сжатие изображений без потерь, что делает его популярным среди пользователей. С течением времени PNG превратился в один из наиболее часто используемых форматов файлов изображений. Почти все операционные системы поддерживают открытие файлов PNG. Например, средство просмотра Microsoft Windows имеет возможность открывать файлы PNG, поскольку ОС по умолчанию поддерживает эту поддержку, доступную как часть установки.
          link: "https://docs.fileformat.com/image/png/"
############################# More Formats ############################
more_formats:
    enable: true
    title: "Рендеринг и просмотр файлов других форматов"
    content: |
        Многоформатный API для просмотра документов и изображений для .NET. Просмотрите некоторые из популярных форматов файлов ниже без каких-либо внешних средств просмотра.
    format: 
        # format loop
        - name: ".NET-просмотрщик DOC-файлов"
          link: "/viewer/net/doc/"
          description: "Документ Microsoft Word"
        # format loop
        - name: ".NET-просмотрщик DOCM-файлов"
          link: "/viewer/net/docm/"
          description: "Документ Microsoft Word с поддержкой макросов"
        # format loop
        - name: ".NET-просмотрщик DOCX-файлов"
          link: "/viewer/net/docx/"
          description: "Документ Microsoft Word с открытым XML"
        # format loop
        - name: ".NET-просмотрщик DOT-файлов"
          link: "/viewer/net/dot/"
          description: "Шаблон документа Microsoft Word"
        # format loop
        - name: ".NET-просмотрщик DOTM-файлов"
          link: "/viewer/net/dotm/"
          description: "Шаблон Microsoft Word с поддержкой макросов"
        # format loop
        - name: ".NET-просмотрщик DOTX-файлов"
          link: "/viewer/net/dotx/"
          description: "Шаблон документа Word Open XML"
        # format loop
        - name: ".NET-просмотрщик RTF-файлов"
          link: "/viewer/net/rtf/"
          description: "Расширенный текстовый формат файла"
        # format loop
        - name: ".NET-просмотрщик TXT-файлов"
          link: "/viewer/net/txt/"
          description: "Формат обычного текстового файла"
        # format loop
        - name: ".NET-просмотрщик XLS-файлов"
          link: "/viewer/net/xls/"
          description: "Формат двоичного файла Microsoft Excel"
        # format loop
        - name: ".NET-просмотрщик XLSX-файлов"
          link: "/viewer/net/xlsx/"
          description: "Электронная таблица Microsoft Excel Open XML"
        # format loop
        - name: ".NET-просмотрщик XLSM-файлов"
          link: "/viewer/net/xlsm/"
          description: "Электронная таблица Microsoft Excel с поддержкой макросов"
        # format loop
        - name: ".NET-просмотрщик XLSB-файлов"
          link: "/viewer/net/xlsb/"
          description: "Двоичный файл электронной таблицы Microsoft Excel"
        # format loop
        - name: ".NET-просмотрщик XLTX-файлов"
          link: "/viewer/net/xltx/"
          description: "Открытый XML-шаблон Microsoft Excel"
        # format loop
        - name: ".NET-просмотрщик TSV-файлов"
          link: "/viewer/net/tsv/"
          description: "Файл значений, разделенных табуляцией"
        # format loop
        - name: ".NET-просмотрщик XLAM-файлов"
          link: "/viewer/net/xlam/"
          description: "Надстройка Microsoft Excel с поддержкой макросов"
        # format loop
        - name: ".NET-просмотрщик CSV-файлов"
          link: "/viewer/net/csv/"
          description: "Файл значений, разделенных запятыми"
        # format loop
        - name: ".NET-просмотрщик PPT-файлов"
          link: "/viewer/net/ppt/"
          description: "Презентация PowerPoint"
        # format loop
        - name: ".NET-просмотрщик PPS-файлов"
          link: "/viewer/net/pps/"
          description: "Слайд-шоу Microsoft PowerPoint"
        # format loop
        - name: ".NET-просмотрщик PPTX-файлов"
          link: "/viewer/net/pptx/"
          description: "Презентация PowerPoint Open XML"
        # format loop
        - name: ".NET-просмотрщик PPSX-файлов"
          link: "/viewer/net/ppsx/"
          description: "Слайд-шоу PowerPoint Open XML"
        # format loop
        - name: ".NET-просмотрщик POTX-файлов"
          link: "/viewer/net/potx/"
          description: "Открытый XML-шаблон Microsoft PowerPoint"
        # format loop
        - name: ".NET-просмотрщик POTM-файлов"
          link: "/viewer/net/potm/"
          description: "Шаблон Microsoft PowerPoint"
        # format loop
        - name: ".NET-просмотрщик PPTM-файлов"
          link: "/viewer/net/pptm/"
          description: "Презентация Microsoft PowerPoint"
        # format loop
        - name: ".NET-просмотрщик PPSM-файлов"
          link: "/viewer/net/ppsm/"
          description: "Слайд-шоу Microsoft PowerPoint"
        # format loop
        - name: ".NET-просмотрщик PDF-файлов"
          link: "/viewer/net/pdf/"
          description: "Adobe Portable Document Format"
        # format loop
        - name: ".NET-просмотрщик XPS-файлов"
          link: "/viewer/net/xps/"
          description: "Спецификация документа Open XML"
        # format loop
        - name: ".NET-просмотрщик TEX-файлов"
          link: "/viewer/net/tex/"
          description: "Исходный документ LaTeX"
        # format loop
        - name: ".NET-просмотрщик ODS-файлов"
          link: "/viewer/net/ods/"
          description: "Открыть электронную таблицу документов"
        # format loop
        - name: ".NET-просмотрщик ODP-файлов"
          link: "/viewer/net/odp/"
          description: "Формат файла презентации OpenDocument"
        # format loop
        - name: ".NET-просмотрщик OTP-файлов"
          link: "/viewer/net/otp/"
          description: "Шаблон графика происхождения"
        # format loop
        - name: ".NET-просмотрщик ODT-файлов"
          link: "/viewer/net/odt/"
          description: "Открыть текст документа"
        # format loop
        - name: ".NET-просмотрщик OTT-файлов"
          link: "/viewer/net/ott/"
          description: "Открыть шаблон документа"
        # format loop
        - name: ".NET-просмотрщик VST-файлов"
          link: "/viewer/net/vst/"
          description: "Microsoft Visio 2003-2010 XML-чертеж"
        # format loop
        - name: ".NET-просмотрщик TIFF-файлов"
          link: "/viewer/net/tiff/"
          description: "Формат файла изображения с тегами"
        # format loop
        - name: ".NET-просмотрщик JPEG-файлов"
          link: "/viewer/net/jpeg/"
          description: "Изображение в формате JPEG"
        # format loop
        - name: ".NET-просмотрщик GIF-файлов"
          link: "/viewer/net/gif/"
          description: "Графический файл формата обмена"
        # format loop
        - name: ".NET-просмотрщик BMP-файлов"
          link: "/viewer/net/bmp/"
          description: "Формат растрового файла"
        # format loop
        - name: ".NET-просмотрщик ICO-файлов"
          link: "/viewer/net/ico/"
          description: "Файл значка Майкрософт"
        # format loop
        - name: ".NET-просмотрщик PSD-файлов"
          link: "/viewer/net/psd/"
          description: "Документ Adobe Photoshop"
        # format loop
        - name: ".NET-просмотрщик WEBP-файлов"
          link: "/viewer/net/webp/"
          description: "Формат файла растрового веб-изображения"
        # format loop
        - name: ".NET-просмотрщик SVG-файлов"
          link: "/viewer/net/svg/"
          description: "Файл масштабируемой векторной графики"
        # format loop
        - name: ".NET-просмотрщик JP2-файлов"
          link: "/viewer/net/jp2/"
          description: "Основной файл изображения JPEG 2000"
        # format loop
        - name: ".NET-просмотрщик MPP-файлов"
          link: "/viewer/net/emz/"
          description: "Документ Microsoft Project"
        # format loop
        - name: ".NET-просмотрщик MPT-файлов"
          link: "/viewer/net/wmz/"
          description: "Шаблон проекта Майкрософт"
        # format loop
        - name: ".NET-просмотрщик HTML-файлов"
          link: "/viewer/net/html/"
          description: "Язык гипертекстовой разметки"
        # format loop
        - name: ".NET-просмотрщик MHT-файлов"
          link: "/viewer/net/mht/"
          description: "MIME-инкапсуляция совокупного HTML"
        # format loop
        - name: ".NET-просмотрщик MHTML-файлов"
          link: "/viewer/net/mhtml/"
          description: "MIME-инкапсуляция совокупного HTML"
        # format loop
        - name: ".NET-просмотрщик MSG-файлов"
          link: "/viewer/net/msg/"
          description: "Сообщение электронной почты Microsoft Outlook"
        # format loop
        - name: ".NET-просмотрщик EML-файлов"
          link: "/viewer/net/eml/"
          description: "Сообщение электронной почты"
        # format loop
        - name: ".NET-просмотрщик ONE-файлов"
          link: "/viewer/net/one/"
          description: "Майкрософт OneNote"
        # format loop
        - name: ".NET-просмотрщик WMF-файлов"
          link: "/viewer/net/wmf/"
          description: "Метафайл Windows"
        # format loop
        - name: ".NET-просмотрщик EMF-файлов"
          link: "/viewer/net/emf/"
          description: "Расширенный метафайл Windows"
        # format loop
        - name: ".NET-просмотрщик PSD-файлов"
          link: "/viewer/net/psd/"
          description: "Документ Adobe Photoshop"
        # format loop
        - name: ".NET-просмотрщик VSD-файлов"
          link: "/viewer/net/vsd/"
          description: "Чертеж Microsoft Visio 2003-2010"
        # format loop
        - name: ".NET-просмотрщик VSDX-файлов"
          link: "/viewer/net/vsdx/"
          description: "Рисование Microsoft Visio"
        # format loop
        - name: ".NET-просмотрщик VSS-файлов"
          link: "/viewer/net/vss/"
          description: "Трафарет Microsoft Visio 2003-2010"
        # format loop
        - name: ".NET-просмотрщик VDX-файлов"
          link: "/viewer/net/vdx/"
          description: "Microsoft Visio 2003-2010 XML-чертеж"
        # format loop
        - name: ".NET-просмотрщик VDW-файлов"
          link: "/viewer/net/vdw/"
          description: "Веб-рисование Microsoft Visio 2010"
        # format loop
        - name: ".NET-просмотрщик EPUB-файлов"
          link: "/viewer/net/epub/"
          description: "Формат файла цифровой электронной книги"
############################# Back to top ###############################
back_to_top:
    enable: true
---
