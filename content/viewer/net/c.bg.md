---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: bg

############################# Head #############################
head_title: ".NET C Viewer API - Четене, преглед, изобразяване в C# VB.NET"
head_description: ".NET API за преглед на документи за четене, изобразяване и показване на C във всеки тип C#, ASP.NET, VB.NET и .NET Core приложения."

############################# Header ############################
title: "C Преглед на файлове за C# .NET приложения" 
description: ".NET API за преглед на документи за четене, изобразяване и показване на C файл във всеки тип C#, ASP.NET, VB.NET и .NET Core приложения. Вижте изобразените файлове с истинско форматиране и оформление в HTML5, PDF или като изображение, като използвате няколко реда от кода." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Изтеглете безплатна пробна версия"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Относно GroupDocs.Viewer за .NET API" 
    content: |
        Започнете да преглеждате 190+ популярни формати на документи във вашите .NET приложения с помощта на GroupDocs.Viewer за .NET API, като добавите няколко реда код. Разработчиците могат лесно да показват PDF, Word Processing, Excel Spreadsheet, Presentation, Visio, Project, Outlook и много други популярни формати на документи в режими HTML5, изображения или PDF. Изобразяването на документа е бързо, идентично с оригиналния изходен файл и не изисква инсталиране на допълнителен софтуер или други външни библиотеки.

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
    title_left: "Стъпки за изобразяване на файл C на C#" 
    content_left: |
        С [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/) можете да изобразите C в HTML, JPEG, PNG или PDF в няколко стъпки.

        * Инсталирайте [GroupDocs.Viewer за .NET](https://www.nuget.org/packages/groupdocs.viewer), като използвате любимия си мениджър на пакети. 
        * Създайте екземпляр на клас Viewer и заредете файла C с пълен път. 
        * Задайте опции за изобразяване на файл C в HTML, PNG, JPEG или PDF формат. 
        * Рендирайте файл и проверете изхода в текущата директория. 
        
    title_right: "Системни изисквания" 
    content_right: |
        GroupDocs.Viewer за .NET API се поддържат на всички основни платформи и операционни системи. Преди да изпълните кода по-долу, моля, уверете се, че имате следните предпоставки, инсталирани на вашата система.

        * Операционни системи: Microsoft Windows, Linux, MacOS 
        * Среди за разработка: Microsoft Visual Studio, Visual Studio Code, .NET CLI 
        * Рамки: .NET Framework, .NET Standard, .NET Core, .NET 
    code: |
        ```cs
                        
            // Set up input C file
            string filePath = "input.c";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render C file to HTML with embedded resources
            	viewer.View(viewOptions);
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
    title: "Изобразяване и преглед на други файлови формати чрез C#"
    exclude: "C"
    content: |
        Многоформатен API за преглед на документи и изображения за .NET. Вижте някои от популярните файлови формати по-долу без външни програми за преглед.
    format: 
        # format loop 1
        - name: "Изобразете DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word Open XML документ" 

        # format loop 2
        - name: "Изобразете CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "CorelDRAW файл" 

        # format loop 3
        - name: "Изобразете PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint Open XML презентация" 

        # format loop 4
        - name: "Рендирайте XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Open XML електронна таблица" 

        # format loop 5
        - name: "Изобразете DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "Чертеж на AutoCAD"

        # format loop 6
        - name: "Изобразяване на XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "XML файл"

        # format loop 7
        - name: "Изобразете PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Документ на Adobe Photoshop"

        # format loop 8
        - name: "Изобразете файл на Adobe Illustrator"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Произведение на Adobe Illustrator"

        # format loop 9
        - name: "Изобразете DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Microsoft Word документ" 

        # format loop 10
        - name: "Изобразете TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Обикновен текстов файл" 

        # format loop 11
        - name: "Изобразете DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Файл с формат за обмен на чертежи"  
          
        # format loop 12
        - name: "Изобразете VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "vCard файл"  
              
        # format loop 13
        - name: "Изобразете SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Мащабируема векторна графика" 
          
        # format loop 14
        - name: "Изобразяване на HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Езиков файл за маркиране на хипертекст" 
          
        # format loop 15
        - name: "Изобразете PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Преносим файл във формат на документ"
          
        # format loop 16
        - name: "Изобразете JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "JPEG изображение"
          
        # format loop 17
        - name: "Изобразете PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Преносима мрежова графика" 
          
        # format loop 18
        - name: "Изобразете EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "Имейл съобщение" 
          
        # format loop 19
        - name: "Изобразете RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Файл с богат текстов формат" 
          
        # format loop 20
        - name: "Изобразете ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "OpenDocument Текстов документ" 
          
        # format loop 21
        - name: "Изобразете CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Файл със стойности, разделени със запетая" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
