---
############################# Static ############################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: ms
product: "Viewer"
product_tag: "viewer"
platform: "Node.js via Java"
platform_tag: "nodejs-java"

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


############################# Head ############################
head_title: "Node.js Document Viewer API untuk PDF Word Excel Imej HTML & E-mel"
head_description: "API pemapar dokumen & fail Node.js. Tambah pemapar PDF, Pemapar Word, Pemapar Excel, Pemapar imej, Pemapar HTML, Pemapar e-mel dalam aplikasi JavaScript."

############################# Header ############################
title: "API Node.js untuk memaparkan & memaparkan Dokumen"
description: "Pustaka Document Viewer untuk membangunkan aplikasi JavaScript yang memaparkan, melihat dan memanipulasi dokumen berbilang format secara asli yang menyokong 180+ format fail."
words:
  for: "for"

actions:
  main: "Muat Turun NPM Percuma"
  main_link: "https://www.npmjs.com/package/@groupdocs/groupdocs.viewer"
  alt: "Pelesenan"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/nodejs-java"
  title: "Bersedia untuk bermula?"
  description: "Cuba ciri GroupDocs.Viewer secara percuma atau minta lesen"

release:
  title: "Versi {0} dikeluarkan"
  notes: "Lihat perkara baharu"
  downloads: "Muat turun"
  link: "https://releases.groupdocs.com/viewer/nodejs-java/release-notes/latest/"

code:
  title: "Render fail PDF dalam JavaScript"
  more: "Lebih banyak contoh"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Node.js-via-Java"
  install: "npm i @groupdocs/groupdocs.viewer"
  content: |
    ```javascript {style=abap}       
    // Tetapkan pilihan HTML output
    const viewOptions = HtmlViewOptions.forEmbeddedResources()
    
    // Pemapar Segera
    const viewer = new Viewer("resume.pdf")

    // Render PDF kepada HTML dengan sumber terbenam
    viewer.view(viewOptions)
    viewer.close()
    ```
############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Viewer sepintas lalu"
  description: "API untuk memaparkan, memaparkan, menukar dokumen, slaid, gambar rajah dan banyak jenis dokumen lain dalam aplikasi Node.js"
  features:
    # feature loop
    - title: "Lihat dokumen dengan cekap & boleh dipercayai"
      content: "Dengan API GroupDocs.Viewer anda boleh dengan cekap memaparkan dokumen daripada sebarang format yang boleh disokong kepada HTML, JPEG, PNG dan PDF dengan pilihan yang fleksibel dan berkuasa sambil mengekalkan integriti kandungan dan struktur dokumen. GroupDocs.Viewer untuk Node.js berfungsi pada platform Windows dan Linux."

    # feature loop
    - title: "Format fail dan dokumen yang paling popular disokong"
      content: "Kami menyokong pemaparan lebih daripada 180 format fail dan dokumen paling popular yang termasuk Word, Excel, PDF, PowerPoint, keluarga format OpenDocument, Arkib, imej Raster dan Vektor, e-Buku, bahasa pengaturcaraan dan penanda serta banyak jenis fail lain, termasuk yang disulitkan fail dengan perlindungan kata laluan."

    # feature loop
    - title: "Output boleh disesuaikan"
      content: "GroupDocs.Viewer membenarkan bukan sahaja untuk memaparkan dokumen, tetapi juga untuk mengawal bagaimana tepatnya, bahagian dokumen mana yang harus diberikan atau sekarang, cara ia harus diberikan, dan untuk menggunakan transformasi yang berbeza pada output yang diberikan."

############################# Platforms ############################
platforms:
  enable: true
  title: "Kemerdekaan platform"
  description: "GroupDocs.Viewer untuk Node.js menyokong sistem pengendalian, rangka kerja dan pengurus pakej berikut"
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

############################# File formats ############################
formats:
  enable: true
  title: "Format fail yang disokong"
  description: |
    GroupDocs.Viewer untuk Node.js melalui Java menyokong operasi dengan berikut [format fail](https://docs.groupdocs.com/viewer/nodejs-java/supported-document-formats/).
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
        ### Imej, Grafik & Gambar rajah
        * **Imej raster:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
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
        ### Lain-lain        
        * **Web:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **Arkib:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **Lain-lain:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "Ciri GroupDocs.Viewer"
  description: "Memaparkan, memaparkan dan menukar PDF dan Dokumen Pejabat dengan lancar"

  items:
    # feature loop
    - icon: "viewhtml"
      title: "Lihat dokumen dalam HTML"
      content: "Tukar dokumen apa-apa jenis kepada dokumen HTML dengan CSS dan SVG, yang boleh dipaparkan dalam mana-mana pelayar web moden."

    # feature loop
    - icon: "rasterize"
      title: "Rasterize dokumen"
      content: "Rasterkan sebarang format dokumen yang boleh disokong kepada imej raster, dengan format imej boleh laras dan kualiti mampatan."

    # feature loop
    - icon: "sourcecode"
      title: "Membuat dan menyerlahkan kod pengaturcaraan"
      content: "Sokongan semua bahasa pengaturcaraan, skrip dan markup yang popular, dengan keupayaan untuk menghuraikan dan menyerlahkan sintaksnya."

    # feature loop
    - icon: "convertpdf"
      title: "Tukar kepada PDF"
      content: "Dokumen bagi sebarang format yang boleh disokong boleh ditukar dan disimpan dengan mudah ke PDF dengan pilihan boleh laras."

    # feature loop
    - icon: "transform"
      title: "Terapkan transformasi"
      content: "Dokumen output boleh diubah semasa pemaparan - halaman boleh diputar dan/atau disusun semula, dan tera air teks boleh diletakkan di atasnya."

    # feature loop
    - icon: "adjustment"
      title: "Pelarasan output HTML"
      content: "Dokumen HTML output, yang dijana oleh GroupDocs.Viewer, boleh ditala dengan sangat halus: ia dibenarkan untuk disimpan ke strim atau fail, dengan sumber luaran atau terbenam, panggilan balik dan sebagainya."

    # feature loop
    - icon: "complex"
      title: "Sokongan struktur dokumen yang kompleks"
      content: "GroupDocs.Viewer menyokong bukan sahaja dokumen tunggal, tetapi juga fail, yang secara dalaman mengandungi senarai atau struktur hierarki dokumen, seperti mesej e-mel dengan lampiran, arkib ZIP dengan fail dalaman dalam folder, imej TIFF berbilang halaman dan sebagainya."

    # feature loop
    - icon: "optimization"
      title: "Pilihan pengoptimuman"
      content: "GroupDocs.Viewer mengandungi subsistem cache boleh laras, yang boleh mempercepatkan masa pemuatan dengan menggunakan versi cache dokumen. Juga satu set pilihan berbeza untuk format yang berbeza membolehkan untuk mengecualikan beberapa bahagian atau aspek dokumen yang tidak perlu daripada pemaparan (fon, lembaran kerja tersembunyi, lampiran e-mel) untuk mengoptimumkan prestasi keseluruhan"

    # feature loop
    - icon: "passwordprotected"
      title: "Sokongan dokumen yang dilindungi kata laluan"
      content: "GroupDocs.Viewer membenarkan untuk membuka dokumen yang disulitkan dari pelbagai jenis: PDF, Pemprosesan Kata, Hamparan, Persembahan dan lain-lain, dengan menyatakan kata laluan dalam pilihan pemuatan."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Sampel kod"
  description: "Sesetengah kes menggunakan GroupDocs.Viewer biasa untuk Node.js melalui operasi Java"
  items:
    # code sample loop
    - title: "Render DOCX kepada HTML"
      content: |
        Sifat kelas `HtmlViewOptions` membolehkan anda mengawal proses penukaran, lebih lanjut mengenainya [di sini](https://docs.groupdocs.com/viewer/nodejs-java/rendering-to-html/). Sebagai contoh, anda boleh membenamkan semua sumber luaran dalam fail HTML output, mengecilkan fail output dan mengoptimumkannya untuk pencetakan.
        {{< landing/code title="JavaScript">}}
        ```javascript {style=abap}
        import { Viewer, HtmlViewOptions } from '@groupdocs/groupdocs.viewer'

        // Tetapkan pilihan HTML output
        const viewOptions = HtmlViewOptions.forEmbeddedResources()

        // Pemapar Segera
        const viewer = new Viewer("resume.docx")

        // Render DOCX kepada HTML dengan sumber terbenam
        viewer.view(viewOptions)
        viewer.close()
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Eksport PPTX ke PDF"
      content: |
        Cipta contoh kelas `PdfViewOptions` dan serahkannya kepada kaedah `Viewer.view` untuk menukar fail PowerPoint PPTX kepada PDF. Sifat kelas `PdfViewOptions` membolehkan anda mengawal proses penukaran. Sebagai contoh, anda boleh melindungi fail PDF output, menyusun semula halamannya dan menentukan kualiti imej dokumen. Rujuk [bahagian dokumentasi berikut](https://docs.groupdocs.com/viewer/nodejs-java/rendering-to-pdf/) untuk butiran.
        {{< landing/code title="JavaScript">}}
        ```javascript {style=abap}   
        import { Viewer, PdfViewOptions } from '@groupdocs/groupdocs.viewer'

        // Tetapkan pilihan PDF output
        const viewOptions = new PdfViewOptions("presentation.pdf")

        // Pemapar Segera
        const viewer = new Viewer("presentation.pptx")

        // Eksport PPTX ke PDF
        viewer.view(viewOptions)
        viewer.close()
        ```
        {{< /landing/code >}}
############################# Reviews ############################
# reviews:
# enable: true
# title: "Ulasan produk GroupDocs"
# description: "Jangan hanya mengambil kata-kata kami untuk itu. Lihat apa yang pemaju lain katakan tentang API kami"

# items:
#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "Perkhidmatan yang sangat baik dan produk yang sangat baik. Mereka sangat membantu dan responsif semasa proses pelaksanaan GroupDocs.Viewer untuk .NET, tidak dapat mengesyorkannya dengan sangat tinggi."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "Selepas melaksanakan dan menggunakan GroupDocs.Viewer untuk .NET dalam projek, ia kelihatan berfungsi dengan baik. Saya telah menguji dengan banyak dokumen dan setakat ini baik. Semua yang saya lemparkan padanya dipaparkan dengan baik dan kelihatan sama baiknya seperti dalam pemapar PDF atau MS Word."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---
