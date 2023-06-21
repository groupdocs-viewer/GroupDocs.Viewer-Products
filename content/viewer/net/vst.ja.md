---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: ja

############################# Head #############################
head_title: ".NET VST ビューア API - C# VB.NET での読み取り、表示、レンダリング"
head_description: "あらゆる種類の C#、ASP.NET、VB.NET、.NET Core アプリケーションで VST を読み取り、レンダリング、表示する .NET ドキュメント ビューア API。"

############################# Header ############################
title: "VST C# .NET アプリケーション用のファイル ビューア" 
description: "あらゆる種類の C#、ASP.NET、VB.NET、.NET Core アプリケーションで VST ファイルを読み取り、レンダリング、表示するための .NET ドキュメント ビューア API。数行のコードを使用して、HTML5、PDF、または画像として、正確な書式設定とレイアウトでレンダリングされたファイルを表示します。" 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "無料トライアルをダウンロード"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: ".NET API 用の GroupDocs.Viewer について" 
    content: |
        数行のコードを追加するだけで、GroupDocs.Viewer for .NET API を使用して .NET アプリケーションで 190 以上の一般的なドキュメント形式の表示を開始できます。開発者は、PDF、ワード プロセッシング、Excel スプレッドシート、プレゼンテーション、Visio、プロジェクト、Outlook、その他多くの一般的なドキュメント形式を HTML5、画像、または PDF モードで簡単に表示できます。ドキュメントのレンダリングは高速で、元のソース ファイルと同一であり、追加のソフトウェアやその他の外部ライブラリをインストールする必要はありません。

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
    title_left: "C# で VST ファイルをレンダリングする手順" 
    content_left: |
        [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/) を使用すると、いくつかの手順で VST を HTML、JPEG、PNG、または PDF にレンダリングできます。

        * お気に入りのパッケージ マネージャーを使用して、[GroupDocs.Viewer for .NET](https://www.nuget.org/packages/groupdocs.viewer) をインストールします。 
        * Viewer クラスのインスタンスを作成し、VST ファイルをフルパスでロードします。 
        * VST ファイルを HTML、PNG、JPEG、または PDF 形式でレンダリングするオプションを設定します。 
        * ファイルをレンダリングし、現在のディレクトリで出力を確認します。 
        
    title_right: "システム要求" 
    content_right: |
        GroupDocs.Viewer for .NET API は、すべての主要なプラットフォームとオペレーティング システムでサポートされています。以下のコードを実行する前に、次の前提条件がシステムにインストールされていることを確認してください。

        * オペレーティング システム: Microsoft Windows、Linux、MacOS 
        * 開発環境: Microsoft Visual Studio、Visual Studio Code、.NET CLI 
        * フレームワーク: .NET Framework、.NET Standard、.NET Core、.NET 
    code: |
        ```cs
                        
            // Set up input VST file
            string filePath = "input.vst";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render VST file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "VST ビューアのライブデモ"
    content: |
        [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/vst) ウェブサイトにアクセスして、今すぐ VST ファイルを表示してください。
    lang: "ja"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "C# を使用したその他のファイル形式のレンダリングと表示"
    exclude: "VST"
    content: |
        .NET 用のマルチフォーマットのドキュメントおよび画像ビューア API。外部ビューアを使用せずに、以下の一般的なファイル形式の一部を表示します。
    format: 
        # format loop 1
        - name: "DOCXをレンダリングする"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft WordのオープンXMLドキュメント" 

        # format loop 2
        - name: "CDR をレンダリングする" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "CorelDRAW ファイル" 

        # format loop 3
        - name: "PPTXのレンダリング"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint オープン XML プレゼンテーション" 

        # format loop 4
        - name: "XLSX をレンダリングする"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel オープン XML スプレッドシート" 

        # format loop 5
        - name: "DWG をレンダリングする"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "AutoCAD 図面"

        # format loop 6
        - name: "XMLのレンダリング"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "XMLファイル"

        # format loop 7
        - name: "PSD をレンダリングする"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Adobe Photoshop ドキュメント"

        # format loop 8
        - name: "Adobe Illustrator ファイルをレンダリングする"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Adobe Illustrator アートワーク"

        # format loop 9
        - name: "ドキュメントのレンダリング"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Microsoft Word文書" 

        # format loop 10
        - name: "TXTをレンダリングする" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "プレーンテキストファイル" 

        # format loop 11
        - name: "DXFのレンダリング" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "図面交換フォーマットファイル"  
          
        # format loop 12
        - name: "VCF をレンダリングする"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "vCard ファイル"  
              
        # format loop 13
        - name: "SVG のレンダリング"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "スケーラブルなベクター グラフィック" 
          
        # format loop 14
        - name: "HTMLのレンダリング"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "ハイパーテキスト マークアップ言語ファイル" 
          
        # format loop 15
        - name: "PDF をレンダリングする"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "PDF形式ファイル"
          
        # format loop 16
        - name: "JPEGをレンダリングする"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "JPEG画像"
          
        # format loop 17
        - name: "PNG をレンダリング"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "ポータブルネットワークグラフィックス" 
          
        # format loop 18
        - name: "EMLをレンダリングする"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "電子メールメッセージ" 
          
        # format loop 19
        - name: "RTFをレンダリングする"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "リッチテキスト形式ファイル" 
          
        # format loop 20
        - name: "ODT のレンダリング"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "OpenDocument テキストドキュメント" 
          
        # format loop 21
        - name: "CSVのレンダリング"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "カンマ区切り値ファイル" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
