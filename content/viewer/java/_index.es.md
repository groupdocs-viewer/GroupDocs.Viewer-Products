---
############################# Static ############################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

product: "Viewer"
product_tag: "viewer"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "Java Document Viewer API para PDF Word Excel HTML Imágenes y correos electrónicos"
head_description: "Visualizador de documentos Java y API de representación de archivos. Agregar visor de PDF, visor de Word, visor de Excel, visor de imágenes, visor de HTML, visor de correo electrónico en aplicaciones Java."

############################# Header ############################
title: "API de Java para renderizar y mostrar documentos"
description: "Biblioteca de visor de documentos para desarrollar aplicaciones Java que representan, visualizan y manipulan de forma nativa documentos multiformato compatibles con más de 170 formatos de archivo."
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Descargue prueba gratis"
    link: "https://downloads.groupdocs.com/viewer/java"

############################# SubMenu ############################
submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Viewer for Java"
        image: "/border/groupdocs-viewer-java.svg"
        product: "GroupDocs.Viewer"
        platform: "Java"

    middle:
        button:
            # button loop
            - link: "#overview"
              text: "Visión de conjunto"

            # button loop
            - link: "#features"
              text: "Características"

            # button loop
            - link: "#support"
              text: "Support"

            # button loop
            - link: "https://products.groupdocs.app/viewer"
              text: "Live Demo"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/java"
              text: "Precios"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/java"
        link_learn: "https://docs.groupdocs.com/viewer/java/"
        link_buy: "https://purchase.groupdocs.com"

############################# Visión de conjunto ############################
overview:
    enable: true
    content: |
      GroupDocs.Viewer para Java combina un potente conjunto de API de visor de documentos para mostrar imágenes y formatos de documentos en sus aplicaciones Java sin necesidad de instalar software adicional. Rasteriza de forma nativa los documentos y los convierte a SVG+HTML+CSS para mejorar la calidad de visualización de los documentos al mismo tiempo que ofrece una salida de alta fidelidad y texto verdadero. Uso de la API de representación de documentos: vea rápidamente PDF, HTML, XML, oficina de Microsoft Word, hojas de cálculo de Excel, presentaciones de PowerPoint, correos electrónicos de Outlook, diagramas de Visio, proyectos, metarchivos, imágenes y otros formatos de archivo con facilidad y menos riesgos de programación. También puede mostrar archivos protegidos con contraseña y permitir obtener la representación del documento como HTML, imagen o formulario PDF después de la representación. Nuestra biblioteca de visor de archivos es bastante personalizable, ya que le permite mostrar el documento completo o renderizarlo parcialmente para acelerar el proceso. A través de GroupDocs.Viewer para la API de Java, puede ver páginas, un rango de celdas específico en una hoja de cálculo o incluso representar una capa de documento individual en formatos, como PDF y CAD.  
        
      GroupDocs.Viewer para la API de Java le permite representar documentos con o sin anotaciones o comentarios para los formatos de archivo admitidos. También le permite agregar directorios de fuentes personalizados y extraer información básica del documento, como tipo de archivo, extensión, nombre, número de páginas, etc. 
        
      GroupDocs.Viewer para Java es compatible con todas las versiones de Java y es compatible con los sistemas operativos populares (Windows, Linux, macOS) que pueden ejecutar el tiempo de ejecución de Java.
    tabs:
      enable: true     
      
      ## TAB ONE ##
      tab_one:
        description: |
          A continuación se muestra una descripción general de GroupDocs.Viewer para Java:

        right:
          enable: true
          icon: "fab fa-html5"
          title: "Visión de conjunto"
          content: |
            * Mostrar más de 50 tipos de documentos
            * Obtener HTML, Imagen, Versión PDF
            * Rotar y reordenar
            * Aplicar marca de agua
            * Caché para proceso rápido
            * Agregar fuentes personalizadas
            * Aplicar estándares de codificación
            * Manejador de datos de entrada personalizado
            * Renderizar con control de cambios
            * Renderizar como HTML receptivo
            * Renderizar capas de PDF y CAD
            * Procesar archivos protegidos
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Viewer para Java es compatible con todos los [formatos de archivo de documentos](https://docs.groupdocs.com/viewer/java/supported-document-formats/), incluidos: oficina de Microsoft, imágenes, diagramas y muchos otros.

        left:
          enable: true
          table:
            # table loop
            - title: "oficina de Microsoft"
              content: |
                * **Word:** DOC, DOCX, DOCM, DOT, DOTX, DOTM, RTF, TXT
                * **Excel:** XLS, XLSX, XLSM, XLSB, XLTM, XLT, XLTM, XLTX, XLAM, SXC, SpreadsheetML
                * **PowerPoint:** PPT, PPTX, PPS, PPSX, PPSM, POT, POTM, POTX, PPTM
                * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
                * **Project:** MPP, MPT, MPX
                * **Outlook:** MSG, EML, EMLX, PST, OST
                * **OneNote:** ONE

            # table loop
            - title: "Otros formatos"
              content: |
                * **PDF Formats:** PDF, TEX, XPS, OXPS
                * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG, OTG, FODP, FODG
                * **Delimiter-Separated Values:** CSV, TSV
                * **Web:** HTML, MHT, MHTML
                * **Metafile:** WMF, EMF, CGM, WMZ, EMZ
                * **PostScript:** PS, EPS
                * **Archives:** ZIP, TAR, BZ2, GZ, RAR, RAR5
                * **Various:** OBJ, EPUB, MOBI, DjVu, XML, VCF, VCARD, NUMBER, NSF

        right:
          enable: true
          table:
            # table loop
            - title: "Imágenes, gráficos y diagramas"
              content: |
                * **Images:** BMP, GIF, JPG, PNG, TIFF, multi-page TIFF, WebP, DNG, DIB, DCM
                * **Windows Icon:** ICO
                * **Scalable Vector Graphics:** SVG, CDR, CMX, IGS, SVGZ
                * **Jpeg2000:** JP2, J2C, J2K, JPC, JPF, JPX, JPM
                * **Adobe Photoshop:** PSD, PSB
                * **Printer Command Language:** PCL
                * **Stereo Lithography (3D Printing):** STL
                * **Industry Foundation Classes:** IFC
                * **Medical Imaging:** DICOM
                * **Plotter Documents:** PLT, HPG
                * **Autodesk Design Web Formats:** DWF, DWG
                * **AutoCAD Drawing:** DGN, DWT, IFC, STL, CF2
                * **ISFF-based DGN (V7):** DGN

            # table loop
            - title: "Formatos de lenguajes de programación"
              content: |
                * **C/C++/C# Files:** C, CC, CS, CPP, CXX, C#, H, HH, M, MM
                * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES
                * **Varios:** VB, PHP, SQL, PL, PY, PV, RB, RST, SASS, SCALA, SCM, SCRIPT, AS, AS3, ASM, BAT, CMAKE, CSS, DIFF, ERB, GROOVY, HAML, LESS, LOG, M, MAKE, MD, ML, MM, SH, SML, VIM, YAML

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Viewer for Java apoya siguiendo Sistemas operativos, Frameworks & Gerente de empaquetacións:
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Sistemas operativos"
              content: |
                * Microsoft Windows Desktop
                * Microsoft Windows Server
                * Linux
                * MacOS

            # table loop
            - icon: "fas fa-code"
              title: "Marcos compatibles"
              content: |
                * Java 7 (1.7) y superior

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-cogs"
              title: "Entornos de desarrollo"
              content: |
                * NetBeans
                * IntelliJ IDEA
                * Eclipse
            # table loop
            - icon: "fas fa-tools"
              title: "Herramienta de automatización de compilación"
              content: |
                * Maven

############################# Características ############################
features:
    enable: true
    title: "GroupDocs.Viewer for Java Características"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "Visor de HTML, PDF, imágenes, Word, Excel y otros formatos de documentos"

      # feature loop
      - icon: "fas fa-eye"
        content: "Renderice archivos de dibujos de AutoCAD (DWG) a formato SVG"

      # feature loop
      - icon: "fas fa-bolt"
        content: "Ajustar el color de fondo del archivo convertido"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "Rasterizar y Convertir Documentos a SVG, HTML y CSS"

      # feature loop
      - icon: "fas fa-code"
        content: "Obtenga representación HTML, imagen o PDF de documentos a través de la representación"

      # feature loop
      - icon: "fas fa-cloud"
        content: "Versiones en caché de documentos para acelerar el tiempo de carga"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "Configurar directorios de fuentes personalizadas"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "Aplicar estándares de codificación to Word, Excel and Email Documents"

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "Procesar documentos de forma remota en FTP o almacenamiento en la nube"

      # feature loop
      - icon: "fas fa-border-all"
        content: "Eliminar o conservar anotaciones y comentarios durante la renderización"

      # feature loop
      - icon: "fas fa-wrench"
        content: "Renderizar páginas de documentos como páginas HTML separadas"

      # feature loop
      - icon: "fas fa-columns"
        content: "Renderizar diapositivas y páginas ocultas y aplicar el reordenamiento de página al documento renderizado"

      # feature loop
      - icon: "fas fa-file-word"
        content: "Renderizar Rango de Páginas, Páginas Específicas o Todas las Páginas en HTML"

      # feature loop
      - icon: "fas fa-envelope"
        content: "Representar u ocultar comentarios de documentos"

      # feature loop
      - icon: "fas fa-print"
        content: "Cree HTML receptivo para algunos formatos de documentos a través de la representación"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "Reduzca el tamaño de archivo resultante del HTML procesado mediante la exclusión de fuentes"

      # feature loop
      - icon: "fas fa-lock"
        content: "Elimine comentarios, espacios en blanco adicionales, etc., para minimizar la salida HTML y CSS"

      # feature loop
      - icon: "fas fa-file-code"
        content: "Usar coordenadas del documento de origen para leer el texto contenido"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "Mostrar/ocultar borde de celda en hojas de Excel de la salida renderizada"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "Representar un número específico de filas de cada página en una hoja de Excel"

      # feature loop
      - icon: "fas fa-heading"
        content: "Modelo de renderizado y todos los diseños no vacíos o un diseño particular de un archivo CAD"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "Procesar los elementos en los archivos de datos de Outlook (OST/PST) como PDF"

      # feature loop
      - icon: "fas fa-cube"
        content: "Representación en mosaico o representación por coordenadas de documentos CAD como imagen, HTML o PDF"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "Establecer restricciones de impresión al renderizar a PDF"

    more_feature:
      # more_feature_loop
      - title: "API eficiente y confiable para ver documentos"
        content: |
          GroupDocs.Viewer for Java API se puede usar para ver, representar y mostrar documentos de más de 150 formatos de archivo diferentes. Se realiza de forma fiable y eficiente manteniendo intactos el contenido y la estructura del documento. El siguiente ejemplo muestra el nivel de facilidad con el que GroupDocs.Viewer para la API de Java representa un archivo DOCX como un archivo de imagen usando Java:
          
          ```java
          // Inicializar visor
          Viewer viewer = new Viewer("sample.docx");
          // Crear opciones de vista
          PdfViewOptions viewOptions = new PdfViewOptions();
          // Convierta el archivo a PDF y verifique la salida en el directorio actual
          viewer.view(viewOptions);
          ```
      # more_feature_loop
      - title: "Realizar transformaciones durante la representación de documentos"
        content: "GroupDocs.Viewer for Java API le ofrece varias opciones de transformación para aplicar en el documento renderizado para una visualización y visualización más personalizada. Puede girar las páginas proporcionando el ángulo. Puede el orden de las páginas renderizadas. Aplique texto específico como marca de agua a páginas o imágenes renderizadas. A través de GroupDocs.Viewer para la API de Java, también tiene la capacidad de agregar fuentes personalizadas al documento que se está procesando."

      # more_feature_loop
      - title: "Trabajar con archivos adjuntos de correo electrónico"
        content: "GroupDocs.Viewer for Java API le permite obtener archivos adjuntos específicos o todos de un correo electrónico. Una vez que obtenga los archivos adjuntos de correo electrónico requeridos, puede convertir estos archivos adjuntos en imágenes o HTML."

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Viewer ofrece API de visualización de documentos para otros entornos de desarrollo populares"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Viewer for .NET"
          image: "/border/groupdocs-viewer-net.svg"
          product: "GroupDocs.Viewer"
          platform: ".NET"
          link: "/viewer/net/"

############################# Back to top ###############################
back_to_top:
  enable: true
---