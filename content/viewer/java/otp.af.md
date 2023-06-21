---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: af

############################# Head #############################
head_title: "Java OTP Viewer API - Gee en vertoon OTP in Java Apps"
head_description: "Bekyk OTP-lêers in Java-, J2EE-, J2SE-toepassings. Ondersteun die besigtiging van 170+ dokument- en beeldlêerformate in HTML-, PDF- of beeldmodus met gevorderde kenmerke om dokumentbesigtigingsopsies te bestuur."

############################# Header ############################
title: "Gee en bekyk OTP in Java" 
description: "Inheemse en hoë werkverrigting OTP lêerkyker-API vir Java-, J2EE- en J2SE-gebaseerde toepassings, wat 'n wye reeks bykomende kenmerke ondersteun om die voorkoms van die uitvoerdokumentformaat aan te pas." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Laai gratis proeflopie af"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Oor GroupDocs.Viewer vir Java API" 
    content: |
        Aktiveer jou Java-toepassings om meer as 170+ lêerformate in HTML-, PDF- of beeldmodusse te vertoon deur GroupDocs.Viewer vir Java API's te gebruik sonder enige bykomende sagteware geïnstalleer; soos Microsoft Office, Apache Open Office, Adobe Acrobat Reader, ens. Ontwikkelaars kan maklik alle gewilde beelde en dokumenttipes bekyk, insluitend Microsoft Office, OpenDocument, HTML, PDF, Argief, Diagramme, Photoshop, AutoCAD en programmeertaalformate binne die Java-toepassings met vinnige en hoogste kwaliteit lewering.

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
              text: "API-verwysing"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Kode voorbeelde"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Regstreekse demonstrasies"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Pryse"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "Stappe om OTP-lêer in Java weer te gee" 
    content_left: |
        Met [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/) kan jy OTP in 'n paar stappe na HTML, JPEG, PNG of PDF weergee.

        * Voeg [GroupDocs.Viewer vir Java](https://releases.groupdocs.com/viewer/java/) by as 'n afhanklikheid van jou projek. 
        * Skep 'n instansie van Viewer-klas en laai die OTP-lêer met volle pad. 
        * Stel opsies om OTP-lêer in HTML-, PNG-, JPEG- of PDF-formaat weer te gee. 
        * Lewer lêer en kontroleer uitvoer in die huidige gids. 
        
    title_right: "Stelselvereistes" 
    content_right: |
        GroupDocs.Viewer vir Java API's word op alle groot platforms en bedryfstelsels ondersteun. Voordat u die kode hieronder uitvoer, maak asseblief seker dat u die volgende voorvereistes op u stelsel geïnstalleer het.

        * Bedryfstelsels: Microsoft Windows, Linux, MacOS 
        * Ontwikkelingsomgewings: NetBeans, IntelliJ IDEA, Eclipse ens. 
        * Raamwerke: J2SE 8.0 (1.8) of hoër (byvoorbeeld Java 17) 
    code: |
        ```java
                        
            // Set up input OTP file
            String filePath = "input.otp";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render OTP file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "OTP Kyker Regstreekse Demo"
    content: |
        Bekyk OTP-lêer op die oomblik deur [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/otp) se webwerf te besoek.
    lang: "af"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Ander lêerformate wat weergegee en bekyk word deur Java"
    exclude: "OTP"
    content: |
        Multi-formaat dokumente en beelde kyker API vir Java. Bekyk sommige van die gewilde lêerformate hieronder sonder enige eksterne kykers.
    format: 
        # format loop 1
        - name: "Lewer DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Oop XML-dokument" 

        # format loop 2
        - name: "Lewer CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "CorelDRAW-lêer" 

        # format loop 3
        - name: "Lewer PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint Oop XML-aanbieding" 

        # format loop 4
        - name: "Gee XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Oop XML Sigblad" 

        # format loop 5
        - name: "Lewer DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "AutoCAD-tekening"

        # format loop 6
        - name: "Gee XML weer"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "XML-lêer"

        # format loop 7
        - name: "Lewer PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Adobe Photoshop-dokument"

        # format loop 8
        - name: "Gee Adobe Illustrator-lêer weer"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Adobe Illustrator kunswerk"

        # format loop 9
        - name: "Lewer DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Microsoft Word-dokument" 

        # format loop 10
        - name: "Lewer TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Gewone tekslêer" 

        # format loop 11
        - name: "Lewer DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Teken Exchange Format Lêer"  
          
        # format loop 12
        - name: "Lewer VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "vCard-lêer"  
              
        # format loop 13
        - name: "Gee SVG weer"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Skaalbare vektorgrafika" 
          
        # format loop 14
        - name: "Gee HTML weer"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "Lewer PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Draagbare dokumentformaat lêer"
          
        # format loop 16
        - name: "Gee JPEG weer"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "JPEG-beeld"
          
        # format loop 17
        - name: "Lewer PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Draagbare netwerkgrafika" 
          
        # format loop 18
        - name: "Lewer EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "E-pos Boodskap" 
          
        # format loop 19
        - name: "Lewer RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Rich Text Format Lêer" 
          
        # format loop 20
        - name: "Lewer ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "OpenDocument teksdokument" 
          
        # format loop 21
        - name: "Gee CSV weer"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Komma-geskeide waardelêer" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
