---
############################# Static ############################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: ja
product: "Viewer"
product_tag: "viewer"
platform: "Node.js via Java"
platform_tag: "nodejs-java"

############################# Drop-down ############################
supported_platforms:
  items:
    # supported_platforms loop
    - title: ".NET"
      tag: "net"
    # supported_platforms loop
    - title: "Java"
      tag: "java"
    # supported_platforms loop
    - title: "Node.js"
      tag: "nodejs-java" 


############################# Head ############################
head_title: "PDF Word Excel HTML 画像と電子メール用の Node.js ドキュメント ビューア API"
head_description: "Node.js ドキュメント ビューアとファイル レンダリング API。 JavaScript アプリケーションに PDF ビューア、Word ビューア、Excel ビューア、画像ビューア、HTML ビューア、電子メール ビューアを追加します。"

############################# Header ############################
title: "ドキュメントをレンダリングおよび表示するための Node.js API"
description: "180 以上のファイル形式をサポートするマルチ形式ドキュメントをネイティブにレンダリング、表示、操作する JavaScript アプリケーションを開発するためのドキュメント ビューア ライブラリ。"
words:
  for: "for"

actions:
  main: "NPM の無料ダウンロード"
  main_link: "https://www.npmjs.com/package/@groupdocs/groupdocs.viewer"
  alt: "ライセンス"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/nodejs-java"
  title: "始める準備はできていますか?"
  description: "GroupDocs.Viewer の機能を無料で試すか、ライセンスをリクエストしてください"

release:
  title: "バージョン {0} がリリースされました"
  notes: "新機能を見る"
  downloads: "ダウンロード"
  link: "https://releases.groupdocs.com/viewer/nodejs-java/release-notes/latest/"

code:
  title: "JavaScript で PDF ファイルをレンダリングする"
  more: "他の例"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Node.js-via-Java"
  install: "npm i @groupdocs/groupdocs.viewer"
  content: |
    ```javascript {style=abap}   
    //Set output HTML options, one file per page
    const viewOptions = HtmlViewOptions.forEmbeddedResources()

    // Instantiate Viewer
    const viewer = new Viewer("resume.pdf")

    // Render PDF to HTML with embedded resources
    viewer.view(viewOptions)
    viewer.close()
    ```
############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Viewer の概要"
  description: "Node.js アプリケーションでドキュメント、スライド、図、その他多くのドキュメント タイプをレンダリング、表示、変換するための API"
  features:
    # feature loop
    - title: "ドキュメントを効率的かつ確実に表示する"
      content: "GroupDocs.Viewer API を使用すると、コンテンツとドキュメント構造の整合性を維持しながら、柔軟で強力なオプションを使用して、サポート可能な形式のドキュメントを HTML、JPEG、PNG、PDF に効率的にレンダリングできます。 Node.js 用の GroupDocs.Viewer は、Windows および Linux プラットフォームで動作します。"

    # feature loop
    - title: "最も一般的なファイルおよびドキュメント形式がサポートされています"
      content: "Word、Excel、PDF、PowerPoint、OpenDocument 形式ファミリー、アーカイブ、ラスター画像とベクター画像、電子書籍、プログラミング言語とマークアップ、および暗号化されたファイルを含むその他の多くのファイル タイプを含む、180 を超える最も一般的なファイルおよびドキュメント形式のレンダリングをサポートしています。パスワードで保護されたファイル。"

    # feature loop
    - title: "カスタマイズ可能な出力"
      content: "GroupDocs.Viewer を使用すると、ドキュメントをレンダリングするだけでなく、ドキュメントのどの部分をレンダリングするか、現時点でどのようにレンダリングするかを正確に制御し、レンダリングされた出力にさまざまな変換を適用することもできます。"

############################# Platforms ############################
platforms:
  enable: true
  title: "プラットフォームの独立性"
  description: "Node.js 用 GroupDocs.Viewer は、次のオペレーティング システム、フレームワーク、パッケージ マネージャーをサポートしています。"
  items:
    # platform loop
    - title: "Amazon"
      image: "amazon"
    # platform loop
    - title: "Docker"
      image: "docker"
    # platform loop
    - title: "Azure"
      image: "azure"
    # platform loop
    - title: "Eclipse"
      image: "eclipse"
    # platform loop
    - title: "IntelliJ"
      image: "intellij"
    # platform loop
    - title: "Windows"
      image: "windows"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "NPM"
      image: "npm"

############################# File formats ############################
formats:
  enable: true
  title: "サポートされているファイル形式"
  description: |
    Java 経由の Node.js 用 GroupDocs.Viewer は、次の [ファイル形式](https://docs.groupdocs.com/viewer/nodejs-java/supported-document-formats/) での操作をサポートします。
  groups:
    # group loop
    - color: "green"
      content: |
        ### Microsoft Office、OpenDocument、およびテキスト形式
        * **Word:** DOC, DOCX, DOCM, DOT, DOTX, DOTM, RTF, TXT
        * **Excel:** XLS, XLSX, XLSM, XLSB, XLTM, XLT, XLTM, XLTX
        * **PowerPoint:** PPT, PPTX, PPS, PPSX, PPSM, POT, POTM, POTX, PPTM        
        * **Project:** MPP, MPT, MPX
        * **Outlook:** MSG, EML, EMLX, PST, OST
        * **OneNote:** ONE
        * **OpenDocument:** ODT, OTT, ODS, ODP, OTP, OTS, ODG
        * **Fixed Page Layout:** PDF, TEX, XPS, OXPS
        * **e-Books:** EPUB, MOBI, DjVu
        * **Delimiter-Separated Values:** CSV, TSV
    # group loop
    - color: "blue"
      content: |
        ### 画像、グラフィック、図表
        * **ラスター画像:** BMP, GIF, JPG, PNG, TIFF, WebP, DNG, DIB, Jpeg2000 family
        * **Windows Icon:** ICO
        * **Scalable Vector Graphics:** SVG, CDR, CMX, IGS, SVGZ        
        * **Adobe Photoshop:** PSD, PSB        
        * **Stereo Lithography (3D Printing):** STL        
        * **Medical Imaging:** DICOM
        * **Plotter Documents:** PLT, HPG
        * **Autodesk Design Web Formats:** DWF, DWG
        * **AutoCAD Drawing:** DWT, IFC, STL, CF2        
      # group loop
    - color: "red"
      content: |
        ### 他の        
        * **ウェブ:** HTML, MHT, MHTML, XML
        * **Metafile:** WMF, EMF, CGM, EMZ, WMZ
        * **Visio:** VSD, VDX, VSS, VSSX, VSX, VST, VSTX, VTX, VSDX, VDW, VSTM, VSSM, VSDM
        * **Project:** MPP, MPT, MPX
        * **PostScript:** PS, EPS
        * **アーカイブ:** ZIP, TAR, BZ2, GZ, RAR, RAR5
        * **他の:** VCF, VCARD, NUMBERS, NSF, OBJ
        * **C/C++/C# Files:** C, CC, C# , CPP, CXX, CS, H, HH, M, MM
        * **Java/JavaScript Files:** JAVA, JS, JSON, PROPERTIES

############################# Features ############################
features:
  enable: true
  title: "GroupDocs.Viewer の機能"
  description: "PDF および Office ドキュメントをシームレスにレンダリング、表示、変換"

  items:
    # feature loop
    - icon: "viewhtml"
      title: "HTML でドキュメントを表示する"
      content: "CSS と SVG を使用して、あらゆる種類のドキュメントを HTML ドキュメントに変換し、最新の Web ブラウザで表示できます。"

    # feature loop
    - icon: "rasterize"
      title: "ドキュメントをラスタライズする"
      content: "サポート可能なドキュメント形式をラスター画像にラスター化し、画像形式と圧縮品質を調整できます。"

    # feature loop
    - icon: "sourcecode"
      title: "プログラミング コードのレンダリングとハイライト表示"
      content: "すべての一般的なプログラミング、スクリプト、マークアップ言語をサポートし、構文を解析して強調表示する機能を備えています。"

    # feature loop
    - icon: "convertpdf"
      title: "PDFに変換"
      content: "サポート可能な形式のドキュメントは、調整可能なオプションを使用して簡単に PDF に変換して保存できます。"

    # feature loop
    - icon: "transform"
      title: "変換を適用する"
      content: "出力ドキュメントはレンダリング中に変換できます。ページは回転および/または再配置でき、テキストの透かしをその上に配置できます。"

    # feature loop
    - icon: "adjustment"
      title: "HTML出力調整"
      content: "GroupDocs.Viewer によって生成される出力 HTML ドキュメントは、非常に細かく調整できます。外部リソースまたは埋め込みリソース、コールバックなどを使用して、ストリームまたはファイルに保存できます。"

    # feature loop
    - icon: "complex"
      title: "複雑な文書構造のサポート"
      content: "GroupDocs.Viewer は、単一のドキュメントだけでなく、添付ファイル付きの電子メール メッセージ、フォルダー内の内部ファイルを含む ZIP アーカイブ、複数ページの TIFF 画像など、ドキュメントのリストまたは階層構造を内部に含むファイルもサポートします。"

    # feature loop
    - icon: "optimization"
      title: "最適化オプション"
      content: "GroupDocs.Viewer には、ドキュメントのキャッシュされたバージョンを使用することで読み込み時間を短縮できる、調整可能なキャッシュ サブシステムが含まれています。また、さまざまな形式に対応するさまざまなオプションのセットにより、ドキュメントの一部の不必要な部分や側面 (フォント、非表示のワークシート、電子メールの添付ファイル) をレンダリングから除外して、全体的なパフォーマンスを最適化することができます。"

    # feature loop
    - icon: "passwordprotected"
      title: "パスワードで保護されたドキュメントのサポート"
      content: "GroupDocs.Viewer を使用すると、読み込みオプションでパスワードを指定することで、PDF、WordProcessing、スプレッドシート、プレゼンテーションなど、さまざまな種類の暗号化されたドキュメントを開くことができます。"

############################# Code samples ############################
code_samples:
  enable: true
  title: "コードサンプル"
  description: "Java 操作による Node.js 用の典型的な GroupDocs.Viewer の使用例"
  items:
    # code sample loop
    - title: "DOCX を HTML にレンダリングする"
      content: |
        `HtmlViewOptions` クラス プロパティを使用すると、変換プロセスを制御できます。詳細については、[こちら](https://docs.groupdocs.com/viewer/nodejs-java/rendering-to-html/) を参照してください。 たとえば、すべての外部リソースを出力 HTML ファイルに埋め込み、出力ファイルを縮小して、印刷用に最適化することができます。
        {{< landing/code title="JavaScript">}}
        ```javascript {style=abap}
        import { Viewer, HtmlViewOptions } from '@groupdocs/groupdocs.viewer'

        //Set output HTML options, one file per page
        const viewOptions = HtmlViewOptions.forEmbeddedResources()

        // Instantiate Viewer
        const viewer = new Viewer("resume.docx")

        // Render PDF to HTML with embedded resources
        viewer.view(viewOptions)
        viewer.close()
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "PPTXをPDFにエクスポート"
      content: |
        `PdfViewOptions` クラス インスタンスを作成し、それを `Viewer.view` メソッドに渡して、PowerPoint PPTX ファイルを PDF に変換します。 `PdfViewOptions` クラス プロパティを使用すると、変換プロセスを制御できます。たとえば、出力 PDF ファイルを保護したり、ページの順序を変更したり、ドキュメントの画像の品質を指定したりできます。詳細については、[次のドキュメント セクション](https://docs.groupdocs.com/viewer/nodejs-java/rendering-to-pdf/) を参照してください。
        {{< landing/code title="JavaScript">}}
        ```javascript {style=abap}   
        import { Viewer, PdfViewOptions } from '@groupdocs/groupdocs.viewer'

        //Set output PDF options
        const viewOptions = new PdfViewOptions("presentation.pdf")

        // Instantiate Viewer
        const viewer = new Viewer("presentation.pptx")

        // Render PDF to HTML with embedded resources
        viewer.view(viewOptions)
        viewer.close()
        ```
        {{< /landing/code >}}
############################# Reviews ############################
# reviews:
# enable: true
# title: "GroupDocs 製品のレビュー"
# description: "私たちの言葉をそのまま鵜呑みにしないでください。他の開発者の API についての意見をご覧ください"

# items:
#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "優れたサービスと優れた製品。これらは、GroupDocs.Viewer for .NET の実装プロセス中に非常に役に立ち、迅速に対応してくれましたが、あまりお勧めできません。"
#     author: "Martin Lasarga"
#     company: "Product Manager at Axentria ECM by G.S.I."

#   # review loop
#   - title: "GroupDocs.Viewer"
#     content: "GroupDocs.Viewer for .NET をプロジェクトに実装して使用した後、非常にうまく機能しているように見えます。多くのドキュメントを使用してテストしましたが、これまでのところ良好です。私が投げたものはすべてうまくレンダリングされ、PDF ビューアーや MS Word と同じくらい見栄えがよくなります。"
#     author: "Mats Oustad"
#     company: "Senior Consultant/Partner at Novanet AS"
---
