---
############################# Static ############################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: uk
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
    # supported_platforms loop
    - title: "Python"
      tag: "python-net"


############################# Head ############################
head_title: "API засобу перегляду документів Node.js для PDF Word Excel HTML зображень і електронних листів"
head_description: "Переглядач документів Node.js і API відтворення файлів. Додайте засіб перегляду PDF, Word, Excel, зображень, HTML, електронної пошти в програмах JavaScript."

############################# Header ############################
title: "API Node.js для візуалізації та відображення документів"
description: "Бібліотека засобу перегляду документів для розробки додатків JavaScript, які нативно відтворюють, переглядають і маніпулюють багатоформатними документами, що підтримують понад 180 форматів файлів."
words:
  for: "for"

actions:
  main: "Безкоштовне завантаження NPM"
  main_link: "https://www.npmjs.com/package/@groupdocs/groupdocs.viewer"
  alt: "Ліцензування"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/nodejs-java"
  title: "Готові почати?"
  description: "Спробуйте функції GroupDocs.Viewer безкоштовно або подайте запит на ліцензію"

release:
  title: "Випущено версію {0}"
  notes: "Подивіться, що нового"
  downloads: "Завантаження"
  link: "https://releases.groupdocs.com/viewer/nodejs-java/release-notes/latest/"

code:
  title: "Відтворення файлів PDF у JavaScript"
  more: "Більше прикладів"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Node.js-via-Java"
  install: "npm i @groupdocs/groupdocs.viewer"
  content: |
    ```javascript {style=abap}       
    // Встановити вихідні параметри HTML
    const viewOptions = HtmlViewOptions.forEmbeddedResources()
    
    // Переглядач екземплярів
    const viewer = new Viewer("resume.pdf")

    // Перетворіть PDF у HTML
    viewer.view(viewOptions)
    viewer.close()
    ```
############################# Overview ############################
overview:
  enable: true
  title: "Короткий огляд GroupDocs.Viewer"
  description: "API для візуалізації, відображення, перетворення документів, слайдів, діаграм і багатьох інших типів документів у програмах Node.js"
  features:
    # feature loop
    - title: "Переглядайте документи ефективно та надійно"
      content: "За допомогою API GroupDocs.Viewer ви можете ефективно відтворювати документи будь-яких підтримуваних форматів у HTML, JPEG, PNG і PDF за допомогою гнучких і потужних параметрів, зберігаючи цілісність вмісту та структури документа. GroupDocs.Viewer для Node.js працює на платформах Windows і Linux."

    # feature loop
    - title: "Підтримуються більшість популярних форматів файлів і документів"
      content: "Ми підтримуємо відтворення понад 180 найпопулярніших форматів файлів і документів, включаючи Word, Excel, PDF, PowerPoint, сімейство форматів OpenDocument, архіви, растрові та векторні зображення, електронні книги, мови програмування та розмітки, а також багато інших типів файлів, у тому числі зашифрованих. файли із захистом паролем."

    # feature loop
    - title: "Настроюваний вихід"
      content: "GroupDocs.Viewer дозволяє не тільки візуалізувати документ, але й контролювати, як саме, які частини документа мають бути візуалізовані або зараз, як вони мають бути візуалізовані, а також застосовувати різні трансформації до відрендерених результатів."

############################# Platforms ############################
platforms:
  enable: true
  title: "Незалежність від платформи"
  description: "GroupDocs.Viewer для Node.js підтримує такі операційні системи, фреймворки та менеджери пакетів"
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
  title: "Підтримувані формати файлів"
  description: |
    GroupDocs.Viewer для Node.js через Java підтримує операції з такими [форматами файлів](https://docs.groupdocs.com/viewer/nodejs-java/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office, OpenDocument і текстові формати
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
        ### Зображення, графіки та діаграми
        * **Растрові зображення:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
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
        ### Інший        
        * **Інтернет:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **Архіви:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **Інший:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "Функції GroupDocs.Viewer"
  description: "Легко візуалізуйте, відображайте та конвертуйте документи PDF і Office"

  items:
    # feature loop
    - icon: "viewhtml"
      title: "Перегляд документів у HTML"
      content: "Перетворіть документ будь-якого типу в документ HTML за допомогою CSS і SVG, який можна відобразити в будь-якому сучасному веб-браузері."

    # feature loop
    - icon: "rasterize"
      title: "Растеризуйте документи"
      content: "Растеризуйте будь-який підтримуваний формат документа до растрового зображення з регульованим форматом зображення та якістю стиснення."

    # feature loop
    - icon: "sourcecode"
      title: "Відтворення та виділення програмних кодів"
      content: "Підтримка всіх популярних мов програмування, сценаріїв і розмітки з можливістю аналізу та виділення їх синтаксису."

    # feature loop
    - icon: "convertpdf"
      title: "Перетворити в PDF"
      content: "Документ будь-якого підтримуваного формату можна легко конвертувати та зберегти у PDF із настроюваними параметрами."

    # feature loop
    - icon: "transform"
      title: "Застосувати перетворення"
      content: "Вихідний документ можна трансформувати під час візуалізації - сторінки можна обертати та/або змінювати порядок, а текстовий водяний знак можна розміщувати поверх них."

    # feature loop
    - icon: "adjustment"
      title: "Налаштування виведення HTML"
      content: "Вихідні HTML-документи, згенеровані GroupDocs.Viewer, можна дуже точно налаштувати: дозволено зберігати в потік або файл із зовнішніми або вбудованими ресурсами, зворотними викликами тощо."

    # feature loop
    - icon: "complex"
      title: "Підтримка складних структур документів"
      content: "GroupDocs.Viewer підтримує не лише окремі документи, а й файли, які містять список або ієрархічну структуру документів, як-от повідомлення електронної пошти з вкладеннями, ZIP-архіви з внутрішніми файлами в папках, багатосторінкові зображення TIFF тощо."

    # feature loop
    - icon: "optimization"
      title: "Варіанти оптимізації"
      content: "GroupDocs.Viewer містить регульовану підсистему кешу, яка може пришвидшити час завантаження за допомогою кешованих версій документів. Крім того, набір різних параметрів для різних форматів дозволяє виключити деякі непотрібні частини або аспекти документів із візуалізації (шрифти, приховані аркуші, вкладення електронної пошти), щоб оптимізувати загальну продуктивність"

    # feature loop
    - icon: "passwordprotected"
      title: "Підтримка документів, захищених паролем"
      content: "GroupDocs.Viewer дозволяє відкривати зашифровані документи різних типів: PDF, WordProcessing, Spreadsheet, Presentation та інші, вказавши пароль у параметрах завантаження."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Зразки коду"
  description: "Деякі випадки використання типового GroupDocs.Viewer для Node.js через операції Java"
  items:
    # code sample loop
    - title: "Перетворення DOCX у HTML"
      content: |
        Властивості класу `HtmlViewOptions` дозволяють контролювати процес перетворення, докладніше про це [тут](https://docs.groupdocs.com/viewer/nodejs-java/rendering-to-html/). Наприклад, ви можете вбудувати всі зовнішні ресурси у вихідний HTML-файл, зменшити вихідний файл і оптимізувати його для друку.
        {{< landing/code title="JavaScript">}}
        ```javascript {style=abap}
        import { Viewer, HtmlViewOptions } from '@groupdocs/groupdocs.viewer'

        // Встановити вихідні параметри HTML
        const viewOptions = HtmlViewOptions.forEmbeddedResources()

        // Переглядач екземплярів
        const viewer = new Viewer("resume.docx")

        // Перетворіть DOCX у HTML за допомогою вбудованих ресурсів
        viewer.view(viewOptions)
        viewer.close()
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Експорт PPTX у PDF"
      content: |
        Створіть екземпляр класу `PdfViewOptions` і передайте його методу `Viewer.view`, щоб перетворити файл PowerPoint PPTX у PDF. Властивості класу `PdfViewOptions` дозволяють контролювати процес перетворення. Наприклад, ви можете захистити вихідний PDF-файл, змінити порядок його сторінок і вказати якість зображень документів. Зверніться до [розділу наступної документації](https://docs.groupdocs.com/viewer/nodejs-java/rendering-to-pdf/), щоб дізнатися більше.
        {{< landing/code title="JavaScript">}}
        ```javascript {style=abap}   
        import { Viewer, PdfViewOptions } from '@groupdocs/groupdocs.viewer'

        // Встановіть параметри вихідного PDF
        const viewOptions = new PdfViewOptions("presentation.pdf")

        // Переглядач екземплярів
        const viewer = new Viewer("presentation.pptx")

        // Експорт PPTX у PDF
        viewer.view(viewOptions)
        viewer.close()
        ```
        {{< /landing/code >}}
############################# Reviews ############################
# reviews:
# enable: true
# title: "Огляди продукції GroupDocs"
# description: "Не вірте нам на слово. Подивіться, що інші розробники кажуть про наші API"

# items:
#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "Відмінний сервіс і відмінні продукти. Вони були надзвичайно корисними та чуйними під час впровадження GroupDocs.Viewer для .NET, тому не можу рекомендувати їх досить високо."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "Після впровадження та використання GroupDocs.Viewer для .NET у проекті виглядає, що він працює дуже добре. Я перевірив багато документів, і поки що все добре. Усе, що я кинув до нього, чудово відображається та виглядає так само добре, як у засобі перегляду PDF чи MS Word."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---
