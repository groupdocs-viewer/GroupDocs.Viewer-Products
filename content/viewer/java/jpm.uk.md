---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: uk

############################# Head #############################
head_title: "Java JPM Viewer API – візуалізація та відображення JPM у програмах Java"
head_description: "Перегляд файлів JPM у програмах Java, J2EE, J2SE. Підтримує перегляд понад 170 форматів документів і файлів зображень у режимі HTML, PDF або зображення з розширеними функціями для керування параметрами перегляду документів."

############################# Header ############################
title: "Рендерити та переглядати JPM на Java" 
description: "Власний і високопродуктивний API переглядача файлів JPM для додатків на основі Java, J2EE та J2SE, що підтримує широкий спектр додаткових функцій для налаштування зовнішнього вигляду формату вихідного документа." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Завантажте безкоштовну пробну версію"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Про GroupDocs.Viewer для Java API" 
    content: |
        Дозвольте програмам Java відображати понад 170 форматів файлів у режимах HTML, PDF або зображень за допомогою GroupDocs.Viewer для Java API без встановлення додаткового програмного забезпечення; наприклад Microsoft Office, Apache Open Office, Adobe Acrobat Reader тощо. Розробники можуть легко переглядати всі популярні зображення та типи документів, включаючи Microsoft Office, OpenDocument, HTML, PDF, архів, діаграми, Photoshop, AutoCAD і формати мови програмування в програмах Java за допомогою швидкий і якісний рендеринг.

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
    title_left: "Кроки для відтворення файлу JPM у Java" 
    content_left: |
        За допомогою [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/) ви можете перетворити JPM у HTML, JPEG, PNG або PDF за кілька кроків.

        * Додайте [GroupDocs.Viewer для Java](https://releases.groupdocs.com/viewer/java/) як залежність до свого проекту. 
        * Створіть екземпляр класу Viewer і завантажте файл JPM із повним шляхом. 
        * Встановіть параметри для відтворення файлу JPM у форматі HTML, PNG, JPEG або PDF. 
        * Відобразити файл і перевірити вивід у поточному каталозі. 
        
    title_right: "Системні вимоги" 
    content_right: |
        API GroupDocs.Viewer для Java підтримуються на всіх основних платформах і операційних системах. Перш ніж виконувати наведений нижче код, переконайтеся, що у вашій системі встановлено такі передумови.

        * Операційні системи: Microsoft Windows, Linux, MacOS 
        * Середовища розробки: NetBeans, IntelliJ IDEA, Eclipse тощо. 
        * Фреймворки: J2SE 8.0 (1.8) або вище (наприклад, Java 17) 
    code: |
        ```java
                        
            // Set up input JPM file
            String filePath = "input.jpm";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render JPM file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "JPM Демо-версія переглядача"
    content: |
        Перегляньте файл JPM просто зараз, відвідавши веб-сайт [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/jpm).
    lang: "uk"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Відтворення та перегляд інших форматів файлів за допомогою Java"
    exclude: "JPM"
    content: |
        Багатоформатний API перегляду документів і зображень для Java. Перегляньте деякі з популярних форматів файлів нижче без зовнішніх програм перегляду.
    format: 
        # format loop 1
        - name: "Рендер DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Відкритий XML-документ Microsoft Word" 

        # format loop 2
        - name: "Рендер CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "Файл CorelDRAW" 

        # format loop 3
        - name: "Рендер PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "Презентація PowerPoint Open XML" 

        # format loop 4
        - name: "Рендер XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Електронна таблиця Microsoft Excel Open XML" 

        # format loop 5
        - name: "Рендер DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "Креслення AutoCAD"

        # format loop 6
        - name: "Виводити XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "Файл XML"

        # format loop 7
        - name: "Рендер PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Документ Adobe Photoshop"

        # format loop 8
        - name: "Відобразити файл Adobe Illustrator"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Ілюстрація Adobe Illustrator"

        # format loop 9
        - name: "Відобразити DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Документ Microsoft Word" 

        # format loop 10
        - name: "Рендерити TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Звичайний текстовий файл" 

        # format loop 11
        - name: "Рендер DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Файл обміну кресленнями"  
          
        # format loop 12
        - name: "Рендер VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "Файл vCard"  
              
        # format loop 13
        - name: "Відтворити SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Масштабована векторна графіка" 
          
        # format loop 14
        - name: "Відобразити HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Мовний файл розмітки гіпертексту" 
          
        # format loop 15
        - name: "Рендер PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Файл формату портативного документа"
          
        # format loop 16
        - name: "Рендер JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "Зображення JPEG"
          
        # format loop 17
        - name: "Рендер PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Портативна мережева графіка" 
          
        # format loop 18
        - name: "Відобразити EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "Повідомлення електронної пошти" 
          
        # format loop 19
        - name: "Рендер RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Файл у текстовому форматі" 
          
        # format loop 20
        - name: "Рендер ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "Текстовий документ OpenDocument" 
          
        # format loop 21
        - name: "Відобразити CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Файл зі значеннями, розділеними комами" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
