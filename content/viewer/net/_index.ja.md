---
############################# Static ##########################
layout: "landing"
date: 2023-06-29T12:38:08
draft: false

lang: ja
product: "Viewer"
product_tag: "viewer"
platform: ".NET"
platform_tag: "net"

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
head_title: ".NET ドキュメント ビューア API、PDF Word Excel 画像 HTML 図のレンダリング"
head_description: "C# ASP.NET ファイル ビューアとレンダリング API。 .NET アプリに PDF ビューア、Word ビューア、Excel ビューア、画像ビューア、HTML ビューア、電子メール ビューア機能を追加します。"

############################# Header ##########################
title: ".NET APIを使用した<br>ドキュメントのレンダリングと表示"
description: "多彩な構成オプションを使用して、180 を超えるドキュメント形式を PDF、HTML、および画像にレンダリングする強力なビューア API。"
words:
  for: "for"

actions:
  main: "無料の NuGet ダウンロード"
  main_link: "https://www.nuget.org/packages/GroupDocs.Viewer"
  alt: "ライセンス"
  alt_link: "https://purchase.groupdocs.com/pricing/viewer/net"
  title: "始める準備はできていますか?"
  description: "GroupDocs.Viewer の機能を無料で試すか、ライセンスをリクエストしてください"

release:
  title: "{0} がリリースされました"
  notes: "新機能を見る"
  downloads: "ダウンロード"
  link: "https://releases.groupdocs.com/viewer/net/release-notes/latest/"

code:
  title: "C# で PDF ファイルをレンダリングする"
  more: "他の例"
  more_link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
  install: "dotnet add package GroupDocs.Viewer"
  content: |
    ```csharp {style=abap}   
    // ソース PDF ファイルをロードします
    using (var viewer = new Viewer("resume.pdf"))
    {
        // 出力 HTML オプションを設定します
        var viewOptions = 
        HtmlViewOptions.ForEmbeddedResources("page{0}.html");
        
        // 埋め込みリソースを使用して PDF を HTML        
        viewer.View(viewOptions);
    }
    ```

############################# Overview ############################
overview:
  enable: true
  title: "GroupDocs.Viewer の概要"
  description: ".NET アプリケーションでドキュメント、スライド、図、その他多くの種類のドキュメントをレンダリング、表示、変換するための API"
  features:
    # feature loop
    - title: "ドキュメントを効率的かつ確実に表示する"
      content: "GroupDocs.Viewer API を使用すると、コンテンツとドキュメント構造の整合性を維持しながら、柔軟で強力なオプションを使用して、サポート可能な形式のドキュメントを HTML、JPEG、PNG、PDF に効率的にレンダリングできます。 GroupDocs.Viewer は .NET Framework 4.6.2 および .NET 6.0 をサポートしており、Windows および Linux プラットフォームで動作します。"

    # feature loop
    - title: "最も一般的なファイルおよびドキュメント形式がサポートされています"
      content: "Word、Excel、PDF、PowerPoint、OpenDocument 形式ファミリー、アーカイブ、ラスター画像とベクター画像、電子書籍、プログラミング言語とマークアップ、および暗号化されたファイルを含むその他の多くのファイル タイプを含む、180 を超える最も一般的なファイルおよびドキュメント形式のレンダリングをサポートしています。パスワードで保護されたファイル。"

    # feature loop
    - title: "カスタマイズ可能な出力"
      content: "GroupDocs.Viewer を使用すると、ドキュメントをレンダリングするだけでなく、ドキュメントのどの部分をレンダリングするか、現時点でどのようにレンダリングするかを正確に制御し、レンダリングされた出力にさまざまな変換を適用することもできます。"

    # feature loop
    - title: "ASP.NET Core の UI"
      content: "数分でプロジェクトに追加できる ASP.NET Core 用のオープン ソース UI パッケージが提供されます。 Viewer.UI パッケージには、Angular ベースの Web UI が含まれており、便利な API とデータ ストレージ プロバイダーのセットを提供します。"

############################# Platforms ############################
platforms:
  enable: true
  title: "プラットフォームの独立性"
  description: "GroupDocs.Viewer for .NET は、次のオペレーティング システム、フレームワーク、パッケージ マネージャーをサポートしています。"
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
    - title: "VS Code"
      image: "vs_code"
    # platform loop
    - title: "ReSharper"
      image: "resharper"
    # platform loop
    - title: "macOS"
      image: "finder"
    # platform loop
    - title: "Linux"
      image: "linux"
    # platform loop
    - title: "NuGet"
      image: "nuget"

############################# File formats ############################
formats:
  enable: true
  title: "サポートされているファイル形式"
  description: |
    GroupDocs.Viewer for .NET は、次の [ファイル形式](https://docs.groupdocs.com/viewer/net/supported-document-formats/) での操作をサポートします。
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
  description: ".NET 操作用の典型的な GroupDocs.Viewer の使用例"
  items:
    # code sample loop
    - title: "DOCX を HTML にレンダリングする"
      content: |
        [HtmlViewOptions](https://reference.groupdocs.com/viewer/net/groupdocs.viewer.options/htmlviewoptions/) クラス プロパティを使用すると、変換プロセスを制御できます。詳細については、[こちら](https://docs.groupdocs.com/viewer/net/rendering-to-html/)。 たとえば、すべての外部リソースを出力 HTML ファイルに埋め込み、出力ファイルを縮小して、印刷用に最適化することができます。
        {{< landing/code title="C#">}}
        ```csharp {style=abap}
        using GroupDocs.Viewer;
        using GroupDocs.Viewer.Options;
        
        // ビューアをインスタンス化する
        using (Viewer viewer = new Viewer("resume.docx"))
        {
            // 出力HTMLオプションを設定する
            HtmlViewOptions options = HtmlViewOptions.ForEmbeddedResources();
            
            // 埋め込みリソースを使用して DOCX を HTML にレンダリングします
            viewer.View(options);
        }
        ```
        {{< /landing/code >}}
    # code sample loop
    - title: "PPTXをPDFにエクスポート"
      content: |
        [PdfViewOptions](https://reference.groupdocs.com/viewer/net/groupdocs.viewer.options/pdfviewoptions/) クラス インスタンスを作成し、それを [Viewer.View](https://reference.groupdocs.com/viewer/net/groupdocs.viewer/viewer/view/#view) メソッドを使用して、PowerPoint PPTX ファイルを PDF に変換します。 PdfViewOptions クラスのプロパティを使用すると、変換プロセスを制御できます。たとえば、出力 PDF ファイルを保護したり、ページの順序を変更したり、ドキュメントの画像の品質を指定したりできます。詳細については、[次のドキュメント セクション](https://docs.groupdocs.com/viewer/net/rendering-to-pdf/) を参照してください。
        {{< landing/code title="C#">}}
        ```csharp {style=abap}   
        using GroupDocs.Viewer;
        using GroupDocs.Viewer.Options;
        
        using (var viewer = new Viewer("presentation.pptx"))
        {
            // 出力 PDF オプションを設定する       
            var viewOptions = new PdfViewOptions("presentation.pdf");
            
            // PPTXをPDFにエクスポート       
            viewer.View(viewOptions);
        }
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