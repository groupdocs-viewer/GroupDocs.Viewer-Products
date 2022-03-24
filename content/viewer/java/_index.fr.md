---
############################# Static ############################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

product: "Viewer"
product_tag: "viewer"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "API Java Document Viewer pour PDF Word Excel HTML Images et e-mails"
head_description: "Visualiseur de documents Java et API de rendu de fichiers. Ajouter une visionneuse PDF, une visionneuse Word, une visionneuse Excel, une visionneuse d'images, une visionneuse HTML, une visionneuse d'e-mails dans les applications Java."

############################# Header ############################
title: "API Java pour rendre et afficher des documents"
description: "Bibliothèque de visionneuse de documents pour développer des applications Java qui rendent, visualisent et manipulent de manière native des documents multiformats prenant en charge plus de 170 formats de fichiers."
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Télécharger la version d'essai gratuite"
    link: "https://downloads.groupdocs.com/viewer/java"

############################# SubMenu ############################
submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Viewer for Java"
        image: "/border/groupdocs-viewer-java.svg"
        product: "GroupDocs.Viewer"
        platform: "Java"

    middle:
        button:
            # button loop
            - link: "#overview"
              text: "Aperçu"

            # button loop
            - link: "#features"
              text: "Caractéristiques"

            # button loop
            - link: "#support"
              text: "Support"

            # button loop
            - link: "https://products.groupdocs.app/viewer"
              text: "Live Demo"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/java"
              text: "Pricing"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/java"
        link_learn: "https://docs.groupdocs.com/viewer/java/"
        link_buy: "https://purchase.groupdocs.com"

############################# Aperçu ############################
overview:
    enable: true
    content: |
      GroupDocs.Viewer pour Java combine un ensemble puissant d'API de visualisation de documents pour afficher des images et des formats de documents dans vos applications Java sans avoir à installer de logiciel supplémentaire. Il rastérise nativement les documents et les convertit en SVG + HTML + CSS pour améliorer la qualité de visualisation des documents tout en offrant une sortie haute fidélité en texte vrai. Utilisation de l'API de rendu de documents - visualisez rapidement des PDF, HTML, XML, Microsoft Office Word, des feuilles de calcul Excel, des présentations PowerPoint, des e-mails Outlook, des diagrammes Visio, des projets, des métafichiers, des images et divers autres formats de fichiers avec facilité et moins de risques de programmation. Il peut également afficher des fichiers protégés par mot de passe et permettre d'obtenir une représentation du document sous forme de HTML, d'image ou de PDF après le rendu. Notre bibliothèque de visionneuse de fichiers est assez personnalisable, car elle vous permet d'afficher l'intégralité du document ou de le rendre partiellement pour accélérer le processus. Grâce à l'API GroupDocs.Viewer pour Java, vous pouvez afficher des pages, une plage de cellules spécifique dans une feuille de calcul ou même restituer une couche de document individuelle dans des formats tels que PDF et CAO.  
        
      GroupDocs.Viewer pour l'API Java vous permet de rendre des documents avec/sans annotation ou commentaires pour les formats de fichiers pris en charge. Il vous permet également d'ajouter des répertoires de polices personnalisés et d'extraire des informations de base sur le document telles que FileType, Extension, Name, PageCount, etc. 
        
      GroupDocs.Viewer pour Java est compatible avec toutes les versions de Java et prend en charge les systèmes d'exploitation courants (Windows, Linux, macOS) capables d'exécuter l'environnement d'exécution Java.
    tabs:
      enable: true     
      
      ## TAB ONE ##
      tab_one:
        description: |
          Voici un aperçu de GroupDocs.Viewer pour Java :

        right:
          enable: true
          icon: "fab fa-html5"
          title: "Aperçu"
          content: |
            * Afficher plus de 50 types de documents
            * Obtenir HTML, Image, Version PDF
            * Rotation et réorganisation
            * Appliquer le filigrane
            * Cache pour un processus rapide
            * Ajouter des polices personnalisées
            * Appliquer les normes d'encodage
            * Gestionnaire de données d'entrée personnalisé
            * Rendu avec suivi des modifications
            * Rendu en HTML réactif
            * Rendu des couches PDF et CAO
            * Rendu des fichiers protégés
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Viewer pour Java prend en charge tous les [formats de fichiers de documents](https://docs.groupdocs.com/viewer/java/supported-document-formats/) courants, y compris : Microsoft Office, les images, les diagrammes et bien d'autres.

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
            - title: "Autres formats"
              content: |
                * **PDF Formats:** PDF, TEX, XPS, OXPS
                * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG, OTG, FODP, FODG
                * **Delimiter-Separated Values:** CSV, TSV
                * **Web:** HTML, MHT, MHTML
                * **Metafile:** WMF, EMF, CGM, WMZ, EMZ
                * **PostScript:** PS, EPS
                * **Archives:** ZIP, TAR, BZ2, GZ, RAR, RAR5
                * **Divers:** OBJ, EPUB, MOBI, DjVu, XML, VCF, VCARD, NUMBER, NSF

        right:
          enable: true
          table:
            # table loop
            - title: "Images, graphiques et diagrammes"
              content: |
                * **Images:** BMP, GIF, JPG, PNG, TIFF, multi-page TIFF, WebP, DNG, DIB, DCM
                * **Windows Icon:** ICO
                * **Scalable Vector Graphics:** SVG, CDR, CMX, IGS, SVGZ
                * **Jpeg2000:** JP2, J2C, J2K, JPC, JPF, JPX, JPM
                * **Adobe Photoshop:** PSD, PSB
                * **Printer Command Language:** PCL
                * **Stereo Lithography (3D Printing):** STL
                * **Industry Foundation Classes:** IFC
                * **Medical Imaging:** DICOM
                * **Plotter Documents:** PLT, HPG
                * **Autodesk Design Web Formats:** DWF, DWG
                * **AutoCAD Drawing:** DGN, DWT, IFC, STL, CF2
                * **ISFF-based DGN (V7):** DGN

            # table loop
            - title: "Formats des langages de programmation"
              content: |
                * **C/C++/C# Files:** C, CC, CS, CPP, CXX, C#, H, HH, M, MM
                * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES
                * **Various:** VB, PHP, SQL, PL, PY, PV, RB, RST, SASS, SCALA, SCM, SCRIPT, AS, AS3, ASM, BAT, CMAKE, CSS, DIFF, ERB, GROOVY, HAML, LESS, LOG, M, MAKE, MD, ML, MM, SH, SML, VIM, YAML

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Viewer for Java prend en charge la suite Systèmes d'exploitation, Frameworks & Directeur chargé d'emballages:
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Systèmes d'exploitation"
              content: |
                * Bureau Microsoft Windows
                * Serveur Microsoft Windows
                * Linux
                * Mac OS

            # table loop
            - icon: "fas fa-code"
              title: "Cadres pris en charge"
              content: |
                * Java 7 (1.7) et supérieur

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-cogs"
              title: "Environnements de développement"
              content: |
                * NetBeans
                * IDÉE IntelliJ
                * Éclipse
            # table loop
            - icon: "fas fa-tools"
              title: "Outil d'automatisation de construction"
              content: |
                * Maven

############################# Caractéristiques ############################
features:
    enable: true
    title: "GroupDocs.Viewer for Java Caractéristiques"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "Visionneuse pour HTML, PDF, Images, Word, Excel et autres formats de documents"

      # feature loop
      - icon: "fas fa-eye"
        content: "Rendre les fichiers de dessins AutoCAD (DWG) au format SVG"

      # feature loop
      - icon: "fas fa-bolt"
        content: "Ajuster la couleur d'arrière-plan du fichier converti"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "Rasteriser et convertir des documents en SVG, HTML et CSS"

      # feature loop
      - icon: "fas fa-code"
        content: "Obtenez une représentation HTML, image ou PDF des documents grâce au rendu"

      # feature loop
      - icon: "fas fa-cloud"
        content: "Versions en cache des documents pour accélérer le temps de chargement"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "Configurer les répertoires de polices personnalisés"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "Appliquer les normes d'encodage aux documents Word, Excel et e-mail"

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "Rendre des documents à distance sur FTP ou Cloud Storage"

      # feature loop
      - icon: "fas fa-border-all"
        content: "Supprimer ou conserver les annotations et les commentaires pendant le rendu"

      # feature loop
      - icon: "fas fa-wrench"
        content: "Afficher les pages de document sous forme de pages HTML distinctes"

      # feature loop
      - icon: "fas fa-columns"
        content: "Rendre les diapositives et les pages masquées et appliquer la réorganisation des pages au document rendu"

      # feature loop
      - icon: "fas fa-file-word"
        content: "Rendre une plage de pages, des pages spécifiques ou toutes les pages en HTML"

      # feature loop
      - icon: "fas fa-envelope"
        content: "Afficher ou masquer les commentaires du document"

      # feature loop
      - icon: "fas fa-print"
        content: "Créer du code HTML réactif pour certains formats de document via le rendu"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "Réduire la taille du fichier résultant du rendu HTML en excluant les polices"

      # feature loop
      - icon: "fas fa-lock"
        content: "Supprimer les commentaires, les espaces blancs supplémentaires, etc., pour réduire la sortie HTML et CSS"

      # feature loop
      - icon: "fas fa-file-code"
        content: "Utiliser les coordonnées du document source pour lire le texte contenu"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "Afficher/masquer la bordure de cellule dans les feuilles Excel de la sortie rendue"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "Rendre le nombre spécifique de lignes de chaque page dans une feuille Excel"

      # feature loop
      - icon: "fas fa-heading"
        content: "Modèle de rendu et toutes les mises en page non vides ou une mise en page particulière d'un fichier CAO"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "Rendre les éléments dans les fichiers de données Outlook (OST/PST) au format PDF"

      # feature loop
      - icon: "fas fa-cube"
        content: "Rendu en mosaïque ou rendu par coordonnées de documents CAO sous forme d'image, HTML ou PDF"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "Définir des restrictions d'impression lors du rendu au format PDF"

    more_feature :
      # more_feature_loop
      - title: "API efficace et fiable pour la visualisation de documents"
        content: |
          L'API GroupDocs.Viewer for Java peut être utilisée pour visualiser, restituer et afficher des documents de plus de 150 formats de fichiers différents. Cela se fait de manière fiable et efficace tout en gardant intact le contenu ainsi que la structure du document. L'exemple suivant montre le niveau de facilité avec lequel l'API GroupDocs.Viewer pour Java restitue un fichier DOCX en tant que fichier image à l'aide de Java :
          
          ```java
          // Initialiser la visionneuse
          Viewer viewer = new Viewer("sample.docx");
          // Créer des options d'affichage
          PdfViewOptions viewOptions = new PdfViewOptions();
          // Convertir le fichier en PDF et vérifier la sortie dans le répertoire actuel
          viewer.view(viewOptions);
          ```
      # more_feature_loop
      - title: "Effectuer des transformations lors du rendu de documents"
        content: "L'API GroupDocs.Viewer pour Java vous offre diverses options de transformation à appliquer sur le document rendu pour une vue et un affichage plus personnalisés. Vous pouvez faire pivoter les pages en fournissant l'angle. Vous pouvez l'ordre des pages rendues. Appliquez un texte spécifique en tant que filigrane aux pages ou aux images rendues. Grâce à GroupDocs.Viewer pour l'API Java, vous avez également la possibilité d'ajouter des polices personnalisées au document en cours de rendu."

      # more_feature_loop
      - title: "Utilisation des pièces jointes aux e-mails"
        content: "L'API GroupDocs.Viewer pour Java vous permet de récupérer des pièces jointes spécifiques ou toutes les pièces jointes d'un e-mail. Une fois que vous avez obtenu les pièces jointes requises, vous pouvez convertir ces fichiers joints en images ou en HTML."

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Viewer propose des API de visualisation de documents pour d'autres environnements de développement populaires"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Viewer for .NET"
          image: "/border/groupdocs-viewer-net.svg"
          product: "GroupDocs.Viewer"
          platform: ".NET"
          link: "/viewer/net/"

############################# Back to top ###############################
back_to_top:
  enable: true
---