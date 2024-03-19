---
############################# Static ############################
layout: "format"
date: 2024-03-19T07:01:07
draft: false
lang: ru
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head #############################
head_title: ".NET CSS API Viewer — чтение, просмотр, рендеринг на C# VB.NET"
head_description: "API средства просмотра документов .NET для чтения, рендеринга и отображения CSS в любых типах приложений C#, ASP.NET, VB.NET и .NET Core."

############################# Header ############################
title: "CSS средство просмотра файлов для приложений C# .NET" 
description: "API средства просмотра документов .NET для чтения, рендеринга и отображения файла CSS в любых типах приложений C#, ASP.NET, VB.NET и .NET Core. Просматривайте обработанные файлы с правильным форматированием и макетом в формате HTML5, PDF или в виде изображения, используя несколько строк кода." 
subtitle: "Решение для рендеринга документов" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "Бесплатная загрузка Nuget"
      link: "https://releases.groupdocs.com/viewer/net/"



############################# About ############################
about:
    enable: true
    title: "О GroupDocs.Viewer для .NET API"
    link: "/viewer/net/"
    link_title: "Узнать больше"
    picture: "about_viewer.svg" # 480 X 400
    content: |
      Начните просматривать более 190 популярных форматов документов в своих приложениях .NET с помощью GroupDocs.Viewer для API .NET, добавив несколько строк кода. Разработчики могут легко отображать PDF-файлы, текстовые редакторы, электронные таблицы Excel, презентации, Visio, Project, Outlook и многие другие популярные форматы документов в режимах HTML5, изображения или PDF. Рендеринг документа происходит быстро, идентично исходному файлу и не требует установки дополнительного программного обеспечения или каких-либо других внешних библиотек.



############################# Steps ############################
steps:
    enable: true
    title: "Действия по рендерингу файла CSS в C#" 
    content: |
      С помощью <a href='https://products.groupdocs.com/viewer/net/'>GroupDocs.Viewer</a> вы можете преобразовать CSS в HTML, JPEG, PNG или PDF за несколько шагов.
      
      1. Установите <a href='https://www.nuget.org/packages/groupdocs.viewer'>GroupDocs.Viewer для .NET</a> с помощью вашего любимого менеджера пакетов. 
      2. Создайте экземпляр класса Viewer и загрузите файл CSS с полным путем.  
      3. Установите параметры для преобразования файла CSS в формат HTML, PNG, JPEG или PDF. 
      4. Отрисуйте файл и проверьте вывод в текущем каталоге. 
   
    code:
      platform: "net"
      copy_title: "Копировать"
      install:
        command: "dotnet add package GroupDocs.Viewer"
        copy_tip: "нажмите, чтобы скопировать"
        copy_done: "скопирован"
      links:
        #  loop
        - title: "Больше примеров"
          link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
        #  loop
        - title: "Документация"
          link: "https://docs.groupdocs.com/viewer/net/"
          
      content: |
        ```csharp {style=abap}

        // Настройте входной файл CSS
        string filePath = "input.css";

        // Создать экземпляр GroupDocs.Viewer
        using (Viewer viewer = new Viewer(filePath))
        {
            // Установить параметры просмотра
            HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                
            // Преобразовать файл CSS в HTML со встроенными ресурсами.
            viewer.View(viewOptions);
        }

        ```            


############################# Actions ############################

actions:
  enable: true
  title: "Готовы начать?"
  description: "Попробуйте функции GroupDocs.Viewer бесплатно или запросите лицензию."
  items:
    #  loop
    - title: "Скачать Nuget"
      link: "https://releases.groupdocs.com/viewer/net/"
      color: "red"
        #  loop
    - title: "Лицензирование"
      link: "https://purchase.groupdocs.com/pricing/viewer/net/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "Рендеринг других форматов файлов с помощью C#"
    exclude: "CSS"
    description: "API многоформатного просмотра документов и изображений для .NET. Просмотрите некоторые популярные форматы файлов ниже без использования внешних программ просмотра."
    items: 
        # format loop 1
        - name: "Рендеринг DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word Open XML Document" 

        # format loop 2
        - name: "Рендеринг CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "CorelDRAW File" 

        # format loop 3
        - name: "Рендеринг PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint Open XML Presentation" 

        # format loop 4
        - name: "Рендер XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet" 

        # format loop 5
        - name: "Рендеринг DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "AutoCAD Drawing"

        # format loop 6
        - name: "Рендеринг XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "XML File"

        # format loop 7
        - name: "Рендеринг PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Adobe Photoshop Document"

        # format loop 8
        - name: "Рендеринг AI"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Adobe Illustrator Artwork"

        # format loop 9
        - name: "Рендеринг DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Microsoft Word Document" 

        # format loop 10
        - name: "Рендеринг TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Plain Text File" 

        # format loop 11
        - name: "Рендеринг DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Drawing Exchange Format File"  
          
        # format loop 12
        - name: "Рендеринг VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "vCard File"  
              
        # format loop 13
        - name: "Рендеринг SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Scalable Vector Graphic" 
          
        # format loop 14
        - name: "Рендеринг HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "Рендеринг PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Portable Document Format File"
          
        # format loop 16
        - name: "Рендеринг JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "JPEG Image"
          
        # format loop 17
        - name: "PNG рендеринг"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Portable Network Graphic" 
          
        # format loop 18
        - name: "Рендеринг EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "E-Mail Message" 
          
        # format loop 19
        - name: "Рендеринг RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Rich Text Format File" 
          
        # format loop 20
        - name: "Рендеринг ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "OpenDocument Text Document" 
          
        # format loop 21
        - name: "Рендеринг CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Comma-Separated Values File" 



---
