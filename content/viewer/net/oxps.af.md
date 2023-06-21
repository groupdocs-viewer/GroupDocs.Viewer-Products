---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: af

############################# Head #############################
head_title: ".NET OXPS Kyker-API - Lees, bekyk, lewer in C# VB.NET"
head_description: ".NET dokumentkyker-API om OXPS te lees, weer te gee en te vertoon in enige tipe C#-, ASP.NET-, VB.NET- en .NET Core-toepassings."

############################# Header ############################
title: "OXPS Lêerkyker vir C# .NET-toepassings" 
description: ".NET-dokumentkyker-API om OXPS-lêer te lees, weer te gee en te vertoon in enige tipe C#-, ASP.NET-, VB.NET- en .NET Core-toepassings. Bekyk die gelewerde lêers met ware formatering en uitleg in HTML5, PDF of as 'n prent deur 'n paar reëls van die kode te gebruik." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Laai gratis proeflopie af"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Oor GroupDocs.Viewer vir .NET API" 
    content: |
        Begin om 190+ gewilde dokumentformate in jou .NET-toepassings te bekyk deur GroupDocs.Viewer vir .NET API's te gebruik deur 'n paar reëls kode by te voeg. Ontwikkelaars kan maklik PDF, Woordverwerking, Excel Sigblad, Aanbieding, Visio, Project, Outlook en baie ander gewilde dokumentformate in HTML5, beeld of PDF-modusse vertoon. Die dokumentweergawe is vinnig, identies aan die oorspronklike bronlêer, en dit vereis nie die installering van bykomende sagteware of enige ander eksterne biblioteke nie.

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
              text: "API-verwysing"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Kode voorbeelde"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Regstreekse demonstrasies"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Pryse"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "Stappe om OXPS-lêer in C# weer te gee" 
    content_left: |
        Met [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/) kan jy OXPS in 'n paar stappe na HTML, JPEG, PNG of PDF weergee.

        * Installeer [GroupDocs.Viewer vir .NET](https://www.nuget.org/packages/groupdocs.viewer) deur jou gunsteling pakketbestuurder te gebruik. 
        * Skep 'n instansie van Viewer-klas en laai die OXPS-lêer met volle pad. 
        * Stel opsies om OXPS-lêer in HTML-, PNG-, JPEG- of PDF-formaat weer te gee. 
        * Lewer lêer en kontroleer uitvoer in die huidige gids. 
        
    title_right: "Stelselvereistes" 
    content_right: |
        GroupDocs.Viewer vir .NET API's word op alle groot platforms en bedryfstelsels ondersteun. Voordat u die kode hieronder uitvoer, maak asseblief seker dat u die volgende voorvereistes op u stelsel geïnstalleer het.

        * Bedryfstelsels: Microsoft Windows, Linux, MacOS 
        * Ontwikkelingsomgewings: Microsoft Visual Studio, Visual Studio Code, .NET CLI 
        * Raamwerke: .NET Framework, .NET Standard, .NET Core, .NET 
    code: |
        ```cs
                        
            // Set up input OXPS file
            string filePath = "input.oxps";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render OXPS file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "OXPS Kyker Regstreekse Demo"
    content: |
        Bekyk OXPS-lêer op die oomblik deur [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/oxps) se webwerf te besoek.
    lang: "af"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Ander lêerformate wat weergegee en bekyk word deur C#"
    exclude: "OXPS"
    content: |
        Multi-formaat dokumente en beelde kyker API vir. NET. Bekyk sommige van die gewilde lêerformate hieronder sonder enige eksterne kykers.
    format: 
        # format loop 1
        - name: "Lewer DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word Oop XML-dokument" 

        # format loop 2
        - name: "Lewer CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "CorelDRAW-lêer" 

        # format loop 3
        - name: "Lewer PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint Oop XML-aanbieding" 

        # format loop 4
        - name: "Gee XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Oop XML Sigblad" 

        # format loop 5
        - name: "Lewer DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "AutoCAD-tekening"

        # format loop 6
        - name: "Gee XML weer"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "XML-lêer"

        # format loop 7
        - name: "Lewer PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Adobe Photoshop-dokument"

        # format loop 8
        - name: "Gee Adobe Illustrator-lêer weer"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Adobe Illustrator kunswerk"

        # format loop 9
        - name: "Lewer DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Microsoft Word-dokument" 

        # format loop 10
        - name: "Lewer TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Gewone tekslêer" 

        # format loop 11
        - name: "Lewer DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Teken Exchange Format Lêer"  
          
        # format loop 12
        - name: "Lewer VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "vCard-lêer"  
              
        # format loop 13
        - name: "Gee SVG weer"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Skaalbare vektorgrafika" 
          
        # format loop 14
        - name: "Gee HTML weer"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "Lewer PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Draagbare dokumentformaat lêer"
          
        # format loop 16
        - name: "Gee JPEG weer"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "JPEG-beeld"
          
        # format loop 17
        - name: "Lewer PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Draagbare netwerkgrafika" 
          
        # format loop 18
        - name: "Lewer EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "E-pos Boodskap" 
          
        # format loop 19
        - name: "Lewer RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Rich Text Format Lêer" 
          
        # format loop 20
        - name: "Lewer ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "OpenDocument teksdokument" 
          
        # format loop 21
        - name: "Gee CSV weer"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Komma-geskeide waardelêer" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
