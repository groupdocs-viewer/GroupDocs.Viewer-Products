---
############################# Static ############################
layout: "format"
date: 2024-03-19T07:00:57
draft: false
lang: vi
product: "Viewer"
product_tag: "viewer"
platform: "Java"
platform_tag: "java"

############################# Head #############################
head_title: "API trình xem Java ONE - hiển thị và hiển thị ONE trong ứng dụng Java"
head_description: "Xem các tệp ONE trong các ứng dụng Java, J2EE, J2SE. Hỗ trợ xem hơn 180 định dạng tệp tài liệu và hình ảnh ở chế độ HTML, PDF hoặc hình ảnh với các tính năng nâng cao để quản lý các tùy chọn xem tài liệu."

############################# Header ############################
title: "Hiển thị và xem ONE trong Java" 
description: "API trình xem tệp ONE gốc và hiệu suất cao dành cho các ứng dụng dựa trên Java, J2EE và J2SE, hỗ trợ nhiều tính năng bổ sung để tùy chỉnh giao diện của định dạng tài liệu đầu ra." 
subtitle: "Giải pháp kết xuất tài liệu" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "Tải xuống Maven miễn phí"
      link: "https://releases.groupdocs.com/viewer/java/"



############################# About ############################
about:
    enable: true
    title: "Giới thiệu về GroupDocs.Viewer dành cho API Java"
    link: "/viewer/java/"
    link_title: "Tìm hiểu thêm"
    picture: "about_viewer.svg" # 480 X 400
    content: |
      Cho phép các ứng dụng Java của bạn hiển thị hơn 180 định dạng tệp ở chế độ HTML, PDF hoặc hình ảnh bằng GroupDocs.Viewer dành cho API Java mà không cần cài đặt bất kỳ phần mềm bổ sung nào; chẳng hạn như Microsoft Office, Apache Open Office, Adobe Acrobat Reader, v.v. Các nhà phát triển có thể dễ dàng xem tất cả các hình ảnh và loại tài liệu phổ biến bao gồm Microsoft Office, OpenDocument, HTML, PDF, Archive, Diagrams, Photoshop, AutoCAD và các định dạng ngôn ngữ lập trình bên trong các ứng dụng Java với kết xuất nhanh và chất lượng cao nhất.



############################# Steps ############################
steps:
    enable: true
    title: "Các bước để hiển thị tệp ONE trong Java" 
    content: |
      Với <a href='https://products.groupdocs.com/viewer/java/'>GroupDocs.Viewer</a> bạn có thể hiển thị ONE thành HTML, JPEG, PNG hoặc PDF chỉ trong vài bước.
      
      1. Thêm <a href='https://releases.groupdocs.com/viewer/java/'>GroupDocs.Viewer for Java</a> làm phần phụ thuộc cho dự án của bạn. 
      2. Tạo một phiên bản của lớp Viewer và tải tệp ONE với đường dẫn đầy đủ.  
      3. Đặt tùy chọn để hiển thị tệp ONE thành định dạng HTML, PNG, JPEG hoặc PDF. 
      4. Kết xuất tệp và kiểm tra đầu ra trong thư mục hiện tại. 
   
    code:
      platform: "java"
      copy_title: "Sao chép"
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
        copy_tip: "bấm vào để sao chép"
        copy_done: "sao chép"
      links:
        #  loop
        - title: "Thêm ví dụ"
          link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Java"
        #  loop
        - title: "Tài liệu"
          link: "https://docs.groupdocs.com/viewer/java/"
          
      content: |
        ```java {style=abap}

        // Thiết lập tệp ONE đầu vào
        String filePath = "input.one";

        // Khởi tạo GroupDocs.Viewer
        try (Viewer viewer = new Viewer(filePath))
        {
            // Đặt tùy chọn xem
            HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                
            // Kết xuất tệp ONE thành HTML bằng tài nguyên được nhúng
            viewer.view(viewOptions);
        }

        ```
            

############################# Actions ############################

actions:
  enable: true
  title: "Sẵn sàng để bắt đầu?"
  description: "Dùng thử miễn phí các tính năng của GroupDocs.Viewer hoặc yêu cầu giấy phép"
  items:
    #  loop
    - title: "Tải xuống Maven"
      link: "https://releases.groupdocs.com/viewer/java/"
      color: "red"
        #  loop
    - title: "Cấp phép"
      link: "https://purchase.groupdocs.com/pricing/viewer/java/"
      color: "light"



############################# More Formats #####################
more_formats:
    enable: true
    title: "Hiển thị các định dạng tệp khác bằng cách sử dụng Java"
    exclude: "ONE"
    description: "API xem tài liệu và hình ảnh đa định dạng cho Java. Xem một số định dạng tệp phổ biến bên dưới mà không cần bất kỳ trình xem bên ngoài nào."
    items: 
        # format loop 1
        - name: "Kết xuất DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Open XML Document" 

        # format loop 2
        - name: "Kết xuất CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "CorelDRAW File" 

        # format loop 3
        - name: "Kết xuất PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint Open XML Presentation" 

        # format loop 4
        - name: "Kết xuất XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet" 

        # format loop 5
        - name: "Kết xuất DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "AutoCAD Drawing"

        # format loop 6
        - name: "Kết xuất XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "XML File"

        # format loop 7
        - name: "Kết xuất PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Adobe Photoshop Document"

        # format loop 8
        - name: "Kết xuất AI"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Adobe Illustrator Artwork"

        # format loop 9
        - name: "Kết xuất DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Microsoft Word Document" 

        # format loop 10
        - name: "Kết xuất TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Plain Text File" 

        # format loop 11
        - name: "Kết xuất DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Drawing Exchange Format File"  
          
        # format loop 12
        - name: "Kết xuất VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "vCard File"  
              
        # format loop 13
        - name: "Kết xuất SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Scalable Vector Graphic" 
          
        # format loop 14
        - name: "Kết xuất HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "Kết xuất PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Portable Document Format File"
          
        # format loop 16
        - name: "Kết xuất JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "JPEG Image"
          
        # format loop 17
        - name: "Kết xuất PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Portable Network Graphic" 
          
        # format loop 18
        - name: "Kết xuất EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "E-Mail Message" 
          
        # format loop 19
        - name: "Kết xuất RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Rich Text Format File" 
          
        # format loop 20
        - name: "Kết xuất ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "OpenDocument Text Document" 
          
        # format loop 21
        - name: "Kết xuất CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Comma-Separated Values File" 


---
