---
############################# Static ##########################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: pt
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
    # supported_platforms loop
    - title: "Python"
      tag: "python-net"

############################# Head ############################
head_title: "API do visualizador de documentos .NET, renderização de diagrama HTML de imagem em PDF Word Excel"
head_description: "Visualizador de arquivos C# ASP.NET e API de renderização. Adicione recursos de visualizador de PDF, visualizador de Word, visualizador de Excel, visualizador de imagens, visualizador de HTML e visualizador de e-mail em aplicativos .NET."

############################# Header ##########################
title: "Renderizar e exibir documentos<br>usando a API .NET"
description: "API de visualizador poderosa para renderizar mais de 180 formatos de documentos em PDF, HTML e imagens com opções versáteis de configuração."
words:
  for: "for"

actions:
  viewer_demo: true
  viewer_demo_file_name: "quarterly-report.docx"
  main: "Download grátis do NuGet"
  main_link: "https://www.nuget.org/packages/GroupDocs.Viewer"
  alt: "Licenciamento"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/net"
  title: "Pronto para começar?"
  description: "Experimente os recursos do GroupDocs.Viewer gratuitamente ou solicite uma licença"

release:
  title: "Versão {0} lançada"
  notes: "Veja o que é novo"
  downloads: "Transferências"
  link: "https://releases.groupdocs.com/viewer/net/release-notes/latest/"

code:
  title: "Renderizar arquivos PDF em C#"
  more: "Mais exemplos"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
  install: "dotnet add package GroupDocs.Viewer"
  content: |
    ```csharp {style=abap}   
    // Carregue o arquivo PDF de origem
    using (var viewer = new Viewer("resume.pdf"))
    {
        // Defina opções de saída HTML, um arquivo por página
        var viewOptions = 
        HtmlViewOptions.ForEmbeddedResources("page{0}.html");
        
        // Renderize PDF em HTML com recursos incorporados        
        viewer.View(viewOptions);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "Visão geral do GroupDocs.Viewer"
  description: "API para renderizar, exibir, converter documentos, slides, diagramas e muitos outros tipos de documentos em aplicativos .NET"
  features:
    # feature loop
    - title: "Visualize documentos de forma eficiente e confiável"
      content: "Com a API GroupDocs.Viewer você pode renderizar documentos de quaisquer formatos suportados para [HTML](https://docs.groupdocs.com/viewer/net/rendering-to-html/), [JPEG, PNG](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/), e [PDF](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/) usando opções flexíveis e avançadas, preservando o conteúdo e a estrutura do documento. O GroupDocs.Viewer suporta .NET Framework 4.6.2 e .NET 6.0 e funciona nos sistemas Windows e Linux."

    # feature loop
    - title: "Os formatos de arquivos e documentos mais populares são suportados"
      content: "A API renderiza mais de 180 formatos de arquivos e documentos, incluindo [Word](https://docs.groupdocs.com/viewer/net/render-word-documents/), [Excel](https://blog.groupdocs.com/viewer/working-with-spreadsheets/), [PDF](https://docs.groupdocs.com/viewer/net/render-pdf-documents/), [PowerPoint](https://blog.groupdocs.com/viewer/view-powerpoint-presentations/), a família OpenDocument, arquivos compactados, imagens raster e vetoriais, e‑Books, linguagens de programação e marcações, além de arquivos criptografados protegidos por senha."

    # feature loop
    - title: "Saída personalizável"
      content: "GroupDocs.Viewer permite não apenas renderizar o documento, mas também controlar como exatamente, quais partes do documento devem ser renderizadas ou agora, como devem ser renderizadas e aplicar diferentes transformações à saída renderizada."

    # feature loop
    - title: "IU para ASP.NET Core"
      content: "Fornecemos um pacote de UI de código aberto para ASP.NET Core que pode ser adicionado ao seu projeto em alguns minutos. O pacote Viewer.UI contém uma interface da web baseada em Angular e oferece um conjunto de APIs úteis e provedores de armazenamento de dados."

############################# Platforms ############################
platforms:
  enable: true
  title: "Suporte de plataformas"
  description: "GroupDocs.Viewer for .NET suporta os seguintes sistemas operacionais, estruturas e gerenciadores de pacotes"
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
  packages:
    # packages loop
    - title: "Pacote específico do Windows"
      content: |
        * Suporta .NET Framework 4.6.2+ e .NET 6.0
        * O suporte mais abrangente para formatos de arquivo
        * Depende de System.Drawing e System.Drawing.Common 
      action: "Baixar NuGet"
      action_link: "https://www.nuget.org/packages/GroupDocs.Viewer"
    # packages loop
    - title: "Pacote multiplataforma" 
      content: |
        * Suporta .NET 6.0 e versões superiores 
        * Suporte limitado a formatos de arquivo 
        * Funciona em Windows, Linux e macOS 
      action: "Baixar NuGet" 
      action_link: "https://www.nuget.org/packages/GroupDocs.Viewer.CrossPlatform" 

############################# File formats ############################
formats:
  enable: true
  title: "Formatos de arquivo suportados"
  description: |
    GroupDocs.Viewer for .NET oferece suporte a operações com os seguintes [formatos de arquivo](https://docs.groupdocs.com/viewer/net/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office, OpenDocument e formatos de texto
        * **Word:** DOC, DOCX, DOCM, DOT, DOTX, DOTM, RTF, TXT
        * **Excel:** XLS, XLSX, XLSM, XLSB, XLTM, XLT, XLTM, XLTX
        * **PowerPoint:** PPT, PPTX, PPS, PPSX, PPSM, POT, POTM, POTX, PPTM        
        * **Project:** MPP, MPT, MPX {{< landing/tooltip icon="windows" title="Suportado por pacote específico do Windows" >}}
        * **Outlook:** MSG, EML, EMLX, PST, OST
        * **OneNote:** ONE {{< landing/tooltip icon="windows" title="Suportado por pacote específico do Windows" >}}
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
        * **Adobe Photoshop:** PSD, PSB {{< landing/tooltip icon="windows" title="Suportado por pacote específico do Windows" >}}       
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
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM {{< landing/tooltip icon="windows" title="Suportado por pacote específico do Windows" >}}
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
      title: "[Ver documentos em HTML](https://blog.groupdocs.com/viewer/view-word-documents-as-html-responsive-page-using-csharp/)"
      content: "Converta documentos de qualquer tipo em um documento HTML com CSS e SVG, que pode ser exibido em qualquer navegador moderno."

    # feature loop
    - icon: "rasterize"
      title: "[Rasterizar documentos](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/)"
      content: "Rasterize qualquer formato de documento compatível para a imagem rasterizada, com formato de imagem e qualidade de compactação ajustáveis."

    # feature loop
    - icon: "font"
      title: "[Controlar fontes do documento](https://blog.groupdocs.com/viewer/working-with-fonts/)"
      content: "Identifique as fontes usadas em um documento. Gerencie fontes ausentes substituindo‑as ou excluindo‑as da saída."

    # feature loop
    - icon: "convertpdf"
      title: "[Converter para PDF](https://blog.groupdocs.com/viewer/rendering-documents-as-pdf/)"
      content: "Documentos de qualquer formato compatível podem ser facilmente convertidos e salvos em PDF com opções ajustáveis."

    # feature loop
    - icon: "transform"
      title: "[Aplicar transformações](https://blog.groupdocs.com/viewer/protect-your-documents-with-watermarks-in-groupdocs-viewer-for-dot-net/)"
      content: "O documento de saída pode ser transformado durante a renderização - as páginas podem ser giradas e/ou reorganizadas e uma marca d’água de texto pode ser colocada sobre elas."

    # feature loop
    - icon: "adjustment"
      title: "[Ajuste de saída HTML](https://blog.groupdocs.com/viewer/render-word-documents-as-clean-html-using-csharp/)"
      content: "Os documentos HTML de saída, gerados pelo GroupDocs.Viewer, podem ser ajustados com muita precisão: é permitido salvar no fluxo ou arquivo, com recursos externos ou incorporados, retornos de chamada e assim por diante."

    # feature loop
    - icon: "complex"
      title: "[Suporte de estruturas de documentos complexas](https://blog.groupdocs.com/viewer/process-microsoft-outlook-email-attachments-in-a-.net-viewer-application/)"
      content: "GroupDocs.Viewer suporta não apenas documentos únicos, mas também arquivos, que contêm internamente uma lista ou estrutura hierárquica de documentos, como mensagens de e-mail com anexos, arquivos ZIP com arquivos internos dentro de pastas, imagens TIFF de várias páginas e assim por diante."

    # feature loop
    - icon: "optimization"
      title: "[Opções de otimização](https://blog.groupdocs.com/viewer/exclude-specific-fonts-from-output-html-using-groupdocs.viewer-for-.net-18.10/)"
      content: "GroupDocs.Viewer contém um subsistema de cache ajustável, que pode acelerar o tempo de carregamento usando as versões em cache dos documentos. Além disso, um conjunto de diferentes opções para diferentes formatos permite excluir algumas partes ou aspectos desnecessários dos documentos da renderização (fontes, planilhas ocultas, anexos de e-mail) para otimizar o desempenho geral."

    # feature loop
    - icon: "passwordprotected"
      title: "[Suporte de documentos protegidos por senha](https://docs.groupdocs.com/viewer/net/load-password-protected-document/)"
      content: "GroupDocs.Viewer permite abrir documentos criptografados de diversos tipos: PDF, WordProcessing, Planilha, Apresentação e outros, especificando uma senha nas opções de carregamento."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Amostras de código"
  description: "Alguns casos de uso de operações típicas do GroupDocs.Viewer para .NET"
  items:
    # code sample loop
    - title: "Renderizar DOCX para HTML"
      content: |
        As propriedades da classe [HtmlViewOptions](https://reference.groupdocs.com/viewer/net/groupdocs.viewer.options/htmlviewoptions/) permitem que você controle o processo de conversão, mais sobre isso [aqui](https://docs.groupdocs.com/viewer/net/rendering-to-html/). Por exemplo, você pode incorporar todos os recursos externos no arquivo HTML de saída, reduzir o arquivo de saída e otimizá-lo para impressão.
        {{< landing/code title="C#">}}
        ```csharp {style=abap}
        using GroupDocs.Viewer;
        using GroupDocs.Viewer.Options;
        
        // Instanciar visualizador
        using (Viewer viewer = new Viewer("resume.docx"))
        {
            // Definir opções de HTML de saída
            HtmlViewOptions options = HtmlViewOptions.ForEmbeddedResources();
            
            // Renderize DOCX para HTML com recursos incorporados
            viewer.View(options);
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Exportar PPTX para PDF"
      content: |
        Crie uma instância de classe [PdfViewOptions](https://reference.groupdocs.com/viewer/net/groupdocs.viewer.options/pdfviewoptions/) e passe-a para o [Viewer.View](https://reference.groupdocs.com/viewer/net/groupdocs.viewer/viewer/view/#view) para converter um arquivo PowerPoint PPTX em PDF. As propriedades da classe PdfViewOptions permitem controlar o processo de conversão. Por exemplo, você pode proteger o arquivo PDF de saída, reordenar suas páginas e especificar a qualidade das imagens do documento. Consulte a [seção de documentação a seguir](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/) para obter detalhes.
        {{< landing/code title="C#">}}
        ```csharp {style=abap}   
        using GroupDocs.Viewer;
        using GroupDocs.Viewer.Options;
        
        using (var viewer = new Viewer("presentation.pptx"))
        {
            // Definir opções de saída de PDF       
            var viewOptions = new PdfViewOptions("presentation.pdf");
            
            // Exportar PPTX para PDF       
            viewer.View(viewOptions);
        }
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