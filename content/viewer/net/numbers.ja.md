---
############################# Static ############################
layout: "format"
date: 2024-05-14T11:12:50
draft: false
lang: ja
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

############################# Head #############################
head_title: ".NET NUMBERS ビューア API - C# VB.NET での読み取り、表示、レンダリング"
head_description: "あらゆる種類の C#、ASP.NET、VB.NET、.NET Core アプリケーションで NUMBERS を読み取り、レンダリング、表示する .NET ドキュメント ビューア API。"

############################# Header ############################
title: "C# .NET アプリケーション用の NUMBERS ファイル ビューア" 
description: "あらゆる種類の C#、ASP.NET、VB.NET、.NET Core アプリケーションで NUMBERS ファイルを読み取り、レンダリング、表示するための .NET ドキュメント ビューア API。数行のコードを使用して、HTML5、PDF、または画像として、正確な書式設定とレイアウトでレンダリングされたファイルを表示します。" 
subtitle: "ドキュメントレンダリングソリューション" 

header_actions:
  enable: true
  items:
    #  loop
    - title: "Nuget の無料ダウンロード"
      link: "https://nuget.org/packages/GroupDocs.Viewer"



############################# About ############################
about:
    enable: true
    title: ".NET API 用の GroupDocs.Viewer について"
    link: "/viewer/net/"
    link_title: "もっと詳しく知る"
    picture: "about_viewer.svg" # 480 X 400
    content: |
      数行のコードを追加するだけで、GroupDocs.Viewer for .NET API を使用して .NET アプリケーションで 190 以上の一般的なドキュメント形式の表示を開始できます。開発者は、PDF、ワード プロセッシング、Excel スプレッドシート、プレゼンテーション、Visio、プロジェクト、Outlook、その他多くの一般的なドキュメント形式を HTML5、画像、または PDF モードで簡単に表示できます。ドキュメントのレンダリングは高速で、元のソース ファイルと同一であり、追加のソフトウェアやその他の外部ライブラリをインストールする必要はありません。



############################# Steps ############################
steps:
    enable: true
    title: "C# で NUMBERS ファイルをレンダリングする手順" 
    content: |
      <a href='https://products.groupdocs.com/viewer/net/'>GroupDocs.Viewer</a> を使用すると、いくつかの手順で NUMBERS を HTML、JPEG、PNG、または PDF にレンダリングできます。
      
      1. 好みのパッケージ マネージャーを使用して、<a href='https://www.nuget.org/packages/groupdocs.viewer'>GroupDocs.Viewer for .NET</a> をインストールします。 
      2. Viewer クラスのインスタンスを作成し、NUMBERS ファイルをフルパスでロードします。  
      3. NUMBERS ファイルを HTML、PNG、JPEG、または PDF 形式でレンダリングするオプションを設定します。 
      4. ファイルをレンダリングし、現在のディレクトリで出力を確認します。 
   
    code:
      platform: "net"
      copy_title: "コピー"
      install:
        command: "dotnet add package GroupDocs.Viewer"
        copy_tip: "クリックしてコピーします"
        copy_done: "コピーされました"
      links:
        #  loop
        - title: "他の例"
          link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
        #  loop
        - title: "ドキュメンテーション"
          link: "https://docs.groupdocs.com/viewer/net/"
          
      content: |
        ```csharp {style=abap}

        // 入力 NUMBERS ファイルを設定する
        string filePath = "input.numbers";

        // GroupDocs.Viewer をインスタンス化する
        using (Viewer viewer = new Viewer(filePath))
        {
            // 表示オプションを設定する
            HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                
            // リソースが埋め込まれた NUMBERS ファイルを HTML にレンダリングします
            viewer.View(viewOptions);
        }

        ```            


############################# Actions ############################

actions:
  enable: true
  title: "始める準備はできていますか?"
  description: "GroupDocs.Viewer の機能を無料で試すか、ライセンスをリクエストしてください"
  items:
    #  loop
    - title: "ナゲットのダウンロード"
      link: "https://nuget.org/packages/GroupDocs.Viewer"
      color: "red"
        #  loop
    - title: "ライセンス"
      link: "https://purchase.groupdocs.com/pricing/viewer/net/"
      color: "light"


############################# More Formats #####################
more_formats:
    enable: true
    title: "C# を使用して他のファイル形式をレンダリングする"
    exclude: "NUMBERS"
    description: ".NET 用のマルチフォーマットのドキュメントおよび画像ビューア API。外部ビューアを使用せずに、以下の一般的なファイル形式の一部を表示します。"
    items: 
        # format loop 1
        - name: "DOCXのレンダリング"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word Open XML Document" 

        # format loop 2
        - name: "CDR をレンダリングする" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "CorelDRAW File" 

        # format loop 3
        - name: "PPTXのレンダリング"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint Open XML Presentation" 

        # format loop 4
        - name: "XLSX をレンダリングする"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Open XML Spreadsheet" 

        # format loop 5
        - name: "DWG をレンダリングする"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "AutoCAD Drawing"

        # format loop 6
        - name: "XMLのレンダリング"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "XML File"

        # format loop 7
        - name: "PSD をレンダリングする"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Adobe Photoshop Document"

        # format loop 8
        - name: "レンダリングAI"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Adobe Illustrator Artwork"

        # format loop 9
        - name: "ドキュメントのレンダリング"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Microsoft Word Document" 

        # format loop 10
        - name: "TXTをレンダリングする" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Plain Text File" 

        # format loop 11
        - name: "DXFのレンダリング" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Drawing Exchange Format File"  
          
        # format loop 12
        - name: "VCF をレンダリングする"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "vCard File"  
              
        # format loop 13
        - name: "SVG のレンダリング"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Scalable Vector Graphic" 
          
        # format loop 14
        - name: "HTMLのレンダリング"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Hypertext Markup Language File" 
          
        # format loop 15
        - name: "PDF をレンダリングする"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Portable Document Format File"
          
        # format loop 16
        - name: "JPEGをレンダリングする"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "JPEG Image"
          
        # format loop 17
        - name: "PNG をレンダリング"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Portable Network Graphic" 
          
        # format loop 18
        - name: "EMLをレンダリングする"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "E-Mail Message" 
          
        # format loop 19
        - name: "RTFをレンダリングする"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Rich Text Format File" 
          
        # format loop 20
        - name: "ODT のレンダリング"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "OpenDocument Text Document" 
          
        # format loop 21
        - name: "CSVのレンダリング"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Comma-Separated Values File" 



---
