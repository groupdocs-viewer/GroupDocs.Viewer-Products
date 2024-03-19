---
############################# Static ############################
layout: "format"
date: 2024-03-19T07:00:43
draft: false
lang: zh
product: "Viewer"
product_tag: "viewer"
platform: "Java"
platform_tag: "java"

############################# Head #############################
head_title: "Java OneNote Viewer API - 在 Java 应用程序中渲染和显示 OneNote"
head_description: "在 Java、J2EE、J2SE 应用程序中查看 OneNote 文件。支持以 HTML、PDF 或图像模式查看 180 多种文档和图像文件格式，并具有管理文档查看选项的高级功能。"

############################# Header ############################
title: "在 Java 中渲染和查看 OneNote" 
description: "适用于基于 Java、J2EE 和 J2SE 的应用程序的本机高性能 OneNote 文件查看器 API，支持多种附加功能来自定义输出文档格式的外观。" 
subtitle: "文档渲染解决方案" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "免费 Maven 下载"
      link: "https://releases.groupdocs.com/viewer/java/"



############################# About ############################
about:
    enable: true
    title: "关于 Java API 的 GroupDocs.Viewer"
    link: "/viewer/java/"
    link_title: "了解更多"
    picture: "about_viewer.svg" # 480 X 400
    content: |
      使用 GroupDocs.Viewer for Java API，使您的 Java 应用程序能够以 HTML、PDF 或图像模式显示超过 180 种文件格式，无需安装任何其他软件；例如 Microsoft Office、Apache Open Office、Adobe Acrobat Reader 等。开发人员可以在 Java 应用程序中轻松查看所有流行的图像和文档类型，包括 Microsoft Office、OpenDocument、HTML、PDF、Archive、图表、Photoshop、AutoCAD 和编程语言格式快速且最高质量的渲染。



############################# Steps ############################
steps:
    enable: true
    title: "在 Java 中渲染 OneNote 文件的步骤" 
    content: |
      使用 <a href='https://products.groupdocs.com/viewer/java/'>GroupDocs.Viewer</a>，您只需几个步骤即可将 OneNote 呈现为 HTML、JPEG、PNG 或 PDF。
      
      1. 添加 <a href='https://releases.groupdocs.com/viewer/java/'>GroupDocs.Viewer for Java</a> 作为项目的依赖项。 
      2. 创建 Viewer 类的实例并加载具有完整路径的 OneNote 文件。  
      3. 设置选项以将 OneNote 文件呈现为 HTML、PNG、JPEG 或 PDF 格式。 
      4. 渲染文件并检查当前目录中的输出。 
   
    code:
      platform: "java"
      copy_title: "复制"
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
        copy_tip: "点击复制"
        copy_done: "复制的"
      links:
        #  loop
        - title: "更多示例"
          link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Java"
        #  loop
        - title: "文档"
          link: "https://docs.groupdocs.com/viewer/java/"
          
      content: |
        ```java {style=abap}

        // 设置输入 OneNote 文件
        String filePath = "input.one";

        // 实例化 GroupDocs.Viewer
        try (Viewer viewer = new Viewer(filePath))
        {
            // 设置视图选项
            HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                
            // 将 OneNote 文件渲染为带有嵌入资源的 HTML
            viewer.view(viewOptions);
        }

        ```
            

############################# Actions ############################

actions:
  enable: true
  title: "准备好开始了吗？"
  description: "免费试用 GroupDocs.Viewer 功能或申请许可证"
  items:
    #  loop
    - title: "Maven下载"
      link: "https://releases.groupdocs.com/viewer/java/"
      color: "red"
        #  loop
    - title: "许可"
      link: "https://purchase.groupdocs.com/pricing/viewer/java/"
      color: "light"



############################# More Formats #####################
more_formats:
    enable: true
    title: "使用 Java 渲染其他文件格式"
    exclude: "OneNote"
    description: "适用于 Java 的多格式文档和图像查看器 API。无需任何外部查看器即可查看以下一些流行的文件格式。"
    items: 
        # format loop 1
        - name: "渲染 DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Open XML Document" 

        # format loop 2
        - name: "渲染 CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "CorelDRAW File" 

        # format loop 3
        - name: "渲染 PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint Open XML Presentation" 

        # format loop 4
        - name: "渲染 XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet" 

        # format loop 5
        - name: "渲染 DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "AutoCAD Drawing"

        # format loop 6
        - name: "渲染 XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "XML File"

        # format loop 7
        - name: "渲染 PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Adobe Photoshop Document"

        # format loop 8
        - name: "渲染 AI"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Adobe Illustrator Artwork"

        # format loop 9
        - name: "渲染 DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Microsoft Word Document" 

        # format loop 10
        - name: "渲染 TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Plain Text File" 

        # format loop 11
        - name: "渲染 DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Drawing Exchange Format File"  
          
        # format loop 12
        - name: "渲染 VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "vCard File"  
              
        # format loop 13
        - name: "渲染 SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Scalable Vector Graphic" 
          
        # format loop 14
        - name: "渲染 HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "渲染 PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Portable Document Format File"
          
        # format loop 16
        - name: "渲染 JPEG"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "JPEG Image"
          
        # format loop 17
        - name: "渲染 PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Portable Network Graphic" 
          
        # format loop 18
        - name: "渲染EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "E-Mail Message" 
          
        # format loop 19
        - name: "渲染 RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Rich Text Format File" 
          
        # format loop 20
        - name: "渲染 ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "OpenDocument Text Document" 
          
        # format loop 21
        - name: "渲染 CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Comma-Separated Values File" 


---
