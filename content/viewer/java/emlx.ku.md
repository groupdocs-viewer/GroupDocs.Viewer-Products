---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: ku

############################# Head #############################
head_title: "Java EMLX API-ya Nêrîner - Di Sepanên Javayê de EMLX bike û nîşan bide"
head_description: "Pelên EMLX di sepanên Java, J2EE, J2SE de bibînin. Bi taybetmendiyên pêşkeftî ve ji bo birêvebirina vebijarkên dîtina belgeyan piştgirî dide dîtina 170+ formatên pelge û pelê wêneyê di HTML, PDF an moda wêneyê de."

############################# Header ############################
title: "EMLX Di Java de pêşkêş bike û bibîne" 
description: "API-a temaşekera pelan a xwemalî û performansa bilind EMLX ji bo sepanên bingehîn ên Java, J2EE û J2SE, piştgirî dide cûrbecûr taybetmendiyên zêde ji bo xweşkirina xuyangê forma belgeya derketinê." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Daxistina Doza Belaş"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Der barê GroupDocs.Viewer ji bo Java API" 
    content: |
        Serlêdanên Java-ya xwe çalak bikin ku bêtirî 170 formatên pelan di modên HTML, PDF an wêneyê de bi karanîna GroupDocs.Viewer ji bo API-yên Java-yê bêyî ku nermalava zêde hatî saz kirin nîşan bidin; wek Microsoft Office, Apache Open Office, Adobe Acrobat Reader hwd. Pêşdebir dikarin bi hêsanî hemî wêne û celebên belgeyên populer ên wekî Microsoft Office, OpenDocument, HTML, PDF, Archive, Diagrams, Photoshop, AutoCAD û formatên zimanê bernamesaziyê di hundurê sepanên Java de bibînin. rendering bi lez û herî bilind.

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
    title_left: "Pêngavên ku pela EMLX di Java de pêşkêş bikin" 
    content_left: |
        Bi [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/) hûn dikarin di çend gavan de EMLX li HTML, JPEG, PNG an PDF bidin.

        * [GroupDocs.Viewer ji bo Java](https://releases.groupdocs.com/viewer/java/) wekî girêdayî projeya xwe zêde bikin. 
        * Nimûneyek ji çîna Viewer biafirîne û pelê EMLX bi riya tevahî bar bike. 
        * Vebijêrk destnîşan bikin ku pelê EMLX di formata HTML, PNG, JPEG an PDF de were pêşkêş kirin. 
        * Di pelrêça heyî de pelê dakêşin û encam kontrol bikin. 
        
    title_right: "Pêdiviyên Sîstemê" 
    content_right: |
        GroupDocs.Viewer ji bo API-yên Java li ser hemî platformên sereke û pergalên xebitandinê têne piştgirî kirin. Berî ku hûn koda jêrîn bicîh bikin, ji kerema xwe pê ewle bibin ku we şertên jêrîn li ser pergala we hatine saz kirin.

        * Pergalên Xebatê: Microsoft Windows, Linux, MacOS 
        * Jîngehên Pêşkeftinê: NetBeans, IntelliJ IDEA, Eclipse hwd. 
        * Çarçove: J2SE 8.0 (1.8) an jor (mînak Java 17) 
    code: |
        ```java
                        
            // Set up input EMLX file
            String filePath = "input.emlx";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render EMLX file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "EMLX Dîmoya Zindî ya Temaşeker"
    content: |
        Bi serdana malpera [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/emlx) niha pelê EMLX bibînin.
    lang: "ku"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Formên Pelê yên Din Bi karanîna Java Renderkirin û Dîtin"
    exclude: "EMLX"
    content: |
        Belgeyên pir-format û API-a temaşekera wêneyan ji bo Java. Hin formatên pelê yên populer ên li jêr bêyî temaşevanên derveyî bibînin.
    format: 
        # format loop 1
        - name: "DOCX bike"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Belgeya XML vekir" 

        # format loop 2
        - name: "CDR bikin" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "Pelê CorelDRAW" 

        # format loop 3
        - name: "PPTX bikin"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint Pêşkêşiya XML vekin" 

        # format loop 4
        - name: "XLSX bikin"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Vekirina XML Spreadsheet" 

        # format loop 5
        - name: "DWG pêşkêş bikin"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "Drawing AutoCAD"

        # format loop 6
        - name: "XML pêşkêş bikin"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "Pelê XML"

        # format loop 7
        - name: "Render PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Belgeya Adobe Photoshop"

        # format loop 8
        - name: "Pelê Adobe Illustrator pêşkêş bikin"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Karê Hunerî ya Adobe Illustrator"

        # format loop 9
        - name: "DOC pêşkêş bikin"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Belgeya Microsoft Word" 

        # format loop 10
        - name: "TXT bikin" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Pelê Nivîsar a Sade" 

        # format loop 11
        - name: "DXF pêşkêş bikin" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Drawing Exchange Format Pele"  
          
        # format loop 12
        - name: "VCF pêşkêş bikin"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "Pelê vCard"  
              
        # format loop 13
        - name: "Render SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Grafika Vektora Scalable" 
          
        # format loop 14
        - name: "HTML-ê pêşkêş bikin"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Pelê Zimanê Nîşankirina Hypertext" 
          
        # format loop 15
        - name: "PDF-ê pêşkêş bikin"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Pelê Forma Belgeya Portable"
          
        # format loop 16
        - name: "JPEG pêşkêş bikin"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "Wêne JPEG"
          
        # format loop 17
        - name: "PNG pêşkêş bikin"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Grafika Tora Portable" 
          
        # format loop 18
        - name: "EML pêşkêş bikin"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "Peyama E-Mail" 
          
        # format loop 19
        - name: "Render RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Pelê Forma Nivîsa dewlemend" 
          
        # format loop 20
        - name: "Render ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "Belgeya Nivîsê ya OpenDocument" 
          
        # format loop 21
        - name: "CSV pêşkêş bikin"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Pelê Nirxên Veqetandî yên Bi Comma" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
