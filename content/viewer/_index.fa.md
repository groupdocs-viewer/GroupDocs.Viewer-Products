---
############################# Static ############################
layout: "family"
date: 2023-12-20T06:39:57
draft: false

product: "Viewer"
product_tag: "viewer"

############################# Head ############################
head_title: "Render and View Documents API | در Premise API و سرویس آنلاین"
head_description: "رندر و مشاهده فایل های Word، PDF، Excel، Powerpoint یا Image به راحتی و رایگان"

############################# Header ############################
title: "اسناد را به راحتی رندر و مشاهده کنید"
description: |
  API نمایشگر قدرتمند برای ارائه فایل های مختلف به PDF، HTML و Image.

  اسناد را از منابع مختلف بارگیری کنید، از جمله فایل ها، جریان ها، URL ها، سرورهای FTP، Amazon S3، Azure Blob Storage و موارد دیگر.

  صفحات HTML پاسخگو ایجاد کنید، از فایل های PDF خروجی محافظت کنید و صفحات آنها را مجددا مرتب کنید، صفحات را بچرخانید، یادداشت ها و نظرات را در صورت نیاز ارائه دهید.
  

############################# Platforms ############################
supported_platforms:
  enable: true  
  head_title: "پلتفرم خود را انتخاب کنید"
  title: "پلتفرم های پشتیبانی شده"
  description: "کتابخانه GroupDocs.Viewer از سیستم عامل ها و چارچوب های زیر پشتیبانی می کند"
  details_link_title: "بیشتر بدانید"
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
  title: "مجموعه ویژگی های GroupDocs.Viewer"
  description: "API برای ارائه فایل‌های مختلف به‌عنوان HTML، PDF، PNG و JPEG در برنامه‌ها برای مشاهده آنها بدون نرم‌افزار شخص ثالث."

  items:
    # feature loop
    - icon: "view"
      title: "مشاهده اسناد و تصاویر"
      content: "اسناد را با رندر کردن آنها به صورت فایل های HTML، PDF، PNG و JPEG مشاهده کنید."
    # feature loop
    - icon: "password"
      title: "اسناد ایمن را باز کنید"
      content: "رمز عبور را برای باز کردن اسناد رمزگذاری شده مشخص کنید."

    # feature loop
    - icon: "load"
      title: "فایل ها را از هر جایی بارگیری کنید"
      content: "اسناد را از فایل های مختلف، URL ها، سرورهای FTP، Amazon S3 و موارد دیگر بارگیری کنید."
    
    # feature loop
    - icon: "pages"
      title: "همه یا صفحات خاص را رندر کنید"
      content: "محدوده‌ای از شماره‌های صفحه را برای ارائه مشخص کنید."


############################# Code samples ############################
code_samples:
  enable: true
  title: "نمونه کد GroupDocs.Viewer"
  description: "برخی از موارد از عملیات معمولی GroupDocs.Viewer در C#، Java، TypeScript استفاده می کنند"
  items:
    # code sample loop
    - title: "نحوه رندر فایل های DOCX به PDF"
      content: |
        اسناد DOCX را بدون نصب Microsoft Word یا سایر نرم افزارها به PDF ارائه دهید. به راحتی فایل های DOCX را در برنامه دات نت خود بارگیری و مشاهده کنید، چه یک برنامه وب یا دسکتاپ. در اینجا مثالی از نحوه ارائه یک فایل DOCX به PDF آورده شده است: 
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // فایل DOCX را برای رندر بارگیری کنید
            using (Viewer viewer = new Viewer("sample.docx"))
            {
              // DOCX را به یک فایل PDF رندر کنید
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
            // فایل DOCX را برای رندر بارگیری کنید
            try (Viewer viewer = new Viewer("sample.docx")) {
                // DOCX را به یک فایل PDF رندر کنید
                PdfViewOptions viewOptions = new PdfViewOptions();
                viewer.view(viewOptions);
            }
            ```
        - language: "TypeScript"
          color: "green"
          content: |
            ```javascript {style=abap}  
            // فایل DOCX را برای رندر بارگیری کنید
            const viewer = new groupdocs.viewer.Viewer("sample.docx")
            
            // DOCX را به یک فایل PDF رندر کنید
            const viewOptions = groupdocs.viewer.PdfViewOptions(output.pdf)
            viewer.view(viewOptions)
            ```


############################# Formats ############################
formats:
  enable: true
  title:  "180+ فرمت فایل پشتیبانی می شود"
  description: "GroupDocs.Viewer از عملیات با محبوب ترین [فرمت های فایل] پشتیبانی می کند (https://docs.groupdocs.com/viewer/net/supported-document-formats/)" 



############################# Metrics ############################

metrics:
  enable: true
  title: "معیارهای عمیق و بینش آماری"
  description: "در تجزیه و تحلیل دقیق ارقام کلیدی ما غوطه ور شوید و معیارهای جامع و بینش آماری را در مورد دستاوردها، تأثیر و رشد ما ارائه دهید."

  items:
    # metrics loop
    - number: "180+"
      title: "فرمت های پشتیبانی شده"
      content: "به راحتی بیش از 180 فرمت فایل از جمله اسناد، تصاویر و نقشه های CAD را بدون دردسر مشاهده کنید. با راه حل جامع مشاهده ما موانع سازگاری را بشکنید و بدون زحمت به فایل های مختلف دسترسی پیدا کنید."

    # metrics loop
    - number: "1.0M"
      title: "دانلودهای NuGet"
      content: "راه حل بسته NuGet ما به یک منبع قابل اعتماد و پذیرفته شده در جامعه توسعه دهندگان تبدیل شده است که یکپارچه سازی یکپارچه و عملکرد ارزشمند را برای پروژه های بی شماری فراهم می کند."

    # metrics loop
    - number: "10+"
      title: "کتابخانه ها"
      content: "محصول ما شامل بیش از 10 کتابخانه است که ویژگی های پیشرفته ای را برای بهینه سازی عملکرد ارائه می دهد. این کتابخانه ها برای برآوردن نیازهای مختلف توسعه با قابلیت های بی نظیر طراحی شده اند."
    
    # metrics loop
    - number: "100+"
      title: "مشتریان خوشحال"
      content: "ارائه خدمات به نمادین ترین مارک ها در سراسر جهان. کشف کنید که چرا صدها نفر GroupDocs.Viewer را دوست دارند! ناوبری بدون درز، همکاری راحت و سهولت استفاده بی نظیر را کاوش کنید. همین الان ملحق شوید، همین الان بپیوندید!"



############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "مشتریان خوشحال ما"
  description: "کتابخانه های GroupDocs توسط برندهای مشهور و برجسته جهانی در سراسر جهان به کار گرفته می شوند."

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
  title: "برای شروع آماده اید؟"
  description: "ویژگی های GroupDocs.Viewer را به صورت رایگان امتحان کنید یا درخواست مجوز کنید"
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
  title:  "سوالات و نگرانی های رایج"
  description:  "پاسخ سوالات متداول را در بخش سوالات متداول ما بیابید تا به سرعت سوالات و نگرانی های خود را برطرف کنید."
  items:
    #  loop
    - question: "آیا می توانم محصولات GroupDocs را قبل از خرید ارزیابی کنم؟"
      answer: |
        آره! همه محصولات GroupDocs دارای یک نسخه ارزیابی بدون ریسک هستند. ما قویاً توسعه دهندگان را تشویق می کنیم که API های ما را قبل از خرید دانلود و امتحان کنند تا مطمئن شوند که نیازهای شما را 100% برآورده می کنند.
    #  loop
    - question: "آیا GroupDocs نمایش محصول را انجام می دهد؟"
      answer: |
        خیر، تمرکز ما بر روی API های خود و ساختن کاربردی ترین و پایدارترین محصولات ممکن است. ما آزمایش‌های کاملاً کاربردی و رایگان را در قالب یک [مجوز موقت](https://purchase.groupdocs.com/temporary-license/) ارائه می‌کنیم تا بتوانید خودتان محصول را آزمایش کنید.    
    #  loop
    - question: "از کجا می توانم محصول را دانلود کنم؟"
      answer: |
        همه محصولات برای دانلود از [وب سایت](https://releases.groupdocs.com) در دسترس هستند. ما نسخه های فیزیکی نرم افزار خود را از طریق پست ارسال نمی کنیم.
    #  loop
    - question: "آیا مجوزهای توسعه‌دهنده GroupDocs برای هر کاربر یا هر کاربر نام‌گذاری شده است؟"
      answer: |
        مجوزهای توسعه دهنده GroupDocs برای هر کاربر است، نه برای هر کاربر نامگذاری شده. ما می دانیم که اعضای یک تیم برنامه نویسی ممکن است در طول زمان تغییر کنند و اینکه هر بار که اتفاق می افتد به روز رسانی مجوز عملی نیست.
    #  loop
    - question: "آیا فقط برای توسعه دهندگان فعال نیاز به مجوز داریم؟ به عنوان مثال، ما یک تیم متشکل از دو توسعه دهنده داریم که در شیفت A کار می کنند و یک تیم دوم متشکل از دو توسعه دهنده در شیفت B کار می کنند ... در این شرایط، آیا به دو یا چهار مجوز نیاز داریم؟"
      answer: |
        همه توسعه دهندگانی که روی پروژه کار می کنند نیاز به مجوز دارند. در این شرایط، GroupDocs تیم شما را چهار عضو می بیند (حتی اگر آنها در زمان های مختلف کار می کنند). 


############################# Cloud ############################

cloud_links:
  enable: true
  title: "APIهای کم کد GroupDocs.Viewer"
  description: "با REST API مبتنی بر ابر ما، مشاهده سند یا تصویر را در هر نوع برنامه‌ای تسریع کنید"

  items:
    #  loop
    - icon: "groupdocs_viewer-for-curl"
      title: "GroupDocs.Viewer Cloud for cURL"
      link: "https://products.groupdocs.cloud/viewer/curl"
      content: "از CURL RESTful document viewer API استفاده کنید تا مایکروسافت آفیس، پی دی اف، و فرمت های مختلف فایل استاندارد دیگر را به طور موثر در برنامه های خود رندر و نمایش دهید."

    #  loop
    - icon: "groupdocs_viewer-for-net"
      title: "GroupDocs.Viewer Cloud for .NET"
      link: "https://products.groupdocs.cloud/viewer/net"
      content: "با Cloud SDK برای دات‌نت، قابلیت‌های مشاهده اسناد را در برنامه‌های NET افزایش دهید. اسناد را به صورت یکپارچه در قالب‌های HTML، PDF یا تصویر مشاهده کنید."

    #  loop
    - icon: "groupdocs_viewer-for-java"
      title: "GroupDocs.Viewer Cloud for Java"
      link: "https://products.groupdocs.cloud/viewer/java"
      content: "با استفاده از یک Document Viewer SDK برای جاوا، قابلیت‌های پیشرفته ارائه اسناد را در برنامه‌های جاوا خود ادغام کنید."
    

############################# Apps ############################

app_links:
  enable: true
  title: "برنامه های GroupDocs.Viewer NoCode"
  description: "برنامه آنلاین که به شما امکان می دهد 180 فرمت فایل محبوب را در مرورگر مشاهده کنید"

  items:
    #  loop
    - icon: "groupdocs_viewer-app"
      title: "GroupDocs.Viewer Total"
      link: "https://products.groupdocs.app/viewer/total"
      content: "برای مشاهده بیش از 180 فرمت فایل مستقیماً از مرورگر وب دلخواه خود، یک برنامه آنلاین رایگان کاوش کنید."

    #  loop
    - icon: "groupdocs_words-app"
      title:  "GroupDocs.Viewer DOCX"
      link: "https://products.groupdocs.app/viewer/docx"
      content: "ابزار مبتنی بر وب برای مشاهده فایل های Microsoft Word بدون دردسر در دستگاه های مختلف."

    #  loop
    - icon: "groupdocs_pdf-app"
      title:  "GroupDocs.Viewer PDF"
      link: "https://products.groupdocs.app/viewer/pdf"
      content: "باز کردن و مشاهده فایل های PDF به صورت آنلاین با نمایشگر PDF رایگان."
    



---