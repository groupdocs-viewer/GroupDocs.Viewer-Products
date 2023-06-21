---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: hu

############################# Head #############################
head_title: "Java SVG Viewer API – SVG renderelés és megjelenítése Java alkalmazásokban"
head_description: "Tekintse meg a SVG fájlokat Java, J2EE, J2SE alkalmazásokban. Támogatja a 170+ dokumentum- és képfájlformátum megtekintését HTML, PDF vagy kép módban, fejlett funkciókkal a dokumentummegtekintési beállítások kezeléséhez."

############################# Header ############################
title: "Render & View SVG Java nyelven" 
description: "Natív és nagy teljesítményű SVG fájlnézegető API Java, J2EE és J2SE alapú alkalmazásokhoz, amely számos további funkciót támogat a kimeneti dokumentumformátum megjelenésének testreszabásához." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Ingyenes próbaverzió letöltése"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "A GroupDocs.Viewer for Java API-ról" 
    content: |
        Engedélyezze Java-alkalmazásainak több mint 170 fájlformátum megjelenítését HTML, PDF vagy kép módban a GroupDocs.Viewer for Java API-k segítségével további szoftver telepítése nélkül; például a Microsoft Office, az Apache Open Office, az Adobe Acrobat Reader stb. gyors és legjobb minőségű renderelés.

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
              text: "API-referencia"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Kódpéldák"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Élő demók"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Árazás"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "A SVG fájl renderelésének lépései a Java programban" 
    content_left: |
        A [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/) segítségével néhány lépésben megjelenítheti a SVG fájlt HTML, JPEG, PNG vagy PDF formátumban.

        * Adja hozzá a [GroupDocs.Viewer for Java] programot (https://releases.groupdocs.com/viewer/java/) projektje függőségeként. 
        * Hozzon létre egy példányt a Viewer osztályból, és töltse be a SVG fájlt a teljes elérési úttal. 
        * Állítsa be a SVG fájl HTML, PNG, JPEG vagy PDF formátumban történő megjelenítését. 
        * Renderelje le a fájlt és ellenőrizze a kimenetet az aktuális könyvtárban. 
        
    title_right: "rendszerkövetelmények" 
    content_right: |
        A GroupDocs.Viewer for Java API-kat minden nagyobb platform és operációs rendszer támogatja. Mielőtt végrehajtaná az alábbi kódot, győződjön meg arról, hogy a következő előfeltételek telepítve vannak a rendszeren.

        * Operációs rendszerek: Microsoft Windows, Linux, MacOS 
        * Fejlesztési környezetek: NetBeans, IntelliJ IDEA, Eclipse stb. 
        * Keretrendszerek: J2SE 8.0 (1.8) vagy újabb (például Java 17) 
    code: |
        ```java
                        
            // Set up input SVG file
            String filePath = "input.svg";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render SVG file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "SVG Viewer élő bemutató"
    content: |
        Tekintse meg a(z) SVG fájlt most a [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/svg) webhelyen.
    lang: "hu"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Egyéb fájlformátumok renderelés és megtekintés a Java használatával"
    exclude: "SVG"
    content: |
        Több formátumú dokumentum- és képnézegető API Java-hoz. Tekintse meg néhány népszerű fájlformátumot alább külső megjelenítők nélkül.
    format: 
        # format loop 1
        - name: "Renderelje le a DOCX-et"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Nyissa meg az XML-dokumentumot" 

        # format loop 2
        - name: "Rendereljen CDR-t" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "CorelDRAW fájl" 

        # format loop 3
        - name: "Rendereljen PPTX-et"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint nyílt XML-bemutató" 

        # format loop 4
        - name: "Renderelje le az XLSX-et"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Nyissa meg az XML-táblázatot" 

        # format loop 5
        - name: "Renderelje le a DWG-t"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "AutoCAD rajz"

        # format loop 6
        - name: "Rendereljen XML-t"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "XML fájl"

        # format loop 7
        - name: "Rendereljen PSD-t"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Adobe Photoshop dokumentum"

        # format loop 8
        - name: "Renderelje le az Adobe Illustrator fájlt"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Adobe Illustrator grafika"

        # format loop 9
        - name: "DOC renderelés"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Microsoft Word dokumentum" 

        # format loop 10
        - name: "TXT renderelés" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Egyszerű szöveges fájl" 

        # format loop 11
        - name: "Renderelje le a DXF-et" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Rajz Exchange formátumú fájl"  
          
        # format loop 12
        - name: "VCF renderelés"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "vCard fájl"  
              
        # format loop 13
        - name: "Rendereljen SVG-t"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Skálázható vektorgrafika" 
          
        # format loop 14
        - name: "Rendereljen HTML-t"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "PDF renderelés"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Portable Document Format File"
          
        # format loop 16
        - name: "JPEG renderelés"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "JPEG kép"
          
        # format loop 17
        - name: "PNG renderelés"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Hordozható hálózati grafika" 
          
        # format loop 18
        - name: "EML megjelenítése"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "E-mail üzenet" 
          
        # format loop 19
        - name: "RTF renderelés"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Rich Text formátumú fájl" 
          
        # format loop 20
        - name: "ODT renderelés"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "OpenDocument szöveges dokumentum" 
          
        # format loop 21
        - name: "CSV megjelenítése"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Vesszővel elválasztott értékek fájl" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
