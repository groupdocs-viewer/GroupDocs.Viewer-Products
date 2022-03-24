---
############################# Static ############################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: ".NET Document Viewer API, Rendu PDF Word Excel Image HTML Diagramme"
head_description: "Visualiseur de fichiers C# ASP.NET et API de rendu. Ajouter une visionneuse PDF, une visionneuse Word, une visionneuse Excel, une visionneuse d'images, une visionneuse HTML, des fonctionnalités de visionneuse d'e-mails dans les applications .NET."

############################# Header ############################
title: "Rendre et afficher des documents via l'API .NET"
description: "API de visionneuse de documents .NET pour rendre plus de 170 formats de documents en PDF, HTML et image avec de puissantes options de configuration."
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Télécharger la version d'essai gratuite"
    link: "https://downloads.groupdocs.com/viewer/net"

############################# SubMenu ############################
submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Viewer for .NET"
        image: "/border/groupdocs-viewer-net.svg"
        product: "GroupDocs.Viewer"
        platform: ".NET"

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
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Pricing"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# Aperçu ############################
overview:
    enable: true
    content: |
      Les API GroupDocs.Viewer pour .NET vous aident à créer des applications puissantes en C#, ASP.NET et d'autres technologies basées sur .NET, qui peuvent restituer et afficher des documents et des images de plus de 170 formats de fichiers sans installer de logiciel externe. La bibliothèque de visionneuse de fichiers pixellise les documents, puis les convertit en SVG + HTML + CSS pour optimiser l'expérience globale de rendu des documents pour la visualisation des documents commerciaux, des images, des fichiers texte, des diagrammes, des graphiques, des pièces jointes aux e-mails et des fichiers PDF avec rapidité, texte réel et haute fidélité dans vos applications. Vous avez la possibilité d'ajouter des fonctionnalités de visualisation et de lecture de documents dans vos applications pour afficher un document entier, un document partiel, une plage de pages/cellules spécifiques, une couche de document individuelle, avec ou sans annotations et commentaires pour les formats de fichiers pris en charge.

      GroupDocs.Viewer pour .NET met en cache la sortie des documents rendus sur le disque local par défaut. Tout type de stockage de cache externe est également pris en charge en mettant en œuvre des interfaces appropriées - Amazon S3, Dropbox, Google Drive, Windows Azure, Redis ou tout autre.
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          Voici un aperçu de GroupDocs.Viewer pour .NET :
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Aperçu"
          content: |
            * Afficher plus de 170 types de documents
            * Obtenir HTML, Image, Version PDF
            * Rotate &amp; Reorder
            * Appliquer le filigrane
            * Cache pour un processus rapide
            * Ajouter des polices personnalisées
            * Appliquer les normes d'encodage
            * Gestionnaire de données d'entrée personnalisé
            * Rendu avec suivi des modifications
            * Rendu en HTML réactif
            * Render PDF &amp; CAD Layers
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Viewer pour .NET prend en charge l'affichage de tous les [formats de fichiers de documents](https://docs.groupdocs.com/viewer/net/supported-document-formats/). Avec seulement quelques lignes de code, ajoutez une visionneuse PDF, Microsoft Office Word, une feuille de calcul Excel, une image, HTML, un e-mail Outlook, OneNote, des capacités de visualisation de projet et de graphiques dans vos applications .NET.

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
                * **Various:** OBJ, EPUB, MOBI, DjVu, XML, VCF, VCARD, NUMBER, NSF

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
          GroupDocs.Viewer for .NET prend en charge la suite Systèmes d'exploitation, Frameworks & Directeur chargé d'emballages:
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Systèmes d'exploitation"
              content: |
                * Bureau Windows
                * Serveur Windows
                * Microsoft Azure
                * Linux

            # table loop
            - icon: "fas fa-code"
              title: "Cadres pris en charge"
              content: |
                * .NET Framework 2.0 ou supérieur
                * .NET Core 3.1
                * .NET 5 ou supérieur

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-box"
              title: "Directeur chargé d'emballage"
              content: |
                * NuGet

            # table loop
            - icon: "fas fa-tools"
              title: "Environnements de développement"
              content: |
                * Microsoft Visual Studio
                * Code Visual Studio
                * CLI .NET

############################# Caractéristiques ############################
features:
    enable: true
    title: "GroupDocs.Viewer for .NET Caractéristiques"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "Rasteriser les documents et les convertir en SVG, HTML et CSS"

      # feature loop
      - icon: "fas fa-eye"
        content: "Convertir du texte en HTML et rendre des documents pour obtenir une représentation HTML, image ou PDF"

      # feature loop
      - icon: "fas fa-bolt"
        content: "Temps de chargement plus rapide à l'aide des versions mises en cache des documents"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "Convertir des présentations avec des formes et du texte avec des effets 3D"

      # feature loop
      - icon: "fas fa-code"
        content: "Encoder des documents Word, Excel et e-mail selon la norme d'encodage souhaitée"

      # feature loop
      - icon: "fas fa-cloud"
        content: "Rendre des documents situés sur des emplacements FTP ou de stockage dans le cloud"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "Exclure les polices lors du rendu au format HTML pour réduire la taille du fichier résultant"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "Réduisez la sortie CSS et HTML en supprimant les commentaires, les espaces blancs supplémentaires, etc."

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "Lire le texte contenu dans un document source à travers ses coordonnées"

      # feature loop
      - icon: "fas fa-border-all"
        content: "Afficher/Masquer les lignes de grille des feuilles Excel dans la représentation de sortie"

      # feature loop
      - icon: "fas fa-wrench"
        content: "Spécifiez le nombre de lignes dans une feuille Excel à afficher sur chaque page"

      # feature loop
      - icon: "fas fa-columns"
        content: "Ignorer les colonnes vides lors du rendu des documents de feuille de calcul"

      # feature loop
      - icon: "fas fa-file-word"
        content: "Rendre des documents Word en pages HTML, images ou PDF, avec suivi des modifications"

      # feature loop
      - icon: "fas fa-envelope"
        content: "Rendu des pièces jointes aux e-mails sous forme de fichiers originaux, d'images ou de représentation HTML"

      # feature loop
      - icon: "fas fa-print"
        content: "Définir des restrictions d'impression sur les documents PDF"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "Rendre le contenu/fichiers contenus dans les archives ZIP en tant que pièces jointes"

      # feature loop
      - icon: "fas fa-lock"
        content: "Obtenir des pièces jointes à partir de documents protégés par mot de passe"

      # feature loop
      - icon: "fas fa-file-code"
        content: "Rendre les formats de fichier des langages de programmation sous forme de texte brut"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "Ajuster les couleurs d'arrière-plan lors de l'affichage des dessins CAO"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "Affichez des documents Excel et convertissez-les en PDF, HTML, JPG et PNG"

      # feature loop
      - icon: "fas fa-heading"
        content: "Obtenir les noms de feuille de calcul à partir du fichier Excel - Afficher les en-têtes de colonne et les numéros de ligne de la feuille de calcul"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "Afficher et convertir des documents Microsoft Project avec des notes"

      # feature loop
      - icon: "fas fa-cube"
        content: "Convertissez des dessins CAO en SVG pour une meilleure expérience de visualisation et de zoom"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "Choisissez de rendre les figures Visio sans schéma"

    more_feature :
      # more_feature_loop
      - title: "Afficher les documents de manière efficace et fiable"
        content: |
          À l'aide de l'API GroupDocs.Viewer, vous pouvez afficher plus de 170 formats de documents de manière efficace et fiable avec l'intégrité du contenu et de la structure du document intacte. L'exemple de code suivant montre à quel point il est facile d'afficher la représentation HTML d'un document DOCX :

          ```cs
          // Visualiseur d'instanciation
          using (Viewer viewer = new Viewer("sample.docx")
          {
              // Définir les options d'affichage
              HtmlViewOptions options = HtmlViewOptions.ForEmbeddedResources();
              // Convertir un fichier en HTML avec des ressources intégrées
              viewer.View(options);
          }
          ```
      # more_feature_loop
      - title: "Appliquer la transformation à la sortie rendue"
        content: "Vous pouvez effectuer diverses transformations sur le document de sortie rendu à l'aide de GroupDocs.Viewer pour l'API .NET. Ces options de transformation vous permettent de contrôler la façon dont vous présentez la sortie rendue pour l'affichage. Les transformations disponibles sont l'option de rotation de page, l'option de réorganisation de page et l'application d'un filigrane de texte."

      # more_feature_loop
      - title: "Travailler avec des fichiers de données Outlook"
        content: "GroupDocs.Viewer pour l'API .NET peut restituer les éléments des fichiers de données Outlook (OST/PST) sous forme de fichiers PDF, HTML et image. Our Viewer API also has the ability to obtain the list of folders contained in Outlook Data Files. Using GroupDocs.Viewer for .NET API, you can specify the folder to render from Outlook Data Files. De même, vous pouvez également obtenir des messages électroniques contenus dans les formats OST/PST en tant que pièces jointes. GroupDocs.Viewer pour .NET vous permet également de filtrer les messages des formats OST/PST en fonction du sujet, du contenu ou de l'expéditeur."

      # more_feature_loop
      - title: "Travailler avec des documents CAO"
        content: "GroupDocs.Viewer pour l'API .NET peut rendre le modèle et toutes les mises en page non vides ou rendre une mise en page spécifique d'un fichier CAO. GroupDocs.Viewer pour l'API .NET prend également en charge le rendu en mosaïque ou le rendu par coordonnées de documents CAO en image, HTML ou PDF. Vous pouvez également obtenir des statuts de couche pour les documents CAO."

############################# Testimonials ###############################
testimonials:
  enable: true

  testimonial:
    # testimonial item loop
    - name: "Mats Oustad"
      designation: "Senior Consultant/Partner at Novanet AS"
      content: "Après avoir implémenté et utilisé GroupDocs.Viewer pour .NET dans le projet, il semble fonctionner très bien. J'ai testé avec beaucoup de documents et jusqu'ici tout va bien. Tout ce que j'y ai lancé s'affiche bien et a l'air aussi bien que dans une visionneuse PDF ou MS Word."
              
    # testimonial item loop
    - name: "Martin Lasarga"
      designation: "Product Manager at Axentria ECM by G.S.I."
      content: "Excellent service et excellents produits. Ils ont été extrêmement utiles et réactifs pendant le processus de mise en œuvre de GroupDocs.Viewer pour .NET, je ne saurais trop les recommander."

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Viewer propose des API de visualisation de documents pour d'autres environnements de développement populaires"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Viewer for Java"
          image: "/border/groupdocs-viewer-java.svg"
          product: "GroupDocs.Viewer"
          platform: "Java"
          link: "/viewer/java/"

############################# Back to top ###############################
back_to_top:
  enable: true
---
