---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: ka

############################# Head #############################
head_title: "Java ODP Viewer API - რენდერი და ჩვენება ODP Java აპებში"
head_description: "ნახეთ ODP ფაილი Java, J2EE, J2SE აპლიკაციებში. მხარს უჭერს 170+ დოკუმენტისა და სურათის ფაილის ფორმატის ნახვას HTML, PDF ან გამოსახულების რეჟიმში გაფართოებული ფუნქციებით დოკუმენტის ნახვის ვარიანტების მართვისთვის."

############################# Header ############################
title: "რენდერი და ნახვა ODP Java-ში" 
description: "მშობლიური და მაღალი ხარისხის ODP ფაილის მაყურებლის API Java, J2EE და J2SE დაფუძნებული აპლიკაციებისთვის, რომელიც მხარს უჭერს დამატებითი ფუნქციების ფართო სპექტრს გამომავალი დოკუმენტის ფორმატის გარეგნობის მორგებისთვის." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "ჩამოტვირთეთ უფასო საცდელი"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "GroupDocs.Viewer-ის შესახებ Java API-სთვის" 
    content: |
        ჩართეთ თქვენი Java აპლიკაციების ჩვენება 170+ ფაილის ფორმატში HTML, PDF ან გამოსახულების რეჟიმებში GroupDocs.Viewer Java API-ებისთვის დამატებითი პროგრამული უზრუნველყოფის დაყენების გარეშე; როგორიცაა Microsoft Office, Apache Open Office, Adobe Acrobat Reader და ა.შ. დეველოპერებს შეუძლიათ ადვილად ნახონ ყველა პოპულარული სურათი და დოკუმენტის ტიპი, მათ შორის Microsoft Office, OpenDocument, HTML, PDF, არქივი, დიაგრამები, Photoshop, AutoCAD და პროგრამირების ენის ფორმატები Java აპლიკაციების შიგნით. სწრაფი და უმაღლესი ხარისხის რენდერირება.

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
              text: "API მითითება"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "კოდის მაგალითები"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "ცოცხალი დემო"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "ფასი"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "ნაბიჯები ODP ფაილის რენდერისთვის Java-ში" 
    content_left: |
        [GroupDocs.Viewer]-ით (https://products.groupdocs.com/viewer/java/) შეგიძლიათ გადაიტანოთ ODP HTML, JPEG, PNG ან PDF-ზე რამდენიმე ნაბიჯით.

        * დაამატეთ [GroupDocs.Viewer for Java](https://releases.groupdocs.com/viewer/java/) თქვენს პროექტზე დამოკიდებულების სახით. 
        * შექმენით Viewer კლასის მაგალითი და ჩატვირთეთ ODP ფაილი სრული ბილიკით. 
        * დააყენეთ პარამეტრები ODP ფაილის HTML, PNG, JPEG ან PDF ფორმატში გადასატანად. 
        * ფაილის რენდერი და შემოწმება მიმდინარე დირექტორიაში. 
        
    title_right: "სისტემის მოთხოვნები" 
    content_right: |
        GroupDocs.Viewer Java API-ებისთვის მხარდაჭერილია ყველა ძირითად პლატფორმაზე და ოპერაციულ სისტემაზე. ქვემოთ მოცემული კოდის შესრულებამდე, გთხოვთ, დარწმუნდეთ, რომ თქვენს სისტემაში დაყენებულია შემდეგი წინაპირობები.

        * ოპერაციული სისტემები: Microsoft Windows, Linux, MacOS 
        * განვითარების გარემო: NetBeans, IntelliJ IDEA, Eclipse და ა.შ. 
        * ჩარჩოები: J2SE 8.0 (1.8) ან უფრო მაღალი (მაგალითად Java 17) 
    code: |
        ```java
                        
            // Set up input ODP file
            String filePath = "input.odp";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render ODP file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "ODP მნახველის ცოცხალი დემო"
    content: |
        იხილეთ ODP ფაილი ახლავე, ეწვიეთ [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/odp) ვებსაიტს.
    lang: "ka"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "ფაილის სხვა ფორმატების რენდერი და ნახვა Java-ის გამოყენებით"
    exclude: "ODP"
    content: |
        მრავალფორმატიანი დოკუმენტების და სურათების მაყურებლის API Java-სთვის. იხილეთ ზოგიერთი პოპულარული ფაილის ფორმატი ქვემოთ ყოველგვარი გარე მნახველების გარეშე.
    format: 
        # format loop 1
        - name: "რენდერი DOCX"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "Microsoft Word ღია XML დოკუმენტი" 

        # format loop 2
        - name: "რენდერი CDR" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "CorelDRAW ფაილი" 

        # format loop 3
        - name: "რენდერი PPTX"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "PowerPoint გახსენით XML პრეზენტაცია" 

        # format loop 4
        - name: "რენდერი XLSX"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "Microsoft Excel გახსენით XML ცხრილი" 

        # format loop 5
        - name: "რენდერი DWG"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "AutoCAD ნახაზი"

        # format loop 6
        - name: "რენდერი XML"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "XML ფაილი"

        # format loop 7
        - name: "რენდერი PSD"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "Adobe Photoshop დოკუმენტი"

        # format loop 8
        - name: "Adobe Illustrator ფაილის რენდერი"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "Adobe Illustrator ნამუშევრები"

        # format loop 9
        - name: "რენდერი DOC"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "Microsoft Word დოკუმენტი" 

        # format loop 10
        - name: "რენდერი TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "უბრალო ტექსტური ფაილი" 

        # format loop 11
        - name: "რენდერი DXF" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "ნახაზის გაცვლის ფორმატის ფაილი"  
          
        # format loop 12
        - name: "რენდერი VCF"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "vCard ფაილი"  
              
        # format loop 13
        - name: "რენდერი SVG"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "მასშტაბირებადი ვექტორული გრაფიკა" 
          
        # format loop 14
        - name: "რენდერი HTML"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "ჰიპერტექსტის მარკირების ენის ფაილი" 
          
        # format loop 15
        - name: "რენდერი PDF"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "პორტატული დოკუმენტის ფორმატის ფაილი"
          
        # format loop 16
        - name: "JPEG რენდერი"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "JPEG გამოსახულება"
          
        # format loop 17
        - name: "რენდერი PNG"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "პორტატული ქსელური გრაფიკა" 
          
        # format loop 18
        - name: "რენდერი EML"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "ელ.ფოსტის შეტყობინება" 
          
        # format loop 19
        - name: "რენდერი RTF"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "მდიდარი ტექსტის ფორმატის ფაილი" 
          
        # format loop 20
        - name: "რენდერი ODT"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "OpenDocument ტექსტური დოკუმენტი" 
          
        # format loop 21
        - name: "რენდერი CSV"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "მძიმით გამოყოფილი მნიშვნელობების ფაილი" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
