---
############################# Static ##########################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

lang: he
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: ".NET Document Viewer API, רנדר PDF Word Excel Image Diagram HTML"
head_description: "C# ASP.NET מציג קבצים וממשק API לעיבוד. הוסף מציג PDF, מציג Word, מציג Excel, מציג תמונות, מציג HTML, באפליקציות NET."

############################# Header ##########################
title: "עיבוד והצג מסמכים באמצעות .NET API"
description: "NET Document Viewer API לעיבוד 190+ פורמטים של מסמכים ל-PDF, HTML ותמונה עם אפשרויות תצורה חזקות."
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Download Free Trial"
    link: "https://downloads.groupdocs.com/viewer/net"

############################# SubMenu #########################
submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Viewer for .NET"
        image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-viewer-net.png"
        product: "GroupDocs.Viewer"
        platform: ".NET"

    middle:
        button:
            # button loop
            - link: "#overview"
              text: "סקירה כללית"

            # button loop
            - link: "#features"
              text: "מאפיינים"

            # button loop
            - link: "#support"
              text: "תמיכה"

            # button loop
            - link: "https://products.groupdocs.app/viewer/total"
              text: "דמו ישיר"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "תמחור"

    right:
        link_download: "https://releases.groupdocs.com/viewer/net/"
        link_learn: "https://docs.groupdocs.com/viewer/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    content: |
      GroupDocs.Viewer עבור ממשקי API של .NET עוזרים לך ליצור יישומים רבי עוצמה ב-C#, ASP.NET וטכנולוגיות אחרות המבוססות על .NET, שיכולים לרנדר ולהציג מסמכים ותמונות של יותר מ-190 פורמטים של קבצים מבלי להתקין תוכנה חיצונית כלשהי. ספריית מציג הקבצים מבצעת רסטר של המסמכים ולאחר מכן ממירה אותם ל-SVG+HTML+CSS כדי לייעל את חוויית עיבוד המסמכים הכוללת לצפייה במסמכים עסקיים, תמונות, קבצי טקסט, דיאגרמות, גרפיקה, קבצי דואר אלקטרוני וקבצי PDF במהירות, טקסט אמיתי ו נאמנות גבוהה בתוך היישומים שלך. יש לך אפשרות להוסיף פונקציונליות של צפייה וקריאה של מסמכים באפליקציות שלך כדי להציג מסמך שלם, מסמך חלקי, טווח דפים/תאים ספציפיים, שכבת מסמך בודדת, עם או בלי הערות והערות עבור פורמטי הקובץ הנתמכים.
       
      GroupDocs.Viewer עבור NET מאחסן במטמון את פלט המסמכים המעובדים לדיסק המקומי כברירת מחדל. כל סוג של אחסון מטמון חיצוני נתמך גם על ידי הטמעת ממשקים מתאימים - Amazon S3, Dropbox, Google Drive, Windows Azure, Redis או כל אחר.
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          להלן סקירה כללית של GroupDocs.Viewer עבור .NET:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "סקירה כללית"
          content: |
            * הצג 190+ סוגי מסמכים 
            * קבל קובץ בפורמט HTML, תמונה, PDF 
            * סובב וסדר מחדש 
            * החל סימן מים 
            * מטמון עבור תהליך מהיר 
            * הוסף גופנים מותאמים אישית 
            * החל תקני קידוד 
            * מטפל בנתוני קלט מותאם אישית 
            * עיבוד עם מעקב אחר שינויים 
            * עיבוד כ-HTML רספונסיבי 
            * עיבוד שכבות PDF ו-CAD 
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Viewer עבור .NET תומך בצפייה בכל הפורמטים הפופולריים של קבצי מסמכים. עם מספר שורות קוד בלבד, הוסף את מציג PDF, Microsoft Office Word, גיליון אלקטרוני של Excel, תמונה, HTML, Outlook, OneNote, Project ויכולות צפייה בגרפיקה ביישומי NET שלך.

        left:
          enable: true
          table:
            # table loop
            - title: "Microsoft Office"
              content: |
                * **Word:** DOC, DOCX, DOCM, DOT, DOTX, DOTM, RTF, TXT
                * **Excel:** XLS, XLSX, XLSM, XLSB, XLTM, XLT, XLTM, XLTX, XLAM, SXC, SpreadsheetML
                * **PowerPoint:** PPT, PPTX, PPS, PPSX, PPSM, POT, POTM, POTX, PPTM
                * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
                * **Project:** MPP, MPT, MPX
                * **Outlook:** MSG, EML, EMLX, PST, OST
                * **OneNote:** ONE

            # table loop
            - title: "Other Formats"
              content: |
                * **קבצי פריסת עמוד:** PDF, TEX, XPS, OXPS
                * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG, OTG, FODP, FODG
                * **ערכים מופרדים במפריד:** CSV, TSV
                * **אינטרנט:** HTML, MHT, MHTML
                * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
                * **PostScript:** PS, EPS
                * **אַרְכִיוֹן:** ZIP, TAR, BZ2, GZ, RAR, RAR5
                * **שׁוֹנִים:** OBJ, EPUB, MOBI, DjVu, XML, VCF, VCARD, NUMBERS, NSF

        right:
          enable: true
          table:
            # table loop
            - title: "תמונות, גרפיקה ודיאגרמות"
              content: |
                * **תמונות:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB
                * **סמל Windows:** ICO
                * **גרפיקה וקטורית ניתנת להרחבה:** SVG, CDR, CMX, IGS, SVGZ
                * **Jpeg2000:** JP2, J2C, J2K, JPC, JPF, JPX, JPM
                * **אדוב פוטושופ:** PSD, PSB
                * **שפת פיקוד מדפסת:** PCL
                * **ליטוגרפיה סטריאו (הדפסת תלת מימד):** STL
                * **שיעורי קרן התעשייה:** IFC
                * **הדמיה רפואית:** DICOM
                * **מסמכי פלוטר:** PLT, HPG
                * **Autodesk Design פורמטי אינטרנט:** DWF, DWG
                * **ציור אוטוקאד:** DWT, IFC, STL, CF2
                * **DGN מבוסס ISFF (V7):** DGN

            # table loop
            - title: "פורמטים של שפות תכנות"
              content: |
                * **קבצי C/C++/C#:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
                * **קבצי Java/JavaScript:** JAVA, JS, JSON, PROPERTIES
                * **שׁוֹנִים:** VB, PHP, SQL, PL, PY, PV, RB, RST, SASS, SCALA, SCM, SCRIPT, AS, AS3, ASM, BAT, CMAKE, CSS, DIFF, ERB, GROOVY, HAML, LESS, LOG, M, MAKE, MD, ML, MM, SH, SML, VIM, YAML

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Viewer עבור .NET תומך במנהלי מערכות הפעלה, מסגרות וחבילות הבאות:
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "מערכות הפעלה"
              content: |
                * Microsoft Windows Server 2003 ואילך 
                * Microsoft Windows XP ואילך 
                * Microsoft Windows 10 ו-11 
                * לינוקס (Ubuntu, OpenSUSE, CentOS ואחרים) 
                * Mac OS X 

            # table loop
            - icon: "fas fa-code"
              title: "מסגרות נתמכות"
              content: |
                * .NET Framework 2.0 ומעלה 
                * .NET Core 3.1 
                * .NET 5 ומעלה 

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-box"
              title: "מנהל אריזה"
              content: |
                * NuGet

            # table loop
            - icon: "fas fa-tools"
              title: "סביבות פיתוח"
              content: |
                * Microsoft Visual Studio
                * Visual Studio Code
                * .NET CLI

############################# Features ############################
features:
    enable: true
    title: "תכונות GroupDocs.Viewer עבור NET"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "רסטר מסמכים והמר אותם ל-SVG, HTML ו-CSS"

      # feature loop
      - icon: "fas fa-eye"
        content: "המר טקסט ל-HTML ועבד מסמכים כדי לקבל ייצוג HTML, תמונה או PDF"

      # feature loop
      - icon: "fas fa-bolt"
        content: "זמן טעינה מהיר יותר באמצעות גרסאות שמור של מסמכים"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "המר מצגות עם צורות וטקסט עם אפקטים תלת מימדיים"

      # feature loop
      - icon: "fas fa-code"
        content: "קידוד מסמכי Word, Excel ל לתקן הקידוד הרצוי"

      # feature loop
      - icon: "fas fa-cloud"
        content: "עיבוד מסמכים הממוקמים ב-FTP או ב-Cloud Storage"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "לא כולל גופנים בעת עיבוד ל-HTML כדי להקטין את גודל הקובץ המתקבל"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "הקטנת פלט CSS ו-HTML על ידי הסרת הערות, רווחים לבנים נוספים וכו'."

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "קרא את הטקסט הכלול במסמך מקור דרך הקואורדינטות שלו"

      # feature loop
      - icon: "fas fa-border-all"
        content: "הצג/הסתר את קווי הרשת של גיליונות Excel בייצוג פלט"

      # feature loop
      - icon: "fas fa-wrench"
        content: "ציין את מספר השורות בגיליון Excel לעיבוד בכל עמוד"

      # feature loop
      - icon: "fas fa-columns"
        content: "התעלם מעמודות ריקות בזמן עיבוד מסמכי גיליון אלקטרוני"

      # feature loop
      - icon: "fas fa-file-word"
        content: "עבד מסמכי Word לדפי HTML, תמונות או PDF, עם מעקב אחר שינויים"

      # feature loop
      - icon: "fas fa-envelope"
        content: "עיבוד קבצים מצורפים קבצים מקוריים, תמונות או בייצוג HTML"

      # feature loop
      - icon: "fas fa-print"
        content: "הגדר הגבלות הדפסה על מסמכי PDF"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "עיבוד תוכן/קבצים הכלולים בארכיון ZIP כקבצים מצורפים"

      # feature loop
      - icon: "fas fa-lock"
        content: "השג קבצים מצורפים ממסמכים המוגנים באמצעות סיסמה"

      # feature loop
      - icon: "fas fa-file-code"
        content: "עיבוד תבניות קבצים של שפות תכנות כטקסט רגיל"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "התאם את צבעי הרקע בעת צפייה בציורי CAD"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "הצג מסמכי Excel והמר ל-PDF, HTML, JPG ו-PNG"

      # feature loop
      - icon: "fas fa-heading"
        content: "קבל שמות גליונות עבודה מקובץ Excel - הצג כותרות עמודות ומספרי שורות בגיליון אלקטרוני"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "הצג והמר מסמכי Microsoft Project עם הערות"

      # feature loop
      - icon: "fas fa-cube"
        content: "המר שרטוטי CAD ל-SVG לחוויית צפייה והתקרבות טובה יותר"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "בחר לעבד דמויות Visio ללא Scheme"

    more_feature:
      # more_feature_loop
      - title: "הצג מסמכים ביעילות ובאמינות"
        content: |
          באמצעות GroupDocs.Viewer API אתה יכול להציג יותר מ-190 פורמטים של מסמכים ביעילות ובאמינות עם שלמות התוכן ומבנה המסמך ללא פגע. הקוד לדוגמה הבא מראה כמה קל לראות ייצוג HTML של מסמך DOCX:

          ```cs
          // Instantiate viewer
          using (Viewer viewer = new Viewer("invoice.docx"))
          {
              // Set view options
              HtmlViewOptions options = HtmlViewOptions.ForEmbeddedResources();
              // Convert file to HTML with embedded resources
              viewer.View(options);
          }
          ```
      # more_feature_loop
      - title: "החל טרנספורמציה על פלט מעובד"
        content: "אתה יכול לבצע טרנספורמציות שונות למסמך הפלט המעובד באמצעות GroupDocs.Viewer עבור .NET API. אפשרויות טרנספורמציה אלו נותנות לך שליטה על הדרך שבה אתה מציג את הפלט המעובד לתצוגה. התמורות הזמינות הן, אפשרות סיבוב עמוד, אפשרות לסדר מחדש של עמודים והחלת סימן מים של טקסט."

      # more_feature_loop
      - title: "עבודה עם קבצי נתונים של Outlook"
        content: "GroupDocs.Viewer עבור .NET API יכול לעבד את הפריטים בקובצי נתונים של Outlook (OST/PST) כ-PDF, HTML וקובצי תמונה. ל-Viewer API שלנו יש גם את היכולת להשיג את רשימת התיקיות הכלולות ב-Outlook Data Files. באמצעות GroupDocs.Viewer עבור .NET API, אתה יכול לציין את התיקיה לעיבוד מקובצי נתונים של Outlook. באופן דומה, אתה יכול גם לקבל הודעות דואר אלקטרוני הכלולות בפורמטים של OST/PST כקבצים מצורפים. GroupDocs.Viewer עבור .NET גם מאפשר לך לסנן הודעות מפורמטים של OST/PST על סמך נושא, תוכן או שולח."

      # more_feature_loop
      - title: "עבודה עם מסמכי CAD"
        content: "GroupDocs.Viewer עבור .NET API יכול לרנדר את המודל ואת כל הפריסות הלא ריקות או לעבד פריסה ספציפית של קובץ CAD. GroupDocs.Viewer עבור .NET API תומך גם בעיבוד אריחים או בעיבוד לפי קואורדינטות של מסמכי CAD לתמונה, HTML או PDF. אתה יכול גם לקבל סטטוסי שכבות עבור מסמכי CAD."

############################# Testimonials ###############################
testimonials:
  enable: true

  testimonial:
    # testimonial item loop
    - name: "Margot Baill"
      designation: "מנהל פיתוח מוצר בחברת Hireology"
      content: "שילוב GroupDocs.Viewer עבור Cloud API היה פשוט עם Ruby SDK הפנטסטי שלהם. אין כל כך הרבה חברות שמוכנות לעבוד איתנו במה שאנחנו רוצים. זו שותפות נהדרת."

    # testimonial item loop
    - name: "Mats Oustad"
      designation: "יועץ/שותף בכיר בחברת Novanet AS"
      content: "לאחר הטמעה ושימוש ב- GroupDocs.Viewer עבור NET בפרויקט, נראה שהוא עובד טוב מאוד. בדקתי עם הרבה מסמכים ועד כה הכל טוב. כל מה שזרקתי עליו מוצג יפה ונראה טוב בדיוק כמו במציג PDF או MS Word."
              
    # testimonial item loop
    - name: "Martin Lasarga"
      designation: "מנהל מוצר ב-Axentria ECM על ידי G.S.I."
      content: "שירות מעולה ומוצרים מעולים. הם היו מאוד מועילים ומגיבים במהלך תהליך ההטמעה של GroupDocs.Viewer עבור .NET, לא יכול להמליץ ​​עליהם מספיק."

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Viewer מציע ממשקי API לצפייה במסמכים עבור סביבות פיתוח פופולריות אחרות"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Viewer for Java"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-viewer-java.png"
          product: "GroupDocs.Viewer"
          platform: "Java"
          link: "/viewer/java/"

############################# Back to top ###############################
back_to_top:
  enable: true
---
