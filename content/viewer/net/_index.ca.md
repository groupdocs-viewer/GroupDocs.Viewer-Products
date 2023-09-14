---
############################# Static ##########################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

lang: ca
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: ".NET Document Viewer API, renderitza PDF Word Excel Imatge HTML Diagrama"
head_description: "Visualitzador de fitxers C# ASP.NET i API de representació. Afegiu un visualitzador de PDF, un visualitzador de paraules, un visualitzador d'Excel, un visualitzador d'imatges, un visualitzador d'HTML i funcions de visualització de correu electrònic a les aplicacions .NET."

############################# Header ##########################
title: "Renderitzar i mostrar documents mitjançant .NET API"
description: ".NET Document Viewer API per renderitzar més de 190 formats de document en PDF, HTML i imatge amb potents opcions de configuració."
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
              text: "Visió general"

            # button loop
            - link: "#features"
              text: "Característiques"

            # button loop
            - link: "#support"
              text: "Suport"

            # button loop
            - link: "https://products.groupdocs.app/viewer/total"
              text: "Demostració en directe"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Preus"

    right:
        link_download: "https://www.nuget.org/packages/GroupDocs.Viewer"
        link_learn: "https://docs.groupdocs.com/viewer/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    content: |
      Les API de GroupDocs.Viewer per a .NET us ajuden a crear aplicacions potents en C#, ASP.NET i altres tecnologies basades en .NET, que poden representar i mostrar documents i imatges de més de 190 formats de fitxer sense instal·lar cap programari extern. La biblioteca del visualitzador de fitxers rasteritza els documents i després els converteix en SVG + HTML + CSS per optimitzar l'experiència global de representació de documents per visualitzar documents comercials, imatges, fitxers de text, diagrames, gràfics, fitxers adjunts de correu electrònic i fitxers PDF amb velocitat, text real i alta fidelitat a les vostres aplicacions. Teniu l'opció d'afegir funcionalitats de visualització i lectura de documents a les vostres aplicacions per mostrar el document sencer, el document parcial, el rang de pàgines/cel·les específics, la capa de document individual, amb o sense anotacions i comentaris per als formats de fitxer admesos.
       
      GroupDocs.Viewer per a .NET guarda a la memòria cau la sortida dels documents renderitzats al disc local de manera predeterminada. Qualsevol tipus d'emmagatzematge de memòria cau externa també és compatible amb la implementació d'interfícies adequades: Amazon S3, Dropbox, Google Drive, Windows Azure, Redis o qualsevol altre.
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          A continuació es mostra una visió general de GroupDocs.Viewer per a .NET:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Visió general"
          content: |
            * Mostra més de 190 tipus de documents 
            * Obteniu un fitxer en format HTML, imatge, PDF 
            * Gira i reordena 
            * Aplicar filigrana 
            * Memòria cau per a un procés ràpid 
            * Afegeix fonts personalitzades 
            * Aplicar estàndards de codificació 
            * Gestor de dades d'entrada personalitzat 
            * Renderitza amb el seguiment dels canvis 
            * Mostra com a HTML responsiu 
            * Renderitza capes de PDF i CAD 
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Viewer per a .NET admet la visualització de tots els formats de fitxer de documents més populars. Amb només unes poques línies de codi, afegiu el visualitzador de PDF, Microsoft Office Word, full de càlcul Excel, imatge, HTML, correu electrònic d'Outlook, OneNote, capacitats de visualització de projectes i gràfics a les vostres aplicacions .NET.

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
                * **Fitxers de disseny de pàgina:** PDF, TEX, XPS, OXPS
                * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG, OTG, FODP, FODG
                * **Valors separats per delimitadors:** CSV, TSV
                * **Web:** HTML, MHT, MHTML
                * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
                * **PostScript:** PS, EPS
                * **Arxius:** ZIP, TAR, BZ2, GZ, RAR, RAR5
                * **Diversos:** OBJ, EPUB, MOBI, DjVu, XML, VCF, VCARD, NUMBERS, NSF

        right:
          enable: true
          table:
            # table loop
            - title: "Imatges, gràfics i diagrames"
              content: |
                * **Imatges:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB
                * **Icona de Windows:** ICO
                * **Gràfics vectorials escalables:** SVG, CDR, CMX, IGS, SVGZ
                * **Jpeg2000:** JP2, J2C, J2K, JPC, JPF, JPX, JPM
                * **Adobe Photoshop:** PSD, PSB
                * **Llenguatge de comandaments de la impressora:** PCL
                * **Litografia estèreo (impressió 3D):** STL
                * **Classes de la Fundació de la indústria:** IFC
                * **Imatge mèdica:** DICOM
                * **Documents del traçador:** PLT, HPG
                * **Formats web de disseny d'Autodesk:** DWF, DWG
                * **Dibuix d'AutoCAD:** DWT, IFC, STL, CF2
                * **DGN basat en ISFF (V7):** DGN

            # table loop
            - title: "Formats de llenguatges de programació"
              content: |
                * **Fitxers C/C++/C#:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
                * **Fitxers Java/JavaScript:** JAVA, JS, JSON, PROPERTIES
                * **Diversos:** VB, PHP, SQL, PL, PY, PV, RB, RST, SASS, SCALA, SCM, SCRIPT, AS, AS3, ASM, BAT, CMAKE, CSS, DIFF, ERB, GROOVY, HAML, LESS, LOG, M, MAKE, MD, ML, MM, SH, SML, VIM, YAML

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Viewer per a .NET és compatible amb els següents sistemes operatius, marcs i gestors de paquets:
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Sistemes operatius"
              content: |
                * Microsoft Windows Server 2003 i posteriors 
                * Microsoft Windows XP i posteriors 
                * Microsoft Windows 10 i 11 
                * Linux (Ubuntu, OpenSUSE, CentOS i altres) 
                * Mac OS X 

            # table loop
            - icon: "fas fa-code"
              title: "Marcs suportats"
              content: |
                * .NET Framework 2.0 o superior 
                * .NET Core 3.1 
                * .NET 5 o superior 

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-box"
              title: "Gestor de paquets"
              content: |
                * NuGet

            # table loop
            - icon: "fas fa-tools"
              title: "Entorns de desenvolupament"
              content: |
                * Microsoft Visual Studio
                * Visual Studio Code
                * .NET CLI

############################# Features ############################
features:
    enable: true
    title: "GroupDocs.Viewer per a funcions de .NET"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "Rasteritza els documents i converteix-los en SVG, HTML i CSS"

      # feature loop
      - icon: "fas fa-eye"
        content: "Converteix text a HTML i renderitza documents per obtenir una representació HTML, imatge o PDF"

      # feature loop
      - icon: "fas fa-bolt"
        content: "Temps de càrrega més ràpid mitjançant versions en memòria cau dels documents"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "Converteix presentacions amb formes i text amb efectes 3D"

      # feature loop
      - icon: "fas fa-code"
        content: "Codifiqueu documents de Word, Excel i correu electrònic a l'estàndard de codificació desitjat"

      # feature loop
      - icon: "fas fa-cloud"
        content: "Renderitza documents situats a FTP o ubicacions d'emmagatzematge al núvol"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "Excloure els tipus de lletra quan es renderitza a HTML per reduir la mida del fitxer resultant"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "Reduïu la sortida CSS i HTML eliminant comentaris, espais en blanc addicionals, etc."

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "Llegeix el text contingut en un document font a través de les seves coordenades"

      # feature loop
      - icon: "fas fa-border-all"
        content: "Mostra/amaga les línies de quadrícula dels fulls d'Excel a la representació de sortida"

      # feature loop
      - icon: "fas fa-wrench"
        content: "Especifiqueu el nombre de files d'un full d'Excel que es mostraran a cada pàgina"

      # feature loop
      - icon: "fas fa-columns"
        content: "Ignoreu les columnes buides durant la representació de documents de full de càlcul"

      # feature loop
      - icon: "fas fa-file-word"
        content: "Renderitza documents de Word en pàgines HTML, imatges o PDF, amb el seguiment dels canvis"

      # feature loop
      - icon: "fas fa-envelope"
        content: "Representa els fitxers adjunts de correu electrònic com a fitxers originals, imatges o en representació HTML"

      # feature loop
      - icon: "fas fa-print"
        content: "Establiu restriccions d'impressió en documents PDF"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "Representa el contingut/fitxers continguts als arxius ZIP com a fitxers adjunts"

      # feature loop
      - icon: "fas fa-lock"
        content: "Obteniu fitxers adjunts de documents protegits amb contrasenya"

      # feature loop
      - icon: "fas fa-file-code"
        content: "Mostra els formats de fitxer dels llenguatges de programació com a text sense format"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "Ajusteu els colors de fons quan visualitzeu dibuixos CAD"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "Veure documents d'Excel i convertir-los a PDF, HTML, JPG i PNG"

      # feature loop
      - icon: "fas fa-heading"
        content: "Obteniu els noms dels fulls de treball del fitxer Excel: mostreu els encapçalaments de les columnes del full de càlcul i els números de les files"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "Veure i convertir documents de Microsoft Project amb Notes"

      # feature loop
      - icon: "fas fa-cube"
        content: "Converteix dibuixos CAD a SVG per obtenir una millor experiència de visualització i zoom"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "Trieu renderitzar figures de Visio sense esquema"

    more_feature:
      # more_feature_loop
      - title: "Veure documents de manera eficient i fiable"
        content: |
          Mitjançant l'API GroupDocs.Viewer, podeu mostrar més de 190 formats de documents de manera eficient i fiable amb el contingut i la integritat de l'estructura del document intactes. El codi d'exemple següent mostra com de fàcil és veure la representació HTML d'un document DOCX:

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
      - title: "Apliqueu la transformació a la sortida renderitzada"
        content: "Podeu realitzar diverses transformacions al document de sortida representat mitjançant l'API de GroupDocs.Viewer per a .NET. Aquestes opcions de transformació us permeten controlar la manera com presenteu la sortida renderitzada per a la visualització. Les transformacions disponibles són l'opció de rotació de la pàgina, l'opció de reordenació de la pàgina i l'aplicació de filigrana de text."

      # more_feature_loop
      - title: "Treballar amb fitxers de dades d'Outlook"
        content: "L'API GroupDocs.Viewer per a .NET pot representar els elements dels fitxers de dades d'Outlook (OST/PST) com a PDF, HTML i fitxers d'imatge. La nostra API Viewer també té la possibilitat d'obtenir la llista de carpetes contingudes als fitxers de dades d'Outlook. Mitjançant l'API GroupDocs.Viewer per a .NET, podeu especificar la carpeta que voleu renderitzar des dels fitxers de dades d'Outlook. De la mateixa manera, també podeu obtenir missatges de correu electrònic continguts en formats OST/PST com a fitxers adjunts. GroupDocs.Viewer per a .NET també us permet filtrar missatges dels formats OST/PST en funció del tema, contingut o remitent."

      # more_feature_loop
      - title: "Treballar amb documents CAD"
        content: "L'API GroupDocs.Viewer per a .NET pot representar el model i tots els dissenys no buits o representar un disseny específic d'un fitxer CAD. GroupDocs.Viewer per a .NET API també admet la representació en mosaic o la representació per coordenades de documents CAD en imatge, HTML o PDF. També podeu obtenir estats de capa per a documents CAD."

############################# Testimonials ###############################
testimonials:
  enable: true

  testimonial:
    # testimonial item loop
    - name: "Margot Baill"
      designation: "Director de desenvolupament de producte a Hireology"
      content: "La integració de GroupDocs.Viewer for Cloud API va ser senzilla amb el seu fantàstic SDK Ruby. No hi ha tantes empreses que estiguin disposades a treballar amb nosaltres en el que volem. És una gran associació."

    # testimonial item loop
    - name: "Mats Oustad"
      designation: "Consultor Sènior/Soci de Novanet AS"
      content: "Després d'implementar i utilitzar GroupDocs.Viewer per a .NET al projecte, sembla que funciona molt bé. He provat amb molts documents i fins ara tot va bé. Tot el que hi he llançat es mostra molt bé i es veu tan bé com ho faria en un visor de PDF o MS Word."
              
    # testimonial item loop
    - name: "Martin Lasarga"
      designation: "Product Manager a Axentria ECM per G.S.I."
      content: "Excel·lent servei i excel·lents productes. Van ser molt útils i sensibles durant el procés d'implementació de GroupDocs.Viewer per a .NET, no els podem recomanar prou."

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Viewer ofereix API de visualització de documents per a altres entorns de desenvolupament populars"

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
