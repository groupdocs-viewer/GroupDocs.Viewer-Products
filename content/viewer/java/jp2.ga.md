---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: ga

############################# Head #############################
head_title: "Java JP2 Viewer API - Rindreáil & Taispeáin JP2 in Java Apps"
head_description: "Féach ar JP2 comhad i bhfeidhmchláir Java, J2EE, J2SE. Tacaíonn sé le breathnú ar 170+ formáid doiciméad agus comhaid íomhá i mód HTML, PDF nó íomhá le hardghnéithe chun roghanna féachana doiciméad a bhainistiú."

############################# Header ############################
title: "Rindreáil & Féach ar JP2 I Java" 
description: "API breathnóir comhad JP2 dúchasach agus ardfheidhmíochta le haghaidh feidhmchláir bunaithe ar Java, J2EE agus J2SE, ag tacú le raon leathan gnéithe breise chun cuma na formáide doiciméid aschuir a shaincheapadh." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Íoslódáil Triail Saor in Aisce"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Maidir le GroupDocs.Viewer le haghaidh Java API" 
    content: |
        Cumasaigh d’fheidhmchláir Java breis is 170+ formáid comhaid a thaispeáint i modhanna HTML, PDF nó íomhá ag baint úsáide as GroupDocs.Viewer do Java APIs gan aon bhogearraí breise a bheith suiteáilte; mar Microsoft Office, Apache Open Office, Adobe Acrobat Reader srl. Is féidir le forbróirí féachaint go héasca ar gach íomhá móréilimh agus cineál doiciméad lena n-áirítear Microsoft Office, OpenDocument, HTML, PDF, Cartlann, Léaráidí, Photoshop, AutoCAD agus formáidí teanga ríomhchlárúcháin taobh istigh de na feidhmchláir Java le rindreáil tapa agus den chaighdeán is airde.

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
    title_left: "Céimeanna chun comhad JP2 a rindreáil in Java" 
    content_left: |
        Le [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/) is féidir leat JP2 a dhéanamh go HTML, JPEG, PNG nó PDF i gceann cúpla céim.

        * Cuir [GroupDocs.Viewer le haghaidh Java](https://releases.groupdocs.com/viewer/java/) mar spleáchas le do thionscadal. 
        * Cruthaigh sampla de rang Amharcóra agus lódáil an comhad JP2 le cosán iomlán. 
        * Socraigh roghanna chun comhad JP2 a chur i bhformáid HTML, PNG, JPEG nó PDF. 
        * Rindreáil comhad agus seiceáil an t-aschur san eolaire reatha. 
        
    title_right: "Riachtanais Chórais" 
    content_right: |
        Tugtar tacaíocht do GroupDocs.Viewer do Java API ar gach mór-ardán agus córas oibriúcháin. Sula ndéanann tú an cód thíos, déan cinnte go bhfuil na réamhriachtanais seo a leanas suiteáilte ar do chóras.

        * Córais Oibriúcháin: Microsoft Windows, Linux, MacOS 
        * Timpeallachtaí Forbartha: NetBeans, IntelliJ IDEA, Eclipse etc. 
        * Creataí: J2SE 8.0 (1.8) nó níos airde (mar shampla Java 17) 
    code: |
        ```java
                        
            // Set up input JP2 file
            String filePath = "input.jp2";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render JP2 file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "JP2 Taispeántas Amharcóra Beo"
    content: |
        Féach ar chomhad JP2 faoi láthair trí chuairt a thabhairt ar an suíomh Gréasáin [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/jp2).
    lang: "ga"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Formáidí Comhaid Eile Rindreála & Breathnú ag úsáid Java"
    exclude: "JP2"
    content: |
        Doiciméid il-format agus API breathnóir íomhánna do Java. Féach ar roinnt de na formáidí comhaid tóir thíos gan aon lucht féachana seachtracha.
    format: 
        # format loop 1
        - name: "Rindreáil DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Oscail Doiciméad XML" 

        # format loop 2
        - name: "Rindreáil CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "Comhad CorelDRAW" 

        # format loop 3
        - name: "Rindreáil PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint Oscail XML Cur i láthair" 

        # format loop 4
        - name: "Rindreáil XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Oscail Scarbhileog XML" 

        # format loop 5
        - name: "Rindreáil DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "Líníocht AutoCAD"

        # format loop 6
        - name: "Rindreáil XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "Comhad XML"

        # format loop 7
        - name: "Rindreáil PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Adobe photoshop doiciméad"

        # format loop 8
        - name: "Rindreáil comhad Adobe Illustrator"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Adobe Illustrator saothar ealaíne"

        # format loop 9
        - name: "Rindreáil DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Doiciméad Microsoft Word" 

        # format loop 10
        - name: "Rindreáil txt" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Comhad Gnáth-théacs" 

        # format loop 11
        - name: "Rindreáil DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Comhad Formáid Malairte Líníochta"  
          
        # format loop 12
        - name: "Rindreáil VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "Comhad vCárta"  
              
        # format loop 13
        - name: "Rindreáil SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Grafaicí veicteoir Inscálaithe" 
          
        # format loop 14
        - name: "Rindreáil HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Comhad Teanga Marcáil Hipirtéacs" 
          
        # format loop 15
        - name: "Rindreáil pdf"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Comhad Formáid Doiciméad Iniompartha"
          
        # format loop 16
        - name: "Rindreáil JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "Íomhá JPEG"
          
        # format loop 17
        - name: "Rindreáil PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Grafaicí líonra soghluaiste" 
          
        # format loop 18
        - name: "Rindreáil EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "Teachtaireacht R-phoist" 
          
        # format loop 19
        - name: "Rindreáil RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Comhad Formáid Téacs Saibhir" 
          
        # format loop 20
        - name: "Rindreáil ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "Doiciméad Téacs OpenDocument" 
          
        # format loop 21
        - name: "Rindreáil CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Comhad Luachanna Deighilte Camóga" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
