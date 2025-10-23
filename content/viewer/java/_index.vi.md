---
############################# Static ############################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

product: "Viewer"
product_tag: "viewer"
platform: "Java"
platform_tag: "java"

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
head_title: "API trình xem tài liệu Java, hiển thị Sơ đồ HTML hình ảnh PDF Word Excel"
head_description: "Thư viện Trình xem Tài liệu để phát triển các ứng dụng Java có khả năng hiển thị, xem và thao tác nguyên bản, các tài liệu đa định dạng hỗ trợ hơn 180 định dạng tệp."

############################# Header ############################
title: "Kết xuất và hiển thị tài liệu<br>sử dụng API Java"
description: "API trình xem mạnh mẽ để hiển thị hơn 180 định dạng tài liệu thành PDF, HTML và Hình ảnh với các tùy chọn cấu hình linh hoạt."
words:
  for: "for"

actions:
  viewer_demo: true
  viewer_demo_file_name: "quarterly-report.docx"
  main: "Tải xuống Maven miễn phí"
  main_link: "https://releases.groupdocs.com/java/repo/com/groupdocs/groupdocs-viewer/"
  alt: "Cấp phép"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/java"
  title: "Sẵn sàng để bắt đầu?"
  description: "Dùng thử miễn phí các tính năng của GroupDocs.Viewer hoặc yêu cầu giấy phép"

release:
  title: "Đã phát hành phiên bản {0}"
  notes: "Xem có gì mới"
  downloads: "Tải xuống"
  link: "https://releases.groupdocs.com/viewer/java/release-notes/latest/"

code:
  title: "Hiển thị tệp PDF trong Java"
  more: "Thêm ví dụ"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Java"
  install: |
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
  content: |
    ```java {style=abap}
    // Trình xem tức thời 
    try (Viewer viewer = new Viewer("resume.pdf"))
    {
        // Đặt tùy chọn HTML đầu ra, một tệp trên mỗi trang  
        HtmlViewOptions viewOptions = 
        HtmlViewOptions.forEmbeddedResources();

        // Kết xuất PDF sang HTML
        viewer.view(viewOptions);
    }
    ```
############################# Overview ############################
overview:
  enable: true
  title: "Tổng quan về GroupDocs.Viewer"
  description: "API để kết xuất, hiển thị, chuyển đổi tài liệu, trang trình bày, sơ đồ và nhiều loại tài liệu khác trong ứng dụng Java"
  features:
    # feature loop
    - title: "Xem tài liệu hiệu quả và đáng tin cậy"
      content: "Với API GroupDocs.Viewer, bạn có thể hiển thị hiệu quả các tài liệu thuộc mọi định dạng có thể hỗ trợ sang HTML, JPEG, PNG và PDF với các tùy chọn linh hoạt và mạnh mẽ trong khi vẫn duy trì tính toàn vẹn của nội dung và cấu trúc tài liệu. GroupDocs.Viewer hoạt động trên nền tảng Windows và Linux."

    # feature loop
    - title: "Hỗ trợ hầu hết các định dạng tệp và tài liệu phổ biến"
      content: "Chúng tôi hỗ trợ hiển thị trên 180 định dạng tài liệu và tệp phổ biến nhất bao gồm Word, Excel, PDF, PowerPoint, nhóm định dạng OpenDocument, Lưu trữ, hình ảnh Raster và Vector, Sách điện tử, ngôn ngữ lập trình và đánh dấu cũng như nhiều loại tệp khác, bao gồm cả mã hóa tập tin có mật khẩu bảo vệ."

    # feature loop
    - title: "Đầu ra có thể tùy chỉnh"
      content: "GroupDocs.Viewer không chỉ cho phép hiển thị tài liệu mà còn kiểm soát cách hiển thị chính xác, phần nào của tài liệu sẽ được hiển thị hoặc bây giờ, cách hiển thị chúng và áp dụng các phép biến đổi khác nhau cho đầu ra được hiển thị."

    # feature loop
    - title: "Giao diện người dùng web cho khung Spring"
      content: "Chúng tôi cung cấp gói giao diện người dùng nguồn mở cho khung Spring có thể được thêm vào dự án của bạn sau vài phút. Gói Viewer.UI chứa giao diện người dùng web dựa trên Angular và cung cấp một bộ API hữu ích và nhà cung cấp lưu trữ dữ liệu."

############################# Platforms ############################
platforms:
  enable: true
  title: "Nền tảng độc lập"
  description: "GroupDocs.Viewer cho Java hỗ trợ các hệ điều hành, khung và trình quản lý gói sau"
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
    - title: "Maven"
      image: "maven"


############################# File formats ############################
formats:
  enable: true
  title: "Các định dạng tập tin được hỗ trợ"
  description: |
    GroupDocs.Viewer dành cho Java hỗ trợ các thao tác với sau [định dạng tệp](https://docs.groupdocs.com/viewer/java/supported-document-formats/).
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
  title: "Mẫu mã"
  description: "Một số trường hợp sử dụng GroupDocs.Viewer điển hình cho các hoạt động Java"
  items:
    # code sample loop
    - title: "Kết xuất DOCX sang HTML"
      content: |
        Thuộc tính lớp [HtmlViewOptions](https://reference.groupdocs.com/viewer/java/com.groupdocs.viewer.options/htmlviewoptions/) cho phép bạn kiểm soát quá trình chuyển đổi, tìm hiểu thêm về điều đó [tại đây](https://docs.groupdocs.com/viewer/java/rendering-to-html/). Ví dụ: bạn có thể nhúng tất cả tài nguyên bên ngoài vào tệp HTML đầu ra, thu nhỏ tệp đầu ra và tối ưu hóa tệp để in.
        {{< landing/code title="Java">}}
        ```java {style=abap}
        import com.groupdocs.viewer.Viewer;
        import com.groupdocs.viewer.options.HtmlViewOptions;

        // Trình xem tức thời
        try (Viewer viewer = new Viewer("resume.docx"))
        {
            // Đặt tùy chọn HTML đầu ra
            HtmlViewOptions options = 
            HtmlViewOptions.forEmbeddedResources();

            // Kết xuất DOCX sang HTML bằng tài nguyên được nhúng
            viewer.view(options);
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "Xuất PPTX sang PDF"
      content: |
        Tạo một phiên bản lớp [PdfViewOptions](https://reference.groupdocs.com/viewer/java/com.groupdocs.viewer.options/pdfviewoptions/) và chuyển nó tới [Viewer.View](https://reference.groupdocs.com/viewer/java/com.groupdocs.viewer/viewer/#view-com.groupdocs.viewer.options.ViewOptions-) để chuyển đổi tệp PowerPoint PPTX sang PDF. Thuộc tính lớp PdfViewOptions cho phép bạn kiểm soát quá trình chuyển đổi. Ví dụ: bạn có thể bảo vệ tệp PDF đầu ra, sắp xếp lại các trang của nó và chỉ định chất lượng của hình ảnh tài liệu. Hãy tham khảo [phần tài liệu sau](https://docs.groupdocs.com/viewer/java/rendering-to-pdf/) để biết chi tiết.
        {{< landing/code title="Java">}}
        ```java {style=abap}   
        import com.groupdocs.viewer.Viewer;
        import com.groupdocs.viewer.options.PdfViewOptions;

        // Trình xem tức thời
        try (Viewer viewer = new Viewer("presentation.pptx"))
        {            
            // Đặt tùy chọn PDF đầu ra
            PdfViewOptions viewOptions = new PdfViewOptions();

            // Xuất PPTX sang PDF
            viewer.view(viewOptions);
        }
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