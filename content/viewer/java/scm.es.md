---
############################# Static ############################
layout: "format"
date: 2024-05-13T10:14:28
draft: false
lang: es
product: "Viewer"
product_tag: "viewer"
platform: "Java"
platform_tag: "java"

############################# Head #############################
head_title: "Java SCM API de visualización: renderiza y muestra SCM en aplicaciones Java"
head_description: "Ver archivos SCM en aplicaciones Java, J2EE, J2SE. Admite la visualización de más de 180 formatos de archivos de imágenes y documentos en HTML, PDF o modo de imagen con funciones avanzadas para administrar las opciones de visualización de documentos."

############################# Header ############################
title: "Renderizar y ver SCM en Java" 
description: "API de visualización de archivos SCM nativa y de alto rendimiento para aplicaciones basadas en Java, J2EE y J2SE, que admite una amplia gama de funciones adicionales para personalizar la apariencia del formato del documento de salida." 
subtitle: "Solución de renderizado de documentos" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "Descarga gratuita de Maven"
      link: "https://releases.groupdocs.com/viewer/java/"



############################# About ############################
about:
    enable: true
    title: "Acerca de GroupDocs.Viewer para la API de Java"
    link: "/viewer/java/"
    link_title: "Aprende más"
    picture: "about_viewer.svg" # 480 X 400
    content: |
      Habilite sus aplicaciones Java para mostrar más de 180 formatos de archivos en HTML, PDF o modos de imagen utilizando GroupDocs.Viewer para las API de Java sin ningún software adicional instalado; como Microsoft Office, Apache Open Office, Adobe Acrobat Reader, etc. Los desarrolladores pueden ver fácilmente todas las imágenes y tipos de documentos populares, incluidos Microsoft Office, OpenDocument, HTML, PDF, Archive, Diagrams, Photoshop, AutoCAD y formatos de lenguaje de programación dentro de las aplicaciones Java con renderizado rápido y de la más alta calidad.



############################# Steps ############################
steps:
    enable: true
    title: "Pasos para renderizar el archivo SCM en Java" 
    content: |
      Con <a href='https://products.groupdocs.com/viewer/java/'>GroupDocs.Viewer</a> puedes renderizar SCM a HTML, JPEG, PNG o PDF en unos pocos pasos.
      
      1. Agregue <a href='https://releases.groupdocs.com/viewer/java/'>GroupDocs.Viewer para Java</a> como una dependencia a su proyecto. 
      2. Cree una instancia de la clase Viewer y cargue el archivo SCM con la ruta completa.  
      3. Configure opciones para representar el archivo SCM en formato HTML, PNG, JPEG o PDF. 
      4. Renderice el archivo y verifique la salida en el directorio actual. 
   
    code:
      platform: "java"
      copy_title: "Copiar"
      install:
        command: |
          <dependencies>
            <dependency>
              <groupId>com.groupdocs</groupId>
              <artifactId>groupdocs-viewer</artifactId>
              <version>{0}</version>
            </dependency>
          </dependencies>

          <repositories>
            <repository>
              <id>repository.groupdocs.com</id>
              <name>GroupDocs Repository</name>
              <url>https://repository.groupdocs.com/repo/</url>
            </repository>
          </repositories>
        copy_tip: "haga clic para copiar"
        copy_done: "copiado"
      links:
        #  loop
        - title: "Más ejemplos"
          link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Java"
        #  loop
        - title: "Documentación"
          link: "https://docs.groupdocs.com/viewer/java/"
          
      content: |
        ```java {style=abap}

        // Configurar el archivo de entrada SCM
        String filePath = "input.scm";

        // Crear una instancia de GroupDocs.Viewer
        try (Viewer viewer = new Viewer(filePath))
        {
            // Establecer opciones de visualización
            HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                
            // Renderice el archivo SCM a HTML con recursos integrados
            viewer.view(viewOptions);
        }

        ```
            

############################# Actions ############################

actions:
  enable: true
  title: "¿Listo para comenzar?"
  description: "Pruebe las funciones de GroupDocs.Viewer de forma gratuita o solicite una licencia"
  items:
    #  loop
    - title: "descargar experto"
      link: "https://releases.groupdocs.com/viewer/java/"
      color: "red"
        #  loop
    - title: "Licencia"
      link: "https://purchase.groupdocs.com/pricing/viewer/java/"
      color: "light"



############################# More Formats #####################
more_formats:
    enable: true
    title: "Renderice otros formatos de archivo usando Java"
    exclude: "SCM"
    description: "API de visor de imágenes y documentos multiformato para Java. Vea algunos de los formatos de archivo populares a continuación sin visores externos."
    items: 
        # format loop 1
        - name: "Renderizar DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Open XML Document" 

        # format loop 2
        - name: "Renderizar CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "CorelDRAW File" 

        # format loop 3
        - name: "Renderizar PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint Open XML Presentation" 

        # format loop 4
        - name: "Renderizar XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet" 

        # format loop 5
        - name: "Renderizar DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "AutoCAD Drawing"

        # format loop 6
        - name: "Renderizar XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "XML File"

        # format loop 7
        - name: "Renderizar PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Adobe Photoshop Document"

        # format loop 8
        - name: "Renderizar AI"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Adobe Illustrator Artwork"

        # format loop 9
        - name: "Renderizar DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Microsoft Word Document" 

        # format loop 10
        - name: "Renderizar texto" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Plain Text File" 

        # format loop 11
        - name: "Renderizar DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Drawing Exchange Format File"  
          
        # format loop 12
        - name: "Renderizar VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "vCard File"  
              
        # format loop 13
        - name: "Renderizar SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Scalable Vector Graphic" 
          
        # format loop 14
        - name: "Renderizar HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "Renderizar PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Portable Document Format File"
          
        # format loop 16
        - name: "Renderizar JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "JPEG Image"
          
        # format loop 17
        - name: "Renderizar PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Portable Network Graphic" 
          
        # format loop 18
        - name: "Representar EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "E-Mail Message" 
          
        # format loop 19
        - name: "Renderizar RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Rich Text Format File" 
          
        # format loop 20
        - name: "Renderizar ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "OpenDocument Text Document" 
          
        # format loop 21
        - name: "Renderizar CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Comma-Separated Values File" 


---
