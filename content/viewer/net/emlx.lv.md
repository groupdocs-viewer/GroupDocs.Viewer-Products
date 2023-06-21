---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: lv

############################# Head #############################
head_title: ".NET EMLX Viewer API — lasīšana, skatīšana, renderēšana C# VB.NET"
head_description: ".NET dokumentu skatītāja API, lai lasītu, renderētu un parādītu EMLX jebkura veida C#, ASP.NET, VB.NET un .NET Core lietojumprogrammās."

############################# Header ############################
title: "EMLX failu skatītājs C# .NET lietojumprogrammām" 
description: ".NET dokumentu skatītāja API, lai lasītu, renderētu un parādītu EMLX failu jebkura veida C#, ASP.NET, VB.NET un .NET Core lietojumprogrammās. Skatiet renderētos failus ar patiesu formatējumu un izkārtojumu HTML5, PDF formātā vai kā attēlu, izmantojot dažas koda rindiņas." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Lejupielādēt bezmaksas izmēģinājuma versiju"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Par GroupDocs.Viewer .NET API" 
    content: |
        Sāciet skatīt 190+ populārus dokumentu formātus savās .NET lietojumprogrammās, izmantojot GroupDocs.Viewer .NET API, pievienojot dažas koda rindiņas. Izstrādātāji var viegli attēlot PDF, tekstapstrādes, Excel izklājlapas, prezentācijas, Visio, Project, Outlook un daudzus citus populārus dokumentu formātus HTML5, attēla vai PDF režīmos. Dokumentu renderēšana ir ātra, identiska oriģinālajam avota failam, un tai nav nepieciešama papildu programmatūras vai citu ārēju bibliotēku instalēšana.

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
              text: "API atsauce"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Kodu piemēri"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Tiešraides demonstrācijas"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Cenu noteikšana"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "Darbības, lai renderētu EMLX failu programmā C#" 
    content_left: |
        Izmantojot programmu [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/), varat atveidot EMLX HTML, JPEG, PNG vai PDF formātā, veicot dažas darbības.

        * Instalējiet [GroupDocs.Viewer for .NET](https://www.nuget.org/packages/groupdocs.viewer), izmantojot savu iecienītāko pakotņu pārvaldnieku. 
        * Izveidojiet Viewer klases gadījumu un ielādējiet failu EMLX ar pilnu ceļu. 
        * Iestatiet opcijas EMLX faila renderēšanai HTML, PNG, JPEG vai PDF formātā. 
        * Renderējiet failu un pārbaudiet izvadi pašreizējā direktorijā. 
        
    title_right: "Sistēmas prasības" 
    content_right: |
        GroupDocs.Viewer for .NET API tiek atbalstīts visās lielākajās platformās un operētājsistēmās. Pirms tālāk norādītā koda izpildes, lūdzu, pārliecinieties, vai jūsu sistēmā ir instalēti šādi priekšnosacījumi.

        * Operētājsistēmas: Microsoft Windows, Linux, MacOS 
        * Izstrādes vides: Microsoft Visual Studio, Visual Studio kods, .NET CLI 
        * Frameworks: .NET Framework, .NET Standard, .NET Core, .NET 
    code: |
        ```cs
                        
            // Set up input EMLX file
            string filePath = "input.emlx";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render EMLX file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "EMLX skatītāja tiešraides demonstrācija"
    content: |
        Skatiet failu EMLX tūlīt, apmeklējot vietni [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/emlx).
    lang: "lv"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Citu failu formātu renderēšana un skatīšana, izmantojot C#"
    exclude: "EMLX"
    content: |
        Vairāku formātu dokumentu un attēlu skatītāja API .NET. Tālāk skatiet dažus populāros failu formātus bez ārējiem skatītājiem.
    format: 
        # format loop 1
        - name: "Renderēt DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word atvērts XML dokuments" 

        # format loop 2
        - name: "Renderēt CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "CorelDRAW fails" 

        # format loop 3
        - name: "Renderēt PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint atvērtā XML prezentācija" 

        # format loop 4
        - name: "Renderēt XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Atvērt XML izklājlapu" 

        # format loop 5
        - name: "Renderēt DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "AutoCAD zīmējums"

        # format loop 6
        - name: "Renderēt XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "XML fails"

        # format loop 7
        - name: "Renderējiet PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Adobe Photoshop dokuments"

        # format loop 8
        - name: "Renderējiet Adobe Illustrator failu"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Adobe Illustrator mākslas darbs"

        # format loop 9
        - name: "Renderēt DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Microsoft Word dokuments" 

        # format loop 10
        - name: "Renderēt TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Vienkārša teksta fails" 

        # format loop 11
        - name: "Renderēt DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Zīmējumu apmaiņas formāta fails"  
          
        # format loop 12
        - name: "Renderēt VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "vCard fails"  
              
        # format loop 13
        - name: "Renderēt SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Mērogojama vektorgrafika" 
          
        # format loop 14
        - name: "Renderējiet HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Hiperteksta iezīmēšanas valodas fails" 
          
        # format loop 15
        - name: "Renderēt PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Portatīvā dokumenta formāta fails"
          
        # format loop 16
        - name: "Renderēt JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "JPEG attēls"
          
        # format loop 17
        - name: "Renderēt PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Pārnēsājama tīkla grafika" 
          
        # format loop 18
        - name: "Renderēt EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "E-pasta ziņa" 
          
        # format loop 19
        - name: "Renderēt RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Bagātināta teksta formāta fails" 
          
        # format loop 20
        - name: "Renderēt ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "OpenDocument teksta dokuments" 
          
        # format loop 21
        - name: "Renderēt CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Komatatdalīto vērtību fails" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
