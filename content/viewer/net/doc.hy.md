---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: hy

############################# Head #############################
head_title: ".NET DOC Viewer API - Կարդացեք, դիտեք, ցուցադրեք C# VB.NET-ում"
head_description: ".NET փաստաթղթերի դիտման API՝ կարդալու, ցուցադրելու և ցուցադրելու DOC ցանկացած տեսակի C#, ASP.NET, VB.NET և .NET Core հավելվածներում:"

############################# Header ############################
title: "DOC Ֆայլերի դիտիչ C# .NET հավելվածների համար" 
description: ".NET փաստաթղթերի դիտման API՝ DOC ֆայլը կարդալու, ցուցադրելու և ցուցադրելու ցանկացած տեսակի C#, ASP.NET, VB.NET և .NET Core հավելվածներում: Դիտեք մատուցված ֆայլերը իրական ձևաչափմամբ և դասավորությամբ HTML5, PDF կամ որպես պատկեր՝ օգտագործելով կոդի մի քանի տող:" 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Ներբեռնեք անվճար փորձաշրջան"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "GroupDocs.Viewer-ի մասին .NET API-ի համար" 
    content: |
        Սկսեք դիտել 190+ հայտնի փաստաթղթերի ձևաչափեր ձեր .NET հավելվածներում՝ օգտագործելով GroupDocs.Viewer-ը .NET API-ների համար՝ ավելացնելով մի քանի տող կոդ: Մշակողները կարող են հեշտությամբ ցուցադրել PDF, Word Processing, Excel Spreadsheet, Presentation, Visio, Project, Outlook և շատ այլ հայտնի փաստաթղթերի ձևաչափեր HTML5, պատկերի կամ PDF ռեժիմներում: Փաստաթղթի մատուցումը արագ է, նույնական է սկզբնական սկզբնաղբյուր ֆայլին, և այն չի պահանջում լրացուցիչ ծրագրակազմի կամ այլ արտաքին գրադարանների տեղադրում:

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
    title_left: "DOC ֆայլը C#-ում ցուցադրելու քայլեր" 
    content_left: |
        [GroupDocs.Viewer] (https://products.groupdocs.com/viewer/net/) միջոցով դուք կարող եք մի քանի քայլով թարգմանել DOC-ը HTML, JPEG, PNG կամ PDF:

        * Տեղադրեք [GroupDocs.Viewer-ը .NET-ի համար](https://www.nuget.org/packages/groupdocs.viewer)՝ օգտագործելով ձեր սիրելի փաթեթների կառավարիչը: 
        * Ստեղծեք Viewer դասի օրինակ և բեռնեք DOC ֆայլը ամբողջ ճանապարհով: 
        * Սահմանեք ընտրանքներ՝ DOC ֆայլը HTML, PNG, JPEG կամ PDF ձևաչափով վերածելու համար: 
        * Ներկայացրեք ֆայլը և ստուգեք արդյունքը ընթացիկ գրացուցակում: 
        
    title_right: "Համակարգի պահանջները" 
    content_right: |
        GroupDocs.Viewer-ը .NET API-ների համար աջակցվում է բոլոր հիմնական հարթակներում և օպերացիոն համակարգերում: Նախքան ստորև նշված կոդը գործարկելը, համոզվեք, որ ձեր համակարգում տեղադրված են հետևյալ նախադրյալները.

        * Օպերացիոն համակարգեր՝ Microsoft Windows, Linux, MacOS 
        * Զարգացման միջավայրեր՝ Microsoft Visual Studio, Visual Studio Code, .NET CLI 
        * Frameworks՝ .NET Framework, .NET Standard, .NET Core, .NET 
    code: |
        ```cs
                        
            // Set up input DOC file
            string filePath = "input.doc";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render DOC file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "DOC Viewer Live Demo"
    content: |
        Դիտեք DOC ֆայլը հենց հիմա՝ այցելելով [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/doc) կայքը:
    lang: "hy"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Ֆայլի այլ ձևաչափեր, որոնք ցուցադրվում և դիտվում են C#-ի միջոցով"
    exclude: "DOC"
    content: |
        Բազմաֆորմատ փաստաթղթեր և պատկերներ դիտող API .NET-ի համար: Դիտեք ստորև ներկայացված ֆայլերի հայտնի ձևաչափերից մի քանիսը առանց արտաքին դիտողների:
    format: 
        # format loop 1
        - name: "Ներկայացրեք DOCX-ը"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word բաց XML փաստաթուղթ" 

        # format loop 2
        - name: "Ցուցադրել CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "CorelDRAW ֆայլ" 

        # format loop 3
        - name: "Ներկայացրեք PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint Բաց XML ներկայացում" 

        # format loop 4
        - name: "Render XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel բաց XML աղյուսակ" 

        # format loop 5
        - name: "Render DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "AutoCAD Նկարչություն"

        # format loop 6
        - name: "Ներկայացրեք XML-ը"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "XML ֆայլ"

        # format loop 7
        - name: "Render PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Adobe Photoshop փաստաթուղթ"

        # format loop 8
        - name: "Ներկայացրեք Adobe Illustrator ֆայլը"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Adobe Illustrator-ի գեղարվեստական ​​աշխատանք"

        # format loop 9
        - name: "Ներկայացրեք DOC-ը"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Microsoft Word փաստաթուղթ" 

        # format loop 10
        - name: "Ներկայացրեք TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Պարզ տեքստային ֆայլ" 

        # format loop 11
        - name: "Render DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Նկարչության փոխանակման ձևաչափի ֆայլ"  
          
        # format loop 12
        - name: "Render VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "vCard ֆայլ"  
              
        # format loop 13
        - name: "Render SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Ընդարձակվող վեկտորային գրաֆիկա" 
          
        # format loop 14
        - name: "Ներկայացնել HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Հիպերտեքստի նշագրման լեզվի ֆայլ" 
          
        # format loop 15
        - name: "Պատկերացրեք PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Դյուրակիր փաստաթղթի ձևաչափի ֆայլ"
          
        # format loop 16
        - name: "Պատկերացրեք JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "JPEG պատկեր"
          
        # format loop 17
        - name: "Render PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Դյուրակիր ցանցային գրաֆիկա" 
          
        # format loop 18
        - name: "Render EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "Էլեկտրոնային փոստի հաղորդագրություն" 
          
        # format loop 19
        - name: "Ներկայացրեք RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Հարուստ տեքստի ձևաչափի ֆայլ" 
          
        # format loop 20
        - name: "Ներկայացնել ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "OpenDocument տեքստային փաստաթուղթ" 
          
        # format loop 21
        - name: "Ներկայացրեք CSV-ը"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Ստորակետերով բաժանված արժեքների ֆայլ" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
