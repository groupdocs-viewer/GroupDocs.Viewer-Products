---
############################# Static ############################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

lang: es
product: "Viewer"
product_tag: "viewer"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "Java Document Viewer API para PDF Word Excel HTML Imágenes y correos electrónicos"
head_description: "Visor de documentos Java y API de representación de archivos. Agregue visor de PDF, visor de Word, visor de Excel, visor de imágenes, visor de HTML, visor de correo electrónico en aplicaciones Java."

############################# Header ############################
title: "API de Java para renderizar y mostrar documentos"
description: "Biblioteca de visor de documentos para desarrollar aplicaciones Java que representan, visualizan y manipulan de forma nativa documentos multiformato compatibles con más de 170 formatos de archivo."
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Download Free Trial"
    link: "https://downloads.groupdocs.com/viewer/java"

############################# SubMenu ############################
submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Viewer for Java"
        image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-viewer-java.png"
        product: "GroupDocs.Viewer"
        platform: "Java"

    middle:
        button:
            # button loop
            - link: "#overview"
              text: "Descripción general"

            # button loop
            - link: "#features"
              text: "Características"

            # button loop
            - link: "#support"
              text: "Apoyo"

            # button loop
            - link: "https://products.groupdocs.app/viewer/total"
              text: "Demo en vivo"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/java"
              text: "Precios"

    right:
        link_download: "https://releases.groupdocs.com/viewer/java/"
        link_learn: "https://docs.groupdocs.com/viewer/java/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    content: |
      GroupDocs.Viewer para Java combina un potente conjunto de API de visor de documentos para mostrar imágenes y formatos de documentos en sus aplicaciones Java sin necesidad de instalar software adicional. Rasteriza de forma nativa los documentos y los convierte a SVG+HTML+CSS para mejorar la calidad de la visualización de documentos al tiempo que ofrece una salida de alta fidelidad y texto verdadero. Uso de la API de representación de documentos: visualice rápidamente PDF, HTML, XML, Microsoft Office Word, hojas de cálculo de Excel, presentaciones de PowerPoint, correos electrónicos de Outlook, diagramas de Visio, proyectos, metarchivos, imágenes y otros formatos de archivo con facilidad y menos riesgos de programación. También puede mostrar archivos protegidos con contraseña y permitir obtener la representación del documento como HTML, imagen o formulario PDF después de la representación. Nuestra biblioteca de visor de archivos es bastante personalizable, ya que le permite mostrar el documento completo o renderizarlo parcialmente para acelerar el proceso. A través de GroupDocs.Viewer para la API de Java, puede ver páginas, un rango de celdas específico en una hoja de cálculo o incluso representar una capa de documento individual en formatos, como PDF y CAD.  

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
          title: "Descripción general"
          content: |
            * Mostrar más de 170 tipos de documentos 
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
          GroupDocs.Viewer para Java es compatible con todos los formatos de archivos de documentos populares, incluidos: Microsoft Office, imágenes, diagramas y muchos otros.

        left:
          enable: true
          table:
            # table loop
            - title: "Microsoft Office"
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
                * **Archivos de diseño de página:** PDF, TEX, XPS, OXPS
                * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG, OTG, FODP, FODG
                * **Valores separados por delimitadores:** CSV, TSV
                * **Web:** HTML, MHT, MHTML
                * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
                * **PostScript:** PS, EPS
                * **Archivo:** ZIP, TAR, BZ2, GZ, RAR, RAR5
                * **Varios:** OBJ, EPUB, MOBI, DjVu, XML, VCF, VCARD, NUMBERS, NSF

        right:
          enable: true
          table:
            # table loop
            - title: "Imágenes, gráficos y diagramas"
              content: |
                * **Imágenes:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB
                * **Icono de ventanas:** ICO
                * **gráficas vectoriales escalables:** SVG, CDR, CMX, IGS, SVGZ
                * **jpeg2000:** JP2, J2C, J2K, JPC, JPF, JPX, JPM
                * **Adobe Photoshop:** PSD, PSB
                * **Lenguaje de comandos de la impresora:** PCL
                * **Litografía estéreo (impresión 3D):** STL
                * **Clases básicas de la industria:** IFC
                * **Imagenes medicas:** DICOM
                * **Documentos de plotter:** PLT, HPG
                * **Formatos web de diseño de Autodesk:** DWF, DWG
                * **dibujo autocad:** DWT, IFC, STL, CF2
                * **DGN basado en ISFF (V7):** DGN

            # table loop
            - title: "Formatos de lenguajes de programación"
              content: |
                * **Archivos C/C++/C#:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
                * **Archivos Java/JavaScript:** JAVA, JS, JSON, PROPERTIES
                * **Varios:** VB, PHP, SQL, PL, PY, PV, RB, RST, SASS, SCALA, SCM, SCRIPT, AS, AS3, ASM, BAT, CMAKE, CSS, DIFF, ERB, GROOVY, HAML, LESS, LOG, M, MAKE, MD, ML, MM, SH, SML, VIM, YAML

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Viewer para Java es compatible con los siguientes sistemas operativos, marcos y administradores de paquetes:
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Sistemas operativos"
              content: |
                * Microsoft Windows Server 2003 y posterior 
                * Microsoft Windows XP y posterior 
                * Microsoft Windows 10 y 11 
                * Linux (Ubuntu, OpenSUSE, CentOS y otros) 
                * Mac OS X 

            # table loop
            - icon: "fas fa-code"
              title: "Marcos compatibles"
              content: |
                * J2SE 8.0 (1.8) o superior (por ejemplo, Java 17) 

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
                * Gradle

############################# Features ############################
features:
    enable: true
    title: "Funciones de GroupDocs.Viewer para Java"

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
        content: "Rasterice y convierta documentos en SVG, HTML y CSS"

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
        content: "Aplicar estándares de codificación a documentos de Word, Excel y correo electrónico"

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
          // Initialize Viewer
          Viewer viewer = new Viewer("invoice.docx");
          // Create view options
          PdfViewOptions viewOptions = new PdfViewOptions();
          // Convert file to PDF and check the output in the current directory
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

############################# Solutions ##########################
solutions:
    enable: true
    title: "GroupDocs.Viewer ofrece API de visualización de documentos para otros entornos de desarrollo populares"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Viewer for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-viewer-net.png"
          product: "GroupDocs.Viewer"
          platform: ".NET"
          link: "/viewer/net/"

############################# Back to top ##########################
back_to_top:
  enable: true
---