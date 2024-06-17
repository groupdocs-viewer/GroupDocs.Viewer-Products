---
############################# Static ############################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: es
product: "Viewer"
product_tag: "viewer"
platform: "Python via .NET"
platform_tag: "python-net"

############################# Drop-down ############################
supported_platforms:
  items:
    # supported_platforms loop
    - title: ".NET"
      tag: "net"
    # supported_platforms loop
    - title: "Java"
      tag: "java"
    # supported_platforms loop
    - title: "Node.js"
      tag: "nodejs-java" 
    # supported_platforms loop
    - title: "Python"
      tag: "python-net" 


############################# Head ############################
head_title: "API Visor de Documentos Python para PDF, Word, Excel, HTML, Imágenes y Correos Electrónicos"
head_description: "API de renderizado de archivos y visor de documentos Python. Agregue visor de PDF, visor de Word, visor de Excel, visor de imágenes, visor de HTML y visor de correo electrónico en aplicaciones Python."

############################# Header ############################
title: "Una API de Python Potente para la Representación Optimizada de Documentos"
description: "Renderice y visualice más de 180 formatos de documento (PDF, HTML, imagen) con API potentes y opciones de configuración versátiles para desarrollar aplicaciones Python."
words:
  for: "for"

actions:
  main: "Descarga Gratuita de PyPI"
  main_link: "https://pypi.org/project/groupdocs-viewer-net/"
  alt: "Licencia"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/python-net"
  title: "¿Listo para comenzar?"
  description: "Pruebe las funciones de GroupDocs.Viewer de forma gratuita o solicite una licencia"

release:
  title: "Versión {0} lanzada"
  notes: "Ver qué hay de nuevo"
  downloads: "Descargas"
  link: "https://releases.groupdocs.com/viewer/python-net/release-notes/latest/"

code:
  title: "Renderizar archivos PDF en Python"
  more: "Más ejemplos"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Python-via-.NET"
  install: "pip install groupdocs-viewer-net"
  content: |
    ```python {style=abap}
    import groupdocs.viewer as gv
    import groupdocs.viewer.options as gvo
    hvo = gvo.HtmlViewOptions  
  
    // Establecer opciones HTML de salida, un archivo por página
    with gv.Viewer("resume.docx") as viewer:
      // Crear una instancia del visor
      opts = hvo.for_embedded_resources("page_{0}.html")

      // Renderizar PDF a HTML con recursos incrustados
      viewer.view(opts)
    ```
############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Viewer de un vistazo"
  description: "API para renderizar, mostrar, convertir documentos, diapositivas, diagramas y muchos otros tipos de documentos en aplicaciones Python"
  features:
    # feature loop
    - title: "Visualice documentos de manera eficiente y confiable"
      content: "Con la API GroupDocs.Viewer, puede renderizar de manera eficiente documentos de cualquier formato compatible a HTML, JPEG, PNG y PDF con opciones flexibles y potentes, manteniendo la integridad del contenido y la estructura del documento. GroupDocs.Viewer para Python funciona en plataformas Windows y Linux."

    # feature loop
    - title: "Se admiten los formatos de archivo y documento más populares"
      content: "Admitimos la renderización de más de 180 de los formatos de archivo y documento más populares, que incluyen Word, Excel, PDF, PowerPoint, la familia de formatos OpenDocument, archivos, imágenes ráster y vectoriales, libros electrónicos, lenguajes de programación y lenguajes de marcado, y muchos otros tipos de archivo, incluidos archivos cifrados con protección por contraseña."

    # feature loop
    - title: "Salida personalizable"
      content: "GroupDocs.Viewer no solo permite renderizar el documento, sino también controlar cómo exactamente, qué partes del documento deben renderizarse o no, cómo deben renderizarse y aplicar diferentes transformaciones a la salida renderizada."

############################# Platforms ############################
platforms:
  enable: true
  title: "Independencia de la plataforma"
  description: "GroupDocs.Viewer para Python admite los siguientes sistemas operativos, frameworks y administradores de paquetes"
  items:
    # platform loop
    - title: "Amazon"
      image: "amazon"
    # platform loop
    - title: "Docker"
      image: "docker"
    # platform loop
    - title: "Azure"
      image: "azure"
    # platform loop
    - title: "Eclipse"
      image: "eclipse"
    # platform loop
    - title: "IntelliJ"
      image: "intellij"
    # platform loop
    - title: "Windows"
      image: "windows"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "PyPI"
      image: "pypi"

############################# File formats ############################
formats:
  enable: true
  title: "Formatos de archivo admitidos"
  description: |
    GroupDocs.Viewer para Python a través de .NET admite operaciones con los siguientes formatos de archivo: [enlace formatos de archivo compatibles](https://docs.groupdocs.com/viewer/python-net/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office, OpenDocument y formatos de texto
        * **Word:** DOC, DOCX, DOCM, DOT, DOTX, DOTM, RTF, TXT
        * **Excel:** XLS, XLSX, XLSM, XLSB, XLTM, XLT, XLTM, XLTX
        * **PowerPoint:** PPT, PPTX, PPS, PPSX, PPSM, POT, POTM, POTX, PPTM        
        * **Project:** MPP, MPT, MPX
        * **Outlook:** MSG, EML, EMLX, PST, OST
        * **OneNote:** ONE
        * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG
        * **Fixed Page Layout:** PDF, TEX, XPS, OXPS
        * **e-Books:** EPUB, MOBI, DjVu
        * **Delimiter-Separated Values:** CSV, TSV
    # group loop
    - color: "blue"
      content: |
        ### Imágenes, gráficos y diagramas
        * **Imágenes rasterizadas:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
        * **Windows Icon:** ICO
        * **Scalable Vector Graphics:** SVG, CDR, CMX, IGS, SVGZ        
        * **Adobe Photoshop:** PSD, PSB        
        * **Stereo Lithography (3D Printing):** STL        
        * **Medical Imaging:** DICOM
        * **Plotter Documents:** PLT, HPG
        * **Autodesk Design Web Formats:** DWF, DWG
        * **AutoCAD Drawing:** DWT, IFC, STL, CF2        
      # group loop
    - color: "red"
      content: |
        ### Otro        
        * **Web:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **Archivo:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **Otro:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "Funciones de GroupDocs.Viewer"
  description: "Represente, visualice y convierta sin problemas documentos PDF y Office"

  items:
    # feature loop
    - icon: "viewhtml"
      title: "Ver documentos en HTML"
      content: "Convierta documentos de cualquier tipo en un documento HTML con CSS y SVG, que se puede mostrar en cualquier navegador web moderno."

    # feature loop
    - icon: "rasterize"
      title: "Rasterizar documentos"
      content: "Rasterice cualquier formato de documento compatible a la imagen rasterizada, con formato de imagen ajustable y calidad de compresión."

    # feature loop
    - icon: "sourcecode"
      title: "Renderizar y resaltar códigos de programación"
      content: "Soporte de todos los lenguajes de programación, scripting y marcado populares, con capacidad de analizar y resaltar su sintaxis."

    # feature loop
    - icon: "convertpdf"
      title: "Convertir a PDF"
      content: "Los documentos de cualquier formato compatible se pueden convertir y guardar fácilmente en PDF con opciones ajustables."

    # feature loop
    - icon: "transform"
      title: "Aplicar transformaciones"
      content: "El documento de salida se puede transformar durante la renderización: las páginas se pueden rotar y/o reorganizar, y se puede colocar una marca de agua de texto encima de ellas."

    # feature loop
    - icon: "adjustment"
      title: "Ajuste de salida HTML"
      content: "Los documentos HTML de salida, generados por GroupDocs.Viewer, se pueden ajustar con mucha precisión: se permite guardarlos en una secuencia o archivo, con recursos externos o integrados, devoluciones de llamada, etc."

    # feature loop
    - icon: "complex"
      title: "Soporte de estructuras de documentos complejas."
      content: "GroupDocs.Viewer admite no solo documentos individuales, sino también archivos que contienen internamente una lista o estructura jerárquica de documentos, como mensajes de correo electrónico con archivos adjuntos, archivos ZIP con archivos internos dentro de carpetas, imágenes TIFF de varias páginas, etc."

    # feature loop
    - icon: "optimization"
      title: "Opciones de optimización"
      content: "GroupDocs.Viewer contiene un subsistema de caché ajustable, que puede acelerar el tiempo de carga utilizando las versiones almacenadas en caché de los documentos. Además, un conjunto de diferentes opciones para diferentes formatos permite excluir algunas partes o aspectos innecesarios de los documentos del renderizado (fuentes, hojas de trabajo ocultas, archivos adjuntos de correo electrónico) para optimizar el rendimiento general."

    # feature loop
    - icon: "passwordprotected"
      title: "Soporte de documentos protegidos con contraseña."
      content: "GroupDocs.Viewer permite abrir documentos cifrados de diferentes tipos: PDF, WordProcessing, Hoja de cálculo, Presentación y otros, especificando una contraseña en las opciones de carga."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Ejemplos de código"
  description: "Algunos casos de uso de operaciones típicas de GroupDocs.Viewer para Python a través de .NET"
  items:
    # code sample loop
    - title: "Renderizar DOCX a HTML"
      content: |
        Las propiedades de la clase `HtmlViewOptions` le permiten controlar el proceso de conversión. Para obtener más información, consulte [aquí](https://docs.groupdocs.com/viewer/python-net/rendering-to-html/). Por ejemplo, puede incrustar todos los recursos externos en el archivo HTML de salida, minimizar el archivo de salida y optimizarlo para la impresión.
        {{< landing/code title="Python">}}
        ```python {style=abap}
        import groupdocs.viewer as gv
        import groupdocs.viewer.options as gvo 

        // Crear una instancia del visor
        with gv.Viewer("resume.docx") as viewer:
          // Establecer opciones HTML de salida, un archivo por página
          viewOptions = gvo.HtmlViewOptions.for_embedded_resources("page_{0}.html")
          // Renderizar DOCX a HTML con recursos incrustados
          viewer.view(viewOptions)
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Exportar PPTX a PDF"
      content: |
        Cree una instancia de la clase `PdfViewOptions` y pásesela al método `Viewer.view` para convertir un archivo PowerPoint PPTX a PDF. Las propiedades de la clase `PdfViewOptions` le permiten controlar el proceso de conversión. Consulte la siguiente sección de la documentación para obtener más detalles: [enlace a la sección de conversión a PDF](https://docs.groupdocs.com/viewer/python-net/rendering-to-pdf/)
        {{< landing/code title="Python">}}
        ```python {style=abap}
        import groupdocs.viewer as gv
        import groupdocs.viewer.options as gvo  

        // Crear una instancia del visor
        with gv.Viewer("presentation.pptx") as viewer:
          // Establecer opciones PDF de salida
          viewOptions = gvo.PdfViewOptions("presentation.pdf")
          // Exportar PPTX a PDF
          viewer.view(viewOptions)
        ```
        {{< /landing/code >}}
############################# Reviews ############################
# reviews:
# enable: true
# title: "Reseñas de productos GroupDocs"
# description: "No confíe sólo en nuestra palabra. Vea lo que otros desarrolladores dicen sobre nuestras API"

# items:
#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "Excelente servicio y excelentes productos. Fueron extremadamente útiles y receptivos durante el proceso de implementación de GroupDocs.Viewer para .NET, no puedo recomendarlos lo suficiente."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "Después de implementar y usar GroupDocs.Viewer para .NET en el proyecto, parece estar funcionando muy bien. He probado con muchos documentos y hasta ahora todo bien. Todo lo que le he añadido se reproduce muy bien y se ve tan bien como en un visor de PDF o MS Word."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---
