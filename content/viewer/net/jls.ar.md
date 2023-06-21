---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: ar

############################# Head #############################
head_title: ".NET JLS Viewer API - قراءة وعرض وعرض في C # VB.NET"
head_description: ".NET document viewer API لقراءة وعرض وعرض JLS في أي نوع من تطبيقات C # و ASP.NET و VB.NET و .NET Core."

############################# Header ############################
title: "JLS عارض الملفات لتطبيقات C # .NET" 
description: ".NET document viewer API لقراءة وعرض وعرض ملف JLS في أي نوع من تطبيقات C # و ASP.NET و VB.NET و .NET Core. اعرض الملفات المعروضة بتنسيق وتخطيط صحيحين بتنسيق HTML5 أو PDF أو كصورة باستخدام بضعة أسطر من الكود." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "تحميل النسخة التجريبية المجانية"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "حول GroupDocs.Viewer for .NET API" 
    content: |
        ابدأ في عرض أكثر من 190 تنسيقًا شائعًا للوثائق في تطبيقات .NET باستخدام GroupDocs.Viewer لـ .NET APIs عن طريق إضافة بضعة أسطر من التعليمات البرمجية. يمكن للمطورين بسهولة عرض ملفات PDF ، ومعالجة الكلمات ، وجداول بيانات Excel ، والعرض التقديمي ، و Visio ، و Project ، و Outlook والعديد من تنسيقات المستندات الشائعة الأخرى في أوضاع HTML5 أو الصور أو PDF. يعد عرض المستند سريعًا ومماثلًا للملف المصدر الأصلي ، ولا يتطلب تثبيت برامج إضافية أو أي مكتبات خارجية أخرى.

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
              text: "أمثلة التعليمات البرمجية"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "العروض التوضيحية الحية"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "التسعير"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "خطوات تقديم ملف JLS في C#" 
    content_left: |
        باستخدام [GroupDocs.Viewer] (https://products.groupdocs.com/viewer/net/) ، يمكنك عرض JLS إلى HTML أو JPEG أو PNG أو PDF في بضع خطوات.

        * قم بتثبيت [GroupDocs.Viewer for .NET] (https://www.nuget.org/packages/groupdocs.viewer) باستخدام مدير الحزم المفضل لديك. 
        * إنشاء مثيل لفئة Viewer وتحميل الملف JLS بالمسار الكامل. 
        * تعيين الخيارات لعرض ملف JLS في تنسيق HTML أو PNG أو JPEG أو PDF. 
        * تقديم ملف والتحقق من الإخراج في الدليل الحالي. 
        
    title_right: "متطلبات النظام" 
    content_right: |
        GroupDocs.Viewer for .NET APIs مدعومة على جميع المنصات وأنظمة التشغيل الرئيسية. قبل تنفيذ الكود أدناه ، يرجى التأكد من تثبيت المتطلبات الأساسية التالية على نظامك.

        * أنظمة التشغيل: مايكروسوفت ويندوز ، لينوكس ، ماك 
        * بيئات التطوير: Microsoft Visual Studio و Visual Studio Code و .NET CLI 
        * الأطر: .NET Framework و .NET Standard و .NET Core و .NET 
    code: |
        ```cs
                        
            // Set up input JLS file
            string filePath = "input.jls";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render JLS file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "JLS عرض توضيحي مباشر للمشاهد"
    content: |
        اعرض ملف JLS الآن من خلال زيارة موقع ويب [GroupDocs.Viewer Online Apps] (https://products.groupdocs.app/viewer/ jls).
    lang: "ar"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "عرض تنسيقات الملفات الأخرى وعرضها باستخدام C#"
    exclude: "JLS"
    content: |
        واجهة برمجة تطبيقات عارض الصور والمستندات متعددة التنسيقات لـ .NET. اعرض بعض تنسيقات الملفات الشائعة أدناه بدون أي مشاهدين خارجيين.
    format: 
        # format loop 1
        - name: "تقديم ملف DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "مستند Microsoft Word المفتوح XML" 

        # format loop 2
        - name: "تقديم CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "ملف CorelDRAW" 

        # format loop 3
        - name: "تقديم PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "عرض تقديمي XML مفتوح في PowerPoint" 

        # format loop 4
        - name: "تقديم XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel افتح جدول بيانات XML" 

        # format loop 5
        - name: "تقديم DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "رسم أوتوكاد"

        # format loop 6
        - name: "تقديم XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "ملف XML"

        # format loop 7
        - name: "تقديم PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "مستند Adobe Photoshop"

        # format loop 8
        - name: "عرض ملف Adobe Illustrator"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "عمل فني من Adobe Illustrator"

        # format loop 9
        - name: "تقديم DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "مستند Microsoft Word" 

        # format loop 10
        - name: "تقديم TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "ملف نصي عادي" 

        # format loop 11
        - name: "تقديم DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "ملف تنسيق تبادل الرسم"  
          
        # format loop 12
        - name: "تقديم VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "ملف vCard"  
              
        # format loop 13
        - name: "تقديم SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "رسم متجه قابل للتحجيم" 
          
        # format loop 14
        - name: "تقديم HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "ملف لغة توصيف النص التشعبي" 
          
        # format loop 15
        - name: "تقديم ملف PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "ملف تنسيق المستند المحمول"
          
        # format loop 16
        - name: "تقديم JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "صورة JPEG"
          
        # format loop 17
        - name: "تقديم PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "رسم الشبكة المحمولة" 
          
        # format loop 18
        - name: "تقديم EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "رسالة الكترونية" 
          
        # format loop 19
        - name: "تقديم RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "ملف بتنسيق نص منسق" 
          
        # format loop 20
        - name: "تقديم ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "مستند نصي OpenDocument" 
          
        # format loop 21
        - name: "تقديم ملف CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "ملف قيم مفصولة بفواصل" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
