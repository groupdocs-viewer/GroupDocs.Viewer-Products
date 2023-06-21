---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: ku

############################# Head #############################
head_title: ".NET eMail API-ya Nêrîner - Di C# VB.NET de Bixwîne, Binêre, Render bike"
head_description: ".NET API-ya temaşevana belgeyê ku di her cûre sepanên C#, ASP.NET, VB.NET & .NET Core de bixwîne, bide û nîşan bide eMail."

############################# Header ############################
title: "eMail Dîmendera Pelê Ji Bo Serlêdanên C# .NET" 
description: ".NET API-a temaşekerê belgeyê ku pelê eMail di her cure sepanên C#, ASP.NET, VB.NET û .NET Core de bixwîne, bide û nîşan bide. Pelên çêkirî yên bi formatkirin û sêwirana rastîn di HTML5, PDF an jî wekî wêneyek bi karanîna çend rêzikên kodê bibînin." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Daxistina Doza Belaş"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Der barê GroupDocs.Viewer ji bo .NET API" 
    content: |
        Bi zêdekirina çend rêzikên kodê dest bi dîtina 190+ formatên belgeyên populer ên di sepanên xwe yên .NET de bi karanîna GroupDocs.Viewer ji bo API-yên .NET bikin. Pêşdebir dikarin bi hêsanî PDF, Pêvajoya Peyv, Excel Spreadsheet, Pêşkêşkirin, Visio, Project, Outlook û gelek formatên belgeyên populer ên di modên HTML5, wêne an PDF de nîşan bidin. Pêşkêşkirina belgeyê bilez e, bi pelê çavkaniya orîjînal re wekhev e, û ew ne hewce ye ku nermalava zêde an pirtûkxaneyên derveyî yên din saz bike.

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
              text: "Çavkanî API"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Nimûneyên Kodê"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Demos Bijî"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Pricing"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "Gavên Renderkirina pelê eMail di C# de" 
    content_left: |
        Bi [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/) hûn dikarin di çend gavan de eMail li HTML, JPEG, PNG an PDF-ê bidin.

        * [GroupDocs.Viewer ji bo .NET](https://www.nuget.org/packages/groupdocs.viewer) bi kargêrê pakêta xweya bijare saz bikin. 
        * Nimûneyek ji çîna Viewer biafirîne û pelê eMail bi riya tevahî bar bike. 
        * Vebijêrk destnîşan bikin ku pelê eMail di formata HTML, PNG, JPEG an PDF de were pêşkêş kirin. 
        * Di pelrêça heyî de pelê dakêşin û encam kontrol bikin. 
        
    title_right: "Pêdiviyên Sîstemê" 
    content_right: |
        GroupDocs.Viewer ji bo API-ên .NET li ser hemî platformên sereke û pergalên xebitandinê têne piştgirî kirin. Berî ku hûn koda jêrîn bicîh bikin, ji kerema xwe pê ewle bibin ku we şertên jêrîn li ser pergala we hatine saz kirin.

        * Pergalên Xebatê: Microsoft Windows, Linux, MacOS 
        * Jîngehên Pêşveçûnê: Microsoft Visual Studio, Visual Studio Code, .NET CLI 
        * Çarçove: .NET Framework, .NET Standard, .NET Core, .NET 
    code: |
        ```cs
                        
            // Set up input eMail file
            string filePath = "input.msg";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render eMail file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "eMail Dîmoya Zindî ya Temaşeker"
    content: |
        Bi serdana malpera [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/email) niha pelê eMail bibînin.
    lang: "ku"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Formên Pelê yên Din Render û Dîtin bi karanîna C#"
    exclude: "eMail"
    content: |
        Belgeyên pir-format û API-ya temaşekera wêneyan ji bo .NET. Hin formatên pelê yên populer ên li jêr bêyî temaşevanên derveyî bibînin.
    format: 
        # format loop 1
        - name: "DOCX bike"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word Belgeya XML vekir" 

        # format loop 2
        - name: "CDR bikin" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "Pelê CorelDRAW" 

        # format loop 3
        - name: "PPTX bikin"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint Pêşkêşiya XML vekin" 

        # format loop 4
        - name: "XLSX bikin"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Vekirina XML Spreadsheet" 

        # format loop 5
        - name: "DWG pêşkêş bikin"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "Drawing AutoCAD"

        # format loop 6
        - name: "XML pêşkêş bikin"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "Pelê XML"

        # format loop 7
        - name: "Render PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Belgeya Adobe Photoshop"

        # format loop 8
        - name: "Pelê Adobe Illustrator pêşkêş bikin"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Karê Hunerî ya Adobe Illustrator"

        # format loop 9
        - name: "DOC pêşkêş bikin"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Belgeya Microsoft Word" 

        # format loop 10
        - name: "TXT bikin" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Pelê Nivîsar a Sade" 

        # format loop 11
        - name: "DXF pêşkêş bikin" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Drawing Exchange Format Pele"  
          
        # format loop 12
        - name: "VCF pêşkêş bikin"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "Pelê vCard"  
              
        # format loop 13
        - name: "Render SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Grafika Vektora Scalable" 
          
        # format loop 14
        - name: "HTML-ê pêşkêş bikin"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Pelê Zimanê Nîşankirina Hypertext" 
          
        # format loop 15
        - name: "PDF-ê pêşkêş bikin"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Pelê Forma Belgeya Portable"
          
        # format loop 16
        - name: "JPEG pêşkêş bikin"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "Wêne JPEG"
          
        # format loop 17
        - name: "PNG pêşkêş bikin"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Grafika Tora Portable" 
          
        # format loop 18
        - name: "EML pêşkêş bikin"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "Peyama E-Mail" 
          
        # format loop 19
        - name: "Render RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Pelê Forma Nivîsa dewlemend" 
          
        # format loop 20
        - name: "Render ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "Belgeya Nivîsê ya OpenDocument" 
          
        # format loop 21
        - name: "CSV pêşkêş bikin"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Pelê Nirxên Veqetandî yên Bi Comma" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
