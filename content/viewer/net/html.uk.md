---
############################# Static ############################
layout: "format"
date: 2024-05-14T11:12:55
draft: false
lang: uk
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head #############################
head_title: ".NET HTML Viewer API - читання, перегляд, рендеринг у C# VB.NET"
head_description: "API переглядача документів .NET для читання, візуалізації та відображення HTML у будь-яких програмах C#, ASP.NET, VB.NET і .NET Core."

############################# Header ############################
title: "Переглядач файлів HTML для програм C# .NET" 
description: "API переглядача документів .NET для читання, візуалізації та відображення файлу HTML у програмах C#, ASP.NET, VB.NET і .NET Core будь-якого типу. Переглядайте відтворені файли зі справжнім форматуванням і макетом у HTML5, PDF або як зображення за допомогою кількох рядків коду." 
subtitle: "РІШЕННЯ ДЛЯ ПЕРЕГЛЯДУ ДОКУМЕНТІВ" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "Безкоштовне завантаження Nuget"
      link: "https://nuget.org/packages/GroupDocs.Viewer"



############################# About ############################
about:
    enable: true
    title: "Про GroupDocs.Viewer для .NET API"
    link: "/viewer/net/"
    link_title: "Дізнатись більше"
    picture: "about_viewer.svg" # 480 X 400
    content: |
      Почніть переглядати понад 190 популярних форматів документів у своїх програмах .NET за допомогою API GroupDocs.Viewer для .NET, додавши кілька рядків коду. Розробники можуть легко відображати PDF, Word Processing, Excel Spreadsheet, Presentation, Visio, Project, Outlook та багато інших популярних форматів документів у режимах HTML5, зображень або PDF. Рендеринг документа відбувається швидко, ідентичний оригінальному вихідному файлу, і не вимагає встановлення додаткового програмного забезпечення чи будь-яких інших зовнішніх бібліотек.



############################# Steps ############################
steps:
    enable: true
    title: "Кроки для перегляду файлу HTML у C#" 
    content: |
      За допомогою <a href='https://products.groupdocs.com/viewer/net/'>GroupDocs.Viewer</a> ви можете перетворити HTML у HTML, JPEG, PNG або PDF за кілька кроків.
      
      1. Установіть <a href='https://www.nuget.org/packages/groupdocs.viewer'>GroupDocs.Viewer для .NET</a> за допомогою улюбленого менеджера пакетів. 
      2. Створіть екземпляр класу Viewer і завантажте файл HTML із повним шляхом.  
      3. Встановіть параметри для перетворення файлу HTML у форматі HTML, PNG, JPEG або PDF. 
      4. Перетворити файл і переглянути результат у поточній директорії. 
   
    code:
      platform: "net"
      copy_title: "Копіювати"
      install:
        command: "dotnet add package GroupDocs.Viewer"
        copy_tip: "натисніть, щоб скопіювати"
        copy_done: "скопійовано"
      links:
        #  loop
        - title: "Більше прикладів"
          link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
        #  loop
        - title: "Документація"
          link: "https://docs.groupdocs.com/viewer/net/"
          
      content: |
        ```csharp {style=abap}

        // Налаштувати вхідний файл HTML
        string filePath = "input.html";

        // Створення екземпляра GroupDocs.Viewer
        using (Viewer viewer = new Viewer(filePath))
        {
            // Налаштувати параметри перегляду
            HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                
            // Перетворіть файл HTML у HTML із вбудованими ресурсами
            viewer.View(viewOptions);
        }

        ```            


############################# Actions ############################

actions:
  enable: true
  title: "Готові почати?"
  description: "Спробуйте функції GroupDocs.Viewer безкоштовно або ортимайте тимчасову ліцензию"
  items:
    #  loop
    - title: "Завантажити Nuget"
      link: "https://nuget.org/packages/GroupDocs.Viewer"
      color: "red"
        #  loop
    - title: "Ліцензування"
      link: "https://purchase.groupdocs.com/pricing/viewer/net/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "Перегляд інших форматів в додатках на C#"
    exclude: "HTML"
    description: "Багатоформатний API перегляду документів і зображень для .NET. Переглядайте популярні формати файлів без встановлення додаткових програм."
    items: 
        # format loop 1
        - name: "Рендер DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word Open XML Document" 

        # format loop 2
        - name: "Рендер CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "CorelDRAW File" 

        # format loop 3
        - name: "Рендер PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint Open XML Presentation" 

        # format loop 4
        - name: "Рендер XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet" 

        # format loop 5
        - name: "Рендер DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "AutoCAD Drawing"

        # format loop 6
        - name: "Відобразити XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "XML File"

        # format loop 7
        - name: "Рендер PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Adobe Photoshop Document"

        # format loop 8
        - name: "Рендер AI"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Adobe Illustrator Artwork"

        # format loop 9
        - name: "Відобразити DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Microsoft Word Document" 

        # format loop 10
        - name: "Рендерити TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Plain Text File" 

        # format loop 11
        - name: "Рендер DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Drawing Exchange Format File"  
          
        # format loop 12
        - name: "Рендер VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "vCard File"  
              
        # format loop 13
        - name: "Відтворити SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Scalable Vector Graphic" 
          
        # format loop 14
        - name: "Відобразити HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "Рендер PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Portable Document Format File"
          
        # format loop 16
        - name: "Рендер JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "JPEG Image"
          
        # format loop 17
        - name: "Рендер PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Portable Network Graphic" 
          
        # format loop 18
        - name: "Відобразити EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "E-Mail Message" 
          
        # format loop 19
        - name: "Рендер RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Rich Text Format File" 
          
        # format loop 20
        - name: "Рендер ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "OpenDocument Text Document" 
          
        # format loop 21
        - name: "Відобразити CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Comma-Separated Values File" 



---
