---
############################# Static ############################
layout: "family"
date: 2023-12-20T06:39:57
draft: false

product: "Viewer"
product_tag: "viewer"

############################# Head ############################
head_title: "API za prikaz i pregled dokumenata | On Premise API i online usluga"
head_description: "Renderirajte i pregledajte Word, PDF, Excel, Powerpoint ili slikovne datoteke jednostavno i besplatno"

############################# Header ############################
title: "Renderirajte i pregledavajte dokumente s lakoćom"
description: |
  Snažan API preglednika za renderiranje različitih datoteka u PDF, HTML i slike.

  Učitajte dokumente iz raznih izvora, uključujući datoteke, tokove, URL-ove, FTP poslužitelje, Amazon S3, Azure Blob Storage i više.

  Generirajte responzivne HTML stranice, zaštitite izlazne PDF datoteke i promijenite redoslijed njihovih stranica, rotirajte stranice, renderirajte bilješke i komentare ako je potrebno.
  

############################# Platforms ############################
supported_platforms:
  enable: true  
  head_title: "Odaberite svoju platformu"
  title: "Podržane platforme"
  description: "Biblioteka GroupDocs.Viewer podržava sljedeće operativne sustave i okvire"
  details_link_title: "Saznajte više"
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
  title: "GroupDocs.Viewer skup značajki"
  description: "API za renderiranje datoteka različitih vrsta kao što su HTML, PDF, PNG i JPEG u aplikacijama za njihov pregled bez softvera treće strane."

  items:
    # feature loop
    - icon: "view"
      title: "Pregledajte dokumente i slike"
      content: "Pregledajte dokumente renderirajući ih kao HTML, PDF, PNG i JPEG datoteke."
    # feature loop
    - icon: "password"
      title: "Otvorite zaštićene dokumente"
      content: "Navedite lozinku za otvaranje šifriranih dokumenata."

    # feature loop
    - icon: "load"
      title: "Učitajte datoteke s bilo kojeg mjesta"
      content: "Učitajte dokumente iz raznih datoteka, URL-ova, FTP poslužitelja, Amazon S3 i više."
    
    # feature loop
    - icon: "pages"
      title: "Prikaz svih ili određenih stranica"
      content: "Odredite raspon brojeva stranica koji će se prikazati."


############################# Code samples ############################
code_samples:
  enable: true
  title: "GroupDocs.Viewer uzorci koda"
  description: "Neki slučajevi upotrebe tipičnih GroupDocs.Viewer operacija u C#, Javi, TypeScriptu"
  items:
    # code sample loop
    - title: "Kako pretvoriti DOCX datoteke u PDF"
      content: |
        Pretvorite DOCX dokumente u PDF bez instaliranja programa Microsoft Word ili drugog softvera. Jednostavno učitajte i pregledajte DOCX datoteke unutar svoje .NET aplikacije, bilo da se radi o web ili desktop aplikaciji. Evo primjera kako pretvoriti DOCX datoteku u PDF: 
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Učitajte DOCX datoteku za renderiranje
            using (Viewer viewer = new Viewer("sample.docx"))
            {
              // Renderirajte DOCX u PDF datoteku
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
            // Učitajte DOCX datoteku za renderiranje
            try (Viewer viewer = new Viewer("sample.docx")) {
                // Renderirajte DOCX u PDF datoteku
                PdfViewOptions viewOptions = new PdfViewOptions();
                viewer.view(viewOptions);
            }
            ```
        - language: "TypeScript"
          color: "green"
          content: |
            ```javascript {style=abap}  
            // Učitajte DOCX datoteku za renderiranje
            const viewer = new groupdocs.viewer.Viewer("sample.docx")
            
            // Renderirajte DOCX u PDF datoteku
            const viewOptions = groupdocs.viewer.PdfViewOptions(output.pdf)
            viewer.view(viewOptions)
            ```


############################# Formats ############################
formats:
  enable: true
  title:  "Podržano je više od 180 formata datoteka"
  description: "GroupDocs.Viewer podržava rad s najpopularnijim [formatima datoteka](https://docs.groupdocs.com/viewer/net/supported-document-formats/)" 



############################# Metrics ############################

metrics:
  enable: true
  title: "Detaljna metrika i statistički uvidi"
  description: "Uronite u detaljnu raščlambu naših ključnih brojki, pružajući sveobuhvatne metrike i statističke uvide u naša postignuća, utjecaj i rast."

  items:
    # metrics loop
    - number: "180+"
      title: "Podržani formati"
      content: "Jednostavno pregledajte više od 180 formata datoteka uključujući dokumente, slike i CAD crteže bez ikakvih problema. Razbijte prepreke kompatibilnosti i pristupajte različitim datotekama bez napora s našim sveobuhvatnim rješenjem za gledanje."

    # metrics loop
    - number: "1.0M"
      title: "NuGet preuzimanja"
      content: "Naše NuGet paket rješenje postalo je pouzdan i široko prihvaćen resurs u zajednici programera, pružajući besprijekornu integraciju i vrijednu funkcionalnost za bezbrojne projekte."

    # metrics loop
    - number: "10+"
      title: "Knjižnice"
      content: "Naš proizvod uključuje 10+ biblioteka koje nude napredne značajke za optimizaciju performansi. Ove su biblioteke dizajnirane da ispune različite razvojne potrebe s neusporedivim mogućnostima."
    
    # metrics loop
    - number: "100+"
      title: "Zadovoljni kupci"
      content: "Poslužuje najpoznatije robne marke širom svijeta. Otkrijte zašto stotine vole GroupDocs.Viewer! Istražite besprijekornu navigaciju, praktičnu suradnju i neusporedivu jednostavnost korištenja. Pridružite se sada!"



############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "Naši zadovoljni kupci"
  description: "GroupDocs biblioteke koriste globalno poznati i ugledni brendovi diljem svijeta."

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
  title: "Jeste li spremni za početak?"
  description: "Isprobajte značajke GroupDocs.Viewer besplatno ili zatražite licencu"
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
  title:  "Uobičajena pitanja i nedoumice"
  description:  "Pronađite odgovore na uobičajena pitanja u našem odjeljku s često postavljanim pitanjima kako biste brzo odgovorili na svoja pitanja i nedoumice."
  items:
    #  loop
    - question: "Mogu li procijeniti GroupDocs proizvode prije kupnje?"
      answer: |
        Da! Svi GroupDocs proizvodi imaju dostupnu probnu verziju bez rizika. Snažno potičemo programere da preuzmu i isprobaju naše API-je prije kupnje kako bismo bili sigurni da će 100% ispuniti vaše potrebe.
    #  loop
    - question: "Radi li GroupDocs demonstracije proizvoda?"
      answer: |
        Ne, naš fokus je na našim API-jima i stvaranju najfunkcionalnijih i najstabilnijih mogućih proizvoda. Nudimo potpuno funkcionalne i besplatne probne verzije u obliku [privremene licence](https://purchase.groupdocs.com/temporary-license/) tako da možete sami isprobati proizvod.    
    #  loop
    - question: "Gdje mogu preuzeti proizvod?"
      answer: |
        Svi proizvodi dostupni su za preuzimanje s [web stranice](https://releases.groupdocs.com). Ne šaljemo fizičke kopije našeg softvera poštom.
    #  loop
    - question: "Jesu li licence za razvojne programere GroupDocs po korisniku ili po imenovanom korisniku?"
      answer: |
        GroupDocs Developer licence su po korisniku, a ne po imenovanom korisniku. Razumijemo da se članovi tima za kodiranje mogu promijeniti tijekom vremena i da nije praktično ažurirati licenciranje svaki put kad se to dogodi.
    #  loop
    - question: "Trebamo li licenciranje samo za aktivne programere? Na primjer, imamo tim od dva programera koji rade u smjeni A i drugi tim od dva programera koji rade u smjeni B … u ovoj situaciji, trebaju li nam dvije ili četiri licence?"
      answer: |
        Svi programeri koji rade na projektu moraju biti licencirani. U ovoj situaciji GroupDocs vidi vaš tim kao da ima četiri člana (iako rade u različito vrijeme). 


############################# Cloud ############################

cloud_links:
  enable: true
  title: "API-ji s niskim kodom GroupDocs.Viewer"
  description: "Ubrzajte pregledavanje dokumenata ili slika u bilo kojoj vrsti aplikacije s našim REST API-jem temeljenim na oblaku"

  items:
    #  loop
    - icon: "groupdocs_viewer-for-curl"
      title: "GroupDocs.Viewer Cloud for cURL"
      link: "https://products.groupdocs.cloud/viewer/curl"
      content: "Upotrijebite API za preglednik dokumenata cURL RESTful kako biste učinkovito prikazali i prikazali Microsoft Office, PDF i razne druge standardne formate datoteka u svojim aplikacijama."

    #  loop
    - icon: "groupdocs_viewer-for-net"
      title: "GroupDocs.Viewer Cloud for .NET"
      link: "https://products.groupdocs.cloud/viewer/net"
      content: "Poboljšajte mogućnosti gledanja dokumenata u .NET aplikacijama uz Cloud SDK za .NET. Neometano pregledavajte dokumente u HTML, PDF ili slikovnim formatima."

    #  loop
    - icon: "groupdocs_viewer-for-java"
      title: "GroupDocs.Viewer Cloud for Java"
      link: "https://products.groupdocs.cloud/viewer/java"
      content: "Integrirajte napredne mogućnosti iscrtavanja dokumenata u svoje Java aplikacije koristeći namjenski izrađen SDK preglednika dokumenata za Javu."
    

############################# Apps ############################

app_links:
  enable: true
  title: "GroupDocs.Viewer NoCode aplikacije"
  description: "Mrežna aplikacija koja vam omogućuje pregled više od 180 popularnih formata datoteka u pregledniku"

  items:
    #  loop
    - icon: "groupdocs_viewer-app"
      title: "GroupDocs.Viewer Total"
      link: "https://products.groupdocs.app/viewer/total"
      content: "Istražite besplatnu online aplikaciju za pregled preko 180 formata datoteka izravno iz vašeg željenog web preglednika."

    #  loop
    - icon: "groupdocs_words-app"
      title:  "GroupDocs.Viewer DOCX"
      link: "https://products.groupdocs.app/viewer/docx"
      content: "Web-bazirani alat za pregledavanje Microsoft Word datoteka bez napora na različitim uređajima."

    #  loop
    - icon: "groupdocs_pdf-app"
      title:  "GroupDocs.Viewer PDF"
      link: "https://products.groupdocs.app/viewer/pdf"
      content: "Otvorite i pregledajte PDF datoteke na mreži s besplatnim PDF preglednikom."
    



---