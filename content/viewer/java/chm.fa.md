---
############################# Static ############################
layout: "format"
date: 2024-03-19T07:00:45
draft: false
lang: fa
product: "Viewer"
product_tag: "viewer"
platform: "Java"
platform_tag: "java"

############################# Head #############################
head_title: "Java CHM Viewer API - رندر و نمایش CHM در برنامه‌های جاوا"
head_description: "فایل‌های CHM را در برنامه‌های Java، J2EE، J2SE مشاهده کنید. از مشاهده بیش از 180 فرمت سند و فایل تصویر در حالت HTML، PDF یا تصویر با ویژگی های پیشرفته برای مدیریت گزینه های مشاهده اسناد پشتیبانی می کند."

############################# Header ############################
title: "رندر و مشاهده CHM در جاوا" 
description: "API نمایشگر فایل بومی و با کارایی بالا CHM برای برنامه‌های مبتنی بر جاوا، J2EE و J2SE، که از طیف گسترده‌ای از ویژگی‌های اضافی برای سفارشی‌سازی ظاهر قالب سند خروجی پشتیبانی می‌کند." 
subtitle: "راه حل ارائه سند" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "دانلود رایگان Maven"
      link: "https://releases.groupdocs.com/viewer/java/"



############################# About ############################
about:
    enable: true
    title: "درباره GroupDocs.Viewer for Java API"
    link: "/viewer/java/"
    link_title: "بیشتر بدانید"
    picture: "about_viewer.svg" # 480 X 400
    content: |
      برنامه های جاوا خود را فعال کنید تا بیش از 180 فرمت فایل را در حالت های HTML، PDF یا تصویر با استفاده از GroupDocs.Viewer برای API های جاوا بدون نصب نرم افزار اضافی نمایش دهند. مانند مایکروسافت آفیس، آپاچی اوپن آفیس، Adobe Acrobat Reader و غیره. توسعه دهندگان به راحتی می توانند تمام تصاویر و انواع اسناد محبوب از جمله Microsoft Office، OpenDocument، HTML، PDF، Archive، Diagrams، Photoshop، AutoCAD و فرمت های زبان برنامه نویسی را در داخل برنامه های جاوا مشاهده کنند. رندر سریع و با کیفیت



############################# Steps ############################
steps:
    enable: true
    title: "مراحل ارائه فایل CHM در Java" 
    content: |
      با <a href='https://products.groupdocs.com/viewer/java/'>GroupDocs.Viewer</a> می‌توانید CHM را در چند مرحله به HTML، JPEG، PNG یا PDF تبدیل کنید.
      
      1. <a href='https://releases.groupdocs.com/viewer/java/'>GroupDocs.Viewer برای جاوا</a> را به عنوان وابستگی به پروژه خود اضافه کنید. 
      2. یک نمونه از کلاس Viewer ایجاد کنید و فایل CHM را با مسیر کامل بارگذاری کنید.  
      3. گزینه هایی را برای رندر کردن فایل CHM در قالب HTML، PNG، JPEG یا PDF تنظیم کنید. 
      4. فایل را رندر کنید و خروجی را در دایرکتوری فعلی بررسی کنید. 
   
    code:
      platform: "java"
      copy_title: "کپی 🀄"
      install:
        command: |
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
        copy_tip: "برای کپی کلیک کنید"
        copy_done: "کپی شده است"
      links:
        #  loop
        - title: "نمونه های بیشتر"
          link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Java"
        #  loop
        - title: "مستندات"
          link: "https://docs.groupdocs.com/viewer/java/"
          
      content: |
        ```java {style=abap}

        // فایل ورودی CHM را تنظیم کنید
        String filePath = "input.chm";

        // Instantiate GroupDocs.Viewer
        try (Viewer viewer = new Viewer(filePath))
        {
            // گزینه های مشاهده را تنظیم کنید
            HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                
            // فایل CHM را با منابع جاسازی شده به HTML ارائه دهید
            viewer.view(viewOptions);
        }

        ```
            

############################# Actions ############################

actions:
  enable: true
  title: "برای شروع آماده اید؟"
  description: "ویژگی های GroupDocs.Viewer را به صورت رایگان امتحان کنید یا درخواست مجوز کنید"
  items:
    #  loop
    - title: "Maven دانلود"
      link: "https://releases.groupdocs.com/viewer/java/"
      color: "red"
        #  loop
    - title: "صدور مجوز"
      link: "https://purchase.groupdocs.com/pricing/viewer/java/"
      color: "light"



############################# More Formats #####################
more_formats:
    enable: true
    title: "سایر قالب‌های فایل را با استفاده از Java رندر کنید"
    exclude: "CHM"
    description: "API نمایشگر اسناد و تصاویر چند فرمت برای جاوا. برخی از قالب‌های فایل محبوب را در زیر بدون هیچ بیننده خارجی مشاهده کنید."
    items: 
        # format loop 1
        - name: "DOCX را رندر کنید"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Open XML Document" 

        # format loop 2
        - name: "CDR را رندر کنید" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "CorelDRAW File" 

        # format loop 3
        - name: "رندر PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint Open XML Presentation" 

        # format loop 4
        - name: "رندر XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet" 

        # format loop 5
        - name: "رندر DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "AutoCAD Drawing"

        # format loop 6
        - name: "XML را رندر کنید"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "XML File"

        # format loop 7
        - name: "رندر PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Adobe Photoshop Document"

        # format loop 8
        - name: "رندر هوش مصنوعی"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Adobe Illustrator Artwork"

        # format loop 9
        - name: "DOC را رندر کنید"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Microsoft Word Document" 

        # format loop 10
        - name: "رندر TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Plain Text File" 

        # format loop 11
        - name: "رندر DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Drawing Exchange Format File"  
          
        # format loop 12
        - name: "VCF را رندر کنید"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "vCard File"  
              
        # format loop 13
        - name: "رندر SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Scalable Vector Graphic" 
          
        # format loop 14
        - name: "HTML را رندر کنید"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "رندر PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Portable Document Format File"
          
        # format loop 16
        - name: "رندر JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "JPEG Image"
          
        # format loop 17
        - name: "رندر PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Portable Network Graphic" 
          
        # format loop 18
        - name: "EML را رندر کنید"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "E-Mail Message" 
          
        # format loop 19
        - name: "RTF را رندر کنید"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Rich Text Format File" 
          
        # format loop 20
        - name: "ODT را رندر کنید"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "OpenDocument Text Document" 
          
        # format loop 21
        - name: "CSV را رندر کنید"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Comma-Separated Values File" 


---
