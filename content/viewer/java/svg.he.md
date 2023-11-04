---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: he

############################# Head #############################
head_title: "Java SVG Viewer API - עיבוד והצג SVG באפליקציות Java"
head_description: "הצג קבצים של SVG ביישומי Java, J2EE, J2SE. תומך בצפייה ב-170+ פורמטים של קבצי מסמכים ותמונה במצב HTML, PDF או תמונה עם תכונות מתקדמות לניהול אפשרויות צפייה במסמכים."

############################# Header ############################
title: "עיבוד והצג SVG ב-Java" 
description: "ממשק API של מציג קבצים SVG מקורי וביצועים גבוהים עבור יישומים מבוססי Java, J2EE ו-J2SE, התומך במגוון רחב של תכונות נוספות להתאמה אישית של המראה של פורמט מסמך הפלט." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "הורד גרסת ניסיון בחינם"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "אודות GroupDocs.Viewer עבור Java API" 
    content: |
        אפשר ליישומי Java שלך להציג יותר מ-170 פורמטים של קבצים במצבי HTML, PDF או תמונה באמצעות GroupDocs.Viewer עבור ממשקי API של Java ללא תוכנה נוספת מותקנת; כגון Microsoft Office, Apache Open Office, Adobe Acrobat Reader וכו'. מפתחים יכולים להציג בקלות את כל התמונות וסוגי המסמכים הפופולריים כולל Microsoft Office, OpenDocument, HTML, PDF, Archive, Diagrams, Photoshop, AutoCAD ושפת תכנות בתבניות של יישומי Java עם עיבוד מהיר ואיכותי ביותר.

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
    title_left: "שלבים לעיבוד קובץ SVG ב-Java" 
    content_left: |
        עם [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/) אתה יכול לעבד את SVG ל-HTML, JPEG, PNG או PDF בכמה שלבים.

        * הוסף את [GroupDocs.Viewer עבור Java](https://releases.groupdocs.com/viewer/java/) כתלות בפרויקט שלך. 
        * צור מופע של מחלקה Viewer וטען את הקובץ SVG עם נתיב מלא. 
        * הגדר אפשרויות לעיבוד קובץ SVG לפורמט HTML, PNG, JPEG או PDF. 
        * עבד את הקובץ ובדוק את הפלט בספרייה הנוכחית. 
        
    title_right: "דרישות מערכת" 
    content_right: |
        GroupDocs.Viewer עבור ממשקי API של Java נתמכים בכל הפלטפורמות ומערכות ההפעלה העיקריות. לפני הפעלת הקוד שלהלן, אנא ודא שהדרישות המוקדמות הבאות מותקנים במערכת שלך.

        * מערכות הפעלה: Microsoft Windows, Linux, MacOS 
        * סביבות פיתוח: NetBeans, IntelliJ IDEA, Eclipse וכו'. 
        * מסגרות: J2SE 8.0 (1.8) ומעלה (לדוגמה Java 17) 
    code: |
        ```java
                        
            // Set up input SVG file
            String filePath = "input.svg";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render SVG file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "SVG הדגמה חיה של הצופה"
    content: |
        הצג את הקובץ SVG כעת על ידי ביקור באתר [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/svg).
    lang: "he"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "פורמטי קבצים אחרים עיבוד והצגה באמצעות Java"
    exclude: "SVG"
    content: |
        ממשק API של מציג מסמכים ותמונות בפורמט רב עבור Java. הצג כמה מפורמטי הקבצים הפופולריים למטה ללא צופים חיצוניים.
    format: 
        # format loop 1
        - name: "עיבוד DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word מסמך XML פתוח" 

        # format loop 2
        - name: "עיבוד CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "קובץ CorelDRAW" 

        # format loop 3
        - name: "עיבוד PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "מצגת PowerPoint Open XML" 

        # format loop 4
        - name: "עיבוד XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "גיליון אלקטרוני פתוח של Microsoft Excel" 

        # format loop 5
        - name: "עיבוד DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "ציור אוטוקאד"

        # format loop 6
        - name: "עיבוד XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "קובץ XML"

        # format loop 7
        - name: "עיבוד PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Adobe Photoshop Document"

        # format loop 8
        - name: "עיבוד קובץ Adobe Illustrator"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "יצירות אמנות של Adobe Illustrator"

        # format loop 9
        - name: "עיבוד DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "מסמך Microsoft Word" 

        # format loop 10
        - name: "עיבוד TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "קובץ טקסט רגיל" 

        # format loop 11
        - name: "עיבוד DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "ציור קובץ בפורמט Exchange"  
          
        # format loop 12
        - name: "עיבוד VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "קובץ vCard"  
              
        # format loop 13
        - name: "עיבוד SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "גרפיקה וקטורית ניתנת להרחבה" 
          
        # format loop 14
        - name: "עיבוד HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "עיבוד PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "קובץ בפורמט מסמך נייד"
          
        # format loop 16
        - name: "עיבוד JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "תמונת JPEG"
          
        # format loop 17
        - name: "עיבוד PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "גרפיקת רשת ניידת" 
          
        # format loop 18
        - name: "עיבוד EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "הודעת אימייל" 
          
        # format loop 19
        - name: "עיבוד RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "קובץ בפורמט טקסט עשיר" 
          
        # format loop 20
        - name: "עיבוד ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "OpenDocument Text Document" 
          
        # format loop 21
        - name: "עיבוד CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "קובץ ערכים מופרדים בפסיקים" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
