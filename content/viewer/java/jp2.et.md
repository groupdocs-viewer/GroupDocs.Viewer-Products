---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: et

############################# Head #############################
head_title: "Java JP2 vaataja API – renderda ja kuva JP2 Java rakendustes"
head_description: "Vaadake JP2 faile Java, J2EE, J2SE rakendustes. Toetab 170+ dokumendi- ja pildifailivormingu vaatamist HTML-, PDF- või pildirežiimis koos täiustatud funktsioonidega dokumentide vaatamise valikute haldamiseks."

############################# Header ############################
title: "Renderda ja kuva JP2 Javas" 
description: "Native ja suure jõudlusega JP2 failivaaturi API Java-, J2EE- ja J2SE-põhiste rakenduste jaoks, mis toetab laia valikut lisafunktsioone väljunddokumendi vormingu välimuse kohandamiseks." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Laadige alla tasuta prooviversioon"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Teave GroupDocs.Vieweri kohta Java API jaoks" 
    content: |
        Lubage oma Java rakendustel kuvada rohkem kui 170 failivormingut HTML-, PDF- või pildirežiimis, kasutades Java API-de jaoks mõeldud GroupDocs.Viewerit ilma täiendava tarkvara installimata; nagu Microsoft Office, Apache Open Office, Adobe Acrobat Reader jne. Arendajad saavad hõlpsasti vaadata Java rakendustes kõiki populaarseid pilte ja dokumenditüüpe, sealhulgas Microsoft Office, OpenDocument, HTML, PDF, arhiiv, diagrammid, Photoshop, AutoCAD ja programmeerimiskeele vormingud. kiire ja kõrge kvaliteediga renderdamine.

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
              text: "API viide"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Koodi näited"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Reaalajas demod"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Hinnakujundus"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "Toimingud faili JP2 renderdamiseks rakenduses Java" 
    content_left: |
        Rakendusega [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/) saate mõne sammuga renderdada faili JP2 HTML-, JPEG-, PNG- või PDF-vormingusse.

        * Lisage [GroupDocs.Viewer for Java](https://releases.groupdocs.com/viewer/java/) oma projekti sõltuvusena. 
        * Looge Vieweri klassi eksemplar ja laadige fail JP2 kogu teega. 
        * Määrake suvandid faili JP2 renderdamiseks HTML-, PNG-, JPEG- või PDF-vormingusse. 
        * Renderda fail ja kontrolli väljundit praeguses kataloogis. 
        
    title_right: "Nõuded süsteemile" 
    content_right: |
        Java API-de GroupDocs.Viewer toetatakse kõigil suurematel platvormidel ja operatsioonisüsteemidel. Enne alloleva koodi käivitamist veenduge, et teie süsteemi on installitud järgmised eeltingimused.

        * Operatsioonisüsteemid: Microsoft Windows, Linux, MacOS 
        * Arenduskeskkonnad: NetBeans, IntelliJ IDEA, Eclipse jne. 
        * Raamistikud: J2SE 8.0 (1.8) või uuem (nt Java 17) 
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
    title: "JP2 vaataja reaalajas demo"
    content: |
        Vaadake kohe faili JP2, külastades veebisaiti [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/jp2).
    lang: "et"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Muud failivormingud renderdamine ja vaatamine Java abil"
    exclude: "JP2"
    content: |
        Mitme vorminguga dokumentide ja piltide vaataja API Java jaoks. Vaadake mõnda populaarset failivormingut allpool ilma väliste vaatajateta.
    format: 
        # format loop 1
        - name: "Renderda DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Wordi avatud XML-dokument" 

        # format loop 2
        - name: "Renderdage CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "CorelDRAW fail" 

        # format loop 3
        - name: "Renderda PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPointi avatud XML-esitlus" 

        # format loop 4
        - name: "Renderdage XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Avage XML-arvutustabel" 

        # format loop 5
        - name: "Renderda DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "AutoCADi joonistamine"

        # format loop 6
        - name: "Renderda XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "XML-fail"

        # format loop 7
        - name: "Renderdage PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Adobe Photoshopi dokument"

        # format loop 8
        - name: "Renderdage Adobe Illustratori fail"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Adobe Illustratori kunstiteos"

        # format loop 9
        - name: "Renderda DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Microsoft Wordi dokument" 

        # format loop 10
        - name: "Renderda TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Lihtteksti fail" 

        # format loop 11
        - name: "Renderda DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Joonise vahetusvormingu fail"  
          
        # format loop 12
        - name: "Renderda VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "vCardi fail"  
              
        # format loop 13
        - name: "Renderda SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Skaleeritav vektorgraafika" 
          
        # format loop 14
        - name: "Renderda HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Hüperteksti märgistuskeele fail" 
          
        # format loop 15
        - name: "Renderda PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Kaasaskantava dokumendivormingu fail"
          
        # format loop 16
        - name: "Renderda JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "JPEG pilt"
          
        # format loop 17
        - name: "Renderda PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Kaasaskantav võrgugraafika" 
          
        # format loop 18
        - name: "Renderda EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "E-posti sõnum" 
          
        # format loop 19
        - name: "Renderda RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Rikasteksti vormingu fail" 
          
        # format loop 20
        - name: "Renderda ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "OpenDocumenti tekstdokument" 
          
        # format loop 21
        - name: "Renderda CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Komaga eraldatud väärtuste fail" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
