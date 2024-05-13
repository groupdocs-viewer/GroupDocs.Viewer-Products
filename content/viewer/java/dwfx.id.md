---
############################# Static ############################
layout: "format"
date: 2024-05-13T10:14:32
draft: false
lang: id
product: "Viewer"
product_tag: "viewer"
platform: "Java"
platform_tag: "java"

############################# Head #############################
head_title: "Java DWFX Viewer API - merender & menampilkan DWFX di aplikasi Java"
head_description: "Lihat file DWFX dalam aplikasi Java, J2EE, J2SE. Mendukung melihat 180+ format file dokumen dan gambar dalam mode HTML, PDF atau gambar dengan fitur-fitur canggih untuk mengelola opsi tampilan dokumen."

############################# Header ############################
title: "Render & lihat DWFX di Java" 
description: "API penampil file DWFX asli dan berkinerja tinggi untuk aplikasi berbasis Java, J2EE dan J2SE, mendukung berbagai fitur tambahan untuk menyesuaikan tampilan format dokumen keluaran." 
subtitle: "Solusi rendering dokumen" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "Unduhan Maven gratis"
      link: "https://releases.groupdocs.com/viewer/java/"



############################# About ############################
about:
    enable: true
    title: "Tentang GroupDocs.Viewer untuk Java API"
    link: "/viewer/java/"
    link_title: "Belajarlah lagi"
    picture: "about_viewer.svg" # 480 X 400
    content: |
      Aktifkan aplikasi Java Anda untuk menampilkan lebih dari 180+ format file dalam mode HTML, PDF, atau gambar menggunakan GroupDocs.Viewer untuk Java API tanpa menginstal perangkat lunak tambahan apa pun; seperti Microsoft Office, Apache Open Office, Adobe Acrobat Reader dll. Pengembang dapat dengan mudah melihat semua gambar dan jenis dokumen populer termasuk Microsoft Office, OpenDocument, HTML, PDF, Archive, Diagram, Photoshop, AutoCAD dan format bahasa pemrograman di dalam aplikasi Java dengan rendering cepat dan kualitas tertinggi.



############################# Steps ############################
steps:
    enable: true
    title: "Langkah-langkah untuk merender file DWFX di Java" 
    content: |
      Dengan <a href='https://products.groupdocs.com/viewer/java/'>GroupDocs.Viewer</a> Anda dapat merender DWFX ke HTML, JPEG, PNG, atau PDF dalam beberapa langkah.
      
      1. Tambahkan <a href='https://releases.groupdocs.com/viewer/java/'>GroupDocs.Viewer untuk Java</a> sebagai dependensi pada proyek Anda. 
      2. Buat instance kelas Viewer dan muat file DWFX dengan path lengkap.  
      3. Tetapkan opsi untuk merender file DWFX ke dalam format HTML, PNG, JPEG, atau PDF. 
      4. Render file dan periksa output di direktori saat ini. 
   
    code:
      platform: "java"
      copy_title: "Menyalin"
      install:
        command: |
          <dependencies>
            <dependency>
              <groupId>com.groupdocs</groupId>
              <artifactId>groupdocs-viewer</artifactId>
              <version>{0}</version>
            </dependency>
          </dependencies>

          <repositories>
            <repository>
              <id>repository.groupdocs.com</id>
              <name>GroupDocs Repository</name>
              <url>https://repository.groupdocs.com/repo/</url>
            </repository>
          </repositories>
        copy_tip: "klik untuk menyalin"
        copy_done: "disalin"
      links:
        #  loop
        - title: "Lebih banyak contoh"
          link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Java"
        #  loop
        - title: "Dokumentasi"
          link: "https://docs.groupdocs.com/viewer/java/"
          
      content: |
        ```java {style=abap}

        // Siapkan file masukan DWFX
        String filePath = "input.dwfx";

        // Buat instance GroupDocs.Viewer
        try (Viewer viewer = new Viewer(filePath))
        {
            // Tetapkan opsi tampilan
            HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                
            // Render file DWFX ke HTML dengan sumber daya yang disematkan
            viewer.view(viewOptions);
        }

        ```
            

############################# Actions ############################

actions:
  enable: true
  title: "Siap untuk memulai?"
  description: "Coba fitur GroupDocs.Viewer secara gratis atau minta lisensi"
  items:
    #  loop
    - title: "Unduhan Maven"
      link: "https://releases.groupdocs.com/viewer/java/"
      color: "red"
        #  loop
    - title: "Perizinan"
      link: "https://purchase.groupdocs.com/pricing/viewer/java/"
      color: "light"



############################# More Formats #####################
more_formats:
    enable: true
    title: "Render format file lain menggunakan Java"
    exclude: "DWFX"
    description: "Dokumen multi-format dan API penampil gambar untuk Java. Lihat beberapa format file populer di bawah ini tanpa pemirsa eksternal."
    items: 
        # format loop 1
        - name: "Render DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Open XML Document" 

        # format loop 2
        - name: "Render CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "CorelDRAW File" 

        # format loop 3
        - name: "Render PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint Open XML Presentation" 

        # format loop 4
        - name: "Render XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet" 

        # format loop 5
        - name: "Render DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "AutoCAD Drawing"

        # format loop 6
        - name: "Render XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "XML File"

        # format loop 7
        - name: "Render PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Adobe Photoshop Document"

        # format loop 8
        - name: "Render AI"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Adobe Illustrator Artwork"

        # format loop 9
        - name: "Render DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Microsoft Word Document" 

        # format loop 10
        - name: "Render TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Plain Text File" 

        # format loop 11
        - name: "Render DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Drawing Exchange Format File"  
          
        # format loop 12
        - name: "Render VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "vCard File"  
              
        # format loop 13
        - name: "Render SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Scalable Vector Graphic" 
          
        # format loop 14
        - name: "Render HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "Render PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Portable Document Format File"
          
        # format loop 16
        - name: "Render JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "JPEG Image"
          
        # format loop 17
        - name: "Render PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Portable Network Graphic" 
          
        # format loop 18
        - name: "Render EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "E-Mail Message" 
          
        # format loop 19
        - name: "Render RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Rich Text Format File" 
          
        # format loop 20
        - name: "Render ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "OpenDocument Text Document" 
          
        # format loop 21
        - name: "Render CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Comma-Separated Values File" 


---
