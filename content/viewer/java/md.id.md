---
layout: "auto-gen"
date: 2022-07-07T12:44:18+03:00
draft: false

head_title: "Java MD Viewer API - Render & Tampilan MD di Aplikasi Java"
head_description: "Lihat file MD di aplikasi Java, J2EE, J2SE. Mendukung tampilan 150+ format file dokumen dan gambar dalam mode HTML, PDF, atau gambar dengan fitur-fitur canggih untuk mengelola opsi tampilan dokumen."

title: "Render & Lihat File MD di Java"
description: "API penampil file MD asli dan berkinerja tinggi untuk aplikasi berbasis Java, J2EE dan J2SE, mendukung berbagai fitur tambahan untuk menyesuaikan tampilan format dokumen keluaran."

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
    title: "Tentang GroupDocs.Viewer untuk Java API"
    content: |
        Aktifkan aplikasi Java Anda untuk menampilkan lebih dari 150+ format file dalam mode HTML, PDF, atau gambar menggunakan GroupDocs.Viewer untuk API Java tanpa menginstal perangkat lunak tambahan apa pun; seperti Microsoft Office, Apache Open Office, Adobe Acrobat Reader dll. Pengembang dapat dengan mudah melihat semua gambar populer dan jenis dokumen termasuk Microsoft Office, OpenDocument, HTML, PDF, Arsip, Diagram, Photoshop, AutoCAD dan format bahasa pemrograman di dalam aplikasi Java dengan rendering yang cepat dan berkualitas tinggi.

steps:
    enable: true
    title_left: "Langkah-langkah untuk Melihat File MD di Java"
    content_left: |
        [GroupDocs.Viewer](/viewer/java/) memudahkan pengembang Java untuk menambahkan fitur tampilan file MD di aplikasi mereka menggunakan beberapa baris kode.

        * Buat instance kelas Viewer dan muat file MD dengan path lengkap.
        * Atur opsi tampilan untuk mengonversi file MD ke format PNG.
        * Konversi file dan periksa output di direktori saat ini.
        
    title_right: "Persyaratan sistem"
    content_right: |
        GroupDocs.Viewer untuk Java API didukung di semua platform dan sistem operasi utama. Sebelum menjalankan kode di bawah ini, pastikan Anda telah menginstal prasyarat berikut di sistem Anda.

        * Sistem Operasi: Microsoft Windows, Linux, MacOS
        * Lingkungan Pengembangan: NetBeans, IntelliJ IDEA, Eclipse dll.
        * Lingkungan Runtime Java: Java 7 (1.7) ke atas
        * Dapatkan versi terbaru GroupDocs.Viewer untuk Java dari [GroupDocs Artifact Repository](https://repository.groupdocs.com/webapp/#/artifacts/browse/tree/General/repo/com/groupdocs/groupdocs-viewer)
        
    code: |
        ```java
        // Buat instance penampil
        try (Viewer viewer = new Viewer("sample.md"))
        {
        	// Setel opsi tampilan
        	PngViewOptions viewOptions = new PngViewOptions();
        	// Konversi file ke PNG dan periksa output di direktori saat ini
        	viewer.view(viewOptions);
        }
        ```
        
demos:
    enable: true
    title: "Demo Langsung Pemirsa MD"
    content: |
        Tampilkan file MD sekarang dengan mengunjungi situs web [GroupDocs.Viewer](https://products.groupdocs.app/viewer/). Demo langsung memiliki manfaat sebagai berikut.
        
about_formats:
    enable: true
    format:
        - icon: "far fa-file-md"
          title: "Tentang Format Berkas MD"
          content: |
            File teks yang dibuat dengan dialek bahasa Markdown disimpan dengan ekstensi file .MD atau .MARKDOWN. File MD disimpan dalam format teks biasa yang menggunakan bahasa penurunan harga yang juga menyertakan simbol teks sebaris, yang menentukan bagaimana teks dapat diformat seperti lekukan, pemformatan tabel, font, dan header. File MD dapat dikonversi ke HTML dengan program bernama Markdown. Bahasa penurunan harga dirilis oleh John Gruber.

          link: "https://docs.fileformat.com/word-processing/md/"

more_formats:
    enable: true
    title: "Rendering & Tampilan Format File Lainnya"
    content: |
        Dokumen multi format dan API penampil gambar untuk Java. Lihat beberapa format file populer di bawah ini tanpa pemirsa eksternal.
    format: 
        - name: "Penampil DOC Java"
          link: "/viewer/java/doc/"
          description: "Dokumen Microsoft Word"

        - name: "Penampil DOCM Java"
          link: "/viewer/java/docm/"
          description: "Dokumen Berkemampuan Makro Microsoft Word"

        - name: "Penampil DOCX Java"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Buka Dokumen XML"

        - name: "Java DOT Viewer"
          link: "/viewer/java/dot/"
          description: "Templat Dokumen Microsoft Word"

        - name: "Java DOTM Viewer"
          link: "/viewer/java/dotm/"
          description: "Templat Microsoft Word Macro-Enabled"

        - name: "Penampil Java DOTX"
          link: "/viewer/java/dotx/"
          description: "Templat Dokumen XML Word Terbuka"

        - name: "Penampil RTF Java"
          link: "/viewer/java/rtf/"
          description: "Format File Teks Kaya"

        - name: "Penampil TXT Java"
          link: "/viewer/java/txt/"
          description: "Format File Teks Biasa"

        - name: "Penampil Java XLS"
          link: "/viewer/java/xls/"
          description: "Format File Biner Microsoft Excel"

        - name: "Penampil Java XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Buka XML Spreadsheet"

        - name: "Penampil Java XLSM"
          link: "/viewer/java/xlsm/"
          description: "Spreadsheet Berkemampuan Makro Microsoft Excel"

        - name: "Penampil Java XLSB"
          link: "/viewer/java/xlsb/"
          description: "File Spreadsheet Biner Microsoft Excel"

        - name: "Penampil Java XLTX"
          link: "/viewer/java/xltx/"
          description: "Templat XML Terbuka Microsoft Excel"

        - name: "Penampil TSV Jawa"
          link: "/viewer/java/tsv/"
          description: "File Nilai Terpisah Tab"

        - name: "Penampil Java XLAM"
          link: "/viewer/java/xlam/"
          description: "Add-In Microsoft Excel Macro-Enabled"

        - name: "Penampil CSV Java"
          link: "/viewer/java/csv/"
          description: "File Nilai Dipisahkan Koma"

        - name: "Penampil PPT Java"
          link: "/viewer/java/ppt/"
          description: "Presentasi powerpoint"

        - name: "Penampil PPS Java"
          link: "/viewer/java/pps/"
          description: "Pertunjukan Slide Microsoft PowerPoint"

        - name: "Penampil PPTX Jawa"
          link: "/viewer/java/pptx/"
          description: "Presentasi PowerPoint Terbuka XML"

        - name: "Penampil PPSX Java"
          link: "/viewer/java/ppsx/"
          description: "PowerPoint Terbuka XML Slide Show"

        - name: "Penampil Java POTX"
          link: "/viewer/java/potx/"
          description: "Templat XML Terbuka Microsoft PowerPoint"

        - name: "Java POTM Viewer"
          link: "/viewer/java/potm/"
          description: "Templat Microsoft PowerPoint"

        - name: "Penampil PPTM Jawa"
          link: "/viewer/java/pptm/"
          description: "Presentasi Microsoft PowerPoint"

        - name: "Penampil PPSM Jawa"
          link: "/viewer/java/ppsm/"
          description: "Pertunjukan Slide Microsoft PowerPoint"

        - name: "Penampil PDF Jawa"
          link: "/viewer/java/pdf/"
          description: "Format Dokumen Portabel Adobe"

        - name: "Penampil Java XPS"
          link: "/viewer/java/xps/"
          description: "Buka Spesifikasi Kertas XML"

        - name: "Penampil Java TEX"
          link: "/viewer/java/tex/"
          description: "Dokumen Sumber LaTeX"

        - name: "Penampil ODS Java"
          link: "/viewer/java/ods/"
          description: "Buka Spreadsheet Dokumen"

        - name: "Penampil ODP Jawa"
          link: "/viewer/java/odp/"
          description: "Format File Presentasi OpenDocument"

        - name: "Penampil OTP Jawa"
          link: "/viewer/java/otp/"
          description: "Templat Grafik Asal"

        - name: "Penampil ODT Jawa"
          link: "/viewer/java/odt/"
          description: "Buka Teks Dokumen"

        - name: "Penampil OTT Jawa"
          link: "/viewer/java/ott/"
          description: "Buka Templat Dokumen"

        - name: "Penampil Java VST"
          link: "/viewer/java/vst/"
          description: "Gambar XML Microsoft Visio 2003-2010"

        - name: "Penampil TIFF Jawa"
          link: "/viewer/java/tiff/"
          description: "Format File Gambar yang Ditandai"

        - name: "Penampil JPEG Java"
          link: "/viewer/java/jpeg/"
          description: "Gambar JPEG"

        - name: "Penampil PNG Jawa"
          link: "/viewer/java/png/"
          description: "Grafik Jaringan Portabel"

        - name: "Penampil GIF Jawa"
          link: "/viewer/java/gif/"
          description: "File Format Pertukaran Grafis"

        - name: "Penampil BMP Jawa"
          link: "/viewer/java/bmp/"
          description: "Format File Bitmap"

        - name: "Penampil ICO Jawa"
          link: "/viewer/java/ico/"
          description: "File Ikon Microsoft"

        - name: "Penampil PSD Jawa"
          link: "/viewer/java/psd/"
          description: "Dokumen Adobe Photoshop"



        - name: "Penampil WEBP Java"
          link: "/viewer/java/webp/"
          description: "Format File Gambar Web Raster"

        - name: "Penampil SVG Java"
          link: "/viewer/java/svg/"
          description: "File Grafik Vektor yang Dapat Diskalakan"

        - name: "Penampil Java JP2"
          link: "/viewer/java/jp2/"
          description: "File Gambar Inti JPEG 2000"

        - name: "Penampil MPP Jawa"
          link: "/viewer/java/emz/"
          description: "Dokumen Proyek Microsoft"

        - name: "Penampil MPT Jawa"
          link: "/viewer/java/wmz/"
          description: "Templat Proyek Microsoft"

        - name: "Penampil HTML Java"
          link: "/viewer/java/html/"
          description: "Hyper Text Markup Language"

        - name: "Penampil MHT Jawa"
          link: "/viewer/java/mht/"
          description: "Enkapsulasi MIME dari HTML Agregat"

        - name: "Penampil Java MHTML"
          link: "/viewer/java/mhtml/"
          description: "Enkapsulasi MIME dari HTML Agregat"

        - name: "Penampil MSG Java"
          link: "/viewer/java/msg/"
          description: "Pesan Email Microsoft Outlook"

        - name: "Penampil EML Java"
          link: "/viewer/java/eml/"
          description: "Pesan email"

        - name: "Penampil Java ONE"
          link: "/viewer/java/one/"
          description: "Microsoft OneNote"


        - name: "Penampil WMF Jawa"
          link: "/viewer/java/wmf/"
          description: "Metafile Windows"

        - name: "Penampil EMF Jawa"
          link: "/viewer/java/emf/"
          description: "Format Metafile yang Ditingkatkan"

        - name: "Penampil PSD Jawa"
          link: "/viewer/java/psd/"
          description: "Dokumen Adobe Photoshop"

        - name: "Penampil Java VSD"
          link: "/viewer/java/vsd/"
          description: "Gambar Microsoft Visio 2003-2010"

        - name: "Penampil Java VSDX"
          link: "/viewer/java/vsdx/"
          description: "Gambar Microsoft Visio"

        - name: "Penampil Java VSS"
          link: "/viewer/java/vss/"
          description: "Microsoft Visio 2003-2010 Stensil"

        - name: "Penampil Java VDX"
          link: "/viewer/java/vdx/"
          description: "Gambar XML Microsoft Visio 2003-2010"

        - name: "Penampil VDW Java"
          link: "/viewer/java/vdw/"
          description: "Gambar Web Microsoft Visio 2010"

        - name: "Penampil EPUB Jawa"
          link: "/viewer/java/epub/"
          description: "Format File E-Book Digital"


back_to_top:
    enable: true
---
