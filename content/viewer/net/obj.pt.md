---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: pt

############################# Head #############################
head_title: ".NET OBJ API do visualizador - Ler, visualizar, renderizar em C# VB.NET"
head_description: "API do visualizador de documentos .NET para ler, renderizar e exibir OBJ em qualquer tipo de aplicativo C#, ASP.NET, VB.NET e .NET Core."

############################# Header ############################
title: "OBJ Visualizador de arquivos para aplicativos C# .NET" 
description: "API do visualizador de documentos .NET para ler, renderizar e exibir o arquivo OBJ em qualquer tipo de aplicativo C#, ASP.NET, VB.NET e .NET Core. Visualize os arquivos renderizados com formatação e layout reais em HTML5, PDF ou como uma imagem usando algumas linhas do código." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Baixar Teste Gratuito"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Sobre GroupDocs.Viewer para API .NET" 
    content: |
        Comece a visualizar mais de 190 formatos de documentos populares em seus aplicativos .NET usando GroupDocs.Viewer para APIs .NET adicionando algumas linhas de código. Os desenvolvedores podem facilmente exibir PDF, Processamento de Texto, Planilha do Excel, Apresentação, Visio, Projeto, Outlook e muitos outros formatos de documento populares nos modos HTML5, imagem ou PDF. A renderização do documento é rápida, idêntica ao arquivo fonte original e não requer a instalação de software adicional ou qualquer outra biblioteca externa.

############################# SubMenu ############################
submenu:
    enable: true

    left:
        img_alt: "GroupDocs.Viewer for .NET"
        image: "https://cms.admin.containerize.com/templates/groupdocs/images/product-logos/90x90-noborder/groupdocs-viewer-net.png"
        product: "GroupDocs.Viewer"
        platform: ".NET"

    middle:
        button:

            # button loop
            - link: "https://apireference.groupdocs.com/viewer/net"
              text: "Referência da API"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Exemplos de código"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Demonstrações ao vivo"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Preços"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "Etapas para renderizar o arquivo OBJ em C#" 
    content_left: |
        Com [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/) você pode renderizar OBJ para HTML, JPEG, PNG ou PDF em algumas etapas.

        * Instale [GroupDocs.Viewer para .NET](https://www.nuget.org/packages/groupdocs.viewer) usando seu gerenciador de pacotes favorito. 
        * Crie uma instância da classe Viewer e carregue o arquivo OBJ com o caminho completo. 
        * Defina as opções para renderizar o arquivo OBJ em formato HTML, PNG, JPEG ou PDF. 
        * Renderize o arquivo e verifique a saída no diretório atual. 
        
    title_right: "Requisitos de sistema" 
    content_right: |
        As APIs do GroupDocs.Viewer para .NET são suportadas em todas as principais plataformas e sistemas operacionais. Antes de executar o código abaixo, certifique-se de ter os seguintes pré-requisitos instalados em seu sistema.

        * Sistemas Operacionais: Microsoft Windows, Linux, MacOS 
        * Ambientes de desenvolvimento: Microsoft Visual Studio, Visual Studio Code, .NET CLI 
        * Estruturas: .NET Framework, .NET Standard, .NET Core, .NET 
    code: |
        ```cs
                        
            // Set up input OBJ file
            string filePath = "input.obj";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render OBJ file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "Demonstração ao vivo do visualizador OBJ"
    content: |
        Veja o arquivo OBJ agora visitando o site [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/obj).
    lang: "pt"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Renderização e visualização de outros formatos de arquivo usando C#"
    exclude: "OBJ"
    content: |
        API de visualizador de imagens e documentos multiformato para .NET. Veja alguns dos formatos de arquivo populares abaixo sem nenhum visualizador externo.
    format: 
        # format loop 1
        - name: "Renderizar DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Documento XML Aberto do Microsoft Word" 

        # format loop 2
        - name: "Renderizar CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "Arquivo CorelDRAW" 

        # format loop 3
        - name: "Renderizar PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "Apresentação PowerPoint Open XML" 

        # format loop 4
        - name: "Renderizar XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Planilha XML Aberta do Microsoft Excel" 

        # format loop 5
        - name: "Renderizar DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "Desenho AutoCAD"

        # format loop 6
        - name: "Renderizar XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "Arquivo XML"

        # format loop 7
        - name: "Renderizar PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Documento Adobe Photoshop"

        # format loop 8
        - name: "Renderizar arquivo do Adobe Illustrator"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Arte do Adobe Illustrator"

        # format loop 9
        - name: "Renderizar DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "documento do Microsoft Word" 

        # format loop 10
        - name: "Renderizar TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Ficheiro de Texto Simples" 

        # format loop 11
        - name: "Renderizar DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Ficheiro de Formato de Intercâmbio de Desenhos"  
          
        # format loop 12
        - name: "Renderizar VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "Arquivo vCard"  
              
        # format loop 13
        - name: "Renderizar SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Gráfico vetorial escalonável" 
          
        # format loop 14
        - name: "Renderizar HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Arquivo de Linguagem de Marcação de Hipertexto" 
          
        # format loop 15
        - name: "Renderizar PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Arquivo de formato de documento portátil"
          
        # format loop 16
        - name: "Renderizar JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "Imagem JPEG"
          
        # format loop 17
        - name: "Renderizar PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Gráfico de Rede Portátil" 
          
        # format loop 18
        - name: "Renderizar EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "Mensagem de email" 
          
        # format loop 19
        - name: "Renderizar RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Ficheiro de Formato Rich Text" 
          
        # format loop 20
        - name: "Renderizar ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "Documento de Texto OpenDocument" 
          
        # format loop 21
        - name: "Renderizar CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Arquivo de valores separados por vírgula" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---