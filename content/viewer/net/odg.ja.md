---
layout: "auto-gen"
date: 2022-02-23T12:00:00+02:00
draft: false

head_title: ".NET ODG Viewer API-C＃VB.NETでの読み取り、表示、レンダリング"
head_description: ".あらゆるタイプのC＃、ASP.NET、VB.NET、および.NET CoreアプリケーションでODGを読み取り、レンダリング、表示するためのNETドキュメントビューアAPI."

title: "C＃.NETアプリケーション用のODGファイルビューア"
description: ".あらゆるタイプのC＃、ASP.NET、VB.NET、および.NET CoreアプリケーションでODGファイルを読み取り、レンダリングし、表示するためのNETドキュメントビューアAPI。レンダリングされたファイルを、HTML5、PDFで、またはコードの数行を使用して画像として、実際のフォーマットとレイアウトで表示します."

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "無料トライアルをダウンロード"
    link: "https://downloads.groupdocs.com/viewer/net"

submenu:
    enable: true

    left:
        img_alt: "GroupDocs.Viewer for .NET"
        image: "https://cms.admin.containerize.com/templates/groupdocs/images/product-logos/90x90-noborder/groupdocs-viewer-net.png"
        product: "GroupDocs.Viewer"
        platform: ".NET"

    middle:
        button:

            - link: "https://apireference.groupdocs.com/viewer/net"
              text: "APIリファレンス"

            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "コード例"

            - link: "https://products.groupdocs.app/viewer/family"
              text: "ライブデモ"

            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "価格設定"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

about:
    enable: true
    title: "GroupDocs.Viewer for .NET APIについて"
    content: |
        数行のコードを追加して、GroupDocs.Viewer for .NET APIを使用して、.NETアプリケーションで170以上の一般的なドキュメント形式の表示を開始します。開発者は、PDF、ワードプロセッシング、Excelスプレッドシート、プレゼンテーション、Visio、Project、Outlook、およびその他の多くの一般的なドキュメント形式をHTML5、画像、またはPDFモードで簡単に表示できます。ドキュメントのレンダリングは高速で、元のソースファイルと同じであり、MicrosoftOfficeやその他の外部ライブラリをインストールする必要はありません。

steps:
    enable: true
    title_left: "C＃でODGファイルを表示する手順"
    content_left: |
        [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/)を使用すると、.NET開発者は、いくつかの簡単な手順を実装することで、アプリケーションにODGファイル表示機能を簡単に追加できます。

        * Viewerクラスのインスタンスを作成し、フルパスでODGファイルをロードします。
        *ODGファイルをPNG形式に変換するオプションを設定します。
        *ファイルを変換し、現在のディレクトリの出力を確認します。
        
    title_right: "システム要求"
    content_right: |
        GroupDocs.Viewer for .NET APIは、すべての主要なプラットフォームとオペレーティングシステムでサポートされています。以下のコードを実行する前に、システムに次の前提条件がインストールされていることを確認してください。

        *オペレーティングシステム: Microsoft Windows、Linux、MacOS
        *開発環境: Microsoft Visual Studio、Visual Studio Code、.NET CLI
        *フレームワーク: .NET Framework、.NET Standard、.NET Core、.NET
        * [NuGet](https://www.nuget.org/packages/groupdocs.viewer)からGroupDocs.Viewerfor.NETの最新バージョンを取得します
        
    code: |
        ```cs
        //ビューアをインスタンス化します
        using (Viewer viewer = new Viewer("sample.odg"))
        {
        	//表示オプションを設定します 
        	ViewOptions viewOptions = new PngViewOptions();
        	//ファイルをPNGに変換し、現在のディレクトリの出力を確認します 
        	viewer.View(viewOptions);
        }
        ```
        
demos:
    enable: true
    title: "ODGビューアのライブデモ"
    content: |
        [GroupDocs.Viewer Live Demos](https://products.groupdocs.app/viewer/odg)Webサイトにアクセスして、ODGファイルを今すぐ表示します。  
        ライブデモには次の利点があります
        
about_formats:
    enable: true
    format:
        - icon: "far fa-file-odg"
          title: "ODGファイル形式について"
          content: |
            ODGファイル形式は、Apache OpenOfficeのDrawアプリケーションで、描画要素をベクターイメージとして保存するために使用されます。これは、Advancement of Structural Information Standards（OASIS）によって概説されているXMLベースのファイル形式の仕様に従います。 ODGは、点、線、曲線を使用して図面をベクトル画像として表します。 OpenOfficeに加えて、LibreOfficeおよびその他のアプリケーションもODGファイル形式での作業をサポートします。たとえば、OpenOfficeでサポートされている他の形式には、ODT、ODF、ODP、ODSなどがあります。

          link: "https://docs.fileformat.com/image/odg/"

more_formats:
    enable: false
    title: "その他のファイル形式レンダリングと表示"
    content: |
        .NET用のマルチフォーマットドキュメントおよび画像ビューアAPI。外部ビューアなしで、以下の一般的なファイル形式のいくつかを表示します。
    format: 
          link: "/viewer/net/doc/"
          description: "MicrosoftWordドキュメント"

          link: "/viewer/net/docm/"
          description: "MicrosoftWordマクロ対応ドキュメント"

          link: "/viewer/net/docx/"
          description: "Microsoft WordOpenXMLドキュメント"

          link: "/viewer/net/dot/"
          description: "MicrosoftWord文書テンプレート"

          link: "/viewer/net/dotm/"
          description: "MicrosoftWordマクロ対応テンプレート"

          link: "/viewer/net/dotx/"
          description: "WordOpenXMLドキュメントテンプレート"

          link: "/viewer/net/rtf/"
          description: "リッチテキストファイル形式"

          link: "/viewer/net/txt/"
          description: "プレーンテキストファイル形式"

          link: "/viewer/net/xls/"
          description: "MicrosoftExcelバイナリファイル形式"

          link: "/viewer/net/xlsx/"
          description: "Microsoft ExcelOpenXMLスプレッドシート"

          link: "/viewer/net/xlsm/"
          description: "MicrosoftExcelマクロ対応スプレッドシート"

          link: "/viewer/net/xlsb/"
          description: "MicrosoftExcelバイナリスプレッドシートファイル"

          link: "/viewer/net/xltx/"
          description: "Microsoft ExcelOpenXMLテンプレート"

          link: "/viewer/net/tsv/"
          description: "タブ区切り値ファイル"

          link: "/viewer/net/xlam/"
          description: "MicrosoftExcelマクロ対応アドイン"

          link: "/viewer/net/csv/"
          description: "カンマ区切り値ファイル"

          link: "/viewer/net/ppt/"
          description: "PowerPointプレゼンテーション"

          link: "/viewer/net/pps/"
          description: "MicrosoftPowerPointスライドショー"

          link: "/viewer/net/pptx/"
          description: "PowerPointOpenXMLプレゼンテーション"

          link: "/viewer/net/ppsx/"
          description: "PowerPointOpenXMLスライドショー"

          link: "/viewer/net/potx/"
          description: "Microsoft PowerPointOpenXMLテンプレート"

          link: "/viewer/net/potm/"
          description: "MicrosoftPowerPointテンプレート"

          link: "/viewer/net/pptm/"
          description: "MicrosoftPowerPointプレゼンテーション"

          link: "/viewer/net/ppsm/"
          description: "MicrosoftPowerPointスライドショー"

          link: "/viewer/net/pdf/"
          description: "AdobePortableドキュメント形式"

          link: "/viewer/net/xps/"
          description: "XMLPaperSpecificationを開く"

          link: "/viewer/net/tex/"
          description: "LaTeXソースドキュメント"

          link: "/viewer/net/ods/"
          description: "ドキュメントスプレッドシートを開く"

          link: "/viewer/net/odp/"
          description: "OpenDocumentプレゼンテーションファイル形式"

          link: "/viewer/net/otp/"
          description: "原点グラフテンプレート"

          link: "/viewer/net/odt/"
          description: "ドキュメントテキストを開く"

          link: "/viewer/net/ott/"
          description: "ドキュメントテンプレートを開く"

          link: "/viewer/net/vst/"
          description: "Microsoft Visio2003-2010XML図面"

          link: "/viewer/net/tiff/"
          description: "タグ付き画像ファイル形式"

          link: "/viewer/net/jpeg/"
          description: "JPEG画像"

          link: "/viewer/net/png/"
          description: "ポータブルネットワークグラフィック"

          link: "/viewer/net/gif/"
          description: "グラフィカルな交換フォーマットファイル"

          link: "/viewer/net/bmp/"
          description: "ビットマップファイル形式"

          link: "/viewer/net/ico/"
          description: "Microsoftアイコンファイル"

          link: "/viewer/net/psd/"
          description: "AdobePhotoshopドキュメント"


          link: "/viewer/net/webp/"
          description: "ラスターWeb画像ファイル形式"

          link: "/viewer/net/svg/"
          description: "スケーラブルベクターグラフィックファイル"

          link: "/viewer/net/jp2/"
          description: "JPEG2000コア画像ファイル"

          link: "/viewer/net/emz/"
          description: "MicrosoftProjectドキュメント"

          link: "/viewer/net/wmz/"
          description: "MicrosoftProjectテンプレート"

          link: "/viewer/net/html/"
          description: "ハイパーテキストマークアップ言語"

          link: "/viewer/net/mht/"
          description: "集約HTMLのMIMEカプセル化"

          link: "/viewer/net/mhtml/"
          description: "集約HTMLのMIMEカプセル化"

          link: "/viewer/net/msg/"
          description: "MicrosoftOutlookの電子メールメッセージ"

          link: "/viewer/net/eml/"
          description: "電子メールメッセージ"

          link: "/viewer/net/one/"
          description: "Microsoft OneNote"

          link: "/viewer/net/wmf/"
          description: "Windowsメタファイル"

          link: "/viewer/net/emf/"
          description: "Windows拡張メタファイル"

          link: "/viewer/net/psd/"
          description: "AdobePhotoshopドキュメント"

          link: "/viewer/net/vsd/"
          description: "MicrosoftVisio2003-2010図面"

          link: "/viewer/net/vsdx/"
          description: "MicrosoftVisio図面"

          link: "/viewer/net/vss/"
          description: "MicrosoftVisio2003-2010ステンシル"

          link: "/viewer/net/vdx/"
          description: "Microsoft Visio2003-2010XML図面"

          link: "/viewer/net/vdw/"
          description: "Microsoft Visio2010Web描画"

          link: "/viewer/net/epub/"
          description: "デジタル電子書籍ファイル形式"


back_to_top:
    enable: true
---
