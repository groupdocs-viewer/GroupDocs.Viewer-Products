---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: fr

############################# Head #############################
head_title: "Java IFC Viewer API - Rendre et afficher IFC dans les applications Java"
head_description: "Affichez les fichiers IFC dans les applications Java, J2EE, J2SE. Prend en charge l'affichage de plus de 170 formats de documents et de fichiers image en mode HTML, PDF ou image avec des fonctionnalités avancées pour gérer les options d'affichage des documents."

############################# Header ############################
title: "Rendre et afficher IFC en Java" 
description: "API de visualisation de fichiers IFC native et hautes performances pour les applications basées sur Java, J2EE et J2SE, prenant en charge un large éventail de fonctionnalités supplémentaires pour personnaliser l'apparence du format de document de sortie." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Télécharger la version d'essai gratuite"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "À propos de l'API GroupDocs.Viewer pour Java" 
    content: |
        Permettez à vos applications Java d'afficher plus de 170 formats de fichiers en modes HTML, PDF ou image à l'aide des API GroupDocs.Viewer pour Java sans aucun logiciel supplémentaire installé ; tels que Microsoft Office, Apache Open Office, Adobe Acrobat Reader, etc. Les développeurs peuvent facilement visualiser toutes les images et tous les types de documents populaires, notamment Microsoft Office, OpenDocument, HTML, PDF, Archive, Diagrammes, Photoshop, AutoCAD et les formats de langage de programmation dans les applications Java avec rendu rapide et de haute qualité.

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
              text: "Référence API"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Exemples de codes"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Démos en direct"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Tarification"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "Étapes pour rendre le fichier IFC dans Java" 
    content_left: |
        Avec [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/), vous pouvez rendre IFC au format HTML, JPEG, PNG ou PDF en quelques étapes.

        * Ajoutez [GroupDocs.Viewer for Java](https://releases.groupdocs.com/viewer/java/) en tant que dépendance à votre projet. 
        * Créez une instance de la classe Viewer et chargez le fichier IFC avec le chemin complet. 
        * Définissez les options pour rendre le fichier IFC au format HTML, PNG, JPEG ou PDF. 
        * Rendre le fichier et vérifier la sortie dans le répertoire courant. 
        
    title_right: "Configuration requise" 
    content_right: |
        Les API GroupDocs.Viewer pour Java sont prises en charge sur toutes les principales plates-formes et systèmes d'exploitation. Avant d'exécuter le code ci-dessous, assurez-vous que les prérequis suivants sont installés sur votre système.

        * Systèmes d'exploitation : Microsoft Windows, Linux, MacOS 
        * Environnements de développement : NetBeans, IntelliJ IDEA, Eclipse etc. 
        * Frameworks : J2SE 8.0 (1.8) ou supérieur (par exemple Java 17) 
    code: |
        ```java
                        
            // Set up input IFC file
            String filePath = "input.ifc";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render IFC file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "IFC Démo en direct du spectateur"
    content: |
        Affichez le fichier IFC dès maintenant en visitant le site Web [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/ifc).
    lang: "fr"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Rendu et affichage d'autres formats de fichiers à l'aide de Java"
    exclude: "IFC"
    content: |
        API de visualisation de documents et d'images multi-formats pour Java. Affichez ci-dessous certains des formats de fichiers populaires sans aucune visionneuse externe.
    format: 
        # format loop 1
        - name: "Rendu DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Document XML ouvert Microsoft Word" 

        # format loop 2
        - name: "Rendu CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "Fichier CorelDRAW" 

        # format loop 3
        - name: "Rendu PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "Présentation PowerPoint Open XML" 

        # format loop 4
        - name: "Rendre XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Feuille de calcul Open XML Microsoft Excel" 

        # format loop 5
        - name: "Rendu DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "Dessin AutoCAD"

        # format loop 6
        - name: "Rendu XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "Fichier XML"

        # format loop 7
        - name: "Rendu PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Document Adobe Photoshop"

        # format loop 8
        - name: "Rendre le fichier Adobe Illustrator"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Illustration d'Adobe Illustrator"

        # format loop 9
        - name: "Rendu DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Document Microsoft Word" 

        # format loop 10
        - name: "Rendu TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Fichier texte brut" 

        # format loop 11
        - name: "Rendu DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Fichier de format d'échange de dessin"  
          
        # format loop 12
        - name: "Rendu VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "Fichier vCard"  
              
        # format loop 13
        - name: "Rendu SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Graphique vectoriel évolutif" 
          
        # format loop 14
        - name: "Rendu HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Fichier de langage de balisage hypertexte" 
          
        # format loop 15
        - name: "Rendu PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Fichier de format de document portable"
          
        # format loop 16
        - name: "Rendu JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "Images JPEG"
          
        # format loop 17
        - name: "Rendu PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Graphique réseau portable" 
          
        # format loop 18
        - name: "Rendu EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "Message électronique" 
          
        # format loop 19
        - name: "Rendu RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Fichier au format RTF" 
          
        # format loop 20
        - name: "ODT de rendu"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "Document texte OpenDocument" 
          
        # format loop 21
        - name: "Rendu CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Fichier de valeurs séparées par des virgules" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
