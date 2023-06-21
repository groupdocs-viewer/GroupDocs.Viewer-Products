---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: es

############################# Head #############################
head_title: "Java VCF Viewer API - Procesar y mostrar VCF en aplicaciones Java"
head_description: "Ver archivos VCF en aplicaciones Java, J2EE, J2SE. Admite la visualización de más de 170 formatos de archivos de imágenes y documentos en HTML, PDF o modo de imagen con funciones avanzadas para administrar las opciones de visualización de documentos."

############################# Header ############################
title: "Renderizar y ver VCF en Java" 
description: "API de visor de archivos VCF nativa y de alto rendimiento para aplicaciones basadas en Java, J2EE y J2SE, que admite una amplia gama de características adicionales para personalizar la apariencia del formato del documento de salida." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Descargue prueba gratis"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Acerca de GroupDocs.Viewer para la API de Java" 
    content: |
        Permita que sus aplicaciones Java muestren más de 170 formatos de archivo en HTML, PDF o modos de imagen usando GroupDocs.Viewer para las API de Java sin ningún software adicional instalado; como Microsoft Office, Apache Open Office, Adobe Acrobat Reader, etc. Los desarrolladores pueden ver fácilmente todas las imágenes y tipos de documentos populares, incluidos Microsoft Office, OpenDocument, HTML, PDF, Archive, Diagrams, Photoshop, AutoCAD y formatos de lenguaje de programación dentro de las aplicaciones Java con renderizado rápido y de la más alta calidad.

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
    title_left: "Pasos para procesar el archivo VCF en Java" 
    content_left: |
        Con [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/) puede representar VCF a HTML, JPEG, PNG o PDF en unos pocos pasos.

        * Agregue [GroupDocs.Viewer for Java](https://releases.groupdocs.com/viewer/java/) como una dependencia de su proyecto. 
        * Cree una instancia de la clase Viewer y cargue el archivo VCF con la ruta completa. 
        * Configure las opciones para representar el archivo VCF en formato HTML, PNG, JPEG o PDF. 
        * Renderice el archivo y verifique la salida en el directorio actual. 
        
    title_right: "Requisitos del sistema" 
    content_right: |
        Las API de GroupDocs.Viewer para Java son compatibles con todas las principales plataformas y sistemas operativos. Antes de ejecutar el código a continuación, asegúrese de tener instalados los siguientes requisitos previos en su sistema.

        * Sistemas operativos: Microsoft Windows, Linux, Mac OS 
        * Entornos de desarrollo: NetBeans, IntelliJ IDEA, Eclipse, etc. 
        * Marcos: J2SE 8.0 (1.8) o superior (por ejemplo, Java 17) 
    code: |
        ```java
                        
            // Set up input VCF file
            String filePath = "input.vcf";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render VCF file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "VCF Espectador de demostración en vivo"
    content: |
        Vea el archivo VCF ahora mismo visitando el sitio web de [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/vcf).
    lang: "es"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Representación y visualización de otros formatos de archivo usando Java"
    exclude: "VCF"
    content: |
        API de visor de documentos e imágenes multiformato para Java. Vea algunos de los formatos de archivo populares a continuación sin ningún visor externo.
    format: 
        # format loop 1
        - name: "Renderizar DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Documento XML abierto de Microsoft Word" 

        # format loop 2
        - name: "Procesar CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "Archivo CorelDRAW" 

        # format loop 3
        - name: "Renderizar PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "Presentación XML abierta de PowerPoint" 

        # format loop 4
        - name: "Renderizar XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Hoja de cálculo XML abierto de Microsoft Excel" 

        # format loop 5
        - name: "Renderizar DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "dibujo autocad"

        # format loop 6
        - name: "Procesar XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "Archivo XML"

        # format loop 7
        - name: "Procesar PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Documento de Adobe Photoshop"

        # format loop 8
        - name: "Renderizar archivo de Adobe Illustrator"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Ilustraciones de Adobe Illustrator"

        # format loop 9
        - name: "renderizar DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Documento de Microsoft Word" 

        # format loop 10
        - name: "Renderizar TXTO" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Archivo de texto sin formato" 

        # format loop 11
        - name: "renderizar DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Archivo de formato de intercambio de dibujo"  
          
        # format loop 12
        - name: "renderizar VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "Archivo vCard"  
              
        # format loop 13
        - name: "renderizar SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Gráfico vectorial escalable" 
          
        # format loop 14
        - name: "renderizar HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Archivo de lenguaje de marcado de hipertexto" 
          
        # format loop 15
        - name: "Renderizar PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Archivo de formato de documento portátil"
          
        # format loop 16
        - name: "Renderizar JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "Imagen JPEG"
          
        # format loop 17
        - name: "renderizar PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Gráfico de red portátil" 
          
        # format loop 18
        - name: "Renderizar EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "Mensaje de correo electrónico" 
          
        # format loop 19
        - name: "renderizar RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Archivo de formato de texto enriquecido" 
          
        # format loop 20
        - name: "Renderizar ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "Documento de texto OpenDocument" 
          
        # format loop 21
        - name: "Procesar CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Archivo de valores separados por comas" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
