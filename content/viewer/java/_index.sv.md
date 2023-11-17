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
head_title: "Java Document Viewer API, rendera PDF Word Excel Image HTML Diagram"
head_description: "Document Viewer-bibliotek för att utveckla Java-applikationer som naturligt renderar, visar och manipulerar dokument i flera format som stöder 180+ filformat."

############################# Header ############################
title: "Återge och visa dokument<br>med Java API"
description: "Kraftfullt Viewer API för att återge 180+ dokumentformat till PDF, HTML och bild med mångsidiga konfigurationsalternativ."
words:
  for: "for"

actions:
  main: "Gratis nedladdning av Maven"
  main_link: "https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-viewer/"
  alt: "Licensiering"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/java"
  title: "Redo att komma igång?"
  description: "Prova GroupDocs.Viewer-funktioner gratis eller begär en licens"

release:
  title: "Version {0} släppt"
  notes: "Se vad som är nytt"
  downloads: "Nedladdningar"
  link: "https://releases.groupdocs.com/viewer/java/release-notes/latest/"

code:
  title: "Återge PDF-filer i Java"
  more: "Fler exempel"
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
  title: "GroupDocs.Viewer i ett ögonkast"
  description: "API för att rendera, visa, konvertera dokument, bilder, diagram och många andra dokumenttyper i Java-applikationer"
  features:
    # feature loop
    - title: "Visa dokument effektivt och tillförlitligt"
      content: "Med GroupDocs.Viewer API kan du effektivt rendera dokument av alla stödjande format till HTML, JPEG, PNG och PDF med flexibla och kraftfulla alternativ samtidigt som innehållet och dokumentstrukturens integritet bibehålls. GroupDocs.Viewer fungerar på Windows- och Linux-plattformar."

    # feature loop
    - title: "De flesta populära fil- och dokumentformaten stöds"
      content: "Vi stöder rendering av över de 180 mest populära fil- och dokumentformaten som inkluderar Word, Excel, PDF, PowerPoint, OpenDocument-formatfamiljen, arkiv, raster- och vektorbilder, e-böcker, programmeringsspråk och uppmärkningar och många andra filtyper, inklusive krypterade filer med lösenordsskydd."

    # feature loop
    - title: "Anpassningsbar utgång"
      content: "GroupDocs.Viewer tillåter inte bara att rendera dokumentet, utan också att kontrollera hur exakt, vilka delar av dokumentet som ska renderas eller nu, hur de ska renderas, och att tillämpa olika transformationer på den renderade utdata."

    # feature loop
    - title: "Webbgränssnitt för Spring framework"
      content: "Vi tillhandahåller ett UI-paket med öppen källkod för Spring framework som kan läggas till ditt projekt på ett par minuter. Viewer.UI-paketet innehåller ett Angular-baserat webbgränssnitt och levererar en uppsättning användbara API:er och datalagringsleverantörer."

############################# Platforms ############################
platforms:
  enable: true
  title: "Plattformsoberoende"
  description: "GroupDocs.Viewer för Java stöder följande operativsystem, ramverk och pakethanterare"
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
  title: "Filformat som stöds"
  description: |
    GroupDocs.Viewer för Java stöder operationer med följande [filformat](https://docs.groupdocs.com/viewer/java/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office, OpenDocument och textformat
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
        ### Bilder, grafik & diagram
        * **Rasterbilder:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
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
        ### Övrig        
        * **webb:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **Arkiv:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **Övrig:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "GroupDocs.Viewer-funktioner"
  description: "Rendera, visa och konvertera PDF- och Office-dokument sömlöst"

  items:
    # feature loop
    - icon: "viewhtml"
      title: "Visa dokument i HTML"
      content: "Konvertera dokument av vilken typ som helst till ett HTML-dokument med CSS och SVG, som kan visas i vilken modern webbläsare som helst."

    # feature loop
    - icon: "rasterize"
      title: "Rasterisera dokument"
      content: "Rasterisera alla dokumentformat som stöds till rasterbilden, med justerbart bildformat och komprimeringskvalitet."

    # feature loop
    - icon: "sourcecode"
      title: "Rendera och markera programmeringskoder"
      content: "Stöd för alla populära programmerings-, skript- och märkningsspråk, med möjlighet att analysera och framhäva deras syntax."

    # feature loop
    - icon: "convertpdf"
      title: "Konvertera till PDF"
      content: "Dokument av vilket format som helst kan enkelt konverteras och sparas till PDF med justerbara alternativ."

    # feature loop
    - icon: "transform"
      title: "Tillämpa transformationer"
      content: "Utdatadokument kan omvandlas under rendering - sidor kan roteras och/eller ordnas om, och textvattenstämpel kan placeras ovanpå dem."

    # feature loop
    - icon: "adjustment"
      title: "HTML-utdatajustering"
      content: "Utdata HTML-dokument, genererade av GroupDocs.Viewer, kan finjusteras: det är tillåtet att spara till strömmen eller filen, med externa eller inbäddade resurser, återuppringningar och så vidare."

    # feature loop
    - icon: "complex"
      title: "Stöd för komplexa dokumentstrukturer"
      content: "GroupDocs.Viewer stöder inte bara enskilda dokument, utan även filer, som internt innehåller en lista eller hierarkisk struktur av dokument, som e-postmeddelanden med bilagor, ZIP-arkiv med interna filer i mappar, flersidiga TIFF-bilder och så vidare."

    # feature loop
    - icon: "optimization"
      title: "Optimeringsalternativ"
      content: "GroupDocs.Viewer innehåller ett justerbart cache-undersystem, som kan förkorta laddningstiden genom att använda de cachade versionerna av dokumenten. En uppsättning olika alternativ för olika format gör det också möjligt att utesluta vissa onödiga delar eller aspekter av dokument från renderingen (teckensnitt, dolda kalkylblad, e-postbilagor) för att optimera den övergripande prestandan"

    # feature loop
    - icon: "passwordprotected"
      title: "Stöd för lösenordsskyddade dokument"
      content: "GroupDocs.Viewer gör det möjligt att öppna krypterade dokument av olika typer: PDF, WordProcessing, Spreadsheet, Presentation och annat, genom att ange ett lösenord i laddningsalternativen."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Kodprover"
  description: "Vissa använder fall av typiska GroupDocs.Viewer för Java-operationer"
  items:
    # code sample loop
    - title: "Rendera DOCX till HTML"
      content: |
        Klassegenskaperna [HtmlViewOptions](https://reference.groupdocs.com/viewer/java/com.groupdocs.viewer.options/htmlviewoptions/) låter dig kontrollera konverteringsprocessen, mer om det [här](https:/ /docs.groupdocs.com/viewer/java/rendering-to-html/). Du kan till exempel bädda in alla externa resurser i HTML-utdatafilen, förminska utdatafilen och optimera den för utskrift.
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
    - title: "Exportera PPTX till PDF"
      content: |
        Skapa en klassinstans [PdfViewOptions](https://reference.groupdocs.com/viewer/java/com.groupdocs.viewer.options/pdfviewoptions/) och skicka den till [Viewer.View](https://reference. groupdocs.com/viewer/java/com.groupdocs.viewer/viewer/#view-com.groupdocs.viewer.options.ViewOptions-) metod för att konvertera en PowerPoint PPTX-fil till PDF. Klassegenskaperna för PdfViewOptions låter dig kontrollera konverteringsprocessen. Du kan till exempel skydda den utgående PDF-filen, ordna om dess sidor och ange kvaliteten på dokumentbilder. Se [följande dokumentationsavsnitt](https://docs.groupdocs.com/viewer/java/rendering-to-pdf/) för detaljer.
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
# title: "GroupDocs produkter recensioner"
# description: "Ta inte bara vårt ord för det. Se vad andra utvecklare säger om våra API:er"

# items:
#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "Utmärkt service och utmärkta produkter. De var extremt hjälpsamma och lyhörda under implementeringsprocessen för GroupDocs.Viewer för .NET, kan inte rekommendera dem tillräckligt starkt."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "Efter att ha implementerat och använt GroupDocs.Viewer för .NET i projektet ser det ut att fungera mycket bra. Jag har testat med en hel del dokument och än så länge så bra. Allt jag har kastat på det återges snyggt och ser lika bra ut som det skulle göra i en PDF-visare eller MS Word."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---