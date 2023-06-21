---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: ca

############################# Head #############################
head_title: ".NET PY Viewer API: lectura, visualització, representació en C# VB.NET"
head_description: "API de visualització de documents .NET per llegir, representar i mostrar PY en qualsevol tipus d'aplicacions C#, ASP.NET, VB.NET i .NET Core."

############################# Header ############################
title: "PY Visor de fitxers per a aplicacions C# .NET" 
description: "API de visualització de documents .NET per llegir, representar i mostrar fitxers PY en qualsevol tipus d'aplicacions C#, ASP.NET, VB.NET i .NET Core. Visualitzeu els fitxers renderitzats amb format i disseny reals en HTML5, PDF o com a imatge utilitzant unes poques línies del codi." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Baixeu la prova gratuïta"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Quant a l'API de GroupDocs.Viewer per a .NET" 
    content: |
        Comenceu a veure més de 190 formats de documents populars a les vostres aplicacions .NET mitjançant GroupDocs.Viewer per a les API .NET afegint unes quantes línies de codi. Els desenvolupadors poden mostrar fàcilment PDF, Processament de textos, Full de càlcul Excel, Presentació, Visio, Projecte, Outlook i molts altres formats de document populars en els modes HTML5, imatge o PDF. La representació del document és ràpida, idèntica al fitxer font original i no requereix instal·lar programari addicional ni cap altra biblioteca externa.

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
              text: "Referència de l'API"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Exemples de codi"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Demostracions en directe"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Preus"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "Passos per renderitzar el fitxer PY a C#" 
    content_left: |
        Amb [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/) podeu renderitzar PY a HTML, JPEG, PNG o PDF en uns quants passos.

        * Instal·leu [GroupDocs.Viewer per a .NET](https://www.nuget.org/packages/groupdocs.viewer) mitjançant el vostre gestor de paquets preferit. 
        * Creeu una instància de la classe Viewer i carregueu el fitxer PY amb el camí complet. 
        * Estableix les opcions per renderitzar el fitxer PY en format HTML, PNG, JPEG o PDF. 
        * Renderitzar el fitxer i comprovar la sortida al directori actual. 
        
    title_right: "Requisits del sistema" 
    content_right: |
        Les API de GroupDocs.Viewer per a .NET són compatibles amb totes les plataformes i sistemes operatius principals. Abans d'executar el codi següent, assegureu-vos que teniu els següents requisits previs instal·lats al vostre sistema.

        * Sistemes operatius: Microsoft Windows, Linux, MacOS 
        * Entorns de desenvolupament: Microsoft Visual Studio, Visual Studio Code, .NET CLI 
        * Frameworks: .NET Framework, .NET Standard, .NET Core, .NET 
    code: |
        ```cs
                        
            // Set up input PY file
            string filePath = "input.py";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render PY file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "PY Visualitzador de demostració en directe"
    content: |
        Consulteu el fitxer PY ara mateix visitant el lloc web [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/py).
    lang: "ca"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Renderització i visualització d'altres formats de fitxer amb C#"
    exclude: "PY"
    content: |
        API de visualització de documents i imatges multiformat per a .NET. Vegeu alguns dels formats de fitxer populars a continuació sense cap visor extern.
    format: 
        # format loop 1
        - name: "Renderitza DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Document XML obert de Microsoft Word" 

        # format loop 2
        - name: "Renderitza CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "Fitxer CorelDRAW" 

        # format loop 3
        - name: "Renderitza PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "Presentació de PowerPoint Open XML" 

        # format loop 4
        - name: "Renderitza XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Full de càlcul XML obert de Microsoft Excel" 

        # format loop 5
        - name: "Renderitza DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "Dibuix d'AutoCAD"

        # format loop 6
        - name: "Renderitza XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "Fitxer XML"

        # format loop 7
        - name: "Renderitza PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Document d'Adobe Photoshop"

        # format loop 8
        - name: "Renderitza el fitxer Adobe Illustrator"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Il·lustració d'Adobe Illustrator"

        # format loop 9
        - name: "Renderitza DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Document de Microsoft Word" 

        # format loop 10
        - name: "Renderitza TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Fitxer de text senzill" 

        # format loop 11
        - name: "Renderitza DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Fitxer de format d'intercanvi de dibuixos"  
          
        # format loop 12
        - name: "Renderitza VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "Fitxer vCard"  
              
        # format loop 13
        - name: "Renderitza SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Gràfic vectorial escalable" 
          
        # format loop 14
        - name: "Renderitza HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Fitxer de llenguatge de marques d'hipertext" 
          
        # format loop 15
        - name: "Renderitza PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Fitxer de format de document portàtil"
          
        # format loop 16
        - name: "Renderitza JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "Imatge JPEG"
          
        # format loop 17
        - name: "Renderitza PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Gràfic de xarxa portàtil" 
          
        # format loop 18
        - name: "Renderitza EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "Missatge de correu electrònic" 
          
        # format loop 19
        - name: "Renderitza RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Fitxer de format de text enriquit" 
          
        # format loop 20
        - name: "Renderitza ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "Document de text OpenDocument" 
          
        # format loop 21
        - name: "Renderitza CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Fitxer de valors separats per comes" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
