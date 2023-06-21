---
############################# Static ##########################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

lang: fa
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: "NET Document Viewer API, Render PDF Word Excel Image HTML Diagram"
head_description: "C# ASP.NET بیننده و API رندر فایل. نمایشگر PDF، نمایشگر Word، نمایشگر اکسل، نمایشگر تصویر، نمایشگر HTML، ویژگی های نمایش ایمیل را در برنامه های NET اضافه کنید."

############################# Header ##########################
title: "ارائه و نمایش اسناد از طریق NET API"
description: "NET Document Viewer API برای ارائه بیش از 190 فرمت سند به PDF، HTML و Image با گزینه های پیکربندی قدرتمند."
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Download Free Trial"
    link: "https://downloads.groupdocs.com/viewer/net"

############################# SubMenu #########################
submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Viewer for .NET"
        image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-viewer-net.png"
        product: "GroupDocs.Viewer"
        platform: ".NET"

    middle:
        button:
            # button loop
            - link: "#overview"
              text: "بررسی اجمالی"

            # button loop
            - link: "#features"
              text: "امکانات"

            # button loop
            - link: "#support"
              text: "حمایت کردن"

            # button loop
            - link: "https://products.groupdocs.app/viewer/total"
              text: "نسخه نمایشی زنده"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "قیمت گذاری"

    right:
        link_download: "https://releases.groupdocs.com/viewer/net/"
        link_learn: "https://docs.groupdocs.com/viewer/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    content: |
      GroupDocs.Viewer for. کتابخانه نمایشگر فایل، اسناد را شطرنجی‌سازی می‌کند و سپس آنها را به SVG+HTML+CSS تبدیل می‌کند تا تجربه کلی ارائه اسناد را برای مشاهده اسناد تجاری، تصاویر، فایل‌های متنی، نمودارها، گرافیک‌ها، پیوست‌های ایمیل و فایل‌های PDF با سرعت، متن واقعی و بهینه‌سازی کند. با وفاداری بالا در داخل برنامه های شما شما می‌توانید قابلیت‌های مشاهده و خواندن اسناد را در برنامه‌های خود اضافه کنید تا کل سند، سند جزئی، محدوده صفحه/سلول خاص، لایه سند مجزا، با یا بدون حاشیه‌نویسی و نظرات برای قالب‌های فایل پشتیبانی‌شده نمایش داده شود.
       
      GroupDocs.Viewer برای دات نت خروجی اسناد رندر شده را به طور پیش فرض در دیسک محلی ذخیره می کند. هر نوع حافظه کش خارجی نیز با پیاده سازی رابط های مناسب پشتیبانی می شود - Amazon S3، Dropbox، Google Drive، Windows Azure، Redis یا هر چیز دیگری.
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          در زیر یک نمای کلی از GroupDocs.Viewer برای دات نت ارائه شده است:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "بررسی اجمالی"
          content: |
            * نمایش بیش از 190 نوع سند 
            * دریافت فایل با فرمت HTML، Image، PDF 
            * چرخش و ترتیب مجدد 
            * واترمارک را اعمال کنید 
            * کش برای فرآیند سریع 
            * اضافه کردن فونت های سفارشی 
            * استانداردهای رمزگذاری را اعمال کنید 
            * کنترل کننده داده های ورودی سفارشی 
            * رندر با تغییرات آهنگ 
            * رندر به عنوان HTML پاسخگو 
            * لایه های PDF و CAD را رندر کنید 
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Viewer برای دات نت از مشاهده همه فرمت های فایل سند محبوب پشتیبانی می کند. تنها با چند خط کد، نمایشگر PDF، Microsoft Office Word، صفحه گسترده اکسل، تصویر، HTML، ایمیل Outlook، OneNote، پروژه و قابلیت‌های مشاهده گرافیک را در برنامه‌های NET خود اضافه کنید.

        left:
          enable: true
          table:
            # table loop
            - title: "Microsoft Office"
              content: |
                * **Word:** DOC, DOCX, DOCM, DOT, DOTX, DOTM, RTF, TXT
                * **Excel:** XLS, XLSX, XLSM, XLSB, XLTM, XLT, XLTM, XLTX, XLAM, SXC, SpreadsheetML
                * **PowerPoint:** PPT, PPTX, PPS, PPSX, PPSM, POT, POTM, POTX, PPTM
                * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
                * **Project:** MPP, MPT, MPX
                * **Outlook:** MSG, EML, EMLX, PST, OST
                * **OneNote:** ONE

            # table loop
            - title: "Other Formats"
              content: |
                * **فایل های طرح بندی صفحه:** PDF, TEX, XPS, OXPS
                * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG, OTG, FODP, FODG
                * **مقادیر جدا شده از جداکننده:** CSV, TSV
                * **وب:** HTML, MHT, MHTML
                * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
                * **PostScript:** PS, EPS
                * **آرشیوها:** ZIP, TAR, BZ2, GZ, RAR, RAR5
                * **مختلف:** OBJ, EPUB, MOBI, DjVu, XML, VCF, VCARD, NUMBERS, NSF

        right:
          enable: true
          table:
            # table loop
            - title: "تصاویر، گرافیک و نمودارها"
              content: |
                * **تصاویر:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB
                * **آیکون ویندوز:** ICO
                * **گرافیک برداری مقیاس پذیر:** SVG, CDR, CMX, IGS, SVGZ
                * **Jpeg2000:** JP2, J2C, J2K, JPC, JPF, JPX, JPM
                * **فتوشاپ:** PSD, PSB
                * **زبان دستور چاپگر:** PCL
                * **لیتوگرافی استریو (چاپ سه بعدی):** STL
                * **کلاس های بنیاد صنعت:** IFC
                * **تصویربرداری پزشکی:** DICOM
                * **اسناد پلاتر:** PLT, HPG
                * **فرمت های وب طراحی اتودسک:** DWF, DWG
                * **طراحی اتوکد:** DWT, IFC, STL, CF2
                * **DGN مبتنی بر ISFF (V7):** DGN

            # table loop
            - title: "فرمت های زبان های برنامه نویسی"
              content: |
                * **فایل های C/C++/C#:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
                * **فایل های جاوا/جاوا اسکریپت:** JAVA, JS, JSON, PROPERTIES
                * **مختلف:** VB, PHP, SQL, PL, PY, PV, RB, RST, SASS, SCALA, SCM, SCRIPT, AS, AS3, ASM, BAT, CMAKE, CSS, DIFF, ERB, GROOVY, HAML, LESS, LOG, M, MAKE, MD, ML, MM, SH, SML, VIM, YAML

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Viewer برای دات نت از سیستم عامل ها، فریم ورک ها و مدیران بسته زیر پشتیبانی می کند:
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "سیستم های عامل"
              content: |
                * مایکروسافت ویندوز سرور 2003 به بعد 
                * مایکروسافت ویندوز XP و جدیدتر 
                * مایکروسافت ویندوز 10 و 11 
                * لینوکس (Ubuntu، OpenSUSE، CentOS و دیگران) 
                * Mac OS X 

            # table loop
            - icon: "fas fa-code"
              title: "چارچوب های پشتیبانی شده"
              content: |
                * NET Framework 2.0 یا بالاتر 
                * NET Core 3.1 
                * دات نت 5 یا بالاتر 

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-box"
              title: "مدیر بسته"
              content: |
                * NuGet

            # table loop
            - icon: "fas fa-tools"
              title: "محیط های توسعه"
              content: |
                * Microsoft Visual Studio
                * Visual Studio Code
                * .NET CLI

############################# Features ############################
features:
    enable: true
    title: "GroupDocs.Viewer برای ویژگی های NET"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "اسناد را شطرنجی کنید و آنها را به SVG، HTML و CSS تبدیل کنید"

      # feature loop
      - icon: "fas fa-eye"
        content: "تبدیل متن به HTML و رندر اسناد برای دریافت نمایش HTML، تصویر یا PDF"

      # feature loop
      - icon: "fas fa-bolt"
        content: "زمان بارگذاری سریعتر با استفاده از نسخه های ذخیره شده اسناد"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "ارائه ها را با اشکال و متن با جلوه های سه بعدی تبدیل کنید"

      # feature loop
      - icon: "fas fa-code"
        content: "اسناد ورد، اکسل و ایمیل را به استاندارد رمزگذاری مورد نظر رمزگذاری کنید"

      # feature loop
      - icon: "fas fa-cloud"
        content: "رندر اسناد واقع در مکان های FTP یا Cloud Storage"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "حذف فونت ها هنگام ارائه به HTML برای کاهش اندازه فایل نتیجه"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "با حذف نظرات، فضاهای سفید اضافی و غیره، خروجی CSS و HTML را کوچک کنید."

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "متن موجود در یک سند منبع را از طریق مختصات آن بخوانید"

      # feature loop
      - icon: "fas fa-border-all"
        content: "نمایش/پنهان کردن خطوط شبکه صفحات اکسل در نمایش خروجی"

      # feature loop
      - icon: "fas fa-wrench"
        content: "تعداد ردیف‌هایی را در یک برگه اکسل که در هر صفحه ارائه می‌شود، مشخص کنید"

      # feature loop
      - icon: "fas fa-columns"
        content: "هنگام ارائه اسناد صفحه گسترده، ستون های خالی را نادیده بگیرید"

      # feature loop
      - icon: "fas fa-file-word"
        content: "اسناد ورد را به صفحات HTML، تصاویر یا PDF، با تغییرات ردیابی، رندر کنید"

      # feature loop
      - icon: "fas fa-envelope"
        content: "پیوست های ایمیل را به صورت فایل های اصلی، تصاویر یا در نمایش HTML ارائه دهید"

      # feature loop
      - icon: "fas fa-print"
        content: "محدودیت های چاپ را روی اسناد PDF تنظیم کنید"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "محتوا/فایل های موجود در آرشیو ZIP را به عنوان پیوست ارائه کنید"

      # feature loop
      - icon: "fas fa-lock"
        content: "پیوست ها را از اسناد محافظت شده با رمز عبور دریافت کنید"

      # feature loop
      - icon: "fas fa-file-code"
        content: "فرمت های فایل زبان های برنامه نویسی را به صورت متن ساده ارائه دهید"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "هنگام مشاهده نقشه های CAD، رنگ های پس زمینه را تنظیم کنید"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "اسناد اکسل را مشاهده کنید و به PDF، HTML، JPG و PNG تبدیل کنید"

      # feature loop
      - icon: "fas fa-heading"
        content: "دریافت نام کاربرگ ها از فایل اکسل – نمایش عناوین ستون ها و شماره ردیف های صفحه گسترده"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "مشاهده و تبدیل اسناد پروژه مایکروسافت با یادداشت ها"

      # feature loop
      - icon: "fas fa-cube"
        content: "برای مشاهده و زوم کردن بهتر، نقشه های CAD را به SVG تبدیل کنید"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "رندر ارقام Visio بدون طرح را انتخاب کنید"

    more_feature:
      # more_feature_loop
      - title: "اسناد را کارآمد و قابل اعتماد مشاهده کنید"
        content: |
          با استفاده از GroupDocs.Viewer API می توانید بیش از 190 فرمت سند را به طور موثر و قابل اعتماد با یکپارچگی ساختار محتوا و سند نمایش دهید. کد نمونه زیر نشان می دهد که مشاهده نمایش HTML یک سند DOCX چقدر آسان است:

          ```cs
          // Instantiate viewer
          using (Viewer viewer = new Viewer("invoice.docx"))
          {
              // Set view options
              HtmlViewOptions options = HtmlViewOptions.ForEmbeddedResources();
              // Convert file to HTML with embedded resources
              viewer.View(options);
          }
          ```
      # more_feature_loop
      - title: "Transformation را در خروجی رندر شده اعمال کنید"
        content: "می‌توانید با استفاده از GroupDocs.Viewer برای NET API، تبدیل‌های مختلفی را در سند خروجی ارائه‌شده انجام دهید. این گزینه های تبدیل به شما امکان کنترل نحوه ارائه خروجی رندر شده برای نمایش را می دهد. تبدیل های موجود عبارتند از، گزینه چرخش صفحه، گزینه ترتیب مجدد صفحه و اعمال واترمارک متن."

      # more_feature_loop
      - title: "کار با فایل های داده Outlook"
        content: "GroupDocs.Viewer for .NET API می‌تواند موارد موجود در فایل‌های داده Outlook (OST/PST) را به صورت فایل‌های PDF، HTML و Image ارائه کند. Viewer API ما همچنین توانایی به دست آوردن لیست پوشه های موجود در Outlook Data Files را دارد. با استفاده از GroupDocs.Viewer برای NET API، می‌توانید پوشه‌ای را برای رندر کردن از Outlook Data Files مشخص کنید. به همین ترتیب، شما همچنین می توانید پیام های ایمیل موجود در فرمت های OST/PST را به عنوان پیوست دریافت کنید. GroupDocs.Viewer برای دات نت همچنین به شما امکان می دهد پیام ها را از فرمت های OST/PST بر اساس موضوع، محتوا یا فرستنده فیلتر کنید."

      # more_feature_loop
      - title: "کار با اسناد CAD"
        content: "GroupDocs.Viewer for .NET API می تواند مدل و همه طرح بندی های غیر خالی را رندر کند یا یک طرح بندی خاص از یک فایل CAD را ارائه دهد. GroupDocs.Viewer for .NET API همچنین از رندر یا رندر کردن با مختصات اسناد CAD به تصویر، HTML یا PDF پشتیبانی می کند. همچنین می توانید وضعیت لایه ها را برای اسناد CAD بدست آورید."

############################# Testimonials ###############################
testimonials:
  enable: true

  testimonial:
    # testimonial item loop
    - name: "Margot Baill"
      designation: "مدیر توسعه محصول در Hireology"
      content: "ادغام GroupDocs.Viewer برای Cloud API با Ruby SDK خارق العاده آنها ساده بود. شرکت های زیادی وجود ندارند که مایل به همکاری با ما در مورد آنچه ما می خواهیم باشند. این یک مشارکت عالی است."

    # testimonial item loop
    - name: "Mats Oustad"
      designation: "مشاور ارشد/شریک در Novanet AS"
      content: "پس از پیاده سازی و استفاده از GroupDocs.Viewer برای دات نت در پروژه، به نظر می رسد که بسیار خوب کار می کند. من با مدارک زیادی تست کردم و تا الان خیلی خوبه. همه چیزهایی که به آن پرتاب کرده‌ام به خوبی رندر می‌شوند و به همان خوبی که در یک نمایشگر PDF یا MS Word ظاهر می‌شوند، خوب به نظر می‌رسند."
              
    # testimonial item loop
    - name: "Martin Lasarga"
      designation: "مدیر محصول در Axentria ECM توسط G.S.I."
      content: "خدمات عالی و محصولات عالی. آنها در طول فرآیند اجرای GroupDocs.Viewer برای دات نت بسیار مفید و پاسخگو بودند، نمی توان آنها را به اندازه کافی توصیه کرد."

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Viewer API های مشاهده اسناد را برای سایر محیط های توسعه محبوب ارائه می دهد"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Viewer for Java"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-viewer-java.png"
          product: "GroupDocs.Viewer"
          platform: "Java"
          link: "/viewer/java/"

############################# Back to top ###############################
back_to_top:
  enable: true
---
