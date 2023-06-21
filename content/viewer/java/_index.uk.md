---
############################# Static ############################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

lang: uk
product: "Viewer"
product_tag: "viewer"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "API перегляду документів Java для PDF Word Excel HTML зображень і електронних листів"
head_description: "API для перегляду документів Java та відтворення файлів. Додайте засіб перегляду PDF, Word, Excel, зображень, HTML, електронної пошти в програмах Java."

############################# Header ############################
title: "Java API для візуалізації та відображення документів"
description: "Бібліотека засобу перегляду документів для розробки додатків Java, які власноруч відтворюють, переглядають і маніпулюють багатоформатними документами, що підтримують понад 170 форматів файлів."
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Download Free Trial"
    link: "https://downloads.groupdocs.com/viewer/java"

############################# SubMenu ############################
submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Viewer for Java"
        image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-viewer-java.png"
        product: "GroupDocs.Viewer"
        platform: "Java"

    middle:
        button:
            # button loop
            - link: "#overview"
              text: "Огляд"

            # button loop
            - link: "#features"
              text: "особливості"

            # button loop
            - link: "#support"
              text: "Підтримка"

            # button loop
            - link: "https://products.groupdocs.app/viewer/total"
              text: "Жива демо"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/java"
              text: "Ціноутворення"

    right:
        link_download: "https://releases.groupdocs.com/viewer/java/"
        link_learn: "https://docs.groupdocs.com/viewer/java/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    content: |
      GroupDocs.Viewer для Java поєднує в собі потужний набір API перегляду документів для відображення зображень і форматів документів у ваших програмах Java без необхідності встановлення додаткового програмного забезпечення. Він оригінально растеризує документи та перетворює їх у SVG+HTML+CSS, щоб підвищити якість перегляду документів, забезпечуючи вихід правдивого тексту з високою точністю. Використовуючи API відтворення документів – швидко переглядайте PDF, HTML, XML, Microsoft Office Word, робочі аркуші Excel, презентації PowerPoint, електронні листи Outlook, діаграми Visio, Project, метафайли, зображення та різноманітні інші формати файлів з легкістю та меншими ризиками програмування. Він також може відображати захищені паролем файли та давати змогу отримувати представлення документа у вигляді HTML, зображення або PDF-форми після візуалізації. Наша бібліотека перегляду файлів є досить настроюваною, оскільки вона дозволяє відображати весь документ або відтворювати його частково, щоб пришвидшити процес. За допомогою GroupDocs.Viewer для Java API ви можете переглядати сторінки, певний діапазон комірок в електронній таблиці або навіть відтворювати окремий шар документа у таких форматах, як PDF і CAD.  

      API GroupDocs.Viewer для Java дозволяє відтворювати документи з анотаціями чи коментарями або без них для підтримуваних форматів файлів. Це також дозволяє додавати спеціальні каталоги шрифтів і видобувати основну інформацію про документ, таку як тип файлу, розширення, ім’я, кількість сторінок тощо.  

      GroupDocs.Viewer для Java сумісний з усіма версіями Java і підтримує популярні операційні системи (Windows, Linux, macOS), які можуть запускати середовище виконання Java.
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          Нижче наведено огляд GroupDocs.Viewer для Java:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Огляд"
          content: |
            * Відображення понад 170 типів документів 
            * Отримайте HTML, зображення, PDF-версію 
            * Обертати та змінювати порядок 
            * Застосувати водяний знак 
            * Кеш для швидкого процесу 
            * Додати власні шрифти 
            * Застосуйте стандарти кодування 
            * Настроюваний обробник вхідних даних 
            * Відтворення з відстеженням змін 
            * Виводити як адаптивний HTML 
            * Відтворення шарів PDF і CAD 
            * Рендеринг захищених файлів 
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Viewer для Java підтримує всі популярні формати файлів документів, включаючи: Microsoft Office, зображення, діаграми та багато інших.

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
            - title: "Інші формати"
              content: |
                * **Файли макетів сторінок:** PDF, TEX, XPS, OXPS
                * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG, OTG, FODP, FODG
                * **Значення, розділені роздільниками:** CSV, TSV
                * **Інтернет:** HTML, MHT, MHTML
                * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
                * **PostScript:** PS, EPS
                * **Архіви:** ZIP, TAR, BZ2, GZ, RAR, RAR5
                * **різноманітні:** OBJ, EPUB, MOBI, DjVu, XML, VCF, VCARD, NUMBERS, NSF

        right:
          enable: true
          table:
            # table loop
            - title: "Зображення, графіки та діаграми"
              content: |
                * **Зображення:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB
                * **Значок Windows:** ICO
                * **Масштабована векторна графіка:** SVG, CDR, CMX, IGS, SVGZ
                * **Jpeg2000:** JP2, J2C, J2K, JPC, JPF, JPX, JPM
                * **Adobe Photoshop:** PSD, PSB
                * **Мова команд принтера:** PCL
                * **Стереолітографія (3D-друк):** STL
                * **Основні класи промисловості:** IFC
                * **Медична візуалізація:** DICOM
                * **Документи для плоттера:** PLT, HPG
                * **Веб-формати Autodesk Design:** DWF, DWG
                * **Креслення AutoCAD:** DWT, IFC, STL, CF2
                * **DGN на основі ISFF (V7):** DGN

            # table loop
            - title: "Формати мов програмування"
              content: |
                * **Файли C/C++/C#:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
                * **Файли Java/JavaScript:** JAVA, JS, JSON, PROPERTIES
                * **різноманітні:** VB, PHP, SQL, PL, PY, PV, RB, RST, SASS, SCALA, SCM, SCRIPT, AS, AS3, ASM, BAT, CMAKE, CSS, DIFF, ERB, GROOVY, HAML, LESS, LOG, M, MAKE, MD, ML, MM, SH, SML, VIM, YAML

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Viewer для Java підтримує наступні операційні системи, фреймворки та менеджери пакетів:
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Операційні системи"
              content: |
                * Microsoft Windows Server 2003 і новіших версій 
                * Microsoft Windows XP і новіших версій 
                * Microsoft Windows 10 і 11 
                * Linux (Ubuntu, OpenSUSE, CentOS та інші) 
                * Mac OS X 

            # table loop
            - icon: "fas fa-code"
              title: "Підтримувані фреймворки"
              content: |
                * J2SE 8.0 (1.8) або вище (наприклад, Java 17) 

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-cogs"
              title: "Середовища розробки"
              content: |
                * NetBeans
                * IntelliJ IDEA
                * Eclipse

            # table loop
            - icon: "fas fa-tools"
              title: "Інструмент автоматизації збірки"
              content: |
                * Maven
                * Gradle

############################# Features ############################
features:
    enable: true
    title: "GroupDocs.Viewer для функцій Java"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "Переглядач для HTML, PDF, зображень, Word, Excel та інших форматів документів"

      # feature loop
      - icon: "fas fa-eye"
        content: "Перетворення файлів креслень AutoCAD (DWG) у формат SVG"

      # feature loop
      - icon: "fas fa-bolt"
        content: "Налаштуйте колір фону конвертованого файлу"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "Растеризуйте та конвертуйте документи у SVG, HTML і CSS"

      # feature loop
      - icon: "fas fa-code"
        content: "Отримайте представлення документів у форматі HTML, зображення або PDF за допомогою візуалізації"

      # feature loop
      - icon: "fas fa-cloud"
        content: "Кешовані версії документів для швидшого завантаження"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "Налаштувати користувацькі каталоги шрифтів"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "Застосовуйте стандарти кодування до документів Word, Excel та електронної пошти"

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "Віддалено відтворюйте документи на FTP або в хмарному сховищі"

      # feature loop
      - icon: "fas fa-border-all"
        content: "Видаліть або збережіть анотації та коментарі під час візуалізації"

      # feature loop
      - icon: "fas fa-wrench"
        content: "Відтворення сторінок документа як окремих сторінок HTML"

      # feature loop
      - icon: "fas fa-columns"
        content: "Відобразити приховані слайди та сторінки та застосувати зміну порядку сторінок до відтвореного документа"

      # feature loop
      - icon: "fas fa-file-word"
        content: "Відтворення діапазону сторінок, певних сторінок або всіх сторінок у HTML"

      # feature loop
      - icon: "fas fa-envelope"
        content: "Відобразити або приховати коментарі документа"

      # feature loop
      - icon: "fas fa-print"
        content: "Створіть адаптивний HTML для деяких форматів документів за допомогою візуалізації"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "Зменшіть кінцевий розмір файлу відтвореного HTML шляхом виключення шрифтів"

      # feature loop
      - icon: "fas fa-lock"
        content: "Видаліть коментарі, зайві пробіли тощо, щоб мінімізувати вихідний HTML і CSS"

      # feature loop
      - icon: "fas fa-file-code"
        content: "Використовуйте координати вихідного документа, щоб прочитати текст, що міститься"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "Показати/сховати межу клітинок на аркушах Excel відтвореного результату"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "Відобразити певну кількість рядків кожної сторінки на аркуші Excel"

      # feature loop
      - icon: "fas fa-heading"
        content: "Відобразити модель і всі непорожні макети або окремий макет файлу CAD"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "Відтворення елементів у файлах даних Outlook (OST/PST) як PDF"

      # feature loop
      - icon: "fas fa-cube"
        content: "Візуалізація плиток або візуалізація за координатами документів САПР як зображення, HTML або PDF"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "Встановіть обмеження друку під час візуалізації у PDF"

    more_feature:
      # more_feature_loop
      - title: "Ефективний і надійний API для перегляду документів"
        content: |
          GroupDocs.Viewer для Java API можна використовувати для перегляду, візуалізації та відображення документів понад 150 різних форматів файлів. Це робиться надійно та ефективно, зберігаючи вміст і структуру документа недоторканими. У наведеному нижче прикладі показано рівень легкості, з яким API GroupDocs.Viewer для Java відтворює файл DOCX як файл зображення за допомогою Java:

          ```java
          // Initialize Viewer
          Viewer viewer = new Viewer("invoice.docx");
          // Create view options
          PdfViewOptions viewOptions = new PdfViewOptions();
          // Convert file to PDF and check the output in the current directory
          viewer.view(viewOptions);
          ```
      # more_feature_loop
      - title: "Виконуйте трансформації під час візуалізації документів"
        content: "API GroupDocs.Viewer для Java пропонує різні параметри трансформації, які можна застосувати до візуалізованого документа для більш персоналізованого перегляду та відображення. Ви можете обертати сторінки, вказавши кут. Ви можете впорядкувати відображені сторінки. Застосуйте певний текст як водяний знак до відтворених сторінок або зображень. За допомогою GroupDocs.Viewer для Java API ви також маєте можливість додавати власні шрифти до документа, що відображається."

      # more_feature_loop
      - title: "Робота з вкладеннями електронної пошти"
        content: "API GroupDocs.Viewer для Java дозволяє отримувати окремі або всі вкладення електронної пошти. Отримавши необхідні вкладення електронної пошти, ви можете відобразити ці вкладені файли у зображення або HTML."

############################# Support ############################
support:
    enable: true

############################# Solutions ##########################
solutions:
    enable: true
    title: "GroupDocs.Viewer пропонує API перегляду документів для інших популярних середовищ розробки"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Viewer for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-viewer-net.png"
          product: "GroupDocs.Viewer"
          platform: ".NET"
          link: "/viewer/net/"

############################# Back to top ##########################
back_to_top:
  enable: true
---