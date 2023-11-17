---
############################# Static ############################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

product: "Viewer"
product_tag: "viewer"
platform: "Java"
platform_tag: "java"

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
head_title: "Java Document Viewer API, render PDF Word Excel Obrázek HTML Diagram"
head_description: "Knihovna Document Viewer pro vývoj aplikací Java, které nativně vykreslují, prohlížejí a manipulují s víceformátovými dokumenty podporujícími více než 180 formátů souborů."

############################# Header ############################
title: "Vykreslování a zobrazování dokumentů<br>pomocí Java API"
description: "Výkonné rozhraní Viewer API pro vykreslování více než 180 formátů dokumentů do PDF, HTML a obrázků s všestrannými možnostmi konfigurace."
words:
  for: "for"

actions:
  main: "Maven ke stažení zdarma"
  main_link: "https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-viewer/"
  alt: "Licencování"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/java"
  title: "Jste připraveni začít?"
  description: "Vyzkoušejte funkce GroupDocs.Viewer zdarma nebo si vyžádejte licenci"

release:
  title: "Vydána verze {0}"
  notes: "Podívejte se, co je nového"
  downloads: "Stahování"
  link: "https://releases.groupdocs.com/viewer/java/release-notes/latest/"

code:
  title: "Vykreslování souborů PDF v Javě"
  more: "Další příklady"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Java"
  install: |
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
  content: |
    ```java {style=abap}
    // Instantiate Viewer
    try (Viewer viewer = new Viewer("resume.pdf"))
    {
        // Set output HTML options, one file per page
        HtmlViewOptions viewOptions = 
            HtmlViewOptions.forEmbeddedResources();

        // Render PDF to HTML with embedded resources
        viewer.view(viewOptions);
    }
    ```
############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Viewer na první pohled"
  description: "API pro vykreslování, zobrazení, převod dokumentů, snímků, diagramů a mnoha dalších typů dokumentů v aplikacích Java"
  features:
    # feature loop
    - title: "Prohlížejte dokumenty efektivně a spolehlivě"
      content: "S GroupDocs.Viewer API můžete efektivně vykreslovat dokumenty všech podporovaných formátů do HTML, JPEG, PNG a PDF s flexibilními a výkonnými možnostmi při zachování integrity obsahu a struktury dokumentu. GroupDocs.Viewer funguje na platformách Windows a Linux."

    # feature loop
    - title: "Jsou podporovány nejoblíbenější formáty souborů a dokumentů"
      content: "Podporujeme vykreslování více než 180 nejoblíbenějších formátů souborů a dokumentů, které zahrnují Word, Excel, PDF, PowerPoint, rodinu formátů OpenDocument, archivy, rastrové a vektorové obrázky, e-knihy, programovací jazyky a značky a mnoho dalších typů souborů, včetně šifrovaných soubory s ochranou heslem."

    # feature loop
    - title: "Přizpůsobitelný výstup"
      content: "GroupDocs.Viewer umožňuje nejen vykreslovat dokument, ale také řídit, jak přesně, které části dokumentu by měly být vykresleny nebo nyní, jak by měly být vykresleny, a aplikovat různé transformace na vykreslený výstup."

    # feature loop
    - title: "Webové uživatelské rozhraní pro Spring framework"
      content: "Poskytujeme balíček uživatelského rozhraní s otevřeným zdrojovým kódem pro framework Spring, který lze do vašeho projektu přidat během několika minut. Balíček Viewer.UI obsahuje webové uživatelské rozhraní založené na Angular a poskytuje sadu užitečných rozhraní API a poskytovatelů úložiště dat."

############################# Platforms ############################
platforms:
  enable: true
  title: "Nezávislost na platformě"
  description: "GroupDocs.Viewer for Java podporuje následující operační systémy, rámce a správce balíčků"
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
    - title: "Maven"
      image: "maven"


############################# File formats ############################
formats:
  enable: true
  title: "Podporované formáty souborů"
  description: |
    GroupDocs.Viewer for Java podporuje operace s následujícími [formáty souborů](https://docs.groupdocs.com/viewer/java/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office, OpenDocument a textové formáty
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
        ### Obrázky, grafika a diagramy
        * **Rastrové obrázky:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
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
        ### jiný        
        * **Web:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **Archiv:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **jiný:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "Funkce GroupDocs.Viewer"
  description: "Bezproblémově vykreslujte, zobrazujte a převádějte PDF a dokumenty Office"

  items:
    # feature loop
    - icon: "viewhtml"
      title: "Prohlížení dokumentů v HTML"
      content: "Převeďte dokument jakéhokoli typu do HTML dokumentu pomocí CSS a SVG, který lze zobrazit v jakémkoli moderním webovém prohlížeči."

    # feature loop
    - icon: "rasterize"
      title: "Rastrovat dokumenty"
      content: "Rasterizujte jakýkoli podporovaný formát dokumentu na rastrový obrázek s nastavitelným formátem obrázku a kvalitou komprese."

    # feature loop
    - icon: "sourcecode"
      title: "Vykreslování a zvýraznění programovacích kódů"
      content: "Podpora všech oblíbených programovacích, skriptovacích a značkovacích jazyků se schopností analyzovat a zvýraznit jejich syntaxi."

    # feature loop
    - icon: "convertpdf"
      title: "Převést do PDF"
      content: "Dokument libovolného podporovaného formátu lze snadno převést a uložit do PDF s nastavitelnými možnostmi."

    # feature loop
    - icon: "transform"
      title: "Použít transformace"
      content: "Výstupní dokument lze během vykreslování transformovat - stránky lze otáčet a/nebo přeskupovat a na jejich horní stranu lze umístit textový vodoznak."

    # feature loop
    - icon: "adjustment"
      title: "Úprava výstupu HTML"
      content: "Výstupní HTML dokumenty, generované GroupDocs.Viewerem, lze velmi jemně vyladit: je možné ukládat do streamu nebo souboru, s externími nebo vloženými zdroji, zpětnými voláními a tak dále."

    # feature loop
    - icon: "complex"
      title: "Podpora složitých struktur dokumentů"
      content: "GroupDocs.Viewer podporuje nejen jednotlivé dokumenty, ale také soubory, které interně obsahují seznam nebo hierarchickou strukturu dokumentů, jako jsou e-mailové zprávy s přílohami, archivy ZIP s interními soubory ve složkách, vícestránkové obrázky TIFF a tak dále."

    # feature loop
    - icon: "optimization"
      title: "Možnosti optimalizace"
      content: "GroupDocs.Viewer obsahuje nastavitelný subsystém mezipaměti, který může zkrátit dobu načítání pomocí verzí dokumentů uložených v mezipaměti. Také sada různých možností pro různé formáty umožňuje vyloučit některé zbytečné části nebo aspekty dokumentů z vykreslování (fonty, skryté pracovní listy, přílohy e-mailů) pro optimalizaci celkového výkonu"

    # feature loop
    - icon: "passwordprotected"
      title: "Podpora dokumentů chráněných heslem"
      content: "GroupDocs.Viewer umožňuje otevřít zašifrované dokumenty různých typů: PDF, WordProcessing, Spreadsheet, Presentation a další, zadáním hesla v možnostech načítání."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Ukázky kódu"
  description: "Některé případy použití typických operací GroupDocs.Viewer pro Java"
  items:
    # code sample loop
    - title: "Vykreslit DOCX do HTML"
      content: |
        Vlastnosti třídy [HtmlViewOptions](https://reference.groupdocs.com/viewer/java/com.groupdocs.viewer.options/htmlviewoptions/) vám umožňují řídit proces převodu, více o tom [zde](https:/ /docs.groupdocs.com/viewer/java/rendering-to-html/). Můžete například vložit všechny externí zdroje do výstupního souboru HTML, minimalizovat výstupní soubor a optimalizovat jej pro tisk.
        {{< landing/code title="Java">}}
        ```java {style=abap}
        import com.groupdocs.viewer.Viewer;
        import com.groupdocs.viewer.options.HtmlViewOptions;

        // Instantiate Viewer
        try (Viewer viewer = new Viewer("resume.docx"))
        {
            // Set output HTML options
            HtmlViewOptions options = 
                HtmlViewOptions.forEmbeddedResources();

            // Render DOCX to HTML with embedded resources
            viewer.view(options);
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Export PPTX do PDF"
      content: |
        Vytvořte instanci třídy [PdfViewOptions](https://reference.groupdocs.com/viewer/java/com.groupdocs.viewer.options/pdfviewoptions/) a předejte ji do [Viewer.View](https://reference. groupdocs.com/viewer/java/com.groupdocs.viewer/viewer/#view-com.groupdocs.viewer.options.ViewOptions-) metoda pro převod souboru PowerPoint PPTX do PDF. Vlastnosti třídy PdfViewOptions vám umožňují řídit proces převodu. Můžete například chránit výstupní soubor PDF, změnit pořadí jeho stránek a určit kvalitu obrazů dokumentů. Podrobnosti naleznete v [následující sekci dokumentace](https://docs.groupdocs.com/viewer/java/rendering-to-pdf/).
        {{< landing/code title="Java">}}
        ```java {style=abap}   
        import com.groupdocs.viewer.Viewer;
        import com.groupdocs.viewer.options.PdfViewOptions;

        // Instantiate Viewer
        try (Viewer viewer = new Viewer("presentation.pptx"))
        {
            // Set output PDF options
            PdfViewOptions viewOptions = new PdfViewOptions();

            // Export PPTX to PDF
            viewer.view(viewOptions);
        }
        ```
        {{< /landing/code >}}
############################# Reviews ############################
# reviews:
# enable: true
# title: "Recenze produktů GroupDocs"
# description: "Neberte nás za slovo. Podívejte se, co o našich API říkají ostatní vývojáři"

# items:
#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "Vynikající služby a skvělé produkty. Během procesu implementace GroupDocs.Viewer for .NET byli extrémně nápomocní a reagovali, nelze je dostatečně doporučit."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "Po implementaci a použití GroupDocs.Viewer pro .NET v projektu to vypadá, že funguje velmi dobře. Testoval jsem se spoustou dokumentů a zatím dobrý. Všechno, co jsem na něj hodil, se pěkně vykresluje a vypadá stejně dobře, jako by to vypadalo v prohlížeči PDF nebo MS Word."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---