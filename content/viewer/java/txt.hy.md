---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: hy

############################# Head #############################
head_title: "Java TXT Viewer API - Արտադրել և ցուցադրել TXT-ը Java հավելվածներում"
head_description: "Դիտեք TXT ֆայլեր Java, J2EE, J2SE հավելվածներում: Աջակցում է 170+ փաստաթղթերի և պատկերի ֆայլերի ձևաչափերի դիտում HTML, PDF կամ պատկերի ռեժիմում՝ առաջադեմ գործառույթներով՝ փաստաթղթերի դիտման ընտրանքները կառավարելու համար:"

############################# Header ############################
title: "Արտադրել և դիտել TXT Java-ում" 
description: "Բնական և բարձր արդյունավետությամբ TXT ֆայլերի դիտման API Java, J2EE և J2SE հիմնված հավելվածների համար, որն աջակցում է լրացուցիչ հնարավորությունների լայն շրջանակ՝ ելքային փաստաթղթի ձևաչափը հարմարեցնելու համար:" 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Ներբեռնեք անվճար փորձաշրջան"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "GroupDocs.Viewer-ի Java API-ի մասին" 
    content: |
        Թույլ տվեք ձեր Java հավելվածներին ցուցադրել ավելի քան 170+ ֆայլի ձևաչափեր HTML, PDF կամ պատկերի ռեժիմներում՝ օգտագործելով GroupDocs.Viewer Java API-ների համար՝ առանց որևէ լրացուցիչ ծրագրաշարի տեղադրման; ինչպիսիք են Microsoft Office, Apache Open Office, Adobe Acrobat Reader և այլն: Մշակողները կարող են հեշտությամբ դիտել բոլոր հայտնի պատկերները և փաստաթղթերի տեսակները, ներառյալ Microsoft Office, OpenDocument, HTML, PDF, Archive, Diagrams, Photoshop, AutoCAD և ծրագրավորման լեզուների ձևաչափերը Java հավելվածների ներսում: արագ և բարձրորակ մատուցում։

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
              text: "API հղում"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Կոդի օրինակներ"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Կենդանի Դեմոներ"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Գնագոյացում"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "TXT ֆայլը Java-ում ցուցադրելու քայլեր" 
    content_left: |
        [GroupDocs.Viewer] (https://products.groupdocs.com/viewer/java/) օգնությամբ դուք կարող եք մի քանի քայլով TXT-ը վերածել HTML, JPEG, PNG կամ PDF:

        * Ավելացրեք [GroupDocs.Viewer for Java](https://releases.groupdocs.com/viewer/java/) որպես կախվածություն ձեր նախագծին: 
        * Ստեղծեք Viewer դասի օրինակ և բեռնեք TXT ֆայլը ամբողջ ճանապարհով: 
        * Սահմանեք ընտրանքներ՝ TXT ֆայլը HTML, PNG, JPEG կամ PDF ձևաչափով վերածելու համար: 
        * Ներկայացրեք ֆայլը և ստուգեք արդյունքը ընթացիկ գրացուցակում: 
        
    title_right: "Համակարգի պահանջները" 
    content_right: |
        GroupDocs.Viewer-ը Java API-ների համար աջակցվում է բոլոր հիմնական հարթակներում և օպերացիոն համակարգերում: Նախքան ստորև նշված կոդը գործարկելը, համոզվեք, որ ձեր համակարգում տեղադրված են հետևյալ նախադրյալները.

        * Օպերացիոն համակարգեր՝ Microsoft Windows, Linux, MacOS 
        * Զարգացման միջավայրեր՝ NetBeans, IntelliJ IDEA, Eclipse և այլն: 
        * Շրջանակներ՝ J2SE 8.0 (1.8) կամ ավելի բարձր (օրինակ՝ Java 17) 
    code: |
        ```java
                        
            // Set up input TXT file
            String filePath = "input.txt";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render TXT file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "TXT Viewer Live Demo"
    content: |
        Դիտեք TXT ֆայլը հենց հիմա՝ այցելելով [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/txt) կայքը:
    lang: "hy"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Ֆայլի այլ ձևաչափեր, որոնք ցուցադրվում և դիտվում են Java-ի միջոցով"
    exclude: "TXT"
    content: |
        Բազմաֆորմատ փաստաթղթեր և պատկերներ դիտող API Java-ի համար: Դիտեք ստորև ներկայացված ֆայլերի հայտնի ձևաչափերից մի քանիսը առանց արտաքին դիտողների:
    format: 
        # format loop 1
        - name: "Ներկայացրեք DOCX-ը"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word բաց XML փաստաթուղթ" 

        # format loop 2
        - name: "Ցուցադրել CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "CorelDRAW ֆայլ" 

        # format loop 3
        - name: "Ներկայացրեք PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint Բաց XML ներկայացում" 

        # format loop 4
        - name: "Render XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel բաց XML աղյուսակ" 

        # format loop 5
        - name: "Render DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "AutoCAD Նկարչություն"

        # format loop 6
        - name: "Ներկայացրեք XML-ը"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "XML ֆայլ"

        # format loop 7
        - name: "Render PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Adobe Photoshop փաստաթուղթ"

        # format loop 8
        - name: "Ներկայացրեք Adobe Illustrator ֆայլը"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Adobe Illustrator-ի գեղարվեստական ​​աշխատանք"

        # format loop 9
        - name: "Ներկայացրեք DOC-ը"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Microsoft Word փաստաթուղթ" 

        # format loop 10
        - name: "Ներկայացրեք TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Պարզ տեքստային ֆայլ" 

        # format loop 11
        - name: "Render DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Նկարչության փոխանակման ձևաչափի ֆայլ"  
          
        # format loop 12
        - name: "Render VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "vCard ֆայլ"  
              
        # format loop 13
        - name: "Render SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Ընդարձակվող վեկտորային գրաֆիկա" 
          
        # format loop 14
        - name: "Ներկայացնել HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Հիպերտեքստի նշագրման լեզվի ֆայլ" 
          
        # format loop 15
        - name: "Պատկերացրեք PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Դյուրակիր փաստաթղթի ձևաչափի ֆայլ"
          
        # format loop 16
        - name: "Պատկերացրեք JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "JPEG պատկեր"
          
        # format loop 17
        - name: "Render PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Դյուրակիր ցանցային գրաֆիկա" 
          
        # format loop 18
        - name: "Render EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "Էլեկտրոնային փոստի հաղորդագրություն" 
          
        # format loop 19
        - name: "Ներկայացրեք RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Հարուստ տեքստի ձևաչափի ֆայլ" 
          
        # format loop 20
        - name: "Ներկայացնել ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "OpenDocument տեքստային փաստաթուղթ" 
          
        # format loop 21
        - name: "Ներկայացրեք CSV-ը"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Ստորակետերով բաժանված արժեքների ֆայլ" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
