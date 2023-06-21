---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: el

############################# Head #############################
head_title: ".NET IGS API προβολής - Ανάγνωση, προβολή, απόδοση σε C# VB.NET"
head_description: "API προβολής εγγράφων .NET για ανάγνωση, απόδοση και εμφάνιση του IGS σε οποιονδήποτε τύπο εφαρμογών C#, ASP.NET, VB.NET και .NET Core."

############################# Header ############################
title: "IGS Προβολή αρχείων για εφαρμογές C# .NET" 
description: "API προβολής εγγράφων .NET για ανάγνωση, απόδοση και εμφάνιση αρχείου IGS σε οποιονδήποτε τύπο εφαρμογών C#, ASP.NET, VB.NET και .NET Core. Δείτε τα αποδοθέντα αρχεία με αληθινή μορφοποίηση και διάταξη σε HTML5, PDF ή ως εικόνα χρησιμοποιώντας μερικές γραμμές του κώδικα." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Κατεβάστε δωρεάν δοκιμή"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Σχετικά με το GroupDocs.Viewer για .NET API" 
    content: |
        Ξεκινήστε την προβολή 190+ δημοφιλών μορφών εγγράφων στις εφαρμογές σας .NET χρησιμοποιώντας το GroupDocs.Viewer για API .NET προσθέτοντας μερικές γραμμές κώδικα. Οι προγραμματιστές μπορούν εύκολα να εμφανίσουν PDF, Επεξεργασία κειμένου, Υπολογιστικό φύλλο Excel, Παρουσίαση, Visio, Project, Outlook και πολλές άλλες δημοφιλείς μορφές εγγράφων σε λειτουργίες HTML5, εικόνας ή PDF. Η απόδοση του εγγράφου είναι γρήγορη, πανομοιότυπη με το αρχικό αρχείο προέλευσης και δεν απαιτεί εγκατάσταση πρόσθετου λογισμικού ή άλλων εξωτερικών βιβλιοθηκών.

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
              text: "Αναφορά API"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Παραδείγματα κώδικα"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Live Demos"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Τιμολόγηση"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "Βήματα για την απόδοση του αρχείου IGS στο C#" 
    content_left: |
        Με το [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/) μπορείτε να αποδώσετε το IGS σε HTML, JPEG, PNG ή PDF σε λίγα βήματα.

        * Εγκαταστήστε το [GroupDocs.Viewer για .NET](https://www.nuget.org/packages/groupdocs.viewer) χρησιμοποιώντας τον αγαπημένο σας διαχειριστή πακέτων. 
        * Δημιουργήστε μια παρουσία της κλάσης Viewer και φορτώστε το αρχείο IGS με πλήρη διαδρομή. 
        * Ορίστε επιλογές για απόδοση του αρχείου IGS σε μορφή HTML, PNG, JPEG ή PDF. 
        * Αποδώστε το αρχείο και ελέγξτε την έξοδο στον τρέχοντα κατάλογο. 
        
    title_right: "Απαιτήσεις συστήματος" 
    content_right: |
        Το GroupDocs.Viewer για API .NET υποστηρίζεται σε όλες τις μεγάλες πλατφόρμες και λειτουργικά συστήματα. Πριν εκτελέσετε τον παρακάτω κώδικα, βεβαιωθείτε ότι έχετε εγκαταστήσει τις ακόλουθες προϋποθέσεις στο σύστημά σας.

        * Λειτουργικά συστήματα: Microsoft Windows, Linux, MacOS 
        * Περιβάλλοντα ανάπτυξης: Microsoft Visual Studio, Visual Studio Code, .NET CLI 
        * Frameworks: .NET Framework, .NET Standard, .NET Core, .NET 
    code: |
        ```cs
                        
            // Set up input IGS file
            string filePath = "input.igs";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render IGS file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "IGS Ζωντανή επίδειξη προβολής"
    content: |
        Δείτε το αρχείο IGS αυτήν τη στιγμή, μεταβαίνοντας στον ιστότοπο [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/igs).
    lang: "el"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Άλλες μορφές αρχείων Απόδοση και προβολή με χρήση C#"
    exclude: "IGS"
    content: |
        API προβολής εγγράφων και εικόνων πολλαπλών μορφών για .NET. Δείτε μερικές από τις δημοφιλείς μορφές αρχείων παρακάτω χωρίς κανένα εξωτερικό πρόγραμμα προβολής.
    format: 
        # format loop 1
        - name: "Απόδοση DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word Open XML Document" 

        # format loop 2
        - name: "Απόδοση CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "Αρχείο CorelDRAW" 

        # format loop 3
        - name: "Απόδοση PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint Ανοίξτε την παρουσίαση XML" 

        # format loop 4
        - name: "Απόδοση XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Άνοιγμα υπολογιστικού φύλλου XML" 

        # format loop 5
        - name: "Απόδοση DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "Σχέδιο AutoCAD"

        # format loop 6
        - name: "Απόδοση XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "Αρχείο XML"

        # format loop 7
        - name: "Απόδοση PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Έγγραφο Adobe Photoshop"

        # format loop 8
        - name: "Αποδώστε το αρχείο Adobe Illustrator"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Έργο τέχνης Adobe Illustrator"

        # format loop 9
        - name: "Απόδοση DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Έγγραφο Microsoft Word" 

        # format loop 10
        - name: "Απόδοση TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Αρχείο απλού κειμένου" 

        # format loop 11
        - name: "Απόδοση DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Σχέδιο αρχείου μορφής Exchange"  
          
        # format loop 12
        - name: "Απόδοση VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "Αρχείο vCard"  
              
        # format loop 13
        - name: "Απόδοση SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Κλιμακόμενα διανυσματικά γραφικά" 
          
        # format loop 14
        - name: "Απόδοση HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Αρχείο γλώσσας σήμανσης υπερκειμένου" 
          
        # format loop 15
        - name: "Απόδοση PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Φορητό αρχείο μορφής εγγράφου"
          
        # format loop 16
        - name: "Απόδοση JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "Εικόνα JPEG"
          
        # format loop 17
        - name: "Απόδοση PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Φορητό γραφικό δικτύου" 
          
        # format loop 18
        - name: "Απόδοση EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "Μήνυμα E-Mail" 
          
        # format loop 19
        - name: "Απόδοση RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Αρχείο μορφής εμπλουτισμένου κειμένου" 
          
        # format loop 20
        - name: "Απόδοση ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "Έγγραφο κειμένου OpenDocument" 
          
        # format loop 21
        - name: "Απόδοση CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Αρχείο τιμών διαχωρισμένων με κόμματα" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
