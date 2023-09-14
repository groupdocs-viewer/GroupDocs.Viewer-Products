---
############################# Static ##########################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

lang: fr
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: "API de visionneuse de documents .NET, rendu PDF Word Excel Image HTML Diagramme"
head_description: "Visualiseur de fichiers C# ASP.NET et API de rendu. Ajoutez une visionneuse PDF, une visionneuse Word, une visionneuse Excel, une visionneuse d'images, une visionneuse HTML, des fonctionnalités de visionneuse de courrier électronique dans les applications .NET."

############################# Header ##########################
title: "Rendre et afficher des documents via l'API .NET"
description: "API de visionneuse de documents .NET pour rendre plus de 190 formats de documents en PDF, HTML et image avec de puissantes options de configuration."
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
              text: "Aperçu"

            # button loop
            - link: "#features"
              text: "Caractéristiques"

            # button loop
            - link: "#support"
              text: "Soutien"

            # button loop
            - link: "https://products.groupdocs.app/viewer/total"
              text: "Démo en direct"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Tarification"

    right:
        link_download: "https://www.nuget.org/packages/GroupDocs.Viewer"
        link_learn: "https://docs.groupdocs.com/viewer/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    content: |
      Les API GroupDocs.Viewer pour .NET vous aident à créer des applications puissantes en C#, ASP.NET et d'autres technologies basées sur .NET, qui peuvent restituer et afficher des documents et des images de plus de 190 formats de fichiers sans installer de logiciel externe. La bibliothèque de visionneuse de fichiers pixellise les documents, puis les convertit en SVG + HTML + CSS pour optimiser l'expérience globale de rendu des documents pour la visualisation des documents commerciaux, des images, des fichiers texte, des diagrammes, des graphiques, des pièces jointes aux e-mails et des fichiers PDF avec rapidité, texte réel et haute fidélité dans vos applications. Vous avez la possibilité d'ajouter des fonctionnalités de visualisation et de lecture de documents dans vos applications pour afficher un document entier, un document partiel, une plage de pages/cellules spécifiques, une couche de document individuelle, avec ou sans annotations et commentaires pour les formats de fichiers pris en charge.
       
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
            * Afficher plus de 190 types de documents 
            * Obtenir un fichier au format HTML, Image, PDF 
            * Rotation et réorganisation 
            * Appliquer le filigrane 
            * Cache pour un processus rapide 
            * Ajouter des polices personnalisées 
            * Appliquer les normes d'encodage 
            * Gestionnaire de données d'entrée personnalisé 
            * Rendu avec suivi des modifications 
            * Rendu en HTML réactif 
            * Rendu des couches PDF et CAO 
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Viewer pour .NET prend en charge l'affichage de tous les formats de fichiers de documents courants. Avec seulement quelques lignes de code, ajoutez une visionneuse PDF, Microsoft Office Word, une feuille de calcul Excel, une image, HTML, un e-mail Outlook, OneNote, des capacités de visualisation de projet et de graphiques dans vos applications .NET.

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
                * **Fichiers de mise en page:** PDF, TEX, XPS, OXPS
                * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG, OTG, FODP, FODG
                * **Valeurs séparées par un délimiteur:** CSV, TSV
                * **la toile:** HTML, MHT, MHTML
                * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
                * **PostScript:** PS, EPS
                * **Les archives:** ZIP, TAR, BZ2, GZ, RAR, RAR5
                * **Divers:** OBJ, EPUB, MOBI, DjVu, XML, VCF, VCARD, NUMBERS, NSF

        right:
          enable: true
          table:
            # table loop
            - title: "Images, graphiques et diagrammes"
              content: |
                * **Images:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB
                * **Icône Windows:** ICO
                * **Image Vectorielle:** SVG, CDR, CMX, IGS, SVGZ
                * **Jpeg2000:** JP2, J2C, J2K, JPC, JPF, JPX, JPM
                * **Adobe Photoshop:** PSD, PSB
                * **Langage de commande de l'imprimante:** PCL
                * **Stéréo Lithographie (Impression 3D):** STL
                * **Classes de base de l'industrie:** IFC
                * **L'imagerie médicale:** DICOM
                * **Documents de traceur:** PLT, HPG
                * **Formats Web d'Autodesk Design:** DWF, DWG
                * **Dessin AutoCAD:** DWT, IFC, STL, CF2
                * **DGN basé sur ISFF (V7):** DGN

            # table loop
            - title: "Formats des langages de programmation"
              content: |
                * **Fichiers C/C++/C#:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
                * **Fichiers Java/JavaScript:** JAVA, JS, JSON, PROPERTIES
                * **Divers:** VB, PHP, SQL, PL, PY, PV, RB, RST, SASS, SCALA, SCM, SCRIPT, AS, AS3, ASM, BAT, CMAKE, CSS, DIFF, ERB, GROOVY, HAML, LESS, LOG, M, MAKE, MD, ML, MM, SH, SML, VIM, YAML

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Viewer pour .NET prend en charge les systèmes d'exploitation, frameworks et gestionnaires de packages suivants :
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Systèmes d'exploitation"
              content: |
                * Microsoft Windows Server 2003 et versions ultérieures 
                * Microsoft Windows XP et versions ultérieures 
                * Microsoft Windows 10 et 11 
                * Linux (Ubuntu, OpenSUSE, CentOS et autres) 
                * Mac OS X 

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
                * Visual Studio Code
                * .NET CLI

############################# Features ############################
features:
    enable: true
    title: "GroupDocs.Viewer pour les fonctionnalités .NET"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "Rastérisez les documents et convertissez-les en SVG, HTML et CSS"

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
        content: "Convertissez les dessins CAO en SVG pour une meilleure expérience de visualisation et de zoom"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "Choisissez de rendre les figures Visio sans schéma"

    more_feature:
      # more_feature_loop
      - title: "Afficher les documents de manière efficace et fiable"
        content: |
          À l'aide de l'API GroupDocs.Viewer, vous pouvez afficher plus de 190 formats de documents de manière efficace et fiable avec l'intégrité du contenu et de la structure du document intacte. L'exemple de code suivant montre à quel point il est facile d'afficher la représentation HTML d'un document DOCX :

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
      - title: "Appliquer la transformation à la sortie rendue"
        content: "Vous pouvez effectuer diverses transformations sur le document de sortie rendu à l'aide de GroupDocs.Viewer pour l'API .NET. Ces options de transformation vous permettent de contrôler la façon dont vous présentez la sortie rendue pour l'affichage. Les transformations disponibles sont l'option de rotation de page, l'option de réorganisation de page et l'application d'un filigrane de texte."

      # more_feature_loop
      - title: "Travailler avec des fichiers de données Outlook"
        content: "L'API GroupDocs.Viewer pour .NET peut restituer les éléments des fichiers de données Outlook (OST/PST) sous forme de fichiers PDF, HTML et image. Notre API Viewer a également la capacité d'obtenir la liste des dossiers contenus dans les fichiers de données Outlook. À l'aide de GroupDocs.Viewer pour l'API .NET, vous pouvez spécifier le dossier à afficher à partir des fichiers de données Outlook. De même, vous pouvez également obtenir des messages électroniques contenus dans les formats OST/PST sous forme de pièces jointes. GroupDocs.Viewer pour .NET vous permet également de filtrer les messages des formats OST/PST en fonction du sujet, du contenu ou de l'expéditeur."

      # more_feature_loop
      - title: "Travailler avec des documents CAO"
        content: "GroupDocs.Viewer pour l'API .NET peut rendre le modèle et toutes les mises en page non vides ou rendre une mise en page spécifique d'un fichier CAO. GroupDocs.Viewer pour l'API .NET prend également en charge le rendu en mosaïque ou le rendu par coordonnées de documents CAO en image, HTML ou PDF. Vous pouvez également obtenir des statuts de couche pour les documents CAO."

############################# Testimonials ###############################
testimonials:
  enable: true

  testimonial:
    # testimonial item loop
    - name: "Margot Baill"
      designation: "Directeur du développement de produits chez Hireology"
      content: "L'intégration de GroupDocs.Viewer pour l'API Cloud était simple avec leur fantastique SDK Ruby. Il n'y a pas beaucoup d'entreprises prêtes à travailler avec nous sur ce que nous voulons. C'est un excellent partenariat."

    # testimonial item loop
    - name: "Mats Oustad"
      designation: "Consultant Senior/Partenaire chez Novanet AS"
      content: "Après avoir implémenté et utilisé GroupDocs.Viewer pour .NET dans le projet, il semble très bien fonctionner. J'ai testé avec beaucoup de documents et jusqu'ici tout va bien. Tout ce que j'y ai lancé s'affiche bien et est aussi beau que dans une visionneuse PDF ou MS Word."
              
    # testimonial item loop
    - name: "Martin Lasarga"
      designation: "Chef de produit chez Axentria ECM by G.S.I."
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
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-viewer-java.png"
          product: "GroupDocs.Viewer"
          platform: "Java"
          link: "/viewer/java/"

############################# Back to top ###############################
back_to_top:
  enable: true
---
