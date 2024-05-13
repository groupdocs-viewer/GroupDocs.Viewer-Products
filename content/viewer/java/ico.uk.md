---
############################# Static ############################
layout: "format"
date: 2024-05-13T10:14:45
draft: false
lang: uk
product: "Viewer"
product_tag: "viewer"
platform: "Java"
platform_tag: "java"

############################# Head #############################
head_title: "Java ICO Viewer API — візуалізація та відображення ICO у програмах Java"
head_description: "Перегляд файлів ICO у програмах Java, J2EE, J2SE. Підтримує перегляд понад 180 форматів документів і файлів зображень у режимі HTML, PDF або зображення з розширеними функціями для керування параметрами перегляду документів."

############################# Header ############################
title: "Рендерити та переглядати ICO у Java" 
description: "Власний і високопродуктивний API перегляду файлів ICO для програм на основі Java, J2EE та J2SE, що підтримує широкий спектр додаткових функцій для налаштування зовнішнього вигляду формату вихідного документа." 
subtitle: "РІШЕННЯ ДЛЯ ПЕРЕГЛЯДУ ДОКУМЕНТІВ" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "Безкоштовне завантаження Maven"
      link: "https://releases.groupdocs.com/viewer/java/"



############################# About ############################
about:
    enable: true
    title: "Про GroupDocs.Viewer для Java API"
    link: "/viewer/java/"
    link_title: "Дізнатись більше"
    picture: "about_viewer.svg" # 480 X 400
    content: |
      Дозвольте вашим програмам Java відображати понад 180 форматів файлів у режимах HTML, PDF або зображень за допомогою API GroupDocs.Viewer для Java без встановлення додаткового програмного забезпечення; наприклад Microsoft Office, Apache Open Office, Adobe Acrobat Reader тощо. Розробники можуть легко переглядати всі популярні зображення та типи документів, включаючи Microsoft Office, OpenDocument, HTML, PDF, архів, діаграми, Photoshop, AutoCAD і формати мов програмування в програмах Java.



############################# Steps ############################
steps:
    enable: true
    title: "Кроки для перегляду файлу ICO у Java" 
    content: |
      За допомогою <a href='https://products.groupdocs.com/viewer/java/'>GroupDocs.Viewer</a> ви можете перетворити ICO у HTML, JPEG, PNG або PDF за кілька кроків.
      
      1. Додайте <a href='https://releases.groupdocs.com/viewer/java/'>GroupDocs.Viewer для Java</a> як залежність до свого проекту. 
      2. Створіть екземпляр класу Viewer і завантажте файл ICO із повним шляхом.  
      3. Встановіть параметри для перетворення файлу ICO у форматі HTML, PNG, JPEG або PDF. 
      4. Перетворити файл і переглянути результат у поточній директорії. 
   
    code:
      platform: "java"
      copy_title: "Копіювати"
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
        copy_tip: "натисніть, щоб скопіювати"
        copy_done: "скопійовано"
      links:
        #  loop
        - title: "Більше прикладів"
          link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Java"
        #  loop
        - title: "Документація"
          link: "https://docs.groupdocs.com/viewer/java/"
          
      content: |
        ```java {style=abap}

        // Налаштувати вхідний файл ICO
        String filePath = "input.ico";

        // Створення екземпляра GroupDocs.Viewer
        try (Viewer viewer = new Viewer(filePath))
        {
            // Налаштувати параметри перегляду
            HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                
            // Перетворіть файл ICO у HTML із вбудованими ресурсами
            viewer.view(viewOptions);
        }

        ```
            

############################# Actions ############################

actions:
  enable: true
  title: "Готові почати?"
  description: "Спробуйте функції GroupDocs.Viewer безкоштовно або ортимайте тимчасову ліцензию"
  items:
    #  loop
    - title: "Завантажити Maven"
      link: "https://releases.groupdocs.com/viewer/java/"
      color: "red"
        #  loop
    - title: "Ліцензування"
      link: "https://purchase.groupdocs.com/pricing/viewer/java/"
      color: "light"



############################# More Formats #####################
more_formats:
    enable: true
    title: "Перегляд інших форматів в додатках на Java"
    exclude: "ICO"
    description: "Багатоформатний API перегляду документів і зображень для Java. Переглядайте популярні формати файлів без встановлення додаткових програм."
    items: 
        # format loop 1
        - name: "Рендер DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Open XML Document" 

        # format loop 2
        - name: "Рендер CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "CorelDRAW File" 

        # format loop 3
        - name: "Рендер PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint Open XML Presentation" 

        # format loop 4
        - name: "Рендер XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet" 

        # format loop 5
        - name: "Рендер DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "AutoCAD Drawing"

        # format loop 6
        - name: "Відобразити XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "XML File"

        # format loop 7
        - name: "Рендер PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Adobe Photoshop Document"

        # format loop 8
        - name: "Рендер AI"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Adobe Illustrator Artwork"

        # format loop 9
        - name: "Відобразити DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Microsoft Word Document" 

        # format loop 10
        - name: "Рендерити TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Plain Text File" 

        # format loop 11
        - name: "Рендер DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Drawing Exchange Format File"  
          
        # format loop 12
        - name: "Рендер VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "vCard File"  
              
        # format loop 13
        - name: "Відтворити SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Scalable Vector Graphic" 
          
        # format loop 14
        - name: "Відобразити HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "Рендер PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Portable Document Format File"
          
        # format loop 16
        - name: "Рендер JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "JPEG Image"
          
        # format loop 17
        - name: "Рендер PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Portable Network Graphic" 
          
        # format loop 18
        - name: "Відобразити EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "E-Mail Message" 
          
        # format loop 19
        - name: "Рендер RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Rich Text Format File" 
          
        # format loop 20
        - name: "Рендер ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "OpenDocument Text Document" 
          
        # format loop 21
        - name: "Відобразити CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Comma-Separated Values File" 


---
