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
head_title: "Java Document Viewer API, PDF Word Excel გამოსახულების HTML დიაგრამა"
head_description: "Document Viewer ბიბლიოთეკა Java აპლიკაციების გასავითარებლად, რომლებიც ბუნებრივად ასახავს, ​​ნახულობს და მანიპულირებს მრავალფორმატიანი დოკუმენტებით, რომლებიც მხარს უჭერენ 180+ ფაილის ფორმატს."

############################# Header ############################
title: "დოკუმენტების რენდერი და ჩვენება<br>Java API-ის გამოყენებით"
description: "მძლავრი Viewer API 180+ დოკუმენტის ფორმატის გადასაყვანად PDF, HTML და გამოსახულება მრავალმხრივი კონფიგურაციის ვარიანტებით."
words:
  for: "for"

actions:
  main: "უფასო Maven ჩამოტვირთვა"
  main_link: "https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-viewer/"
  alt: "ლიცენზირება"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/java"
  title: "მზად ხართ დასაწყებად?"
  description: "სცადეთ GroupDocs.Viewer ფუნქციები უფასოდ ან მოითხოვეთ ლიცენზია"

release:
  title: "ვერსია {0} გამოვიდა"
  notes: "ნახეთ რა არის ახალი"
  downloads: "ჩამოტვირთვები"
  link: "https://releases.groupdocs.com/viewer/java/release-notes/latest/"

code:
  title: "PDF ფაილების რენდერი Java-ში"
  more: "მეტი მაგალითები"
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
        // დააყენეთ გამომავალი HTML პარამეტრები  
        HtmlViewOptions viewOptions = 
        HtmlViewOptions.forEmbeddedResources();

        // PDF-ის გადატანა HTML-ში ჩაშენებული რესურსებით
        viewer.view(viewOptions);
    }
    ```
############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Viewer ერთი შეხედვით"
  description: "API Java აპლიკაციებში დოკუმენტების, სლაიდების, დიაგრამების და მრავალი სხვა ტიპის დოკუმენტის რენდერაციის, ჩვენების, კონვერტაციისთვის"
  features:
    # feature loop
    - title: "იხილეთ დოკუმენტები ეფექტურად და საიმედოდ"
      content: "GroupDocs.Viewer API-ით შეგიძლიათ ეფექტურად გადაიტანოთ ნებისმიერი მხარდაჭერილი ფორმატის დოკუმენტები HTML, JPEG, PNG და PDF-ზე მოქნილი და მძლავრი ვარიანტებით, კონტენტისა და დოკუმენტის სტრუქტურის მთლიანობის შენარჩუნებით. GroupDocs.Viewer მუშაობს Windows და Linux პლატფორმებზე."

    # feature loop
    - title: "ფაილებისა და დოკუმენტების ყველაზე პოპულარული ფორმატები მხარდაჭერილია"
      content: "ჩვენ მხარს ვუჭერთ 180-ზე მეტ პოპულარულ ფაილის და დოკუმენტის ფორმატს, რომლებიც მოიცავს Word, Excel, PDF, PowerPoint, OpenDocument ფორმატების ოჯახს, არქივებს, რასტერულ და ვექტორულ სურათებს, ელ-წიგნებს, პროგრამირების ენებს და მარკირებას, და მრავალი სხვა ფაილის ტიპს, მათ შორის დაშიფრულს. ფაილები პაროლით დაცვით."

    # feature loop
    - title: "დააკონფიგურიროთ გამომავალი"
      content: "GroupDocs.Viewer საშუალებას იძლევა არა მხოლოდ გადაიტანოს დოკუმენტი, არამედ გააკონტროლოს როგორ ზუსტად, დოკუმენტის რომელი ნაწილები უნდა იყოს რენდერი ან ახლა, როგორ უნდა მოხდეს მათი რენდერი და გამოიყენოს სხვადასხვა ტრანსფორმაციები გამოტანილ გამოსავალზე."

    # feature loop
    - title: "ვებ UI გაზაფხულის ჩარჩოსთვის"
      content: "ჩვენ გთავაზობთ ღია კოდის UI პაკეტს Spring Framework-ისთვის, რომელიც შეიძლება დაემატოს თქვენს პროექტს რამდენიმე წუთში. Viewer.UI პაკეტი შეიცავს Angular-ზე დაფუძნებულ web-UI-ს და აწვდის სასარგებლო API-ებისა და მონაცემთა შენახვის პროვაიდერებს."

############################# Platforms ############################
platforms:
  enable: true
  title: "პლატფორმის დამოუკიდებლობა"
  description: "GroupDocs.Viewer Java-სთვის მხარს უჭერს შემდეგ ოპერაციულ სისტემებს, ჩარჩოებსა და პაკეტის მენეჯერებს"
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
  title: "მხარდაჭერილი ფაილის ფორმატები"
  description: |
    GroupDocs.Viewer Java-სთვის მხარს უჭერს ოპერაციებს შემდეგი [ფაილის ფორმატები](https://docs.groupdocs.com/viewer/java/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office, OpenDocument და ტექსტის ფორმატები
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
        ### სურათები, გრაფიკა და დიაგრამები
        * **რასტერული სურათები:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
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
        ### სხვა        
        * **ვებ:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **არქივები:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **სხვა:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "GroupDocs.Viewer ფუნქციები"
  description: "PDF და საოფისე დოკუმენტების შეუფერხებლად რენდერი, ჩვენება და კონვერტაცია"

  items:
    # feature loop
    - icon: "viewhtml"
      title: "იხილეთ დოკუმენტები HTML-ში"
      content: "ნებისმიერი ტიპის დოკუმენტის გადაქცევა HTML დოკუმენტად CSS და SVG-ით, რომელიც შეიძლება იყოს ნაჩვენები ნებისმიერ თანამედროვე ვებ-ბრაუზერში."

    # feature loop
    - icon: "rasterize"
      title: "დოკუმენტების რასტერიზაცია"
      content: "ნებისმიერი მხარდაჭერილი დოკუმენტის ფორმატის რასტერიზაცია რასტრულ სურათზე, გამოსახულების რეგულირებადი ფორმატითა და შეკუმშვის ხარისხით."

    # feature loop
    - icon: "sourcecode"
      title: "პროგრამირების კოდების რენდერი და მონიშვნა"
      content: "ყველა პოპულარული პროგრამირების, სკრიპტის და მარკირების ენების მხარდაჭერა, მათი სინტაქსის გაანალიზებისა და ხაზგასმის შესაძლებლობით."

    # feature loop
    - icon: "convertpdf"
      title: "გადაიყვანეთ PDF-ზე"
      content: "ნებისმიერი მხარდაჭერილი ფორმატის დოკუმენტი შეიძლება ადვილად გარდაიქმნას და შეინახოს PDF-ში რეგულირებადი ვარიანტებით."

    # feature loop
    - icon: "transform"
      title: "გამოიყენეთ ტრანსფორმაციები"
      content: "გამომავალი დოკუმენტი შეიძლება გარდაიქმნას რენდერის დროს - გვერდები შეიძლება შემოტრიალდეს და/ან გადააწყდეს და ტექსტის ჭვირნიშანი განთავსდეს მათ თავზე."

    # feature loop
    - icon: "adjustment"
      title: "HTML გამომავალი კორექტირება"
      content: "გამომავალი HTML დოკუმენტები, გენერირებული GroupDocs.Viewer-ის მიერ, შეიძლება ძალიან წვრილად დააკონფიგურიროთ: ნებადართულია შენახვა ნაკადში ან ფაილში, გარე ან ჩაშენებული რესურსებით, გამოძახებით და ა.შ."

    # feature loop
    - icon: "complex"
      title: "რთული დოკუმენტური სტრუქტურების მხარდაჭერა"
      content: "GroupDocs.Viewer მხარს უჭერს არა მხოლოდ ცალკეულ დოკუმენტებს, არამედ ფაილებს, რომლებიც შეიცავს დოკუმენტების სიას ან იერარქიულ სტრუქტურას, როგორიცაა ელ. ფოსტის შეტყობინებები დანართებით, ZIP არქივები შიდა ფაილებით საქაღალდეებში, მრავალგვერდიანი TIFF სურათები და ა.შ."

    # feature loop
    - icon: "optimization"
      title: "ოპტიმიზაციის პარამეტრები"
      content: "GroupDocs.Viewer შეიცავს რეგულირებადი ქეშის ქვესისტემას, რომელსაც შეუძლია დააჩქაროს ჩატვირთვის დრო დოკუმენტების ქეშირებული ვერსიების გამოყენებით. ასევე სხვადასხვა ფორმატის სხვადასხვა ვარიანტების ნაკრები საშუალებას გაძლევთ გამორიცხოთ დოკუმენტების ზოგიერთი არასაჭირო ნაწილი ან ასპექტი რენდერიდან (შრიფტები, დამალული სამუშაო ფურცლები, ელფოსტის დანართები) საერთო შესრულების ოპტიმიზაციისთვის."

    # feature loop
    - icon: "passwordprotected"
      title: "პაროლით დაცული დოკუმენტების მხარდაჭერა"
      content: "GroupDocs.Viewer საშუალებას გაძლევთ გახსნათ სხვადასხვა ტიპის დაშიფრული დოკუმენტები: PDF, WordProcessing, Spreadsheet, Presentation და სხვა, პაროლის მითითებით ჩატვირთვის ვარიანტებში."

############################# Code samples ############################
code_samples:
  enable: true
  title: "კოდის ნიმუშები"
  description: "ზოგიერთი იყენებს ტიპიური GroupDocs.Viewer-ს Java ოპერაციებისთვის"
  items:
    # code sample loop
    - title: "DOCX-ის გადაცემა HTML-ში"
      content: |
        [HtmlViewOptions](https://reference.groupdocs.com/viewer/java/com.groupdocs.viewer.options/htmlviewoptions/) კლასის თვისებები საშუალებას გაძლევთ აკონტროლოთ კონვერტაციის პროცესი, მეტი ამის შესახებ [აქ](https://docs.groupdocs.com/viewer/java/rendering-to-html/). მაგალითად, თქვენ შეგიძლიათ ჩართოთ ყველა გარე რესურსი გამომავალ HTML ფაილში, შეამციროთ გამომავალი ფაილი და ოპტიმიზაცია მოახდინოთ დასაბეჭდად.
        {{< landing/code title="Java">}}
        ```java {style=abap}
        import com.groupdocs.viewer.Viewer;
        import com.groupdocs.viewer.options.HtmlViewOptions;

        // Instantiate Viewer
        try (Viewer viewer = new Viewer("resume.docx"))
        {
            // გამომავალი HTML პარამეტრების დაყენება
            HtmlViewOptions options = 
            HtmlViewOptions.forEmbeddedResources();

            // DOCX-ის გადაცემა HTML-ში ჩაშენებული რესურსებით
            viewer.view(options);
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "ექსპორტი PPTX PDF-ში"
      content: |
        შექმენით [PdfViewOptions](https://reference.groupdocs.com/viewer/java/com.groupdocs.viewer.options/pdfviewoptions/) კლასის ინსტანცია და გადაეცით [Viewer.View](https://reference.groupdocs.com/viewer/java/com.groupdocs.viewer/viewer/#view-com.groupdocs.viewer.options.ViewOptions-) მეთოდი PowerPoint PPTX ფაილის PDF-ში გადასაყვანად. PdfViewOptions კლასის თვისებები საშუალებას გაძლევთ აკონტროლოთ კონვერტაციის პროცესი. მაგალითად, შეგიძლიათ დაიცვათ გამომავალი PDF ფაილი, გადააკეთოთ მისი გვერდები და მიუთითოთ დოკუმენტის სურათების ხარისხი. იხილეთ [დოკუმენტაციის შემდეგი განყოფილება](https://docs.groupdocs.com/viewer/java/rendering-to-pdf/) დეტალებისთვის.
        {{< landing/code title="Java">}}
        ```java {style=abap}   
        import com.groupdocs.viewer.Viewer;
        import com.groupdocs.viewer.options.PdfViewOptions;

        // Instantiate Viewer
        try (Viewer viewer = new Viewer("presentation.pptx"))
        {            
            // დააყენეთ გამომავალი PDF პარამეტრები
            PdfViewOptions viewOptions = new PdfViewOptions();

            // ექსპორტი PPTX PDF-ში
            viewer.view(viewOptions);
        }
        ```
        {{< /landing/code >}}
############################# Reviews ############################
# reviews:
# enable: true
# title: "GroupDocs პროდუქტების მიმოხილვები"
# description: "უბრალოდ ნუ მიიღებ ჩვენს სიტყვას. ნახეთ, რას ამბობენ სხვა დეველოპერები ჩვენს API-ებზე"

# items:
#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "შესანიშნავი მომსახურება და შესანიშნავი პროდუქტები. ისინი ძალიან სასარგებლო და პასუხისმგებელნი იყვნენ GroupDocs.Viewer .NET-ის განხორციელების პროცესის დროს, ვერ გირჩევთ მათ საკმარისად დიდ რეკომენდაციას."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "პროექტში .NET-ისთვის GroupDocs.Viewer-ის დანერგვისა და გამოყენების შემდეგ, როგორც ჩანს, ის ძალიან კარგად მუშაობს. ბევრი საბუთით მაქვს ტესტირება და ჯერჯერობით კარგია. ყველაფერი, რაც მე გადავყარე, ლამაზად არის გადმოცემული და გამოიყურება ისეთივე კარგად, როგორც PDF მაყურებელში ან MS Word-ში."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---