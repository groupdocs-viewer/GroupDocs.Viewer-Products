---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: ja

############################# Head #############################
head_title: "Java PPS ビューア API - Java アプリでの PPS のレンダリングと表示"
head_description: "Java、J2EE、J2SE アプリケーションの PPS ファイルを表示します。ドキュメント表示オプションを管理するための高度な機能を備えた HTML、PDF、またはイメージ モードでの 170 以上のドキュメントおよび画像ファイル形式の表示をサポートします。"

############################# Header ############################
title: "Java で PPS をレンダリングして表示する" 
description: "Java、J2EE、および J2SE ベースのアプリケーション用のネイティブで高性能の PPS ファイル ビューア API。出力ドキュメント形式の外観をカスタマイズするための幅広い追加機能をサポートします。" 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "無料トライアルをダウンロード"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Java API 用の GroupDocs.Viewer について" 
    content: |
        追加のソフトウェアをインストールしなくても、GroupDocs.Viewer for Java API を使用して、Java アプリケーションで 170 以上のファイル形式を HTML、PDF、または画像モードで表示できるようにします。 Microsoft Office、Apache Open Office、Adobe Acrobat Reader など。開発者は、Microsoft Office、OpenDocument、HTML、PDF、アーカイブ、図、Photoshop、AutoCAD などの一般的な画像やドキュメント タイプ、および Java アプリケーション内のプログラミング言語形式を簡単に表示できます。高速かつ最高品質のレンダリング。

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
              text: "APIリファレンス"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "コード例"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "ライブデモ"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "価格設定"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "Java で PPS ファイルをレンダリングする手順" 
    content_left: |
        [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/) を使用すると、いくつかの手順で PPS を HTML、JPEG、PNG、または PDF にレンダリングできます。

        * [GroupDocs.Viewer for Java](https://releases.groupdocs.com/viewer/java/) を依存関係としてプロジェクトに追加します。 
        * Viewer クラスのインスタンスを作成し、PPS ファイルをフルパスでロードします。 
        * PPS ファイルを HTML、PNG、JPEG、または PDF 形式でレンダリングするオプションを設定します。 
        * ファイルをレンダリングし、現在のディレクトリで出力を確認します。 
        
    title_right: "システム要求" 
    content_right: |
        GroupDocs.Viewer for Java API は、すべての主要なプラットフォームとオペレーティング システムでサポートされています。以下のコードを実行する前に、次の前提条件がシステムにインストールされていることを確認してください。

        * オペレーティング システム: Microsoft Windows、Linux、MacOS 
        * 開発環境: NetBeans、IntelliJ IDEA、Eclipse など。 
        * フレームワーク: J2SE 8.0 (1.8) 以降 (Java 17 など) 
    code: |
        ```java
                        
            // Set up input PPS file
            String filePath = "input.pps";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render PPS file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "PPS ビューアのライブデモ"
    content: |
        [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/pps) ウェブサイトにアクセスして、今すぐ PPS ファイルを表示してください。
    lang: "ja"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Java を使用したその他のファイル形式のレンダリングと表示"
    exclude: "PPS"
    content: |
        Java 用のマルチフォーマットのドキュメントおよび画像ビューア API。外部ビューアを使用せずに、以下の一般的なファイル形式の一部を表示します。
    format: 
        # format loop 1
        - name: "DOCXをレンダリングする"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft WordのオープンXMLドキュメント" 

        # format loop 2
        - name: "CDR をレンダリングする" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "CorelDRAW ファイル" 

        # format loop 3
        - name: "PPTXのレンダリング"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint オープン XML プレゼンテーション" 

        # format loop 4
        - name: "XLSX をレンダリングする"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel オープン XML スプレッドシート" 

        # format loop 5
        - name: "DWG をレンダリングする"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "AutoCAD 図面"

        # format loop 6
        - name: "XMLのレンダリング"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "XMLファイル"

        # format loop 7
        - name: "PSD をレンダリングする"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Adobe Photoshop ドキュメント"

        # format loop 8
        - name: "Adobe Illustrator ファイルをレンダリングする"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Adobe Illustrator アートワーク"

        # format loop 9
        - name: "ドキュメントのレンダリング"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Microsoft Word文書" 

        # format loop 10
        - name: "TXTをレンダリングする" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "プレーンテキストファイル" 

        # format loop 11
        - name: "DXFのレンダリング" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "図面交換フォーマットファイル"  
          
        # format loop 12
        - name: "VCF をレンダリングする"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "vCard ファイル"  
              
        # format loop 13
        - name: "SVG のレンダリング"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "スケーラブルなベクター グラフィック" 
          
        # format loop 14
        - name: "HTMLのレンダリング"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "ハイパーテキスト マークアップ言語ファイル" 
          
        # format loop 15
        - name: "PDF をレンダリングする"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "PDF形式ファイル"
          
        # format loop 16
        - name: "JPEGをレンダリングする"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "JPEG画像"
          
        # format loop 17
        - name: "PNG をレンダリング"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "ポータブルネットワークグラフィックス" 
          
        # format loop 18
        - name: "EMLをレンダリングする"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "電子メールメッセージ" 
          
        # format loop 19
        - name: "RTFをレンダリングする"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "リッチテキスト形式ファイル" 
          
        # format loop 20
        - name: "ODT のレンダリング"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "OpenDocument テキストドキュメント" 
          
        # format loop 21
        - name: "CSVのレンダリング"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "カンマ区切り値ファイル" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
