---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: th

############################# Head #############################
head_title: "Java CC Viewer API - แสดงผลและแสดงผล CC ในแอป Java"
head_description: "ดูไฟล์ CC ในแอปพลิเคชัน Java, J2EE, J2SE รองรับการดูไฟล์เอกสารและรูปภาพมากกว่า 170 รูปแบบในโหมด HTML, PDF หรือรูปภาพ พร้อมคุณสมบัติขั้นสูงในการจัดการตัวเลือกการดูเอกสาร"

############################# Header ############################
title: "แสดงผล & ดู CC ใน Java" 
description: "API โปรแกรมดูไฟล์แบบเนทีฟและประสิทธิภาพสูง CC สำหรับแอปพลิเคชันที่ใช้ Java, J2EE และ J2SE รองรับคุณสมบัติเพิ่มเติมที่หลากหลายเพื่อปรับแต่งรูปลักษณ์ของรูปแบบเอกสารเอาต์พุต" 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "ดาวน์โหลดรุ่นทดลองใช้ฟรี"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "เกี่ยวกับ GroupDocs.Viewer สำหรับ Java API" 
    content: |
        เปิดใช้งานแอปพลิเคชัน Java ของคุณเพื่อแสดงรูปแบบไฟล์มากกว่า 170+ รูปแบบในโหมด HTML, PDF หรือรูปภาพโดยใช้ GroupDocs.Viewer สำหรับ Java API โดยไม่ต้องติดตั้งซอฟต์แวร์เพิ่มเติม เช่น Microsoft Office, Apache Open Office, Adobe Acrobat Reader เป็นต้น นักพัฒนาสามารถดูรูปภาพและประเภทเอกสารยอดนิยมทั้งหมดได้อย่างง่ายดาย รวมทั้ง Microsoft Office, OpenDocument, HTML, PDF, Archive, Diagrams, Photoshop, AutoCAD และรูปแบบภาษาโปรแกรมภายในแอปพลิเคชัน Java ด้วย การเรนเดอร์ที่รวดเร็วและมีคุณภาพสูงสุด

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
    title_left: "ขั้นตอนใน Render ไฟล์ CC ใน Java" 
    content_left: |
        ด้วย [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/) คุณสามารถแสดง CC เป็น HTML, JPEG, PNG หรือ PDF ในไม่กี่ขั้นตอน

        * เพิ่ม [GroupDocs.Viewer สำหรับ Java](https://releases.groupdocs.com/viewer/java/) เป็นการพึ่งพาในโครงการของคุณ 
        * สร้างอินสแตนซ์ของคลาส Viewer และโหลดไฟล์ CC ด้วยเส้นทางแบบเต็ม 
        * ตั้งค่าตัวเลือกเพื่อแสดงไฟล์ CC เป็นรูปแบบ HTML, PNG, JPEG หรือ PDF 
        * เรนเดอร์ไฟล์และตรวจสอบเอาต์พุตในไดเร็กทอรีปัจจุบัน 
        
    title_right: "ความต้องการของระบบ" 
    content_right: |
        GroupDocs.Viewer สำหรับ Java API ได้รับการสนับสนุนบนแพลตฟอร์มและระบบปฏิบัติการหลักทั้งหมด ก่อนดำเนินการโค้ดด้านล่าง โปรดตรวจสอบว่าคุณได้ติดตั้งข้อกำหนดเบื้องต้นต่อไปนี้ในระบบของคุณแล้ว

        * ระบบปฏิบัติการ: Microsoft Windows, Linux, MacOS 
        * สภาพแวดล้อมการพัฒนา: NetBeans, IntelliJ IDEA, Eclipse เป็นต้น 
        * กรอบงาน: J2SE 8.0 (1.8) หรือสูงกว่า (เช่น Java 17) 
    code: |
        ```java
                        
            // Set up input CC file
            String filePath = "input.cc";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render CC file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "CC โปรแกรมดูการสาธิตสด"
    content: |
        ดูไฟล์ CC ตอนนี้โดยไปที่เว็บไซต์ [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/cc)
    lang: "th"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "รูปแบบไฟล์อื่นๆ การเรนเดอร์และการดูโดยใช้ Java"
    exclude: "CC"
    content: |
        API โปรแกรมดูเอกสารและรูปภาพหลายรูปแบบสำหรับ Java ดูรูปแบบไฟล์ยอดนิยมบางรูปแบบด้านล่างโดยไม่ต้องใช้โปรแกรมดูภายนอก
    format: 
        # format loop 1
        - name: "เรนเดอร์ DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word เปิดเอกสาร XML" 

        # format loop 2
        - name: "เรนเดอร์ CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "ไฟล์ CorelDRAW" 

        # format loop 3
        - name: "เรนเดอร์ PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint เปิดงานนำเสนอ XML" 

        # format loop 4
        - name: "เรนเดอร์ XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Open XML สเปรดชีต" 

        # format loop 5
        - name: "แสดงผล DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "เขียนแบบ AutoCAD"

        # format loop 6
        - name: "แสดงผล XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "ไฟล์ XML"

        # format loop 7
        - name: "เรนเดอร์ PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "เอกสาร Adobe Photoshop"

        # format loop 8
        - name: "เรนเดอร์ไฟล์ Adobe Illustrator"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Adobe Illustrator งานศิลปะ"

        # format loop 9
        - name: "เรนเดอร์ DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "เอกสาร Microsoft Word" 

        # format loop 10
        - name: "เรนเดอร์ TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "ไฟล์ข้อความธรรมดา" 

        # format loop 11
        - name: "เรนเดอร์ DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "ไฟล์รูปแบบการแลกเปลี่ยนการวาด"  
          
        # format loop 12
        - name: "แสดงผล VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "ไฟล์ vCard"  
              
        # format loop 13
        - name: "แสดงผล SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "กราฟิกแบบเวกเตอร์ที่ปรับขนาดได้" 
          
        # format loop 14
        - name: "แสดงผล HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "ไฟล์ภาษามาร์กอัปไฮเปอร์เท็กซ์" 
          
        # format loop 15
        - name: "เรนเดอร์ PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "ไฟล์รูปแบบเอกสารพกพา"
          
        # format loop 16
        - name: "เรนเดอร์ JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "รูปภาพ JPEG"
          
        # format loop 17
        - name: "เรนเดอร์ PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "กราฟิกเครือข่ายแบบพกพา" 
          
        # format loop 18
        - name: "แสดงผล EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "ข้อความอีเมล" 
          
        # format loop 19
        - name: "เรนเดอร์ RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "ไฟล์รูปแบบ Rich Text" 
          
        # format loop 20
        - name: "เรนเดอร์ ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "เอกสารข้อความ OpenDocument" 
          
        # format loop 21
        - name: "แสดงผล CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "ไฟล์ค่าที่คั่นด้วยเครื่องหมายจุลภาค" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
