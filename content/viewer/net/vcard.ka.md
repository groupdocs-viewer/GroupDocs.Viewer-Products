---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: ka

############################# Head #############################
head_title: ".NET vCard Viewer API - წაკითხვა, ნახვა, რენდერი C#-ში VB.NET"
head_description: ".NET დოკუმენტის მაყურებლის API წასაკითხად, რენდერით და გამოსატანად vCard ნებისმიერი ტიპის C#, ASP.NET, VB.NET და .NET Core აპლიკაციებში."

############################# Header ############################
title: "vCard ფაილების მაყურებელი C# .NET აპლიკაციებისთვის" 
description: ".NET დოკუმენტის მაყურებლის API წაიკითხოს, რენდერი და აჩვენოს vCard ფაილი ნებისმიერი ტიპის C#, ASP.NET, VB.NET და .NET Core აპლიკაციებში. იხილეთ გადაღებული ფაილები ნამდვილი ფორმატირებით და განლაგებით HTML5, PDF ან გამოსახულების სახით კოდის რამდენიმე სტრიქონის გამოყენებით." 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "ჩამოტვირთეთ უფასო საცდელი"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "GroupDocs.Viewer-ის შესახებ .NET API-სთვის" 
    content: |
        დაიწყეთ 190+ პოპულარული დოკუმენტის ფორმატის ნახვა თქვენს .NET აპლიკაციებში GroupDocs.Viewer-ის გამოყენებით .NET API-ებისთვის რამდენიმე სტრიქონის კოდის დამატებით. დეველოპერებს შეუძლიათ მარტივად აჩვენონ PDF, Word Processing, Excel Spreadsheet, Presentation, Visio, Project, Outlook და მრავალი სხვა პოპულარული დოკუმენტის ფორმატები HTML5, image ან PDF რეჟიმში. დოკუმენტის გადმოცემა სწრაფია, ორიგინალური წყაროს ფაილის იდენტურია და არ საჭიროებს დამატებითი პროგრამული უზრუნველყოფის ან სხვა გარე ბიბლიოთეკების ინსტალაციას.

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
    title_left: "ნაბიჯები vCard ფაილის რენდერისთვის C#-ში" 
    content_left: |
        [GroupDocs.Viewer]-ით (https://products.groupdocs.com/viewer/net/) შეგიძლიათ გადაიტანოთ vCard HTML, JPEG, PNG ან PDF-ზე რამდენიმე ნაბიჯით.

        * დააინსტალირეთ [GroupDocs.Viewer for .NET](https://www.nuget.org/packages/groupdocs.viewer) თქვენი საყვარელი პაკეტის მენეჯერის გამოყენებით. 
        * შექმენით Viewer კლასის მაგალითი და ჩატვირთეთ vCard ფაილი სრული ბილიკით. 
        * დააყენეთ პარამეტრები vCard ფაილის HTML, PNG, JPEG ან PDF ფორმატში გადასატანად. 
        * ფაილის რენდერი და შემოწმება მიმდინარე დირექტორიაში. 
        
    title_right: "სისტემის მოთხოვნები" 
    content_right: |
        GroupDocs.Viewer .NET API-ებისთვის მხარდაჭერილია ყველა ძირითად პლატფორმაზე და ოპერაციულ სისტემაზე. ქვემოთ მოცემული კოდის შესრულებამდე, გთხოვთ, დარწმუნდეთ, რომ თქვენს სისტემაში დაყენებულია შემდეგი წინაპირობები.

        * ოპერაციული სისტემები: Microsoft Windows, Linux, MacOS 
        * განვითარების გარემო: Microsoft Visual Studio, Visual Studio Code, .NET CLI 
        * Frameworks: .NET Framework, .NET Standard, .NET Core, .NET 
    code: |
        ```cs
                        
            // Set up input vCard file
            string filePath = "input.vcf";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render vCard file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "vCard მნახველის ცოცხალი დემო"
    content: |
        იხილეთ vCard ფაილი ახლავე, ეწვიეთ [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/vcf) ვებსაიტს.
    lang: "ka"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "ფაილის სხვა ფორმატების რენდერი და ნახვა C#-ის გამოყენებით"
    exclude: "vCard"
    content: |
        მრავალფორმატიანი დოკუმენტებისა და სურათების მაყურებლის API .NET-ისთვის. იხილეთ ზოგიერთი პოპულარული ფაილის ფორმატი ქვემოთ ყოველგვარი გარე მნახველების გარეშე.
    format: 
        # format loop 1
        - name: "რენდერი DOCX"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "Microsoft Word ღია XML დოკუმენტი" 

        # format loop 2
        - name: "რენდერი CDR" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "CorelDRAW ფაილი" 

        # format loop 3
        - name: "რენდერი PPTX"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "PowerPoint გახსენით XML პრეზენტაცია" 

        # format loop 4
        - name: "რენდერი XLSX"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "Microsoft Excel გახსენით XML ცხრილი" 

        # format loop 5
        - name: "რენდერი DWG"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "AutoCAD ნახაზი"

        # format loop 6
        - name: "რენდერი XML"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "XML ფაილი"

        # format loop 7
        - name: "რენდერი PSD"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "Adobe Photoshop დოკუმენტი"

        # format loop 8
        - name: "Adobe Illustrator ფაილის რენდერი"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "Adobe Illustrator ნამუშევრები"

        # format loop 9
        - name: "რენდერი DOC"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "Microsoft Word დოკუმენტი" 

        # format loop 10
        - name: "რენდერი TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "უბრალო ტექსტური ფაილი" 

        # format loop 11
        - name: "რენდერი DXF" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "ნახაზის გაცვლის ფორმატის ფაილი"  
          
        # format loop 12
        - name: "რენდერი VCF"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "vCard ფაილი"  
              
        # format loop 13
        - name: "რენდერი SVG"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "მასშტაბირებადი ვექტორული გრაფიკა" 
          
        # format loop 14
        - name: "რენდერი HTML"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "ჰიპერტექსტის მარკირების ენის ფაილი" 
          
        # format loop 15
        - name: "რენდერი PDF"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "პორტატული დოკუმენტის ფორმატის ფაილი"
          
        # format loop 16
        - name: "JPEG რენდერი"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "JPEG გამოსახულება"
          
        # format loop 17
        - name: "რენდერი PNG"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "პორტატული ქსელური გრაფიკა" 
          
        # format loop 18
        - name: "რენდერი EML"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "ელ.ფოსტის შეტყობინება" 
          
        # format loop 19
        - name: "რენდერი RTF"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "მდიდარი ტექსტის ფორმატის ფაილი" 
          
        # format loop 20
        - name: "რენდერი ODT"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "OpenDocument ტექსტური დოკუმენტი" 
          
        # format loop 21
        - name: "რენდერი CSV"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "მძიმით გამოყოფილი მნიშვნელობების ფაილი" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
