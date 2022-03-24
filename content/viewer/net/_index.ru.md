---
############################# Static ############################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: ".NET Document Viewer API, Render PDF Word Excel Image HTML Diagram"
head_description: "Средство просмотра файлов C# ASP.NET и API рендеринга. Добавить средство просмотра PDF, средство просмотра Word, средство просмотра Excel, средство просмотра изображений, средство просмотра HTML, функции просмотра электронной почты в приложениях .NET."

############################# Header ############################
title: "Рендеринг и отображение документов через .NET API"
description: ".NET Document Viewer API для преобразования более 170 форматов документов в PDF, HTML и изображения с мощными параметрами конфигурации."
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
        image: "/border/groupdocs-viewer-net.svg"
        product: "GroupDocs.Viewer"
        platform: ".NET"

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
              text: "Support"

            # button loop
            - link: "https://products.groupdocs.app/viewer"
              text: "Live Demo"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Pricing"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# Обзор ############################
overview:
    enable: true
    content: |
      API-интерфейсы GroupDocs.Viewer для .NET помогают создавать мощные приложения на C#, ASP.NET и других технологиях на основе .NET, которые могут обрабатывать и отображать документы и изображения более чем 170 форматов файлов без установки какого-либо внешнего программного обеспечения. Библиотека просмотра файлов растрирует документы, а затем преобразует их в SVG+HTML+CSS, чтобы оптимизировать общий процесс рендеринга документов для просмотра бизнес-документов, изображений, текстовых файлов, диаграмм, графики, вложений электронной почты и файлов PDF со скоростью, истинным текстом и высокой точности внутри ваших приложений. У вас есть возможность добавить функции просмотра и чтения документов в свои приложения для отображения всего документа, частичного документа, определенного диапазона страниц/ячеек, отдельного слоя документа, с аннотациями и комментариями или без них для поддерживаемых форматов файлов.  

      GroupDocs.Viewer для .NET по умолчанию кэширует вывод визуализированных документов на локальный диск. Также поддерживается любой тип внешнего кэш-хранилища путем реализации соответствующих интерфейсов — Amazon S3, Dropbox, Google Drive, Windows Azure, Redis или любых других.
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          Ниже приведен обзор GroupDocs.Viewer для .NET:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Обзор"
          content: |
            * Показать более 170 типов документов
            * Получить HTML, изображение, PDF-версию
            * Rotate &amp; Reorder
            * Применить водяной знак
            * Кэш для быстрого процесса
            * Добавить пользовательские шрифты
            * Применение стандартов кодирования
            * Пользовательский обработчик входных данных
            * Рендеринг с отслеживанием изменений
            * Отобразить как адаптивный HTML
            * Render PDF &amp; CAD Layers
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Viewer для .NET поддерживает просмотр всех популярных [форматов файлов документов](https://docs.groupdocs.com/viewer/net/supported-document-formats/). Всего несколькими строками кода добавьте средство просмотра PDF, Microsoft Office Word, электронные таблицы Excel, изображения, HTML, электронную почту Outlook, OneNote, Project и возможности просмотра графики в свои приложения .NET.

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
                * **PDF Formats:** PDF, TEX, XPS, OXPS
                * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG, OTG, FODP, FODG
                * **Delimiter-Separated Values:** CSV, TSV
                * **Web:** HTML, MHT, MHTML
                * **Metafile:** WMF, EMF, CGM, WMZ, EMZ
                * **PostScript:** PS, EPS
                * **Archives:** ZIP, TAR, BZ2, GZ, RAR, RAR5
                * **Various:** OBJ, EPUB, MOBI, DjVu, XML, VCF, VCARD, NUMBER, NSF

        right:
          enable: true
          table:
            # table loop
            - title: "Изображения, графики и диаграммы"
              content: |
                * **Images:** BMP, GIF, JPG, PNG, TIFF, multi-page TIFF, WebP, DNG, DIB, DCM
                * **Windows Icon:** ICO
                * **Scalable Vector Graphics:** SVG, CDR, CMX, IGS, SVGZ
                * **Jpeg2000:** JP2, J2C, J2K, JPC, JPF, JPX, JPM
                * **Adobe Photoshop:** PSD, PSB
                * **Printer Command Language:** PCL
                * **Stereo Lithography (3D Printing):** STL
                * **Industry Foundation Classes:** IFC
                * **Medical Imaging:** DICOM
                * **Plotter Documents:** PLT, HPG
                * **Autodesk Design Web Formats:** DWF, DWG
                * **AutoCAD Drawing:** DGN, DWT, IFC, STL, CF2
                * **ISFF-based DGN (V7):** DGN

            # table loop
            - title: "Форматы языков программирования"
              content: |
                * **C/C++/C# Files:** C, CC, CS, CPP, CXX, C#, H, HH, M, MM
                * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES
                * **Various:** VB, PHP, SQL, PL, PY, PV, RB, RST, SASS, SCALA, SCM, SCRIPT, AS, AS3, ASM, BAT, CMAKE, CSS, DIFF, ERB, GROOVY, HAML, LESS, LOG, M, MAKE, MD, ML, MM, SH, SML, VIM, YAML

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Viewer for .NET поддерживает следующие Операционные системы, Frameworks & Менеджер пакетовs:
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Операционные системы"
              content: |
                * Рабочий стол Windows
                * Windows-сервер
                * Microsoft Azure
                * линукс

            # table loop
            - icon: "fas fa-code"
              title: "Поддерживаемые платформы"
              content: |
                * .NET Framework 2.0 или выше
                * .NET Core 3.1
                * .NET 5 или выше

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-box"
              title: "Менеджер пакетов"
              content: |
                * NuGet

            # table loop
            - icon: "fas fa-tools"
              title: "Среды разработки"
              content: |
                * Microsoft Visual Studio
                * Код Visual Studio
                * .NET CLI

############################# Функции ############################
features:
    enable: true
    title: "GroupDocs.Viewer for .NET Функции"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "Растрируйте документы и конвертируйте их в SVG, HTML и CSS"

      # feature loop
      - icon: "fas fa-eye"
        content: "Преобразование текста в HTML и рендеринг документов для получения представления HTML, изображения или PDF"

      # feature loop
      - icon: "fas fa-bolt"
        content: "Более быстрое время загрузки с использованием кэшированных версий документов"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "Конвертировать презентации с фигурами и текстом с 3D-эффектами"

      # feature loop
      - icon: "fas fa-code"
        content: "Кодируйте документы Word, Excel и электронной почты в соответствии с желаемым стандартом кодирования"

      # feature loop
      - icon: "fas fa-cloud"
        content: "Рендеринг документов, расположенных на FTP или в облачных хранилищах"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "Исключение шрифтов при рендеринге в HTML для уменьшения результирующего размера файла"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "Сократите вывод CSS и HTML, удалив комментарии, лишние пробелы и т. д."

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "Чтение текста, содержащегося в исходном документе, через его координаты"

      # feature loop
      - icon: "fas fa-border-all"
        content: "Показать/скрыть линии сетки листов Excel в выходном представлении"

      # feature loop
      - icon: "fas fa-wrench"
        content: "Укажите количество строк в листе Excel, которое будет отображаться на каждой странице."

      # feature loop
      - icon: "fas fa-columns"
        content: "Игнорировать пустые столбцы при рендеринге электронных таблиц"

      # feature loop
      - icon: "fas fa-file-word"
        content: "Преобразование документов Word в HTML-страницы, изображения или PDF с отслеживанием изменений"

      # feature loop
      - icon: "fas fa-envelope"
        content: "Визуализация вложений электронной почты в виде исходных файлов, изображений или в HTML-представлении"

      # feature loop
      - icon: "fas fa-print"
        content: "Установите ограничения на печать PDF-документов"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "Рендеринг содержимого/файлов, содержащихся в ZIP-архивах, в виде вложений"

      # feature loop
      - icon: "fas fa-lock"
        content: "Получение вложений из защищенных паролем документов"

      # feature loop
      - icon: "fas fa-file-code"
        content: "Отображать форматы файлов языков программирования как обычный текст"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "Настройка цветов фона при просмотре чертежей САПР"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "Просмотр документов Excel и преобразование в PDF, HTML, JPG и PNG"

      # feature loop
      - icon: "fas fa-heading"
        content: "Получить имена рабочих листов из файла Excel — отображать заголовки столбцов электронной таблицы и номера строк"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "Просмотр и преобразование документов Microsoft Project с помощью заметок"

      # feature loop
      - icon: "fas fa-cube"
        content: "Преобразование чертежей САПР в формат SVG для лучшего просмотра и масштабирования"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "Выберите визуализацию рисунков Visio без схемы"

    больше_функций:
      # more_feature_loop
      - title: "Просматривайте документы эффективно и надежно"
        content: |
          С помощью API GroupDocs.Viewer вы можете эффективно и надежно отображать более 170 форматов документов с сохранением целостности содержимого и структуры документа. Следующий пример кода показывает, насколько просто просмотреть HTML-представление документа DOCX:

          ```cs
          // Создать средство просмотра
          using (Viewer viewer = new Viewer("sample.docx")
          {
              // Установить параметры просмотра
              HtmlViewOptions options = HtmlViewOptions.ForEmbeddedResources();
              // Преобразование файла в HTML со встроенными ресурсами
              viewer.View(options);
          }
          ```
      # more_feature_loop
      - title: "Применить преобразование к визуализируемому выводу"
        content: "Вы можете выполнять различные преобразования визуализированного выходного документа с помощью GroupDocs.Viewer для .NET API. Эти параметры преобразования дают вам контроль над тем, как вы представляете визуализированный вывод для отображения. Доступные преобразования: опция поворота страницы, опция изменения порядка страниц и применение текстового водяного знака."

      # more_feature_loop
      - title: "Работа с файлами данных Outlook"
        content: "GroupDocs.Viewer для .NET API может отображать элементы в файлах данных Outlook (OST/PST) в виде файлов PDF, HTML и файлов изображений. Наш Viewer API также имеет возможность получить список папок, содержащихся в файлах данных Outlook. Используя GroupDocs.Viewer для .NET API, вы можете указать папку для отображения из файлов данных Outlook. Кроме того, вы также можете получать сообщения электронной почты, содержащиеся в форматах OST/PST, в виде вложений. GroupDocs.Viewer для .NET также позволяет фильтровать сообщения в форматах OST/PST по теме, содержанию или отправителю."

      # more_feature_loop
      - title: "Работа с CAD-документами"
        content: "GroupDocs.Viewer для .NET API может отображать модель и все непустые макеты или отображать определенный макет файла САПР. GroupDocs.Viewer для .NET API также поддерживает мозаичный рендеринг или рендеринг по координатам документов САПР в изображение, HTML или PDF. Вы также можете получить статусы слоев для документов САПР.."

############################# Testimonials ###############################
testimonials:
  enable: true

  testimonial:
    # testimonial item loop
    - name: "Mats Oustad"
      designation: "Senior Consultant/Partner at Novanet AS"
      content: "После внедрения и использования GroupDocs.Viewer для .NET в проекте все работает очень хорошо. Я проверил с большим количеством документов и до сих пор все хорошо. Все, что я добавил, хорошо отображается и выглядит так же хорошо, как в программе просмотра PDF или MS Word.."
              
    # testimonial item loop
    - name: "Martin Lasarga"
      designation: "Product Manager at Axentria ECM by G.S.I."
      content: "Отличный сервис и отличные продукты. Они были чрезвычайно полезны и отзывчивы во время процесса внедрения GroupDocs.Viewer для .NET, не могу рекомендовать их достаточно высоко."

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Viewer предлагает API для просмотра документов для других популярных сред разработки."

    solution:
        # solution loop
        - img_alt: "GroupDocs.Viewer for Java"
          image: "/border/groupdocs-viewer-java.svg"
          product: "GroupDocs.Viewer"
          platform: "Java"
          link: "/viewer/java/"

############################# Back to top ###############################
back_to_top:
  enable: true
---
