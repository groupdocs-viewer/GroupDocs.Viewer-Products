---
############################# Static ############################
layout: "family"
date: 2023-12-20T06:39:57
draft: false

product: "Viewer"
product_tag: "viewer"

############################# Head ############################
head_title: "API kết xuất và xem tài liệu | API tại chỗ và dịch vụ trực tuyến"
head_description: "Kết xuất và xem các tệp Word, PDF, Excel, Powerpoint hoặc Hình ảnh một cách dễ dàng và miễn phí"

############################# Header ############################
title: "Hiển thị và xem tài liệu một cách dễ dàng"
description: |
  API trình xem mạnh mẽ để hiển thị các tệp khác nhau thành PDF, HTML và Hình ảnh.

  Tải tài liệu từ nhiều nguồn khác nhau, bao gồm tệp, luồng, URL, máy chủ FTP, Amazon S3, Azure Blob Storage, v.v.

  Tạo các trang HTML đáp ứng, bảo vệ các tệp PDF đầu ra và sắp xếp lại các trang của chúng, xoay trang, hiển thị ghi chú và nhận xét nếu cần.
  

############################# Platforms ############################
supported_platforms:
  enable: true  
  head_title: "Chọn nền tảng của bạn"
  title: "Nền tảng được hỗ trợ"
  description: "Thư viện GroupDocs.Viewer hỗ trợ các hệ điều hành và framework sau"
  details_link_title: "Tìm hiểu thêm"
  items:
    # supported_platforms loop
    - title: ".NET"
      description: "GroupDocs.Viewer for .NET"
      color: "blue"
      tag: "net"
      link: "/viewer/net/"
      features_link: "https://docs.groupdocs.com/viewer/net/system-requirements/"
      features:
        # features loop
        - content: ".NET Framework 4.6.2+  <br>  .NET Core 3.1  <br>  .NET 6+"
          rows: "3"
        # features loop
        - content: "Windows, Linux"
          rows: "1"
        # features loop
        - content: "180+ file formats"
          rows: "1"
        # features loop
        - content: "UI package for ASP.NET Core"
          rows: "1"
        # features loop
        - content: "ASP.NET WebForms Demo  <br>  ASP.NET MVC Demo  <br>  ASP.NET Core Demo"
          rows: "3"
    
    # supported_platforms loop
    - title: "Java"
      description: "GroupDocs.Viewer for Java"
      color: "red"
      tag: "java"
      link: "/viewer/java/"
      features_link: "https://docs.groupdocs.com/viewer/java/system-requirements/"
      features:
        # features loop
        - content: "J2SE 8.0 (1.8)+"
          rows: "3"
        # features loop
        - content:  "Windows, Linux, macOS"
          rows: "1"       
        # features loop
        - content:  "180+ file formats"
          rows: "1"
        # features loop
        - content:  "UI package for Spring and Dropwizard"
          rows: "1"
        # features loop
        - content:  "Spring Demo  <br>  Dropwizard demo"
          rows: "3"

    # supported_platforms loop
    - title: "Node.js"
      description: "GroupDocs.Viewer for Node.js"
      color: "green"
      tag: "nodejs-java"
      link: "/viewer/nodejs-java/"
      features_link: "https://docs.groupdocs.com/viewer/nodejs-java/system-requirements/"
      features:
        # features loop
        - content: "Node.js 16+  <br>  and J2SE 8.0 (1.8)+"
          rows: "3"
        # features loop
        - content:  "Windows, Linux, macOS"
          rows: "1"
        # features loop
        - content:  "180+ file formats"
          rows: "1"
        # features loop
        - content:  "UI package - coming soon "
          rows: "1" 
        # features loop
        - content:  "Demo - coming soon "
          rows: "3" 



############################# Features ############################

features:
  enable: true
  title: "Bộ tính năng của GroupDocs.Viewer"
  description: "API để hiển thị các loại tệp khác nhau dưới dạng HTML, PDF, PNG và JPEG trong các ứng dụng để xem chúng mà không cần phần mềm của bên thứ ba."

  items:
    # feature loop
    - icon: "view"
      title: "Xem tài liệu và hình ảnh"
      content: "Xem tài liệu bằng cách hiển thị chúng dưới dạng tệp HTML, PDF, PNG và JPEG."
    # feature loop
    - icon: "password"
      title: "Mở tài liệu được bảo mật"
      content: "Chỉ định mật khẩu để mở tài liệu được mã hóa."

    # feature loop
    - icon: "load"
      title: "Tải tập tin từ mọi nơi"
      content: "Tải tài liệu từ nhiều tệp, URL, máy chủ FTP, Amazon S3, v.v."
    
    # feature loop
    - icon: "pages"
      title: "Hiển thị tất cả hoặc các trang cụ thể"
      content: "Chỉ định một phạm vi số trang sẽ được hiển thị."


############################# Code samples ############################
code_samples:
  enable: true
  title: "Mẫu mã GroupDocs.Viewer"
  description: "Một số trường hợp sử dụng các thao tác GroupDocs.Viewer điển hình trong C#, Java, TypeScript"
  items:
    # code sample loop
    - title: "Cách hiển thị tệp DOCX thành PDF"
      content: |
        Hiển thị tài liệu DOCX thành PDF mà không cần cài đặt Microsoft Word hoặc phần mềm khác. Dễ dàng tải và xem các tệp DOCX trong ứng dụng .NET của bạn, cho dù đó là ứng dụng web hay máy tính để bàn. Dưới đây là ví dụ về cách hiển thị tệp DOCX thành PDF: 
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Tải tệp DOCX để kết xuất
            using (Viewer viewer = new Viewer("sample.docx"))
            {
              // Kết xuất DOCX thành tệp PDF
              PdfViewOptions viewOptions = new PdfViewOptions();
              viewer.View(viewOptions);
            }
            ```
        - language: "Java"
          color: "red"
          content: |
            ```java {style=abap}   
            import com.groupdocs.viewer.Viewer;
            import com.groupdocs.viewer.options.PdfViewOptions;
            // ...
            // Tải tệp DOCX để kết xuất
            try (Viewer viewer = new Viewer("sample.docx")) {
                // Kết xuất DOCX thành tệp PDF
                PdfViewOptions viewOptions = new PdfViewOptions();
                viewer.view(viewOptions);
            }
            ```
        - language: "TypeScript"
          color: "green"
          content: |
            ```javascript {style=abap}  
            // Tải tệp DOCX để kết xuất
            const viewer = new groupdocs.viewer.Viewer("sample.docx")
            
            // Kết xuất DOCX thành tệp PDF
            const viewOptions = groupdocs.viewer.PdfViewOptions(output.pdf)
            viewer.view(viewOptions)
            ```


############################# Formats ############################
formats:
  enable: true
  title:  "Hơn 180 định dạng tệp được hỗ trợ"
  description: "GroupDocs.Viewer hỗ trợ các thao tác với [định dạng tệp](https://docs.groupdocs.com/viewer/net/supported-document-formats/) phổ biến nhất" 



############################# Metrics ############################

metrics:
  enable: true
  title: "Số liệu chuyên sâu và hiểu biết thống kê"
  description: "Đi sâu vào phân tích chi tiết về các số liệu quan trọng của chúng tôi, cung cấp số liệu toàn diện và thông tin thống kê chuyên sâu về thành tích, tác động và sự phát triển của chúng tôi."

  items:
    # metrics loop
    - number: "180+"
      title: "Các định dạng được hỗ trợ"
      content: "Dễ dàng xem hơn 180 định dạng tệp bao gồm tài liệu, hình ảnh và bản vẽ CAD một cách dễ dàng. Phá vỡ các rào cản tương thích và truy cập các tệp đa dạng một cách dễ dàng bằng giải pháp xem toàn diện của chúng tôi."

    # metrics loop
    - number: "1.0M"
      title: "Tải xuống NuGet"
      content: "Giải pháp gói NuGet của chúng tôi đã trở thành tài nguyên đáng tin cậy và được áp dụng rộng rãi trong cộng đồng nhà phát triển, cung cấp khả năng tích hợp liền mạch và chức năng có giá trị cho vô số dự án."

    # metrics loop
    - number: "10+"
      title: "Thư viện"
      content: "Sản phẩm của chúng tôi bao gồm hơn 10 thư viện, cung cấp các tính năng nâng cao để tối ưu hóa hiệu suất. Những thư viện này được thiết kế để đáp ứng các nhu cầu phát triển khác nhau với khả năng tuyệt vời."
    
    # metrics loop
    - number: "100+"
      title: "Khách hàng hạnh phúc"
      content: "Phục vụ các thương hiệu mang tính biểu tượng nhất trên toàn cầu. Khám phá lý do tại sao hàng trăm người yêu thích GroupDocs.Viewer! Khám phá khả năng điều hướng liền mạch, cộng tác thuận tiện và tính dễ sử dụng chưa từng có. Tham gia ngay!"



############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "Khách hàng hạnh phúc của chúng tôi"
  description: "Thư viện GroupDocs được các thương hiệu nổi tiếng và nổi tiếng trên toàn thế giới sử dụng."

  items:
    # customers loop
    - title: "BenQ Corporation"
      logo: "benq"
    # customers loop
    - title: "Nasdaq Stock Market"
      logo: "nasdaq"
    # customers loop
    - title: "AT&T Inc."
      logo: "att"
    # customers loop
    - title: "AstraZeneca"
      logo: "astrazeneca"
    # customers loop
    - title: "Central Bank of Argentina"
      logo: "argentinacentralbank"
    # customers loop
    - title: "Roche Holding AG"
      logo: "roche"
    # customers loop
    - title: "Capita"
      logo: "capita"
    # customers loop
    - title: "Axa S.A."
      logo: "axa"
    # customers loop
    - title: "Instructure Inc."
      logo: "instructure"
     # customers loop
    - title: "Wipro"
      logo: "wipro"



############################# Actions ############################

actions:
  enable: true
  title: "Sẵn sàng để bắt đầu?"
  description: "Dùng thử miễn phí các tính năng của GroupDocs.Viewer hoặc yêu cầu giấy phép"
  items:
    #  loop
    - title: ".NET"
      link: "/viewer/net/"
      color: "blue"
        #  loop
    - title: "Java"
      link: "/viewer/java/"
      color: "red"
        #  loop
    - title: "Node.js"
      link: "/viewer/nodejs-java/"
      color: "green"


############################# Faq ############################

faq:
  enable: true
  title:  "Các câu hỏi và mối quan tâm thường gặp"
  description:  "Tìm câu trả lời cho các câu hỏi thường gặp trong phần Câu hỏi thường gặp của chúng tôi để nhanh chóng giải quyết các thắc mắc và mối quan tâm của bạn."
  items:
    #  loop
    - question: "Tôi có thể đánh giá các sản phẩm GroupDocs trước khi mua không?"
      answer: |
        Đúng! Tất cả các sản phẩm của GroupDocs đều có sẵn phiên bản đánh giá, không rủi ro. Chúng tôi đặc biệt khuyến khích các nhà phát triển tải xuống và dùng thử API của chúng tôi trước khi mua để đảm bảo rằng chúng sẽ đáp ứng 100% nhu cầu của bạn.
    #  loop
    - question: "GroupDocs có trình diễn sản phẩm không?"
      answer: |
        Không, trọng tâm của chúng tôi là các API và tạo ra những sản phẩm ổn định và có chức năng nhất có thể. Chúng tôi cung cấp các bản dùng thử miễn phí và đầy đủ chức năng dưới dạng [giấy phép tạm thời](https://purchase.groupdocs.com/temporary-license/) để bạn có thể tự mình dùng thử sản phẩm.    
    #  loop
    - question: "Tôi có thể tải sản phẩm ở đâu?"
      answer: |
        Bạn có thể tải xuống tất cả sản phẩm từ [trang web](https://releases.groupdocs.com). Chúng tôi không gửi bản sao thực của phần mềm qua thư.
    #  loop
    - question: "Giấy phép nhà phát triển GroupDocs dành cho mỗi người dùng hay mỗi người dùng được đặt tên?"
      answer: |
        Giấy phép Nhà phát triển GroupDocs dành cho mỗi người dùng, không phải cho mỗi người dùng được đặt tên. Chúng tôi hiểu rằng các thành viên của nhóm viết mã có thể thay đổi theo thời gian và việc phải cập nhật giấy phép mỗi lần điều đó xảy ra là không thực tế.
    #  loop
    - question: "Chúng ta có cần cấp phép chỉ cho các nhà phát triển đang hoạt động không? Ví dụ: chúng tôi có một nhóm gồm hai nhà phát triển làm việc ở ca A và một nhóm thứ hai gồm hai nhà phát triển làm việc ở ca B… trong tình huống này, chúng tôi cần hai hay bốn giấy phép?"
      answer: |
        Tất cả các nhà phát triển đang làm việc trong dự án đều phải được cấp phép. Trong tình huống này, GroupDocs thấy nhóm của bạn có bốn thành viên (mặc dù họ làm việc vào những thời điểm khác nhau). 


############################# Cloud ############################

cloud_links:
  enable: true
  title: "API mã thấp GroupDocs.Viewer"
  description: "Tăng tốc độ xem tài liệu hoặc hình ảnh trong bất kỳ loại ứng dụng nào với API REST dựa trên đám mây của chúng tôi"

  items:
    #  loop
    - icon: "groupdocs_viewer-for-curl"
      title: "GroupDocs.Viewer Cloud for cURL"
      link: "https://products.groupdocs.cloud/viewer/curl"
      content: "Sử dụng API trình xem tài liệu cURL RESTful để hiển thị và hiển thị hiệu quả Microsoft Office, PDF và nhiều định dạng tệp tiêu chuẩn khác trong ứng dụng của bạn."

    #  loop
    - icon: "groupdocs_viewer-for-net"
      title: "GroupDocs.Viewer Cloud for .NET"
      link: "https://products.groupdocs.cloud/viewer/net"
      content: "Nâng cao khả năng xem tài liệu trong các ứng dụng .NET với Cloud SDK cho .NET. Xem tài liệu liền mạch ở định dạng HTML, PDF hoặc hình ảnh."

    #  loop
    - icon: "groupdocs_viewer-for-java"
      title: "GroupDocs.Viewer Cloud for Java"
      link: "https://products.groupdocs.cloud/viewer/java"
      content: "Tích hợp khả năng hiển thị tài liệu nâng cao vào các ứng dụng Java của bạn bằng cách sử dụng SDK Trình xem Tài liệu được xây dựng có mục đích dành cho Java."
    

############################# Apps ############################

app_links:
  enable: true
  title: "Ứng dụng GroupDocs.Viewer NoCode"
  description: "Ứng dụng trực tuyến cho phép bạn xem hơn 180 định dạng tệp phổ biến trong trình duyệt"

  items:
    #  loop
    - icon: "groupdocs_viewer-app"
      title: "GroupDocs.Viewer Total"
      link: "https://products.groupdocs.app/viewer/total"
      content: "Khám phá ứng dụng trực tuyến miễn phí để xem hơn 180 định dạng tệp trực tiếp từ trình duyệt web ưa thích của bạn."

    #  loop
    - icon: "groupdocs_words-app"
      title:  "GroupDocs.Viewer DOCX"
      link: "https://products.groupdocs.app/viewer/docx"
      content: "Công cụ dựa trên web để xem các tệp Microsoft Word một cách dễ dàng trên nhiều thiết bị khác nhau."

    #  loop
    - icon: "groupdocs_pdf-app"
      title:  "GroupDocs.Viewer PDF"
      link: "https://products.groupdocs.app/viewer/pdf"
      content: "Mở và xem tệp PDF trực tuyến bằng trình xem PDF miễn phí."
    



---