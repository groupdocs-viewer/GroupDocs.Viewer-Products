---
############################# Static ############################
layout: "format"
date: 2024-03-19T07:00:50
draft: false
lang: ja
product: "Viewer"
product_tag: "viewer"
platform: "Java"
platform_tag: "java"

############################# Head #############################
head_title: "Java XLTX ビューア API - Java アプリで XLTX をレンダリングおよび表示します"
head_description: "Java、J2EE、J2SE アプリケーションの XLTX ファイルを表示します。ドキュメント表示オプションを管理する高度な機能を備えた HTML、PDF、またはイメージ モードでの 180 以上のドキュメントおよび画像ファイル形式の表示をサポートします。"

############################# Header ############################
title: "Java で XLTX をレンダリングして表示する" 
description: "Java、J2EE、および J2SE ベースのアプリケーション用のネイティブで高性能な XLTX ファイル ビューア API。出力ドキュメント形式の外観をカスタマイズするための幅広い追加機能をサポートします。" 
subtitle: "ドキュメントレンダリングソリューション" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "Maven の無料ダウンロード"
      link: "https://releases.groupdocs.com/viewer/java/"



############################# About ############################
about:
    enable: true
    title: "Java API 用の GroupDocs.Viewer について"
    link: "/viewer/java/"
    link_title: "もっと詳しく知る"
    picture: "about_viewer.svg" # 480 X 400
    content: |
      追加のソフトウェアをインストールしなくても、GroupDocs.Viewer for Java API を使用して、Java アプリケーションで 180 以上のファイル形式を HTML、PDF、または画像モードで表示できるようにします。 Microsoft Office、Apache Open Office、Adobe Acrobat Reader など。開発者は、Microsoft Office、OpenDocument、HTML、PDF、アーカイブ、図、Photoshop、AutoCAD などの一般的な画像やドキュメント タイプ、および Java アプリケーション内のプログラミング言語形式を簡単に表示できます。高速かつ最高品質のレンダリング。



############################# Steps ############################
steps:
    enable: true
    title: "Java で XLTX ファイルをレンダリングする手順" 
    content: |
      <a href='https://products.groupdocs.com/viewer/java/'>GroupDocs.Viewer</a> を使用すると、いくつかの手順で XLTX を HTML、JPEG、PNG、または PDF にレンダリングできます。
      
      1. <a href='https://releases.groupdocs.com/viewer/java/'>GroupDocs.Viewer for Java</a> を依存関係としてプロジェクトに追加します。 
      2. Viewer クラスのインスタンスを作成し、XLTX ファイルをフルパスでロードします。  
      3. XLTX ファイルを HTML、PNG、JPEG、または PDF 形式でレンダリングするオプションを設定します。 
      4. ファイルをレンダリングし、現在のディレクトリで出力を確認します。 
   
    code:
      platform: "java"
      copy_title: "コピー"
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
        copy_tip: "クリックしてコピーします"
        copy_done: "コピーされました"
      links:
        #  loop
        - title: "他の例"
          link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Java"
        #  loop
        - title: "ドキュメンテーション"
          link: "https://docs.groupdocs.com/viewer/java/"
          
      content: |
        ```java {style=abap}

        // 入力 XLTX ファイルを設定する
        String filePath = "input.xltx";

        // GroupDocs.Viewer をインスタンス化する
        try (Viewer viewer = new Viewer(filePath))
        {
            // 表示オプションを設定する
            HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                
            // リソースが埋め込まれた XLTX ファイルを HTML にレンダリングします
            viewer.view(viewOptions);
        }

        ```
            

############################# Actions ############################

actions:
  enable: true
  title: "始める準備はできていますか?"
  description: "GroupDocs.Viewer の機能を無料で試すか、ライセンスをリクエストしてください"
  items:
    #  loop
    - title: "Mavenのダウンロード"
      link: "https://releases.groupdocs.com/viewer/java/"
      color: "red"
        #  loop
    - title: "ライセンス"
      link: "https://purchase.groupdocs.com/pricing/viewer/java/"
      color: "light"



############################# More Formats #####################
more_formats:
    enable: true
    title: "Java を使用して他のファイル形式をレンダリングする"
    exclude: "XLTX"
    description: "Java 用のマルチフォーマットのドキュメントおよび画像ビューア API。外部ビューアを使用せずに、以下の一般的なファイル形式の一部を表示します。"
    items: 
        # format loop 1
        - name: "DOCXのレンダリング"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Open XML Document" 

        # format loop 2
        - name: "CDR をレンダリングする" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "CorelDRAW File" 

        # format loop 3
        - name: "PPTXのレンダリング"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint Open XML Presentation" 

        # format loop 4
        - name: "XLSX をレンダリングする"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet" 

        # format loop 5
        - name: "DWG をレンダリングする"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "AutoCAD Drawing"

        # format loop 6
        - name: "XMLのレンダリング"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "XML File"

        # format loop 7
        - name: "PSD をレンダリングする"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Adobe Photoshop Document"

        # format loop 8
        - name: "レンダリングAI"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Adobe Illustrator Artwork"

        # format loop 9
        - name: "ドキュメントのレンダリング"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Microsoft Word Document" 

        # format loop 10
        - name: "TXTをレンダリングする" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Plain Text File" 

        # format loop 11
        - name: "DXFのレンダリング" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Drawing Exchange Format File"  
          
        # format loop 12
        - name: "VCF をレンダリングする"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "vCard File"  
              
        # format loop 13
        - name: "SVG のレンダリング"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Scalable Vector Graphic" 
          
        # format loop 14
        - name: "HTMLのレンダリング"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "PDF をレンダリングする"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Portable Document Format File"
          
        # format loop 16
        - name: "JPEGをレンダリングする"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "JPEG Image"
          
        # format loop 17
        - name: "PNG をレンダリング"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Portable Network Graphic" 
          
        # format loop 18
        - name: "EMLをレンダリングする"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "E-Mail Message" 
          
        # format loop 19
        - name: "RTFをレンダリングする"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Rich Text Format File" 
          
        # format loop 20
        - name: "ODT のレンダリング"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "OpenDocument Text Document" 
          
        # format loop 21
        - name: "CSVのレンダリング"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Comma-Separated Values File" 


---
