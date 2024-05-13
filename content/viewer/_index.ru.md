---
############################# Static ##########################
layout: "family"
date: 2023-12-20T06:39:57
draft: false

product: "Viewer"
product_tag: "viewer"

############################# Head ############################
head_title: "API рендеринга и просмотра документов | Локальный API и онлайн-сервис"
head_description: "Легко и бесплатно визуализируйте и просматривайте файлы Word, PDF, Excel, Powerpoint или изображения."

############################# Header ##########################
title: "С легкостью визуализируйте и просматривайте документы"
description: |
  Мощный API-интерфейс просмотра для преобразования различных файлов в PDF, HTML и изображения.

  Загружайте документы из различных источников, включая файлы, потоки, URL-адреса, FTP-серверы, Amazon S3, хранилище BLOB-объектов Azure и многое другое.

  Создавайте адаптивные HTML-страницы, защищайте выходные PDF-файлы и меняйте порядок их страниц, поворачивайте страницы, отображайте примечания и комментарии, если это необходимо.

############################# Platforms ############################
supported_platforms:
  enable: true  
  head_title: "Выберите свою платформу"
  title: "Поддерживаемые платформы"
  description: "Библиотека GroupDocs.Viewer поддерживает следующие операционные системы и платформы."
  details_link_title: "Узнать больше"
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
        - content: "Более 180 форматов файлов"
          rows: "1"
        # features loop
        - content: "Пакет пользовательского интерфейса для ASP.NET Core"
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
        - content: "Более 180 форматов файлов"
          rows: "1"
        # features loop
        - content:  "Пакет пользовательского интерфейса для Spring и Dropwizard"
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
        - content:  "Более 180 форматов файлов"
          rows: "1"
        # features loop
        - content:  "Пакет пользовательского интерфейса – скоро появится"
          rows: "1" 
        # features loop
        - content:  "Демо-версия - скоро"
          rows: "3" 

    # supported_platforms loop
    - title: "Python"
      description: "GroupDocs.Viewer for Python"
      color: "yellow"
      tag: "python-net"
      link: "/viewer/python-net/"
      features_link: "https://docs.groupdocs.com/viewer/python-net/system-requirements/"
      features:
        # features loop
        - content: "Python 3.9+  <br>  and .Net 6+"
          rows: "3"
        # features loop
        - content:  "Windows, Linux, macOS"
          rows: "1"
        # features loop
        - content:  "Более 180 форматов файлов"
          rows: "1"
        # features loop
        - content:  "Пакет пользовательского интерфейса – скоро появится"
          rows: "1" 
        # features loop
        - content:  "Демо-версия - скоро"
          rows: "3" 

############################# Features ############################

features:
  enable: true
  title: "Набор функций GroupDocs.Viewer"
  description: "API для рендеринга файлов различных типов, таких как HTML, PDF, PNG и JPEG, в приложениях для их просмотра без стороннего программного обеспечения."

  items:
    # feature loop
    - icon: "view"
      title: "Просмотр документов и изображений"
      content: "Просматривайте документы, отображая их в виде файлов HTML, PDF, PNG и JPEG."

    # feature loop
    - icon: "password"
      title: "Открытие защищенных документов"
      content: "Укажите пароль для открытия зашифрованных документов."

    # feature loop
    - icon: "load"
      title: "Загружайте файлы откуда угодно"
      content: "Загружайте документы из различных файлов, URL-адресов, FTP-серверов, Amazon S3 и т. д."
    
    # feature loop
    - icon: "pages"
      title: "Рендеринг всех или определенных страниц"
      content: "Укажите диапазон номеров страниц для отображения."


############################# Code samples ############################
code_samples:
  enable: true
  title: "Примеры кода GroupDocs.Viewer"
  description: "Некоторые варианты использования GroupDocs.Viewer в C#, Java, TypeScript"
  items:
    # code sample loop
    - title: "Как преобразовать файлы DOCX в PDF"
      content: |
       Преобразуйте документы DOCX в PDF без установки Microsoft Word или другого программного обеспечения. Легко загружайте и просматривайте файлы DOCX в своем приложении .NET, будь то веб-приложение или настольное приложение. Вот пример того, как преобразовать файл DOCX в PDF:
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Загрузите файл DOCX для рендеринга
            using (Viewer viewer = new Viewer("sample.docx"))
            {
              // Преобразование DOCX в PDF-файл
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
            // Загрузите файл DOCX для рендеринга
            try (Viewer viewer = new Viewer("sample.docx")) {
                // Преобразование DOCX в PDF-файл
                PdfViewOptions viewOptions = new PdfViewOptions();
                viewer.view(viewOptions);
            }
            ```
        - language: "TypeScript"
          color: "green"
          content: |
            ```javascript {style=abap}  
            // Загрузите файл DOCX для рендеринга
            const viewer = new groupdocs.viewer.Viewer("sample.docx")
            
            // Преобразование DOCX в PDF-файл
            const viewOptions = groupdocs.viewer.PdfViewOptions(output.pdf)
            viewer.view(viewOptions)
            ```

        - language: "Python"
          color: "yellow"
          content: |
            ```python {style=abap} 
            import groupdocs.viewer as gv
            import groupdocs.viewer.options as gvo   
            // Загрузите файл DOCX для рендеринга
            with gv.Viewer("sample.docx") as viewer:
            
                // Преобразование DOCX в PDF-файл
                viewOptions = gvo.PdfViewOptions("output.pdf")
                viewer.view(viewOptions)
            ```

############################# Formats ############################
formats:
  enable: true
  title:  "Поддерживается более 180 форматов файлов"
  description: "GroupDocs.Viewer поддерживает работу с наиболее популярными [форматами файлов](https://docs.groupdocs.com/viewer/net/supported-document-formats/)"


############################# Metrics ############################

metrics:
  enable: true
  title: "Углубленные показатели и статистические данные"
  description: "Ознакомьтесь с подробной разбивкой наших ключевых показателей, предоставив комплексные показатели и статистическую информацию о наших достижениях, влиянии и росте."

  items:
    # metrics loop
    - number: "180+"
      title: "Поддерживаемые форматы"
      content: "Легко и без проблем просматривайте файлы более 180 форматов, включая документы, изображения и чертежи САПР. Преодолевайте барьеры совместимости и легко получайте доступ к разнообразным файлам с помощью нашего комплексного решения для просмотра."
    # metrics loop
    - number: "1.0M"
      title: "Загрузки NuGet"
      content: "Наше пакетное решение NuGet стало надежным и широко распространенным ресурсом в сообществе разработчиков, обеспечивая плавную интеграцию и ценную функциональность для бесчисленного количества проектов."

    # metrics loop
    - number: "10+"
      title: "Библиотеки"
      content: "Наш продукт включает более 10 библиотек, предлагающих расширенные функции для оптимизации производительности. Эти библиотеки предназначены для удовлетворения различных потребностей разработки и обладают непревзойденными возможностями."
    
    # metrics loop
    - number: "100+"
      title: "Счастливые клиенты"
      content: "Обслуживание самых знаковых брендов по всему миру. Узнайте, почему сотни людей любят GroupDocs.Viewer! Откройте для себя безупречную навигацию, удобное сотрудничество и непревзойденную простоту использования. Присоединяйся сейчас!"


############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "Наши счастливые клиенты"
  description: "Библиотеки GroupDocs используются всемирно известными и выдающимися брендами по всему миру."

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
  title: "Готовы начать?"
  description: "Попробуйте функции GroupDocs.Viewer бесплатно или запросите лицензию."

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
        #  loop
    - title: "Python"
      link: "/viewer/python-net/"
      color: "yellow"

############################# Faq ############################

faq:
  enable: true
  title: "Распространенные вопросы и опасения"
  description: "Найдите ответы на распространенные вопросы в нашем разделе часто задаваемых вопросов, чтобы быстро решить ваши вопросы и проблемы."

  items:
    #  loop
    - question: "Могу ли я оценить продукты GroupDocs перед покупкой?"
      answer: |
        Да! Все продукты GroupDocs имеют безрисковую ознакомительную версию. Мы настоятельно рекомендуем разработчикам загрузить и опробовать наши API перед покупкой, чтобы убедиться, что они удовлетворят ваши потребности на 100%.
    #  loop
    - question: "Проводит ли GroupDocs демонстрации продуктов?"
      answer: |
        Нет, мы сосредоточены на наших API и создании максимально функциональных и стабильных продуктов. Мы предлагаем полнофункциональные и бесплатные пробные версии в форме [временной лицензии](https://purchase.groupdocs.com/temporary-license/), чтобы вы могли опробовать продукт самостоятельно.
    #  loop
    - question: "Где я могу скачать продукт?"
      answer: |
        Все продукты доступны для загрузки с [веб-сайта](https://releases.groupdocs.com). Мы не отправляем физические копии нашего программного обеспечения по почте.    
    #  loop
    - question: "Лицензии разработчика GroupDocs предоставляются для каждого пользователя или для имени пользователя?"
      answer: |
        Лицензии разработчика GroupDocs предоставляются на пользователя, а не на именованного пользователя. Мы понимаем, что члены команды программистов могут меняться со временем и что обновлять лицензию каждый раз, когда это происходит, нецелесообразно.
    #  loop
    - question: "Нужно ли нам лицензирование только для активных разработчиков? Например, у нас есть команда из двух разработчиков, работающих в смену А, и вторая команда из двух разработчиков, работающих в смену Б… в этой ситуации нам нужны две или четыре лицензии?"
      answer: |
        Все разработчики, работающие над проектом, должны иметь лицензию. В этой ситуации GroupDocs считает, что в вашей команде четыре участника (даже если они работают в разное время).

############################# Cloud ############################

cloud_links:
  enable: true
  title: "API-интерфейсы GroupDocs.Viewer с минимальным кодом"
  description: "Ускорьте просмотр документов или изображений в любом типе приложений с помощью нашего облачного REST API."

  items:
    #  loop
    - icon: "groupdocs_viewer-for-curl"
      title: "GroupDocs.Viewer Cloud for cURL"
      link: "https://products.groupdocs.cloud/viewer/curl"
      content: "Используйте API-интерфейс просмотра документов RESTful cURL для эффективной визуализации и демонстрации Microsoft Office, PDF и различных других стандартных форматов файлов в ваших приложениях."

    #  loop
    - icon: "groupdocs_viewer-for-net"
      title: "GroupDocs.Viewer Cloud for .NET"
      link: "https://products.groupdocs.cloud/viewer/net"
      content: "Расширьте возможности просмотра документов в приложениях .NET с помощью Cloud SDK для .NET. Беспрепятственный просмотр документов в форматах HTML, PDF или изображений."
    #  loop
    - icon: "groupdocs_viewer-for-java"
      title: "GroupDocs.Viewer Cloud for Java"
      link: "https://products.groupdocs.cloud/viewer/java"
      content: "Интегрируйте расширенные возможности рендеринга документов в свои приложения Java с помощью специального SDK Document Viewer для Java."

############################# Apps ############################

app_links:
  enable: true
  title: "Приложения GroupDocs.Viewer NoCode"
  description: "Онлайн-приложение, позволяющее просматривать более 180 популярных форматов файлов в браузере."

  items:
    #  loop
    - icon: "groupdocs_viewer-app"
      title: "GroupDocs.Viewer Total"
      link: "https://products.groupdocs.app/viewer/total"
      content: "Изучите бесплатное онлайн-приложение для просмотра файлов более 180 форматов прямо из предпочитаемого вами веб-браузера."

    #  loop
    - icon: "groupdocs_words-app"
      title:  "GroupDocs.Viewer DOCX"
      link: "https://products.groupdocs.app/viewer/docx"
      content: "Веб-инструмент для удобного просмотра файлов Microsoft Word на различных устройствах."

    #  loop
    - icon: "groupdocs_pdf-app"
      title:  "GroupDocs.Viewer PDF"
      link: "https://products.groupdocs.app/viewer/pdf"
      content: "Открывайте и просматривайте PDF-файлы онлайн с помощью бесплатной программы просмотра PDF-файлов."
    

---