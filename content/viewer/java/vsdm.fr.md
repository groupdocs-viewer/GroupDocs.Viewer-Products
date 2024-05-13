---
############################# Static ############################
layout: "format"
date: 2024-05-13T10:14:32
draft: false
lang: fr
product: "Viewer"
product_tag: "viewer"
platform: "Java"
platform_tag: "java"

############################# Head #############################
head_title: "API Java VSDM Viewer - rendu et affichage VSDM dans les applications Java"
head_description: "Affichez les fichiers VSDM dans les applications Java, J2EE, J2SE. Prend en charge l'affichage de plus de 180 formats de documents et de fichiers image en mode HTML, PDF ou image avec des fonctionnalités avancées pour gérer les options d'affichage des documents."

############################# Header ############################
title: "Rendu et affichage VSDM en Java" 
description: "API de visualisation de fichiers VSDM native et hautes performances pour les applications basées sur Java, J2EE et J2SE, prenant en charge un large éventail de fonctionnalités supplémentaires pour personnaliser l'apparence du format du document de sortie." 
subtitle: "Solution de rendu de documents" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "Téléchargement gratuit de Maven"
      link: "https://releases.groupdocs.com/viewer/java/"



############################# About ############################
about:
    enable: true
    title: "À propos de l'API GroupDocs.Viewer pour Java"
    link: "/viewer/java/"
    link_title: "Apprendre encore plus"
    picture: "about_viewer.svg" # 480 X 400
    content: |
      Permettez à vos applications Java d'afficher plus de 180 formats de fichiers en modes HTML, PDF ou image à l'aide des API GroupDocs.Viewer pour Java sans aucun logiciel supplémentaire installé ; tels que Microsoft Office, Apache Open Office, Adobe Acrobat Reader, etc. Les développeurs peuvent facilement visualiser toutes les images et types de documents populaires, notamment Microsoft Office, OpenDocument, HTML, PDF, Archive, Diagrams, Photoshop, AutoCAD et les formats de langage de programmation dans les applications Java avec rendu rapide et de la plus haute qualité.



############################# Steps ############################
steps:
    enable: true
    title: "Étapes pour restituer le fichier VSDM dans Java" 
    content: |
      Avec <a href='https://products.groupdocs.com/viewer/java/'>GroupDocs.Viewer</a>, vous pouvez restituer VSDM au format HTML, JPEG, PNG ou PDF en quelques étapes.
      
      1. Ajoutez <a href='https://releases.groupdocs.com/viewer/java/'>GroupDocs.Viewer for Java</a> comme dépendance à votre projet. 
      2. Créez une instance de la classe Viewer et chargez le fichier VSDM avec le chemin complet.  
      3. Définissez les options pour restituer le fichier VSDM au format HTML, PNG, JPEG ou PDF. 
      4. Rendu le fichier et vérifiez la sortie dans le répertoire actuel. 
   
    code:
      platform: "java"
      copy_title: "Copie"
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
        copy_tip: "cliquez pour copier"
        copy_done: "copié"
      links:
        #  loop
        - title: "Plus d'exemples"
          link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Java"
        #  loop
        - title: "Documentation"
          link: "https://docs.groupdocs.com/viewer/java/"
          
      content: |
        ```java {style=abap}

        // Configurer le fichier d'entrée VSDM
        String filePath = "input.vsdm";

        // Instancier GroupDocs.Viewer
        try (Viewer viewer = new Viewer(filePath))
        {
            // Définir les options d'affichage
            HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                
            // Rendre le fichier VSDM au format HTML avec des ressources intégrées
            viewer.view(viewOptions);
        }

        ```
            

############################# Actions ############################

actions:
  enable: true
  title: "Prêt à commencer?"
  description: "Essayez les fonctionnalités de GroupDocs.Viewer gratuitement ou demandez une licence"
  items:
    #  loop
    - title: "Téléchargement Maven"
      link: "https://releases.groupdocs.com/viewer/java/"
      color: "red"
        #  loop
    - title: "Licence"
      link: "https://purchase.groupdocs.com/pricing/viewer/java/"
      color: "light"



############################# More Formats #####################
more_formats:
    enable: true
    title: "Rendre d'autres formats de fichiers à l'aide de Java"
    exclude: "VSDM"
    description: "API de visualisation de documents et d'images multiformats pour Java. Affichez certains des formats de fichiers populaires ci-dessous sans aucun lecteur externe."
    items: 
        # format loop 1
        - name: "Rendre DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Open XML Document" 

        # format loop 2
        - name: "Rendre le CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "CorelDRAW File" 

        # format loop 3
        - name: "Rendu PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint Open XML Presentation" 

        # format loop 4
        - name: "Rendu XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet" 

        # format loop 5
        - name: "Rendu DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "AutoCAD Drawing"

        # format loop 6
        - name: "Rendre XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "XML File"

        # format loop 7
        - name: "Rendu PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Adobe Photoshop Document"

        # format loop 8
        - name: "Render AI"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Adobe Illustrator Artwork"

        # format loop 9
        - name: "Rendu DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Microsoft Word Document" 

        # format loop 10
        - name: "Rendu TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Plain Text File" 

        # format loop 11
        - name: "Rendu DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Drawing Exchange Format File"  
          
        # format loop 12
        - name: "Rendu VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "vCard File"  
              
        # format loop 13
        - name: "Rendu SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Scalable Vector Graphic" 
          
        # format loop 14
        - name: "Rendre le HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "Rendre le PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Portable Document Format File"
          
        # format loop 16
        - name: "Rendu JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "JPEG Image"
          
        # format loop 17
        - name: "Rendu PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Portable Network Graphic" 
          
        # format loop 18
        - name: "Rendre EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "E-Mail Message" 
          
        # format loop 19
        - name: "Rendu RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Rich Text Format File" 
          
        # format loop 20
        - name: "Rendu ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "OpenDocument Text Document" 
          
        # format loop 21
        - name: "Rendu CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Comma-Separated Values File" 


---
