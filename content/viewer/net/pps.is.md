---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: is

############################# Head #############################
head_title: ".NET PPS áhorfandaforritaskil - lesa, skoða, skila í C# VB.NET"
head_description: ".NET skjalaskoðara API til að lesa, birta og birta PPS í hvers kyns C#, ASP.NET, VB.NET og .NET Core forritum."

############################# Header ############################
title: "PPS Skráaskoðari fyrir C# .NET forrit" 
description: ".NET skjalaskoðara API til að lesa, birta og birta PPS skrá í hvers kyns C#, ASP.NET, VB.NET og .NET Core forritum. Skoðaðu gerðir skrár með sannri sniði og uppsetningu í HTML5, PDF eða sem mynd með því að nota nokkrar línur af kóðanum." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Sækja ókeypis prufuáskrift"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Um GroupDocs.Viewer fyrir .NET API" 
    content: |
        Byrjaðu að skoða 190+ vinsæl skjalasnið í .NET forritunum þínum með því að nota GroupDocs.Viewer fyrir .NET API með því að bæta við nokkrum línum af kóða. Hönnuðir geta auðveldlega sýnt PDF, ritvinnslu, Excel töflureikni, kynningu, Visio, Project, Outlook og mörg önnur vinsæl skjalasnið í HTML5, mynd eða PDF ham. Skjalavinnslan er hröð, eins og upprunalega frumskráin og það þarf ekki að setja upp viðbótarhugbúnað eða önnur utanaðkomandi bókasöfn.

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
              text: "API tilvísun"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Dæmi um kóða"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Sýningar í beinni"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Verðlag"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "Skref til að gera PPS skrá í C#" 
    content_left: |
        Með [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/) geturðu gert PPS í HTML, JPEG, PNG eða PDF í nokkrum skrefum.

        * Settu upp [GroupDocs.Viewer fyrir .NET](https://www.nuget.org/packages/groupdocs.viewer) með uppáhalds pakkastjóranum þínum. 
        * Búðu til tilvik af Viewer class og hlaðið PPS skránni með fullri slóð. 
        * Stilltu valkosti til að gera PPS skrána á HTML, PNG, JPEG eða PDF sniði. 
        * Gerðu skrá og athugaðu úttak í núverandi möppu. 
        
    title_right: "kerfis kröfur" 
    content_right: |
        GroupDocs.Viewer fyrir .NET API eru studd á öllum helstu kerfum og stýrikerfum. Áður en þú keyrir kóðann hér að neðan skaltu ganga úr skugga um að þú hafir eftirfarandi forsendur uppsettar á kerfinu þínu.

        * Stýrikerfi: Microsoft Windows, Linux, MacOS 
        * Þróunarumhverfi: Microsoft Visual Studio, Visual Studio Code, .NET CLI 
        * Frameworks: .NET Framework, .NET Standard, .NET Core, .NET 
    code: |
        ```cs
                        
            // Set up input PPS file
            string filePath = "input.pps";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render PPS file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "PPS Sýning áhorfanda í beinni"
    content: |
        Skoðaðu PPS skrána núna með því að fara á vefsíðu [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/pps).
    lang: "is"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Önnur skráarsnið endurgerð og skoðun með C#"
    exclude: "PPS"
    content: |
        Forritaskil fyrir skjöl og myndir á mörgum sniðum fyrir .NET. Skoðaðu nokkur af vinsælustu skráarsniðunum hér að neðan án utanaðkomandi áhorfenda.
    format: 
        # format loop 1
        - name: "Gerðu DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word Opið XML skjal" 

        # format loop 2
        - name: "Gerðu CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "CorelDRAW skrá" 

        # format loop 3
        - name: "Gerðu PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint Open XML kynning" 

        # format loop 4
        - name: "Gerðu XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Opinn XML töflureikni" 

        # format loop 5
        - name: "Gerðu DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "AutoCAD teikning"

        # format loop 6
        - name: "Gerðu XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "XML skrá"

        # format loop 7
        - name: "Gerðu PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Adobe Photoshop skjal"

        # format loop 8
        - name: "Gerðu Adobe Illustrator skrá"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Adobe Illustrator listaverk"

        # format loop 9
        - name: "Skildu DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Microsoft Word skjal" 

        # format loop 10
        - name: "Gerðu TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Einföld textaskrá" 

        # format loop 11
        - name: "Gerðu DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Teikning Exchange Format File"  
          
        # format loop 12
        - name: "Gerðu VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "vCard skrá"  
              
        # format loop 13
        - name: "Gerðu SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Skalanleg vektorgrafík" 
          
        # format loop 14
        - name: "Gerðu HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "Gerðu PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Færanleg skjalasniðsskrá"
          
        # format loop 16
        - name: "Gerðu JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "JPEG mynd"
          
        # format loop 17
        - name: "Gerðu PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Færanleg netgrafík" 
          
        # format loop 18
        - name: "Gerðu EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "Tölvupóstskeyti" 
          
        # format loop 19
        - name: "Gerðu RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Ríkt textasnið skrá" 
          
        # format loop 20
        - name: "Gerðu ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "OpenDocument textaskjal" 
          
        # format loop 21
        - name: "Gerðu CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Komma-aðskilin gildisskrá" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
