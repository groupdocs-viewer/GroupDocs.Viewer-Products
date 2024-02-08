---
############################# Static ############################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: ar
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
head_title: "Node.js Document Viewer API للصور ورسائل البريد الإلكتروني بتنسيق PDF وWord وExcel وHTML"
head_description: "عارض المستندات Node.js وواجهة برمجة تطبيقات عرض الملفات. أضف عارض PDF، وعارض Word، وعارض Excel، وعارض الصور، وعارض HTML، وعارض البريد الإلكتروني في تطبيقات JavaScript."

############################# Header ############################
title: "Node.js API لعرض وعرض المستندات"
description: "مكتبة عارض المستندات لتطوير تطبيقات JavaScript التي تعرض وتعرض وتعالج المستندات متعددة التنسيقات التي تدعم أكثر من 180 تنسيق ملف."
words:
  for: "for"

actions:
  main: "تنزيل NPM مجانًا"
  main_link: "https://www.npmjs.com/package/@groupdocs/groupdocs.viewer"
  alt: "الترخيص"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/nodejs-java"
  title: "على استعداد للبدء؟"
  description: "جرب ميزات GroupDocs.Viewer مجانًا أو اطلب ترخيصًا"

release:
  title: "تم إصدار الإصدار {0}."
  notes: "ترى ما هو الجديد"
  downloads: "التحميلات"
  link: "https://releases.groupdocs.com/viewer/nodejs-java/release-notes/latest/"

code:
  title: "تقديم ملفات PDF في جافا سكريبت"
  more: "مزيد من الأمثلة"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Node.js-via-Java"
  install: "npm i @groupdocs/groupdocs.viewer"
  content: |
    ```javascript {style=abap}       
    // قم بتعيين خيارات HTML للإخراج، ملف واحد لكل صفحة
    const viewOptions = HtmlViewOptions.forEmbeddedResources()
    
    // إنشاء مثيل للعارض
    const viewer = new Viewer("resume.pdf")

    // تحويل PDF إلى HTML باستخدام الموارد المضمنة
    viewer.view(viewOptions)
    viewer.close()
    ```
############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Viewer في لمحة"
  description: "واجهة برمجة التطبيقات (API) لعرض وعرض وتحويل المستندات والشرائح والرسوم البيانية والعديد من أنواع المستندات الأخرى في تطبيقات Node.js"
  features:
    # feature loop
    - title: "عرض المستندات بكفاءة وموثوقية"
      content: "باستخدام GroupDocs.Viewer API، يمكنك عرض المستندات بكفاءة من أي تنسيقات مدعومة إلى HTML وJPEG وPNG وPDF مع خيارات مرنة وقوية مع الحفاظ على سلامة المحتوى وبنية المستند. يعمل GroupDocs.Viewer for Node.js على نظامي التشغيل Windows وLinux."

    # feature loop
    - title: "يتم دعم تنسيقات الملفات والمستندات الأكثر شيوعًا"
      content: "نحن ندعم عرض أكثر من 180 تنسيقًا من تنسيقات الملفات والمستندات الأكثر شيوعًا والتي تشمل Word وExcel وPDF وPowerPoint ومجموعة تنسيقات OpenDocument والأرشيفات والصور النقطية والمتجهة والكتب الإلكترونية ولغات البرمجة والعلامات المميزة والعديد من أنواع الملفات الأخرى، بما في ذلك الملفات المشفرة الملفات مع حماية كلمة المرور."

    # feature loop
    - title: "إخراج قابل للتخصيص"
      content: "لا يسمح GroupDocs.Viewer بعرض المستند فحسب، بل يسمح أيضًا بالتحكم في كيفية عرض أجزاء المستند بالضبط أو الآن، وكيفية عرضها، وتطبيق تحويلات مختلفة على المخرجات المقدمة."

############################# Platforms ############################
platforms:
  enable: true
  title: "استقلالية المنصة"
  description: "يدعم GroupDocs.Viewer for Node.js أنظمة التشغيل وأطر العمل ومديري الحزم التالية"
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
  title: "تنسيقات الملفات المدعومة"
  description: |
    يدعم GroupDocs.Viewer لـ Node.js عبر Java العمليات باستخدام التالية [formats](https://docs.groupdocs.com/viewer/net/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office وOpenDocument وتنسيقات النص
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
        ### الصور والرسومات والرسوم البيانية
        * **الصور النقطية:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
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
        ### آخر        
        * **ويب:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **أرشيف:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **آخر:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "ميزات GroupDocs.Viewer"
  description: "عرض وعرض وتحويل مستندات PDF وOffice بسهولة"

  items:
    # feature loop
    - icon: "viewhtml"
      title: "عرض المستندات بتنسيق HTML"
      content: "قم بتحويل مستند من أي نوع إلى مستند HTML باستخدام CSS وSVG، والذي يمكن عرضه في أي متصفح ويب حديث."

    # feature loop
    - icon: "rasterize"
      title: "تنقيط المستندات"
      content: "قم بتنقيط أي تنسيق مستند مدعوم إلى الصورة النقطية، مع تنسيق صورة قابل للتعديل وجودة ضغط."

    # feature loop
    - icon: "sourcecode"
      title: "تقديم وإبراز رموز البرمجة"
      content: "دعم جميع لغات البرمجة والبرمجة النصية والترميزية الشائعة، مع القدرة على تحليل تركيبها وإبرازها."

    # feature loop
    - icon: "convertpdf"
      title: "تحويل إلى قوات الدفاع الشعبي"
      content: "يمكن بسهولة تحويل المستند بأي تنسيق مدعوم وحفظه إلى ملف PDF باستخدام خيارات قابلة للتعديل."

    # feature loop
    - icon: "transform"
      title: "تطبيق التحولات"
      content: "يمكن تحويل المستند الناتج أثناء العرض - يمكن تدوير الصفحات و/أو إعادة ترتيبها، ويمكن وضع علامة مائية نصية فوقها."

    # feature loop
    - icon: "adjustment"
      title: "تعديل إخراج HTML"
      content: "يمكن ضبط مستندات HTML الناتجة، التي تم إنشاؤها بواسطة GroupDocs.Viewer، بدقة شديدة: يُسمح بحفظها في الدفق أو الملف، باستخدام موارد خارجية أو مضمنة، وعمليات الاسترجاعات وما إلى ذلك."

    # feature loop
    - icon: "complex"
      title: "دعم هياكل المستندات المعقدة"
      content: "لا يدعم GroupDocs.Viewer المستندات الفردية فحسب، بل يدعم أيضًا الملفات التي تحتوي داخليًا على قائمة أو بنية هرمية للمستندات، مثل رسائل البريد الإلكتروني مع المرفقات وأرشيفات ZIP مع الملفات الداخلية داخل المجلدات وصور TIFF متعددة الصفحات وما إلى ذلك."

    # feature loop
    - icon: "optimization"
      title: "خيارات التحسين"
      content: "يحتوي GroupDocs.Viewer على نظام فرعي لذاكرة التخزين المؤقت قابل للتعديل، والذي يمكنه تسريع وقت التحميل باستخدام الإصدارات المخزنة مؤقتًا للمستندات. تسمح أيضًا مجموعة من الخيارات المختلفة للتنسيقات المختلفة باستبعاد بعض الأجزاء أو الجوانب غير الضرورية من المستندات من العرض (الخطوط وأوراق العمل المخفية ومرفقات البريد الإلكتروني) لتحسين الأداء العام"

    # feature loop
    - icon: "passwordprotected"
      title: "دعم المستندات المحمية بكلمة مرور"
      content: "يسمح GroupDocs.Viewer بفتح المستندات المشفرة بمختلف أنواعها: PDF وWordProcessing وSpreadsheet وPresentation وغيرها، وذلك عن طريق تحديد كلمة مرور في خيارات التحميل."

############################# Code samples ############################
code_samples:
  enable: true
  title: "عينات التعليمات البرمجية"
  description: "تستخدم بعض حالات GroupDocs.Viewer النموذجية لـ Node.js عبر عمليات Java"
  items:
    # code sample loop
    - title: "تقديم DOCX إلى HTML"
      content: |
        تيح لك خصائص فئة التحكم في عملية التحويل، المزيد عن ذلا على سبيل المثال، يمكنك تضمين كافة الموارد الخارجية في ملف HTML الناتج، وتصغير ملف الإخراج، وتحسينه للطباعة.
        {{< landing/code title="JavaScript">}}
        ```javascript {style=abap}
        import { Viewer, HtmlViewOptions } from '@groupdocs/groupdocs.viewer'

        // قم بتعيين خيارات HTML للإخراج، ملف واحد لكل صفحة
        const viewOptions = HtmlViewOptions.forEmbeddedResources()

        // إنشاء مثيل للعارض
        const viewer = new Viewer("resume.docx")

        // تحويل DOCX إلى HTML باستخدام الموارد المضمنة
        viewer.view(viewOptions)
        viewer.close()
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "تصدير PPTX إلى PDF"
      content: |
        قم بإنشاء مثيل فئة `PdfViewOptions` وقم بتمريره إلى طريقة `Viewer.view` لتحويل ملف PowerPoint PPTX إلى PDF. تتيح لك خصائص فئة `PdfViewOptions` التحكم في عملية التحويل. على سبيل المثال، يمكنك حماية ملف الناتج وإعادة ترتيب صفحاته وتحديد جودة صور المستند. راجع [PDF](https://docs.groupdocs.com/viewer/nodejs-java/rendering-to-pdf/) للحصول على التفاصيل.
        {{< landing/code title="JavaScript">}}
        ```javascript {style=abap}   
        import { Viewer, PdfViewOptions } from '@groupdocs/groupdocs.viewer'

        // ضبط خيارات إخراج PDF
        const viewOptions = new PdfViewOptions("presentation.pdf")

        // إنشاء مثيل للعارض
        const viewer = new Viewer("presentation.pptx")

        // تصدير PPTX إلى PDF
        viewer.view(viewOptions)
        viewer.close()
        ```
        {{< /landing/code >}}
############################# Reviews ############################
# reviews:
# enable: true
# title: "مراجعات منتجات GroupDocs"
# description: "لا تأخذ كلمتنا فقط. تعرف على ما يقوله المطورون الآخرون عن واجهات برمجة التطبيقات الخاصة بنا"

# items:
#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "خدمة ممتازة ومنتجات ممتازة. لقد كانت مفيدة للغاية وسريعة الاستجابة أثناء عملية تنفيذ GroupDocs.Viewer for .NET، ولا يمكنني أن أوصي بها بدرجة كافية."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "بعد تنفيذ واستخدام GroupDocs.Viewer لـ .NET في المشروع، يبدو أنه يعمل بشكل جيد جدًا. لقد اختبرت مع الكثير من الوثائق وحتى الآن جيدة جدًا. يتم عرض كل شيء قمت بتطبيقه بشكل جيد ويبدو جيدًا تمامًا كما هو الحال في عارض PDF أو MS Word."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---
