---
############################# Static ############################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

lang: ru
product: "Viewer"
product_tag: "viewer"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "Java Document Viewer API для PDF Word Excel HTML изображения и сообщения электронной почты"
head_description: "Просмотрщик документов Java и API рендеринга файлов. Добавьте средство просмотра PDF, средство просмотра Word, средство просмотра Excel, средство просмотра изображений, средство просмотра HTML, средство просмотра электронной почты в приложениях Java."

############################# Header ############################
title: "Java API для рендеринга и отображения документов"
description: "Библиотека средства просмотра документов для разработки приложений Java, которые изначально отображают, просматривают и манипулируют многоформатными документами, поддерживающими более 170 форматов файлов."
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Download Free Trial"
    link: "https://downloads.groupdocs.com/viewer/java"

############################# SubMenu ############################
submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Viewer for Java"
        image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-viewer-java.png"
        product: "GroupDocs.Viewer"
        platform: "Java"

    middle:
        button:
            # button loop
            - link: "#overview"
              text: "Обзор"

            # button loop
            - link: "#features"
              text: "Функции"

            # button loop
            - link: "#support"
              text: "Поддерживать"

            # button loop
            - link: "https://products.groupdocs.app/viewer/total"
              text: "Живая демонстрация"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/java"
              text: "Цены"

    right:
        link_download: "https://releases.groupdocs.com/viewer/java/"
        link_learn: "https://docs.groupdocs.com/viewer/java/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    content: |
      GroupDocs.Viewer для Java сочетает в себе мощный набор API-интерфейсов для просмотра документов для отображения изображений и форматов документов в ваших приложениях Java без необходимости установки дополнительного программного обеспечения. Он изначально растрирует документы и преобразует их в SVG+HTML+CSS, чтобы улучшить качество просмотра документов, обеспечивая при этом истинный текст и высокое качество вывода. Используя API рендеринга документов, вы можете быстро просматривать PDF, HTML, XML, Microsoft Office Word, рабочие листы Excel, презентации PowerPoint, электронные письма Outlook, диаграммы Visio, Project, метафайлы, изображения и различные другие форматы файлов с легкостью и меньшими опасностями программирования. Он также может отображать файлы, защищенные паролем, и позволяет получить представление документа в виде HTML, изображения или формы PDF после рендеринга. Наша библиотека для просмотра файлов легко настраивается, так как позволяет отображать весь документ или отображать его частично для ускорения процесса. С помощью API GroupDocs.Viewer для Java вы можете просматривать страницы, определенный диапазон ячеек в электронной таблице или даже визуализировать отдельный слой документа в таких форматах, как PDF и CAD.  

      GroupDocs.Viewer for Java API позволяет отображать документы с аннотациями или комментариями или без них для поддерживаемых форматов файлов. Он также позволяет добавлять каталоги пользовательских шрифтов и извлекать основную информацию о документе, такую ​​как тип файла, расширение, имя, количество страниц и т. д.  

      GroupDocs.Viewer для Java совместим со всеми версиями Java и поддерживает популярные операционные системы (Windows, Linux, macOS), способные запускать среду выполнения Java.
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          Ниже приводится обзор GroupDocs.Viewer для Java:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Обзор"
          content: |
            * Показать более 170 типов документов 
            * Получить HTML, изображение, PDF-версию 
            * Повернуть и изменить порядок 
            * Применить водяной знак 
            * Кэш для быстрого процесса 
            * Добавить пользовательские шрифты 
            * Применение стандартов кодирования 
            * Пользовательский обработчик входных данных 
            * Рендеринг с отслеживанием изменений 
            * Отобразить как адаптивный HTML 
            * Рендеринг слоев PDF и CAD 
            * Рендеринг защищенных файлов 
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Viewer для Java поддерживает все популярные форматы файлов документов, включая: Microsoft Office, изображения, диаграммы и многие другие.

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
            - title: "Другие форматы"
              content: |
                * **Файлы макета страницы:** PDF, TEX, XPS, OXPS
                * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG, OTG, FODP, FODG
                * **Значения, разделенные разделителем:** CSV, TSV
                * **Интернет:** HTML, MHT, MHTML
                * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
                * **PostScript:** PS, EPS
                * **Архивы:** ZIP, TAR, BZ2, GZ, RAR, RAR5
                * **Различный:** OBJ, EPUB, MOBI, DjVu, XML, VCF, VCARD, NUMBERS, NSF

        right:
          enable: true
          table:
            # table loop
            - title: "Изображения, графики и диаграммы"
              content: |
                * **Изображений:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB
                * **Значок Windows:** ICO
                * **Масштабируемая векторная графика:** SVG, CDR, CMX, IGS, SVGZ
                * **JPEG2000:** JP2, J2C, J2K, JPC, JPF, JPX, JPM
                * **Adobe Photoshop:** PSD, PSB
                * **Язык команд принтера:** PCL
                * **Стереолитография (3D-печать):** STL
                * **Классы отраслевой основы:** IFC
                * **Медицинская визуализация:** DICOM
                * **Плоттер Документы:** PLT, HPG
                * **Веб-форматы Autodesk Design:** DWF, DWG
                * **Чертеж Автокад:** DWT, IFC, STL, CF2
                * **DGN на основе ISFF (V7):** DGN

            # table loop
            - title: "Форматы языков программирования"
              content: |
                * **Файлы C/C++/C#:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
                * **Файлы Java/JavaScript:** JAVA, JS, JSON, PROPERTIES
                * **Различный:** VB, PHP, SQL, PL, PY, PV, RB, RST, SASS, SCALA, SCM, SCRIPT, AS, AS3, ASM, BAT, CMAKE, CSS, DIFF, ERB, GROOVY, HAML, LESS, LOG, M, MAKE, MD, ML, MM, SH, SML, VIM, YAML

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Viewer для Java поддерживает следующие операционные системы, платформы и менеджеры пакетов:
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Операционные системы"
              content: |
                * Microsoft Windows Server 2003 и более поздние версии 
                * Microsoft Windows XP и более поздние версии 
                * Microsoft Windows 10 и 11 
                * Linux (Ubuntu, OpenSUSE, CentOS и другие) 
                * Mac OS X 

            # table loop
            - icon: "fas fa-code"
              title: "Поддерживаемые платформы"
              content: |
                * J2SE 8.0 (1.8) или выше (например, Java 17) 

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-cogs"
              title: "Среды разработки"
              content: |
                * NetBeans
                * IntelliJ IDEA
                * Eclipse

            # table loop
            - icon: "fas fa-tools"
              title: "Инструмент автоматизации сборки"
              content: |
                * Maven
                * Gradle

############################# Features ############################
features:
    enable: true
    title: "Возможности GroupDocs.Viewer для Java"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "Средство просмотра HTML, PDF, изображений, Word, Excel и других форматов документов"

      # feature loop
      - icon: "fas fa-eye"
        content: "Преобразование файлов чертежей AutoCAD (DWG) в формат SVG"

      # feature loop
      - icon: "fas fa-bolt"
        content: "Настройте цвет фона преобразованного файла"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "Растеризация и преобразование документов в SVG, HTML и CSS"

      # feature loop
      - icon: "fas fa-code"
        content: "Получите представление документов в формате HTML, изображения или PDF посредством рендеринга"

      # feature loop
      - icon: "fas fa-cloud"
        content: "Кэшированные версии документов для ускорения загрузки"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "Настройка каталогов пользовательских шрифтов"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "Применение стандартов кодирования к документам Word, Excel и электронной почте"

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "Удаленно отображать документы на FTP или в облачном хранилище"

      # feature loop
      - icon: "fas fa-border-all"
        content: "Удалить или сохранить аннотации и комментарии во время рендеринга"

      # feature loop
      - icon: "fas fa-wrench"
        content: "Отображение страниц документа как отдельных HTML-страниц"

      # feature loop
      - icon: "fas fa-columns"
        content: "Рендеринг скрытых слайдов и страниц и применение изменения порядка страниц к визуализируемому документу"

      # feature loop
      - icon: "fas fa-file-word"
        content: "Рендеринг диапазона страниц, определенных страниц или всех страниц в HTML"

      # feature loop
      - icon: "fas fa-envelope"
        content: "Отображение или скрытие комментариев к документу"

      # feature loop
      - icon: "fas fa-print"
        content: "Создание адаптивного HTML для некоторых форматов документов с помощью рендеринга"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "Уменьшите результирующий размер файла отображаемого HTML, исключив шрифты"

      # feature loop
      - icon: "fas fa-lock"
        content: "Удалите комментарии, лишние пробелы и т. д., чтобы минимизировать вывод HTML и CSS."

      # feature loop
      - icon: "fas fa-file-code"
        content: "Используйте координаты исходного документа для чтения содержащегося текста"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "Показать/скрыть границу ячейки в листах Excel визуализированного вывода"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "Визуализация определенного количества строк каждой страницы в листе Excel"

      # feature loop
      - icon: "fas fa-heading"
        content: "Визуализация модели и всех непустых макетов или определенного макета файла САПР"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "Визуализация элементов в файлах данных Outlook (OST/PST) в формате PDF"

      # feature loop
      - icon: "fas fa-cube"
        content: "Мозаичный рендеринг или рендеринг по координатам документов САПР в виде изображения, HTML или PDF"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "Установите ограничения печати при рендеринге в PDF"

    more_feature:
      # more_feature_loop
      - title: "Эффективный и надежный API для просмотра документов"
        content: |
          GroupDocs.Viewer для Java API можно использовать для просмотра, обработки и отображения документов более чем 150 различных форматов файлов. Это делается надежно и эффективно, сохраняя содержимое и структуру документа нетронутыми. В следующем примере показан уровень простоты, с которой GroupDocs.Viewer для API Java обрабатывает файл DOCX как файл изображения с помощью Java:

          ```java
          // Initialize Viewer
          Viewer viewer = new Viewer("invoice.docx");
          // Create view options
          PdfViewOptions viewOptions = new PdfViewOptions();
          // Convert file to PDF and check the output in the current directory
          viewer.view(viewOptions);
          ```
      # more_feature_loop
      - title: "Выполнение преобразований при рендеринге документов"
        content: "GroupDocs.Viewer for Java API предлагает различные параметры преобразования, которые можно применить к визуализируемому документу для более индивидуального просмотра и отображения. Вы можете поворачивать страницы, указав угол. Вы можете заказать отображаемые страницы. Применяйте определенный текст в качестве водяного знака к обработанным страницам или изображениям. С помощью API GroupDocs.Viewer для Java у вас также есть возможность добавлять пользовательские шрифты в отображаемый документ."

      # more_feature_loop
      - title: "Работа с вложениями электронной почты"
        content: "GroupDocs.Viewer for Java API позволяет получать отдельные или все вложения электронной почты. Как только вы получите необходимые вложения электронной почты, вы можете преобразовать эти вложенные файлы в изображения или HTML."

############################# Support ############################
support:
    enable: true

############################# Solutions ##########################
solutions:
    enable: true
    title: "GroupDocs.Viewer предлагает API для просмотра документов для других популярных сред разработки."

    solution:
        # solution loop
        - img_alt: "GroupDocs.Viewer for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-viewer-net.png"
          product: "GroupDocs.Viewer"
          platform: ".NET"
          link: "/viewer/net/"

############################# Back to top ##########################
back_to_top:
  enable: true
---