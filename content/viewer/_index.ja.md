---
############################# Static ##########################
layout: "family"
date: 2023-12-20T06:39:57
draft: false

product: "Viewer"
product_tag: "viewer"

############################# Head ############################
head_title: "ドキュメント API のレンダリングと表示 |オンプレミスAPIとオンラインサービス"
head_description: "Word、PDF、Excel、Powerpoint、または画像ファイルを簡単かつ無料でレンダリングして表示します"

############################# Header ##########################
title: "ドキュメントを簡単にレンダリングして表示する"
description: |
  さまざまなファイルを PDF、HTML、画像にレンダリングするための強力なビューア API。

  ファイル、ストリーム、URL、FTP サーバー、Amazon S3、Azure Blob Storage など、さまざまなソースからドキュメントを読み込みます。

  レスポンシブな HTML ページを生成し、出力 PDF ファイルを保護し、必要に応じてページの並べ替え、ページの回転、メモやコメントのレンダリングを行います。

############################# Platforms ############################
supported_platforms:
  enable: true  
  head_title: "プラットフォームを選択してください"
  title: "サポートされているプラ​​ットフォーム"
  description: "GroupDocs.Viewer ライブラリは、次のオペレーティング システムとフレームワークをサポートしています。"
  details_link_title: "もっと詳しく知る"
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
        - content: "180 以上のファイル形式"
          rows: "1"
        # features loop
        - content: "ASP.NET Core の UI パッケージ"
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
        - content: "180 以上のファイル形式"
          rows: "1"
        # features loop
        - content:  "Spring および Dropwizard の UI パッケージ"
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
        - content:  "180 以上のファイル形式"
          rows: "1"
        # features loop
        - content:  "UI パッケージ - 近日公開予定"
          rows: "1" 
        # features loop
        - content:  "デモ - 近日公開予定"
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
        - content:  "180 以上のファイル形式"
          rows: "1"
        # features loop
        - content:  "UI パッケージ - 近日公開予定"
          rows: "1" 
        # features loop
        - content:  "デモ - 近日公開予定"
          rows: "3" 

############################# Features ############################

features:
  enable: true
  title: "GroupDocs.Viewer の機能セット"
  description: "アプリケーションでさまざまなタイプのファイルを HTML、PDF、PNG、JPEG としてレンダリングし、サードパーティ ソフトウェアを使用せずに表示するための API。"

  items:
    # feature loop
    - icon: "view"
      title: "ドキュメントと画像を表示する"
      content: "ドキュメントを HTML、PDF、PNG、JPEG ファイルとしてレンダリングして表示します。"

    # feature loop
    - icon: "password"
      title: "保護された文書を開く"
      content: "暗号化されたドキュメントを開くためのパスワードを指定します。"

    # feature loop
    - icon: "load"
      title: "どこからでもファイルをロード"
      content: "さまざまなファイル、URL、FTP サーバー、Amazon S3 などからドキュメントを読み込みます。"
    
    # feature loop
    - icon: "pages"
      title: "すべてまたは特定のページをレンダリングする"
      content: "レンダリングするページ番号の範囲を指定します。"


############################# Code samples ############################
code_samples:
  enable: true
  title: "GroupDocs.Viewer コード サンプル"
  description: "C#、Java、TypeScript での典型的な GroupDocs.Viewer 操作のいくつかの使用例"
  items:
    # code sample loop
    - title: "DOCX ファイルを PDF にレンダリングする方法"
      content: |
       Microsoft Word やその他のソフトウェアをインストールしなくても、DOCX ドキュメントを PDF にレンダリングできます。 Web アプリケーションでもデスクトップ アプリケーションでも、.NET アプリケーション内で DOCX ファイルを簡単にロードして表示できます。以下は、DOCX ファイルを PDF にレンダリングする方法の例です。
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // レンダリングするDOCXファイルをロードします
            using (Viewer viewer = new Viewer("sample.docx"))
            {
              // DOCX を PDF ファイルにレンダリングする
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
            // レンダリングするDOCXファイルをロードします
            try (Viewer viewer = new Viewer("sample.docx")) {
                // DOCX を PDF ファイルにレンダリングする
                PdfViewOptions viewOptions = new PdfViewOptions();
                viewer.view(viewOptions);
            }
            ```
        - language: "TypeScript"
          color: "green"
          content: |
            ```javascript {style=abap}  
            // レンダリングするDOCXファイルをロードします
            const viewer = new groupdocs.viewer.Viewer("sample.docx")
            
            // DOCX を PDF ファイルにレンダリングする
            const viewOptions = groupdocs.viewer.PdfViewOptions(output.pdf)
            viewer.view(viewOptions)
            ```

        - language: "Python"
          color: "yellow"
          content: |
            ```python {style=abap} 
            import groupdocs.viewer as gv
            import groupdocs.viewer.options as gvo   
            // レンダリングするDOCXファイルをロードします
            with gv.Viewer("sample.docx") as viewer:
            
            // DOCX を PDF ファイルにレンダリングする
            viewOptions = gvo.PdfViewOptions("output.pdf")
            viewer.view(viewOptions)
            ```

############################# Formats ############################
formats:
  enable: true
  title:  "180 以上のファイル形式をサポート"
  description: "GroupDocs.Viewer は、最も一般的な [ファイル形式](https://docs.groupdocs.com/viewer/net/supported-document-formats/) での操作をサポートしています。"


############################# Metrics ############################

metrics:
  enable: true
  title: "詳細な指標と統計的洞察"
  description: "当社の主要な数値を詳細に分析し、当社の業績、影響、成長に関する包括的な指標と統計的洞察を提供します。"

  items:
    # metrics loop
    - number: "180+"
      title: "サポートされている形式"
      content: "ドキュメント、画像、CAD 図面などの 180 を超えるファイル形式を手間なく簡単に表示できます。当社の包括的な表示ソリューションを使用すると、互換性の壁を打ち破り、さまざまなファイルに簡単にアクセスできます。"
    # metrics loop
    - number: "1.0M"
      title: "NuGetのダウンロード"
      content: "当社の NuGet パッケージ ソリューションは、開発者コミュニティで信頼され広く採用されているリソースとなり、無数のプロジェクトにシームレスな統合と貴重な機能を提供します。"

    # metrics loop
    - number: "10+"
      title: "図書館"
      content: "当社の製品には 10 以上のライブラリが含まれており、パフォーマンスを最適化するための高度な機能を提供します。これらのライブラリは、比類のない機能でさまざまな開発ニーズを満たすように設計されています。"
    
    # metrics loop
    - number: "100+"
      title: "幸せな顧客"
      content: "世界中の最も象徴的なブランドにサービスを提供しています。何人もが GroupDocs.Viewer を愛用する理由を発見してください。シームレスなナビゲーション、便利なコラボレーション、比類のない使いやすさを体験してください。今すぐ参加してください！"


############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "幸せなお客様"
  description: "GroupDocs ライブラリは、世界中の世界的に有名な有名ブランドで採用されています。"

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
  title: "始める準備はできていますか?"
  description: "GroupDocs.Viewer の機能を無料で試すか、ライセンスをリクエストしてください"

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
  title: "よくある質問と懸念事項"
  description: "FAQセクションで一般的な質問に対する回答を見つけて、質問や懸念事項にすぐに対処してください。"

  items:
    #  loop
    - question: "購入前に GroupDocs 製品を評価できますか?"
      answer: |
        はい！すべての GroupDocs 製品には、リスクのない評価版が用意されています。開発者には、お客様のニーズを 100% 満たすことを確認するために、購入前に API をダウンロードして試してみることを強くお勧めします。
    #  loop
    - question: "GroupDocs は製品のデモンストレーションを行いますか?"
      answer: |
        いいえ、私たちは API と、可能な限り最も機能的で安定した製品を作ることに重点を置いています。製品をご自身でテストできるように、[一時ライセンス](https://purchase.groupdocs.com/temporary-license/) の形式で完全な機能の無料トライアルを提供しています。
    #  loop
    - question: "製品はどこでダウンロードできますか?"
      answer: |
        すべての製品は、[Web サイト](https://releases.groupdocs.com) からダウンロードできます。ソフトウェアの物理コピーを郵送することはありません。    
    #  loop
    - question: "GroupDocs 開発者ライセンスはユーザーごとですか、それとも指定ユーザーごとですか?"
      answer: |
        GroupDocs Developer ライセンスは、指定ユーザーごとではなく、ユーザーごとに付与されます。私たちは、コーディング チームのメンバーは時間の経過とともに変わる可能性があり、そのたびにライセンスを更新する必要があるのは現実的ではないことを理解しています。
    #  loop
    - question: "アクティブな開発者のみにライセンスが必要ですか?たとえば、2 人の開発者からなるチームがシフト A で作業し、2 人の開発者からなる 2 番目のチームがシフト B で作業しているとします。この状況では、2 つまたは 4 つのライセンスが必要でしょうか?"
      answer: |
        プロジェクトに取り組むすべての開発者はライセンスを取得する必要があります。この状況では、GroupDocs はチームに 4 人のメンバーがいると見なします (たとえメンバーが異なる時間に働いていたとしても)。

############################# Cloud ############################

cloud_links:
  enable: true
  title: "GroupDocs.Viewer ローコード API"
  description: "クラウドベースの REST API を使用して、あらゆるタイプのアプリケーションでドキュメントや画像の表示を高速化します。"

  items:
    #  loop
    - icon: "groupdocs_viewer-for-curl"
      title: "GroupDocs.Viewer Cloud for cURL"
      link: "https://products.groupdocs.cloud/viewer/curl"
      content: "cURL RESTful ドキュメント ビューア API を使用して、Microsoft Office、PDF、およびその他のさまざまな標準ファイル形式をアプリケーションで効率的にレンダリングして表示します。"

    #  loop
    - icon: "groupdocs_viewer-for-net"
      title: "GroupDocs.Viewer Cloud for .NET"
      link: "https://products.groupdocs.cloud/viewer/net"
      content: "Cloud SDK for .NET を使用して、.NET アプリケーションのドキュメント表示機能を強化します。 HTML、PDF、または画像形式でドキュメントをシームレスに表示します。"
    #  loop
    - icon: "groupdocs_viewer-for-java"
      title: "GroupDocs.Viewer Cloud for Java"
      link: "https://products.groupdocs.cloud/viewer/java"
      content: "Java 専用の Document Viewer SDK を使用して、高度なドキュメント レンダリング機能を Java アプリケーションに統合します。"

############################# Apps ############################

app_links:
  enable: true
  title: "GroupDocs.Viewer NoCode アプリ"
  description: "180 以上の一般的なファイル形式をブラウザで表示できるオンライン アプリケーション"

  items:
    #  loop
    - icon: "groupdocs_viewer-app"
      title: "GroupDocs.Viewer Total"
      link: "https://products.groupdocs.app/viewer/total"
      content: "無料のオンライン アプリケーションを探索して、お好みの Web ブラウザから 180 以上のファイル形式を直接表示してください。"

    #  loop
    - icon: "groupdocs_words-app"
      title:  "GroupDocs.Viewer DOCX"
      link: "https://products.groupdocs.app/viewer/docx"
      content: "さまざまなデバイスで Microsoft Word ファイルを簡単に表示できる Web ベースのツール。"

    #  loop
    - icon: "groupdocs_pdf-app"
      title:  "GroupDocs.Viewer PDF"
      link: "https://products.groupdocs.app/viewer/pdf"
      content: "無料の PDF ビューアを使用して、オンラインで PDF ファイルを開いて表示します。"
    

---