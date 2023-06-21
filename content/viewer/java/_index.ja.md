---
############################# Static ############################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false

lang: ja
product: "Viewer"
product_tag: "viewer"
platform: "Java"
platform_tag: "java"

############################# Head ############################
head_title: "PDF Word Excel HTML 画像および電子メール用の Java ドキュメント ビューア API"
head_description: "Java ドキュメント ビューアおよびファイル レンダリング API。 Java アプリケーションに PDF ビューア、Word ビューア、Excel ビューア、画像ビューア、HTML ビューア、電子メール ビューアを追加します。"

############################# Header ############################
title: "ドキュメントをレンダリングおよび表示するための Java API"
description: "170 以上のファイル形式をサポートするマルチ形式ドキュメントをネイティブに表示、表示、操作する Java アプリケーションを開発するためのドキュメント ビューア ライブラリ。"
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Download Free Trial"
    link: "https://downloads.groupdocs.com/viewer/java"

############################# SubMenu ############################
submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Viewer for Java"
        image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-viewer-java.png"
        product: "GroupDocs.Viewer"
        platform: "Java"

    middle:
        button:
            # button loop
            - link: "#overview"
              text: "概要"

            # button loop
            - link: "#features"
              text: "特徴"

            # button loop
            - link: "#support"
              text: "サポート"

            # button loop
            - link: "https://products.groupdocs.app/viewer/total"
              text: "ライブデモ"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/java"
              text: "価格設定"

    right:
        link_download: "https://releases.groupdocs.com/viewer/java/"
        link_learn: "https://docs.groupdocs.com/viewer/java/"
        link_buy: "https://purchase.groupdocs.com"

############################# Overview ############################
overview:
    enable: true
    content: |
      GroupDocs.Viewer for Java は、強力なドキュメント ビューア API のセットを組み合わせて、追加のソフトウェアをインストールすることなく、Java アプリケーションで画像とドキュメント形式を表示します。ドキュメントをネイティブにラスタライズして SVG+HTML+CSS に変換し、ドキュメントの表示品質を向上させながら、忠実度の高い出力を提供します。ドキュメント レンダリング API を使用すると、PDF、HTML、XML、Microsoft Office Word、Excel ワークシート、PowerPoint プレゼンテーション、Outlook 電子メール、Visio 図、プロジェクト、メタファイル、画像、その他のさまざまなファイル形式を簡単に、プログラミングの危険性を減らしてすばやく表示できます。また、パスワードで保護されたファイルを表示したり、レンダリング後にドキュメント表現を HTML、画像、または PDF 形式で取得したりすることもできます。当社のファイル ビューア ライブラリは、ドキュメント全体を表示したり、部分的にレンダリングしてプロセスを高速化したりできるため、非常にカスタマイズ可能です。 GroupDocs.Viewer for Java API を使用すると、スプレッドシート内のページや特定のセル範囲を表示したり、PDF や CAD などの形式で個々のドキュメント レイヤーをレンダリングしたりできます。  

      GroupDocs.Viewer for Java API を使用すると、サポートされているファイル形式の注釈またはコメントの有無にかかわらずドキュメントをレンダリングできます。また、カスタム フォント ディレクトリを追加したり、ファイル タイプ、拡張子、名前、ページ数などの基本的なドキュメント情報を抽出したりすることもできます。  

      GroupDocs.Viewer for Java は、すべての Java バージョンと互換性があり、Java ランタイムを実行できる一般的なオペレーティング システム (Windows、Linux、macOS) をサポートします。
    tabs:
      enable: true
      
      ## TAB ONE ##
      tab_one:
        description: |
          Java 用 GroupDocs.Viewer の概要は次のとおりです。
      
        right:
          enable: true
          icon: "fab fa-html5"
          title: "概要"
          content: |
            * 170 以上のドキュメントタイプを表示 
            * HTML、画像、PDF バージョンを取得 
            * 回転と並べ替え 
            * ウォーターマークを適用する 
            * 高速処理のためのキャッシュ 
            * カスタムフォントの追加 
            * エンコーディング標準を適用する 
            * カスタム入力データ ハンドラー 
            * 変更を追跡してレンダリングする 
            * レスポンシブ HTML としてレンダリング 
            * PDF および CAD レイヤーのレンダリング 
            * 保護されたファイルをレンダリングする 
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Viewer for Java は、Microsoft Office、画像、図などの一般的なドキュメント ファイル形式をすべてサポートしています。

        left:
          enable: true
          table:
            # table loop
            - title: "Microsoft Office"
              content: |
                * **Word:** DOC, DOCX, DOCM, DOT, DOTX, DOTM, RTF, TXT
                * **Excel:** XLS, XLSX, XLSM, XLSB, XLTM, XLT, XLTM, XLTX, XLAM, SXC, SpreadsheetML
                * **PowerPoint:** PPT, PPTX, PPS, PPSX, PPSM, POT, POTM, POTX, PPTM
                * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
                * **Project:** MPP, MPT, MPX
                * **Outlook:** MSG, EML, EMLX, PST, OST
                * **OneNote:** ONE

            # table loop
            - title: "その他の形式"
              content: |
                * **ページレイアウトファイル:** PDF, TEX, XPS, OXPS
                * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG, OTG, FODP, FODG
                * **デリミタで区切られた値:** CSV, TSV
                * **ウェブ:** HTML, MHT, MHTML
                * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
                * **PostScript:** PS, EPS
                * **アーカイブ:** ZIP, TAR, BZ2, GZ, RAR, RAR5
                * **様々:** OBJ, EPUB, MOBI, DjVu, XML, VCF, VCARD, NUMBERS, NSF

        right:
          enable: true
          table:
            # table loop
            - title: "画像、グラフィック、図表"
              content: |
                * **画像:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB
                * **ウィンドウのアイコン:** ICO
                * **スケーラブルなベクター グラフィックス:** SVG, CDR, CMX, IGS, SVGZ
                * **JPEG2000:** JP2, J2C, J2K, JPC, JPF, JPX, JPM
                * **アドビフォトショップ:** PSD, PSB
                * **プリンターコマンド言語:** PCL
                * **ステレオリソグラフィー (3D プリンティング):** STL
                * **業界基礎クラス:** IFC
                * **医療画像処理:** DICOM
                * **プロッタドキュメント:** PLT, HPG
                * **Autodesk Design の Web フォーマット:** DWF, DWG
                * **AutoCAD 図面:** DWT, IFC, STL, CF2
                * **ISFF ベースの DGN (V7):** DGN

            # table loop
            - title: "プログラミング言語の形式"
              content: |
                * **C/C++/C# ファイル:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
                * **Java/JavaScript ファイル:** JAVA, JS, JSON, PROPERTIES
                * **様々:** VB, PHP, SQL, PL, PY, PV, RB, RST, SASS, SCALA, SCM, SCRIPT, AS, AS3, ASM, BAT, CMAKE, CSS, DIFF, ERB, GROOVY, HAML, LESS, LOG, M, MAKE, MD, ML, MM, SH, SML, VIM, YAML

      ## TAB THREE ##
      tab_three:
        description: |
          GroupDocs.Viewer for Java は、次のオペレーティング システム、フレームワーク、パッケージ マネージャーをサポートしています。
        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "オペレーティングシステム"
              content: |
                * Microsoft Windows Server 2003以降 
                * Microsoft Windows XP以降 
                * Microsoft Windows 10および11 
                * Linux (Ubuntu、OpenSUSE、CentOS など) 
                * Mac OS X 

            # table loop
            - icon: "fas fa-code"
              title: "サポートされているフレームワーク"
              content: |
                * J2SE 8.0 (1.8) 以降 (Java 17 など) 

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-cogs"
              title: "開発環境"
              content: |
                * NetBeans
                * IntelliJ IDEA
                * Eclipse

            # table loop
            - icon: "fas fa-tools"
              title: "ビルド自動化ツール"
              content: |
                * Maven
                * Gradle

############################# Features ############################
features:
    enable: true
    title: "Java 用 GroupDocs.Viewer の機能"

    feature:
      # feature loop
      - icon: "fas fa-copy"
        content: "HTML、PDF、画像、Word、Excel、その他のドキュメント形式のビューア"

      # feature loop
      - icon: "fas fa-eye"
        content: "AutoCAD 図面 (DWG) ファイルを SVG 形式にレンダリングする"

      # feature loop
      - icon: "fas fa-bolt"
        content: "変換後のファイルの背景色を調整する"
      
      # feature loop
      - icon: "fas fa-file-powerpoint"
        content: "ドキュメントをラスタライズして SVG、HTML、CSS に変換"

      # feature loop
      - icon: "fas fa-code"
        content: "レンダリングを通じてドキュメントの HTML、画像、または PDF 表現を取得する"

      # feature loop
      - icon: "fas fa-cloud"
        content: "ドキュメントのキャッシュされたバージョンで読み込み時間を短縮"

      # feature loop
      - icon: "fas fa-remove-format"
        content: "カスタム フォント ディレクトリの構成"

      # feature loop
      - icon: "fas fa-comment-slash"
        content: "Word、Excel、電子メール文書にエンコーディング標準を適用"

      # feature loop
      - icon: "fas fa-location-arrow"
        content: "FTP またはクラウド ストレージでドキュメントをリモート レンダリングする"

      # feature loop
      - icon: "fas fa-border-all"
        content: "レンダリング中に注釈とコメントを削除または保持する"

      # feature loop
      - icon: "fas fa-wrench"
        content: "ドキュメント ページを個別の HTML ページとしてレンダリングする"

      # feature loop
      - icon: "fas fa-columns"
        content: "非表示のスライドとページをレンダリングし、レンダリングされたドキュメントにページの並べ替えを適用する"

      # feature loop
      - icon: "fas fa-file-word"
        content: "ページ範囲、特定のページ、またはすべてのページを HTML にレンダリングします"

      # feature loop
      - icon: "fas fa-envelope"
        content: "ドキュメントのコメントを表示または非表示にする"

      # feature loop
      - icon: "fas fa-print"
        content: "レンダリングを通じて一部のドキュメント形式のレスポンシブ HTML を作成する"

      # feature loop
      - icon: "fas fa-file-archive"
        content: "フォントを除外して、レンダリングされた HTML のファイル サイズを削減する"

      # feature loop
      - icon: "fas fa-lock"
        content: "コメントや余分な空白などを削除して、出力HTMLとCSSを縮小します"

      # feature loop
      - icon: "fas fa-file-code"
        content: "ソースドキュメントの座標を使用して、含まれているテキストを読み取る"
      
      # feature loop
      - icon: "fas fa-fill-drip"
        content: "レンダリングされた出力の Excel シートのセル境界線の表示/非表示"

      # feature loop
      - icon: "fas fa-file-excel"
        content: "Excel シートの各ページの特定の行数をレンダリングする"

      # feature loop
      - icon: "fas fa-heading"
        content: "モデルと空ではないすべてのレイアウト、または CAD ファイルの特定のレイアウトをレンダリングします。"

      # feature loop
      - icon: "fas fa-project-diagram"
        content: "Outlook データ ファイル (OST/PST) 内のアイテムを PDF としてレンダリングする"

      # feature loop
      - icon: "fas fa-cube"
        content: "タイル レンダリング、または CAD ドキュメントの画像、HTML、PDF としての座標によるレンダリング"

      # feature loop
      - icon: "fab fa-uncharted"
        content: "PDF にレンダリングするときに印刷制限を設定する"

    more_feature:
      # more_feature_loop
      - title: "ドキュメントを表示するための効率的で信頼性の高い API"
        content: |
          GroupDocs.Viewer for Java API を使用すると、150 を超える異なるファイル形式のドキュメントを表示、レンダリング、表示できます。これは、文書の内容と構造をそのまま維持しながら、確実かつ効率的に実行されます。次の例は、GroupDocs.Viewer for Java API が Java を使用して DOCX ファイルを画像ファイルとしてレンダリングする際の容易さのレベルを示しています。

          ```java
          // Initialize Viewer
          Viewer viewer = new Viewer("invoice.docx");
          // Create view options
          PdfViewOptions viewOptions = new PdfViewOptions();
          // Convert file to PDF and check the output in the current directory
          viewer.view(viewOptions);
          ```
      # more_feature_loop
      - title: "ドキュメントのレンダリング中に変換を実行する"
        content: "GroupDocs.Viewer for Java API は、よりカスタマイズされたビューと表示のために、レンダリングされたドキュメントに適用されるさまざまな変換オプションを提供します。角度を指定することでページを回転できます。レンダリングされるページの順序を変更できます。レンダリングされたページまたは画像に特定のテキストを透かしとして適用します。 GroupDocs.Viewer for Java API を使用して、レンダリングされるドキュメントにカスタム フォントを追加することもできます。"

      # more_feature_loop
      - title: "電子メールの添付ファイルの操作"
        content: "GroupDocs.Viewer for Java API を使用すると、電子メールの特定またはすべての添付ファイルを取得できます。必要な電子メールの添付ファイルを取得したら、これらの添付ファイルを画像または HTML にレンダリングできます。"

############################# Support ############################
support:
    enable: true

############################# Solutions ##########################
solutions:
    enable: true
    title: "GroupDocs.Viewer は、他の一般的な開発環境向けのドキュメント表示 API を提供します"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Viewer for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-viewer-net.png"
          product: "GroupDocs.Viewer"
          platform: ".NET"
          link: "/viewer/net/"

############################# Back to top ##########################
back_to_top:
  enable: true
---