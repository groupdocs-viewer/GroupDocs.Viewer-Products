---
############################# Static ############################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: fa
product: "Viewer"
product_tag: "viewer"
platform: "Node.js via Java"
platform_tag: "nodejs-java"

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
head_title: "Node.js Document Viewer API برای تصاویر و ایمیل های PDF Word Excel HTML"
head_description: "نمایشگر اسناد Node.js و API رندر فایل ها. نمایشگر PDF، نمایشگر Word، نمایشگر اکسل، نمایشگر تصویر، نمایشگر HTML، نمایشگر ایمیل را در برنامه های جاوا اسکریپت اضافه کنید."

############################# Header ############################
title: "Node.js API برای ارائه و نمایش اسناد"
description: "کتابخانه Document Viewer برای توسعه برنامه‌های جاوا اسکریپت که اسناد چند قالبی را به‌طور بومی رندر، مشاهده و دستکاری می‌کنند و بیش از 180 فرمت فایل را پشتیبانی می‌کنند."
words:
  for: "for"

actions:
  main: "دانلود رایگان NPM"
  main_link: "https://www.npmjs.com/package/@groupdocs/groupdocs.viewer"
  alt: "صدور مجوز"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/nodejs-java"
  title: "برای شروع آماده اید؟"
  description: "ویژگی های GroupDocs.Viewer را به صورت رایگان امتحان کنید یا درخواست مجوز کنید"

release:
  title: "نسخه {0} منتشر شد"
  notes: "ببینید چه چیزی جدید است"
  downloads: "دانلودها"
  link: "https://releases.groupdocs.com/viewer/nodejs-java/release-notes/latest/"

code:
  title: "فایل های PDF را در جاوا اسکریپت رندر کنید"
  more: "نمونه های بیشتر"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Node.js-via-Java"
  install: "npm i @groupdocs/groupdocs.viewer"
  content: |
    ```javascript {style=abap}       
    // گزینه های خروجی HTML را تنظیم کنید، یک فایل در هر صفحه
    const viewOptions = HtmlViewOptions.forEmbeddedResources()
    
    // Instantiate Viewer
    const viewer = new Viewer("resume.pdf")

    // PDF را با منابع تعبیه شده به HTML ارائه دهید
    viewer.view(viewOptions)
    viewer.close()
    ```
############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Viewer در یک نگاه"
  description: "API برای رندر، نمایش، تبدیل اسناد، اسلایدها، نمودارها و بسیاری از انواع اسناد دیگر در برنامه های Node.js"
  features:
    # feature loop
    - title: "اسناد را کارآمد و قابل اعتماد مشاهده کنید"
      content: "با GroupDocs.Viewer API می‌توانید با حفظ یکپارچگی محتوا و ساختار سند، اسناد را با هر فرمت قابل پشتیبانی به HTML، JPEG، PNG، و PDF با گزینه‌های منعطف و قدرتمند ارائه کنید. GroupDocs.Viewer برای Node.js روی پلتفرم های ویندوز و لینوکس کار می کند."

    # feature loop
    - title: "اکثر فرمت های فایل و سند محبوب پشتیبانی می شوند"
      content: "ما از ارائه بیش از 180 فرمت فایل و سند محبوب پشتیبانی می کنیم که شامل Word، Excel، PDF، PowerPoint، خانواده فرمت های OpenDocument، آرشیو، تصاویر Raster و Vector، کتاب های الکترونیکی، زبان های برنامه نویسی و نشانه گذاری ها، و بسیاری از انواع فایل های دیگر، از جمله رمزگذاری شده است. فایل هایی با محافظت از رمز عبور"

    # feature loop
    - title: "خروجی قابل تنظیم"
      content: "GroupDocs.Viewer نه تنها اجازه می دهد تا سند را رندر کند، بلکه کنترل کند که دقیقاً چه قسمت هایی از سند باید رندر شوند یا اکنون، چگونه باید رندر شوند و تبدیل های مختلف را در خروجی رندر شده اعمال می کند."

############################# Platforms ############################
platforms:
  enable: true
  title: "استقلال سکو"
  description: "GroupDocs.Viewer برای Node.js از سیستم عامل ها، فریمورک ها و مدیریت بسته های زیر پشتیبانی می کند"
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
    - title: "NPM"
      image: "npm"

############################# File formats ############################
formats:
  enable: true
  title: "فرمت های فایل پشتیبانی شده"
  description: |
    GroupDocs.Viewer برای Node.js از طریق جاوا از عملیات ب زیر پشتیبانی می‌کند [formats](https://docs.groupdocs.com/viewer/nodejs-java/supported-document-formats/).
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
      title: "مشاهده اسناد در HTML"
      content: "هر نوع سندی را با CSS و SVG به یک سند HTML تبدیل کنید، که می تواند در هر مرورگر وب مدرن نمایش داده شود."

    # feature loop
    - icon: "rasterize"
      title: "اسناد را شطرنجی کنید"
      content: "هر قالب سند قابل پشتیبانی را با فرمت تصویر قابل تنظیم و کیفیت فشرده سازی به تصویر شطرنجی تبدیل کنید."

    # feature loop
    - icon: "sourcecode"
      title: "کدهای برنامه نویسی را رندر و برجسته کنید"
      content: "پشتیبانی از همه زبان‌های برنامه‌نویسی، اسکریپت‌نویسی و نشانه‌گذاری محبوب، با قابلیت تجزیه و برجسته کردن نحو آنها."

    # feature loop
    - icon: "convertpdf"
      title: "تبدیل به PDF"
      content: "سند با هر فرمت قابل پشتیبانی را می توان به راحتی با گزینه های قابل تنظیم به PDF تبدیل و ذخیره کرد."

    # feature loop
    - icon: "transform"
      title: "تغییرات را اعمال کنید"
      content: "سند خروجی را می توان در حین رندر تبدیل کرد - صفحات را می توان چرخاند و/یا مرتب کرد و واترمارک متنی در بالای آنها قرار داد."

    # feature loop
    - icon: "adjustment"
      title: "تنظیم خروجی HTML"
      content: "اسناد HTML خروجی، تولید شده توسط GroupDocs.Viewer، را می توان بسیار دقیق تنظیم کرد: امکان ذخیره در جریان یا فایل، با منابع خارجی یا جاسازی شده، تماس های برگشتی و غیره وجود دارد."

    # feature loop
    - icon: "complex"
      title: "پشتیبانی از ساختارهای پیچیده سند"
      content: "GroupDocs.Viewer نه تنها از اسناد منفرد، بلکه از فایل‌هایی نیز پشتیبانی می‌کند که در داخل شامل فهرست یا ساختار سلسله مراتبی از اسناد هستند، مانند پیام‌های ایمیل با پیوست‌ها، آرشیوهای ZIP با فایل‌های داخلی درون پوشه‌ها، تصاویر TIFF چند صفحه‌ای و غیره."

    # feature loop
    - icon: "optimization"
      title: "گزینه های بهینه سازی"
      content: "GroupDocs.Viewer حاوی یک زیرسیستم کش قابل تنظیم است که می تواند با استفاده از نسخه های ذخیره شده اسناد، زمان بارگذاری را تسریع بخشد. همچنین مجموعه ای از گزینه های مختلف برای فرمت های مختلف اجازه می دهد تا برخی از بخش ها یا جنبه های غیر ضروری اسناد را از رندر حذف کنید (فونت ها، کاربرگ های مخفی، پیوست های ایمیل) برای بهینه سازی عملکرد کلی."

    # feature loop
    - icon: "passwordprotected"
      title: "پشتیبانی از اسناد محافظت شده با رمز عبور"
      content: "GroupDocs.Viewer اجازه می دهد تا اسناد رمزگذاری شده را از انواع مختلف باز کنید: PDF، WordProcessing، Spreadsheet، Presentation و غیره، با تعیین رمز عبور در گزینه های بارگیری."

############################# Code samples ############################
code_samples:
  enable: true
  title: "نمونه کد"
  description: "برخی از موارد معمولی GroupDocs.Viewer برای Node.js از طریق عملیات جاوا استفاده می کنند"
  items:
    # code sample loop
    - title: "DOCX را به HTML رندر کنید"
      content: |
        ویژگی‌های کلاس  به شما امکان می‌دهد فرآیند تبدیل را کنترل کنید، بیشتر در مورد آن [HtmlViewOptions](https://docs.groupdocs.com/viewer/nodejs-java/rendering-to-html/). به عنوان مثال، می توانید تمام منابع خارجی را در فایل HTML خروجی جاسازی کنید، فایل خروجی را کوچک کنید و آن را برای چاپ بهینه کنید.
        {{< landing/code title="JavaScript">}}
        ```javascript {style=abap}
        import { Viewer, HtmlViewOptions } from '@groupdocs/groupdocs.viewer'

        // گزینه های خروجی HTML را تنظیم کنید، یک فایل در هر صفحه
        const viewOptions = HtmlViewOptions.forEmbeddedResources()

        // Instantiate Viewer
        const viewer = new Viewer("resume.docx")

        // DOCX را با منابع جاسازی شده به HTML ارائه دهید
        viewer.view(viewOptions)
        viewer.close()
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "PPTX را به PDF صادر کنید"
      content: |
        یک نمونه کلاس PdfViewOptions ایجاد کنید و آن را به روش Viewer.view منتقل کنید تا یک فایل پاورپوینت PPTX را به PDF تبدیل کنید. ویژگی های کلاس `PdfViewOptions` به شما امکان می دهد فرآیند تبدیل را کنترل کنید. به عنوان مثال، می توانید از فایل PDF خروجی محافظت کنید، صفحات آن را مجددا مرتب کنید و کیفیت تصاویر سند را مشخص کنید. برای جزئیات بیشتر ب [PDF](https://docs.groupdocs.com/viewer/nodejs-java/rendering-to-pdf/) مراجعه کنید.
        {{< landing/code title="JavaScript">}}
        ```javascript {style=abap}   
        import { Viewer, PdfViewOptions } from '@groupdocs/groupdocs.viewer'

        // گزینه های PDF خروجی را تنظیم کنید
        const viewOptions = new PdfViewOptions("presentation.pdf")

        // Instantiate Viewer
        const viewer = new Viewer("presentation.pptx")

        // PPTX را به PDF صادر کنید
        viewer.view(viewOptions)
        viewer.close()
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
