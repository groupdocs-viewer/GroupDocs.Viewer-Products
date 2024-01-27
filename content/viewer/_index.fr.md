---
############################# Static ############################
layout: "family"
date: 2023-12-20T06:39:57
draft: false

product: "Viewer"
product_tag: "viewer"

############################# Head ############################
head_title: "API de rendu et d'affichage de documents | API sur site et service en ligne"
head_description: "Rendre et visualiser des fichiers Word, PDF, Excel, Powerpoint ou Image facilement et gratuitement"

############################# Header ############################
title: "Rendre et visualiser des documents en toute simplicité"
description: |
  API de visualisation puissante pour restituer différents fichiers au format PDF, HTML et image.

  Chargez des documents à partir de diverses sources, notamment des fichiers, des flux, des URL, des serveurs FTP, Amazon S3, Azure Blob Storage, etc.

  Générez des pages HTML réactives, protégez les fichiers PDF de sortie et réorganisez leurs pages, faites pivoter les pages, restituez les notes et les commentaires si nécessaire.
  

############################# Platforms ############################
supported_platforms:
  enable: true  
  head_title: "Choisissez votre plateforme"
  title: "Plateformes prises en charge"
  description: "La bibliothèque GroupDocs.Viewer prend en charge les systèmes d'exploitation et les frameworks suivants"
  details_link_title: "Apprendre encore plus"
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
        - content: "180+ file formats"
          rows: "1"
        # features loop
        - content: "UI package for ASP.NET Core"
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
        - content:  "180+ file formats"
          rows: "1"
        # features loop
        - content:  "UI package for Spring and Dropwizard"
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
        - content:  "180+ file formats"
          rows: "1"
        # features loop
        - content:  "UI package - coming soon "
          rows: "1" 
        # features loop
        - content:  "Demo - coming soon "
          rows: "3" 



############################# Features ############################

features:
  enable: true
  title: "Ensemble de fonctionnalités de GroupDocs.Viewer"
  description: "API pour restituer des fichiers de différents types tels que HTML, PDF, PNG et JPEG dans des applications afin de les visualiser sans logiciel tiers."

  items:
    # feature loop
    - icon: "view"
      title: "Afficher des documents et des images"
      content: "Affichez des documents en les restituant sous forme de fichiers HTML, PDF, PNG et JPEG."
    # feature loop
    - icon: "password"
      title: "Ouvrir des documents sécurisés"
      content: "Spécifiez un mot de passe pour ouvrir les documents cryptés."

    # feature loop
    - icon: "load"
      title: "Chargez des fichiers de n'importe où"
      content: "Chargez des documents à partir de divers fichiers, URL, serveurs FTP, Amazon S3, etc."
    
    # feature loop
    - icon: "pages"
      title: "Afficher toutes les pages ou des pages spécifiques"
      content: "Spécifiez une plage de numéros de page à afficher."


############################# Code samples ############################
code_samples:
  enable: true
  title: "Exemples de code GroupDocs.Viewer"
  description: "Quelques cas d'utilisation d'opérations GroupDocs.Viewer typiques en C#, Java, TypeScript"
  items:
    # code sample loop
    - title: "Comment rendre des fichiers DOCX au format PDF"
      content: |
        Rendu des documents DOCX au format PDF sans Microsoft Word ou autre logiciel installé. Chargez et affichez facilement des fichiers DOCX dans votre application .NET, qu'il s'agisse d'une application Web ou de bureau. Voici un exemple de comment rendre un fichier DOCX au format PDF : 
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Charger le fichier DOCX à rendre
            using (Viewer viewer = new Viewer("sample.docx"))
            {
              // Rendre DOCX dans un fichier PDF
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
            // Charger le fichier DOCX à rendre
            try (Viewer viewer = new Viewer("sample.docx")) {
                // Rendre DOCX dans un fichier PDF
                PdfViewOptions viewOptions = new PdfViewOptions();
                viewer.view(viewOptions);
            }
            ```
        - language: "TypeScript"
          color: "green"
          content: |
            ```javascript {style=abap}  
            // Charger le fichier DOCX à rendre
            const viewer = new groupdocs.viewer.Viewer("sample.docx")
            
            // Rendre DOCX dans un fichier PDF
            const viewOptions = groupdocs.viewer.PdfViewOptions(output.pdf)
            viewer.view(viewOptions)
            ```


############################# Formats ############################
formats:
  enable: true
  title:  "Plus de 180 formats de fichiers pris en charge"
  description: "GroupDocs.Viewer prend en charge les opérations avec les [formats de fichiers](https://docs.groupdocs.com/viewer/net/supported-document-formats/) les plus populaires" 



############################# Metrics ############################

metrics:
  enable: true
  title: "Mesures approfondies et informations statistiques"
  description: "Plongez dans une présentation détaillée de nos chiffres clés, fournissant des mesures complètes et des informations statistiques sur nos réalisations, notre impact et notre croissance."

  items:
    # metrics loop
    - number: "180+"
      title: "Formats pris en charge"
      content: "Visualisez facilement plus de 180 formats de fichiers, notamment des documents, des images et des dessins CAO, sans tracas. Brisez les barrières de compatibilité et accédez sans effort à divers fichiers grâce à notre solution de visualisation complète."

    # metrics loop
    - number: "1.0M"
      title: "Téléchargements NuGet"
      content: "Notre solution de package NuGet est devenue une ressource fiable et largement adoptée par la communauté des développeurs, offrant une intégration transparente et des fonctionnalités précieuses pour d'innombrables projets."

    # metrics loop
    - number: "10+"
      title: "Bibliothèques"
      content: "Notre produit comprend plus de 10 bibliothèques offrant des fonctionnalités avancées pour optimiser les performances. Ces bibliothèques sont conçues pour répondre à différents besoins de développement avec des capacités inégalées."
    
    # metrics loop
    - number: "100+"
      title: "Clients satisfaits"
      content: "Au service des marques les plus emblématiques du monde entier. Découvrez pourquoi des centaines de personnes aiment GroupDocs.Viewer ! Découvrez une navigation transparente, une collaboration pratique et une facilité d'utilisation inégalée. Adhérer maintenant!"



############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "Nos clients satisfaits"
  description: "Les bibliothèques GroupDocs sont utilisées par des marques de renommée mondiale et distinguées à travers le monde."

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
  title: "Prêt à commencer?"
  description: "Essayez les fonctionnalités de GroupDocs.Viewer gratuitement ou demandez une licence"
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


############################# Faq ############################

faq:
  enable: true
  title:  "Questions et préoccupations courantes"
  description:  "Trouvez des réponses aux demandes courantes dans notre section FAQ pour répondre rapidement à vos questions et préoccupations."
  items:
    #  loop
    - question: "Puis-je évaluer les produits GroupDocs avant de les acheter ?"
      answer: |
        Oui! Tous les produits GroupDocs disposent d'une version d'évaluation sans risque. Nous encourageons fortement les développeurs à télécharger et à essayer nos API avant d'acheter pour nous assurer qu'elles répondront à 100 % à vos besoins.
    #  loop
    - question: "GroupDocs fait-il des démonstrations de produits ?"
      answer: |
        Non, nous nous concentrons sur nos API et sur la création des produits les plus fonctionnels et les plus stables possibles. Nous proposons des essais entièrement fonctionnels et gratuits sous la forme d'une [licence temporaire](https://purchase.groupdocs.com/temporary-license/) afin que vous puissiez tester le produit par vous-même.    
    #  loop
    - question: "Où puis-je télécharger le produit ?"
      answer: |
        Tous les produits peuvent être téléchargés à partir du [site Web](https://releases.groupdocs.com). Nous n'envoyons pas de copies physiques de nos logiciels par courrier.
    #  loop
    - question: "Les licences de développeur GroupDocs sont-elles par utilisateur ou par utilisateur nommé ?"
      answer: |
        Les licences GroupDocs Developer sont attribuées par utilisateur et non par utilisateur nommé. Nous comprenons que les membres d'une équipe de codage peuvent changer au fil du temps et qu'il n'est pas pratique de devoir mettre à jour les licences à chaque fois que cela se produit.
    #  loop
    - question: "Avons-nous besoin de licences uniquement pour les développeurs actifs ? Par exemple, nous avons une équipe de deux développeurs travaillant sur l’équipe A et une deuxième équipe de deux développeurs travaillant sur l’équipe B… dans cette situation, avons-nous besoin de deux ou quatre licences ?"
      answer: |
        Tous les développeurs qui travaillent sur le projet doivent détenir une licence. Dans cette situation, GroupDocs considère votre équipe comme composée de quatre membres (même s'ils travaillent à des horaires différents). 


############################# Cloud ############################

cloud_links:
  enable: true
  title: "API à faible code GroupDocs.Viewer"
  description: "Accélérez la visualisation de documents ou d'images dans tout type d'application grâce à notre API REST basée sur le cloud"

  items:
    #  loop
    - icon: "groupdocs_viewer-for-curl"
      title: "GroupDocs.Viewer Cloud for cURL"
      link: "https://products.groupdocs.cloud/viewer/curl"
      content: "Utilisez l'API de visualisation de documents cURL RESTful pour restituer et présenter efficacement Microsoft Office, PDF et divers autres formats de fichiers standard dans vos applications."

    #  loop
    - icon: "groupdocs_viewer-for-net"
      title: "GroupDocs.Viewer Cloud for .NET"
      link: "https://products.groupdocs.cloud/viewer/net"
      content: "Améliorez les capacités d'affichage de documents dans les applications .NET avec le SDK Cloud pour .NET. Affichez des documents de manière transparente aux formats HTML, PDF ou image."

    #  loop
    - icon: "groupdocs_viewer-for-java"
      title: "GroupDocs.Viewer Cloud for Java"
      link: "https://products.groupdocs.cloud/viewer/java"
      content: "Intégrez des fonctionnalités avancées de rendu de documents dans vos applications Java à l'aide d'un SDK de visionneuse de documents spécialement conçu pour Java."
    

############################# Apps ############################

app_links:
  enable: true
  title: "Applications GroupDocs.Viewer NoCode"
  description: "Application en ligne vous permettant de visualiser plus de 180 formats de fichiers populaires dans un navigateur"

  items:
    #  loop
    - icon: "groupdocs_viewer-app"
      title: "GroupDocs.Viewer Total"
      link: "https://products.groupdocs.app/viewer/total"
      content: "Explorez une application en ligne gratuite pour afficher plus de 180 formats de fichiers directement depuis votre navigateur Web préféré."

    #  loop
    - icon: "groupdocs_words-app"
      title:  "GroupDocs.Viewer DOCX"
      link: "https://products.groupdocs.app/viewer/docx"
      content: "Outil Web permettant de visualiser facilement des fichiers Microsoft Word sur différents appareils."

    #  loop
    - icon: "groupdocs_pdf-app"
      title:  "GroupDocs.Viewer PDF"
      link: "https://products.groupdocs.app/viewer/pdf"
      content: "Ouvrez et visualisez des fichiers PDF en ligne avec la visionneuse PDF gratuite."
    



---