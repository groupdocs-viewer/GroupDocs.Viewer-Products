---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: uk

############################# Head #############################
head_title: ".NET JPX Viewer API - читання, перегляд, рендеринг у C# VB.NET"
head_description: "API переглядача документів .NET для читання, візуалізації та відображення JPX у будь-яких програмах C#, ASP.NET, VB.NET і .NET Core."

############################# Header ############################
title: "JPX Переглядач файлів для програм C# .NET" 
description: "API переглядача документів .NET для читання, візуалізації та відображення файлу JPX у будь-яких програмах C#, ASP.NET, VB.NET і .NET Core. Переглядайте відтворені файли зі справжнім форматуванням і макетом у HTML5, PDF або як зображення за допомогою кількох рядків коду." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Завантажте безкоштовну пробну версію"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Про GroupDocs.Viewer для .NET API" 
    content: |
        Почніть переглядати понад 190 популярних форматів документів у своїх програмах .NET за допомогою API GroupDocs.Viewer для .NET, додавши кілька рядків коду. Розробники можуть легко відображати PDF, Word Processing, Excel Spreadsheet, Presentation, Visio, Project, Outlook та багато інших популярних форматів документів у режимах HTML5, зображень або PDF. Рендеринг документа відбувається швидко, ідентичний оригінальному вихідному файлу, і не вимагає встановлення додаткового програмного забезпечення чи будь-яких інших зовнішніх бібліотек.

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
              text: "Довідник API"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Приклади коду"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Живі демонстрації"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Ціноутворення"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "Кроки для відтворення файлу JPX мовою C#" 
    content_left: |
        За допомогою [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/) ви можете перетворити JPX у HTML, JPEG, PNG або PDF за кілька кроків.

        * Установіть [GroupDocs.Viewer для .NET](https://www.nuget.org/packages/groupdocs.viewer) за допомогою вашого улюбленого менеджера пакетів. 
        * Створіть екземпляр класу Viewer і завантажте файл JPX із повним шляхом. 
        * Встановіть параметри для відтворення файлу JPX у форматі HTML, PNG, JPEG або PDF. 
        * Відобразити файл і перевірити вивід у поточному каталозі. 
        
    title_right: "Системні вимоги" 
    content_right: |
        API GroupDocs.Viewer для .NET підтримуються на всіх основних платформах і операційних системах. Перш ніж виконувати наведений нижче код, переконайтеся, що у вашій системі встановлено такі передумови.

        * Операційні системи: Microsoft Windows, Linux, MacOS 
        * Середовища розробки: Microsoft Visual Studio, Visual Studio Code, .NET CLI 
        * Frameworks: .NET Framework, .NET Standard, .NET Core, .NET 
    code: |
        ```cs
                        
            // Set up input JPX file
            string filePath = "input.jpx";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render JPX file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "JPX Демо-версія переглядача"
    content: |
        Перегляньте файл JPX просто зараз, відвідавши веб-сайт [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/jpx).
    lang: "uk"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Відтворення та перегляд інших форматів файлів за допомогою C#"
    exclude: "JPX"
    content: |
        Багатоформатний API перегляду документів і зображень для .NET. Перегляньте деякі з популярних форматів файлів нижче без зовнішніх програм перегляду.
    format: 
        # format loop 1
        - name: "Рендер DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Відкритий XML-документ Microsoft Word" 

        # format loop 2
        - name: "Рендер CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "Файл CorelDRAW" 

        # format loop 3
        - name: "Рендер PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "Презентація PowerPoint Open XML" 

        # format loop 4
        - name: "Рендер XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Електронна таблиця Microsoft Excel Open XML" 

        # format loop 5
        - name: "Рендер DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "Креслення AutoCAD"

        # format loop 6
        - name: "Виводити XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "Файл XML"

        # format loop 7
        - name: "Рендер PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Документ Adobe Photoshop"

        # format loop 8
        - name: "Відобразити файл Adobe Illustrator"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Ілюстрація Adobe Illustrator"

        # format loop 9
        - name: "Відобразити DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Документ Microsoft Word" 

        # format loop 10
        - name: "Рендерити TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Звичайний текстовий файл" 

        # format loop 11
        - name: "Рендер DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Файл обміну кресленнями"  
          
        # format loop 12
        - name: "Рендер VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "Файл vCard"  
              
        # format loop 13
        - name: "Відтворити SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Масштабована векторна графіка" 
          
        # format loop 14
        - name: "Відобразити HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Мовний файл розмітки гіпертексту" 
          
        # format loop 15
        - name: "Рендер PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Файл формату портативного документа"
          
        # format loop 16
        - name: "Рендер JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "Зображення JPEG"
          
        # format loop 17
        - name: "Рендер PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Портативна мережева графіка" 
          
        # format loop 18
        - name: "Відобразити EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "Повідомлення електронної пошти" 
          
        # format loop 19
        - name: "Рендер RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Файл у текстовому форматі" 
          
        # format loop 20
        - name: "Рендер ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "Текстовий документ OpenDocument" 
          
        # format loop 21
        - name: "Відобразити CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Файл зі значеннями, розділеними комами" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
