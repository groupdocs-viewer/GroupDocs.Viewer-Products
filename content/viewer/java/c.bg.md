---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: bg

############################# Head #############################
head_title: "Java C Viewer API - Изобразяване и показване на C в Java приложения"
head_description: "Вижте C файлове в Java, J2EE, J2SE приложения. Поддържа преглед на 170+ файлови формати на документи и изображения в режим HTML, PDF или изображения с разширени функции за управление на опциите за преглед на документи."

############################# Header ############################
title: "Изобразяване и преглед на C в Java" 
description: "Вътрешен и високопроизводителен API за преглед на файлове C за приложения, базирани на Java, J2EE и J2SE, поддържащи широк набор от допълнителни функции за персонализиране на външния вид на формата на изходния документ." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Изтеглете безплатна пробна версия"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Относно GroupDocs.Viewer за Java API" 
    content: |
        Разрешете вашите Java приложения да показват над 170+ файлови формата в HTML, PDF или режими на изображения, като използвате GroupDocs.Viewer за Java API без инсталиран допълнителен софтуер; като Microsoft Office, Apache Open Office, Adobe Acrobat Reader и др. Разработчиците могат лесно да преглеждат всички популярни изображения и типове документи, включително Microsoft Office, OpenDocument, HTML, PDF, архив, диаграми, Photoshop, AutoCAD и формати на език за програмиране в приложенията на Java с бързо и висококачествено изобразяване.

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
              text: "Справка за API"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Примери за кодове"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Демонстрации на живо"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Ценообразуване"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "Стъпки за изобразяване на файл C в Java" 
    content_left: |
        С [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/) можете да изобразите C в HTML, JPEG, PNG или PDF в няколко стъпки.

        * Добавете [GroupDocs.Viewer за Java](https://releases.groupdocs.com/viewer/java/) като зависимост към вашия проект. 
        * Създайте екземпляр на клас Viewer и заредете файла C с пълен път. 
        * Задайте опции за изобразяване на файл C в HTML, PNG, JPEG или PDF формат. 
        * Рендирайте файл и проверете изхода в текущата директория. 
        
    title_right: "Системни изисквания" 
    content_right: |
        GroupDocs.Viewer за Java API се поддържат на всички основни платформи и операционни системи. Преди да изпълните кода по-долу, моля, уверете се, че имате следните предпоставки, инсталирани на вашата система.

        * Операционни системи: Microsoft Windows, Linux, MacOS 
        * Среди за разработка: NetBeans, IntelliJ IDEA, Eclipse и др. 
        * Рамки: J2SE 8.0 (1.8) или по-нова версия (например Java 17) 
    code: |
        ```java
                        
            // Set up input C file
            String filePath = "input.c";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render C file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "C Демо на живо за зрителя"
    content: |
        Вижте файла C точно сега, като посетите уебсайта на [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/c).
    lang: "bg"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Изобразяване и преглед на други файлови формати с Java"
    exclude: "C"
    content: |
        Многоформатен API за преглед на документи и изображения за Java. Вижте някои от популярните файлови формати по-долу без външни програми за преглед.
    format: 
        # format loop 1
        - name: "Изобразете DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Open XML документ" 

        # format loop 2
        - name: "Изобразете CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "CorelDRAW файл" 

        # format loop 3
        - name: "Изобразете PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint Open XML презентация" 

        # format loop 4
        - name: "Рендирайте XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Open XML електронна таблица" 

        # format loop 5
        - name: "Изобразете DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "Чертеж на AutoCAD"

        # format loop 6
        - name: "Изобразяване на XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "XML файл"

        # format loop 7
        - name: "Изобразете PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Документ на Adobe Photoshop"

        # format loop 8
        - name: "Изобразете файл на Adobe Illustrator"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Произведение на Adobe Illustrator"

        # format loop 9
        - name: "Изобразете DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Microsoft Word документ" 

        # format loop 10
        - name: "Изобразете TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Обикновен текстов файл" 

        # format loop 11
        - name: "Изобразете DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Файл с формат за обмен на чертежи"  
          
        # format loop 12
        - name: "Изобразете VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "vCard файл"  
              
        # format loop 13
        - name: "Изобразете SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Мащабируема векторна графика" 
          
        # format loop 14
        - name: "Изобразяване на HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Езиков файл за маркиране на хипертекст" 
          
        # format loop 15
        - name: "Изобразете PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Преносим файл във формат на документ"
          
        # format loop 16
        - name: "Изобразете JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "JPEG изображение"
          
        # format loop 17
        - name: "Изобразете PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Преносима мрежова графика" 
          
        # format loop 18
        - name: "Изобразете EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "Имейл съобщение" 
          
        # format loop 19
        - name: "Изобразете RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Файл с богат текстов формат" 
          
        # format loop 20
        - name: "Изобразете ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "OpenDocument Текстов документ" 
          
        # format loop 21
        - name: "Изобразете CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Файл със стойности, разделени със запетая" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
