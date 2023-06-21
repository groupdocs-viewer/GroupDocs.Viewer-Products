---
############################# Static ############################
layout: "auto-gen-viewer"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: hi

############################# Head #############################
head_title: "Java EMLX Viewer API - Java Apps में रेंडर और डिस्प्ले EMLX"
head_description: "Java, J2EE, J2SE अनुप्रयोगों में EMLX फ़ाइलें देखें। दस्तावेज़ देखने के विकल्पों को प्रबंधित करने के लिए उन्नत सुविधाओं के साथ एचटीएमएल, पीडीएफ या छवि मोड में 170+ दस्तावेज़ और छवि फ़ाइल स्वरूपों को देखने का समर्थन करता है।"

############################# Header ############################
title: "जावा में EMLX प्रस्तुत करें और देखें" 
description: "Java, J2EE और J2SE आधारित अनुप्रयोगों के लिए नेटिव और उच्च प्रदर्शन EMLX फ़ाइल व्यूअर API, आउटपुट दस्तावेज़ स्वरूप के स्वरूप को अनुकूलित करने के लिए अतिरिक्त सुविधाओं की एक विस्तृत श्रृंखला का समर्थन करता है।" 

bg_overlay: false
button:
    enable: true
    icon: "fas fa-arrow-down"
    label: "नि: शुल्क परीक्षण डाउनलोड करें"
    link: "https://releases.groupdocs.com/viewer/net"

############################# About ############################
about:
    enable: true
    title: "Java API के लिए GroupDocs.Viewer के बारे में" 
    content: |
        GroupDocs का उपयोग करके HTML, PDF या छवि मोड में 170+ से अधिक फ़ाइल स्वरूपों को प्रदर्शित करने के लिए अपने जावा अनुप्रयोगों को सक्षम करें। बिना किसी अतिरिक्त सॉफ़्टवेयर को स्थापित किए Java API के लिए व्यूअर; जैसे माइक्रोसॉफ्ट ऑफिस, अपाचे ओपन ऑफिस, एडोब एक्रोबैट रीडर इत्यादि। डेवलपर्स आसानी से जावा अनुप्रयोगों के अंदर माइक्रोसॉफ्ट ऑफिस, ओपन डॉक्यूमेंट, एचटीएमएल, पीडीएफ, आर्काइव, आरेख, फोटोशॉप, ऑटोकैड और प्रोग्रामिंग भाषा प्रारूपों सहित सभी लोकप्रिय छवियों और दस्तावेज़ प्रकारों को देख सकते हैं। तेज और उच्चतम गुणवत्ता प्रतिपादन।

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
    title_left: "Java में EMLX फ़ाइल रेंडर करने के चरण" 
    content_left: |
        [GroupDocs.Viewer](https://products.groupdocs.com/viewer/java/) से आप कुछ चरणों में EMLX को HTML, JPEG, PNG या PDF में रेंडर कर सकते हैं।

        * अपने प्रोजेक्ट की निर्भरता के रूप में [GroupDocs.Viewer for Java](https://releases.groupdocs.com/viewer/java/) जोड़ें। 
        * व्यूअर वर्ग का एक उदाहरण बनाएं और EMLX फ़ाइल को पूर्ण पथ के साथ लोड करें। 
        * EMLX फ़ाइल को HTML, PNG, JPEG या PDF स्वरूप में रेंडर करने के लिए विकल्प सेट करें। 
        * फ़ाइल रेंडर करें और वर्तमान निर्देशिका में आउटपुट जांचें। 
        
    title_right: "सिस्टम आवश्यकताएं" 
    content_right: |
        GroupDocs.Viewer for Java APIs सभी प्रमुख प्लेटफॉर्म और ऑपरेटिंग सिस्टम पर समर्थित हैं। नीचे दिए गए कोड को निष्पादित करने से पहले, कृपया सुनिश्चित करें कि आपके सिस्टम पर निम्नलिखित पूर्वापेक्षाएँ स्थापित हैं।

        * ऑपरेटिंग सिस्टम: माइक्रोसॉफ्ट विंडोज, लिनक्स, मैकओएस 
        * विकास का वातावरण: नेटबीन्स, इंटेलीज आईडिया, एक्लिप्स आदि। 
        * चौखटे: J2SE 8.0 (1.8) या ऊपर (उदाहरण के लिए जावा 17) 
    code: |
        ```java
                        
            // Set up input EMLX file
            String filePath = "input.emlx";
        
            // Instantiate Viewer
            try (Viewer viewer = new Viewer(filePath))
            {
            	// Set view options 
            	HtmlViewOptions viewOptions = HtmlViewOptions.forEmbeddedResources();
                    
            	// Render EMLX file to HTML with embedded resources
            	viewer.view(viewOptions);
            }
             
        ```
############################# Demos ############################
demos:
    enable: true
    title: "EMLX दर्शक लाइव डेमो"
    content: |
        [GroupDocs.Viewer Online Apps](https://products.groupdocs.app/viewer/emlx) वेबसाइट पर जाकर अभी EMLX फ़ाइल देखें।
    lang: "hi"

############################# About Formats ####################
about_formats:
    enable: false

############################# More Formats #####################
more_formats:
    enable: true
    title: "Java का उपयोग करके अन्य फ़ाइल स्वरूपों का प्रतिपादन और देखना"
    exclude: "EMLX"
    content: |
        जावा के लिए बहु-प्रारूप दस्तावेज़ और छवि दर्शक एपीआई। नीचे दिए गए कुछ लोकप्रिय फ़ाइल स्वरूपों को बिना किसी बाहरी दर्शकों के देखें।
    format: 
        # format loop 1
        - name: "DOCX प्रस्तुत करें"
          format: "DOCX"
          link: "/viewer/java/docx/"
          description: "माइक्रोसॉफ्ट वर्ड ओपन एक्सएमएल दस्तावेज़" 

        # format loop 2
        - name: "सीडीआर प्रस्तुत करें" 
          format: "CDR"
          link: "/viewer/java/cdr/"
          description: "कोरल ड्रॉ फ़ाइल" 

        # format loop 3
        - name: "पीपीटीएक्स प्रस्तुत करें"
          format: "PPTX"
          link: "/viewer/java/pptx/"
          description: "पावरपॉइंट ओपन एक्सएमएल प्रस्तुति" 

        # format loop 4
        - name: "एक्सएलएसएक्स प्रस्तुत करें"
          format: "XLSX"
          link: "/viewer/java/xlsx/"
          description: "माइक्रोसॉफ्ट एक्सेल ओपन एक्सएमएल स्प्रेडशीट" 

        # format loop 5
        - name: "DWG प्रस्तुत करें"
          format: "DWG"
          link: "/viewer/java/dwg/"
          description: "ऑटोकैड ड्राइंग"

        # format loop 6
        - name: "रेंडर एक्सएमएल"
          format: "XML"
          link: "/viewer/java/xml/"
          description: "एक्सएमएल फ़ाइल"

        # format loop 7
        - name: "PSD प्रस्तुत करें"
          format: "PSD"
          link: "/viewer/java/psd/"
          description: "एडोब फोटोशॉप दस्तावेज़"

        # format loop 8
        - name: "एडोब इलस्ट्रेटर फ़ाइल प्रस्तुत करें"
          format: "AI"
          link: "/viewer/java/ai/"
          description: "एडोब इलस्ट्रेटर कलाकृति"

        # format loop 9
        - name: "रेंडर डीओसी"
          format: "DOC"
          link: "/viewer/java/doc/"
          description: "माइक्रोसॉफ्ट वर्ड दस्तावेज़" 

        # format loop 10
        - name: "रेंडर TXT" 
          format: "TXT"
          link: "/viewer/java/txt/"
          description: "सादा पाठ फ़ाइल" 

        # format loop 11
        - name: "डीएक्सएफ प्रस्तुत करें" 
          format: "DXF"
          link: "/viewer/java/dxf/"
          description: "ड्राइंग एक्सचेंज प्रारूप फ़ाइल"  
          
        # format loop 12
        - name: "वीसीएफ प्रस्तुत करें"
          format: "VCF"
          link: "/viewer/java/vcf/"
          description: "वीकार्ड फ़ाइल"  
              
        # format loop 13
        - name: "एसवीजी प्रस्तुत करें"
          format: "SVG"
          link: "/viewer/java/svg/"
          description: "स्केलेबल वेक्टर ग्राफिक" 
          
        # format loop 14
        - name: "एचटीएमएल प्रस्तुत करें"
          format: "HTML"
          link: "/viewer/java/html/"
          description: "हाइपरटेक्स्ट मार्कअप लैंग्वेज फ़ाइल" 
          
        # format loop 15
        - name: "पीडीएफ प्रस्तुत करें"
          format: "PDF"
          link: "/viewer/java/pdf/"
          description: "पोर्टेबल दस्तावेज़ स्वरूप फ़ाइल"
          
        # format loop 16
        - name: "जेपीईजी प्रस्तुत करें"
          format: "JPG"
          link: "/viewer/java/jpg/"
          description: "जेपीईजी छवि"
          
        # format loop 17
        - name: "पीएनजी प्रस्तुत करें"
          format: "PNG"
          link: "/viewer/java/png/"
          description: "पोर्टेबल नेटवर्क ग्राफिक" 
          
        # format loop 18
        - name: "ईएमएल प्रस्तुत करें"
          format: "EML"
          link: "/viewer/java/eml/"
          description: "विद्युतडाक संदेश" 
          
        # format loop 19
        - name: "आरटीएफ प्रस्तुत करें"
          format: "RTF"
          link: "/viewer/java/rtf/"
          description: "रिच टेक्स्ट फ़ॉर्मेट फ़ाइल" 
          
        # format loop 20
        - name: "ओडीटी प्रस्तुत करें"
          format: "ODT"
          link: "/viewer/java/odt/"
          description: "OpenDocument पाठ दस्तावेज़" 
          
        # format loop 21
        - name: "सीएसवी प्रस्तुत करें"
          format: "CSV"
          link: "/viewer/java/csv/"
          description: "अल्पविराम से अलग किए गए मान फ़ाइल" 
          
############################# Back to top ###############################
back_to_top:
    enable: true
---
