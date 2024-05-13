---
############################# Static ############################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: th
product: "Viewer"
product_tag: "viewer"
platform: "Python via .NET"
platform_tag: "python-net"

############################# Drop-down ############################
supported_platforms:
  items:
    # supported_platforms loop
    - title: ".NET"
      tag: "net"
    # supported_platforms loop
    - title: "Java"
      tag: "java"
    # supported_platforms loop
    - title: "Node.js"
      tag: "nodejs-java" 
    # supported_platforms loop
    - title: "Python"
      tag: "python-net" 


############################# Head ############################
head_title: "Python API สำหรับการดูเอกสาร (PDF, Word, Excel, HTML, รูปภาพ และอีเมล)"
head_description: "Python API สำหรับการเรนเดอร์ไฟล์และการดูเอกสาร เพิ่มโปรแกรมดู PDF, โปรแกรมดู Word, โปรแกรมดู Excel, โปรแกรมดูรูปภาพ, โปรแกรมดู HTML และโปรแกรมดูอีเมล ลงในแอปพลิเคชัน Python"

############################# Header ############################
title: "Python API ที่ทรงพลังสำหรับการเรนเดอร์เอกสารที่ปรับให้เหมาะสม"
description: "เรนเดอร์และแสดงผลเอกสารมากกว่า 180 รูปแบบ (PDF, HTML, รูปภาพ) ด้วย API ที่ทรงพลังและตัวเลือกการกำหนดค่าที่หลากหลายสำหรับการพัฒนาแอปพลิเคชัน Python"
words:
  for: "for"

actions:
  main: "ดาวน์โหลดฟรีจาก PyPI"
  main_link: "https://pypi.org/project/groupdocs-viewer/"
  alt: "การออกใบอนุญาต"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/python-net"
  title: "พร้อมที่จะเริ่มต้นหรือยัง?"
  description: "ลองใช้คุณสมบัติ GroupDocs.Viewer ฟรีหรือขอใบอนุญาต"

release:
  title: "เวอร์ชัน {0} เปิดตัวแล้ว"
  notes: "ดูว่ามีอะไรใหม่"
  downloads: "ดาวน์โหลด"
  link: "https://releases.groupdocs.com/viewer/python-net/release-notes/latest/"

code:
  title: "การเรนเดอร์ไฟล์ PDF ใน Python"
  more: "ตัวอย่างเพิ่มเติม"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Python-via-.NET"
  install: "pip install GroupDocs.Viewer"
  content: |
    ```python {style=abap}
    import groupdocs.viewer as gv
    import groupdocs.viewer.options as gvo
    hvo = gvo.HtmlViewOptions  
  
    // ตั้งค่าตัวเลือกเอาต์พุต HTML (หนึ่งไฟล์ต่อหน้า)
    with gv.Viewer("resume.docx") as viewer:
      // สร้างอินสแตนซ์ของโปรแกรมดู
      opts = hvo.for_embedded_resources("page_{0}.html")

      // การเรนเดอร์ PDF เป็น HTML ด้วยทรัพยากรที่ฝังอยู่
      viewer.view(opts)
    ```
############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Viewer ภาพรวม"
  description: "API สำหรับการเรนเดอร์, การแสดงผล และการแปลงเอกสาร, สไลด์, ไดอะแกรม และเอกสารประเภทอื่นๆ อีกมากมายในแอปพลิเคชัน Python"
  features:
    # feature loop
    - title: "ดูเอกสารอย่างมีประสิทธิภาพและเชื่อถือได้"
      content: "ด้วย GroupDocs.Viewer API คุณสามารถเรนเดอร์เอกสารทุกรูปแบบที่รองรับเป็น HTML, JPEG, PNG และ PDF ได้อย่างมีประสิทธิภาพด้วยตัวเลือกที่ยืดหยุ่นและทรงพลัง ช่วยรักษาความสมบูรณ์ของเนื้อหาและโครงสร้างของเอกสาร GroupDocs.Viewer สำหรับ Python ทำงานบนแพลตฟอร์ม Windows และ Linux"

    # feature loop
    - title: "รองรับรูปแบบไฟล์และเอกสารส่วนใหญ่ที่นิยมใช้"
      content: "รองรับการเรนเดอร์รูปแบบไฟล์และเอกสารมากกว่า 180 รูปแบบที่นิยมใช้มากที่สุด รวมถึง Word, Excel, PDF, PowerPoint, กลุ่มรูปแบบ OpenDocument, ไฟล์เก็บถาวร, รูปภาพแบบแรสเตอร์และเวกเตอร์, อีบุ๊ก, ภาษาโปรแกรมและมาร์กอัป และไฟล์ประเภทอื่นๆ อีกมากมาย รวมถึงไฟล์ที่เข้ารหัสด้วยการป้องกันด้วยรหัสผ่าน"

    # feature loop
    - title: "เอาต์พุตที่กำหนดเองได้"
      content: "GroupDocs.Viewer ไม่เพียงแต่ช่วยให้คุณเรนเดอร์เอกสารเท่านั้น แต่ยังควบคุมส่วนต่างๆ ของเอกสารที่ต้องการเรนเดอร์หรือไม่ ควบคุมวิธีการเรนเดอร์ และนำการแปลงต่างๆ ไปใช้กับเอาต์พุตที่เรนเดอร์ได้อย่างแม่นยำ"

############################# Platforms ############################
platforms:
  enable: true
  title: "ไม่ขึ้นกับแพลตฟอร์ม"
  description: "GroupDocs.Viewer สำหรับ Python รองรับระบบปฏิบัติการ, กรอบงาน และตัวจัดการแพ็กเกจต่อไปนี้"
  items:
    # platform loop
    - title: "Amazon"
      image: "amazon"
    # platform loop
    - title: "Docker"
      image: "docker"
    # platform loop
    - title: "Azure"
      image: "azure"
    # platform loop
    - title: "Eclipse"
      image: "eclipse"
    # platform loop
    - title: "IntelliJ"
      image: "intellij"
    # platform loop
    - title: "Windows"
      image: "windows"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "PyPI"
      image: "pypi"

############################# File formats ############################
formats:
  enable: true
  title: "รูปแบบไฟล์ที่รองรับ"
  description: |
    GroupDocs.Viewer for Python (via .NET) รองรับการดำเนินการกับรูปแบบไฟล์ต่อไปนี้: [รูปแบบไฟล์ที่รองรับ](https://docs.groupdocs.com/viewer/python-net/supported-document-formats/)
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office, OpenDocument และรูปแบบข้อความ
        * **Word:** DOC, DOCX, DOCM, DOT, DOTX, DOTM, RTF, TXT
        * **Excel:** XLS, XLSX, XLSM, XLSB, XLTM, XLT, XLTM, XLTX
        * **PowerPoint:** PPT, PPTX, PPS, PPSX, PPSM, POT, POTM, POTX, PPTM        
        * **Project:** MPP, MPT, MPX
        * **Outlook:** MSG, EML, EMLX, PST, OST
        * **OneNote:** ONE
        * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG
        * **Fixed Page Layout:** PDF, TEX, XPS, OXPS
        * **e-Books:** EPUB, MOBI, DjVu
        * **Delimiter-Separated Values:** CSV, TSV
    # group loop
    - color: "blue"
      content: |
        ### รูปภาพ กราฟิก และไดอะแกรม
        * **ภาพแรสเตอร์:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
        * **Windows Icon:** ICO
        * **Scalable Vector Graphics:** SVG, CDR, CMX, IGS, SVGZ        
        * **Adobe Photoshop:** PSD, PSB        
        * **Stereo Lithography (3D Printing):** STL        
        * **Medical Imaging:** DICOM
        * **Plotter Documents:** PLT, HPG
        * **Autodesk Design Web Formats:** DWF, DWG
        * **AutoCAD Drawing:** DWT, IFC, STL, CF2        
      # group loop
    - color: "red"
      content: |
        ### อื่น        
        * **เว็บ:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **หอจดหมายเหตุ:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **อื่น:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "คุณสมบัติ GroupDocs.Viewer"
  description: "เรนเดอร์ แสดง และแปลงเอกสาร PDF และ Office ได้อย่างราบรื่น"

  items:
    # feature loop
    - icon: "viewhtml"
      title: "ดูเอกสารในรูปแบบ HTML"
      content: "แปลงเอกสารทุกประเภทให้เป็นเอกสาร HTML ด้วย CSS และ SVG ซึ่งสามารถแสดงในเว็บเบราว์เซอร์สมัยใหม่"

    # feature loop
    - icon: "rasterize"
      title: "แปลงเอกสารเป็นแรสเตอร์"
      content: "แรสเตอร์รูปแบบเอกสารที่รองรับให้เป็นภาพแรสเตอร์ พร้อมรูปแบบภาพที่ปรับได้และคุณภาพการบีบอัด"

    # feature loop
    - icon: "sourcecode"
      title: "เรนเดอร์และไฮไลต์โค้ดโปรแกรม"
      content: "รองรับการเขียนโปรแกรม สคริปต์ และภาษามาร์กอัปยอดนิยมทั้งหมด พร้อมความสามารถในการแยกวิเคราะห์และเน้นไวยากรณ์ของภาษาเหล่านั้น"

    # feature loop
    - icon: "convertpdf"
      title: "แปลงเป็น PDF"
      content: "เอกสารในรูปแบบที่รองรับสามารถแปลงและบันทึกเป็น PDF ได้อย่างง่ายดายพร้อมตัวเลือกที่ปรับได้"

    # feature loop
    - icon: "transform"
      title: "ใช้การแปลง"
      content: "เอกสารเอาต์พุตสามารถแปลงได้ในระหว่างการเรนเดอร์ - สามารถหมุนหน้าและ/หรือจัดเรียงหน้าใหม่ได้ และอาจวางลายน้ำข้อความไว้บนหน้าเหล่านั้นได้"

    # feature loop
    - icon: "adjustment"
      title: "การปรับเอาต์พุต HTML"
      content: "เอกสาร HTML เอาท์พุตที่สร้างโดย GroupDocs.Viewer สามารถปรับแต่งได้อย่างละเอียด: อนุญาตให้บันทึกลงในสตรีมหรือไฟล์ด้วยทรัพยากรภายนอกหรือแบบฝัง การเรียกกลับ และอื่นๆ"

    # feature loop
    - icon: "complex"
      title: "รองรับโครงสร้างเอกสารที่ซับซ้อน"
      content: "GroupDocs.Viewer รองรับไม่เพียงแต่เอกสารเดียวเท่านั้น แต่ยังรวมถึงไฟล์ต่างๆ ที่ภายในประกอบด้วยรายการหรือโครงสร้างลำดับชั้นของเอกสาร เช่น ข้อความอีเมลพร้อมไฟล์แนบ ไฟล์ ZIP ที่มีไฟล์ภายในภายในโฟลเดอร์ รูปภาพ TIFF แบบหลายหน้า และอื่นๆ"

    # feature loop
    - icon: "optimization"
      title: "ตัวเลือกการเพิ่มประสิทธิภาพ"
      content: "GroupDocs.Viewer มีระบบย่อยแคชที่ปรับได้ ซึ่งสามารถเร่งเวลาการโหลดให้เร็วขึ้นได้โดยใช้เอกสารเวอร์ชันแคช นอกจากนี้ ชุดของตัวเลือกที่แตกต่างกันสำหรับรูปแบบที่แตกต่างกันยังช่วยแยกส่วนหรือลักษณะที่ไม่จำเป็นของเอกสารออกจากการเรนเดอร์ (แบบอักษร แผ่นงานที่ซ่อน ไฟล์แนบในอีเมล) เพื่อเพิ่มประสิทธิภาพโดยรวม"

    # feature loop
    - icon: "passwordprotected"
      title: "รองรับเอกสารที่มีการป้องกันด้วยรหัสผ่าน"
      content: "GroupDocs.Viewer อนุญาตให้เปิดเอกสารที่เข้ารหัสประเภทต่างๆ: PDF, WordProcessing, Spreadsheet, Presentation และอื่นๆ โดยระบุรหัสผ่านในตัวเลือกการโหลด"

############################# Code samples ############################
code_samples:
  enable: true
  title: "ตัวอย่างโค้ด"
  description: "บางกรณีการใช้งานทั่วไปของการดำเนินการ GroupDocs.Viewer สำหรับ Python ผ่าน .NET"
  items:
    # code sample loop
    - title: "แปลง DOCX เป็น HTML"
      content: |
        คุณสมบัติของคลาส [HtmlViewOptions](placeholder) ช่วยให้คุณควบคุมกระบวนการแปลง สำหรับข้อมูลเพิ่มเติม โปรดดู [ที่นี่](https://docs.groupdocs.com/viewer/python-net/rendering-to-html/) ตัวอย่างเช่น คุณสามารถฝังทรัพยากรภายนอกทั้งหมดลงในไฟล์ HTML เอาต์พุต, ย่อขนาดไฟล์เอาต์พุต และปรับให้เหมาะสำหรับการพิมพ์
        {{< landing/code title="Python">}}
        ```python {style=abap}
        import groupdocs.viewer as gv
        import groupdocs.viewer.options as gvo 

        // สร้างอินสแตนซ์ของโปรแกรมดู (already translated)
        with gv.Viewer("resume.docx") as viewer:
          // ตั้งค่าตัวเลือกเอาต์พุต HTML (หนึ่งไฟล์ต่อหน้า) (already translated)
          viewOptions = gvo.HtmlViewOptions.for_embedded_resources("page_{0}.html")
          // การเรนเดอร์ PDF เป็น HTML ด้วยทรัพยากรที่ฝังอยู่ (already translated)
          viewer.view(viewOptions)
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "ส่งออก PPTX เป็น PDF"
      content: |
        สร้างอินสแตนซ์ของคลาส [PdfViewOptions](placeholder) และส่งผ่านไปยังเมธอด `Viewer.view` เพื่อแปลงไฟล์ PowerPoint PPTX เป็น PDF คุณสมบัติของคลาส [PdfViewOptions](placeholder) ช่วยให้คุณควบคุมกระบวนการแปลง ตัวอย่างเช่น คุณสามารถป้องกันไฟล์ PDF เอาต์พุต, เปลี่ยนลำดับหน้าของไฟล์ หรือระบุคุณภาพของรูปภาพในเอกสาร สำหรับข้อมูลเพิ่มเติม โปรดดู [ส่วนต่อไปนี้ของเอกสาร](https://docs.groupdocs.com/viewer/python-net/rendering-to-pdf/)
        {{< landing/code title="Python">}}
        ```python {style=abap}
        import groupdocs.viewer as gv
        import groupdocs.viewer.options as gvo  

        // สร้างอินสแตนซ์ของโปรแกรมดู (already translated)
        with gv.Viewer("presentation.pptx") as viewer:
          // ตั้งค่าตัวเลือกเอาต์พุต PDF (Set output PDF options)
          viewOptions = gvo.PdfViewOptions("presentation.pdf")
          // ส่งออก PPTX เป็น PDF (Export PPTX to PDF) (already translated)
          viewer.view(viewOptions)
        ```
        {{< /landing/code >}}
############################# Reviews ############################
# reviews:
# enable: true
# title: "บทวิจารณ์ผลิตภัณฑ์ GroupDocs"
# description: "อย่าเพิ่งเชื่อคำพูดของเรา ดูว่านักพัฒนารายอื่นพูดถึง API ของเราอย่างไร"

# items:
#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "บริการที่เป็นเลิศและผลิตภัณฑ์ที่เป็นเลิศ พวกเขามีประโยชน์และตอบสนองอย่างมากในระหว่างกระบวนการใช้งาน GroupDocs.Viewer สำหรับ .NET ไม่สามารถแนะนำได้มากพอ"
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "หลังจากใช้งานและใช้งาน GroupDocs.Viewer สำหรับ .NET ในโครงการแล้ว ดูเหมือนว่าจะทำงานได้ดีมาก ฉันได้ทดสอบกับเอกสารจำนวนมากและจนถึงตอนนี้ก็ดีมาก ทุกสิ่งที่ฉันใส่ลงไปนั้นเรนเดอร์ได้อย่างสวยงามและดูดีไม่แพ้กันในโปรแกรมดู PDF หรือ MS Word"
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---
