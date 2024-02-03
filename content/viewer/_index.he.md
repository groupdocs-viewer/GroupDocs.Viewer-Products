---
############################# Static ##########################
layout: "family"
date: 2023-12-20T06:39:57
draft: false

product: "Viewer"
product_tag: "viewer"

############################# Head ############################
head_title: "עיבוד והצג מסמכים API | On Premise API ושירות מקוון"
head_description: "עבד והצג קבצי Word, PDF, Excel, Powerpoint או Image בקלות ובחינם"

############################# Header ##########################
title: "עבד והצג מסמכים בקלות"
description: |
  API רב עוצמה של Viewer לעיבוד קבצים שונים ל-PDF, HTML ותמונה.

  טען מסמכים ממקורות שונים, כולל קבצים, זרמים, כתובות URL, שרתי FTP, Amazon S3, Azure Blob Storage ועוד.

  צור דפי HTML רספונסיביים, הגן על קובצי ה-PDF הפלט וסדר מחדש את הדפים שלהם, סובב דפים, עבד הערות והערות במידת הצורך.

############################# Platforms ############################
supported_platforms:
  enable: true  
  head_title: "בחר את הפלטפורמה שלך"
  title: "פלטפורמות נתמכות"
  description: "ספריית GroupDocs.Viewer תומכת במערכות ההפעלה ובמסגרות הבאות"
  details_link_title: "למד עוד"
  items:
    # supported_platforms loop
    - title: ".NET"
      description: "GroupDocs.Viewer for .NET"
      color: "blue"
      tag: "net"
      link: "/viewer/net/"
      features_link: "https://docs.groupdocs.com/viewer/net/system-requirements/"
      features:
        # features loop
        - content: ".NET Framework 4.6.2+  <br>  .NET Core 3.1  <br>  .NET 6+"
          rows: "3"
        # features loop
        - content: "Windows, Linux"
          rows: "1"
        # features loop
        - content: "180+ פורמטים של קבצים"
          rows: "1"
        # features loop
        - content: "חבילת ממשק משתמש עבור ASP.NET Core"
          rows: "1"
        # features loop
        - content: "ASP.NET WebForms Demo  <br>  ASP.NET MVC Demo  <br>  ASP.NET Core Demo"
          rows: "3"
    
    # supported_platforms loop
    - title: "Java"
      description: "GroupDocs.Viewer for Java"
      color: "red"
      tag: "java"
      link: "/viewer/java/"
      features_link: "https://docs.groupdocs.com/viewer/java/system-requirements/"
      features:
        # features loop
        - content: "J2SE 8.0 (1.8)+"
          rows: "3"
        # features loop
        - content:  "Windows, Linux, macOS"
          rows: "1"       
        # features loop
        - content: "180+ פורמטים של קבצים"
          rows: "1"
        # features loop
        - content:  "חבילת ממשק משתמש עבור Spring ו-Dropwizard"
          rows: "1"
        # features loop
        - content:  "Spring Demo  <br>  Dropwizard demo"
          rows: "3"

    # supported_platforms loop
    - title: "Node.js"
      description: "GroupDocs.Viewer for Node.js"
      color: "green"
      tag: "nodejs-java"
      link: "/viewer/nodejs-java/"
      features_link: "https://docs.groupdocs.com/viewer/nodejs-java/system-requirements/"
      features:
        # features loop
        - content: "Node.js 16+  <br>  and J2SE 8.0 (1.8)+"
          rows: "3"
        # features loop
        - content:  "Windows, Linux, macOS"
          rows: "1"
        # features loop
        - content:  "180+ פורמטים של קבצים"
          rows: "1"
        # features loop
        - content:  "חבילת UI - בקרוב"
          rows: "1" 
        # features loop
        - content:  "הדגמה - בקרוב"
          rows: "3" 


############################# Features ############################

features:
  enable: true
  title: "ערכת התכונות של GroupDocs.Viewer"
  description: "API לעיבוד קבצים מסוגים שונים כמו HTML, PDF, PNG ו-JPEG ביישומים כדי להציג אותם ללא תוכנת צד שלישי."

  items:
    # feature loop
    - icon: "view"
      title: "הצג מסמכים ותמונות"
      content: "הצג מסמכים על ידי עיבודם כקובצי HTML, PDF, PNG ו-JPEG."

    # feature loop
    - icon: "password"
      title: "פתח מסמכים מאובטחים"
      content: "ציין סיסמה לפתיחת מסמכים מוצפנים."

    # feature loop
    - icon: "load"
      title: "טען קבצים מכל מקום"
      content: "טען מסמכים מקבצים שונים, כתובות URL, שרתי FTP, Amazon S3 ועוד."
    
    # feature loop
    - icon: "pages"
      title: "עבד את כל הדפים או הדפים הספציפיים"
      content: "ציין טווח של מספרי עמודים לעיבוד."


############################# Code samples ############################
code_samples:
  enable: true
  title: "דוגמאות קוד של GroupDocs.Viewer"
  description: "חלקם משתמשים במקרים של פעולות טיפוסיות של GroupDocs.Viewer ב-C#, Java, TypeScript"
  items:
    # code sample loop
    - title: "כיצד לעבד קובצי DOCX ל-PDF"
      content: |
       עיבוד מסמכי DOCX ל-PDF ללא Microsoft Word או תוכנה אחרת מותקנת. טען והצג בקלות קובצי DOCX בתוך יישום ה-.NET שלך, בין אם זה יישום אינטרנט או שולחן עבודה. להלן דוגמה כיצד לעבד קובץ DOCX ל-PDF:
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // טען קובץ DOCX לעיבוד
            using (Viewer viewer = new Viewer("sample.docx"))
            {
              // עיבוד DOCX לקובץ PDF
              PdfViewOptions viewOptions = new PdfViewOptions();
              viewer.View(viewOptions);
            }
            ```
        - language: "Java"
          color: "red"
          content: |
            ```java {style=abap}   
            import com.groupdocs.viewer.Viewer;
            import com.groupdocs.viewer.options.PdfViewOptions;
            // ...
            // טען קובץ DOCX לעיבוד
            try (Viewer viewer = new Viewer("sample.docx")) {
                // עיבוד DOCX לקובץ PDF
                PdfViewOptions viewOptions = new PdfViewOptions();
                viewer.view(viewOptions);
            }
            ```
        - language: "TypeScript"
          color: "green"
          content: |
            ```javascript {style=abap}  
            // טען קובץ DOCX לעיבוד
            const viewer = new groupdocs.viewer.Viewer("sample.docx")
            
            // עיבוד DOCX לקובץ PDF
            const viewOptions = groupdocs.viewer.PdfViewOptions(output.pdf)
            viewer.view(viewOptions)
            ```


############################# Formats ############################
formats:
  enable: true
  title:  "180+ פורמטים של קבצים נתמכים"
  description: "GroupDocs.Viewer תומך בפעולות עם הפופולריים ביותר [formats](https://docs.groupdocs.com/viewer/net/supported-document-formats/)"


############################# Metrics ############################

metrics:
  enable: true
  title: "מדדי עומק ותובנות סטטיסטיות"
  description: "צלול לתוך פירוט מפורט של נתוני המפתח שלנו, מספקים מדדים מקיפים ותובנות סטטיסטיות לגבי ההישגים, ההשפעה והצמיחה שלנו."

  items:
    # metrics loop
    - number: "180+"
      title: "פורמטים נתמכים"
      content: "הצג בקלות למעלה מ-180 פורמטים של קבצים, כולל מסמכים, תמונות וציורי CAD ללא טרחה. שבור מחסומי תאימות וגישה לקבצים מגוונים ללא מאמץ עם פתרון הצפייה המקיף שלנו."
    # metrics loop
    - number: "1.0M"
      title: "הורדות של NuGet"
      content: "פתרון החבילה NuGet שלנו הפך למשאב מהימן ומאומץ בקהילת המפתחים, ומספק אינטגרציה חלקה ופונקציונליות רבת ערך עבור אינספור פרויקטים."

    # metrics loop
    - number: "10+"
      title: "ספריות"
      content: "המוצר שלנו כולל 10+ ספריות, המציע תכונות מתקדמות למיטוב הביצועים. ספריות אלו נועדו למלא צורכי פיתוח שונים עם יכולות שאין שני להן."
    
    # metrics loop
    - number: "100+"
      title: "לקוחות מרוצים"
      content: "משרת את המותגים האייקוניים ביותר ברחבי העולם. גלה מדוע מאות אוהבים את GroupDocs.Viewer! חקור ניווט חלק, שיתוף פעולה נוח וקלות שימוש ללא תחרות. הצטרף עכשיו!"


############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "הלקוחות המרוצים שלנו"
  description: "ספריות GroupDocs מועסקות על ידי מותגים בעלי שם עולמי ומכובד ברחבי העולם."

  items:
    # customers loop
    - title: "BenQ Corporation"
      logo: "benq"
    # customers loop
    - title: "Nasdaq Stock Market"
      logo: "nasdaq"
    # customers loop
    - title: "AT&T Inc."
      logo: "att"
    # customers loop
    - title: "AstraZeneca"
      logo: "astrazeneca"
    # customers loop
    - title: "Central Bank of Argentina"
      logo: "argentinacentralbank"
    # customers loop
    - title: "Roche Holding AG"
      logo: "roche"
    # customers loop
    - title: "Capita"
      logo: "capita"
    # customers loop
    - title: "Axa S.A."
      logo: "axa"
    # customers loop
    - title: "Instructure Inc."
      logo: "instructure"
     # customers loop
    - title: "Wipro"
      logo: "wipro"



############################# Actions ############################

actions:
  enable: true
  title: "מוכנים להתחיל?"
  description: "נסה את תכונות GroupDocs.Viewer בחינם או בקש רישיון"

  items:
    #  loop
    - title: ".NET"
      link: "/viewer/net/"
      color: "blue"
        #  loop
    - title: "Java"
      link: "/viewer/java/"
      color: "red"
        #  loop
    - title: "Node.js"
      link: "/viewer/nodejs-java/"
      color: "green"


############################# Faq ############################

faq:
  enable: true
  title: "שאלות וחששות נפוצים"
  description: "מצא תשובות לשאלות נפוצות בחלק השאלות הנפוצות שלנו כדי לענות במהירות על השאלות והחששות שלך."

  items:
    #  loop
    - question: "האם אוכל להעריך את מוצרי GroupDocs לפני הרכישה?"
      answer: |
        כן! לכל מוצרי GroupDocs יש גרסת הערכה נטולת סיכון. אנו ממליצים מאוד למפתחים להוריד ולנסות את ממשקי ה-API שלנו לפני הרכישה כדי להבטיח שהם ימלאו את הצרכים שלך ב-100%.
    #  loop
    - question: "האם GroupDocs עושה הדגמות של מוצרים?"
      answer: |
        לא, ההתמקדות שלנו היא בממשקי ה-API שלנו והפיכת המוצרים הפונקציונליים והיציבים ביותר האפשריים. אנחנו כן מציעים נסיונות פונקציונליים לחלוטין וחינמיים בצורה של[license](https://purchase.groupdocs.com/temporary-license/) כדי שתוכלו לבדוק את המוצר בעצמכם.
    #  loop
    - question: "היכן ניתן להוריד את המוצר?"
      answer: |
        כל המוצרים זמינים להורדה מ[releases](https://releases.groupdocs.com). איננו שולחים עותקים פיזיים של התוכנה שלנו בדואר.    
    #  loop
    - question: "האם רשיונות מפתחים של GroupDocs הם לכל משתמש, או לכל משתמש בשם?"
      answer: |
        רישיונות מפתחים של GroupDocs הם לכל משתמש, לא לכל משתמש בעל שם. אנו מבינים שחברי צוות קידוד עשויים להשתנות עם הזמן וכי אין זה מעשי לעדכן את הרישוי בכל פעם שמתרחשת.
    #  loop
    - question: "האם אנחנו צריכים רישוי רק למפתחים פעילים? לדוגמה, יש לנו צוות של שני מפתחים שעובדים במשמרת A וצוות שני של שני מפתחים שעובדים במשמרת B... במצב הזה, האם אנחנו צריכים שניים או ארבעה רישיונות?"
      answer: |
        כל המפתחים שעובדים על הפרויקט צריכים לקבל רישיון. במצב זה, GroupDocs רואה בצוות שלך ארבעה חברים (למרות שהם עובדים בזמנים שונים).

############################# Cloud ############################

cloud_links:
  enable: true
  title: "ממשקי API של קוד נמוך של GroupDocs.Viewer"
  description: "האץ את הצגת המסמכים או התמונות בכל סוג של יישום עם REST API מבוסס הענן שלנו"

  items:
    #  loop
    - icon: "groupdocs_viewer-for-curl"
      title: "GroupDocs.Viewer Cloud for cURL"
      link: "https://products.groupdocs.cloud/viewer/curl"
      content: "השתמש בממשק ה-API של cURL RESTful לצפייה במסמכים כדי לעבד ולהציג ביעילות את Microsoft Office, PDF ופורמטי קבצים סטנדרטיים שונים ביישומים שלך."

    #  loop
    - icon: "groupdocs_viewer-for-net"
      title: "GroupDocs.Viewer Cloud for .NET"
      link: "https://products.groupdocs.cloud/viewer/net"
      content: "שפר את יכולות הצפייה במסמכים ביישומי NET עם Cloud SDK עבור .NET. הצג מסמכים בצורה חלקה בפורמטים של HTML, PDF או תמונה."
    #  loop
    - icon: "groupdocs_viewer-for-java"
      title: "GroupDocs.Viewer Cloud for Java"
      link: "https://products.groupdocs.cloud/viewer/java"
      content: "שלב יכולות עיבוד מסמכים מתקדמות ביישומי Java שלך באמצעות SDK של Document Viewer עבור Java."

############################# Apps ############################

app_links:
  enable: true
  title: "אפליקציות GroupDocs.Viewer NoCode"
  description: "אפליקציה מקוונת המאפשרת לך לצפות ב-180+ פורמטי קבצים פופולריים בדפדפן"

  items:
    #  loop
    - icon: "groupdocs_viewer-app"
      title: "GroupDocs.Viewer Total"
      link: "https://products.groupdocs.app/viewer/total"
      content: "חקור יישום מקוון בחינם כדי להציג למעלה מ-180 פורמטי קבצים ישירות מדפדפן האינטרנט המועדף עליך."

    #  loop
    - icon: "groupdocs_words-app"
      title:  "GroupDocs.Viewer DOCX"
      link: "https://products.groupdocs.app/viewer/docx"
      content: "כלי מבוסס אינטרנט לצפייה בקבצי Microsoft Word ללא מאמץ בין מכשירים שונים."

    #  loop
    - icon: "groupdocs_pdf-app"
      title:  "GroupDocs.Viewer PDF"
      link: "https://products.groupdocs.app/viewer/pdf"
      content: "פתח והצג קבצי PDF באופן מקוון עם מציג PDF בחינם."
    

---