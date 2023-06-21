---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: lv

############################# Head #############################
head_title: "Java ERB skatītāja API — atveidot un attēlot ERB Java lietotnēs"
head_description: "Skatiet ERB failus Java, J2EE, J2SE lietojumprogrammās. Atbalsta vairāk nekā 170 dokumentu un attēlu failu formātu skatīšanu HTML, PDF vai attēla režīmā ar papildu funkcijām, lai pārvaldītu dokumentu skatīšanas opcijas."

############################# Header ############################
title: "Renderēt un skatīt ERB Java" 
description: "Vietējā un augstas veiktspējas ERB failu skatītāja API Java, J2EE un J2SE lietojumprogrammām, kas atbalsta plašu papildu funkciju klāstu, lai pielāgotu izvades dokumenta formāta izskatu." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Lejupielādēt bezmaksas izmēģinājuma versiju"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Par GroupDocs.Viewer for Java API" 
    content: |
        Iespējojiet savas Java lietojumprogrammas, lai parādītu vairāk nekā 170 failu formātus HTML, PDF vai attēlu režīmos, izmantojot GroupDocs.Viewer Java API, neinstalējot papildu programmatūru; piemēram, Microsoft Office, Apache Open Office, Adobe Acrobat Reader utt. Izstrādātāji var viegli skatīt visus populāros attēlus un dokumentu veidus, tostarp Microsoft Office, OpenDocument, HTML, PDF, arhīvu, diagrammas, Photoshop, AutoCAD un programmēšanas valodu formātus Java lietojumprogrammās, izmantojot ātra un augstākās kvalitātes renderēšana.

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
    title_left: "Darbības, lai renderētu ERB failu programmā Java" 
    content_left: |
        Izmantojot programmu [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/), varat atveidot ERB HTML, JPEG, PNG vai PDF formātā, veicot dažas darbības.

        * Pievienojiet [GroupDocs.Viewer for Java](https://releases.groupdocs.com/viewer/java/) kā sava projekta atkarību. 
        * Izveidojiet Viewer klases gadījumu un ielādējiet failu ERB ar pilnu ceļu. 
        * Iestatiet opcijas ERB faila renderēšanai HTML, PNG, JPEG vai PDF formātā. 
        * Renderējiet failu un pārbaudiet izvadi pašreizējā direktorijā. 
        
    title_right: "Sistēmas prasības" 
    content_right: |
        GroupDocs.Viewer for Java API tiek atbalstītas visās lielākajās platformās un operētājsistēmās. Pirms tālāk norādītā koda izpildes, lūdzu, pārliecinieties, vai jūsu sistēmā ir instalēti šādi priekšnosacījumi.

        * Operētājsistēmas: Microsoft Windows, Linux, MacOS 
        * Izstrādes vides: NetBeans, IntelliJ IDEA, Eclipse utt. 
        * Ietvars: J2SE 8.0 (1.8) vai jaunāka versija (piemēram, Java 17) 
    code: |
        ```java
                        
            // Set up input ERB file
            String filePath = "input.erb";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render ERB file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "ERB skatītāja tiešraides demonstrācija"
    content: |
        Skatiet failu ERB tūlīt, apmeklējot vietni [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/erb).
    lang: "lv"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Citu failu formātu renderēšana un skatīšana, izmantojot Java"
    exclude: "ERB"
    content: |
        Vairāku formātu dokumentu un attēlu skatītāja API Java. Tālāk skatiet dažus populāros failu formātus bez ārējiem skatītājiem.
    format: 
        # format loop 1
        - name: "Renderēt DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word atvērts XML dokuments" 

        # format loop 2
        - name: "Renderēt CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "CorelDRAW fails" 

        # format loop 3
        - name: "Renderēt PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint atvērtā XML prezentācija" 

        # format loop 4
        - name: "Renderēt XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Atvērt XML izklājlapu" 

        # format loop 5
        - name: "Renderēt DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "AutoCAD zīmējums"

        # format loop 6
        - name: "Renderēt XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "XML fails"

        # format loop 7
        - name: "Renderējiet PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Adobe Photoshop dokuments"

        # format loop 8
        - name: "Renderējiet Adobe Illustrator failu"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Adobe Illustrator mākslas darbs"

        # format loop 9
        - name: "Renderēt DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Microsoft Word dokuments" 

        # format loop 10
        - name: "Renderēt TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Vienkārša teksta fails" 

        # format loop 11
        - name: "Renderēt DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Zīmējumu apmaiņas formāta fails"  
          
        # format loop 12
        - name: "Renderēt VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "vCard fails"  
              
        # format loop 13
        - name: "Renderēt SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Mērogojama vektorgrafika" 
          
        # format loop 14
        - name: "Renderējiet HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Hiperteksta iezīmēšanas valodas fails" 
          
        # format loop 15
        - name: "Renderēt PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Portatīvā dokumenta formāta fails"
          
        # format loop 16
        - name: "Renderēt JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "JPEG attēls"
          
        # format loop 17
        - name: "Renderēt PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Pārnēsājama tīkla grafika" 
          
        # format loop 18
        - name: "Renderēt EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "E-pasta ziņa" 
          
        # format loop 19
        - name: "Renderēt RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Bagātināta teksta formāta fails" 
          
        # format loop 20
        - name: "Renderēt ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "OpenDocument teksta dokuments" 
          
        # format loop 21
        - name: "Renderēt CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Komatatdalīto vērtību fails" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
