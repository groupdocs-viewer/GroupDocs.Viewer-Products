---
############################# Static ############################
layout: "format"
date: 2024-05-14T11:12:52
draft: false
lang: pt
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head #############################
head_title: ".NET JS API Viewer - ler, visualizar, renderizar em C# VB.NET"
head_description: "API do visualizador de documentos .NET para ler, renderizar e exibir JS em qualquer tipo de aplicativos C#, ASP.NET, VB.NET e .NET Core."

############################# Header ############################
title: "Visualizador de arquivos JS para aplicativos C# .NET" 
description: "API do visualizador de documentos .NET para ler, renderizar e exibir arquivos JS em qualquer tipo de aplicativos C#, ASP.NET, VB.NET e .NET Core. Visualize os arquivos renderizados com formatação e layout verdadeiros em HTML5, PDF ou como imagem usando algumas linhas de código." 
subtitle: "Solução de renderização de documentos" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "Download grátis do Nuget"
      link: "https://nuget.org/packages/GroupDocs.Viewer"



############################# About ############################
about:
    enable: true
    title: "Sobre GroupDocs.Viewer para API .NET"
    link: "/viewer/net/"
    link_title: "Saber mais"
    picture: "about_viewer.svg" # 480 X 400
    content: |
      Comece a visualizar mais de 190 formatos de documentos populares em seus aplicativos .NET usando GroupDocs.Viewer para APIs .NET adicionando algumas linhas de código. Os desenvolvedores podem exibir facilmente PDF, processamento de texto, planilha do Excel, apresentação, Visio, Projeto, Outlook e muitos outros formatos de documentos populares nos modos HTML5, imagem ou PDF. A renderização do documento é rápida, idêntica ao arquivo de origem original e não requer instalação de software adicional ou qualquer outra biblioteca externa.



############################# Steps ############################
steps:
    enable: true
    title: "Etapas para renderizar o arquivo JS em C#" 
    content: |
      Com <a href='https://products.groupdocs.com/viewer/net/'>GroupDocs.Viewer</a> você pode renderizar JS para HTML, JPEG, PNG ou PDF em algumas etapas.
      
      1. Instale <a href='https://www.nuget.org/packages/groupdocs.viewer'>GroupDocs.Viewer for .NET</a> usando seu gerenciador de pacotes favorito. 
      2. Crie uma instância da classe Viewer e carregue o arquivo JS com caminho completo.  
      3. Defina opções para renderizar o arquivo JS em formato HTML, PNG, JPEG ou PDF. 
      4. Renderize o arquivo e verifique a saída no diretório atual. 
   
    code:
      platform: "net"
      copy_title: "cópia de"
      install:
        command: "dotnet add package GroupDocs.Viewer"
        copy_tip: "clique para copiar"
        copy_done: "copiado"
      links:
        #  loop
        - title: "Mais exemplos"
          link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
        #  loop
        - title: "Documentação"
          link: "https://docs.groupdocs.com/viewer/net/"
          
      content: |
        ```csharp {style=abap}

        // Configurar arquivo de entrada JS
        string filePath = "input.js";

        // Instanciar GroupDocs.Viewer
        using (Viewer viewer = new Viewer(filePath))
        {
            // Definir opções de visualização
            HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                
            // Renderize o arquivo JS em HTML com recursos incorporados
            viewer.View(viewOptions);
        }

        ```            


############################# Actions ############################

actions:
  enable: true
  title: "Pronto para começar?"
  description: "Experimente os recursos do GroupDocs.Viewer gratuitamente ou solicite uma licença"
  items:
    #  loop
    - title: "Baixar pepita"
      link: "https://nuget.org/packages/GroupDocs.Viewer"
      color: "red"
        #  loop
    - title: "Licenciamento"
      link: "https://purchase.groupdocs.com/pricing/viewer/net/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "Renderize outros formatos de arquivo usando C#"
    exclude: "JS"
    description: "API de visualização de documentos e imagens multiformato para .NET. Veja alguns dos formatos de arquivo populares abaixo, sem visualizadores externos."
    items: 
        # format loop 1
        - name: "Renderizar DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word Open XML Document" 

        # format loop 2
        - name: "Renderizar CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "CorelDRAW File" 

        # format loop 3
        - name: "Renderizar PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint Open XML Presentation" 

        # format loop 4
        - name: "Renderizar XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet" 

        # format loop 5
        - name: "Renderizar DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "AutoCAD Drawing"

        # format loop 6
        - name: "Renderizar XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "XML File"

        # format loop 7
        - name: "Renderizar PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Adobe Photoshop Document"

        # format loop 8
        - name: "Renderizar AI"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Adobe Illustrator Artwork"

        # format loop 9
        - name: "Renderizar DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Microsoft Word Document" 

        # format loop 10
        - name: "Renderizar TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Plain Text File" 

        # format loop 11
        - name: "Renderizar DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Drawing Exchange Format File"  
          
        # format loop 12
        - name: "Renderizar VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "vCard File"  
              
        # format loop 13
        - name: "Renderizar SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Scalable Vector Graphic" 
          
        # format loop 14
        - name: "Renderizar HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "Renderizar PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Portable Document Format File"
          
        # format loop 16
        - name: "Renderizar JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "JPEG Image"
          
        # format loop 17
        - name: "Renderizar PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Portable Network Graphic" 
          
        # format loop 18
        - name: "Renderizar EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "E-Mail Message" 
          
        # format loop 19
        - name: "Renderizar RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Rich Text Format File" 
          
        # format loop 20
        - name: "Renderizar ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "OpenDocument Text Document" 
          
        # format loop 21
        - name: "Renderizar CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Comma-Separated Values File" 



---
