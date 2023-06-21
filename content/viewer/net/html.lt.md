---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: lt

############################# Head #############################
head_title: ".NET HTML peržiūros programos API – skaitykite, žiūrėkite, atvaizduokite C# VB.NET"
head_description: ".NET dokumentų peržiūros programos API, skirta skaityti, pateikti ir rodyti HTML bet kokio tipo C#, ASP.NET, VB.NET ir .NET Core programose."

############################# Header ############################
title: "HTML failų peržiūros programa, skirta C# .NET programoms" 
description: ".NET dokumentų peržiūros programa, skirta skaityti, pateikti ir rodyti HTML failą bet kokio tipo C#, ASP.NET, VB.NET ir .NET Core programose. Peržiūrėkite pateiktus failus su tikru formatavimu ir išdėstymu HTML5, PDF formatu arba kaip vaizdą naudodami kelias kodo eilutes." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Atsisiųskite nemokamą bandomąją versiją"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Apie GroupDocs.Viewer, skirta .NET API" 
    content: |
        Pradėkite žiūrėti daugiau nei 190 populiarių dokumentų formatų savo .NET programose naudodami GroupDocs.Viewer, skirtą .NET API, pridėdami kelias kodo eilutes. Kūrėjai gali lengvai rodyti PDF, teksto apdorojimo, „Excel“ skaičiuoklės, pristatymo, „Visio“, „Project“, „Outlook“ ir daugelio kitų populiarių dokumentų formatų HTML5, vaizdo ar PDF režimais. Dokumento atvaizdavimas yra greitas, identiškas pirminiam šaltinio failui ir jam nereikia įdiegti papildomos programinės įrangos ar kitų išorinių bibliotekų.

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
    title_left: "Veiksmai, kaip pateikti HTML failą C#" 
    content_left: |
        Naudodami [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/) atlikdami kelis veiksmus galite pateikti HTML į HTML, JPEG, PNG arba PDF.

        * Įdiekite [GroupDocs.Viewer for .NET](https://www.nuget.org/packages/groupdocs.viewer) naudodami mėgstamą paketų tvarkyklę. 
        * Sukurkite Viewer klasės egzempliorių ir įkelkite failą HTML su visu keliu. 
        * Nustatykite parinktis, kaip pateikti HTML failą HTML, PNG, JPEG arba PDF formatu. 
        * Pateikite failą ir patikrinkite išvestį dabartiniame kataloge. 
        
    title_right: "Sistemos reikalavimai" 
    content_right: |
        „GroupDocs.Viewer“, skirta .NET API, palaikoma visose pagrindinėse platformose ir operacinėse sistemose. Prieš vykdydami toliau pateiktą kodą, įsitikinkite, kad jūsų sistemoje yra įdiegtos šios būtinos sąlygos.

        * Operacinės sistemos: Microsoft Windows, Linux, MacOS 
        * Kūrimo aplinkos: „Microsoft Visual Studio“, „Visual Studio Code“, .NET CLI 
        * Frameworks: .NET Framework, .NET Standard, .NET Core, .NET 
    code: |
        ```cs
                        
            // Set up input HTML file
            string filePath = "input.html";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render HTML file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "HTML žiūrovo tiesioginė demonstracija"
    content: |
        Peržiūrėkite HTML failą dabar apsilankę [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/html) svetainėje.
    lang: "lt"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Kitų failų formatų atvaizdavimas ir peržiūra naudojant C#"
    exclude: "HTML"
    content: |
        Kelių formatų dokumentų ir vaizdų peržiūros API, skirta .NET. Peržiūrėkite kai kuriuos toliau pateiktus populiarius failų formatus be jokių išorinių peržiūros priemonių.
    format: 
        # format loop 1
        - name: "Pateikite DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word Open XML dokumentas" 

        # format loop 2
        - name: "Pateikite CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "CorelDRAW failas" 

        # format loop 3
        - name: "Pateikti PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "„PowerPoint“ atidarytas XML pristatymas" 

        # format loop 4
        - name: "Pateikti XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Atidarykite XML skaičiuoklę" 

        # format loop 5
        - name: "Pateikti DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "AutoCAD piešimas"

        # format loop 6
        - name: "Pateikite XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "XML failas"

        # format loop 7
        - name: "Pateikite PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Adobe Photoshop dokumentas"

        # format loop 8
        - name: "Pateikite „Adobe Illustrator“ failą"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Adobe Illustrator meno kūriniai"

        # format loop 9
        - name: "Pateikti DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Microsoft Word dokumentas" 

        # format loop 10
        - name: "Pateikti TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Paprasto teksto failas" 

        # format loop 11
        - name: "Atvaizduokite DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Brėžinio mainų formato failas"  
          
        # format loop 12
        - name: "Pateikti VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "vCard failas"  
              
        # format loop 13
        - name: "Pateikti SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Mastelio keitimo vektorinė grafika" 
          
        # format loop 14
        - name: "Pateikite HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Hiperteksto žymėjimo kalbos failas" 
          
        # format loop 15
        - name: "Pateikti PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Nešiojamojo dokumento formato failas"
          
        # format loop 16
        - name: "Pateikti JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "JPEG vaizdas"
          
        # format loop 17
        - name: "Pateikti PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Nešiojama tinklo grafika" 
          
        # format loop 18
        - name: "Pateikti EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "El. pašto žinutė" 
          
        # format loop 19
        - name: "Pateikti RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Raiškiojo teksto formato failas" 
          
        # format loop 20
        - name: "Pateikti ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "OpenDocument tekstinis dokumentas" 
          
        # format loop 21
        - name: "Pateikite CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Kableliais atskirtų reikšmių failas" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
