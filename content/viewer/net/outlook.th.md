---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: th

############################# Head #############################
head_title: ".NET Outlook Viewer API - อ่าน ดู แสดงผลใน C# VB.NET"
head_description: "API โปรแกรมดูเอกสาร .NET เพื่ออ่าน เรนเดอร์ และแสดง Outlook ในแอปพลิเคชัน C#, ASP.NET, VB.NET และ .NET Core ทุกประเภท"

############################# Header ############################
title: "Outlook โปรแกรมดูไฟล์สำหรับแอปพลิเคชัน C# .NET" 
description: "API โปรแกรมดูเอกสาร .NET เพื่ออ่าน แสดงผล และแสดงไฟล์ Outlook ในแอปพลิเคชัน C#, ASP.NET, VB.NET และ .NET Core ทุกประเภท ดูไฟล์ที่เรนเดอร์ด้วยการจัดรูปแบบและเค้าโครงจริงใน HTML5, PDF หรือเป็นรูปภาพโดยใช้โค้ดไม่กี่บรรทัด" 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "ดาวน์โหลดรุ่นทดลองใช้ฟรี"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "เกี่ยวกับ GroupDocs.Viewer สำหรับ .NET API" 
    content: |
        เริ่มดูรูปแบบเอกสารยอดนิยมกว่า 190 รูปแบบในแอปพลิเคชัน .NET ของคุณโดยใช้ GroupDocs.Viewer สำหรับ .NET API โดยเพิ่มโค้ดสองสามบรรทัด นักพัฒนาสามารถแสดง PDF, Word Processing, Excel Spreadsheet, Presentation, Visio, Project, Outlook และรูปแบบเอกสารยอดนิยมอื่นๆ ในโหมด HTML5 รูปภาพ หรือ PDF ได้อย่างง่ายดาย การแสดงเอกสารทำได้รวดเร็ว เหมือนกับไฟล์ต้นฉบับ และไม่ต้องติดตั้งซอฟต์แวร์เพิ่มเติมหรือไลบรารีภายนอกอื่นใด

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
              text: "การอ้างอิง API"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "ตัวอย่างโค้ด"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "การสาธิตสด"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "ราคา"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "ขั้นตอนใน Render ไฟล์ Outlook ใน C#" 
    content_left: |
        ด้วย [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/) คุณสามารถแสดง Outlook เป็น HTML, JPEG, PNG หรือ PDF ในไม่กี่ขั้นตอน

        * ติดตั้ง [GroupDocs.Viewer สำหรับ .NET](https://www.nuget.org/packages/groupdocs.viewer) โดยใช้ตัวจัดการแพ็คเกจที่คุณชื่นชอบ 
        * สร้างอินสแตนซ์ของคลาส Viewer และโหลดไฟล์ Outlook ด้วยเส้นทางแบบเต็ม 
        * ตั้งค่าตัวเลือกเพื่อแสดงไฟล์ Outlook เป็นรูปแบบ HTML, PNG, JPEG หรือ PDF 
        * เรนเดอร์ไฟล์และตรวจสอบเอาต์พุตในไดเร็กทอรีปัจจุบัน 
        
    title_right: "ความต้องการของระบบ" 
    content_right: |
        GroupDocs.Viewer สำหรับ .NET API ได้รับการสนับสนุนบนแพลตฟอร์มและระบบปฏิบัติการหลักทั้งหมด ก่อนดำเนินการโค้ดด้านล่าง โปรดตรวจสอบว่าคุณได้ติดตั้งข้อกำหนดเบื้องต้นต่อไปนี้ในระบบของคุณแล้ว

        * ระบบปฏิบัติการ: Microsoft Windows, Linux, MacOS 
        * สภาพแวดล้อมการพัฒนา: Microsoft Visual Studio, Visual Studio Code, .NET CLI 
        * กรอบงาน: .NET Framework, .NET Standard, .NET Core, .NET 
    code: |
        ```cs
                        
            // Set up input Outlook file
            string filePath = "input.pst";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render Outlook file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "Outlook โปรแกรมดูการสาธิตสด"
    content: |
        ดูไฟล์ Outlook ตอนนี้โดยไปที่เว็บไซต์ [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/outlook)
    lang: "th"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "รูปแบบไฟล์อื่นๆ การเรนเดอร์และการดูโดยใช้ C#"
    exclude: "Outlook"
    content: |
        API โปรแกรมดูเอกสารและรูปภาพหลายรูปแบบสำหรับ .NET ดูรูปแบบไฟล์ยอดนิยมบางรูปแบบด้านล่างโดยไม่ต้องใช้โปรแกรมดูภายนอก
    format: 
        # format loop 1
        - name: "เรนเดอร์ DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word เปิดเอกสาร XML" 

        # format loop 2
        - name: "เรนเดอร์ CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "ไฟล์ CorelDRAW" 

        # format loop 3
        - name: "เรนเดอร์ PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint เปิดงานนำเสนอ XML" 

        # format loop 4
        - name: "เรนเดอร์ XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Open XML สเปรดชีต" 

        # format loop 5
        - name: "แสดงผล DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "เขียนแบบ AutoCAD"

        # format loop 6
        - name: "แสดงผล XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "ไฟล์ XML"

        # format loop 7
        - name: "เรนเดอร์ PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "เอกสาร Adobe Photoshop"

        # format loop 8
        - name: "เรนเดอร์ไฟล์ Adobe Illustrator"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Adobe Illustrator งานศิลปะ"

        # format loop 9
        - name: "เรนเดอร์ DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "เอกสาร Microsoft Word" 

        # format loop 10
        - name: "เรนเดอร์ TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "ไฟล์ข้อความธรรมดา" 

        # format loop 11
        - name: "เรนเดอร์ DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "ไฟล์รูปแบบการแลกเปลี่ยนการวาด"  
          
        # format loop 12
        - name: "แสดงผล VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "ไฟล์ vCard"  
              
        # format loop 13
        - name: "แสดงผล SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "กราฟิกแบบเวกเตอร์ที่ปรับขนาดได้" 
          
        # format loop 14
        - name: "แสดงผล HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "ไฟล์ภาษามาร์กอัปไฮเปอร์เท็กซ์" 
          
        # format loop 15
        - name: "เรนเดอร์ PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "ไฟล์รูปแบบเอกสารพกพา"
          
        # format loop 16
        - name: "เรนเดอร์ JPEG"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "รูปภาพ JPEG"
          
        # format loop 17
        - name: "เรนเดอร์ PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "กราฟิกเครือข่ายแบบพกพา" 
          
        # format loop 18
        - name: "แสดงผล EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "ข้อความอีเมล" 
          
        # format loop 19
        - name: "เรนเดอร์ RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "ไฟล์รูปแบบ Rich Text" 
          
        # format loop 20
        - name: "เรนเดอร์ ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "เอกสารข้อความ OpenDocument" 
          
        # format loop 21
        - name: "แสดงผล CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "ไฟล์ค่าที่คั่นด้วยเครื่องหมายจุลภาค" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
