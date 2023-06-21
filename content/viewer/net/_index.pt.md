---
############################# Static ##########################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

lang: pt
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: "API do visualizador de documentos .NET, Renderizar PDF Word Excel Imagem HTML Diagrama"
head_description: "Visualizador de arquivos C# ASP.NET e API de renderização. Adicione visualizador de PDF, visualizador de Word, visualizador de Excel, visualizador de imagens, visualizador de HTML, recursos de visualizador de e-mail em aplicativos .NET."

############################# Header ##########################
title: "Renderizar e exibir documentos via API .NET"
description: "API do visualizador de documentos .NET para renderizar mais de 190 formatos de documentos em PDF, HTML e imagens com poderosas opções de configuração."
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Download Free Trial"
    link: "https://downloads.groupdocs.com/viewer/net"

############################# SubMenu #########################
submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Viewer for .NET"
        image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-viewer-net.png"
        product: "GroupDocs.Viewer"
        platform: ".NET"

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
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Preços"

    right:
        link_download: "https://releases.groupdocs.com/viewer/net/"
        link_learn: "https://docs.groupdocs.com/viewer/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    content: |
      GroupDocs.Viewer para APIs .NET ajudam você a criar aplicativos poderosos em C#, ASP.NET e outras tecnologias baseadas em .NET, que podem renderizar e exibir documentos e imagens de mais de 190 formatos de arquivo sem instalar nenhum software externo. A biblioteca do visualizador de arquivos rasteriza os documentos e os converte em SVG+HTML+CSS para otimizar a experiência geral de renderização de documentos para visualização de documentos comerciais, imagens, arquivos de texto, diagramas, gráficos, anexos de e-mail e arquivos PDF com velocidade, texto verdadeiro e alta fidelidade dentro de seus aplicativos. Você tem a opção de adicionar funcionalidades de visualização e leitura de documentos em seus aplicativos para exibir o documento inteiro, documento parcial, página/intervalo de células específico, camada de documento individual, com ou sem anotações e comentários para os formatos de arquivo suportados.
       
      O GroupDocs.Viewer para .NET armazena em cache a saída dos documentos renderizados no disco local por padrão. Qualquer tipo de armazenamento em cache externo também é suportado pela implementação de interfaces apropriadas – Amazon S3, Dropbox, Google Drive, Windows Azure, Redis ou qualquer outro.
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          A seguir está uma visão geral do GroupDocs.Viewer para .NET:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Visão geral"
          content: |
            * Exibir mais de 190 tipos de documentos 
            * Obtenha um arquivo em formato HTML, Imagem, PDF 
            * Girar e reordenar 
            * Aplicar marca d'água 
            * Cache para Processo Rápido 
            * Adicionar fontes personalizadas 
            * Aplicar padrões de codificação 
            * Manipulador de dados de entrada personalizado 
            * Renderizar com Alterações de Faixa 
            * Renderizar como HTML responsivo 
            * Renderizar camadas de PDF e CAD 
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Viewer para .NET oferece suporte à exibição de todos os formatos populares de arquivo de documento. Com apenas algumas linhas de código, adicione visualizador de PDF, Microsoft Office Word, planilha do Excel, imagem, HTML, e-mail do Outlook, OneNote, projeto e recursos de visualização de gráficos em seus aplicativos .NET.

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
            - title: "Other Formats"
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
          GroupDocs.Viewer para .NET suporta os seguintes sistemas operacionais, estruturas e gerenciadores de pacotes:
        
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
                * .NET Framework 2.0 ou superior 
                * .NET Núcleo 3.1 
                * .NET 5 ou superior 

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-box"
              title: "Gerenciador de pacotes"
              content: |
                * NuGet

            # table loop
            - icon: "fas fa-tools"
              title: "Ambientes de Desenvolvimento"
              content: |
                * Microsoft Visual Studio
                * Visual Studio Code
                * .NET CLI

############################# Features ############################
features:
    enable: true
    title: "Recursos do GroupDocs.Viewer para .NET"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "Rasterizar documentos e convertê-los em SVG, HTML e CSS"

      # feature loop
      - icon: "fas fa-eye"
        content: "Converta texto em HTML e renderize documentos para obter representação em HTML, imagem ou PDF"

      # feature loop
      - icon: "fas fa-bolt"
        content: "Tempo de carregamento mais rápido usando versões em cache de documentos"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "Converta apresentações com formas e texto com efeitos 3D"

      # feature loop
      - icon: "fas fa-code"
        content: "Codifique documentos do Word, Excel e e-mail para o padrão de codificação desejado"

      # feature loop
      - icon: "fas fa-cloud"
        content: "Renderize documentos localizados em FTP ou locais de armazenamento em nuvem"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "Excluindo fontes ao renderizar para HTML para reduzir o tamanho do arquivo resultante"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "Reduza a saída de CSS e HTML removendo comentários, espaços em branco extras, etc."

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "Leia o texto contido em um documento de origem por meio de suas coordenadas"

      # feature loop
      - icon: "fas fa-border-all"
        content: "Mostrar/ocultar as linhas de grade das planilhas do Excel na representação de saída"

      # feature loop
      - icon: "fas fa-wrench"
        content: "Especifique o número de linhas em uma planilha do Excel a serem renderizadas em cada página"

      # feature loop
      - icon: "fas fa-columns"
        content: "Ignorar colunas vazias ao renderizar documentos de planilha"

      # feature loop
      - icon: "fas fa-file-word"
        content: "Renderize documentos do Word em páginas HTML, imagens ou PDF, com alterações de controle"

      # feature loop
      - icon: "fas fa-envelope"
        content: "Renderize anexos de e-mail como arquivos originais, imagens ou em representação HTML"

      # feature loop
      - icon: "fas fa-print"
        content: "Definir restrições de impressão em documentos PDF"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "Renderizar conteúdo/arquivos contidos em arquivos ZIP como anexos"

      # feature loop
      - icon: "fas fa-lock"
        content: "Obtenha anexos de documentos protegidos por senha"

      # feature loop
      - icon: "fas fa-file-code"
        content: "Renderizar formatos de arquivo de linguagens de programação como texto sem formatação"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "Ajustar cores de fundo ao visualizar desenhos CAD"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "Visualize documentos do Excel e converta em PDF, HTML, JPG e PNG"

      # feature loop
      - icon: "fas fa-heading"
        content: "Obter nomes de planilhas do arquivo do Excel - exibir cabeçalhos de colunas e números de linhas da planilha"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "Visualize e converta documentos do Microsoft Project com notas"

      # feature loop
      - icon: "fas fa-cube"
        content: "Converta desenhos CAD em SVG para uma melhor experiência de visualização e zoom"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "Escolha renderizar figuras do Visio sem esquema"

    more_feature:
      # more_feature_loop
      - title: "Visualize documentos de forma eficiente e confiável"
        content: |
          Usando a API GroupDocs.Viewer, você pode exibir mais de 190 formatos de documentos de forma eficiente e confiável com o conteúdo e a integridade da estrutura do documento intacta. O exemplo de código a seguir mostra como é fácil visualizar a representação HTML de um documento DOCX:

          ```cs
          // Instantiate viewer
          using (Viewer viewer = new Viewer("invoice.docx"))
          {
              // Set view options
              HtmlViewOptions options = HtmlViewOptions.ForEmbeddedResources();
              // Convert file to HTML with embedded resources
              viewer.View(options);
          }
          ```
      # more_feature_loop
      - title: "Aplicar transformação à saída renderizada"
        content: "Você pode executar várias transformações no documento de saída renderizado usando GroupDocs.Viewer para .NET API. Essas opções de transformação fornecem controle sobre a maneira como você apresenta a saída renderizada para exibição. As transformações disponíveis são opção de rotação de página, opção de reordenar página e aplicação de marca d'água de texto."

      # more_feature_loop
      - title: "Trabalhando com arquivos de dados do Outlook"
        content: "GroupDocs.Viewer para .NET API pode processar os itens em arquivos de dados do Outlook (OST/PST) como PDF, HTML e arquivos de imagem. Nossa API do visualizador também tem a capacidade de obter a lista de pastas contidas nos arquivos de dados do Outlook. Usando GroupDocs.Viewer para API .NET, você pode especificar a pasta a ser renderizada a partir dos Arquivos de Dados do Outlook. Da mesma forma, você também pode obter mensagens de e-mail contidas nos formatos OST/PST como anexos. GroupDocs.Viewer para .NET também permite filtrar mensagens de formatos OST/PST com base no assunto, conteúdo ou remetente."

      # more_feature_loop
      - title: "Trabalhando com documentos CAD"
        content: "GroupDocs.Viewer para .NET API pode renderizar modelos e todos os layouts não vazios ou renderizar um layout específico de um arquivo CAD. GroupDocs.Viewer para .NET API também suporta renderização lado a lado ou renderização por coordenadas de documentos CAD em imagem, HTML ou PDF. Você também pode obter status de camada para documentos CAD."

############################# Testimonials ###############################
testimonials:
  enable: true

  testimonial:
    # testimonial item loop
    - name: "Margot Baill"
      designation: "Diretor de desenvolvimento de produtos na Hireology"
      content: "A integração do GroupDocs.Viewer para Cloud API foi simples com seu fantástico Ruby SDK. Não há muitas empresas por aí que estejam dispostas a trabalhar conosco no que queremos. É uma ótima parceria."

    # testimonial item loop
    - name: "Mats Oustad"
      designation: "Consultor Sênior/Sócio na Novanet AS"
      content: "Depois de implementar e usar o GroupDocs.Viewer for .NET no projeto parece estar funcionando muito bem. Eu testei com muitos documentos e até agora tudo bem. Tudo o que joguei nele renderiza bem e parece tão bom quanto em um visualizador de PDF ou MS Word."
              
    # testimonial item loop
    - name: "Martin Lasarga"
      designation: "Gerente de Produto na Axentria ECM by G.S.I."
      content: "Excelente atendimento e excelentes produtos. Eles foram extremamente úteis e receptivos durante o processo de implementação do GroupDocs.Viewer para .NET, não podemos recomendá-los o suficiente."

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Viewer oferece APIs de visualização de documentos para outros ambientes de desenvolvimento populares"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Viewer for Java"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-viewer-java.png"
          product: "GroupDocs.Viewer"
          platform: "Java"
          link: "/viewer/java/"

############################# Back to top ###############################
back_to_top:
  enable: true
---
