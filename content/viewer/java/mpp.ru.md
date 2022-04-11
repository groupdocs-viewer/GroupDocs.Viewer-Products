---
############################# Static ############################
layout: "auto-gen"
date: 2022-02-23T12:00:00+02:00
draft: false
############################# Head ############################
head_title: "Java MPP Viewer API — рендеринг и отображение MPP в приложениях Java"
head_description: "Просмотр файлов MPP в приложениях Java, J2EE, J2SE. Поддерживает просмотр более 150 форматов файлов документов и изображений в формате HTML, PDF или изображения с расширенными функциями для управления параметрами просмотра документов."
############################# Header ############################
title: "Рендеринг и просмотр файла MPP в Java"
description: "Встроенный и высокопроизводительный API-интерфейс для просмотра файлов MPP для приложений на основе Java, J2EE и J2SE, поддерживающий широкий спектр дополнительных функций для настройки внешнего вида формата выходного документа."
bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Скачать бесплатную пробную версию"
    link: "https://downloads.groupdocs.com/viewer/java"
############################# SubMenu ############################
submenu:
    enable: true
    left:
        img_alt: "GroupDocs.Viewer for Java"
        image: "https://cms.admin.containerize.com/templates/groupdocs/images/product-logos/90x90-noborder/groupdocs-viewer-java.png"
        product: "GroupDocs.Viewer"
        platform: "Java"
    middle:
        button:
            # button loop
            - link: "https://apireference.groupdocs.com/viewer/java"
              text: "Справочник по API"
            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Java"
              text: "Примеры кода"
            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Живые демонстрации"
            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/java"
              text: "Цены"
    right:
        link_download: "https://downloads.groupdocs.com/viewer/java"
        link_learn: "https://docs.groupdocs.com/viewer/java"
        link_buy: "https://purchase.groupdocs.com"
############################# About ############################
about:
    enable: true
    title: "О GroupDocs.Viewer для Java API"
    content: |
        Разрешите своим приложениям Java отображать более 150 форматов файлов в режимах HTML, PDF или изображений с помощью API GroupDocs.Viewer для Java без установки дополнительного программного обеспечения; таких как Microsoft Office, Apache Open Office, Adobe Acrobat Reader и т. д. Разработчики могут легко просматривать все популярные форматы изображений и документов, включая Microsoft Office, OpenDocument, HTML, PDF, архив, диаграммы, Photoshop, AutoCAD и языки программирования, внутри приложений Java с помощью быстрый и качественный рендеринг.
############################# Steps ############################
steps:
    enable: true
    title_left: "Шаги для просмотра файла MPP в Java"
    content_left: |
        [GroupDocs.Viewer](/ru/viewer/java/) позволяет разработчикам Java легко добавлять функцию просмотра файлов MPP в свои приложения с помощью нескольких строк кода.
        * Создайте экземпляр класса Viewer и загрузите файл MPP с полным путем.
        * Установите параметры просмотра для преобразования файла MPP в формат PNG.
        * Преобразование файла и проверка вывода в текущем каталоге.
    title_right: "Системные Требования"
    content_right: |
        API GroupDocs.Viewer для Java поддерживаются на всех основных платформах и операционных системах. Перед выполнением приведенного ниже кода убедитесь, что в вашей системе установлены следующие предварительные компоненты.
        * Операционные системы: Microsoft Windows, Linux, MacOS
        * Среда разработки: NetBeans, IntelliJ IDEA, Eclipse и т. д.
        * Среда выполнения Java: Java 7 (1.7) и выше
        * Получите последнюю версию GroupDocs.Viewer для Java из [репозитория артефактов GroupDocs](https://repository.groupdocs.com/webapp/#/artifacts/browse/tree/General/repo/com/groupdocs/groupdocs-viewer)
    code: |
        ```java
        // Создаем средство просмотра
        try (Viewer viewer = new Viewer("sample.mpp"))
        {
        	// Установить параметры просмотра
        	PngViewOptions viewOptions = new PngViewOptions();
        	// Конвертируем файл в PNG и проверяем вывод в текущем каталоге
        	viewer.view(viewOptions);
        }
        ```
############################# Demos ############################
demos:
    enable: true
    title: "Демонстрации MPP Viewer в реальном времени"
    content: |
        Отобразите файл MPP прямо сейчас, посетив веб-сайт [GroupDocs.Viewer Живые волнения](https://products.groupdocs.app/viewer/).
############################# About Formats ############################
about_formats:
    enable: true
    format:
        # format loop
        - icon: "far fa-file-mpp"
          title: "О формате файла MPP"
          content: |
            Файл с расширением MPP — это файл данных Microsoft Project, в котором интегрированно хранится информация, связанная с управлением проектами. Это собственный формат файла, разработанный Microsoft как формат файла для Microsoft Project (MSP), который представляет собой прикладное программное обеспечение для управления проектами. Помимо MPP, MSP поддерживает другие форматы файлов, а также XML-схему проекта. Несколько API и приложений предоставляют возможность конвертировать формат файлов MPP в другие. У Microsoft теперь есть онлайн-сервер Project Server, на который можно загружать файлы управления проектами для совместной работы нескольких пользователей.
          link: "https://docs.fileformat.com/project-management/mpp/"
############################# More Formats ############################
more_formats:
    enable: true
    title: "Рендеринг и просмотр файлов других форматов"
    content: |
        Многоформатный API для просмотра документов и изображений для Java. Просмотрите некоторые из популярных форматов файлов ниже без каких-либо внешних средств просмотра.
    format: 
        # format loop
        - name: "Java-просмотрщик DOC-файлов"
          link: "/viewer/java/doc/"
          description: "Документ Microsoft Word"
        # format loop
        - name: "Java-просмотрщик DOCM-файлов"
          link: "/viewer/java/docm/"
          description: "Документ Microsoft Word с поддержкой макросов"
        # format loop
        - name: "Java-просмотрщик DOCX-файлов"
          link: "/viewer/java/docx/"
          description: "Документ Microsoft Word с открытым XML"
        # format loop
        - name: "Java-просмотрщик DOT-файлов"
          link: "/viewer/java/dot/"
          description: "Шаблон документа Microsoft Word"
        # format loop
        - name: "Java-просмотрщик DOTM-файлов"
          link: "/viewer/java/dotm/"
          description: "Шаблон Microsoft Word с поддержкой макросов"
        # format loop
        - name: "Java-просмотрщик DOTX-файлов"
          link: "/viewer/java/dotx/"
          description: "Шаблон документа Word Open XML"
        # format loop
        - name: "Java-просмотрщик RTF-файлов"
          link: "/viewer/java/rtf/"
          description: "Расширенный текстовый формат файла"
        # format loop
        - name: "Java-просмотрщик TXT-файлов"
          link: "/viewer/java/txt/"
          description: "Формат обычного текстового файла"
        # format loop
        - name: "Java-просмотрщик XLS-файлов"
          link: "/viewer/java/xls/"
          description: "Формат двоичного файла Microsoft Excel"
        # format loop
        - name: "Java-просмотрщик XLSX-файлов"
          link: "/viewer/java/xlsx/"
          description: "Электронная таблица Microsoft Excel Open XML"
        # format loop
        - name: "Java-просмотрщик XLSM-файлов"
          link: "/viewer/java/xlsm/"
          description: "Электронная таблица Microsoft Excel с поддержкой макросов"
        # format loop
        - name: "Java-просмотрщик XLSB-файлов"
          link: "/viewer/java/xlsb/"
          description: "Двоичный файл электронной таблицы Microsoft Excel"
        # format loop
        - name: "Java-просмотрщик XLTX-файлов"
          link: "/viewer/java/xltx/"
          description: "Открытый XML-шаблон Microsoft Excel"
        # format loop
        - name: "Java-просмотрщик TSV-файлов"
          link: "/viewer/java/tsv/"
          description: "Файл значений, разделенных табуляцией"
        # format loop
        - name: "Java-просмотрщик XLAM-файлов"
          link: "/viewer/java/xlam/"
          description: "Надстройка Microsoft Excel с поддержкой макросов"
        # format loop
        - name: "Java-просмотрщик CSV-файлов"
          link: "/viewer/java/csv/"
          description: "Файл значений, разделенных запятыми"
        # format loop
        - name: "Java-просмотрщик PPT-файлов"
          link: "/viewer/java/ppt/"
          description: "Презентация PowerPoint"
        # format loop
        - name: "Java-просмотрщик PPS-файлов"
          link: "/viewer/java/pps/"
          description: "Слайд-шоу Microsoft PowerPoint"
        # format loop
        - name: "Java-просмотрщик PPTX-файлов"
          link: "/viewer/java/pptx/"
          description: "Презентация PowerPoint Open XML"
        # format loop
        - name: "Java-просмотрщик PPSX-файлов"
          link: "/viewer/java/ppsx/"
          description: "Слайд-шоу PowerPoint Open XML"
        # format loop
        - name: "Java-просмотрщик POTX-файлов"
          link: "/viewer/java/potx/"
          description: "Открытый XML-шаблон Microsoft PowerPoint"
        # format loop
        - name: "Java-просмотрщик POTM-файлов"
          link: "/viewer/java/potm/"
          description: "Шаблон Microsoft PowerPoint"
        # format loop
        - name: "Java-просмотрщик PPTM-файлов"
          link: "/viewer/java/pptm/"
          description: "Презентация Microsoft PowerPoint"
        # format loop
        - name: "Java-просмотрщик PPSM-файлов"
          link: "/viewer/java/ppsm/"
          description: "Слайд-шоу Microsoft PowerPoint"
        # format loop
        - name: "Java-просмотрщик PDF-файлов"
          link: "/viewer/java/pdf/"
          description: "Adobe Portable Document Format"
        # format loop
        - name: "Java-просмотрщик XPS-файлов"
          link: "/viewer/java/xps/"
          description: "Спецификация документа Open XML"
        # format loop
        - name: "Java-просмотрщик TEX-файлов"
          link: "/viewer/java/tex/"
          description: "Исходный документ LaTeX"
        # format loop
        - name: "Java-просмотрщик ODS-файлов"
          link: "/viewer/java/ods/"
          description: "Открыть электронную таблицу документов"
        # format loop
        - name: "Java-просмотрщик ODP-файлов"
          link: "/viewer/java/odp/"
          description: "Формат файла презентации OpenDocument"
        # format loop
        - name: "Java-просмотрщик OTP-файлов"
          link: "/viewer/java/otp/"
          description: "Шаблон графика происхождения"
        # format loop
        - name: "Java-просмотрщик ODT-файлов"
          link: "/viewer/java/odt/"
          description: "Открыть текст документа"
        # format loop
        - name: "Java-просмотрщик OTT-файлов"
          link: "/viewer/java/ott/"
          description: "Открыть шаблон документа"
        # format loop
        - name: "Java-просмотрщик VST-файлов"
          link: "/viewer/java/vst/"
          description: "Microsoft Visio 2003-2010 XML-чертеж"
        # format loop
        - name: "Java-просмотрщик TIFF-файлов"
          link: "/viewer/java/tiff/"
          description: "Формат файла изображения с тегами"
        # format loop
        - name: "Java-просмотрщик JPEG-файлов"
          link: "/viewer/java/jpeg/"
          description: "Изображение в формате JPEG"
        # format loop
        - name: "Java-просмотрщик PNG-файлов"
          link: "/viewer/java/png/"
          description: "Портативная сетевая графика"
        # format loop
        - name: "Java-просмотрщик GIF-файлов"
          link: "/viewer/java/gif/"
          description: "Графический файл формата обмена"
        # format loop
        - name: "Java-просмотрщик BMP-файлов"
          link: "/viewer/java/bmp/"
          description: "Формат растрового файла"
        # format loop
        - name: "Java-просмотрщик ICO-файлов"
          link: "/viewer/java/ico/"
          description: "Файл значка Майкрософт"
        # format loop
        - name: "Java-просмотрщик PSD-файлов"
          link: "/viewer/java/psd/"
          description: "Документ Adobe Photoshop"
        # format loop
        - name: "Java-просмотрщик WEBP-файлов"
          link: "/viewer/java/webp/"
          description: "Формат файла растрового веб-изображения"
        # format loop
        - name: "Java-просмотрщик SVG-файлов"
          link: "/viewer/java/svg/"
          description: "Файл масштабируемой векторной графики"
        # format loop
        - name: "Java-просмотрщик JP2-файлов"
          link: "/viewer/java/jp2/"
          description: "Основной файл изображения JPEG 2000"
        # format loop
        - name: "Java-просмотрщик MPT-файлов"
          link: "/viewer/java/wmz/"
          description: "Шаблон проекта Майкрософт"
        # format loop
        - name: "Java-просмотрщик HTML-файлов"
          link: "/viewer/java/html/"
          description: "Язык гипертекстовой разметки"
        # format loop
        - name: "Java-просмотрщик MHT-файлов"
          link: "/viewer/java/mht/"
          description: "MIME-инкапсуляция совокупного HTML"
        # format loop
        - name: "Java-просмотрщик MHTML-файлов"
          link: "/viewer/java/mhtml/"
          description: "MIME-инкапсуляция совокупного HTML"
        # format loop
        - name: "Java-просмотрщик MSG-файлов"
          link: "/viewer/java/msg/"
          description: "Сообщение электронной почты Microsoft Outlook"
        # format loop
        - name: "Java-просмотрщик EML-файлов"
          link: "/viewer/java/eml/"
          description: "Сообщение электронной почты"
        # format loop
        - name: "Java-просмотрщик ONE-файлов"
          link: "/viewer/java/one/"
          description: "Майкрософт OneNote"
        # format loop
        - name: "Java-просмотрщик WMF-файлов"
          link: "/viewer/java/wmf/"
          description: "Метафайл Windows"
        # format loop
        - name: "Java-просмотрщик EMF-файлов"
          link: "/viewer/java/emf/"
          description: "Расширенный формат метафайла"
        # format loop
        - name: "Java-просмотрщик PSD-файлов"
          link: "/viewer/java/psd/"
          description: "Документ Adobe Photoshop"
        # format loop
        - name: "Java-просмотрщик VSD-файлов"
          link: "/viewer/java/vsd/"
          description: "Чертеж Microsoft Visio 2003-2010"
        # format loop
        - name: "Java-просмотрщик VSDX-файлов"
          link: "/viewer/java/vsdx/"
          description: "Рисование Microsoft Visio"
        # format loop
        - name: "Java-просмотрщик VSS-файлов"
          link: "/viewer/java/vss/"
          description: "Трафарет Microsoft Visio 2003-2010"
        # format loop
        - name: "Java-просмотрщик VDX-файлов"
          link: "/viewer/java/vdx/"
          description: "Microsoft Visio 2003-2010 XML-чертеж"
        # format loop
        - name: "Java-просмотрщик VDW-файлов"
          link: "/viewer/java/vdw/"
          description: "Веб-рисование Microsoft Visio 2010"
        # format loop
        - name: "Java-просмотрщик EPUB-файлов"
          link: "/viewer/java/epub/"
          description: "Формат файла цифровой электронной книги"
############################# Back to top ###############################
back_to_top:
    enable: true
---
