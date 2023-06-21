---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: vi

############################# Head #############################
head_title: ".NET PST Viewer API - Đọc, Xem, Kết xuất trong C# VB.NET"
head_description: "API trình xem tài liệu .NET để đọc, kết xuất và hiển thị PST trong bất kỳ loại ứng dụng C#, ASP.NET, VB.NET & .NET Core nào."

############################# Header ############################
title: "PST Trình xem tệp cho các ứng dụng C# .NET" 
description: "API trình xem tài liệu .NET để đọc, kết xuất và hiển thị tệp PST trong bất kỳ loại ứng dụng C#, ASP.NET, VB.NET & .NET Core nào. Xem các tệp được hiển thị với định dạng & bố cục thực trong HTML5, PDF hoặc dưới dạng hình ảnh bằng cách sử dụng một vài dòng mã." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Tải xuống bản dùng thử miễn phí"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Giới thiệu về GroupDocs.Viewer cho .NET API" 
    content: |
        Bắt đầu xem hơn 190 định dạng tài liệu phổ biến trong các ứng dụng .NET của bạn bằng GroupDocs.Viewer cho API .NET bằng cách thêm một vài dòng mã. Các nhà phát triển có thể dễ dàng hiển thị PDF, Xử lý văn bản, Bảng tính Excel, Bản trình bày, Visio, Project, Outlook và nhiều định dạng tài liệu phổ biến khác ở chế độ HTML5, hình ảnh hoặc PDF. Kết xuất tài liệu nhanh, giống với tệp nguồn ban đầu và không yêu cầu cài đặt phần mềm bổ sung hoặc bất kỳ thư viện bên ngoài nào khác.

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
    title_left: "Các bước để kết xuất tệp PST trong C#" 
    content_left: |
        Với [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/), bạn có thể kết xuất PST thành HTML, JPEG, PNG hoặc PDF trong một vài bước.

        * Cài đặt [GroupDocs.Viewer cho .NET](https://www.nuget.org/packages/groupdocs.viewer) bằng trình quản lý gói yêu thích của bạn. 
        * Tạo một thể hiện của lớp Viewer và tải tệp PST với đường dẫn đầy đủ. 
        * Đặt các tùy chọn để hiển thị tệp PST thành định dạng HTML, PNG, JPEG hoặc PDF. 
        * Kết xuất tệp và kiểm tra đầu ra trong thư mục hiện tại. 
        
    title_right: "yêu cầu hệ thống" 
    content_right: |
        API GroupDocs.Viewer dành cho .NET được hỗ trợ trên tất cả các nền tảng và hệ điều hành chính. Trước khi thực thi mã bên dưới, vui lòng đảm bảo rằng bạn đã cài đặt các điều kiện tiên quyết sau trên hệ thống của mình.

        * Hệ điều hành: Microsoft Windows, Linux, MacOS 
        * Môi trường phát triển: Microsoft Visual Studio, Visual Studio Code, .NET CLI 
        * Khung: .NET Framework, .NET Standard, .NET Core, .NET 
    code: |
        ```cs
                        
            // Set up input PST file
            string filePath = "input.pst";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render PST file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "PST Trình diễn trực tiếp dành cho người xem"
    content: |
        Xem tệp PST ngay bây giờ bằng cách truy cập trang web [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/pst).
    lang: "vi"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Hiển thị & Xem các định dạng tệp khác bằng C#"
    exclude: "PST"
    content: |
        API trình xem hình ảnh và tài liệu đa định dạng cho .NET. Xem một số định dạng tệp phổ biến dưới đây mà không cần bất kỳ người xem bên ngoài nào.
    format: 
        # format loop 1
        - name: "Kết xuất DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Tài liệu XML mở Microsoft Word" 

        # format loop 2
        - name: "Kết xuất CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "Tệp CorelDRAW" 

        # format loop 3
        - name: "Kết xuất PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "Bản trình bày XML mở PowerPoint" 

        # format loop 4
        - name: "Kết xuất XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Bảng tính XML mở của Microsoft Excel" 

        # format loop 5
        - name: "Kết xuất DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "Vẽ AutoCAD"

        # format loop 6
        - name: "Kết xuất XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "Tệp XML"

        # format loop 7
        - name: "Kết xuất PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Tài liệu Adobe Photoshop"

        # format loop 8
        - name: "Kết xuất tệp Adobe Illustrator"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Adobe Illustrator Tác phẩm nghệ thuật"

        # format loop 9
        - name: "Kết xuất tài liệu"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Tài liệu Microsoft Word" 

        # format loop 10
        - name: "Kết xuất TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Tệp văn bản thuần túy" 

        # format loop 11
        - name: "Kết xuất DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Vẽ tệp định dạng trao đổi"  
          
        # format loop 12
        - name: "Kết xuất VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "Tệp vCard"  
              
        # format loop 13
        - name: "Kết xuất SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Đồ họa Vector có thể mở rộng" 
          
        # format loop 14
        - name: "Kết xuất HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Tệp ngôn ngữ đánh dấu siêu văn bản" 
          
        # format loop 15
        - name: "Kết xuất PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Tệp định dạng tài liệu di động"
          
        # format loop 16
        - name: "Kết xuất JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "Ảnh JPEG"
          
        # format loop 17
        - name: "Kết xuất PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Đồ họa mạng di động" 
          
        # format loop 18
        - name: "Kết xuất EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "Thư điện tử" 
          
        # format loop 19
        - name: "Kết xuất RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Tệp định dạng văn bản có định dạng" 
          
        # format loop 20
        - name: "Kết xuất ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "Tài liệu văn bản OpenDocument" 
          
        # format loop 21
        - name: "Kết xuất CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Tệp giá trị được phân tách bằng dấu phẩy" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
