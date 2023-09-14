---
############################# Static ##########################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

lang: ru
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: ".NET Document Viewer API, рендеринг PDF, Word, Excel, изображения, HTML-диаграммы"
head_description: "Средство просмотра файлов C# ASP.NET и API рендеринга. Добавьте средства просмотра PDF, средства просмотра Word, средства просмотра Excel, средства просмотра изображений, средства просмотра HTML, функции просмотра электронной почты в приложениях .NET."

############################# Header ##########################
title: "Рендеринг и отображение документов через .NET API"
description: ".NET Document Viewer API для преобразования более 190 форматов документов в PDF, HTML и изображения с мощными параметрами конфигурации."
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Download Free Trial"
    link: "https://downloads.groupdocs.com/viewer/net"

############################# SubMenu #########################
submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Viewer for .NET"
        image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-viewer-net.png"
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
              text: "Поддерживать"

            # button loop
            - link: "https://products.groupdocs.app/viewer/total"
              text: "Живая демонстрация"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Цены"

    right:
        link_download: "https://www.nuget.org/packages/GroupDocs.Viewer"
        link_learn: "https://docs.groupdocs.com/viewer/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    content: |
      API-интерфейсы GroupDocs.Viewer для .NET помогают создавать мощные приложения на C#, ASP.NET и других технологиях на основе .NET, которые могут обрабатывать и отображать документы и изображения более чем 190 форматов файлов без установки какого-либо внешнего программного обеспечения. Библиотека просмотра файлов растрирует документы, а затем преобразует их в SVG+HTML+CSS, чтобы оптимизировать общий процесс рендеринга документов для просмотра бизнес-документов, изображений, текстовых файлов, диаграмм, графики, вложений электронной почты и файлов PDF со скоростью, истинным текстом и высокой точности внутри ваших приложений. У вас есть возможность добавить функции просмотра и чтения документов в свои приложения для отображения всего документа, частичного документа, определенного диапазона страниц/ячеек, отдельного слоя документа, с аннотациями и комментариями или без них для поддерживаемых форматов файлов.
       
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
            * Показать более 190 типов документов 
            * Получить файл в формате HTML, Image, PDF 
            * Повернуть и изменить порядок 
            * Применить водяной знак 
            * Кэш для быстрого процесса 
            * Добавить пользовательские шрифты 
            * Применение стандартов кодирования 
            * Пользовательский обработчик входных данных 
            * Рендеринг с отслеживанием изменений 
            * Отобразить как адаптивный HTML 
            * Рендеринг слоев PDF и CAD 
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Viewer для .NET поддерживает просмотр всех популярных форматов файлов документов. Всего несколькими строками кода добавьте средство просмотра PDF, Microsoft Office Word, электронные таблицы Excel, изображения, HTML, электронную почту Outlook, OneNote, Project и возможности просмотра графики в свои приложения .NET.

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
            - title: "Other Formats"
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
          GroupDocs.Viewer для .NET поддерживает следующие операционные системы, платформы и менеджеры пакетов:
        
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
                * Visual Studio Code
                * .NET CLI

############################# Features ############################
features:
    enable: true
    title: "GroupDocs.Viewer для функций .NET"

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
        content: "Преобразование презентаций с фигурами и текстом с 3D-эффектами"

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

    more_feature:
      # more_feature_loop
      - title: "Просматривайте документы эффективно и надежно"
        content: |
          С помощью API GroupDocs.Viewer вы можете эффективно и надежно отображать более 190 форматов документов с сохранением целостности содержимого и структуры документа. Следующий пример кода показывает, насколько просто просмотреть HTML-представление документа DOCX:

          ```cs
          // Instantiate viewer
          using (Viewer viewer = new Viewer("invoice.docx"))
          {
              // Set view options
              HtmlViewOptions options = HtmlViewOptions.ForEmbeddedResources();
              // Convert file to HTML with embedded resources
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
        content: "GroupDocs.Viewer для .NET API может отображать модель и все непустые макеты или отображать определенный макет файла САПР. GroupDocs.Viewer для .NET API также поддерживает мозаичный рендеринг или рендеринг по координатам документов САПР в изображение, HTML или PDF. Вы также можете получить статусы слоев для документов САПР."

############################# Testimonials ###############################
testimonials:
  enable: true

  testimonial:
    # testimonial item loop
    - name: "Margot Baill"
      designation: "Директор по развитию продуктов Hireology"
      content: "Интеграция GroupDocs.Viewer for Cloud API была простой благодаря их фантастическому Ruby SDK. Не так уж много компаний готовы работать с нами над тем, что мы хотим. Это отличное партнерство."

    # testimonial item loop
    - name: "Mats Oustad"
      designation: "Старший консультант/партнер в Novanet AS"
      content: "После внедрения и использования GroupDocs.Viewer для .NET в проекте все работает очень хорошо. Я проверил с большим количеством документов и до сих пор все хорошо. Все, что я добавил, хорошо отображается и выглядит так же хорошо, как в программе просмотра PDF или MS Word."
              
    # testimonial item loop
    - name: "Martin Lasarga"
      designation: "Менеджер по продукту в Axentria ECM by G.S.I."
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
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-viewer-java.png"
          product: "GroupDocs.Viewer"
          platform: "Java"
          link: "/viewer/java/"

############################# Back to top ###############################
back_to_top:
  enable: true
---
