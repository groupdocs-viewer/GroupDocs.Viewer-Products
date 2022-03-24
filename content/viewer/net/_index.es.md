---
############################# Static ############################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: ".NET Document Viewer API, renderizar PDF Word Excel Imagen HTML Diagrama"
head_description: "Visualizador de archivos C# ASP.NET y API de representación. Agregue visor de PDF, visor de Word, visor de Excel, visor de imágenes, visor de HTML, funciones de visor de correo electrónico en aplicaciones .NET."

############################# Header ############################
title: "Renderizar y mostrar documentos a través de la API de .NET"
description: ".NET Document Viewer API para renderizar más de 170 formatos de documentos en PDF, HTML e imagen con potentes opciones de configuración."
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Descargue prueba gratis"
    link: "https://downloads.groupdocs.com/viewer/net"

############################# SubMenu ############################
submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Viewer for .NET"
        image: "/border/groupdocs-viewer-net.svg"
        product: "GroupDocs.Viewer"
        platform: ".NET"

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
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Precios"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# Visión de conjunto ############################
overview:
    enable: true
    content: |
      Las API de GroupDocs.Viewer para .NET lo ayudan a crear aplicaciones potentes en C#, ASP.NET y otras tecnologías basadas en .NET, que pueden representar y mostrar documentos e imágenes de más de 170 formatos de archivo sin instalar ningún software externo. La biblioteca del visor de archivos rasteriza los documentos y luego los convierte en SVG+HTML+CSS para optimizar la experiencia general de representación de documentos para ver documentos comerciales, imágenes, archivos de texto, diagramas, gráficos, archivos adjuntos de correo electrónico y archivos PDF con velocidad, texto verdadero y alta fidelidad dentro de sus aplicaciones. Tiene la opción de agregar funcionalidades de visualización y lectura de documentos en sus aplicaciones para mostrar un documento completo, un documento parcial, un rango de celdas/página específico, una capa de documento individual, con o sin anotaciones y comentarios para los formatos de archivo admitidos.  

      GroupDocs.Viewer para .NET almacena en caché la salida de documentos renderizados en el disco local de forma predeterminada. También se admite cualquier tipo de almacenamiento en caché externo mediante la implementación de interfaces adecuadas: Amazon S3, Dropbox, Google Drive, Windows Azure, Redis o cualquier otro.
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          A continuación se muestra una descripción general de GroupDocs.Viewer para .NET:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Visión de conjunto"
          content: |
            * Mostrar más de 170 tipos de documentos
            * Obtener HTML, Imagen, Versión PDF
            * Rotate &amp; Reorder
            * Aplicar marca de agua
            * Caché para proceso rápido
            * Agregar fuentes personalizadas
            * Aplicar estándares de codificación
            * Manejador de datos de entrada personalizado
            * Renderizar con control de cambios
            * Renderizar como HTML receptivo
            * Render PDF &amp; CAD Layers
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Viewer para .NET admite la visualización de todos los [formatos de archivo de documentos populares](https://docs.groupdocs.com/viewer/net/supported-document-formats/). Con solo unas pocas líneas de código, agregue el visor de PDF, la oficina de Microsoft Word, la hoja de cálculo de Excel, la imagen, HTML, el correo electrónico de Outlook, OneNote, el proyecto y las capacidades de visualización de gráficos en sus aplicaciones .NET.

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
                * **Various:** VB, PHP, SQL, PL, PY, PV, RB, RST, SASS, SCALA, SCM, SCRIPT, AS, AS3, ASM, BAT, CMAKE, CSS, DIFF, ERB, GROOVY, HAML, LESS, LOG, M, MAKE, MD, ML, MM, SH, SML, VIM, YAML

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Viewer for .NET apoya Sistemas operativos, Frameworks & Gerente de empaquetacións:
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Sistemas operativos"
              content: |
                * Windows Desktop
                * Windows Server
                * Microsoft Azure
                * Linux

            # table loop
            - icon: "fas fa-code"
              title: "Marcos compatibles"
              content: |
                * .NET Framework 2.0 o superior
                * .NET Core 3.1
                * .NET 5 or higher

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-box"
              title: "Gerente de empaquetación"
              content: |
                * NuGet

            # table loop
            - icon: "fas fa-tools"
              title: "Entornos de desarrollo"
              content: |
                * Microsoft Visual Studio
                * Visual Studio Code
                * .NET CLI

############################# Características ############################
features:
    enable: true
    title: "GroupDocs.Viewer for .NET Características"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "Rasterice documentos y conviértalos en SVG, HTML y CSS"

      # feature loop
      - icon: "fas fa-eye"
        content: "Convierta texto a HTML y renderice documentos para obtener una representación de HTML, imagen o PDF"

      # feature loop
      - icon: "fas fa-bolt"
        content: "Tiempo de carga más rápido usando versiones en caché de documentos"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "Convertir presentaciones con Formas y Texto con Efectos 3D"

      # feature loop
      - icon: "fas fa-code"
        content: "Codifique documentos de Word, Excel y correo electrónico según el estándar de codificación deseado"

      # feature loop
      - icon: "fas fa-cloud"
        content: "Renderizar documentos ubicados en FTP o ubicaciones de almacenamiento en la nube"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "Exclusión de fuentes al renderizar a HTML para reducir el tamaño del archivo resultante"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "Minimice la salida de CSS y HTML eliminando comentarios, espacios en blanco adicionales, etc."

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "Leer el texto contenido en un documento de origen a través de sus coordenadas"

      # feature loop
      - icon: "fas fa-border-all"
        content: "Mostrar/ocultar las líneas de cuadrícula de las hojas de Excel en la representación de salida"

      # feature loop
      - icon: "fas fa-wrench"
        content: "Especifique el número de filas en una hoja de Excel para representar en cada página"

      # feature loop
      - icon: "fas fa-columns"
        content: "Ignorar columnas vacías al renderizar documentos de hoja de cálculo"

      # feature loop
      - icon: "fas fa-file-word"
        content: "Transforme documentos de Word en páginas HTML, imágenes o PDF, con control de cambios"

      # feature loop
      - icon: "fas fa-envelope"
        content: "Procesar archivos adjuntos de correo electrónico como archivos originales, imágenes o en representación HTML"

      # feature loop
      - icon: "fas fa-print"
        content: "Establecer restricciones de impresión en documentos PDF"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "Procesar contenido/archivos contenidos en archivos ZIP como archivos adjuntos"

      # feature loop
      - icon: "fas fa-lock"
        content: "Obtener archivos adjuntos de documentos protegidos con contraseña"

      # feature loop
      - icon: "fas fa-file-code"
        content: "Representar formatos de archivo de lenguajes de programación como texto sin formato"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "Ajustar los colores de fondo al ver dibujos CAD"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "Ver documentos de Excel y convertir a PDF, HTML, JPG y PNG"

      # feature loop
      - icon: "fas fa-heading"
        content: "Obtenga los nombres de las hojas de cálculo de un archivo de Excel: muestre los encabezados de columna y los números de fila de la hoja de cálculo"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "Ver y convertir documentos de Microsoft Project con notas"

      # feature loop
      - icon: "fas fa-cube"
        content: "Convierta dibujos CAD a SVG para una mejor experiencia de visualización y zoom"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "Elija renderizar figuras de Visio sin esquema"

    more_feature:
      # more_feature_loop
      - title: "Ver documentos de manera eficiente y confiable"
        content: |
          Al usar la API GroupDocs.Viewer, puede mostrar más de 170 formatos de documentos de manera eficiente y confiable con la integridad del contenido y la estructura del documento intacta. El siguiente código de ejemplo muestra lo fácil que es ver la representación HTML de un documento DOCX:

          ```cs
          // Visor de instancias
          using (Viewer viewer = new Viewer("sample.docx")
          {
              // Establecer opciones de vista
              HtmlViewOptions options = HtmlViewOptions.ForEmbeddedResources();
              // Convertir archivo a HTML con recursos incrustados
              viewer.View(options);
          }
          ```
      # more_feature_loop
      - title: "Aplicar transformación a la salida renderizada"
        content: "Puede realizar varias transformaciones en el documento de salida representado mediante GroupDocs.Viewer para la API de .NET. Estas opciones de transformación le brindan control sobre la forma en que presenta la salida renderizada para su visualización. Las transformaciones disponibles son, opción de rotación de página, opción de reordenamiento de página y aplicación de marca de agua de texto."

      # more_feature_loop
      - title: "Trabajar con archivos de datos de Outlook"
        content: "GroupDocs.Viewer para .NET API puede representar los elementos en los archivos de datos de Outlook (OST/PST) como PDF, HTML y archivos de imagen. Nuestra API Viewer también tiene la capacidad de obtener la lista de carpetas contenidas en los archivos de datos de Outlook. Con GroupDocs.Viewer para la API de .NET, puede especificar la carpeta para procesar desde los archivos de datos de Outlook. Asimismo, también puede obtener mensajes de correo electrónico contenidos en formatos OST/PST como archivos adjuntos. GroupDocs.Viewer para .NET también le permite filtrar mensajes de formatos OST/PST según el asunto, el contenido o el remitente."

      # more_feature_loop
      - title: "Trabajar con documentos CAD"
        content: "GroupDocs.Viewer para .NET API puede representar el modelo y todos los diseños no vacíos o representar un diseño específico de un archivo CAD. GroupDocs.Viewer para .NET API también admite la representación en mosaico o la representación por coordenadas de documentos CAD en imágenes, HTML o PDF. También puede obtener estados de capa para documentos CAD."

############################# Testimonials ###############################
testimonials:
  enable: true

  testimonial:
    # testimonial item loop
    - name: "Mats Oustad"
      designation: "Senior Consultant/Partner at Novanet AS"
      content: "Después de implementar y usar GroupDocs.Viewer para .NET en el proyecto, parece estar funcionando muy bien. He probado con una gran cantidad de documentos y hasta ahora todo bien. Todo lo que le he arrojado se ve muy bien y se ve tan bien como lo haría en un visor de PDF o MS Word."
              
    # testimonial item loop
    - name: "Martin Lasarga"
      designation: "Product Manager at Axentria ECM by G.S.I."
      content: "Excelente servicio y excelentes productos. Fueron extremadamente útiles y receptivos durante el proceso de implementación de GroupDocs.Viewer para .NET, no puedo recomendarlos lo suficiente."

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Viewer ofrece API de visualización de documentos para otros entornos de desarrollo populares"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Viewer for Java"
          image: "/border/groupdocs-viewer-java.svg"
          product: "GroupDocs.Viewer"
          platform: "Java"
          link: "/viewer/java/"

############################# Back to top ###############################
back_to_top:
  enable: true
---
