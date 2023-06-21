---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: ga

############################# Head #############################
head_title: ".NET EPUB Viewer API - Léigh, Amharc, Rindreáil i C# VB.NET"
head_description: "API breathnóir doiciméad .NET chun EPUB a léamh, a sholáthar agus a thaispeáint in aon chineál feidhmchláir C#, ASP.NET, VB.NET & .NET Core."

############################# Header ############################
title: "Epub Amharcóir Comhad Le haghaidh Feidhmchláir C# .NET" 
description: ".NET document viewer API chun comhad EPUB a léamh, a sholáthar agus a thaispeáint in aon chineál feidhmchláir C#, ASP.NET, VB.NET & .NET Core. Féach ar na comhaid rindreáilte le fíorfhormáidiú & leagan amach in HTML5, PDF nó mar íomhá ag baint úsáide as cúpla líne den chód." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Íoslódáil Triail Saor in Aisce"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Maidir le GroupDocs.Viewer le haghaidh .NET API" 
    content: |
        Tosaigh ag breathnú ar 190+ formáid doiciméad coitianta i d’fheidhmchláir .NET ag úsáid GroupDocs.Viewer le haghaidh .NET APIs trí chúpla líne de chód a chur leis. Is féidir le forbróirí PDF, Próiseáil Focal, Scarbhileog Excel, Cur i Láthair, Visio, Tionscadal, Outlook agus go leor formáidí doiciméad eile a bhfuil tóir orthu a thaispeáint go héasca i modhanna HTML5, íomhá nó PDF. Tá rindreáil an doiciméid tapa, comhionann leis an mbunchomhad foinse, agus ní gá bogearraí breise ná aon leabharlanna seachtracha eile a shuiteáil.

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
              text: "Tagairt API"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Samplaí de Chóid"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Taispeántas beo"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Praghsáil"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "Céimeanna chun comhad EPUB a rindreáil in C#" 
    content_left: |
        Le [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/) is féidir leat EPUB a dhéanamh go HTML, JPEG, PNG nó PDF i gcúpla céim.

        * Suiteáil [GroupDocs.Viewer le haghaidh .NET](https://www.nuget.org/packages/groupdocs.viewer) ag baint úsáide as an mbainisteoir pacáiste is fearr leat. 
        * Cruthaigh sampla de rang Amharcóra agus lódáil an comhad EPUB le cosán iomlán. 
        * Socraigh roghanna chun comhad EPUB a chur i bhformáid HTML, PNG, JPEG nó PDF. 
        * Rindreáil comhad agus seiceáil an t-aschur san eolaire reatha. 
        
    title_right: "Riachtanais Chórais" 
    content_right: |
        Tacaítear le GroupDocs.Viewer do .NET API ar gach mór-ardán agus córas oibriúcháin. Sula ndéanann tú an cód thíos, déan cinnte go bhfuil na réamhriachtanais seo a leanas suiteáilte ar do chóras.

        * Córais Oibriúcháin: Microsoft Windows, Linux, MacOS 
        * Timpeallachtaí Forbartha: Microsoft Visual Studio, Visual Studio Code, .NET CLI 
        * Creataí: .NET Framework, .NET Standard, .NET Core, .NET 
    code: |
        ```cs
                        
            // Set up input EPUB file
            string filePath = "input.epub";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render EPUB file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "EPUB Taispeántas Amharcóra Beo"
    content: |
        Féach ar chomhad EPUB faoi láthair trí chuairt a thabhairt ar an suíomh Gréasáin [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/epub).
    lang: "ga"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Formáidí Comhaid Eile Rindreála & Breathnú ag úsáid C#"
    exclude: "EPUB"
    content: |
        Doiciméid il-formáid agus API breathnóir íomhánna le haghaidh. GLAN. Féach ar roinnt de na formáidí comhaid tóir thíos gan aon lucht féachana seachtracha.
    format: 
        # format loop 1
        - name: "Rindreáil DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word Oscail Doiciméad XML" 

        # format loop 2
        - name: "Rindreáil CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "Comhad CorelDRAW" 

        # format loop 3
        - name: "Rindreáil PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint Oscail XML Cur i láthair" 

        # format loop 4
        - name: "Rindreáil XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Oscail Scarbhileog XML" 

        # format loop 5
        - name: "Rindreáil DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "Líníocht AutoCAD"

        # format loop 6
        - name: "Rindreáil XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "Comhad XML"

        # format loop 7
        - name: "Rindreáil PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Adobe photoshop doiciméad"

        # format loop 8
        - name: "Rindreáil comhad Adobe Illustrator"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Adobe Illustrator saothar ealaíne"

        # format loop 9
        - name: "Rindreáil DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Doiciméad Microsoft Word" 

        # format loop 10
        - name: "Rindreáil txt" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Comhad Gnáth-théacs" 

        # format loop 11
        - name: "Rindreáil DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Comhad Formáid Malairte Líníochta"  
          
        # format loop 12
        - name: "Rindreáil VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "Comhad vCárta"  
              
        # format loop 13
        - name: "Rindreáil SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Grafaicí veicteoir Inscálaithe" 
          
        # format loop 14
        - name: "Rindreáil HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Comhad Teanga Marcáil Hipirtéacs" 
          
        # format loop 15
        - name: "Rindreáil pdf"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Comhad Formáid Doiciméad Iniompartha"
          
        # format loop 16
        - name: "Rindreáil JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "Íomhá JPEG"
          
        # format loop 17
        - name: "Rindreáil PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Grafaicí líonra soghluaiste" 
          
        # format loop 18
        - name: "Rindreáil EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "Teachtaireacht R-phoist" 
          
        # format loop 19
        - name: "Rindreáil RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Comhad Formáid Téacs Saibhir" 
          
        # format loop 20
        - name: "Rindreáil ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "Doiciméad Téacs OpenDocument" 
          
        # format loop 21
        - name: "Rindreáil CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Comhad Luachanna Deighilte Camóga" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
