---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: lt

############################# Head #############################
head_title: "„Java“ TXT peržiūros programos API – atvaizduokite ir rodykite TXT „Java Apps“."
head_description: "Peržiūrėkite TXT failus Java, J2EE, J2SE programose. Palaiko 170+ dokumentų ir vaizdo failų formatų peržiūrą HTML, PDF arba vaizdo režimu su pažangiomis funkcijomis, leidžiančiomis valdyti dokumentų peržiūros parinktis."

############################# Header ############################
title: "Pateikti ir peržiūrėti TXT Java" 
description: "Savoji ir didelio našumo TXT failų peržiūros programa, skirta Java, J2EE ir J2SE pagrįstoms programoms, palaikanti daugybę papildomų funkcijų, leidžiančių tinkinti išvesties dokumento formato išvaizdą." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Atsisiųskite nemokamą bandomąją versiją"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Apie GroupDocs.Viewer, skirtą Java API" 
    content: |
        Įgalinkite „Java“ programas rodyti daugiau nei 170 failų formatų HTML, PDF arba vaizdo režimais, naudodami „GroupDocs.Viewer“, skirtą „Java“ API, neįdiegę jokios papildomos programinės įrangos; pvz., „Microsoft Office“, „Apache Open Office“, „Adobe Acrobat Reader“ ir kt. Kūrėjai gali lengvai peržiūrėti visus populiarius vaizdus ir dokumentų tipus, įskaitant „Microsoft Office“, „OpenDocument“, HTML, PDF, archyvą, diagramas, „Photoshop“, „AutoCAD“ ir programavimo kalbos formatus „Java“ programose naudodami greitas ir aukščiausios kokybės atvaizdavimas.

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
              text: "API nuoroda"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Kodo pavyzdžiai"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Tiesioginės demonstracinės versijos"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Kainodara"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "Veiksmai, kaip pateikti TXT failą Java" 
    content_left: |
        Naudodami [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/) atlikdami kelis veiksmus galite pateikti TXT į HTML, JPEG, PNG arba PDF.

        * Pridėkite [GroupDocs.Viewer for Java](https://releases.groupdocs.com/viewer/java/) kaip projekto priklausomybę. 
        * Sukurkite Viewer klasės egzempliorių ir įkelkite failą TXT su visu keliu. 
        * Nustatykite parinktis, kaip pateikti TXT failą HTML, PNG, JPEG arba PDF formatu. 
        * Pateikite failą ir patikrinkite išvestį dabartiniame kataloge. 
        
    title_right: "Sistemos reikalavimai" 
    content_right: |
        „GroupDocs.Viewer“, skirta „Java“ API, palaikoma visose pagrindinėse platformose ir operacinėse sistemose. Prieš vykdydami toliau pateiktą kodą, įsitikinkite, kad jūsų sistemoje yra įdiegtos šios būtinos sąlygos.

        * Operacinės sistemos: Microsoft Windows, Linux, MacOS 
        * Kūrimo aplinkos: NetBeans, IntelliJ IDEA, Eclipse ir kt. 
        * Frameworks: J2SE 8.0 (1.8) arba naujesnė versija (pvz., Java 17) 
    code: |
        ```java
                        
            // Set up input TXT file
            String filePath = "input.txt";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render TXT file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "TXT žiūrovo tiesioginė demonstracija"
    content: |
        Peržiūrėkite TXT failą dabar apsilankę [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/txt) svetainėje.
    lang: "lt"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Kitų failų formatų atvaizdavimas ir peržiūra naudojant Java"
    exclude: "TXT"
    content: |
        Kelių formatų dokumentų ir vaizdų peržiūros API, skirta „Java“. Peržiūrėkite kai kuriuos toliau pateiktus populiarius failų formatus be jokių išorinių peržiūros priemonių.
    format: 
        # format loop 1
        - name: "Pateikite DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Open XML dokumentas" 

        # format loop 2
        - name: "Pateikite CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "CorelDRAW failas" 

        # format loop 3
        - name: "Pateikti PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "„PowerPoint“ atidarytas XML pristatymas" 

        # format loop 4
        - name: "Pateikti XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Atidarykite XML skaičiuoklę" 

        # format loop 5
        - name: "Pateikti DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "AutoCAD piešimas"

        # format loop 6
        - name: "Pateikite XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "XML failas"

        # format loop 7
        - name: "Pateikite PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Adobe Photoshop dokumentas"

        # format loop 8
        - name: "Pateikite „Adobe Illustrator“ failą"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Adobe Illustrator meno kūriniai"

        # format loop 9
        - name: "Pateikti DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Microsoft Word dokumentas" 

        # format loop 10
        - name: "Pateikti TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Paprasto teksto failas" 

        # format loop 11
        - name: "Atvaizduokite DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Brėžinio mainų formato failas"  
          
        # format loop 12
        - name: "Pateikti VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "vCard failas"  
              
        # format loop 13
        - name: "Pateikti SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Mastelio keitimo vektorinė grafika" 
          
        # format loop 14
        - name: "Pateikite HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Hiperteksto žymėjimo kalbos failas" 
          
        # format loop 15
        - name: "Pateikti PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Nešiojamojo dokumento formato failas"
          
        # format loop 16
        - name: "Pateikti JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "JPEG vaizdas"
          
        # format loop 17
        - name: "Pateikti PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Nešiojama tinklo grafika" 
          
        # format loop 18
        - name: "Pateikti EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "El. pašto žinutė" 
          
        # format loop 19
        - name: "Pateikti RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Raiškiojo teksto formato failas" 
          
        # format loop 20
        - name: "Pateikti ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "OpenDocument tekstinis dokumentas" 
          
        # format loop 21
        - name: "Pateikite CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Kableliais atskirtų reikšmių failas" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
