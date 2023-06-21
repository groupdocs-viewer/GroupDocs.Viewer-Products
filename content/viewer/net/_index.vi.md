---
############################# Static ##########################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

lang: vi
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head ############################
head_title: ".NET Document Viewer API, Render PDF Word Excel Image HTML Diagram"
head_description: "API hiển thị và xem tệp C# ASP.NET. Thêm các tính năng xem PDF, xem Word, xem Excel, xem ảnh, xem HTML, xem email trong các ứng dụng .NET."

############################# Header ##########################
title: "Kết xuất & hiển thị tài liệu qua .NET API"
description: "API trình xem tài liệu .NET để kết xuất hơn 190 định dạng tài liệu thành PDF, HTML và hình ảnh với các tùy chọn cấu hình mạnh mẽ."
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Download Free Trial"
    link: "https://downloads.groupdocs.com/viewer/net"

############################# SubMenu #########################
submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Viewer for .NET"
        image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-viewer-net.png"
        product: "GroupDocs.Viewer"
        platform: ".NET"

    middle:
        button:
            # button loop
            - link: "#overview"
              text: "Tổng quan"

            # button loop
            - link: "#features"
              text: "Đặc trưng"

            # button loop
            - link: "#support"
              text: "Ủng hộ"

            # button loop
            - link: "https://products.groupdocs.app/viewer/total"
              text: "Bản thử trực tiếp"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "định giá"

    right:
        link_download: "https://releases.groupdocs.com/viewer/net/"
        link_learn: "https://docs.groupdocs.com/viewer/net/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    content: |
      API GroupDocs.Viewer cho .NET giúp bạn tạo các ứng dụng mạnh mẽ trong C#, ASP.NET và các công nghệ dựa trên .NET khác, có thể kết xuất và hiển thị tài liệu cũng như hình ảnh của hơn 190 định dạng tệp mà không cần cài đặt bất kỳ phần mềm bên ngoài nào. Thư viện trình xem tệp quét các tài liệu và sau đó chuyển đổi chúng thành SVG+HTML+CSS để tối ưu hóa trải nghiệm kết xuất tài liệu tổng thể để xem các tài liệu kinh doanh, hình ảnh, tệp văn bản, sơ đồ, đồ họa, tệp đính kèm email và tệp PDF với tốc độ, văn bản thực và độ trung thực cao bên trong các ứng dụng của bạn. Bạn có tùy chọn thêm các chức năng xem và đọc tài liệu trong các ứng dụng của mình để hiển thị toàn bộ tài liệu, một phần tài liệu, phạm vi trang/ô cụ thể, lớp tài liệu riêng lẻ, có hoặc không có chú thích và nhận xét cho các định dạng tệp được hỗ trợ.
       
      Theo mặc định, GroupDocs.Viewer dành cho .NET lưu trữ các tài liệu được kết xuất vào đĩa cục bộ trong bộ đệm ẩn. Bất kỳ loại bộ nhớ cache bên ngoài nào cũng được hỗ trợ bằng cách triển khai các giao diện thích hợp – Amazon S3, Dropbox, Google Drive, Windows Azure, Redis hoặc bất kỳ giao diện nào khác.
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          Sau đây là tổng quan về GroupDocs.Viewer cho .NET:
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Tổng quan"
          content: |
            * Hiển thị hơn 190 loại tài liệu 
            * Nhận tệp ở định dạng HTML, Hình ảnh, PDF 
            * Xoay & Sắp xếp lại 
            * Áp dụng hình mờ 
            * Bộ nhớ cache cho quá trình nhanh 
            * Thêm phông chữ tùy chỉnh 
            * Áp dụng tiêu chuẩn mã hóa 
            * Trình xử lý dữ liệu đầu vào tùy chỉnh 
            * Kết xuất với các thay đổi theo dõi 
            * Kết xuất dưới dạng HTML đáp ứng 
            * Kết xuất các lớp PDF & CAD 
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Viewer for .NET hỗ trợ xem tất cả các định dạng tệp tài liệu phổ biến. Chỉ với một vài dòng mã, hãy thêm trình xem PDF, Microsoft Office Word, bảng tính Excel, Hình ảnh, HTML, email Outlook, OneNote, Dự án và khả năng xem đồ họa trong các ứng dụng .NET của bạn.

        left:
          enable: true
          table:
            # table loop
            - title: "Microsoft Office"
              content: |
                * **Word:** DOC, DOCX, DOCM, DOT, DOTX, DOTM, RTF, TXT
                * **Excel:** XLS, XLSX, XLSM, XLSB, XLTM, XLT, XLTM, XLTX, XLAM, SXC, SpreadsheetML
                * **PowerPoint:** PPT, PPTX, PPS, PPSX, PPSM, POT, POTM, POTX, PPTM
                * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
                * **Project:** MPP, MPT, MPX
                * **Outlook:** MSG, EML, EMLX, PST, OST
                * **OneNote:** ONE

            # table loop
            - title: "Other Formats"
              content: |
                * **Tệp bố cục trang:** PDF, TEX, XPS, OXPS
                * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG, OTG, FODP, FODG
                * **Các giá trị được phân tách bằng dấu phân cách:** CSV, TSV
                * **mạng:** HTML, MHT, MHTML
                * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
                * **PostScript:** PS, EPS
                * **lưu trữ:** ZIP, TAR, BZ2, GZ, RAR, RAR5
                * **Nhiều:** OBJ, EPUB, MOBI, DjVu, XML, VCF, VCARD, NUMBERS, NSF

        right:
          enable: true
          table:
            # table loop
            - title: "Hình ảnh, Đồ họa & Biểu đồ"
              content: |
                * **Hình ảnh:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB
                * **biểu tượng cửa sổ:** ICO
                * **Đồ họa Vector có thể mở rộng:** SVG, CDR, CMX, IGS, SVGZ
                * **JPEG2000:** JP2, J2C, J2K, JPC, JPF, JPX, JPM
                * **AdobePhotoshop:** PSD, PSB
                * **Ngôn ngữ lệnh máy in:** PCL
                * **In thạch bản nổi (In 3D):** STL
                * **Các lớp nền tảng công nghiệp:** IFC
                * **hình ảnh y tế:** DICOM
                * **Tài liệu máy vẽ:** PLT, HPG
                * **Định dạng web thiết kế Autodesk:** DWF, DWG
                * **Vẽ AutoCAD:** DWT, IFC, STL, CF2
                * **DGN dựa trên ISFF (V7):** DGN

            # table loop
            - title: "Định dạng ngôn ngữ lập trình"
              content: |
                * **Tệp C/C++/C#:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
                * **Tệp Java/JavaScript:** JAVA, JS, JSON, PROPERTIES
                * **Nhiều:** VB, PHP, SQL, PL, PY, PV, RB, RST, SASS, SCALA, SCM, SCRIPT, AS, AS3, ASM, BAT, CMAKE, CSS, DIFF, ERB, GROOVY, HAML, LESS, LOG, M, MAKE, MD, ML, MM, SH, SML, VIM, YAML

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Viewer cho .NET hỗ trợ các Hệ điều hành, Khung & Trình quản lý gói sau:
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Các hệ điều hành"
              content: |
                * Microsoft Windows Server 2003 trở lên 
                * Microsoft Windows XP trở lên 
                * Windows 10 & 11 
                * Linux (Ubuntu, OpenSUSE, CentOS và những thứ khác) 
                * hệ điều hành Mac 

            # table loop
            - icon: "fas fa-code"
              title: "Khung được hỗ trợ"
              content: |
                * .NET Framework 2.0 trở lên 
                * .NET Lõi 3.1 
                * .NET 5 trở lên 

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-box"
              title: "Trình quản lý gói"
              content: |
                * NuGet

            # table loop
            - icon: "fas fa-tools"
              title: "Môi trường phát triển"
              content: |
                * Microsoft Visual Studio
                * Visual Studio Code
                * .NET CLI

############################# Features ############################
features:
    enable: true
    title: "GroupDocs.Viewer cho các tính năng .NET"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "Rasterize Tài liệu và Chuyển đổi chúng thành SVG, HTML & CSS"

      # feature loop
      - icon: "fas fa-eye"
        content: "Chuyển đổi Văn bản sang HTML và Kết xuất Tài liệu để có được Biểu diễn HTML, Hình ảnh hoặc PDF"

      # feature loop
      - icon: "fas fa-bolt"
        content: "Thời gian tải nhanh hơn bằng cách sử dụng các phiên bản tài liệu được lưu trong bộ nhớ cache"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "Chuyển đổi bản trình bày có hình dạng và văn bản với hiệu ứng 3D"

      # feature loop
      - icon: "fas fa-code"
        content: "Mã hóa tài liệu Word, Excel và Email theo tiêu chuẩn mã hóa mong muốn"

      # feature loop
      - icon: "fas fa-cloud"
        content: "Kết xuất tài liệu tại FTP hoặc Vị trí lưu trữ đám mây"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "Loại trừ Phông chữ khi Kết xuất sang HTML để giảm Kích thước Tệp Kết quả"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "Giảm thiểu đầu ra CSS & HTML bằng cách xóa nhận xét, khoảng trắng bổ sung, v.v."

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "Đọc văn bản có trong tài liệu nguồn thông qua tọa độ của nó"

      # feature loop
      - icon: "fas fa-border-all"
        content: "Hiển thị/Ẩn Đường lưới của Trang tính Excel trong Biểu diễn Kết xuất"

      # feature loop
      - icon: "fas fa-wrench"
        content: "Chỉ định Số hàng trong một trang tính Excel sẽ được hiển thị trên mỗi Trang"

      # feature loop
      - icon: "fas fa-columns"
        content: "Bỏ qua các cột trống trong khi hiển thị tài liệu bảng tính"

      # feature loop
      - icon: "fas fa-file-word"
        content: "Kết xuất Tài liệu Word thành Trang HTML, Hình ảnh hoặc PDF, với Theo dõi Thay đổi"

      # feature loop
      - icon: "fas fa-envelope"
        content: "Kết xuất tệp đính kèm email dưới dạng tệp gốc, hình ảnh hoặc dưới dạng biểu diễn HTML"

      # feature loop
      - icon: "fas fa-print"
        content: "Đặt giới hạn in trên tài liệu PDF"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "Kết xuất Nội dung/Tệp có trong Lưu trữ ZIP dưới dạng Tệp đính kèm"

      # feature loop
      - icon: "fas fa-lock"
        content: "Nhận tệp đính kèm từ tài liệu được bảo vệ bằng mật khẩu"

      # feature loop
      - icon: "fas fa-file-code"
        content: "Kết xuất định dạng tệp ngôn ngữ lập trình dưới dạng văn bản thuần túy"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "Điều chỉnh màu nền khi xem bản vẽ CAD"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "Xem tài liệu Excel và Chuyển đổi sang PDF, HTML, JPG & PNG"

      # feature loop
      - icon: "fas fa-heading"
        content: "Lấy tên bảng tính từ tệp Excel – Hiển thị tiêu đề cột bảng tính và số hàng"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "Xem & Chuyển đổi Tài liệu Dự án Microsoft bằng Ghi chú"

      # feature loop
      - icon: "fas fa-cube"
        content: "Chuyển đổi bản vẽ CAD sang SVG để có trải nghiệm xem và thu phóng tốt hơn"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "Chọn kết xuất các hình Visio không có lược đồ"

    more_feature:
      # more_feature_loop
      - title: "Xem tài liệu hiệu quả và đáng tin cậy"
        content: |
          Sử dụng GroupDocs.Viewer API, bạn có thể hiển thị hơn 190 định dạng tài liệu một cách hiệu quả và đáng tin cậy với nội dung và cấu trúc tài liệu nguyên vẹn. Mã mẫu sau đây cho thấy việc xem biểu diễn HTML của tài liệu DOCX dễ dàng như thế nào:

          ```cs
          // Instantiate viewer
          using (Viewer viewer = new Viewer("invoice.docx"))
          {
              // Set view options
              HtmlViewOptions options = HtmlViewOptions.ForEmbeddedResources();
              // Convert file to HTML with embedded resources
              viewer.View(options);
          }
          ```
      # more_feature_loop
      - title: "Áp dụng chuyển đổi cho đầu ra được kết xuất"
        content: "Bạn có thể thực hiện các chuyển đổi khác nhau đối với tài liệu đầu ra được hiển thị bằng cách sử dụng GroupDocs.Viewer cho .NET API. Các tùy chọn chuyển đổi này cung cấp cho bạn quyền kiểm soát cách bạn trình bày đầu ra được kết xuất để hiển thị. Các biến đổi có sẵn là tùy chọn xoay trang, tùy chọn sắp xếp lại trang và áp dụng hình mờ văn bản."

      # more_feature_loop
      - title: "Làm việc với tệp dữ liệu Outlook"
        content: "GroupDocs.Viewer cho .NET API có thể kết xuất các mục trong Tệp Dữ liệu Outlook (OST/PST) dưới dạng Tệp PDF, HTML và Hình ảnh. API Trình xem của chúng tôi cũng có khả năng lấy danh sách các thư mục có trong Tệp Dữ liệu Outlook. Sử dụng GroupDocs.Viewer cho .NET API, bạn có thể chỉ định thư mục sẽ hiển thị từ Tệp Dữ liệu Outlook. Tương tự như vậy, bạn cũng có thể lấy các email có định dạng OST/PST dưới dạng tệp đính kèm. GroupDocs.Viewer cho .NET cũng cho phép bạn lọc thư từ định dạng OST/PST dựa trên chủ đề, nội dung hoặc người gửi."

      # more_feature_loop
      - title: "Làm việc với tài liệu CAD"
        content: "GroupDocs.Viewer cho .NET API có thể hiển thị mô hình và tất cả các bố cục không trống hoặc hiển thị bố cục cụ thể của tệp CAD. GroupDocs.Viewer cho .NET API cũng hỗ trợ kết xuất theo ô hoặc kết xuất theo tọa độ của tài liệu CAD thành hình ảnh, HTML hoặc PDF. Bạn cũng có thể lấy trạng thái lớp cho tài liệu CAD."

############################# Testimonials ###############################
testimonials:
  enable: true

  testimonial:
    # testimonial item loop
    - name: "Margot Baill"
      designation: "Giám đốc phát triển sản phẩm tại Hireology"
      content: "Việc tích hợp GroupDocs.Viewer cho Cloud API thật đơn giản với Ruby SDK tuyệt vời của họ. Không có nhiều công ty sẵn sàng làm việc với chúng tôi về những gì chúng tôi muốn. Đó là một quan hệ đối tác tuyệt vời."

    # testimonial item loop
    - name: "Mats Oustad"
      designation: "Senior Consultant/Partner at Novanet AS"
      content: "Sau khi triển khai và sử dụng GroupDocs.Viewer cho .NET trong dự án, có vẻ như nó đang hoạt động rất tốt. Tôi đã thử nghiệm với rất nhiều tài liệu và cho đến nay rất tốt. Mọi thứ tôi đã ném vào nó đều hiển thị độc đáo và trông đẹp mắt như trong trình xem PDF hoặc MS Word."
              
    # testimonial item loop
    - name: "Martin Lasarga"
      designation: "Giám đốc sản phẩm tại Axentria ECM của G.S.I."
      content: "Dịch vụ tuyệt vời và sản phẩm tuyệt vời. Chúng cực kỳ hữu ích và phản hồi nhanh trong quá trình triển khai GroupDocs.Viewer cho .NET, không thể đề xuất chúng đủ cao."

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Viewer cung cấp API xem tài liệu cho các môi trường phát triển phổ biến khác"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Viewer for Java"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-viewer-java.png"
          product: "GroupDocs.Viewer"
          platform: "Java"
          link: "/viewer/java/"

############################# Back to top ###############################
back_to_top:
  enable: true
---
