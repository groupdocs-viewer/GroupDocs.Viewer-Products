---
############################# Static ############################
layout: "family"
date: 2023-12-20T06:39:57
draft: false

product: "Viewer"
product_tag: "viewer"

############################# Head ############################
head_title: "API απόδοσης και προβολής εγγράφων | On Premise API και ηλεκτρονική υπηρεσία"
head_description: "Αποδώστε και προβάλετε αρχεία Word, PDF, Excel, Powerpoint ή Image εύκολα και δωρεάν"

############################# Header ############################
title: "Αποδώστε και προβάλετε έγγραφα με ευκολία"
description: |
  Ισχυρό API Viewer για απόδοση διαφορετικών αρχείων σε PDF, HTML και Εικόνα.

  Φορτώστε έγγραφα από διάφορες πηγές, συμπεριλαμβανομένων αρχείων, ροών, διευθύνσεων URL, διακομιστών FTP, Amazon S3, αποθήκευσης Azure Blob και άλλων.

  Δημιουργήστε σελίδες HTML με απόκριση, προστατέψτε τα αρχεία PDF εξόδου και αναδιατάξτε τις σελίδες τους, περιστρέψτε σελίδες, αποδώστε σημειώσεις και σχόλια εάν χρειάζεται.
  

############################# Platforms ############################
supported_platforms:
  enable: true  
  head_title: "Επιλέξτε την πλατφόρμα σας"
  title: "Υποστηριζόμενες πλατφόρμες"
  description: "Η βιβλιοθήκη GroupDocs.Viewer υποστηρίζει τα ακόλουθα λειτουργικά συστήματα και πλαίσια"
  details_link_title: "Μάθε περισσότερα"
  items:
    # supported_platforms loop
    - title: ".NET"
      description: "GroupDocs.Viewer for .NET"
      color: "blue"
      tag: "net"
      link: "/viewer/net/"
      features_link: "https://docs.groupdocs.com/viewer/net/system-requirements/"
      features:
        # features loop
        - content: ".NET Framework 4.6.2+  <br>  .NET Core 3.1  <br>  .NET 6+"
          rows: "3"
        # features loop
        - content: "Windows, Linux"
          rows: "1"
        # features loop
        - content: "180+ file formats"
          rows: "1"
        # features loop
        - content: "UI package for ASP.NET Core"
          rows: "1"
        # features loop
        - content: "ASP.NET WebForms Demo  <br>  ASP.NET MVC Demo  <br>  ASP.NET Core Demo"
          rows: "3"
    
    # supported_platforms loop
    - title: "Java"
      description: "GroupDocs.Viewer for Java"
      color: "red"
      tag: "java"
      link: "/viewer/java/"
      features_link: "https://docs.groupdocs.com/viewer/java/system-requirements/"
      features:
        # features loop
        - content: "J2SE 8.0 (1.8)+"
          rows: "3"
        # features loop
        - content:  "Windows, Linux, macOS"
          rows: "1"       
        # features loop
        - content:  "180+ file formats"
          rows: "1"
        # features loop
        - content:  "UI package for Spring and Dropwizard"
          rows: "1"
        # features loop
        - content:  "Spring Demo  <br>  Dropwizard demo"
          rows: "3"

    # supported_platforms loop
    - title: "Node.js"
      description: "GroupDocs.Viewer for Node.js"
      color: "green"
      tag: "nodejs-java"
      link: "/viewer/nodejs-java/"
      features_link: "https://docs.groupdocs.com/viewer/nodejs-java/system-requirements/"
      features:
        # features loop
        - content: "Node.js 16+  <br>  and J2SE 8.0 (1.8)+"
          rows: "3"
        # features loop
        - content:  "Windows, Linux, macOS"
          rows: "1"
        # features loop
        - content:  "180+ file formats"
          rows: "1"
        # features loop
        - content:  "UI package - coming soon "
          rows: "1" 
        # features loop
        - content:  "Demo - coming soon "
          rows: "3" 



############################# Features ############################

features:
  enable: true
  title: "Σύνολο δυνατοτήτων του GroupDocs.Viewer"
  description: "API για απόδοση αρχείων διαφορετικών τύπων όπως HTML, PDF, PNG και JPEG σε εφαρμογές για προβολή τους χωρίς λογισμικό τρίτων."

  items:
    # feature loop
    - icon: "view"
      title: "Προβολή εγγράφων και εικόνων"
      content: "Προβάλετε έγγραφα αποδίδοντάς τα ως αρχεία HTML, PDF, PNG και JPEG."
    # feature loop
    - icon: "password"
      title: "Ανοίξτε ασφαλή έγγραφα"
      content: "Καθορίστε έναν κωδικό πρόσβασης για το άνοιγμα κρυπτογραφημένων εγγράφων."

    # feature loop
    - icon: "load"
      title: "Φόρτωση αρχείων από οπουδήποτε"
      content: "Φορτώστε έγγραφα από διάφορα αρχεία, διευθύνσεις URL, διακομιστές FTP, Amazon S3 και άλλα."
    
    # feature loop
    - icon: "pages"
      title: "Απόδοση όλων ή συγκεκριμένων σελίδων"
      content: "Καθορίστε ένα εύρος αριθμών σελίδων προς απόδοση."


############################# Code samples ############################
code_samples:
  enable: true
  title: "Δείγματα κώδικα GroupDocs.Viewer"
  description: "Ορισμένες περιπτώσεις χρησιμοποιούν τυπικές λειτουργίες GroupDocs.Viewer σε C#, Java, TypeScript"
  items:
    # code sample loop
    - title: "Πώς να αποδώσετε αρχεία DOCX σε PDF"
      content: |
        Αποδώστε έγγραφα DOCX σε PDF χωρίς εγκατεστημένο το Microsoft Word ή άλλο λογισμικό. Φορτώστε και προβάλετε εύκολα αρχεία DOCX στην εφαρμογή σας .NET, είτε πρόκειται για εφαρμογή web είτε για επιτραπέζιους υπολογιστές. Ακολουθεί ένα παράδειγμα του τρόπου απόδοσης ενός αρχείου DOCX σε PDF: 
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Φορτώστε το αρχείο DOCX για απόδοση
            using (Viewer viewer = new Viewer("sample.docx"))
            {
              // Αποδώστε το DOCX σε αρχείο PDF
              PdfViewOptions viewOptions = new PdfViewOptions();
              viewer.View(viewOptions);
            }
            ```
        - language: "Java"
          color: "red"
          content: |
            ```java {style=abap}   
            import com.groupdocs.viewer.Viewer;
            import com.groupdocs.viewer.options.PdfViewOptions;
            // ...
            // Φορτώστε το αρχείο DOCX για απόδοση
            try (Viewer viewer = new Viewer("sample.docx")) {
                // Αποδώστε το DOCX σε αρχείο PDF
                PdfViewOptions viewOptions = new PdfViewOptions();
                viewer.view(viewOptions);
            }
            ```
        - language: "TypeScript"
          color: "green"
          content: |
            ```javascript {style=abap}  
            // Φορτώστε το αρχείο DOCX για απόδοση
            const viewer = new groupdocs.viewer.Viewer("sample.docx")
            
            // Αποδώστε το DOCX σε αρχείο PDF
            const viewOptions = groupdocs.viewer.PdfViewOptions(output.pdf)
            viewer.view(viewOptions)
            ```


############################# Formats ############################
formats:
  enable: true
  title:  "Υποστηρίζονται 180+ μορφές αρχείων"
  description: "Το GroupDocs.Viewer υποστηρίζει λειτουργίες με τις πιο δημοφιλείς [μορφές αρχείων](https://docs.groupdocs.com/viewer/net/supported-document-formats/)" 



############################# Metrics ############################

metrics:
  enable: true
  title: "Σε βάθος μετρήσεις και στατιστικές πληροφορίες"
  description: "Ανακαλύψτε μια λεπτομερή ανάλυση των βασικών μας στοιχείων, παρέχοντας ολοκληρωμένες μετρήσεις και στατιστικές πληροφορίες για τα επιτεύγματά μας, τον αντίκτυπο και την ανάπτυξή μας."

  items:
    # metrics loop
    - number: "180+"
      title: "Υποστηριζόμενες μορφές"
      content: "Προβάλετε εύκολα πάνω από 180 μορφές αρχείων, συμπεριλαμβανομένων εγγράφων, εικόνων και σχεδίων CAD χωρίς προβλήματα. Σπάστε τα εμπόδια συμβατότητας και αποκτήστε πρόσβαση σε διάφορα αρχεία χωρίς κόπο με την ολοκληρωμένη λύση προβολής μας."

    # metrics loop
    - number: "1.0M"
      title: "Λήψεις NuGet"
      content: "Η λύση πακέτου NuGet έχει γίνει ένας αξιόπιστος και ευρέως διαδεδομένος πόρος στην κοινότητα προγραμματιστών, παρέχοντας απρόσκοπτη ενοποίηση και πολύτιμη λειτουργικότητα για αμέτρητα έργα."

    # metrics loop
    - number: "10+"
      title: "Βιβλιοθήκες"
      content: "Το προϊόν μας περιλαμβάνει 10+ βιβλιοθήκες, προσφέροντας προηγμένες λειτουργίες για βελτιστοποίηση της απόδοσης. Αυτές οι βιβλιοθήκες έχουν σχεδιαστεί για να ικανοποιούν διαφορετικές ανάγκες ανάπτυξης με απαράμιλλες δυνατότητες."
    
    # metrics loop
    - number: "100+"
      title: "Ευτυχισμένοι πελάτες"
      content: "Εξυπηρετεί τις πιο εμβληματικές μάρκες σε όλο τον κόσμο. Ανακαλύψτε γιατί εκατοντάδες λατρεύουν το GroupDocs.Viewer! Εξερευνήστε την απρόσκοπτη πλοήγηση, τη βολική συνεργασία και την απαράμιλλη ευκολία χρήσης. Πάρε μέρος τώρα!"



############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "Οι ευχαριστημένοι πελάτες μας"
  description: "Οι βιβλιοθήκες GroupDocs χρησιμοποιούνται από παγκοσμίου φήμης και διακεκριμένες μάρκες σε όλο τον κόσμο."

  items:
    # customers loop
    - title: "BenQ Corporation"
      logo: "benq"
    # customers loop
    - title: "Nasdaq Stock Market"
      logo: "nasdaq"
    # customers loop
    - title: "AT&T Inc."
      logo: "att"
    # customers loop
    - title: "AstraZeneca"
      logo: "astrazeneca"
    # customers loop
    - title: "Central Bank of Argentina"
      logo: "argentinacentralbank"
    # customers loop
    - title: "Roche Holding AG"
      logo: "roche"
    # customers loop
    - title: "Capita"
      logo: "capita"
    # customers loop
    - title: "Axa S.A."
      logo: "axa"
    # customers loop
    - title: "Instructure Inc."
      logo: "instructure"
     # customers loop
    - title: "Wipro"
      logo: "wipro"



############################# Actions ############################

actions:
  enable: true
  title: "Είστε έτοιμοι να ξεκινήσετε;"
  description: "Δοκιμάστε τις δυνατότητες του GroupDocs.Viewer δωρεάν ή ζητήστε άδεια"
  items:
    #  loop
    - title: ".NET"
      link: "/viewer/net/"
      color: "blue"
        #  loop
    - title: "Java"
      link: "/viewer/java/"
      color: "red"
        #  loop
    - title: "Node.js"
      link: "/viewer/nodejs-java/"
      color: "green"


############################# Faq ############################

faq:
  enable: true
  title:  "Συνήθεις ερωτήσεις και προβληματισμοί"
  description:  "Βρείτε απαντήσεις σε κοινά ερωτήματα στην ενότητα Συχνές Ερωτήσεις για να αντιμετωπίσετε γρήγορα τα ερωτήματα και τις ανησυχίες σας."
  items:
    #  loop
    - question: "Μπορώ να αξιολογήσω τα προϊόντα GroupDocs πριν από την αγορά;"
      answer: |
        Ναί! Όλα τα προϊόντα GroupDocs διαθέτουν μια έκδοση αξιολόγησης χωρίς κινδύνους. Ενθαρρύνουμε θερμά τους προγραμματιστές να κατεβάσουν και να δοκιμάσουν τα API μας πριν από την αγορά, για να διασφαλίσουν ότι θα καλύψουν τις ανάγκες σας 100%.
    #  loop
    - question: "Το GroupDocs κάνει επιδείξεις προϊόντων;"
      answer: |
        Όχι, η εστίασή μας είναι στα API μας και στην παραγωγή των πιο λειτουργικών και σταθερών δυνατών προϊόντων. Προσφέρουμε πλήρως λειτουργικές και δωρεάν δοκιμές με τη μορφή [προσωρινής άδειας](https://purchase.groupdocs.com/temporary-license/), ώστε να μπορείτε να δοκιμάσετε το προϊόν μόνοι σας.    
    #  loop
    - question: "Πού μπορώ να κατεβάσω το προϊόν;"
      answer: |
        Όλα τα προϊόντα είναι διαθέσιμα για λήψη από τον [ιστότοπο](https://releases.groupdocs.com). Δεν αποστέλλουμε φυσικά αντίγραφα του λογισμικού μας μέσω ταχυδρομείου.
    #  loop
    - question: "Είναι άδειες προγραμματιστών του GroupDocs ανά χρήστη ή ανά επώνυμο χρήστη;"
      answer: |
        Οι άδειες προγραμματιστή του GroupDocs είναι ανά χρήστη και όχι ανά χρήστη. Κατανοούμε ότι τα μέλη μιας ομάδας κωδικοποίησης ενδέχεται να αλλάξουν με την πάροδο του χρόνου και ότι δεν είναι πρακτικό να χρειάζεται να ενημερώνετε την αδειοδότηση κάθε φορά που συμβαίνει.
    #  loop
    - question: "Χρειαζόμαστε άδεια χρήσης μόνο για ενεργούς προγραμματιστές; Για παράδειγμα, έχουμε μια ομάδα δύο προγραμματιστών που εργάζονται στη βάρδια Α και μια δεύτερη ομάδα δύο προγραμματιστών που εργάζονται στη βάρδια Β… σε αυτήν την περίπτωση, χρειαζόμαστε δύο ή τέσσερις άδειες;"
      answer: |
        Όλοι οι προγραμματιστές που εργάζονται στο έργο πρέπει να έχουν άδεια. Σε αυτήν την περίπτωση, το GroupDocs βλέπει την ομάδα σας να έχει τέσσερα μέλη (παρόλο που εργάζονται σε διαφορετικούς χρόνους). 


############################# Cloud ############################

cloud_links:
  enable: true
  title: "GroupDocs.Viewer χαμηλού κώδικα API"
  description: "Επιταχύνετε την προβολή εγγράφων ή εικόνων σε οποιονδήποτε τύπο εφαρμογής με το REST API που βασίζεται σε σύννεφο"

  items:
    #  loop
    - icon: "groupdocs_viewer-for-curl"
      title: "GroupDocs.Viewer Cloud for cURL"
      link: "https://products.groupdocs.cloud/viewer/curl"
      content: "Χρησιμοποιήστε το API προβολής εγγράφων cURL RESTful για αποτελεσματική απόδοση και προβολή του Microsoft Office, του PDF και διαφόρων άλλων τυπικών μορφών αρχείων στις εφαρμογές σας."

    #  loop
    - icon: "groupdocs_viewer-for-net"
      title: "GroupDocs.Viewer Cloud for .NET"
      link: "https://products.groupdocs.cloud/viewer/net"
      content: "Βελτιώστε τις δυνατότητες προβολής εγγράφων σε εφαρμογές .NET με το Cloud SDK για .NET. Προβάλετε έγγραφα απρόσκοπτα σε μορφές HTML, PDF ή εικόνας."

    #  loop
    - icon: "groupdocs_viewer-for-java"
      title: "GroupDocs.Viewer Cloud for Java"
      link: "https://products.groupdocs.cloud/viewer/java"
      content: "Ενσωματώστε προηγμένες δυνατότητες απόδοσης εγγράφων στις εφαρμογές σας Java χρησιμοποιώντας ένα ειδικά διαμορφωμένο SDK προβολής εγγράφων για Java."
    

############################# Apps ############################

app_links:
  enable: true
  title: "Εφαρμογές GroupDocs.Viewer NoCode"
  description: "Διαδικτυακή εφαρμογή που σας επιτρέπει να προβάλλετε 180+ δημοφιλείς μορφές αρχείων στο πρόγραμμα περιήγησης"

  items:
    #  loop
    - icon: "groupdocs_viewer-app"
      title: "GroupDocs.Viewer Total"
      link: "https://products.groupdocs.app/viewer/total"
      content: "Εξερευνήστε μια δωρεάν διαδικτυακή εφαρμογή για να δείτε περισσότερες από 180 μορφές αρχείων απευθείας από το πρόγραμμα περιήγησης ιστού που προτιμάτε."

    #  loop
    - icon: "groupdocs_words-app"
      title:  "GroupDocs.Viewer DOCX"
      link: "https://products.groupdocs.app/viewer/docx"
      content: "Βασισμένο στο Web εργαλείο για την εύκολη προβολή αρχείων Microsoft Word σε διάφορες συσκευές."

    #  loop
    - icon: "groupdocs_pdf-app"
      title:  "GroupDocs.Viewer PDF"
      link: "https://products.groupdocs.app/viewer/pdf"
      content: "Ανοίξτε και προβάλετε αρχεία PDF online με δωρεάν πρόγραμμα προβολής PDF."
    



---