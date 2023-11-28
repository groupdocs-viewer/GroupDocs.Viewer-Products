---
############################# Static ############################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: pt
product: "Viewer"
product_tag: "viewer"
platform: "Node.js via Java"
platform_tag: "nodejs-java"

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
head_title: "API do visualizador de documentos Node.js para imagens e e-mails HTML do Word Excel em PDF"
head_description: "Visualizador de documentos Node.js e API de renderização de arquivos. Adicione visualizador de PDF, visualizador de Word, visualizador de Excel, visualizador de imagens, visualizador de HTML, visualizador de e-mail em aplicativos JavaScript."

############################# Header ############################
title: "API Node.js para renderizar e exibir documentos"
description: "Biblioteca do Document Viewer para desenvolver aplicativos JavaScript que renderizam, visualizam e manipulam nativamente documentos multiformatos que suportam mais de 180 formatos de arquivo."
words:
  for: "for"

actions:
  main: "Baixar NPM grátis"
  main_link: "https://www.npmjs.com/package/@groupdocs/groupdocs.viewer"
  alt: "Licenciamento"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/nodejs-java"
  title: "Pronto para começar?"
  description: "Experimente os recursos do GroupDocs.Viewer gratuitamente ou solicite uma licença"

release:
  title: "Versão {0} lançada"
  notes: "Veja o que é novo"
  downloads: "Transferências"
  link: "https://releases.groupdocs.com/viewer/nodejs-java/release-notes/latest/"

code:
  title: "Renderizar arquivos PDF em JavaScript"
  more: "Mais exemplos"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Node.js-via-Java"
  install: "npm i @groupdocs/groupdocs.viewer"
  content: |
    ```javascript {style=abap}   
    //Set output HTML options, one file per page
    const viewOptions = HtmlViewOptions.forEmbeddedResources()

    // Instantiate Viewer
    const viewer = new Viewer("resume.pdf")

    // Render PDF to HTML with embedded resources
    viewer.view(viewOptions)
    viewer.close()
    ```
############################# Overview ############################
overview:
  enable: true
  title: "Visão geral do GroupDocs.Viewer"
  description: "API para renderizar, exibir, converter documentos, slides, diagramas e muitos outros tipos de documentos em aplicativos Node.js."
  features:
    # feature loop
    - title: "Visualize documentos de forma eficiente e confiável"
      content: "Com a API GroupDocs.Viewer, você pode renderizar com eficiência documentos de qualquer formato compatível para HTML, JPEG, PNG e PDF com opções flexíveis e poderosas, mantendo a integridade do conteúdo e da estrutura do documento. GroupDocs.Viewer para Node.js funciona em plataformas Windows e Linux."

    # feature loop
    - title: "Os formatos de arquivos e documentos mais populares são suportados"
      content: "Oferecemos suporte à renderização dos 180 formatos de arquivos e documentos mais populares, que incluem Word, Excel, PDF, PowerPoint, família de formatos OpenDocument, arquivos, imagens raster e vetoriais, e-books, linguagens de programação e marcações e muitos outros tipos de arquivos, incluindo arquivos criptografados. arquivos com proteção por senha."

    # feature loop
    - title: "Saída personalizável"
      content: "GroupDocs.Viewer permite não apenas renderizar o documento, mas também controlar como exatamente, quais partes do documento devem ser renderizadas ou agora, como devem ser renderizadas e aplicar diferentes transformações à saída renderizada."

############################# Platforms ############################
platforms:
  enable: true
  title: "Independência de plataforma"
  description: "GroupDocs.Viewer para Node.js oferece suporte aos seguintes sistemas operacionais, estruturas e gerenciadores de pacotes"
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
    - title: "NPM"
      image: "npm"

############################# File formats ############################
formats:
  enable: true
  title: "Formatos de arquivo suportados"
  description: |
    GroupDocs.Viewer para Node.js via Java oferece suporte a operações com os seguintes [formatos de arquivo](https://docs.groupdocs.com/viewer/nodejs-java/supported-document-formats/).
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
      title: "Ver documentos em HTML"
      content: "Converta documentos de qualquer tipo em um documento HTML com CSS e SVG, que pode ser exibido em qualquer navegador moderno."

    # feature loop
    - icon: "rasterize"
      title: "Rasterizar documentos"
      content: "Rasterize qualquer formato de documento compatível para a imagem rasterizada, com formato de imagem e qualidade de compactação ajustáveis."

    # feature loop
    - icon: "sourcecode"
      title: "Renderizar e destacar códigos de programação"
      content: "Suporte para todas as linguagens populares de programação, script e marcação, com capacidade de analisar e destacar sua sintaxe."

    # feature loop
    - icon: "convertpdf"
      title: "Converter para PDF"
      content: "Documentos de qualquer formato compatível podem ser facilmente convertidos e salvos em PDF com opções ajustáveis."

    # feature loop
    - icon: "transform"
      title: "Aplicar transformações"
      content: "O documento de saída pode ser transformado durante a renderização - as páginas podem ser giradas e/ou reorganizadas e uma marca d’água de texto pode ser colocada sobre elas."

    # feature loop
    - icon: "adjustment"
      title: "Ajuste de saída HTML"
      content: "Os documentos HTML de saída, gerados pelo GroupDocs.Viewer, podem ser ajustados com muita precisão: é permitido salvar no fluxo ou arquivo, com recursos externos ou incorporados, retornos de chamada e assim por diante."

    # feature loop
    - icon: "complex"
      title: "Suporte de estruturas de documentos complexas"
      content: "GroupDocs.Viewer suporta não apenas documentos únicos, mas também arquivos, que contêm internamente uma lista ou estrutura hierárquica de documentos, como mensagens de e-mail com anexos, arquivos ZIP com arquivos internos dentro de pastas, imagens TIFF de várias páginas e assim por diante."

    # feature loop
    - icon: "optimization"
      title: "Opções de otimização"
      content: "GroupDocs.Viewer contém um subsistema de cache ajustável, que pode acelerar o tempo de carregamento usando as versões em cache dos documentos. Além disso, um conjunto de diferentes opções para diferentes formatos permite excluir algumas partes ou aspectos desnecessários dos documentos da renderização (fontes, planilhas ocultas, anexos de e-mail) para otimizar o desempenho geral."

    # feature loop
    - icon: "passwordprotected"
      title: "Suporte de documentos protegidos por senha"
      content: "GroupDocs.Viewer permite abrir documentos criptografados de diversos tipos: PDF, WordProcessing, Planilha, Apresentação e outros, especificando uma senha nas opções de carregamento."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Amostras de código"
  description: "Alguns casos de uso de GroupDocs.Viewer típico para Node.js por meio de operações Java"
  items:
    # code sample loop
    - title: "Renderizar DOCX para HTML"
      content: |
        As propriedades da classe `HtmlViewOptions` permitem que você controle o processo de conversão, mais sobre isso [aqui](https://docs.groupdocs.com/viewer/nodejs-java/rendering-to-html/). Por exemplo, você pode incorporar todos os recursos externos no arquivo HTML de saída, reduzir o arquivo de saída e otimizá-lo para impressão.
        {{< landing/code title="JavaScript">}}
        ```javascript {style=abap}
        import { Viewer, HtmlViewOptions } from '@groupdocs/groupdocs.viewer'

        //Set output HTML options, one file per page
        const viewOptions = HtmlViewOptions.forEmbeddedResources()

        // Instantiate Viewer
        const viewer = new Viewer("resume.docx")

        // Render PDF to HTML with embedded resources
        viewer.view(viewOptions)
        viewer.close()
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Exportar PPTX para PDF"
      content: |
        Crie uma instância da classe `PdfViewOptions` e passe-a para o método `Viewer.view` para converter um arquivo PowerPoint PPTX em PDF. As propriedades da classe `PdfViewOptions` permitem controlar o processo de conversão. Por exemplo, você pode proteger o arquivo PDF de saída, reordenar suas páginas e especificar a qualidade das imagens do documento. Consulte a [seção de documentação a seguir](https://docs.groupdocs.com/viewer/nodejs-java/rendering-to-pdf/) para obter detalhes.
        {{< landing/code title="JavaScript">}}
        ```javascript {style=abap}   
        import { Viewer, PdfViewOptions } from '@groupdocs/groupdocs.viewer'

        //Set output PDF options
        const viewOptions = new PdfViewOptions("presentation.pdf")

        // Instantiate Viewer
        const viewer = new Viewer("presentation.pptx")

        // Render PDF to HTML with embedded resources
        viewer.view(viewOptions)
        viewer.close()
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
