---
############################# Static ##########################
layout: "family"
date: 2023-12-20T06:39:57
draft: false

product: "Viewer"
product_tag: "viewer"

############################# Head ############################
head_title: "Render and View Documents API | On Premise API dan perkhidmatan dalam talian"
head_description: "Render & lihat fail Word, PDF, Excel, Powerpoint atau Imej dengan mudah dan percuma"

############################# Header ##########################
title: "Buat dan lihat dokumen dengan mudah"
description: |
  API Pemapar Berkuasa untuk Memaparkan fail berbeza kepada PDF, HTML dan Imej.

  Muatkan dokumen daripada pelbagai sumber, termasuk fail, strim, URL, pelayan FTP, Amazon S3, Storan Azure Blob dan banyak lagi.

  Hasilkan halaman HTML responsif, lindungi fail PDF keluaran dan susun semula halaman mereka, putar halaman, berikan nota dan ulasan jika perlu.

############################# Platforms ############################
supported_platforms:
  enable: true  
  head_title: "Pilih platform anda"
  title: "Platform yang disokong"
  description: "Pustaka GroupDocs.Viewer menyokong sistem pengendalian dan rangka kerja berikut"
  details_link_title: "Ketahui lebih lanjut"
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
        - content: "180+ format fail"
          rows: "1"
        # features loop
        - content: "Pakej UI untuk Teras ASP.NET"
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
        - content: "180+ format fail"
          rows: "1"
        # features loop
        - content:  "Pakej UI untuk Spring dan Dropwizard"
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
        - content:  "180+ format fail"
          rows: "1"
        # features loop
        - content:  "Pakej UI - akan datang tidak lama lagi"
          rows: "1" 
        # features loop
        - content:  "Demo - akan datang tidak lama lagi"
          rows: "3" 


############################# Features ############################

features:
  enable: true
  title: "Set ciri GroupDocs.Viewer"
  description: "API untuk memaparkan fail pelbagai jenis sebagai HTML, PDF, PNG dan JPEG dalam aplikasi untuk melihatnya tanpa perisian pihak ketiga."

  items:
    # feature loop
    - icon: "view"
      title: "Lihat dokumen dan imej"
      content: "Lihat dokumen dengan menjadikannya sebagai fail HTML, PDF, PNG dan JPEG."

    # feature loop
    - icon: "password"
      title: "Buka dokumen selamat"
      content: "Tentukan kata laluan untuk membuka dokumen yang disulitkan."

    # feature loop
    - icon: "load"
      title: "Muatkan fail dari mana-mana sahaja"
      content: "Muatkan dokumen daripada pelbagai fail, URL, pelayan FTP, Amazon S3 dan banyak lagi."
    
    # feature loop
    - icon: "pages"
      title: "Render semua atau halaman tertentu"
      content: "Tentukan julat nombor halaman yang hendak diberikan."


############################# Code samples ############################
code_samples:
  enable: true
  title: "Contoh kod GroupDocs.Viewer"
  description: "Sesetengah kes menggunakan operasi GroupDocs.Viewer biasa dalam C#, Java, TypeScript"
  items:
    # code sample loop
    - title: "Bagaimana untuk menjadikan fail DOCX kepada PDF"
      content: |
       Render dokumen DOCX kepada PDF tanpa Microsoft Word atau perisian lain dipasang. Muatkan dan lihat fail DOCX dengan mudah dalam aplikasi .NET anda, sama ada aplikasi web atau desktop. Berikut ialah contoh cara untuk menjadikan fail DOCX kepada PDF:
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Muatkan fail DOCX untuk dipaparkan
            using (Viewer viewer = new Viewer("sample.docx"))
            {
              // Render DOCX kepada fail PDF
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
            // Muatkan fail DOCX untuk dipaparkan
            try (Viewer viewer = new Viewer("sample.docx")) {
                // Render DOCX kepada fail PDF
                PdfViewOptions viewOptions = new PdfViewOptions();
                viewer.view(viewOptions);
            }
            ```
        - language: "TypeScript"
          color: "green"
          content: |
            ```javascript {style=abap}  
            // Muatkan fail DOCX untuk dipaparkan
            const viewer = new groupdocs.viewer.Viewer("sample.docx")
            
            // Render DOCX kepada fail PDF
            const viewOptions = groupdocs.viewer.PdfViewOptions(output.pdf)
            viewer.view(viewOptions)
            ```


############################# Formats ############################
formats:
  enable: true
  title:  "180+ format fail disokong"
  description: "GroupDocs.Viewer menyokong operasi dengan yang paling popular [format fail](https://docs.groupdocs.com/viewer/net/supported-document-formats/)"


############################# Metrics ############################

metrics:
  enable: true
  title: "Metrik dan cerapan statistik yang mendalam"
  description: "Terokai butiran terperinci angka utama kami, memberikan metrik dan cerapan statistik yang komprehensif tentang pencapaian, impak dan pertumbuhan kami."

  items:
    # metrics loop
    - number: "180+"
      title: "Format yang disokong"
      content: "Lihat lebih 180 format fail dengan mudah termasuk dokumen, imej dan lukisan CAD tanpa kerumitan. Putuskan halangan keserasian dan akses pelbagai fail dengan mudah dengan penyelesaian tontonan komprehensif kami."
    # metrics loop
    - number: "1.0M"
      title: "Muat turun NuGet"
      content: "Penyelesaian pakej NuGet kami telah menjadi sumber yang dipercayai dan diterima pakai secara meluas dalam komuniti pembangun, menyediakan penyepaduan yang lancar dan kefungsian berharga untuk banyak projek."

    # metrics loop
    - number: "10+"
      title: "Perpustakaan"
      content: "Produk kami termasuk 10+ perpustakaan, menawarkan ciri termaju untuk mengoptimumkan prestasi. Perpustakaan ini direka bentuk untuk memenuhi keperluan pembangunan yang berbeza dengan keupayaan yang tiada tandingan."
    
    # metrics loop
    - number: "100+"
      title: "Pelanggan gembira"
      content: "Melayani jenama paling ikonik di seluruh dunia. Temui sebab beratus-ratus suka GroupDocs.Viewer! Terokai navigasi yang lancar, kerjasama yang mudah dan kemudahan penggunaan yang tiada tandingan. Sertai sekarang!"


############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "Pelanggan kami gembira"
  description: "Perpustakaan GroupDocs digunakan oleh jenama terkenal dan terkenal di seluruh dunia di seluruh dunia."

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
  title: "Bersedia untuk bermula?"
  description: "Cuba ciri GroupDocs.Viewer secara percuma atau minta lesen"

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
  title: "Soalan dan kebimbangan biasa"
  description: "Dapatkan jawapan kepada pertanyaan biasa di bahagian Soalan Lazim kami untuk menangani pertanyaan dan kebimbangan anda dengan cepat."

  items:
    #  loop
    - question: "Bolehkah saya menilai produk GroupDocs sebelum membeli?"
      answer: |
        Ya! Semua produk GroupDocs mempunyai versi penilaian bebas risiko yang tersedia. Kami amat menggalakkan pembangun untuk memuat turun dan mencuba API kami sebelum membeli untuk memastikan ia memenuhi keperluan anda 100%.
    #  loop
    - question: "Adakah GroupDocs melakukan demonstrasi produk?"
      answer: |
        Tidak, tumpuan kami adalah pada API kami dan menjadikan produk yang paling berfungsi dan stabil mungkin. Kami menawarkan percubaan yang berfungsi sepenuhnya dan percuma dalam bentuk [lesen sementara](https://purchase.groupdocs.com/temporary-license/) supaya anda boleh menguji produk itu sendiri.
    #  loop
    - question: "Di manakah saya boleh memuat turun produk?"
      answer: |
        Semua produk tersedia untuk dimuat turun dari [tapak web](https://releases.groupdocs.com). Kami tidak menghantar salinan fizikal perisian kami melalui mel.    
    #  loop
    - question: "Adakah lesen pembangun GroupDocs setiap pengguna, atau setiap pengguna bernama?"
      answer: |
        Lesen Pembangun GroupDocs adalah untuk setiap pengguna, bukan setiap pengguna bernama. Kami memahami bahawa ahli pasukan pengekodan mungkin berubah dari semasa ke semasa dan adalah tidak praktikal untuk mengemas kini pelesenan setiap kali berlaku.
    #  loop
    - question: "Adakah kita memerlukan pelesenan untuk pembangun aktif sahaja? Sebagai contoh, kami mempunyai pasukan dua pembangun yang bekerja pada syif A dan pasukan kedua dua pembangun bekerja pada syif B … dalam situasi ini, adakah kami memerlukan dua atau empat lesen?"
      answer: |
        Semua pemaju yang sedang mengusahakan projek itu perlu dilesenkan. Dalam situasi ini, GroupDocs melihat pasukan anda mempunyai empat ahli (walaupun mereka bekerja pada masa yang berbeza).

############################# Cloud ############################

cloud_links:
  enable: true
  title: "API kod rendah GroupDocs.Viewer"
  description: "Mempercepatkan paparan dokumen atau imej dalam sebarang jenis aplikasi dengan API REST berasaskan awan kami"

  items:
    #  loop
    - icon: "groupdocs_viewer-for-curl"
      title: "GroupDocs.Viewer Cloud for cURL"
      link: "https://products.groupdocs.cloud/viewer/curl"
      content: "Gunakan API pemapar dokumen CURL RESTful untuk memaparkan dan mempamerkan Microsoft Office, PDF dan pelbagai format fail standard lain dengan cekap dalam aplikasi anda."

    #  loop
    - icon: "groupdocs_viewer-for-net"
      title: "GroupDocs.Viewer Cloud for .NET"
      link: "https://products.groupdocs.cloud/viewer/net"
      content: "Tingkatkan keupayaan melihat dokumen dalam aplikasi .NET dengan Cloud SDK untuk .NET. Lihat dokumen dengan lancar dalam format HTML, PDF atau imej."
    #  loop
    - icon: "groupdocs_viewer-for-java"
      title: "GroupDocs.Viewer Cloud for Java"
      link: "https://products.groupdocs.cloud/viewer/java"
      content: "Integrasikan keupayaan pemaparan dokumen lanjutan ke dalam aplikasi Java anda menggunakan SDK Pemapar Dokumen yang dibina khas untuk Java."

############################# Apps ############################

app_links:
  enable: true
  title: "Apl NoCode GroupDocs.Viewer"
  description: "Aplikasi dalam talian yang membolehkan anda melihat 180+ format fail popular dalam penyemak imbas"

  items:
    #  loop
    - icon: "groupdocs_viewer-app"
      title: "GroupDocs.Viewer Total"
      link: "https://products.groupdocs.app/viewer/total"
      content: "Terokai aplikasi dalam talian percuma untuk melihat lebih 180 format fail terus daripada pelayar web pilihan anda."

    #  loop
    - icon: "groupdocs_words-app"
      title:  "GroupDocs.Viewer DOCX"
      link: "https://products.groupdocs.app/viewer/docx"
      content: "Alat berasaskan web untuk melihat fail Microsoft Word dengan mudah merentas pelbagai peranti."

    #  loop
    - icon: "groupdocs_pdf-app"
      title:  "GroupDocs.Viewer PDF"
      link: "https://products.groupdocs.app/viewer/pdf"
      content: "Buka dan lihat fail PDF dalam talian dengan pemapar PDF percuma."
    

---