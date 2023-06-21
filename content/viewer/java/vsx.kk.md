---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: kk

############################# Head #############################
head_title: "Java VSX Viewer API - Java қолданбаларында VSX көрсету және көрсету"
head_description: "Java, J2EE, J2SE қолданбаларында VSX файлдарды қараңыз. Құжатты қарау опцияларын басқару үшін кеңейтілген мүмкіндіктері бар HTML, PDF немесе кескін режимінде 170+ құжат пен кескін файл пішімін қарауды қолдайды."

############################# Header ############################
title: "Java тілінде VSX көрсету және көру" 
description: "Java, J2EE және J2SE негізіндегі қолданбаларға арналған түпнұсқа және жоғары өнімділік VSX файлды қарау API, шығыс құжат пішімінің көрінісін теңшеу үшін кең ауқымды қосымша мүмкіндіктерді қолдайды." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Тегін сынақ нұсқасын жүктеп алыңыз"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Java API үшін GroupDocs.Viewer туралы" 
    content: |
        Java қолданбаларын ешбір қосымша бағдарламалық құрал орнатылмай, Java API интерфейстеріне арналған GroupDocs.Viewer арқылы HTML, PDF немесе кескін режимдерінде 170-тен астам файл пішімдерін көрсетуге қосыңыз; Microsoft Office, Apache Open Office, Adobe Acrobat Reader т.б. сияқты. Әзірлеушілер барлық танымал кескіндер мен құжат түрлерін, соның ішінде Microsoft Office, OpenDocument, HTML, PDF, Archive, Diagrams, Photoshop, AutoCAD және Java қолданбаларының ішіндегі бағдарламалау тілі пішімдерін оңай көре алады. жылдам және жоғары сапалы көрсету.

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
              text: "API анықтамасы"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Код мысалдары"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Тікелей демонстрациялар"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Баға белгілеу"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "VSX файлын Java ішінде көрсету қадамдары" 
    content_left: |
        [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/) көмегімен VSX файлын HTML, JPEG, PNG немесе PDF форматтарына бірнеше қадаммен көрсетуге болады.

        * Жобаңызға тәуелділік ретінде [GroupDocs.Viewer for Java](https://releases.groupdocs.com/viewer/java/) қосыңыз. 
        * Viewer класының данасын жасаңыз және толық жолы бар VSX файлын жүктеңіз. 
        * VSX файлын HTML, PNG, JPEG немесе PDF пішімінде көрсету опцияларын орнатыңыз. 
        * Файлды көрсетіңіз және ағымдағы каталогтағы нәтижені тексеріңіз. 
        
    title_right: "Жүйе талаптары" 
    content_right: |
        Java API интерфейстеріне арналған GroupDocs.Viewer бағдарламасына барлық негізгі платформалар мен операциялық жүйелерде қолдау көрсетіледі. Төмендегі кодты орындамас бұрын, жүйеде келесі алғышарттар орнатылғанына көз жеткізіңіз.

        * Операциялық жүйелер: Microsoft Windows, Linux, MacOS 
        * Әзірлеу орталары: NetBeans, IntelliJ IDEA, Eclipse т.б. 
        * Frameworks: J2SE 8.0 (1.8) немесе одан жоғары (мысалы, Java 17) 
    code: |
        ```java
                        
            // Set up input VSX file
            String filePath = "input.vsx";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render VSX file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "VSX Көрерменнің тікелей көрсетілімі"
    content: |
        VSX файлын дәл қазір [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/vsx) веб-сайтына кіру арқылы қараңыз.
    lang: "kk"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Басқа файл пішімдері Java арқылы көрсету және қарау"
    exclude: "VSX"
    content: |
        Java үшін көп форматты құжаттар мен кескіндерді қарау API. Төмендегі кейбір танымал файл пішімдерін сыртқы көрушілерсіз қараңыз.
    format: 
        # format loop 1
        - name: "DOCX көрсету"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word ашық XML құжаты" 

        # format loop 2
        - name: "CDR көрсету" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "CorelDRAW файлы" 

        # format loop 3
        - name: "PPTX көрсету"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint ашық XML презентациясы" 

        # format loop 4
        - name: "XLSX көрсету"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel ашық XML электрондық кестесі" 

        # format loop 5
        - name: "DWG көрсету"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "AutoCAD сызбасы"

        # format loop 6
        - name: "XML көрсету"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "XML файлы"

        # format loop 7
        - name: "PSD көрсету"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Adobe Photoshop құжаты"

        # format loop 8
        - name: "Adobe Illustrator файлын көрсетіңіз"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Adobe Illustrator Artwork"

        # format loop 9
        - name: "DOC көрсету"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Microsoft Word құжаты" 

        # format loop 10
        - name: "TXT көрсету" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Қарапайым мәтіндік файл" 

        # format loop 11
        - name: "DXF көрсету" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Exchange пішімінің файлын салу"  
          
        # format loop 12
        - name: "VCF көрсету"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "vCard файлы"  
              
        # format loop 13
        - name: "SVG көрсету"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Масштабталатын векторлық графика" 
          
        # format loop 14
        - name: "HTML көрсету"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Гипермәтіндік белгілеу тілінің файлы" 
          
        # format loop 15
        - name: "PDF көрсету"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Портативті құжат пішімі файлы"
          
        # format loop 16
        - name: "JPEG көрсету"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "JPEG кескіні"
          
        # format loop 17
        - name: "PNG көрсету"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Портативті желілік графика" 
          
        # format loop 18
        - name: "EML көрсету"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "Электрондық пошта хабары" 
          
        # format loop 19
        - name: "RTF көрсету"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Rich Text Format File" 
          
        # format loop 20
        - name: "ODT көрсету"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "OpenDocument мәтіндік құжаты" 
          
        # format loop 21
        - name: "CSV көрсету"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Үтірмен бөлінген мәндер файлы" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
