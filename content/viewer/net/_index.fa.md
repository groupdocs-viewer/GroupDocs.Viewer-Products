---
############################# Static ##########################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: fa
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

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
head_title: "API نمایشگر اسناد دات نت، رندر PDF Word Excel Image HTML Diagram"
head_description: "C# ASP.NET بیننده و API رندر فایل. نمایشگر PDF، نمایشگر Word، نمایشگر اکسل، نمایشگر تصویر، نمایشگر HTML، ویژگی های نمایش ایمیل را در برنامه های NET اضافه کنید."

############################# Header ##########################
title: "رندر و نمایش اسناد<br>با استفاده از NET API"
description: "API نمایشگر قدرتمند برای ارائه بیش از 180 فرمت سند به PDF، HTML، و تصویر با گزینه های پیکربندی همه کاره."
words:
  for: "for"

actions:
  viewer_demo: true
  viewer_demo_file_name: "quarterly-report.docx"
  main: "دانلود رایگان NuGet"
  main_link: "https://www.nuget.org/packages/GroupDocs.Viewer"
  alt: "صدور مجوز"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/net"
  title: "برای شروع آماده اید؟"
  description: "ویژگی های GroupDocs.Viewer را به صورت رایگان امتحان کنید یا درخواست مجوز کنید"

release:
  title: "نسخه {0} منتشر شد"
  notes: "ببینید چه چیزی جدید است"
  downloads: "دانلودها"
  link: "https://releases.groupdocs.com/viewer/net/release-notes/latest/"

code:
  title: "رندر فایل های پی دی اف در سی شارپ"
  more: "نمونه های بیشتر"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
  install: "dotnet add package GroupDocs.Viewer"
  content: |
    ```csharp {style=abap}   
    // فایل PDF منبع را بارگیری کنید
    using (var viewer = new Viewer("resume.pdf"))
    {
        // گزینه های خروجی HTML را تنظیم کنید، یک فایل در هر صفحه
        var viewOptions = 
        HtmlViewOptions.ForEmbeddedResources("page{0}.html");
        
        // PDF را با منابع تعبیه شده به HTML ارائه دهید        
        viewer.View(viewOptions);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Viewer در یک نگاه"
  description: "API برای رندر، نمایش، تبدیل اسناد، اسلایدها، نمودارها و بسیاری از انواع اسناد دیگر در برنامه های NET"
  features:
    # feature loop
    - title: "اسناد را کارآمد و قابل اعتماد مشاهده کنید"
      content: "با استفاده از GroupDocs.Viewer API می‌توانید اسناد با هر قالب پشتیبانی‌شده را به‌صورت کارآمد به [HTML](https://docs.groupdocs.com/viewer/net/rendering-to-html/)، [JPEG, PNG](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/)، و [PDF](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/) رندر کنید؛ این کار با گزینه‌های انعطاف‌پذیر و قدرتمند انجام می‌شود و محتوا و ساختار سند حفظ می‌شود. GroupDocs.Viewer از .NET Framework 4.6.2 و .NET 6.0 پشتیبانی می‌کند و بر روی پلتفرم‌های Windows و Linux کار می‌کند."

    # feature loop
    - title: "اکثر فرمت های فایل و سند محبوب پشتیبانی می شوند"
      content: "ما بیش از ۱۸۰ فرمت فایل و سند پرکاربرد را پشتیبانی می‌کنیم که شامل [Word](https://docs.groupdocs.com/viewer/net/render-word-documents/)، [Excel](https://blog.groupdocs.com/viewer/working-with-spreadsheets/)، [PDF](https://docs.groupdocs.com/viewer/net/render-pdf-documents/)، [PowerPoint](https://blog.groupdocs.com/viewer/view-powerpoint-presentations/)، خانواده فرمت‌های OpenDocument، آرشیوها، تصاویر رستر و وکتور، کتاب‌های الکترونیکی، زبان‌ها و قالب‌های برنامه‌نویسی و بسیاری از انواع فایل‌های دیگر می‌شود، از جمله فایل‌های رمزگذاری‌شده با حفاظت رمزعبور."

    # feature loop
    - title: "خروجی قابل تنظیم"
      content: "GroupDocs.Viewer نه تنها اجازه می دهد تا سند را رندر کند، بلکه کنترل کند که دقیقاً چه قسمت هایی از سند باید رندر شوند یا اکنون، چگونه باید رندر شوند و تبدیل های مختلف را در خروجی رندر شده اعمال می کند."

    # feature loop
    - title: "UI برای ASP.NET Core"
      content: "ما یک بسته UI منبع باز برای ASP.NET Core ارائه می دهیم که می تواند در عرض چند دقیقه به پروژه شما اضافه شود. بسته Viewer.UI شامل یک web-UI مبتنی بر Angular است و مجموعه ای از APIهای مفید و ارائه دهندگان ذخیره سازی داده را ارائه می دهد."

############################# Platforms ############################
platforms:
  enable: true
  title: "پشتیبانی از پلتفرم ها"
  description: "GroupDocs.Viewer برای دات نت از سیستم عامل ها، فریمورک ها و مدیران بسته های زیر پشتیبانی می کند"
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
    - title: "VS Code"
      image: "vs_code"
    # platform loop
    - title: "ReSharper"
      image: "resharper"
    # platform loop
    - title: "macOS"
      image: "finder"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "NuGet"
      image: "nuget"
  packages:
    # packages loop
    - title: "بسته مخصوص ویندوز"
      content: |
        * از .NET Framework 4.6.2+ و .NET 6.0 پشتیبانی می کند
        * جامع ترین فرمت های فایل پشتیبانی می کند
        * بستگی به System.Drawing و System.Drawing.Common دارد 
      action: "دانلود NuGet"
      action_link: "https://www.nuget.org/packages/GroupDocs.Viewer"
    # packages loop
    - title: "بسته کراس پلت فرم" 
      content: |
        * پشتیبانی از دات نت 6.0 و نسخه های بالاتر 
        * پشتیبانی از فرمت های فایل محدود 
        * روی ویندوز، لینوکس و macOS کار می کند 
      action: "دانلود NuGet" 
      action_link: "https://www.nuget.org/packages/GroupDocs.Viewer.CrossPlatform" 

############################# File formats ############################
formats:
  enable: true
  title: "فرمت های فایل پشتیبانی شده"
  description: |
    GroupDocs.Viewer برای NET از عملیات با زیر پشتیبانی می‌کند [formats](https://docs.groupdocs.com/viewer/net/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### مایکروسافت آفیس، OpenDocument و فرمت های متنی
        * **Word:** DOC, DOCX, DOCM, DOT, DOTX, DOTM, RTF, TXT
        * **Excel:** XLS, XLSX, XLSM, XLSB, XLTM, XLT, XLTM, XLTX
        * **PowerPoint:** PPT, PPTX, PPS, PPSX, PPSM, POT, POTM, POTX, PPTM        
        * **Project:** MPP, MPT, MPX {{< landing/tooltip icon="windows" title="پشتیبانی شده توسط بسته ویژه ویندوز" >}}
        * **Outlook:** MSG, EML, EMLX, PST, OST
        * **OneNote:** ONE {{< landing/tooltip icon="windows" title="پشتیبانی شده توسط بسته ویژه ویندوز" >}}
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
        * **Adobe Photoshop:** PSD, PSB {{< landing/tooltip icon="windows" title="پشتیبانی شده توسط بسته ویژه ویندوز" >}}       
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
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM {{< landing/tooltip icon="windows" title="پشتیبانی شده توسط بسته ویژه ویندوز" >}}
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
      title: "[مشاهده اسناد در HTML](https://blog.groupdocs.com/viewer/view-word-documents-as-html-responsive-page-using-csharp/)"
      content: "هر نوع سندی را با CSS و SVG به یک سند HTML تبدیل کنید، که می تواند در هر مرورگر وب مدرن نمایش داده شود."

    # feature loop
    - icon: "rasterize"
      title: "[اسناد را شطرنجی کنید](https://docs.groupdocs.com/viewer/net/rendering-to-png-or-jpeg/)"
      content: "هر قالب سند قابل پشتیبانی را با فرمت تصویر قابل تنظیم و کیفیت فشرده سازی به تصویر شطرنجی تبدیل کنید."

    # feature loop
    - icon: "font"
      title: "[کنترل فونت‌های سند](https://blog.groupdocs.com/viewer/working-with-fonts/)"
      content: "فونت‌های استفاده شده در سند را شناسایی کنید. فونت‌های مفقود را با جایگزینی یا حذف از خروجی مدیریت کنید."

    # feature loop
    - icon: "convertpdf"
      title: "[تبدیل به PDF](https://blog.groupdocs.com/viewer/rendering-documents-as-pdf/)"
      content: "سند با هر فرمت قابل پشتیبانی را می توان به راحتی با گزینه های قابل تنظیم به PDF تبدیل و ذخیره کرد."

    # feature loop
    - icon: "transform"
      title: "[تغییرات را اعمال کنید](https://blog.groupdocs.com/viewer/protect-your-documents-with-watermarks-in-groupdocs-viewer-for-dot-net/)"
      content: "سند خروجی را می توان در حین رندر تبدیل کرد - صفحات را می توان چرخاند و/یا مرتب کرد و واترمارک متنی در بالای آنها قرار داد."

    # feature loop
    - icon: "adjustment"
      title: "[تنظیم خروجی HTML](https://blog.groupdocs.com/viewer/render-word-documents-as-clean-html-using-csharp/)"
      content: "اسناد HTML خروجی، تولید شده توسط GroupDocs.Viewer، را می توان بسیار دقیق تنظیم کرد: امکان ذخیره در جریان یا فایل، با منابع خارجی یا جاسازی شده، تماس های برگشتی و غیره وجود دارد."

    # feature loop
    - icon: "complex"
      title: "[پشتیبانی از ساختارهای پیچیده سند](https://blog.groupdocs.com/viewer/process-microsoft-outlook-email-attachments-in-a-.net-viewer-application/)"
      content: "GroupDocs.Viewer نه تنها از اسناد منفرد، بلکه از فایل‌هایی نیز پشتیبانی می‌کند که در داخل شامل فهرست یا ساختار سلسله مراتبی از اسناد هستند، مانند پیام‌های ایمیل با پیوست‌ها، آرشیوهای ZIP با فایل‌های داخلی درون پوشه‌ها، تصاویر TIFF چند صفحه‌ای و غیره."

    # feature loop
    - icon: "optimization"
      title: "[گزینه های بهینه سازی](https://blog.groupdocs.com/viewer/exclude-specific-fonts-from-output-html-using-groupdocs.viewer-for-.net-18.10/)"
      content: "GroupDocs.Viewer حاوی یک زیرسیستم کش قابل تنظیم است که می تواند با استفاده از نسخه های ذخیره شده اسناد، زمان بارگذاری را تسریع بخشد. همچنین مجموعه ای از گزینه های مختلف برای فرمت های مختلف اجازه می دهد تا برخی از بخش ها یا جنبه های غیر ضروری اسناد را از رندر حذف کنید (فونت ها، کاربرگ های مخفی، پیوست های ایمیل) برای بهینه سازی عملکرد کلی."

    # feature loop
    - icon: "passwordprotected"
      title: "[پشتیبانی از اسناد محافظت شده با رمز عبور](https://docs.groupdocs.com/viewer/net/load-password-protected-document/)"
      content: "GroupDocs.Viewer اجازه می دهد تا اسناد رمزگذاری شده را از انواع مختلف باز کنید: PDF، WordProcessing، Spreadsheet، Presentation و غیره، با تعیین رمز عبور در گزینه های بارگیری."

############################# Code samples ############################
code_samples:
  enable: true
  title: "نمونه کد"
  description: "برخی از موارد معمولی GroupDocs.Viewer برای عملیات NET استفاده می کنند"
  items:
    # code sample loop
    - title: "DOCX را به HTML رندر کنید"
      content: |
        ویژگی های کلاس [HtmlViewOptions](https://reference.groupdocs.com/viewer/net/groupdocs.viewer.options/htmlviewoptions/) به شما امکان می دهد فرآیند تبدیل را کنترل کنید، در مورد آن اینجا[HTML](https://docs.groupdocs.com/viewer/net/rendering-to-html/). به عنوان مثال، می توانید تمام منابع خارجی را در فایل HTML خروجی جاسازی کنید، فایل خروجی را کوچک کنید و آن را برای چاپ بهینه کنید.
        {{< landing/code title="C#">}}
        ```csharp {style=abap}
        using GroupDocs.Viewer;
        using GroupDocs.Viewer.Options;
        
        // بیننده فوری
        using (Viewer viewer = new Viewer("resume.docx"))
        {
            // گزینه های خروجی HTML را تنظیم کنید
            HtmlViewOptions options = HtmlViewOptions.ForEmbeddedResources();
            
            // DOCX را با منابع جاسازی شده به HTML ارائه دهید
            viewer.View(options);
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "PPTX را به PDF صادر کنید"
      content: |
        یک نمونه کلاس [PdfViewOptions](https://reference.groupdocs.com/viewer/net/groupdocs.viewer.options/pdfviewoptions/) ایجاد کنید و آن را به [Viewer.View](https://reference.groupdocs.com/viewer/net/groupdocs.viewer/viewer/view/#view) ارسال کنید. ر برای تبدیل فایل پاورپوینت PPTX به PDF. ویژگی های کلاس PdfViewOptions به شما امکان می دهد فرآیند تبدیل را کنترل کنید. به عنوان مثال، می توانید از فایل خروجی محافظت کنید، صفحات آن را مجددا مرتب کنید و کیفیت تصاویر سند را مشخص کنید. برای جزئیات به [PDF](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/) مراجعه کنید.
        {{< landing/code title="C#">}}
        ```csharp {style=abap}   
        using GroupDocs.Viewer;
        using GroupDocs.Viewer.Options;
        
        using (var viewer = new Viewer("presentation.pptx"))
        {
            // گزینه های PDF خروجی را تنظیم کنید       
            var viewOptions = new PdfViewOptions("presentation.pdf");
            
            // PPTX را به PDF صادر کنید       
            viewer.View(viewOptions);
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