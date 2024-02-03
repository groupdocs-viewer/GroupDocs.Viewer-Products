---
############################# Static ##########################
layout: "family"
date: 2023-12-20T06:39:57
draft: false

product: "Viewer"
product_tag: "viewer"

############################# Head ############################
head_title: "Render and View Documents API | On Premise API és online szolgáltatás"
head_description: "Rendereljen és tekintsen meg Word, PDF, Excel, Powerpoint vagy képfájlokat egyszerűen és ingyenesen"

############################# Header ##########################
title: "Rendereljen és tekintsen meg dokumentumokat könnyedén"
description: |
  Hatékony Viewer API a különböző fájlok PDF, HTML és kép formátumban való megjelenítéséhez.

  Töltsön be dokumentumokat különböző forrásokból, beleértve a fájlokat, adatfolyamokat, URL-eket, FTP-kiszolgálókat, Amazon S3-at, Azure Blob Storage-ot és egyebeket.

  Hozzon létre reszponzív HTML-oldalakat, védje meg a kimeneti PDF-fájlokat, rendezze át az oldalakat, forgassa el az oldalakat, jelenítsen meg jegyzeteket és megjegyzéseket, ha szükséges.

############################# Platforms ############################
supported_platforms:
  enable: true  
  head_title: "Válassza ki a platformját"
  title: "Támogatott platformok"
  description: "A GroupDocs.Viewer könyvtár a következő operációs rendszereket és keretrendszereket támogatja"
  details_link_title: "Tudj meg többet"
  items:
    # supported_platforms loop
    - title: ".NET"
      description: "GroupDocs.Viewer for .NET"
      color: "blue"
      tag: "net"
      link: "/viewer/net/"
      features_link: "https://docs.groupdocs.com/viewer/net/system-requirements/"
      features:
        # features loop
        - content: ".NET Framework 4.6.2+  <br>  .NET Core 3.1  <br>  .NET 6+"
          rows: "3"
        # features loop
        - content: "Windows, Linux"
          rows: "1"
        # features loop
        - content: "180+ fájlformátum"
          rows: "1"
        # features loop
        - content: "UI-csomag az ASP.NET Core számára"
          rows: "1"
        # features loop
        - content: "ASP.NET WebForms Demo  <br>  ASP.NET MVC Demo  <br>  ASP.NET Core Demo"
          rows: "3"
    
    # supported_platforms loop
    - title: "Java"
      description: "GroupDocs.Viewer for Java"
      color: "red"
      tag: "java"
      link: "/viewer/java/"
      features_link: "https://docs.groupdocs.com/viewer/java/system-requirements/"
      features:
        # features loop
        - content: "J2SE 8.0 (1.8)+"
          rows: "3"
        # features loop
        - content:  "Windows, Linux, macOS"
          rows: "1"       
        # features loop
        - content: "180+ fájlformátum"
          rows: "1"
        # features loop
        - content:  "UI-csomag a Spring és a Dropwizard számára"
          rows: "1"
        # features loop
        - content:  "Spring Demo  <br>  Dropwizard demo"
          rows: "3"

    # supported_platforms loop
    - title: "Node.js"
      description: "GroupDocs.Viewer for Node.js"
      color: "green"
      tag: "nodejs-java"
      link: "/viewer/nodejs-java/"
      features_link: "https://docs.groupdocs.com/viewer/nodejs-java/system-requirements/"
      features:
        # features loop
        - content: "Node.js 16+  <br>  and J2SE 8.0 (1.8)+"
          rows: "3"
        # features loop
        - content:  "Windows, Linux, macOS"
          rows: "1"
        # features loop
        - content:  "180+ fájlformátum"
          rows: "1"
        # features loop
        - content:  "UI csomag – hamarosan"
          rows: "1" 
        # features loop
        - content:  "Demo – hamarosan"
          rows: "3" 


############################# Features ############################

features:
  enable: true
  title: "A GroupDocs.Viewer szolgáltatáskészlete"
  description: "API különböző típusú, például HTML-, PDF-, PNG- és JPEG-fájlok megjelenítéséhez az alkalmazásokban, hogy azokat harmadik féltől származó szoftverek nélkül is megtekinthesse."

  items:
    # feature loop
    - icon: "view"
      title: "Dokumentumok és képek megtekintése"
      content: "Tekintse meg a dokumentumokat HTML-, PDF-, PNG- és JPEG-fájlokként."

    # feature loop
    - icon: "password"
      title: "Nyissa meg a védett dokumentumokat"
      content: "Adjon meg egy jelszót a titkosított dokumentumok megnyitásához."

    # feature loop
    - icon: "load"
      title: "Fájlok betöltése bárhonnan"
      content: "Töltsön be dokumentumokat különféle fájlokról, URL-ekről, FTP-szerverekről, Amazon S3-ról és egyebekről."
    
    # feature loop
    - icon: "pages"
      title: "Az összes vagy bizonyos oldalak megjelenítése"
      content: "Adja meg a megjelenítendő oldalszámok tartományát."


############################# Code samples ############################
code_samples:
  enable: true
  title: "GroupDocs.Viewer kódminták"
  description: "Egyes esetekben a tipikus GroupDocs.Viewer műveleteket használják C#, Java, TypeScript nyelven"
  items:
    # code sample loop
    - title: "Hogyan lehet DOCX fájlokat PDF formátumba renderelni"
      content: |
       A DOCX dokumentumokat PDF formátumba renderelheti Microsoft Word vagy más szoftver telepítése nélkül. Könnyedén tölthet be és tekinthet meg DOCX-fájlokat .NET-alkalmazásában, legyen szó webes vagy asztali alkalmazásról. Íme egy példa arra, hogyan lehet DOCX fájlt PDF formátumba renderelni:
      samples:
        - language: "C#"
          color: "blue"
          content: |
            ```csharp {style=abap}   
            // Töltsön be DOCX fájlt a rendereléshez
            using (Viewer viewer = new Viewer("sample.docx"))
            {
              // A DOCX renderelése PDF-fájlba
              PdfViewOptions viewOptions = new PdfViewOptions();
              viewer.View(viewOptions);
            }
            ```
        - language: "Java"
          color: "red"
          content: |
            ```java {style=abap}   
            import com.groupdocs.viewer.Viewer;
            import com.groupdocs.viewer.options.PdfViewOptions;
            // ...
            // Töltsön be DOCX fájlt a rendereléshez
            try (Viewer viewer = new Viewer("sample.docx")) {
                // A DOCX renderelése PDF-fájlba
                PdfViewOptions viewOptions = new PdfViewOptions();
                viewer.view(viewOptions);
            }
            ```
        - language: "TypeScript"
          color: "green"
          content: |
            ```javascript {style=abap}  
            // Töltsön be DOCX fájlt a rendereléshez
            const viewer = new groupdocs.viewer.Viewer("sample.docx")
            
            // A DOCX renderelése PDF-fájlba
            const viewOptions = groupdocs.viewer.PdfViewOptions(output.pdf)
            viewer.view(viewOptions)
            ```


############################# Formats ############################
formats:
  enable: true
  title:  "180+ fájlformátum támogatott"
  description: "A GroupDocs.Viewer támogatja a legnépszerűbb végzett műveleteket [fájlformátumokkal](https://docs.groupdocs.com/viewer/net/supported-document-formats/)"


############################# Metrics ############################

metrics:
  enable: true
  title: "Mélyreható mérőszámok és statisztikai betekintések"
  description: "Merüljön el kulcsszámaink részletes lebontásában, átfogó mutatókat és statisztikai betekintést nyújtva eredményeinket, hatásunkat és növekedésünket illetően."

  items:
    # metrics loop
    - number: "180+"
      title: "Támogatott formátumok"
      content: "Több mint 180 fájlformátum, köztük dokumentumok, képek és CAD-rajzok problémamentes megtekintése. Átfogó megtekintési megoldásunkkal törje meg a kompatibilitási akadályokat, és könnyedén hozzáférhet a különféle fájlokhoz."
    # metrics loop
    - number: "1.0M"
      title: "NuGet letöltések"
      content: "NuGet csomagmegoldásunk megbízható és széles körben elfogadott erőforrássá vált a fejlesztői közösségben, zökkenőmentes integrációt és értékes funkcionalitást biztosítva számtalan projekt számára."

    # metrics loop
    - number: "10+"
      title: "Könyvtárak"
      content: "Termékünk több mint 10 könyvtárat tartalmaz, amelyek fejlett funkciókat kínálnak a teljesítmény optimalizálása érdekében. Ezeket a könyvtárakat úgy tervezték, hogy páratlan képességekkel kielégítsék a különböző fejlesztési igényeket."
    
    # metrics loop
    - number: "100+"
      title: "Boldog ügyfelek"
      content: "A világ legikonikusabb márkáit szolgáljuk ki. Fedezze fel, miért szeretik százak a GroupDocs.Viewer-t! Fedezze fel a zökkenőmentes navigációt, a kényelmes együttműködést és a páratlanul egyszerű használatot. Csatlakozz most!"


############################# Customers ############################
# logo size X1 => 170:70  X2 => 340 : 140

customers:
  enable: true
  title: "Boldog ügyfeleink"
  description: "A GroupDocs könyvtárakat világszerte elismert és előkelő márkák alkalmazzák szerte a világon."

  items:
    # customers loop
    - title: "BenQ Corporation"
      logo: "benq"
    # customers loop
    - title: "Nasdaq Stock Market"
      logo: "nasdaq"
    # customers loop
    - title: "AT&T Inc."
      logo: "att"
    # customers loop
    - title: "AstraZeneca"
      logo: "astrazeneca"
    # customers loop
    - title: "Central Bank of Argentina"
      logo: "argentinacentralbank"
    # customers loop
    - title: "Roche Holding AG"
      logo: "roche"
    # customers loop
    - title: "Capita"
      logo: "capita"
    # customers loop
    - title: "Axa S.A."
      logo: "axa"
    # customers loop
    - title: "Instructure Inc."
      logo: "instructure"
     # customers loop
    - title: "Wipro"
      logo: "wipro"



############################# Actions ############################

actions:
  enable: true
  title: "Készen áll az indulásra?"
  description: "Próbálja ki ingyenesen a GroupDocs.Viewer funkcióit, vagy kérjen licencet"

  items:
    #  loop
    - title: ".NET"
      link: "/viewer/net/"
      color: "blue"
        #  loop
    - title: "Java"
      link: "/viewer/java/"
      color: "red"
        #  loop
    - title: "Node.js"
      link: "/viewer/nodejs-java/"
      color: "green"


############################# Faq ############################

faq:
  enable: true
  title: "Gyakori kérdések és aggályok"
  description: "Keresse meg a válaszokat a gyakori kérdésekre a GYIK részben, hogy gyorsan válaszoljon kérdéseire és aggályaira."

  items:
    #  loop
    - question: "Értékelhetem a GroupDocs termékeket a vásárlás előtt?"
      answer: |
        Igen! Minden GroupDocs-termék kockázatmentes, értékelő verzióval rendelkezik. Nyomatékosan javasoljuk a fejlesztőknek, hogy vásárlás előtt töltsék le és próbálják ki API-jainkat, hogy azok 100%-osan kielégítsék az Ön igényeit.
    #  loop
    - question: "A GroupDocs készít termékbemutatókat?"
      answer: |
        Nem, mi az API-inkra és a lehető legfunkcionálisabb és legstabilabb termékekre összpontosítunk. Teljesen működőképes és ingyenes próbaverziókat kínálunk [ideiglenes licenc](https://purchase.groupdocs.com/temporary-license/) formájában, így Ön is kipróbálhatja a terméket.
    #  loop
    - question: "Hol tudom letölteni a terméket?"
      answer: |
        Minden termék letölthető a [webhelyről](https://releases.groupdocs.com). Szoftverünk fizikai másolatát nem küldjük postai úton.    
    #  loop
    - question: "A GroupDocs fejlesztői licence felhasználónként vagy megnevezett felhasználónként vonatkozik?"
      answer: |
        A GroupDocs fejlesztői licencek felhasználónként érvényesek, nem megnevezett felhasználókonként. Tisztában vagyunk vele, hogy a kódoló csapat tagjai idővel változhatnak, és nem célszerű minden alkalommal frissíteni a licencet.
    #  loop
    - question: "Csak aktív fejlesztőknek van szükségünk licencre? Például van egy két fejlesztőből álló csapatunk az A műszakban és egy két fejlesztőből álló csapat a B műszakban… ebben a helyzetben két vagy négy licencre van szükségünk?"
      answer: |
        Minden fejlesztőnek, aki a projekten dolgozik, licenccel kell rendelkeznie. Ebben a helyzetben a GroupDocs négytagúnak tekinti a csapatát (annak ellenére, hogy különböző időpontokban dolgoznak).

############################# Cloud ############################

cloud_links:
  enable: true
  title: "GroupDocs.Viewer alacsony kódú API-k"
  description: "Felhőalapú REST API-nkkal felgyorsíthatja a dokumentumok vagy képek megtekintését bármilyen típusú alkalmazásban"

  items:
    #  loop
    - icon: "groupdocs_viewer-for-curl"
      title: "GroupDocs.Viewer Cloud for cURL"
      link: "https://products.groupdocs.cloud/viewer/curl"
      content: "Használja a cURL RESTful dokumentumnézegető API-t a Microsoft Office, PDF és más szabványos fájlformátumok hatékony megjelenítéséhez és bemutatásához alkalmazásaiban."

    #  loop
    - icon: "groupdocs_viewer-for-net"
      title: "GroupDocs.Viewer Cloud for .NET"
      link: "https://products.groupdocs.cloud/viewer/net"
      content: "A .NET-alkalmazások dokumentummegtekintési képességeinek javítása a .NET-hez készült Cloud SDK segítségével. Tekintse meg a dokumentumokat zökkenőmentesen HTML, PDF vagy képformátumban."
    #  loop
    - icon: "groupdocs_viewer-for-java"
      title: "GroupDocs.Viewer Cloud for Java"
      link: "https://products.groupdocs.cloud/viewer/java"
      content: "Integráljon fejlett dokumentum-megjelenítési képességeket Java-alkalmazásaiba egy erre a célra kialakított Java Document Viewer SDK segítségével."

############################# Apps ############################

app_links:
  enable: true
  title: "GroupDocs.Viewer NoCode alkalmazások"
  description: "Online alkalmazás, amely lehetővé teszi több mint 180 népszerű fájlformátum megtekintését a böngészőben"

  items:
    #  loop
    - icon: "groupdocs_viewer-app"
      title: "GroupDocs.Viewer Total"
      link: "https://products.groupdocs.app/viewer/total"
      content: "Fedezzen fel egy ingyenes online alkalmazást, amellyel több mint 180 fájlformátumot tekinthet meg közvetlenül kedvenc webböngészőjéből."

    #  loop
    - icon: "groupdocs_words-app"
      title:  "GroupDocs.Viewer DOCX"
      link: "https://products.groupdocs.app/viewer/docx"
      content: "Webalapú eszköz a Microsoft Word fájlok könnyű megtekintésére különféle eszközökön."

    #  loop
    - icon: "groupdocs_pdf-app"
      title:  "GroupDocs.Viewer PDF"
      link: "https://products.groupdocs.app/viewer/pdf"
      content: "Nyissa meg és tekintse meg a PDF-fájlokat online az ingyenes PDF-nézegetővel."
    

---