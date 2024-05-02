---
############################# Static ##########################
layout: "family"
date: 2023-12-20T06:39:57
draft: false

product: "Viewer"
product_tag: "viewer"

############################# Head ############################
head_title: "Render dan Lihat Dokumen API | API Lokal dan layanan online"
head_description: "Render & lihat file Word, PDF, Excel, Powerpoint atau Gambar dengan mudah dan gratis"

############################# Header ##########################
title: "Render dan lihat dokumen dengan mudah"
description: |
  API Penampil yang Kuat untuk Merender berbagai file ke PDF, HTML, dan Gambar.

  Memuat dokumen dari berbagai sumber, termasuk file, aliran, URL, server FTP, Amazon S3, Azure Blob Storage, dan banyak lagi.

  Hasilkan halaman HTML responsif, lindungi file PDF keluaran dan susun ulang halamannya, putar halaman, render catatan dan komentar jika diperlukan.

############################# Platforms ############################
supported_platforms:
  enable: true  
  head_title: "Pilih platform Anda"
  title: "Platform yang didukung"
  description: "Pustaka GroupDocs.Viewer mendukung sistem operasi dan kerangka kerja berikut"
  details_link_title: "Belajarlah lagi"
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
        - content: "180+ format file"
          rows: "1"
        # features loop
        - content: "Paket UI untuk ASP.NET Core"
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
        - content: "180+ format file"
          rows: "1"
        # features loop
        - content:  "Paket UI untuk Spring dan Dropwizard"
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
        - content:  "180+ format file"
          rows: "1"
        # features loop
        - content:  "Paket UI - segera hadir"
          rows: "1" 
        # features loop
        - content:  "Demo - segera hadir"
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
        - content:  "180+ format file"
          rows: "1"
        # features loop
        - content:  "Paket UI - segera hadir"
          rows: "1" 
        # features loop
        - content:  "Demo - segera hadir"
          rows: "3" 

############################# Features ############################

features:
  enable: true
  title: "Kumpulan fitur GroupDocs.Viewer"
  description: "API untuk merender file dari berbagai jenis seperti HTML, PDF, PNG, dan JPEG dalam aplikasi untuk melihatnya tanpa perangkat lunak pihak ketiga."

  items:
    # feature loop
    - icon: "view"
      title: "Lihat dokumen dan gambar"
      content: "Lihat dokumen dengan merendernya sebagai file HTML, PDF, PNG, dan JPEG."

    # feature loop
    - icon: "password"
      title: "Buka dokumen aman"
      content: "Tentukan kata sandi untuk membuka dokumen terenkripsi."

    # feature loop
    - icon: "load"
      title: "Muat file dari mana saja"
      content: "Muat dokumen dari berbagai file, URL, server FTP, Amazon S3, dan lainnya."
    
    # feature loop
    - icon: "pages"
      title: "Render semua atau halaman tertentu"
      content: "Tentukan rentang nomor halaman yang akan dirender."


############################# Code samples ############################
code_samples:
  enable: true
  title: "Contoh kode GroupDocs.Viewer"
  description: "Beberapa kasus penggunaan operasi GroupDocs.Viewer yang umum di C#, Java, TypeScript"
  items:
    # code sample loop
    - title: "Cara merender file DOCX ke PDF"
      content: |
       Render dokumen DOCX ke PDF tanpa menginstal Microsoft Word atau perangkat lunak lain. Memuat dan melihat file DOCX dengan mudah dalam aplikasi .NET Anda, baik itu aplikasi web atau desktop. Berikut adalah contoh cara merender file DOCX ke PDF:
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Muat file DOCX untuk dirender
            using (Viewer viewer = new Viewer("sample.docx"))
            {
              // Render DOCX ke file PDF
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
            // Muat file DOCX untuk dirender
            try (Viewer viewer = new Viewer("sample.docx")) {
                // Render DOCX ke file PDF
                PdfViewOptions viewOptions = new PdfViewOptions();
                viewer.view(viewOptions);
            }
            ```
        - language: "TypeScript"
          color: "green"
          content: |
            ```javascript {style=abap}  
            // Muat file DOCX untuk dirender
            const viewer = new groupdocs.viewer.Viewer("sample.docx")
            
            // Render DOCX ke file PDF
            const viewOptions = groupdocs.viewer.PdfViewOptions(output.pdf)
            viewer.view(viewOptions)
            ```

        - language: "Python"
          color: "yellow"
          content: |
            ```python {style=abap} 
            import groupdocs.viewer as gv
            import groupdocs.viewer.options as gvo   
            // Muat file DOCX untuk dirender
            with gv.Viewer("sample.docx") as viewer:
            
            // Render DOCX ke file PDF
            viewOptions = gvo.PdfViewOptions("output.pdf")
            viewer.view(viewOptions)
            ```

############################# Formats ############################
formats:
  enable: true
  title:  "180+ format file didukung"
  description: "GroupDocs.Viewer mendukung operasi dengan paling popule [format file](https://docs.groupdocs.com/viewer/net/supported-document-formats/)"


############################# Metrics ############################

metrics:
  enable: true
  title: "Metrik mendalam dan wawasan statistik"
  description: "Pelajari rincian angka-angka penting kami, yang memberikan metrik komprehensif dan wawasan statistik mengenai pencapaian, dampak, dan pertumbuhan kami."

  items:
    # metrics loop
    - number: "180+"
      title: "Format yang didukung"
      content: "Lihat lebih dari 180 format file termasuk dokumen, gambar, dan gambar CAD dengan mudah tanpa repot. Hancurkan hambatan kompatibilitas dan akses beragam file dengan mudah menggunakan solusi tampilan komprehensif kami."
    # metrics loop
    - number: "1.0M"
      title: "Unduhan NuGet"
      content: "Solusi paket NuGet kami telah menjadi sumber daya tepercaya dan diadopsi secara luas di komunitas pengembang, menyediakan integrasi tanpa batas dan fungsionalitas berharga untuk banyak proyek."

    # metrics loop
    - number: "10+"
      title: "Perpustakaan"
      content: "Produk kami mencakup 10+ perpustakaan, menawarkan fitur-fitur canggih untuk mengoptimalkan kinerja. Perpustakaan ini dirancang untuk memenuhi kebutuhan pengembangan yang berbeda dengan kemampuan yang tak tertandingi."
    
    # metrics loop
    - number: "100+"
      title: "Pelanggan yang senang"
      content: "Melayani merek paling ikonik di seluruh dunia. Temukan mengapa ratusan orang menyukai GroupDocs.Viewer! Jelajahi navigasi yang lancar, kolaborasi yang nyaman, dan kemudahan penggunaan yang tak tertandingi. Bergabung sekarang!"


############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "Pelanggan kami yang bahagia"
  description: "Perpustakaan GroupDocs digunakan oleh merek-merek terkenal dan terkemuka secara global di seluruh dunia."

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
  title: "Siap untuk memulai?"
  description: "Coba fitur GroupDocs.Viewer secara gratis atau minta lisensi"

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
  title: "Pertanyaan dan kekhawatiran umum"
  description: "Temukan jawaban atas pertanyaan umum di bagian FAQ kami untuk menjawab pertanyaan dan kekhawatiran Anda dengan cepat."

  items:
    #  loop
    - question: "Bisakah saya mengevaluasi produk GroupDocs sebelum membeli?"
      answer: |
        Ya! Semua produk GroupDocs memiliki versi evaluasi yang bebas risiko. Kami sangat menganjurkan pengembang untuk mengunduh dan mencoba API kami sebelum membeli untuk memastikan bahwa API tersebut akan memenuhi kebutuhan Anda 100%.
    #  loop
    - question: "Apakah GroupDocs melakukan demonstrasi produk?"
      answer: |
        Tidak, fokus kami adalah pada API kami dan membuat produk yang paling fungsional dan stabil. Kami menawarkan uji coba yang berfungsi penuh dan gratis dalam bentuk [lisensi sementara](https://purchase.groupdocs.com/temporary-license/) sehingga Anda dapat menguji sendiri produk tersebut.
    #  loop
    - question: "Dimana saya bisa mendownload produknya?"
      answer: |
        Semua produk tersedia untuk diunduh dari [situs web](https://releases.groupdocs.com). Kami tidak mengirimkan salinan fisik perangkat lunak kami melalui surat.    
    #  loop
    - question: "Apakah lisensi pengembang GroupDocs per pengguna, atau per pengguna yang disebutkan namanya?"
      answer: |
        Lisensi Pengembang GroupDocs adalah per pengguna, bukan per pengguna yang disebutkan namanya. Kami memahami bahwa anggota tim coding dapat berubah seiring berjalannya waktu dan tidak praktis jika harus memperbarui lisensi setiap kali hal tersebut terjadi.
    #  loop
    - question: "Apakah kita memerlukan lisensi hanya untuk pengembang aktif? Misalnya, kami memiliki tim yang terdiri dari dua pengembang yang mengerjakan shift A dan tim kedua yang terdiri dari dua pengembang yang mengerjakan shift B… dalam situasi ini, apakah kami memerlukan dua atau empat lisensi?"
      answer: |
        Semua pengembang yang mengerjakan proyek harus memiliki lisensi. Dalam situasi ini, GroupDocs melihat tim Anda memiliki empat anggota (meskipun mereka bekerja pada waktu yang berbeda).

############################# Cloud ############################

cloud_links:
  enable: true
  title: "GroupDocs.Viewer API kode rendah"
  description: "Percepat tampilan dokumen atau gambar di semua jenis aplikasi dengan REST API kami yang berbasis cloud"

  items:
    #  loop
    - icon: "groupdocs_viewer-for-curl"
      title: "GroupDocs.Viewer Cloud for cURL"
      link: "https://products.groupdocs.cloud/viewer/curl"
      content: "Gunakan API penampil dokumen cURL RESTful untuk merender dan menampilkan Microsoft Office, PDF, dan berbagai format file standar lainnya secara efisien dalam aplikasi Anda."

    #  loop
    - icon: "groupdocs_viewer-for-net"
      title: "GroupDocs.Viewer Cloud for .NET"
      link: "https://products.groupdocs.cloud/viewer/net"
      content: "Tingkatkan kemampuan melihat dokumen di aplikasi .NET dengan Cloud SDK untuk .NET. Lihat dokumen dengan lancar dalam format HTML, PDF, atau gambar."
    #  loop
    - icon: "groupdocs_viewer-for-java"
      title: "GroupDocs.Viewer Cloud for Java"
      link: "https://products.groupdocs.cloud/viewer/java"
      content: "Integrasikan kemampuan rendering dokumen tingkat lanjut ke dalam aplikasi Java Anda menggunakan SDK Penampil Dokumen untuk Java yang dibuat khusus."

############################# Apps ############################

app_links:
  enable: true
  title: "Aplikasi NoCode GroupDocs.Viewer"
  description: "Aplikasi online memungkinkan Anda melihat 180+ format file populer di browser"

  items:
    #  loop
    - icon: "groupdocs_viewer-app"
      title: "GroupDocs.Viewer Total"
      link: "https://products.groupdocs.app/viewer/total"
      content: "Jelajahi aplikasi online gratis untuk melihat lebih dari 180 format file langsung dari browser web pilihan Anda."

    #  loop
    - icon: "groupdocs_words-app"
      title:  "GroupDocs.Viewer DOCX"
      link: "https://products.groupdocs.app/viewer/docx"
      content: "Alat berbasis web untuk melihat file Microsoft Word dengan mudah di berbagai perangkat."

    #  loop
    - icon: "groupdocs_pdf-app"
      title:  "GroupDocs.Viewer PDF"
      link: "https://products.groupdocs.app/viewer/pdf"
      content: "Buka dan lihat file PDF online dengan penampil PDF gratis."
    

---