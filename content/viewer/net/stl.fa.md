---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: fa

############################# Head #############################
head_title: ".NET STL API نمایشگر - خواندن، مشاهده، رندر در سی شارپ VB.NET"
head_description: "API نمایشگر اسناد NET برای خواندن، رندر و نمایش STL در هر نوع برنامه‌های C#، ASP.NET، VB.NET و NET Core."

############################# Header ############################
title: "STL نمایشگر فایل برای برنامه های C# .NET" 
description: ".NET document viewer API برای خواندن، رندر و نمایش فایل STL در هر نوع برنامه های C#، ASP.NET، VB.NET و NET Core. فایل های رندر شده را با قالب بندی و چیدمان واقعی در HTML5، PDF یا به صورت تصویر با استفاده از چند خط کد مشاهده کنید." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "دانلود آزمایشی رایگان"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "درباره GroupDocs.Viewer برای NET API" 
    content: |
        با افزودن چند خط کد، با استفاده از GroupDocs.Viewer برای API های NET، بیش از 190 فرمت سند محبوب را در برنامه های NET خود مشاهده کنید. توسعه دهندگان به راحتی می توانند PDF، Word Processing، Excel Spreadsheet، Presentation، Visio، Project، Outlook و بسیاری دیگر از فرمت های سند محبوب را در حالت های HTML5، تصویر یا PDF نمایش دهند. رندر سند سریع و مشابه فایل منبع اصلی است و نیازی به نصب نرم افزار اضافی یا کتابخانه های خارجی دیگر ندارد.

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
    title_left: "مراحل ارائه فایل STL در C#" 
    content_left: |
        با [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/) می‌توانید STL را در چند مرحله به HTML، JPEG، PNG یا PDF تبدیل کنید.

        * [GroupDocs.Viewer for .NET](https://www.nuget.org/packages/groupdocs.viewer) را با استفاده از مدیر بسته مورد علاقه خود نصب کنید. 
        * یک نمونه از کلاس Viewer ایجاد کنید و فایل STL را با مسیر کامل بارگذاری کنید. 
        * گزینه هایی را برای رندر کردن فایل STL در قالب HTML، PNG، JPEG یا PDF تنظیم کنید. 
        * فایل را رندر کنید و خروجی را در دایرکتوری فعلی بررسی کنید. 
        
    title_right: "سیستم مورد نیاز" 
    content_right: |
        GroupDocs.Viewer برای API های دات نت در تمام سیستم عامل ها و سیستم عامل های اصلی پشتیبانی می شود. لطفا قبل از اجرای کد زیر، از نصب پیش نیازهای زیر بر روی سیستم خود اطمینان حاصل کنید.

        * سیستم عامل: مایکروسافت ویندوز، لینوکس، MacOS 
        * محیط های توسعه: Microsoft Visual Studio، Visual Studio Code، NET CLI 
        * فریم‌ورک‌ها: NET Framework، NET Standard، NET Core، .NET 
    code: |
        ```cs
                        
            // Set up input STL file
            string filePath = "input.stl";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render STL file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "STL نمایشگر زنده"
    content: |
        فایل STL را هم اکنون با بازدید از وب سایت [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/stl) مشاهده کنید.
    lang: "fa"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "سایر فرمت‌های فایل رندر و مشاهده با استفاده از C#"
    exclude: "STL"
    content: |
        API نمایشگر اسناد و تصاویر چند فرمتی برای دات نت. برخی از قالب‌های فایل محبوب را در زیر بدون هیچ بیننده خارجی مشاهده کنید.
    format: 
        # format loop 1
        - name: "DOCX را رندر کنید"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word Open XML Document" 

        # format loop 2
        - name: "CDR را رندر کنید" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "فایل کورل دراو" 

        # format loop 3
        - name: "رندر PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "پاورپوینت ارائه XML را باز کنید" 

        # format loop 4
        - name: "رندر XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "مایکروسافت اکسل صفحه گسترده XML را باز کنید" 

        # format loop 5
        - name: "رندر DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "طراحی اتوکد"

        # format loop 6
        - name: "XML را رندر کنید"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "فایل XML"

        # format loop 7
        - name: "رندر PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "سند Adobe Photoshop"

        # format loop 8
        - name: "فایل Adobe Illustrator را رندر کنید"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "آثار هنری Adobe Illustrator"

        # format loop 9
        - name: "DOC را رندر کنید"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "سند مایکروسافت ورد" 

        # format loop 10
        - name: "رندر TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "فایل متنی ساده" 

        # format loop 11
        - name: "رندر DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "در حال ترسیم فایل فرمت تبادل"  
          
        # format loop 12
        - name: "VCF را رندر کنید"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "فایل کارت مجازی"  
              
        # format loop 13
        - name: "رندر SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "گرافیک برداری مقیاس پذیر" 
          
        # format loop 14
        - name: "HTML را رندر کنید"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "فایل زبان نشانه گذاری فرامتن" 
          
        # format loop 15
        - name: "رندر PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "فایل فرمت سند قابل حمل"
          
        # format loop 16
        - name: "رندر JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "تصویر JPEG"
          
        # format loop 17
        - name: "رندر PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "گرافیک شبکه قابل حمل" 
          
        # format loop 18
        - name: "EML را رندر کنید"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "پیام ایمیل" 
          
        # format loop 19
        - name: "رندر RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "فایل با فرمت متن غنی" 
          
        # format loop 20
        - name: "ODT را رندر کنید"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "سند متنی OpenDocument" 
          
        # format loop 21
        - name: "CSV را رندر کنید"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "فایل مقادیر جدا شده با کاما" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
