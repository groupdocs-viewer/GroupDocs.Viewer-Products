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
    # supported_platforms loop
    - title: "Python"
      tag: "python-net"


############################# Head ############################
head_title: "Java Document Viewer API، رندر PDF Word Excel Image HTML Diagram"
head_description: "کتابخانه Document Viewer برای توسعه برنامه‌های جاوا که اسناد چند فرمتی را به‌طور بومی ارائه، مشاهده و دستکاری می‌کنند که از بیش از 180 فرمت فایل پشتیبانی می‌کنند."

############################# Header ############################
title: "رندر و نمایش اسناد<br>با استفاده از Java API"
description: "API نمایشگر قدرتمند برای ارائه بیش از 180 فرمت سند به PDF، HTML، و تصویر با گزینه های پیکربندی همه کاره."
words:
  for: "for"

actions:
  viewer_demo: true
  viewer_demo_file_name: "quarterly-report.docx"
  main: "دانلود رایگان Maven"
  main_link: "https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-viewer/"
  alt: "صدور مجوز"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/java"
  title: "برای شروع آماده اید؟"
  description: "ویژگی های GroupDocs.Viewer را به صورت رایگان امتحان کنید یا درخواست مجوز کنید"

release:
  title: "نسخه {0} منتشر شد"
  notes: "ببینید چه چیزی جدید است"
  downloads: "دانلودها"
  link: "https://releases.groupdocs.com/viewer/java/release-notes/latest/"

code:
  title: "رندر فایل های پی دی اف در جاوا"
  more: "نمونه های بیشتر"
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
        // گزینه های خروجی HTML را تنظیم کنید، یک فایل در هر صفحه  
        HtmlViewOptions viewOptions = 
        HtmlViewOptions.forEmbeddedResources();

        // PDF را با منابع تعبیه شده به HTML ارائه دهید
        viewer.view(viewOptions);
    }
    ```
############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Viewer در یک نگاه"
  description: "API برای رندر، نمایش، تبدیل اسناد، اسلایدها، نمودارها و بسیاری از انواع اسناد دیگر در برنامه های جاوا"
  features:
    # feature loop
    - title: "اسناد را کارآمد و قابل اعتماد مشاهده کنید"
      content: "با استفاده از GroupDocs.Viewer API می‌توانید اسناد با هر قالب پشتیبانی‌شده را به‌صورت کارآمد به [HTML](https://docs.groupdocs.com/viewer/java/rendering-to-html/)، [JPEG, PNG](https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/)، و [PDF](https://docs.groupdocs.com/viewer/java/rendering-to-pdf/) رندر کنید؛ این کار با گزینه‌های انعطاف‌پذیر و قدرتمند انجام می‌شود و محتوا و ساختار سند حفظ می‌شود. GroupDocs.Viewer بر روی پلتفرم‌های Windows و Linux کار می‌کند."

    # feature loop
    - title: "اکثر فرمت های فایل و سند محبوب پشتیبانی می شوند"
      content: "ما بیش از ۱۸۰ فرمت فایل و سند پرکاربرد را پشتیبانی می‌کنیم که شامل [Word](https://docs.groupdocs.com/viewer/java/render-word-documents/)، [Excel](https://docs.groupdocs.com/viewer/java/render-excel-and-apple-numbers-spreadsheets/)، [PDF](https://docs.groupdocs.com/viewer/java/render-pdf-documents/)، [PowerPoint](https://blog.groupdocs.com/viewer/view-powerpoint-presentations/)، خانواده فرمت‌های OpenDocument، آرشیوها، تصاویر رستر و وکتور، کتاب‌های الکترونیکی، زبان‌ها و قالب‌های برنامه‌نویسی و بسیاری از انواع فایل‌های دیگر می‌شود، از جمله فایل‌های رمزگذاری‌شده با حفاظت رمزعبور."

    # feature loop
    - title: "خروجی قابل تنظیم"
      content: "GroupDocs.Viewer نه تنها اجازه می دهد تا سند را رندر کند، بلکه کنترل کند که دقیقاً چه قسمت هایی از سند باید رندر شوند یا اکنون، چگونه باید رندر شوند و تبدیل های مختلف را در خروجی رندر شده اعمال می کند."

    # feature loop
    - title: "رابط کاربری وب برای چارچوب Spring"
      content: "ما یک بسته UI منبع باز برای چارچوب Spring ارائه می دهیم که می تواند در عرض چند دقیقه به پروژه شما اضافه شود. بسته Viewer.UI شامل یک web-UI مبتنی بر Angular است و مجموعه ای از APIهای مفید و ارائه دهندگان ذخیره سازی داده را ارائه می دهد."

############################# Platforms ############################
platforms:
  enable: true
  title: "استقلال سکو"
  description: "GroupDocs.Viewer برای جاوا از سیستم عامل ها، چارچوب ها و مدیریت بسته های زیر پشتیبانی می کند"
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
  title: "فرمت های فایل پشتیبانی شده"
  description: |
    GroupDocs.Viewer برای جاوا از عملیات با زیر پشتیبانی می‌کند [formats](https://docs.groupdocs.com/viewer/java/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### مایکروسافت آفیس، OpenDocument و فرمت های متنی
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
        ### تصاویر، گرافیک و نمودارها
        * **تصاویر شطرنجی:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
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
        ### دیگر        
        * **وب:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **آرشیوها:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **دیگر:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "ویژگی های GroupDocs.Viewer"
  description: "رندر، نمایش، و تبدیل یکپارچه PDF و اسناد آفیس"

  items:
    # feature loop
    - icon: "viewhtml"
      title: "[مشاهده اسناد در HTML](https://docs.groupdocs.com/viewer/java/rendering-to-html/)"
      content: "هر نوع سندی را با CSS و SVG به یک سند HTML تبدیل کنید، که می تواند در هر مرورگر وب مدرن نمایش داده شود."

    # feature loop
    - icon: "rasterize"
      title: "[اسناد را شطرنجی کنید](https://docs.groupdocs.com/viewer/java/rendering-to-png-or-jpeg/)"
      content: "هر قالب سند قابل پشتیبانی را با فرمت تصویر قابل تنظیم و کیفیت فشرده سازی به تصویر شطرنجی تبدیل کنید."

    # feature loop
    - icon: "font"
      title: "[کنترل فونت‌های سند](https://docs.groupdocs.com/viewer/java/set-custom-fonts/)"
      content: "فونت‌های استفاده شده در سند را شناسایی کنید. فونت‌های مفقود را با جایگزینی یا حذف از خروجی مدیریت کنید."

    # feature loop
    - icon: "convertpdf"
      title: "[تبدیل به PDF](https://docs.groupdocs.com/viewer/java/rendering-to-pdf/)"
      content: "سند با هر فرمت قابل پشتیبانی را می توان به راحتی با گزینه های قابل تنظیم به PDF تبدیل و ذخیره کرد."

    # feature loop
    - icon: "transform"
      title: "[تغییرات را اعمال کنید](https://docs.groupdocs.com/viewer/java/flip-or-rotate-pages/)"
      content: "سند خروجی را می توان در حین رندر تبدیل کرد - صفحات را می توان چرخاند و/یا مرتب کرد و واترمارک متنی در بالای آنها قرار داد."

    # feature loop
    - icon: "adjustment"
      title: "[تنظیم خروجی HTML](https://docs.groupdocs.com/viewer/java/rendering-to-html/)"
      content: "اسناد HTML خروجی، تولید شده توسط GroupDocs.Viewer، را می توان بسیار دقیق تنظیم کرد: امکان ذخیره در جریان یا فایل، با منابع خارجی یا جاسازی شده، تماس های برگشتی و غیره وجود دارد."

    # feature loop
    - icon: "complex"
      title: "[پشتیبانی از ساختارهای پیچیده سند](https://blog.groupdocs.com/viewer/view-files-and-folders-in-zip-and-tar-archives-using-java-api/)"
      content: "GroupDocs.Viewer نه تنها از اسناد منفرد، بلکه از فایل‌هایی نیز پشتیبانی می‌کند که در داخل شامل فهرست یا ساختار سلسله مراتبی از اسناد هستند، مانند پیام‌های ایمیل با پیوست‌ها، آرشیوهای ZIP با فایل‌های داخلی درون پوشه‌ها، تصاویر TIFF چند صفحه‌ای و غیره."

    # feature loop
    - icon: "optimization"
      title: "[گزینه های بهینه سازی](https://docs.groupdocs.com/viewer/java/how-to-use-custom-cache-implementation/)"
      content: "GroupDocs.Viewer حاوی یک زیرسیستم کش قابل تنظیم است که می تواند با استفاده از نسخه های ذخیره شده اسناد، زمان بارگذاری را تسریع بخشد. همچنین مجموعه ای از گزینه های مختلف برای فرمت های مختلف اجازه می دهد تا برخی از بخش ها یا جنبه های غیر ضروری اسناد را از رندر حذف کنید (فونت ها، کاربرگ های مخفی، پیوست های ایمیل) برای بهینه سازی عملکرد کلی."

    # feature loop
    - icon: "passwordprotected"
      title: "[پشتیبانی از اسناد محافظت شده با رمز عبور](https://docs.groupdocs.com/viewer/java/load-password-protected-document/)"
      content: "GroupDocs.Viewer اجازه می دهد تا اسناد رمزگذاری شده را از انواع مختلف باز کنید: PDF، WordProcessing، Spreadsheet، Presentation و غیره، با تعیین رمز عبور در گزینه های بارگیری."

############################# Code samples ############################
code_samples:
  enable: true
  title: "نمونه کد"
  description: "برخی از موارد معمولی GroupDocs.Viewer برای عملیات جاوا استفاده می کنند"
  items:
    # code sample loop
    - title: "DOCX را به HTML رندر کنید"
      content: |
        ویژگی‌های کلاس [HtmlViewOptions](https://reference.groupdocs.com/viewer/java/com.groupdocs.viewer.options/htmlviewoptions/) به شما امکان می‌دهد فرآیند تبدیل را کنترل کنید، در مورد آن [اینجا](https://docs.groupdocs.com/viewer/java/rendering-to-html/). به عنوان مثال، می توانید تمام منابع خارجی را در فایل HTML خروجی جاسازی کنید، فایل خروجی را کوچک کنید و آن را برای چاپ بهینه کنید.
        {{< landing/code title="Java">}}
        ```java {style=abap}
        import com.groupdocs.viewer.Viewer;
        import com.groupdocs.viewer.options.HtmlViewOptions;

        // Instantiate Viewer
        try (Viewer viewer = new Viewer("resume.docx"))
        {
            // گزینه های خروجی HTML را تنظیم کنید
            HtmlViewOptions options = 
            HtmlViewOptions.forEmbeddedResources();

            // DOCX را با منابع جاسازی شده به HTML ارائه دهید
            viewer.view(options);
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "PPTX را به PDF صادر کنید"
      content: |
        یک نمونه کلاس [PdfViewOptions](https://reference.groupdocs.com/viewer/java/com.groupdocs.viewer.options/pdfviewoptions/) ایجاد کنید و آن را به [Viewer.View](https://reference.groupdocs.com/viewer/net/groupdocs.viewer/viewer/view/#view) ارسال کنید. روش برای تبدیل فایل پاورپوینت PPTX به PDF. ویژگی های کلاس PdfViewOptions به شما امکان می دهد فرآیند تبدیل را کنترل کنید. به عنوان مثال، می توانید از فایل  خروجی محافظت کنید، صفحات آن را مجددا مرتب کنید و کیفیت تصاویر سند را مشخص کنید. برای جزئیات به [PDF](https://docs.groupdocs.com/viewer/java/rendering-to-pdf/) مراجعه کنید.
        {{< landing/code title="Java">}}
        ```java {style=abap}   
        import com.groupdocs.viewer.Viewer;
        import com.groupdocs.viewer.options.PdfViewOptions;

        // Instantiate Viewer
        try (Viewer viewer = new Viewer("presentation.pptx"))
        {            
            // گزینه های PDF خروجی را تنظیم کنید
            PdfViewOptions viewOptions = new PdfViewOptions();

            // PPTX را به PDF صادر کنید
            viewer.view(viewOptions);
        }
        ```
        {{< /landing/code >}}
############################# Reviews ############################
# reviews:
# enable: true
# title: "بررسی محصولات GroupDocs"
# description: "فقط حرف ما را قبول نکنید. ببینید سایر توسعه دهندگان در مورد API های ما چه می گویند"

# items:
#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "خدمات عالی و محصولات عالی. آنها در طول فرآیند اجرای GroupDocs.Viewer برای دات نت بسیار مفید و پاسخگو بودند، نمی توان آنها را به اندازه کافی توصیه کرد."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "پس از پیاده سازی و استفاده از GroupDocs.Viewer برای دات نت در پروژه، به نظر می رسد که بسیار خوب کار می کند. من با مدارک زیادی تست کردم و تا الان خیلی خوبه. همه چیزهایی که به آن پرتاب کرده‌ام به خوبی رندر می‌شوند و به همان خوبی که در یک نمایشگر PDF یا MS Word به نظر می‌رسند."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---