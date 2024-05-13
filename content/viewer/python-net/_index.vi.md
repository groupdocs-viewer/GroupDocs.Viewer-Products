---
############################# Static ############################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: vi
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
head_title: "Python API để xem tài liệu (PDF, Word, Excel, HTML, hình ảnh và email)"
head_description: "Python API để hiển thị và xem tài liệu. Thêm trình xem PDF, trình xem Word, trình xem Excel, trình xem hình ảnh, trình xem HTML và trình xem email vào các ứng dụng Python của bạn."

############################# Header ############################
title: "Python API mạnh mẽ để hiển thị tài liệu được tối ưu hóa"
description: "Hiển thị và xem hơn 180 định dạng tài liệu (PDF, HTML, hình ảnh) với các API mạnh mẽ và tùy chọn cấu hình linh hoạt để phát triển ứng dụng Python."
words:
  for: "for"

actions:
  main: "Tải xuống miễn phí từ PyPI"
  main_link: "https://pypi.org/project/groupdocs-viewer/"
  alt: "Cấp phép"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/python-net"
  title: "Sẵn sàng để bắt đầu?"
  description: "Dùng thử miễn phí các tính năng của GroupDocs.Viewer hoặc yêu cầu giấy phép"

release:
  title: "Đã phát hành phiên bản {0}"
  notes: "Xem có gì mới"
  downloads: "Tải xuống"
  link: "https://releases.groupdocs.com/viewer/python-net/release-notes/latest/"

code:
  title: "Hiển thị tệp PDF trong Python"
  more: "Thêm ví dụ"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Python-via-.NET"
  install: "pip install GroupDocs.Viewer"
  content: |
    ```python {style=abap}
    import groupdocs.viewer as gv
    import groupdocs.viewer.options as gvo
    hvo = gvo.HtmlViewOptions  
  
    // Cài đặt các tùy chọn đầu ra HTML (một tệp cho mỗi trang)
    with gv.Viewer("resume.docx") as viewer:
      // Tạo một phiên bản của trình xem
      opts = hvo.for_embedded_resources("page_{0}.html")

      // Hiển thị PDF sang HTML với các tài nguyên được nhúng
      viewer.view(opts)
    ```
############################# Overview ############################
overview:
  enable: true
  title: "Tổng quan về GroupDocs.Viewer"
  description: "API để hiển thị, xem và chuyển đổi tài liệu, slide, biểu đồ và nhiều loại tài liệu khác trong các ứng dụng Python"
  features:
    # feature loop
    - title: "Hiển thị tài liệu hiệu quả và đáng tin cậy"
      content: "Với GroupDocs.Viewer API, bạn có thể hiển thị hiệu quả các tài liệu của bất kỳ định dạng được hỗ trợ nào sang HTML, JPEG, PNG và PDF với các tùy chọn linh hoạt và mạnh mẽ, duy trì tính toàn vẹn của nội dung và cấu trúc tài liệu. GroupDocs.Viewer cho Python hoạt động trên các nền tảng Windows và Linux."

    # feature loop
    - title: "Hỗ trợ hầu hết các định dạng tệp và tài liệu phổ biến"
      content: "Chúng tôi hỗ trợ hiển thị hơn 180 định dạng tệp và tài liệu phổ biến nhất, bao gồm Word, Excel, PDF, PowerPoint, họ định dạng OpenDocument, αρχεία (archive), hình ảnh raster và vector, sách điện tử, ngôn ngữ lập trình và đánh dấu và nhiều loại tệp khác, bao gồm các tệp được mã hóa với bảo vệ bằng mật khẩu."

    # feature loop
    - title: "Đầu ra có thể tùy chỉnh"
      content: "GroupDocs.Viewer không chỉ cho phép bạn hiển thị tài liệu mà còn cho phép bạn kiểm soát chính xác những phần nào của tài liệu cần được hiển thị hoặc không, cách chúng cần được hiển thị và áp dụng các chuyển đổi khác nhau cho đầu ra được hiển thị."

############################# Platforms ############################
platforms:
  enable: true
  title: "Không phụ thuộc nền tảng"
  description: "GroupDocs.Viewer cho Python hỗ trợ các hệ điều hành, framework và trình quản lý gói sau"
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
    - title: "PyPI"
      image: "pypi"

############################# File formats ############################
formats:
  enable: true
  title: "Các định dạng tập tin được hỗ trợ"
  description: |
    GroupDocs.Viewer cho Python (qua .NET) hỗ trợ các thao tác với các định dạng tệp sau: [định dạng tệp được hỗ trợ](https://docs.groupdocs.com/viewer/python-net/supported-document-formats/).
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office, OpenDocument và các định dạng văn bản
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
        ### Hình ảnh, Đồ họa & Sơ đồ
        * **Hình ảnh raster:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
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
        ### Khác        
        * **Web:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **Lưu trữ:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **Khác:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "Tính năng của GroupDocs.Viewer"
  description: "Hiển thị, hiển thị và chuyển đổi tài liệu PDF và Office một cách liền mạch"

  items:
    # feature loop
    - icon: "viewhtml"
      title: "Xem tài liệu bằng HTML"
      content: "Chuyển đổi bất kỳ loại tài liệu nào thành tài liệu HTML bằng CSS và SVG, có thể được hiển thị trong bất kỳ trình duyệt web hiện đại nào."

    # feature loop
    - icon: "rasterize"
      title: "Rasterize tài liệu"
      content: "Rasterize bất kỳ định dạng tài liệu nào có thể hỗ trợ thành hình ảnh raster, với định dạng hình ảnh có thể điều chỉnh và chất lượng nén."

    # feature loop
    - icon: "sourcecode"
      title: "Hiển thị và đánh dấu mã lập trình"
      content: "Hỗ trợ tất cả các ngôn ngữ lập trình, viết kịch bản và đánh dấu phổ biến, với khả năng phân tích cú pháp và làm nổi bật cú pháp của chúng."

    # feature loop
    - icon: "convertpdf"
      title: "Chuyển đổi sang PDF"
      content: "Tài liệu ở bất kỳ định dạng hỗ trợ nào đều có thể dễ dàng chuyển đổi và lưu thành PDF với các tùy chọn có thể điều chỉnh."

    # feature loop
    - icon: "transform"
      title: "Áp dụng các phép biến đổi"
      content: "Tài liệu đầu ra có thể được chuyển đổi trong quá trình hiển thị - các trang có thể được xoay và/hoặc sắp xếp lại và hình mờ văn bản có thể được đặt trên chúng."

    # feature loop
    - icon: "adjustment"
      title: "Điều chỉnh đầu ra HTML"
      content: "Các tài liệu HTML đầu ra do GroupDocs.Viewer tạo ra có thể được điều chỉnh rất tinh vi: nó được phép lưu vào luồng hoặc tệp, với các tài nguyên bên ngoài hoặc được nhúng, lệnh gọi lại, v.v."

    # feature loop
    - icon: "complex"
      title: "Hỗ trợ cấu trúc tài liệu phức tạp"
      content: "GroupDocs.Viewer không chỉ hỗ trợ các tài liệu đơn lẻ mà còn hỗ trợ các tệp chứa danh sách hoặc cấu trúc phân cấp của tài liệu, như email có tệp đính kèm, kho lưu trữ ZIP với các tệp nội bộ trong thư mục, hình ảnh TIFF nhiều trang, v.v."

    # feature loop
    - icon: "optimization"
      title: "Tùy chọn tối ưu hóa"
      content: "GroupDocs.Viewer chứa một hệ thống con bộ nhớ đệm có thể điều chỉnh, hệ thống này có thể rút ngắn thời gian tải bằng cách sử dụng các phiên bản tài liệu được lưu trong bộ nhớ đệm. Ngoài ra, một tập hợp các tùy chọn khác nhau cho các định dạng khác nhau cho phép loại trừ một số phần hoặc khía cạnh không cần thiết của tài liệu khỏi quá trình hiển thị (phông chữ, bảng tính ẩn, tệp đính kèm email) để tối ưu hóa hiệu suất tổng thể"

    # feature loop
    - icon: "passwordprotected"
      title: "Hỗ trợ các tài liệu được bảo vệ bằng mật khẩu"
      content: "GroupDocs.Viewer cho phép mở các tài liệu được mã hóa thuộc nhiều loại khác nhau: PDF, WordProcessing, Bảng tính, Bản trình bày và các loại khác bằng cách chỉ định mật khẩu trong các tùy chọn tải."

############################# Code samples ############################
code_samples:
  enable: true
  title: "Ví dụ mã"
  description: "Một số trường hợp sử dụng典型 (đặc trưng - diction) của các hoạt động GroupDocs.Viewer cho Python thông qua .NET"
  items:
    # code sample loop
    - title: "Chuyển đổi DOCX sang HTML"
      content: |
        Các thuộc tính của lớp `HtmlViewOptions` cho phép bạn kiểm soát quá trình chuyển đổi. Để biết thêm thông tin, vui lòng xem [ở đây](https://docs.groupdocs.com/viewer/python-net/rendering-to-html/). Ví dụ: bạn có thể nhúng tất cả các tài nguyên bên ngoài vào tệp HTML đầu ra, nén tệp đầu ra và tối ưu hóa nó để in.
        {{< landing/code title="Python">}}
        ```python {style=abap}
        import groupdocs.viewer as gv
        import groupdocs.viewer.options as gvo 

        // Tạo một phiên bản của trình xem (already translated)
        with gv.Viewer("resume.docx") as viewer:
          // Cài đặt các tùy chọn đầu ra HTML (một tệp cho mỗi trang) (already translated)
          viewOptions = gvo.HtmlViewOptions.for_embedded_resources("page_{0}.html")
          // Hiển thị PDF sang HTML với các tài nguyên được nhúng (already translated)
          viewer.view(viewOptions)
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Xuất PPTX sang PDF"
      content: |
        Tạo một phiên bản của lớp `PdfViewOptions` và truyền nó cho phương thức `Viewer.view` để chuyển đổi tệp PowerPoint PPTX sang PDF. Các thuộc tính của lớp `PdfViewOptions` cho phép bạn kiểm soát quá trình chuyển đổi. Ví dụ: bạn có thể bảo vệ tệp PDF đầu ra, sắp xếp lại các trang của nó và chỉ định chất lượng hình ảnh của tài liệu. Để biết thêm thông tin, vui lòng xem [phần tiếp theo của tài liệu](https://docs.groupdocs.com/viewer/python-net/rendering-to-pdf/).
        {{< landing/code title="Python">}}
        ```python {style=abap}
        import groupdocs.viewer as gv
        import groupdocs.viewer.options as gvo  

        // Tạo một phiên bản của trình xem (already translated)
        with gv.Viewer("presentation.pptx") as viewer:
          // Cài đặt các tùy chọn đầu ra PDF (Set output PDF options)
          viewOptions = gvo.PdfViewOptions("presentation.pdf")
          // Xuất PPTX sang PDF (Export PPTX to PDF) (already translated)
          viewer.view(viewOptions)
        ```
        {{< /landing/code >}}
############################# Reviews ############################
# reviews:
# enable: true
# title: "Đánh giá sản phẩm GroupDocs"
# description: "Đừng chỉ tin lời chúng tôi. Xem những nhà phát triển khác nói gì về API của chúng tôi"

# items:
#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "Dịch vụ tuyệt vời và sản phẩm tuyệt vời. Chúng cực kỳ hữu ích và phản hồi nhanh trong quá trình triển khai GroupDocs.Viewer cho .NET, không thể giới thiệu chúng đủ cao."
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "Sau khi triển khai và sử dụng GroupDocs.Viewer cho .NET trong dự án, có vẻ như nó hoạt động rất tốt. Tôi đã thử nghiệm với rất nhiều tài liệu và cho đến nay vẫn tốt. Mọi thứ tôi đưa vào nó đều hiển thị độc đáo và trông đẹp như trong trình xem PDF hoặc MS Word."
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---
