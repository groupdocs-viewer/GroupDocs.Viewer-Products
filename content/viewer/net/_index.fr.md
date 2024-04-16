---
############################# Static ##########################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: fr
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Drop-down ############################
supported_platforms:
  items:
    # supported_platforms loop
    - title: ".NET"
      tag: "net"
    # supported_platforms loop
    - title: "Java"
      tag: "java"
    # supported_platforms loop
    - title: "Node.js"
      tag: "nodejs-java" 

############################# Head ############################
head_title: "API de visualisation de documents .NET, rendu PDF Word Excel Image HTML Diagramme"
head_description: "Visionneuse de fichiers C# ASP.NET et API de rendu. Ajoutez une visionneuse PDF, une visionneuse Word, une visionneuse Excel, une visionneuse d'images, une visionneuse HTML et des fonctionnalités de visionneuse de courrier électronique dans les applications .NET."

############################# Header ##########################
title: "Rendre et afficher des documents<br>à l'aide de l'API .NET"
description: "API de visualisation puissante pour restituer plus de 180 formats de documents au format PDF, HTML et Image avec des options de configuration polyvalentes."
words:
  for: "for"

actions:
  main: "Téléchargement gratuit de NuGet"
  main_link: "https://www.nuget.org/packages/GroupDocs.Viewer"
  alt: "Licence"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/net"
  title: "Prêt à commencer?"
  description: "Essayez les fonctionnalités de GroupDocs.Viewer gratuitement ou demandez une licence"

release:
  title: "Version {0} publiée"
  notes: "Nouveautés"
  downloads: "Téléchargements"
  link: "https://releases.groupdocs.com/viewer/net/release-notes/latest/"

code:
  title: "Rendre les fichiers PDF en C#"
  more: "Plus d'exemples"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
  install: "dotnet add package GroupDocs.Viewer"
  content: |
    ```csharp {style=abap}   
    // Charger le fichier PDF source
    using (var viewer = new Viewer("resume.pdf"))
    {
        // Définir les options HTML de sortie
        var viewOptions = 
        HtmlViewOptions.ForEmbeddedResources("page{0}.html");
        
        // Rendu PDF en HTML avec des ressources intégrées        
        viewer.View(viewOptions);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Viewer en un coup d'œil"
  description: "API pour restituer, afficher, convertir des documents, des diapositives, des diagrammes et de nombreux autres types de documents dans les applications .NET"
  features:
    # feature loop
    - title: "Visualisez les documents de manière efficace et fiable"
      content: "Avec l'API GroupDocs.Viewer, vous pouvez restituer efficacement des documents de tous les formats pris en charge au format HTML, JPEG, PNG et PDF avec des options flexibles et puissantes tout en préservant l'intégrité du contenu et de la structure du document. GroupDocs.Viewer prend en charge .NET Framework 4.6.2 et .NET 6.0, il fonctionne sur les plateformes Windows et Linux."

    # feature loop
    - title: "Les formats de fichiers et de documents les plus courants sont pris en charge"
      content: "Nous prenons en charge le rendu des 180 formats de fichiers et de documents les plus populaires, notamment Word, Excel, PDF, PowerPoint, la famille de formats OpenDocument, les archives, les images raster et vectorielles, les livres électroniques, les langages de programmation et les balises, ainsi que de nombreux autres types de fichiers, y compris les fichiers cryptés. fichiers avec protection par mot de passe."

    # feature loop
    - title: "Sortie personnalisable"
      content: "GroupDocs.Viewer permet non seulement de restituer le document, mais également de contrôler comment exactement, quelles parties du document doivent être rendues ou maintenant, comment elles doivent être rendues, et d'appliquer différentes transformations à la sortie rendue."

    # feature loop
    - title: "Interface utilisateur pour ASP.NET Core"
      content: "Nous fournissons un package d'interface utilisateur open source pour ASP.NET Core qui peut être ajouté à votre projet en quelques minutes. Le package Viewer.UI contient une interface utilisateur Web basée sur Angular et fournit un ensemble d'API et de fournisseurs de stockage de données utiles."

############################# Platforms ############################
platforms:
  enable: true
  title: "Prise en charge des plateformes"
  description: "GroupDocs.Viewer pour .NET prend en charge les systèmes d'exploitation, frameworks et gestionnaires de packages suivants"
  items:
    # platform loop
    - title: "Amazon"
      image: "amazon"
    # platform loop
    - title: "Docker"
      image: "docker"
    # platform loop
    - title: "Azure"
      image: "azure"
    # platform loop
    - title: "VS Code"
      image: "vs_code"
    # platform loop
    - title: "ReSharper"
      image: "resharper"
    # platform loop
    - title: "macOS"
      image: "finder"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "NuGet"
      image: "nuget"
  packages:
    # packages loop
    - title: "Package spécifique à Windows"
      content: |
        * Prend en charge .NET Framework 4.6.2+ et .NET 6.0
        * Prise en charge des formats de fichiers les plus complets
        * Dépend de System.Drawing et System.Drawing.Common 
      action: "Téléchargement de NuGet"
      action_link: "https://www.nuget.org/packages/GroupDocs.Viewer"
    # packages loop
    - title: "Forfait multiplateforme" 
      content: |
        * Prend en charge .NET 6.0 et les versions supérieures 
        * Prise en charge limitée des formats de fichiers 
        * Fonctionne sous Windows, Linux et macOS 
      action: "Téléchargement de NuGet" 
      action_link: "https://www.nuget.org/packages/GroupDocs.Viewer.CrossPlatform" 

############################# File formats ############################
formats:
  enable: true
  title: "Formats de fichiers pris en charge"
  description: |
    GroupDocs.Viewer pour .NET prend en charge les opérations avec les [formats de fichiers](https://docs.groupdocs.com/viewer/net/supported-document-formats/) suivants.
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office, OpenDocument et formats texte
        * **Word:** DOC, DOCX, DOCM, DOT, DOTX, DOTM, RTF, TXT
        * **Excel:** XLS, XLSX, XLSM, XLSB, XLTM, XLT, XLTM, XLTX
        * **PowerPoint:** PPT, PPTX, PPS, PPSX, PPSM, POT, POTM, POTX, PPTM        
        * **Project:** MPP, MPT, MPX
        * **Outlook:** MSG, EML, EMLX, PST, OST
        * **OneNote:** ONE
        * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG
        * **Fixed Page Layout:** PDF, TEX, XPS, OXPS
        * **e-Books:** EPUB, MOBI, DjVu
        * **Delimiter-Separated Values:** CSV, TSV
    # group loop
    - color: "blue"
      content: |
        ### Images, graphiques et diagrammes
        * **Images rastées:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
        * **Windows Icon:** ICO
        * **Scalable Vector Graphics:** SVG, CDR, CMX, IGS, SVGZ        
        * **Adobe Photoshop:** PSD, PSB        
        * **Stereo Lithography (3D Printing):** STL        
        * **Medical Imaging:** DICOM
        * **Plotter Documents:** PLT, HPG
        * **Autodesk Design Web Formats:** DWF, DWG
        * **AutoCAD Drawing:** DWT, IFC, STL, CF2        
      # group loop
    - color: "red"
      content: |
        ### Autre        
        * **la toile:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **Les archives:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **Autre:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "Fonctionnalités de GroupDocs.Viewer"
  description: "Rendre, afficher et convertir en toute transparence des documents PDF et Office"

  items:
    # feature loop
    - icon: "viewhtml"
      title: "Afficher les documents en HTML"
      content: "Convertissez un document de n'importe quel type en un document HTML avec CSS et SVG, qui peut être affiché dans n'importe quel navigateur Web moderne."

    # feature loop
    - icon: "rasterize"
      title: "Pixelliser les documents"
      content: "Pixellisez n'importe quel format de document pris en charge sur l'image raster, avec un format d'image et une qualité de compression réglables."

    # feature loop
    - icon: "sourcecode"
      title: "Restituer et mettre en évidence les codes de programmation"
      content: "Prise en charge de tous les langages de programmation, de script et de balisage populaires, avec possibilité d'analyser et de mettre en évidence leur syntaxe."

    # feature loop
    - icon: "convertpdf"
      title: "Convertir en PDF"
      content: "Les documents de n'importe quel format pris en charge peuvent être facilement convertis et enregistrés au format PDF avec des options réglables."

    # feature loop
    - icon: "transform"
      title: "Appliquer des transformations"
      content: "Le document de sortie peut être transformé pendant le rendu - les pages peuvent être pivotées et/ou réorganisées et un filigrane de texte peut être placé dessus."

    # feature loop
    - icon: "adjustment"
      title: "Ajustement de la sortie HTML"
      content: "Les documents HTML de sortie, générés par GroupDocs.Viewer, peuvent être réglés très finement: il est permis de les enregistrer dans le flux ou dans un fichier, avec des ressources externes ou intégrées, des rappels, etc."

    # feature loop
    - icon: "complex"
      title: "Prise en charge de structures de documents complexes"
      content: "GroupDocs.Viewer prend en charge non seulement les documents uniques, mais également les fichiers qui contiennent en interne une liste ou une structure hiérarchique de documents, comme des messages électroniques avec pièces jointes, des archives ZIP avec des fichiers internes dans des dossiers, des images TIFF multipages, etc."

    # feature loop
    - icon: "optimization"
      title: "Options d'optimisation"
      content: "GroupDocs.Viewer contient un sous-système de cache réglable, qui peut réduire le temps de chargement en utilisant les versions mises en cache des documents. De plus, un ensemble d'options différentes pour différents formats permet d'exclure du rendu certaines parties ou aspects inutiles des documents (polices, feuilles de calcul masquées, pièces jointes aux e-mails) pour optimiser les performances globales."

    # feature loop
    - icon: "passwordprotected"
      title: "Prise en charge des documents protégés par mot de passe"
      content: "GroupDocs.Viewer permet d'ouvrir les documents cryptés de différents types : PDF, WordProcessing, Spreadsheet, Présentation et autres, en spécifiant un mot de passe dans les options de chargement."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Exemples de codes"
  description: "Quelques cas d'utilisation de GroupDocs.Viewer typique pour les opérations .NET"
  items:
    # code sample loop
    - title: "Rendre DOCX en HTML"
      content: |
        Les propriétés de classe [HtmlViewOptions](https://reference.groupdocs.com/viewer/net/groupdocs.viewer.options/htmlviewoptions/) vous permettent de contrôler le processus de conversion, plus d'informations à ce sujet [ici](https://docs.groupdocs.com/viewer/net/rendering-to-html/). Par exemple, vous pouvez intégrer toutes les ressources externes dans le fichier HTML de sortie, réduire le fichier de sortie et l'optimiser pour l'impression.
        {{< landing/code title="C#">}}
        ```csharp {style=abap}
        using GroupDocs.Viewer;
        using GroupDocs.Viewer.Options;
        
        // Instancier le visualiseur
        using (Viewer viewer = new Viewer("resume.docx"))
        {
            // Définir les options HTML de sortie
            HtmlViewOptions options = HtmlViewOptions.ForEmbeddedResources();
            
            // Rendre DOCX en HTML avec des ressources intégrées
            viewer.View(options);
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Exporter PPTX en PDF"
      content: |
        Créez une instance de classe [PdfViewOptions](https://reference.groupdocs.com/viewer/net/groupdocs.viewer.options/pdfviewoptions/) et transmettez-la à [Viewer.View](https://reference.groupdocs.com/viewer/net/groupdocs.viewer/viewer/view/#view) pour convertir un fichier PowerPoint PPTX en PDF. Les propriétés de la classe PdfViewOptions vous permettent de contrôler le processus de conversion. Par exemple, vous pouvez protéger le fichier PDF de sortie, réorganiser ses pages et spécifier la qualité des images du document. Reportez-vous à la [section de documentation suivante](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/) pour plus de détails.
        {{< landing/code title="C#">}}
        ```csharp {style=abap}   
        using GroupDocs.Viewer;
        using GroupDocs.Viewer.Options;
        
        using (var viewer = new Viewer("presentation.pptx"))
        {
            // Définir les options du PDF de sortie       
            var viewOptions = new PdfViewOptions("presentation.pdf");
            
            // Exporter PPTX en PDF       
            viewer.View(viewOptions);
        }
        ```
        {{< /landing/code >}}
############################# Reviews ############################
# reviews:
# enable: true
# title: "Avis sur les produits GroupDocs"
# description: "Ne vous contentez pas de nous croire sur parole. Découvrez ce que d'autres développeurs disent de nos API"

# items:
#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "Excellent service et excellents produits. Ils ont été extrêmement utiles et réactifs pendant le processus de mise en œuvre de GroupDocs.Viewer pour .NET, et ne sauraient les recommander assez."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "Après avoir implémenté et utilisé GroupDocs.Viewer pour .NET dans le projet, cela semble très bien fonctionner. J'ai testé avec beaucoup de documents et jusqu'ici tout va bien. Tout ce que j'ai lancé s'affiche bien et est aussi beau que dans une visionneuse PDF ou MS Word."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---