---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: ms

############################# Head #############################
head_title: "Java WMZ Viewer API - Render & Display WMZ dalam Java Apps"
head_description: "Lihat WMZ fail dalam aplikasi Java, J2EE, J2SE. Menyokong melihat 170+ format fail dokumen dan imej dalam mod HTML, PDF atau imej dengan ciri lanjutan untuk mengurus pilihan melihat dokumen."

############################# Header ############################
title: "Render & Lihat WMZ Dalam Java" 
description: "API pemapar fail WMZ asli dan berprestasi tinggi untuk aplikasi berasaskan Java, J2EE dan J2SE, menyokong pelbagai ciri tambahan untuk menyesuaikan penampilan format dokumen output." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Muat turun Percubaan Percuma"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Mengenai GroupDocs.Viewer for Java API" 
    content: |
        Dayakan aplikasi Java anda untuk memaparkan lebih 170+ format fail dalam mod HTML, PDF atau imej menggunakan GroupDocs.Viewer untuk API Java tanpa sebarang perisian tambahan dipasang; seperti Microsoft Office, Apache Open Office, Adobe Acrobat Reader dll. Pembangun boleh melihat semua imej dan jenis dokumen popular dengan mudah termasuk Microsoft Office, OpenDocument, HTML, PDF, Arkib, Gambar rajah, Photoshop, AutoCAD dan format bahasa pengaturcaraan di dalam aplikasi Java dengan rendering yang pantas dan berkualiti tinggi.

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
              text: "Rujukan API"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Contoh Kod"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Demo Langsung"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "penentuan harga"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "Langkah-langkah untuk Memaparkan fail WMZ dalam Java" 
    content_left: |
        Dengan [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/) anda boleh memaparkan WMZ kepada HTML, JPEG, PNG atau PDF dalam beberapa langkah.

        * Tambahkan [GroupDocs.Viewer untuk Java](https://releases.groupdocs.com/viewer/java/) sebagai pergantungan kepada projek anda. 
        * Buat contoh kelas Viewer dan muatkan fail WMZ dengan laluan penuh. 
        * Tetapkan pilihan untuk memaparkan fail WMZ ke dalam format HTML, PNG, JPEG atau PDF. 
        * Render fail dan semak output dalam direktori semasa. 
        
    title_right: "Keperluan Sistem" 
    content_right: |
        GroupDocs.Viewer untuk API Java disokong pada semua platform dan sistem pengendalian utama. Sebelum melaksanakan kod di bawah, sila pastikan anda mempunyai prasyarat berikut dipasang pada sistem anda.

        * Sistem Pengendalian: Microsoft Windows, Linux, MacOS 
        * Persekitaran Pembangunan: NetBeans, IntelliJ IDEA, Eclipse dll. 
        * Rangka Kerja: J2SE 8.0 (1.8) atau lebih tinggi (contohnya Java 17) 
    code: |
        ```java
                        
            // Set up input WMZ file
            String filePath = "input.wmz";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render WMZ file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "WMZ Demo Langsung Penonton"
    content: |
        Lihat fail WMZ sekarang dengan melawati tapak web [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/wmz).
    lang: "ms"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Pemaparan & Paparan Format Fail Lain menggunakan Java"
    exclude: "WMZ"
    content: |
        API pemapar dokumen dan imej berbilang format untuk Java. Lihat beberapa format fail popular di bawah tanpa sebarang pemapar luaran.
    format: 
        # format loop 1
        - name: "Render DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Dokumen XML Terbuka Microsoft Word" 

        # format loop 2
        - name: "Render CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "Fail CorelDRAW" 

        # format loop 3
        - name: "Render PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "Persembahan XML Terbuka PowerPoint" 

        # format loop 4
        - name: "Buat XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Hamparan XML Terbuka Microsoft Excel" 

        # format loop 5
        - name: "Render DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "Lukisan AutoCAD"

        # format loop 6
        - name: "Render XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "Fail XML"

        # format loop 7
        - name: "Render JPA"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Dokumen Adobe Photoshop"

        # format loop 8
        - name: "Render fail Adobe Illustrator"
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
          description: "Fail Teks Biasa" 

        # format loop 11
        - name: "Render DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Melukis Fail Format Pertukaran"  
          
        # format loop 12
        - name: "Render VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "Fail vCard"  
              
        # format loop 13
        - name: "Render SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Grafik Vektor Boleh Skala" 
          
        # format loop 14
        - name: "Render HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Fail Bahasa Penanda Hiperteks" 
          
        # format loop 15
        - name: "Render PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Fail Format Dokumen Mudah Alih"
          
        # format loop 16
        - name: "Render JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "Imej JPEG"
          
        # format loop 17
        - name: "Paparkan PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Grafik Rangkaian Mudah Alih" 
          
        # format loop 18
        - name: "Render EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "Mesej E-Mel" 
          
        # format loop 19
        - name: "Render RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Fail Format Teks Kaya" 
          
        # format loop 20
        - name: "Render ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "Dokumen Teks OpenDocument" 
          
        # format loop 21
        - name: "Render CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Fail Nilai Dipisahkan Koma" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
