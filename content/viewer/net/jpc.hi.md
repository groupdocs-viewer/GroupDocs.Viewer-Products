---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: hi

############################# Head #############################
head_title: ".NET JPC व्यूअर एपीआई - C# VB.NET में पढ़ें, देखें, रेंडर करें"
head_description: "किसी भी प्रकार के C#, ASP.NET, VB.NET और .NET कोर अनुप्रयोगों में JPC को पढ़ने, प्रस्तुत करने और प्रदर्शित करने के लिए .NET दस्तावेज़ व्यूअर API।"

############################# Header ############################
title: "JPC C# .NET अनुप्रयोगों के लिए फ़ाइल व्यूअर" 
description: "किसी भी प्रकार के C#, ASP.NET, VB.NET और .NET कोर अनुप्रयोगों में JPC फ़ाइल को पढ़ने, प्रस्तुत करने और प्रदर्शित करने के लिए .NET दस्तावेज़ व्यूअर API। एचटीएमएल 5, पीडीएफ में या कोड की कुछ पंक्तियों का उपयोग करके एक छवि के रूप में प्रस्तुत की गई फ़ाइलों को सही स्वरूपण और लेआउट के साथ देखें।" 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "नि: शुल्क परीक्षण डाउनलोड करें"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: ".NET API के लिए GroupDocs.Viewer के बारे में" 
    content: |
        कोड की कुछ पंक्तियों को जोड़कर .NET APIs के लिए GroupDocs.Viewer का उपयोग करके अपने .NET अनुप्रयोगों में 190+ लोकप्रिय दस्तावेज़ स्वरूपों को देखना प्रारंभ करें। डेवलपर्स HTML5, छवि या पीडीएफ मोड में आसानी से पीडीएफ, वर्ड प्रोसेसिंग, एक्सेल स्प्रेडशीट, प्रेजेंटेशन, विसिओ, प्रोजेक्ट, आउटलुक और कई अन्य लोकप्रिय दस्तावेज़ प्रारूप प्रदर्शित कर सकते हैं। दस्तावेज़ रेंडरिंग तेज़ है, मूल स्रोत फ़ाइल के समान है, और इसके लिए अतिरिक्त सॉफ़्टवेयर या किसी अन्य बाहरी लाइब्रेरी को स्थापित करने की आवश्यकता नहीं है।

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
              text: "एपीआई संदर्भ"

            # button loop
            - link: "https://github.com/groupdocs-viewer/GroupDocs.Viewer-for-.NET"
              text: "कोड उदाहरण"

            # button loop
            - link: "https://products.groupdocs.app/viewer/family"
              text: "लाइव डेमो"

            # button loop
            - link: "https://purchase.groupdocs.com/pricing/viewer/net"
              text: "मूल्य निर्धारण"

    right:
        link_download: "https://downloads.groupdocs.com/viewer/net"
        link_learn: "https://docs.groupdocs.com/viewer/net"
        link_buy: "https://purchase.groupdocs.com"

############################# Steps ############################
steps:
    enable: true
    title_left: "C# में JPC फ़ाइल रेंडर करने के चरण" 
    content_left: |
        [GroupDocs.Viewer](https://products.groupdocs.com/viewer/net/) से आप कुछ चरणों में JPC को HTML, JPEG, PNG या PDF में रेंडर कर सकते हैं।

        * अपने पसंदीदा पैकेज मैनेजर का इस्तेमाल करके [GroupDocs.Viewer for .NET](https://www.nuget.org/packages/groupdocs.viewer) इंस्टॉल करें। 
        * व्यूअर वर्ग का एक उदाहरण बनाएं और JPC फ़ाइल को पूर्ण पथ के साथ लोड करें। 
        * JPC फ़ाइल को HTML, PNG, JPEG या PDF स्वरूप में रेंडर करने के लिए विकल्प सेट करें। 
        * फ़ाइल रेंडर करें और वर्तमान निर्देशिका में आउटपुट जांचें। 
        
    title_right: "सिस्टम आवश्यकताएं" 
    content_right: |
        .NET API के लिए GroupDocs.Viewer सभी प्रमुख प्लेटफॉर्म और ऑपरेटिंग सिस्टम पर समर्थित हैं। नीचे दिए गए कोड को निष्पादित करने से पहले, कृपया सुनिश्चित करें कि आपके सिस्टम पर निम्नलिखित पूर्वापेक्षाएँ स्थापित हैं।

        * ऑपरेटिंग सिस्टम: माइक्रोसॉफ्ट विंडोज, लिनक्स, मैकओएस 
        * विकास वातावरण: Microsoft विज़ुअल स्टूडियो, विज़ुअल स्टूडियो कोड, .NET CLI 
        * फ्रेमवर्क: .NET फ्रेमवर्क, .NET स्टैंडर्ड, .NET कोर, .NET 
    code: |
        ```cs
                        
            // Set up input JPC file
            string filePath = "input.jpc";
        
            // Instantiate Viewer
            using (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.ForEmbeddedResources();
                    
            	// Render JPC file to HTML with embedded resources
            	viewer.View(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "JPC दर्शक लाइव डेमो"
    content: |
        [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/jpc) वेबसाइट पर जाकर अभी JPC फ़ाइल देखें।
    lang: "hi"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "C# का उपयोग करके अन्य फ़ाइल स्वरूपों का प्रतिपादन और देखना"
    exclude: "JPC"
    content: |
        .NET के लिए बहु-प्रारूप दस्तावेज़ और छवि व्यूअर API। नीचे दिए गए कुछ लोकप्रिय फ़ाइल स्वरूपों को बिना किसी बाहरी दर्शकों के देखें।
    format: 
        # format loop 1
        - name: "DOCX प्रस्तुत करें"
          format: "DOCX"
          link: "/viewer/net/docx/"
          description: "माइक्रोसॉफ्ट वर्ड ओपन एक्सएमएल दस्तावेज़" 

        # format loop 2
        - name: "सीडीआर प्रस्तुत करें" 
          format: "CDR"
          link: "/viewer/net/cdr/"
          description: "कोरल ड्रॉ फ़ाइल" 

        # format loop 3
        - name: "पीपीटीएक्स प्रस्तुत करें"
          format: "PPTX"
          link: "/viewer/net/pptx/"
          description: "पावरपॉइंट ओपन एक्सएमएल प्रस्तुति" 

        # format loop 4
        - name: "एक्सएलएसएक्स प्रस्तुत करें"
          format: "XLSX"
          link: "/viewer/net/xlsx/"
          description: "माइक्रोसॉफ्ट एक्सेल ओपन एक्सएमएल स्प्रेडशीट" 

        # format loop 5
        - name: "DWG प्रस्तुत करें"
          format: "DWG"
          link: "/viewer/net/dwg/"
          description: "ऑटोकैड ड्राइंग"

        # format loop 6
        - name: "रेंडर एक्सएमएल"
          format: "XML"
          link: "/viewer/net/xml/"
          description: "एक्सएमएल फ़ाइल"

        # format loop 7
        - name: "PSD प्रस्तुत करें"
          format: "PSD"
          link: "/viewer/net/psd/"
          description: "एडोब फोटोशॉप दस्तावेज़"

        # format loop 8
        - name: "एडोब इलस्ट्रेटर फ़ाइल प्रस्तुत करें"
          format: "AI"
          link: "/viewer/net/ai/"
          description: "एडोब इलस्ट्रेटर कलाकृति"

        # format loop 9
        - name: "रेंडर डीओसी"
          format: "DOC"
          link: "/viewer/net/doc/"
          description: "माइक्रोसॉफ्ट वर्ड दस्तावेज़" 

        # format loop 10
        - name: "रेंडर TXT" 
          format: "TXT"
          link: "/viewer/net/txt/"
          description: "सादा पाठ फ़ाइल" 

        # format loop 11
        - name: "डीएक्सएफ प्रस्तुत करें" 
          format: "DXF"
          link: "/viewer/net/dxf/"
          description: "ड्राइंग एक्सचेंज प्रारूप फ़ाइल"  
          
        # format loop 12
        - name: "वीसीएफ प्रस्तुत करें"
          format: "VCF"
          link: "/viewer/net/vcf/"
          description: "वीकार्ड फ़ाइल"  
              
        # format loop 13
        - name: "एसवीजी प्रस्तुत करें"
          format: "SVG"
          link: "/viewer/net/svg/"
          description: "स्केलेबल वेक्टर ग्राफिक" 
          
        # format loop 14
        - name: "एचटीएमएल प्रस्तुत करें"
          format: "HTML"
          link: "/viewer/net/html/"
          description: "हाइपरटेक्स्ट मार्कअप लैंग्वेज फ़ाइल" 
          
        # format loop 15
        - name: "पीडीएफ प्रस्तुत करें"
          format: "PDF"
          link: "/viewer/net/pdf/"
          description: "पोर्टेबल दस्तावेज़ स्वरूप फ़ाइल"
          
        # format loop 16
        - name: "जेपीईजी प्रस्तुत करें"
          format: "JPG"
          link: "/viewer/net/jpg/"
          description: "जेपीईजी छवि"
          
        # format loop 17
        - name: "पीएनजी प्रस्तुत करें"
          format: "PNG"
          link: "/viewer/net/png/"
          description: "पोर्टेबल नेटवर्क ग्राफिक" 
          
        # format loop 18
        - name: "ईएमएल प्रस्तुत करें"
          format: "EML"
          link: "/viewer/net/eml/"
          description: "विद्युतडाक संदेश" 
          
        # format loop 19
        - name: "आरटीएफ प्रस्तुत करें"
          format: "RTF"
          link: "/viewer/net/rtf/"
          description: "रिच टेक्स्ट फ़ॉर्मेट फ़ाइल" 
          
        # format loop 20
        - name: "ओडीटी प्रस्तुत करें"
          format: "ODT"
          link: "/viewer/net/odt/"
          description: "OpenDocument पाठ दस्तावेज़" 
          
        # format loop 21
        - name: "सीएसवी प्रस्तुत करें"
          format: "CSV"
          link: "/viewer/net/csv/"
          description: "अल्पविराम से अलग किए गए मान फ़ाइल" 
          
        # format loop 21
        - name: "{format-content-net.more_formats_name_xps}"
          format: "XPS"
          link: "/viewer/net/xps/"
          description: "{format-content-net.more_formats_description_xps}" 

############################# Back to top ###############################
back_to_top:
    enable: true
---
