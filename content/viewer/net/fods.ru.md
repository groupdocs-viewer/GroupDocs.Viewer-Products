---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: ru

############################# Head #############################
head_title: ".NET FODS Viewer API — чтение, просмотр, рендеринг на C# VB.NET"
head_description: "API-интерфейс средства просмотра документов .NET для чтения, рендеринга и отображения FODS в приложениях C#, ASP.NET, VB.NET и .NET Core любого типа."

############################# Header ############################
title: "FODS Средство просмотра файлов для приложений C# .NET" 
description: "API-интерфейс средства просмотра документов .NET для чтения, рендеринга и отображения файла FODS в приложениях C#, ASP.NET, VB.NET и .NET Core любого типа. Просматривайте визуализированные файлы с истинным форматированием и макетом в формате HTML5, PDF или в виде изображения, используя несколько строк кода." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Скачать бесплатную пробную версию"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "О GroupDocs.Viewer для .NET API" 
    content: |
        Начните просматривать более 190 популярных форматов документов в своих приложениях .NET с помощью GroupDocs.Viewer для API .NET, добавив несколько строк кода. Разработчики могут легко отображать PDF, Word Processing, электронные таблицы Excel, презентации, Visio, Project, Outlook и многие другие популярные форматы документов в режимах HTML5, изображений или PDF. Рендеринг документа быстрый, идентичный оригинальному исходному файлу и не требует установки дополнительного программного обеспечения или каких-либо других внешних библиотек.

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

############################# Steps ############################
steps:
    enable: true
    title_left: "Шаги для рендеринга файла FODS в C#" 
    content_left: |
        С помощью [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/) вы можете преобразовать FODS в HTML, JPEG, PNG или PDF за несколько шагов.

        * Установите [GroupDocs.Viewer для .NET](https://www.nuget.org/packages/groupdocs.viewer), используя ваш любимый менеджер пакетов. 
        * Создайте экземпляр класса Viewer и загрузите файл FODS с полным путем. 
        * Установите параметры для преобразования файла FODS в формат HTML, PNG, JPEG или PDF. 
        * Рендерим файл и проверяем вывод в текущем каталоге. 
        
    title_right: "Системные Требования" 
    content_right: |
        API GroupDocs.Viewer для .NET поддерживаются на всех основных платформах и операционных системах. Перед выполнением приведенного ниже кода убедитесь, что в вашей системе установлены следующие предварительные компоненты.

        * Операционные системы: Microsoft Windows, Linux, MacOS 
        * Среды разработки: Microsoft Visual Studio, Visual Studio Code, .NET CLI 
        * Фреймворки: .NET Framework, .NET Standard, .NET Core, .NET 
    code: |
        ```cs
                        
            // Set up input FODS file
            string filePath = "input.fods";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render FODS file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "FODS Демо-версия программы просмотра"
    content: |
        Просмотрите файл FODS прямо сейчас, посетив веб-сайт [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/fods).
    lang: "ru"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Рендеринг и просмотр файлов других форматов с помощью C#"
    exclude: "FODS"
    content: |
        Многоформатный API для просмотра документов и изображений для .NET. Просмотрите некоторые из популярных форматов файлов ниже без каких-либо внешних средств просмотра.
    format: 
        # format loop 1
        - name: "Рендеринг DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Документ Microsoft Word с открытым XML" 

        # format loop 2
        - name: "Рендеринг CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "Файл CorelDRAW" 

        # format loop 3
        - name: "Рендеринг PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "Презентация PowerPoint Open XML" 

        # format loop 4
        - name: "Рендеринг XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Электронная таблица Microsoft Excel Open XML" 

        # format loop 5
        - name: "Визуализация DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "Чертеж Автокад"

        # format loop 6
        - name: "Рендеринг XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "XML-файл"

        # format loop 7
        - name: "Рендер PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Документ Adobe Photoshop"

        # format loop 8
        - name: "Рендеринг файла Adobe Illustrator"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Работа Adobe Illustrator"

        # format loop 9
        - name: "Рендеринг DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Документ Microsoft Word" 

        # format loop 10
        - name: "Рендеринг TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Простой текстовый файл" 

        # format loop 11
        - name: "Визуализировать DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Файл формата обмена чертежами"  
          
        # format loop 12
        - name: "Рендеринг VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "файл визитной карточки"  
              
        # format loop 13
        - name: "Визуализировать SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Масштабируемая векторная графика" 
          
        # format loop 14
        - name: "Рендеринг HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Файл языка гипертекстовой разметки" 
          
        # format loop 15
        - name: "Рендер PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Файл переносимого формата документа"
          
        # format loop 16
        - name: "Рендеринг JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "Изображение в формате JPEG"
          
        # format loop 17
        - name: "Рендер PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Портативная сетевая графика" 
          
        # format loop 18
        - name: "Рендер EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "Сообщение электронной почты" 
          
        # format loop 19
        - name: "Рендеринг в формате RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Файл форматированного текста" 
          
        # format loop 20
        - name: "Рендеринг ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "Текстовый документ OpenDocument" 
          
        # format loop 21
        - name: "Отобразить CSV-файл"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Файл значений, разделенных запятыми" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
