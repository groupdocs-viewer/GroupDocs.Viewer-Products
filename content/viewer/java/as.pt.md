---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: pt

############################# Head #############################
head_title: "Java AS API do visualizador - renderizar e exibir AS em aplicativos Java"
head_description: "Veja arquivos AS em aplicativos Java, J2EE, J2SE. Suporta a visualização de mais de 170 formatos de arquivo de imagem e documento em HTML, PDF ou modo de imagem com recursos avançados para gerenciar as opções de visualização de documentos."

############################# Header ############################
title: "Renderizar e visualizar AS em Java" 
description: "API do visualizador de arquivos AS nativo e de alto desempenho para aplicativos baseados em Java, J2EE e J2SE, suportando uma ampla gama de recursos adicionais para personalizar a aparência do formato do documento de saída." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Baixar Teste Gratuito"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Sobre GroupDocs.Viewer para API Java" 
    content: |
        Permita que seus aplicativos Java exibam mais de 170 formatos de arquivo nos modos HTML, PDF ou imagem usando GroupDocs.Viewer para APIs Java sem nenhum software adicional instalado; como Microsoft Office, Apache Open Office, Adobe Acrobat Reader etc. Os desenvolvedores podem facilmente visualizar todas as imagens populares e tipos de documentos, incluindo Microsoft Office, OpenDocument, HTML, PDF, Arquivo, Diagramas, Photoshop, AutoCAD e formatos de linguagem de programação dentro dos aplicativos Java com renderização rápida e de alta qualidade.

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
    title_left: "Etapas para renderizar o arquivo AS em Java" 
    content_left: |
        Com [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/) você pode renderizar AS para HTML, JPEG, PNG ou PDF em algumas etapas.

        * Adicione [GroupDocs.Viewer for Java](https://releases.groupdocs.com/viewer/java/) como uma dependência ao seu projeto. 
        * Crie uma instância da classe Viewer e carregue o arquivo AS com o caminho completo. 
        * Defina as opções para renderizar o arquivo AS em formato HTML, PNG, JPEG ou PDF. 
        * Renderize o arquivo e verifique a saída no diretório atual. 
        
    title_right: "Requisitos de sistema" 
    content_right: |
        As APIs do GroupDocs.Viewer para Java são suportadas em todas as principais plataformas e sistemas operacionais. Antes de executar o código abaixo, certifique-se de ter os seguintes pré-requisitos instalados em seu sistema.

        * Sistemas Operacionais: Microsoft Windows, Linux, MacOS 
        * Ambientes de Desenvolvimento: NetBeans, IntelliJ IDEA, Eclipse etc. 
        * Frameworks: J2SE 8.0 (1.8) ou superior (por exemplo, Java 17) 
    code: |
        ```java
                        
            // Set up input AS file
            String filePath = "input.as";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render AS file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "Demonstração ao vivo do visualizador AS"
    content: |
        Veja o arquivo AS agora visitando o site [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/as).
    lang: "pt"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Renderização e visualização de outros formatos de arquivo usando Java"
    exclude: "AS"
    content: |
        API de visualizador de documentos e imagens em vários formatos para Java. Veja alguns dos formatos de arquivo populares abaixo sem nenhum visualizador externo.
    format: 
        # format loop 1
        - name: "Renderizar DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Documento XML Aberto do Microsoft Word" 

        # format loop 2
        - name: "Renderizar CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "Arquivo CorelDRAW" 

        # format loop 3
        - name: "Renderizar PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "Apresentação PowerPoint Open XML" 

        # format loop 4
        - name: "Renderizar XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Planilha XML Aberta do Microsoft Excel" 

        # format loop 5
        - name: "Renderizar DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "Desenho AutoCAD"

        # format loop 6
        - name: "Renderizar XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "Arquivo XML"

        # format loop 7
        - name: "Renderizar PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Documento Adobe Photoshop"

        # format loop 8
        - name: "Renderizar arquivo do Adobe Illustrator"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Arte do Adobe Illustrator"

        # format loop 9
        - name: "Renderizar DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "documento do Microsoft Word" 

        # format loop 10
        - name: "Renderizar TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Ficheiro de Texto Simples" 

        # format loop 11
        - name: "Renderizar DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Ficheiro de Formato de Intercâmbio de Desenhos"  
          
        # format loop 12
        - name: "Renderizar VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "Arquivo vCard"  
              
        # format loop 13
        - name: "Renderizar SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Gráfico vetorial escalonável" 
          
        # format loop 14
        - name: "Renderizar HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Arquivo de Linguagem de Marcação de Hipertexto" 
          
        # format loop 15
        - name: "Renderizar PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Arquivo de formato de documento portátil"
          
        # format loop 16
        - name: "Renderizar JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "Imagem JPEG"
          
        # format loop 17
        - name: "Renderizar PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Gráfico de Rede Portátil" 
          
        # format loop 18
        - name: "Renderizar EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "Mensagem de email" 
          
        # format loop 19
        - name: "Renderizar RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Ficheiro de Formato Rich Text" 
          
        # format loop 20
        - name: "Renderizar ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "Documento de Texto OpenDocument" 
          
        # format loop 21
        - name: "Renderizar CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Arquivo de valores separados por vírgula" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
