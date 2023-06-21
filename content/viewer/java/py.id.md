---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: id

############################# Head #############################
head_title: "Java PY Viewer API - Render & Tampilkan PY di Aplikasi Java"
head_description: "Lihat file PY dalam aplikasi Java, J2EE, J2SE. Mendukung tampilan 170+ format file dokumen dan gambar dalam mode HTML, PDF, atau gambar dengan fitur lanjutan untuk mengelola opsi tampilan dokumen."

############################# Header ############################
title: "Render & Lihat PY Di Java" 
description: "API penampil file PY asli dan berkinerja tinggi untuk aplikasi berbasis Java, J2EE dan J2SE, mendukung berbagai fitur tambahan untuk menyesuaikan tampilan format dokumen keluaran." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Unduh Uji Coba Gratis"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Tentang GroupDocs.Viewer untuk Java API" 
    content: |
        Aktifkan aplikasi Java Anda untuk menampilkan lebih dari 170+ format file dalam mode HTML, PDF, atau gambar menggunakan GroupDocs.Viewer untuk API Java tanpa memasang perangkat lunak tambahan apa pun; seperti Microsoft Office, Apache Open Office, Adobe Acrobat Reader dll. Pengembang dapat dengan mudah melihat semua gambar populer dan jenis dokumen termasuk Microsoft Office, OpenDocument, HTML, PDF, Arsip, Diagram, Photoshop, AutoCAD dan format bahasa pemrograman di dalam aplikasi Java dengan rendering cepat dan kualitas tertinggi.

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
    title_left: "Langkah-langkah untuk Merender file PY di Java" 
    content_left: |
        Dengan [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/) Anda dapat merender PY ke HTML, JPEG, PNG, atau PDF dalam beberapa langkah.

        * Tambahkan [GroupDocs.Viewer for Java](https://releases.groupdocs.com/viewer/java/) sebagai dependensi ke project Anda. 
        * Buat instance kelas Viewer dan muat file PY dengan path lengkap. 
        * Setel opsi untuk merender file PY ke dalam format HTML, PNG, JPEG, atau PDF. 
        * Render file dan periksa output di direktori saat ini. 
        
    title_right: "Persyaratan sistem" 
    content_right: |
        GroupDocs.Viewer untuk API Java didukung di semua platform dan sistem operasi utama. Sebelum menjalankan kode di bawah ini, harap pastikan bahwa Anda telah menginstal prasyarat berikut di sistem Anda.

        * Sistem Operasi: Microsoft Windows, Linux, MacOS 
        * Lingkungan Pengembangan: NetBeans, IntelliJ IDEA, Eclipse dll. 
        * Kerangka kerja: J2SE 8.0 (1.8) atau lebih tinggi (misalnya Java 17) 
    code: |
        ```java
                        
            // Set up input PY file
            String filePath = "input.py";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render PY file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "PY Demo Langsung Pemirsa"
    content: |
        Lihat file PY sekarang juga dengan mengunjungi situs web [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/py).
    lang: "id"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Rendering & Tampilan Format File Lainnya menggunakan Java"
    exclude: "PY"
    content: |
        Dokumen multi-format dan API penampil gambar untuk Java. Lihat beberapa format file populer di bawah ini tanpa penampil eksternal.
    format: 
        # format loop 1
        - name: "Merender DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Dokumen XML Microsoft Word Terbuka" 

        # format loop 2
        - name: "Render CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "File CorelDraw" 

        # format loop 3
        - name: "Render PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "Presentasi PowerPoint Terbuka XML" 

        # format loop 4
        - name: "Render XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet" 

        # format loop 5
        - name: "Render DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "Menggambar AutoCAD"

        # format loop 6
        - name: "Merender XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "Berkas XML"

        # format loop 7
        - name: "Render PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Dokumen Adobe Photoshop"

        # format loop 8
        - name: "Render file Adobe Illustrator"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Karya Seni Adobe Illustrator"

        # format loop 9
        - name: "Render DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Dokumen Microsoft Word" 

        # format loop 10
        - name: "Render TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "File Teks Biasa" 

        # format loop 11
        - name: "Render DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Menggambar File Format Pertukaran"  
          
        # format loop 12
        - name: "Render VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "File vCard"  
              
        # format loop 13
        - name: "Render SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Grafik Vektor yang Dapat Diskalakan" 
          
        # format loop 14
        - name: "Merender HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "File Bahasa Markup Hiperteks" 
          
        # format loop 15
        - name: "Render PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "File Format Dokumen Portabel"
          
        # format loop 16
        - name: "Render JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "Gambar JPEG"
          
        # format loop 17
        - name: "Render PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Grafik Jaringan Portabel" 
          
        # format loop 18
        - name: "Render EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "Pesan Email" 
          
        # format loop 19
        - name: "Render RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "File Format Teks Kaya" 
          
        # format loop 20
        - name: "Render ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "Dokumen Teks OpenDocument" 
          
        # format loop 21
        - name: "Render CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "File Nilai yang Dipisahkan Koma" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
