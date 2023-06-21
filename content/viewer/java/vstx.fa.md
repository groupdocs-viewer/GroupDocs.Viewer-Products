---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: fa

############################# Head #############################
head_title: "Java VSTX Viewer API - رندر و نمایش VSTX در برنامه‌های جاوا"
head_description: "فایل‌های VSTX را در برنامه‌های Java، J2EE، J2SE مشاهده کنید. از مشاهده بیش از 170 فرمت سند و فایل تصویر در حالت HTML، PDF یا تصویر با ویژگی های پیشرفته برای مدیریت گزینه های مشاهده اسناد پشتیبانی می کند."

############################# Header ############################
title: "رندر و مشاهده VSTX در جاوا" 
description: "API نمایشگر فایل بومی و با کارایی بالا VSTX برای برنامه های کاربردی مبتنی بر جاوا، J2EE و J2SE، از طیف گسترده ای از ویژگی های اضافی برای سفارشی کردن ظاهر قالب سند خروجی پشتیبانی می کند." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "دانلود آزمایشی رایگان"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "درباره GroupDocs.Viewer for Java API" 
    content: |
        برنامه های جاوا خود را فعال کنید تا بیش از 170 فرمت فایل را در حالت های HTML، PDF یا تصویر با استفاده از GroupDocs.Viewer برای API های جاوا بدون نصب نرم افزار اضافی نمایش دهند. مانند مایکروسافت آفیس، آپاچی اوپن آفیس، ادوبی آکروبات ریدر و غیره. توسعه دهندگان می توانند به راحتی تمامی تصاویر و انواع اسناد محبوب از جمله مایکروسافت آفیس، OpenDocument، HTML، PDF، آرشیو، نمودارها، فتوشاپ، اتوکد و فرمت های زبان برنامه نویسی را در داخل برنامه های جاوا مشاهده کنند. رندر سریع و با کیفیت

############################# SubMenu ############################
submenu:
    enable: true

    left:
        img_alt: "GroupDocs.Viewer for .NET"
        image: "https://cms.admin.containerize.com/templates/groupdocs/images/product-logos/90x90-noborder/groupdocs-viewer-net.png"
        product: "GroupDocs.Viewer"
        platform: ".NET"

    middle:
        button:

            # button loop
            - link: "https://apireference.groupdocs.com/viewer/net"
              text: "مرجع API"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "نمونه های کد"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "دموهای زنده"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "قیمت گذاری"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "مراحل رندر فایل VSTX در Java" 
    content_left: |
        با [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/) می‌توانید VSTX را در چند مرحله به HTML، JPEG، PNG یا PDF تبدیل کنید.

        * [GroupDocs.Viewer for Java](https://releases.groupdocs.com/viewer/java/) را به عنوان یک وابستگی به پروژه خود اضافه کنید. 
        * یک نمونه از کلاس Viewer ایجاد کنید و فایل VSTX را با مسیر کامل بارگذاری کنید. 
        * گزینه هایی را برای رندر کردن فایل VSTX در قالب HTML، PNG، JPEG یا PDF تنظیم کنید. 
        * فایل را رندر کنید و خروجی را در دایرکتوری فعلی بررسی کنید. 
        
    title_right: "سیستم مورد نیاز" 
    content_right: |
        GroupDocs.Viewer برای API های جاوا در همه سیستم عامل ها و سیستم عامل های اصلی پشتیبانی می شود. لطفا قبل از اجرای کد زیر، از نصب پیش نیازهای زیر بر روی سیستم خود اطمینان حاصل کنید.

        * سیستم عامل: مایکروسافت ویندوز، لینوکس، MacOS 
        * محیط های توسعه: NetBeans، IntelliJ IDEA، Eclipse و غیره. 
        * چارچوب: J2SE 8.0 (1.8) یا بالاتر (به عنوان مثال جاوا 17) 
    code: |
        ```java
                        
            // Set up input VSTX file
            String filePath = "input.vstx";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render VSTX file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "VSTX نمایشگر زنده"
    content: |
        فایل VSTX را هم اکنون با بازدید از وب سایت [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/vstx) مشاهده کنید.
    lang: "fa"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "سایر قالب‌های فایل رندر و مشاهده با استفاده از Java"
    exclude: "VSTX"
    content: |
        API نمایشگر اسناد و تصاویر چند فرمت برای جاوا. برخی از قالب‌های فایل محبوب را در زیر بدون هیچ بیننده خارجی مشاهده کنید.
    format: 
        # format loop 1
        - name: "DOCX را رندر کنید"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Open XML Document" 

        # format loop 2
        - name: "CDR را رندر کنید" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "فایل کورل دراو" 

        # format loop 3
        - name: "رندر PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "پاورپوینت ارائه XML را باز کنید" 

        # format loop 4
        - name: "رندر XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "مایکروسافت اکسل صفحه گسترده XML را باز کنید" 

        # format loop 5
        - name: "رندر DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "طراحی اتوکد"

        # format loop 6
        - name: "XML را رندر کنید"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "فایل XML"

        # format loop 7
        - name: "رندر PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "سند Adobe Photoshop"

        # format loop 8
        - name: "فایل Adobe Illustrator را رندر کنید"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "آثار هنری Adobe Illustrator"

        # format loop 9
        - name: "DOC را رندر کنید"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "سند مایکروسافت ورد" 

        # format loop 10
        - name: "رندر TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "فایل متنی ساده" 

        # format loop 11
        - name: "رندر DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "در حال ترسیم فایل فرمت تبادل"  
          
        # format loop 12
        - name: "VCF را رندر کنید"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "فایل کارت مجازی"  
              
        # format loop 13
        - name: "رندر SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "گرافیک برداری مقیاس پذیر" 
          
        # format loop 14
        - name: "HTML را رندر کنید"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "فایل زبان نشانه گذاری فرامتن" 
          
        # format loop 15
        - name: "رندر PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "فایل فرمت سند قابل حمل"
          
        # format loop 16
        - name: "رندر JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "تصویر JPEG"
          
        # format loop 17
        - name: "رندر PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "گرافیک شبکه قابل حمل" 
          
        # format loop 18
        - name: "EML را رندر کنید"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "پیام ایمیل" 
          
        # format loop 19
        - name: "رندر RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "فایل با فرمت متن غنی" 
          
        # format loop 20
        - name: "ODT را رندر کنید"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "سند متنی OpenDocument" 
          
        # format loop 21
        - name: "CSV را رندر کنید"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "فایل مقادیر جدا شده با کاما" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
