---
############################# Static ############################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: fa
product: "Viewer"
product_tag: "viewer"
platform: "Python via .NET"
platform_tag: "python-net"

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
head_title: "API نمایشگر اسناد پایتون برای PDF، Word، Excel، HTML، تصاویر و ایمیل‌ها"
head_description: "API نمایشگر اسناد و رندر فایل پایتون. نمایشگر PDF، نمایشگر Word، نمایشگر Excel، نمایشگر تصویر، نمایشگر HTML و نمایشگر ایمیل را به برنامه‌های Python اضافه کنید."

############################# Header ############################
title: "یک API قدرتمند پایتون برای نمایش بهینه اسناد"
description: "رندر و نمایش بیش از 180 فرمت سند (PDF، HTML، تصویر) با API های قدرتمند و گزینه های پیکربندی متنوع برای توسعه برنامه های پایتون."
words:
  for: "for"

actions:
  viewer_demo: true
  viewer_demo_file_name: "quarterly-report.docx"
  main: "دانلود رایگان PyPI"
  main_link: "https://pypi.org/project/groupdocs-viewer-net/"
  alt: "صدور مجوز"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/python-net"
  title: "برای شروع آماده اید؟"
  description: "ویژگی های GroupDocs.Viewer را به صورت رایگان امتحان کنید یا درخواست مجوز کنید"

release:
  title: "نسخه {0} منتشر شد"
  notes: "ببینید چه چیزی جدید است"
  downloads: "دانلودها"
  link: "https://releases.groupdocs.com/viewer/python-net/release-notes/latest/"

code:
  title: "رندر فایل‌های PDF در پایتون"
  more: "نمونه های بیشتر"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Python-via-.NET"
  install: "pip install groupdocs-viewer-net"
  content: |
    ```python {style=abap}
    import groupdocs.viewer as gv
    import groupdocs.viewer.options as gvo
    hvo = gvo.HtmlViewOptions  
  
    // تنظیم گزینه‌های خروجی HTML، یک فایل در هر صفحه
    with gv.Viewer("resume.docx") as viewer:
      // ایجاد نمونه اولیه نمایشگر
      opts = hvo.for_embedded_resources("page_{0}.html")

      // رندر PDF به HTML با منابع جاسازی شده
      viewer.view(opts)
    ```
############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Viewer در یک نگاه"
  description: "API برای رندر، نمایش، تبدیل اسناد، اسلایدها، نمودارها و بسیاری از انواع دیگر اسناد در برنامه های کاربردی پایتون"
  features:
    # feature loop
    - title: "اسناد را به طور کارآمد و قابل اعتماد مشاهده کنید"
      content: "با استفاده از GroupDocs.Viewer API می‌توانید اسناد با هر قالب پشتیبانی‌شده را به‌صورت کارآمد به [HTML](https://docs.groupdocs.com/viewer/python-net/rendering-to-html/)، JPEG، PNG و [PDF](https://docs.groupdocs.com/viewer/python-net/rendering-to-pdf/) رندر کنید؛ این کار با گزینه‌های انعطاف‌پذیر و قدرتمند انجام می‌شود و محتوا و ساختار سند حفظ می‌شود. GroupDocs.Viewer برای Python بر روی پلتفرم‌های Windows و Linux کار می‌کند."

    # feature loop
    - title: "پشتیبانی از محبوب‌ترین فرمت‌های فایل و سند"
      content: "ما بیش از ۱۸۰ فرمت فایل و سند پرکاربرد را پشتیبانی می‌کنیم که شامل [Word](https://docs.groupdocs.com/viewer/python-net/render-word-documents/)، [Excel](https://docs.groupdocs.com/viewer/python-net/specify-rendering-options/)، [PDF](https://docs.groupdocs.com/viewer/python-net/render-pdf-documents/)، [PowerPoint](https://docs.groupdocs.com/viewer/python-net/render-presentations/)، خانواده فرمت‌های OpenDocument، آرشیوها، تصاویر رستر و وکتور، کتاب‌های الکترونیکی، زبان‌ها و قالب‌های برنامه‌نویسی و بسیاری از انواع فایل‌های دیگر می‌شود، از جمله فایل‌های رمزگذاری‌شده با حفاظت رمزعبور."

    # feature loop
    - title: "خروجی قابل تنظیم"
      content: "GroupDocs.Viewer نه تنها رندر سند را امکان پذیر می کند، بلکه کنترل اینکه دقیقاً کدام قسمت های سند رندر شوند یا نشوند، چگونه رندر شوند و اعمال تحولات مختلف روی خروجی رندر شده را نیز امکان پذیر می کند."

############################# Platforms ############################
platforms:
  enable: true
  title: "استقلال از پلتفرم"
  description: "GroupDocs.Viewer برای پایتون از سیستم‌عامل‌ها، فریم‌ورک‌ها و مدیریت بسته‌های زیر پشتیبانی می‌کند"
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
    - title: "PyPI"
      image: "pypi"

############################# File formats ############################
formats:
  enable: true
  title: "فرمت های فایل پشتیبانی شده"
  description: |
    GroupDocs.Viewer برای پایتون از طریق .NET از عملیات با فرمت‌های فایل زیر پشتیبانی می‌کند: [لینک به فرمت‌های فایل پشتیبانی‌شده](https://docs.groupdocs.com/viewer/python-net/supported-document-formats/).
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
      title: "[مشاهده اسناد در HTML](https://docs.groupdocs.com/viewer/python-net/rendering-to-html/)"
      content: "هر نوع سندی را با CSS و SVG به یک سند HTML تبدیل کنید، که می تواند در هر مرورگر وب مدرن نمایش داده شود."

    # feature loop
    - icon: "rasterize"
      title: "[اسناد را شطرنجی کنید](https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Python-via-.NET/blob/master/Examples/basic_usage/render_document_to_image/render_to_png.py)"
      content: "هر قالب سند قابل پشتیبانی را با فرمت تصویر قابل تنظیم و کیفیت فشرده سازی به تصویر شطرنجی تبدیل کنید."

    # feature loop
    - icon: "font"
      title: "[کنترل فونت‌های سند](https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Python-via-.NET/blob/master/Examples/advanced_usage/rendering/common_rendering_options/replace_missing_font.py)"
      content: "فونت‌های استفاده شده در سند را شناسایی کنید. فونت‌های مفقود را با جایگزینی یا حذف از خروجی مدیریت کنید."

    # feature loop
    - icon: "convertpdf"
      title: "[تبدیل به PDF](https://docs.groupdocs.com/viewer/python-net/rendering-to-pdf/)"
      content: "سند با هر فرمت قابل پشتیبانی را می توان به راحتی با گزینه های قابل تنظیم به PDF تبدیل و ذخیره کرد."

    # feature loop
    - icon: "transform"
      title: "[تغییرات را اعمال کنید](https://docs.groupdocs.com/viewer/python-net/add-text-watermark/)"
      content: "سند خروجی را می توان در حین رندر تبدیل کرد - صفحات را می توان چرخاند و/یا مرتب کرد و واترمارک متنی در بالای آنها قرار داد."

    # feature loop
    - icon: "adjustment"
      title: "[تنظیم خروجی HTML](https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Python-via-.NET/blob/master/Examples/basic_usage/render_document_to_html/render_to_html_with_embedded_resources.py)"
      content: "اسناد HTML خروجی، تولید شده توسط GroupDocs.Viewer، را می توان بسیار دقیق تنظیم کرد: امکان ذخیره در جریان یا فایل، با منابع خارجی یا جاسازی شده، تماس های برگشتی و غیره وجود دارد."

    # feature loop
    - icon: "complex"
      title: "[پشتیبانی از ساختارهای پیچیده سند](https://docs.groupdocs.com/viewer/python-net/how-to-extract-and-save-attachments/)"
      content: "GroupDocs.Viewer نه تنها از اسناد منفرد، بلکه از فایل‌هایی نیز پشتیبانی می‌کند که در داخل شامل فهرست یا ساختار سلسله مراتبی از اسناد هستند، مانند پیام‌های ایمیل با پیوست‌ها، آرشیوهای ZIP با فایل‌های داخلی درون پوشه‌ها، تصاویر TIFF چند صفحه‌ای و غیره."

    # feature loop
    - icon: "optimization"
      title: "[گزینه های بهینه سازی](https://docs.groupdocs.com/viewer/python-net/caching-results/)"
      content: "GroupDocs.Viewer حاوی یک زیرسیستم کش قابل تنظیم است که می تواند با استفاده از نسخه های ذخیره شده اسناد، زمان بارگذاری را تسریع بخشد. همچنین مجموعه ای از گزینه های مختلف برای فرمت های مختلف اجازه می دهد تا برخی از بخش ها یا جنبه های غیر ضروری اسناد را از رندر حذف کنید (فونت ها، کاربرگ های مخفی، پیوست های ایمیل) برای بهینه سازی عملکرد کلی."

    # feature loop
    - icon: "passwordprotected"
      title: "[پشتیبانی از اسناد محافظت شده با رمز عبور](https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Python-via-.NET/blob/master/Examples/advanced_usage/loading/load_password_protected_document.py)"
      content: "GroupDocs.Viewer اجازه می دهد تا اسناد رمزگذاری شده را از انواع مختلف باز کنید: PDF، WordProcessing، Spreadsheet، Presentation و غیره، با تعیین رمز عبور در گزینه های بارگیری."

############################# Code samples ############################
code_samples:
  enable: true
  title: "نمونه های کد"
  description: "برخی از موارد استفاده از GroupDocs معمولی.بیننده برای پایتون از طریق. net عملیات"
  items:
    # code sample loop
    - title: "رندر DOCX به HTML"
      content: |
        ویژگی های کلاس `HtmlViewOptions` به شما امکان کنترل فرآیند تبدیل را می دهد. برای اطلاعات بیشتر، [اینجا](https://docs.groupdocs.com/viewer/python-net/rendering-to-html/) را ببینید. برای مثال، می توانید تمام منابع خارجی را در فایل خروجی HTML جاسازی کنید، فایل خروجی را به حداقل برسانید و آن را برای چاپ بهینه کنید.
        {{< landing/code title="Python">}}
        ```python {style=abap}
        import groupdocs.viewer as gv
        import groupdocs.viewer.options as gvo 

        // ایجاد نمونه از Viewer
        with gv.Viewer("resume.docx") as viewer:
          // تنظیم گزینه های خروجی HTML، یک فایل در هر صفحه
          viewOptions = gvo.HtmlViewOptions.for_embedded_resources("page_{0}.html")
          // رندر DOCX به HTML با منابع جاسازی شده
          viewer.view(viewOptions)
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "خروجی گرفتن PPTX به PDF"
      content: |
        یک نمونه از کلاس `PdfViewOptions` ایجاد کنید و آن را به متد `Viewer.view` برای تبدیل یک فایل پاورپوینت PPTX به PDF منتقل کنید. ویژگی های کلاس `PdfViewOptions` به شما امکان کنترل فرآیند تبدیل را می دهد. برای جزئیات بیشتر، بخش بعدی اسناد را در [اینجا](https://docs.groupdocs.com/viewer/python-net/rendering-to-pdf/) ببینید.
        {{< landing/code title="Python">}}
        ```python {style=abap}
        import groupdocs.viewer as gv
        import groupdocs.viewer.options as gvo  

        // ایجاد نمونه از Viewer
        with gv.Viewer("presentation.pptx") as viewer:
          // تنظیم گزینه های خروجی PDF
          viewOptions = gvo.PdfViewOptions("presentation.pdf")
          // خروجی گرفتن PPTX به PDF
          viewer.view(viewOptions)
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
