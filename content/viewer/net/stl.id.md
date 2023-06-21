---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: id

############################# Head #############################
head_title: ".NET STL Viewer API - Baca, Lihat, Render dalam C# VB.NET"
head_description: "API penampil dokumen .NET untuk membaca, merender, dan menampilkan STL dalam semua jenis aplikasi C#, ASP.NET, VB.NET & .NET Core."

############################# Header ############################
title: "STL Penampil File Untuk Aplikasi C# .NET" 
description: "API penampil dokumen .NET untuk membaca, merender, dan menampilkan file STL dalam semua jenis aplikasi C#, ASP.NET, VB.NET & .NET Core. Lihat file yang dirender dengan pemformatan & tata letak sebenarnya dalam HTML5, PDF, atau sebagai gambar menggunakan beberapa baris kode." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Unduh Uji Coba Gratis"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Tentang GroupDocs.Viewer untuk .NET API" 
    content: |
        Mulai melihat 190+ format dokumen populer di aplikasi .NET Anda menggunakan GroupDocs.Viewer untuk .NET API dengan menambahkan beberapa baris kode. Pengembang dapat dengan mudah menampilkan PDF, Pemrosesan Kata, Excel Spreadsheet, Presentasi, Visio, Proyek, Outlook, dan banyak format dokumen populer lainnya dalam mode HTML5, gambar, atau PDF. Perenderan dokumen cepat, identik dengan file sumber asli, dan tidak memerlukan penginstalan perangkat lunak tambahan atau pustaka eksternal lainnya.

############################# SubMenu ############################
submenu:
    enable: true

    left:
        img_alt: "GroupDocs.Viewer for .NET"
        image: "https://cms.admin.containerize.com/templates/groupdocs/images/product-logos/90x90-noborder/groupdocs-viewer-net.png"
        product: "GroupDocs.Viewer"
        platform: ".NET"

    middle:
        button:

            # button loop
            - link: "https://apireference.groupdocs.com/viewer/net"
              text: "Referensi API"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Contoh Kode"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Demo Langsung"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Harga"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "Langkah-langkah Render file STL di C#" 
    content_left: |
        Dengan [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/) Anda dapat merender STL ke HTML, JPEG, PNG, atau PDF dalam beberapa langkah.

        * Instal [GroupDocs.Viewer untuk .NET](https://www.nuget.org/packages/groupdocs.viewer) menggunakan pengelola paket favorit Anda. 
        * Buat instance kelas Viewer dan muat file STL dengan path lengkap. 
        * Setel opsi untuk merender file STL ke dalam format HTML, PNG, JPEG, atau PDF. 
        * Render file dan periksa output di direktori saat ini. 
        
    title_right: "Persyaratan sistem" 
    content_right: |
        GroupDocs.Viewer untuk .NET API didukung di semua platform utama dan sistem operasi. Sebelum menjalankan kode di bawah ini, harap pastikan bahwa Anda telah menginstal prasyarat berikut di sistem Anda.

        * Sistem Operasi: Microsoft Windows, Linux, MacOS 
        * Lingkungan Pengembangan: Microsoft Visual Studio, Visual Studio Code, .NET CLI 
        * Kerangka kerja: .NET Framework, .NET Standard, .NET Core, .NET 
    code: |
        ```cs
                        
            // Set up input STL file
            string filePath = "input.stl";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render STL file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "STL Demo Langsung Pemirsa"
    content: |
        Lihat file STL sekarang juga dengan mengunjungi situs web [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/stl).
    lang: "id"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Rendering & Tampilan Format Berkas Lainnya menggunakan C#"
    exclude: "STL"
    content: |
        Dokumen multi-format dan API penampil gambar untuk .NET. Lihat beberapa format file populer di bawah ini tanpa penampil eksternal.
    format: 
        # format loop 1
        - name: "Merender DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Dokumen XML Microsoft Word Terbuka" 

        # format loop 2
        - name: "Render CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "File CorelDraw" 

        # format loop 3
        - name: "Render PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "Presentasi PowerPoint Terbuka XML" 

        # format loop 4
        - name: "Render XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet" 

        # format loop 5
        - name: "Render DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "Menggambar AutoCAD"

        # format loop 6
        - name: "Merender XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "Berkas XML"

        # format loop 7
        - name: "Render PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Dokumen Adobe Photoshop"

        # format loop 8
        - name: "Render file Adobe Illustrator"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Karya Seni Adobe Illustrator"

        # format loop 9
        - name: "Render DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Dokumen Microsoft Word" 

        # format loop 10
        - name: "Render TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "File Teks Biasa" 

        # format loop 11
        - name: "Render DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Menggambar File Format Pertukaran"  
          
        # format loop 12
        - name: "Render VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "File vCard"  
              
        # format loop 13
        - name: "Render SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Grafik Vektor yang Dapat Diskalakan" 
          
        # format loop 14
        - name: "Merender HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "File Bahasa Markup Hiperteks" 
          
        # format loop 15
        - name: "Render PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "File Format Dokumen Portabel"
          
        # format loop 16
        - name: "Render JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "Gambar JPEG"
          
        # format loop 17
        - name: "Render PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Grafik Jaringan Portabel" 
          
        # format loop 18
        - name: "Render EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "Pesan Email" 
          
        # format loop 19
        - name: "Render RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "File Format Teks Kaya" 
          
        # format loop 20
        - name: "Render ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "Dokumen Teks OpenDocument" 
          
        # format loop 21
        - name: "Render CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "File Nilai yang Dipisahkan Koma" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
