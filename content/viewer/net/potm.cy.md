---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: cy

############################# Head #############################
head_title: ".NET POTM Viewer API - Darllen, Gweld, Rendro yn C# VB.NET"
head_description: "API gwyliwr dogfen .NET i ddarllen, rendrad ac arddangos POTM mewn unrhyw fath o gymwysiadau C#, ASP.NET, VB.NET & .NET Core."

############################# Header ############################
title: "POTM Gwyliwr Ffeil Ar Gyfer C# .NET Applications" 
description: ".NET document viewer API i ddarllen, rendrad ac arddangos POTM ffeil mewn unrhyw fath o C#, ASP.NET, VB.NET & .NET Core ceisiadau. Gweld y ffeiliau wedi'u rendro gyda gwir fformat a gosodiad yn HTML5, PDF neu fel delwedd gan ddefnyddio ychydig o linellau o'r cod." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Download Treial Am Ddim"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Ynglŷn â GroupDocs.Viewer ar gyfer .NET API" 
    content: |
        Dechreuwch edrych ar 190+ o fformatau dogfen poblogaidd yn eich cymwysiadau .NET gan ddefnyddio GroupDocs.Viewer ar gyfer .NET APIs trwy ychwanegu ychydig linellau o god. Gall datblygwyr arddangos PDF, Prosesu Geiriau, Taenlen Excel, Cyflwyniad, Visio, Project, Outlook a llawer o fformatau dogfen poblogaidd eraill yn hawdd mewn moddau HTML5, delwedd neu PDF. Mae'r broses rendro dogfennau yn gyflym, yn union yr un fath â'r ffeil ffynhonnell wreiddiol, ac nid oes angen gosod meddalwedd ychwanegol nac unrhyw lyfrgelloedd allanol eraill.

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
              text: "Cyfeirnod API"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Enghreifftiau Cod"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Demos Byw"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Prisio"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "Camau i Rendro ffeil POTM yn C#" 
    content_left: |
        Gyda [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/) gallwch rendro POTM i HTML, JPEG, PNG neu PDF mewn ychydig o gamau.

        * Gosod [GroupDocs.Viewer ar gyfer .NET](https://www.nuget.org/packages/groupdocs.viewer) gan ddefnyddio eich hoff reolwr pecynnau. 
        * Creu enghraifft o ddosbarth Gwyliwr a llwytho'r ffeil POTM gyda llwybr llawn. 
        * Gosod opsiynau i rendr ffeil POTM i fformat HTML, PNG, JPEG neu PDF. 
        * Rendro ffeil a gwirio allbwn yn y cyfeiriadur cyfredol. 
        
    title_right: "Gofynion y System" 
    content_right: |
        Cefnogir GroupDocs.Viewer ar gyfer APIs .NET ar yr holl brif lwyfannau a systemau gweithredu. Cyn gweithredu'r cod isod, gwnewch yn siŵr bod gennych y rhagofynion canlynol wedi'u gosod ar eich system.

        * Systemau Gweithredu: Microsoft Windows, Linux, MacOS 
        * Amgylcheddau Datblygu: Microsoft Visual Studio, Visual Studio Code, .NET CLI 
        * Fframweithiau: .NET Framework, .NET Standard, .NET Core, .NET 
    code: |
        ```cs
                        
            // Set up input POTM file
            string filePath = "input.potm";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render POTM file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "POTM Viewer Live Demo"
    content: |
        Gweld POTM ffeil ar hyn o bryd drwy ymweld â gwefan [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/potm).
    lang: "cy"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Fformatau Ffeil Eraill Rendro a Gweld gan ddefnyddio C#"
    exclude: "POTM"
    content: |
        Dogfennau aml-fformat a delwedd gwyliwr API ar gyfer .NET. Gweld rhai o'r fformatau ffeil poblogaidd isod heb unrhyw wylwyr allanol.
    format: 
        # format loop 1
        - name: "Rendro DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word Dogfen XML Agored" 

        # format loop 2
        - name: "Rendro CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "Ffeil CorelDRAW" 

        # format loop 3
        - name: "Rendro PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint Open XML Presentation" 

        # format loop 4
        - name: "Rendro XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Agor Taenlen XML" 

        # format loop 5
        - name: "Rendro DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "Lluniadu AutoCAD"

        # format loop 6
        - name: "Rendro XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "Ffeil XML"

        # format loop 7
        - name: "Rendro PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Dogfen Adobe Photoshop"

        # format loop 8
        - name: "Rendro ffeil Adobe Illustrator"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Gwaith Celf Adobe Illustrator"

        # format loop 9
        - name: "Rendro DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Dogfen Microsoft Word" 

        # format loop 10
        - name: "Rendro TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Ffeil Testun Plaen" 

        # format loop 11
        - name: "Rendro DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Arlunio Ffeil Fformat Cyfnewid"  
          
        # format loop 12
        - name: "Rendro VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "Ffeil vCard"  
              
        # format loop 13
        - name: "Rendro SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Graffeg Fector Graddadwy" 
          
        # format loop 14
        - name: "Rendro HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Ffeil Iaith Marcio Hyperdestun" 
          
        # format loop 15
        - name: "Rendro PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Ffeil Fformat Dogfen Gludadwy"
          
        # format loop 16
        - name: "Rendro JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "Delwedd JPEG"
          
        # format loop 17
        - name: "Rendro PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Graffeg Rhwydwaith Cludadwy" 
          
        # format loop 18
        - name: "Rendro EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "Neges E-bost" 
          
        # format loop 19
        - name: "Rendro RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Ffeil Fformat Testun Cyfoethog" 
          
        # format loop 20
        - name: "Rendro ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "Dogfen Testun OpenDocument" 
          
        # format loop 21
        - name: "Rendro CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Ffeil Gwerthoedd Wedi'u Gwahanu gan Goma" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
