---
############################# Static ##########################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

lang: id
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: ".NET Document Viewer API, Render PDF Word Excel Image HTML Diagram"
head_description: "C# ASP.NET file viewer & rendering API. Tambahkan penampil PDF, penampil Word, penampil Excel, penampil Gambar, penampil HTML, fitur penampil Email di aplikasi .NET."

############################# Header ##########################
title: "Render & Tampilkan Dokumen melalui .NET API"
description: ".NET Document Viewer API untuk Merender 190+ format dokumen menjadi PDF, HTML, dan Gambar dengan Opsi Konfigurasi yang Kuat."
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
              text: "Ringkasan"

            # button loop
            - link: "#features"
              text: "Fitur"

            # button loop
            - link: "#support"
              text: "Mendukung"

            # button loop
            - link: "https://products.groupdocs.app/viewer/total"
              text: "Demo Langsung"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Harga"

    right:
        link_download: "https://www.nuget.org/packages/GroupDocs.Viewer"
        link_learn: "https://docs.groupdocs.com/viewer/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    content: |
      GroupDocs.Viewer untuk .NET API membantu Anda membuat aplikasi canggih dalam C#, ASP.NET, dan teknologi berbasis .NET lainnya, yang dapat merender dan menampilkan dokumen dan gambar dari 190+ format file tanpa menginstal perangkat lunak eksternal apa pun. Pustaka penampil file meraster dokumen dan kemudian mengubahnya menjadi SVG+HTML+CSS untuk mengoptimalkan keseluruhan pengalaman rendering dokumen untuk melihat dokumen bisnis, gambar, file teks, diagram, grafik, lampiran email, dan file PDF dengan kecepatan, teks asli, dan fidelitas tinggi di dalam aplikasi Anda. Anda memiliki opsi untuk menambahkan fungsionalitas melihat dan membaca dokumen dalam aplikasi Anda untuk menampilkan seluruh dokumen, sebagian dokumen, halaman/rentang sel tertentu, lapisan dokumen individual, dengan atau tanpa anotasi dan komentar untuk format file yang didukung.
       
      GroupDocs.Viewer untuk .NET meng-cache keluaran dokumen yang dirender ke disk lokal secara default. Semua jenis penyimpanan cache eksternal juga didukung dengan mengimplementasikan antarmuka yang sesuai – Amazon S3, Dropbox, Google Drive, Windows Azure, Redis atau lainnya.
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          Berikut adalah ikhtisar GroupDocs.Viewer untuk .NET:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Ringkasan"
          content: |
            * Tampilkan 190+ Jenis Dokumen 
            * Dapatkan file dalam format HTML, Gambar, PDF 
            * Putar & Susun Ulang 
            * Terapkan Tanda Air 
            * Cache untuk Proses Cepat 
            * Tambahkan Font Kustom 
            * Terapkan Standar Pengodean 
            * Penangan Data Input Kustom 
            * Render dengan Lacak Perubahan 
            * Render sebagai HTML Responsif 
            * Render Lapisan PDF & CAD 
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Viewer untuk .NET mendukung tampilan semua format file dokumen populer. Hanya dengan beberapa baris kode, tambahkan penampil PDF, Microsoft Office Word, spreadsheet Excel, Gambar, HTML, email Outlook, OneNote, Proyek, dan kemampuan tampilan grafik di aplikasi .NET Anda.

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
                * **File Tata Letak Halaman:** PDF, TEX, XPS, OXPS
                * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG, OTG, FODP, FODG
                * **Nilai yang Dipisahkan Pembatas:** CSV, TSV
                * **Web:** HTML, MHT, MHTML
                * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
                * **PostScript:** PS, EPS
                * **Arsip:** ZIP, TAR, BZ2, GZ, RAR, RAR5
                * **Bermacam-macam:** OBJ, EPUB, MOBI, DjVu, XML, VCF, VCARD, NUMBERS, NSF

        right:
          enable: true
          table:
            # table loop
            - title: "Gambar, Grafik & Diagram"
              content: |
                * **Gambar-gambar:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB
                * **Ikon Jendela:** ICO
                * **Grafik Vektor yang Dapat Diskalakan:** SVG, CDR, CMX, IGS, SVGZ
                * **JPEG2000:** JP2, J2C, J2K, JPC, JPF, JPX, JPM
                * **Adobe Photoshop:** PSD, PSB
                * **Bahasa Perintah Pencetak:** PCL
                * **Litografi Stereo (Pencetakan 3D):** STL
                * **Kelas Yayasan Industri:** IFC
                * **Pencitraan medis:** DICOM
                * **Dokumen Plotter:** PLT, HPG
                * **Format Web Desain Autodesk:** DWF, DWG
                * **Menggambar AutoCAD:** DWT, IFC, STL, CF2
                * **DGN berbasis ISFF (V7):** DGN

            # table loop
            - title: "Format Bahasa Pemrograman"
              content: |
                * **File C/C++/C#:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
                * **File Java/JavaScript:** JAVA, JS, JSON, PROPERTIES
                * **Bermacam-macam:** VB, PHP, SQL, PL, PY, PV, RB, RST, SASS, SCALA, SCM, SCRIPT, AS, AS3, ASM, BAT, CMAKE, CSS, DIFF, ERB, GROOVY, HAML, LESS, LOG, M, MAKE, MD, ML, MM, SH, SML, VIM, YAML

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Viewer untuk .NET mendukung Sistem Operasi, Kerangka & Manajer Paket berikut:
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Sistem operasi"
              content: |
                * Microsoft Windows Server 2003 dan yang lebih baru 
                * Microsoft Windows XP dan yang lebih baru 
                * Microsoft Windows 10 & 11 
                * Linux (Ubuntu, OpenSUSE, CentOS dan lainnya) 
                * Mac OS X 

            # table loop
            - icon: "fas fa-code"
              title: "Framework yang Didukung"
              content: |
                * .NET Framework 2.0 atau lebih tinggi 
                * .NET Inti 3.1 
                * .NET 5 atau lebih tinggi 

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-box"
              title: "Manajer Paket"
              content: |
                * NuGet

            # table loop
            - icon: "fas fa-tools"
              title: "Lingkungan Pengembangan"
              content: |
                * Microsoft Visual Studio
                * Visual Studio Code
                * .NET CLI

############################# Features ############################
features:
    enable: true
    title: "GroupDocs.Viewer untuk Fitur .NET"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "Raster Dokumen dan Ubah menjadi SVG, HTML & CSS"

      # feature loop
      - icon: "fas fa-eye"
        content: "Konversikan Teks ke HTML dan Render Dokumen untuk mendapatkan Representasi HTML, Gambar, atau PDF"

      # feature loop
      - icon: "fas fa-bolt"
        content: "Waktu Pemuatan Lebih Cepat menggunakan Versi Tembolok Dokumen"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "Konversi Presentasi dengan Bentuk dan Teks dengan Efek 3D"

      # feature loop
      - icon: "fas fa-code"
        content: "Enkode Dokumen Word, Excel, dan Email ke Standar Pengkodean yang Diinginkan"

      # feature loop
      - icon: "fas fa-cloud"
        content: "Render Dokumen terletak di FTP atau Cloud Storage Locations"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "Mengecualikan Font saat Merender ke HTML untuk mengurangi Ukuran File yang Dihasilkan"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "Perkecil Keluaran CSS & HTML dengan Menghapus Komentar, Spasi Putih Ekstra, dll."

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "Baca Teks yang Terkandung dalam Dokumen Sumber melalui Koordinatnya"

      # feature loop
      - icon: "fas fa-border-all"
        content: "Tampilkan/Sembunyikan Garis Kisi Lembar Excel dalam Representasi Keluaran"

      # feature loop
      - icon: "fas fa-wrench"
        content: "Tentukan Jumlah Baris dalam lembar Excel yang akan dirender di Setiap Halaman"

      # feature loop
      - icon: "fas fa-columns"
        content: "Abaikan Kolom Kosong saat Merender Dokumen Spreadsheet"

      # feature loop
      - icon: "fas fa-file-word"
        content: "Render Dokumen Word menjadi Halaman HTML, Gambar, atau PDF, dengan Lacak Perubahan"

      # feature loop
      - icon: "fas fa-envelope"
        content: "Render Lampiran Email sebagai File Asli, Gambar, atau dalam representasi HTML"

      # feature loop
      - icon: "fas fa-print"
        content: "Tetapkan batasan pencetakan pada dokumen PDF"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "Render Konten/File yang terdapat dalam Arsip ZIP sebagai Lampiran"

      # feature loop
      - icon: "fas fa-lock"
        content: "Dapatkan Lampiran dari Dokumen yang Dilindungi Kata Sandi"

      # feature loop
      - icon: "fas fa-file-code"
        content: "Render Format File Bahasa Pemrograman sebagai Teks Biasa"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "Sesuaikan Warna Latar Belakang saat Melihat Gambar CAD"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "Lihat dokumen Excel dan Konversi ke PDF, HTML, JPG & PNG"

      # feature loop
      - icon: "fas fa-heading"
        content: "Dapatkan Nama Lembar Kerja dari file Excel – Tampilkan Judul Kolom Spreadsheet dan nomor Baris"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "Lihat & Konversi Dokumen Proyek Microsoft dengan Catatan"

      # feature loop
      - icon: "fas fa-cube"
        content: "Konversi Gambar CAD ke SVG untuk Pengalaman Melihat & Memperbesar yang lebih baik"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "Pilih untuk Merender Angka Visio tanpa Skema"

    more_feature:
      # more_feature_loop
      - title: "Lihat Dokumen Secara Efisien & Andal"
        content: |
          Dengan menggunakan GroupDocs.Viewer API, Anda dapat menampilkan lebih dari 190 format dokumen secara efisien dan andal dengan konten dan integritas struktur dokumen utuh. Kode contoh berikut menunjukkan betapa mudahnya melihat representasi HTML dari dokumen DOCX:

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
      - title: "Terapkan Transformasi ke Output yang Dirender"
        content: "Anda dapat melakukan berbagai transformasi ke dokumen keluaran yang dirender menggunakan GroupDocs.Viewer untuk .NET API. Opsi transformasi ini memberi Anda kendali atas cara Anda menampilkan output yang dirender untuk ditampilkan. Transformasi yang tersedia adalah, opsi rotasi halaman, opsi penyusunan ulang halaman, dan penerapan watermark teks."

      # more_feature_loop
      - title: "Bekerja dengan File Data Outlook"
        content: "GroupDocs.Viewer untuk .NET API dapat merender item dalam File Data Outlook (OST/PST) sebagai File PDF, HTML, dan Gambar. API Penampil kami juga memiliki kemampuan untuk mendapatkan daftar folder yang terdapat dalam File Data Outlook. Menggunakan GroupDocs.Viewer untuk .NET API, Anda dapat menentukan folder yang akan dirender dari File Data Outlook. Demikian pula, Anda juga dapat memperoleh pesan email yang terdapat dalam format OST/PST sebagai lampiran. GroupDocs.Viewer untuk .NET juga memungkinkan Anda memfilter pesan dari format OST/PST berdasarkan subjek, konten, atau pengirim."

      # more_feature_loop
      - title: "Bekerja dengan Dokumen CAD"
        content: "GroupDocs.Viewer untuk .NET API dapat merender model dan semua tata letak tidak kosong atau merender tata letak tertentu dari file CAD. GroupDocs.Viewer untuk .NET API juga mendukung rendering ubin atau rendering dengan koordinat dokumen CAD menjadi gambar, HTML, atau PDF. Anda juga dapat memperoleh status lapisan untuk dokumen CAD."

############################# Testimonials ###############################
testimonials:
  enable: true

  testimonial:
    # testimonial item loop
    - name: "Margot Baill"
      designation: "Direktur Pengembangan Produk di Hireology"
      content: "Mengintegrasikan GroupDocs.Viewer untuk Cloud API sangat mudah dengan Ruby SDK mereka yang fantastis. Tidak banyak perusahaan di luar sana yang mau bekerja sama dengan kami untuk apa yang kami inginkan. Ini kemitraan yang hebat."

    # testimonial item loop
    - name: "Mats Oustad"
      designation: "Konsultan Senior/Mitra di Novanet AS"
      content: "Setelah mengimplementasikan dan menggunakan GroupDocs.Viewer untuk .NET dalam proyek ini tampaknya bekerja dengan sangat baik. Saya telah menguji dengan banyak dokumen dan sejauh ini bagus. Semua yang saya lemparkan membuatnya bagus dan terlihat sebagus di penampil PDF atau MS Word."
              
    # testimonial item loop
    - name: "Martin Lasarga"
      designation: "Manajer Produk di Axentria ECM oleh G.S.I."
      content: "Layanan prima dan produk unggulan. Mereka sangat membantu dan responsif selama GroupDocs.Viewer untuk proses implementasi .NET, tidak dapat merekomendasikan mereka dengan cukup tinggi."

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Viewer menawarkan API tampilan dokumen untuk lingkungan pengembangan populer lainnya"

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
