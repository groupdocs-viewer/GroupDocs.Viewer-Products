---
############################# Static ############################
layout: "format"
date: 2024-05-14T11:12:41
draft: false
lang: pt
product: "Viewer"
product_tag: "viewer"
platform: "Java"
platform_tag: "java"

############################# Head #############################
head_title: "Java TIFF API Viewer - renderizar e exibir TIFF em aplicativos Java"
head_description: "Visualize arquivos TIFF em aplicativos Java, J2EE, J2SE. Suporta a visualização de mais de 180 formatos de documentos e arquivos de imagem em HTML, PDF ou modo de imagem com recursos avançados para gerenciar opções de visualização de documentos."

############################# Header ############################
title: "Renderizar e visualizar TIFF em Java" 
description: "API visualizadora de arquivos TIFF nativa e de alto desempenho para aplicativos baseados em Java, J2EE e J2SE, suportando uma ampla gama de recursos adicionais para personalizar a aparência do formato do documento de saída." 
subtitle: "Solução de renderização de documentos" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "Baixar Maven grátis"
      link: "https://releases.groupdocs.com/viewer/java/"



############################# About ############################
about:
    enable: true
    title: "Sobre GroupDocs.Viewer para API Java"
    link: "/viewer/java/"
    link_title: "Saber mais"
    picture: "about_viewer.svg" # 480 X 400
    content: |
      Permita que seus aplicativos Java exibam mais de 180 formatos de arquivo em HTML, PDF ou modos de imagem usando GroupDocs.Viewer para APIs Java sem qualquer software adicional instalado; como Microsoft Office, Apache Open Office, Adobe Acrobat Reader etc. Os desenvolvedores podem visualizar facilmente todas as imagens e tipos de documentos populares, incluindo Microsoft Office, OpenDocument, HTML, PDF, Archive, Diagrams, Photoshop, AutoCAD e formatos de linguagem de programação dentro dos aplicativos Java com renderização rápida e da mais alta qualidade.



############################# Steps ############################
steps:
    enable: true
    title: "Etapas para renderizar o arquivo TIFF em Java" 
    content: |
      Com <a href='https://products.groupdocs.com/viewer/java/'>GroupDocs.Viewer</a> você pode renderizar TIFF para HTML, JPEG, PNG ou PDF em algumas etapas.
      
      1. Adicione <a href='https://releases.groupdocs.com/viewer/java/'>GroupDocs.Viewer for Java</a> como uma dependência ao seu projeto. 
      2. Crie uma instância da classe Viewer e carregue o arquivo TIFF com caminho completo.  
      3. Defina opções para renderizar o arquivo TIFF em formato HTML, PNG, JPEG ou PDF. 
      4. Renderize o arquivo e verifique a saída no diretório atual. 
   
    code:
      platform: "java"
      copy_title: "cópia de"
      install:
        command: |
          <dependencies>
            <dependency>
              <groupId>com.groupdocs</groupId>
              <artifactId>groupdocs-viewer</artifactId>
              <version>{0}</version>
            </dependency>
          </dependencies>

          <repositories>
            <repository>
              <id>repository.groupdocs.com</id>
              <name>GroupDocs Repository</name>
              <url>https://repository.groupdocs.com/repo/</url>
            </repository>
          </repositories>
        copy_tip: "clique para copiar"
        copy_done: "copiado"
      links:
        #  loop
        - title: "Mais exemplos"
          link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Java"
        #  loop
        - title: "Documentação"
          link: "https://docs.groupdocs.com/viewer/java/"
          
      content: |
        ```java {style=abap}

        // Configurar arquivo de entrada TIFF
        String filePath = "input.tiff";

        // Instanciar GroupDocs.Viewer
        try (Viewer viewer = new Viewer(filePath))
        {
            // Definir opções de visualização
            HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                
            // Renderize o arquivo TIFF em HTML com recursos incorporados
            viewer.view(viewOptions);
        }

        ```
            

############################# Actions ############################

actions:
  enable: true
  title: "Pronto para começar?"
  description: "Experimente os recursos do GroupDocs.Viewer gratuitamente ou solicite uma licença"
  items:
    #  loop
    - title: "Baixar Maven"
      link: "https://releases.groupdocs.com/viewer/java/"
      color: "red"
        #  loop
    - title: "Licenciamento"
      link: "https://purchase.groupdocs.com/pricing/viewer/java/"
      color: "light"



############################# More Formats #####################
more_formats:
    enable: true
    title: "Renderize outros formatos de arquivo usando Java"
    exclude: "TIFF"
    description: "API de visualização de documentos e imagens multiformato para Java. Veja alguns dos formatos de arquivo populares abaixo, sem visualizadores externos."
    items: 
        # format loop 1
        - name: "Renderizar DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Open XML Document" 

        # format loop 2
        - name: "Renderizar CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "CorelDRAW File" 

        # format loop 3
        - name: "Renderizar PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint Open XML Presentation" 

        # format loop 4
        - name: "Renderizar XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet" 

        # format loop 5
        - name: "Renderizar DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "AutoCAD Drawing"

        # format loop 6
        - name: "Renderizar XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "XML File"

        # format loop 7
        - name: "Renderizar PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Adobe Photoshop Document"

        # format loop 8
        - name: "Renderizar AI"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Adobe Illustrator Artwork"

        # format loop 9
        - name: "Renderizar DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Microsoft Word Document" 

        # format loop 10
        - name: "Renderizar TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Plain Text File" 

        # format loop 11
        - name: "Renderizar DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Drawing Exchange Format File"  
          
        # format loop 12
        - name: "Renderizar VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "vCard File"  
              
        # format loop 13
        - name: "Renderizar SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Scalable Vector Graphic" 
          
        # format loop 14
        - name: "Renderizar HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "Renderizar PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Portable Document Format File"
          
        # format loop 16
        - name: "Renderizar JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "JPEG Image"
          
        # format loop 17
        - name: "Renderizar PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Portable Network Graphic" 
          
        # format loop 18
        - name: "Renderizar EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "E-Mail Message" 
          
        # format loop 19
        - name: "Renderizar RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Rich Text Format File" 
          
        # format loop 20
        - name: "Renderizar ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "OpenDocument Text Document" 
          
        # format loop 21
        - name: "Renderizar CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Comma-Separated Values File" 


---
