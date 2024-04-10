---
############################# Static ############################
layout: "format"
date: 2024-04-10T13:10:15
draft: false
lang: fa
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head #############################
head_title: ".NET XLT بیننده API - خواندن، مشاهده، رندر در C# VB.NET"
head_description: "API نمایشگر اسناد NET برای خواندن، رندر و نمایش XLT در هر نوع برنامه‌های C#، ASP.NET، VB.NET و NET Core."

############################# Header ############################
title: "نمایشگر فایل XLT برای برنامه های C# .NET" 
description: ".NET document viewer API برای خواندن، رندر و نمایش فایل XLT در هر نوع برنامه های C#، ASP.NET، VB.NET و NET Core. فایل های رندر شده را با قالب بندی و چیدمان واقعی در HTML5، PDF یا به صورت تصویر با استفاده از چند خط کد مشاهده کنید." 
subtitle: "راه حل ارائه سند" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "دانلود رایگان Nuget"
      link: "https://nuget.org/packages/GroupDocs.Viewer"



############################# About ############################
about:
    enable: true
    title: "درباره GroupDocs.Viewer برای NET API"
    link: "/viewer/net/"
    link_title: "بیشتر بدانید"
    picture: "about_viewer.svg" # 480 X 400
    content: |
      با افزودن چند خط کد، با استفاده از GroupDocs.Viewer برای API های NET، بیش از 190 قالب سند محبوب را در برنامه های NET خود مشاهده کنید. توسعه دهندگان به راحتی می توانند PDF، Word Processing، Excel Spreadsheet، Presentation، Visio، Project، Outlook و بسیاری دیگر از فرمت های سند محبوب را در حالت های HTML5، تصویر یا PDF نمایش دهند. رندر سند سریع، مشابه فایل منبع اصلی است و نیازی به نصب نرم افزار اضافی یا کتابخانه های خارجی دیگر ندارد.



############################# Steps ############################
steps:
    enable: true
    title: "مراحل ارائه فایل XLT در C#" 
    content: |
      با <a href='https://products.groupdocs.com/viewer/net/'>GroupDocs.Viewer</a> می‌توانید XLT را در چند مرحله به HTML، JPEG، PNG یا PDF تبدیل کنید.
      
      1. با استفاده از مدیر بسته مورد علاقه خود، <a href='https://www.nuget.org/packages/groupdocs.viewer'>GroupDocs.Viewer را برای دات نت</a> نصب کنید. 
      2. یک نمونه از کلاس Viewer ایجاد کنید و فایل XLT را با مسیر کامل بارگذاری کنید.  
      3. گزینه هایی را برای رندر کردن فایل XLT در قالب HTML، PNG، JPEG یا PDF تنظیم کنید. 
      4. فایل را رندر کنید و خروجی را در دایرکتوری فعلی بررسی کنید. 
   
    code:
      platform: "net"
      copy_title: "کپی 🀄"
      install:
        command: "dotnet add package GroupDocs.Viewer"
        copy_tip: "برای کپی کلیک کنید"
        copy_done: "کپی شده است"
      links:
        #  loop
        - title: "نمونه های بیشتر"
          link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
        #  loop
        - title: "مستندات"
          link: "https://docs.groupdocs.com/viewer/net/"
          
      content: |
        ```csharp {style=abap}

        // فایل ورودی XLT را تنظیم کنید
        string filePath = "input.xlt";

        // Instantiate GroupDocs.Viewer
        using (Viewer viewer = new Viewer(filePath))
        {
            // گزینه های مشاهده را تنظیم کنید
            HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                
            // فایل XLT را با منابع جاسازی شده به HTML ارائه دهید
            viewer.View(viewOptions);
        }

        ```            


############################# Actions ############################

actions:
  enable: true
  title: "برای شروع آماده اید؟"
  description: "ویژگی های GroupDocs.Viewer را به صورت رایگان امتحان کنید یا درخواست مجوز کنید"
  items:
    #  loop
    - title: "دانلود Nuget"
      link: "https://nuget.org/packages/GroupDocs.Viewer"
      color: "red"
        #  loop
    - title: "صدور مجوز"
      link: "https://purchase.groupdocs.com/pricing/viewer/net/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "سایر قالب‌های فایل را با استفاده از C# رندر کنید"
    exclude: "XLT"
    description: "API نمایشگر اسناد و تصاویر چند فرمتی برای دات نت. برخی از قالب‌های فایل محبوب را در زیر بدون هیچ بیننده خارجی مشاهده کنید."
    items: 
        # format loop 1
        - name: "DOCX را رندر کنید"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word Open XML Document" 

        # format loop 2
        - name: "CDR را رندر کنید" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "CorelDRAW File" 

        # format loop 3
        - name: "رندر PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint Open XML Presentation" 

        # format loop 4
        - name: "رندر XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet" 

        # format loop 5
        - name: "رندر DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "AutoCAD Drawing"

        # format loop 6
        - name: "XML را رندر کنید"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "XML File"

        # format loop 7
        - name: "رندر PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Adobe Photoshop Document"

        # format loop 8
        - name: "رندر هوش مصنوعی"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Adobe Illustrator Artwork"

        # format loop 9
        - name: "DOC را رندر کنید"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Microsoft Word Document" 

        # format loop 10
        - name: "رندر TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Plain Text File" 

        # format loop 11
        - name: "رندر DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Drawing Exchange Format File"  
          
        # format loop 12
        - name: "VCF را رندر کنید"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "vCard File"  
              
        # format loop 13
        - name: "رندر SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Scalable Vector Graphic" 
          
        # format loop 14
        - name: "HTML را رندر کنید"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "رندر PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Portable Document Format File"
          
        # format loop 16
        - name: "رندر JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "JPEG Image"
          
        # format loop 17
        - name: "رندر PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Portable Network Graphic" 
          
        # format loop 18
        - name: "EML را رندر کنید"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "E-Mail Message" 
          
        # format loop 19
        - name: "RTF را رندر کنید"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Rich Text Format File" 
          
        # format loop 20
        - name: "ODT را رندر کنید"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "OpenDocument Text Document" 
          
        # format loop 21
        - name: "CSV را رندر کنید"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Comma-Separated Values File" 



---
