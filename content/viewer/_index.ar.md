---
############################# Static ############################
layout: "family"
date: 2023-12-20T06:39:57
draft: false

product: "Viewer"
product_tag: "viewer"

############################# Head ############################
head_title: "عرض وعرض المستندات API | On Premise API والخدمة عبر الإنترنت"
head_description: "عرض وعرض ملفات Word أو PDF أو Excel أو Powerpoint أو الصور بسهولة ومجانية"

############################# Header ############################
title: "عرض المستندات وعرضها بسهولة"
description: |
  واجهة برمجة تطبيقات عارض قوية لعرض ملفات مختلفة إلى PDF وHTML وصورة.

  قم بتحميل المستندات من مصادر مختلفة، بما في ذلك الملفات والتدفقات وعناوين URL وخوادم FTP وAmazon S3 وAzure Blob Storage والمزيد.

  قم بإنشاء صفحات HTML سريعة الاستجابة، وحماية ملفات PDF الناتجة وإعادة ترتيب صفحاتها، وتدوير الصفحات، وتقديم الملاحظات والتعليقات إذا لزم الأمر.
  

############################# Platforms ############################
supported_platforms:
  enable: true  
  head_title: "اختر النظام الأساسي الخاص بك"
  title: "المنصات المدعومة"
  description: "تدعم مكتبة GroupDocs.Viewer أنظمة التشغيل وأطر العمل التالية"
  details_link_title: "يتعلم أكثر"
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
  title: "مجموعة ميزات GroupDocs.Viewer"
  description: "واجهة برمجة التطبيقات (API) لعرض ملفات من أنواع مختلفة مثل HTML وPDF وPNG وJPEG في التطبيقات لعرضها بدون برامج خارجية."

  items:
    # feature loop
    - icon: "view"
      title: "عرض المستندات والصور"
      content: "عرض المستندات من خلال تقديمها كملفات HTML وPDF وPNG وJPEG."
    # feature loop
    - icon: "password"
      title: "فتح المستندات المضمونة"
      content: "حدد كلمة مرور لفتح المستندات المشفرة."

    # feature loop
    - icon: "load"
      title: "تحميل الملفات من أي مكان"
      content: "قم بتحميل المستندات من ملفات مختلفة وعناوين URL وخوادم FTP وAmazon S3 والمزيد."
    
    # feature loop
    - icon: "pages"
      title: "عرض كل الصفحات أو صفحات محددة"
      content: "حدد نطاقًا من أرقام الصفحات التي سيتم عرضها."


############################# Code samples ############################
code_samples:
  enable: true
  title: "نماذج التعليمات البرمجية لـ GroupDocs.Viewer"
  description: "تستخدم بعض حالات عمليات GroupDocs.Viewer النموذجية في C#، وJava، وTypeScript"
  items:
    # code sample loop
    - title: "كيفية تحويل ملفات DOCX إلى PDF"
      content: |
        قم بتحويل مستندات DOCX إلى PDF بدون تثبيت Microsoft Word أو أي برامج أخرى. قم بتحميل ملفات DOCX وعرضها بسهولة داخل تطبيق .NET الخاص بك، سواء كان تطبيق ويب أو تطبيق سطح مكتب. فيما يلي مثال لكيفية تحويل ملف DOCX إلى PDF: 
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // قم بتحميل ملف DOCX لعرضه
            using (Viewer viewer = new Viewer("sample.docx"))
            {
              // تقديم DOCX إلى ملف PDF
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
            // قم بتحميل ملف DOCX لعرضه
            try (Viewer viewer = new Viewer("sample.docx")) {
                // تقديم DOCX إلى ملف PDF
                PdfViewOptions viewOptions = new PdfViewOptions();
                viewer.view(viewOptions);
            }
            ```
        - language: "TypeScript"
          color: "green"
          content: |
            ```javascript {style=abap}  
            // قم بتحميل ملف DOCX لعرضه
            const viewer = new groupdocs.viewer.Viewer("sample.docx")
            
            // تقديم DOCX إلى ملف PDF
            const viewOptions = groupdocs.viewer.PdfViewOptions(output.pdf)
            viewer.view(viewOptions)
            ```


############################# Formats ############################
formats:
  enable: true
  title:  "يدعم أكثر من 180 تنسيقًا للملفات"
  description: "يدعم GroupDocs.Viewer ا[تنسيقات الملفات] الأكثر شيوعًا(https://docs.groupdocs.com/viewer/net/supported-document-formats/)" 



############################# Metrics ############################

metrics:
  enable: true
  title: "مقاييس متعمقة ورؤى إحصائية"
  description: "تعمق في التحليل التفصيلي لأرقامنا الرئيسية، مع توفير مقاييس شاملة ورؤى إحصائية حول إنجازاتنا وتأثيرنا ونمونا."

  items:
    # metrics loop
    - number: "180+"
      title: "التنسيقات المدعومة"
      content: "يمكنك عرض أكثر من 180 تنسيق ملف بسهولة، بما في ذلك المستندات والصور ورسومات CAD دون أي متاعب. اكسر حواجز التوافق وقم بالوصول إلى الملفات المتنوعة بسهولة من خلال حل العرض الشامل الخاص بنا."

    # metrics loop
    - number: "1.0M"
      title: "تنزيلات نوجيت"
      content: "لقد أصبح حل حزمة NuGet الخاص بنا مصدرًا موثوقًا به ومعتمدًا على نطاق واسع في مجتمع المطورين، مما يوفر تكاملًا سلسًا ووظائف قيمة لعدد لا يحصى من المشاريع."

    # metrics loop
    - number: "10+"
      title: "المكتبات"
      content: "يشتمل منتجنا على أكثر من 10 مكتبات تقدم ميزات متقدمة لتحسين الأداء. تم تصميم هذه المكتبات لتلبية احتياجات التطوير المختلفة بقدرات لا مثيل لها."
    
    # metrics loop
    - number: "100+"
      title: "الزبائن سعداء"
      content: "خدمة العلامات التجارية الأكثر شهرة في جميع أنحاء العالم. اكتشف سبب حب المئات لـ GroupDocs.Viewer! استكشف التنقل السلس والتعاون المريح وسهولة الاستخدام التي لا مثيل لها. نضم الان!"



############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "عملائنا السعداء"
  description: "يتم استخدام مكتبات GroupDocs بواسطة علامات تجارية مشهورة ومتميزة عالميًا في جميع أنحاء العالم."

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
  title: "على استعداد للبدء؟"
  description: "جرب ميزات GroupDocs.Viewer مجانًا أو اطلب ترخيصًا"
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
  title:  "الأسئلة والمخاوف الشائعة"
  description:  "يمكنك العثور على إجابات للاستفسارات الشائعة في قسم الأسئلة الشائعة لمعالجة استفساراتك ومخاوفك بسرعة."
  items:
    #  loop
    - question: "هل يمكنني تقييم منتجات GroupDocs قبل الشراء؟"
      answer: |
        نعم! تتمتع جميع منتجات GroupDocs بإصدار تقييمي خالٍ من المخاطر. نحن نشجع المطورين بشدة على تنزيل واجهات برمجة التطبيقات الخاصة بنا وتجربتها قبل الشراء للتأكد من أنها ستلبي احتياجاتك بنسبة 100%.
    #  loop
    - question: "هل تقوم GroupDocs بإجراء عروض توضيحية للمنتج؟"
      answer: |
        لا، ينصب تركيزنا على واجهات برمجة التطبيقات (APIs) الخاصة بنا وجعل المنتجات الأكثر وظيفية واستقرارًا ممكنة. نحن نقدم تجارب مجانية تعمل بكامل طاقتها في شكل [ترخيص مؤقت](https://purchase.groupdocs.com/temporary-license/) حتى تتمكن من اختبار المنتج بنفسك.    
    #  loop
    - question: "أين يمكنني تنزيل المنتج؟"
      answer: |
        جميع المنتجات متاحة للتنزيل من [موقع الويب](https://releases.groupdocs.com). نحن لا نرسل نسخًا مادية من برامجنا عبر البريد.
    #  loop
    - question: "هل تراخيص مطور GroupDocs لكل مستخدم أم لكل مستخدم محدد؟"
      answer: |
        تراخيص مطور GroupDocs مخصصة لكل مستخدم، وليس لكل مستخدم مسمى. نحن ندرك أن أعضاء فريق البرمجة قد يتغيرون بمرور الوقت وأنه ليس من العملي أن نضطر إلى تحديث الترخيص في كل مرة يحدث ذلك.
    #  loop
    - question: "هل نحتاج إلى ترخيص للمطورين النشطين فقط؟ على سبيل المثال، لدينا فريق من مطورين اثنين يعملان على المناوبة أ وفريق ثانٍ من مطورين اثنين يعملان على المناوبة ب... في هذه الحالة، هل نحتاج إلى ترخيصين أو أربعة تراخيص؟"
      answer: |
        يجب أن يكون جميع المطورين الذين يعملون في المشروع مرخصين. في هذه الحالة، يرى GroupDocs أن فريقك يضم أربعة أعضاء (على الرغم من أنهم يعملون في أوقات مختلفة). 


############################# Cloud ############################

cloud_links:
  enable: true
  title: "GroupDocs.Viewer واجهات برمجة التطبيقات ذات التعليمات البرمجية المنخفضة"
  description: "قم بتسريع عرض المستندات أو الصور في أي نوع من التطبيقات باستخدام REST API المستند إلى السحابة"

  items:
    #  loop
    - icon: "groupdocs_viewer-for-curl"
      title: "GroupDocs.Viewer Cloud for cURL"
      link: "https://products.groupdocs.cloud/viewer/curl"
      content: "استخدم واجهة برمجة تطبيقات عارض المستندات cURL RESTful لعرض وعرض Microsoft Office وPDF والعديد من تنسيقات الملفات القياسية الأخرى بكفاءة في تطبيقاتك."

    #  loop
    - icon: "groupdocs_viewer-for-net"
      title: "GroupDocs.Viewer Cloud for .NET"
      link: "https://products.groupdocs.cloud/viewer/net"
      content: "قم بتحسين إمكانيات عرض المستندات في تطبيقات .NET باستخدام Cloud SDK لـ .NET. عرض المستندات بسلاسة بتنسيقات HTML أو PDF أو الصور."

    #  loop
    - icon: "groupdocs_viewer-for-java"
      title: "GroupDocs.Viewer Cloud for Java"
      link: "https://products.groupdocs.cloud/viewer/java"
      content: "قم بدمج إمكانات عرض المستندات المتقدمة في تطبيقات Java الخاصة بك باستخدام Document Viewer SDK المصمم خصيصًا لهذا الغرض لـ Java."
    

############################# Apps ############################

app_links:
  enable: true
  title: "تطبيقات GroupDocs.Viewer NoCode"
  description: "تطبيق عبر الإنترنت يتيح لك عرض أكثر من 180 تنسيقًا شائعًا للملفات في المتصفح"

  items:
    #  loop
    - icon: "groupdocs_viewer-app"
      title: "GroupDocs.Viewer Total"
      link: "https://products.groupdocs.app/viewer/total"
      content: "استكشف تطبيقًا مجانيًا عبر الإنترنت لعرض أكثر من 180 تنسيقًا للملفات مباشرة من متصفح الويب المفضل لديك."

    #  loop
    - icon: "groupdocs_words-app"
      title:  "GroupDocs.Viewer DOCX"
      link: "https://products.groupdocs.app/viewer/docx"
      content: "أداة قائمة على الويب لعرض ملفات Microsoft Word بسهولة عبر الأجهزة المختلفة."

    #  loop
    - icon: "groupdocs_pdf-app"
      title:  "GroupDocs.Viewer PDF"
      link: "https://products.groupdocs.app/viewer/pdf"
      content: "افتح واعرض ملفات PDF عبر الإنترنت باستخدام عارض PDF المجاني."
    



---