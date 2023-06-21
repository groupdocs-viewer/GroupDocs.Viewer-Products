---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: kk

############################# Head #############################
head_title: ".NET DCM Viewer API - C# VB.NET тілінде оқу, көру, көрсету"
head_description: "C#, ASP.NET, VB.NET және .NET Core қолданбаларының кез келген түріндегі DCM файлын оқу, көрсету және көрсету үшін .NET құжатты қарау API."

############################# Header ############################
title: "DCM C# .NET қолданбаларына арналған файлдарды қарау құралы" 
description: "C#, ASP.NET, VB.NET және .NET Core қолданбаларының кез келген түріндегі DCM файлын оқу, көрсету және көрсету үшін .NET құжатты қарау API. Көрсетілген файлдарды шынайы пішімдеумен және орналасумен HTML5, PDF немесе кодтың бірнеше жолын пайдаланып кескін ретінде қараңыз." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Тегін сынақ нұсқасын жүктеп алыңыз"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: ".NET API үшін GroupDocs.Viewer туралы" 
    content: |
        Кодтың бірнеше жолын қосу арқылы .NET API үшін GroupDocs.Viewer арқылы .NET қолданбаларында 190+ танымал құжат пішімдерін қарауды бастаңыз. Әзірлеушілер PDF, Word Processing, Excel Spreadsheet, Presentation, Visio, Project, Outlook және басқа да көптеген танымал құжат пішімдерін HTML5, кескін немесе PDF режимдерінде оңай көрсете алады. Құжатты көрсету жылдам, бастапқы бастапқы файлмен бірдей және ол қосымша бағдарламалық құралды немесе басқа сыртқы кітапханаларды орнатуды қажет етпейді.

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
    title_left: "DCM файлын C# ішінде көрсету қадамдары" 
    content_left: |
        [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/) көмегімен DCM файлын HTML, JPEG, PNG немесе PDF форматына бірнеше қадамда көрсетуге болады.

        * Таңдаулы бума менеджерін пайдаланып [GroupDocs.Viewer for .NET](https://www.nuget.org/packages/groupdocs.viewer) орнатыңыз. 
        * Viewer класының данасын жасаңыз және толық жолы бар DCM файлын жүктеңіз. 
        * DCM файлын HTML, PNG, JPEG немесе PDF пішімінде көрсету опцияларын орнатыңыз. 
        * Файлды көрсетіңіз және ағымдағы каталогтағы нәтижені тексеріңіз. 
        
    title_right: "Жүйе талаптары" 
    content_right: |
        .NET API интерфейстеріне арналған GroupDocs.Viewer бағдарламасына барлық негізгі платформалар мен операциялық жүйелерде қолдау көрсетіледі. Төмендегі кодты орындамас бұрын, жүйеде келесі алғышарттар орнатылғанына көз жеткізіңіз.

        * Операциялық жүйелер: Microsoft Windows, Linux, MacOS 
        * Әзірлеу орталары: Microsoft Visual Studio, Visual Studio Code, .NET CLI 
        * Frameworks: .NET Framework, .NET Standard, .NET Core, .NET 
    code: |
        ```cs
                        
            // Set up input DCM file
            string filePath = "input.dcm";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render DCM file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "DCM Көрерменнің тікелей көрсетілімі"
    content: |
        DCM файлын дәл қазір [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/dcm) веб-сайтына кіру арқылы қараңыз.
    lang: "kk"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Басқа файл пішімдері C# арқылы көрсету және қарау"
    exclude: "DCM"
    content: |
        .NET үшін көп форматты құжаттар мен кескіндерді қарау API. Төмендегі кейбір танымал файл пішімдерін сыртқы көрушілерсіз қараңыз.
    format: 
        # format loop 1
        - name: "DOCX көрсету"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word ашық XML құжаты" 

        # format loop 2
        - name: "CDR көрсету" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "CorelDRAW файлы" 

        # format loop 3
        - name: "PPTX көрсету"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint ашық XML презентациясы" 

        # format loop 4
        - name: "XLSX көрсету"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel ашық XML электрондық кестесі" 

        # format loop 5
        - name: "DWG көрсету"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "AutoCAD сызбасы"

        # format loop 6
        - name: "XML көрсету"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "XML файлы"

        # format loop 7
        - name: "PSD көрсету"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Adobe Photoshop құжаты"

        # format loop 8
        - name: "Adobe Illustrator файлын көрсетіңіз"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Adobe Illustrator Artwork"

        # format loop 9
        - name: "DOC көрсету"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Microsoft Word құжаты" 

        # format loop 10
        - name: "TXT көрсету" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Қарапайым мәтіндік файл" 

        # format loop 11
        - name: "DXF көрсету" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Exchange пішімінің файлын салу"  
          
        # format loop 12
        - name: "VCF көрсету"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "vCard файлы"  
              
        # format loop 13
        - name: "SVG көрсету"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Масштабталатын векторлық графика" 
          
        # format loop 14
        - name: "HTML көрсету"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Гипермәтіндік белгілеу тілінің файлы" 
          
        # format loop 15
        - name: "PDF көрсету"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Портативті құжат пішімі файлы"
          
        # format loop 16
        - name: "JPEG көрсету"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "JPEG кескіні"
          
        # format loop 17
        - name: "PNG көрсету"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Портативті желілік графика" 
          
        # format loop 18
        - name: "EML көрсету"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "Электрондық пошта хабары" 
          
        # format loop 19
        - name: "RTF көрсету"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Rich Text Format File" 
          
        # format loop 20
        - name: "ODT көрсету"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "OpenDocument мәтіндік құжаты" 
          
        # format loop 21
        - name: "CSV көрсету"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Үтірмен бөлінген мәндер файлы" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
