---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: ro

############################# Head #############################
head_title: ".NET AI Viewer API - Citiți, vizualizați, randați în C# VB.NET"
head_description: ".NET document viewer API pentru a citi, reda și afișa AI în orice tip de aplicații C#, ASP.NET, VB.NET și .NET Core."

############################# Header ############################
title: "AI Vizualizator de fișiere pentru aplicații C# .NET" 
description: ".NET document viewer API pentru a citi, reda și afișa fișierul AI în orice tip de aplicații C#, ASP.NET, VB.NET și .NET Core. Vizualizați fișierele redate cu formatare și aspect adevărat în HTML5, PDF sau ca imagine folosind câteva rânduri de cod." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Descarcare varianta scurta de prezentare gratuita"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Despre GroupDocs.Viewer for .NET API" 
    content: |
        Începeți să vizualizați peste 190 de formate de documente populare în aplicațiile dvs. .NET folosind GroupDocs.Viewer pentru API-urile .NET adăugând câteva linii de cod. Dezvoltatorii pot afișa cu ușurință PDF, Procesare de text, Foaie de calcul Excel, Prezentare, Visio, Proiect, Outlook și multe alte formate de document populare în moduri HTML5, imagine sau PDF. Redarea documentului este rapidă, identică cu fișierul sursă original și nu necesită instalarea de software suplimentar sau alte biblioteci externe.

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
              text: "Referință API"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Exemple de coduri"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Demo live"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Prețuri"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "Pași pentru redarea fișierului AI în C#" 
    content_left: |
        Cu [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/) puteți randa AI în HTML, JPEG, PNG sau PDF în câțiva pași.

        * Instalați [GroupDocs.Viewer pentru .NET](https://www.nuget.org/packages/groupdocs.viewer) folosind managerul de pachete preferat. 
        * Creați o instanță a clasei Viewer și încărcați fișierul AI cu calea completă. 
        * Setați opțiunile de redare a fișierului AI în format HTML, PNG, JPEG sau PDF. 
        * Redați fișierul și verificați rezultatul în directorul curent. 
        
    title_right: "Cerințe de sistem" 
    content_right: |
        API-urile GroupDocs.Viewer pentru .NET sunt acceptate pe toate platformele și sistemele de operare majore. Înainte de a executa codul de mai jos, vă rugăm să vă asigurați că aveți următoarele cerințe preliminare instalate pe sistemul dumneavoastră.

        * Sisteme de operare: Microsoft Windows, Linux, MacOS 
        * Medii de dezvoltare: Microsoft Visual Studio, Visual Studio Code, .NET CLI 
        * Framework: .NET Framework, .NET Standard, .NET Core, .NET 
    code: |
        ```cs
                        
            // Set up input AI file
            string filePath = "input.ai";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render AI file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "AI Viewer Live Demo"
    content: |
        Vizualizați fișierul AI chiar acum, vizitând site-ul web [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/ai).
    lang: "ro"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Redarea și vizualizarea altor formate de fișiere folosind C#"
    exclude: "AI"
    content: |
        API de vizualizare a documentelor și imaginilor multiformat pentru .NET. Vizualizați câteva dintre formatele de fișiere populare de mai jos, fără niciun vizualizator extern.
    format: 
        # format loop 1
        - name: "Redați DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Document Microsoft Word Open XML" 

        # format loop 2
        - name: "Redați CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "Fișierul CorelDRAW" 

        # format loop 3
        - name: "Redați PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "Prezentare PowerPoint Open XML" 

        # format loop 4
        - name: "Redați XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet" 

        # format loop 5
        - name: "Redați DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "Desen AutoCAD"

        # format loop 6
        - name: "Redați XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "Fișier XML"

        # format loop 7
        - name: "Redați PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Document Adobe Photoshop"

        # format loop 8
        - name: "Redați fișierul Adobe Illustrator"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Opera de artă Adobe Illustrator"

        # format loop 9
        - name: "Redați DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Document Microsoft Word" 

        # format loop 10
        - name: "Redați TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Fișier text simplu" 

        # format loop 11
        - name: "Redați DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Fișier în format Schimb de desene"  
          
        # format loop 12
        - name: "Redați VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "Fișier vCard"  
              
        # format loop 13
        - name: "Redați SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Grafic vectorial scalabil" 
          
        # format loop 14
        - name: "Redați HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Fișier limbaj de marcare hipertext" 
          
        # format loop 15
        - name: "Redați PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Fișier în format de document portabil"
          
        # format loop 16
        - name: "Redați JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "Imagine JPEG"
          
        # format loop 17
        - name: "Redați PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Grafică de rețea portabilă" 
          
        # format loop 18
        - name: "Redați EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "Mesaj e-mail" 
          
        # format loop 19
        - name: "Redați RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Fișier cu format text îmbogățit" 
          
        # format loop 20
        - name: "Reda ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "Document text OpenDocument" 
          
        # format loop 21
        - name: "Redați CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Fișier cu valori separate prin virgulă" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
