---
############################# Static ############################
layout: "format"
date: 2024-05-13T10:14:53
draft: false
lang: fr
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head #############################
head_title: "API de la visionneuse .NET ERB - lire, afficher, rendre en C# VB.NET"
head_description: "API de visualisation de documents .NET pour lire, restituer et afficher ERB dans tout type d'applications C#, ASP.NET, VB.NET et .NET Core."

############################# Header ############################
title: "ERB visionneuse de fichiers pour les applications C# .NET" 
description: "API de visualisation de documents .NET pour lire, restituer et afficher le fichier ERB dans tout type d'applications C#, ASP.NET, VB.NET et .NET Core. Affichez les fichiers rendus avec un véritable formatage et une mise en page en HTML5, PDF ou sous forme d'image en utilisant quelques lignes de code." 
subtitle: "Solution de rendu de documents" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "Téléchargement gratuit de Nugets"
      link: "https://nuget.org/packages/GroupDocs.Viewer"



############################# About ############################
about:
    enable: true
    title: "À propos de l'API GroupDocs.Viewer pour .NET"
    link: "/viewer/net/"
    link_title: "Apprendre encore plus"
    picture: "about_viewer.svg" # 480 X 400
    content: |
      Commencez à visualiser plus de 190 formats de documents populaires dans vos applications .NET à l'aide des API GroupDocs.Viewer pour .NET en ajoutant quelques lignes de code. Les développeurs peuvent facilement afficher PDF, traitement de texte, feuille de calcul Excel, présentation, Visio, projet, Outlook et de nombreux autres formats de documents populaires en modes HTML5, image ou PDF. Le rendu du document est rapide, identique au fichier source d'origine, et ne nécessite pas l'installation de logiciels supplémentaires ni d'autres bibliothèques externes.



############################# Steps ############################
steps:
    enable: true
    title: "Étapes pour restituer le fichier ERB dans C#" 
    content: |
      Avec <a href='https://products.groupdocs.com/viewer/net/'>GroupDocs.Viewer</a>, vous pouvez restituer ERB au format HTML, JPEG, PNG ou PDF en quelques étapes.
      
      1. Installez <a href='https://www.nuget.org/packages/groupdocs.viewer'>GroupDocs.Viewer pour .NET</a> à l'aide de votre gestionnaire de packages préféré. 
      2. Créez une instance de la classe Viewer et chargez le fichier ERB avec le chemin complet.  
      3. Définissez les options pour restituer le fichier ERB au format HTML, PNG, JPEG ou PDF. 
      4. Rendu le fichier et vérifiez la sortie dans le répertoire actuel. 
   
    code:
      platform: "net"
      copy_title: "Copie"
      install:
        command: "dotnet add package GroupDocs.Viewer"
        copy_tip: "cliquez pour copier"
        copy_done: "copié"
      links:
        #  loop
        - title: "Plus d'exemples"
          link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
        #  loop
        - title: "Documentation"
          link: "https://docs.groupdocs.com/viewer/net/"
          
      content: |
        ```csharp {style=abap}

        // Configurer le fichier d'entrée ERB
        string filePath = "input.erb";

        // Instancier GroupDocs.Viewer
        using (Viewer viewer = new Viewer(filePath))
        {
            // Définir les options d'affichage
            HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                
            // Rendre le fichier ERB au format HTML avec des ressources intégrées
            viewer.View(viewOptions);
        }

        ```            


############################# Actions ############################

actions:
  enable: true
  title: "Prêt à commencer?"
  description: "Essayez les fonctionnalités de GroupDocs.Viewer gratuitement ou demandez une licence"
  items:
    #  loop
    - title: "Téléchargement de Nugets"
      link: "https://nuget.org/packages/GroupDocs.Viewer"
      color: "red"
        #  loop
    - title: "Licence"
      link: "https://purchase.groupdocs.com/pricing/viewer/net/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "Rendre d'autres formats de fichiers en utilisant C#"
    exclude: "ERB"
    description: "API de visualisation de documents et d'images multiformats pour .NET. Affichez certains des formats de fichiers populaires ci-dessous sans aucun lecteur externe."
    items: 
        # format loop 1
        - name: "Rendre DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word Open XML Document" 

        # format loop 2
        - name: "Rendre le CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "CorelDRAW File" 

        # format loop 3
        - name: "Rendu PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint Open XML Presentation" 

        # format loop 4
        - name: "Rendu XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet" 

        # format loop 5
        - name: "Rendu DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "AutoCAD Drawing"

        # format loop 6
        - name: "Rendre XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "XML File"

        # format loop 7
        - name: "Rendu PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Adobe Photoshop Document"

        # format loop 8
        - name: "Render AI"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Adobe Illustrator Artwork"

        # format loop 9
        - name: "Rendu DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Microsoft Word Document" 

        # format loop 10
        - name: "Rendu TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Plain Text File" 

        # format loop 11
        - name: "Rendu DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Drawing Exchange Format File"  
          
        # format loop 12
        - name: "Rendu VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "vCard File"  
              
        # format loop 13
        - name: "Rendu SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Scalable Vector Graphic" 
          
        # format loop 14
        - name: "Rendre le HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "Rendre le PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Portable Document Format File"
          
        # format loop 16
        - name: "Rendu JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "JPEG Image"
          
        # format loop 17
        - name: "Rendu PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Portable Network Graphic" 
          
        # format loop 18
        - name: "Rendre EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "E-Mail Message" 
          
        # format loop 19
        - name: "Rendu RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Rich Text Format File" 
          
        # format loop 20
        - name: "Rendu ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "OpenDocument Text Document" 
          
        # format loop 21
        - name: "Rendu CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Comma-Separated Values File" 



---
