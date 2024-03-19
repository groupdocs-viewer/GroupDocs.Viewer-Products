---
############################# Static ############################
layout: "format"
date: 2024-03-19T07:01:03
draft: false
lang: id
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head #############################
head_title: ".NET SH Viewer API - baca, lihat, render dalam C# VB.NET"
head_description: "API penampil dokumen .NET untuk membaca, merender, dan menampilkan SH di semua jenis aplikasi C#, ASP.NET, VB.NET & .NET Core."

############################# Header ############################
title: "SH penampil file untuk aplikasi C# .NET" 
description: "API penampil dokumen .NET untuk membaca, merender, dan menampilkan file SH dalam semua jenis aplikasi C#, ASP.NET, VB.NET & .NET Core. Lihat file yang dirender dengan format & tata letak sebenarnya dalam HTML5, PDF, atau sebagai gambar menggunakan beberapa baris kode." 
subtitle: "Solusi rendering dokumen" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "Unduh Nuget gratis"
      link: "https://releases.groupdocs.com/viewer/net/"



############################# About ############################
about:
    enable: true
    title: "Tentang GroupDocs.Viewer untuk .NET API"
    link: "/viewer/net/"
    link_title: "Belajarlah lagi"
    picture: "about_viewer.svg" # 480 X 400
    content: |
      Mulai lihat 190+ format dokumen populer di aplikasi .NET Anda menggunakan GroupDocs.Viewer untuk .NET API dengan menambahkan beberapa baris kode. Pengembang dapat dengan mudah menampilkan PDF, Pemrosesan Kata, Excel Spreadsheet, Presentasi, Visio, Project, Outlook dan banyak format dokumen populer lainnya dalam mode HTML5, gambar atau PDF. Render dokumen cepat, identik dengan file sumber asli, dan tidak memerlukan instalasi perangkat lunak tambahan atau perpustakaan eksternal lainnya.



############################# Steps ############################
steps:
    enable: true
    title: "Langkah-langkah merender file SH di C#" 
    content: |
      Dengan <a href='https://products.groupdocs.com/viewer/net/'>GroupDocs.Viewer</a> Anda dapat merender SH ke HTML, JPEG, PNG, atau PDF dalam beberapa langkah.
      
      1. Instal <a href='https://www.nuget.org/packages/groupdocs.viewer'>GroupDocs.Viewer untuk .NET</a> menggunakan pengelola paket favorit Anda. 
      2. Buat instance kelas Viewer dan muat file SH dengan path lengkap.  
      3. Tetapkan opsi untuk merender file SH ke dalam format HTML, PNG, JPEG, atau PDF. 
      4. Render file dan periksa output di direktori saat ini. 
   
    code:
      platform: "net"
      copy_title: "Menyalin"
      install:
        command: "dotnet add package GroupDocs.Viewer"
        copy_tip: "klik untuk menyalin"
        copy_done: "disalin"
      links:
        #  loop
        - title: "Lebih banyak contoh"
          link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
        #  loop
        - title: "Dokumentasi"
          link: "https://docs.groupdocs.com/viewer/net/"
          
      content: |
        ```csharp {style=abap}

        // Siapkan file masukan SH
        string filePath = "input.sh";

        // Buat instance GroupDocs.Viewer
        using (Viewer viewer = new Viewer(filePath))
        {
            // Tetapkan opsi tampilan
            HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                
            // Render file SH ke HTML dengan sumber daya yang disematkan
            viewer.View(viewOptions);
        }

        ```            


############################# Actions ############################

actions:
  enable: true
  title: "Siap untuk memulai?"
  description: "Coba fitur GroupDocs.Viewer secara gratis atau minta lisensi"
  items:
    #  loop
    - title: "Unduhan nuget"
      link: "https://releases.groupdocs.com/viewer/net/"
      color: "red"
        #  loop
    - title: "Perizinan"
      link: "https://purchase.groupdocs.com/pricing/viewer/net/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "Render format file lain menggunakan C#"
    exclude: "SH"
    description: "Dokumen multi-format dan API penampil gambar untuk .NET. Lihat beberapa format file populer di bawah ini tanpa pemirsa eksternal."
    items: 
        # format loop 1
        - name: "Render DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word Open XML Document" 

        # format loop 2
        - name: "Render CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "CorelDRAW File" 

        # format loop 3
        - name: "Render PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint Open XML Presentation" 

        # format loop 4
        - name: "Render XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet" 

        # format loop 5
        - name: "Render DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "AutoCAD Drawing"

        # format loop 6
        - name: "Render XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "XML File"

        # format loop 7
        - name: "Render PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Adobe Photoshop Document"

        # format loop 8
        - name: "Render AI"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Adobe Illustrator Artwork"

        # format loop 9
        - name: "Render DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Microsoft Word Document" 

        # format loop 10
        - name: "Render TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Plain Text File" 

        # format loop 11
        - name: "Render DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Drawing Exchange Format File"  
          
        # format loop 12
        - name: "Render VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "vCard File"  
              
        # format loop 13
        - name: "Render SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Scalable Vector Graphic" 
          
        # format loop 14
        - name: "Render HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "Render PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Portable Document Format File"
          
        # format loop 16
        - name: "Render JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "JPEG Image"
          
        # format loop 17
        - name: "Render PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Portable Network Graphic" 
          
        # format loop 18
        - name: "Render EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "E-Mail Message" 
          
        # format loop 19
        - name: "Render RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Rich Text Format File" 
          
        # format loop 20
        - name: "Render ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "OpenDocument Text Document" 
          
        # format loop 21
        - name: "Render CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Comma-Separated Values File" 



---
