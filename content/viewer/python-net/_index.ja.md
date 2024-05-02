---
############################# Static ############################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: ja
product: "Viewer"
product_tag: "viewer"
platform: "Python via .NET"
platform_tag: "python-net"

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
    # supported_platforms loop
    - title: "Python"
      tag: "python-net" 


############################# Head ############################
head_title: "PythonドキュメントビューアーAPI (PDF、Word、Excel、HTML、画像、電子メール向け)"
head_description: "PythonファイルレンダリングおよびドキュメントビューアーAPI。PythonアプリケーションにPDFビューアー、Wordビューアー、Excelビューアー、画像ビューアー、HTMLビューアー、および電子メールビューアーを追加します。"

############################# Header ############################
title: "最適化されたドキュメントレンダリングのための強力なPython API"
description: "強力なAPIと汎用的な構成オプションを使用して、Pythonアプリケーションで180を超えるドキュメント形式 (PDF、HTML、画像) をレンダリングして表示します。"
words:
  for: "for"

actions:
  main: "PyPIから無料でダウンロード"
  main_link: "https://pypi.org/project/groupdocs-viewer/"
  alt: "ライセンス"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/python-net"
  title: "始める準備はできていますか?"
  description: "GroupDocs.Viewer の機能を無料で試すか、ライセンスをリクエストしてください"

release:
  title: "{0} がリリースされました"
  notes: "新機能を見る"
  downloads: "ダウンロード"
  link: "https://releases.groupdocs.com/viewer/python-net/release-notes/latest/"

code:
  title: "PythonでのPDFファイルのレンダリング"
  more: "他の例"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-Python-via-.NET"
  install: "pip install GroupDocs.Viewer"
  content: |
    ```python {style=abap}
    import groupdocs.viewer as gv
    import groupdocs.viewer.options as gvo
    hvo = gvo.HtmlViewOptions  
  
    // 出力HTMLオプションを設定 (1ページあたりの1ファイル)
    with gv.Viewer("resume.docx") as viewer:
      // ビューアーをインスタンス化
      opts = hvo.for_embedded_resources("page_{0}.html")

      // 埋め込みリソースを使用したPDFからHTMLへのレンダリング
      viewer.view(opts)
    ```
############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Viewerの概要"
  description: "Pythonアプリケーションでドキュメント、スライド、図表、およびその他の多くのドキュメントタイプのレンダリング、表示、変換を行うためのAPI"
  features:
    # feature loop
    - title: "ドキュメントを効率的かつ確実に表示"
      content: "GroupDocs.Viewer APIを使用すると、サポートされているすべての形式のドキュメントを柔軟で強力なオプションを使用してHTML、JPEG、PNG、およびPDFに効率的にレンダリングでき、コンテンツとドキュメント構造の整合性を維持できます。GroupDocs.Viewer for Pythonは、WindowsおよびLinuxプラットフォームで動作します。"

    # feature loop
    - title: "最も人気のあるファイル形式とドキュメント形式がサポートされています"
      content: "Word、Excel、PDF、PowerPoint、OpenDocument形式ファミリ、アーカイブ、ラスターおよびベクター画像、電子ブック、プログラミング言語とマークアップ、およびパスワード保護による暗号化ファイルを含む、180を超える最も人気のあるファイル形式とドキュメント形式のレンダリングをサポートしています。"

    # feature loop
    - title: "カスタマイズ可能な出力"
      content: "GroupDocs.Viewerを使用すると、ドキュメントのレンダリングだけでなく、レンダリングする必要のあるドキュメントの部分を正確に制御したり、レンダリング方法を制御したり、レンダリングされた出力にさまざまな変換を適用したりすることもできます。"

############################# Platforms ############################
platforms:
  enable: true
  title: "プラットフォーム非依存性"
  description: "GroupDocs.Viewer for Pythonは、以下のオペレーティングシステム、フレームワーク、およびパッケージマネージャーをサポートしています"
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
    - title: "PyPI"
      image: "pypi"

############################# File formats ############################
formats:
  enable: true
  title: "サポートされているファイル形式"
  description: |
    GroupDocs.Viewer for Python (via .NET)は、以下のファイル形式に対する操作をサポートしています: [サポートされているファイル形式](https://docs.groupdocs.com/viewer/python-net/supported-document-formats/).
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
  description: "Python経由の.Netを使用したGroupDocs.Viewerの操作の典型的なユースケース"
  items:
    # code sample loop
    - title: "DOCXをHTMLに変換"
      content: |
        ``HtmlViewOptions`` クラスのプロパティを使用すると、変換プロセスを制御できます。詳細については、[こちら](https://docs.groupdocs.com/viewer/python-net/rendering-to-html/)を参照してください。 たとえば、すべての外部リソースを出力HTMLファイルに埋め込む、出力ファイルを圧縮する、印刷用に最適化することができます。
        {{< landing/code title="Python">}}
        ```python {style=abap}
        import groupdocs.viewer as gv
        import groupdocs.viewer.options as gvo 

        // ビューアーをインスタンス化
        with gv.Viewer("resume.docx") as viewer:
          // 出力HTMLオプションを設定 (1ページあたりの1ファイル)
          viewOptions = gvo.HtmlViewOptions.for_embedded_resources("page_{0}.html")
          // 埋め込みリソースを使用したPDFからHTMLへのレンダリング
          viewer.view(viewOptions)
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "PPTXをPDFにエクスポート"
      content: |
        ``PdfViewOptions`` クラスのインスタンスを作成し、``Viewer.view`` メソッドに渡して、PowerPoint PPTXファイルをPDFに変換します。 ``PdfViewOptions`` クラスのプロパティを使用すると、変換プロセスを制御できます。たとえば、出力PDFファイルを保護したり、ページの順序を変更したり、ドキュメントの画像の品質を指定したりできます。詳細については、[次のドキュメントセクション](https://docs.groupdocs.com/viewer/python-net/rendering-to-pdf/)を参照してください。
        {{< landing/code title="JavaScript">}}
        ```python {style=abap}
        import groupdocs.viewer as gv
        import groupdocs.viewer.options as gvo  

        // ビューアーをインスタンス化
        with gv.Viewer("presentation.pptx") as viewer:
          // 出力PDFオプションを設定 (Set output PDF options)
          viewOptions = gvo.PdfViewOptions("presentation.pdf")
          // PPTXをPDFにエクスポート (Export PPTX to PDF)
          viewer.view(viewOptions)
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
