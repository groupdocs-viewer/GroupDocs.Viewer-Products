---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: ms

############################# Head #############################
head_title: ".NET DWF Viewer API - Baca, Lihat, Render dalam C# VB.NET"
head_description: "API pemapar dokumen .NET untuk membaca, membuat dan memaparkan DWF dalam sebarang jenis aplikasi C#, ASP.NET, VB.NET & .NET Core."

############################# Header ############################
title: "DWF Pemapar Fail Untuk Aplikasi C# .NET" 
description: "API pemapar dokumen .NET untuk membaca, membuat dan memaparkan fail DWF dalam sebarang jenis aplikasi C#, ASP.NET, VB.NET & .NET Core. Lihat fail yang diberikan dengan pemformatan & reka letak sebenar dalam HTML5, PDF atau sebagai imej menggunakan beberapa baris kod." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Muat turun Percubaan Percuma"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Mengenai GroupDocs.Viewer untuk .NET API" 
    content: |
        Mula melihat 190+ format dokumen popular dalam aplikasi .NET anda menggunakan GroupDocs.Viewer untuk API .NET dengan menambahkan beberapa baris kod. Pembangun boleh dengan mudah memaparkan PDF, Pemprosesan Perkataan, Hamparan Excel, Persembahan, Visio, Projek, Outlook dan banyak lagi format dokumen popular dalam mod HTML5, imej atau PDF. Penyampaian dokumen adalah pantas, sama dengan fail sumber asal, dan ia tidak memerlukan pemasangan perisian tambahan atau mana-mana perpustakaan luaran lain.

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
    title_left: "Langkah-langkah untuk Memaparkan fail DWF dalam C#" 
    content_left: |
        Dengan [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/) anda boleh memaparkan DWF kepada HTML, JPEG, PNG atau PDF dalam beberapa langkah.

        * Pasang [GroupDocs.Viewer untuk .NET](https://www.nuget.org/packages/groupdocs.viewer) menggunakan pengurus pakej kegemaran anda. 
        * Buat contoh kelas Viewer dan muatkan fail DWF dengan laluan penuh. 
        * Tetapkan pilihan untuk memaparkan fail DWF ke dalam format HTML, PNG, JPEG atau PDF. 
        * Render fail dan semak output dalam direktori semasa. 
        
    title_right: "Keperluan Sistem" 
    content_right: |
        GroupDocs.Viewer untuk API .NET disokong pada semua platform dan sistem pengendalian utama. Sebelum melaksanakan kod di bawah, sila pastikan anda mempunyai prasyarat berikut dipasang pada sistem anda.

        * Sistem Pengendalian: Microsoft Windows, Linux, MacOS 
        * Persekitaran Pembangunan: Microsoft Visual Studio, Visual Studio Code, .NET CLI 
        * Rangka Kerja: Rangka Kerja .NET, Standard .NET, Teras .NET, .NET 
    code: |
        ```cs
                        
            // Set up input DWF file
            string filePath = "input.dwf";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render DWF file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "DWF Demo Langsung Penonton"
    content: |
        Lihat fail DWF sekarang dengan melawati tapak web [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/dwf).
    lang: "ms"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Paparan & Paparan Format Fail Lain menggunakan C#"
    exclude: "DWF"
    content: |
        API pemapar dokumen dan imej berbilang format untuk .NET. Lihat beberapa format fail popular di bawah tanpa sebarang pemapar luaran.
    format: 
        # format loop 1
        - name: "Render DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Dokumen XML Terbuka Microsoft Word" 

        # format loop 2
        - name: "Render CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "Fail CorelDRAW" 

        # format loop 3
        - name: "Render PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "Persembahan XML Terbuka PowerPoint" 

        # format loop 4
        - name: "Buat XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Hamparan XML Terbuka Microsoft Excel" 

        # format loop 5
        - name: "Render DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "Lukisan AutoCAD"

        # format loop 6
        - name: "Render XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "Fail XML"

        # format loop 7
        - name: "Render JPA"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Dokumen Adobe Photoshop"

        # format loop 8
        - name: "Render fail Adobe Illustrator"
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
          description: "Fail Teks Biasa" 

        # format loop 11
        - name: "Render DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Melukis Fail Format Pertukaran"  
          
        # format loop 12
        - name: "Render VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "Fail vCard"  
              
        # format loop 13
        - name: "Render SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Grafik Vektor Boleh Skala" 
          
        # format loop 14
        - name: "Render HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Fail Bahasa Penanda Hiperteks" 
          
        # format loop 15
        - name: "Render PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Fail Format Dokumen Mudah Alih"
          
        # format loop 16
        - name: "Render JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "Imej JPEG"
          
        # format loop 17
        - name: "Paparkan PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Grafik Rangkaian Mudah Alih" 
          
        # format loop 18
        - name: "Render EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "Mesej E-Mel" 
          
        # format loop 19
        - name: "Render RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Fail Format Teks Kaya" 
          
        # format loop 20
        - name: "Render ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "Dokumen Teks OpenDocument" 
          
        # format loop 21
        - name: "Render CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Fail Nilai Dipisahkan Koma" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
