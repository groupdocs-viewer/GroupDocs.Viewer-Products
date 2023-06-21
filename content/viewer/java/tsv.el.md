---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: el

############################# Head #############################
head_title: "Java TSV API προβολής - Απόδοση και εμφάνιση TSV σε εφαρμογές Java"
head_description: "Προβολή αρχείων TSV σε εφαρμογές Java, J2EE, J2SE. Υποστηρίζει την προβολή 170+ μορφών αρχείων εγγράφων και εικόνων σε λειτουργία HTML, PDF ή εικόνας με προηγμένες λειτουργίες για τη διαχείριση των επιλογών προβολής εγγράφων."

############################# Header ############################
title: "Απόδοση και προβολή TSV σε Java" 
description: "Εγγενές και υψηλής απόδοσης TSV API προβολής αρχείων για εφαρμογές που βασίζονται σε Java, J2EE και J2SE, που υποστηρίζει ένα ευρύ φάσμα πρόσθετων λειτουργιών για την προσαρμογή της εμφάνισης της μορφής εγγράφου εξόδου." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Κατεβάστε δωρεάν δοκιμή"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Σχετικά με το GroupDocs.Viewer for Java API" 
    content: |
        Ενεργοποιήστε τις εφαρμογές σας Java να εμφανίζουν περισσότερες από 170 μορφές αρχείων σε λειτουργίες HTML, PDF ή εικόνας χρησιμοποιώντας το GroupDocs.Viewer για Java API χωρίς να έχει εγκατασταθεί κανένα πρόσθετο λογισμικό. όπως το Microsoft Office, το Apache Open Office, το Adobe Acrobat Reader κ.λπ. Οι προγραμματιστές μπορούν εύκολα να δουν όλες τις δημοφιλείς εικόνες και τύπους εγγράφων, όπως Microsoft Office, OpenDocument, HTML, PDF, Archive, Diagrams, Photoshop, AutoCAD και μορφές γλώσσας προγραμματισμού μέσα στις εφαρμογές Java με γρήγορη και ποιοτική απόδοση.

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
    title_left: "Βήματα για την απόδοση του αρχείου TSV στο Java" 
    content_left: |
        Με το [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/) μπορείτε να αποδώσετε το TSV σε HTML, JPEG, PNG ή PDF σε λίγα βήματα.

        * Προσθέστε το [GroupDocs.Viewer για Java](https://releases.groupdocs.com/viewer/java/) ως εξάρτηση στο έργο σας. 
        * Δημιουργήστε μια παρουσία της κλάσης Viewer και φορτώστε το αρχείο TSV με πλήρη διαδρομή. 
        * Ορίστε επιλογές για απόδοση του αρχείου TSV σε μορφή HTML, PNG, JPEG ή PDF. 
        * Αποδώστε το αρχείο και ελέγξτε την έξοδο στον τρέχοντα κατάλογο. 
        
    title_right: "Απαιτήσεις συστήματος" 
    content_right: |
        Τα GroupDocs.Viewer για Java API υποστηρίζονται σε όλες τις μεγάλες πλατφόρμες και λειτουργικά συστήματα. Πριν εκτελέσετε τον παρακάτω κώδικα, βεβαιωθείτε ότι έχετε εγκαταστήσει τις ακόλουθες προϋποθέσεις στο σύστημά σας.

        * Λειτουργικά συστήματα: Microsoft Windows, Linux, MacOS 
        * Περιβάλλοντα Ανάπτυξης: NetBeans, IntelliJ IDEA, Eclipse κ.λπ. 
        * Πλαίσια: J2SE 8.0 (1.8) ή νεότερη έκδοση (για παράδειγμα Java 17) 
    code: |
        ```java
                        
            // Set up input TSV file
            String filePath = "input.tsv";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render TSV file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "TSV Ζωντανή επίδειξη προβολής"
    content: |
        Δείτε το αρχείο TSV αυτήν τη στιγμή, μεταβαίνοντας στον ιστότοπο [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/tsv).
    lang: "el"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Άλλες μορφές αρχείων Απόδοση και προβολή με χρήση Java"
    exclude: "TSV"
    content: |
        API προβολής εγγράφων και εικόνων πολλαπλών μορφών για Java. Δείτε μερικές από τις δημοφιλείς μορφές αρχείων παρακάτω χωρίς κανένα εξωτερικό πρόγραμμα προβολής.
    format: 
        # format loop 1
        - name: "Απόδοση DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Open XML Document" 

        # format loop 2
        - name: "Απόδοση CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "Αρχείο CorelDRAW" 

        # format loop 3
        - name: "Απόδοση PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint Ανοίξτε την παρουσίαση XML" 

        # format loop 4
        - name: "Απόδοση XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Άνοιγμα υπολογιστικού φύλλου XML" 

        # format loop 5
        - name: "Απόδοση DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "Σχέδιο AutoCAD"

        # format loop 6
        - name: "Απόδοση XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "Αρχείο XML"

        # format loop 7
        - name: "Απόδοση PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Έγγραφο Adobe Photoshop"

        # format loop 8
        - name: "Αποδώστε το αρχείο Adobe Illustrator"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Έργο τέχνης Adobe Illustrator"

        # format loop 9
        - name: "Απόδοση DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Έγγραφο Microsoft Word" 

        # format loop 10
        - name: "Απόδοση TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Αρχείο απλού κειμένου" 

        # format loop 11
        - name: "Απόδοση DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Σχέδιο αρχείου μορφής Exchange"  
          
        # format loop 12
        - name: "Απόδοση VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "Αρχείο vCard"  
              
        # format loop 13
        - name: "Απόδοση SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Κλιμακόμενα διανυσματικά γραφικά" 
          
        # format loop 14
        - name: "Απόδοση HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Αρχείο γλώσσας σήμανσης υπερκειμένου" 
          
        # format loop 15
        - name: "Απόδοση PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Φορητό αρχείο μορφής εγγράφου"
          
        # format loop 16
        - name: "Απόδοση JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "Εικόνα JPEG"
          
        # format loop 17
        - name: "Απόδοση PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Φορητό γραφικό δικτύου" 
          
        # format loop 18
        - name: "Απόδοση EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "Μήνυμα E-Mail" 
          
        # format loop 19
        - name: "Απόδοση RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Αρχείο μορφής εμπλουτισμένου κειμένου" 
          
        # format loop 20
        - name: "Απόδοση ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "Έγγραφο κειμένου OpenDocument" 
          
        # format loop 21
        - name: "Απόδοση CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Αρχείο τιμών διαχωρισμένων με κόμματα" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
