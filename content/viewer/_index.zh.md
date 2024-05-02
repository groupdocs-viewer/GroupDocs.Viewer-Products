---
############################# Static ##########################
layout: "family"
date: 2023-12-20T06:39:57
draft: false

product: "Viewer"
product_tag: "viewer"

############################# Head ############################
head_title: "渲染和查看文档 API |本地API和在线服务"
head_description: "轻松免费地渲染和查看 Word、PDF、Excel、Powerpoint 或图像文件"

############################# Header ##########################
title: "轻松渲染和查看文档"
description: |
  强大的查看器 API 可将不同文件渲染为 PDF、HTML 和图像。

  从各种来源加载文档，包括文件、流、URL、FTP 服务器、Amazon S3、Azure Blob 存储等。

  生成响应式 HTML 页面、保护输出 PDF 文件并重新排序其页面、旋转页面、渲染注释和注释（如果需要）。

############################# Platforms ############################
supported_platforms:
  enable: true  
  head_title: "选择您的平台"
  title: "支持的平台"
  description: "GroupDocs.Viewer 库支持以下操作系统和框架"
  details_link_title: "了解更多"
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
        - content: "180 多种文件格式"
          rows: "1"
        # features loop
        - content: "ASP.NET Core 的 UI 包"
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
        - content: "180 多种文件格式"
          rows: "1"
        # features loop
        - content:  "Spring 和 Dropwizard 的 UI 包"
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
        - content:  "180 多种文件格式"
          rows: "1"
        # features loop
        - content:  "UI 包 - 即将推出"
          rows: "1" 
        # features loop
        - content:  "演示 - 即将推出"
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
        - content:  "180 多种文件格式"
          rows: "1"
        # features loop
        - content:  "UI 包 - 即将推出"
          rows: "1" 
        # features loop
        - content:  "演示 - 即将推出"
          rows: "3" 

############################# Features ############################

features:
  enable: true
  title: "GroupDocs.Viewer 的功能集"
  description: "API 可在应用程序中将不同类型的文件呈现为 HTML、PDF、PNG 和 JPEG，以便无需第三方软件即可查看它们。"

  items:
    # feature loop
    - icon: "view"
      title: "查看文档和图像"
      content: "通过将文档呈现为 HTML、PDF、PNG 和 JPEG 文件来查看文档。"

    # feature loop
    - icon: "password"
      title: "打开受保护的文档"
      content: "指定打开加密文档的密码。"

    # feature loop
    - icon: "load"
      title: "从任何地方加载文件"
      content: "从各种文件、URL、FTP 服务器、Amazon S3 等加载文档。"
    
    # feature loop
    - icon: "pages"
      title: "渲染所有或特定页面"
      content: "指定要呈现的页码范围。"


############################# Code samples ############################
code_samples:
  enable: true
  title: "GroupDocs.Viewer 代码示例"
  description: "C#、Java、TypeScript 中典型 GroupDocs.Viewer 操作的一些用例"
  items:
    # code sample loop
    - title: "如何将 DOCX 文件渲染为 PDF"
      content: |
       将 DOCX 文档渲染为 PDF，无需安装 Microsoft Word 或其他软件。在 .NET 应用程序中轻松加载和查看 DOCX 文件，无论是 Web 应用程序还是桌面应用程序。以下是如何将 DOCX 文件呈现为 PDF 的示例：
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // 加载 DOCX 文件进行渲染
            using (Viewer viewer = new Viewer("sample.docx"))
            {
              // 将 DOCX 渲染为 PDF 文件
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
            // 加载 DOCX 文件进行渲染
            try (Viewer viewer = new Viewer("sample.docx")) {
                // 将 DOCX 渲染为 PDF 文件
                PdfViewOptions viewOptions = new PdfViewOptions();
                viewer.view(viewOptions);
            }
            ```
        - language: "TypeScript"
          color: "green"
          content: |
            ```javascript {style=abap}  
            // 加载 DOCX 文件进行渲染
            const viewer = new groupdocs.viewer.Viewer("sample.docx")
            
            // 将 DOCX 渲染为 PDF 文件
            const viewOptions = groupdocs.viewer.PdfViewOptions(output.pdf)
            viewer.view(viewOptions)
            ```

        - language: "Python"
          color: "yellow"
          content: |
            ```python {style=abap} 
            import groupdocs.viewer as gv
            import groupdocs.viewer.options as gvo   
            // 加载 DOCX 文件进行渲染
            with gv.Viewer("sample.docx") as viewer:
            
            // 将 DOCX 渲染为 PDF 文件
            viewOptions = gvo.PdfViewOptions("output.pdf")
            viewer.view(viewOptions)
            ```

############################# Formats ############################
formats:
  enable: true
  title:  "支持 180 多种文件格式"
  description: "GroupDocs.Viewer支持最流行的的操作[文件格式](https://docs.groupdocs.com/viewer/net/supported-document-formats/)"


############################# Metrics ############################

metrics:
  enable: true
  title: "深入的指标和统计见解"
  description: "深入了解我们的关键数据的详细分类，提供有关我们的成就、影响和增长的全面指标和统计见解。"

  items:
    # metrics loop
    - number: "180+"
      title: "支持的格式"
      content: "轻松轻松查看 180 多种文件格式，包括文档、图像和 CAD 绘图。借助我们全面的查看解决方案，打破兼容性障碍并轻松访问各种文件。"
    # metrics loop
    - number: "1.0M"
      title: "NuGet 下载"
      content: "我们的 NuGet 包解决方案已成为开发人员社区中值得信赖且广泛采用的资源，为无数项目提供无缝集成和有价值的功能。"

    # metrics loop
    - number: "10+"
      title: "图书馆"
      content: "我们的产品包括 10 多个库，提供先进的功能来优化性能。这些库旨在以无与伦比的功能满足不同的开发需求。"
    
    # metrics loop
    - number: "100+"
      title: "快乐的顾客"
      content: "为全球最具标志性的品牌提供服务。了解为什么数百人喜欢 GroupDocs.Viewer！探索无缝导航、便捷协作和无与伦比的易用性。立即加入！"


############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "我们满意的客户"
  description: "GroupDocs 库被世界各地的全球知名和杰出品牌所采用。"

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
  title: "准备好开始了吗？"
  description: "免费试用 GroupDocs.Viewer 功能或申请许可证"

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
  title: "常见问题和疑虑"
  description: "在我们的常见问题解答部分查找常见问题的答案，以快速解决您的疑问和疑虑。"

  items:
    #  loop
    - question: "我可以在购买前评估 GroupDocs 产品吗？"
      answer: |
        是的！所有 GroupDocs 产品均提供无风险评估版本。我们强烈鼓励开发人员在购买前下载并试用我们的 API，以确保它们 100% 满足您的需求。
    #  loop
    - question: "GroupDocs 是否进行产品演示？"
      answer: |
        不，我们的重点是 API 并打造功能最强大、最稳定的产品。我们确实以[临时许可证](https://purchase.groupdocs.com/temporary-license/)的形式提供功能齐全的免费试用版，以便您可以亲自测试该产品。
    #  loop
    - question: "我在哪里可以下载该产品？"
      answer: |
        所有产品都可以从[网站](https://releases.groupdocs.com)下载。我们不会通过邮件发送我们软件的物理副本。    
    #  loop
    - question: "GroupDocs 开发人员许可证是按用户还是按指定用户授予的？"
      answer: |
        GroupDocs 开发人员许可证是按用户授予的，而不是按指定用户授予的。我们了解编码团队的成员可能会随着时间的推移而发生变化，并且每次发生时都必须更新许可是不切实际的。
    #  loop
    - question: "我们是否只需要为活跃的开发人员授予许可？例如，我们有一个由两名开发人员组成的团队从事 A 班次工作，而另一个由两名开发人员组成的团队从事 B 班次工作……在这种情况下，我们需要两个还是四个许可证？"
      answer: |
        所有从事该项目的开发人员都需要获得许可。在这种情况下，GroupDocs 会将您的团队视为有四名成员（即使他们在不同的时间工作）。

############################# Cloud ############################

cloud_links:
  enable: true
  title: "GroupDocs.Viewer 低代码 API"
  description: "使用我们基于云的 REST API 加速任何类型应用程序中的文档或图像查看"

  items:
    #  loop
    - icon: "groupdocs_viewer-for-curl"
      title: "GroupDocs.Viewer Cloud for cURL"
      link: "https://products.groupdocs.cloud/viewer/curl"
      content: "使用 cURL RESTful 文档查看器 API 在您的应用程序中高效地呈现和展示 Microsoft Office、PDF 和各种其他标准文件格式。"

    #  loop
    - icon: "groupdocs_viewer-for-net"
      title: "GroupDocs.Viewer Cloud for .NET"
      link: "https://products.groupdocs.cloud/viewer/net"
      content: "使用 Cloud SDK for .NET 增强 .NET 应用程序中的文档查看功能。无缝查看 HTML、PDF 或图像格式的文档。"
    #  loop
    - icon: "groupdocs_viewer-for-java"
      title: "GroupDocs.Viewer Cloud for Java"
      link: "https://products.groupdocs.cloud/viewer/java"
      content: "使用专门构建的 Java 文档查看器 SDK 将高级文档呈现功能集成到您的 Java 应用程序中。"

############################# Apps ############################

app_links:
  enable: true
  title: "GroupDocs.Viewer NoCode 应用程序"
  description: "在线应用程序允许您在浏览器中查看 180 多种流行的文件格式"

  items:
    #  loop
    - icon: "groupdocs_viewer-app"
      title: "GroupDocs.Viewer Total"
      link: "https://products.groupdocs.app/viewer/total"
      content: "探索免费的在线应用程序，直接从您喜欢的网络浏览器查看 180 多种文件格式。"

    #  loop
    - icon: "groupdocs_words-app"
      title:  "GroupDocs.Viewer DOCX"
      link: "https://products.groupdocs.app/viewer/docx"
      content: "基于 Web 的工具，用于在各种设备上轻松查看 Microsoft Word 文件。"

    #  loop
    - icon: "groupdocs_pdf-app"
      title:  "GroupDocs.Viewer PDF"
      link: "https://products.groupdocs.app/viewer/pdf"
      content: "使用免费的 PDF 查看器在线打开和查看 PDF 文件。"
    

---