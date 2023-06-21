---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: es

############################# Head #############################
head_title: ".NET PSD Viewer API - Leer, Ver, Renderizar en C# VB.NET"
head_description: "API de visor de documentos .NET para leer, representar y mostrar PSD en cualquier tipo de aplicaciones C#, ASP.NET, VB.NET y .NET Core."

############################# Header ############################
title: "PSD Visor de archivos para aplicaciones C# .NET" 
description: "API de visor de documentos .NET para leer, representar y mostrar archivos PSD en cualquier tipo de aplicaciones C#, ASP.NET, VB.NET y .NET Core. Vea los archivos renderizados con formato y diseño reales en HTML5, PDF o como una imagen usando unas pocas líneas de código." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Descargue prueba gratis"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Acerca de GroupDocs.Viewer para la API de .NET" 
    content: |
        Comience a ver más de 190 formatos de documentos populares en sus aplicaciones .NET utilizando GroupDocs.Viewer para las API de .NET agregando unas pocas líneas de código. Los desarrolladores pueden mostrar fácilmente PDF, procesamiento de textos, hoja de cálculo de Excel, presentación, Visio, Project, Outlook y muchos otros formatos de documentos populares en los modos HTML5, imagen o PDF. La representación del documento es rápida, idéntica al archivo fuente original y no requiere la instalación de software adicional ni ninguna otra biblioteca externa.

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
              text: "Referencia de la API"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Ejemplos de código"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "demostraciones en vivo"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Precios"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "Pasos para procesar el archivo PSD en C#" 
    content_left: |
        Con [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/) puede representar PSD a HTML, JPEG, PNG o PDF en unos pocos pasos.

        * Instale [GroupDocs.Viewer para .NET](https://www.nuget.org/packages/groupdocs.viewer) con su administrador de paquetes favorito. 
        * Cree una instancia de la clase Viewer y cargue el archivo PSD con la ruta completa. 
        * Configure las opciones para representar el archivo PSD en formato HTML, PNG, JPEG o PDF. 
        * Renderice el archivo y verifique la salida en el directorio actual. 
        
    title_right: "Requisitos del sistema" 
    content_right: |
        Las API de GroupDocs.Viewer para .NET son compatibles con todas las principales plataformas y sistemas operativos. Antes de ejecutar el código a continuación, asegúrese de tener instalados los siguientes requisitos previos en su sistema.

        * Sistemas operativos: Microsoft Windows, Linux, Mac OS 
        * Entornos de desarrollo: Microsoft Visual Studio, Visual Studio Code, .NET CLI 
        * Marcos: .NET Framework, .NET Standard, .NET Core, .NET 
    code: |
        ```cs
                        
            // Set up input PSD file
            string filePath = "input.psd";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render PSD file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "PSD Espectador de demostración en vivo"
    content: |
        Vea el archivo PSD ahora mismo visitando el sitio web de [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/psd).
    lang: "es"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Representación y visualización de otros formatos de archivo mediante C#"
    exclude: "PSD"
    content: |
        API de visor de documentos e imágenes multiformato para .NET. Vea algunos de los formatos de archivo populares a continuación sin ningún visor externo.
    format: 
        # format loop 1
        - name: "Renderizar DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Documento XML abierto de Microsoft Word" 

        # format loop 2
        - name: "Procesar CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "Archivo CorelDRAW" 

        # format loop 3
        - name: "Renderizar PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "Presentación XML abierta de PowerPoint" 

        # format loop 4
        - name: "Renderizar XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Hoja de cálculo XML abierto de Microsoft Excel" 

        # format loop 5
        - name: "Renderizar DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "dibujo autocad"

        # format loop 6
        - name: "Procesar XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "Archivo XML"

        # format loop 7
        - name: "Procesar PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Documento de Adobe Photoshop"

        # format loop 8
        - name: "Renderizar archivo de Adobe Illustrator"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Ilustraciones de Adobe Illustrator"

        # format loop 9
        - name: "renderizar DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Documento de Microsoft Word" 

        # format loop 10
        - name: "Renderizar TXTO" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Archivo de texto sin formato" 

        # format loop 11
        - name: "renderizar DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Archivo de formato de intercambio de dibujo"  
          
        # format loop 12
        - name: "renderizar VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "Archivo vCard"  
              
        # format loop 13
        - name: "renderizar SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Gráfico vectorial escalable" 
          
        # format loop 14
        - name: "renderizar HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Archivo de lenguaje de marcado de hipertexto" 
          
        # format loop 15
        - name: "Renderizar PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Archivo de formato de documento portátil"
          
        # format loop 16
        - name: "Renderizar JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "Imagen JPEG"
          
        # format loop 17
        - name: "renderizar PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Gráfico de red portátil" 
          
        # format loop 18
        - name: "Renderizar EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "Mensaje de correo electrónico" 
          
        # format loop 19
        - name: "renderizar RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Archivo de formato de texto enriquecido" 
          
        # format loop 20
        - name: "Renderizar ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "Documento de texto OpenDocument" 
          
        # format loop 21
        - name: "Procesar CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Archivo de valores separados por comas" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
