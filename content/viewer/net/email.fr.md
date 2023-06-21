---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: fr

############################# Head #############################
head_title: ".NET eMail API Viewer - Lire, Afficher, Rendre en C# VB.NET"
head_description: "API de visionneuse de documents .NET pour lire, restituer et afficher eMail dans tout type d'applications C#, ASP.NET, VB.NET et .NET Core."

############################# Header ############################
title: "eMail Visionneuse de fichiers pour les applications C# .NET" 
description: "API de visionneuse de documents .NET pour lire, restituer et afficher le fichier eMail dans tout type d'applications C #, ASP.NET, VB.NET et .NET Core. Affichez les fichiers rendus avec une mise en forme et une mise en page authentiques au format HTML5, PDF ou sous forme d'image en utilisant quelques lignes de code." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Télécharger la version d'essai gratuite"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "À propos de l'API GroupDocs.Viewer pour .NET" 
    content: |
        Commencez à visualiser plus de 190 formats de documents populaires dans vos applications .NET à l'aide de GroupDocs.Viewer pour les API .NET en ajoutant quelques lignes de code. Les développeurs peuvent facilement afficher PDF, traitement de texte, feuille de calcul Excel, présentation, Visio, projet, Outlook et de nombreux autres formats de documents populaires en modes HTML5, image ou PDF. Le rendu du document est rapide, identique au fichier source d'origine et ne nécessite pas l'installation de logiciels supplémentaires ou d'autres bibliothèques externes.

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
    title_left: "Étapes pour rendre le fichier eMail dans C#" 
    content_left: |
        Avec [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/), vous pouvez rendre eMail au format HTML, JPEG, PNG ou PDF en quelques étapes.

        * Installez [GroupDocs.Viewer pour .NET](https://www.nuget.org/packages/groupdocs.viewer) à l'aide de votre gestionnaire de packages préféré. 
        * Créez une instance de la classe Viewer et chargez le fichier eMail avec le chemin complet. 
        * Définissez les options pour rendre le fichier eMail au format HTML, PNG, JPEG ou PDF. 
        * Rendre le fichier et vérifier la sortie dans le répertoire courant. 
        
    title_right: "Configuration requise" 
    content_right: |
        Les API GroupDocs.Viewer pour .NET sont prises en charge sur toutes les principales plateformes et systèmes d'exploitation. Avant d'exécuter le code ci-dessous, assurez-vous que les prérequis suivants sont installés sur votre système.

        * Systèmes d'exploitation : Microsoft Windows, Linux, MacOS 
        * Environnements de développement : Microsoft Visual Studio, Visual Studio Code, .NET CLI 
        * Cadres : .NET Framework, .NET Standard, .NET Core, .NET 
    code: |
        ```cs
                        
            // Set up input eMail file
            string filePath = "input.msg";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render eMail file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "eMail Démo en direct du spectateur"
    content: |
        Affichez le fichier eMail dès maintenant en visitant le site Web [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/email).
    lang: "fr"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Rendu et affichage d'autres formats de fichiers à l'aide de C#"
    exclude: "eMail"
    content: |
        API de visualisation de documents et d'images multi-formats pour .NET. Affichez ci-dessous certains des formats de fichiers populaires sans aucune visionneuse externe.
    format: 
        # format loop 1
        - name: "Rendu DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Document XML ouvert Microsoft Word" 

        # format loop 2
        - name: "Rendu CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "Fichier CorelDRAW" 

        # format loop 3
        - name: "Rendu PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "Présentation PowerPoint Open XML" 

        # format loop 4
        - name: "Rendre XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Feuille de calcul Open XML Microsoft Excel" 

        # format loop 5
        - name: "Rendu DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "Dessin AutoCAD"

        # format loop 6
        - name: "Rendu XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "Fichier XML"

        # format loop 7
        - name: "Rendu PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Document Adobe Photoshop"

        # format loop 8
        - name: "Rendre le fichier Adobe Illustrator"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Illustration d'Adobe Illustrator"

        # format loop 9
        - name: "Rendu DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Document Microsoft Word" 

        # format loop 10
        - name: "Rendu TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Fichier texte brut" 

        # format loop 11
        - name: "Rendu DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Fichier de format d'échange de dessin"  
          
        # format loop 12
        - name: "Rendu VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "Fichier vCard"  
              
        # format loop 13
        - name: "Rendu SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Graphique vectoriel évolutif" 
          
        # format loop 14
        - name: "Rendu HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Fichier de langage de balisage hypertexte" 
          
        # format loop 15
        - name: "Rendu PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Fichier de format de document portable"
          
        # format loop 16
        - name: "Rendu JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "Images JPEG"
          
        # format loop 17
        - name: "Rendu PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Graphique réseau portable" 
          
        # format loop 18
        - name: "Rendu EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "Message électronique" 
          
        # format loop 19
        - name: "Rendu RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Fichier au format RTF" 
          
        # format loop 20
        - name: "ODT de rendu"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "Document texte OpenDocument" 
          
        # format loop 21
        - name: "Rendu CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Fichier de valeurs séparées par des virgules" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
