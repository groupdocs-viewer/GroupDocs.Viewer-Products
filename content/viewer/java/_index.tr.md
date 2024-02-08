---
############################# Static ############################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

product: "Viewer"
product_tag: "viewer"
platform: "Java"
platform_tag: "java"

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
head_title: "Java Belge Görüntüleyici API'si, PDF Word Excel Görüntüsü HTML Diyagramını oluşturma"
head_description: "180'den fazla dosya formatını destekleyen çok formatlı belgeleri yerel olarak işleyen, görüntüleyen ve işleyen Java uygulamaları geliştirmek için Belge Görüntüleyici kitaplığı."

############################# Header ############################
title: "Java API'yi kullanarak<br>belgeleri oluşturun ve görüntüleyin"
description: "Çok yönlü yapılandırma seçenekleriyle 180'den fazla belge formatını PDF, HTML ve Görüntüye dönüştürmek için Güçlü Görüntüleyici API'si."
words:
  for: "for"

actions:
  main: "Ücretsiz Maven İndir"
  main_link: "https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-viewer/"
  alt: "Lisanslama"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/java"
  title: "başlamaya hazır mısın?"
  description: "GroupDocs.Viewer özelliklerini ücretsiz deneyin veya lisans isteyin"

release:
  title: "Sürüm {0} yayınlandı"
  notes: "Yenilikleri görün"
  downloads: "İndirilenler"
  link: "https://releases.groupdocs.com/viewer/java/release-notes/latest/"

code:
  title: "PDF dosyalarını Java'da oluşturma"
  more: "Daha fazla örnek"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Java"
  install: |
    <dependencies>
      <dependency>
        <groupId>com.groupdocs</groupId>
        <artifactId>groupdocs-viewer</artifactId>
        <version>{0}</version>
      </dependency>
    </dependencies>

    <repositories>
      <repository>
        <id>repository.groupdocs.com</id>
        <name>GroupDocs Repository</name>
        <url>https://repository.groupdocs.com/repo/</url>
      </repository>
    </repositories>
  content: |
    ```java {style=abap}
    // Örnek Görüntüleyici 
    try (Viewer viewer = new Viewer("resume.pdf"))
    {
        // HTML çıktı seçeneklerini ayarlama  
        HtmlViewOptions viewOptions = 
        HtmlViewOptions.forEmbeddedResources();

        // Gömülü kaynaklarla PDF'yi HTML'ye dönüştürün
        viewer.view(viewOptions);
    }
    ```
############################# Overview ############################
overview:
  enable: true
  title: "Bir bakışta GroupDocs.Viewer"
  description: "Java uygulamalarında belgeleri, slaytları, diyagramları ve diğer birçok belge türünü işlemek, görüntülemek, dönüştürmek için API"
  features:
    # feature loop
    - title: "Belgeleri verimli ve güvenilir bir şekilde görüntüleyin"
      content: "GroupDocs.Viewer API ile, içerik ve belge yapısı bütünlüğünü korurken, esnek ve güçlü seçeneklerle desteklenebilir herhangi bir formattaki belgeleri verimli bir şekilde HTML, JPEG, PNG ve PDF'ye dönüştürebilirsiniz. GroupDocs.Viewer, Windows ve Linux platformlarında çalışır."

    # feature loop
    - title: "En popüler dosya ve belge formatları desteklenir"
      content: "Word, Excel, PDF, PowerPoint, OpenDocument format ailesi, Arşivler, Raster ve Vektör görselleri, e-Kitaplar, programlama dilleri ve işaretlemeler ve şifreli dahil olmak üzere diğer birçok dosya türünü içeren 180'den fazla popüler dosya ve belge formatının görüntülenmesini destekliyoruz Şifre korumalı dosyalar."

    # feature loop
    - title: "Özelleştirilebilir çıktı"
      content: "GroupDocs.Viewer sadece belgenin render edilmesine değil, aynı zamanda belgenin tam olarak nasıl, hangi bölümlerinin veya şimdi render edilmesi gerektiğinin, nasıl render edilmesi gerektiğinin kontrol edilmesine ve render edilen çıktıya farklı dönüşümler uygulanmasına da olanak sağlar."

    # feature loop
    - title: "Bahar çerçevesi için Web kullanıcı arayüzü"
      content: "Spring çerçevesi için projenize birkaç dakika içinde eklenebilecek açık kaynaklı bir UI paketi sunuyoruz. Viewer.UI paketi, Angular tabanlı bir web kullanıcı arayüzü içerir ve bir dizi yararlı API ve veri depolama sağlayıcısı sunar."

############################# Platforms ############################
platforms:
  enable: true
  title: "Platform bağımsızlığı"
  description: "GroupDocs.Viewer for Java aşağıdaki işletim sistemlerini, çerçeveleri ve paket yöneticilerini destekler"
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
    - title: "Maven"
      image: "maven"


############################# File formats ############################
formats:
  enable: true
  title: "Desteklenen dosya formatları"
  description: |
    GroupDocs.Viewer for Java, aşağıdaki [dosya formatlarıyla](https://docs.groupdocs.com/viewer/java/supported-document-formats/) yapılan işlemleri destekler.
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office, OpenDocument ve metin formatları
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
        ### Görseller, Grafikler ve Diyagramlar
        * **Raster görüntüler:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
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
        ### Diğer        
        * **ağ:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **Arşivler:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **Diğer:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "GroupDocs.Viewer özellikleri"
  description: "PDF ve Office Belgelerini sorunsuz bir şekilde oluşturun, görüntüleyin ve dönüştürün"

  items:
    # feature loop
    - icon: "viewhtml"
      title: "Belgeleri HTML'de görüntüleme"
      content: "Her türden belgeyi CSS ve SVG ile herhangi bir modern web tarayıcısında görüntülenebilecek bir HTML belgesine dönüştürün."

    # feature loop
    - icon: "rasterize"
      title: "Belgeleri rasterleştirme"
      content: "Desteklenebilir herhangi bir belge formatını, ayarlanabilir görüntü formatı ve sıkıştırma kalitesiyle taramalı görüntüye rasterleştirin."

    # feature loop
    - icon: "sourcecode"
      title: "Programlama kodlarını işleyin ve vurgulayın"
      content: "Sözdizimlerini ayrıştırma ve vurgulama özelliğiyle tüm popüler programlama, komut dosyası yazma ve işaretleme dillerini destekler."

    # feature loop
    - icon: "convertpdf"
      title: "PDF'ye dönüştür"
      content: "Desteklenebilir herhangi bir formattaki belge, ayarlanabilir seçeneklerle kolayca dönüştürülebilir ve PDF'ye kaydedilebilir."

    # feature loop
    - icon: "transform"
      title: "Dönüşümleri uygula"
      content: "Çıktı belgesi, oluşturma sırasında dönüştürülebilir; sayfalar döndürülebilir ve/veya yeniden düzenlenebilir ve bunların üzerine metin filigranı yerleştirilebilir."

    # feature loop
    - icon: "adjustment"
      title: "HTML çıktı ayarı"
      content: "GroupDocs.Viewer tarafından oluşturulan çıktı HTML belgeleri çok hassas bir şekilde ayarlanabilir: harici veya gömülü kaynaklar, geri aramalar vb. ile akışa veya dosyaya kaydedilmesine izin verilir."

    # feature loop
    - icon: "complex"
      title: "Karmaşık belge yapılarının desteklenmesi"
      content: "GroupDocs.Viewer yalnızca tek belgeleri değil, aynı zamanda ekleri olan e-posta mesajları, klasörler içindeki dahili dosyalara sahip ZIP arşivleri, çok sayfalı TIFF görüntüleri vb. gibi dahili olarak bir liste veya belgelerin hiyerarşik yapısını içeren dosyaları da destekler."

    # feature loop
    - icon: "optimization"
      title: "Optimizasyon seçenekleri"
      content: "GroupDocs.Viewer, belgelerin önbelleğe alınmış sürümlerini kullanarak yükleme süresini kısaltabilen ayarlanabilir bir önbellek alt sistemi içerir. Ayrıca, farklı formatlar için bir dizi farklı seçenek, genel performansı optimize etmek için belgelerin bazı gereksiz bölümlerini veya yönlerini (yazı tipleri, gizli çalışma sayfaları, e-posta ekleri) oluşturmanın dışında bırakmanıza olanak tanır"

    # feature loop
    - icon: "passwordprotected"
      title: "Parola korumalı belgelerin desteği"
      content: "GroupDocs.Viewer, yükleme seçeneklerinde bir parola belirleyerek PDF, Kelime İşleme, Elektronik Tablo, Sunum ve diğerleri gibi farklı türlerdeki şifrelenmiş belgeleri açmanıza olanak tanır."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Kod örnekleri"
  description: "Java işlemleri için tipik GroupDocs.Viewer'ın bazı kullanım durumları"
  items:
    # code sample loop
    - title: "DOCX'i HTML'ye dönüştür"
      content: |
        [HtmlViewOptions](https://reference.groupdocs.com/viewer/java/com.groupdocs.viewer.options/htmlviewoptions/) sınıfı özellikleri, dönüştürme sürecini kontrol etmenize olanak tanır; bununla ilgili daha fazla bilgiyi [burada](https://docs.groupdocs.com/viewer/java/rendering-to-html/). Örneğin, tüm harici kaynakları çıktı HTML dosyasına gömebilir, çıktı dosyasını küçültebilir ve yazdırma için optimize edebilirsiniz.
        {{< landing/code title="Java">}}
        ```java {style=abap}
        import com.groupdocs.viewer.Viewer;
        import com.groupdocs.viewer.options.HtmlViewOptions;

        // Örnek Görüntüleyici
        try (Viewer viewer = new Viewer("resume.docx"))
        {
            // Çıktı HTML seçeneklerini ayarlama
            HtmlViewOptions options = 
            HtmlViewOptions.forEmbeddedResources();

            // Gömülü kaynaklarla DOCX'i HTML'ye dönüştürün
            viewer.view(options);
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "PPTX'i PDF'ye aktar"
      content: |
        Bir [PdfViewOptions](https://reference.groupdocs.com/viewer/java/com.groupdocs.viewer.options/pdfviewoptions/) sınıf örneği oluşturun ve bunu [Viewer.View](https://reference.php) öğesine aktarın. PowerPoint PPTX dosyasını PDF'ye dönüştürmek için yöntem. PdfViewOptions sınıfının özellikleri, dönüştürme sürecini kontrol etmenize olanak tanır. Örneğin, çıktı PDF dosyasını koruyabilir, sayfalarını yeniden sıralayabilir ve belge görüntülerinin kalitesini belirleyebilirsiniz. Ayrıntılar için [aşağıdaki belgeler bölümüne](https://docs.groupdocs.com/viewer/java/rendering-to-pdf/) bakın.
        {{< landing/code title="Java">}}
        ```java {style=abap}   
        import com.groupdocs.viewer.Viewer;
        import com.groupdocs.viewer.options.PdfViewOptions;

        // Örnek Görüntüleyici
        try (Viewer viewer = new Viewer("presentation.pptx"))
        {            
            // Çıktı PDF seçeneklerini ayarlama
            PdfViewOptions viewOptions = new PdfViewOptions();

            // PPTX'i PDF'ye aktar
            viewer.view(viewOptions);
        }
        ```
        {{< /landing/code >}}
############################# Reviews ############################
# reviews:
# enable: true
# title: "GroupDocs ürün incelemeleri"
# description: "Sadece bizim sözümüze güvenmeyin. Diğer geliştiricilerin API'lerimiz hakkında neler söylediğini görün"

# items:
#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "Mükemmel servis ve mükemmel ürünler. GroupDocs.Viewer for .NET uygulama sürecinde son derece yardımsever ve duyarlı davrandılar, onları yeterince tavsiye edemem."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "GroupDocs.Viewer for .NET'i projede uygulayıp kullandıktan sonra çok iyi çalışıyor gibi görünüyor. Çok sayıda belgeyle test ettim ve şu ana kadar her şey yolunda. Yaptığım her şey güzel bir şekilde işleniyor ve bir PDF görüntüleyicide veya MS Word'de olduğu kadar iyi görünüyor."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---