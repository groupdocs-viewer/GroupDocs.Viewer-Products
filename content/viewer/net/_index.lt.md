---
############################# Static ##########################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: lt
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
head_title: ".NET dokumentų peržiūros programos API, pateikia PDF Word Excel vaizdo HTML diagramą"
head_description: "C# ASP.NET failų peržiūros programa ir atvaizdavimo API. Pridėkite PDF peržiūros programą, „Word“ peržiūros programą, „Excel“ peržiūros programą, vaizdų peržiūros priemonę, HTML peržiūros priemonę, el. pašto peržiūros priemonę .NET programose."

############################# Header ##########################
title: "Pateikite ir rodykite dokumentus<br>naudodami .NET API"
description: "Galingas peržiūros programos API, leidžiantis paversti 180 ir daugiau dokumentų formatų į PDF, HTML ir vaizdus su įvairiomis konfigūravimo parinktimis."
words:
  for: "for"

actions:
  main: "Nemokamas NuGet atsisiuntimas"
  main_link: "https://www.nuget.org/packages/GroupDocs.Viewer"
  alt: "Licencijavimas"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/net"
  title: "Pasiruošę pradėti?"
  description: "Išbandykite GroupDocs.Viewer funkcijas nemokamai arba paprašykite licencijos"

release:
  title: "Išleista {0} versija"
  notes: "Pažiūrėkite, kas naujo"
  downloads: "Atsisiuntimai"
  link: "https://releases.groupdocs.com/viewer/net/release-notes/latest/"

code:
  title: "Pateikite PDF failus C#"
  more: "Daugiau pavyzdžių"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
  install: "dotnet add package GroupDocs.Viewer"
  content: |
    ```csharp {style=abap}   
    // Load the source PDF file
    using (var viewer = new Viewer("resume.pdf"))
    {
        // Set output HTML options, one file per page
        var viewOptions = 
          HtmlViewOptions.ForEmbeddedResources("page_{0}.html");
        
        // Render PDF to HTML with embedded resources
        viewer.View(viewOptions);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Viewer iš pirmo žvilgsnio"
  description: "API, skirta pateikti, rodyti, konvertuoti dokumentus, skaidres, diagramas ir daugelį kitų dokumentų tipų .NET programose"
  features:
    # feature loop
    - title: "Peržiūrėkite dokumentus efektyviai ir patikimai"
      content: "Naudodami GroupDocs.Viewer API galite efektyviai pateikti bet kokio palaikomo formato dokumentus į HTML, JPEG, PNG ir PDF su lanksčiomis ir galingomis parinktimis, išlaikant turinio ir dokumentų struktūros vientisumą. GroupDocs.Viewer palaiko .NET Framework 4.6.2 ir .NET 6.0, veikia Windows ir Linux platformose."

    # feature loop
    - title: "Palaikomi populiariausi failų ir dokumentų formatai"
      content: "Mes palaikome daugiau nei 180 populiariausių failų ir dokumentų formatų, įskaitant Word, Excel, PDF, PowerPoint, OpenDocument formatų šeimą, archyvus, rastrinius ir vektorinius vaizdus, ​​el. knygas, programavimo kalbas ir žymėjimus bei daugybę kitų failų tipų, įskaitant šifruotus, pateikimą. failus su slaptažodžiu."

    # feature loop
    - title: "Pritaikoma išvestis"
      content: "GroupDocs.Viewer leidžia ne tik atvaizduoti dokumentą, bet ir valdyti kaip tiksliai, kurios dokumento dalys turi būti atvaizduojamos ar dabar, kaip jos turi būti atvaizduojamos bei pritaikyti įvairias transformacijas pateiktai išvestiei."

    # feature loop
    - title: "UI skirta ASP.NET Core"
      content: "Pateikiame atvirojo kodo vartotojo sąsajos paketą, skirtą ASP.NET Core, kurį galima pridėti prie projekto per kelias minutes. Viewer.UI pakete yra kampinė žiniatinklio vartotojo sąsaja ir pateikiamas naudingų API ir duomenų saugojimo teikėjų rinkinys."

############################# Platforms ############################
platforms:
  enable: true
  title: "Platformos nepriklausomybė"
  description: "GroupDocs.Viewer for .NET palaiko šias operacines sistemas, sistemas ir paketų tvarkykles"
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

############################# File formats ############################
formats:
  enable: true
  title: "Palaikomi failų formatai"
  description: |
    NET skirta GroupDocs.Viewer palaiko operacijas su šiais [failų formatais](https://docs.groupdocs.com/viewer/net/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office, OpenDocument ir teksto formatai
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
        ### Vaizdai, grafika ir diagramos
        * **Rastriniai vaizdai:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
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
        ### Kita        
        * **Žiniatinklis:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **Archyvai:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **Kita:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "GroupDocs.Viewer funkcijos"
  description: "Sklandžiai atvaizduokite, rodykite ir konvertuokite PDF ir „Office“ dokumentus"

  items:
    # feature loop
    - icon: "viewhtml"
      title: "Peržiūrėkite dokumentus HTML formatu"
      content: "Konvertuokite bet kokio tipo dokumentą į HTML dokumentą su CSS ir SVG, kurie gali būti rodomi bet kurioje šiuolaikinėje žiniatinklio naršyklėje."

    # feature loop
    - icon: "rasterize"
      title: "Rasterizuoti dokumentus"
      content: "Rastruokite bet kokį palaikomą dokumento formatą į rastrinį vaizdą su reguliuojamu vaizdo formatu ir glaudinimo kokybe."

    # feature loop
    - icon: "sourcecode"
      title: "Pateikite ir paryškinkite programavimo kodus"
      content: "Visų populiarių programavimo, scenarijų ir žymėjimo kalbų palaikymas su galimybe analizuoti ir paryškinti jų sintaksę."

    # feature loop
    - icon: "convertpdf"
      title: "Konvertuoti į PDF"
      content: "Bet kokio palaikomo formato dokumentas gali būti lengvai konvertuojamas ir įrašomas į PDF su reguliuojamomis parinktimis."

    # feature loop
    - icon: "transform"
      title: "Taikyti transformacijas"
      content: "Išvesties dokumentas gali būti transformuojamas atvaizdavimo metu – puslapius galima pasukti ir (arba) pertvarkyti, o ant jų uždėti tekstinį vandens ženklą."

    # feature loop
    - icon: "adjustment"
      title: "HTML išvesties koregavimas"
      content: "Išvesties HTML dokumentus, sugeneruotus GroupDocs.Viewer, galima labai tiksliai sureguliuoti: leidžiama įrašyti į srautą ar failą, naudojant išorinius ar įterptus išteklius, atgalinius skambučius ir pan."

    # feature loop
    - icon: "complex"
      title: "Sudėtingų dokumentų struktūrų palaikymas"
      content: "GroupDocs.Viewer palaiko ne tik atskirus dokumentus, bet ir failus, kurių viduje yra dokumentų sąrašas arba hierarchinė struktūra, pvz., el. laiškai su priedais, ZIP archyvai su vidiniais failais aplankuose, kelių puslapių TIFF vaizdai ir pan."

    # feature loop
    - icon: "optimization"
      title: "Optimizavimo parinktys"
      content: "GroupDocs.Viewer turi reguliuojamą talpyklos posistemę, kuri gali sutrumpinti įkėlimo laiką naudojant talpykloje esančias dokumentų versijas. Taip pat įvairių formatų parinkčių rinkinys leidžia atvaizduoti kai kurias nereikalingas dokumentų dalis ar aspektus (šriftus, paslėptus darbalapius, el. pašto priedus), kad būtų optimizuotas bendras našumas."

    # feature loop
    - icon: "passwordprotected"
      title: "Slaptažodžiu apsaugotų dokumentų palaikymas"
      content: "GroupDocs.Viewer leidžia atidaryti šifruotus įvairių tipų dokumentus: PDF, WordProcessing, Spreadsheet, Presentation ir kitus, įkėlimo parinktyse nurodant slaptažodį."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Kodo pavyzdžiai"
  description: "Kai kurie tipiniai GroupDocs.Viewer atvejai naudojami .NET operacijoms"
  items:
    # code sample loop
    - title: "Pateikite DOCX į HTML"
      content: |
        [HtmlViewOptions](https://reference.groupdocs.com/viewer/net/groupdocs.viewer.options/htmlviewoptions/) klasės ypatybės leidžia valdyti konversijos procesą, daugiau apie tai [čia](https://docs .groupdocs.com/viewer/net/rendering-to-html/). Pavyzdžiui, galite įterpti visus išorinius išteklius į išvesties HTML failą, sumažinti išvesties failą ir optimizuoti jį spausdinimui.
        {{< landing/code title="C#">}}
        ```csharp {style=abap}
        using GroupDocs.Viewer;
        using GroupDocs.Viewer.Options;
        
        // Instantiate viewer
        using (Viewer viewer = new Viewer("resume.docx"))
        {
            // Set output HTML options
            HtmlViewOptions options = HtmlViewOptions.ForEmbeddedResources();
            
            // Render DOCX to HTML with embedded resources
            viewer.View(options);
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Eksportuokite PPTX į PDF"
      content: |
        Sukurkite [PdfViewOptions](https://reference.groupdocs.com/viewer/net/groupdocs.viewer.options/pdfviewoptions/) klasės egzempliorių ir perduokite jį [Viewer.View](https://reference.groupdocs. com/viewer/net/groupdocs.viewer/viewer/view/#view) metodas PowerPoint PPTX failą konvertuoti į PDF. PdfViewOptions klasės ypatybės leidžia valdyti konversijos procesą. Pavyzdžiui, galite apsaugoti išvesties PDF failą, pertvarkyti jo puslapius ir nurodyti dokumento vaizdų kokybę. Norėdami gauti daugiau informacijos, žr. [toliau pateiktą dokumentų skyrių](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/).
        {{< landing/code title="C#">}}
        ```csharp {style=abap}   
        using GroupDocs.Viewer;
        using GroupDocs.Viewer.Options;
        
        using (var viewer = new Viewer("presentation.pptx"))
        {
            // Set output PDF options
            var viewOptions = new PdfViewOptions("presentation.pdf");
            
            // Export PPTX to PDF
            viewer.View(viewOptions);
        }
        ```
        {{< /landing/code >}}
############################# Reviews ############################
# reviews:
# enable: true
# title: "GroupDocs produktų apžvalgos"
# description: "Netikėkite mūsų žodžio. Sužinokite, ką kiti kūrėjai sako apie mūsų API"

# items:
#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "Puikus aptarnavimas ir puikūs produktai. Jie buvo labai naudingi ir reagavo per GroupDocs.Viewer .NET diegimo procesą, todėl negaliu jų rekomenduoti."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "Projekte įdiegus ir panaudojus GroupDocs.Viewer for .NET, atrodo, kad jis veikia labai gerai. Išbandžiau su daugybe dokumentų ir kol kas viskas gerai. Viskas, ką sukūriau, gražiai atvaizduojama ir atrodo taip pat gerai, kaip ir PDF peržiūros programoje arba MS Word."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---