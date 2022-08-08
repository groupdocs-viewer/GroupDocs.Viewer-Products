---
layout: "auto-gen"
date: 2022-07-07T12:44:18+03:00
draft: false

head_title: ".NET WORD Viewer API - Baca, Lihat, Render di C# VB.NET"
head_description: "..NET document viewer API untuk membaca, merender, dan menampilkan file WORD dalam semua jenis aplikasi C#, ASP.NET, VB.NET & .NET Core."

title: "WORD File Viewer untuk Aplikasi C# .NET"
description: "..NET document viewer API untuk membaca, merender, dan menampilkan file WORD dalam semua jenis aplikasi C#, ASP.NET, VB.NET & .NET Core. Lihat file yang dirender dengan format & tata letak yang benar dalam HTML5, PDF, atau sebagai gambar menggunakan beberapa baris kode."

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Unduh Uji Coba Gratis"
    link: "https://downloads.groupdocs.com/viewer/net"

submenu:
    enable: true

    left:
        img_alt: "GroupDocs.Viewer for .NET"
        image: "https://cms.admin.containerize.com/templates/groupdocs/images/product-logos/90x90-noborder/groupdocs-viewer-net.png"
        product: "GroupDocs.Viewer"
        platform: ".NET"

    middle:
        button:

            - link: "https://apireference.groupdocs.com/viewer/net"
              text: "Referensi API"

            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Contoh Kode"

            - link: "https://products.groupdocs.app/viewer/family"
              text: "Demo Langsung"

            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Harga"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

about:
    enable: true
    title: "Tentang GroupDocs.Viewer untuk .NET API"
    content: |
        Mulai lihat 170+ format dokumen populer di aplikasi .NET Anda menggunakan GroupDocs.Viewer untuk .NET API dengan menambahkan beberapa baris kode. Pengembang dapat dengan mudah menampilkan PDF, Pemrosesan WORD, Spreadsheet Excel, Presentasi, Visio, Proyek, Outlook, dan banyak format dokumen populer lainnya dalam mode HTML5, gambar, atau PDF. Render dokumen cepat, identik dengan file sumber asli, dan tidak perlu menginstal Microsoft Office atau pustaka eksternal lainnya.

steps:
    enable: true
    title_left: "Langkah-langkah untuk Melihat File WORD di C#"
    content_left: |
        [GroupDocs.Viewer](viewer/net/) memudahkan pengembang .NET untuk menambahkan fitur tampilan file WORD dalam aplikasi mereka dengan menerapkan beberapa langkah mudah.

        * Buat instance kelas Viewer dan muat file WORD dengan path lengkap.
        * Atur opsi untuk mengonversi file WORD ke format PNG.
        * Konversi file dan periksa output di direktori saat ini.
        
    title_right: "Persyaratan sistem"
    content_right: |
        GroupDocs.Viewer untuk .NET API didukung di semua platform dan sistem operasi utama. Sebelum menjalankan kode di bawah ini, pastikan Anda telah menginstal prasyarat berikut di sistem Anda.

        * Sistem Operasi: Microsoft Windows, Linux, MacOS
        * Lingkungan Pengembangan: Microsoft Visual Studio, Kode Visual Studio, .NET CLI
        * Kerangka: .NET Framework, .NET Standard, .NET Core, .NET
        * Dapatkan GroupDocs.Viewer versi terbaru untuk .NET dari [NuGet](https://www.nuget.org/packages/groupdocs.viewer)
        
    code: |
        ```cs
        // Buat instance penampil
        using (Viewer viewer = new Viewer("sample.docx"))
        {
        	// Setel opsi tampilan 
        	ViewOptions viewOptions = new PngViewOptions();
        	// Konversi file ke PNG dan periksa output di direktori saat ini 
        	viewer.View(viewOptions);
        }
        ```
        
demos:
    enable: true
    title: "Demo Langsung Pemirsa WORD"
    content: |
        Tampilkan file WORD sekarang juga dengan mengunjungi situs web [GroupDocs.Viewer](https://products.groupdocs.app/viewer/WORD). Demo langsung memiliki manfaat sebagai berikut.
        
about_formats:
    enable: true
    format:
        - icon: "far fa-file-word-o"
          title: "Tentang Format Berkas WORD"
          content: |
            File pemrosesan WORD berisi informasi pengguna dalam format teks biasa atau teks kaya. Format file teks biasa berisi teks yang tidak diformat dan tidak ada pengaturan font atau halaman, dll. yang dapat diterapkan. Sebaliknya, format file teks kaya memungkinkan opsi pemformatan seperti pengaturan jenis font, gaya (tebal, miring, garis bawah, dll.), margin halaman, judul, poin dan angka, dan beberapa fitur pemformatan lainnya. Penggunaan file teks biasa telah berkurang secara signifikan dengan berlalunya waktu karena ada komputer dan program yang lebih kuat yang tersedia untuk menawarkan pemrosesan file teks kaya. Ekstensi file teks biasa yang umum dan format file terkait termasuk TXT, CSV, sedangkan ekstensi file untuk dokumen teks kaya termasuk DOCX, DOC, dan RTF.

          link: "https://docs.fileformat.com/word-processing/"

more_formats:
    enable: true
    title: "Rendering & Tampilan Format File Lainnya"
    content: |
        Dokumen multi format dan API penampil gambar untuk .NET. Lihat beberapa format file populer di bawah ini tanpa pemirsa eksternal.
    format: 
        - name: ".Penampil NET DOC"
          link: "/viewer/net/doc/"
          description: "Dokumen Microsoft WORD"

        - name: ".NET DOCM Viewer"
          link: "/viewer/net/docm/"
          description: "Dokumen Microsoft WORD Macro-Enabled"

        - name: ".Penampil NET DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft WORD Buka Dokumen XML"

        - name: ".Penampil DOT BERSIH"
          link: "/viewer/net/dot/"
          description: "Templat Dokumen Microsoft WORD"

        - name: ".Penampil NET DOTM"
          link: "/viewer/net/dotm/"
          description: "Template Microsoft WORD Macro-Enabled"

        - name: ".Penampil NET DOTX"
          link: "/viewer/net/dotx/"
          description: "WORD Buka Templat Dokumen XML"

        - name: ".NET RTF Viewer"
          link: "/viewer/net/rtf/"
          description: "Format File Teks Kaya"

        - name: ".Penampil TXT NET"
          link: "/viewer/net/txt/"
          description: "Format File Teks Biasa"

        - name: ".Penampil NET XLS"
          link: "/viewer/net/xls/"
          description: "Format File Biner Microsoft Excel"

        - name: ".NET XLSX Penampil"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Buka XML Spreadsheet"

        - name: ".NET XLSM Viewer"
          link: "/viewer/net/xlsm/"
          description: "Spreadsheet Berkemampuan Makro Microsoft Excel"

        - name: ".NET XLSB Viewer"
          link: "/viewer/net/xlsb/"
          description: "File Spreadsheet Biner Microsoft Excel"

        - name: ".NET XLTX Viewer"
          link: "/viewer/net/xltx/"
          description: "Templat XML Terbuka Microsoft Excel"

        - name: ".Penampil TSV NET"
          link: "/viewer/net/tsv/"
          description: "File Nilai Terpisah Tab"

        - name: ".NET XLAM Viewer"
          link: "/viewer/net/xlam/"
          description: "Add-In Microsoft Excel Macro-Enabled"

        - name: ".Penampil CSV NET"
          link: "/viewer/net/csv/"
          description: "File Nilai Dipisahkan Koma"

        - name: ".Penampil PPT NET"
          link: "/viewer/net/ppt/"
          description: "Presentasi powerpoint"

        - name: ".NET PPS Viewer"
          link: "/viewer/net/pps/"
          description: "Pertunjukan Slide Microsoft PowerPoint"

        - name: ".Penampil PPTX NET"
          link: "/viewer/net/pptx/"
          description: "Presentasi PowerPoint Terbuka XML"

        - name: ".NET PPSX Viewer"
          link: "/viewer/net/ppsx/"
          description: "PowerPoint Terbuka XML Slide Show"

        - name: ".Penampil NET POTX"
          link: "/viewer/net/potx/"
          description: "Templat XML Terbuka Microsoft PowerPoint"

        - name: ".Penampil NET POTM"
          link: "/viewer/net/potm/"
          description: "Templat Microsoft PowerPoint"

        - name: ".Penampil PPTM NET"
          link: "/viewer/net/pptm/"
          description: "Presentasi Microsoft PowerPoint"

        - name: ".NET PPSM Viewer"
          link: "/viewer/net/ppsm/"
          description: "Pertunjukan Slide Microsoft PowerPoint"

        - name: ".NET PDF Viewer"
          link: "/viewer/net/pdf/"
          description: "Format Dokumen Portabel Adobe"

        - name: ".Penampil NET XPS"
          link: "/viewer/net/xps/"
          description: "Buka Spesifikasi Kertas XML"

        - name: ".Penampil NET TEX"
          link: "/viewer/net/tex/"
          description: "Dokumen Sumber LaTeX"

        - name: ".Penampil NET ODS"
          link: "/viewer/net/ods/"
          description: "Buka Spreadsheet Dokumen"

        - name: ".Penampil ODP NET"
          link: "/viewer/net/odp/"
          description: "Format File Presentasi OpenDocument"

        - name: ".Penampil OTP NET"
          link: "/viewer/net/otp/"
          description: "Templat Grafik Asal"

        - name: ".Penampil NET ODT"
          link: "/viewer/net/odt/"
          description: "Buka Teks Dokumen"

        - name: ".Penampil OTT BERSIH"
          link: "/viewer/net/ott/"
          description: "Buka Templat Dokumen"

        - name: ".Penampil VST NET"
          link: "/viewer/net/vst/"
          description: "Gambar XML Microsoft Visio 2003-2010"

        - name: ".Penampil TIFF BERSIH"
          link: "/viewer/net/tiff/"
          description: "Format File Gambar yang Ditandai"

        - name: ".NET JPEG Viewer"
          link: "/viewer/net/jpeg/"
          description: "Gambar JPEG"

        - name: ".Penampil PNG BERSIH"
          link: "/viewer/net/png/"
          description: "Grafik Jaringan Portabel"

        - name: ".Penampil GIF BERSIH"
          link: "/viewer/net/gif/"
          description: "File Format Pertukaran Grafis"

        - name: ".NET BMP Viewer"
          link: "/viewer/net/bmp/"
          description: "Format File Bitmap"

        - name: ".Penampil ICO NET"
          link: "/viewer/net/ico/"
          description: "File Ikon Microsoft"

        - name: "..NET PSD Viewer"
          link: "/viewer/net/psd/"
          description: "Dokumen Adobe Photoshop"


        - name: ".NET WEBP Viewer"
          link: "/viewer/net/webp/"
          description: "Format File Gambar Web Raster"

        - name: ".Penampil SVG NET"
          link: "/viewer/net/svg/"
          description: "File Grafik Vektor yang Dapat Diskalakan"

        - name: ".NET JP2 Penampil"
          link: "/viewer/net/jp2/"
          description: "File Gambar Inti JPEG 2000"

        - name: ".Penampil MPP NET"
          link: "/viewer/net/emz/"
          description: "Dokumen Proyek Microsoft"

        - name: ".Penampil MPT NET"
          link: "/viewer/net/wmz/"
          description: "Templat Proyek Microsoft"

        - name: ".Penampil HTML NET"
          link: "/viewer/net/html/"
          description: "Hyper Text Markup Language"

        - name: ".NET MHT Viewer"
          link: "/viewer/net/mht/"
          description: "Enkapsulasi MIME dari HTML Agregat"

        - name: ".NET MHTML Viewer"
          link: "/viewer/net/mhtml/"
          description: "Enkapsulasi MIME dari HTML Agregat"

        - name: ".NET MSG Viewer"
          link: "/viewer/net/msg/"
          description: "Pesan Email Microsoft Outlook"

        - name: ".NET EML Viewer"
          link: "/viewer/net/eml/"
          description: "Pesan email"

        - name: ".BERSIH SATU Pemirsa"
          link: "/viewer/net/one/"
          description: "Microsoft OneNote"

        - name: ".NET WMF Viewer"
          link: "/viewer/net/wmf/"
          description: "Metafile Windows"

        - name: ".NET EMF Viewer"
          link: "/viewer/net/emf/"
          description: "Metafile yang Ditingkatkan Windows"

        - name: "..NET PSD Viewer"
          link: "/viewer/net/psd/"
          description: "Dokumen Adobe Photoshop"

        - name: ".NET VSD Viewer"
          link: "/viewer/net/vsd/"
          description: "Gambar Microsoft Visio 2003-2010"

        - name: ".Penampil NET VSDX"
          link: "/viewer/net/vsdx/"
          description: "Gambar Microsoft Visio"

        - name: ".NET VSS Viewer"
          link: "/viewer/net/vss/"
          description: "Microsoft Visio 2003-2010 Stensil"

        - name: ".Penampil VDX NET"
          link: "/viewer/net/vdx/"
          description: "Gambar XML Microsoft Visio 2003-2010"

        - name: ".NET VDW Viewer"
          link: "/viewer/net/vdw/"
          description: "Gambar Web Microsoft Visio 2010"

        - name: ".NET EPUB Viewer"
          link: "/viewer/net/epub/"
          description: "Format File E-Book Digital"


back_to_top:
    enable: true
---
