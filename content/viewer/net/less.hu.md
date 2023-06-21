---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: hu

############################# Head #############################
head_title: ".NET LESS Viewer API – olvasás, megtekintés, renderelés C# VB.NET-ben"
head_description: ".NET dokumentumnézegető API a LESS olvasásához, megjelenítéséhez és megjelenítéséhez bármilyen típusú C#, ASP.NET, VB.NET és .NET Core alkalmazásokban."

############################# Header ############################
title: "LESS Fájlnézegető C# .NET alkalmazásokhoz" 
description: ".NET dokumentumnézegető API LESS fájlok olvasásához, megjelenítéséhez és megjelenítéséhez bármilyen típusú C#, ASP.NET, VB.NET és .NET Core alkalmazásokban. Tekintse meg a renderelt fájlokat valódi formázással és elrendezéssel HTML5-ben, PDF-ben vagy képként a kód néhány sorával." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Ingyenes próbaverzió letöltése"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "A GroupDocs.Viewer for .NET API-ról" 
    content: |
        Kezdje meg a .NET-alkalmazásaiban több mint 190 népszerű dokumentumformátum megtekintését a GroupDocs.Viewer for .NET API-k használatával néhány sor kód hozzáadásával. A fejlesztők könnyedén megjeleníthetik a PDF-et, a szövegszerkesztőt, az Excel-táblázatot, a prezentációt, a Visio-t, a Projectet, az Outlook-ot és sok más népszerű dokumentumformátumot HTML5, kép vagy PDF módban. A dokumentum-megjelenítés gyors, megegyezik az eredeti forrásfájllal, és nem igényel további szoftverek vagy egyéb külső könyvtárak telepítését.

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
    title_left: "A LESS fájl renderelésének lépései a C# programban" 
    content_left: |
        A [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/) segítségével néhány lépésben megjelenítheti a LESS fájlt HTML, JPEG, PNG vagy PDF formátumban.

        * Telepítse a [GroupDocs.Viewer for .NET] programot (https://www.nuget.org/packages/groupdocs.viewer) kedvenc csomagkezelőjével. 
        * Hozzon létre egy példányt a Viewer osztályból, és töltse be a LESS fájlt a teljes elérési úttal. 
        * Állítsa be a LESS fájl HTML, PNG, JPEG vagy PDF formátumban történő megjelenítését. 
        * Renderelje le a fájlt és ellenőrizze a kimenetet az aktuális könyvtárban. 
        
    title_right: "rendszerkövetelmények" 
    content_right: |
        A GroupDocs.Viewer for .NET API-kat minden nagyobb platform és operációs rendszer támogatja. Mielőtt végrehajtaná az alábbi kódot, győződjön meg arról, hogy a következő előfeltételek telepítve vannak a rendszeren.

        * Operációs rendszerek: Microsoft Windows, Linux, MacOS 
        * Fejlesztési környezetek: Microsoft Visual Studio, Visual Studio Code, .NET CLI 
        * Keretrendszerek: .NET Framework, .NET Standard, .NET Core, .NET 
    code: |
        ```cs
                        
            // Set up input LESS file
            string filePath = "input.less";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render LESS file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "LESS Viewer élő bemutató"
    content: |
        Tekintse meg a(z) LESS fájlt most a [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/less) webhelyen.
    lang: "hu"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Egyéb fájlformátumok renderelés és megtekintés a C# használatával"
    exclude: "LESS"
    content: |
        Több formátumú dokumentumok és képnézegető API .NET-hez. Tekintse meg néhány népszerű fájlformátumot alább külső megjelenítők nélkül.
    format: 
        # format loop 1
        - name: "Renderelje le a DOCX-et"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word Nyissa meg az XML-dokumentumot" 

        # format loop 2
        - name: "Rendereljen CDR-t" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "CorelDRAW fájl" 

        # format loop 3
        - name: "Rendereljen PPTX-et"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint nyílt XML-bemutató" 

        # format loop 4
        - name: "Renderelje le az XLSX-et"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Nyissa meg az XML-táblázatot" 

        # format loop 5
        - name: "Renderelje le a DWG-t"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "AutoCAD rajz"

        # format loop 6
        - name: "Rendereljen XML-t"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "XML fájl"

        # format loop 7
        - name: "Rendereljen PSD-t"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Adobe Photoshop dokumentum"

        # format loop 8
        - name: "Renderelje le az Adobe Illustrator fájlt"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Adobe Illustrator grafika"

        # format loop 9
        - name: "DOC renderelés"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Microsoft Word dokumentum" 

        # format loop 10
        - name: "TXT renderelés" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Egyszerű szöveges fájl" 

        # format loop 11
        - name: "Renderelje le a DXF-et" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Rajz Exchange formátumú fájl"  
          
        # format loop 12
        - name: "VCF renderelés"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "vCard fájl"  
              
        # format loop 13
        - name: "Rendereljen SVG-t"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Skálázható vektorgrafika" 
          
        # format loop 14
        - name: "Rendereljen HTML-t"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "PDF renderelés"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Portable Document Format File"
          
        # format loop 16
        - name: "JPEG renderelés"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "JPEG kép"
          
        # format loop 17
        - name: "PNG renderelés"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Hordozható hálózati grafika" 
          
        # format loop 18
        - name: "EML megjelenítése"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "E-mail üzenet" 
          
        # format loop 19
        - name: "RTF renderelés"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Rich Text formátumú fájl" 
          
        # format loop 20
        - name: "ODT renderelés"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "OpenDocument szöveges dokumentum" 
          
        # format loop 21
        - name: "CSV megjelenítése"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Vesszővel elválasztott értékek fájl" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
