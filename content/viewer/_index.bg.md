---
############################# Static ############################
layout: "family"
date: 2023-12-20T06:39:57
draft: false

product: "Viewer"
product_tag: "viewer"

############################# Head ############################
head_title: "API за изобразяване и преглед на документи | On Premise API и онлайн услуга"
head_description: "Рендирайте и преглеждайте Word, PDF, Excel, Powerpoint или файлове с изображения лесно и безплатно"

############################# Header ############################
title: "Рендирайте и преглеждайте документи с лекота"
description: |
  Мощен API на Viewer за изобразяване на различни файлове в PDF, HTML и изображения.

  Зареждайте документи от различни източници, включително файлове, потоци, URL адреси, FTP сървъри, Amazon S3, Azure Blob Storage и др.

  Генерирайте адаптивни HTML страници, защитете изходните PDF файлове и пренаредете страниците им, завъртете страници, изобразете бележки и коментари, ако е необходимо.
  

############################# Platforms ############################
supported_platforms:
  enable: true  
  head_title: "Изберете своята платформа"
  title: "Поддържани платформи"
  description: "Библиотеката GroupDocs.Viewer поддържа следните операционни системи и рамки"
  details_link_title: "Научете повече"
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
  title: "Набор от функции на GroupDocs.Viewer"
  description: "API за изобразяване на файлове от различни типове като HTML, PDF, PNG и JPEG в приложения, за да ги разглеждате без софтуер на трети страни."

  items:
    # feature loop
    - icon: "view"
      title: "Преглед на документи и изображения"
      content: "Преглеждайте документи, като ги изобразявате като HTML, PDF, PNG и JPEG файлове."
    # feature loop
    - icon: "password"
      title: "Отворете защитени документи"
      content: "Задайте парола за отваряне на криптирани документи."

    # feature loop
    - icon: "load"
      title: "Зареждайте файлове отвсякъде"
      content: "Заредете документи от различни файлове, URL адреси, FTP сървъри, Amazon S3 и др."
    
    # feature loop
    - icon: "pages"
      title: "Изобразете всички или определени страници"
      content: "Задайте диапазон от номера на страници, които да бъдат изобразени."


############################# Code samples ############################
code_samples:
  enable: true
  title: "Примерни кодове на GroupDocs.Viewer"
  description: "Някои случаи на използване на типични операции на GroupDocs.Viewer в C#, Java, TypeScript"
  items:
    # code sample loop
    - title: "Как да рендирате DOCX файлове в PDF"
      content: |
        Рендирайте DOCX документи в PDF без инсталиран Microsoft Word или друг софтуер. Лесно зареждайте и преглеждайте DOCX файлове във вашето .NET приложение, независимо дали е уеб или настолно приложение. Ето пример как да изобразите DOCX файл в PDF: 
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Заредете DOCX файл за изобразяване
            using (Viewer viewer = new Viewer("sample.docx"))
            {
              // Рендирайте DOCX в PDF файл
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
            // Заредете DOCX файл за изобразяване
            try (Viewer viewer = new Viewer("sample.docx")) {
                // Рендирайте DOCX в PDF файл
                PdfViewOptions viewOptions = new PdfViewOptions();
                viewer.view(viewOptions);
            }
            ```
        - language: "TypeScript"
          color: "green"
          content: |
            ```javascript {style=abap}  
            // Заредете DOCX файл за изобразяване
            const viewer = new groupdocs.viewer.Viewer("sample.docx")
            
            // Рендирайте DOCX в PDF файл
            const viewOptions = groupdocs.viewer.PdfViewOptions(output.pdf)
            viewer.view(viewOptions)
            ```


############################# Formats ############################
formats:
  enable: true
  title:  "Поддържат се над 180 файлови формата"
  description: "GroupDocs.Viewer поддържа операции с най-популярните [файлови формати](https://docs.groupdocs.com/viewer/net/supported-document-formats/)" 



############################# Metrics ############################

metrics:
  enable: true
  title: "Задълбочени показатели и статистически прозрения"
  description: "Потопете се в подробна разбивка на нашите ключови цифри, предоставяйки изчерпателни показатели и статистически прозрения за нашите постижения, въздействие и растеж."

  items:
    # metrics loop
    - number: "180+"
      title: "Поддържани формати"
      content: "Преглеждайте лесно над 180 файлови формата, включително документи, изображения и CAD чертежи безпроблемно. Разчупете бариерите за съвместимост и достъпвайте различни файлове без усилие с нашето цялостно решение за преглед."

    # metrics loop
    - number: "1.0M"
      title: "Изтегляния на NuGet"
      content: "Нашето пакетно решение NuGet се превърна в доверен и широко възприет ресурс в общността на разработчиците, осигурявайки безпроблемна интеграция и ценна функционалност за безброй проекти."

    # metrics loop
    - number: "10+"
      title: "библиотеки"
      content: "Нашият продукт включва 10+ библиотеки, предлагащи разширени функции за оптимизиране на производителността. Тези библиотеки са проектирани да изпълняват различни нужди за разработка с несравними възможности."
    
    # metrics loop
    - number: "100+"
      title: "Доволни клиенти"
      content: "Обслужване на най-емблематичните марки по целия свят. Открийте защо стотици обичат GroupDocs.Viewer! Открийте безпроблемна навигация, удобно сътрудничество и несравнима лекота на използване. Присъедини се сега!"



############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "Нашите доволни клиенти"
  description: "Библиотеките на GroupDocs се използват от световно известни и изтъкнати марки по целия свят."

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
  title: "Готови ли сте да започнете?"
  description: "Изпробвайте функциите на GroupDocs.Viewer безплатно или поискайте лиценз"
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
  title:  "Често срещани въпроси и опасения"
  description:  "Намерете отговори на често срещани запитвания в нашия раздел с често задавани въпроси, за да отговорите бързо на вашите запитвания и притеснения."
  items:
    #  loop
    - question: "Мога ли да оценя продуктите на GroupDocs преди закупуване?"
      answer: |
        да Всички продукти на GroupDocs имат налична безрискова версия за оценка. Силно насърчаваме разработчиците да изтеглят и изпробват нашите API преди покупка, за да сме сигурни, че ще задоволят вашите нужди на 100%.
    #  loop
    - question: "GroupDocs прави ли демонстрации на продукти?"
      answer: |
        Не, нашият фокус е върху нашите API и създаването на възможно най-функционалните и стабилни продукти. Ние предлагаме напълно функционални и безплатни пробни версии под формата на [временен лиценз](https://purchase.groupdocs.com/temporary-license/), така че можете да изпробвате продукта сами.    
    #  loop
    - question: "Къде мога да изтегля продукта?"
      answer: |
        Всички продукти са достъпни за изтегляне от [уебсайта](https://releases.groupdocs.com). Ние не изпращаме физически копия на нашия софтуер по пощата.
    #  loop
    - question: "Лицензите за разработчици на GroupDocs за потребител ли са или за посочен потребител?"
      answer: |
        Лицензите за разработчици на GroupDocs са за потребител, а не за посочен потребител. Разбираме, че членовете на екипа по програмиране може да се променят с течение на времето и че не е практично да се налага да актуализирате лиценза всеки път, когато това се случи.
    #  loop
    - question: "Имаме ли нужда от лицензиране само за активни разработчици? Например, имаме екип от двама разработчици, работещи на смяна А, и втори екип от двама разработчици, работещи на смяна Б... в тази ситуация имаме ли нужда от два или четири лиценза?"
      answer: |
        Всички разработчици, които работят по проекта, трябва да бъдат лицензирани. В тази ситуация GroupDocs вижда вашия екип като четирима членове (въпреки че работят по различно време). 


############################# Cloud ############################

cloud_links:
  enable: true
  title: "API с нисък код на GroupDocs.Viewer"
  description: "Ускорете гледането на документ или изображение във всеки тип приложение с нашия базиран в облак REST API"

  items:
    #  loop
    - icon: "groupdocs_viewer-for-curl"
      title: "GroupDocs.Viewer Cloud for cURL"
      link: "https://products.groupdocs.cloud/viewer/curl"
      content: "Използвайте API за преглед на документи cURL RESTful за ефективно изобразяване и демонстриране на Microsoft Office, PDF и различни други стандартни файлови формати във вашите приложения."

    #  loop
    - icon: "groupdocs_viewer-for-net"
      title: "GroupDocs.Viewer Cloud for .NET"
      link: "https://products.groupdocs.cloud/viewer/net"
      content: "Подобрете възможностите за преглед на документи в .NET приложения с Cloud SDK за .NET. Преглеждайте безпроблемно документи в HTML, PDF или графични формати."

    #  loop
    - icon: "groupdocs_viewer-for-java"
      title: "GroupDocs.Viewer Cloud for Java"
      link: "https://products.groupdocs.cloud/viewer/java"
      content: "Интегрирайте усъвършенствани възможности за изобразяване на документи във вашите Java приложения, като използвате специално създаден SDK за Java за преглед на документи."
    

############################# Apps ############################

app_links:
  enable: true
  title: "Приложения GroupDocs.Viewer NoCode"
  description: "Онлайн приложение, което ви позволява да преглеждате 180+ популярни файлови формата в браузър"

  items:
    #  loop
    - icon: "groupdocs_viewer-app"
      title: "GroupDocs.Viewer Total"
      link: "https://products.groupdocs.app/viewer/total"
      content: "Разгледайте безплатно онлайн приложение, за да видите над 180 файлови формата директно от предпочитания от вас уеб браузър."

    #  loop
    - icon: "groupdocs_words-app"
      title:  "GroupDocs.Viewer DOCX"
      link: "https://products.groupdocs.app/viewer/docx"
      content: "Уеб базиран инструмент за безпроблемно разглеждане на файлове на Microsoft Word на различни устройства."

    #  loop
    - icon: "groupdocs_pdf-app"
      title:  "GroupDocs.Viewer PDF"
      link: "https://products.groupdocs.app/viewer/pdf"
      content: "Отваряйте и преглеждайте PDF файлове онлайн с безплатен PDF преглед."
    



---