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
                * **Word:** [DOC](https://products.groupdocs.com/ru/viewer/net/doc/), [DOCX](https://products.groupdocs.com/ru/viewer/net/docx/), [DOCM](https://products.groupdocs.com/ru/viewer/net/docm/), [DOT](https://products.groupdocs.com/ru/viewer/net/dot/), [DOTX](https://products.groupdocs.com/ru/viewer/net/dotx/), [DOTM](https://products.groupdocs.com/ru/viewer/net/dotm/), [RTF](https://products.groupdocs.com/ru/viewer/net/rtf/), [TXT](https://products.groupdocs.com/ru/viewer/net/txt/)
                * **Excel:** [XLS](https://products.groupdocs.com/ru/viewer/net/xls/), [XLSX](https://products.groupdocs.com/ru/viewer/net/xlsx/), [XLSM](https://products.groupdocs.com/ru/viewer/net/xlsm/), [XLSB](https://products.groupdocs.com/ru/viewer/net/xlsb/), [XLTM](https://products.groupdocs.com/ru/viewer/net/xltm/), [XLT](https://products.groupdocs.com/ru/viewer/net/xlt/), [XLTM](https://products.groupdocs.com/ru/viewer/net/xltm/), [XLTX](https://products.groupdocs.com/ru/viewer/net/xltx/), [XLAM](https://products.groupdocs.com/ru/viewer/net/xlam/), [SXC](https://products.groupdocs.com/ru/viewer/net/sxc/), [SpreadsheetML](https://products.groupdocs.com/ru/viewer/net/xml/)
                * **PowerPoint:** [PPT](https://products.groupdocs.com/ru/viewer/net/ppt/), [PPTX](https://products.groupdocs.com/ru/viewer/net/pptx/), [PPS](https://products.groupdocs.com/ru/viewer/net/pps/), [PPSX](https://products.groupdocs.com/ru/viewer/net/ppsx/), [PPSM](https://products.groupdocs.com/ru/viewer/net/ppsm/), [POT](https://products.groupdocs.com/ru/viewer/net/pot/), [POTM](https://products.groupdocs.com/ru/viewer/net/potm/), [POTX](https://products.groupdocs.com/ru/viewer/net/potx/), [PPTM](https://products.groupdocs.com/ru/viewer/net/pptm/)
                * **Visio:** [VSD](https://products.groupdocs.com/ru/viewer/net/vsd/), [VDX](https://products.groupdocs.com/ru/viewer/net/vdx/), [VSS](https://products.groupdocs.com/ru/viewer/net/vss/), [VSSX](https://products.groupdocs.com/ru/viewer/net/vssx/), [VSX](https://products.groupdocs.com/ru/viewer/net/vsx/), [VST](https://products.groupdocs.com/ru/viewer/net/vst/), [VSTX](https://products.groupdocs.com/ru/viewer/net/vstx/), [VTX](https://products.groupdocs.com/ru/viewer/net/vtx/), [VSDX](https://products.groupdocs.com/ru/viewer/net/vsdx/), [VDW](https://products.groupdocs.com/ru/viewer/net/vdw/), [VSTM](https://products.groupdocs.com/ru/viewer/net/vstm/), [VSSM](https://products.groupdocs.com/ru/viewer/net/vssm/), [VSDM](https://products.groupdocs.com/ru/viewer/net/vsdm/)
                * **Project:** [MPP](https://products.groupdocs.com/ru/viewer/net/mpp/), [MPT](https://products.groupdocs.com/ru/viewer/net/mpt/), [MPX](https://products.groupdocs.com/ru/viewer/net/mpx/)
                * **Outlook:** [MSG](https://products.groupdocs.com/ru/viewer/net/msg/), [EML](https://products.groupdocs.com/ru/viewer/net/eml/), [EMLX](https://products.groupdocs.com/ru/viewer/net/emlx/), [PST](https://products.groupdocs.com/ru/viewer/net/pst/), [OST](https://products.groupdocs.com/ru/viewer/net/ost/)
                * **OneNote:** [ONE](https://products.groupdocs.com/ru/viewer/net/one/)

            # table loop
            - title: "Другие форматы"
              content: |
                * **PDF Formats:** [PDF](https://products.groupdocs.com/ru/viewer/net/pdf/), [TEX](https://products.groupdocs.com/ru/viewer/net/tex/), [XPS](https://products.groupdocs.com/ru/viewer/net/xps/), [OXPS](https://products.groupdocs.com/ru/viewer/net/oxps/), [OST](https://products.groupdocs.com/ru/viewer/net/ost/)
                * **OpenDocument:** [ODT](https://products.groupdocs.com/ru/viewer/net/odt/), [OTT](https://products.groupdocs.com/ru/viewer/net/ott/), [ODS](https://products.groupdocs.com/ru/viewer/net/ods/), [ODP](https://products.groupdocs.com/ru/viewer/net/odp/), [OTP](https://products.groupdocs.com/ru/viewer/net/otp/), [OTS](https://products.groupdocs.com/ru/viewer/net/ots/), [ODG](https://products.groupdocs.com/ru/viewer/net/odg/), [OTG](https://products.groupdocs.com/ru/viewer/net/otg/), [FODP](https://products.groupdocs.com/ru/viewer/net/fodp/), [FODG](https://products.groupdocs.com/ru/viewer/net/fodg/)
                * **Delimiter-Separated Values:** [CSV](https://products.groupdocs.com/ru/viewer/net/csv/), [TSV](https://products.groupdocs.com/ru/viewer/net/tsv/)
                * **Web:** [HTML](https://products.groupdocs.com/ru/viewer/net/html/), [MHT](https://products.groupdocs.com/ru/viewer/net/mht/), [MHTML](https://products.groupdocs.com/ru/viewer/net/mhtml/)
                * **Metafile:** [WMF](https://products.groupdocs.com/ru/viewer/net/wmf/), [EMF](https://products.groupdocs.com/ru/viewer/net/emf/), [CGM](https://products.groupdocs.com/ru/viewer/net/cgm/), [EMZ](https://products.groupdocs.com/ru/viewer/net/emz/), WMZ
                * **PostScript:** [PS](https://products.groupdocs.com/ru/viewer/net/ps/), [EPS](https://products.groupdocs.com/ru/viewer/net/eps/)
                * **Archives:** [ZIP](https://products.groupdocs.com/ru/viewer/net/zip/), [TAR](https://products.groupdocs.com/ru/viewer/net/tar/), [BZ2](https://products.groupdocs.com/ru/viewer/net/bz2/), [GZ](https://products.groupdocs.com/ru/viewer/net/gz/), [RAR](https://products.groupdocs.com/ru/viewer/net/rar/), [RAR5](https://products.groupdocs.com/ru/viewer/net/rar/)
                * **Various:** [OBJ](https://products.groupdocs.com/ru/viewer/net/obj/), [EPUB](https://products.groupdocs.com/ru/viewer/net/epub/), [MOBI](https://products.groupdocs.com/ru/viewer/net/mobi/), [DjVu](https://products.groupdocs.com/ru/viewer/net/djvu/), [XML](https://products.groupdocs.com/ru/viewer/net/xml/), [VCF](https://products.groupdocs.com/ru/viewer/net/vcf/), [VCARD](https://products.groupdocs.com/ru/viewer/net/vcard/), [NUMBERS](https://products.groupdocs.com/ru/viewer/net/numbers/), [NSF](https://products.groupdocs.com/ru/viewer/net/nsf/)

        right:
          enable: true
          table:
            # table loop
            - title: "Изображения, графики и диаграммы"
              content: |
                * **Images:** [BMP](https://products.groupdocs.com/ru/viewer/net/bmp/), [GIF](https://products.groupdocs.com/ru/viewer/net/gif/), [JPG](https://products.groupdocs.com/ru/viewer/net/jpg/), [PNG](https://products.groupdocs.com/ru/viewer/net/png/), [TIFF](https://products.groupdocs.com/ru/viewer/net/tiff/), [WebP](https://products.groupdocs.com/ru/viewer/net/webp/), [DNG](https://products.groupdocs.com/ru/viewer/net/dng/), [DIB](https://products.groupdocs.com/ru/viewer/net/dib/)
                * **Windows Icon:** [ICO](https://products.groupdocs.com/ru/viewer/net/ico/)
                * **Scalable Vector Graphics:** [SVG](https://products.groupdocs.com/ru/viewer/net/svg/), [CDR](https://products.groupdocs.com/ru/viewer/net/cdr/), [CMX](https://products.groupdocs.com/ru/viewer/net/cmx/), [IGS](https://products.groupdocs.com/ru/viewer/net/igs/), [SVGZ](https://products.groupdocs.com/ru/viewer/net/svgz/)
                * **Jpeg2000:** [JP2](https://products.groupdocs.com/ru/viewer/net/jp2/), [J2C](https://products.groupdocs.com/ru/viewer/net/j2c/), [J2K](https://products.groupdocs.com/ru/viewer/net/j2k/), [JPC](https://products.groupdocs.com/ru/viewer/net/jpc/), [JPF](https://products.groupdocs.com/ru/viewer/net/jpf/), [JPX](https://products.groupdocs.com/ru/viewer/net/jpx/), [JPM](https://products.groupdocs.com/ru/viewer/net/jpm/)
                 * **Adobe Photoshop:** [PSD](https://products.groupdocs.com/ru/viewer/net/psd/), [PSB](https://products.groupdocs.com/ru/viewer/net/psb/)
                * **Printer Command Language:** [PCL](https://products.groupdocs.com/ru/viewer/net/pcl/)
                * **Stereo Lithography (3D Printing):** [STL](https://products.groupdocs.com/ru/viewer/net/stl/)
                * **Industry Foundation Classes:** [IFC](https://products.groupdocs.com/ru/viewer/net/ifc/)
                * **Medical Imaging:** [DICOM](https://products.groupdocs.com/ru/viewer/net/dcm/)
                * **Plotter Documents:** [PLT](https://products.groupdocs.com/ru/viewer/net/plt/), [HPG](https://products.groupdocs.com/ru/viewer/net/hpg/)
                * **Autodesk Design Web Formats:** [DWF](https://products.groupdocs.com/ru/viewer/net/plt/), [DWG](https://products.groupdocs.com/ru/viewer/net/dwg/)
                * **AutoCAD Drawing:** [DWT](https://products.groupdocs.com/ru/viewer/net/dwt/), [IFC](https://products.groupdocs.com/ru/viewer/net/ifc/), [STL](https://products.groupdocs.com/ru/viewer/net/stl/), [CF2](https://products.groupdocs.com/ru/viewer/net/cf2/)
                * **ISFF-based DGN (V7):** [DGN](https://products.groupdocs.com/ru/viewer/net/dgn/)
            # table loop
            - title: "Форматы языков программирования"
              content: |
                * **C/C++/C# Files:** [C](https://products.groupdocs.com/ru/viewer/net/c/), [CC](https://products.groupdocs.com/ru/viewer/net/cc/), [C# ](https://products.groupdocs.com/ru/viewer/net/cs/), [CPP](https://products.groupdocs.com/ru/viewer/net/cpp/), [CXX](https://products.groupdocs.com/ru/viewer/net/cxx/), [CS](https://products.groupdocs.com/ru/viewer/net/cs/), [H](https://products.groupdocs.com/ru/viewer/net/h/), [HH](https://products.groupdocs.com/ru/viewer/net/hh/), [M](https://products.groupdocs.com/ru/viewer/net/m/), [MM](https://products.groupdocs.com/ru/viewer/net/mm/)
                * **Java/JavaScript Files:** [JAVA](https://products.groupdocs.com/ru/viewer/net/java/), [JS](https://products.groupdocs.com/ru/viewer/net/js/), [JSON](https://products.groupdocs.com/ru/viewer/net/json/), [PROPERTIES](https://products.groupdocs.com/ru/viewer/net/properties/)
                * **Various:** [VB](https://products.groupdocs.com/ru/viewer/net/vb/), [PHP](https://products.groupdocs.com/ru/viewer/net/php/), [SQL](https://products.groupdocs.com/ru/viewer/net/sql/), [PL](https://products.groupdocs.com/ru/viewer/net/pl/), [PY](https://products.groupdocs.com/ru/viewer/net/py/), [PV](https://products.groupdocs.com/ru/viewer/net/pv/), [RB](https://products.groupdocs.com/ru/viewer/net/rb/), [RST](https://products.groupdocs.com/ru/viewer/net/rst/), [SASS](https://products.groupdocs.com/ru/viewer/net/sass/), [SCALA](https://products.groupdocs.com/ru/viewer/net/scala/), [SCM](https://products.groupdocs.com/ru/viewer/net/scm/), [SCRIPT](https://products.groupdocs.com/ru/viewer/net/script/), [AS](https://products.groupdocs.com/ru/viewer/net/as/), [AS3](https://products.groupdocs.com/ru/viewer/net/as3/), [ASM](https://products.groupdocs.com/ru/viewer/net/asm/), [BAT](https://products.groupdocs.com/ru/viewer/net/bat/), [CMAKE](https://products.groupdocs.com/ru/viewer/net/cmake/), [CSS](https://products.groupdocs.com/ru/viewer/net/css/), [DIFF](https://products.groupdocs.com/ru/viewer/net/diff/), [ERB](https://products.groupdocs.com/ru/viewer/net/erb/), [GROOVY](https://products.groupdocs.com/ru/viewer/net/groovy/), [HAML](https://products.groupdocs.com/ru/viewer/net/haml/), [LESS](https://products.groupdocs.com/ru/viewer/net/less/), [LOG](https://products.groupdocs.com/ru/viewer/net/log/), [M](https://products.groupdocs.com/ru/viewer/net/m/), [MAKE](https://products.groupdocs.com/ru/viewer/net/make/), [MD](https://products.groupdocs.com/ru/viewer/net/md/), [ML](https://products.groupdocs.com/ru/viewer/net/ml/), [MM](https://products.groupdocs.com/ru/viewer/net/mm/), [SH](https://products.groupdocs.com/ru/viewer/net/sh/), [SML](https://products.groupdocs.com/ru/viewer/net/sml/), [VIM](https://products.groupdocs.com/ru/viewer/net/vim/), [YAML](https://products.groupdocs.com/ru/viewer/net/yaml/)

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
