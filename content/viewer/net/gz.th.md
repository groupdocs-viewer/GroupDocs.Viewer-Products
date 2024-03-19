---
############################# Static ############################
layout: "format"
date: 2024-03-19T07:01:08
draft: false
lang: th
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head #############################
head_title: ".NET GZ Viewer API - อ่าน ดู เรนเดอร์ใน C# VB.NET"
head_description: "API โปรแกรมดูเอกสาร .NET เพื่ออ่าน เรนเดอร์ และแสดง GZ ในแอปพลิเคชัน C#, ASP.NET, VB.NET และ .NET Core ทุกประเภท"

############################# Header ############################
title: "โปรแกรมดูไฟล์ GZ สำหรับแอปพลิเคชัน C# .NET" 
description: "API โปรแกรมดูเอกสาร .NET เพื่ออ่าน เรนเดอร์ และแสดงไฟล์ GZ ในแอปพลิเคชัน C#, ASP.NET, VB.NET และ .NET Core ทุกประเภท ดูไฟล์ที่เรนเดอร์ด้วยการจัดรูปแบบและเค้าโครงที่แท้จริงใน HTML5, PDF หรือเป็นรูปภาพโดยใช้โค้ดเพียงไม่กี่บรรทัด" 
subtitle: "โซลูชันการแสดงผลเอกสาร" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "ดาวน์โหลดฟรี Nuget"
      link: "https://releases.groupdocs.com/viewer/net/"



############################# About ############################
about:
    enable: true
    title: "เกี่ยวกับ GroupDocs.Viewer สำหรับ .NET API"
    link: "/viewer/net/"
    link_title: "เรียนรู้เพิ่มเติม"
    picture: "about_viewer.svg" # 480 X 400
    content: |
      เริ่มดูรูปแบบเอกสารยอดนิยมกว่า 190 รูปแบบในแอปพลิเคชัน .NET ของคุณโดยใช้ GroupDocs.Viewer สำหรับ .NET API โดยการเพิ่มโค้ดสองสามบรรทัด นักพัฒนาสามารถแสดง PDF, การประมวลผลคำ, สเปรดชีต Excel, การนำเสนอ, Visio, โครงการ, Outlook และรูปแบบเอกสารยอดนิยมอื่นๆ ในโหมด HTML5, รูปภาพ หรือ PDF ได้อย่างง่ายดาย การเรนเดอร์เอกสารรวดเร็ว เหมือนกับไฟล์ต้นฉบับ และไม่จำเป็นต้องติดตั้งซอฟต์แวร์เพิ่มเติมหรือไลบรารีภายนอกอื่นใด



############################# Steps ############################
steps:
    enable: true
    title: "ขั้นตอนในการแสดงผลไฟล์ GZ ใน C#" 
    content: |
      ด้วย <a href='https://products.groupdocs.com/viewer/net/'>GroupDocs.Viewer</a> คุณสามารถแสดงผล GZ เป็น HTML, JPEG, PNG หรือ PDF ได้ในไม่กี่ขั้นตอน
      
      1. ติดตั้ง <a href='https://www.nuget.org/packages/groupdocs.viewer'>GroupDocs.Viewer สำหรับ .NET</a> โดยใช้ตัวจัดการแพ็คเกจที่คุณชื่นชอบ 
      2. สร้างอินสแตนซ์ของคลาส Viewer และโหลดไฟล์ GZ ด้วยเส้นทางแบบเต็ม  
      3. ตั้งค่าตัวเลือกเพื่อแสดงไฟล์ GZ เป็นรูปแบบ HTML, PNG, JPEG หรือ PDF 
      4. เรนเดอร์ไฟล์และตรวจสอบเอาต์พุตในไดเร็กทอรีปัจจุบัน 
   
    code:
      platform: "net"
      copy_title: "สำเนา"
      install:
        command: "dotnet add package GroupDocs.Viewer"
        copy_tip: "คลิกเพื่อคัดลอก"
        copy_done: "คัดลอก"
      links:
        #  loop
        - title: "ตัวอย่างเพิ่มเติม"
          link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
        #  loop
        - title: "เอกสารประกอบ"
          link: "https://docs.groupdocs.com/viewer/net/"
          
      content: |
        ```csharp {style=abap}

        // ตั้งค่าไฟล์อินพุต GZ
        string filePath = "input.gz";

        // สร้างอินสแตนซ์ GroupDocs.Viewer
        using (Viewer viewer = new Viewer(filePath))
        {
            // ตั้งค่าตัวเลือกมุมมอง
            HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                
            // เรนเดอร์ไฟล์ GZ เป็น HTML ด้วยทรัพยากรที่ฝังอยู่
            viewer.View(viewOptions);
        }

        ```            


############################# Actions ############################

actions:
  enable: true
  title: "พร้อมที่จะเริ่มต้นหรือยัง?"
  description: "ลองใช้คุณสมบัติ GroupDocs.Viewer ฟรีหรือขอใบอนุญาต"
  items:
    #  loop
    - title: "ดาวน์โหลด"
      link: "https://releases.groupdocs.com/viewer/net/"
      color: "red"
        #  loop
    - title: "การออกใบอนุญาต"
      link: "https://purchase.groupdocs.com/pricing/viewer/net/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "เรนเดอร์ไฟล์รูปแบบอื่นโดยใช้ C#"
    exclude: "GZ"
    description: "API โปรแกรมดูเอกสารและรูปภาพหลายรูปแบบสำหรับ .NET ดูรูปแบบไฟล์ยอดนิยมบางรูปแบบด้านล่างโดยไม่ต้องใช้โปรแกรมดูจากภายนอก"
    items: 
        # format loop 1
        - name: "เรนเดอร์ DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word Open XML Document" 

        # format loop 2
        - name: "เรนเดอร์ CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "CorelDRAW File" 

        # format loop 3
        - name: "เรนเดอร์ PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint Open XML Presentation" 

        # format loop 4
        - name: "เรนเดอร์ XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet" 

        # format loop 5
        - name: "เรนเดอร์ DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "AutoCAD Drawing"

        # format loop 6
        - name: "เรนเดอร์ XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "XML File"

        # format loop 7
        - name: "เรนเดอร์ PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Adobe Photoshop Document"

        # format loop 8
        - name: "เรนเดอร์ AI"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Adobe Illustrator Artwork"

        # format loop 9
        - name: "เรนเดอร์ DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Microsoft Word Document" 

        # format loop 10
        - name: "เรนเดอร์ TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Plain Text File" 

        # format loop 11
        - name: "เรนเดอร์ DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Drawing Exchange Format File"  
          
        # format loop 12
        - name: "เรนเดอร์ VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "vCard File"  
              
        # format loop 13
        - name: "เรนเดอร์ SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Scalable Vector Graphic" 
          
        # format loop 14
        - name: "เรนเดอร์ HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "เรนเดอร์ PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Portable Document Format File"
          
        # format loop 16
        - name: "เรนเดอร์ JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "JPEG Image"
          
        # format loop 17
        - name: "เรนเดอร์ PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Portable Network Graphic" 
          
        # format loop 18
        - name: "เรนเดอร์ EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "E-Mail Message" 
          
        # format loop 19
        - name: "เรนเดอร์ RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Rich Text Format File" 
          
        # format loop 20
        - name: "เรนเดอร์ ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "OpenDocument Text Document" 
          
        # format loop 21
        - name: "แสดงผล CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Comma-Separated Values File" 



---
