---
############################# Static ##########################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: uk
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

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
head_title: "API засобу перегляду документів .NET, візуалізація PDF Word Excel Зображення HTML Діаграма"
head_description: "Перегляд файлів C# ASP.NET і API відтворення. Додайте функції перегляду PDF, Word, Excel, зображень, HTML, електронної пошти в програмах .NET."

############################# Header ##########################
title: "Рендеринг і відображення документів<br>за допомогою .NET API"
description: "Потужний API Viewer для перетворення понад 180 форматів документів у PDF, HTML і зображення з різноманітними параметрами конфігурації."
words:
  for: "for"

actions:
  main: "Безкоштовне завантаження NuGet"
  main_link: "https://www.nuget.org/packages/GroupDocs.Viewer"
  alt: "Ліцензування"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/net"
  title: "Готові почати?"
  description: "Спробуйте функції GroupDocs.Viewer безкоштовно або подайте запит на ліцензію"

release:
  title: "Випущено версію {0}"
  notes: "Подивіться, що нового"
  downloads: "Завантаження"
  link: "https://releases.groupdocs.com/viewer/net/release-notes/latest/"

code:
  title: "Рендер PDF-файлів у C#"
  more: "Більше прикладів"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
  install: "dotnet add package GroupDocs.Viewer"
  content: |
    ```csharp {style=abap}   
    // Завантажте вихідний файл PDF
    using (var viewer = new Viewer("resume.pdf"))
    {
        // Встановити вихідні параметри HTML
        var viewOptions = 
        HtmlViewOptions.ForEmbeddedResources("page{0}.html");
        
        // Перетворіть PDF у HTML        
        viewer.View(viewOptions);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "Короткий огляд GroupDocs.Viewer"
  description: "API для відтворення, відображення, перетворення документів, слайдів, діаграм і багатьох інших типів документів у програмах .NET"
  features:
    # feature loop
    - title: "Переглядайте документи ефективно та надійно"
      content: "За допомогою API GroupDocs.Viewer ви можете ефективно відтворювати документи будь-яких підтримуваних форматів у HTML, JPEG, PNG і PDF за допомогою гнучких і потужних параметрів, зберігаючи цілісність вмісту та структури документа. GroupDocs.Viewer підтримує .NET Framework 4.6.2 і .NET 6.0, працює на платформах Windows і Linux."

    # feature loop
    - title: "Підтримуються більшість популярних форматів файлів і документів"
      content: "Ми підтримуємо відтворення понад 180 найпопулярніших форматів файлів і документів, включаючи Word, Excel, PDF, PowerPoint, сімейство форматів OpenDocument, архіви, растрові та векторні зображення, електронні книги, мови програмування та розмітки, а також багато інших типів файлів, у тому числі зашифрованих. файли із захистом паролем."

    # feature loop
    - title: "Настроюваний вихід"
      content: "GroupDocs.Viewer дозволяє не тільки візуалізувати документ, але й контролювати, як саме, які частини документа мають бути візуалізовані або зараз, як вони мають бути візуалізовані, а також застосовувати різні трансформації до відрендерених результатів."

    # feature loop
    - title: "Інтерфейс користувача для ASP.NET Core"
      content: "Ми надаємо пакет інтерфейсу користувача з відкритим кодом для ASP.NET Core, який можна додати до вашого проекту за пару хвилин. Пакет Viewer.UI містить веб-інтерфейс на основі Angular і надає набір корисних API і постачальників даних для зберігання."

############################# Platforms ############################
platforms:
  enable: true
  title: "Підтримка платформ"
  description: "GroupDocs.Viewer для .NET підтримує такі операційні системи, фреймворки та менеджери пакетів"
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
    - title: "VS Code"
      image: "vs_code"
    # platform loop
    - title: "ReSharper"
      image: "resharper"
    # platform loop
    - title: "macOS"
      image: "finder"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "NuGet"
      image: "nuget"
  packages:
    # packages loop
    - title: "Спеціальний пакет для Windows"
      content: |
        * Підтримує .NET Framework 4.6.2+ і .NET 6.0
        * Найбільш повна підтримка форматів файлів
        * Залежить від System.Drawing і System.Drawing.Common 
      action: "Завантажити NuGet"
      action_link: "https://www.nuget.org/packages/GroupDocs.Viewer"
    # packages loop
    - title: "Кросплатформенний пакет" 
      content: |
        * Підтримує .NET 6.0 і новіші версії 
        * Обмежена підтримка форматів файлів 
        * Працює на Windows, Linux і macOS 
      action: "Завантажити NuGet" 
      action_link: "https://www.nuget.org/packages/GroupDocs.Viewer.CrossPlatform" 

############################# File formats ############################
formats:
  enable: true
  title: "Підтримувані формати файлів"
  description: |
    GroupDocs.Viewer для .NET підтримує операції з такими [форматами файлів](https://docs.groupdocs.com/viewer/net/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office, OpenDocument і текстові формати
        * **Word:** DOC, DOCX, DOCM, DOT, DOTX, DOTM, RTF, TXT
        * **Excel:** XLS, XLSX, XLSM, XLSB, XLTM, XLT, XLTM, XLTX
        * **PowerPoint:** PPT, PPTX, PPS, PPSX, PPSM, POT, POTM, POTX, PPTM        
        * **Project:** MPP, MPT, MPX {{< landing/tooltip icon="windows" title="Підтримується спеціальним пакетом Windows" >}}
        * **Outlook:** MSG, EML, EMLX, PST, OST
        * **OneNote:** ONE {{< landing/tooltip icon="windows" title="Підтримується спеціальним пакетом Windows" >}}
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
        * **Adobe Photoshop:** PSD, PSB {{< landing/tooltip icon="windows" title="Підтримується спеціальним пакетом Windows" >}}       
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
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM {{< landing/tooltip icon="windows" title="Підтримується спеціальним пакетом Windows" >}}
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
  description: "Деякі випадки використання типових операцій GroupDocs.Viewer для .NET"
  items:
    # code sample loop
    - title: "Перетворення DOCX у HTML"
      content: |
        Властивості класу [HtmlViewOptions](https://reference.groupdocs.com/viewer/net/groupdocs.viewer.options/htmlviewoptions/) дозволяють контролювати процес перетворення, більше про це [тут](https://docs.groupdocs.com/viewer/net/rendering-to-html/). Наприклад, ви можете вбудувати всі зовнішні ресурси у вихідний HTML-файл, зменшити вихідний файл і оптимізувати його для друку.
        {{< landing/code title="C#">}}
        ```csharp {style=abap}
        using GroupDocs.Viewer;
        using GroupDocs.Viewer.Options;
        
        // Переглядач екземплярів
        using (Viewer viewer = new Viewer("resume.docx"))
        {
            // Встановіть параметри вихідного HTML
            HtmlViewOptions options = HtmlViewOptions.ForEmbeddedResources();
            
            // Перетворіть DOCX у HTML за допомогою вбудованих ресурсів
            viewer.View(options);
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Експорт PPTX у PDF"
      content: |
        Створіть екземпляр класу [PdfViewOptions](https://reference.groupdocs.com/viewer/net/groupdocs.viewer.options/pdfviewoptions/) і передайте його в [Viewer.View](https://reference.groupdocs.com/viewer/net/groupdocs.viewer/viewer/view/#view) для перетворення файлу PowerPoint PPTX у PDF. Властивості класу PdfViewOptions дозволяють контролювати процес перетворення. Наприклад, ви можете захистити вихідний PDF-файл, змінити порядок його сторінок і вказати якість зображень документів. Зверніться до [наступного розділу документації](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/), щоб дізнатися більше.
        {{< landing/code title="C#">}}
        ```csharp {style=abap}   
        using GroupDocs.Viewer;
        using GroupDocs.Viewer.Options;
        
        using (var viewer = new Viewer("presentation.pptx"))
        {
            // Встановіть параметри вихідного PDF       
            var viewOptions = new PdfViewOptions("presentation.pdf");
            
            // Експорт PPTX у PDF       
            viewer.View(viewOptions);
        }
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