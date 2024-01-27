---
############################# Static ############################
layout: "family"
date: 2023-12-20T06:39:57
draft: false

product: "Viewer"
product_tag: "viewer"

############################# Head ############################
head_title: "API візуалізації та перегляду документів | On Premise API та онлайн-сервіс"
head_description: "Відтворюйте та переглядайте файли Word, PDF, Excel, Powerpoint або зображення легко та безкоштовно"

############################# Header ############################
title: "З легкістю візуалізуйте та переглядайте документи"
description: |
  Потужний API перегляду для рендерингу різних файлів у PDF, HTML і зображення.

  Завантажуйте документи з різних джерел, зокрема файлів, потоків, URL-адрес, FTP-серверів, Amazon S3, Azure Blob Storage тощо.

  Створюйте адаптивні HTML-сторінки, захищайте вихідні PDF-файли та змінюйте порядок їхніх сторінок, повертайте сторінки, візуалізуйте примітки та коментарі, якщо потрібно.
  

############################# Platforms ############################
supported_platforms:
  enable: true  
  head_title: "Виберіть свою платформу"
  title: "Підтримувані платформи"
  description: "Бібліотека GroupDocs.Viewer підтримує такі операційні системи та фреймворки"
  details_link_title: "Вивчайте більше"
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
        - content: "180+ file formats"
          rows: "1"
        # features loop
        - content: "UI package for ASP.NET Core"
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
        - content:  "180+ file formats"
          rows: "1"
        # features loop
        - content:  "UI package for Spring and Dropwizard"
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
        - content:  "180+ file formats"
          rows: "1"
        # features loop
        - content:  "UI package - coming soon "
          rows: "1" 
        # features loop
        - content:  "Demo - coming soon "
          rows: "3" 



############################# Features ############################

features:
  enable: true
  title: "Набір функцій GroupDocs.Viewer"
  description: "API для візуалізації файлів різних типів як HTML, PDF, PNG і JPEG у програмах для їх перегляду без стороннього програмного забезпечення."

  items:
    # feature loop
    - icon: "view"
      title: "Перегляд документів і зображень"
      content: "Переглядайте документи, відтворюючи їх як файли HTML, PDF, PNG і JPEG."
    # feature loop
    - icon: "password"
      title: "Відкрийте захищені документи"
      content: "Вкажіть пароль для відкриття зашифрованих документів."

    # feature loop
    - icon: "load"
      title: "Завантажуйте файли з будь-якого місця"
      content: "Завантажуйте документи з різних файлів, URL-адрес, FTP-серверів, Amazon S3 тощо."
    
    # feature loop
    - icon: "pages"
      title: "Виводити всі або окремі сторінки"
      content: "Укажіть діапазон номерів сторінок, які потрібно відобразити."


############################# Code samples ############################
code_samples:
  enable: true
  title: "Приклади коду GroupDocs.Viewer"
  description: "Деякі випадки використання типових операцій GroupDocs.Viewer у C#, Java, TypeScript"
  items:
    # code sample loop
    - title: "Як конвертувати файли DOCX у PDF"
      content: |
        Перетворюйте документи DOCX у PDF без встановлення Microsoft Word чи іншого програмного забезпечення. Легко завантажуйте та переглядайте файли DOCX у своїй програмі .NET, будь то веб-програма чи настільна програма. Ось приклад того, як перевести файл DOCX у PDF: 
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Завантажте файл DOCX для візуалізації
            using (Viewer viewer = new Viewer("sample.docx"))
            {
              // Перетворення DOCX у файл PDF
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
            // Завантажте файл DOCX для візуалізації
            try (Viewer viewer = new Viewer("sample.docx")) {
                // Перетворення DOCX у файл PDF
                PdfViewOptions viewOptions = new PdfViewOptions();
                viewer.view(viewOptions);
            }
            ```
        - language: "TypeScript"
          color: "green"
          content: |
            ```javascript {style=abap}  
            // Завантажте файл DOCX для візуалізації
            const viewer = new groupdocs.viewer.Viewer("sample.docx")
            
            // Перетворення DOCX у файл PDF
            const viewOptions = groupdocs.viewer.PdfViewOptions(output.pdf)
            viewer.view(viewOptions)
            ```


############################# Formats ############################
formats:
  enable: true
  title:  "Підтримується понад 180 форматів файлів"
  description: "GroupDocs.Viewer підтримує роботу з найпопулярнішими [форматами файлів](https://docs.groupdocs.com/viewer/net/supported-document-formats/)" 



############################# Metrics ############################

metrics:
  enable: true
  title: "Поглиблені показники та статистичні дані"
  description: "Ознайомтеся з детальною розбивкою наших ключових цифр, надаючи вичерпні показники та статистичну інформацію про наші досягнення, вплив і зростання."

  items:
    # metrics loop
    - number: "180+"
      title: "Підтримувані формати"
      content: "Легко переглядайте понад 180 форматів файлів, включаючи документи, зображення та креслення САПР, без проблем. Долайте бар’єри сумісності та легко отримуйте доступ до різноманітних файлів за допомогою нашого комплексного рішення для перегляду."

    # metrics loop
    - number: "1.0M"
      title: "Завантаження NuGet"
      content: "Наше пакетне рішення NuGet стало надійним і широко поширеним ресурсом у спільноті розробників, забезпечуючи повну інтеграцію та цінні функції для незліченних проектів."

    # metrics loop
    - number: "10+"
      title: "Бібліотеки"
      content: "Наш продукт містить понад 10 бібліотек, які пропонують розширені функції для оптимізації продуктивності. Ці бібліотеки створені для задоволення різноманітних потреб розробки з неперевершеними можливостями."
    
    # metrics loop
    - number: "100+"
      title: "Задоволені клієнти"
      content: "Обслуговування найвідоміших брендів у всьому світі. Дізнайтеся, чому сотні люблять GroupDocs.Viewer! Відкрийте для себе зручну навігацію, зручну співпрацю та неперевершену простоту використання. Приєднуйся зараз!"



############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "Наші щасливі клієнти"
  description: "Бібліотеки GroupDocs використовують всесвітньо відомі та видатні бренди по всьому світу."

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
  title: "Готові почати?"
  description: "Спробуйте функції GroupDocs.Viewer безкоштовно або подайте запит на ліцензію"
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
  title:  "Поширені запитання та проблеми"
  description:  "Знайдіть відповіді на поширені запити в нашому розділі поширених запитань, щоб швидко відповісти на свої запити та проблеми."
  items:
    #  loop
    - question: "Чи можу я оцінити продукти GroupDocs перед покупкою?"
      answer: |
        Так! Для всіх продуктів GroupDocs доступна безризикова оціночна версія. Ми наполегливо рекомендуємо розробникам завантажити та спробувати наші API перед покупкою, щоб переконатися, що вони на 100% задовольнять ваші потреби.
    #  loop
    - question: "Чи проводить GroupDocs демонстрації продуктів?"
      answer: |
        Ні, ми зосереджені на наших API та створенні максимально функціональних і стабільних продуктів. Ми пропонуємо повністю функціональні та безкоштовні пробні версії у формі [тимчасової ліцензії](https://purchase.groupdocs.com/temporary-license/), тож ви можете випробувати продукт самостійно.    
    #  loop
    - question: "Де я можу завантажити продукт?"
      answer: |
        Усі продукти доступні для завантаження з [веб-сайту](https://releases.groupdocs.com). Ми не надсилаємо фізичні копії нашого програмного забезпечення поштою.
    #  loop
    - question: "Ліцензії розробника GroupDocs надаються на одного користувача чи на одного користувача?"
      answer: |
        Ліцензії GroupDocs Developer надаються на користувача, а не на користувача. Ми розуміємо, що члени команди програмістів можуть змінюватися з часом і що непрактично оновлювати ліцензії кожного разу, коли це відбувається.
    #  loop
    - question: "Чи потрібна нам ліцензія лише для активних розробників? Наприклад, у нас є команда з двох розробників, які працюють у зміну А, і друга команда з двох розробників, які працюють у зміну Б… у цій ситуації нам потрібні дві чи чотири ліцензії?"
      answer: |
        Усі розробники, які працюють над проектом, повинні мати ліцензію. У цій ситуації GroupDocs вважає, що ваша команда складається з чотирьох учасників (хоча вони працюють у різний час). 


############################# Cloud ############################

cloud_links:
  enable: true
  title: "API із низьким кодом GroupDocs.Viewer"
  description: "Прискоріть перегляд документів або зображень у будь-якому додатку за допомогою нашого хмарного REST API"

  items:
    #  loop
    - icon: "groupdocs_viewer-for-curl"
      title: "GroupDocs.Viewer Cloud for cURL"
      link: "https://products.groupdocs.cloud/viewer/curl"
      content: "Використовуйте API переглядача документів cURL RESTful для ефективного візуалізації та демонстрації Microsoft Office, PDF та інших стандартних форматів файлів у ваших програмах."

    #  loop
    - icon: "groupdocs_viewer-for-net"
      title: "GroupDocs.Viewer Cloud for .NET"
      link: "https://products.groupdocs.cloud/viewer/net"
      content: "Розширення можливостей перегляду документів у програмах .NET за допомогою Cloud SDK для .NET. Легко переглядайте документи у форматах HTML, PDF або зображення."

    #  loop
    - icon: "groupdocs_viewer-for-java"
      title: "GroupDocs.Viewer Cloud for Java"
      link: "https://products.groupdocs.cloud/viewer/java"
      content: "Інтегруйте розширені можливості візуалізації документів у свої програми Java за допомогою спеціально розробленого пакета SDK для перегляду документів для Java."
    

############################# Apps ############################

app_links:
  enable: true
  title: "Програми GroupDocs.Viewer NoCode"
  description: "Онлайн-програма, яка дозволяє переглядати понад 180 популярних форматів файлів у браузері"

  items:
    #  loop
    - icon: "groupdocs_viewer-app"
      title: "GroupDocs.Viewer Total"
      link: "https://products.groupdocs.app/viewer/total"
      content: "Дослідіть безкоштовну онлайн-програму для перегляду понад 180 форматів файлів безпосередньо з улюбленого веб-браузера."

    #  loop
    - icon: "groupdocs_words-app"
      title:  "GroupDocs.Viewer DOCX"
      link: "https://products.groupdocs.app/viewer/docx"
      content: "Веб-інструмент для легкого перегляду файлів Microsoft Word на різних пристроях."

    #  loop
    - icon: "groupdocs_pdf-app"
      title:  "GroupDocs.Viewer PDF"
      link: "https://products.groupdocs.app/viewer/pdf"
      content: "Відкривайте та переглядайте PDF-файли онлайн за допомогою безкоштовного засобу перегляду PDF."
    



---