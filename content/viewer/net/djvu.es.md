---
############################# Static ############################
layout: "format"
date: 2024-04-10T13:10:14
draft: false
lang: es
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head #############################
head_title: ".NET DJVU API de visor: leer, ver y representar en C# VB.NET"
head_description: "API de visor de documentos .NET para leer, representar y mostrar DJVU en cualquier tipo de aplicaciones C#, ASP.NET, VB.NET y .NET Core."

############################# Header ############################
title: "DJVU visor de archivos para aplicaciones C# .NET" 
description: "API de visor de documentos .NET para leer, representar y mostrar archivos DJVU en cualquier tipo de aplicaciones C#, ASP.NET, VB.NET y .NET Core. Vea los archivos renderizados con formato y diseño reales en HTML5, PDF o como una imagen usando unas pocas líneas de código." 
subtitle: "Solución de renderizado de documentos" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "Descarga gratuita de Nuget"
      link: "https://nuget.org/packages/GroupDocs.Viewer"



############################# About ############################
about:
    enable: true
    title: "Acerca de GroupDocs.Viewer para la API .NET"
    link: "/viewer/net/"
    link_title: "Aprende más"
    picture: "about_viewer.svg" # 480 X 400
    content: |
      Comience a ver más de 190 formatos de documentos populares en sus aplicaciones .NET usando GroupDocs.Viewer para API .NET agregando algunas líneas de código. Los desarrolladores pueden mostrar fácilmente PDF, procesamiento de textos, hojas de cálculo de Excel, presentaciones, Visio, proyectos, Outlook y muchos otros formatos de documentos populares en modos HTML5, imagen o PDF. La representación del documento es rápida, idéntica al archivo fuente original y no requiere la instalación de software adicional ni ninguna otra biblioteca externa.



############################# Steps ############################
steps:
    enable: true
    title: "Pasos para renderizar el archivo DJVU en C#" 
    content: |
      Con <a href='https://products.groupdocs.com/viewer/net/'>GroupDocs.Viewer</a> puede renderizar DJVU a HTML, JPEG, PNG o PDF en unos pocos pasos.
      
      1. Instale <a href='https://www.nuget.org/packages/groupdocs.viewer'>GroupDocs.Viewer para .NET</a> usando su administrador de paquetes favorito. 
      2. Cree una instancia de la clase Viewer y cargue el archivo DJVU con la ruta completa.  
      3. Configure opciones para representar el archivo DJVU en formato HTML, PNG, JPEG o PDF. 
      4. Renderice el archivo y verifique la salida en el directorio actual. 
   
    code:
      platform: "net"
      copy_title: "Copiar"
      install:
        command: "dotnet add package GroupDocs.Viewer"
        copy_tip: "haga clic para copiar"
        copy_done: "copiado"
      links:
        #  loop
        - title: "Más ejemplos"
          link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
        #  loop
        - title: "Documentación"
          link: "https://docs.groupdocs.com/viewer/net/"
          
      content: |
        ```csharp {style=abap}

        // Configurar el archivo de entrada DJVU
        string filePath = "input.djvu";

        // Crear una instancia de GroupDocs.Viewer
        using (Viewer viewer = new Viewer(filePath))
        {
            // Establecer opciones de visualización
            HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                
            // Renderice el archivo DJVU a HTML con recursos integrados
            viewer.View(viewOptions);
        }

        ```            


############################# Actions ############################

actions:
  enable: true
  title: "¿Listo para comenzar?"
  description: "Pruebe las funciones de GroupDocs.Viewer de forma gratuita o solicite una licencia"
  items:
    #  loop
    - title: "descarga nuget"
      link: "https://nuget.org/packages/GroupDocs.Viewer"
      color: "red"
        #  loop
    - title: "Licencia"
      link: "https://purchase.groupdocs.com/pricing/viewer/net/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "Renderice otros formatos de archivo usando C#"
    exclude: "DJVU"
    description: "API de visor de imágenes y documentos multiformato para .NET. Vea algunos de los formatos de archivo populares a continuación sin visores externos."
    items: 
        # format loop 1
        - name: "Renderizar DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word Open XML Document" 

        # format loop 2
        - name: "Renderizar CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "CorelDRAW File" 

        # format loop 3
        - name: "Renderizar PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint Open XML Presentation" 

        # format loop 4
        - name: "Renderizar XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet" 

        # format loop 5
        - name: "Renderizar DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "AutoCAD Drawing"

        # format loop 6
        - name: "Renderizar XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "XML File"

        # format loop 7
        - name: "Renderizar PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Adobe Photoshop Document"

        # format loop 8
        - name: "Renderizar AI"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Adobe Illustrator Artwork"

        # format loop 9
        - name: "Renderizar DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Microsoft Word Document" 

        # format loop 10
        - name: "Renderizar texto" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Plain Text File" 

        # format loop 11
        - name: "Renderizar DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Drawing Exchange Format File"  
          
        # format loop 12
        - name: "Renderizar VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "vCard File"  
              
        # format loop 13
        - name: "Renderizar SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Scalable Vector Graphic" 
          
        # format loop 14
        - name: "Renderizar HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "Renderizar PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Portable Document Format File"
          
        # format loop 16
        - name: "Renderizar JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "JPEG Image"
          
        # format loop 17
        - name: "Renderizar PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Portable Network Graphic" 
          
        # format loop 18
        - name: "Representar EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "E-Mail Message" 
          
        # format loop 19
        - name: "Renderizar RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Rich Text Format File" 
          
        # format loop 20
        - name: "Renderizar ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "OpenDocument Text Document" 
          
        # format loop 21
        - name: "Renderizar CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Comma-Separated Values File" 



---
