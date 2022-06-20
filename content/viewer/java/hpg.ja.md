---
layout: "auto-gen"
date: 2022-02-23T12:00:00+02:00
draft: false

head_title: "Java HPGViewerAPI-JavaアプリでHPGをレンダリングおよび表示"
head_description: "Java、J2EE、J2SEアプリケーションでHPGファイルを表示します。ドキュメント表示オプションを管理するための高度な機能を備えた、HTML、PDF、または画像モードでの150以上のドキュメントおよび画像ファイル形式の表示をサポート."

title: "JavaでのHPGファイルのレンダリングと表示"
description: "Java、J2EE、およびJ2SEベースのアプリケーション用のネイティブで高性能なHPGファイルビューアAPI。出力ドキュメント形式の外観をカスタマイズするためのさまざまな追加機能をサポートします。"

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "無料トライアルをダウンロード"
    link: "https://downloads.groupdocs.com/viewer/java"

submenu:
    enable: true

    left:
        img_alt: "GroupDocs.Viewer for Java"
        image: "https://cms.admin.containerize.com/templates/groupdocs/images/product-logos/90x90-noborder/groupdocs-viewer-java.png"
        product: "GroupDocs.Viewer"
        platform: "Java"

    middle:
        button:

            - link: "https://apireference.groupdocs.com/viewer/java"
              text: "APIリファレンス"

            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Java"
              text: "コード例"

            - link: "https://products.groupdocs.app/viewer/family"
              text: "ライブデモ"

            - link: "https://purchase.groupdocs.com/pricing/viewer/java"
              text: "価格設定"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/java"
        link_learn: "https://docs.groupdocs.com/viewer/java"
        link_buy: "https://purchase.groupdocs.com"

about:
    enable: true
    title: "GroupDocs.Viewer for Java APIについて"
    content: |
        追加のソフトウェアをインストールせずに、GroupDocs.Viewer for Java APIを使用して、JavaアプリケーションがHTML、PDF、または画像モードで150を超えるファイル形式を表示できるようにします。 Microsoft Office、Apache Open Office、Adobe Acrobat Readerなど。開発者は、Microsoft Office、OpenDocument、HTML、PDF、アーカイブ、図、Photoshop、AutoCAD、およびJavaアプリケーション内のプログラミング言語形式を含むすべての一般的な画像とドキュメントタイプを簡単に表示できます。高速で最高品質のレンダリング。

steps:
    enable: true
    title_left: "JavaでHPGファイルを表示する手順"
    content_left: |
        [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/)を使用すると、Java開発者は、数行のコードを使用して、アプリケーションにHPGファイル表示機能を簡単に追加できます。

        *  Viewerクラスのインスタンスを作成し、フルパスでHPGファイルをロードします。
        * HPGファイルをPNG形式に変換するための表示オプションを設定します。
        * ファイルを変換し、現在のディレクトリの出力を確認します。
        
    title_right: "システム要求"
    content_right: |
        GroupDocs.Viewer for Java APIは、すべての主要なプラットフォームとオペレーティングシステムでサポートされています。以下のコードを実行する前に、システムに次の前提条件がインストールされていることを確認してください。

        * オペレーティングシステム: Microsoft Windows、Linux、MacOS
        * 開発環境: NetBeans、IntelliJ IDEA、Eclipseなど。
        * Javaランタイム環境: Java 7（1.7）以降
        * [GroupDocs Artifactリポジトリ](https://repository.groupdocs.com/webapp/#/artifacts/browse/tree/General/repo/com/groupdocs/groupdocs-viewer)からJava用のGroupDocs.Viewerの最新バージョンを入手してください。
        
    code: |
        ```java
        //ビューアをインスタンス化します
        try (Viewer viewer = new Viewer("sample.hpg"))
        {
        	//表示オプションを設定します
        	PngViewOptions viewOptions = new PngViewOptions();
        	//ファイルをPNGに変換し、現在のディレクトリの出力を確認します
        	viewer.view(viewOptions);
        }
        ```
        
demos:
    enable: true
    title: "HPGビューアのライブデモ"
    content: |
        [GroupDocs.Viewer Live Demos](https://products.groupdocs.app/viewer/)サイトにアクセスして、HPGファイルを今すぐ表示します。  
        ライブデモには次の利点があります
        
about_formats:
    enable: true
    format:
        - icon: "far fa-file-hpg"
          title: "HPGファイル形式について"
          content: |
            {{hpg}}

          link: "/{{hpg_url}}"

more_formats:
    enable: false
    title: "その他のファイル形式レンダリングと表示"
    content: |
        Java用のマルチフォーマットドキュメントおよび画像ビューアAPI。外部ビューアなしで、以下の一般的なファイル形式のいくつかを表示します。
    format: 
          link: "/viewer/java/doc/"
          description: "MicrosoftWordドキュメント"

          link: "/viewer/java/docm/"
          description: "MicrosoftWordマクロ対応ドキュメント"

          link: "/viewer/java/docx/"
          description: "Microsoft WordOpenXMLドキュメント"

          link: "/viewer/java/dot/"
          description: "MicrosoftWord文書テンプレート"

          link: "/viewer/java/dotm/"
          description: "MicrosoftWordマクロ対応テンプレート"

          link: "/viewer/java/dotx/"
          description: "WordOpenXMLドキュメントテンプレート"

          link: "/viewer/java/rtf/"
          description: "リッチテキストファイル形式"

          link: "/viewer/java/txt/"
          description: "プレーンテキストファイル形式"

          link: "/viewer/java/xls/"
          description: "MicrosoftExcelバイナリファイル形式"

          link: "/viewer/java/xlsx/"
          description: "Microsoft ExcelOpenXMLスプレッドシート"

          link: "/viewer/java/xlsm/"
          description: "MicrosoftExcelマクロ対応スプレッドシート"

          link: "/viewer/java/xlsb/"
          description: "MicrosoftExcelバイナリスプレッドシートファイル"

          link: "/viewer/java/xltx/"
          description: "Microsoft ExcelOpenXMLテンプレート"

          link: "/viewer/java/tsv/"
          description: "タブ区切り値ファイル"

          link: "/viewer/java/xlam/"
          description: "MicrosoftExcelマクロ対応アドイン"

          link: "/viewer/java/csv/"
          description: "カンマ区切り値ファイル"

          link: "/viewer/java/ppt/"
          description: "PowerPointプレゼンテーション"

          link: "/viewer/java/pps/"
          description: "MicrosoftPowerPointスライドショー"

          link: "/viewer/java/pptx/"
          description: "PowerPointOpenXMLプレゼンテーション"

          link: "/viewer/java/ppsx/"
          description: "PowerPointOpenXMLスライドショー"

          link: "/viewer/java/potx/"
          description: "Microsoft PowerPointOpenXMLテンプレート"

          link: "/viewer/java/potm/"
          description: "MicrosoftPowerPointテンプレート"

          link: "/viewer/java/pptm/"
          description: "MicrosoftPowerPointプレゼンテーション"

          link: "/viewer/java/ppsm/"
          description: "MicrosoftPowerPointスライドショー"

          link: "/viewer/java/pdf/"
          description: "AdobePortableドキュメント形式"

          link: "/viewer/java/xps/"
          description: "XMLPaperSpecificationを開く"

          link: "/viewer/java/tex/"
          description: "LaTeXソースドキュメント"

          link: "/viewer/java/ods/"
          description: "ドキュメントスプレッドシートを開く"

          link: "/viewer/java/odp/"
          description: "OpenDocumentプレゼンテーションファイル形式"

          link: "/viewer/java/otp/"
          description: "原点グラフテンプレート"

          link: "/viewer/java/odt/"
          description: "ドキュメントテキストを開く"

          link: "/viewer/java/ott/"
          description: "ドキュメントテンプレートを開く"

          link: "/viewer/java/vst/"
          description: "Microsoft Visio2003-2010XML図面"

          link: "/viewer/java/tiff/"
          description: "タグ付き画像ファイル形式"

          link: "/viewer/java/jpeg/"
          description: "JPEG画像"

          link: "/viewer/java/png/"
          description: "ポータブルネットワークグラフィック"

          link: "/viewer/java/gif/"
          description: "グラフィカルな交換フォーマットファイル"

          link: "/viewer/java/bmp/"
          description: "ビットマップファイル形式"

          link: "/viewer/java/ico/"
          description: "Microsoftアイコンファイル"

          link: "/viewer/java/psd/"
          description: "AdobePhotoshopドキュメント"



          link: "/viewer/java/webp/"
          description: "ラスターWeb画像ファイル形式"

          link: "/viewer/java/svg/"
          description: "スケーラブルベクターグラフィックファイル"

          link: "/viewer/java/jp2/"
          description: "JPEG2000コア画像ファイル"

          link: "/viewer/java/emz/"
          description: "MicrosoftProjectドキュメント"

          link: "/viewer/java/wmz/"
          description: "MicrosoftProjectテンプレート"

          link: "/viewer/java/html/"
          description: "ハイパーテキストマークアップ言語"

          link: "/viewer/java/mht/"
          description: "集約HTMLのMIMEカプセル化"

          link: "/viewer/java/mhtml/"
          description: "集約HTMLのMIMEカプセル化"

          link: "/viewer/java/msg/"
          description: "MicrosoftOutlookの電子メールメッセージ"

          link: "/viewer/java/eml/"
          description: "電子メールメッセージ"

          link: "/viewer/java/one/"
          description: "Microsoft OneNote"


          link: "/viewer/java/wmf/"
          description: "Windowsメタファイル"

          link: "/viewer/java/emf/"
          description: "強化されたメタファイル形式"

          link: "/viewer/java/psd/"
          description: "AdobePhotoshopドキュメント"

          link: "/viewer/java/vsd/"
          description: "MicrosoftVisio2003-2010図面"

          link: "/viewer/java/vsdx/"
          description: "MicrosoftVisio図面"

          link: "/viewer/java/vss/"
          description: "MicrosoftVisio2003-2010ステンシル"

          link: "/viewer/java/vdx/"
          description: "Microsoft Visio2003-2010XML図面"

          link: "/viewer/java/vdw/"
          description: "Microsoft Visio2010Web描画"

          link: "/viewer/java/epub/"
          description: "デジタル電子書籍ファイル形式"


back_to_top:
    enable: true
---
