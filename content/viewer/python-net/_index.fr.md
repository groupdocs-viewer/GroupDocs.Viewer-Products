---
############################# Static ############################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: fr
product: "Viewer"
product_tag: "viewer"
platform: "Python via .NET"
platform_tag: "python-net"

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
    # supported_platforms loop
    - title: "Python"
      tag: "python-net" 


############################# Head ############################
head_title: "API visionneuse de documents Python pour PDF, Word, Excel, HTML, images et e-mails"
head_description: "API de rendu de fichiers et de visionneuse de documents Python. Ajoutez un visionneur de PDF, un visionneur de Word, un visionneur Excel, une visionneuse d'images, un visionneur HTML et un visionneur de courrier électronique aux applications Python."

############################# Header ############################
title: "Une API Python puissante pour le rendu optimisé de documents"
description: "Rendu et affichage de plus de 180 formats de document (PDF, HTML, image) avec des API puissantes et des options de configuration polyvalentes pour développer des applications Python."
words:
  for: "for"

actions:
  main: "Téléchargement gratuit de PyPI"
  main_link: "https://pypi.org/project/groupdocs-viewer/"
  alt: "Licence"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/python-net"
  title: "Prêt à commencer?"
  description: "Essayez les fonctionnalités de GroupDocs.Viewer gratuitement ou demandez une licence"

release:
  title: "Version {0} publiée"
  notes: "Nouveautés"
  downloads: "Téléchargements"
  link: "https://releases.groupdocs.com/viewer/python-net/release-notes/latest/"

code:
  title: "Rendu de fichiers PDF en Python"
  more: "Plus d'exemples"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Python-via-.NET"
  install: "pip install GroupDocs.Viewer"
  content: |
    ```python {style=abap}
    import groupdocs.viewer as gv
    import groupdocs.viewer.options as gvo
    hvo = gvo.HtmlViewOptions  
  
    // Définir les options HTML de sortie, un fichier par page
    with gv.Viewer("resume.docx") as viewer:
      // Créer une instance de la visionneuse
      opts = hvo.for_embedded_resources("page_{0}.html")

      // Rendu de PDF en HTML avec des ressources intégrées
      viewer.view(opts)
    ```
############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Viewer en un coup d'œil"
  description: "API pour le rendu, l'affichage et la conversion de documents, de diapositives, de diagrammes et de nombreux autres types de documents dans les applications Python"
  features:
    # feature loop
    - title: "Afficher les documents de manière efficace et fiable"
      content: "Avec l'API GroupDocs.Viewer, vous pouvez rendre efficacement des documents de tous les formats pris en charge au format HTML, JPEG, PNG et PDF avec des options flexibles et puissantes, tout en conservant l'intégrité du contenu et de la structure du document. GroupDocs.Viewer pour Python fonctionne sur les plateformes Windows et Linux."

    # feature loop
    - title: "Prise en charge de la plupart des formats de fichiers et de documents courants"
      content: "Nous prenons en charge le rendu de plus de 180 des formats de fichiers et de documents les plus courants, notamment Word, Excel, PDF, PowerPoint, les formats OpenDocument, les archives, les images matricielles et vectorielles, les livres électroniques, les langages de programmation et de balisage, ainsi que de nombreux autres types de fichiers, y compris les fichiers chiffrés protégés par mot de passe."

    # feature loop
    - title: "Sortie personnalisable"
      content: "GroupDocs.Viewer permet non seulement de rendre le document, mais aussi de contrôler comment, quelles parties du document doivent être rendues ou non, comment elles doivent être rendues et d'appliquer différentes transformations à la sortie rendue."

############################# Platforms ############################
platforms:
  enable: true
  title: "Indépendance de la plateforme"
  description: "GroupDocs.Viewer pour Python prend en charge les systèmes d'exploitation, les frameworks et les gestionnaires de paquets suivants"
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
    - title: "Eclipse"
      image: "eclipse"
    # platform loop
    - title: "IntelliJ"
      image: "intellij"
    # platform loop
    - title: "Windows"
      image: "windows"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "NPM"
      image: "npm"
    # platform loop
    - title: "PyPI"
      image: "pypi"

############################# File formats ############################
formats:
  enable: true
  title: "Formats de fichiers pris en charge"
  description: |
    GroupDocs.Viewer pour Python via .NET prend en charge les opérations avec les formats de fichier suivants: [lien vers les formats de fichier pris en charge](https://docs.groupdocs.com/viewer/python-net/supported-document-formats/).
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
  title: "Exemples de code"
  description: "Quelques cas d'utilisation d'opérations GroupDocs.Viewer typiques pour Python via .NET"
  items:
    # code sample loop
    - title: "Rendu de DOCX en HTML"
      content: |
        Les propriétés de la classe `HtmlViewOptions` vous permettent de contrôler le processus de conversion. Pour plus d'informations, consultez [ici](https://docs.groupdocs.com/viewer/python-net/rendering-to-html/). Par exemple, vous pouvez incorporer toutes les ressources externes dans le fichier HTML de sortie, minimiser le fichier de sortie et l'optimiser pour l'impression.
        {{< landing/code title="Python">}}
        ```python {style=abap}
        import groupdocs.viewer as gv
        import groupdocs.viewer.options as gvo 

        // Créer une instance de Viewer
        with gv.Viewer("resume.docx") as viewer:
          // Définir les options HTML de sortie, un fichier par page
          viewOptions = gvo.HtmlViewOptions.for_embedded_resources("page_{0}.html")
          // Rendu de DOCX en HTML avec des ressources intégrées
          viewer.view(viewOptions)
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Exporter PPTX au format PDF"
      content: |
        Créez une instance de la classe `PdfViewOptions` et transmettez-la à la méthode `Viewer.view` pour convertir un fichier PowerPoint PPTX en PDF. Les propriétés de la classe `PdfViewOptions` vous permettent de contrôler le processus de conversion. Par exemple, vous pouvez protéger le fichier PDF de sortie, réorganiser ses pages et spécifier la qualité des images du document. Consultez la [section suivante de la documentation](https://docs.groupdocs.com/viewer/python-net/rendering-to-pdf/) pour plus de détails.
        {{< landing/code title="JavaScript">}}
        ```python {style=abap}
        import groupdocs.viewer as gv
        import groupdocs.viewer.options as gvo  

        // Créer une instance de Viewer
        with gv.Viewer("presentation.pptx") as viewer:
          // Définir les options de sortie PDF
          viewOptions = gvo.PdfViewOptions("presentation.pdf")
          // Exporter PPTX au format PDF
          viewer.view(viewOptions)
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
