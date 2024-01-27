---
############################# Static ############################
layout: "family"
date: 2023-12-20T06:39:57
draft: false

product: "Viewer"
product_tag: "viewer"

############################# Head ############################
head_title: "Render and View Documents API | Premise API-ზე და ონლაინ სერვისზე"
head_description: "Word, PDF, Excel, Powerpoint ან Image ფაილების გადაცემა და ნახვა მარტივად და უფასოდ"

############################# Header ############################
title: "დოკუმენტების გაფორმება და ნახვა მარტივად"
description: |
  მძლავრი Viewer API სხვადასხვა ფაილების PDF, HTML და Image გადასაცემად.

  ჩატვირთეთ დოკუმენტები სხვადასხვა წყაროდან, მათ შორის ფაილები, ნაკადები, URL, FTP სერვერები, Amazon S3, Azure Blob Storage და სხვა.

  შექმენით პასუხისმგებელი HTML გვერდები, დაიცავით გამომავალი PDF ფაილები და დაალაგეთ მათი გვერდები, დაატრიალეთ გვერდები, საჭიროების შემთხვევაში ჩანაწერები და კომენტარები.
  

############################# Platforms ############################
supported_platforms:
  enable: true  
  head_title: "აირჩიეთ თქვენი პლატფორმა"
  title: "მხარდაჭერილი პლატფორმები"
  description: "GroupDocs.Viewer ბიბლიოთეკა მხარს უჭერს შემდეგ ოპერაციულ სისტემებსა და ჩარჩოებს"
  details_link_title: "Გაიგე მეტი"
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
  title: "GroupDocs.Viewer-ის ფუნქციების ნაკრები"
  description: "API სხვადასხვა ტიპის ფაილების HTML, PDF, PNG და JPEG გადასაცემად აპლიკაციებში, რომ ნახოთ ისინი მესამე მხარის პროგრამული უზრუნველყოფის გარეშე."

  items:
    # feature loop
    - icon: "view"
      title: "იხილეთ დოკუმენტები და სურათები"
      content: "იხილეთ დოკუმენტები HTML, PDF, PNG და JPEG ფაილებად გადაცემით."
    # feature loop
    - icon: "password"
      title: "გახსენით დაცული დოკუმენტები"
      content: "მიუთითეთ პაროლი დაშიფრული დოკუმენტების გასახსნელად."

    # feature loop
    - icon: "load"
      title: "ჩატვირთეთ ფაილები ნებისმიერი ადგილიდან"
      content: "ჩატვირთეთ დოკუმენტები სხვადასხვა ფაილებიდან, URL-ებიდან, FTP სერვერებიდან, Amazon S3 და სხვა."
    
    # feature loop
    - icon: "pages"
      title: "ყველა ან კონკრეტული გვერდის რენდერი"
      content: "მიუთითეთ შესასრულებელი გვერდის ნომრების დიაპაზონი."


############################# Code samples ############################
code_samples:
  enable: true
  title: "GroupDocs.Viewer კოდის ნიმუშები"
  description: "ზოგიერთი იყენებს ტიპიური GroupDocs.Viewer ოპერაციების შემთხვევებს C#, Java, TypeScript-ში"
  items:
    # code sample loop
    - title: "როგორ გადავიტანოთ DOCX ფაილები PDF-ში"
      content: |
        გადაიტანეთ DOCX დოკუმენტები PDF-ზე Microsoft Word-ის ან სხვა პროგრამული უზრუნველყოფის დაყენების გარეშე. მარტივად ჩატვირთეთ და ნახეთ DOCX ფაილები თქვენს .NET აპლიკაციაში, იქნება ეს ვებ თუ დესკტოპის აპლიკაცია. აქ არის მაგალითი იმისა, თუ როგორ უნდა გადაიტანოთ DOCX ფაილი PDF-ზე: 
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // ჩატვირთეთ DOCX ფაილი რენდერისთვის
            using (Viewer viewer = new Viewer("sample.docx"))
            {
              // გადაიტანეთ DOCX PDF ფაილში
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
            // ჩატვირთეთ DOCX ფაილი რენდერისთვის
            try (Viewer viewer = new Viewer("sample.docx")) {
                // გადაიტანეთ DOCX PDF ფაილში
                PdfViewOptions viewOptions = new PdfViewOptions();
                viewer.view(viewOptions);
            }
            ```
        - language: "TypeScript"
          color: "green"
          content: |
            ```javascript {style=abap}  
            // ჩატვირთეთ DOCX ფაილი რენდერისთვის
            const viewer = new groupdocs.viewer.Viewer("sample.docx")
            
            // გადაიტანეთ DOCX PDF ფაილში
            const viewOptions = groupdocs.viewer.PdfViewOptions(output.pdf)
            viewer.view(viewOptions)
            ```


############################# Formats ############################
formats:
  enable: true
  title:  "180+ ფაილის ფორმატის მხარდაჭერა"
  description: "GroupDocs.Viewer მხარს უჭერს ოპერაციებს ყველაზე პოპულარული [ფაილის ფორმატები](https://docs.groupdocs.com/viewer/net/supported-document-formats/)" 



############################# Metrics ############################

metrics:
  enable: true
  title: "სიღრმისეული მეტრიკა და სტატისტიკური შეხედულებები"
  description: "გაეცანით ჩვენი საკვანძო ფიგურების დეტალურ აღწერას, მოგვაწოდეთ ყოვლისმომცველი მეტრიკა და სტატისტიკური ინფორმაცია ჩვენი მიღწევების, გავლენისა და ზრდის შესახებ."

  items:
    # metrics loop
    - number: "180+"
      title: "მხარდაჭერილი ფორმატები"
      content: "მარტივად ნახეთ 180-ზე მეტი ფაილის ფორმატი, მათ შორის დოკუმენტები, სურათები და CAD ნახატები უპრობლემოდ. დაარღვიე თავსებადობის ბარიერები და წვდომა მრავალფეროვან ფაილებზე ძალისხმევის გარეშე ჩვენი ყოვლისმომცველი სანახავი გადაწყვეტით."

    # metrics loop
    - number: "1.0M"
      title: "NuGet ჩამოტვირთვები"
      content: "ჩვენი NuGet პაკეტის გადაწყვეტა გახდა სანდო და ფართოდ მიღებული რესურსი დეველოპერთა საზოგადოებაში, რომელიც უზრუნველყოფს შეუფერხებელ ინტეგრაციას და ღირებულ ფუნქციონირებას უამრავი პროექტისთვის."

    # metrics loop
    - number: "10+"
      title: "ბიბლიოთეკები"
      content: "ჩვენი პროდუქტი მოიცავს 10+ ბიბლიოთეკას, რომელიც გთავაზობთ გაფართოებულ ფუნქციებს მუშაობის ოპტიმიზაციისთვის. ეს ბიბლიოთეკები შექმნილია განვითარების სხვადასხვა საჭიროებების შესასრულებლად შეუდარებელი შესაძლებლობებით."
    
    # metrics loop
    - number: "100+"
      title: "ბედნიერი მომხმარებლები"
      content: "ემსახურება ყველაზე საკულტო ბრენდებს მთელს მსოფლიოში. აღმოაჩინეთ რატომ უყვარს ასობით GroupDocs.Viewer! გამოიკვლიეთ უწყვეტი ნავიგაცია, მოსახერხებელი თანამშრომლობა და გამოყენების შეუდარებელი სიმარტივე. Შემოგვიერთდი ეხლავე!"



############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "ჩვენი ბედნიერი მომხმარებლები"
  description: "GroupDocs-ის ბიბლიოთეკები დასაქმებულია გლობალურად ცნობილი და გამორჩეული ბრენდების მიერ მთელ მსოფლიოში."

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
  title: "მზად ხართ დასაწყებად?"
  description: "სცადეთ GroupDocs.Viewer ფუნქციები უფასოდ ან მოითხოვეთ ლიცენზია"
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
  title:  "საერთო კითხვები და შეშფოთება"
  description:  "იპოვეთ პასუხები საერთო შეკითხვებზე ჩვენს ხშირად დასმული კითხვების განყოფილებაში, რათა სწრაფად მოგვარდეს თქვენი შეკითხვები და პრობლემები."
  items:
    #  loop
    - question: "შემიძლია შევაფასო GroupDocs-ის პროდუქტები შეძენამდე?"
      answer: |
        დიახ! GroupDocs-ის ყველა პროდუქტს აქვს რისკის გარეშე, შეფასების ვერსია. ჩვენ მტკიცედ მოვუწოდებთ დეველოპერებს, ჩამოტვირთონ და სცადონ ჩვენი API-ები შეძენამდე, რათა უზრუნველყონ, რომ ისინი 100%-ით დააკმაყოფილებენ თქვენს საჭიროებებს.
    #  loop
    - question: "აკეთებს თუ არა GroupDocs პროდუქტის დემონსტრირებას?"
      answer: |
        არა, ჩვენი ყურადღება გამახვილებულია ჩვენს API-ებზე და მაქსიმალურად ფუნქციონალურ და სტაბილურ პროდუქტებზე. ჩვენ გთავაზობთ სრულად ფუნქციონალურ და უფასო საცდელებს [დროებითი ლიცენზიის](https://purchase.groupdocs.com/temporary-license/) სახით, ასე რომ თქვენ შეგიძლიათ შეამოწმოთ პროდუქტი თქვენთვის.    
    #  loop
    - question: "საიდან შემიძლია გადმოვწერო პროდუქტი?"
      answer: |
        ყველა პროდუქტის ჩამოტვირთვა შესაძლებელია [ვებგვერდიდან](https://releases.groupdocs.com). ჩვენ არ ვაგზავნით ჩვენი პროგრამული უზრუნველყოფის ფიზიკურ ასლებს ფოსტით.
    #  loop
    - question: "არის GroupDocs-ის დეველოპერის ლიცენზიები თითო მომხმარებლისთვის, თუ დასახელებული მომხმარებლისთვის?"
      answer: |
        GroupDocs დეველოპერის ლიცენზიები მოცემულია თითო მომხმარებლისთვის და არა დასახელებული მომხმარებლისთვის. ჩვენ გვესმის, რომ კოდირების ჯგუფის წევრები შეიძლება შეიცვალოს დროთა განმავლობაში და რომ არ არის პრაქტიკული ლიცენზირების განახლება ყოველ ჯერზე.
    #  loop
    - question: "გვჭირდება ლიცენზირება მხოლოდ აქტიური დეველოპერებისთვის? მაგალითად, ჩვენ გვყავს ორი დეველოპერისგან შემდგარი გუნდი, რომელიც მუშაობს A ცვლაზე და მეორე გუნდი ორი დეველოპერისგან, რომელიც მუშაობს B ცვლაზე… ამ სიტუაციაში, გვჭირდება ორი ან ოთხი ლიცენზია?"
      answer: |
        ყველა დეველოპერი, რომელიც მუშაობს პროექტზე, უნდა იყოს ლიცენზირებული. ამ სიტუაციაში, GroupDocs ხედავს თქვენს გუნდს ოთხ წევრად (მიუხედავად იმისა, რომ ისინი მუშაობენ სხვადასხვა დროს). 


############################# Cloud ############################

cloud_links:
  enable: true
  title: "GroupDocs.Viewer დაბალი კოდის API-ები"
  description: "დააჩქარეთ დოკუმენტის ან სურათის ნახვა ნებისმიერი ტიპის აპლიკაციაში ჩვენი ღრუბელზე დაფუძნებული REST API-ით"

  items:
    #  loop
    - icon: "groupdocs_viewer-for-curl"
      title: "GroupDocs.Viewer Cloud for cURL"
      link: "https://products.groupdocs.cloud/viewer/curl"
      content: "გამოიყენეთ cURL RESTful დოკუმენტების მაყურებლის API, რათა ეფექტურად წარმოაჩინოთ და წარმოაჩინოთ Microsoft Office, PDF და სხვა სტანდარტული ფაილის ფორმატები თქვენს აპლიკაციებში."

    #  loop
    - icon: "groupdocs_viewer-for-net"
      title: "GroupDocs.Viewer Cloud for .NET"
      link: "https://products.groupdocs.cloud/viewer/net"
      content: "გააუმჯობესეთ დოკუმენტების ნახვის შესაძლებლობები .NET აპლიკაციებში Cloud SDK-ით .NET-ისთვის. იხილეთ დოკუმენტები შეუფერხებლად HTML, PDF ან გამოსახულების ფორმატებში."

    #  loop
    - icon: "groupdocs_viewer-for-java"
      title: "GroupDocs.Viewer Cloud for Java"
      link: "https://products.groupdocs.cloud/viewer/java"
      content: "ჩართეთ დოკუმენტების გადაცემის გაფართოებული შესაძლებლობები თქვენს Java აპლიკაციებში Java-სთვის განკუთვნილი Document Viewer SDK-ის გამოყენებით."
    

############################# Apps ############################

app_links:
  enable: true
  title: "GroupDocs.Viewer NoCode აპები"
  description: "ონლაინ აპლიკაცია, რომელიც საშუალებას გაძლევთ ნახოთ 180+ პოპულარული ფაილის ფორმატი ბრაუზერში"

  items:
    #  loop
    - icon: "groupdocs_viewer-app"
      title: "GroupDocs.Viewer Total"
      link: "https://products.groupdocs.app/viewer/total"
      content: "გამოიკვლიეთ უფასო ონლაინ აპლიკაცია, რომ ნახოთ 180-ზე მეტი ფაილის ფორმატი პირდაპირ თქვენი სასურველი ვებ ბრაუზერიდან."

    #  loop
    - icon: "groupdocs_words-app"
      title:  "GroupDocs.Viewer DOCX"
      link: "https://products.groupdocs.app/viewer/docx"
      content: "ვებ-ზე დაფუძნებული ინსტრუმენტი Microsoft Word ფაილების უპრობლემოდ სანახავად სხვადასხვა მოწყობილობებზე."

    #  loop
    - icon: "groupdocs_pdf-app"
      title:  "GroupDocs.Viewer PDF"
      link: "https://products.groupdocs.app/viewer/pdf"
      content: "გახსენით და ნახეთ PDF ფაილები ონლაინ უფასო PDF მაყურებლის საშუალებით."
    



---