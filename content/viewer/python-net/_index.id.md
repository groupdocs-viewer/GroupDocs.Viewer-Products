---
############################# Static ############################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: id
product: "Viewer"
product_tag: "viewer"
platform: "Python via .NET"
platform_tag: "python-net"

############################# Drop-down ############################
supported_platforms:
  items:
    # supported_platforms loop
    - title: ".NET"
      tag: "net"
    # supported_platforms loop
    - title: "Java"
      tag: "java"
    # supported_platforms loop
    - title: "Node.js"
      tag: "nodejs-java" 
    # supported_platforms loop
    - title: "Python"
      tag: "python-net" 


############################# Head ############################
head_title: "API Penampil Dokumen Python untuk PDF, Word, Excel, HTML, Gambar & Email"
head_description: "API rendering file dan penampil dokumen Python. Tambahkan penampil PDF, penampil Word, penampil Excel, penampil Gambar, penampil HTML, dan penampil Email ke aplikasi Python."

############################# Header ############################
title: "API Python yang Kuat untuk Rendering Dokumen yang Dioptimalkan"
description: "Render dan tampilkan lebih dari 180 format dokumen (PDF, HTML, Gambar) dengan API yang kuat dan opsi konfigurasi yang serbaguna untuk mengembangkan aplikasi Python."
words:
  for: "for"

actions:
  main: "Unduh Gratis dari PyPI"
  main_link: "https://pypi.org/project/groupdocs-viewer/"
  alt: "Perizinan"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/python-net"
  title: "Siap untuk memulai?"
  description: "Coba fitur GroupDocs.Viewer secara gratis atau minta lisensi"

release:
  title: "Versi {0} dirilis"
  notes: "Lihat apa yang baru"
  downloads: "Unduhan"
  link: "https://releases.groupdocs.com/viewer/python-net/release-notes/latest/"

code:
  title: "Rendering File PDF di Python"
  more: "Lebih banyak contoh"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Python-via-.NET"
  install: "pip install GroupDocs.Viewer"
  content: |
    ```python {style=abap}
    import groupdocs.viewer as gv
    import groupdocs.viewer.options as gvo
    hvo = gvo.HtmlViewOptions  
  
    // Atur opsi HTML keluaran, satu file per halaman
    with gv.Viewer("resume.docx") as viewer:
      // Buat Instance Penampil
      opts = hvo.for_embedded_resources("page_{0}.html")

      // Render PDF ke HTML dengan sumber daya yang tertanam
      viewer.view(opts)
    ```
############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Viewer Sekilas"
  description: "API untuk rendering, tampilan, dan konversi dokumen, slide, diagram, dan banyak jenis dokumen lainnya dalam aplikasi Python"
  features:
    # feature loop
    - title: "Lihat dokumen secara efisien dan andal"
      content: "Dengan GroupDocs.Viewer API, Anda dapat dengan efisien membuat rendering dokumen dari semua format yang didukung ke HTML, JPEG, PNG, dan PDF dengan opsi yang fleksibel dan kuat, sambil mempertahankan integritas konten dan struktur dokumen. GroupDocs.Viewer untuk Python berfungsi pada platform Windows dan Linux."

    # feature loop
    - title: "Mendukung sebagian besar format file dan dokumen umum"
      content: "Kami mendukung rendering lebih dari 180 format file dan dokumen yang paling populer, termasuk Word, Excel, PDF, PowerPoint, keluarga format OpenDocument, Arsip, Gambar Raster dan Vektor, eBook, bahasa pemrograman dan markup, dan banyak lagi jenis file lainnya, termasuk file terenkripsi dengan perlindungan kata sandi."

    # feature loop
    - title: "Keluaran yang Dapat Dikustomisasi"
      content: "GroupDocs.Viewer memungkinkan tidak hanya untuk membuat rendering dokumen, tetapi juga untuk mengontrol bagaimana tepatnya, bagian mana dari dokumen yang harus dirender atau tidak, bagaimana mereka harus dirender, dan menerapkan transformasi yang berbeda ke keluaran yang dirender."

############################# Platforms ############################
platforms:
  enable: true
  title: "Independensi Platform"
  description: "GroupDocs.Viewer untuk Python mendukung sistem operasi, framework, dan pengelola paket berikut"
  items:
    # platform loop
    - title: "Amazon"
      image: "amazon"
    # platform loop
    - title: "Docker"
      image: "docker"
    # platform loop
    - title: "Azure"
      image: "azure"
    # platform loop
    - title: "Eclipse"
      image: "eclipse"
    # platform loop
    - title: "IntelliJ"
      image: "intellij"
    # platform loop
    - title: "Windows"
      image: "windows"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "NPM"
      image: "npm"
    # platform loop
    - title: "PyPI"
      image: "pypi"

############################# File formats ############################
formats:
  enable: true
  title: "Format file yang didukung"
  description: |
    GroupDocs.Viewer untuk Python via .NET mendukung operasi dengan format file berikut: [format file yang didukung](https://docs.groupdocs.com/viewer/python-net/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office, OpenDocument dan format teks
        * **Word:** DOC, DOCX, DOCM, DOT, DOTX, DOTM, RTF, TXT
        * **Excel:** XLS, XLSX, XLSM, XLSB, XLTM, XLT, XLTM, XLTX
        * **PowerPoint:** PPT, PPTX, PPS, PPSX, PPSM, POT, POTM, POTX, PPTM        
        * **Project:** MPP, MPT, MPX
        * **Outlook:** MSG, EML, EMLX, PST, OST
        * **OneNote:** ONE
        * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG
        * **Fixed Page Layout:** PDF, TEX, XPS, OXPS
        * **e-Books:** EPUB, MOBI, DjVu
        * **Delimiter-Separated Values:** CSV, TSV
    # group loop
    - color: "blue"
      content: |
        ### Gambar, Grafik & Diagram
        * **Gambar raster:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
        * **Windows Icon:** ICO
        * **Scalable Vector Graphics:** SVG, CDR, CMX, IGS, SVGZ        
        * **Adobe Photoshop:** PSD, PSB        
        * **Stereo Lithography (3D Printing):** STL        
        * **Medical Imaging:** DICOM
        * **Plotter Documents:** PLT, HPG
        * **Autodesk Design Web Formats:** DWF, DWG
        * **AutoCAD Drawing:** DWT, IFC, STL, CF2        
      # group loop
    - color: "red"
      content: |
        ### Lainnya        
        * **jaring:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **Arsip:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **Lainnya:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "Fitur GroupDocs.Viewer"
  description: "Render, tampilkan, dan konversi PDF dan Dokumen Office dengan lancar"

  items:
    # feature loop
    - icon: "viewhtml"
      title: "Lihat dokumen dalam HTML"
      content: "Ubah dokumen jenis apa pun menjadi dokumen HTML dengan CSS dan SVG, yang dapat ditampilkan di browser web modern mana pun."

    # feature loop
    - icon: "rasterize"
      title: "Rasterisasi dokumen"
      content: "Rasterisasi format dokumen apa pun yang didukung ke gambar raster, dengan format gambar dan kualitas kompresi yang dapat disesuaikan."

    # feature loop
    - icon: "sourcecode"
      title: "Render dan sorot kode pemrograman"
      content: "Dukungan untuk semua bahasa pemrograman, skrip, dan markup populer, dengan kemampuan untuk mengurai dan menyorot sintaksisnya."

    # feature loop
    - icon: "convertpdf"
      title: "Konversikan ke PDF"
      content: "Dokumen format apa pun yang didukung dapat dengan mudah dikonversi dan disimpan ke PDF dengan opsi yang dapat disesuaikan."

    # feature loop
    - icon: "transform"
      title: "Terapkan transformasi"
      content: "Dokumen keluaran dapat diubah selama rendering - halaman dapat diputar dan/atau disusun ulang, dan tanda air teks dapat ditempatkan di atasnya."

    # feature loop
    - icon: "adjustment"
      title: "Penyesuaian keluaran HTML"
      content: "Dokumen HTML keluaran, yang dihasilkan oleh GroupDocs.Viewer, dapat disetel dengan sangat baik: diperbolehkan untuk menyimpan ke aliran atau file, dengan sumber daya eksternal atau tertanam, panggilan balik, dan sebagainya."

    # feature loop
    - icon: "complex"
      title: "Dukungan struktur dokumen yang kompleks"
      content: "GroupDocs.Viewer tidak hanya mendukung satu dokumen, tetapi juga file, yang secara internal berisi daftar atau struktur hierarki dokumen, seperti pesan email dengan lampiran, arsip ZIP dengan file internal di dalam folder, gambar TIFF multi-halaman, dan sebagainya."

    # feature loop
    - icon: "optimization"
      title: "Opsi pengoptimalan"
      content: "GroupDocs.Viewer berisi subsistem cache yang dapat disesuaikan, yang dapat mempercepat waktu pemuatan dengan menggunakan versi dokumen yang di-cache. Juga serangkaian opsi berbeda untuk format berbeda memungkinkan untuk mengecualikan beberapa bagian atau aspek dokumen yang tidak diperlukan dari rendering (font, lembar kerja tersembunyi, lampiran email) untuk mengoptimalkan kinerja keseluruhan"

    # feature loop
    - icon: "passwordprotected"
      title: "Dukungan dokumen yang dilindungi kata sandi"
      content: "GroupDocs.Viewer memungkinkan untuk membuka dokumen terenkripsi dari berbagai jenis: PDF, WordProcessing, Spreadsheet, Presentasi, dan lainnya, dengan menentukan kata sandi dalam opsi pemuatan."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Contoh kode"
  description: "Beberapa kasus penggunaan operasi GroupDocs.Viewer khas untuk Python via .NET"
  items:
    # code sample loop
    - title: "Render DOCX ke HTML"
      content: |
        Properti kelas `HtmlViewOptions` memungkinkan Anda untuk mengontrol proses konversi, lebih lanjut tentang itu [di sini](https://docs.groupdocs.com/viewer/python-net/rendering-to-html/). Misalnya, Anda dapat menyematkan semua sumber daya eksternal dalam file HTML keluaran, memperkecil file keluaran, dan mengoptimalkannya untuk pencetakan.
        {{< landing/code title="Python">}}
        ```python {style=abap}
        import groupdocs.viewer as gv
        import groupdocs.viewer.options as gvo 

        // Buat Instance Penampil
        with gv.Viewer("resume.docx") as viewer:
          // Atur opsi HTML keluaran, satu file per halaman
          viewOptions = gvo.HtmlViewOptions.for_embedded_resources("page_{0}.html")
          // Render PDF ke HTML dengan sumber daya yang tertanam
          viewer.view(viewOptions)
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Ekspor PPTX ke PDF"
      content: |
        Buat instance kelas `PdfViewOptions` dan berikan ke metode `Viewer.view` untuk mengonversi file PowerPoint PPTX ke PDF. Properti kelas `PdfViewOptions` memungkinkan Anda untuk mengontrol proses konversi. Misalnya, Anda dapat melindungi file PDF keluaran, menyusun ulang halamannya, dan menentukan kualitas gambar dokumen. Lihat [bagian dokumentasi berikut](https://docs.groupdocs.com/viewer/python-net/rendering-to-pdf/) untuk detailnya.
        {{< landing/code title="JavaScript">}}
        ```python {style=abap}
        import groupdocs.viewer as gv
        import groupdocs.viewer.options as gvo  

        // Buat Instance Penampil
        with gv.Viewer("presentation.pptx") as viewer:
          // Set output PDF options (Atur opsi PDF keluaran)
          viewOptions = gvo.PdfViewOptions("presentation.pdf")
          // Ekspor PPTX ke PDF (Export PPTX to PDF)
          viewer.view(viewOptions)
        ```
        {{< /landing/code >}}
############################# Reviews ############################
# reviews:
# enable: true
# title: "Ulasan produk GroupDocs"
# description: "Jangan hanya percaya kata-kata kami begitu saja. Lihat apa yang dikatakan pengembang lain tentang API kami"

# items:
#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "Pelayanan prima dan produk unggulan. Mereka sangat membantu dan responsif selama proses implementasi GroupDocs.Viewer untuk .NET, dan sangat merekomendasikannya."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "Setelah mengimplementasikan dan menggunakan GroupDocs.Viewer untuk .NET dalam proyek tersebut tampaknya berfungsi dengan baik. Saya telah menguji dengan banyak dokumen dan sejauh ini bagus. Semua yang saya berikan ditampilkan dengan baik dan terlihat sama bagusnya dengan penampil PDF atau MS Word."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---
