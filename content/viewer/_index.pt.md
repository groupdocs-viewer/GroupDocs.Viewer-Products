---
############################# Static ##########################
layout: "family"
date: 2023-12-20T06:39:57
draft: false

product: "Viewer"
product_tag: "viewer"

############################# Head ############################
head_title: "API de renderização e visualização de documentos | API local e serviço online"
head_description: "Renderize e visualize arquivos Word, PDF, Excel, Powerpoint ou imagem de forma fácil e gratuita"

############################# Header ##########################
title: "Renderize e visualize documentos com facilidade"
description: |
  API de visualizador poderosa para renderizar diferentes arquivos em PDF, HTML e imagem.

  Carregue documentos de diversas fontes, incluindo arquivos, streams, URLs, servidores FTP, Amazon S3, Azure Blob Storage e muito mais.

  Gere páginas HTML responsivas, proteja os arquivos PDF de saída e reordene suas páginas, gire páginas, renderize notas e comentários, se necessário.

############################# Platforms ############################
supported_platforms:
  enable: true  
  head_title: "Escolha sua plataforma"
  title: "Plataformas suportadas"
  description: "A biblioteca GroupDocs.Viewer oferece suporte aos seguintes sistemas operacionais e estruturas"
  details_link_title: "Saber mais"
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
        - content: "Mais de 180 formatos de arquivo"
          rows: "1"
        # features loop
        - content: "Pacote de UI para ASP.NET Core"
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
        - content: "Mais de 180 formatos de arquivo"
          rows: "1"
        # features loop
        - content:  "Pacote UI para Spring e Dropwizard"
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
        - content:  "Mais de 180 formatos de arquivo"
          rows: "1"
        # features loop
        - content:  "Pacote UI – em breve"
          rows: "1" 
        # features loop
        - content:  "Demonstração - em breve"
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
        - content:  "Mais de 180 formatos de arquivo"
          rows: "1"
        # features loop
        - content:  "Pacote UI – em breve"
          rows: "1" 
        # features loop
        - content:  "Demonstração - em breve"
          rows: "3" 

############################# Features ############################

features:
  enable: true
  title: "Conjunto de recursos do GroupDocs.Viewer"
  description: "API para renderizar arquivos de diferentes tipos como HTML, PDF, PNG e JPEG em aplicativos para visualizá-los sem software de terceiros."

  items:
    # feature loop
    - icon: "view"
      title: "Ver documentos e imagens"
      content: "Visualize documentos renderizando-os como arquivos HTML, PDF, PNG e JPEG."

    # feature loop
    - icon: "password"
      title: "Abra documentos protegidos"
      content: "Especifique uma senha para abrir documentos criptografados."

    # feature loop
    - icon: "load"
      title: "Carregue arquivos de qualquer lugar"
      content: "Carregue documentos de vários arquivos, URLs, servidores FTP, Amazon S3 e muito mais."
    
    # feature loop
    - icon: "pages"
      title: "Renderizar todas ou páginas específicas"
      content: "Especifique um intervalo de números de páginas a serem renderizados."


############################# Code samples ############################
code_samples:
  enable: true
  title: "Amostras de código GroupDocs.Viewer"
  description: "Alguns casos de uso de operações típicas do GroupDocs.Viewer em C#, Java, TypeScript"
  items:
    # code sample loop
    - title: "Como renderizar arquivos DOCX em PDF"
      content: |
       Renderize documentos DOCX em PDF sem o Microsoft Word ou outro software instalado. Carregue e visualize facilmente arquivos DOCX em seu aplicativo .NET, seja ele um aplicativo da web ou de desktop. Aqui está um exemplo de como renderizar um arquivo DOCX em PDF:
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Carregar arquivo DOCX para renderizar
            using (Viewer viewer = new Viewer("sample.docx"))
            {
              // Renderizar DOCX em um arquivo PDF
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
            // Carregar arquivo DOCX para renderizar
            try (Viewer viewer = new Viewer("sample.docx")) {
                // Renderizar DOCX em um arquivo PDF
                PdfViewOptions viewOptions = new PdfViewOptions();
                viewer.view(viewOptions);
            }
            ```
        - language: "TypeScript"
          color: "green"
          content: |
            ```javascript {style=abap}  
            // Carregar arquivo DOCX para renderizar
            const viewer = new groupdocs.viewer.Viewer("sample.docx")
            
            // Renderizar DOCX em um arquivo PDF
            const viewOptions = groupdocs.viewer.PdfViewOptions(output.pdf)
            viewer.view(viewOptions)
            ```

        - language: "Python"
          color: "yellow"
          content: |
            ```python {style=abap} 
            import groupdocs.viewer as gv
            import groupdocs.viewer.options as gvo   
            // Carregar arquivo DOCX para renderizar
            with gv.Viewer("sample.docx") as viewer:
            
            // Renderizar DOCX em um arquivo PDF
            viewOptions = gvo.PdfViewOptions("output.pdf")
            viewer.view(viewOptions)
            ```

############################# Formats ############################
formats:
  enable: true
  title:  "Mais de 180 formatos de arquivo suportados"
  description: "GroupDocs.Viewer suporta operações com os mais populares [formatos de arquivo](https://docs.groupdocs.com/viewer/net/supported-document-formats/)"


############################# Metrics ############################

metrics:
  enable: true
  title: "Métricas detalhadas e insights estatísticos"
  description: "Mergulhe em uma análise detalhada de nossos principais números, fornecendo métricas abrangentes e insights estatísticos sobre nossas conquistas, impacto e crescimento."

  items:
    # metrics loop
    - number: "180+"
      title: "Formatos suportados"
      content: "Visualize facilmente mais de 180 formatos de arquivo, incluindo documentos, imagens e desenhos CAD, sem complicações. Quebre barreiras de compatibilidade e acesse diversos arquivos sem esforço com nossa solução de visualização abrangente."
    # metrics loop
    - number: "1.0M"
      title: "Downloads do NuGet"
      content: "Nossa solução de pacote NuGet se tornou um recurso confiável e amplamente adotado na comunidade de desenvolvedores, fornecendo integração perfeita e funcionalidades valiosas para inúmeros projetos."

    # metrics loop
    - number: "10+"
      title: "Bibliotecas"
      content: "Nosso produto inclui mais de 10 bibliotecas, oferecendo recursos avançados para otimizar o desempenho. Essas bibliotecas são projetadas para atender a diferentes necessidades de desenvolvimento com recursos incomparáveis."
    
    # metrics loop
    - number: "100+"
      title: "Clientes satisfeitos"
      content: "Servindo as marcas mais icônicas do mundo. Descubra por que centenas de pessoas adoram o GroupDocs.Viewer! Explore navegação perfeita, colaboração conveniente e facilidade de uso incomparável. Entrar!"


############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "Nossos clientes satisfeitos"
  description: "As bibliotecas GroupDocs são empregadas por marcas renomadas e distintas em todo o mundo."

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
  title: "Pronto para começar?"
  description: "Experimente os recursos do GroupDocs.Viewer gratuitamente ou solicite uma licença"

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
  title: "Perguntas e preocupações comuns"
  description: "Encontre respostas para perguntas comuns em nossa seção de perguntas frequentes para responder rapidamente às suas dúvidas e preocupações."

  items:
    #  loop
    - question: "Posso avaliar os produtos GroupDocs antes de comprá-los?"
      answer: |
        Sim! Todos os produtos GroupDocs têm uma versão de avaliação livre de riscos disponível. Recomendamos fortemente que os desenvolvedores baixem e experimentem nossas APIs antes de comprar para garantir que elas atenderão 100% às suas necessidades.
    #  loop
    - question: "O GroupDocs faz demonstrações de produtos?"
      answer: |
        Não, nosso foco está em nossas APIs e em tornar os produtos mais funcionais e estáveis ​​possíveis. Oferecemos testes totalmente funcionais e gratuitos na forma de uma [licença temporária](https://purchase.groupdocs.com/temporary-license/) para que você possa testar o produto por si mesmo.
    #  loop
    - question: "Onde posso baixar o produto?"
      answer: |
        Todos os produtos estão disponíveis para download no [website](https://releases.groupdocs.com). Não enviamos cópias físicas do nosso software por correio.    
    #  loop
    - question: "As licenças de desenvolvedor do GroupDocs são por usuário ou por usuário nomeado?"
      answer: |
        As licenças do GroupDocs Developer são por usuário, não por usuário nomeado. Entendemos que os membros de uma equipe de codificação podem mudar com o tempo e que não é prático ter que atualizar o licenciamento sempre que isso ocorre.
    #  loop
    - question: "Precisamos de licenciamento apenas para desenvolvedores ativos? Por exemplo, temos uma equipe de dois desenvolvedores trabalhando no turno A e uma segunda equipe de dois desenvolvedores trabalhando no turno B… nesta situação, precisamos de duas ou quatro licenças?"
      answer: |
        Todos os desenvolvedores que estão trabalhando no projeto precisam ser licenciados. Nessa situação, o GroupDocs vê sua equipe como tendo quatro membros (mesmo que trabalhem em horários diferentes).

############################# Cloud ############################

cloud_links:
  enable: true
  title: "APIs de baixo código GroupDocs.Viewer"
  description: "Acelere a visualização de documentos ou imagens em qualquer tipo de aplicativo com nossa API REST baseada em nuvem"

  items:
    #  loop
    - icon: "groupdocs_viewer-for-curl"
      title: "GroupDocs.Viewer Cloud for cURL"
      link: "https://products.groupdocs.cloud/viewer/curl"
      content: "Use a API do visualizador de documentos RESTful cURL para renderizar e exibir com eficiência o Microsoft Office, PDF e vários outros formatos de arquivo padrão em seus aplicativos."

    #  loop
    - icon: "groupdocs_viewer-for-net"
      title: "GroupDocs.Viewer Cloud for .NET"
      link: "https://products.groupdocs.cloud/viewer/net"
      content: "Aprimore os recursos de visualização de documentos em aplicativos .NET com o Cloud SDK for .NET. Visualize documentos perfeitamente em formatos HTML, PDF ou de imagem."
    #  loop
    - icon: "groupdocs_viewer-for-java"
      title: "GroupDocs.Viewer Cloud for Java"
      link: "https://products.groupdocs.cloud/viewer/java"
      content: "Integre recursos avançados de renderização de documentos em seus aplicativos Java usando um SDK do Document Viewer para Java desenvolvido especificamente."

############################# Apps ############################

app_links:
  enable: true
  title: "Aplicativos GroupDocs.Viewer NoCode"
  description: "Aplicativo on-line que permite visualizar mais de 180 formatos de arquivo populares no navegador"

  items:
    #  loop
    - icon: "groupdocs_viewer-app"
      title: "GroupDocs.Viewer Total"
      link: "https://products.groupdocs.app/viewer/total"
      content: "Explore um aplicativo on-line gratuito para visualizar mais de 180 formatos de arquivo diretamente do seu navegador preferido."

    #  loop
    - icon: "groupdocs_words-app"
      title:  "GroupDocs.Viewer DOCX"
      link: "https://products.groupdocs.app/viewer/docx"
      content: "Ferramenta baseada na Web para visualizar arquivos do Microsoft Word sem esforço em vários dispositivos."

    #  loop
    - icon: "groupdocs_pdf-app"
      title:  "GroupDocs.Viewer PDF"
      link: "https://products.groupdocs.app/viewer/pdf"
      content: "Abra e visualize arquivos PDF online com o visualizador de PDF gratuito."
    

---