---
############################# Static ##########################
layout: "family"
date: 2023-12-20T06:39:57
draft: false

product: "Viewer"
product_tag: "viewer"

############################# Head ############################
head_title: "API แสดงผลและดูเอกสาร | บน Premise API และบริการออนไลน์"
head_description: "เรนเดอร์และดูไฟล์ Word, PDF, Excel, Powerpoint หรือ Image ได้อย่างง่ายดายและฟรี"

############################# Header ##########################
title: "เรนเดอร์และดูเอกสารได้อย่างง่ายดาย"
description: |
  Viewer API อันทรงพลังเพื่อเรนเดอร์ไฟล์ต่าง ๆ เป็น PDF, HTML และรูปภาพ

  โหลดเอกสารจากแหล่งต่างๆ รวมถึงไฟล์ สตรีม URL เซิร์ฟเวอร์ FTP, Amazon S3, Azure Blob Storage และอื่นๆ

  สร้างหน้า HTML ที่ตอบสนอง ป้องกันไฟล์ PDF เอาท์พุต และจัดลำดับหน้าใหม่ หมุนหน้า แสดงผลบันทึกย่อและความคิดเห็นหากจำเป็น

############################# Platforms ############################
supported_platforms:
  enable: true  
  head_title: "เลือกแพลตฟอร์มของคุณ"
  title: "แพลตฟอร์มที่รองรับ"
  description: "ไลบรารี GroupDocs.Viewer รองรับระบบปฏิบัติการและเฟรมเวิร์กต่อไปนี้"
  details_link_title: "เรียนรู้เพิ่มเติม"
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
        - content: "รูปแบบไฟล์มากกว่า 180 รูปแบบ"
          rows: "1"
        # features loop
        - content: "แพ็คเกจ UI สำหรับ ASP.NET Core"
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
        - content: "รูปแบบไฟล์มากกว่า 180 รูปแบบ"
          rows: "1"
        # features loop
        - content:  "แพ็คเกจ UI สำหรับ Spring และ Dropwizard"
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
        - content:  "รูปแบบไฟล์มากกว่า 180 รูปแบบ"
          rows: "1"
        # features loop
        - content:  "แพ็คเกจ UI - เร็วๆ นี้"
          rows: "1" 
        # features loop
        - content:  "การสาธิต - เร็ว ๆ นี้"
          rows: "3" 

    # supported_platforms loop
    - title: "Python"
      description: "GroupDocs.Viewer for Python"
      color: "yellow"
      tag: "python-net"
      link: "/viewer/python-net/"
      features_link: "https://docs.groupdocs.com/viewer/python-net/system-requirements/"
      features:
        # features loop
        - content: "Python 3.9+  <br>  and .Net 6+"
          rows: "3"
        # features loop
        - content:  "Windows, Linux, macOS"
          rows: "1"
        # features loop
        - content:  "รูปแบบไฟล์มากกว่า 180 รูปแบบ"
          rows: "1"
        # features loop
        - content:  "แพ็คเกจ UI - เร็วๆ นี้"
          rows: "1" 
        # features loop
        - content:  "การสาธิต - เร็ว ๆ นี้"
          rows: "3" 

############################# Features ############################

features:
  enable: true
  title: "ชุดคุณลักษณะของ GroupDocs.Viewer"
  description: "API เพื่อเรนเดอร์ไฟล์ประเภทต่างๆ เช่น HTML, PDF, PNG และ JPEG ในแอปพลิเคชันเพื่อดูโดยไม่ต้องใช้ซอฟต์แวร์บุคคลที่สาม"

  items:
    # feature loop
    - icon: "view"
      title: "ดูเอกสารและรูปภาพ"
      content: "ดูเอกสารโดยแสดงผลเป็นไฟล์ HTML, PDF, PNG และ JPEG"

    # feature loop
    - icon: "password"
      title: "เปิดเอกสารที่มีการรักษาความปลอดภัย"
      content: "ระบุรหัสผ่านเพื่อเปิดเอกสารที่เข้ารหัส"

    # feature loop
    - icon: "load"
      title: "โหลดไฟล์ได้จากทุกที่"
      content: "โหลดเอกสารจากไฟล์ต่างๆ, URL, เซิร์ฟเวอร์ FTP, Amazon S3 และอื่นๆ"
    
    # feature loop
    - icon: "pages"
      title: "แสดงผลทั้งหมดหรือเฉพาะหน้า"
      content: "ระบุช่วงของหมายเลขหน้าที่จะแสดงผล"


############################# Code samples ############################
code_samples:
  enable: true
  title: "ตัวอย่างโค้ด GroupDocs.Viewer"
  description: "กรณีการใช้งานบางส่วนของการดำเนินการ GroupDocs.Viewer ทั่วไปใน C#, Java, TypeScript"
  items:
    # code sample loop
    - title: "วิธีเรนเดอร์ไฟล์ DOCX เป็น PDF"
      content: |
       เรนเดอร์เอกสาร DOCX เป็น PDF โดยไม่ต้องติดตั้ง Microsoft Word หรือซอฟต์แวร์อื่นๆ โหลดและดูไฟล์ DOCX ภายในแอปพลิเคชัน .NET ของคุณได้อย่างง่ายดาย ไม่ว่าจะเป็นแอปพลิเคชันบนเว็บหรือเดสก์ท็อป ต่อไปนี้คือตัวอย่างวิธีเรนเดอร์ไฟล์ DOCX เป็น PDF:
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // โหลดไฟล์ DOCX เพื่อเรนเดอร์
            using (Viewer viewer = new Viewer("sample.docx"))
            {
              // เรนเดอร์ DOCX เป็นไฟล์ PDF
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
            // โหลดไฟล์ DOCX เพื่อเรนเดอร์
            try (Viewer viewer = new Viewer("sample.docx")) {
                // เรนเดอร์ DOCX เป็นไฟล์ PDF
                PdfViewOptions viewOptions = new PdfViewOptions();
                viewer.view(viewOptions);
            }
            ```
        - language: "TypeScript"
          color: "green"
          content: |
            ```javascript {style=abap}  
            // โหลดไฟล์ DOCX เพื่อเรนเดอร์
            const viewer = new groupdocs.viewer.Viewer("sample.docx")
            
            // เรนเดอร์ DOCX เป็นไฟล์ PDF
            const viewOptions = groupdocs.viewer.PdfViewOptions(output.pdf)
            viewer.view(viewOptions)
            ```

        - language: "Python"
          color: "yellow"
          content: |
            ```python {style=abap} 
            import groupdocs.viewer as gv
            import groupdocs.viewer.options as gvo   
            // โหลดไฟล์ DOCX เพื่อเรนเดอร์
            with gv.Viewer("sample.docx") as viewer:
            
                // เรนเดอร์ DOCX เป็นไฟล์ PDF
                viewOptions = gvo.PdfViewOptions("output.pdf")
                viewer.view(viewOptions)
            ```

############################# Formats ############################
formats:
  enable: true
  title:  "รองรับไฟล์มากกว่า 180 รูปแบบ"
  description: "GroupDocs.Viewer รองรับการทำงานด้วย [รูปแบบไฟล์](https://docs.groupdocs.com/viewer/net/supported-document-formats/) ยอดนิยมที่สุด"


############################# Metrics ############################

metrics:
  enable: true
  title: "ตัวชี้วัดเชิงลึกและข้อมูลเชิงลึกทางสถิติ"
  description: "เจาะลึกรายละเอียดตัวเลขหลักของเรา โดยให้ตัวชี้วัดที่ครอบคลุมและข้อมูลเชิงลึกทางสถิติเกี่ยวกับความสำเร็จ ผลกระทบ และการเติบโตของเรา"

  items:
    # metrics loop
    - number: "180+"
      title: "รูปแบบที่รองรับ"
      content: "ดูรูปแบบไฟล์ได้มากกว่า 180 รูปแบบได้อย่างง่ายดาย รวมถึงเอกสาร รูปภาพ และแบบร่าง CAD โดยไม่ยุ่งยาก ทำลายอุปสรรคด้านความเข้ากันได้และเข้าถึงไฟล์ที่หลากหลายได้อย่างง่ายดายด้วยโซลูชันการรับชมที่ครอบคลุมของเรา"
    # metrics loop
    - number: "1.0M"
      title: "ดาวน์โหลด NuGet"
      content: "โซลูชันแพ็คเกจ NuGet ของเราได้กลายเป็นทรัพยากรที่เชื่อถือได้และนำไปใช้อย่างกว้างขวางในชุมชนนักพัฒนา โดยให้การบูรณาการที่ราบรื่นและฟังก์ชันการทำงานที่มีคุณค่าสำหรับโครงการนับไม่ถ้วน"

    # metrics loop
    - number: "10+"
      title: "ห้องสมุด"
      content: "ผลิตภัณฑ์ของเราประกอบด้วยไลบรารีมากกว่า 10 ไลบรารี ที่นำเสนอคุณลักษณะขั้นสูงเพื่อเพิ่มประสิทธิภาพการทำงาน ไลบรารีเหล่านี้ได้รับการออกแบบมาเพื่อตอบสนองความต้องการในการพัฒนาที่แตกต่างกันด้วยความสามารถที่เหนือชั้น"
    
    # metrics loop
    - number: "100+"
      title: "ลูกค้ามีความสุข"
      content: "ให้บริการแบรนด์ที่โดดเด่นที่สุดทั่วโลก ค้นพบว่าทำไมคนนับร้อยถึงชื่นชอบ GroupDocs.Viewer! สำรวจการนำทางที่ราบรื่น การทำงานร่วมกันที่สะดวกสบาย และความสะดวกในการใช้งานที่เหนือชั้น เข้าร่วมเดี๋ยวนี้!"


############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "ลูกค้าที่มีความสุขของเรา"
  description: "ห้องสมุด GroupDocs ได้รับการว่าจ้างจากแบรนด์ที่มีชื่อเสียงและโดดเด่นระดับโลกทั่วโลก"

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
  title: "พร้อมที่จะเริ่มต้นหรือยัง?"
  description: "ลองใช้คุณสมบัติ GroupDocs.Viewer ฟรีหรือขอใบอนุญาต"

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
        #  loop
    - title: "Python"
      link: "/viewer/python-net/"
      color: "yellow"

############################# Faq ############################

faq:
  enable: true
  title: "คำถามและข้อกังวลทั่วไป"
  description: "ค้นหาคำตอบสำหรับคำถามทั่วไปในส่วนคำถามที่พบบ่อยของเราเพื่อตอบข้อสงสัยและข้อกังวลของคุณอย่างรวดเร็ว"

  items:
    #  loop
    - question: "ฉันสามารถประเมินผลิตภัณฑ์ GroupDocs ก่อนซื้อได้หรือไม่"
      answer: |
        ใช่! ผลิตภัณฑ์ GroupDocs ทั้งหมดมีเวอร์ชันประเมินผลที่ปราศจากความเสี่ยง เราขอแนะนำให้นักพัฒนาดาวน์โหลดและลองใช้ API ของเราก่อนซื้อเพื่อให้แน่ใจว่าจะตอบสนองความต้องการของคุณได้ 100%
    #  loop
    - question: "GroupDocs สาธิตผลิตภัณฑ์หรือไม่"
      answer: |
        ไม่ เรามุ่งเน้นที่ API ของเราและทำให้ผลิตภัณฑ์มีฟังก์ชันการทำงานและมีเสถียรภาพมากที่สุดเท่าที่จะเป็นไปได้ เรานำเสนอการทดลองใช้งานได้เต็มรูปแบบและทดลองใช้ฟรีในรูปแบบของ [ใบอนุญาตชั่วคราว](https://purchase.groupdocs.com/temporary-license/) เพื่อให้คุณสามารถทดสอบผลิตภัณฑ์ได้ด้วยตัวเอง
    #  loop
    - question: "ฉันจะดาวน์โหลดผลิตภัณฑ์ได้ที่ไหน?"
      answer: |
        ผลิตภัณฑ์ทั้งหมดพร้อมให้ดาวน์โหลดจาก [เว็บไซต์](https://releases.groupdocs.com) เราไม่ส่งสำเนาทางกายภาพของซอฟต์แวร์ของเราทางไปรษณีย์    
    #  loop
    - question: "สิทธิ์การใช้งานของนักพัฒนา GroupDocs ต่อผู้ใช้หรือต่อผู้ใช้ที่ระบุชื่อ"
      answer: |
        สิทธิ์การใช้งาน GroupDocs Developer เป็นแบบต่อผู้ใช้ ไม่ใช่ต่อผู้ใช้ที่ระบุชื่อ เราเข้าใจดีว่าสมาชิกในทีมเขียนโค้ดอาจเปลี่ยนแปลงไปตามกาลเวลา และไม่ใช่เรื่องจริงที่จะต้องอัปเดตใบอนุญาตในแต่ละครั้งที่เกิดขึ้น
    #  loop
    - question: "เราจำเป็นต้องมีใบอนุญาตสำหรับนักพัฒนาที่ใช้งานอยู่เท่านั้นหรือไม่? ตัวอย่างเช่น เรามีทีมนักพัฒนาสองคนที่ทำงานเกี่ยวกับกะ A และทีมที่สองประกอบด้วยนักพัฒนาสองคนที่ทำงานเกี่ยวกับกะ B … ในสถานการณ์นี้ เราจำเป็นต้องมีใบอนุญาตสองหรือสี่ใบหรือไม่"
      answer: |
        นักพัฒนาทุกคนที่ทำงานในโปรเจ็กต์นี้จำเป็นต้องได้รับใบอนุญาต ในสถานการณ์นี้ GroupDocs มองว่าทีมของคุณมีสมาชิกสี่คน (แม้ว่าจะทำงานคนละเวลาก็ตาม)

############################# Cloud ############################

cloud_links:
  enable: true
  title: "GroupDocs.Viewer API แบบโค้ดต่ำ"
  description: "เร่งความเร็วในการดูเอกสารหรือรูปภาพในแอปพลิเคชันทุกประเภทด้วย REST API บนคลาวด์ของเรา"

  items:
    #  loop
    - icon: "groupdocs_viewer-for-curl"
      title: "GroupDocs.Viewer Cloud for cURL"
      link: "https://products.groupdocs.cloud/viewer/curl"
      content: "ใช้ API โปรแกรมดูเอกสาร cURL RESTful เพื่อเรนเดอร์และแสดง Microsoft Office, PDF และรูปแบบไฟล์มาตรฐานอื่นๆ ในแอปพลิเคชันของคุณอย่างมีประสิทธิภาพ"

    #  loop
    - icon: "groupdocs_viewer-for-net"
      title: "GroupDocs.Viewer Cloud for .NET"
      link: "https://products.groupdocs.cloud/viewer/net"
      content: "ปรับปรุงความสามารถในการดูเอกสารในแอปพลิเคชัน .NET ด้วย Cloud SDK สำหรับ .NET ดูเอกสารได้อย่างราบรื่นในรูปแบบ HTML, PDF หรือรูปภาพ"
    #  loop
    - icon: "groupdocs_viewer-for-java"
      title: "GroupDocs.Viewer Cloud for Java"
      link: "https://products.groupdocs.cloud/viewer/java"
      content: "ผสานรวมความสามารถในการเรนเดอร์เอกสารขั้นสูงเข้ากับแอปพลิเคชัน Java ของคุณโดยใช้ Document Viewer SDK ที่สร้างขึ้นตามวัตถุประสงค์เฉพาะสำหรับ Java"

############################# Apps ############################

app_links:
  enable: true
  title: "แอพ GroupDocs.Viewer NoCode"
  description: "แอปพลิเคชันออนไลน์ที่ให้คุณดูรูปแบบไฟล์ยอดนิยมมากกว่า 180 รูปแบบในเบราว์เซอร์"

  items:
    #  loop
    - icon: "groupdocs_viewer-app"
      title: "GroupDocs.Viewer Total"
      link: "https://products.groupdocs.app/viewer/total"
      content: "สำรวจแอปพลิเคชันออนไลน์ฟรีเพื่อดูรูปแบบไฟล์มากกว่า 180 รูปแบบได้โดยตรงจากเว็บเบราว์เซอร์ที่คุณต้องการ"

    #  loop
    - icon: "groupdocs_words-app"
      title:  "GroupDocs.Viewer DOCX"
      link: "https://products.groupdocs.app/viewer/docx"
      content: "เครื่องมือบนเว็บสำหรับการดูไฟล์ Microsoft Word บนอุปกรณ์ต่างๆ ได้อย่างง่ายดาย"

    #  loop
    - icon: "groupdocs_pdf-app"
      title:  "GroupDocs.Viewer PDF"
      link: "https://products.groupdocs.app/viewer/pdf"
      content: "เปิดและดูไฟล์ PDF ออนไลน์ด้วยโปรแกรมดู PDF ฟรี"
    

---