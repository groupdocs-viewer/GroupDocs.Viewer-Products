---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: ru

############################# Head #############################
head_title: "Java HPG Viewer API — рендеринг и отображение HPG в приложениях Java"
head_description: "Просмотр HPG файлов в приложениях Java, J2EE, J2SE. Поддерживает просмотр более 170 форматов файлов документов и изображений в формате HTML, PDF или изображения с расширенными функциями для управления параметрами просмотра документов."

############################# Header ############################
title: "Рендеринг и просмотр HPG в Java" 
description: "Собственный и высокопроизводительный HPG API-интерфейс просмотра файлов для приложений на основе Java, J2EE и J2SE, поддерживающий широкий спектр дополнительных функций для настройки внешнего вида выходного формата документа." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Скачать бесплатную пробную версию"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "О GroupDocs.Viewer для Java API" 
    content: |
        Разрешите своим приложениям Java отображать более 170 форматов файлов в режимах HTML, PDF или изображений с помощью API GroupDocs.Viewer для Java без установки какого-либо дополнительного программного обеспечения; таких как Microsoft Office, Apache Open Office, Adobe Acrobat Reader и т. д. Разработчики могут легко просматривать все популярные форматы изображений и документов, включая Microsoft Office, OpenDocument, HTML, PDF, архив, диаграммы, Photoshop, AutoCAD и языки программирования, внутри приложений Java с помощью быстрый и качественный рендеринг.

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
    title_left: "Шаги для рендеринга файла HPG в Java" 
    content_left: |
        С помощью [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/) вы можете преобразовать HPG в HTML, JPEG, PNG или PDF за несколько шагов.

        * Добавьте [GroupDocs.Viewer для Java](https://releases.groupdocs.com/viewer/java/) в качестве зависимости к вашему проекту. 
        * Создайте экземпляр класса Viewer и загрузите файл HPG с полным путем. 
        * Установите параметры для преобразования файла HPG в формат HTML, PNG, JPEG или PDF. 
        * Рендерим файл и проверяем вывод в текущем каталоге. 
        
    title_right: "Системные Требования" 
    content_right: |
        API GroupDocs.Viewer для Java поддерживаются на всех основных платформах и операционных системах. Перед выполнением приведенного ниже кода убедитесь, что в вашей системе установлены следующие предварительные компоненты.

        * Операционные системы: Microsoft Windows, Linux, MacOS 
        * Среды разработки: NetBeans, IntelliJ IDEA, Eclipse и т. д. 
        * Фреймворки: J2SE 8.0 (1.8) или выше (например, Java 17) 
    code: |
        ```java
                        
            // Set up input HPG file
            String filePath = "input.hpg";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render HPG file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "HPG Демо-версия программы просмотра"
    content: |
        Просмотрите файл HPG прямо сейчас, посетив веб-сайт [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/hpg).
    lang: "ru"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Рендеринг и просмотр файлов других форматов с использованием Java"
    exclude: "HPG"
    content: |
        Многоформатный API для просмотра документов и изображений для Java. Просмотрите некоторые из популярных форматов файлов ниже без каких-либо внешних средств просмотра.
    format: 
        # format loop 1
        - name: "Рендеринг DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Документ Microsoft Word с открытым XML" 

        # format loop 2
        - name: "Рендеринг CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "Файл CorelDRAW" 

        # format loop 3
        - name: "Рендеринг PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "Презентация PowerPoint Open XML" 

        # format loop 4
        - name: "Рендеринг XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Электронная таблица Microsoft Excel Open XML" 

        # format loop 5
        - name: "Визуализация DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "Чертеж Автокад"

        # format loop 6
        - name: "Рендеринг XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "XML-файл"

        # format loop 7
        - name: "Рендер PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Документ Adobe Photoshop"

        # format loop 8
        - name: "Рендеринг файла Adobe Illustrator"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Работа Adobe Illustrator"

        # format loop 9
        - name: "Рендеринг DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Документ Microsoft Word" 

        # format loop 10
        - name: "Рендеринг TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Простой текстовый файл" 

        # format loop 11
        - name: "Визуализировать DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Файл формата обмена чертежами"  
          
        # format loop 12
        - name: "Рендеринг VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "файл визитной карточки"  
              
        # format loop 13
        - name: "Визуализировать SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Масштабируемая векторная графика" 
          
        # format loop 14
        - name: "Рендеринг HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Файл языка гипертекстовой разметки" 
          
        # format loop 15
        - name: "Рендер PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Файл переносимого формата документа"
          
        # format loop 16
        - name: "Рендеринг JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "Изображение в формате JPEG"
          
        # format loop 17
        - name: "Рендер PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Портативная сетевая графика" 
          
        # format loop 18
        - name: "Рендер EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "Сообщение электронной почты" 
          
        # format loop 19
        - name: "Рендеринг в формате RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Файл форматированного текста" 
          
        # format loop 20
        - name: "Рендеринг ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "Текстовый документ OpenDocument" 
          
        # format loop 21
        - name: "Отобразить CSV-файл"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Файл значений, разделенных запятыми" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
