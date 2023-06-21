---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: fi

############################# Head #############################
head_title: "Java RST Viewer API - Renderöi ja näytä RST Java-sovelluksissa"
head_description: "Tarkastele RST-tiedostoja Java-, J2EE- ja J2SE-sovelluksissa. Tukee yli 170 asiakirja- ja kuvatiedostomuodon katselua HTML-, PDF- tai kuvatilassa edistyneillä ominaisuuksilla asiakirjojen katseluvaihtoehtojen hallitsemiseksi."

############################# Header ############################
title: "Renderöi ja näytä RST Javassa" 
description: "Alkuperäinen ja korkean suorituskyvyn RST-tiedostojen katselusovellusliittymä Java-, J2EE- ja J2SE-pohjaisille sovelluksille, joka tukee laajaa valikoimaa lisäominaisuuksia tulostetun asiakirjamuodon ulkoasun mukauttamiseen." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Lataa ilmainen kokeiluversio"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Tietoja GroupDocs.Viewer for Java API:sta" 
    content: |
        Salli Java-sovellusten näyttää yli 170 tiedostomuotoa HTML-, PDF- tai kuvatiloissa käyttämällä GroupDocs.Viewer for Java API -sovellusliittymiä ilman lisäohjelmistoja. kuten Microsoft Office, Apache Open Office, Adobe Acrobat Reader jne. Kehittäjät voivat helposti tarkastella kaikkia suosittuja kuvia ja asiakirjatyyppejä, mukaan lukien Microsoft Office, OpenDocument, HTML, PDF, arkisto, kaaviot, Photoshop, AutoCAD ja ohjelmointikieliformaatit Java-sovellusten sisällä. nopea ja laadukas renderöinti.

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
    title_left: "Vaiheet tiedoston RST renderöimiseksi Java" 
    content_left: |
        [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/) avulla voit hahmontaa RST HTML-, JPEG-, PNG- tai PDF-muotoon muutamassa vaiheessa.

        * Lisää [GroupDocs.Viewer for Java](https://releases.groupdocs.com/viewer/java/) projektisi riippuvuudeksi. 
        * Luo Viewer-luokan ilmentymä ja lataa RST tiedosto koko polulla. 
        * Aseta asetukset renderöidäksesi RST-tiedosto HTML-, PNG-, JPEG- tai PDF-muotoon. 
        * Renderöi tiedosto ja tarkista tuloste nykyisessä hakemistossa. 
        
    title_right: "Laitteistovaatimukset" 
    content_right: |
        GroupDocs.Viewer for Java API:t ovat tuettuja kaikilla tärkeimmillä alustoilla ja käyttöjärjestelmillä. Ennen kuin suoritat alla olevan koodin, varmista, että olet asentanut järjestelmääsi seuraavat edellytykset.

        * Käyttöjärjestelmät: Microsoft Windows, Linux, MacOS 
        * Kehitysympäristöt: NetBeans, IntelliJ IDEA, Eclipse jne. 
        * Kehykset: J2SE 8.0 (1.8) tai uudempi (esimerkiksi Java 17) 
    code: |
        ```java
                        
            // Set up input RST file
            String filePath = "input.rst";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render RST file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "RST Viewerin live-demo"
    content: |
        Tarkastele tiedostoa RST heti käymällä [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/rst) -sivustolla.
    lang: "fi"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Muiden tiedostomuotojen renderöinti ja katselu käyttämällä Java"
    exclude: "RST"
    content: |
        Monimuotoisten asiakirjojen ja kuvien katselusovellusliittymä Javalle. Katso joitain suosittuja tiedostomuotoja alla ilman ulkoisia katseluohjelmia.
    format: 
        # format loop 1
        - name: "Renderöi DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Avaa XML-asiakirja" 

        # format loop 2
        - name: "Renderöi CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "CorelDRAW tiedosto" 

        # format loop 3
        - name: "Renderöi PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint Open XML-esitys" 

        # format loop 4
        - name: "Renderöi XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Open XML-laskentataulukko" 

        # format loop 5
        - name: "Renderöi DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "AutoCAD-piirustus"

        # format loop 6
        - name: "Renderöi XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "XML-tiedosto"

        # format loop 7
        - name: "Renderöi PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Adobe Photoshop asiakirja"

        # format loop 8
        - name: "Piirrä Adobe Illustrator -tiedosto"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Adobe Illustrator -kuvio"

        # format loop 9
        - name: "Renderöi DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Microsoft Word -asiakirja" 

        # format loop 10
        - name: "Renderöi TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Pelkkä tekstitiedosto" 

        # format loop 11
        - name: "Renderöi DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Piirustus Exchange-muotoinen tiedosto"  
          
        # format loop 12
        - name: "Renderöi VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "vCard-tiedosto"  
              
        # format loop 13
        - name: "Renderöi SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Skaalautuva vektorigrafiikka" 
          
        # format loop 14
        - name: "Renderöi HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "Renderöi PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Portable Document Format -tiedosto"
          
        # format loop 16
        - name: "Renderöi JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "JPEG-kuva"
          
        # format loop 17
        - name: "Renderöi PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Kannettava verkkografiikka" 
          
        # format loop 18
        - name: "Renderöi EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "Sähköpostiviesti" 
          
        # format loop 19
        - name: "Renderöi RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Rich Text -muotoinen tiedosto" 
          
        # format loop 20
        - name: "Renderöi ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "OpenDocument-tekstiasiakirja" 
          
        # format loop 21
        - name: "Renderöi CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Pilkuilla eroteltujen arvojen tiedosto" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
