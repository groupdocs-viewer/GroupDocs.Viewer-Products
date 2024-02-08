---
############################# Static ##########################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: es
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

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

############################# Head ############################
head_title: "API de visor de documentos .NET, renderizado PDF Word Excel Imagen HTML Diagrama"
head_description: "Visor de archivos C# ASP.NET y API de renderizado. Agregue funciones de visor de PDF, visor de Word, visor de Excel, visor de imágenes, visor HTML y visor de correo electrónico en aplicaciones .NET."

############################# Header ##########################
title: "Representar y mostrar documentos<br>usando .NET API"
description: "Potente API Viewer para representar más de 180 formatos de documentos en PDF, HTML e imágenes con opciones de configuración versátiles."
words:
  for: "for"

actions:
  main: "Descarga gratuita de NuGet"
  main_link: "https://www.nuget.org/packages/GroupDocs.Viewer"
  alt: "Licencia"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/net"
  title: "¿Listo para comenzar?"
  description: "Pruebe las funciones de GroupDocs.Viewer de forma gratuita o solicite una licencia"

release:
  title: "Versión {0} lanzada"
  notes: "Ver qué hay de nuevo"
  downloads: "Descargas"
  link: "https://releases.groupdocs.com/viewer/net/release-notes/latest/"

code:
  title: "Renderizar archivos PDF en C#"
  more: "Más ejemplos"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
  install: "dotnet add package GroupDocs.Viewer"
  content: |
    ```csharp {style=abap}   
    // Cargue el archivo PDF de origen
    using (var viewer = new Viewer("resume.pdf"))
    {
        // Establecer opciones HTML de salida
        var viewOptions = 
        HtmlViewOptions.ForEmbeddedResources("page{0}.html");
        
        // Renderice PDF a HTML con recursos integrados        
        viewer.View(viewOptions);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Viewer de un vistazo"
  description: "API para renderizar, mostrar, convertir documentos, diapositivas, diagramas y muchos otros tipos de documentos en aplicaciones .NET"
  features:
    # feature loop
    - title: "Vea documentos de manera eficiente y confiable"
      content: "Con GroupDocs.Viewer API puede representar de manera eficiente documentos de cualquier formato compatible en HTML, JPEG, PNG y PDF con opciones flexibles y potentes mientras mantiene la integridad del contenido y la estructura del documento. GroupDocs.Viewer es compatible con .NET Framework 4.6.2 y .NET 6.0, funciona en plataformas Windows y Linux."

    # feature loop
    - title: "Se admiten los formatos de archivos y documentos más populares"
      content: "Admitimos la renderización de los 180 formatos de archivos y documentos más populares, que incluyen Word, Excel, PDF, PowerPoint, familia de formatos OpenDocument, archivos, imágenes rasterizadas y vectoriales, libros electrónicos, lenguajes de programación y marcas, y muchos otros tipos de archivos, incluidos los cifrados. archivos con protección por contraseña."

    # feature loop
    - title: "Salida personalizable"
      content: "GroupDocs.Viewer permite no sólo renderizar el documento, sino también controlar cómo exactamente, qué partes del documento deben renderizarse o ahora, cómo deben renderizarse y aplicar diferentes transformaciones a la salida renderizada."

    # feature loop
    - title: "Interfaz de usuario para ASP.NET Core"
      content: "Proporcionamos un paquete de interfaz de usuario de código abierto para ASP.NET Core que se puede agregar a su proyecto en un par de minutos. El paquete Viewer.UI contiene una interfaz de usuario web basada en Angular y ofrece un conjunto de API útiles y proveedores de almacenamiento de datos."

############################# Platforms ############################
platforms:
  enable: true
  title: "Independencia de plataforma"
  description: "GroupDocs.Viewer para .NET admite los siguientes sistemas operativos, marcos y administradores de paquetes"
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
    - title: "VS Code"
      image: "vs_code"
    # platform loop
    - title: "ReSharper"
      image: "resharper"
    # platform loop
    - title: "macOS"
      image: "finder"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "NuGet"
      image: "nuget"

############################# File formats ############################
formats:
  enable: true
  title: "Formatos de archivo admitidos"
  description: |
    GroupDocs.Viewer para .NET admite operaciones con los siguientes [formatos de archivo](https://docs.groupdocs.com/viewer/net/supported-document-formats/).
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
  description: "Algunos casos de uso de GroupDocs.Viewer típico para operaciones .NET"
  items:
    # code sample loop
    - title: "Renderizar DOCX a HTML"
      content: |
        Las propiedades de clase [HtmlViewOptions](https://reference.groupdocs.com/viewer/net/groupdocs.viewer.options/htmlviewoptions/) le permiten controlar el proceso de conversión, más sobre eso [aquí](https://docs.groupdocs.com/viewer/net/rendering-to-html/). Por ejemplo, puede incrustar todos los recursos externos en el archivo HTML de salida, minimizar el archivo de salida y optimizarlo para imprimir.
        {{< landing/code title="C#">}}
        ```csharp {style=abap}
        using GroupDocs.Viewer;
        using GroupDocs.Viewer.Options;
        
        // Visor de instancias
        using (Viewer viewer = new Viewer("resume.docx"))
        {
            // Establecer opciones HTML de salida
            HtmlViewOptions options = HtmlViewOptions.ForEmbeddedResources();
            
            // Renderice DOCX a HTML con recursos integrados
            viewer.View(options);
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Exportar PPTX a PDF"
      content: |
        Cree una instancia de clase [PdfViewOptions](https://reference.groupdocs.com/viewer/net/groupdocs.viewer.options/pdfviewoptions/) y pásela a [Viewer.View](https://reference.groupdocs.com/viewer/net/groupdocs.viewer/viewer/view/#view) método para convertir un archivo PPTX de PowerPoint a PDF. Las propiedades de la clase PdfViewOptions le permiten controlar el proceso de conversión. Por ejemplo, puede proteger el archivo PDF de salida, reordenar sus páginas y especificar la calidad de las imágenes del documento. Consulte la [siguiente sección de documentación](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/) para obtener más detalles.
        {{< landing/code title="C#">}}
        ```csharp {style=abap}   
        using GroupDocs.Viewer;
        using GroupDocs.Viewer.Options;
        
        using (var viewer = new Viewer("presentation.pptx"))
        {
            // Establecer opciones de salida de PDF       
            var viewOptions = new PdfViewOptions("presentation.pdf");
            
            // Exportar PPTX a PDF       
            viewer.View(viewOptions);
        }
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