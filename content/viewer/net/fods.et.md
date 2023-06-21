---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: et

############################# Head #############################
head_title: ".NET FODS Viewer API – lugemine, vaatamine, renderdamine C# VB.NET-is"
head_description: ".NET-i dokumendivaaturi API FODS lugemiseks, renderdamiseks ja kuvamiseks mis tahes tüüpi C#, ASP.NET, VB.NET ja .NET Core rakendustes."

############################# Header ############################
title: "FODS failivaatur C# .NET-i rakenduste jaoks" 
description: ".NET-i dokumendivaaturi API FODS-faili lugemiseks, renderdamiseks ja kuvamiseks mis tahes tüüpi C#, ASP.NET, VB.NET ja .NET Core rakendustes. Vaadake renderdatud faile tõese vormingu ja paigutusega HTML5-s, PDF-is või pildina, kasutades mõnda koodirida." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Laadige alla tasuta prooviversioon"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Teave .NET API jaoks mõeldud GroupDocs.Vieweri kohta" 
    content: |
        Alustage oma .NET-rakendustes üle 190 populaarse dokumendivormingu vaatamist, kasutades .NET API-de jaoks mõeldud GroupDocs.Viewerit, lisades paar koodirida. Arendajad saavad hõlpsalt kuvada PDF-i, tekstitöötluse, Exceli arvutustabeli, esitluse, visio, projekti, Outlooki ja paljusid teisi populaarseid dokumendivorminguid HTML5-, pildi- või PDF-režiimis. Dokumendi renderdamine on kiire, identne algse lähtefailiga ning see ei nõua täiendava tarkvara ega muude väliste teekide installimist.

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
    title_left: "Toimingud faili FODS renderdamiseks rakenduses C#" 
    content_left: |
        Rakendusega [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/) saate mõne sammuga renderdada faili FODS HTML-, JPEG-, PNG- või PDF-vormingusse.

        * Installige [GroupDocs.Viewer for .NET](https://www.nuget.org/packages/groupdocs.viewer), kasutades oma lemmikpaketihaldurit. 
        * Looge Vieweri klassi eksemplar ja laadige fail FODS kogu teega. 
        * Määrake suvandid faili FODS renderdamiseks HTML-, PNG-, JPEG- või PDF-vormingusse. 
        * Renderda fail ja kontrolli väljundit praeguses kataloogis. 
        
    title_right: "Nõuded süsteemile" 
    content_right: |
        GroupDocs.Viewer for .NET API on toetatud kõikidel suurematel platvormidel ja operatsioonisüsteemidel. Enne alloleva koodi käivitamist veenduge, et teie süsteemi on installitud järgmised eeltingimused.

        * Operatsioonisüsteemid: Microsoft Windows, Linux, MacOS 
        * Arenduskeskkonnad: Microsoft Visual Studio, Visual Studio Code, .NET CLI 
        * Frameworks: .NET Framework, .NET Standard, .NET Core, .NET 
    code: |
        ```cs
                        
            // Set up input FODS file
            string filePath = "input.fods";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render FODS file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "FODS vaataja reaalajas demo"
    content: |
        Vaadake kohe faili FODS, külastades veebisaiti [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/fods).
    lang: "et"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Muud failivormingud renderdamine ja vaatamine C# abil"
    exclude: "FODS"
    content: |
        Mitme vorminguga dokumentide ja piltide vaataja API .NET-i jaoks. Vaadake mõnda populaarset failivormingut allpool ilma väliste vaatajateta.
    format: 
        # format loop 1
        - name: "Renderda DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Wordi avatud XML-dokument" 

        # format loop 2
        - name: "Renderdage CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "CorelDRAW fail" 

        # format loop 3
        - name: "Renderda PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPointi avatud XML-esitlus" 

        # format loop 4
        - name: "Renderdage XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Avage XML-arvutustabel" 

        # format loop 5
        - name: "Renderda DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "AutoCADi joonistamine"

        # format loop 6
        - name: "Renderda XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "XML-fail"

        # format loop 7
        - name: "Renderdage PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Adobe Photoshopi dokument"

        # format loop 8
        - name: "Renderdage Adobe Illustratori fail"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Adobe Illustratori kunstiteos"

        # format loop 9
        - name: "Renderda DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Microsoft Wordi dokument" 

        # format loop 10
        - name: "Renderda TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Lihtteksti fail" 

        # format loop 11
        - name: "Renderda DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Joonise vahetusvormingu fail"  
          
        # format loop 12
        - name: "Renderda VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "vCardi fail"  
              
        # format loop 13
        - name: "Renderda SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Skaleeritav vektorgraafika" 
          
        # format loop 14
        - name: "Renderda HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Hüperteksti märgistuskeele fail" 
          
        # format loop 15
        - name: "Renderda PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Kaasaskantava dokumendivormingu fail"
          
        # format loop 16
        - name: "Renderda JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "JPEG pilt"
          
        # format loop 17
        - name: "Renderda PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Kaasaskantav võrgugraafika" 
          
        # format loop 18
        - name: "Renderda EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "E-posti sõnum" 
          
        # format loop 19
        - name: "Renderda RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Rikasteksti vormingu fail" 
          
        # format loop 20
        - name: "Renderda ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "OpenDocumenti tekstdokument" 
          
        # format loop 21
        - name: "Renderda CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Komaga eraldatud väärtuste fail" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
