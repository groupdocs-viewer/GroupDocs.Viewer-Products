---
############################# Static ##########################
layout: "family"
date: 2023-12-20T06:39:57
draft: false

product: "Viewer"
product_tag: "viewer"

############################# Head ############################
head_title: "Belgeleri Oluşturma ve Görüntüleme API'si | Şirket İçi API ve çevrimiçi hizmet"
head_description: "Word, PDF, Excel, Powerpoint veya Resim dosyalarını kolayca ve ücretsiz olarak oluşturun ve görüntüleyin"

############################# Header ##########################
title: "Belgeleri kolaylıkla işleyin ve görüntüleyin"
description: |
  Farklı dosyaları PDF, HTML ve Görüntüye dönüştürmek için Güçlü Görüntüleyici API'si.

  Dosyalar, akışlar, URL'ler, FTP sunucuları, Amazon S3, Azure Blob Depolama ve daha fazlası dahil olmak üzere çeşitli kaynaklardan belgeler yükleyin.

  Duyarlı HTML sayfaları oluşturun, çıktı PDF dosyalarını koruyun ve sayfalarını yeniden sıralayın, sayfaları döndürün, gerekirse notları ve yorumları işleyin.

############################# Platforms ############################
supported_platforms:
  enable: true  
  head_title: "Platformunuzu seçin"
  title: "Desteklenen platformlar"
  description: "GroupDocs.Viewer kitaplığı aşağıdaki işletim sistemlerini ve çerçeveleri destekler"
  details_link_title: "Daha fazla bilgi edin"
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
        - content: "180'den fazla dosya formatı"
          rows: "1"
        # features loop
        - content: "ASP.NET Core için kullanıcı arayüzü paketi"
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
        - content: "180'den fazla dosya formatı"
          rows: "1"
        # features loop
        - content:  "Spring ve Dropwizard için kullanıcı arayüzü paketi"
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
        - content:  "180'den fazla dosya formatı"
          rows: "1"
        # features loop
        - content:  "Kullanıcı arayüzü paketi - çok yakında"
          rows: "1" 
        # features loop
        - content:  "Demo - yakında"
          rows: "3" 


############################# Features ############################

features:
  enable: true
  title: "GroupDocs.Viewer'ın özellik seti"
  description: "Uygulamalarda farklı türdeki dosyaları HTML, PDF, PNG ve JPEG olarak işlemek ve bunları üçüncü taraf yazılım olmadan görüntülemek için API."

  items:
    # feature loop
    - icon: "view"
      title: "Belgeleri ve resimleri görüntüleyin"
      content: "Belgeleri HTML, PDF, PNG ve JPEG dosyaları olarak işleyerek görüntüleyin."

    # feature loop
    - icon: "password"
      title: "Güvenli belgeleri açın"
      content: "Şifrelenmiş belgeleri açmak için bir parola belirtin."

    # feature loop
    - icon: "load"
      title: "Dosyaları her yerden yükleyin"
      content: "Çeşitli dosyalardan, URL'lerden, FTP sunucularından, Amazon S3'ten ve daha fazlasından belge yükleyin."
    
    # feature loop
    - icon: "pages"
      title: "Tüm sayfaları veya belirli sayfaları oluştur"
      content: "İşlenecek sayfa numaraları aralığını belirtin."


############################# Code samples ############################
code_samples:
  enable: true
  title: "GroupDocs.Viewer kod örnekleri"
  description: "C#, Java ve TypeScript'teki tipik GroupDocs.Viewer işlemlerinin bazı kullanım durumları"
  items:
    # code sample loop
    - title: "DOCX dosyalarını PDF'ye dönüştürme"
      content: |
       Microsoft Word veya başka bir yazılım yüklenmeden DOCX belgelerini PDF'ye dönüştürün. İster web ister masaüstü uygulaması olsun, .NET uygulamanızdaki DOCX dosyalarını kolayca yükleyin ve görüntüleyin. Bir DOCX dosyasının PDF'ye nasıl dönüştürüleceğine ilişkin bir örnek:
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Oluşturulacak DOCX dosyasını yükleyin
            using (Viewer viewer = new Viewer("sample.docx"))
            {
              // DOCX'i PDF dosyasına dönüştür
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
            // Oluşturulacak DOCX dosyasını yükleyin
            try (Viewer viewer = new Viewer("sample.docx")) {
                // DOCX'i PDF dosyasına dönüştür
                PdfViewOptions viewOptions = new PdfViewOptions();
                viewer.view(viewOptions);
            }
            ```
        - language: "TypeScript"
          color: "green"
          content: |
            ```javascript {style=abap}  
            // Oluşturulacak DOCX dosyasını yükleyin
            const viewer = new groupdocs.viewer.Viewer("sample.docx")
            
            // DOCX'i PDF dosyasına dönüştür
            const viewOptions = groupdocs.viewer.PdfViewOptions(output.pdf)
            viewer.view(viewOptions)
            ```


############################# Formats ############################
formats:
  enable: true
  title:  "180'den fazla dosya formatı desteklenir"
  description: "GroupDocs.Viewer, en popüler [dosya formatlarıyla](https://docs.groupdocs.com/viewer/net/supported-document-formats/) işlemleri destekler."


############################# Metrics ############################

metrics:
  enable: true
  title: "Ayrıntılı ölçümler ve istatistiksel bilgiler"
  description: "Başarılarımıza, etkimize ve büyümemize ilişkin kapsamlı ölçümler ve istatistiksel bilgiler sağlayan önemli rakamlarımızın ayrıntılı bir dökümünü inceleyin."

  items:
    # metrics loop
    - number: "180+"
      title: "Desteklenen formatlar"
      content: "Belgeler, resimler ve CAD çizimleri de dahil olmak üzere 180'den fazla dosya formatını sorunsuz bir şekilde kolayca görüntüleyin. Kapsamlı görüntüleme çözümümüzle uyumluluk engellerini aşın ve çeşitli dosyalara zahmetsizce erişin."
    # metrics loop
    - number: "1.0M"
      title: "NuGet indirmeleri"
      content: "NuGet paket çözümümüz, geliştirici topluluğunda güvenilir ve yaygın olarak benimsenen bir kaynak haline geldi ve sayısız proje için kusursuz entegrasyon ve değerli işlevsellik sağladı."

    # metrics loop
    - number: "10+"
      title: "Kütüphaneler"
      content: "Ürünümüz, performansı optimize etmek için gelişmiş özellikler sunan 10'dan fazla kitaplık içerir. Bu kütüphaneler, benzersiz yeteneklerle farklı geliştirme ihtiyaçlarını karşılamak üzere tasarlanmıştır."
    
    # metrics loop
    - number: "100+"
      title: "Memnun müşteriler"
      content: "Dünyanın en ikonik markalarına hizmet veriyoruz. Yüzlerce kişinin GroupDocs.Viewer'ı neden sevdiğini keşfedin! Sorunsuz gezinmeyi, rahat işbirliğini ve benzersiz kullanım kolaylığını keşfedin. Şimdi Katıl!"


############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "Mutlu müşterilerimiz"
  description: "GroupDocs kütüphaneleri dünya çapında tanınmış ve seçkin markalar tarafından kullanılmaktadır."

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
  title: "başlamaya hazır mısın?"
  description: "GroupDocs.Viewer özelliklerini ücretsiz deneyin veya lisans isteyin"

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
  title: "Sık sorulan sorular ve endişeler"
  description: "Sorularınızı ve endişelerinizi hızla gidermek için sık sorulan soruların yanıtlarını SSS bölümümüzde bulabilirsiniz."

  items:
    #  loop
    - question: "GroupDocs ürünlerini satın almadan önce değerlendirebilir miyim?"
      answer: |
        Evet! Tüm GroupDocs ürünlerinin risksiz bir değerlendirme sürümü mevcuttur. İhtiyaçlarınızı %100 karşıladıklarından emin olmak için geliştiricilerin satın almadan önce API'lerimizi indirip denemelerini önemle tavsiye ederiz.
    #  loop
    - question: "GroupDocs ürün tanıtımları yapıyor mu?"
      answer: |
        Hayır, odak noktamız API'lerimiz ve mümkün olan en işlevsel ve istikrarlı ürünleri sunmaktır. Ürünü kendiniz test edebilmeniz için [geçici lisans](https://purchase.groupdocs.com/temporary-license/) biçiminde tamamen işlevsel ve ücretsiz denemeler sunuyoruz.
    #  loop
    - question: "Ürünü nereden indirebilirim?"
      answer: |
        Tüm ürünler [web sitesinden](https://releases.groupdocs.com) indirilebilir. Yazılımımızın fiziksel kopyalarını posta yoluyla göndermiyoruz.    
    #  loop
    - question: "GroupDocs geliştirici lisansları kullanıcı başına mı, yoksa adlandırılmış kullanıcı başına mı?"
      answer: |
        GroupDocs Geliştirici lisansları, adlandırılmış kullanıcı başına değil, kullanıcı başınadır. Kodlama ekibinin üyelerinin zaman içinde değişebileceğini ve her seferinde lisansı güncelleme zorunluluğunun pratik olmadığını biliyoruz.
    #  loop
    - question: "Yalnızca aktif geliştiriciler için lisansa ihtiyacımız var mı? Örneğin, A vardiyasında çalışan iki geliştiriciden oluşan bir ekibimiz ve B vardiyasında çalışan iki geliştiriciden oluşan ikinci bir ekibimiz var… bu durumda iki veya dört lisansa mı ihtiyacımız var?"
      answer: |
        Proje üzerinde çalışan tüm geliştiricilerin lisans alması gerekir. Bu durumda GroupDocs ekibinizin dört üyeden oluştuğunu görür (her ne kadar farklı zamanlarda çalışıyor olsalar da).

############################# Cloud ############################

cloud_links:
  enable: true
  title: "GroupDocs.Viewer düşük kodlu API'ler"
  description: "Bulut tabanlı REST API'miz ile her türlü uygulamada belge veya resim görüntülemeyi hızlandırın"

  items:
    #  loop
    - icon: "groupdocs_viewer-for-curl"
      title: "GroupDocs.Viewer Cloud for cURL"
      link: "https://products.groupdocs.cloud/viewer/curl"
      content: "Uygulamalarınızda Microsoft Office, PDF ve diğer çeşitli standart dosya formatlarını verimli bir şekilde oluşturmak ve sergilemek için cURL RESTful belge görüntüleyici API'sini kullanın."

    #  loop
    - icon: "groupdocs_viewer-for-net"
      title: "GroupDocs.Viewer Cloud for .NET"
      link: "https://products.groupdocs.cloud/viewer/net"
      content: ".NET için Cloud SDK ile .NET uygulamalarındaki belge görüntüleme yeteneklerini geliştirin. Belgeleri HTML, PDF veya resim formatlarında sorunsuz bir şekilde görüntüleyin."
    #  loop
    - icon: "groupdocs_viewer-for-java"
      title: "GroupDocs.Viewer Cloud for Java"
      link: "https://products.groupdocs.cloud/viewer/java"
      content: "Java için özel olarak oluşturulmuş Belge Görüntüleyici SDK'sını kullanarak gelişmiş belge oluşturma yeteneklerini Java uygulamalarınıza entegre edin."

############################# Apps ############################

app_links:
  enable: true
  title: "GroupDocs.Viewer NoCode uygulamaları"
  description: "Tarayıcıda 180'den fazla popüler dosya formatını görüntülemenizi sağlayan çevrimiçi uygulama"

  items:
    #  loop
    - icon: "groupdocs_viewer-app"
      title: "GroupDocs.Viewer Total"
      link: "https://products.groupdocs.app/viewer/total"
      content: "180'den fazla dosya formatını doğrudan tercih ettiğiniz web tarayıcısından görüntülemek için ücretsiz çevrimiçi uygulamayı keşfedin."

    #  loop
    - icon: "groupdocs_words-app"
      title:  "GroupDocs.Viewer DOCX"
      link: "https://products.groupdocs.app/viewer/docx"
      content: "Microsoft Word dosyalarını çeşitli cihazlarda zahmetsizce görüntülemek için web tabanlı araç."

    #  loop
    - icon: "groupdocs_pdf-app"
      title:  "GroupDocs.Viewer PDF"
      link: "https://products.groupdocs.app/viewer/pdf"
      content: "Ücretsiz PDF görüntüleyiciyle PDF dosyalarını çevrimiçi açın ve görüntüleyin."
    

---