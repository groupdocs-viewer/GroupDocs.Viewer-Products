---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: da

############################# Head #############################
head_title: ".NET PCL Viewer API - Læs, Vis, Render i C# VB.NET"
head_description: ".NET document viewer API til at læse, gengive og vise PCL i enhver type C#, ASP.NET, VB.NET og .NET Core applikationer."

############################# Header ############################
title: "PCL Filfremviser til C# .NET-applikationer" 
description: ".NET document viewer API til at læse, gengive og vise PCL fil i enhver type C#, ASP.NET, VB.NET og .NET Core applikationer. Se de gengivede filer med ægte formatering og layout i HTML5, PDF eller som et billede ved hjælp af et par linjer af koden." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Download gratis prøveversion"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Om GroupDocs.Viewer til .NET API" 
    content: |
        Begynd at se mere end 190 populære dokumentformater i dine .NET-applikationer ved hjælp af GroupDocs.Viewer til .NET API'er ved at tilføje et par linjer kode. Udviklere kan nemt vise PDF, tekstbehandling, Excel-regneark, præsentation, Visio, Project, Outlook og mange andre populære dokumentformater i HTML5-, billed- eller PDF-tilstande. Dokumentgengivelsen er hurtig, identisk med den originale kildefil, og den kræver ikke installation af yderligere software eller andre eksterne biblioteker.

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
              text: "API-reference"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Kode eksempler"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Live demoer"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Prissætning"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "Trin til gengivelse af filen PCL i C#" 
    content_left: |
        Med [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/) kan du gengive PCL til HTML, JPEG, PNG eller PDF i nogle få trin.

        * Installer [GroupDocs.Viewer for .NET](https://www.nuget.org/packages/groupdocs.viewer) ved hjælp af din foretrukne pakkehåndtering. 
        * Opret en forekomst af Viewer-klassen og indlæs PCL-filen med fuld sti. 
        * Indstil muligheder for at gengive filen PCL til HTML-, PNG-, JPEG- eller PDF-format. 
        * Gengiv filen og kontroller output i den aktuelle mappe. 
        
    title_right: "Systemkrav" 
    content_right: |
        GroupDocs.Viewer til .NET API'er understøttes på alle større platforme og operativsystemer. Før du udfører koden nedenfor, skal du sørge for, at du har følgende forudsætninger installeret på dit system.

        * Operativsystemer: Microsoft Windows, Linux, MacOS 
        * Udviklingsmiljøer: Microsoft Visual Studio, Visual Studio Code, .NET CLI 
        * Frameworks: .NET Framework, .NET Standard, .NET Core, .NET 
    code: |
        ```cs
                        
            // Set up input PCL file
            string filePath = "input.pcl";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render PCL file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "PCL Live-demo"
    content: |
        Se filen PCL lige nu ved at besøge webstedet [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/pcl).
    lang: "da"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Andre filformater gengivelse og visning ved hjælp af C#"
    exclude: "PCL"
    content: |
        Multi-format dokumenter og billeder viewer API til .NET. Se nogle af de populære filformater nedenfor uden eksterne seere.
    format: 
        # format loop 1
        - name: "Render DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word Open XML-dokument" 

        # format loop 2
        - name: "Gengiv CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "CorelDRAW-fil" 

        # format loop 3
        - name: "Gengiv PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint Open XML-præsentation" 

        # format loop 4
        - name: "Gengiv XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Open XML-regneark" 

        # format loop 5
        - name: "Gengiv DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "AutoCAD tegning"

        # format loop 6
        - name: "Gengiv XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "XML-fil"

        # format loop 7
        - name: "Gengiv PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Adobe Photoshop-dokument"

        # format loop 8
        - name: "Gengiv Adobe Illustrator-fil"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Adobe Illustrator kunstværk"

        # format loop 9
        - name: "Gengiv DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Microsoft Word-dokument" 

        # format loop 10
        - name: "Gengiv TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Almindelig tekstfil" 

        # format loop 11
        - name: "Render DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Tegning af Exchange-formatfil"  
          
        # format loop 12
        - name: "Render VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "vCard-fil"  
              
        # format loop 13
        - name: "Gengiv SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Skalerbar vektorgrafik" 
          
        # format loop 14
        - name: "Gengiv HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "Gengiv PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Fil i bærbart dokumentformat"
          
        # format loop 16
        - name: "Gengiv JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "JPEG billede"
          
        # format loop 17
        - name: "Gengiv PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Bærbar netværksgrafik" 
          
        # format loop 18
        - name: "Gør EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "E-mail besked" 
          
        # format loop 19
        - name: "Gengiv RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Rich Text Format fil" 
          
        # format loop 20
        - name: "Render ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "OpenDocument tekstdokument" 
          
        # format loop 21
        - name: "Gengiv CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Kommaseparerede værdier fil" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
