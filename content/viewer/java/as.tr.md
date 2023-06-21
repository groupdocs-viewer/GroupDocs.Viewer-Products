---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: tr

############################# Head #############################
head_title: "Java AS Görüntüleyici API'si - Java Uygulamalarında AS Oluşturun ve Görüntüleyin"
head_description: "AS dosyalarını Java, J2EE, J2SE uygulamalarında görüntüleyin. Belge görüntüleme seçeneklerini yönetmek için gelişmiş özelliklerle HTML, PDF veya görüntü modunda 170'den fazla belge ve görüntü dosyası formatını görüntülemeyi destekler."

############################# Header ############################
title: "Java'da AS Oluşturun ve Görüntüleyin" 
description: "Java, J2EE ve J2SE tabanlı uygulamalar için yerel ve yüksek performanslı AS dosya görüntüleyici API'si, çıktı belge biçiminin görünümünü özelleştirmek için çok çeşitli ek özellikleri destekler." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "Ücretsiz deneme sürümünü indirin"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "GroupDocs.Viewer for Java API hakkında" 
    content: |
        Java API'leri için GroupDocs.Viewer'ı herhangi bir ek yazılım yüklemeden kullanarak Java uygulamalarınızın HTML, PDF veya görüntü modlarında 170'den fazla dosya biçimini görüntülemesini sağlayın; Microsoft Office, Apache Open Office, Adobe Acrobat Reader vb. Geliştiriciler, Microsoft Office, OpenDocument, HTML, PDF, Archive, Diagrams, Photoshop, AutoCAD ve programlama dili formatları da dahil olmak üzere tüm popüler görsel ve belge türlerini Java uygulamaları içerisinde kolayca görüntüleyebilirler. hızlı ve en yüksek kalitede render.

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
    title_left: "AS dosyasını Java içinde Oluşturma Adımları" 
    content_left: |
        [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/) ile AS dosyasını birkaç adımda HTML, JPEG, PNG veya PDF'ye dönüştürebilirsiniz.

        * Projenize bir bağımlılık olarak [GroupDocs.Viewer for Java](https://releases.groupdocs.com/viewer/java/) ekleyin. 
        * Viewer sınıfının bir örneğini oluşturun ve AS dosyasını tam yolla yükleyin. 
        * AS dosyasını HTML, PNG, JPEG veya PDF formatına dönüştürmek için seçenekleri ayarlayın. 
        * Dosyayı işleyin ve geçerli dizindeki çıktıyı kontrol edin. 
        
    title_right: "sistem gereksinimleri" 
    content_right: |
        Java API'leri için GroupDocs.Viewer, tüm büyük platformlarda ve işletim sistemlerinde desteklenir. Aşağıdaki kodu çalıştırmadan önce lütfen sisteminizde aşağıdaki önkoşulların yüklü olduğundan emin olun.

        * İşletim Sistemleri: Microsoft Windows, Linux, MacOS 
        * Geliştirme Ortamları: NetBeans, IntelliJ IDEA, Eclipse vb. 
        * Çerçeveler: J2SE 8.0 (1.8) veya üzeri (örneğin Java 17) 
    code: |
        ```java
                        
            // Set up input AS file
            String filePath = "input.as";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render AS file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "AS İzleyici Canlı Demosu"
    content: |
        [GroupDocs.Viewer Çevrimiçi Uygulamaları](https://products.groupdocs.app/viewer/as) web sitesini ziyaret ederek AS dosyasını hemen görüntüleyin.
    lang: "tr"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Java Kullanarak Oluşturma ve Görüntüleme Diğer Dosya Biçimleri"
    exclude: "AS"
    content: |
        Java için çok formatlı belgeler ve resim görüntüleyici API'si. Herhangi bir harici görüntüleyici olmadan aşağıdaki popüler dosya biçimlerinden bazılarını görüntüleyin.
    format: 
        # format loop 1
        - name: "DOCX'i Oluştur"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word Açık XML Belgesi" 

        # format loop 2
        - name: "CDR'yi Oluştur" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "CorelDRAW Dosyası" 

        # format loop 3
        - name: "PPTX'i Oluştur"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint Açık XML Sunumu" 

        # format loop 4
        - name: "XLSX'i Oluştur"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel Açık XML Elektronik Tablosu" 

        # format loop 5
        - name: "DWG'yi Oluştur"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "AutoCAD Çizimi"

        # format loop 6
        - name: "XML'i Oluştur"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "XML Dosyası"

        # format loop 7
        - name: "PSD'yi Oluştur"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Adobe Photoshop Belgesi"

        # format loop 8
        - name: "Adobe Illustrator dosyasını işleyin"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Adobe Illustrator Çizimi"

        # format loop 9
        - name: "Belge Oluştur"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Microsoft Word Belgesi" 

        # format loop 10
        - name: "TXT'yi oluştur" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "Düz Metin Dosyası" 

        # format loop 11
        - name: "DXF'yi Oluştur" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "Çizim Değişim Formatı Dosyası"  
          
        # format loop 12
        - name: "VCF'yi Oluştur"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "vCard Dosyası"  
              
        # format loop 13
        - name: "SVG'yi oluştur"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "Ölçeklenebilir Vektör Grafiği" 
          
        # format loop 14
        - name: "HTML'yi Oluştur"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "Köprü Metni İşaretleme Dili Dosyası" 
          
        # format loop 15
        - name: "PDF Oluştur"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "Taşınabilir Belge Biçimi Dosyası"
          
        # format loop 16
        - name: "JPEG oluştur"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "JPEG Görüntüsü"
          
        # format loop 17
        - name: "PNG'yi oluştur"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "Taşınabilir Ağ Grafiği" 
          
        # format loop 18
        - name: "EML'yi oluştur"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "E-posta mesajı" 
          
        # format loop 19
        - name: "RTF'yi oluştur"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "Zengin Metin Biçimi Dosyası" 
          
        # format loop 20
        - name: "ODT'yi oluştur"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "OpenDocument Metin Belgesi" 
          
        # format loop 21
        - name: "CSV'yi oluştur"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "Virgülle Ayrılmış Değerler Dosyası" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
