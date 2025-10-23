---
############################# Static ##########################
layout: "family"
date: 2023-12-20T06:39:57
draft: false

product: "Viewer"
product_tag: "viewer"

############################# Head ############################
head_title: "Renderizar y ver documentos API | SDK de visor de documentos on‑premise y servicio en línea"
head_description: "Renderice y vea archivos de Word, PDF, Excel, Powerpoint o imágenes de forma fácil y gratuita"

############################# Header ##########################
title: "Renderice y vea documentos con facilidad"
description: |
  SDK potente de visor de documentos para renderizar distintos archivos a PDF, HTML e Imagen.

  Cargue documentos de diversas fuentes, incluidos archivos, secuencias, URL, servidores FTP, Amazon S3, Azure Blob Storage y más.

  Genere páginas HTML responsivas, proteja los archivos PDF de salida y reordene sus páginas, rote páginas, renderice notas y comentarios si es necesario.

############################# Platforms ############################
supported_platforms:
  enable: true  
  head_title: "Elige tu plataforma"
  title: "Plataformas compatibles"
  description: "La biblioteca GroupDocs.Viewer admite los siguientes sistemas operativos y marcos"
  details_link_title: "Aprende más"
  items:
    # supported_platforms loop
    - title: ".NET"
      description: "GroupDocs.Viewer for .NET"
      color: "blue"
      tag: "net"
      link: "/viewer/net/"
      features_link: "https://docs.groupdocs.com/viewer/net/system-requirements/"
      features:
        # features loop
        - content: ".NET Framework 4.6.2+  <br>  .NET Core 3.1  <br>  .NET 6+"
          rows: "3"
        # features loop
        - content: "Windows, Linux"
          rows: "1"
        # features loop
        - content: "Más de 180 formatos de archivo"
          rows: "1"
        # features loop
        - content: "Paquete de interfaz de usuario para ASP.NET Core"
          rows: "1"
        # features loop
        - content: "ASP.NET WebForms Demo  <br>  ASP.NET MVC Demo  <br>  ASP.NET Core Demo"
          rows: "3"
    
    # supported_platforms loop
    - title: "Java"
      description: "GroupDocs.Viewer for Java"
      color: "red"
      tag: "java"
      link: "/viewer/java/"
      features_link: "https://docs.groupdocs.com/viewer/java/system-requirements/"
      features:
        # features loop
        - content: "J2SE 8.0 (1.8)+"
          rows: "3"
        # features loop
        - content:  "Windows, Linux, macOS"
          rows: "1"       
        # features loop
        - content: "Más de 180 formatos de archivo"
          rows: "1"
        # features loop
        - content:  "Paquete de interfaz de usuario para Spring y Dropwizard"
          rows: "1"
        # features loop
        - content:  "Spring Demo  <br>  Dropwizard demo"
          rows: "3"

    # supported_platforms loop
    - title: "Node.js"
      description: "GroupDocs.Viewer for Node.js"
      color: "green"
      tag: "nodejs-java"
      link: "/viewer/nodejs-java/"
      features_link: "https://docs.groupdocs.com/viewer/nodejs-java/system-requirements/"
      features:
        # features loop
        - content: "Node.js 16+  <br>  and J2SE 8.0 (1.8)+"
          rows: "3"
        # features loop
        - content:  "Windows, Linux, macOS"
          rows: "1"
        # features loop
        - content:  "Más de 180 formatos de archivo"
          rows: "1"
        # features loop
        - content:  "Paquete de interfaz de usuario: próximamente"
          rows: "1" 
        # features loop
        - content:  "Demostración: próximamente"
          rows: "3" 

    # supported_platforms loop
    - title: "Python"
      description: "GroupDocs.Viewer for Python"
      color: "yellow"
      tag: "python-net"
      link: "/viewer/python-net/"
      features_link: "https://docs.groupdocs.com/viewer/python-net/system-requirements/"
      features:
        # features loop
        - content: "Python 3.9+  <br>  and .Net 6+"
          rows: "3"
        # features loop
        - content:  "Windows, Linux, macOS"
          rows: "1"
        # features loop
        - content:  "Más de 180 formatos de archivo"
          rows: "1"
        # features loop
        - content:  "Paquete de interfaz de usuario: próximamente"
          rows: "1" 
        # features loop
        - content:  "Demostración: próximamente"
          rows: "3" 

############################# Features ############################

features:
  enable: true
  title: "Conjunto de funciones de GroupDocs.Viewer"
  description: "API para renderizar archivos de diferentes tipos como HTML, PDF, PNG y JPEG en aplicaciones para verlos sin software de terceros."

  items:
    # feature loop
    - icon: "view"
      title: "Ver documentos e imágenes."
      content: "Vea documentos representándolos como archivos HTML, PDF, PNG y JPEG."

    # feature loop
    - icon: "password"
      title: "Abrir documentos seguros"
      content: "Especifique una contraseña para abrir documentos cifrados."

    # feature loop
    - icon: "load"
      title: "Cargue archivos desde cualquier lugar"
      content: "Cargue documentos desde varios archivos, URL, servidores FTP, Amazon S3 y más."
    
    # feature loop
    - icon: "pages"
      title: "Renderizar todas o páginas específicas"
      content: "Especifique un rango de números de página que se representarán."


############################# Code samples ############################
code_samples:
  enable: true
  title: "Ejemplos de código de GroupDocs.Viewer"
  description: "Algunos casos de uso de operaciones típicas de GroupDocs.Viewer en C#, Java, TypeScript"
  items:
    # code sample loop
    - title: "Cómo renderizar archivos DOCX a PDF"
      content: |
       Renderice documentos DOCX a PDF sin Microsoft Word u otro software instalado. Cargue y vea fácilmente archivos DOCX dentro de su aplicación .NET, ya sea una aplicación web o de escritorio. A continuación se muestra un ejemplo de cómo convertir un archivo DOCX a PDF:
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Cargue el archivo DOCX para renderizar
            using (Viewer viewer = new Viewer("sample.docx"))
            {
              // Renderizar DOCX a un archivo PDF
              PdfViewOptions viewOptions = new PdfViewOptions();
              viewer.View(viewOptions);
            }
            ```
        - language: "Java"
          color: "red"
          content: |
            ```java {style=abap}   
            import com.groupdocs.viewer.Viewer;
            import com.groupdocs.viewer.options.PdfViewOptions;
            // ...
            // Cargue el archivo DOCX para renderizar
            try (Viewer viewer = new Viewer("sample.docx")) {
                // Renderizar DOCX a un archivo PDF
                PdfViewOptions viewOptions = new PdfViewOptions();
                viewer.view(viewOptions);
            }
            ```
        - language: "TypeScript"
          color: "green"
          content: |
            ```javascript {style=abap}  
            // Cargue el archivo DOCX para renderizar
            const viewer = new groupdocs.viewer.Viewer("sample.docx")
            
            // Renderizar DOCX a un archivo PDF
            const viewOptions = groupdocs.viewer.PdfViewOptions(output.pdf)
            viewer.view(viewOptions)
            ```

        - language: "Python"
          color: "yellow"
          content: |
            ```python {style=abap} 
            import groupdocs.viewer as gv
            import groupdocs.viewer.options as gvo   
            // Cargue el archivo DOCX para renderizar
            with gv.Viewer("sample.docx") as viewer:
            
                // Renderizar DOCX a un archivo PDF
                viewOptions = gvo.PdfViewOptions("output.pdf")
                viewer.view(viewOptions)
            ```

############################# Formats ############################
formats:
  enable: true
  title:  "Más de 180 formatos de archivo compatibles"
  description: "GroupDocs.Viewer admite operaciones con los más populares [formatos de archivo](https://docs.groupdocs.com/viewer/net/supported-document-formats/)"


############################# Metrics ############################

metrics:
  enable: true
  title: "Métricas detalladas y conocimientos estadísticos"
  description: "Sumérgete en un desglose detallado de nuestras cifras clave, proporcionando métricas completas y conocimientos estadísticos sobre nuestros logros, impacto y crecimiento."

  items:
    # metrics loop
    - number: "180+"
      title: "Formatos soportados"
      content: "Vea fácilmente más de 180 formatos de archivos, incluidos documentos, imágenes y dibujos CAD, sin complicaciones. Rompe las barreras de compatibilidad y accede a diversos archivos sin esfuerzo con nuestra solución de visualización integral."
    # metrics loop
    - number: "1.0M"
      title: "Descargas NuGet"
      content: "Nuestra solución de paquete NuGet se ha convertido en un recurso confiable y ampliamente adoptado en la comunidad de desarrolladores, brindando una integración perfecta y una funcionalidad valiosa para innumerables proyectos."

    # metrics loop
    - number: "10+"
      title: "Bibliotecas"
      content: "Nuestro producto incluye más de 10 bibliotecas que ofrecen funciones avanzadas para optimizar el rendimiento. Estas bibliotecas están diseñadas para satisfacer diferentes necesidades de desarrollo con capacidades incomparables."
    
    # metrics loop
    - number: "100+"
      title: "Clientes felices"
      content: "Sirviendo a las marcas más emblemáticas de todo el mundo. ¡Descubra por qué a cientos de personas les encanta GroupDocs.Viewer! Explore una navegación fluida, una colaboración cómoda y una facilidad de uso incomparable. ¡Únete ahora!"


############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "Nuestros clientes felices"
  description: "Las bibliotecas de GroupDocs son utilizadas por marcas distinguidas y reconocidas a nivel mundial en todo el mundo."

  items:
    # customers loop
    - title: "BenQ Corporation"
      logo: "benq"
    # customers loop
    - title: "Nasdaq Stock Market"
      logo: "nasdaq"
    # customers loop
    - title: "AT&T Inc."
      logo: "att"
    # customers loop
    - title: "AstraZeneca"
      logo: "astrazeneca"
    # customers loop
    - title: "Central Bank of Argentina"
      logo: "argentinacentralbank"
    # customers loop
    - title: "Roche Holding AG"
      logo: "roche"
    # customers loop
    - title: "Capita"
      logo: "capita"
    # customers loop
    - title: "Axa S.A."
      logo: "axa"
    # customers loop
    - title: "Instructure Inc."
      logo: "instructure"
     # customers loop
    - title: "Wipro"
      logo: "wipro"



############################# Actions ############################

actions:
  enable: true
  title: "¿Listo para comenzar?"
  description: "Pruebe las funciones de GroupDocs.Viewer de forma gratuita o solicite una licencia"

  items:
    #  loop
    - title: ".NET"
      link: "/viewer/net/"
      color: "blue"
        #  loop
    - title: "Java"
      link: "/viewer/java/"
      color: "red"
        #  loop
    - title: "Node.js"
      link: "/viewer/nodejs-java/"
      color: "green"
        #  loop
    - title: "Python"
      link: "/viewer/python-net/"
      color: "yellow"

############################# Faq ############################

faq:
  enable: true
  title: "Preguntas e inquietudes comunes"
  description: "Encuentre respuestas a consultas comunes en nuestra sección de preguntas frecuentes para abordar rápidamente sus consultas e inquietudes."

  items:
    #  loop
    - question: "¿Puedo evaluar los productos de GroupDocs antes de comprarlos?"
      answer: |
        ¡Sí! Todos los productos GroupDocs tienen disponible una versión de evaluación sin riesgos. Recomendamos encarecidamente a los desarrolladores que descarguen y prueben nuestras API antes de comprarlas para asegurarse de que satisfarán sus necesidades al 100%.
    #  loop
    - question: "¿GroupDocs realiza demostraciones de productos?"
      answer: |
        No, nuestro enfoque está en nuestras API y en hacer los productos más funcionales y estables posibles. Ofrecemos pruebas totalmente funcionales y gratuitas en forma de [licencia temporal](https://purchase.groupdocs.com/temporary-license/) para que pueda probar el producto usted mismo.
    #  loop
    - question: "¿Dónde puedo descargar el producto?"
      answer: |
        Todos los productos están disponibles para descargar desde el [sitio web](https://releases.groupdocs.com). No enviamos copias físicas de nuestro software por correo.    
    #  loop
    - question: "¿Las licencias de desarrollador de GroupDocs son por usuario o por usuario designado?"
      answer: |
        Las licencias de GroupDocs Developer son por usuario, no por usuario designado. Entendemos que los miembros de un equipo de codificación pueden cambiar con el tiempo y que no es práctico tener que actualizar las licencias cada vez que esto ocurre.
    #  loop
    - question: "¿Necesitamos licencias sólo para desarrolladores activos? Por ejemplo, tenemos un equipo de dos desarrolladores trabajando en el turno A y un segundo equipo de dos desarrolladores trabajando en el turno B… en esta situación, ¿necesitamos dos o cuatro licencias?"
      answer: |
        Todos los desarrolladores que estén trabajando en el proyecto deben tener una licencia. En esta situación, GroupDocs considera que su equipo tiene cuatro miembros (aunque trabajen en momentos diferentes).

############################# Cloud ############################

cloud_links:
  enable: true
  title: "API de código bajo de GroupDocs.Viewer"
  description: "Acelere la visualización de documentos o imágenes en cualquier tipo de aplicación con nuestra API REST basada en la nube"

  items:
    #  loop
    - icon: "groupdocs_viewer-for-curl"
      title: "GroupDocs.Viewer Cloud for cURL"
      link: "https://products.groupdocs.cloud/viewer/curl"
      content: "Utilice la API del visor de documentos cURL RESTful para representar y mostrar de manera eficiente Microsoft Office, PDF y varios otros formatos de archivos estándar en sus aplicaciones."

    #  loop
    - icon: "groupdocs_viewer-for-net"
      title: "GroupDocs.Viewer Cloud for .NET"
      link: "https://products.groupdocs.cloud/viewer/net"
      content: "Mejore las capacidades de visualización de documentos en aplicaciones .NET con Cloud SDK para .NET. Vea documentos sin problemas en formatos HTML, PDF o imagen."
    #  loop
    - icon: "groupdocs_viewer-for-java"
      title: "GroupDocs.Viewer Cloud for Java"
      link: "https://products.groupdocs.cloud/viewer/java"
      content: "Integre capacidades avanzadas de representación de documentos en sus aplicaciones Java utilizando un SDK de visor de documentos para Java especialmente diseñado."

############################# Apps ############################

app_links:
  enable: true
  title: "Aplicaciones GroupDocs.Viewer NoCode"
  description: "Aplicación en línea que le permite ver más de 180 formatos de archivos populares en el navegador"

  items:
    #  loop
    - icon: "groupdocs_viewer-app"
      title: "GroupDocs.Viewer Total"
      link: "https://products.groupdocs.app/viewer/total"
      content: "Explore una aplicación en línea gratuita para ver más de 180 formatos de archivos directamente desde su navegador web preferido."

    #  loop
    - icon: "groupdocs_words-app"
      title:  "GroupDocs.Viewer DOCX"
      link: "https://products.groupdocs.app/viewer/docx"
      content: "Herramienta basada en web para ver archivos de Microsoft Word sin esfuerzo en varios dispositivos."

    #  loop
    - icon: "groupdocs_pdf-app"
      title:  "GroupDocs.Viewer PDF"
      link: "https://products.groupdocs.app/viewer/pdf"
      content: "Abra y vea archivos PDF en línea con el visor de PDF gratuito."
    

---