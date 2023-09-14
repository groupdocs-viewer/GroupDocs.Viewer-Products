---
############################# Static ##########################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

lang: uk
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: ".NET Document Viewer API, візуалізація PDF Word Excel Image HTML діаграма"
head_description: "Перегляд файлів C# ASP.NET і API відтворення. Додайте функції перегляду PDF, Word, Excel, зображень, HTML, електронної пошти в програмах .NET."

############################# Header ##########################
title: "Рендеринг і відображення документів через .NET API"
description: ".NET Document Viewer API для перетворення понад 190 форматів документів у PDF, HTML і зображення з потужними параметрами конфігурації."
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
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Ціноутворення"

    right:
        link_download: "https://www.nuget.org/packages/GroupDocs.Viewer"
        link_learn: "https://docs.groupdocs.com/viewer/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    content: |
      API GroupDocs.Viewer для .NET допомагають створювати потужні програми на C#, ASP.NET та інших технологіях на основі .NET, які можуть візуалізувати та відображати документи та зображення понад 190 форматів файлів без встановлення будь-якого зовнішнього програмного забезпечення. Бібліотека перегляду файлів растеризує документи, а потім перетворює їх у формат SVG+HTML+CSS, щоб оптимізувати загальний досвід візуалізації документів для перегляду бізнес-документів, зображень, текстових файлів, діаграм, графіки, вкладень електронної пошти та PDF-файлів із швидкістю, справжнім текстом і висока точність у ваших програмах. Ви можете додати функції перегляду та читання документів у своїх програмах, щоб відображати весь документ, частину документа, певний діапазон сторінок/комірок, окремий шар документа з або без анотацій і коментарів для підтримуваних форматів файлів.
       
      GroupDocs.Viewer для .NET за замовчуванням кешує відтворені документи на локальний диск. Будь-який тип зовнішнього кеш-сховища також підтримується шляхом реалізації відповідних інтерфейсів – Amazon S3, Dropbox, Google Drive, Windows Azure, Redis або будь-якого іншого.
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          Нижче наведено огляд GroupDocs.Viewer для .NET:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Огляд"
          content: |
            * Відображення понад 190 типів документів 
            * Отримайте файл у форматі HTML, зображення, PDF 
            * Обертати та змінювати порядок 
            * Застосувати водяний знак 
            * Кеш для швидкого процесу 
            * Додати власні шрифти 
            * Застосуйте стандарти кодування 
            * Настроюваний обробник вхідних даних 
            * Відтворення з відстеженням змін 
            * Виводити як адаптивний HTML 
            * Відтворення шарів PDF і CAD 
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Viewer для .NET підтримує перегляд усіх популярних форматів файлів документів. За допомогою лише кількох рядків коду додайте засіб перегляду PDF, Microsoft Office Word, електронну таблицю Excel, зображення, HTML, електронну пошту Outlook, OneNote, Project і можливості перегляду графіки у своїх програмах .NET.

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
          GroupDocs.Viewer для .NET підтримує такі операційні системи, фреймворки та менеджери пакетів:
        
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
                * .NET Framework 2.0 або вище 
                * .NET Core 3.1 
                * .NET 5 або вище 

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-box"
              title: "Менеджер пакетів"
              content: |
                * NuGet

            # table loop
            - icon: "fas fa-tools"
              title: "Середовища розробки"
              content: |
                * Microsoft Visual Studio
                * Visual Studio Code
                * .NET CLI

############################# Features ############################
features:
    enable: true
    title: "Функції GroupDocs.Viewer для .NET"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "Растеризуйте документи та конвертуйте їх у SVG, HTML і CSS"

      # feature loop
      - icon: "fas fa-eye"
        content: "Перетворюйте текст у HTML і візуалізуйте документи, щоб отримати представлення у форматі HTML, зображення або PDF"

      # feature loop
      - icon: "fas fa-bolt"
        content: "Швидший час завантаження за допомогою кешованих версій документів"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "Перетворюйте презентації з фігурами та текстом за допомогою 3D-ефектів"

      # feature loop
      - icon: "fas fa-code"
        content: "Кодуйте документи Word, Excel і електронні листи до потрібного стандарту кодування"

      # feature loop
      - icon: "fas fa-cloud"
        content: "Відтворити документи, розташовані на FTP або в хмарних сховищах"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "Виключення шрифтів під час візуалізації в HTML для зменшення кінцевого розміру файлу"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "Зменште вихідні дані CSS і HTML, видаливши коментарі, зайві пробіли тощо."

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "Прочитайте текст, що міститься у вихідному документі, через його координати"

      # feature loop
      - icon: "fas fa-border-all"
        content: "Показати/сховати лінії сітки аркушів Excel у вихідному представленні"

      # feature loop
      - icon: "fas fa-wrench"
        content: "Укажіть кількість рядків на аркуші Excel, які мають відображатися на кожній сторінці"

      # feature loop
      - icon: "fas fa-columns"
        content: "Ігноруйте порожні стовпці під час відтворення табличних документів"

      # feature loop
      - icon: "fas fa-file-word"
        content: "Перетворюйте документи Word у HTML-сторінки, зображення або PDF із відстеженням змін"

      # feature loop
      - icon: "fas fa-envelope"
        content: "Відтворюйте вкладення електронної пошти як оригінальні файли, зображення або у форматі HTML"

      # feature loop
      - icon: "fas fa-print"
        content: "Встановіть обмеження друку PDF-документів"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "Відображати вміст/файли, що містяться в ZIP-архівах, як вкладення"

      # feature loop
      - icon: "fas fa-lock"
        content: "Отримайте вкладення із захищених паролем документів"

      # feature loop
      - icon: "fas fa-file-code"
        content: "Відображати формати файлів мов програмування як простий текст"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "Налаштуйте кольори фону під час перегляду креслень САПР"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "Переглядайте документи Excel і конвертуйте їх у PDF, HTML, JPG і PNG"

      # feature loop
      - icon: "fas fa-heading"
        content: "Отримайте назви аркушів із файлу Excel – відображайте заголовки стовпців і номери рядків електронної таблиці"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "Перегляд і конвертація документів Microsoft Project за допомогою приміток"

      # feature loop
      - icon: "fas fa-cube"
        content: "Перетворюйте креслення САПР у SVG для кращого перегляду та масштабування"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "Виберіть відтворення фігур Visio без схеми"

    more_feature:
      # more_feature_loop
      - title: "Переглядайте документи ефективно та надійно"
        content: |
          Використовуючи GroupDocs.Viewer API, ви можете ефективно та надійно відображати понад 190 форматів документів із збереженням цілісності вмісту та структури документа. Наступний зразок коду показує, наскільки легко переглянути HTML-представлення документа DOCX:

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
      - title: "Застосувати трансформацію до відтвореного результату"
        content: "За допомогою GroupDocs.Viewer for .NET API можна виконувати різні перетворення відтвореного вихідного документа. Ці параметри трансформації дають вам змогу контролювати спосіб представлення відтвореного результату для відображення. Доступні перетворення: опція повороту сторінки, опція зміни порядку сторінки та застосування текстового водяного знака."

      # more_feature_loop
      - title: "Робота з файлами даних Outlook"
        content: "API GroupDocs.Viewer для .NET може відтворювати елементи у файлах даних Outlook (OST/PST) як файли PDF, HTML і зображення. Наш API Viewer також має можливість отримати список папок, які містяться у файлах даних Outlook. Використовуючи API GroupDocs.Viewer для .NET, ви можете вказати папку для відтворення з файлів даних Outlook. Так само ви також можете отримати повідомлення електронної пошти у форматах OST/PST як вкладення. GroupDocs.Viewer для .NET також дає змогу фільтрувати повідомлення з форматів OST/PST на основі теми, вмісту чи відправника."

      # more_feature_loop
      - title: "Робота з документами САПР"
        content: "API GroupDocs.Viewer для .NET може відтворювати модель і всі непорожні макети або відтворювати певний макет файлу CAD. API GroupDocs.Viewer для .NET також підтримує мозаїчне рендеринг або візуалізацію за координатами документів CAD у зображення, HTML або PDF. Ви також можете отримати статуси шарів для документів CAD."

############################# Testimonials ###############################
testimonials:
  enable: true

  testimonial:
    # testimonial item loop
    - name: "Margot Baill"
      designation: "Директор з розвитку продуктів в Hireology"
      content: "Інтегрувати GroupDocs.Viewer for Cloud API було просто завдяки фантастичному Ruby SDK. Не так багато компаній, які готові працювати з нами над тим, що ми хочемо. Це чудове партнерство."

    # testimonial item loop
    - name: "Mats Oustad"
      designation: "Старший консультант/партнер Novanet AS"
      content: "Після впровадження та використання GroupDocs.Viewer для .NET у проекті виглядає, що він працює дуже добре. Я перевірив багато документів, і поки що все добре. Усе, що я до нього додав, чудово відображається та виглядає так само добре, як у засобі перегляду PDF чи MS Word."
              
    # testimonial item loop
    - name: "Martin Lasarga"
      designation: "Менеджер із продукції Axentria ECM by G.S.I."
      content: "Відмінний сервіс і відмінні продукти. Вони були надзвичайно корисними та чуйними під час впровадження GroupDocs.Viewer для .NET, тому не можу рекомендувати їх досить високо."

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Viewer пропонує API перегляду документів для інших популярних середовищ розробки"

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
