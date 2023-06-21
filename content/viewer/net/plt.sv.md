---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: sv

############################# Head #############################
head_title: ".NET PLT Viewer API - Läs, visa, rendera i C# VB.NET"
head_description: ".NET Document Viewer API för att läsa, rendera och visa PLT i alla typer av C#, ASP.NET, VB.NET och .NET Core-applikationer."

############################# Header ############################
title: "Plt Filvisare för C# .NET-applikationer" 
description: ".NET Document Viewer API för att läsa, rendera och visa PLT-fil i alla typer av C#-, ASP.NET-, VB.NET- och .NET Core-applikationer. Visa de renderade filerna med riktig formatering och layout i HTML5, PDF eller som en bild med några rader av koden." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Ladda ner gratis provversion"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Om GroupDocs.Viewer för .NET API" 
    content: |
        Börja visa 190+ populära dokumentformat i dina .NET-applikationer med hjälp av GroupDocs.Viewer för .NET API:er genom att lägga till några rader kod. Utvecklare kan enkelt visa PDF, ordbehandling, Excel-kalkylblad, presentation, Visio, Project, Outlook och många andra populära dokumentformat i HTML5-, bild- eller PDF-lägen. Dokumentåtergivningen är snabb, identisk med den ursprungliga källfilen, och den kräver inte installation av ytterligare programvara eller andra externa bibliotek.

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
              text: "API-referens"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Kodexempel"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Live Demos"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Prissättning"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "Steg för att rendera filen PLT i C#" 
    content_left: |
        Med [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/) kan du rendera PLT till HTML, JPEG, PNG eller PDF i några få steg.

        * Installera [GroupDocs.Viewer for .NET](https://www.nuget.org/packages/groupdocs.viewer) med din favoritpakethanterare. 
        * Skapa en instans av Viewer-klassen och ladda PLT-filen med fullständig sökväg. 
        * Ställ in alternativ för att rendera filen PLT till HTML-, PNG-, JPEG- eller PDF-format. 
        * Rendera filen och kontrollera utdata i den aktuella katalogen. 
        
    title_right: "Systemkrav" 
    content_right: |
        GroupDocs.Viewer för .NET API:er stöds på alla större plattformar och operativsystem. Innan du kör koden nedan, se till att du har följande förutsättningar installerade på ditt system.

        * Operativsystem: Microsoft Windows, Linux, MacOS 
        * Utvecklingsmiljöer: Microsoft Visual Studio, Visual Studio Code, .NET CLI 
        * Frameworks: .NET Framework, .NET Standard, .NET Core, .NET 
    code: |
        ```cs
                        
            // Set up input PLT file
            string filePath = "input.plt";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render PLT file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "Plt Viewer Live Demo"
    content: |
        Visa filen PLT just nu genom att besöka webbplatsen [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/plt).
    lang: "sv"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Andra filformat Rendering och visning med C#"
    exclude: "PLT"
    content: |
        Flerformats-API för dokument och bilder för .NET. Se några av de populära filformaten nedan utan några externa tittare.
    format: 
        # format loop 1
        - name: "Rendera DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word Open XML-dokument" 

        # format loop 2
        - name: "Gör CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "CorelDRAW-fil" 

        # format loop 3
        - name: "Gör PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint Open XML-presentation" 

        # format loop 4
        - name: "Rendera XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Öppna XML-kalkylblad" 

        # format loop 5
        - name: "Gör DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "AutoCAD-ritning"

        # format loop 6
        - name: "Rendera XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "XML-fil"

        # format loop 7
        - name: "Gör PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Adobe Photoshop-dokument"

        # format loop 8
        - name: "Rendera Adobe Illustrator-fil"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Konstverk från Adobe Illustrator"

        # format loop 9
        - name: "Gör DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Microsoft Word-dokument" 

        # format loop 10
        - name: "Återge TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Vanlig textfil" 

        # format loop 11
        - name: "Gör DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Rita Exchange Format-fil"  
          
        # format loop 12
        - name: "Gör VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "vCard-fil"  
              
        # format loop 13
        - name: "Rendera SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Skalbar vektorgrafik" 
          
        # format loop 14
        - name: "Återge HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "Gör PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Fil i bärbar dokumentformat"
          
        # format loop 16
        - name: "Återge JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "JPEG-bild"
          
        # format loop 17
        - name: "Återge PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Bärbar nätverksgrafik" 
          
        # format loop 18
        - name: "Gör EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "E-postmeddelande" 
          
        # format loop 19
        - name: "Gör RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "RTF-fil" 
          
        # format loop 20
        - name: "Rendera ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "OpenDocument-textdokument" 
          
        # format loop 21
        - name: "Återge CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Kommaseparerade värdefil" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
