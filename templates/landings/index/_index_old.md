---
############################# Static ##########################
layout: "product"
date: 2022-02-23T12:00:00+02:00
draft: false
lang: <% lower (get "lang") %>
product: "Viewer"
product_tag: "viewer"

############################# Head ############################
head_title: "<% "{index-content.head_title}" %>"
head_description: "<% "{index-content.head_description}" %>"

############################# Header ##########################
title: "<% "{index-content.title}" %>"
description: "<% "{index-content.description}" %>"

############################# APIs ############################
apis:
  enable: true

  api:
    # api loop
    - title: "<% "{index-content.api_high_title}" %>"
      link: "/viewer/"
      label: "<% "{index-content.api_high_label}" %>"
      api_product:
        # api_product loop
        - link: "/viewer/net/"
          img_alt: "GroupDocs.Viewer for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-viewer-net.png"
          product: "GroupDocs.Viewer for"
          platform: ".NET"
          content: "<% "{index-content.api_high_1_content}" %>"

        # api_product loop
        - link: "/viewer/java/"
          img_alt: "GroupDocs.Viewer for Java"
          image: "https://www.groupdocs.cloud/templates/groupdocs/images/product-logos/groupdocs-viewer-java.png"
          product: "GroupDocs.Viewer for"
          platform: "Java"
          content: "<% "{index-content.api_high_2_content}" %>"

    # api loop
    - title: "<% "{index-content.api_low_title}" %>"
      link: "https://products.groupdocs.cloud/viewer"
      label: "<% "{index-content.api_low_label}" %>"
      api_product:
        # api_product loop
        - link: "https://products.groupdocs.cloud/viewer/curl"
          img_alt: "GroupDocs.Viewer Cloud for cURL"
          image: "https://www.groupdocs.cloud/templates/groupdocscloud/images/sdk/272x272/groupdocs_viewer-for-curl.png"
          product: "GroupDocs.Viewer"
          platform: "Cloud for cURL"
          content: "<% "{index-content.api_low_1_content}" %>"

        # api_product loop
        - link: "https://products.groupdocs.cloud/viewer/net"
          img_alt: "GroupDocs.Viewer Cloud SDK for .NET"
          image: "https://www.groupdocs.cloud/templates/groupdocscloud/images/sdk/272x272/groupdocs_viewer-for-net.png"
          product: "GroupDocs.Viewer"
          platform: "Cloud SDK for .NET"
          content: "<% "{index-content.api_low_2_content}" %>"

        # api_product loop
        - link: "https://products.groupdocs.cloud/viewer/java"
          img_alt: "GroupDocs.Viewer Cloud SDK for Java"
          image: "https://www.groupdocs.cloud/templates/groupdocscloud/images/sdk/272x272/groupdocs_viewer-for-java.png"
          product: "GroupDocs.Viewer"
          platform: "Cloud SDK for Java"
          content: "<% "{index-content.api_low_3_content}" %>"

    # api loop
    - title: "<% "{index-content.api_nocode_title}" %>" 
      link: "https://products.groupdocs.app/viewer"
      label: "<% "{index-content.api_nocodelabel}" %>"
      api_product:
        # api_product loop
        - link: "https://products.groupdocs.app/viewer/total"
          img_alt: "GroupDocs.Viewer Total"
          image: "https://www.aspose.cloud/templates/asposeapp/images/products/logo/aspose_viewer-app.png"
          product: "GroupDocs.Viewer"
          platform: "Total"
          content: "<% "{index-content.api_nocode_1_content}" %>"

        # api_product loop
        - link: "https://products.groupdocs.app/viewer/docx"
          img_alt: "GroupDocs.Viewer DOCX"
          image: "https://www.aspose.cloud/templates/groupdocsapp/images/products/logo/groupdocs_words-app.png"
          product: "GroupDocs.Viewer"
          platform: "DOCX"
          content: "<% "{index-content.api_nocode_2_content}" %>"

        # api_product loop
        - link: "https://products.groupdocs.app/viewer/pdf"
          img_alt: "GroupDocs.Viewer PDF"
          image: "https://www.aspose.cloud/templates/groupdocsapp/images/products/logo/groupdocs_pdf-app.png"
          product: "GroupDocs.Viewer"
          platform: "PDF"
          content: "<% "{index-content.api_nocode_3_content}" %>"

############################# Testimonials ###############################
testimonials:
  enable: true
  bg_color: "bg-gray"

  testimonial:
    # testimonial item loop
    - name: "Margot Baill"
      designation: "<% "{index-content.testimonial_1_designation}" %>"
      content: "<% "{index-content.testimonial_1_content}" %>"

    # testimonial item loop
    - name: "Mats Oustad"
      designation: "<% "{index-content.testimonial_2_designation}" %>"
      content: "<% "{index-content.testimonial_2_content}" %>"
              
    # testimonial item loop
    - name: "Martin Lasarga"
      designation: "<% "{index-content.testimonial_3_designation}" %>"
      content: "<% "{index-content.testimonial_3_content}" %>"

############################# Back to top ###############################
back_to_top:
  enable: true
---
