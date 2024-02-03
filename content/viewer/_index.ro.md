---
############################# Static ##########################
layout: "family"
date: 2023-12-20T06:39:57
draft: false

product: "Viewer"
product_tag: "viewer"

############################# Head ############################
head_title: "API de randare și vizualizare a documentelor | On Premise API și serviciu online"
head_description: "Redați și vizualizați fișierele Word, PDF, Excel, Powerpoint sau Image ușor și gratuit"

############################# Header ##########################
title: "Redați și vizualizați documentele cu ușurință"
description: |
  API puternic Viewer pentru a randa diferite fișiere în PDF, HTML și imagine.

  Încărcați documente din diverse surse, inclusiv fișiere, fluxuri, adrese URL, servere FTP, Amazon S3, Azure Blob Storage și multe altele.

  Generați pagini HTML receptive, protejați fișierele PDF de ieșire și reordonați paginile acestora, rotiți paginile, redați note și comentarii dacă este necesar.

############################# Platforms ############################
supported_platforms:
  enable: true  
  head_title: "Alege-ți platforma"
  title: "Platforme acceptate"
  description: "Biblioteca GroupDocs.Viewer acceptă următoarele sisteme de operare și cadre"
  details_link_title: "Află mai multe"
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
        - content: "Peste 180 de formate de fișiere"
          rows: "1"
        # features loop
        - content: "Pachet UI pentru ASP.NET Core"
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
        - content: "Peste 180 de formate de fișiere"
          rows: "1"
        # features loop
        - content:  "Pachet UI pentru Spring și Dropwizard"
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
        - content:  "Peste 180 de formate de fișiere"
          rows: "1"
        # features loop
        - content:  "Pachet UI - în curând"
          rows: "1" 
        # features loop
        - content:  "Demo - în curând"
          rows: "3" 


############################# Features ############################

features:
  enable: true
  title: "Setul de funcții GroupDocs.Viewer"
  description: "API pentru a reda fișiere de diferite tipuri precum HTML, PDF, PNG și JPEG în aplicații pentru a le vizualiza fără software terță parte."

  items:
    # feature loop
    - icon: "view"
      title: "Vizualizați documente și imagini"
      content: "Vizualizați documentele redându-le ca fișiere HTML, PDF, PNG și JPEG."

    # feature loop
    - icon: "password"
      title: "Deschideți documente securizate"
      content: "Specificați o parolă pentru a deschide documente criptate."

    # feature loop
    - icon: "load"
      title: "Încărcați fișiere de oriunde"
      content: "Încărcați documente din diferite fișiere, adrese URL, servere FTP, Amazon S3 și multe altele."
    
    # feature loop
    - icon: "pages"
      title: "Redați toate paginile sau anumite pagini"
      content: "Specificați un interval de numere de pagină care urmează să fie redate."


############################# Code samples ############################
code_samples:
  enable: true
  title: "Exemple de cod GroupDocs.Viewer"
  description: "Unele cazuri de utilizare ale operațiunilor tipice GroupDocs.Viewer în C#, Java, TypeScript"
  items:
    # code sample loop
    - title: "Cum să redați fișierele DOCX în PDF"
      content: |
       Redați documentele DOCX în PDF fără Microsoft Word sau alt software instalat. Încărcați și vizualizați cu ușurință fișierele DOCX în aplicația dvs. .NET, indiferent dacă este o aplicație web sau desktop. Iată un exemplu despre cum să randați un fișier DOCX în PDF:
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Încărcați fișierul DOCX pentru a randa
            using (Viewer viewer = new Viewer("sample.docx"))
            {
              // Redați DOCX într-un fișier PDF
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
            // Încărcați fișierul DOCX pentru a randa
            try (Viewer viewer = new Viewer("sample.docx")) {
                // Redați DOCX într-un fișier PDF
                PdfViewOptions viewOptions = new PdfViewOptions();
                viewer.view(viewOptions);
            }
            ```
        - language: "TypeScript"
          color: "green"
          content: |
            ```javascript {style=abap}  
            // Încărcați fișierul DOCX pentru a randa
            const viewer = new groupdocs.viewer.Viewer("sample.docx")
            
            // Redați DOCX într-un fișier PDF
            const viewOptions = groupdocs.viewer.PdfViewOptions(output.pdf)
            viewer.view(viewOptions)
            ```


############################# Formats ############################
formats:
  enable: true
  title:  "Peste 180 de formate de fișiere acceptate"
  description: "GroupDocs.Viewer acceptă operațiuni cu cele mai populare [formate de fișiere](https://docs.groupdocs.com/viewer/net/supported-document-formats/)"


############################# Metrics ############################

metrics:
  enable: true
  title: "Valori aprofundate și perspective statistice"
  description: "Pătrundeți-vă într-o defalcare detaliată a cifrelor noastre cheie, oferind valori cuprinzătoare și perspective statistice asupra realizărilor, impactului și creșterii noastre."

  items:
    # metrics loop
    - number: "180+"
      title: "Formate acceptate"
      content: "Vizualizați cu ușurință peste 180 de formate de fișiere, inclusiv documente, imagini și desene CAD, fără probleme. Depășiți barierele de compatibilitate și accesați diverse fișiere fără efort cu soluția noastră completă de vizualizare."
    # metrics loop
    - number: "1.0M"
      title: "Descărcări NuGet"
      content: "Soluția noastră de pachet NuGet a devenit o resursă de încredere și adoptată pe scară largă în comunitatea dezvoltatorilor, oferind integrare perfectă și funcționalități valoroase pentru nenumărate proiecte."

    # metrics loop
    - number: "10+"
      title: "Biblioteci"
      content: "Produsul nostru include peste 10 biblioteci, oferind funcții avansate pentru a optimiza performanța. Aceste biblioteci sunt concepute pentru a satisface diferite nevoi de dezvoltare cu capabilități de neegalat."
    
    # metrics loop
    - number: "100+"
      title: "Clienți fericiți"
      content: "Servind cele mai emblematice mărci de pe tot globul. Descoperiți de ce sute iubesc GroupDocs.Viewer! Explorați navigarea perfectă, colaborarea convenabilă și ușurința de utilizare de neegalat. Alătură-te acum!"


############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "Clienții noștri fericiți"
  description: "Bibliotecile GroupDocs sunt folosite de mărci renumite și distinse la nivel global din întreaga lume."

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
  title: "Sunteți gata să începeți?"
  description: "Încercați gratuit funcțiile GroupDocs.Viewer sau solicitați o licență"

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
  title: "Întrebări și preocupări comune"
  description: "Găsiți răspunsuri la întrebările frecvente în secțiunea noastră de întrebări frecvente pentru a vă adresa rapid întrebărilor și preocupărilor."

  items:
    #  loop
    - question: "Pot evalua produsele GroupDocs înainte de a cumpăra?"
      answer: |
        Da! Toate produsele GroupDocs au o versiune de evaluare fără riscuri disponibilă. Încurajăm cu tărie dezvoltatorii să descarce și să încerce API-urile noastre înainte de a cumpăra, pentru a ne asigura că vă vor satisface nevoile 100%.
    #  loop
    - question: "GroupDocs face demonstrații de produse?"
      answer: |
        Nu, ne concentrăm pe API-urile noastre și pe realizarea celor mai funcționale și mai stabile produse posibile. Oferim încercări complet funcționale și gratuite sub forma unei [licențe temporare](https://purchase.groupdocs.com/temporary-license/), astfel încât să puteți testa singur produsul.
    #  loop
    - question: "De unde pot descărca produsul?"
      answer: |
        Toate produsele sunt disponibile pentru descărcare de pe [site-ul web](https://releases.groupdocs.com). Nu trimitem copii fizice ale software-ului nostru prin poștă.    
    #  loop
    - question: "Sunt licențele de dezvoltator GroupDocs per utilizator sau pentru fiecare utilizator numit?"
      answer: |
        Licențele pentru dezvoltatori GroupDocs sunt pentru fiecare utilizator, nu pentru fiecare utilizator numit. Înțelegem că membrii unei echipe de codificare se pot schimba în timp și că nu este practic să fie necesar să actualizați licențele de fiecare dată când se întâmplă acest lucru.
    #  loop
    - question: "Avem nevoie de licență doar pentru dezvoltatorii activi? De exemplu, avem o echipă de doi dezvoltatori care lucrează pe tura A și o a doua echipă de doi dezvoltatori care lucrează pe tura B... în această situație, avem nevoie de două sau patru licențe?"
      answer: |
        Toți dezvoltatorii care lucrează la proiect trebuie să fie licențiați. În această situație, GroupDocs vede echipa ta ca având patru membri (chiar dacă lucrează în momente diferite).

############################# Cloud ############################

cloud_links:
  enable: true
  title: "API-uri de cod redus GroupDocs.Viewer"
  description: "Accelerați vizualizarea documentelor sau imaginilor în orice tip de aplicație cu API-ul nostru REST bazat pe cloud"

  items:
    #  loop
    - icon: "groupdocs_viewer-for-curl"
      title: "GroupDocs.Viewer Cloud for cURL"
      link: "https://products.groupdocs.cloud/viewer/curl"
      content: "Utilizați API-ul de vizualizare a documentelor cURL RESTful pentru a reda și a prezenta eficient Microsoft Office, PDF și diverse alte formate standard de fișiere în aplicațiile dvs."

    #  loop
    - icon: "groupdocs_viewer-for-net"
      title: "GroupDocs.Viewer Cloud for .NET"
      link: "https://products.groupdocs.cloud/viewer/net"
      content: "Îmbunătățiți capabilitățile de vizualizare a documentelor în aplicațiile .NET cu Cloud SDK pentru .NET. Vizualizați documentele fără probleme în formate HTML, PDF sau imagine."
    #  loop
    - icon: "groupdocs_viewer-for-java"
      title: "GroupDocs.Viewer Cloud for Java"
      link: "https://products.groupdocs.cloud/viewer/java"
      content: "Integrați capabilități avansate de redare a documentelor în aplicațiile dvs. Java utilizând un SDK pentru vizualizarea documentelor creat special pentru Java."

############################# Apps ############################

app_links:
  enable: true
  title: "Aplicații GroupDocs.Viewer NoCode"
  description: "Aplicație online care vă permite să vizualizați peste 180 de formate de fișiere populare în browser"

  items:
    #  loop
    - icon: "groupdocs_viewer-app"
      title: "GroupDocs.Viewer Total"
      link: "https://products.groupdocs.app/viewer/total"
      content: "Explorați o aplicație online gratuită pentru a vizualiza peste 180 de formate de fișiere direct din browserul dvs. web preferat."

    #  loop
    - icon: "groupdocs_words-app"
      title:  "GroupDocs.Viewer DOCX"
      link: "https://products.groupdocs.app/viewer/docx"
      content: "Instrument bazat pe web pentru vizualizarea fără efort a fișierelor Microsoft Word pe diferite dispozitive."

    #  loop
    - icon: "groupdocs_pdf-app"
      title:  "GroupDocs.Viewer PDF"
      link: "https://products.groupdocs.app/viewer/pdf"
      content: "Deschideți și vizualizați fișiere PDF online cu vizualizatorul PDF gratuit."
    

---