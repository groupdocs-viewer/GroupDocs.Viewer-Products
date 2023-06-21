---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: vi

############################# Head #############################
head_title: "API Trình xem Java MM - Kết xuất & Hiển thị MM trong Ứng dụng Java"
head_description: "Xem các tệp MM trong các ứng dụng Java, J2EE, J2SE. Hỗ trợ xem hơn 170 định dạng tệp tài liệu và hình ảnh ở chế độ HTML, PDF hoặc hình ảnh với các tính năng nâng cao để quản lý các tùy chọn xem tài liệu."

############################# Header ############################
title: "Kết xuất & Xem MM Trong Java" 
description: "API trình xem tệp MM gốc và hiệu suất cao dành cho các ứng dụng dựa trên Java, J2EE và J2SE, hỗ trợ nhiều tính năng bổ sung để tùy chỉnh giao diện của định dạng tài liệu đầu ra." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Tải xuống bản dùng thử miễn phí"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Giới thiệu về API GroupDocs.Viewer cho Java" 
    content: |
        Cho phép các ứng dụng Java của bạn hiển thị hơn 170 định dạng tệp ở chế độ HTML, PDF hoặc hình ảnh bằng API GroupDocs.Viewer cho Java mà không cần cài đặt bất kỳ phần mềm bổ sung nào; chẳng hạn như Microsoft Office, Apache Open Office, Adobe Acrobat Reader, v.v. Các nhà phát triển có thể dễ dàng xem tất cả các loại hình ảnh và tài liệu phổ biến bao gồm Microsoft Office, OpenDocument, HTML, PDF, Archive, Diagrams, Photoshop, AutoCAD và các định dạng ngôn ngữ lập trình bên trong các ứng dụng Java với kết xuất nhanh và chất lượng cao nhất.

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
              text: "Tham chiếu API"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Ví dụ mã"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Bản trình diễn trực tiếp"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "định giá"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "Các bước để kết xuất tệp MM trong Java" 
    content_left: |
        Với [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/), bạn có thể kết xuất MM thành HTML, JPEG, PNG hoặc PDF trong một vài bước.

        * Thêm [GroupDocs.Viewer for Java](https://releases.groupdocs.com/viewer/java/) làm phần phụ thuộc cho dự án của bạn. 
        * Tạo một thể hiện của lớp Viewer và tải tệp MM với đường dẫn đầy đủ. 
        * Đặt các tùy chọn để hiển thị tệp MM thành định dạng HTML, PNG, JPEG hoặc PDF. 
        * Kết xuất tệp và kiểm tra đầu ra trong thư mục hiện tại. 
        
    title_right: "yêu cầu hệ thống" 
    content_right: |
        API GroupDocs.Viewer dành cho Java được hỗ trợ trên tất cả các nền tảng và hệ điều hành chính. Trước khi thực thi mã bên dưới, vui lòng đảm bảo rằng bạn đã cài đặt các điều kiện tiên quyết sau trên hệ thống của mình.

        * Hệ điều hành: Microsoft Windows, Linux, MacOS 
        * Môi trường phát triển: NetBeans, IntelliJ IDEA, Eclipse, v.v. 
        * Framework: J2SE 8.0 (1.8) trở lên (ví dụ Java 17) 
    code: |
        ```java
                        
            // Set up input MM file
            String filePath = "input.mm";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render MM file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "MM Trình diễn trực tiếp dành cho người xem"
    content: |
        Xem tệp MM ngay bây giờ bằng cách truy cập trang web [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/mm).
    lang: "vi"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Hiển thị & Xem các định dạng tệp khác bằng Java"
    exclude: "MM"
    content: |
        API trình xem hình ảnh và tài liệu đa định dạng cho Java. Xem một số định dạng tệp phổ biến dưới đây mà không cần bất kỳ người xem bên ngoài nào.
    format: 
        # format loop 1
        - name: "Kết xuất DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Tài liệu XML mở Microsoft Word" 

        # format loop 2
        - name: "Kết xuất CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "Tệp CorelDRAW" 

        # format loop 3
        - name: "Kết xuất PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "Bản trình bày XML mở PowerPoint" 

        # format loop 4
        - name: "Kết xuất XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Bảng tính XML mở của Microsoft Excel" 

        # format loop 5
        - name: "Kết xuất DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "Vẽ AutoCAD"

        # format loop 6
        - name: "Kết xuất XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "Tệp XML"

        # format loop 7
        - name: "Kết xuất PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Tài liệu Adobe Photoshop"

        # format loop 8
        - name: "Kết xuất tệp Adobe Illustrator"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Adobe Illustrator Tác phẩm nghệ thuật"

        # format loop 9
        - name: "Kết xuất tài liệu"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Tài liệu Microsoft Word" 

        # format loop 10
        - name: "Kết xuất TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Tệp văn bản thuần túy" 

        # format loop 11
        - name: "Kết xuất DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Vẽ tệp định dạng trao đổi"  
          
        # format loop 12
        - name: "Kết xuất VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "Tệp vCard"  
              
        # format loop 13
        - name: "Kết xuất SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Đồ họa Vector có thể mở rộng" 
          
        # format loop 14
        - name: "Kết xuất HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Tệp ngôn ngữ đánh dấu siêu văn bản" 
          
        # format loop 15
        - name: "Kết xuất PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Tệp định dạng tài liệu di động"
          
        # format loop 16
        - name: "Kết xuất JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "Ảnh JPEG"
          
        # format loop 17
        - name: "Kết xuất PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Đồ họa mạng di động" 
          
        # format loop 18
        - name: "Kết xuất EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "Thư điện tử" 
          
        # format loop 19
        - name: "Kết xuất RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Tệp định dạng văn bản có định dạng" 
          
        # format loop 20
        - name: "Kết xuất ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "Tài liệu văn bản OpenDocument" 
          
        # format loop 21
        - name: "Kết xuất CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Tệp giá trị được phân tách bằng dấu phẩy" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
