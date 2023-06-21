---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: fi

############################# Head #############################
head_title: ".NET AS Viewer API - lue, katsele, renderöi C# VB.NETissä"
head_description: ".NET-dokumenttien katselusovellusliittymä AS lukemiseen, hahmontamiseen ja näyttämiseen kaikissa C#-, ASP.NET-, VB.NET- ja .NET Core -sovelluksissa."

############################# Header ############################
title: "AS Tiedostojen katseluohjelma C# .NET -sovelluksille" 
description: ".NET-dokumenttien katselusovellusliittymä AS-tiedoston lukemiseen, hahmontamiseen ja näyttämiseen kaikissa C#-, ASP.NET-, VB.NET- ja .NET Core -sovelluksissa. Tarkastele hahmonnettuja tiedostoja oikealla muotoilulla ja asettelulla HTML5- tai PDF-muodossa tai kuvana muutamalla koodirivillä." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Lataa ilmainen kokeiluversio"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Tietoja GroupDocs.Viewer for .NET API:lle" 
    content: |
        Aloita yli 190 suositun asiakirjamuodon katseleminen .NET-sovelluksissasi GroupDocs.Viewer for .NET API -sovellusliittymien avulla lisäämällä muutama koodirivi. Kehittäjät voivat helposti näyttää PDF-, tekstinkäsittely-, Excel-laskentataulukon, esityksen, Vision, Projectin, Outlookin ja monia muita suosittuja asiakirjamuotoja HTML5-, kuva- tai PDF-tilassa. Asiakirjan renderöinti on nopeaa, identtinen alkuperäisen lähdetiedoston kanssa, eikä se vaadi lisäohjelmistojen tai muiden ulkoisten kirjastojen asentamista.

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
              text: "API-viite"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Esimerkkejä koodista"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Live-demoja"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Hinnoittelu"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "Vaiheet tiedoston AS renderöimiseksi ohjelmassa C#" 
    content_left: |
        [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/) avulla voit hahmontaa AS HTML-, JPEG-, PNG- tai PDF-muotoon muutamassa vaiheessa.

        * Asenna [GroupDocs.Viewer for .NET](https://www.nuget.org/packages/groupdocs.viewer) käyttämällä suosikkipakettienhallintaasi. 
        * Luo Viewer-luokan ilmentymä ja lataa AS tiedosto koko polulla. 
        * Aseta asetukset renderöidäksesi AS-tiedosto HTML-, PNG-, JPEG- tai PDF-muotoon. 
        * Renderöi tiedosto ja tarkista tuloste nykyisessä hakemistossa. 
        
    title_right: "Laitteistovaatimukset" 
    content_right: |
        GroupDocs.Viewer for .NET API on tuettu kaikilla tärkeimmillä alustoilla ja käyttöjärjestelmillä. Ennen kuin suoritat alla olevan koodin, varmista, että olet asentanut järjestelmääsi seuraavat edellytykset.

        * Käyttöjärjestelmät: Microsoft Windows, Linux, MacOS 
        * Kehitysympäristöt: Microsoft Visual Studio, Visual Studio Code, .NET CLI 
        * Frameworks: .NET Framework, .NET Standard, .NET Core, .NET 
    code: |
        ```cs
                        
            // Set up input AS file
            string filePath = "input.as";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render AS file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "AS Viewerin live-demo"
    content: |
        Tarkastele tiedostoa AS heti käymällä [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/as) -sivustolla.
    lang: "fi"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Muiden tiedostomuotojen renderöinti ja katselu käyttämällä C#"
    exclude: "AS"
    content: |
        Monimuotoisten asiakirjojen ja kuvien katselusovellusliittymä .NET:lle. Katso joitain suosittuja tiedostomuotoja alla ilman ulkoisia katseluohjelmia.
    format: 
        # format loop 1
        - name: "Renderöi DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word Avaa XML-asiakirja" 

        # format loop 2
        - name: "Renderöi CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "CorelDRAW tiedosto" 

        # format loop 3
        - name: "Renderöi PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint Open XML-esitys" 

        # format loop 4
        - name: "Renderöi XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Open XML-laskentataulukko" 

        # format loop 5
        - name: "Renderöi DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "AutoCAD-piirustus"

        # format loop 6
        - name: "Renderöi XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "XML-tiedosto"

        # format loop 7
        - name: "Renderöi PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Adobe Photoshop asiakirja"

        # format loop 8
        - name: "Piirrä Adobe Illustrator -tiedosto"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Adobe Illustrator -kuvio"

        # format loop 9
        - name: "Renderöi DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Microsoft Word -asiakirja" 

        # format loop 10
        - name: "Renderöi TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Pelkkä tekstitiedosto" 

        # format loop 11
        - name: "Renderöi DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Piirustus Exchange-muotoinen tiedosto"  
          
        # format loop 12
        - name: "Renderöi VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "vCard-tiedosto"  
              
        # format loop 13
        - name: "Renderöi SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Skaalautuva vektorigrafiikka" 
          
        # format loop 14
        - name: "Renderöi HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "Renderöi PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Portable Document Format -tiedosto"
          
        # format loop 16
        - name: "Renderöi JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "JPEG-kuva"
          
        # format loop 17
        - name: "Renderöi PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Kannettava verkkografiikka" 
          
        # format loop 18
        - name: "Renderöi EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "Sähköpostiviesti" 
          
        # format loop 19
        - name: "Renderöi RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Rich Text -muotoinen tiedosto" 
          
        # format loop 20
        - name: "Renderöi ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "OpenDocument-tekstiasiakirja" 
          
        # format loop 21
        - name: "Renderöi CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Pilkuilla eroteltujen arvojen tiedosto" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
