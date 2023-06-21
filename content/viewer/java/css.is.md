---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: is

############################# Head #############################
head_title: "Java CSS áhorfandaforritaskil - birta og birta CSS í Java forritum"
head_description: "Skoðaðu CSS skrár í Java, J2EE, J2SE forritum. Styður að skoða 170+ skjala- og myndaskráarsnið í HTML, PDF eða myndham með háþróaðri eiginleikum til að stjórna skjalaskoðunarvalkostum."

############################# Header ############################
title: "Gerðu og skoðaðu CSS í Java" 
description: "Innbyggt og afkastamikið CSS skráaskoðaraforritaskil fyrir Java, J2EE og J2SE byggð forrit, sem styður fjölbreytt úrval viðbótareiginleika til að sérsníða útlit útlagsskjalsniðsins." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Sækja ókeypis prufuáskrift"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Um GroupDocs.Viewer fyrir Java API" 
    content: |
        Gerðu Java forritunum þínum kleift að sýna yfir 170+ skráarsnið í HTML, PDF eða myndhami með því að nota GroupDocs.Viewer fyrir Java API án þess að nokkur viðbótarhugbúnaður sé settur upp; eins og Microsoft Office, Apache Open Office, Adobe Acrobat Reader o.fl. Hönnuðir geta auðveldlega skoðað allar vinsælar myndir og skjalagerðir þar á meðal Microsoft Office, OpenDocument, HTML, PDF, Archive, Diagrams, Photoshop, AutoCAD og forritunarmálssnið inni í Java forritunum með hröð og hágæða flutningur.

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
    title_left: "Skref til að gera CSS skrá í Java" 
    content_left: |
        Með [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/) geturðu gert CSS í HTML, JPEG, PNG eða PDF í nokkrum skrefum.

        * Bættu við [GroupDocs.Viewer fyrir Java](https://releases.groupdocs.com/viewer/java/) sem háð verkefninu þínu. 
        * Búðu til tilvik af Viewer class og hlaðið CSS skránni með fullri slóð. 
        * Stilltu valkosti til að gera CSS skrána á HTML, PNG, JPEG eða PDF sniði. 
        * Gerðu skrá og athugaðu úttak í núverandi möppu. 
        
    title_right: "kerfis kröfur" 
    content_right: |
        GroupDocs.Viewer fyrir Java API eru studd á öllum helstu kerfum og stýrikerfum. Áður en þú keyrir kóðann hér að neðan skaltu ganga úr skugga um að þú hafir eftirfarandi forsendur uppsettar á kerfinu þínu.

        * Stýrikerfi: Microsoft Windows, Linux, MacOS 
        * Þróunarumhverfi: NetBeans, IntelliJ IDEA, Eclipse o.fl. 
        * Rammar: J2SE 8.0 (1.8) eða nýrri (til dæmis Java 17) 
    code: |
        ```java
                        
            // Set up input CSS file
            String filePath = "input.css";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render CSS file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "CSS Sýning áhorfanda í beinni"
    content: |
        Skoðaðu CSS skrána núna með því að fara á vefsíðu [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/css).
    lang: "is"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Önnur skráarsnið flutningur og skoðun með Java"
    exclude: "CSS"
    content: |
        Multi-snið skjöl og myndir skoðara API fyrir Java. Skoðaðu nokkur af vinsælustu skráarsniðunum hér að neðan án utanaðkomandi áhorfenda.
    format: 
        # format loop 1
        - name: "Gerðu DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Opið XML skjal" 

        # format loop 2
        - name: "Gerðu CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "CorelDRAW skrá" 

        # format loop 3
        - name: "Gerðu PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint Open XML kynning" 

        # format loop 4
        - name: "Gerðu XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Opinn XML töflureikni" 

        # format loop 5
        - name: "Gerðu DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "AutoCAD teikning"

        # format loop 6
        - name: "Gerðu XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "XML skrá"

        # format loop 7
        - name: "Gerðu PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Adobe Photoshop skjal"

        # format loop 8
        - name: "Gerðu Adobe Illustrator skrá"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Adobe Illustrator listaverk"

        # format loop 9
        - name: "Skildu DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Microsoft Word skjal" 

        # format loop 10
        - name: "Gerðu TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Einföld textaskrá" 

        # format loop 11
        - name: "Gerðu DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Teikning Exchange Format File"  
          
        # format loop 12
        - name: "Gerðu VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "vCard skrá"  
              
        # format loop 13
        - name: "Gerðu SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Skalanleg vektorgrafík" 
          
        # format loop 14
        - name: "Gerðu HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "Gerðu PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Færanleg skjalasniðsskrá"
          
        # format loop 16
        - name: "Gerðu JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "JPEG mynd"
          
        # format loop 17
        - name: "Gerðu PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Færanleg netgrafík" 
          
        # format loop 18
        - name: "Gerðu EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "Tölvupóstskeyti" 
          
        # format loop 19
        - name: "Gerðu RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Ríkt textasnið skrá" 
          
        # format loop 20
        - name: "Gerðu ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "OpenDocument textaskjal" 
          
        # format loop 21
        - name: "Gerðu CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Komma-aðskilin gildisskrá" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
