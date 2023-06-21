---
############################# Static ############################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

lang: pt
product: "Viewer"
product_tag: "viewer"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "Java Document Viewer API para PDF Word Excel HTML Imagens e e-mails"
head_description: "Visualizador de documentos Java e API de renderização de arquivos. Adicione visualizador de PDF, visualizador de Word, visualizador de Excel, visualizador de imagens, visualizador de HTML, visualizador de e-mail em aplicativos Java."

############################# Header ############################
title: "API Java para renderizar e exibir documentos"
description: "Biblioteca do visualizador de documentos para desenvolver aplicativos Java que renderizam, visualizam e manipulam nativamente documentos multiformatos com suporte para mais de 170 formatos de arquivo."
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
              text: "Visão geral"

            # button loop
            - link: "#features"
              text: "Características"

            # button loop
            - link: "#support"
              text: "Apoiar"

            # button loop
            - link: "https://products.groupdocs.app/viewer/total"
              text: "Demonstração ao vivo"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/java"
              text: "Preços"

    right:
        link_download: "https://releases.groupdocs.com/viewer/java/"
        link_learn: "https://docs.groupdocs.com/viewer/java/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    content: |
      GroupDocs.Viewer for Java combina um poderoso conjunto de APIs de visualizador de documentos para exibir imagens e formatos de documentos em seus aplicativos Java sem a necessidade de instalar software adicional. Ele rasteriza nativamente os documentos e os converte em SVG+HTML+CSS para aprimorar a qualidade da visualização do documento enquanto fornece uma saída de texto verdadeiro e de alta fidelidade. Usando a API de renderização de documentos - visualize rapidamente PDF, HTML, XML, Microsoft Office Word, planilhas do Excel, apresentações do PowerPoint, e-mails do Outlook, diagramas do Visio, projetos, metarquivos, imagens e vários outros formatos de arquivo com facilidade e menos riscos de programação. Ele também pode exibir arquivos protegidos por senha e permitir a representação do documento como HTML, imagem ou formato PDF após a renderização. Nossa biblioteca de visualizador de arquivos é bastante personalizável, pois permite exibir o documento inteiro ou renderizá-lo parcialmente para acelerar o processo. Por meio do GroupDocs.Viewer para Java API, você pode visualizar páginas, intervalos de células específicos em uma planilha ou até mesmo renderizar uma camada de documento individual em formatos como PDF e CAD.  

      GroupDocs.Viewer para Java API permite renderizar documentos com/sem anotações ou comentários para formatos de arquivo suportados. Ele também permite adicionar diretórios de fontes personalizados e extrair informações básicas do documento, como tipo de arquivo, extensão, nome, contagem de páginas, etc.  

      GroupDocs.Viewer for Java é compatível com todas as versões de Java e oferece suporte a sistemas operacionais populares (Windows, Linux, macOS) capazes de executar Java runtime.
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          A seguir está uma visão geral do GroupDocs.Viewer para Java:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Visão geral"
          content: |
            * Exibir mais de 170 tipos de documentos 
            * Obter HTML, Imagem, Versão PDF 
            * Girar e reordenar 
            * Aplicar marca d'água 
            * Cache para Processo Rápido 
            * Adicionar fontes personalizadas 
            * Aplicar padrões de codificação 
            * Manipulador de dados de entrada personalizado 
            * Renderizar com Alterações de Faixa 
            * Renderizar como HTML responsivo 
            * Renderizar camadas de PDF e CAD 
            * Renderizar arquivos protegidos 
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Viewer para Java oferece suporte a todos os formatos populares de arquivos de documentos, incluindo: Microsoft Office, imagens, diagramas e muitos outros.

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
            - title: "Outros formatos"
              content: |
                * **Arquivos de layout de página:** PDF, TEX, XPS, OXPS
                * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG, OTG, FODP, FODG
                * **Valores separados por delimitador:** CSV, TSV
                * **Rede:** HTML, MHT, MHTML
                * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
                * **PostScript:** PS, EPS
                * **Arquivos:** ZIP, TAR, BZ2, GZ, RAR, RAR5
                * **Vários:** OBJ, EPUB, MOBI, DjVu, XML, VCF, VCARD, NUMBERS, NSF

        right:
          enable: true
          table:
            # table loop
            - title: "Imagens, gráficos e diagramas"
              content: |
                * **Imagens:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB
                * **Ícone do Windows:** ICO
                * **Gráficos vetoriais escalonáveis:** SVG, CDR, CMX, IGS, SVGZ
                * **JPEG2000:** JP2, J2C, J2K, JPC, JPF, JPX, JPM
                * **Adobe Photoshop:** PSD, PSB
                * **Linguagem de Comando da Impressora:** PCL
                * **Litografia estéreo (impressão 3D):** STL
                * **Classes da Fundação da Indústria:** IFC
                * **Imagiologia médica:** DICOM
                * **Documentos da plotter:** PLT, HPG
                * **Formatos da Web do Autodesk Design:** DWF, DWG
                * **Desenho AutoCAD:** DWT, IFC, STL, CF2
                * **DGN baseado em ISFF (V7):** DGN

            # table loop
            - title: "Linguagens de Programação Formatos"
              content: |
                * **Arquivos C/C++/C#:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
                * **Arquivos Java/JavaScript:** JAVA, JS, JSON, PROPERTIES
                * **Vários:** VB, PHP, SQL, PL, PY, PV, RB, RST, SASS, SCALA, SCM, SCRIPT, AS, AS3, ASM, BAT, CMAKE, CSS, DIFF, ERB, GROOVY, HAML, LESS, LOG, M, MAKE, MD, ML, MM, SH, SML, VIM, YAML

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Viewer for Java suporta os seguintes sistemas operacionais, estruturas e gerenciadores de pacotes:
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Sistemas operacionais"
              content: |
                * Microsoft Windows Server 2003 e posterior 
                * Microsoft Windows XP e posterior 
                * Microsoft Windows 10 e 11 
                * Linux (Ubuntu, OpenSUSE, CentOS e outros) 
                * Mac OS X 

            # table loop
            - icon: "fas fa-code"
              title: "Estruturas suportadas"
              content: |
                * J2SE 8.0 (1.8) ou superior (por exemplo, Java 17) 

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-cogs"
              title: "Ambientes de Desenvolvimento"
              content: |
                * NetBeans
                * IntelliJ IDEA
                * Eclipse

            # table loop
            - icon: "fas fa-tools"
              title: "Construir Ferramenta de Automação"
              content: |
                * Maven
                * Gradle

############################# Features ############################
features:
    enable: true
    title: "Recursos do GroupDocs.Viewer para Java"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "Visualizador para HTML, PDF, Imagens, Word, Excel e outros formatos de documento"

      # feature loop
      - icon: "fas fa-eye"
        content: "Renderize arquivos de desenhos do AutoCAD (DWG) para o formato SVG"

      # feature loop
      - icon: "fas fa-bolt"
        content: "Ajuste a cor de fundo do arquivo convertido"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "Rasterize e converta documentos em SVG, HTML e CSS"

      # feature loop
      - icon: "fas fa-code"
        content: "Obtenha representação de documentos em HTML, imagem ou PDF por meio de renderização"

      # feature loop
      - icon: "fas fa-cloud"
        content: "Versões em cache de documentos para acelerar o tempo de carregamento"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "Configurar diretórios de fontes personalizadas"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "Aplicar padrões de codificação a documentos do Word, Excel e e-mail"

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "Renderize documentos remotamente em FTP ou armazenamento em nuvem"

      # feature loop
      - icon: "fas fa-border-all"
        content: "Remover ou manter anotações e comentários durante a renderização"

      # feature loop
      - icon: "fas fa-wrench"
        content: "Renderizar páginas do documento como páginas HTML separadas"

      # feature loop
      - icon: "fas fa-columns"
        content: "Renderizar slides e páginas ocultos e aplicar reordenar página ao documento renderizado"

      # feature loop
      - icon: "fas fa-file-word"
        content: "Renderizar intervalo de páginas, páginas específicas ou todas as páginas em HTML"

      # feature loop
      - icon: "fas fa-envelope"
        content: "Renderizar ou ocultar comentários do documento"

      # feature loop
      - icon: "fas fa-print"
        content: "Crie HTML responsivo para alguns formatos de documento por meio de renderização"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "Reduza o tamanho do arquivo resultante do HTML renderizado excluindo fontes"

      # feature loop
      - icon: "fas fa-lock"
        content: "Remova comentários, espaços em branco extras, etc., para minimizar a saída HTML e CSS"

      # feature loop
      - icon: "fas fa-file-code"
        content: "Use as coordenadas do documento de origem para ler o texto contido"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "Mostrar/ocultar borda da célula em planilhas Excel da saída renderizada"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "Renderize um número específico de linhas de cada página em uma planilha do Excel"

      # feature loop
      - icon: "fas fa-heading"
        content: "Modelo de renderização e todos os layouts não vazios ou um layout específico de um arquivo CAD"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "Renderize os itens nos arquivos de dados do Outlook (OST/PST) como PDF"

      # feature loop
      - icon: "fas fa-cube"
        content: "Renderização de ladrilhos ou renderização por coordenadas de documentos CAD como imagem, HTML ou PDF"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "Definir restrições de impressão ao renderizar para PDF"

    more_feature:
      # more_feature_loop
      - title: "API eficiente e confiável para visualização de documentos"
        content: |
          GroupDocs.Viewer para Java API pode ser usado para visualizar, renderizar e exibir documentos de mais de 150 formatos de arquivo diferentes. Isso é feito de forma confiável e eficiente, mantendo o conteúdo e a estrutura do documento intactos. O exemplo a seguir mostra o nível de facilidade com que GroupDocs.Viewer para Java API renderiza um arquivo DOCX como um arquivo de imagem usando Java:

          ```java
          // Initialize Viewer
          Viewer viewer = new Viewer("invoice.docx");
          // Create view options
          PdfViewOptions viewOptions = new PdfViewOptions();
          // Convert file to PDF and check the output in the current directory
          viewer.view(viewOptions);
          ```
      # more_feature_loop
      - title: "Executar transformações durante a renderização de documentos"
        content: "GroupDocs.Viewer para Java API oferece várias opções de transformação a serem aplicadas no documento renderizado para uma visualização e exibição mais personalizadas. Você pode girar as páginas fornecendo o ângulo. Você pode definir a ordem das páginas renderizadas. Aplique um texto específico como marca d'água a páginas ou imagens renderizadas. Por meio do GroupDocs.Viewer para Java API, você também pode adicionar fontes personalizadas ao documento que está sendo renderizado."

      # more_feature_loop
      - title: "Trabalhando com anexos de e-mail"
        content: "GroupDocs.Viewer para Java API permite que você busque anexos específicos ou todos de um e-mail. Depois de obter os anexos de e-mail necessários, você pode renderizar esses arquivos anexados em imagens ou HTML."

############################# Support ############################
support:
    enable: true

############################# Solutions ##########################
solutions:
    enable: true
    title: "GroupDocs.Viewer oferece APIs de visualização de documentos para outros ambientes de desenvolvimento populares"

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