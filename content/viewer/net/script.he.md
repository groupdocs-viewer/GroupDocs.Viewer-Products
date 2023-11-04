---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: he

############################# Head #############################
head_title: "NET SCRIPT Viewer API - קריאה, הצג, עיבוד ב-C# VB.NET"
head_description: "ממשק API של מציג מסמכים של NET לקריאה, רינדור והצגה של SCRIPT בכל סוג של יישומי C#, ASP.NET, VB.NET ו-.NET Core."

############################# Header ############################
title: "SCRIPT מציג קבצים עבור יישומי C# .NET" 
description: "ממשק API של מציג מסמכים .NET לקריאה, רינדור והצגה של קובץ SCRIPT בכל סוג של יישומי C#, ASP.NET, VB.NET ו-.NET Core. הצג את הקבצים המעובדים עם עיצוב ופריסה אמיתיים ב-HTML5, PDF או כתמונה באמצעות כמה שורות של הקוד." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "הורד גרסת ניסיון בחינם"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "אודות GroupDocs.Viewer עבור .NET API" 
    content: |
        התחל לצפות ב-190+ פורמטים פופולריים של מסמכים ביישומי NET שלך באמצעות GroupDocs.Viewer עבור ממשקי API של .NET על ידי הוספת כמה שורות קוד. מפתחים יכולים להציג בקלות PDF, עיבוד תמלילים, גיליון אלקטרוני של Excel, מצגת, Visio, Project, Outlook ועוד הרבה פורמטים פופולריים של מסמכים במצבי HTML5, תמונה או PDF. עיבוד המסמכים מהיר, זהה לקובץ המקור המקורי, ואינו מצריך התקנת תוכנה נוספת או כל ספרייה חיצונית אחרת.

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
              text: "הפניה ל-API"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "דוגמאות קוד"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "הדגמות חיות"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "תמחור"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "שלבים לעיבוד קובץ SCRIPT ב-C#" 
    content_left: |
        עם [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/) אתה יכול לעבד את SCRIPT ל-HTML, JPEG, PNG או PDF בכמה שלבים.

        * התקן את [GroupDocs.Viewer עבור .NET](https://www.nuget.org/packages/groupdocs.viewer) באמצעות מנהל החבילות המועדף עליך. 
        * צור מופע של מחלקה Viewer וטען את הקובץ SCRIPT עם נתיב מלא. 
        * הגדר אפשרויות לעיבוד קובץ SCRIPT לפורמט HTML, PNG, JPEG או PDF. 
        * עבד את הקובץ ובדוק את הפלט בספרייה הנוכחית. 
        
    title_right: "דרישות מערכת" 
    content_right: |
        ממשקי API של GroupDocs.Viewer עבור .NET נתמכים בכל הפלטפורמות ומערכות ההפעלה העיקריות. לפני הפעלת הקוד שלהלן, אנא ודא שהדרישות המוקדמות הבאות מותקנים במערכת שלך.

        * מערכות הפעלה: Microsoft Windows, Linux, MacOS 
        * סביבות פיתוח: Microsoft Visual Studio, Visual Studio Code, .NET CLI 
        * מסגרות: .NET Framework, .NET Standard, .NET Core, .NET 
    code: |
        ```cs
                        
            // Set up input SCRIPT file
            string filePath = "input.script";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render SCRIPT file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "SCRIPT הדגמה חיה של הצופה"
    content: |
        הצג את הקובץ SCRIPT כעת על ידי ביקור באתר [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/script).
    lang: "he"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "פורמטי קבצים אחרים עיבוד והצגה באמצעות C#"
    exclude: "SCRIPT"
    content: |
        ממשק API של מציג מסמכים ותמונות בפורמט רב עבור NET. הצג כמה מפורמטי הקבצים הפופולריים למטה ללא צופים חיצוניים.
    format: 
        # format loop 1
        - name: "עיבוד DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word מסמך XML פתוח" 

        # format loop 2
        - name: "עיבוד CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "קובץ CorelDRAW" 

        # format loop 3
        - name: "עיבוד PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "מצגת PowerPoint Open XML" 

        # format loop 4
        - name: "עיבוד XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "גיליון אלקטרוני פתוח של Microsoft Excel" 

        # format loop 5
        - name: "עיבוד DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "ציור אוטוקאד"

        # format loop 6
        - name: "עיבוד XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "קובץ XML"

        # format loop 7
        - name: "עיבוד PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Adobe Photoshop Document"

        # format loop 8
        - name: "עיבוד קובץ Adobe Illustrator"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "יצירות אמנות של Adobe Illustrator"

        # format loop 9
        - name: "עיבוד DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "מסמך Microsoft Word" 

        # format loop 10
        - name: "עיבוד TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "קובץ טקסט רגיל" 

        # format loop 11
        - name: "עיבוד DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "ציור קובץ בפורמט Exchange"  
          
        # format loop 12
        - name: "עיבוד VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "קובץ vCard"  
              
        # format loop 13
        - name: "עיבוד SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "גרפיקה וקטורית ניתנת להרחבה" 
          
        # format loop 14
        - name: "עיבוד HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "עיבוד PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "קובץ בפורמט מסמך נייד"
          
        # format loop 16
        - name: "עיבוד JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "תמונת JPEG"
          
        # format loop 17
        - name: "עיבוד PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "גרפיקת רשת ניידת" 
          
        # format loop 18
        - name: "עיבוד EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "הודעת אימייל" 
          
        # format loop 19
        - name: "עיבוד RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "קובץ בפורמט טקסט עשיר" 
          
        # format loop 20
        - name: "עיבוד ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "OpenDocument Text Document" 
          
        # format loop 21
        - name: "עיבוד CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "קובץ ערכים מופרדים בפסיקים" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
