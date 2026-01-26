---
############################# Static ############################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: pt
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
head_title: "API visualizador de documentos Python para PDF, Word, Excel, HTML, imagens e e-mail"
head_description: "API de renderização de arquivos e visualizador de documentos Python. Adicione visualizador de PDF, visualizador de Word, visualizador de Excel, visualizador de imagens, visualizador de HTML e visualizador de e-mail aos aplicativos Python."

############################# Header ############################
title: "API Python poderosa para renderização otimizada de documentos"
description: "Renderize e visualize mais de 180 formatos de documento (PDF, HTML, imagem) com APIs robustas e opções de configuração versáteis para o desenvolvimento de aplicativos Python."
words:
  for: "for"

actions:
  viewer_demo: true
  viewer_demo_file_name: "quarterly-report.docx"
  main: "Download gratuito do PyPI"
  main_link: "https://pypi.org/project/groupdocs-viewer-net/"
  alt: "Licenciamento"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/python-net"
  title: "Pronto para começar?"
  description: "Experimente os recursos do GroupDocs.Viewer gratuitamente ou solicite uma licença"

release:
  title: "Versão {0} lançada"
  notes: "Veja o que é novo"
  downloads: "Transferências"
  link: "https://releases.groupdocs.com/viewer/python-net/release-notes/latest/"

code:
  title: "Renderização de arquivo PDF em Python"
  more: "Mais exemplos"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Python-via-.NET"
  install: "pip install groupdocs-viewer-net"
  content: |
    ```python {style=abap}
    import groupdocs.viewer as gv
    import groupdocs.viewer.options as gvo
    hvo = gvo.HtmlViewOptions  
  
    // Defina as opções de saída HTML, um arquivo por página
    with gv.Viewer("resume.docx") as viewer:
      // Crie uma instância do visualizador
      opts = hvo.for_embedded_resources("page_{0}.html")

      // Renderização de PDF em HTML com recursos incorporados
      viewer.view(opts)
    ```
############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Viewer em resumo"
  description: "API para renderização, visualização e conversão de documentos, slides, diagramas e muitos outros tipos de documentos em aplicativos Python"
  features:
    # feature loop
    - title: "Visualize documentos de forma eficiente e confiável"
      content: "Com a API GroupDocs.Viewer você pode renderizar documentos de quaisquer formatos suportados para [HTML](https://docs.groupdocs.com/viewer/python-net/rendering-to-html/), JPEG, PNG, e [PDF](https://docs.groupdocs.com/viewer/python-net/rendering-to-pdf/) usando opções flexíveis e avançadas, preservando o conteúdo e a estrutura do documento. O GroupDocs.Viewer para Python funciona nos sistemas Windows e Linux."

    # feature loop
    - title: "Suporta a maioria dos formatos de arquivo e documento comuns"
      content: "A API renderiza mais de 180 formatos de arquivos e documentos, incluindo [Word](https://docs.groupdocs.com/viewer/python-net/render-word-documents/), [Excel](https://docs.groupdocs.com/viewer/python-net/specify-rendering-options/), [PDF](https://docs.groupdocs.com/viewer/python-net/render-pdf-documents/), [PowerPoint](https://docs.groupdocs.com/viewer/python-net/render-presentations/), a família OpenDocument, arquivos compactados, imagens raster e vetoriais, e‑Books, linguagens de programação e marcações, além de arquivos criptografados protegidos por senha."

    # feature loop
    - title: "Saída personalizável"
      content: "O GroupDocs.Viewer permite não apenas renderizar o documento, mas também controlar como exatamente quais partes do documento devem ser renderizadas ou não, como devem ser renderizadas e aplicar diferentes transformações à saída renderizada."

############################# Platforms ############################
platforms:
  enable: true
  title: "Independência de plataforma"
  description: "O GroupDocs.Viewer para Python oferece suporte aos seguintes sistemas operacionais, frameworks e gerenciadores de pacotes"
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
  title: "Formatos de arquivo suportados"
  description: |
    O GroupDocs.Viewer para Python (via .NET) oferece suporte a operações com os seguintes formatos de arquivo: [formatos de arquivo suportados](https://docs.groupdocs.com/viewer/python-net/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office, OpenDocument e formatos de texto
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
        ### Imagens, gráficos e diagramas
        * **Imagens rasterizadas:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
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
        ### Outro        
        * **Rede:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **Arquivos:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **Outro:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "Recursos do GroupDocs.Viewer"
  description: "Renderize, exiba e converta perfeitamente documentos PDF e Office"

  items:
    # feature loop
    - icon: "viewhtml"
      title: "[Ver documentos em HTML](https://docs.groupdocs.com/viewer/python-net/rendering-to-html/)"
      content: "Converta documentos de qualquer tipo em um documento HTML com CSS e SVG, que pode ser exibido em qualquer navegador moderno."

    # feature loop
    - icon: "rasterize"
      title: "[Rasterizar documentos](https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Python-via-.NET/blob/master/Examples/basic_usage/render_document_to_image/render_to_png.py)"
      content: "Rasterize qualquer formato de documento compatível para a imagem rasterizada, com formato de imagem e qualidade de compactação ajustáveis."

    # feature loop
    - icon: "font"
      title: "[Controlar fontes do documento](https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Python-via-.NET/blob/master/Examples/advanced_usage/rendering/common_rendering_options/replace_missing_font.py)"
      content: "Identifique as fontes usadas em um documento. Gerencie fontes ausentes substituindo‑as ou excluindo‑as da saída."

    # feature loop
    - icon: "convertpdf"
      title: "[Converter para PDF](https://docs.groupdocs.com/viewer/python-net/rendering-to-pdf/)"
      content: "Documentos de qualquer formato compatível podem ser facilmente convertidos e salvos em PDF com opções ajustáveis."

    # feature loop
    - icon: "transform"
      title: "[Aplicar transformações](https://docs.groupdocs.com/viewer/python-net/add-text-watermark/)"
      content: "O documento de saída pode ser transformado durante a renderização - as páginas podem ser giradas e/ou reorganizadas e uma marca d’água de texto pode ser colocada sobre elas."

    # feature loop
    - icon: "adjustment"
      title: "[Ajuste de saída HTML](https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Python-via-.NET/blob/master/Examples/basic_usage/render_document_to_html/render_to_html_with_embedded_resources.py)"
      content: "Os documentos HTML de saída, gerados pelo GroupDocs.Viewer, podem ser ajustados com muita precisão: é permitido salvar no fluxo ou arquivo, com recursos externos ou incorporados, retornos de chamada e assim por diante."

    # feature loop
    - icon: "complex"
      title: "[Suporte de estruturas de documentos complexas](https://docs.groupdocs.com/viewer/python-net/how-to-extract-and-save-attachments/)"
      content: "GroupDocs.Viewer suporta não apenas documentos únicos, mas também arquivos, que contêm internamente uma lista ou estrutura hierárquica de documentos, como mensagens de e-mail com anexos, arquivos ZIP com arquivos internos dentro de pastas, imagens TIFF de várias páginas e assim por diante."

    # feature loop
    - icon: "optimization"
      title: "Opções de otimização"
      content: "GroupDocs.Viewer contém um subsistema de cache ajustável, que pode acelerar o tempo de carregamento usando as versões em cache dos documentos. Além disso, um conjunto de diferentes opções para diferentes formatos permite excluir algumas partes ou aspectos desnecessários dos documentos da renderização (fontes, planilhas ocultas, anexos de e-mail) para otimizar o desempenho geral."

    # feature loop
    - icon: "passwordprotected"
      title: "[Suporte de documentos protegidos por senha](https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Python-via-.NET/blob/master/Examples/advanced_usage/loading/load_password_protected_document.py)"
      content: "GroupDocs.Viewer permite abrir documentos criptografados de diversos tipos: PDF, WordProcessing, Planilha, Apresentação e outros, especificando uma senha nas opções de carregamento."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Exemplos de código"
  description: "Alguns casos de uso de operações típicas do GroupDocs.Viewer para Python via .NET"
  items:
    # code sample loop
    - title: "Renderização de DOCX em HTML"
      content: |
        As propriedades da classe `HtmlViewOptions` permitem controlar o processo de conversão. Para obter mais informações, consulte [aqui](https://docs.groupdocs.com/viewer/python-net/rendering-to-html/). Por exemplo, você pode incorporar todos os recursos externos no arquivo HTML de saída, reduzir o tamanho do arquivo e otimizá-lo para impressão.
        {{< landing/code title="Python">}}
        ```python {style=abap}
        import groupdocs.viewer as gv
        import groupdocs.viewer.options as gvo 

        // Crie uma instância do visualizador
        with gv.Viewer("resume.docx") as viewer:
          // Defina as opções de saída HTML, um arquivo por página
          viewOptions = gvo.HtmlViewOptions.for_embedded_resources("page_{0}.html")
          // Renderização de PDF em HTML com recursos incorporados
          viewer.view(viewOptions)
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Exportação de PPTX em PDF"
      content: |
        Crie uma instância da classe `PdfViewOptions` e passe-a para o método `Viewer.view` para converter um arquivo PowerPoint PPTX em PDF. As propriedades da classe `PdfViewOptions` permitem controlar o processo de conversão. Por exemplo, você pode proteger o arquivo PDF de saída, reorganizar suas páginas e especificar a qualidade das imagens do documento. Consulte a [seguinte seção da documentação](https://docs.groupdocs.com/viewer/python-net/rendering-to-pdf/) para obter detalhes.
        {{< landing/code title="Python">}}
        ```python {style=abap}
        import groupdocs.viewer as gv
        import groupdocs.viewer.options as gvo  

        // Crie uma instância do visualizador
        with gv.Viewer("presentation.pptx") as viewer:
          // Defina as opções de saída de PDF (Set output PDF options)
          viewOptions = gvo.PdfViewOptions("presentation.pdf")
          // Exporte PPTX para PDF (Export PPTX to PDF)
          viewer.view(viewOptions)
        ```
        {{< /landing/code >}}
############################# Reviews ############################
# reviews:
# enable: true
# title: "Avaliações de produtos GroupDocs"
# description: "Não acredite apenas na nossa palavra. Veja o que outros desenvolvedores dizem sobre nossas APIs"

# items:
#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "Excelente atendimento e excelentes produtos. Eles foram extremamente úteis e receptivos durante o processo de implementação do GroupDocs.Viewer para .NET, não posso recomendá-los o suficiente."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "Depois de implementar e usar o GroupDocs.Viewer for .NET no projeto, parece estar funcionando muito bem. Eu testei com muitos documentos e até agora tudo bem. Tudo o que joguei nele é renderizado perfeitamente e parece tão bom quanto em um visualizador de PDF ou MS Word."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---
