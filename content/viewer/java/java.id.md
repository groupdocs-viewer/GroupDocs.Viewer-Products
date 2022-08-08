---
layout: "auto-gen"
date: 2022-07-07T12:44:18+03:00
draft: false

head_title: "JAVA JAVA Viewer API - Render & Tampilan JAVA di Aplikasi JAVA"
head_description: "Lihat file JAVA dalam aplikasi JAVA, J2EE, J2SE. Mendukung tampilan 150+ format file dokumen dan gambar dalam mode HTML, PDF, atau gambar dengan fitur-fitur canggih untuk mengelola opsi tampilan dokumen."

title: "Render & Lihat File JAVA dalam JAVA"
description: "API penampil file JAVA asli dan berkinerja tinggi untuk aplikasi berbasis JAVA, J2EE dan J2SE, mendukung berbagai fitur tambahan untuk menyesuaikan tampilan format dokumen keluaran."

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Unduh Uji Coba Gratis"
    link: "https://downloads.groupdocs.com/viewer/java"

submenu:
    enable: true

    left:
        img_alt: "GroupDocs.Viewer for Java"
        image: "https://cms.admin.containerize.com/templates/groupdocs/images/product-logos/90x90-noborder/groupdocs-viewer-java.png"
        product: "GroupDocs.Viewer"
        platform: "Java"

    middle:
        button:

            - link: "https://apireference.groupdocs.com/viewer/java"
              text: "Referensi API"

            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Java"
              text: "Contoh Kode"

            - link: "https://products.groupdocs.app/viewer/family"
              text: "Demo Langsung"

            - link: "https://purchase.groupdocs.com/pricing/viewer/java"
              text: "Harga"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/java"
        link_learn: "https://docs.groupdocs.com/viewer/java"
        link_buy: "https://purchase.groupdocs.com"

about:
    enable: true
    title: "Tentang GroupDocs.Viewer untuk JAVA API"
    content: |
        Aktifkan aplikasi JAVA Anda untuk menampilkan lebih dari 150+ format file dalam mode HTML, PDF, atau gambar menggunakan GroupDocs.Viewer untuk JAVA API tanpa menginstal perangkat lunak tambahan apa pun; seperti Microsoft Office, Apache Open Office, Adobe Acrobat Reader dll. Pengembang dapat dengan mudah melihat semua gambar populer dan jenis dokumen termasuk Microsoft Office, OpenDocument, HTML, PDF, Arsip, Diagram, Photoshop, AutoCAD, dan format bahasa pemrograman di dalam aplikasi JAVA dengan rendering yang cepat dan berkualitas tinggi.

steps:
    enable: true
    title_left: "Langkah-langkah untuk Melihat File JAVA di JAVA"
    content_left: |
        [GroupDocs.Viewer](viewer/JAVA/) memudahkan pengembang JAVA untuk menambahkan fitur tampilan file JAVA di aplikasi mereka menggunakan beberapa baris kode.

        * Buat instance kelas Viewer dan muat file JAVA dengan path lengkap.
        * Atur opsi tampilan untuk mengonversi file JAVA ke format PNG.
        * Konversi file dan periksa output di direktori saat ini.
        
    title_right: "Persyaratan sistem"
    content_right: |
        GroupDocs.Viewer untuk JAVA API didukung di semua platform dan sistem operasi utama. Sebelum menjalankan kode di bawah ini, pastikan Anda telah menginstal prasyarat berikut di sistem Anda.

        * Sistem Operasi: Microsoft Windows, Linux, MacOS
        * Lingkungan Pengembangan: NetBeans, IntelliJ IDEA, Eclipse dll.
        * JAVA Runtime Environment: JAVA 7 (1.7) ke atas
        * Dapatkan versi terbaru GroupDocs.Viewer untuk JAVA dari [GroupDocs Artifact Repository](https://repository.groupdocs.com/webapp/#/artifacts/browse/tree/General/repo/com/groupdocs/groupdocs-viewer)
        
    code: |
        ```java
        // Buat instance penampil
        try (Viewer viewer = new Viewer("sample.java"))
        {
        	// Setel opsi tampilan
        	PngViewOptions viewOptions = new PngViewOptions();
        	// Konversi file ke PNG dan periksa output di direktori saat ini
        	viewer.view(viewOptions);
        }
        ```
        
demos:
    enable: true
    title: "Demo Langsung Pemirsa JAVA"
    content: |
        Tampilkan file JAVA sekarang dengan mengunjungi situs web [GroupDocs.Viewer](https://products.groupdocs.app/viewer/). Demo langsung memiliki manfaat sebagai berikut.
        
about_formats:
    enable: true
    format:
        - icon: "far fa-file-java"
          title: "Tentang Format Berkas JAVA"
          content: |
            JAVA adalah bahasa berorientasi objek tujuan umum yang dapat berjalan di berbagai platform. Kode sumber JAVA terdapat dalam file dengan ekstensi .JAVA. JAVA digunakan untuk pengembangan aplikasi seluler, aplikasi web, aplikasi desktop, game, dll. JAVA berfungsi di berbagai platform termasuk Windows, Mac, Linux, Raspberry Pi, dll. JAVA sangat mirip dengan C# dan C++ sehingga lebih mudah untuk beralih di antara bahasa-bahasa ini.

          link: "https://docs.fileformat.com/programming/java/"

more_formats:
    enable: true
    title: "Rendering & Tampilan Format File Lainnya"
    content: |
        Dokumen multi format dan API penampil gambar untuk JAVA. Lihat beberapa format file populer di bawah ini tanpa pemirsa eksternal.
    format: 
        - name: "JAVA Penampil DOC"
          link: "/viewer/java/doc/"
          description: "Dokumen Microsoft Word"

        - name: "Penampil DOCM JAVA"
          link: "/viewer/java/docm/"
          description: "Dokumen Berkemampuan Makro Microsoft Word"

        - name: "JAVA Penampil DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Buka Dokumen XML"

        - name: "JAVA DOT Penampil"
          link: "/viewer/java/dot/"
          description: "Templat Dokumen Microsoft Word"

        - name: "Penampil DOTM JAVA"
          link: "/viewer/java/dotm/"
          description: "Templat Microsoft Word Macro-Enabled"

        - name: "Penampil DOTX JAVA"
          link: "/viewer/java/dotx/"
          description: "Templat Dokumen XML Word Terbuka"

        - name: "Penampil RTF JAVA"
          link: "/viewer/java/rtf/"
          description: "Format File Teks Kaya"

        - name: "JAVA TXT Penampil"
          link: "/viewer/java/txt/"
          description: "Format File Teks Biasa"

        - name: "Penampil JAVA XLS"
          link: "/viewer/java/xls/"
          description: "Format File Biner Microsoft Excel"

        - name: "Penampil JAVA XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Buka XML Spreadsheet"

        - name: "JAVA XLSM Penampil"
          link: "/viewer/java/xlsm/"
          description: "Spreadsheet Berkemampuan Makro Microsoft Excel"

        - name: "Penampil JAVA XLSB"
          link: "/viewer/java/xlsb/"
          description: "File Spreadsheet Biner Microsoft Excel"

        - name: "Penampil JAVA XLTX"
          link: "/viewer/java/xltx/"
          description: "Templat XML Terbuka Microsoft Excel"

        - name: "JAVA Penonton TSV"
          link: "/viewer/java/tsv/"
          description: "File Nilai Terpisah Tab"

        - name: "Penampil XLAM JAVA"
          link: "/viewer/java/xlam/"
          description: "Add-In Microsoft Excel Macro-Enabled"

        - name: "Penampil CSV JAVA"
          link: "/viewer/java/csv/"
          description: "File Nilai Dipisahkan Koma"

        - name: "Penampil PPT JAVA"
          link: "/viewer/java/ppt/"
          description: "Presentasi powerpoint"

        - name: "Penampil PPS JAVA"
          link: "/viewer/java/pps/"
          description: "Pertunjukan Slide Microsoft PowerPoint"

        - name: "Penampil PPTX JAVA"
          link: "/viewer/java/pptx/"
          description: "Presentasi PowerPoint Terbuka XML"

        - name: "Penampil JAVA PPSX"
          link: "/viewer/java/ppsx/"
          description: "PowerPoint Terbuka XML Slide Show"

        - name: "Penampil JAVA POTX"
          link: "/viewer/java/potx/"
          description: "Templat XML Terbuka Microsoft PowerPoint"

        - name: "Penampil JAVA POTM"
          link: "/viewer/java/potm/"
          description: "Templat Microsoft PowerPoint"

        - name: "Penampil PPTM JAVA"
          link: "/viewer/java/pptm/"
          description: "Presentasi Microsoft PowerPoint"

        - name: "JAVA Penampil PPSM"
          link: "/viewer/java/ppsm/"
          description: "Pertunjukan Slide Microsoft PowerPoint"

        - name: "JAVA Penampil PDF"
          link: "/viewer/java/pdf/"
          description: "Format Dokumen Portabel Adobe"

        - name: "Penampil JAVA XPS"
          link: "/viewer/java/xps/"
          description: "Buka Spesifikasi Kertas XML"

        - name: "Penampil JAVA TEX"
          link: "/viewer/java/tex/"
          description: "Dokumen Sumber LaTeX"

        - name: "JAVA Penampil ODS"
          link: "/viewer/java/ods/"
          description: "Buka Spreadsheet Dokumen"

        - name: "JAVA Penampil ODP"
          link: "/viewer/java/odp/"
          description: "Format File Presentasi OpenDocument"

        - name: "JAVA Penampil OTP"
          link: "/viewer/java/otp/"
          description: "Templat Grafik Asal"

        - name: "JAVA Penampil ODT"
          link: "/viewer/java/odt/"
          description: "Buka Teks Dokumen"

        - name: "JAVA Penonton OTT"
          link: "/viewer/java/ott/"
          description: "Buka Templat Dokumen"

        - name: "Penonton VST JAVA"
          link: "/viewer/java/vst/"
          description: "Gambar XML Microsoft Visio 2003-2010"

        - name: "Penampil TIFF JAVA"
          link: "/viewer/java/tiff/"
          description: "Format File Gambar yang Ditandai"

        - name: "Penampil JPEG JAVA"
          link: "/viewer/java/jpeg/"
          description: "Gambar JPEG"

        - name: "Penampil PNG JAVA"
          link: "/viewer/java/png/"
          description: "Grafik Jaringan Portabel"

        - name: "Penampil GIF JAVA"
          link: "/viewer/java/gif/"
          description: "File Format Pertukaran Grafis"

        - name: "Penampil BMP JAVA"
          link: "/viewer/java/bmp/"
          description: "Format File Bitmap"

        - name: "JAVA Penampil ICO"
          link: "/viewer/java/ico/"
          description: "File Ikon Microsoft"

        - name: "Penampil PSD JAVA"
          link: "/viewer/java/psd/"
          description: "Dokumen Adobe Photoshop"



        - name: "Penampil WEBP JAVA"
          link: "/viewer/java/webp/"
          description: "Format File Gambar Web Raster"

        - name: "Penampil SVG JAVA"
          link: "/viewer/java/svg/"
          description: "File Grafik Vektor yang Dapat Diskalakan"

        - name: "JAVA JP2 Penampil"
          link: "/viewer/java/jp2/"
          description: "File Gambar Inti JPEG 2000"

        - name: "Penampil MPP JAVA"
          link: "/viewer/java/emz/"
          description: "Dokumen Proyek Microsoft"

        - name: "Penampil JAVA MPT"
          link: "/viewer/java/wmz/"
          description: "Templat Proyek Microsoft"

        - name: "Penampil HTML JAVA"
          link: "/viewer/java/html/"
          description: "Hyper Text Markup Language"

        - name: "Penampil JAVA MHT"
          link: "/viewer/java/mht/"
          description: "Enkapsulasi MIME dari HTML Agregat"

        - name: "JAVA MHTML Penampil"
          link: "/viewer/java/mhtml/"
          description: "Enkapsulasi MIME dari HTML Agregat"

        - name: "JAVA Penampil MSG"
          link: "/viewer/java/msg/"
          description: "Pesan Email Microsoft Outlook"

        - name: "JAVA Penampil EML"
          link: "/viewer/java/eml/"
          description: "Pesan email"

        - name: "JAVA SATU Pemirsa"
          link: "/viewer/java/one/"
          description: "Microsoft OneNote"


        - name: "JAVA Penampil WMF"
          link: "/viewer/java/wmf/"
          description: "Metafile Windows"

        - name: "JAVA Penampil EMF"
          link: "/viewer/java/emf/"
          description: "Format Metafile yang Ditingkatkan"

        - name: "Penampil PSD JAVA"
          link: "/viewer/java/psd/"
          description: "Dokumen Adobe Photoshop"

        - name: "Penampil VSD JAVA"
          link: "/viewer/java/vsd/"
          description: "Gambar Microsoft Visio 2003-2010"

        - name: "Penampil JAVA VSDX"
          link: "/viewer/java/vsdx/"
          description: "Gambar Microsoft Visio"

        - name: "Penampil VSS JAVA"
          link: "/viewer/java/vss/"
          description: "Microsoft Visio 2003-2010 Stensil"

        - name: "Penampil JAVA VDX"
          link: "/viewer/java/vdx/"
          description: "Gambar XML Microsoft Visio 2003-2010"

        - name: "Penampil VDW JAVA"
          link: "/viewer/java/vdw/"
          description: "Gambar Web Microsoft Visio 2010"

        - name: "JAVA EPUB Penampil"
          link: "/viewer/java/epub/"
          description: "Format File E-Book Digital"


back_to_top:
    enable: true
---
