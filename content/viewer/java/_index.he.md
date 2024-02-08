---
############################# Static ############################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

product: "Viewer"
product_tag: "viewer"
platform: "Java"
platform_tag: "java"

############################# Drop-down ############################
supported_platforms:
  items:
    # supported_platforms loop
    - title: ".NET"
      tag: "net"
    # supported_platforms loop
    - title: "Java"
      tag: "java"
    # supported_platforms loop
    - title: "Node.js"
      tag: "nodejs-java" 


############################# Head ############################
head_title: "Java Document Viewer API, render PDF Word Excel Image Diagram HTML"
head_description: "ספריית Document Viewer לפיתוח יישומי Java המציגים, מציגים ומתפעלים באופן טבעי מסמכים מרובי פורמטים התומכים ב-180+ פורמטים של קבצים."

############################# Header ############################
title: "עבד והצג מסמכים<br>באמצעות Java API"
description: "API רב עוצמה של Viewer לעיבוד 180+ פורמטים של מסמכים ל-PDF, HTML ותמונה עם אפשרויות תצורה מגוונות."
words:
  for: "for"

actions:
  main: "הורדה חינם של מייבן"
  main_link: "https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-viewer/"
  alt: "רישוי"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/java"
  title: "מוכנים להתחיל?"
  description: "נסה את תכונות GroupDocs.Viewer בחינם או בקש רישיון"

release:
  title: "גרסה {0} שוחררה"
  notes: "תראה מה חדש"
  downloads: "הורדות"
  link: "https://releases.groupdocs.com/viewer/java/release-notes/latest/"

code:
  title: "עיבוד קבצי PDF ב-Java"
  more: "דוגמאות נוספות"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Java"
  install: |
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
  content: |
    ```java {style=abap}
    // Instantiate Viewer 
    try (Viewer viewer = new Viewer("resume.pdf"))
    {
        // הגדר אפשרויות פלט HTML, קובץ אחד לכל עמוד  
        HtmlViewOptions viewOptions = 
        HtmlViewOptions.forEmbeddedResources();

        // עיבוד PDF ל-HTML עם משאבים משובצים
        viewer.view(viewOptions);
    }
    ```
############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Viewer במבט חטוף"
  description: "API לעיבוד, תצוגה, המרת מסמכים, שקופיות, דיאגרמות וסוגי מסמכים רבים אחרים ביישומי Java"
  features:
    # feature loop
    - title: "הצג מסמכים ביעילות ובאמינות"
      content: "עם GroupDocs.Viewer API אתה יכול להציג ביעילות מסמכים מכל פורמט נתמך ל-HTML, JPEG, PNG ו-PDF עם אפשרויות גמישות וחזקות תוך שמירה על שלמות התוכן ושל מבנה המסמך. GroupDocs.Viewer עובד על פלטפורמות Windows ו-Linux."

    # feature loop
    - title: "רוב הפורמטים הפופולריים של קבצים ומסמכים נתמכים"
      content: "אנו תומכים בעיבוד של למעלה מ-180 הפורמטים הפופולריים ביותר של קבצים ומסמכים הכוללים Word, Excel, PDF, PowerPoint, משפחת הפורמטים של OpenDocument, ארכיונים, תמונות רסטר ו-וקטור, ספרים אלקטרוניים, שפות תכנות ותגי עיצוב וסוגי קבצים רבים אחרים, כולל מוצפנים קבצים עם הגנת סיסמה."

    # feature loop
    - title: "פלט להתאמה אישית"
      content: "GroupDocs.Viewer מאפשר לא רק לרנדר את המסמך, אלא גם לשלוט כיצד בדיוק, אילו חלקים מהמסמך יש לרנדר או כעת, כיצד יש לרנדר אותם, ולהחיל טרנספורמציות שונות על הפלט המעובד."

    # feature loop
    - title: "ממשק משתמש אינטרנט עבור Spring framework"
      content: "אנו מספקים חבילת ממשק משתמש בקוד פתוח עבור Spring framework שניתן להוסיף לפרויקט שלך תוך מספר דקות. חבילת Viewer.UI מכילה ממשק משתמש אינטרנטי מבוסס Angular ומספקת קבוצה של ממשקי API שימושיים וספקי אחסון נתונים."

############################# Platforms ############################
platforms:
  enable: true
  title: "עצמאות פלטפורמה"
  description: "GroupDocs.Viewer עבור Java תומך במערכות ההפעלה, המסגרות ומנהלי החבילות הבאות"
  items:
    # platform loop
    - title: "Amazon"
      image: "amazon"
    # platform loop
    - title: "Docker"
      image: "docker"
    # platform loop
    - title: "Azure"
      image: "azure"
    # platform loop
    - title: "Eclipse"
      image: "eclipse"
    # platform loop
    - title: "IntelliJ"
      image: "intellij"
    # platform loop
    - title: "Windows"
      image: "windows"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "Maven"
      image: "maven"


############################# File formats ############################
formats:
  enable: true
  title: "פורמטי קבצים נתמכים"
  description: |
    GroupDocs.Viewer עבור Java תומך בפעולות עם הבאים [formats](https://docs.groupdocs.com/viewer/java/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office, OpenDocument ופורמטים של טקסט
        * **Word:** DOC, DOCX, DOCM, DOT, DOTX, DOTM, RTF, TXT
        * **Excel:** XLS, XLSX, XLSM, XLSB, XLTM, XLT, XLTM, XLTX
        * **PowerPoint:** PPT, PPTX, PPS, PPSX, PPSM, POT, POTM, POTX, PPTM        
        * **Project:** MPP, MPT, MPX
        * **Outlook:** MSG, EML, EMLX, PST, OST
        * **OneNote:** ONE
        * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG
        * **Fixed Page Layout:** PDF, TEX, XPS, OXPS
        * **e-Books:** EPUB, MOBI, DjVu
        * **Delimiter-Separated Values:** CSV, TSV
    # group loop
    - color: "blue"
      content: |
        ### תמונות, גרפיקה ודיאגרמות
        * **תמונות רסטר:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
        * **Windows Icon:** ICO
        * **Scalable Vector Graphics:** SVG, CDR, CMX, IGS, SVGZ        
        * **Adobe Photoshop:** PSD, PSB        
        * **Stereo Lithography (3D Printing):** STL        
        * **Medical Imaging:** DICOM
        * **Plotter Documents:** PLT, HPG
        * **Autodesk Design Web Formats:** DWF, DWG
        * **AutoCAD Drawing:** DWT, IFC, STL, CF2        
      # group loop
    - color: "red"
      content: |
        ### אַחֵר        
        * **אינטרנט:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **אַרְכִיוֹן:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **אַחֵר:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "תכונות GroupDocs.Viewer"
  description: "עיבוד חלק, הצג והמר PDF ומסמכי Office"

  items:
    # feature loop
    - icon: "viewhtml"
      title: "הצג מסמכים ב-HTML"
      content: "המר מסמך מכל סוג למסמך HTML עם CSS ו-SVG, שניתן להציג בכל דפדפן אינטרנט מודרני."

    # feature loop
    - icon: "rasterize"
      title: "רסטר מסמכים"
      content: "רסטר כל פורמט מסמך נתמך לתמונת הרסטר, עם פורמט תמונה ואיכות דחיסה מתכווננת."

    # feature loop
    - icon: "sourcecode"
      title: "עיבוד והדגשת קודי תכנות"
      content: "תמיכה בכל שפות התכנות, הסקריפטים והסימון הפופולריות, עם יכולת לנתח ולהדגיש את התחביר שלהן."

    # feature loop
    - icon: "convertpdf"
      title: "המר ל-PDF"
      content: "ניתן להמיר ולשמור בקלות מסמך בכל פורמט נתמך ל-PDF עם אפשרויות מתכווננות."

    # feature loop
    - icon: "transform"
      title: "החל טרנספורמציות"
      content: "ניתן לשנות את מסמך הפלט במהלך העיבוד - ניתן לסובב ו/או לארגן מחדש דפים, וניתן להציב סימן מים של טקסט מעליהם."

    # feature loop
    - icon: "adjustment"
      title: "התאמת פלט HTML"
      content: "פלט מסמכי HTML, שנוצרו על ידי GroupDocs.Viewer, ניתנים לכיוון עדין מאוד: מותר לשמור בזרם או בקובץ, עם משאבים חיצוניים או משובצים, התקשרויות חוזרות וכן הלאה."

    # feature loop
    - icon: "complex"
      title: "תמיכה במבני מסמכים מורכבים"
      content: "GroupDocs.Viewer תומך לא רק במסמכים בודדים, אלא גם בקבצים, המכילים באופן פנימי רשימה או מבנה היררכי של מסמכים, כמו הודעות דואר אלקטרוני עם קבצים מצורפים, ארכיוני ZIP עם קבצים פנימיים בתוך תיקיות, תמונות TIFF מרובות עמודים, וכן הלאה."

    # feature loop
    - icon: "optimization"
      title: "אפשרויות אופטימיזציה"
      content: "GroupDocs.Viewer מכיל תת-מערכת מטמון מתכווננת, שיכולה לקצר את זמן הטעינה על ידי שימוש בגרסאות המאוחסנות של המסמכים. כמו כן, קבוצה של אפשרויות שונות עבור פורמטים שונים מאפשרת לא לכלול חלקים או היבטים מיותרים של מסמכים מהעיבוד (גופנים, גליונות עבודה נסתרים, קבצים מצורפים לדואל) כדי לייעל את הביצועים הכוללים"

    # feature loop
    - icon: "passwordprotected"
      title: "תמיכה במסמכים מוגני סיסמה"
      content: "GroupDocs.Viewer מאפשר לפתוח את המסמכים המוצפנים מסוגים שונים: PDF, עיבוד וורדפרס, גיליון אלקטרוני, מצגת ועוד, על ידי ציון סיסמה באפשרויות הטעינה."

############################# Code samples ############################
code_samples:
  enable: true
  title: "דוגמאות קוד"
  description: "חלק משתמשים במקרים של GroupDocs.Viewer טיפוסי עבור פעולות Java"
  items:
    # code sample loop
    - title: "עיבוד DOCX ל-HTML"
      content: |
        מאפייני המחלקה [HtmlViewOptions](https://reference.groupdocs.com/viewer/java/com.groupdocs.viewer.options/htmlviewoptions/) מאפשרים לך לשלוט בתהליך ההמרה, עוד על כך [HTML](https://docs.groupdocs.com/viewer/java/rendering-to-html/). לדוגמה, אתה יכול להטמיע את כל המשאבים החיצוניים בקובץ HTML הפלט, להקטין את קובץ הפלט ולבצע אופטימיזציה להדפסה.
        {{< landing/code title="Java">}}
        ```java {style=abap}
        import com.groupdocs.viewer.Viewer;
        import com.groupdocs.viewer.options.HtmlViewOptions;

        // Instantiate Viewer
        try (Viewer viewer = new Viewer("resume.docx"))
        {
            // הגדר אפשרויות פלט HTML
            HtmlViewOptions options = 
            HtmlViewOptions.forEmbeddedResources();

            // עיבוד DOCX ל-HTML עם משאבים משובצים
            viewer.view(options);
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "ייצוא PPTX ל-PDF"
      content: |
        צור מופע מחלקה [PdfViewOptions](https://reference.groupdocs.com/viewer/java/com.groupdocs.viewer.options/pdfviewoptions/) והעביר אותו ל-[Viewer.View](https://reference.groupdocs.com/viewer/java/com.groupdocs.viewer/viewer/#view-com.groupdocs.viewer.options.ViewOptions) להמרת קובץ PowerPoint PPTX ל-PDF. מאפייני המחלקה PdfViewOptions מאפשרים לך לשלוט בתהליך ההמרה. לדוגמה, אתה יכול להגן על קובץ ההפלט, לסדר מחדש את העמודים שלו ולציין את איכות תמונות המסמך. עיין ב[PDF](https://docs.groupdocs.com/viewer/java/rendering-to-pdf/) לפרטים.
        {{< landing/code title="Java">}}
        ```java {style=abap}   
        import com.groupdocs.viewer.Viewer;
        import com.groupdocs.viewer.options.PdfViewOptions;

        // Instantiate Viewer
        try (Viewer viewer = new Viewer("presentation.pptx"))
        {            
            // הגדר אפשרויות פלט PDF
            PdfViewOptions viewOptions = new PdfViewOptions();

            // ייצוא PPTX ל-PDF
            viewer.view(viewOptions);
        }
        ```
        {{< /landing/code >}}
############################# Reviews ############################
# reviews:
# enable: true
# title: "סקירות מוצרים של GroupDocs"
# description: "אל תסתפק במילה שלנו. ראה מה מפתחים אחרים אומרים על ממשקי ה-API שלנו"

# items:
#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "שירות מעולה ומוצרים מעולים. הם היו מאוד מועילים ומגיבים במהלך תהליך ההטמעה של GroupDocs.Viewer עבור .NET, לא יכול להמליץ ​​עליהם מספיק."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "לאחר הטמעה ושימוש ב- GroupDocs.Viewer עבור NET בפרויקט, נראה שהוא עובד טוב מאוד. בדקתי עם הרבה מסמכים ועד כה הכל טוב. כל מה שזרקתי עליו מוצג יפה ונראה טוב בדיוק כמו במציג PDF או MS Word."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---