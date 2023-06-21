---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: ar

############################# Head #############################
head_title: "Java WEBP Viewer API - Render & Display WEBP في تطبيقات Java"
head_description: "عرض ملفات WEBP في تطبيقات Java و J2EE و J2SE. يدعم عرض أكثر من 170 تنسيقًا لملف المستندات والصور بتنسيق HTML أو PDF أو وضع الصورة مع ميزات متقدمة لإدارة خيارات عرض المستندات."

############################# Header ############################
title: "تقديم وعرض WEBP في Java" 
description: "واجهة برمجة تطبيقات عارض الملفات الأصلية وعالية الأداء WEBP للتطبيقات المستندة إلى Java و J2EE و J2SE ، مما يدعم نطاقًا واسعًا من الميزات الإضافية لتخصيص مظهر تنسيق المستند الناتج." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "تحميل النسخة التجريبية المجانية"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "حول GroupDocs.Viewer لجافا API" 
    content: |
        تمكين تطبيقات Java الخاصة بك لعرض أكثر من 170 تنسيقًا للملف في أوضاع HTML أو PDF أو الصور باستخدام GroupDocs.Viewer لواجهات برمجة تطبيقات Java بدون تثبيت أي برامج إضافية ؛ مثل Microsoft Office و Apache Open Office و Adobe Acrobat Reader وما إلى ذلك ، يمكن للمطورين بسهولة عرض جميع الصور وأنواع المستندات الشائعة بما في ذلك Microsoft Office و OpenDocument و HTML و PDF والأرشيف والرسومات التخطيطية و Photoshop و AutoCAD وتنسيقات لغة البرمجة داخل تطبيقات Java باستخدام تقديم سريع وأعلى جودة.

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
    title_left: "خطوات تقديم ملف WEBP في Java" 
    content_left: |
        باستخدام [GroupDocs.Viewer] (https://products.groupdocs.com/viewer/java/) ، يمكنك عرض WEBP إلى HTML أو JPEG أو PNG أو PDF في بضع خطوات.

        * أضف [GroupDocs.Viewer for Java] (https://releases.groupdocs.com/viewer/java/) كعنصر تبعية لمشروعك. 
        * إنشاء مثيل لفئة Viewer وتحميل الملف WEBP بالمسار الكامل. 
        * تعيين الخيارات لعرض ملف WEBP في تنسيق HTML أو PNG أو JPEG أو PDF. 
        * تقديم ملف والتحقق من الإخراج في الدليل الحالي. 
        
    title_right: "متطلبات النظام" 
    content_right: |
        GroupDocs.Viewer for Java APIs مدعومة على جميع المنصات وأنظمة التشغيل الرئيسية. قبل تنفيذ الكود أدناه ، يرجى التأكد من تثبيت المتطلبات الأساسية التالية على نظامك.

        * أنظمة التشغيل: مايكروسوفت ويندوز ، لينوكس ، ماك 
        * بيئات التطوير: NetBeans ، IntelliJ IDEA ، Eclipse إلخ. 
        * الأطر: J2SE 8.0 (1.8) أو أعلى (على سبيل المثال Java 17) 
    code: |
        ```java
                        
            // Set up input WEBP file
            String filePath = "input.webp";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render WEBP file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "WEBP عرض توضيحي مباشر للمشاهد"
    content: |
        اعرض ملف WEBP الآن من خلال زيارة موقع ويب [GroupDocs.Viewer Online Apps] (https://products.groupdocs.app/viewer/ webp).
    lang: "ar"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "عرض تنسيقات الملفات الأخرى وعرضها باستخدام Java"
    exclude: "WEBP"
    content: |
        متعدد التنسيقات وعارض الصور API لجافا. اعرض بعض تنسيقات الملفات الشائعة أدناه بدون أي مشاهدين خارجيين.
    format: 
        # format loop 1
        - name: "تقديم ملف DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "مستند Microsoft Word المفتوح XML" 

        # format loop 2
        - name: "تقديم CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "ملف CorelDRAW" 

        # format loop 3
        - name: "تقديم PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "عرض تقديمي XML مفتوح في PowerPoint" 

        # format loop 4
        - name: "تقديم XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel افتح جدول بيانات XML" 

        # format loop 5
        - name: "تقديم DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "رسم أوتوكاد"

        # format loop 6
        - name: "تقديم XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "ملف XML"

        # format loop 7
        - name: "تقديم PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "مستند Adobe Photoshop"

        # format loop 8
        - name: "عرض ملف Adobe Illustrator"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "عمل فني من Adobe Illustrator"

        # format loop 9
        - name: "تقديم DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "مستند Microsoft Word" 

        # format loop 10
        - name: "تقديم TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "ملف نصي عادي" 

        # format loop 11
        - name: "تقديم DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "ملف تنسيق تبادل الرسم"  
          
        # format loop 12
        - name: "تقديم VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "ملف vCard"  
              
        # format loop 13
        - name: "تقديم SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "رسم متجه قابل للتحجيم" 
          
        # format loop 14
        - name: "تقديم HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "ملف لغة توصيف النص التشعبي" 
          
        # format loop 15
        - name: "تقديم ملف PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "ملف تنسيق المستند المحمول"
          
        # format loop 16
        - name: "تقديم JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "صورة JPEG"
          
        # format loop 17
        - name: "تقديم PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "رسم الشبكة المحمولة" 
          
        # format loop 18
        - name: "تقديم EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "رسالة الكترونية" 
          
        # format loop 19
        - name: "تقديم RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "ملف بتنسيق نص منسق" 
          
        # format loop 20
        - name: "تقديم ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "مستند نصي OpenDocument" 
          
        # format loop 21
        - name: "تقديم ملف CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "ملف قيم مفصولة بفواصل" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
