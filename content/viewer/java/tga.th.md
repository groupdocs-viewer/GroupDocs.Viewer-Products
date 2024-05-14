---
############################# Static ############################
layout: "format"
date: 2024-05-14T11:12:44
draft: false
lang: th
product: "Viewer"
product_tag: "viewer"
platform: "Java"
platform_tag: "java"

############################# Head #############################
head_title: "Java TGA Viewer API - เรนเดอร์และแสดง TGA ในแอป Java"
head_description: "ดูไฟล์ TGA ในแอปพลิเคชัน Java, J2EE, J2SE รองรับการดูเอกสารและไฟล์รูปภาพมากกว่า 180 รูปแบบในโหมด HTML, PDF หรือรูปภาพพร้อมคุณสมบัติขั้นสูงเพื่อจัดการตัวเลือกการดูเอกสาร"

############################# Header ############################
title: "เรนเดอร์และดู TGA ใน Java" 
description: "API โปรแกรมดูไฟล์ TGA แบบเนทีฟและประสิทธิภาพสูงสำหรับแอปพลิเคชันที่ใช้ Java, J2EE และ J2SE ซึ่งรองรับคุณสมบัติเพิ่มเติมที่หลากหลายเพื่อปรับแต่งลักษณะที่ปรากฏของรูปแบบเอกสารเอาต์พุต" 
subtitle: "โซลูชันการแสดงผลเอกสาร" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "ดาวน์โหลดฟรี Maven"
      link: "https://releases.groupdocs.com/viewer/java/"



############################# About ############################
about:
    enable: true
    title: "เกี่ยวกับ GroupDocs.Viewer สำหรับ Java API"
    link: "/viewer/java/"
    link_title: "เรียนรู้เพิ่มเติม"
    picture: "about_viewer.svg" # 480 X 400
    content: |
      ช่วยให้แอปพลิเคชัน Java ของคุณแสดงรูปแบบไฟล์ได้มากกว่า 180 รูปแบบในโหมด HTML, PDF หรือรูปภาพโดยใช้ GroupDocs.Viewer สำหรับ Java API โดยไม่ต้องติดตั้งซอฟต์แวร์เพิ่มเติม เช่น Microsoft Office, Apache Open Office, Adobe Acrobat Reader เป็นต้น นักพัฒนาสามารถดูรูปภาพและเอกสารยอดนิยมทุกประเภทได้อย่างง่ายดาย รวมถึง Microsoft Office, OpenDocument, HTML, PDF, Archive, Diagrams, Photoshop, AutoCAD และรูปแบบภาษาการเขียนโปรแกรมภายในแอปพลิเคชัน Java ด้วย การเรนเดอร์ที่รวดเร็วและมีคุณภาพสูงสุด



############################# Steps ############################
steps:
    enable: true
    title: "ขั้นตอนในการแสดงผลไฟล์ TGA ใน Java" 
    content: |
      ด้วย <a href='https://products.groupdocs.com/viewer/java/'>GroupDocs.Viewer</a> คุณสามารถแสดงผล TGA เป็น HTML, JPEG, PNG หรือ PDF ได้ในไม่กี่ขั้นตอน
      
      1. เพิ่ม <a href='https://releases.groupdocs.com/viewer/java/'>GroupDocs.Viewer for Java</a> เป็นข้อมูลอ้างอิงสำหรับโปรเจ็กต์ของคุณ 
      2. สร้างอินสแตนซ์ของคลาส Viewer และโหลดไฟล์ TGA ด้วยเส้นทางแบบเต็ม  
      3. ตั้งค่าตัวเลือกเพื่อแสดงไฟล์ TGA เป็นรูปแบบ HTML, PNG, JPEG หรือ PDF 
      4. เรนเดอร์ไฟล์และตรวจสอบเอาต์พุตในไดเร็กทอรีปัจจุบัน 
   
    code:
      platform: "java"
      copy_title: "สำเนา"
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
        copy_tip: "คลิกเพื่อคัดลอก"
        copy_done: "คัดลอก"
      links:
        #  loop
        - title: "ตัวอย่างเพิ่มเติม"
          link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Java"
        #  loop
        - title: "เอกสารประกอบ"
          link: "https://docs.groupdocs.com/viewer/java/"
          
      content: |
        ```java {style=abap}

        // ตั้งค่าไฟล์อินพุต TGA
        String filePath = "input.tga";

        // สร้างอินสแตนซ์ GroupDocs.Viewer
        try (Viewer viewer = new Viewer(filePath))
        {
            // ตั้งค่าตัวเลือกมุมมอง
            HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                
            // เรนเดอร์ไฟล์ TGA เป็น HTML ด้วยทรัพยากรที่ฝังอยู่
            viewer.view(viewOptions);
        }

        ```
            

############################# Actions ############################

actions:
  enable: true
  title: "พร้อมที่จะเริ่มต้นหรือยัง?"
  description: "ลองใช้คุณสมบัติ GroupDocs.Viewer ฟรีหรือขอใบอนุญาต"
  items:
    #  loop
    - title: "ดาวน์โหลด มาเวน"
      link: "https://releases.groupdocs.com/viewer/java/"
      color: "red"
        #  loop
    - title: "การออกใบอนุญาต"
      link: "https://purchase.groupdocs.com/pricing/viewer/java/"
      color: "light"



############################# More Formats #####################
more_formats:
    enable: true
    title: "เรนเดอร์ไฟล์รูปแบบอื่นโดยใช้ Java"
    exclude: "TGA"
    description: "API โปรแกรมดูเอกสารและรูปภาพหลายรูปแบบสำหรับ Java ดูรูปแบบไฟล์ยอดนิยมบางรูปแบบด้านล่างโดยไม่ต้องใช้โปรแกรมดูจากภายนอก"
    items: 
        # format loop 1
        - name: "เรนเดอร์ DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Open XML Document" 

        # format loop 2
        - name: "เรนเดอร์ CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "CorelDRAW File" 

        # format loop 3
        - name: "เรนเดอร์ PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint Open XML Presentation" 

        # format loop 4
        - name: "เรนเดอร์ XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet" 

        # format loop 5
        - name: "เรนเดอร์ DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "AutoCAD Drawing"

        # format loop 6
        - name: "เรนเดอร์ XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "XML File"

        # format loop 7
        - name: "เรนเดอร์ PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Adobe Photoshop Document"

        # format loop 8
        - name: "เรนเดอร์ AI"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Adobe Illustrator Artwork"

        # format loop 9
        - name: "เรนเดอร์ DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Microsoft Word Document" 

        # format loop 10
        - name: "เรนเดอร์ TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Plain Text File" 

        # format loop 11
        - name: "เรนเดอร์ DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Drawing Exchange Format File"  
          
        # format loop 12
        - name: "เรนเดอร์ VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "vCard File"  
              
        # format loop 13
        - name: "เรนเดอร์ SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Scalable Vector Graphic" 
          
        # format loop 14
        - name: "เรนเดอร์ HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "เรนเดอร์ PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Portable Document Format File"
          
        # format loop 16
        - name: "เรนเดอร์ JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "JPEG Image"
          
        # format loop 17
        - name: "เรนเดอร์ PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Portable Network Graphic" 
          
        # format loop 18
        - name: "เรนเดอร์ EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "E-Mail Message" 
          
        # format loop 19
        - name: "เรนเดอร์ RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Rich Text Format File" 
          
        # format loop 20
        - name: "เรนเดอร์ ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "OpenDocument Text Document" 
          
        # format loop 21
        - name: "แสดงผล CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Comma-Separated Values File" 


---
