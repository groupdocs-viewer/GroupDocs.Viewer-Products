---
############################# Static ############################
layout: "format"
date: 2024-04-10T13:10:22
draft: false
lang: vi
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head #############################
head_title: "API trình xem .NET JLS - đọc, xem, hiển thị trong C# VB.NET"
head_description: "API trình xem tài liệu .NET để đọc, hiển thị và hiển thị JLS trong mọi loại ứng dụng C#, ASP.NET, VB.NET & .NET Core."

############################# Header ############################
title: "Trình xem tệp JLS dành cho ứng dụng C# .NET" 
description: "API trình xem tài liệu .NET để đọc, hiển thị và hiển thị tệp JLS trong mọi loại ứng dụng C#, ASP.NET, VB.NET & .NET Core. Xem các tệp được hiển thị với định dạng và bố cục thực ở dạng HTML5, PDF hoặc dưới dạng hình ảnh bằng cách sử dụng một vài dòng mã." 
subtitle: "Giải pháp kết xuất tài liệu" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "Tải xuống Nuget miễn phí"
      link: "https://nuget.org/packages/GroupDocs.Viewer"



############################# About ############################
about:
    enable: true
    title: "Giới thiệu về GroupDocs.Viewer cho .NET API"
    link: "/viewer/net/"
    link_title: "Tìm hiểu thêm"
    picture: "about_viewer.svg" # 480 X 400
    content: |
      Bắt đầu xem hơn 190 định dạng tài liệu phổ biến trong các ứng dụng .NET của bạn bằng GroupDocs.Viewer dành cho API .NET bằng cách thêm một vài dòng mã. Các nhà phát triển có thể dễ dàng hiển thị PDF, Word Xử lý, Bảng tính Excel, Bản trình bày, Visio, Project, Outlook và nhiều định dạng tài liệu phổ biến khác ở chế độ HTML5, hình ảnh hoặc PDF. Quá trình kết xuất tài liệu diễn ra nhanh chóng, giống hệt với tệp nguồn gốc và không yêu cầu cài đặt phần mềm bổ sung hoặc bất kỳ thư viện bên ngoài nào khác.



############################# Steps ############################
steps:
    enable: true
    title: "Các bước để hiển thị tệp JLS trong C#" 
    content: |
      Với <a href='https://products.groupdocs.com/viewer/net/'>GroupDocs.Viewer</a> bạn có thể hiển thị JLS thành HTML, JPEG, PNG hoặc PDF chỉ trong vài bước.
      
      1. Cài đặt <a href='https://www.nuget.org/packages/groupdocs.viewer'>GroupDocs.Viewer for .NET</a> bằng trình quản lý gói yêu thích của bạn. 
      2. Tạo một phiên bản của lớp Viewer và tải tệp JLS với đường dẫn đầy đủ.  
      3. Đặt tùy chọn để hiển thị tệp JLS thành định dạng HTML, PNG, JPEG hoặc PDF. 
      4. Kết xuất tệp và kiểm tra đầu ra trong thư mục hiện tại. 
   
    code:
      platform: "net"
      copy_title: "Sao chép"
      install:
        command: "dotnet add package GroupDocs.Viewer"
        copy_tip: "bấm vào để sao chép"
        copy_done: "sao chép"
      links:
        #  loop
        - title: "Thêm ví dụ"
          link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
        #  loop
        - title: "Tài liệu"
          link: "https://docs.groupdocs.com/viewer/net/"
          
      content: |
        ```csharp {style=abap}

        // Thiết lập tệp JLS đầu vào
        string filePath = "input.jls";

        // Khởi tạo GroupDocs.Viewer
        using (Viewer viewer = new Viewer(filePath))
        {
            // Đặt tùy chọn xem
            HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                
            // Kết xuất tệp JLS thành HTML bằng tài nguyên được nhúng
            viewer.View(viewOptions);
        }

        ```            


############################# Actions ############################

actions:
  enable: true
  title: "Sẵn sàng để bắt đầu?"
  description: "Dùng thử miễn phí các tính năng của GroupDocs.Viewer hoặc yêu cầu giấy phép"
  items:
    #  loop
    - title: "Tải xuống Nuget"
      link: "https://nuget.org/packages/GroupDocs.Viewer"
      color: "red"
        #  loop
    - title: "Cấp phép"
      link: "https://purchase.groupdocs.com/pricing/viewer/net/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "Hiển thị các định dạng tệp khác bằng cách sử dụng C#"
    exclude: "JLS"
    description: "API xem tài liệu và hình ảnh đa định dạng cho .NET. Xem một số định dạng tệp phổ biến bên dưới mà không cần bất kỳ trình xem bên ngoài nào."
    items: 
        # format loop 1
        - name: "Kết xuất DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word Open XML Document" 

        # format loop 2
        - name: "Kết xuất CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "CorelDRAW File" 

        # format loop 3
        - name: "Kết xuất PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint Open XML Presentation" 

        # format loop 4
        - name: "Kết xuất XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet" 

        # format loop 5
        - name: "Kết xuất DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "AutoCAD Drawing"

        # format loop 6
        - name: "Kết xuất XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "XML File"

        # format loop 7
        - name: "Kết xuất PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Adobe Photoshop Document"

        # format loop 8
        - name: "Kết xuất AI"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Adobe Illustrator Artwork"

        # format loop 9
        - name: "Kết xuất DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Microsoft Word Document" 

        # format loop 10
        - name: "Kết xuất TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Plain Text File" 

        # format loop 11
        - name: "Kết xuất DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Drawing Exchange Format File"  
          
        # format loop 12
        - name: "Kết xuất VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "vCard File"  
              
        # format loop 13
        - name: "Kết xuất SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Scalable Vector Graphic" 
          
        # format loop 14
        - name: "Kết xuất HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "Kết xuất PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Portable Document Format File"
          
        # format loop 16
        - name: "Kết xuất JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "JPEG Image"
          
        # format loop 17
        - name: "Kết xuất PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Portable Network Graphic" 
          
        # format loop 18
        - name: "Kết xuất EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "E-Mail Message" 
          
        # format loop 19
        - name: "Kết xuất RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Rich Text Format File" 
          
        # format loop 20
        - name: "Kết xuất ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "OpenDocument Text Document" 
          
        # format loop 21
        - name: "Kết xuất CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Comma-Separated Values File" 



---
