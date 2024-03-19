---
############################# Static ############################
layout: "format"
date: 2024-03-19T07:00:52
draft: false
lang: ru
product: "Viewer"
product_tag: "viewer"
platform: "Java"
platform_tag: "java"

############################# Head #############################
head_title: "API Java BAT Viewer – рендеринг и отображение BAT в приложениях Java"
head_description: "Просмотр файлов BAT в приложениях Java, J2EE, J2SE. Поддерживает просмотр более 180 форматов документов и изображений в режиме HTML, PDF или изображений, а также расширенные функции для управления параметрами просмотра документов."

############################# Header ############################
title: "Рендеринг и просмотр BAT в Java" 
description: "Собственный высокопроизводительный API-интерфейс просмотра файлов BAT для приложений на базе Java, J2EE и J2SE, поддерживающий широкий спектр дополнительных функций для настройки внешнего вида формата выходного документа." 
subtitle: "Решение для рендеринга документов" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "Бесплатная загрузка Maven"
      link: "https://releases.groupdocs.com/viewer/java/"



############################# About ############################
about:
    enable: true
    title: "О GroupDocs.Viewer для Java API"
    link: "/viewer/java/"
    link_title: "Узнать больше"
    picture: "about_viewer.svg" # 480 X 400
    content: |
      Позвольте вашим Java-приложениям отображать более 180+ форматов файлов в режимах HTML, PDF или изображений с помощью API GroupDocs.Viewer для Java без установки какого-либо дополнительного программного обеспечения; такие как Microsoft Office, Apache Open Office, Adobe Acrobat Reader и т. д. Разработчики могут легко просматривать все популярные изображения и типы документов, включая Microsoft Office, OpenDocument, HTML, PDF, Archive, Diagrams, Photoshop, AutoCAD и форматы языков программирования внутри приложений Java с помощью быстрый и качественный рендеринг.



############################# Steps ############################
steps:
    enable: true
    title: "Действия по рендерингу файла BAT в Java" 
    content: |
      С помощью <a href='https://products.groupdocs.com/viewer/java/'>GroupDocs.Viewer</a> вы можете преобразовать BAT в HTML, JPEG, PNG или PDF за несколько шагов.
      
      1. Добавьте <a href='https://releases.groupdocs.com/viewer/java/'>GroupDocs.Viewer для Java</a> в качестве зависимости к вашему проекту. 
      2. Создайте экземпляр класса Viewer и загрузите файл BAT с полным путем.  
      3. Установите параметры для преобразования файла BAT в формат HTML, PNG, JPEG или PDF. 
      4. Отрисуйте файл и проверьте вывод в текущем каталоге. 
   
    code:
      platform: "java"
      copy_title: "Копировать"
      install:
        command: |
          <dependencies>
            <dependency>
              <groupId>com.groupdocs</groupId>
              <artifactId>groupdocs-viewer</artifactId>
              <version>{0}</version>
            </dependency>
          </dependencies>

          <repositories>
            <repository>
              <id>repository.groupdocs.com</id>
              <name>GroupDocs Repository</name>
              <url>https://repository.groupdocs.com/repo/</url>
            </repository>
          </repositories>
        copy_tip: "нажмите, чтобы скопировать"
        copy_done: "скопирован"
      links:
        #  loop
        - title: "Больше примеров"
          link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Java"
        #  loop
        - title: "Документация"
          link: "https://docs.groupdocs.com/viewer/java/"
          
      content: |
        ```java {style=abap}

        // Настройте входной файл BAT
        String filePath = "input.bat";

        // Создать экземпляр GroupDocs.Viewer
        try (Viewer viewer = new Viewer(filePath))
        {
            // Установить параметры просмотра
            HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                
            // Преобразовать файл BAT в HTML со встроенными ресурсами.
            viewer.view(viewOptions);
        }

        ```
            

############################# Actions ############################

actions:
  enable: true
  title: "Готовы начать?"
  description: "Попробуйте функции GroupDocs.Viewer бесплатно или запросите лицензию."
  items:
    #  loop
    - title: "Maven скачать"
      link: "https://releases.groupdocs.com/viewer/java/"
      color: "red"
        #  loop
    - title: "Лицензирование"
      link: "https://purchase.groupdocs.com/pricing/viewer/java/"
      color: "light"



############################# More Formats #####################
more_formats:
    enable: true
    title: "Рендеринг других форматов файлов с помощью Java"
    exclude: "BAT"
    description: "API многоформатного просмотра документов и изображений для Java. Просмотрите некоторые популярные форматы файлов ниже без использования внешних программ просмотра."
    items: 
        # format loop 1
        - name: "Рендеринг DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Open XML Document" 

        # format loop 2
        - name: "Рендеринг CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "CorelDRAW File" 

        # format loop 3
        - name: "Рендеринг PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint Open XML Presentation" 

        # format loop 4
        - name: "Рендер XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet" 

        # format loop 5
        - name: "Рендеринг DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "AutoCAD Drawing"

        # format loop 6
        - name: "Рендеринг XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "XML File"

        # format loop 7
        - name: "Рендеринг PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Adobe Photoshop Document"

        # format loop 8
        - name: "Рендеринг AI"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Adobe Illustrator Artwork"

        # format loop 9
        - name: "Рендеринг DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Microsoft Word Document" 

        # format loop 10
        - name: "Рендеринг TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Plain Text File" 

        # format loop 11
        - name: "Рендеринг DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Drawing Exchange Format File"  
          
        # format loop 12
        - name: "Рендеринг VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "vCard File"  
              
        # format loop 13
        - name: "Рендеринг SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Scalable Vector Graphic" 
          
        # format loop 14
        - name: "Рендеринг HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "Рендеринг PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Portable Document Format File"
          
        # format loop 16
        - name: "Рендеринг JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "JPEG Image"
          
        # format loop 17
        - name: "PNG рендеринг"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Portable Network Graphic" 
          
        # format loop 18
        - name: "Рендеринг EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "E-Mail Message" 
          
        # format loop 19
        - name: "Рендеринг RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Rich Text Format File" 
          
        # format loop 20
        - name: "Рендеринг ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "OpenDocument Text Document" 
          
        # format loop 21
        - name: "Рендеринг CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Comma-Separated Values File" 


---
