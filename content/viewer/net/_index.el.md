---
############################# Static ##########################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: el
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
head_title: "API προβολής εγγράφων .NET, απόδοση PDF Word Excel Image HTML Diagram"
head_description: "API προβολής και απόδοσης αρχείων C# ASP.NET. Προσθήκη προγράμματος προβολής PDF, προβολής Word, προβολής Excel, Προβολής εικόνων, προβολής HTML, λειτουργιών προβολής email σε εφαρμογές .NET."

############################# Header ##########################
title: "Απόδοση και εμφάνιση εγγράφων<br>χρησιμοποιώντας .NET API"
description: "Ισχυρό API προβολής για απόδοση 180+ μορφών εγγράφων σε PDF, HTML και Εικόνα με ευέλικτες επιλογές διαμόρφωσης."
words:
  for: "for"

actions:
  main: "Δωρεάν λήψη NuGet"
  main_link: "https://www.nuget.org/packages/GroupDocs.Viewer"
  alt: "Αδειοδότηση"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/net"
  title: "Είστε έτοιμοι να ξεκινήσετε;"
  description: "Δοκιμάστε τις δυνατότητες του GroupDocs.Viewer δωρεάν ή ζητήστε άδεια"

release:
  title: "Η έκδοση {0} κυκλοφόρησε"
  notes: "Δείτε τι νέο υπάρχει"
  downloads: "Λήψεις"
  link: "https://releases.groupdocs.com/viewer/net/release-notes/latest/"

code:
  title: "Απόδοση αρχείων PDF σε C#"
  more: "Περισσότερα παραδείγματα"
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
  title: "GroupDocs.Viewer με μια ματιά"
  description: "API για απόδοση, εμφάνιση, μετατροπή εγγράφων, διαφανειών, διαγραμμάτων και πολλών άλλων τύπων εγγράφων σε εφαρμογές .NET"
  features:
    # feature loop
    - title: "Προβολή εγγράφων αποτελεσματικά και αξιόπιστα"
      content: "Με το GroupDocs.Viewer API μπορείτε να αποδώσετε αποτελεσματικά έγγραφα οποιασδήποτε υποστηρίσιμης μορφής σε HTML, JPEG, PNG και PDF με ευέλικτες και ισχυρές επιλογές, διατηρώντας παράλληλα την ακεραιότητα του περιεχομένου και της δομής του εγγράφου. Το GroupDocs.Viewer υποστηρίζει .NET Framework 4.6.2 και .NET 6.0, λειτουργεί σε πλατφόρμες Windows και Linux."

    # feature loop
    - title: "Υποστηρίζονται οι πιο δημοφιλείς μορφές αρχείων και εγγράφων"
      content: "Υποστηρίζουμε την απόδοση των 180 πιο δημοφιλών μορφών αρχείων και εγγράφων που περιλαμβάνουν Word, Excel, PDF, PowerPoint, οικογένεια μορφών OpenDocument, Αρχεία, εικόνες Raster και Vector, e-Books, γλώσσες προγραμματισμού και επισημάνσεις, και πολλούς άλλους τύπους αρχείων, συμπεριλαμβανομένων των κρυπτογραφημένων αρχεία με προστασία κωδικού πρόσβασης."

    # feature loop
    - title: "Προσαρμόσιμη έξοδος"
      content: "Το GroupDocs.Viewer επιτρέπει όχι μόνο την απόδοση του εγγράφου, αλλά και τον έλεγχο του πώς ακριβώς, ποια μέρη του εγγράφου πρέπει να αποδοθούν ή τώρα, πώς πρέπει να αποδοθούν και να εφαρμόσει διαφορετικούς μετασχηματισμούς στην απόδοση απόδοσης."

    # feature loop
    - title: "UI για ASP.NET Core"
      content: "Παρέχουμε ένα πακέτο διεπαφής χρήστη ανοιχτού κώδικα για το ASP.NET Core που μπορεί να προστεθεί στο έργο σας σε λίγα λεπτά. Το πακέτο Viewer.UI περιέχει μια διεπαφή ιστού που βασίζεται σε Angular και παρέχει ένα σύνολο χρήσιμων API και παρόχων αποθήκευσης δεδομένων."

############################# Platforms ############################
platforms:
  enable: true
  title: "Ανεξαρτησία πλατφόρμας"
  description: "Το GroupDocs.Viewer για .NET υποστηρίζει τα ακόλουθα λειτουργικά συστήματα, πλαίσια και διαχειριστές πακέτων"
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
  title: "Υποστηριζόμενες μορφές αρχείων"
  description: |
    Το GroupDocs.Viewer για .NET υποστηρίζει λειτουργίες με τις ακόλουθες [μορφές αρχείων](https://docs.groupdocs.com/viewer/net/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office, OpenDocument και μορφές κειμένου
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
        ### Εικόνες, Γραφικά & Διαγράμματα
        * **Εικόνες ράστερ:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
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
        ### Αλλα        
        * **Ιστός:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **Αρχεία:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **Αλλα:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "Λειτουργίες GroupDocs.Viewer"
  description: "Απρόσκοπτη απόδοση, προβολή και μετατροπή εγγράφων PDF και Office"

  items:
    # feature loop
    - icon: "viewhtml"
      title: "Προβολή εγγράφων σε HTML"
      content: "Μετατρέψτε έγγραφο οποιουδήποτε τύπου σε έγγραφο HTML με CSS και SVG, το οποίο μπορεί να εμφανιστεί σε οποιοδήποτε σύγχρονο πρόγραμμα περιήγησης ιστού."

    # feature loop
    - icon: "rasterize"
      title: "Ραστεροποίηση εγγράφων"
      content: "Ραστερίστε οποιαδήποτε υποστηρίσιμη μορφή εγγράφου στην εικόνα ράστερ, με ρυθμιζόμενη μορφή εικόνας και ποιότητα συμπίεσης."

    # feature loop
    - icon: "sourcecode"
      title: "Απόδοση και επισήμανση κωδικών προγραμματισμού"
      content: "Υποστήριξη όλων των δημοφιλών γλωσσών προγραμματισμού, δέσμης ενεργειών και σήμανσης, με δυνατότητα ανάλυσης και επισήμανσης της σύνταξής τους."

    # feature loop
    - icon: "convertpdf"
      title: "Μετατροπή σε PDF"
      content: "Έγγραφο οποιασδήποτε υποστηρίσιμης μορφής μπορεί εύκολα να μετατραπεί και να αποθηκευτεί σε PDF με ρυθμιζόμενες επιλογές."

    # feature loop
    - icon: "transform"
      title: "Εφαρμόστε μετασχηματισμούς"
      content: "Το έγγραφο εξόδου μπορεί να μετατραπεί κατά τη διάρκεια της απόδοσης - οι σελίδες μπορούν να περιστραφούν ή/και να αναδιαταχθούν και να τοποθετηθεί υδατογράφημα κειμένου επάνω τους."

    # feature loop
    - icon: "adjustment"
      title: "Προσαρμογή εξόδου HTML"
      content: "Έγγραφα HTML εξόδου, που δημιουργούνται από το GroupDocs.Viewer, μπορούν να συντονιστούν πολύ καλά: επιτρέπεται η αποθήκευση στη ροή ή το αρχείο, με εξωτερικούς ή ενσωματωμένους πόρους, επιστροφές κλήσης και ούτω καθεξής."

    # feature loop
    - icon: "complex"
      title: "Υποστήριξη πολύπλοκων δομών εγγράφων"
      content: "Το GroupDocs.Viewer υποστηρίζει όχι μόνο τα μεμονωμένα έγγραφα, αλλά και αρχεία, τα οποία εσωτερικά περιέχουν μια λίστα ή ιεραρχική δομή εγγράφων, όπως μηνύματα email με συνημμένα, αρχεία ZIP με εσωτερικά αρχεία μέσα σε φακέλους, εικόνες TIFF πολλών σελίδων κ.λπ."

    # feature loop
    - icon: "optimization"
      title: "Επιλογές βελτιστοποίησης"
      content: "Το GroupDocs.Viewer περιέχει ένα προσαρμόσιμο υποσύστημα προσωρινής μνήμης, το οποίο μπορεί να επιταχύνει το χρόνο φόρτωσης χρησιμοποιώντας τις αποθηκευμένες εκδόσεις των εγγράφων. Επίσης, ένα σύνολο διαφορετικών επιλογών για διαφορετικές μορφές επιτρέπει τον αποκλεισμό ορισμένων περιττών τμημάτων ή πτυχών εγγράφων από την απόδοση (γραμματοσειρές, κρυφά φύλλα εργασίας, συνημμένα email) για βελτιστοποίηση της συνολικής απόδοσης"

    # feature loop
    - icon: "passwordprotected"
      title: "Υποστήριξη εγγράφων που προστατεύονται με κωδικό πρόσβασης"
      content: "Το GroupDocs.Viewer επιτρέπει το άνοιγμα των κρυπτογραφημένων εγγράφων διαφορετικών τύπων: PDF, WordProcessing, Spreadsheet, Presentation και άλλα, καθορίζοντας έναν κωδικό πρόσβασης στις επιλογές φόρτωσης."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Δείγματα κωδικών"
  description: "Ορισμένες περιπτώσεις χρησιμοποιούν τυπικά GroupDocs.Viewer για λειτουργίες .NET"
  items:
    # code sample loop
    - title: "Αποδώστε το DOCX σε HTML"
      content: |
        Οι ιδιότητες κλάσης [HtmlViewOptions](https://reference.groupdocs.com/viewer/net/groupdocs.viewer.options/htmlviewoptions/) σάς επιτρέπουν να ελέγχετε τη διαδικασία μετατροπής, περισσότερα σχετικά [εδώ](https://docs .groupdocs.com/viewer/net/rendering-to-html/). Για παράδειγμα, μπορείτε να ενσωματώσετε όλους τους εξωτερικούς πόρους στο αρχείο HTML εξόδου, να ελαχιστοποιήσετε το αρχείο εξόδου και να το βελτιστοποιήσετε για εκτύπωση.
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
    - title: "Εξαγωγή PPTX σε PDF"
      content: |
        Δημιουργήστε μια παρουσία κλάσης [PdfViewOptions](https://reference.groupdocs.com/viewer/net/groupdocs.viewer.options/pdfviewoptions/) και περάστε την στο [Viewer.View](https://reference.groupdocs. com/viewer/net/groupdocs.viewer/viewer/view/#view) μέθοδος για τη μετατροπή ενός αρχείου PowerPoint PPTX σε PDF. Οι ιδιότητες κλάσης PdfViewOptions σάς επιτρέπουν να ελέγχετε τη διαδικασία μετατροπής. Για παράδειγμα, μπορείτε να προστατεύσετε το αρχείο PDF εξόδου, να αναδιατάξετε τις σελίδες του και να καθορίσετε την ποιότητα των εικόνων του εγγράφου. Ανατρέξτε στην [ακόλουθη ενότητα τεκμηρίωσης](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/) για λεπτομέρειες.
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
# title: "Κριτικές προϊόντων GroupDocs"
# description: "Μην παίρνετε το λόγο μας για αυτό. Δείτε τι λένε άλλοι προγραμματιστές για τα API μας"

# items:
#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "Εξαιρετική εξυπηρέτηση και εξαιρετικά προϊόντα. Ήταν εξαιρετικά χρήσιμοι και ανταποκρίθηκαν κατά τη διαδικασία υλοποίησης του GroupDocs.Viewer για .NET, δεν μπορώ να τα προτείνω αρκετά."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "Μετά την εφαρμογή και χρήση του GroupDocs.Viewer για .NET στο έργο, φαίνεται να λειτουργεί πολύ καλά. Έχω δοκιμάσει με πολλά έγγραφα και μέχρι στιγμής καλά. Όλα όσα έχω ρίξει σε αυτό αποδίδονται όμορφα και φαίνονται εξίσου καλά με ένα πρόγραμμα προβολής PDF ή MS Word."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---