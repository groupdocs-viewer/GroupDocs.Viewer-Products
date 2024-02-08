---
############################# Static ############################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: he
product: "Viewer"
product_tag: "viewer"
platform: "Node.js via Java"
platform_tag: "nodejs-java"

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
head_title: "Node.js Document Viewer API עבור PDF Word Excel תמונות HTML והודעות דואר אלקטרוני"
head_description: "מציג מסמכים של Node.js ו-API לעיבוד קבצים. הוסף מציג PDF, מציג Word, מציג Excel, מציג תמונות, מציג HTML, מציג דואל ביישומי JavaScript."

############################# Header ############################
title: "API של Node.js לעיבוד והצגת מסמכים"
description: "ספריית מציג מסמכים לפיתוח יישומי JavaScript המציגים, מציגים ומתפעלים באופן טבעי מסמכים בפורמטים רבים התומכים ב-180+ פורמטים של קבצים."
words:
  for: "for"

actions:
  main: "הורדה חינם של NPM"
  main_link: "https://www.npmjs.com/package/@groupdocs/groupdocs.viewer"
  alt: "רישוי"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/nodejs-java"
  title: "מוכנים להתחיל?"
  description: "נסה את תכונות GroupDocs.Viewer בחינם או בקש רישיון"

release:
  title: "גרסה {0} שוחררה"
  notes: "תראה מה חדש"
  downloads: "הורדות"
  link: "https://releases.groupdocs.com/viewer/nodejs-java/release-notes/latest/"

code:
  title: "עיבוד קובצי PDF ב-JavaScript"
  more: "דוגמאות נוספות"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Node.js-via-Java"
  install: "npm i @groupdocs/groupdocs.viewer"
  content: |
    ```javascript {style=abap}       
    // הגדר אפשרויות פלט HTML, קובץ אחד לכל עמוד
    const viewOptions = HtmlViewOptions.forEmbeddedResources()
    
    // Instantiate Viewer
    const viewer = new Viewer("resume.pdf")

    // עיבוד PDF ל-HTML עם משאבים משובצים
    viewer.view(viewOptions)
    viewer.close()
    ```
############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Viewer במבט חטוף"
  description: "API לעיבוד, תצוגה, המרת מסמכים, שקופיות, דיאגרמות וסוגי מסמכים רבים אחרים ביישומי Node.js"
  features:
    # feature loop
    - title: "הצג מסמכים ביעילות ובאמינות"
      content: "עם GroupDocs.Viewer API אתה יכול להציג ביעילות מסמכים מכל פורמט נתמך ל-HTML, JPEG, PNG ו-PDF עם אפשרויות גמישות וחזקות תוך שמירה על שלמות התוכן ושל מבנה המסמך. GroupDocs.Viewer עבור Node.js עובד על פלטפורמות Windows ו-Linux."

    # feature loop
    - title: "רוב הפורמטים הפופולריים של קבצים ומסמכים נתמכים"
      content: "אנו תומכים בעיבוד של למעלה מ-180 הפורמטים הפופולריים ביותר של קבצים ומסמכים הכוללים Word, Excel, PDF, PowerPoint, משפחת הפורמטים של OpenDocument, ארכיונים, תמונות רסטר ו-וקטור, ספרים אלקטרוניים, שפות תכנות ותגי עיצוב וסוגי קבצים רבים אחרים, כולל מוצפנים קבצים עם הגנת סיסמה."

    # feature loop
    - title: "פלט להתאמה אישית"
      content: "GroupDocs.Viewer מאפשר לא רק לרנדר את המסמך, אלא גם לשלוט כיצד בדיוק, אילו חלקים מהמסמך יש לרנדר או כעת, כיצד יש לרנדר אותם, ולהחיל טרנספורמציות שונות על הפלט המעובד."

############################# Platforms ############################
platforms:
  enable: true
  title: "עצמאות פלטפורמה"
  description: "GroupDocs.Viewer עבור Node.js תומך במערכות ההפעלה, המסגרות ומנהלי החבילות הבאות"
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
    - title: "NPM"
      image: "npm"

############################# File formats ############################
formats:
  enable: true
  title: "פורמטי קבצים נתמכים"
  description: |
    GroupDocs.Viewer עבור Node.js דרך Java תומך בפעולות עם הבאים [formats](https://docs.groupdocs.com/viewer/nodejs-java/supported-document-formats/).
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
  description: "חלק משתמשים במקרים של GroupDocs.Viewer טיפוסי עבור Node.js באמצעות פעולות Java"
  items:
    # code sample loop
    - title: "עיבוד DOCX ל-HTML"
      content: |
        מאפייני המחלקה `HtmlViewOptions` מאפשרים לך לשלוט בתהליך ההמרה, עוד על כך [HTML](https://docs.groupdocs.com/viewer/nodejs-java/rendering-to-html/). לדוגמה, אתה יכול להטמיע את כל המשאבים החיצוניים בקובץ HTML הפלט, להקטין את קובץ הפלט ולבצע אופטימיזציה להדפסה.
        {{< landing/code title="JavaScript">}}
        ```javascript {style=abap}
        import { Viewer, HtmlViewOptions } from '@groupdocs/groupdocs.viewer'

        // הגדר אפשרויות פלט HTML, קובץ אחד לכל עמוד
        const viewOptions = HtmlViewOptions.forEmbeddedResources()

        // Instantiate Viewer
        const viewer = new Viewer("resume.docx")

        // עיבוד DOCX ל-HTML עם משאבים משובצים
        viewer.view(viewOptions)
        viewer.close()
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "ייצוא PPTX ל-PDF"
      content: |
        צור מופע מחלקה 'PdfViewOptions' והעביר אותו לשיטת 'Viewer.view' כדי להמיר קובץ PowerPoint PPTX ל-PDF. מאפייני המחלקה 'PdfViewOptions' מאפשרים לך לשלוט בתהליך ההמרה. לדוגמה, אתה יכול להגן על קובץ ה הפלט, לסדר מחדש את העמודים שלו ולציין את איכות תמונות המסמך. עיין ב[PDF](https://docs.groupdocs.com/viewer/nodejs-java/rendering-to-pdf/) לפרטים.
        {{< landing/code title="JavaScript">}}
        ```javascript {style=abap}   
        import { Viewer, PdfViewOptions } from '@groupdocs/groupdocs.viewer'

        // הגדר אפשרויות פלט PDF
        const viewOptions = new PdfViewOptions("presentation.pdf")

        // Instantiate Viewer
        const viewer = new Viewer("presentation.pptx")

        // ייצוא PPTX ל-PDF
        viewer.view(viewOptions)
        viewer.close()
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
