---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: tr

############################# Head #############################
head_title: ".NET J2K Viewer API - C# VB.NET'te Oku, Görüntüle, Oluştur"
head_description: "J2K dosyasını her tür C#, ASP.NET, VB.NET ve .NET Core uygulamasında okumak, işlemek ve görüntülemek için .NET belge görüntüleyici API'si."

############################# Header ############################
title: "C# .NET Uygulamaları İçin J2K Dosya Görüntüleyici" 
description: "J2K dosyasını her türden C#, ASP.NET, VB.NET ve .NET Core uygulamalarında okumak, işlemek ve görüntülemek için .NET belge görüntüleyici API'si. İşlenen dosyaları HTML5, PDF veya birkaç satır kod kullanarak bir görüntü olarak gerçek biçimlendirme ve düzen ile görüntüleyin." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Ücretsiz deneme sürümünü indirin"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: ".NET API için GroupDocs.Viewer hakkında" 
    content: |
        Birkaç satır kod ekleyerek .NET API'leri için GroupDocs.Viewer'ı kullanarak .NET uygulamalarınızda 190'dan fazla popüler belge biçimini görüntülemeye başlayın. Geliştiriciler PDF, Kelime İşleme, Excel Elektronik Tablosu, Sunum, Visio, Proje, Outlook ve diğer birçok popüler belge formatını HTML5, görüntü veya PDF modlarında kolayca görüntüleyebilir. Belge oluşturma hızlıdır, orijinal kaynak dosyayla aynıdır ve ek yazılım veya başka herhangi bir harici kitaplığın yüklenmesini gerektirmez.

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
              text: "API Referansı"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "Kod Örnekleri"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "Canlı Demolar"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "Fiyatlandırma"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "J2K dosyasını C# içinde Oluşturma Adımları" 
    content_left: |
        [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/) ile J2K dosyasını birkaç adımda HTML, JPEG, PNG veya PDF'ye dönüştürebilirsiniz.

        * Favori paket yöneticinizi kullanarak [GroupDocs.Viewer for .NET](https://www.nuget.org/packages/groupdocs.viewer) yükleyin. 
        * Viewer sınıfının bir örneğini oluşturun ve J2K dosyasını tam yolla yükleyin. 
        * J2K dosyasını HTML, PNG, JPEG veya PDF formatına dönüştürmek için seçenekleri ayarlayın. 
        * Dosyayı işleyin ve geçerli dizindeki çıktıyı kontrol edin. 
        
    title_right: "sistem gereksinimleri" 
    content_right: |
        .NET API'leri için GroupDocs.Viewer, tüm büyük platformlarda ve işletim sistemlerinde desteklenir. Aşağıdaki kodu çalıştırmadan önce lütfen sisteminizde aşağıdaki önkoşulların yüklü olduğundan emin olun.

        * İşletim Sistemleri: Microsoft Windows, Linux, MacOS 
        * Geliştirme Ortamları: Microsoft Visual Studio, Visual Studio Code, .NET CLI 
        * Çerçeveler: .NET Çerçevesi, .NET Standardı, .NET Core, .NET 
    code: |
        ```cs
                        
            // Set up input J2K file
            string filePath = "input.j2k";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render J2K file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "J2K İzleyici Canlı Demosu"
    content: |
        [GroupDocs.Viewer Çevrimiçi Uygulamaları](https://products.groupdocs.app/viewer/j2k) web sitesini ziyaret ederek J2K dosyasını hemen görüntüleyin.
    lang: "tr"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "C# Kullanarak Oluşturma ve Görüntüleme Diğer Dosya Biçimleri"
    exclude: "J2K"
    content: |
        .NET için çok formatlı belgeler ve resim görüntüleyici API'si. Herhangi bir harici görüntüleyici olmadan aşağıdaki popüler dosya biçimlerinden bazılarını görüntüleyin.
    format: 
        # format loop 1
        - name: "DOCX'i Oluştur"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word Açık XML Belgesi" 

        # format loop 2
        - name: "CDR'yi Oluştur" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "CorelDRAW Dosyası" 

        # format loop 3
        - name: "PPTX'i Oluştur"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint Açık XML Sunumu" 

        # format loop 4
        - name: "XLSX'i Oluştur"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel Açık XML Elektronik Tablosu" 

        # format loop 5
        - name: "DWG'yi Oluştur"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "AutoCAD Çizimi"

        # format loop 6
        - name: "XML'i Oluştur"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "XML Dosyası"

        # format loop 7
        - name: "PSD'yi Oluştur"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Adobe Photoshop Belgesi"

        # format loop 8
        - name: "Adobe Illustrator dosyasını işleyin"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Adobe Illustrator Çizimi"

        # format loop 9
        - name: "Belge Oluştur"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Microsoft Word Belgesi" 

        # format loop 10
        - name: "TXT'yi oluştur" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "Düz Metin Dosyası" 

        # format loop 11
        - name: "DXF'yi Oluştur" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "Çizim Değişim Formatı Dosyası"  
          
        # format loop 12
        - name: "VCF'yi Oluştur"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "vCard Dosyası"  
              
        # format loop 13
        - name: "SVG'yi oluştur"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "Ölçeklenebilir Vektör Grafiği" 
          
        # format loop 14
        - name: "HTML'yi Oluştur"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "Köprü Metni İşaretleme Dili Dosyası" 
          
        # format loop 15
        - name: "PDF Oluştur"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "Taşınabilir Belge Biçimi Dosyası"
          
        # format loop 16
        - name: "JPEG oluştur"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "JPEG Görüntüsü"
          
        # format loop 17
        - name: "PNG'yi oluştur"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "Taşınabilir Ağ Grafiği" 
          
        # format loop 18
        - name: "EML'yi oluştur"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "E-posta mesajı" 
          
        # format loop 19
        - name: "RTF'yi oluştur"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "Zengin Metin Biçimi Dosyası" 
          
        # format loop 20
        - name: "ODT'yi oluştur"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "OpenDocument Metin Belgesi" 
          
        # format loop 21
        - name: "CSV'yi oluştur"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "Virgülle Ayrılmış Değerler Dosyası" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
