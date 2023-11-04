---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: mk

############################# Head #############################
head_title: "Java GZ Прегледувач API - Рендерирај и прикажувај GZ во Java апликации"
head_description: "Приказ на датотеки GZ во апликациите Java, J2EE, J2SE. Поддржува прегледување на 170+ формати на документи и датотеки со слики во HTML, PDF или режим на слика со напредни функции за управување со опциите за прегледување документи."

############################# Header ############################
title: "Рендерирање и прегледување на GZ во Java" 
description: "АПИ за прегледувач на датотеки со автоматско и високи перформанси GZ за апликации базирани на Java, J2EE и J2SE, што поддржува широк опсег на дополнителни функции за прилагодување на изгледот на форматот на излезниот документ." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Преземете бесплатен пробен период"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "За GroupDocs.Viewer за Java API" 
    content: |
        Овозможете ги вашите Java апликации да прикажуваат преку 170+ формати на датотеки во HTML, PDF или режими на слика користејќи GroupDocs.Viewer за Java API без инсталиран дополнителен софтвер; како што се Microsoft Office, Apache Open Office, Adobe Acrobat Reader итн. Програмерите можат лесно да ги прегледуваат сите популарни слики и типови документи, вклучувајќи Microsoft Office, OpenDocument, HTML, PDF, Archive, Diagrams, Photoshop, AutoCAD и формати на програмски јазици во Java апликациите со брзо и најквалитетно рендерирање.

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
              text: "Референца на API"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Примери за кодови"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Демости во живо"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Цените"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "Чекори за прикажување на датотеката GZ во Java" 
    content_left: |
        Со [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/) може да го преведете GZ во HTML, JPEG, PNG или PDF во неколку чекори.

        * Додајте [GroupDocs.Viewer за Java](https://releases.groupdocs.com/viewer/java/) како зависност на вашиот проект. 
        * Направете примерок од класата Viewer и вчитајте ја датотеката GZ со целосна патека. 
        * Поставете опции за прикажување на датотеката GZ во HTML, PNG, JPEG или PDF формат. 
        * Рендерирајте ја датотеката и проверете го излезот во тековниот директориум. 
        
    title_right: "Системски барања" 
    content_right: |
        GroupDocs.Viewer за Java API се поддржани на сите главни платформи и оперативни системи. Пред да го извршите кодот подолу, проверете дали ги имате инсталирано следните предуслови на вашиот систем.

        * Оперативни системи: Microsoft Windows, Linux, MacOS 
        * Развојни средини: NetBeans, IntelliJ IDEA, Eclipse итн. 
        * Рамки: J2SE 8.0 (1.8) или погоре (на пример Java 17) 
    code: |
        ```java
                        
            // Set up input GZ file
            String filePath = "input.gz";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render GZ file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "GZ Прегледувач во живо демо"
    content: |
        Погледнете ја датотеката GZ во моментов со посета на веб-локацијата [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/gz).
    lang: "mk"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Други формати на датотеки што се прикажуваат и се прикажуваат со користење на Java"
    exclude: "GZ"
    content: |
        API за прегледувач на документи и слики со повеќе формати за Java. Погледнете некои од популарните формати на датотеки подолу без никакви надворешни гледачи.
    format: 
        # format loop 1
        - name: "Рендерирајте го DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Отвори XML документ" 

        # format loop 2
        - name: "Рендерирајте CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "Датотека CorelDRAW" 

        # format loop 3
        - name: "Рендерирајте PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint Отворете XML презентација" 

        # format loop 4
        - name: "Рендерирајте XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Мајкрософт Ексел Отвори XML табела" 

        # format loop 5
        - name: "Рендерирајте DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "Цртеж AutoCAD"

        # format loop 6
        - name: "Рендерирајте XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "XML-датотека"

        # format loop 7
        - name: "Рендерирајте PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Документ на Adobe Photoshop"

        # format loop 8
        - name: "Рендерирајте ја датотеката Adobe Illustrator"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Уметничко дело на Adobe Illustrator"

        # format loop 9
        - name: "Рендерирајте DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Microsoft Word документ" 

        # format loop 10
        - name: "Рендерирајте TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Обична текстуална датотека" 

        # format loop 11
        - name: "Рендерирајте DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Датотека со формат за размена на цртање"  
          
        # format loop 12
        - name: "Рендерирајте VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "vCard датотека"  
              
        # format loop 13
        - name: "Рендерирајте SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Скалабилна векторска графика" 
          
        # format loop 14
        - name: "Рендерирајте HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Датотека за јазик за означување на хипертекст" 
          
        # format loop 15
        - name: "Преведете PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Датотека за формат на пренослив документ"
          
        # format loop 16
        - name: "Рендерирајте JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "JPEG слика"
          
        # format loop 17
        - name: "Рендерирајте PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Пренослива мрежна графика" 
          
        # format loop 18
        - name: "Рендерирајте EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "E-mail порака" 
          
        # format loop 19
        - name: "Рендерирајте RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Датотека за формат на богат текст" 
          
        # format loop 20
        - name: "Рендерирајте ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "OpenDocument текстуален документ" 
          
        # format loop 21
        - name: "Рендерирајте CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Датотека со вредности разделени со запирки" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
