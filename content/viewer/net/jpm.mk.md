---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: mk

############################# Head #############################
head_title: ".NET JPM API за прегледувач - Читање, прегледување, прикажување во C# VB.NET"
head_description: ".NET API за прегледувач на документи за читање, прикажување и прикажување на JPM во кој било тип на C#, ASP.NET, VB.NET и .NET Core апликации."

############################# Header ############################
title: "JPM Прегледувач на датотеки за C# .NET апликации" 
description: ".NET API за прегледувач на документи за читање, прикажување и прикажување на датотеката JPM во кој било тип на C#, ASP.NET, VB.NET и .NET Core апликации. Прегледајте ги рендерираните датотеки со вистинско форматирање и распоред во HTML5, PDF или како слика користејќи неколку линии од кодот." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Преземете бесплатен пробен период"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "За GroupDocs.Viewer за .NET API" 
    content: |
        Започнете да гледате повеќе од 190 популарни формати на документи во вашите .NET апликации користејќи GroupDocs.Viewer за .NET API со додавање на неколку линии код. Програмерите можат лесно да прикажат PDF, обработка на текст, Excel табеларни пресметки, презентации, Visio, проект, Outlook и многу други популарни формати на документи во режими HTML5, слика или PDF. Рендерирањето на документите е брзо, идентично со оригиналната изворна датотека и не бара инсталирање дополнителен софтвер или други надворешни библиотеки.

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
    title_left: "Чекори за прикажување на датотеката JPM во C#" 
    content_left: |
        Со [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/) може да го преведете JPM во HTML, JPEG, PNG или PDF во неколку чекори.

        * Инсталирајте го [GroupDocs.Viewer за .NET](https://www.nuget.org/packages/groupdocs.viewer) користејќи го вашиот омилен менаџер на пакети. 
        * Направете примерок од класата Viewer и вчитајте ја датотеката JPM со целосна патека. 
        * Поставете опции за прикажување на датотеката JPM во HTML, PNG, JPEG или PDF формат. 
        * Рендерирајте ја датотеката и проверете го излезот во тековниот директориум. 
        
    title_right: "Системски барања" 
    content_right: |
        GroupDocs.Viewer за .NET API се поддржани на сите главни платформи и оперативни системи. Пред да го извршите кодот подолу, проверете дали ги имате инсталирано следните предуслови на вашиот систем.

        * Оперативни системи: Microsoft Windows, Linux, MacOS 
        * Развојни средини: Microsoft Visual Studio, Visual Studio Code, .NET CLI 
        * Рамки: .NET Framework, .NET Standard, .NET Core, .NET 
    code: |
        ```cs
                        
            // Set up input JPM file
            string filePath = "input.jpm";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render JPM file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "JPM Прегледувач во живо демо"
    content: |
        Погледнете ја датотеката JPM во моментов со посета на веб-локацијата [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/jpm).
    lang: "mk"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Други формати на датотеки што се прикажуваат и се прикажуваат со користење на C#"
    exclude: "JPM"
    content: |
        API за прегледувач на документи и слики со повеќе формати за .NET. Погледнете некои од популарните формати на датотеки подолу без никакви надворешни гледачи.
    format: 
        # format loop 1
        - name: "Рендерирајте го DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word Отвори XML документ" 

        # format loop 2
        - name: "Рендерирајте CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "Датотека CorelDRAW" 

        # format loop 3
        - name: "Рендерирајте PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint Отворете XML презентација" 

        # format loop 4
        - name: "Рендерирајте XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Мајкрософт Ексел Отвори XML табела" 

        # format loop 5
        - name: "Рендерирајте DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "Цртеж AutoCAD"

        # format loop 6
        - name: "Рендерирајте XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "XML-датотека"

        # format loop 7
        - name: "Рендерирајте PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Документ на Adobe Photoshop"

        # format loop 8
        - name: "Рендерирајте ја датотеката Adobe Illustrator"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Уметничко дело на Adobe Illustrator"

        # format loop 9
        - name: "Рендерирајте DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Microsoft Word документ" 

        # format loop 10
        - name: "Рендерирајте TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Обична текстуална датотека" 

        # format loop 11
        - name: "Рендерирајте DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Датотека со формат за размена на цртање"  
          
        # format loop 12
        - name: "Рендерирајте VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "vCard датотека"  
              
        # format loop 13
        - name: "Рендерирајте SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Скалабилна векторска графика" 
          
        # format loop 14
        - name: "Рендерирајте HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Датотека за јазик за означување на хипертекст" 
          
        # format loop 15
        - name: "Преведете PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Датотека за формат на пренослив документ"
          
        # format loop 16
        - name: "Рендерирајте JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "JPEG слика"
          
        # format loop 17
        - name: "Рендерирајте PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Пренослива мрежна графика" 
          
        # format loop 18
        - name: "Рендерирајте EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "E-mail порака" 
          
        # format loop 19
        - name: "Рендерирајте RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Датотека за формат на богат текст" 
          
        # format loop 20
        - name: "Рендерирајте ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "OpenDocument текстуален документ" 
          
        # format loop 21
        - name: "Рендерирајте CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Датотека со вредности разделени со запирки" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
