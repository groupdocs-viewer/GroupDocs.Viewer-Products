---
############################# Static ##########################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

lang: bg
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: ".NET Document Viewer API, изобразяване на PDF Word Excel Изображение HTML диаграма"
head_description: "C# ASP.NET API за преглед на файлове и изобразяване. Добавете функции за преглед на PDF, Word, Excel, изображения, HTML, имейл в приложенията .NET."

############################# Header ##########################
title: "Изобразяване и показване на документи чрез .NET API"
description: ".NET Document Viewer API за изобразяване на 190+ формати на документи в PDF, HTML и изображения с мощни опции за конфигуриране."
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
              text: "Преглед"

            # button loop
            - link: "#features"
              text: "Характеристика"

            # button loop
            - link: "#support"
              text: "поддържа"

            # button loop
            - link: "https://products.groupdocs.app/viewer/total"
              text: "Демо на живо"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Ценообразуване"

    right:
        link_download: "https://releases.groupdocs.com/viewer/net/"
        link_learn: "https://docs.groupdocs.com/viewer/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    content: |
      GroupDocs.Viewer за .NET API ви помага да създавате мощни приложения в C#, ASP.NET и други базирани на .NET технологии, които могат да изобразяват и показват документи и изображения от 190+ файлови формата, без да инсталирате външен софтуер. Библиотеката за преглед на файлове растеризира документите и след това ги преобразува в SVG+HTML+CSS, за да оптимизира цялостното изобразяване на документи за преглед на бизнес документи, изображения, текстови файлове, диаграми, графики, прикачени файлове към имейли и PDF файлове със скорост, истински текст и висока точност във вашите приложения. Имате възможност да добавите функции за разглеждане и четене на документи във вашите приложения, за да показвате цял документ, частичен документ, конкретна страница/диапазон от клетки, отделен слой на документа, със или без анотации и коментари за поддържаните файлови формати.
       
      GroupDocs.Viewer за .NET кешира изведените документи на локалния диск по подразбиране. Всеки тип външно кеш съхранение също се поддържа чрез внедряване на подходящи интерфейси – Amazon S3, Dropbox, Google Drive, Windows Azure, Redis или всеки друг.
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          Следва общ преглед на GroupDocs.Viewer за .NET:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Преглед"
          content: |
            * Показване на 190+ типа документи 
            * Вземете файл във формат HTML, изображение, PDF 
            * Завъртане и пренареждане 
            * Прилагане на воден знак 
            * Кеш за бърз процес 
            * Добавете персонализирани шрифтове 
            * Прилагане на стандарти за кодиране 
            * Персонализиран манипулатор на входни данни 
            * Рендиране с проследяване на промените 
            * Изобразяване като адаптивен HTML 
            * Изобразяване на PDF и CAD слоеве 
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Viewer за .NET поддържа преглед на всички популярни файлови формати на документи. Само с няколко реда код добавете PDF Viewer, Microsoft Office Word, Excel електронна таблица, Image, HTML, Outlook имейл, OneNote, Project и възможности за преглед на графики във вашите .NET приложения.

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
                * **Файлове за оформление на страници:** PDF, TEX, XPS, OXPS
                * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG, OTG, FODP, FODG
                * **Стойности, разделени с разделител:** CSV, TSV
                * **Мрежа:** HTML, MHT, MHTML
                * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
                * **PostScript:** PS, EPS
                * **Архив:** ZIP, TAR, BZ2, GZ, RAR, RAR5
                * **различни:** OBJ, EPUB, MOBI, DjVu, XML, VCF, VCARD, NUMBERS, NSF

        right:
          enable: true
          table:
            # table loop
            - title: "Изображения, графики и диаграми"
              content: |
                * **Изображения:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB
                * **Икона на Windows:** ICO
                * **Мащабируема векторна графика:** SVG, CDR, CMX, IGS, SVGZ
                * **Jpeg2000:** JP2, J2C, J2K, JPC, JPF, JPX, JPM
                * **Адобе Фотошоп:** PSD, PSB
                * **Език за команди на принтера:** PCL
                * **Стерео литография (3D печат):** STL
                * **Основни класове в индустрията:** IFC
                * **Медицински изображения:** DICOM
                * **Документи за плотер:** PLT, HPG
                * **Уеб формати за дизайн на Autodesk:** DWF, DWG
                * **Чертеж на AutoCAD:** DWT, IFC, STL, CF2
                * **Базиран на ISFF DGN (V7):** DGN

            # table loop
            - title: "Формати на езици за програмиране"
              content: |
                * **C/C++/C# файлове:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
                * **Java/JavaScript файлове:** JAVA, JS, JSON, PROPERTIES
                * **различни:** VB, PHP, SQL, PL, PY, PV, RB, RST, SASS, SCALA, SCM, SCRIPT, AS, AS3, ASM, BAT, CMAKE, CSS, DIFF, ERB, GROOVY, HAML, LESS, LOG, M, MAKE, MD, ML, MM, SH, SML, VIM, YAML

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Viewer за .NET поддържа следните операционни системи, рамки и мениджъри на пакети:
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Операционна система"
              content: |
                * Microsoft Windows Server 2003 и по-нова версия 
                * Microsoft Windows XP и по-нова версия 
                * Microsoft Windows 10 и 11 
                * Linux (Ubuntu, OpenSUSE, CentOS и други) 
                * Mac OS X 

            # table loop
            - icon: "fas fa-code"
              title: "Поддържани рамки"
              content: |
                * .NET Framework 2.0 или по-нова версия 
                * .NET Core 3.1 
                * .NET 5 или по-нова версия 

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-box"
              title: "Мениджър на пакети"
              content: |
                * NuGet

            # table loop
            - icon: "fas fa-tools"
              title: "Среди за разработка"
              content: |
                * Microsoft Visual Studio
                * Visual Studio Code
                * .NET CLI

############################# Features ############################
features:
    enable: true
    title: "GroupDocs.Viewer за функции на .NET"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "Растеризирайте документи и ги конвертирайте в SVG, HTML и CSS"

      # feature loop
      - icon: "fas fa-eye"
        content: "Преобразувайте текст в HTML и визуализирайте документи, за да получите HTML, изображение или PDF представяне"

      # feature loop
      - icon: "fas fa-bolt"
        content: "По-бързо време за зареждане с помощта на кеширани версии на документи"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "Преобразувайте презентации с форми и текст с 3D ефекти"

      # feature loop
      - icon: "fas fa-code"
        content: "Кодирайте Word, Excel и имейл документи до желания стандарт за кодиране"

      # feature loop
      - icon: "fas fa-cloud"
        content: "Рендирайте документи, намиращи се на FTP или места за съхранение в облак"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "Изключване на шрифтове при изобразяване в HTML за намаляване на резултантния размер на файла"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "Минимизирайте CSS и HTML изхода чрез премахване на коментари, допълнителни бели пространства и др."

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "Прочетете текста, съдържащ се в изходен документ чрез неговите координати"

      # feature loop
      - icon: "fas fa-border-all"
        content: "Показване/скриване на линиите на мрежата на листове на Excel в изходно представяне"

      # feature loop
      - icon: "fas fa-wrench"
        content: "Посочете броя на редовете в лист на Excel, които да бъдат изобразени на всяка страница"

      # feature loop
      - icon: "fas fa-columns"
        content: "Игнорирайте празните колони, докато изобразявате документи от електронни таблици"

      # feature loop
      - icon: "fas fa-file-word"
        content: "Преобразувайте Word документи в HTML страници, изображения или PDF с проследяване на промените"

      # feature loop
      - icon: "fas fa-envelope"
        content: "Изобразете прикачени файлове към имейл като оригинални файлове, изображения или в HTML представяне"

      # feature loop
      - icon: "fas fa-print"
        content: "Задаване на ограничения за печат на PDF документи"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "Изобразяване на съдържание/файлове, съдържащи се в ZIP архиви, като прикачени файлове"

      # feature loop
      - icon: "fas fa-lock"
        content: "Получавайте прикачени файлове от защитени с парола документи"

      # feature loop
      - icon: "fas fa-file-code"
        content: "Рендирайте файловите формати на езиците за програмиране като обикновен текст"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "Регулирайте цветовете на фона, когато преглеждате CAD чертежи"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "Преглеждайте документи на Excel и конвертирайте в PDF, HTML, JPG и PNG"

      # feature loop
      - icon: "fas fa-heading"
        content: "Вземете имена на работни листове от Excel файл – Показване на заглавия на колони и номера на редове в електронната таблица"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "Преглеждайте и конвертирайте документи на Microsoft Project с бележки"

      # feature loop
      - icon: "fas fa-cube"
        content: "Преобразувайте CAD чертежи в SVG за по-добро изживяване при гледане и мащабиране"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "Изберете да изобразите Visio фигури без схема"

    more_feature:
      # more_feature_loop
      - title: "Преглеждайте документи ефективно и надеждно"
        content: |
          С помощта на API на GroupDocs.Viewer можете да показвате повече от 190 формата на документи ефективно и надеждно с непокътната цялост на съдържанието и структурата на документа. Следният примерен код показва колко лесно е да видите HTML представяне на DOCX документ:

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
      - title: "Прилагане на трансформация към изобразен изход"
        content: "Можете да извършвате различни трансформации на изобразения изходен документ с помощта на GroupDocs.Viewer за .NET API. Тези опции за трансформация ви дават контрол върху начина, по който представяте изобразения изход за показване. Наличните трансформации са опция за завъртане на страницата, опция за пренареждане на страницата и прилагане на текстов воден знак."

      # more_feature_loop
      - title: "Работа с файлове с данни на Outlook"
        content: "GroupDocs.Viewer за .NET API може да визуализира елементите във файловете с данни на Outlook (OST/PST) като PDF, HTML и файлове с изображения. Нашият API за преглед също има способността да получи списъка с папки, съдържащи се във файловете с данни на Outlook. Използвайки GroupDocs.Viewer за .NET API, можете да посочите папката за изобразяване от файлове с данни на Outlook. По същия начин можете също да получите имейл съобщения, съдържащи се във формати OST/PST като прикачени файлове. GroupDocs.Viewer за .NET също ви позволява да филтрирате съобщения от OST/PST формати въз основа на тема, съдържание или подател."

      # more_feature_loop
      - title: "Работа с CAD документи"
        content: "GroupDocs.Viewer за .NET API може да визуализира модел и всички непразни оформления или да визуализира конкретно оформление на CAD файл. GroupDocs.Viewer за .NET API също така поддържа рендиране с мозайки или рендиране по координати на CAD документи в изображение, HTML или PDF. Можете също да получите състояния на слоеве за CAD документи."

############################# Testimonials ###############################
testimonials:
  enable: true

  testimonial:
    # testimonial item loop
    - name: "Margot Baill"
      designation: "Директор продуктово развитие в Hireology"
      content: "Интегрирането на GroupDocs.Viewer for Cloud API беше лесно с техния фантастичен Ruby SDK. Няма толкова много компании, които са готови да работят с нас по това, което искаме. Това е страхотно партньорство."

    # testimonial item loop
    - name: "Mats Oustad"
      designation: "Старши консултант/партньор в Novanet AS"
      content: "След внедряване и използване на GroupDocs.Viewer за .NET в проекта изглежда, че работи много добре. Тествах с много документи и засега добре. Всичко, което съм хвърлил върху него, се изобразява добре и изглежда също толкова добре, колкото би било в PDF програма за преглед или MS Word."
              
    # testimonial item loop
    - name: "Martin Lasarga"
      designation: "Продуктов мениджър в Axentria ECM от G.S.I."
      content: "Отлично обслужване и отлични продукти. Те бяха изключително полезни и отзивчиви по време на процеса на внедряване на GroupDocs.Viewer за .NET, не мога да ги препоръчам достатъчно силно."

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Viewer предлага API за преглед на документи за други популярни среди за разработка"

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
