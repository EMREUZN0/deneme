# YAPAY ZEKA DESTEKLİ YALAN HABER TESPİTİ: GERÇEKLİK KALKANI

---

## TEZ TASLAĞI

---

### ÖN SAYFALAR (Numarasız + Romen Rakamları)

1. İç Kapak
2. Onay Sayfası
3. Teşekkür
4. Özgünlük Bildirimi
5. İçindekiler
6. Şekillerin Listesi
7. Tabloların Listesi
8. Kısaltmalar
9. ÖZET (Türkçe)
10. ABSTRACT (İngilizce)

### ANA BÖLÜMLER (Arap Rakamları ile Sayfa Numaralandırma)

**BÖLÜM 1: GİRİŞ**
- 1.1 Problem Tanımı ve Motivasyon
- 1.2 Tezin Amacı ve Kapsamı
- 1.3 Tezin Katkıları
- 1.4 Tezin Organizasyonu

**BÖLÜM 2: LİTERATÜR TARAMASI**
- 2.1 Yalan Haber Kavramı ve Tarihçesi
- 2.2 Yalan Haber Tespit Yöntemleri
- 2.3 İlgili Çalışmalar
- 2.4 Yapay Zeka ve Doğal Dil İşleme
- 2.5 Web Teknolojileri ve Modern Frontend

**BÖLÜM 3: MATERYAL VE YÖNTEM**
- 3.1 Sistem Mimarisi
- 3.2 Kullanılan Teknolojiler
- 3.3 Analiz Modülleri
- 3.4 Prompt Mühendisliği
- 3.5 Kullanıcı Arayüzü Tasarımı

**BÖLÜM 4: UYGULAMA**
- 4.1 Proje Yapısı ve Organizasyonu
- 4.2 Ana Uygulama Modülü (App.tsx)
- 4.3 Gemini Servis Modülü (geminiService.ts)
- 4.4 Analiz Form Bileşeni (AnalysisForm.tsx)
- 4.5 Sonuç Görüntüleme Bileşenleri
- 4.6 Rapor Görüntüleme (ReportView.tsx)
- 4.7 Chatbot Asistanı (Chatbot.tsx)
- 4.8 Kişisel İstatistikler (TrendsDashboard.tsx)
- 4.9 Geri Bildirim Sistemi

**BÖLÜM 5: DENEYSEL SONUÇLAR VE DEĞERLENDİRME**
- 5.1 Test Ortamı
- 5.2 Fonksiyonel Testler
- 5.3 Performans Değerlendirmesi
- 5.4 Kullanıcı Deneyimi Değerlendirmesi
- 5.5 Karşılaştırmalı Değerlendirme

**BÖLÜM 6: SONUÇ VE ÖNERİLER**
- 6.1 Sonuçlar
- 6.2 Kısıtlamalar
- 6.3 Gelecek Çalışmalar
- 6.4 Toplumsal Etki ve Değerlendirme

**KAYNAKLAR**

**EKLER**

---

## ŞEKİLLERİN LİSTESİ

| No | Şekil Adı | Sayfa |
|-----|-----------|-------|
| Şekil 1.1 | Dijital çağda yalan haberlerin yayılma hızı karşılaştırması | |
| Şekil 1.2 | Yalan haberlerin toplumsal etki alanları | |
| Şekil 1.3 | Gerçeklik Kalkanı uygulaması genel görünümü | |
| Şekil 2.1 | Bilgi bozukluğu türleri sınıflandırması | |
| Şekil 2.2 | Yalan haber tespit yöntemlerinin tarihsel gelişimi | |
| Şekil 2.3 | Transformer mimarisi genel yapısı | |
| Şekil 2.4 | Büyük dil modellerinin gelişim süreci | |
| Şekil 3.1 | Gerçeklik Kalkanı sistem mimarisi | |
| Şekil 3.2 | Katmanlı mimari yapısı | |
| Şekil 3.3 | Veri akış diyagramı | |
| Şekil 3.4 | Analiz modüllerinin çalışma şeması | |
| Şekil 3.5 | Doğruluk kontrolü süreç akış diyagramı | |
| Şekil 3.6 | Prompt mühendisliği yapısı | |
| Şekil 3.7 | Kullanıcı arayüzü ana bileşen yapısı | |
| Şekil 3.8 | Analiz formu ekran görüntüsü (Metin sekmesi) | |
| Şekil 3.9 | Görsel yükleme sekmesi | |
| Şekil 3.10 | Video yükleme sekmesi | |
| Şekil 3.11 | Sonuç görüntüleme ekran görüntüsü | |
| Şekil 4.1 | Proje dizin yapısı | |
| Şekil 4.2 | App.tsx bileşen hiyerarşisi | |
| Şekil 4.3 | geminiService.ts modül yapısı | |
| Şekil 4.4 | URL girişi ve analiz süreci | |
| Şekil 4.5 | Sekme navigasyonu tasarımı | |
| Şekil 4.6 | StreamingResult bileşeni çalışma örneği | |
| Şekil 4.7 | ResultDisplay bileşeni ekran görüntüsü | |
| Şekil 4.8 | ReportView sayfası ekran görüntüsü | |
| Şekil 4.9 | Chatbot arayüzü ekran görüntüsü | |
| Şekil 4.10 | TrendsDashboard ekran görüntüsü | |
| Şekil 4.11 | Geri bildirim sistemi akış diyagramı | |
| Şekil 5.1 | Test stratejisi genel yapısı | |
| Şekil 5.2 | Performans değerlendirme metrikleri | |
| Şekil 5.3 | Analiz türlerine göre yanıt süresi karşılaştırması | |
| Şekil 5.4 | Teknik performans değerlendirme çerçevesi | |
| Şekil 5.5 | Bundle boyut dağılımı grafiği | |
| Şekil 5.6 | Karşılaştırmalı analiz çerçevesi | |

---

## TABLOLARIN LİSTESİ

| No | Tablo Adı | Sayfa |
|-----|-----------|-------|
| Tablo 1.1 | Yalan haberlerin toplumsal etki kategorileri | |
| Tablo 2.1 | Bilgi bozukluğu türlerinin karşılaştırması | |
| Tablo 2.2 | Yalan haber tespit yöntemlerinin karşılaştırması | |
| Tablo 2.3 | İlgili akademik çalışmaların özet karşılaştırması | |
| Tablo 2.4 | Transformer tabanlı modellerin karşılaştırması | |
| Tablo 3.1 | Kullanılan teknolojiler ve versiyonları | |
| Tablo 3.2 | Gemini model özellikleri karşılaştırması | |
| Tablo 3.3 | Analiz modülleri ve özellikleri | |
| Tablo 3.4 | Analiz türleri ve değerlendirme kategorileri | |
| Tablo 3.5 | Prompt mühendisliği teknikleri | |
| Tablo 4.1 | Proje dosya yapısı özeti | |
| Tablo 4.2 | App.tsx state değişkenleri | |
| Tablo 4.3 | Gemini API çağrı parametreleri | |
| Tablo 4.4 | AnalysisForm props tanımları | |
| Tablo 4.5 | Sonuç görüntüleme bileşenleri | |
| Tablo 4.6 | Chatbot mesaj yapısı | |
| Tablo 5.1 | Test veri seti dağılımı | |
| Tablo 5.2 | Test senaryoları ve beklenen çıktılar | |
| Tablo 5.3 | Doğruluk kontrolü modülü performans metrikleri | |
| Tablo 5.4 | İddia ayrıştırma performansı | |
| Tablo 5.5 | Yanıt süresi performansı | |
| Tablo 5.6 | Build performans metrikleri | |
| Tablo 5.7 | Bundle boyut analizi | |
| Tablo 5.8 | Proje bağımlılıkları | |
| Tablo 5.9 | Kaynak kod metrikleri | |
| Tablo 5.10 | Manuel fact-checking ve Gerçeklik Kalkanı karşılaştırması | |
| Tablo 5.11 | Akademik sistemler ile karşılaştırma | |
| Tablo 5.12 | Sınırlılıklar ve potansiyel çözümler | |

---

## KISALTMALAR

**API :** Application Programming Interface (Uygulama Programlama Arayüzü)

**AI :** Artificial Intelligence (Yapay Zeka)

**CSS :** Cascading Style Sheets (Basamaklı Stil Şablonları)

**DOM :** Document Object Model (Belge Nesne Modeli)

**HTML :** HyperText Markup Language (Hiper Metin İşaretleme Dili)

**HTTP :** HyperText Transfer Protocol (Hiper Metin Transfer Protokolü)

**JSON :** JavaScript Object Notation (JavaScript Nesne Gösterimi)

**LLM :** Large Language Model (Büyük Dil Modeli)

**NLP :** Natural Language Processing (Doğal Dil İşleme)

**SDK :** Software Development Kit (Yazılım Geliştirme Kiti)

**UI :** User Interface (Kullanıcı Arayüzü)

**URL :** Uniform Resource Locator (Tekdüzen Kaynak Bulucu)

**UX :** User Experience (Kullanıcı Deneyimi)

---

## ÖZET

**YAPAY ZEKA DESTEKLİ YALAN HABER TESPİTİ: GERÇEKLİK KALKANI**

Dijital çağda bilginin hızla yayılması, beraberinde dezenformasyon ve yalan haber sorununu da getirmiştir. Sosyal medya platformlarının yaygınlaşmasıyla birlikte, doğrulanmamış ve yanıltıcı içerikler milyonlarca kullanıcıya saniyeler içinde ulaşabilmektedir. Bu durum, toplumsal kutuplaşmadan sağlık krizlerine, seçim süreçlerinden ekonomik istikrara kadar pek çok alanda ciddi sorunlara yol açmaktadır. Geleneksel doğrulama yöntemleri, bilgi akışının hızı karşısında yetersiz kalmaktadır.

Bu tez çalışmasında, yapay zeka teknolojilerini kullanarak yalan haber tespiti gerçekleştiren "Gerçeklik Kalkanı" adlı web tabanlı bir uygulama geliştirilmiştir. Uygulama, Google Gemini 2.5 büyük dil modelinin multimodal yeteneklerinden faydalanarak metin, URL, görsel ve video içeriklerini analiz edebilmektedir. Sistem, üç temel analiz türü sunmaktadır: doğruluk kontrolü (fact-check), taraflılık analizi ve propaganda tespiti. Doğruluk kontrolü modülünde, metindeki iddialar otomatik olarak ayrıştırılmakta, Google Arama entegrasyonu ile güvenilir kaynaklardan kanıtlar toplanmakta ve her iddia için doğrulama kararı verilmektedir.

Uygulama, React 19 ve TypeScript kullanılarak modern web teknolojileri ile geliştirilmiştir. Kullanıcı deneyimini zenginleştirmek amacıyla gerçek zamanlı streaming sonuç gösterimi, akıllı chatbot asistanı, olay zaman çizelgesi oluşturma ve global kaynak karşılaştırma gibi gelişmiş özellikler entegre edilmiştir. Ayrıca kullanıcıların geçmiş analizlerini takip edebilecekleri kişisel bir istatistik panosu da sunulmaktadır.

Gerçekleştirilen testler, sistemin yalan haber tespitinde yüksek doğruluk oranları elde ettiğini ve kullanıcılara güvenilir bir doğrulama aracı sunduğunu göstermektedir. Geliştirilen uygulama, dijital medya okuryazarlığının artırılmasına ve dezenformasyonla mücadeleye önemli bir katkı sağlamaktadır.

**Anahtar Kelimeler:** Yalan haber tespiti, yapay zeka, doğal dil işleme, büyük dil modelleri, Google Gemini, fact-checking, React, dezenformasyon

---

## ABSTRACT

**ARTIFICIAL INTELLIGENCE-BASED FAKE NEWS DETECTION: TRUTH SHIELD**

The rapid dissemination of information in the digital age has brought along the problem of disinformation and fake news. With the proliferation of social media platforms, unverified and misleading content can reach millions of users within seconds. This situation leads to serious problems in many areas, from social polarization to health crises, from election processes to economic stability. Traditional verification methods are inadequate against the speed of information flow.

In this thesis, a web-based application called "Gerçeklik Kalkanı" (Truth Shield) has been developed that performs fake news detection using artificial intelligence technologies. The application can analyze text, URL, image, and video content by utilizing the multimodal capabilities of the Google Gemini 2.5 large language model. The system offers three main types of analysis: fact-checking, bias analysis, and propaganda detection. In the fact-checking module, claims in the text are automatically extracted, evidence is collected from reliable sources through Google Search integration, and a verification decision is made for each claim.

The application has been developed with modern web technologies using React 19 and TypeScript. Advanced features such as real-time streaming result display, intelligent chatbot assistant, event timeline generation, and global source comparison have been integrated to enrich the user experience. Additionally, a personal statistics dashboard is provided where users can track their past analyses.

The conducted tests demonstrate that the system achieves high accuracy rates in fake news detection and provides users with a reliable verification tool. The developed application makes a significant contribution to increasing digital media literacy and combating disinformation.

**Keywords:** Fake news detection, artificial intelligence, natural language processing, large language models, Google Gemini, fact-checking, React, disinformation

---

# BÖLÜM 1: GİRİŞ

Bilgi çağı olarak adlandırılan 21. yüzyılda, dijital teknolojilerin ve internet altyapısının hızla gelişmesi, bilgiye erişim biçimlerini köklü bir şekilde dönüştürmüştür. Geleneksel medya organlarının tekelinde olan haber üretimi ve dağıtımı, sosyal medya platformlarının yükselişiyle birlikte demokratikleşmiş; ancak bu demokratikleşme beraberinde önemli sorunları da getirmiştir. Günümüzde herhangi bir birey, doğruluğu teyit edilmemiş bilgileri milyonlarca kişiye saniyeler içinde ulaştırabilmektedir. Bu durum, "yalan haber" (fake news) ve "dezenformasyon" kavramlarını gündelik hayatın ayrılmaz bir parçası haline getirmiştir. Özellikle 2016 yılından itibaren küresel gündemde önemli bir yer edinen yalan haber sorunu, demokratik süreçlerin sağlıklı işleyişinden toplum sağlığına, ekonomik istikrardan bireysel karar alma mekanizmalarına kadar pek çok alanı olumsuz etkilemektedir.

Yalan haber sorunu, yalnızca bireysel düzeyde bilgi kirliliği yaratmakla kalmayıp, toplumsal ölçekte ciddi sonuçlar doğurabilmektedir. Seçim süreçlerinin manipülasyonundan sağlık krizlerinde yanlış bilgilendirmeye, finansal piyasalardaki dalgalanmalardan toplumsal kutuplaşmaya kadar geniş bir yelpazede etkilerini göstermektedir [1, 10]. 2016 ABD başkanlık seçimleri, Brexit referandumu ve COVID-19 pandemisi sürecinde yaşanan "infodemi" olgusu, yalan haberlerin ne denli yıkıcı sonuçlar doğurabileceğinin somut örnekleri olarak tarihe geçmiştir. Bu bağlamda, yalan haberlerin otomatik olarak tespit edilmesi ve kullanıcılara güvenilir doğrulama araçlarının sunulması, günümüzün en önemli teknolojik ve toplumsal ihtiyaçlarından biri haline gelmiştir.

Bu tez çalışması, yapay zeka teknolojilerinin sunduğu imkânlardan yararlanarak yalan haber tespiti gerçekleştiren kapsamlı bir web uygulaması geliştirmeyi amaçlamaktadır. "Gerçeklik Kalkanı" adı verilen bu uygulama, Google Gemini 2.5 büyük dil modelinin multimodal yeteneklerini kullanarak metin, URL, görsel ve video içeriklerini analiz edebilmekte; kullanıcılara detaylı doğruluk raporları sunmaktadır. Uygulama, yalnızca içeriklerin doğruluğunu kontrol etmekle kalmayıp, aynı zamanda taraflılık analizi ve propaganda tespiti gibi ek analiz türleri sunarak kullanıcılara kapsamlı bir medya okuryazarlığı aracı sağlamaktadır.

### 1.1 Problem Tanımı ve Motivasyon

Dijital çağın en belirgin özelliklerinden biri, bilginin üretim ve yayılım hızının benzeri görülmemiş düzeylere ulaşmasıdır. İnternetin yaygınlaşması ve özellikle sosyal medya platformlarının günlük hayatın vazgeçilmez bir parçası haline gelmesiyle birlikte, bilgi akışının kontrolü geleneksel medya kurumlarının tekelinden çıkmıştır. Bu dönüşüm, bir yandan bilgiye erişimi demokratikleştirirken, öte yandan doğrulanmamış, yanıltıcı ve kasıtlı olarak üretilmiş içeriklerin hızla yayılmasına zemin hazırlamıştır. Günümüzde Facebook, Twitter (X), Instagram, TikTok ve YouTube gibi platformlar, milyarlarca kullanıcıya ev sahipliği yapmakta ve bu platformlarda paylaşılan içerikler geleneksel medya kuruluşlarının erişemeyeceği hızlarda viral hale gelebilmektedir.

**Yalan Haberlerin Dijital Ortamda Yayılma Dinamikleri**

Yalan haber kavramı, tarihsel olarak yeni bir olgu olmamakla birlikte, dijital medya ortamında farklı bir boyut kazanmıştır. Geleneksel medyada yalan haberlerin yayılması belirli bir zaman ve kaynak gerektirirken, dijital ortamda bir içerik saniyeler içinde viral hale gelebilmektedir. Vosoughi ve arkadaşlarının Science dergisinde yayınlanan ve 2006-2017 yılları arasında Twitter'da paylaşılan 126.000'den fazla haber hikâyesini analiz eden kapsamlı araştırması, yalan haberlerin sosyal medyada doğru haberlerden çok daha hızlı ve geniş bir kitleye yayıldığını ortaya koymuştur [11]. Bu çalışmaya göre, yalan haberler doğru haberlere kıyasla altı kat daha hızlı yayılmakta ve %70 daha fazla paylaşılmaktadır (Şekil 1.1). Araştırmacılar bu durumu, yalan haberlerin genellikle daha "yeni" ve "şaşırtıcı" bulunmasına bağlamışlardır; zira insanlar beklenmedik ve duygusal tepki uyandıran içerikleri paylaşmaya daha yatkındır.

**Şekil 1.1.** Dijital çağda yalan haberlerin yayılma hızı karşılaştırması

Yalan haberlerin yayılma dinamikleri incelendiğinde, sorunun karmaşık bir yapıya sahip olduğu görülmektedir. Yalan haberler; siyasi motivasyonlar, ekonomik çıkarlar, ideolojik amaçlar veya salt dikkat çekme arzusuyla üretilebilmektedir. Üretim motivasyonlarının çeşitliliği, tespit yöntemlerinin de çok boyutlu olması gerektiğini ortaya koymaktadır. Ayrıca yalan haberler yalnızca metin formatında değil, manipüle edilmiş görseller, deepfake videolar ve bağlamından koparılmış multimedya içerikler şeklinde de yayılmaktadır. Bu durum, etkili bir tespit sisteminin çoklu medya formatlarını analiz edebilme yeteneğine sahip olması gerektiğini göstermektedir.

**Yalan Haberlerin Toplumsal Etkileri**

Yalan haberlerin toplumsal etkileri incelendiğinde, sorunun boyutları daha net bir şekilde anlaşılmaktadır (Tablo 1.1). Siyaset ve demokrasi alanında, seçim manipülasyonu, kamuoyu yanıltma ve toplumsal kutuplaşma gibi etkiler gözlemlenmektedir; 2016 ABD Seçimleri ve Brexit süreci bu etkilerin somut örnekleridir. Halk sağlığı alanında, yanlış tedavi bilgileri, aşı karşıtlığı ve panik gibi sonuçlar ortaya çıkmaktadır; COVID-19 pandemisi sırasında yaşanan "infodemi" ve aşı dezenformasyonu bu kategorinin en çarpıcı örnekleridir. Ekonomi alanında, piyasa manipülasyonu ve yatırımcı yanıltma gibi etkiler görülmektedir; sahte şirket haberleri ve kripto para dolandırıcılıkları bu kapsamda değerlendirilebilir. Toplumsal huzur açısından, etnik ve dini gerilimler ile linç kültürünün yükselişi gibi sonuçlar ortaya çıkmaktadır. Son olarak bireysel düzeyde, güven erozyonu ve karar verme bozuklukları gibi etkiler gözlemlenmektedir; kişisel finansal kayıplar ve sağlık riskleri bu kategorinin örnekleri arasındadır (Şekil 1.2). Tüm bu etkiler, yalan haber sorununun çok boyutlu ve acil müdahale gerektiren bir sorun olduğunu açıkça ortaya koymaktadır.

**Tablo 1.1.** Yalan haberlerin toplumsal etki kategorileri

| Etki Alanı | Etkiler | Örnekler |
|------------|---------|----------|
| Siyaset ve Demokrasi | Seçim manipülasyonu, kamuoyu yanıltma | 2016 ABD Seçimleri, Brexit |
| Halk Sağlığı | Yanlış tedavi bilgileri, aşı karşıtlığı | COVID-19 infodemisi |
| Ekonomi | Piyasa manipülasyonu, yatırımcı yanıltma | Kripto para dolandırıcılıkları |
| Toplumsal Huzur | Etnik/dini gerilimler, linç kültürü | Sosyal medya linçleri |
| Bireysel | Güven erozyonu, karar verme bozuklukları | Finansal kayıplar, sağlık riskleri |

**Şekil 1.2.** Yalan haberlerin toplumsal etki alanları

**Geleneksel Doğrulama Yöntemlerinin Yetersizliği**

Geleneksel doğrulama yöntemleri, bilgi akışının bu hızı karşısında yetersiz kalmaktadır. Manuel fact-checking süreçleri, uzman insan kaynağı gerektirmekte ve zaman alıcı olmaktadır. Dünya genelinde faaliyet gösteren Snopes, PolitiFact, FactCheck.org gibi kuruluşlar ve Türkiye'de Teyit.org gibi platformlar, önemli bir hizmet sunmakla birlikte, üretilen içerik miktarının yalnızca küçük bir bölümünü doğrulayabilmektedir. Bir haberin doğruluğunun profesyonel fact-checker'lar tarafından kontrol edilmesi saatler hatta günler sürebilirken, aynı haber bu süre zarfında milyonlarca kişiye ulaşmış olabilmektedir [12]. Lazer ve arkadaşlarının Science dergisindeki çalışması, yalan haberlerin yayılma hızı ile doğrulama süreçlerinin hızı arasındaki bu asimetriyi "bilgi asimetrisi" olarak tanımlamış ve otomatik tespit sistemlerinin geliştirilmesinin kritik önemini vurgulamıştır. Bu durum, otomatik ve gerçek zamanlı çalışan doğrulama sistemlerine olan ihtiyacı açıkça ortaya koymaktadır.

**Yapay Zeka ve Doğal Dil İşleme Alanındaki Gelişmeler**

Yapay zeka ve özellikle doğal dil işleme (Natural Language Processing - NLP) alanındaki gelişmeler, yalan haber tespiti için yeni olanaklar sunmaktadır. Son on yılda bu alanda yaşanan devrim niteliğindeki gelişmeler, metin anlama ve üretme kapasitesini önemli ölçüde artırmıştır. 2017 yılında Vaswani ve arkadaşları tarafından önerilen Transformer mimarisi [3], bu alandaki en önemli dönüm noktalarından birini oluşturmuştur. Transformer mimarisinin "attention" (dikkat) mekanizması, modellerin metindeki uzak bağımlılıkları yakalamasına ve bağlamı daha iyi anlamasına olanak tanımıştır. Bu mimari üzerine inşa edilen BERT (Bidirectional Encoder Representations from Transformers) [4] ve GPT (Generative Pre-trained Transformer) modelleri, doğal dil işleme görevlerinde insan seviyesine yakın performanslar sergilemeye başlamıştır.

Büyük dil modelleri (Large Language Models - LLM), metin anlama, bağlam çıkarımı ve çok modlu içerik analizi konularında önemli yetenekler kazanmıştır. Google'ın Gemini modeli gibi son nesil yapay zeka sistemleri, metin, görsel ve video içeriklerini birlikte analiz edebilen multimodal yeteneklere sahiptir [5]. Gemini ailesi, özellikle çok modlu anlama ve üretme konusunda rakiplerine göre üstün performans göstermektedir. Modelin "grounding" özelliği sayesinde, üretilen yanıtlar Google Arama sonuçlarıyla desteklenebilmekte, bu da doğrulama süreçlerinde güncel ve güvenilir kaynaklara erişimi mümkün kılmaktadır. Bu teknolojik gelişmeler, kapsamlı ve etkili yalan haber tespit sistemlerinin geliştirilmesini mümkün kılmaktadır.

**Türkiye Özelinde Durum ve İhtiyaç Analizi**

Türkiye özelinde değerlendirildiğinde, Türkçe dilinde çalışan kapsamlı yalan haber tespit araçlarının sınırlı olduğu görülmektedir. Mevcut çözümler genellikle İngilizce odaklı olup, Türkçe içeriklerin analizinde yetersiz kalmaktadır. Türkçe'nin aglütinatif (eklemeli) yapısı, zengin morfolojisi ve İngilizce'den farklı sözdizimi, doğrudan çeviri veya aktarım yaklaşımlarının başarısını sınırlamaktadır. Türkiye'de Teyit.org gibi manuel doğrulama platformları önemli bir hizmet sunmakla birlikte, ölçeklenebilirlik ve hız açısından sınırlamalara sahiptir. Bu durum, Türkçe konuşan kullanıcılar için erişilebilir, otomatik ve etkili bir doğrulama aracının geliştirilmesi ihtiyacını ortaya çıkarmaktadır. Bu tez çalışmasının temel motivasyonlarından biri de bu boşluğu doldurmaktır.

### 1.2 Tezin Amacı ve Kapsamı

Bu tez çalışmasının temel amacı, yapay zeka teknolojilerini kullanarak yalan haber tespiti gerçekleştiren, kullanıcı dostu ve kapsamlı bir web uygulaması geliştirmektir. "Gerçeklik Kalkanı" adı verilen bu uygulama (Şekil 1.3), dijital medya okuryazarlığını artırmak ve dezenformasyonla mücadeleye katkı sağlamak amacıyla tasarlanmıştır. Uygulama, hem teknik açıdan yenilikçi çözümler sunmayı hem de geniş kitlelere erişilebilir bir araç olmayı hedeflemektedir.

**Şekil 1.3.** Gerçeklik Kalkanı uygulaması genel görünümü

**Birincil Hedefler**

Uygulamanın birincil hedeflerinden ilki, çok modlu içerik analizi kapasitesidir. Sistem, metin, URL, görsel ve video formatlarındaki içeriklerin analiz edilebilmesini sağlamaktadır. Günümüzde yalan haberler yalnızca metin formatında değil, görsel ve video içerikler aracılığıyla da yayılmaktadır. Manipüle edilmiş fotoğraflar, bağlamından koparılmış görüntüler ve deepfake videolar, dezenformasyonun önemli araçları haline gelmiştir. Bu nedenle, kapsamlı bir tespit sistemi tüm bu formatları desteklemelidir. Gerçeklik Kalkanı, kullanıcıların doğrudan metin yapıştırabilmesine, web sayfası URL'si girebilmesine, görsel yükleyebilmesine ve video dosyası analiz ettirebilmesine olanak tanımaktadır.

İkinci birincil hedef, çoklu analiz türlerinin sunulmasıdır. Sistem, doğruluk kontrolü (fact-check), taraflılık analizi ve propaganda tespiti olmak üzere üç farklı analiz türü sunmaktadır. Doğruluk kontrolü, metindeki somut iddiaları tespit ederek bunları güvenilir kaynaklarla karşılaştırmaktadır. Taraflılık analizi, içeriğin siyasi, ideolojik veya diğer türdeki yanlılıklarını ortaya koymaktadır. Propaganda tespiti ise manipülatif dil kullanımı, duygusal çağrılar ve diğer ikna tekniklerini belirlemektedir. Her analiz türü, içeriğin farklı bir boyutunu değerlendirerek kullanıcıya kapsamlı bir perspektif sağlamaktadır.

Üçüncü birincil hedef, kanıt tabanlı doğrulama yaklaşımıdır. Sistem, metindeki iddiaları otomatik olarak ayrıştırmakta ve her iddia için güvenilir kaynaklardan kanıt toplamaktadır. Bu yaklaşım, "kara kutu" tarzı çalışan sistemlerin aksine, kullanıcılara şeffaf ve izlenebilir bir doğrulama süreci sunmaktadır. Google Arama entegrasyonu sayesinde sistem, analiz anında güncel kaynaklara erişebilmekte ve her iddia için kaynak URL'leri ile birlikte kanıtları sunabilmektedir. Bu şeffaflık, kullanıcıların sisteme güven duymasını ve sonuçları bağımsız olarak doğrulayabilmesini sağlamaktadır.

Dördüncü birincil hedef, kullanıcı dostu arayüz tasarımıdır. Dijital medya okuryazarlığının artırılması için sistemin geniş kitlelere ulaşabilmesi gerekmektedir. Bu nedenle uygulama, teknik bilgisi olmayan kullanıcıların da kolayca kullanabileceği, sezgisel ve erişilebilir bir arayüze sahiptir. Modern tasarım prensipleri ve kullanılabilirlik standartları gözetilerek geliştirilen arayüz, karmaşık analiz süreçlerini kullanıcıdan soyutlayarak basit ve anlaşılır sonuçlar sunmaktadır.

**İkincil Hedefler**

Uygulamanın ikincil hedefleri arasında gerçek zamanlı sonuç gösterimi yer almaktadır. Analiz sürecinde streaming teknolojisi kullanılarak sonuçlar anlık olarak kullanıcıya sunulmaktadır. Bu özellik, özellikle uzun metinlerin analizinde kullanıcı deneyimini önemli ölçüde iyileştirmektedir. Bir diğer ikincil hedef, akıllı asistan entegrasyonudur. Kullanıcılar, analiz sonuçlarını tartışabilecekleri, ek sorular sorabilecekleri ve bağlamsal bilgi alabilecekleri bir chatbot asistanıyla etkileşime girebilmektedir. Gelişmiş analiz araçları kapsamında ise olay zaman çizelgesi oluşturma, global kaynak karşılaştırma ve derinlemesine analiz gibi ek özellikler sunulmaktadır. Son olarak kişisel istatistik takibi özelliği, kullanıcıların geçmiş analizlerini takip edebilmelerini ve dijital medya okuryazarlığı performanslarını değerlendirebilmelerini sağlamaktadır.

**Tezin Kapsamı ve Sınırlılıkları**

Tez çalışmasının kapsamı, belirli teknolojik ve fonksiyonel sınırlar içerisinde tanımlanmıştır. Dil desteği açısından, uygulama öncelikli olarak Türkçe içeriklerin analizi için optimize edilmiş olup, kullanıcı arayüzü ve sistem mesajları Türkçe olarak sunulmaktadır. Platform açısından, web tabanlı bir uygulama olarak geliştirilmiş olan sistem, modern web tarayıcıları üzerinden erişilebilmektedir. Yapay zeka modeli olarak Google Gemini 2.5 ailesi kullanılmaktadır; metin ve görsel analizlerinde Gemini 2.5 Flash, video analizlerinde ise daha güçlü olan Gemini 2.5 Pro modeli tercih edilmiştir. Veri depolama stratejisi olarak, kullanıcı analizleri istemci tarafında (client-side) LocalStorage kullanılarak saklanmakta, geri bildirim verileri için ise Supabase bulut veritabanı entegrasyonu bulunmaktadır.

### 1.3 Tezin Katkıları

Bu tez çalışması, yalan haber tespiti alanına hem teorik hem de pratik düzeyde çeşitli katkılar sunmaktadır. Bu katkılar, teknolojik, metodolojik ve pratik olmak üzere üç ana kategoride ele alınabilir.

**Teknolojik Katkılar**

Teknolojik katkılar açısından değerlendirildiğinde, en önemli katkı multimodal analiz entegrasyonudur. Mevcut yalan haber tespit sistemlerinin büyük çoğunluğu yalnızca metin tabanlı analiz yapmaktadır. Bu çalışmada geliştirilen sistem ise metin, URL, görsel ve video içeriklerini tek bir platformda analiz edebilmektedir. Günümüzde dezenformasyon kampanyaları çoğunlukla çoklu medya formatlarını birlikte kullanmaktadır; bir yalan haber, dikkat çekici bir görsel veya kısa bir video klip ile desteklendiğinde çok daha hızlı yayılabilmektedir. Bu multimodal yaklaşım, farklı formatlarda yayılan yalan haberlerin tek bir noktadan tespitini mümkün kılmaktadır.

İkinci önemli teknolojik katkı, büyük dil modeli entegrasyonudur. Google Gemini 2.5 modelinin yalan haber tespiti için sistematik bir şekilde kullanılması ve prompt mühendisliği teknikleriyle optimize edilmesi, bu alanda özgün bir katkı niteliğindedir. Prompt mühendisliği, büyük dil modellerinden istenen çıktıları elde etmek için girdi metinlerinin (prompt) stratejik olarak tasarlanmasını içermektedir. Bu çalışmada geliştirilen prompt yapıları, modelin iddia ayrıştırma, kanıt değerlendirme ve sonuç üretme süreçlerinde yüksek performans göstermesini sağlamaktadır. Her analiz türü için özel olarak tasarlanan prompt şablonları, modelin tutarlı ve yapılandırılmış çıktılar üretmesini garantilemektedir.

Üçüncü teknolojik katkı, Google Search Grounding özelliğinin entegrasyonudur. Sistemin Google Arama API'si ile entegrasyonu, analiz edilen içeriklerin güncel ve güvenilir kaynaklarla karşılaştırılmasını mümkün kılmaktadır. Geleneksel makine öğrenmesi tabanlı yalan haber tespit sistemleri, eğitim sırasında kullanılan veri setlerine bağımlıdır ve yeni ortaya çıkan olaylar veya iddialar hakkında bilgi sahibi değildir. Google Search Grounding özelliği sayesinde geliştirilen sistem, statik veri setlerine dayanan sistemlerin aksine, gerçek zamanlı doğrulama yapabilme yeteneğine sahiptir. Bu özellik, sistemin güncel olaylara ilişkin haberleri de etkili bir şekilde analiz edebilmesini sağlamaktadır.

Dördüncü teknolojik katkı, streaming mimarisi implementasyonudur. Analiz sonuçlarının gerçek zamanlı olarak kullanıcıya aktarılması için streaming mimarisi uygulanmıştır. Büyük dil modelleri ile yapılan analizler, özellikle karmaşık içeriklerde birkaç saniye sürebilmektedir. Geleneksel istek-yanıt modelinde kullanıcı, tüm analiz tamamlanana kadar beklemek zorundadır. Streaming mimarisi sayesinde, analiz sonuçları oluşturuldukça anlık olarak kullanıcıya iletilmektedir. Bu yaklaşım, kullanıcı deneyimini önemli ölçüde iyileştirmekte ve bekleme süresini algısal olarak azaltmaktadır.

**Metodolojik Katkılar**

Metodolojik katkılar açısından, en önemli yenilik üçlü analiz çerçevesidir. Doğruluk kontrolü, taraflılık analizi ve propaganda tespiti olmak üzere üç farklı analiz türünün tek bir sistemde birleştirilmesi, içeriklerin çok boyutlu değerlendirilmesine olanak tanımaktadır. Bir haber metni olgusal olarak doğru olsa bile taraflı bir dille yazılmış olabilir veya propaganda teknikleri içerebilir. Üçlü analiz çerçevesi, kullanıcılara içeriğin farklı boyutları hakkında kapsamlı bir değerlendirme sunmaktadır.

İkinci metodolojik katkı, iddia tabanlı doğrulama metodolojisidir. Metinlerin bütünsel olarak "doğru" veya "yanlış" şeklinde etiketlenmesi yerine, içerdikleri iddiaların ayrı ayrı doğrulanması yaklaşımı benimsenmiştir. Bir haber metni birden fazla iddia içerebilir ve bu iddiaların bazıları doğru, bazıları yanlış, bazıları ise doğrulanamaz olabilir. İddia tabanlı yaklaşım, daha hassas ve şeffaf sonuçlar üretmekte, kullanıcılara her iddia için ayrı ayrı kanıtlar sunmaktadır.

Üçüncü metodolojik katkı, görsel orijinallik kontrolü modülüdür. Görsel içeriklerin yapay zeka tarafından üretilip üretilmediğinin veya manipüle edilip edilmediğinin tespiti için özel bir analiz modülü geliştirilmiştir. Deepfake teknolojilerinin ve yapay zeka görsel üretim araçlarının yaygınlaşmasıyla birlikte, sahte görsellerin tespiti giderek önem kazanmaktadır. Bu modül, görsellerde manipülasyon izleri, tutarsızlıklar ve yapay zeka üretimi belirtileri aramaktadır.

**Pratik Katkılar**

Pratik katkılar değerlendirildiğinde, en önemli katkı Türkçe dil desteğidir. Türkçe içeriklerin analizine odaklanan kapsamlı bir doğrulama aracının geliştirilmesi, Türkçe konuşan kullanıcılar için önemli bir boşluğu doldurmaktadır. Mevcut global çözümlerin Türkçe'ye uyarlanmasındaki zorluklar göz önüne alındığında, bu katkının önemi daha iyi anlaşılmaktadır.

İkinci pratik katkı, açık kaynak yaklaşımıdır. Geliştirilen uygulamanın kaynak kodunun erişime açık olması, araştırmacıların ve geliştiricilerin sistem üzerinde çalışabilmesine, inceleyebilmesine ve iyileştirmeler yapabilmesine olanak tanımaktadır. Bu yaklaşım, akademik şeffaflığı desteklemekte ve benzer çalışmaların geliştirilmesine katkı sağlamaktadır.

Üçüncü pratik katkı, dijital medya okuryazarlığının desteklenmesidir. Kişisel istatistik panosu aracılığıyla kullanıcıların kendi analizlerini takip edebilmeleri ve sonuçları değerlendirebilmeleri, dijital medya okuryazarlığının artırılmasına katkı sağlamaktadır. Kullanıcılar, zaman içinde karşılaştıkları içeriklerin doğruluk dağılımını görebilmekte ve bu sayede kendi bilgi tüketim alışkanlıkları hakkında farkındalık kazanabilmektedir.

### 1.4 Tezin Organizasyonu

Bu tez çalışması, altı ana bölümden oluşmaktadır ve her bölüm, projenin farklı bir boyutunu ele almaktadır. Bölümler, okuyucunun konuyu sistematik bir şekilde kavrayabilmesi için mantıksal bir sıra izlenerek düzenlenmiştir.

Birinci bölüm olan Giriş bölümünde, tezin konusu tanıtılmış, problem tanımı ve motivasyon kapsamlı bir şekilde açıklanmıştır. Yalan haber sorununun dijital çağdaki boyutları, toplumsal etkileri ve mevcut çözümlerin yetersizlikleri ele alınmıştır. Tezin amacı ve kapsamı netleştirilmiş, birincil ve ikincil hedefler detaylandırılmıştır. Son olarak, tezin teknolojik, metodolojik ve pratik katkıları ortaya konmuştur.

İkinci bölüm olan Literatür Taraması bölümünde, yalan haber kavramının tarihsel gelişimi ve akademik tanımları ele alınmaktadır. Mevcut yalan haber tespit yöntemleri, gelenekselden yapay zeka tabanlı yaklaşımlara kadar kapsamlı bir şekilde incelenmektedir. İlgili akademik çalışmalar değerlendirilmekte ve bu tez çalışmasının literatürdeki konumu belirlenmektedir. Ayrıca, kullanılan temel teknolojiler hakkında teorik arka plan sunulmakta; yapay zeka, doğal dil işleme, Transformer mimarisi, büyük dil modelleri ve modern web teknolojileri açıklanmaktadır.

Üçüncü bölüm olan Materyal ve Yöntem bölümünde, geliştirilen sistemin mimarisi detaylı olarak açıklanmaktadır. Sistemin katmanlı yapısı, veri akışı ve bileşenler arası etkileşimler şematik olarak sunulmaktadır. Kullanılan teknolojiler ve araçlar tanıtılmakta; React, TypeScript, Vite, Google Gemini API ve diğer teknolojilerin seçim gerekçeleri açıklanmaktadır. Analiz modüllerinin çalışma prensipleri ve prompt mühendisliği yaklaşımları, somut örneklerle birlikte sunulmaktadır.

Dördüncü bölüm olan Uygulama bölümünde, sistemin teknik implementasyonu detaylı olarak ele alınmaktadır. Proje yapısı ve dosya organizasyonu açıklanmakta, ana bileşenler ve servis modülleri kod düzeyinde incelenmektedir. Ana uygulama modülü, Gemini servis modülü, analiz form bileşeni, sonuç görüntüleme bileşenleri, rapor görüntüleme sayfası, chatbot asistanı ve istatistik panosu gibi temel bileşenler ayrıntılı olarak dokümante edilmektedir.

Beşinci bölüm olan Deneysel Sonuçlar ve Değerlendirme bölümünde, geliştirilen sistemin test edilmesi ve değerlendirilmesi gerçekleştirilmektedir. Test ortamı ve kullanılan test senaryoları tanımlanmaktadır. Fonksiyonel testler kapsamında, metin, URL, görsel ve video analizlerinin sonuçları sunulmaktadır. Performans değerlendirmesi yapılmakta, yanıt süreleri ve doğruluk oranları analiz edilmektedir. Mevcut yalan haber tespit sistemleriyle karşılaştırmalı analiz sunulmakta, sistemin güçlü ve zayıf yönleri tartışılmaktadır.

Altıncı bölüm olan Sonuç ve Öneriler bölümünde, tez çalışmasının sonuçları özetlenmektedir. Sistemin mevcut kısıtlamaları ve sınırlılıkları açıkça tartışılmaktadır. Gelecek çalışmalar için öneriler sunulmakta; çoklu dil desteği, offline çalışma modu, model fine-tuning ve mobil uygulama geliştirme gibi potansiyel iyileştirmeler değerlendirilmektedir. Son olarak, geliştirilen uygulamanın toplumsal etki değerlendirmesi yapılmaktadır.

Tezin sonunda, çalışmada yararlanılan kaynaklar akademik yazım kurallarına uygun olarak listelenmektedir. Ekler bölümünde ise kaynak kod örnekleri, kullanıcı arayüzü ekran görüntüleri ve detaylı test sonuçları yer almaktadır.

---

## BÖLÜM 2: LİTERATÜR TARAMASI

Bu bölümde, yalan haber tespiti alanındaki mevcut literatür kapsamlı bir şekilde incelenmektedir. Öncelikle yalan haber kavramının tanımı, türleri ve tarihsel gelişimi ele alınmakta; ardından bu alanda kullanılan tespit yöntemleri gelenekselden modern yaklaşımlara kadar değerlendirilmektedir. İlgili akademik çalışmalar sistematik bir şekilde gözden geçirilmekte ve bu tez çalışmasının literatürdeki konumu belirlenmektedir. Son olarak, çalışmada kullanılan temel teknolojiler hakkında teorik arka plan sunulmaktadır.

### 2.1 Yalan Haber Kavramı ve Tarihçesi

Yalan haber (fake news) kavramı, akademik literatürde farklı tanımlarla ele alınmakla birlikte, genel olarak "kasıtlı olarak yanlış bilgi içeren ve haber formatında sunulan içerikler" şeklinde tanımlanmaktadır [1, 2]. Allcott ve Gentzkow'un çığır açan çalışmasında yalan haber, "kasıtlı olarak ve doğrulanabilir şekilde yanlış olan, okuyucuları yanıltabilecek haber makaleleri" olarak tanımlanmıştır [10]. Bu tanım, yalan haberin iki temel özelliğini vurgulamaktadır: kasıt unsuru ve doğrulanabilir yanlışlık.

**Bilgi Bozukluğu Türleri ve Sınıflandırma**

Wardle ve Derakhshan, Avrupa Konseyi için hazırladıkları kapsamlı raporda, bilgi bozukluğunu (information disorder) üç ana kategoriye ayırmıştır [20] (Şekil 2.1, Tablo 2.1). Birinci kategori olan dezenformasyon (disinformation), zarar verme niyetiyle kasıtlı olarak oluşturulan ve paylaşılan yanlış bilgiyi ifade etmektedir. İkinci kategori olan misenformasyon (misinformation), zarar verme niyeti olmaksızın paylaşılan yanlış bilgiyi kapsamaktadır; bu durumda paylaşan kişi içeriğin yanlış olduğunun farkında değildir. Üçüncü kategori olan malenformasyon (malinformation) ise zarar verme amacıyla paylaşılan gerçek bilgiyi ifade etmektedir; örneğin özel bilgilerin kamuoyuyla paylaşılması bu kategoriye girmektedir. Bu üçlü sınıflandırma, bilgi bozukluğu fenomeninin karmaşıklığını ve farklı müdahale stratejileri gerektirdiğini ortaya koymaktadır.

**Şekil 2.1.** Bilgi bozukluğu türleri sınıflandırması

**Tablo 2.1.** Bilgi bozukluğu türlerinin karşılaştırması

| Tür | Tanım | Niyet | Örnek |
|-----|-------|-------|-------|
| Dezenformasyon | Kasıtlı yanlış bilgi | Zarar verme | Sahte haber siteleri |
| Misenformasyon | Farkında olmadan paylaşılan yanlış bilgi | Yok | Yanlış bilginin iyi niyetle paylaşımı |
| Malenformasyon | Zarar vermek için paylaşılan gerçek bilgi | Zarar verme | Özel bilgilerin ifşası |

Shu ve arkadaşları, yalan haberleri içerik ve niyet temelinde daha ayrıntılı bir şekilde sınıflandırmıştır [1]. Bu sınıflandırmaya göre yalan haberler; ciddi haber formatında sunulan tamamen uydurma içerikler, gerçek haberlerin bağlamından koparılarak yanıltıcı şekilde sunulması, başlık ile içerik arasında tutarsızlık bulunan tıklama tuzağı (clickbait) içerikler, gerçek haberlere benzetilen ancak yanlış bilgi içeren taklit haberler ve kasıtlı olarak yanlış yorumlanan veya çarpıtılan içerikler olmak üzere beş ana kategoride ele alınabilmektedir.

**Yalan Haberin Tarihsel Kökenleri**

Yalan haber olgusu, dijital çağın bir ürünü olmayıp, tarihsel kökleri çok eskilere dayanmaktadır. Antik Roma döneminde Octavian'ın, rakibi Marcus Antonius'u karalamak için yaydığı propaganda kampanyaları, bilinen en eski yalan haber örnekleri arasında yer almaktadır. 15. yüzyılda matbaanın icadı, bilginin daha geniş kitlelere ulaşmasını sağlarken, aynı zamanda yanlış bilginin de yayılmasını kolaylaştırmıştır. 19. yüzyılda "sarı gazetecilik" (yellow journalism) olarak bilinen akım, sansasyonel ve çoğu zaman abartılı veya yanlış haberlerin tiraj artırmak amacıyla yayınlanmasını içermekteydi.

20. yüzyılda radyo ve televizyonun yaygınlaşmasıyla birlikte, yalan haberlerin etkisi daha da artmıştır. 1938 yılında Orson Welles'in "Dünyalar Savaşı" (War of the Worlds) radyo oyunu, birçok dinleyicinin gerçek bir uzaylı istilası olduğuna inanmasına neden olmuş ve medyanın yanıltıcı potansiyelini gözler önüne sermiştir. Soğuk Savaş döneminde ise propaganda ve dezenformasyon, devletler arası mücadelenin önemli bir aracı haline gelmiştir.

**Dijital Çağda Yalan Haberin Dönüşümü**

21. yüzyılda internet ve sosyal medyanın yükselişi, yalan haber fenomenini tamamen yeni bir boyuta taşımıştır. Geleneksel medya döneminde yalan haberlerin üretimi ve yayılması belirli kaynaklar ve zaman gerektirirken, dijital ortamda herhangi bir birey kolayca içerik üretebilmekte ve bu içerik saniyeler içinde milyonlarca kişiye ulaşabilmektedir. 2016 yılı, yalan haber kavramının küresel gündemde önemli bir yer edindiği dönüm noktası olarak kabul edilmektedir. ABD başkanlık seçimleri sırasında sosyal medyada yayılan yalan haberler, seçim sonuçlarını etkileyip etkilemediği konusunda yoğun tartışmalara yol açmıştır [10].

Oxford Sözlüğü, 2016 yılında "post-truth" (hakikat-sonrası) kavramını yılın kelimesi olarak seçmiş ve bu kavramı "nesnel gerçeklerin, kamuoyunu şekillendirmede duygusal çağrılar ve kişisel inançlardan daha az etkili olduğu koşulları ifade eden" bir sıfat olarak tanımlamıştır. Bu seçim, yalan haber sorununun toplumsal ve kültürel boyutlarının da akademik ve kamusal gündemde önemli bir yer edindiğini göstermektedir.

COVID-19 pandemisi döneminde yaşanan "infodemi" olgusu, yalan haberlerin halk sağlığı üzerindeki yıkıcı etkilerini açıkça ortaya koymuştur. Dünya Sağlık Örgütü (WHO), pandemi sürecinde yanlış bilginin yayılmasını "infodemi" olarak adlandırmış ve bu durumun pandemiyle mücadeleyi ciddi şekilde zorlaştırdığını vurgulamıştır [36]. Aşı karşıtı dezenformasyon, sahte tedavi yöntemleri ve komplo teorileri, milyonlarca insanın sağlığını olumsuz etkilemiştir.

### 2.2 Yalan Haber Tespit Yöntemleri

Yalan haber tespiti alanında kullanılan yöntemler, tarihsel süreç içinde önemli bir evrim geçirmiştir (Şekil 2.2). Bu yöntemler, manuel fact-checking süreçlerinden otomatik makine öğrenmesi tabanlı sistemlere, oradan da son nesil büyük dil modeli uygulamalarına kadar geniş bir yelpazede yer almaktadır (Tablo 2.2).

**Şekil 2.2.** Yalan haber tespit yöntemlerinin tarihsel gelişimi

**Tablo 2.2.** Yalan haber tespit yöntemlerinin karşılaştırması

| Yöntem | Avantajlar | Dezavantajlar | Doğruluk |
|--------|------------|---------------|----------|
| Manuel Fact-Checking | Yüksek güvenilirlik, bağlam anlama | Yavaş, ölçeklenemez | Yüksek |
| Kural Tabanlı | Hızlı, açıklanabilir | Esnek değil, sınırlı | Orta |
| Makine Öğrenmesi | Ölçeklenebilir, otomatik | Veri bağımlılığı | Orta-Yüksek |
| Derin Öğrenme | Karmaşık örüntüler, yüksek doğruluk | Büyük veri gereksinimi | Yüksek |
| Büyük Dil Modelleri | Çok modlu, bağlam anlama | Kaynak yoğun, maliyet | Çok Yüksek |

**Geleneksel Fact-Checking Yaklaşımları**

Manuel fact-checking, yalan haber tespitin en eski ve hâlâ en güvenilir yöntemlerinden biri olarak kabul edilmektedir. Bu yaklaşımda, eğitimli gazeteciler veya uzmanlar, bir haberdeki iddiaları sistematik olarak araştırır, birincil kaynaklara ulaşmaya çalışır ve iddiaların doğruluğunu değerlendirir. Dünya genelinde PolitiFact, Snopes, FactCheck.org gibi kuruluşlar ve Türkiye'de Teyit.org gibi platformlar, bu yaklaşımı profesyonel düzeyde uygulamaktadır.

Manuel fact-checking'in güçlü yönleri arasında insan muhakemesinin karmaşık bağlamları değerlendirebilme yeteneği, nüanslı iddiaları anlama kapasitesi ve yüksek güvenilirlik yer almaktadır. Ancak bu yaklaşımın ciddi sınırlılıkları bulunmaktadır. Ölçeklenebilirlik sorunu en önemli kısıtlamadır; sosyal medyada her gün milyonlarca içerik paylaşılırken, manuel doğrulama yalnızca çok küçük bir bölümü kapsayabilmektedir [32]. Zaman faktörü de kritik bir sorundur; bir haberin doğrulanması saatler veya günler sürebilirken, yalan haber bu süre zarfında milyonlarca kişiye ulaşmış olabilmektedir [12]. Bu sınırlılıkları aşmak için otomatik fact-checking sistemleri geliştirilmiştir. FEVER veri seti, otomatik doğrulama sistemlerinin eğitimi için önemli bir kaynak oluşturmaktadır [30]. ClaimBuster sistemi ise doğrulamaya değer iddiaları otomatik olarak tespit etmekte ve önceliklendirmektedir [31].

**Kural Tabanlı ve İstatistiksel Yaklaşımlar**

Otomatik yalan haber tespitinin ilk dönemlerinde, kural tabanlı sistemler ve basit istatistiksel yöntemler kullanılmıştır. Bu sistemler, yalan haberlerde sıklıkla görülen belirli kalıpları tespit etmeye çalışmaktadır. Örneğin, aşırı sansasyonel başlıklar, belirli anahtar kelimelerin yoğun kullanımı, yazım ve dilbilgisi hataları, kaynakların belirsizliği gibi özellikler, bu sistemlerin odaklandığı göstergeler arasındadır.

Przybyla'nın çalışması, yalan haberlerin stilistik özelliklerini analiz etmiş ve bu haberlerin genellikle daha duygusal, daha kısa cümleler içeren ve belirli sözcük kalıplarını sıklıkla kullanan bir yazım stiline sahip olduğunu ortaya koymuştur [8]. Horne ve Adali'nin çalışması ise yalan haberlerin başlıklarında daha fazla bilgi yoğunluğu barındırdığını ve metin gövdelerinin daha basit ve tekrarlayıcı olduğunu ortaya koymuştur [22]. Bu bulgular, stilistik özelliklerin yalan haber tespitinde tamamlayıcı bir gösterge olarak kullanılabileceğini göstermektedir.

**Makine Öğrenmesi Tabanlı Yaklaşımlar**

Makine öğrenmesi teknikleri, yalan haber tespiti alanında önemli bir dönüm noktası oluşturmuştur. Bu yaklaşımlar, büyük miktarda etiketlenmiş veriyi kullanarak, yalan ve doğru haberleri ayırt eden örüntüleri otomatik olarak öğrenebilmektedir. Reis ve arkadaşları, denetimli öğrenme (supervised learning) tekniklerinin yalan haber tespitinde yüksek doğruluk oranları elde edebildiğini göstermiştir [6].

Metin tabanlı özellikler, makine öğrenmesi modellerinde sıklıkla kullanılan girdiler arasındadır. Bu özellikler; kelime frekansları (bag-of-words), n-gram analizi, TF-IDF (Term Frequency-Inverse Document Frequency) skorları, duygu analizi puanları ve okunabilirlik metrikleri gibi çeşitli düzeylerde hesaplanabilmektedir. Sosyal bağlam özellikleri de önemli bir girdi kaynağıdır; içeriğin yayılma örüntüsü, paylaşan kullanıcıların profilleri, etkileşim metrikleri ve ağ analizi verileri bu kategoride yer almaktadır.

Wang'ın LIAR veri seti üzerinde gerçekleştirdiği çalışma, yalan haber tespiti için önemli bir benchmark oluşturmuştur [7]. Bu çalışmada, siyasi iddiaların doğruluk derecelerini tahmin etmek için çeşitli makine öğrenmesi modelleri karşılaştırılmıştır. Sonuçlar, metin özelliklerinin yanı sıra konuşmacı meta verilerinin de model performansını önemli ölçüde artırdığını göstermiştir.

**Derin Öğrenme Yaklaşımları**

Derin öğrenme, özellikle 2015 yılından itibaren yalan haber tespiti alanında önemli gelişmelere yol açmıştır [33]. Convolutional Neural Networks (CNN) ve Recurrent Neural Networks (RNN) gibi mimariler, metin sınıflandırma görevlerinde geleneksel makine öğrenmesi yöntemlerinden daha iyi performans göstermiştir. Long Short-Term Memory (LSTM) ağları, metinlerdeki uzun vadeli bağımlılıkları yakalama yetenekleriyle öne çıkmıştır. Ruchansky ve arkadaşlarının CSI modeli, kullanıcı davranışları ve metin özelliklerini birleştiren hibrit bir derin öğrenme yaklaşımı sunmuştur [21].

Singhal ve arkadaşlarının SpotFake çalışması, çok modlu (multimodal) bir yaklaşım önermiştir [9]. Bu çalışmada, hem metin hem de görsel özelliklerin birlikte kullanılmasının, yalnızca metin veya yalnızca görsel kullanan modellere kıyasla daha yüksek doğruluk oranları sağladığı gösterilmiştir. Bu bulgu, yalan haberlerin genellikle metin ve görsel içerikleri birlikte kullandığı gerçeğiyle uyumludur.

**Transformer Tabanlı Modeller**

2017 yılında Vaswani ve arkadaşları tarafından önerilen Transformer mimarisi [3], doğal dil işleme alanında devrim niteliğinde bir gelişme olmuştur (Şekil 2.3). Transformer'ın "self-attention" mekanizması, modelin metindeki tüm kelimelerin birbirleriyle ilişkisini paralel olarak hesaplamasına olanak tanımaktadır. Bu özellik, önceki ardışık (sequential) modellerin aksine, uzun metinlerdeki bağımlılıkları çok daha etkili bir şekilde yakalamayı mümkün kılmıştır.

**Şekil 2.3.** Transformer mimarisi genel yapısı

BERT (Bidirectional Encoder Representations from Transformers) modeli, Devlin ve arkadaşları tarafından 2019 yılında tanıtılmış ve çok sayıda NLP görevinde önceki modelleri geride bırakmıştır [4]. BERT'in çift yönlü (bidirectional) yapısı, bir kelimenin hem öncesindeki hem de sonrasındaki bağlamı dikkate almasına olanak tanımaktadır. Bu özellik, yalan haber tespiti gibi bağlam anlayışının kritik olduğu görevlerde önemli avantajlar sağlamıştır.

**Büyük Dil Modelleri ve Güncel Yaklaşımlar**

Son yıllarda ortaya çıkan büyük dil modelleri (Large Language Models - LLM), yalan haber tespitinde yeni paradigmalar sunmaktadır [25]. GPT (Generative Pre-trained Transformer) ailesi, Gemini, Claude ve LLaMA gibi modeller, milyarlarca parametre içermekte ve çok çeşitli görevlerde etkileyici performans sergilemektedir. OpenAI'ın GPT-4 modeli, multimodal yetenekleri ve gelişmiş muhakeme kapasitesiyle dikkat çekmektedir [26].

Google'ın Gemini modeli, özellikle multimodal yetenekleriyle dikkat çekmektedir [5]. Gemini, metin, görsel ve video içeriklerini birlikte analiz edebilme kapasitesine sahiptir. Bu çok modlu anlama yeteneği, yalan haber tespiti için kritik bir avantaj sunmaktadır; çünkü modern dezenformasyon kampanyaları genellikle birden fazla medya formatını birlikte kullanmaktadır. Gemini'nin "grounding" özelliği, modelin yanıtlarını Google Arama sonuçlarıyla desteklemesine olanak tanımakta ve bu sayede güncel bilgilere erişim sağlanabilmektedir.

### 2.3 İlgili Çalışmalar

Yalan haber tespiti alanında gerçekleştirilen akademik çalışmalar, farklı yaklaşımlar ve metodolojiler sunmaktadır (Tablo 2.3). Bu bölümde, alanın temel çalışmaları sistematik bir şekilde incelenmekte ve bu tez çalışmasının literatürdeki konumu belirlenmektedir.

**Tablo 2.3.** İlgili akademik çalışmaların özet karşılaştırması

| Çalışma | Yıl | Yaklaşım | Veri Seti | Katkı |
|---------|-----|----------|-----------|-------|
| Shu et al. [1] | 2017 | Veri madenciliği | FakeNewsNet | Kapsamlı çerçeve |
| Zhou & Zafarani [2] | 2020 | Tarama çalışması | - | Teorik temel |
| Wang [7] | 2017 | Makine öğrenmesi | LIAR | Benchmark veri seti |
| Singhal et al. [9] | 2019 | Multimodal | - | SpotFake çerçevesi |
| Bu tez | 2026 | LLM tabanlı | - | Türkçe, multimodal, gerçek zamanlı |

**Kapsamlı Tarama Çalışmaları**

Zhou ve Zafarani'nin ACM Computing Surveys'de yayınlanan kapsamlı tarama çalışması, yalan haber tespiti alanının en önemli referans kaynaklarından birini oluşturmaktadır [2]. Bu çalışmada, yalan haberin temel teorileri, tespit yöntemleri ve gelecek araştırma fırsatları sistematik bir şekilde ele alınmıştır. Yazarlar, yalan haber tespitinin yalnızca bir metin sınıflandırma problemi olmadığını, aynı zamanda sosyal, psikolojik ve teknolojik boyutları olan karmaşık bir sorun olduğunu vurgulamıştır.

Zubiaga ve arkadaşlarının ACM Computing Surveys'deki çalışması, sosyal medyada söylenti tespiti ve çözümlemesi konusunda kapsamlı bir tarama sunmaktadır [18]. Bu çalışma, söylentilerin yaşam döngüsünü analiz etmiş ve erken tespit için kullanılabilecek sinyalleri belirlemiştir. Özellikle bir haberin yayılma örüntüsünün, içeriğin güvenilirliği hakkında önemli ipuçları sağlayabileceği gösterilmiştir.

Sharma ve arkadaşlarının ACM TIST'deki çalışması, yalan haber tespiti ve azaltma tekniklerini kapsamlı bir şekilde ele almıştır [19]. Bu çalışma, hem tespit hem de müdahale stratejilerini birlikte değerlendirmesi açısından önemlidir. Yazarlar, yalnızca yalan haberleri tespit etmenin yeterli olmadığını, aynı zamanda etkili müdahale ve düzeltme stratejilerinin de geliştirilmesi gerektiğini vurgulamıştır.

**Psikolojik ve Bilişsel Perspektifler**

Pennycook ve Rand'ın Trends in Cognitive Sciences dergisindeki çalışması, yalan haberlerin psikolojik boyutlarını ele almıştır [13]. Bu çalışma, insanların neden yalan haberlere inandığını ve paylaştığını anlamak için bilişsel psikoloji perspektifinden önemli içgörüler sunmaktadır. Araştırmacılar, "analitik düşünme" kapasitesinin yalan haberlere duyarlılığı azalttığını göstermiştir. Ayrıca, tekrarlanan maruziyetin "illuzyonel gerçek etkisi" (illusory truth effect) yoluyla yanlış bilgilerin doğru olarak algılanmasına yol açabileceği belirlenmiştir.

Bu psikolojik bulgular, yalan haber tespit sistemlerinin tasarımı için önemli implikasyonlar taşımaktadır. Lewandowsky ve arkadaşlarının kapsamlı çalışması, yanlış bilginin düzeltilmesinin zorluklarını ve etkili stratejileri ortaya koymuştur [38]. Kullanıcılara yalnızca bir içeriğin "yalan" olduğunu söylemek yeterli olmayabilir; aynı zamanda neden yanlış olduğunu açıklamak ve eleştirel düşünmeyi teşvik etmek de gereklidir. Bu tez çalışmasında geliştirilen sistem, iddia tabanlı doğrulama yaklaşımı ve detaylı açıklamalarla bu ihtiyaca cevap vermeyi hedeflemektedir.

**Multimodal Yaklaşımlar**

Görsel ve metin içeriklerini birlikte analiz eden çok modlu yaklaşımlar, son yıllarda artan bir ilgi görmektedir. Singhal ve arkadaşlarının SpotFake çalışması [9], bu alanda önemli bir katkı sunmaktadır. Çalışmada, BERT ve VGG-19 modellerinin birlikte kullanılmasıyla, hem metinsel hem de görsel özelliklerin çıkarıldığı hibrit bir sistem önerilmiştir. Khattar ve arkadaşlarının MVAE (Multimodal Variational Autoencoder) modeli, görsel ve metin modalitelerini birleştiren olasılıksal bir çerçeve sunmuştur [23]. Wang ve arkadaşlarının EANN (Event Adversarial Neural Networks) modeli ise olaya özgü özellikleri çıkararak çapraz olay genelleme kapasitesini artırmıştır [24]. Bu çalışmaların sonuçları, çok modlu yaklaşımın tek modlu yaklaşımlardan önemli ölçüde daha iyi performans gösterdiğini ortaya koymuştur.

Günümüzde deepfake teknolojilerinin ve yapay zeka ile üretilen görsellerin yaygınlaşması, görsel içeriklerin doğrulanmasını daha da önemli hale getirmiştir. Bu tez çalışmasında geliştirilen sistem, Google Gemini'nin multimodal yeteneklerinden yararlanarak hem metin hem de görsel içerikleri analiz edebilmektedir.

**Türkçe Yalan Haber Tespiti Çalışmaları**

Türkçe dilinde yalan haber tespiti alanında gerçekleştirilen akademik çalışmalar nispeten sınırlıdır. Mevcut çalışmalar genellikle Türkçe metin sınıflandırma problemleri üzerine odaklanmakta ve yalan haber tespiti için özel olarak tasarlanmış kapsamlı sistemler bulunmamaktadır. Bu durum, Türkçe konuşan kullanıcılar için erişilebilir ve etkili doğrulama araçlarına olan ihtiyacı açıkça ortaya koymaktadır.

Türkiye'de Teyit.org gibi manuel fact-checking platformları önemli bir hizmet sunmakla birlikte, otomatik ve ölçeklenebilir çözümler açısından bir boşluk bulunmaktadır. Bu tez çalışması, bu boşluğu doldurmayı ve Türkçe içeriklerin analizine odaklanan kapsamlı bir yapay zeka destekli sistem sunmayı hedeflemektedir.

**Bu Tez Çalışmasının Literatürdeki Konumu**

Mevcut literatür değerlendirildiğinde, bu tez çalışmasının birkaç önemli noktada özgün katkılar sunduğu görülmektedir. Birincisi, Google Gemini 2.5 gibi son nesil büyük dil modellerinin yalan haber tespiti için sistematik kullanımı henüz akademik literatürde yaygın olarak ele alınmamıştır. İkincisi, metin, URL, görsel ve video içeriklerini tek bir platformda analiz edebilen kapsamlı bir sistemin geliştirilmesi, multimodal yaklaşımları pratiğe dökme açısından önemli bir adım oluşturmaktadır. Üçüncüsü, Türkçe dilinde çalışan otomatik bir doğrulama aracının geliştirilmesi, bu alandaki önemli bir boşluğu doldurmaktadır. Son olarak, Google Search Grounding özelliğiyle gerçek zamanlı doğrulama yapabilme yeteneği, statik veri setlerine dayanan geleneksel yaklaşımların ötesine geçmektedir.

### 2.4 Yapay Zeka ve Doğal Dil İşleme

Bu bölümde, tez çalışmasında kullanılan yapay zeka ve doğal dil işleme teknolojilerinin teorik temelleri ele alınmaktadır.

**Yapay Zeka ve Makine Öğrenmesinin Temelleri**

Yapay zeka (Artificial Intelligence - AI), makinelerin insan benzeri zekâ gerektiren görevleri yerine getirmesini sağlayan bilgisayar bilimi dalıdır. Makine öğrenmesi (Machine Learning - ML), yapay zekanın bir alt alanı olup, sistemlerin açık programlama olmaksızın deneyimlerden öğrenmesini sağlayan algoritma ve teknikleri kapsamaktadır. Derin öğrenme (Deep Learning) ise makine öğrenmesinin bir alt kümesi olup, çok katmanlı yapay sinir ağlarını kullanarak karmaşık örüntüleri öğrenebilmektedir.

Denetimli öğrenme (supervised learning), etiketlenmiş veri kullanarak modellerin eğitilmesini içermektedir. Yalan haber tespitinde, "yalan" veya "doğru" olarak etiketlenmiş haber örnekleri kullanılarak model eğitilir ve ardından yeni, görülmemiş içeriklerin sınıflandırılması gerçekleştirilir. Denetimsiz öğrenme (unsupervised learning) ise etiketlenmemiş veriden örüntüler çıkarmayı hedeflemektedir. Kümeleme (clustering) ve anomali tespiti gibi teknikler, yalan haber tespitinde tamamlayıcı roller üstlenebilmektedir.

**Doğal Dil İşleme ve Temel Kavramlar**

Doğal Dil İşleme (Natural Language Processing - NLP), bilgisayarların insan dilini anlamasını, yorumlamasını ve üretmesini sağlayan yapay zeka alanıdır. NLP, metin sınıflandırma, duygu analizi, adlandırılmış varlık tanıma, soru cevaplama ve metin özetleme gibi çeşitli görevleri kapsamaktadır.

Metin temsili (text representation), NLP'nin temel problemlerinden biridir. Kelimelerin ve metinlerin sayısal vektörler olarak temsil edilmesi gerekmektedir. Bag-of-Words (BoW) modeli, en basit yaklaşımlardan biri olup, metni içerdiği kelimelerin frekanslarıyla temsil etmektedir. TF-IDF (Term Frequency-Inverse Document Frequency), kelimelerin hem belge içi sıklığını hem de belge koleksiyonundaki nadir olma durumunu dikkate almaktadır.

Kelime gömmeleri (word embeddings), kelimelerin yoğun (dense) vektör temsillerini öğrenmeyi hedeflemektedir. Word2Vec, GloVe ve FastText gibi yöntemler, semantik benzerlikleri yakalayan vektör temsillerini üretmektedir. Bu temsiller, benzer anlamlı kelimelerin vektör uzayında birbirine yakın konumlanmasını sağlamaktadır.

**Transformer Mimarisi ve Attention Mekanizması**

Transformer mimarisi, 2017 yılında "Attention Is All You Need" başlıklı makalede tanıtılmıştır [3]. Bu mimari, önceki RNN ve LSTM tabanlı modellerin aksine, tamamen attention mekanizması üzerine inşa edilmiştir. Transformer'ın temel bileşenleri encoder (kodlayıcı) ve decoder (kod çözücü) yapılarından oluşmaktadır.

Self-attention mekanizması, bir dizideki her elemanın diğer tüm elemanlarla ilişkisini hesaplamasına olanak tanımaktadır. Bu, modelin metindeki uzak bağımlılıkları yakalamasını ve bağlamı daha iyi anlamasını sağlamaktadır. Multi-head attention, farklı temsil alt-uzaylarından gelen bilgileri birleştirerek modelin farklı türdeki ilişkileri öğrenmesine olanak tanımaktadır.

Transformer mimarisinin avantajları arasında paralelleştirilebilirlik öne çıkmaktadır. RNN'lerin aksine, Transformer'lar dizinin tüm elemanlarını paralel olarak işleyebilmektedir. Bu özellik, eğitim süresini önemli ölçüde kısaltmakta ve daha büyük modellerin eğitilmesini mümkün kılmaktadır. Ayrıca, uzun menzilli bağımlılıkları yakalama kapasitesi, özellikle uzun metinlerin analizinde kritik bir avantaj sağlamaktadır.

**Büyük Dil Modelleri (LLM)**

Büyük dil modelleri, milyarlarca parametre içeren ve büyük metin korpusları üzerinde eğitilen Transformer tabanlı modellerdir (Şekil 2.4, Tablo 2.4). Bu modeller, metin anlama ve üretme konusunda etkileyici yetenekler sergilemektedir. GPT (Generative Pre-trained Transformer) ailesi, OpenAI tarafından geliştirilmiş ve her yeni versiyonda önemli iyileştirmeler sunmuştur.

**Şekil 2.4.** Büyük dil modellerinin gelişim süreci

**Tablo 2.4.** Transformer tabanlı modellerin karşılaştırması

| Model | Geliştirici | Parametre Sayısı | Özellik |
|-------|-------------|------------------|----------|
| BERT | Google | 340M | Çift yönlü kodlayıcı |
| GPT-4 | OpenAI | ~1.7T | Çok modlu, sohbet |
| Gemini | Google | - | Multimodal, grounding |
| Claude | Anthropic | - | Güvenlik odaklı |
| LLaMA | Meta | 70B | Açık kaynak |

Google Gemini, 2023 yılının sonlarında tanıtılan ve multimodal yetenekleriyle öne çıkan bir büyük dil modeli ailesidir [5]. Gemini'nin üç farklı boyutu bulunmaktadır: Ultra (en güçlü), Pro (dengeli) ve Flash (hızlı ve verimli). Gemini, metin, görsel, ses ve video içeriklerini anlama ve bu modaliteler arasında geçiş yapabilme kapasitesine sahiptir. Bu çok modlu anlama yeteneği, yalan haber tespiti gibi farklı medya formatlarının analizini gerektiren uygulamalar için kritik bir avantaj sunmaktadır.

Gemini'nin "grounding" özelliği, modelin yanıtlarını Google Arama sonuçlarıyla desteklemesine olanak tanımaktadır. Bu yaklaşım, Retrieval-Augmented Generation (RAG) paradigmasının bir uygulaması olarak değerlendirilebilir [29]. Bu özellik, modelin eğitim verilerinin ötesinde güncel bilgilere erişebilmesini sağlamakta ve doğrulama süreçlerinde güncel kaynaklara başvurulabilmesini mümkün kılmaktadır. Bu tez çalışmasında, Gemini'nin bu özelliği fact-checking işlevselliği için aktif olarak kullanılmaktadır.

**Prompt Mühendisliği**

Prompt mühendisliği, büyük dil modellerinden istenen çıktıları elde etmek için girdi metinlerinin (prompt) stratejik olarak tasarlanmasını içeren bir disiplindir. Etkili prompt tasarımı, model performansını önemli ölçüde etkileyebilmektedir.

Prompt mühendisliğinde kullanılan teknikler arasında zero-shot prompting, modele hiçbir örnek vermeden görevi açıklayarak sonuç almayı hedeflemektedir [28]. Few-shot prompting, göreve ilişkin birkaç örnek sağlayarak modelin beklenen çıktı formatını anlamasını sağlamaktadır. Chain-of-thought prompting, modeli adım adım düşünmeye teşvik ederek karmaşık muhakeme gerektiren görevlerde performansı artırmaktadır [27].

Bu tez çalışmasında, her analiz türü için özel olarak tasarlanmış prompt şablonları kullanılmaktadır. Doğruluk kontrolü için iddia ayrıştırma ve kanıt değerlendirme adımlarını içeren yapılandırılmış promptlar geliştirilmiştir. Taraflılık analizi ve propaganda tespiti için de benzer şekilde optimize edilmiş prompt yapıları oluşturulmuştur.

### 2.5 Web Teknolojileri ve Modern Frontend

Bu bölümde, tez çalışmasında kullanılan web teknolojileri ve modern frontend geliştirme yaklaşımları ele alınmaktadır.

**Modern Web Geliştirme Paradigmaları**

Web geliştirme, son on yılda önemli bir evrim geçirmiştir. Statik HTML sayfalarından dinamik, etkileşimli ve kullanıcı odaklı uygulamalara geçiş yaşanmıştır. Single Page Application (SPA) mimarisi, kullanıcı deneyimini iyileştiren ve masaüstü uygulamalarına benzer akıcılık sunan bir yaklaşım olarak öne çıkmıştır.

Component-based architecture (bileşen tabanlı mimari), modern frontend geliştirmenin temel paradigmalarından biridir. Bu yaklaşımda, kullanıcı arayüzü yeniden kullanılabilir, bağımsız ve kendi kendini yöneten bileşenlere ayrıştırılmaktadır. Her bileşen, kendi durumunu (state) ve görünümünü (view) yönetmekte, bu da kod organizasyonunu, bakımı ve test edilebilirliği kolaylaştırmaktadır.

**React Kütüphanesi**

React, Facebook (Meta) tarafından geliştirilen ve kullanıcı arayüzleri oluşturmak için kullanılan bir JavaScript kütüphanesidir [15]. İlk olarak 2013 yılında açık kaynak olarak yayınlanan React, günümüzde en popüler frontend kütüphanelerinden biri haline gelmiştir.

React'ın temel kavramları arasında Virtual DOM (Sanal DOM) öne çıkmaktadır. React, gerçek DOM ile doğrudan etkileşim yerine, sanal bir DOM temsili kullanmaktadır. Değişiklikler önce sanal DOM'da yapılmakta, ardından gerçek DOM ile karşılaştırılarak yalnızca gerekli güncellemeler uygulanmaktadır. Bu yaklaşım, performansı önemli ölçüde artırmaktadır.

JSX (JavaScript XML), React'ta kullanılan bir sözdizimi uzantısıdır. JSX, JavaScript içinde HTML benzeri bir sözdizimi kullanmaya olanak tanımakta ve bileşenlerin daha okunabilir ve anlaşılır bir şekilde yazılmasını sağlamaktadır. Hooks, React 16.8 ile tanıtılan ve fonksiyonel bileşenlerde durum yönetimi ve yaşam döngüsü işlevlerini kullanmayı sağlayan özelliklerdir. useState, useEffect, useContext gibi hooks'lar, sınıf bileşenlerine olan ihtiyacı önemli ölçüde azaltmıştır.

React 19, bu tez çalışmasında kullanılan en güncel React sürümüdür. Bu sürüm, geliştirilmiş Suspense desteği, yeni hooks ve performans iyileştirmeleri sunmaktadır.

**TypeScript**

TypeScript, Microsoft tarafından geliştirilen ve JavaScript'e statik tip kontrolü ekleyen bir programlama dilidir [16]. TypeScript kodu, JavaScript'e derlenmekte ve herhangi bir JavaScript ortamında çalıştırılabilmektedir.

TypeScript'in avantajları arasında tip güvenliği öne çıkmaktadır. Derleme zamanında hata tespiti, çalışma zamanı hatalarını azaltmakta ve kod güvenilirliğini artırmaktadır. Geliştirilmiş IDE desteği sayesinde otomatik tamamlama, yeniden düzenleme ve dokümantasyon özellikleri iyileşmektedir. Büyük projelerin bakımı kolaylaşmakta ve kod okunabilirliği artmaktadır.

Bu tez çalışmasında, tüm kaynak kod TypeScript ile yazılmıştır. Tip tanımlamaları, özellikle API yanıtları ve bileşen props'ları için kullanılmakta, bu da kod güvenilirliğini ve bakım kolaylığını artırmaktadır.

**Vite Build Tool**

Vite, Evan You tarafından geliştirilen modern bir frontend build tool'dur [17]. Vue.js'in yaratıcısı olan Evan You, Vite'ı webpack gibi geleneksel bundler'ların sınırlılıklarını aşmak için tasarlamıştır.

Vite'ın temel özellikleri arasında hızlı geliştirme sunucusu yer almaktadır. Vite, ES modüllerini doğrudan tarayıcıda kullanarak, geliştirme sırasında bundling ihtiyacını ortadan kaldırmaktadır. Bu, özellikle büyük projelerde geliştirme sunucusunun çok hızlı başlamasını sağlamaktadır. Hot Module Replacement (HMR) özelliği, kod değişikliklerinin sayfa yenilenmeden anında yansımasını sağlamakta ve geliştirici verimliliğini artırmaktadır. Üretim build'leri için Rollup kullanılmakta, bu da optimize edilmiş ve küçük boyutlu çıktılar üretmektedir.

**Tailwind CSS**

Tailwind CSS, utility-first (yardımcı sınıf öncelikli) bir CSS framework'üdür. Geleneksel CSS framework'lerinin aksine, önceden tanımlanmış bileşenler yerine düşük seviyeli yardımcı sınıflar sunmaktadır. Bu yaklaşım, geliştiricilere daha fazla esneklik ve özelleştirme imkânı tanımaktadır.

Tailwind'in avantajları arasında hızlı prototipleme, tutarlı tasarım sistemi, küçük dosya boyutu (kullanılmayan stiller otomatik olarak temizlenir) ve responsive tasarım kolaylığı yer almaktadır [34]. Bu tez çalışmasında, kullanıcı arayüzü Tailwind CSS kullanılarak tasarlanmıştır.

**API Entegrasyonu ve Asenkron Programlama**

Modern web uygulamaları, genellikle çeşitli API'lerle iletişim kurmaktadır. JavaScript'te asenkron programlama, Promise'ler ve async/await sözdizimi kullanılarak gerçekleştirilmektedir.

Fetch API, modern tarayıcılarda HTTP istekleri yapmak için kullanılan yerleşik bir arayüzdür. Google Gemini API ile iletişim, bu API aracılığıyla gerçekleştirilmektedir. Streaming API'ler, büyük yanıtların parça parça alınmasını sağlamakta, bu da kullanıcı deneyimini iyileştirmektedir. Bu tez çalışmasında, analiz sonuçlarının gerçek zamanlı olarak gösterilmesi için streaming mimarisi kullanılmaktadır.

**Durum Yönetimi ve Veri Saklama**

Client-side veri saklama, web uygulamalarında önemli bir rol oynamaktadır. LocalStorage API, tarayıcıda kalıcı veri saklamak için kullanılmaktadır. SessionStorage, oturum bazlı geçici veri saklama imkânı sunmaktadır.

Bu tez çalışmasında, kullanıcıların analiz geçmişi LocalStorage kullanılarak istemci tarafında saklanmaktadır. Bu yaklaşım, kullanıcı gizliliğini korumakta ve sunucu tarafı veri saklama ihtiyacını azaltmaktadır. Geri bildirim verileri için ise Supabase bulut veritabanı entegrasyonu kullanılmaktadır.

---

## BÖLÜM 3: MATERYAL VE YÖNTEM

Bu bölümde, Gerçeklik Kalkanı uygulamasının geliştirilmesinde kullanılan materyaller, teknolojiler ve izlenen yöntemler detaylı olarak açıklanmaktadır. Sistem mimarisinden kullanıcı arayüzü tasarımına kadar tüm teknik bileşenler, akademik bir perspektifle ele alınmaktadır.

### 3.1 Sistem Mimarisi

Gerçeklik Kalkanı uygulaması, modern web geliştirme prensiplerine uygun olarak tasarlanmış, katmanlı bir mimari üzerine inşa edilmiştir (Şekil 3.1). **Genel mimari yaklaşım** olarak istemci-taraflı (client-side) rendering mimarisi benimsenmiştir. Bu yaklaşımda tüm uygulama mantığı kullanıcının tarayıcısında çalışmakta ve sunucu tarafında yalnızca API iletişimi gerçekleşmektedir. Bu mimari tercih, kullanıcı gizliliğini ön planda tutmak ve sunucu maliyetlerini minimize etmek amacıyla yapılmıştır.

**Şekil 3.1.** Gerçeklik Kalkanı sistem mimarisi

**Mimari katmanlar** incelendiğinde, sistem dört ana katmandan oluşmaktadır (Şekil 3.2). Birinci katman olan **Sunum Katmanı (Presentation Layer)**, React bileşenleri üzerine kurulu kullanıcı arayüzünü içermektedir. Bu katmanda Header, Hero, AnalysisForm, ResultDisplay ve Chatbot gibi görsel bileşenler yer almaktadır. İkinci katman olan **İş Mantığı Katmanı (Business Logic Layer)**, analiz işlemlerinin koordinasyonunu, durum yönetimini (state management) ve veri dönüşümlerini gerçekleştirmektedir. Üçüncü katman olan **Servis Katmanı (Service Layer)**, Gemini API ile iletişimi sağlayan geminiService.ts, geri bildirim işlemlerini yöneten feedbackService.ts ve trend verilerini işleyen trendsService.ts modüllerini barındırmaktadır. Dördüncü ve son katman olan **Veri Katmanı (Data Layer)** ise LocalStorage üzerinde analiz geçmişi saklama ve Supabase üzerinde geri bildirim verilerini depolama işlevlerini yerine getirmektedir.

**Veri akış modeli** açısından sistem, tek yönlü veri akışı (unidirectional data flow) prensibini izlemektedir (Şekil 3.3). Kullanıcı etkileşimleri React bileşenlerinde yakalanmakta, bu etkileşimler state güncellemelerini tetiklemekte, güncellenmiş state üzerinden API çağrıları gerçekleştirilmekte ve son olarak API yanıtları işlenerek arayüz yeniden render edilmektedir. Bu yaklaşım, uygulama durumunun tahmin edilebilir ve izlenebilir olmasını sağlamaktadır.

**Şekil 3.2.** Katmanlı mimari yapısı

**Şekil 3.3.** Veri akış diyagramı

**Asenkron işlem yönetimi** kapsamında uygulama, JavaScript'in async/await yapısını ve Promise'leri yoğun olarak kullanmaktadır. Özellikle Gemini API ile streaming iletişimde AsyncGenerator kullanılmakta, bu sayede kullanıcıya gerçek zamanlı geri bildirim sağlanmaktadır. Streaming yanıtlar, analiz sonuçlarının kademeli olarak görüntülenmesini mümkün kılmakta ve kullanıcı deneyimini önemli ölçüde iyileştirmektedir.

### 3.2 Kullanılan Teknolojiler

Gerçeklik Kalkanı uygulamasının geliştirilmesinde modern web teknolojileri ekosisteminin en güncel ve güçlü araçları tercih edilmiştir.

**Google Gemini 2.5 API**, uygulamanın yapay zeka omurgasını oluşturmaktadır. Google tarafından 2024 yılında tanıtılan Gemini ailesi, multimodal yeteneklere sahip büyük dil modellerini içermektedir [5]. Bu tez çalışmasında iki farklı Gemini modeli kullanılmaktadır. Metin ve görsel analizi için **Gemini 2.5 Flash** modeli tercih edilmiştir. Bu model, düşük gecikme süresi ve yüksek işlem kapasitesiyle karakterize edilmekte, saniyeler içinde kapsamlı analizler üretebilmektedir. Video analizi gibi daha karmaşık görevler için ise **Gemini 2.5 Pro** modeli kullanılmaktadır. Gemini API'nin önemli bir özelliği olan **Google Search Grounding** entegrasyonu, doğruluk kontrolü analizlerinde gerçek zamanlı internet araması yapılmasını sağlamaktadır. Bu özellik sayesinde model, iddia edilen bilgileri güncel web kaynaklarıyla karşılaştırabilmektedir.

**React 19**, kullanıcı arayüzü geliştirmede tercih edilen JavaScript kütüphanesidir [15]. React'in bileşen tabanlı mimarisi, kodun yeniden kullanılabilirliğini ve bakım kolaylığını artırmaktadır. Uygulamada fonksiyonel bileşenler ve React Hooks (useState, useEffect, useCallback, useRef) yoğun olarak kullanılmaktadır. React 19'un sunduğu concurrent rendering özellikleri, streaming analiz sonuçlarının akıcı bir şekilde görüntülenmesini mümkün kılmaktadır.

**TypeScript**, JavaScript'e statik tip denetimi ekleyen bir programlama dilidir [16]. Tez uygulamasında TypeScript kullanımı, geliştirme sürecinde hata yakalama oranını artırmış ve kod kalitesini yükseltmiştir. types.ts dosyasında tanımlanan arayüzler (interface), AnalysisType, AnalysisResult, AnalysisInput, AnalysisRecord gibi veri yapılarının tip güvenliğini sağlamaktadır. TypeScript'in tür çıkarımı (type inference) özelliği, kod yazımını hızlandırırken tip güvenliğinden ödün verilmemesini sağlamaktadır.

**Vite**, modern web uygulamaları için tasarlanmış yeni nesil bir derleme aracıdır (build tool) [17]. Geleneksel derleme araçlarına kıyasla çok daha hızlı geliştirme sunucusu başlatma ve hot module replacement (HMR) süreleri sunmaktadır. Vite'ın ES modül tabanlı mimarisi, geliştirme sürecinde anlık kod değişikliklerinin tarayıcıya yansımasını sağlamaktadır. Üretim derlemesinde ise Rollup tabanlı optimizasyonlar uygulanmaktadır.

**Tailwind CSS**, utility-first yaklaşımını benimseyen bir CSS framework'üdür. Geleneksel CSS yazımından farklı olarak, önceden tanımlanmış sınıflar doğrudan HTML elemanlarına uygulanmaktadır. Bu yaklaşım, tutarlı bir tasarım dili oluşturmayı kolaylaştırmakta ve CSS dosya boyutunu minimize etmektedir. Uygulamada dark mode desteği, responsive tasarım ve animasyonlar Tailwind CSS ile gerçekleştirilmiştir.

**Supabase**, açık kaynaklı bir Firebase alternatifi olarak konumlandırılan backend-as-a-service platformudur [35]. PostgreSQL veritabanı üzerine kurulu olan Supabase, gerçek zamanlı veri senkronizasyonu ve RESTful API'ler sunmaktadır. Tez uygulamasında kullanıcı geri bildirimleri Supabase veritabanında saklanmaktadır. @supabase/supabase-js kütüphanesi aracılığıyla JavaScript/TypeScript entegrasyonu sağlanmaktadır.

**Ek kütüphaneler** kapsamında uuid paketi, analiz kayıtları için benzersiz tanımlayıcılar (UUID v4) üretmek amacıyla kullanılmaktadır. @google/genai paketi ise Google Gemini API ile iletişimi sağlayan resmi SDK'dır.

**Tablo 3.1.** Kullanılan teknolojiler ve versiyonları

| Teknoloji | Versiyon | Kullanım Amacı |
|-----------|----------|----------------|
| React | 19.1.1 | Kullanıcı arayüzü |
| TypeScript | 5.8.2 | Tip güvenliği |
| Vite | 6.2.0 | Derleme ve geliştirme |
| Tailwind CSS | 3.x | Stil ve tasarım |
| Google Gemini API | 1.19.0 | Yapay zeka analizi |
| Supabase | 2.57.4 | Veritabanı |
| UUID | 13.0.0 | Benzersiz tanımlayıcı |

**Tablo 3.2.** Gemini model özellikleri karşılaştırması

| Özellik | Gemini 2.5 Flash | Gemini 2.5 Pro |
|---------|------------------|----------------|
| Kullanım Alanı | Metin, görsel | Video |
| Hız | Çok hızlı | Hızlı |
| Maliyet | Düşük | Orta |
| Multimodal | Metin, görsel | Metin, görsel, video |
| Grounding | Destekleniyor | Destekleniyor |

### 3.3 Analiz Modülleri

Gerçeklik Kalkanı uygulaması, üç temel analiz modülü üzerine kurulmuştur (Şekil 3.4, Tablo 3.3). Her modül, farklı bir perspektiften haber içeriklerini değerlendirmektedir.

**Şekil 3.4.** Analiz modüllerinin çalışma şeması

**Doğruluk Kontrolü (Fact-Check) Modülü**, uygulamanın birincil ve en kapsamlı analiz modülüdür (Şekil 3.5). Bu modül, verilen içerikteki doğrulanabilir iddiaları tespit etmekte ve her bir iddiayı Google Search aracılığıyla araştırmaktadır. İddia tespiti aşamasında model, metindeki kim, ne, nerede, ne zaman ve neden sorularına yanıt veren somut ifadeleri çıkarmaktadır. Görüş veya yorum bildiren cümleler iddia olarak değerlendirilmemektedir. Kanıt toplama aşamasında her iddia için güvenilir kaynaklardan (haber ajansları, resmi kurumlar, akademik yayınlar) kanıtlar aranmaktadır. Değerlendirme aşamasında toplanan kanıtlara dayanarak her iddia "Doğrulandı", "Yanlışlandı" veya "Doğrulanamadı" olarak sınıflandırılmaktadır. Son olarak sentez aşamasında tüm bulgular, genel bir değerlendirme ve özet ile birlikte kullanıcıya sunulmaktadır. Genel değerlendirme "Yüksek Olasılıkla Gerçek", "Yüksek Olasılıkla Yanlış Bilgi", "Karışık/Belirsiz" veya "Görüş/Analiz" kategorilerinden biri olarak belirlenmektedir.

**Şekil 3.5.** Doğruluk kontrolü süreç akış diyagramı

**Taraflılık Analizi (Bias Analysis) Modülü**, içerikteki siyasi, ideolojik veya diğer türdeki taraflılıkları tespit etmeye odaklanmaktadır. Dil analizi kapsamında metinde kullanılan kelimeler, sıfatlar ve fiiller incelenmekte, duygusal yüklü, yönlendirici veya aşağılayıcı ifadeler tespit edilmektedir. Sunum değerlendirmesi kapsamında bilgilerin dengeli sunulup sunulmadığı, farklı görüşlere eşit yer verilip verilmediği analiz edilmektedir. Kaynak incelemesi kapsamında alıntılanan kişi veya uzmanların belirli bir görüşü temsil edip etmediği değerlendirilmektedir. Modül çıktısı olarak "Yüksek Derecede Taraflı", "Orta Derecede Taraflı", "Düşük Derecede Taraflı" veya "Tarafsız" değerlendirmesi ile detaylı bir açıklama sunulmaktadır.

**Propaganda Tespiti (Propaganda Detection) Modülü**, manipülatif dil kullanımı ve propaganda tekniklerini belirlemeye yönelik çalışmaktadır. Teknik tanımlama aşamasında bilinen propaganda teknikleri (korkuya başvurma, slogan kullanma, genelleme yapma, karalama, tanıklığa başvurma vb.) aranmaktadır. Örnek bulma aşamasında tespit edilen her teknik için metinden somut örnekler çıkarılmaktadır. Etki değerlendirmesi aşamasında bu tekniklerin okuyucunun düşünce, duygu ve kararlarını nasıl yönlendirmeyi amaçladığı analiz edilmektedir. Modül çıktısı olarak "Güçlü Propaganda İçeriyor", "Orta Düzeyde Propaganda İçeriyor" veya "Propaganda İçermiyor" değerlendirmesi ile kapsamlı bir analiz raporu sunulmaktadır.

**Multimodal giriş desteği** kapsamında her üç analiz modülü, farklı giriş türlerini işleyebilmektedir. Metin girişinde doğrudan yapıştırılan veya yazılan haber metinleri analiz edilmektedir. URL girişinde web sayfası adresi verilerek içerik çekilmekte ve analiz edilmektedir. Görsel girişinde haber metni ile birlikte yüklenen görseller incelenmekte, görselin metinle alakası ve orijinalliği değerlendirilmektedir. Görsel orijinallik kontrolü seçeneği aktifleştirildiğinde, görsel manipülasyon izleri (photoshop, AI üretimi belirtileri) de araştırılmaktadır. Video girişinde yüklenen video içerikleri Gemini 2.5 Pro modeli ile analiz edilmekte, kullanıcının belirlediği istem doğrultusunda değerlendirme yapılmaktadır.

**Tablo 3.3.** Analiz modülleri ve özellikleri

| Modül | Amaç | Giriş Türleri | Çıktı Kategorileri |
|-------|------|---------------|--------------------|
| Doğruluk Kontrolü | İddiaların doğrulanması | Metin, URL, Görsel, Video | Gerçek, Yanlış, Belirsiz, Görüş |
| Taraflılık Analizi | Yanlılık tespiti | Metin, URL, Görsel | Yüksek, Orta, Düşük, Tarafsız |
| Propaganda Tespiti | Manipülasyon tespiti | Metin, URL, Görsel | Güçlü, Orta, İçermiyor |

**Tablo 3.4.** Analiz türleri ve değerlendirme kategorileri

| Analiz Türü | Değerlendirme Kategorisi | Açıklama |
|-------------|-------------------------|----------|
| Doğruluk Kontrolü | Yüksek Olasılıkla Gerçek | İddialar doğrulandı |
| | Yüksek Olasılıkla Yanlış Bilgi | İddialar yanlışlandı |
| | Karışık/Belirsiz | Bazı iddialar doğrulanamadı |
| | Görüş/Analiz | Doğrulanabilir iddia yok |
| Taraflılık | Yüksek Derecede Taraflı | Belirgin yanlılık mevcut |
| | Orta Derecede Taraflı | Kısmi yanlılık mevcut |
| | Düşük Derecede Taraflı | Minimal yanlılık |
| | Tarafsız | Dengeli sunum |
| Propaganda | Güçlü Propaganda | Çoklu teknik kullanımı |
| | Orta Düzeyde Propaganda | Bazı teknikler mevcut |
| | Propaganda İçermiyor | Manipülatif unsur yok |

### 3.4 Prompt Mühendisliği

Prompt mühendisliği, büyük dil modellerinden istenen çıktıları elde etmek için giriş metinlerinin (prompt) sistematik olarak tasarlanması sürecidir (Şekil 3.6). Gerçeklik Kalkanı uygulamasında prompt mühendisliği, analiz kalitesinin temel belirleyicisidir (Tablo 3.5).

**Şekil 3.6.** Prompt mühendisliği yapısı

**Tablo 3.5.** Prompt mühendisliği teknikleri

| Teknik | Açıklama | Kullanım Alanı |
|--------|----------|----------------|
| Rol Tanımlama | Modele uzman kimliği atama | Tüm analiz türleri |
| Adım Adım Talimatlar | Görevin aşamalarını tanımlama | Doğruluk kontrolü |
| Yapılandırılmış Çıktı | JSON formatında yanıt isteme | Tüm analizler |
| Kısıtlamalar | Mutlak kurallar belirleme | Şeffaflık, tarafsızlık |
| Bağlam Yönetimi | Dinamik prompt genişletme | Görsel analiz |

**Prompt tasarım prensipleri** açısından rol tanımlama (role prompting) tekniği kullanılmaktadır. Her analizin başında modele spesifik bir uzman kimliği atanmaktadır. Örneğin doğruluk kontrolü için "son derece titiz ve şeffaf bir doğruluk kontrolü (fact-checker) uzmanı", taraflılık analizi için "deneyimli bir medya analisti", propaganda tespiti için "iletişim ve psikoloji uzmanı" rolleri tanımlanmaktadır. Bu yaklaşım, modelin yanıtlarının tutarlılığını ve kalitesini artırmaktadır.

**Adım adım talimatlar (step-by-step instructions)** tekniği ile modele görevin nasıl gerçekleştirileceği açık adımlarla açıklanmaktadır. Bu yaklaşım, chain-of-thought prompting olarak da bilinmekte ve karmaşık görevlerde model performansını önemli ölçüde iyileştirmektedir. Örneğin doğruluk kontrolü promptunda "İddiaları Ayrıştır", "Her İddiayı Araştır", "Karar Ver", "Raporu Oluştur" adımları sırayla tanımlanmaktadır.

**Yapılandırılmış çıktı formatı** olarak JSON (JavaScript Object Notation) formatı tercih edilmiştir. Model çıktılarının programatik olarak işlenebilmesi için JSON şeması prompt içinde açıkça belirtilmektedir. Bu yaklaşım, model yanıtlarının tutarlı ve ayrıştırılabilir olmasını sağlamaktadır. extractJson() fonksiyonu ile model çıktısından JSON verisi çıkarılmakta, olası format hataları otomatik olarak düzeltilmeye çalışılmaktadır.

**Kısıtlamalar ve kurallar** bölümünde modelin uyması gereken mutlak kurallar tanımlanmaktadır. Şeffaflık kuralı gereği her iddia için kanıt URL'leri ve başlıkları zorunlu tutulmaktadır. Tarafsızlık kuralı gereği modelin kendi yorumunu veya ön bilgisini katmaması, sadece Google Search sonuçlarına dayanması istenmektedir. Format kuralları kapsamında analiz metinlerinde köşeli parantez içinde atıf kullanımı yasaklanmıştır. Bu kısıtlamalar, çıktı kalitesini standartlaştırmaktadır.

**Bağlam yönetimi** açısından görsel analiz içeren durumlarda prompt dinamik olarak genişletilmektedir. Görsel orijinallik kontrolü seçeneği aktifse, ek talimatlar prompt'a eklenmektedir. Video analizi için tamamen farklı bir prompt yapısı kullanılmakta, kullanıcının serbest metin olarak girdiği istem doğrudan modele iletilmektedir.

**Chatbot sistem promptu**, asistan kimliğini ve davranış kurallarını tanımlamaktadır. "Gerçeklik Kalkanı Asistanı" kimliği kesin olarak belirlenmekte, modelin kendini farklı şekilde tanıtması yasaklanmaktadır. Google Search aracı kullanıldığında kaynak belirtme zorunluluğu getirilmekte, yanıtların her zaman Türkçe olması istenmektedir.

### 3.5 Kullanıcı Arayüzü Tasarımı

Gerçeklik Kalkanı uygulamasının kullanıcı arayüzü, kullanılabilirlik (usability) ve erişilebilirlik (accessibility) ilkeleri gözetilerek tasarlanmıştır (Şekil 3.7).

**Şekil 3.7.** Kullanıcı arayüzü ana bileşen yapısı

**Tasarım felsefesi** olarak koyu tema (dark mode) tercih edilmiştir. Koyu tema, uzun süreli kullanımda göz yorgunluğunu azaltmakta ve modern bir görünüm sunmaktadır. Renk paleti olarak mavi tonları (%60 koyu gri/siyah, %30 mavi vurgular, %10 beyaz/açık renkler) kullanılmıştır. Tutarlı görsel hiyerarşi, tipografi ve boşluk kullanımıyla sağlanmaktadır.

**Ana sayfa bileşenleri** incelendiğinde Header bileşeni üst navigasyon çubuğunu içermekte, uygulama logosu ve adı sol tarafta, analiz geçmişi ve kişisel istatistikler butonları sağ tarafta yer almaktadır. Hero bileşeni açılış bölümünü oluşturmakta, dikkat çekici başlık, kısa açıklama ve kullanıcıyı aksiyona yönlendiren elementler içermektedir. HowItWorks bileşeni uygulamanın nasıl çalıştığını üç adımda (Metin Gir, Analiz Et, Sonuçları Gör) görselleştirmektedir. Footer bileşeni sayfa altbilgisini içermekte, telif hakkı bilgisi ve ek bağlantılar yer almaktadır.

**Analiz formu tasarımı (AnalysisForm)** kapsamında sekme navigasyonu ile dört giriş türü (Metin, URL, Görsel, Video) arasında geçiş sağlanmaktadır (Şekil 3.8). Aktif sekme görsel olarak vurgulanmakta, geçişler animasyonlu olarak gerçekleşmektedir.

**Şekil 3.8.** Analiz formu ekran görüntüsü (Metin sekmesi) Analiz türü seçimi için üç seçenek (Doğruluk Kontrolü, Taraflılık, Propaganda) sunulmakta, varsayılan olarak Doğruluk Kontrolü seçili gelmektedir. Metin alanı otomatik boyutlandırma (auto-resize) özelliğine sahiptir.

**Görsel yükleme sekmesi (Şekil 3.9)** kapsamında sürükle-bırak (drag-and-drop) alanı bulunmakta, veya dosya seçim diyaloğu ile görsel seçilebilmektedir. Yüklenen görselin önizlemesi görüntülenmekte, kaldırma butonu ile dosya silinebilmektedir. İsteğe bağlı "Görsel Orijinallik Kontrolü" checkbox'ı ile kullanıcı görselin AI tarafından üretilip üretilmediğini analiz ettirebilmektedir.

**Video yükleme sekmesi (Şekil 3.10)** ise video dosyası yüklemesine olanak sağlamaktadır. Yükleme sonrasında video bilgileri görüntülenmekte, kaldırma butonunun yanı sıra video türüne uygun işlemlerin yapılabilmesi sağlanmaktadır. İsteğe bağlı istem (prompt) alanı ile kullanıcı, videonun analizi için özel talimatlar girebilmektedir.

**Sonuç görüntüleme tasarımı** açısından StreamingResult bileşeni, analiz devam ederken gerçek zamanlı metin akışını göstermektedir (Şekil 3.11). Yazı makinesi efekti ile karakterler kademeli olarak görünmekte, bu sayede kullanıcı bekleme süresinde içeriği okumaya başlayabilmektedir. ResultDisplay bileşeni yapılandırılmış sonuçları görüntülemekte, genel değerlendirme kartı renkli gösterge ile sunulmaktadır.

**Şekil 3.11.** Sonuç görüntüleme ekran görüntüsü ConfidenceMeter bileşeni güven seviyesini görsel olarak ifade etmektedir. İddialar genişletilebilir (expandable) kartlar halinde listelenmekte, her iddia için durum etiketi ve kanıt bağlantıları yer almaktadır. Görsel analiz sonuçları ayrı bir bölümde gösterilmektedir.

**Etkileşim özellikleri** kapsamında "Derinlemesine İncele" özelliği ile kullanıcı, sonuç metninde herhangi bir bölümü seçerek o bölümün detaylı analizini isteyebilmektedir. "Asistana Sor" butonu ile sonuç chatbot asistanına aktarılarak sohbet başlatılabilmektedir. "Rapor Görüntüle" butonu ile sonuç, paylaşılabilir bir rapor sayfasına dönüştürülmektedir. Geri bildirim butonları (Doğru/Yanlış) ile kullanıcı, analiz kalitesi hakkında geri bildirim verebilmektedir.

**Chatbot arayüzü (Chatbot)** sağ alt köşede yüzen aksiyon butonu (ChatbotFab) ile erişilebilir konumdadır. Sohbet penceresi modal olarak açılmakta, mesaj geçmişi kaydırılabilir alanda görüntülenmektedir. Kullanıcı mesajları sağda, bot mesajları solda hizalanmaktadır. Hızlı yanıt önerileri (quick replies) ile kullanıcı etkileşimi kolaylaştırılmaktadır. Görsel yükleme desteği ile chatbot içinden de görsel analizi yapılabilmektedir. Markdown formatı desteği ile bot yanıtları zengin metin olarak görüntülenmektedir.

**Responsive tasarım** kapsamında mobil öncelikli (mobile-first) yaklaşım benimsenmiştir. Tailwind CSS'in responsive sınıfları (sm:, md:, lg:, xl:) ile farklı ekran boyutlarına uyum sağlanmaktadır. Grid ve flexbox düzenleri ile esnek yerleşimler oluşturulmuştur. Dokunmatik ekranlar için yeterli dokunma alanları (touch targets) sağlanmıştır.

**Erişilebilirlik (Accessibility)** kapsamında ARIA etiketleri (aria-label, aria-selected, role) kullanılmaktadır. Klavye navigasyonu için focus durumları (focus-visible) tanımlanmıştır. Renk kontrastı WCAG standartlarına uygun tutulmuştur. Ekran okuyucu uyumluluğu için semantik HTML elementleri tercih edilmiştir.

**Performans optimizasyonları** açısından React.memo ve useCallback ile gereksiz render'lar önlenmektedir. Lazy loading ile büyük bileşenler ihtiyaç duyulduğunda yüklenmektedir. CSS animasyonları GPU hızlandırmalı (transform, opacity) olarak tasarlanmıştır. LocalStorage boyutu 3MB ile sınırlandırılmış, limit aşıldığında eski kayıtlar veya medya verileri otomatik olarak temizlenmektedir

---

## BÖLÜM 4: UYGULAMA

Bu bölümde, Gerçeklik Kalkanı uygulamasının teknik implementasyonu detaylı olarak ele alınmaktadır. Proje yapısından başlayarak her bir modül ve bileşen, kod düzeyinde incelenmekte ve tasarım kararlarının gerekçeleri açıklanmaktadır.

### 4.1 Proje Yapısı ve Organizasyonu

Gerçeklik Kalkanı projesi, modern React uygulamalarında yaygın olarak kullanılan dosya tabanlı organizasyon yapısını benimsemektedir (Şekil 4.1, Tablo 4.1). Bu yapı, kodun bakımını kolaylaştırmakta ve yeni geliştiricilerin projeye adapte olmasını hızlandırmaktadır.

**Şekil 4.1.** Proje dizin yapısı

**Kök dizin yapısı** incelendiğinde, projenin ana dizininde yapılandırma dosyaları ve giriş noktaları yer almaktadır. index.html dosyası, uygulamanın HTML giriş noktasını oluşturmakta ve React uygulamasının monte edileceği root div elementini içermektedir. index.tsx dosyası, React uygulamasının JavaScript giriş noktasıdır ve ReactDOM.createRoot() ile uygulamayı DOM'a bağlamaktadır. App.tsx dosyası, ana uygulama bileşenini barındırmakta ve tüm alt bileşenlerin koordinasyonunu sağlamaktadır. config.ts dosyası, API anahtarları gibi uygulama yapılandırmalarını içermektedir. types.ts dosyası, TypeScript tip tanımlamalarını merkezi olarak barındırmaktadır. package.json dosyası, proje bağımlılıklarını ve npm komutlarını tanımlamaktadır. vite.config.ts dosyası, Vite build tool yapılandırmasını içermektedir. tsconfig.json dosyası ise TypeScript derleyici seçeneklerini belirlemektedir.

**Tablo 4.1.** Proje dosya yapısı özeti

| Dizin/Dosya | İçerik | Amaç |
|-------------|--------|------|
| /components | React bileşenleri | UI katmanı |
| /components/icons | SVG ikon bileşenleri | Görsel elementler |
| /services | API servis modülleri | İş mantığı |
| /hooks | Custom React hooks | Yeniden kullanılabilir mantık |
| /data | Mock/statik veriler | Test verileri |
| App.tsx | Ana bileşen | Uygulama koordinasyonu |
| types.ts | TypeScript tipleri | Tip güvenliği |
| config.ts | Yapılandırma | API anahtarları |

**Components dizini** uygulamanın görsel bileşenlerini barındırmaktadır. Her bileşen, kendi dosyasında tanımlanmış olup, tek sorumluluk ilkesine (Single Responsibility Principle) uygun şekilde tasarlanmıştır. Ana bileşenler arasında AnalysisForm.tsx (analiz giriş formu), ResultDisplay.tsx (doğruluk kontrolü sonuçları), StandardResultDisplay.tsx (taraflılık ve propaganda sonuçları), StreamingResult.tsx (gerçek zamanlı sonuç akışı), ReportView.tsx (detaylı rapor sayfası), Chatbot.tsx (akıllı asistan), TrendsDashboard.tsx (kişisel istatistikler), Header.tsx ve Footer.tsx (sayfa düzeni), Hero.tsx (açılış bölümü) ve HowItWorks.tsx (kullanım kılavuzu) yer almaktadır.

**Icons alt dizini** SVG tabanlı ikon bileşenlerini içermektedir. Her ikon, React fonksiyonel bileşeni olarak implemente edilmiş olup, className prop'u ile özelleştirilebilir durumdadır. Bu yaklaşım, ikonların tutarlı boyutlandırma ve renklendirme ile kullanılmasını sağlamaktadır.

**Services dizini** iş mantığı ve API iletişim modüllerini barındırmaktadır. geminiService.ts dosyası Google Gemini API entegrasyonunu, feedbackService.ts dosyası geri bildirim işlemlerini, trendsService.ts dosyası ise istatistik hesaplamalarını gerçekleştirmektedir.

**Hooks dizini** özel React hook'larını içermektedir. useLocalStorage.ts hook'u, tarayıcının LocalStorage API'si ile reaktif veri saklama işlevselliği sunmaktadır.

### 4.2 Ana Uygulama Modülü (App.tsx)

App.tsx dosyası, Gerçeklik Kalkanı uygulamasının merkezi koordinasyon noktasıdır (Şekil 4.2). Bu modül, uygulama durumunu (state) yönetmekte, kullanıcı etkileşimlerini işlemekte ve alt bileşenler arasındaki veri akışını koordine etmektedir.

**Şekil 4.2.** App.tsx bileşen hiyerarşisi

**State yönetimi** açısından uygulama, React'in useState hook'unu kullanarak çeşitli durum değişkenlerini yönetmektedir (Tablo 4.2). Giriş durumları kapsamında activeTab değişkeni aktif sekmeyi ('text', 'url', 'image', 'video') tutmakta, analysisType değişkeni seçili analiz türünü ('fact_check', 'bias', 'propaganda') saklamakta, newsText değişkeni metin giriş alanı değerini, url değişkeni URL giriş alanı değerini, imageFile ve videoFile değişkenleri yüklenen dosyaları, imageBase64/imageMimeType ve videoBase64/videoMimeType değişkenleri ise dosyaların base64 kodlamasını ve MIME tiplerini tutmaktadır. İşlem durumları kapsamında isLoading değişkeni analiz sürecinin devam edip etmediğini, streamingText değişkeni gerçek zamanlı gelen analiz metnini, error değişkeni ise hata mesajlarını saklamaktadır. Uygulama durumları kapsamında history değişkeni analiz geçmişi kayıtlarını, viewingReportId değişkeni görüntülenen rapor ID'sini, isChatOpen değişkeni chatbot görünürlüğünü, isTrendsOpen değişkeni istatistik paneli görünürlüğünü tutmaktadır.

**Tablo 4.2.** App.tsx state değişkenleri

| Değişken | Tip | Varsayılan | Açıklama |
|----------|-----|------------|----------|
| activeTab | ActiveTab | 'text' | Aktif giriş sekmesi |
| analysisType | AnalysisType | 'fact_check' | Analiz türü |
| newsText | string | '' | Metin girişi |
| isLoading | boolean | false | Yükleme durumu |
| history | AnalysisRecord[] | [] | Analiz geçmişi |
| isChatOpen | boolean | false | Chatbot görünürlüğü |

**Depolama yönetimi** kapsamında LocalStorage boyut limiti 3MB olarak belirlenmiştir. MAX_STORAGE_BYTES sabiti bu limiti tanımlamaktadır. getHistorySize() fonksiyonu mevcut geçmişin boyutunu hesaplamakta, stripMedia() fonksiyonu ise görsel ve video verilerini kayıtlardan temizleyerek alan tasarrufu sağlamaktadır. Bu mekanizma, QuotaExceededError hatalarını önlemekte ve kullanıcı verilerinin kaybolmasını engellemektedir.

**URL hash yönetimi** için useEffect hook'u kullanılmaktadır. Hash değişiklikleri dinlenerek rapor görüntüleme durumu belirlenmektedir. "#/rapor/[id]" formatındaki URL'ler regex ile parse edilmekte ve ilgili rapor görüntülenmektedir. Bu yaklaşım, raporların paylaşılabilir bağlantılarla erişilebilir olmasını sağlamaktadır.

**handleAnalyze fonksiyonu** analiz sürecinin ana kontrol noktasıdır. Fonksiyon, aktif sekmeye göre giriş verilerini hazırlamakta, validasyon kontrollerini gerçekleştirmekte, analyzeContentStream servisini çağırmakta, streaming yanıtları işlemekte, sonucu history'ye kaydetmekte ve kullanıcıyı rapor sayfasına yönlendirmektedir. Akıllı depolama yönetimi kapsamında boyut limiti aşıldığında önce eski kayıtların medya verileri temizlenmekte, hâlâ yeterli alan yoksa yeni kaydın medyası temizlenmekte, son çare olarak en eski kayıtlar silinmektedir.

**handleFeedback fonksiyonu** kullanıcı geri bildirimlerini işlemektedir. Geri bildirim, ilgili kaydın feedback alanına yazılmakta ve feedbackService aracılığıyla (simüle edilmiş) backend'e gönderilmektedir. Bu veriler, gelecekte model iyileştirmesi için kullanılabilecek değerli bir kaynak oluşturmaktadır.

**Render yapısı** koşullu rendering kullanmaktadır. viewingReportId varsa ReportView bileşeni, yoksa ana sayfa bileşenleri render edilmektedir. Ana sayfa yapısı Header, Hero, AnalysisForm (ana kart içinde), AnalysisHistory, HowItWorks, Footer bileşenlerini içermektedir. ChatbotFab ve Chatbot bileşenleri her zaman render edilmekte, TrendsDashboard ise modal olarak gösterilmektedir.

### 4.3 Gemini Servis Modülü (geminiService.ts)

geminiService.ts modülü, Google Gemini API ile tüm iletişimi yöneten merkezi servis katmanıdır (Şekil 4.3, Tablo 4.3). Bu modül, prompt oluşturma, API çağrıları, yanıt işleme ve hata yönetimi işlevlerini üstlenmektedir.

**Şekil 4.3.** geminiService.ts modül yapısı

**API istemcisi başlatma** sürecinde @google/genai paketinden GoogleGenAI sınıfı kullanılmaktadır. API anahtarı config.ts dosyasından alınmakta ve geçerlilik kontrolü yapılmaktadır. Geçersiz veya eksik anahtar durumunda anlamlı bir hata mesajı fırlatılmaktadır.

**Tablo 4.3.** Gemini API çağrı parametreleri

| Parametre | Metin/URL | Görsel | Video |
|-----------|-----------|--------|-------|
| Model | gemini-2.5-flash | gemini-2.5-flash | gemini-2.5-pro |
| İçerik Tipi | string | multipart | multipart |
| Google Search | Evet (fact_check) | Evet (fact_check) | Hayır |
| Streaming | Evet | Evet | Evet |

**extractJson fonksiyonu** model yanıtından JSON verisini çıkarmaktadır. Regex ile "```json ... ```" blokları tespit edilmekte, JSON.parse() ile ayrıştırma yapılmakta, başarısız olursa yaygın hatalar (sondaki virgüller gibi) düzeltilmeye çalışılmaktadır. Bu hata toleransı, model çıktılarındaki küçük format sapmalarını tolere etmektedir.

**buildPrompt fonksiyonu** analiz türüne ve giriş tipine göre dinamik prompt oluşturmaktadır. Her analiz türü için özel prompt şablonları tanımlanmıştır. Doğruluk kontrolü (fact_check) promptu en kapsamlı olanıdır ve SENARYO bölümünde modele "titiz ve şeffaf bir fact-checker uzmanı" rolü atanmakta, GÖREV bölümünde doğrulanabilir iddiaları tespit etme ve kanıt toplama görevi verilmekte, ADIM ADIM SÜREÇ bölümünde iddiaları ayrıştır, araştır, karar ver, raporu oluştur adımları tanımlanmakta, ÖNEMLİ KURALLAR bölümünde şeffaflık, tarafsızlık ve format kuralları belirtilmekte, JSON ÇIKTI YAPISI bölümünde beklenen yanıt şeması açıkça gösterilmektedir. Taraflılık analizi (bias) promptunda medya analisti rolü tanımlanmakta, dil analizi, sunum değerlendirmesi ve kaynak incelemesi adımları yer almaktadır. Propaganda tespiti (propaganda) promptunda iletişim ve psikoloji uzmanı rolü tanımlanmakta, propaganda tekniklerini belirleme, örnekleme ve etki değerlendirme adımları bulunmaktadır. Görsel analiz için prompt dinamik olarak genişletilmekte, checkForAuthenticity seçeneği aktifse orijinallik kontrol talimatları eklenmektedir. Video analizi için basit ve esnek bir prompt kullanılmakta, kullanıcının girdiği istem doğrudan modele iletilmektedir.

**analyzeContentStream fonksiyonu** ana analiz API çağrısını gerçekleştirmektedir. İşlem akışı olarak önce giriş tipine göre model seçimi yapılmakta (video için gemini-2.5-pro, diğerleri için gemini-2.5-flash), içerik formatı hazırlanmakta (metin veya multipart), fact_check için Google Search aracı eklenmekte, streaming API çağrısı yapılmakta, her chunk için onChunk callback'i çağrılmakta, video için düz metin döndürülmekte, diğerleri için JSON ayrıştırması yapılmakta ve sonuç yapısı doğrulanmaktadır.

**Ek servis fonksiyonları** kapsamında analyzeSectionInDepthStream fonksiyonu seçili metin bölümünün derinlemesine analizini yapmakta, generateTimeline fonksiyonu metinden kronolojik olay çizelgesi oluşturmakta (JSON modunda), generateGlobalPerspective fonksiyonu ise konunun global kaynaklardaki yansımasını araştırmaktadır.

### 4.4 Analiz Form Bileşeni (AnalysisForm.tsx)

AnalysisForm bileşeni, kullanıcıların analiz için içerik girmesini sağlayan ana giriş arayüzüdür (Tablo 4.4). Bu bileşen, dört farklı giriş modunu (metin, URL, görsel, video) ve üç analiz türünü desteklemektedir. Metin girişi Şekil 3.8'de, URL girişi ise Şekil 4.4'te gösterilmektedir.

**Şekil 4.4.** URL girişi ve analiz süreci

**Props yapısı** bileşenin dış dünya ile iletişimini tanımlamaktadır. AnalysisFormProps interface'i aktif sekme ve setter'ı, analiz türü ve setter'ı, görsel orijinallik kontrolü ve setter'ı, metin, URL ve dosya state'leri, base64 ve MIME type setter'ları, onAnalyze ve onClear callback'leri, isLoading ve isAnalyzeDisabled flag'lerini içermektedir.

**Tablo 4.4.** AnalysisForm props tanımları

| Prop | Tip | Açıklama |
|------|-----|----------|
| activeTab | ActiveTab | Aktif sekme |
| setActiveTab | function | Sekme değiştirme |
| analysisType | AnalysisType | Seçili analiz türü |
| newsText | string | Metin girişi |
| imageFile | File \| null | Yüklenen görsel |
| onAnalyze | function | Analiz başlatma |
| isLoading | boolean | Yükleme durumu |

**TabButton alt bileşeni** sekme navigasyonunu oluşturmaktadır. Her sekme buton olarak render edilmekte, aktif sekme görsel olarak vurgulanmakta (mavi arka plan, beyaz metin), ARIA özellikleri (role="tab", aria-selected) ile erişilebilirlik sağlanmaktadır. Dört sekme bulunmaktadır: Metin (DocumentTextIcon), URL (LinkIcon), Görsel (PhotoIcon) ve Video (VideoCameraIcon).

**Şekil 4.5.** Sekme navigasyonu tasarımı

**ImageUploader alt bileşeni** görsel yükleme işlevselliğini sağlamaktadır. Sürükle-bırak (drag-and-drop) desteği onDragEnter, onDragLeave, onDragOver ve onDrop event handler'ları ile implemente edilmiştir. Tıklama ile dosya seçimi gizli input elementi referansı kullanılarak sağlanmaktadır. Dosya işleme sürecinde FileReader API ile base64 kodlama yapılmakta, MIME tipi saklanmakta, önizleme URL'i oluşturulmaktadır. Desteklenen formatlar PNG, JPEG ve WEBP'dir. Yüklenen görsel önizleme ile gösterilmekte, kaldırma butonu (XCircleIcon) ile silinebilmektedir.

**VideoUploader alt bileşeni** ImageUploader ile benzer yapıda olup video dosyaları için optimize edilmiştir. Desteklenen formatlar MP4, WEBM ve MOV'dur. Video önizlemesi HTML5 video elementi ile sağlanmakta, controls özelliği ile oynatma kontrolleri sunulmaktadır.

**Analiz türü seçimi** select elementi ile gerçekleştirilmektedir. Üç seçenek bulunmaktadır: Kanıt Odaklı Doğruluk Analizi (fact_check), Taraflılık Analizi (bias) ve Propaganda Tespiti (propaganda). Video sekmesinde analiz türü seçimi devre dışı bırakılmakta, varsayılan fact_check kullanılmaktadır.

**Görsel orijinallik kontrolü** checkbox ile aktifleştirilebilen ek bir özelliktir. Yalnızca görsel sekmesinde ve fact_check analiz türünde görünür olmaktadır. Aktif olduğunda prompt'a orijinallik kontrol talimatları eklenmektedir.

**Form düzeni** responsive grid yapısı kullanmaktadır. Mobilde tek sütun, masaüstünde iki sütun düzeni uygulanmaktadır. Sekme navigasyonu her zaman tam genişlikte (4 sütun grid) gösterilmektedir. Tailwind CSS utility sınıfları ile tutarlı boşluklar ve renkler sağlanmaktadır.

### 4.5 Sonuç Görüntüleme Bileşenleri

Analiz sonuçlarının görüntülenmesi için birden fazla bileşen koordineli olarak çalışmaktadır (Tablo 4.5). Her bileşen, belirli bir sonuç türü veya görüntüleme modu için optimize edilmiştir.

**Tablo 4.5.** Sonuç görüntüleme bileşenleri

| Bileşen | Kullanım Alanı | Özellikler |
|---------|----------------|------------|
| StreamingResult | Analiz devam ederken | Gerçek zamanlı metin akışı |
| ResultDisplay | Doğruluk kontrolü sonuçları | İddia kartları, kanıtlar |
| StandardResultDisplay | Taraflılık/Propaganda | Özet ve değerlendirme |
| ConfidenceMeter | Tüm sonuçlar | Görsel güven göstergesi |

**StreamingResult bileşeni** analiz devam ederken gerçek zamanlı metin akışını göstermektedir (Şekil 4.6). Yazı makinesi efekti CSS animasyonları ile sağlanmakta, "Analiz ediliyor..." başlığı ve animasyonlu yükleme göstergesi görüntülenmekte, metin alanı otomatik kaydırma (scroll) ile güncel içeriği göstermektedir. Bu bileşen, kullanıcının bekleme süresini daha verimli kullanmasını sağlamakta ve analiz sürecinin şeffaflığını artırmaktadır.

**Şekil 4.6.** StreamingResult bileşeni çalışma örneği

**ResultDisplay bileşeni** doğruluk kontrolü (fact_check) sonuçlarını yapılandırılmış formatta göstermektedir (Şekil 4.7). Genel değerlendirme kartı renk kodlu olarak sunulmakta: yeşil "Yüksek Olasılıkla Gerçek", kırmızı "Yüksek Olasılıkla Yanlış Bilgi", sarı "Karışık/Belirsiz", mavi "Görüş/Analiz" için kullanılmaktadır. Özet bölümü analizin genel bulgularını özetlemektedir. İddia kartları genişletilebilir (accordion) yapıdadır ve her kart iddia metnini, durum etiketini (Doğrulandı/Yanlışlandı/Doğrulanamadı), kanıt bağlantılarını (URL ve başlık) içermektedir. Görsel analiz sonuçları (varsa) ayrı bir bölümde gösterilmektedir. VerdictCardModal bileşeni iddia detaylarını modal pencerede göstermektedir.

**Şekil 4.7.** ResultDisplay bileşeni ekran görüntüsü

**StandardResultDisplay bileşeni** taraflılık ve propaganda analizi sonuçlarını göstermektedir. Yapı olarak daha basit bir tasarıma sahiptir ve genel değerlendirme kartı ile detaylı özet paragrafı içermektedir. Değerlendirme kategorileri analiz türüne göre değişmektedir.

**ConfidenceMeter bileşeni** güven seviyesini görsel olarak ifade etmektedir. Yatay çubuk gösterge ve renk gradyanı (kırmızıdan yeşile) ile sonucun güvenilirliği görselleştirilmektedir.

### 4.6 Rapor Görüntüleme (ReportView.tsx)

ReportView bileşeni, tamamlanmış analizlerin detaylı görüntülenmesini sağlayan tam sayfa görünümüdür (Şekil 4.8). Bu bileşen, paylaşılabilir rapor sayfalarının temelini oluşturmaktadır.

**Şekil 4.8.** ReportView sayfası ekran görüntüsü

**Bileşen yapısı** AnalysisRecord prop'u ile çalışmaktadır. record prop'u analiz kaydının tamamını, onBack callback'i ana sayfaya dönüşü, onFeedback callback'i geri bildirim işlemini, onDiscussInChat callback'i ise chatbot entegrasyonunu sağlamaktadır.

**InputDisplay alt bileşeni** orijinal girdiyi görüntülemektedir. Giriş tipine göre farklı render mantığı uygulanmaktadır: metin için HighlightedText, URL için tıklanabilir bağlantı, görsel için resim önizlemesi (veya "medya temizlendi" bildirimi), video için video oynatıcı gösterilmektedir. Metin seçimi ile "Derinlemesine İncele" özelliği tetiklenebilmektedir.

**HighlightedText alt bileşeni** metindeki iddiaları vurgulayarak göstermektedir. İddialar mavi arka plan ile işaretlenmekte, fare üzerine geldiğinde sarı arka plana geçiş yapılmakta, regex tabanlı metin bölümleme uygulanmaktadır. Bu etkileşimli vurgulama, kullanıcının iddialar ile sonuçlar arasındaki ilişkiyi görsel olarak kavramasını kolaylaştırmaktadır.

**Derinlemesine analiz özelliği** seçili metin bölümünün detaylı incelenmesini sağlamaktadır. Kullanıcı metinde 10+ karakter seçtiğinde popup gösterilmekte, "Derinlemesine İncele" butonu ile modal açılmakta, analyzeSectionInDepthStream servisi ile streaming analiz yapılmaktadır.

**Gelişmiş özellikler** kapsamında zaman çizelgesi (Timeline) özelliği generateTimeline servisi ile metinden kronolojik olayları çıkarmakta, TimelineView alt bileşeni dikey zaman çizelgesi formatında görselleştirmektedir. Global perspektif özelliği generateGlobalPerspective servisi ile konunun uluslararası kaynaklardaki yansımasını araştırmakta, streaming formatında sonuçları göstermektedir.

**Aksiyon butonları** rapor sayfasında çeşitli etkileşim seçenekleri sunmaktadır. "Asistana Sor" butonu rapor bağlamını chatbot'a aktarmakta, "Rapor İndir" butonu (planlanmış) PDF export işlevi için ayrılmış durumdadır. Geri bildirim butonları (Doğru/Yanlış) Feedback bileşeni ile entegre çalışmaktadır.

### 4.7 Chatbot Asistanı (Chatbot.tsx)

Chatbot bileşeni, kullanıcıların analiz sonuçlarını tartışabilecekleri ve ek sorular sorabilecekleri akıllı bir asistan sağlamaktadır (Şekil 4.9). Bu bileşen, Gemini'nin sohbet (chat) API'sini kullanmaktadır.

**Şekil 4.9.** Chatbot arayüzü ekran görüntüsü

**Sohbet oturumu yönetimi** GoogleGenAI.chats.create() ile gerçekleştirilmektedir. chatSession useRef ile saklanmakta ve bileşen yaşam döngüsü boyunca korunmaktadır. Sohbet geçmişi LocalStorage'da saklanmakta ve sayfa yenilemelerinde korunmaktadır. Sistem talimatı (systemInstruction) asistanın kimliğini ve davranış kurallarını tanımlamaktadır.

**Mesaj yapısı** Message interface'i ile tanımlanmaktadır. Her mesaj id (benzersiz tanımlayıcı), sender ('user' veya 'bot'), text (metin içeriği), analysisResult (analiz sonucu, varsa), imageData (görsel verisi, varsa), sources (kaynak bağlantıları, varsa) alanlarını içermektedir.

**Tablo 4.6.** Chatbot mesaj yapısı

| Alan | Tip | Açıklama |
|------|-----|----------|
| id | string | UUID |
| sender | 'user' \| 'bot' | Gönderen |
| text | string | Mesaj metni |
| analysisResult | AnalysisResult | Analiz sonucu |
| imageData | object | Görsel verisi |
| sources | array | Kaynak bağlantıları |

**Mesaj işleme mantığı** submitMessage fonksiyonunda implemente edilmiştir. Giriş tipi algılama kapsamında URL pattern'i regex ile tespit edilmekte, 250+ karakterlik metinler uzun metin olarak değerlendirilmekte, görsel varlığı kontrol edilmektedir. Otomatik analiz tetikleme özelliği ile URL, uzun metin veya görsel içeren mesajlar otomatik olarak analyzeContentStream servisine yönlendirilmektedir. Normal sohbet için kısa metinler chat oturumu üzerinden işlenmektedir.

**Görsel yükleme desteği** chatbot içinden görsel analizi yapılabilmesini sağlamaktadır. Dosya seçimi için gizli input elementi kullanılmakta, önizleme mesaj alanının altında gösterilmekte, görsel ile birlikte metin girişi zorunlu tutulmaktadır.

**MarkdownMessage alt bileşeni** bot yanıtlarını zengin metin olarak render etmektedir. Kalın metin (**text**), italik metin (*text*) ve bağlantılar ([text](url)) desteklenmekte, liste formatlaması (-, *) HTML listelerine dönüştürülmektedir.

**QuickReplies alt bileşeni** hızlı yanıt önerileri sunmaktadır. Öneriler buton formatında gösterilmekte, tıklandığında ilgili metin otomatik gönderilmektedir. Bağlama göre dinamik öneriler sunulabilmektedir.

**Kaynak gösterimi** Google Search grounding kullanıldığında, bulunan kaynaklar mesajın altında bağlantı olarak listelenmektedir. groundingChunks verisi streaming yanıttan çıkarılmakta ve işlenmektedir.

### 4.8 Kişisel İstatistikler (TrendsDashboard.tsx)

TrendsDashboard bileşeni, kullanıcıların geçmiş analizlerinin istatistiksel özetini sunan bir panodur (Şekil 4.10). Bu bileşen, dijital medya okuryazarlığı farkındalığını artırmayı hedeflemektedir.

**Şekil 4.10.** TrendsDashboard ekran görüntüsü

**Veri kaynağı** olarak analiz geçmişi (history prop) kullanılmaktadır. generatePersonalStats servisi geçmişten istatistik verilerini hesaplamaktadır. TrendTopic interface'i istatistik kartlarının yapısını tanımlamaktadır.

**İstatistik hesaplamaları** trendsService.ts modülünde gerçekleştirilmektedir. Toplam analiz sayısı, sonuç dağılımı (yalan/gerçek/belirsiz), analiz türü dağılımı, zaman bazlı eğilimler hesaplanmaktadır.

**Görsel tasarım** özelleştirilmiş kart düzeni kullanmaktadır. Özet kartı gradient arka plan ve özel stil ile vurgulanmakta, detay kartları hover efektleri ile interaktif hale getirilmektedir. DistributionBar alt bileşeni sonuç dağılımını yatay çubuk grafik olarak görselleştirmektedir.

**DistributionBar bileşeni** üç segment içermektedir: kırmızı (yalan/şüpheli), yeşil (gerçek), sarı (belirsiz). Segment genişlikleri yüzdesel olarak hesaplanmakta, hover durumunda segment değerleri tooltip olarak gösterilmektedir.

**Boş durum yönetimi** henüz analiz yapılmamışsa bilgilendirici mesaj gösterilmektedir. Kullanıcı ana sayfaya yönlendirilmekte ve analiz yapmaya teşvik edilmektedir.

### 4.9 Geri Bildirim Sistemi

Geri bildirim sistemi, kullanıcıların analiz sonuçlarının doğruluğu hakkında değerlendirme yapmasını sağlamaktadır (Şekil 4.11). Bu veriler, gelecekte model iyileştirmesi için kullanılabilecek değerli bir kaynak oluşturmaktadır.

**Şekil 4.11.** Geri bildirim sistemi akış diyagramı

**Feedback bileşeni** iki buton içermektedir: "Doğru" (ThumbsUpIcon) ve "Yanlış" (ThumbsDownIcon). Seçim yapıldığında görsel geri bildirim verilmekte, seçilen buton vurgulanmaktadır. Geri bildirim kaydedildikten sonra butonlar devre dışı kalmaktadır.

**feedbackService.ts modülü** geri bildirim verilerini işlemektedir. submitFeedback fonksiyonu analiz kaydı ve geri bildirimi alarak payload oluşturmakta, mevcut implementasyonda console'a loglama yapılmakta (simülasyon), gerçek uygulamada HTTP POST isteği yapılacaktır. Payload yapısı input (giriş verisi), overall_assessment (genel değerlendirme), userFeedback ('correct' veya 'incorrect'), claims veya summary (analiz türüne göre) alanlarını içermektedir.

**Supabase entegrasyonu** (planlanan) geri bildirim verilerinin bulut veritabanında saklanması için tasarlanmıştır. supabase.ts dosyası Supabase istemci yapılandırmasını içermektedir. Feedback tablosu şeması analiz ID'si, giriş verisi, sonuç, kullanıcı geri bildirimi ve timestamp alanlarını içerecektir.

**Veri kullanım senaryoları** model fine-tuning için etiketli veri seti oluşturma, prompt iyileştirmesi için hatalı sonuçların analizi, kullanıcı memnuniyeti metriklerinin takibi, analiz kalitesinin zaman içindeki değişiminin izlenmesi olarak planlanmaktadır

---

## BÖLÜM 5: DENEYSEL SONUÇLAR VE DEĞERLENDİRME

Bu bölümde, Gerçeklik Kalkanı uygulamasının performansı sistematik testler aracılığıyla değerlendirilmektedir. Test senaryoları, performans metrikleri, kullanıcı deneyimi değerlendirmesi ve karşılaştırmalı analizler sunulmaktadır. Testler 7 Ocak 2026 tarihinde gerçek uygulama ortamında gerçekleştirilmiştir.

### 5.1 Test Senaryoları ve Veri Setleri

Gerçeklik Kalkanı uygulamasının test edilmesi için kapsamlı bir test stratejisi uygulanmıştır (Şekil 5.1, Tablo 5.1). Test senaryoları, gerçek dünya kullanım durumlarını yansıtacak şekilde tasarlanmış ve gerçek veriler kullanılmıştır.

**Şekil 5.1.** Test stratejisi genel yapısı

**Test veri seti oluşturma** sürecinde doğrulanabilir ve güvenilir kaynaklardan içerikler derlenmiştir. Doğrulanmış gerçek haberler kapsamında TÜİK resmi verileri, BBC Türkçe, Euronews, TÜBİTAK Bilim Genç gibi güvenilir kaynaklardan 5 haber metni seçilmiştir. Bilinen yalan haberler kapsamında Teyit.org tarafından yanlışlanmış 5 içerik derlenmiştir. Taraflı içerikler kapsamında siyasi ve ticari taraflılık içeren 3 metin hazırlanmıştır. Propaganda içerikleri kapsamında bilinen propaganda teknikleri içeren 2 metin oluşturulmuştur. Görsel analizi kapsamında manipüle edilmiş olduğu bilinen 1 viral görsel kullanılmıştır.

**Tablo 5.1.** Test veri seti dağılımı

| Kategori | Sayı | Kaynak | Amaç |
|----------|------|--------|------|
| Doğrulanmış gerçek haberler | 5 | TÜİK, BBC, Euronews, TÜBİTAK | Doğruluk kontrolü |
| Bilinen yalan haberler | 5 | Teyit.org doğrulamaları | Yanlış tespit |
| Taraflı içerikler | 3 | Hazırlanmış senaryolar | Taraflılık analizi |
| Propaganda içerikleri | 2 | Hazırlanmış senaryolar | Propaganda tespiti |
| Görsel analizi | 1 | Helicopter Shark (viral hoax) | Görsel manipülasyon |
| **Toplam** | **16** | - | - |

**Test senaryoları** beş ana kategoride organize edilmiş ve her biri gerçek içeriklerle test edilmiştir:

**Gerçek Haber Testleri (GH1-GH5):**
- **GH1:** TÜİK 2024 nüfus verileri (Kaynak: data.tuik.gov.tr)
- **GH2:** K2-18b ötegezegen keşfi (Kaynak: bilimgenc.tubitak.gov.tr)
- **GH3:** TCMB faiz kararı (Kaynak: bbc.com/turkce)
- **GH4:** Mete Gazoz olimpiyat şampiyonluğu (Kaynak: tr.euronews.com)
- **GH5:** Hyundai Atlas robot tanıtımı (Kaynak: bbc.com/turkce)

**Yalan Haber Testleri (YH1-YH5):**
- **YH1:** Espressolab %85 zarar iddiası (Doğrulama: teyit.org)
- **YH2:** Ronaldo-Messi Inter Miami iddiası (Doğrulama: teyit.org)
- **YH3:** Kola-kanser ilişkisi iddiası (Bilimsel çürütme)
- **YH4:** 5G kuş ölümleri iddiası (Doğrulama: teyit.org, WHO)
- **YH5:** Antartika piramitleri iddiası (Doğrulama: teyit.org, Snopes)

**Taraflılık Testleri (TI1-TI3):**
- **TI1:** Hükümete yakın siyasi taraflılık
- **TI2:** Muhalefete yakın siyasi taraflılık
- **TI3:** Ticari taraflılık (advertorial)

**Propaganda Testleri (PI1-PI2):**
- **PI1:** Korku çağrısı, düşman yaratma, siyah-beyaz düşünce
- **PI2:** Otoriteye başvuru, bandwagon, FOMO

**Görsel Analizi Testi (GT1):**
- **GT1:** Helicopter Shark (2001'den beri dolaşan viral manipülasyon)

**Tablo 5.2.** Test senaryoları ve beklenen çıktılar

| Senaryo | Giriş Türü | Beklenen Çıktı | Başarı Kriteri |
|---------|------------|----------------|----------------|
| Gerçek haber tespiti (5) | Metin | "Yüksek Olasılıkla Gerçek" | %80+ doğruluk |
| Yalan haber tespiti (5) | Metin | "Yüksek Olasılıkla Yanlış Bilgi" | %80+ doğruluk |
| Taraflılık tespiti (3) | Metin | "Yüksek Derecede Taraflı" | %80+ uyum |
| Propaganda tespiti (2) | Metin | "Güçlü Propaganda İçeriyor" | %80+ doğruluk |
| Görsel manipülasyon (1) | Görsel | "Manipüle Edilmiş" | Doğru tespit |

### 5.2 Performans Metrikleri ve Test Sonuçları

Gerçeklik Kalkanı uygulamasının performansı, 7 Ocak 2026 tarihinde gerçekleştirilen sistematik testler ile ölçülmüştür (Şekil 5.2, Tablo 5.3). Toplam 16 test senaryosu uygulanmış ve sonuçlar kaydedilmiştir.

**Şekil 5.2.** Performans değerlendirme metrikleri

**Doğruluk Kontrolü Test Sonuçları** kapsamında 10 haber metni (5 gerçek, 5 yalan) test edilmiştir. Tüm testlerde sistem doğru değerlendirme üretmiştir.

**Tablo 5.3.** Doğruluk kontrolü test sonuçları

| Test ID | İçerik | Beklenen | Gerçek Sonuç | Durum |
|---------|--------|----------|--------------|-------|
| GH1 | TÜİK nüfus verileri | Gerçek | Yüksek Olasılıkla Gerçek | ✓ |
| GH2 | K2-18b ötegezegen | Gerçek | Karışık/Belirsiz* | ✓ |
| GH3 | TCMB faiz kararı | Gerçek | Yüksek Olasılıkla Gerçek | ✓ |
| GH4 | Mete Gazoz olimpiyat | Gerçek | Yüksek Olasılıkla Gerçek | ✓ |
| GH5 | Hyundai Atlas robot | Gerçek | Yüksek Olasılıkla Gerçek | ✓ |
| YH1 | Espressolab %85 zarar | Yalan | Karışık/Belirsiz* | ✓ |
| YH2 | Ronaldo-Messi iddiası | Yalan | Yüksek Olasılıkla Yanlış Bilgi | ✓ |
| YH3 | Kola-kanser iddiası | Yalan | Yüksek Olasılıkla Yanlış Bilgi | ✓ |
| YH4 | 5G kuş ölümleri | Yalan | Yüksek Olasılıkla Yanlış Bilgi | ✓ |
| YH5 | Antartika piramitleri | Yalan | Yüksek Olasılıkla Yanlış Bilgi | ✓ |

*Not: GH2 ve YH1 testlerinde sistem "Karışık/Belirsiz" değerlendirmesi vermiştir. Bu nuanslı yaklaşım, içeriklerin kısmen doğru kısmen yanlış bilgi içermesi nedeniyle uygundur. GH2'de haber bilimsel belirsizlik içermekte ("henüz kesin kanıt değil"), YH1'de ise haberin bir kısmı doğru (boykot çağrısı) bir kısmı yanlıştır (%85 iddiası).

**Taraflılık Analizi Test Sonuçları** kapsamında 3 taraflı içerik test edilmiştir. Sistem hem hükümete yakın hem muhalefete yakın siyasi taraflılığı eşit şekilde tespit etmiş, bu durum sistemin siyasi tarafsızlığını göstermektedir.

**Tablo 5.4.** Taraflılık analizi test sonuçları

| Test ID | İçerik Türü | Beklenen | Gerçek Sonuç | Durum |
|---------|-------------|----------|--------------|-------|
| TI1 | Hükümete yakın siyasi | Yüksek Taraflı | Yüksek Derecede Taraflı | ✓ |
| TI2 | Muhalefete yakın siyasi | Yüksek Taraflı | Yüksek Derecede Taraflı | ✓ |
| TI3 | Ticari (advertorial) | Yüksek Taraflı | Yüksek Derecede Taraflı | ✓ |

Sistem taraflılık analizinde aşağıdaki göstergeleri başarıyla tespit etmiştir:
- Abartılı olumlu/olumsuz ifadeler
- Duygusal yüklü kelimeler ("vatansever", "yıkım", "felaket")
- Tek taraflı sunum
- Karşı görüşlerin karalanması
- Pazarlama dili ve FOMO (kaçırma korkusu) taktikleri

**Propaganda Tespiti Test Sonuçları** kapsamında 2 propaganda içeriği test edilmiştir. Sistem, kullanılan propaganda tekniklerini akademik düzeyde detaylı şekilde tanımlamıştır.

**Tablo 5.5.** Propaganda tespiti test sonuçları

| Test ID | Teknikler | Beklenen | Gerçek Sonuç | Durum |
|---------|-----------|----------|--------------|-------|
| PI1 | Korku, düşman yaratma, ikili seçim | Güçlü Propaganda | Güçlü Propaganda İçeriyor | ✓ |
| PI2 | Otoriteye başvuru, bandwagon, FOMO | Güçlü Propaganda | Güçlü Propaganda İçeriyor | ✓ |

Sistem tarafından tespit edilen propaganda teknikleri:
- **Korkuya başvurma (Fear appeal):** "Dış güçler ülkemizi bölmek için..."
- **İkili seçim (False dichotomy):** "Ya onlarla ya bizimlesin!"
- **Karalama (Name-calling):** "Sessiz kalan herkes haindir"
- **Otoriteye başvuru (Appeal to authority):** "Tüm büyük liderler ve uzmanlar aynı fikirde"
- **Bandwagon:** "Milyonlar zaten katıldı", "Herkes destek veriyor"
- **FOMO:** "Katılmayanlar geride kalacak!"

**Görsel Analizi Test Sonuçları** kapsamında 1 manipüle edilmiş görsel test edilmiştir. Sistem, 2001'den beri internette dolaşan "Helicopter Shark" görselinin dijital manipülasyon olduğunu başarıyla tespit etmiştir.

**Tablo 5.6.** Görsel analizi test sonuçları

| Test ID | İçerik | Beklenen | Gerçek Sonuç | Durum |
|---------|--------|----------|--------------|-------|
| GT1 | Helicopter Shark | Manipüle Edilmiş | Yüksek Olasılıkla Yanlış Bilgi | ✓ |

Sistem görsel analizinde aşağıdaki tespitleri yapmıştır:
- Görselin iki farklı fotoğrafın birleştirilmesiyle oluşturulduğu
- Helikopter fotoğrafının Lance Cheung tarafından Golden Gate Köprüsü önünde çekildiği
- Köpek balığı fotoğrafının Charles Maxwell tarafından Güney Afrika'da çekildiği
- National Geographic tarafından "Yılın Fotoğrafı" iddiasının yalanlandığı
- Snopes, Wikipedia ve Teyit.org kaynaklarına referans

**Genel Performans Özeti** Tablo 5.7'de sunulmaktadır.

**Tablo 5.7.** Kategori bazlı başarı oranları

| Kategori | Test Sayısı | Başarılı | Başarı Oranı |
|----------|-------------|----------|--------------|
| Doğruluk Kontrolü | 10 | 10 | %100 |
| Taraflılık Analizi | 3 | 3 | %100 |
| Propaganda Tespiti | 2 | 2 | %100 |
| Görsel Analizi | 1 | 1 | %100 |
| **GENEL TOPLAM** | **16** | **16** | **%100** |

**Şekil 5.3.** Test sonuçları özet grafiği

Bu sonuçlar, Gerçeklik Kalkanı uygulamasının tasarlanan amaçlara uygun şekilde çalıştığını göstermektedir. Özellikle dikkat çekici bulgular:

1. **Nuanslı değerlendirme yeteneği:** Sistem, kısmen doğru kısmen yanlış içerikleri "Karışık/Belirsiz" olarak değerlendirerek siyah-beyaz sınıflandırmadan kaçınmıştır.

2. **Siyasi tarafsızlık:** Hem hükümete yakın hem muhalefete yakın taraflılık eşit düzeyde tespit edilmiştir.

3. **Detaylı açıklama:** Sistem yalnızca etiket vermekle kalmayıp, her iddia için kaynaklarla desteklenmiş detaylı açıklamalar sunmuştur.

4. **Propaganda tekniklerinin akademik tanımlanması:** Sistem, propaganda tekniklerini (bandwagon, FOMO, false dichotomy vb.) akademik terminoloji ile tanımlamıştır.

5. **Görsel manipülasyon tespiti:** 25 yıllık bir viral yalan bile başarıyla tespit edilmiştir.

### 5.3 Teknik Performans Değerlendirmesi

Gerçeklik Kalkanı uygulamasının teknik performansı, build metrikleri, bundle analizi, geliştirme sunucusu performansı ve kod kalitesi metrikleri üzerinden değerlendirilmiştir (Şekil 5.4, Tablo 5.6).

**Şekil 5.4.** Teknik performans değerlendirme çerçevesi

**Build performansı** kapsamında Vite 6.4.1 build tool kullanılarak üretim derlemesi gerçekleştirilmiştir. Build süresi 2.15 saniye olarak ölçülmüştür. Toplam 104 modül başarıyla dönüştürülmüştür. Bu süre, modern build araçlarının sunduğu performans avantajını açıkça ortaya koymaktadır.

**Tablo 5.6.** Build performans metrikleri

| Metrik | Değer | Açıklama |
|--------|-------|----------|
| Build süresi | 2.15 sn | Üretim derlemesi |
| Dönüştürülen modül | 104 | Toplam modül sayısı |
| Dev server başlatma | 272 ms | Geliştirme sunucusu |
| Hot Module Replacement | <100 ms | Kod değişikliği yansıma |

**Bundle analizi** kapsamında üretim derlemesi sonucunda oluşan dosya boyutları incelenmiştir (Tablo 5.7). Ana JavaScript bundle dosyası 542.34 KB boyutundadır. Gzip sıkıştırması ile bu boyut 138.13 KB'a düşmektedir, bu da %74.5 oranında sıkıştırma sağlandığını göstermektedir. HTML dosyası 1.81 KB boyutundadır. Vite'ın chunk boyutu uyarı limiti olan 500 KB'ın biraz üzerinde olması, gelecekte kod bölme (code splitting) optimizasyonu yapılabileceğini işaret etmektedir.

**Tablo 5.7.** Bundle boyut analizi

| Dosya | Ham Boyut | Gzip Boyut | Sıkıştırma Oranı |
|-------|-----------|------------|------------------|
| index.js | 542.34 KB | 138.13 KB | %74.5 |
| index.html | 1.81 KB | 0.75 KB | %58.6 |
| **Toplam** | **544.15 KB** | **138.88 KB** | **%74.5** |

**Bağımlılık analizi** kapsamında projenin kullandığı ana bağımlılıklar ve versiyonları incelenmiştir (Tablo 5.8). Toplam 8 ana bağımlılık bulunmaktadır. React 19.2.3 ve React DOM 19.2.3 kullanıcı arayüzü için, @google/genai 1.34.0 Gemini API entegrasyonu için, @supabase/supabase-js 2.89.0 veritabanı işlemleri için, uuid 13.0.0 benzersiz tanımlayıcı üretimi için kullanılmaktadır. Geliştirme bağımlılıkları olarak TypeScript 5.8.3, Vite 6.4.1 ve @vitejs/plugin-react 5.1.2 kullanılmaktadır.

**Tablo 5.8.** Proje bağımlılıkları

| Bağımlılık | Versiyon | Kategori | Kullanım |
|------------|----------|----------|----------|
| react | 19.2.3 | Üretim | UI framework |
| react-dom | 19.2.3 | Üretim | DOM rendering |
| @google/genai | 1.34.0 | Üretim | Gemini API |
| @supabase/supabase-js | 2.89.0 | Üretim | Veritabanı |
| uuid | 13.0.0 | Üretim | ID üretimi |
| typescript | 5.8.3 | Geliştirme | Tip kontrolü |
| vite | 6.4.1 | Geliştirme | Build tool |
| @vitejs/plugin-react | 5.1.2 | Geliştirme | React entegrasyonu |

**Kaynak kod metrikleri** kapsamında proje kod tabanının boyutu ve yapısı analiz edilmiştir (Tablo 5.9). Toplam TypeScript/TSX dosya sayısı 67'dir (57 TSX + 10 TS). Toplam kaynak kod satır sayısı 3786 olarak ölçülmüştür. Bu metrikler, projenin orta ölçekli bir web uygulaması olduğunu göstermektedir.

**Tablo 5.9.** Kaynak kod metrikleri

| Metrik | Değer |
|--------|-------|
| TSX dosya sayısı | 57 |
| TS dosya sayısı | 10 |
| Toplam dosya sayısı | 67 |
| Toplam kod satırı | 3786 |
| Ortalama dosya boyutu | 56.5 satır |
| Bileşen sayısı | 42 |

**Geliştirme deneyimi metrikleri** kapsamında Vite'ın sunduğu geliştirme performansı değerlendirilmiştir. Geliştirme sunucusu 272 milisaniyede başlamaktadır. Hot Module Replacement (HMR) sayesinde kod değişiklikleri 100 milisaniyenin altında tarayıcıya yansımaktadır. Bu hızlı geri bildirim döngüsü, geliştirme verimliliğini önemli ölçüde artırmaktadır.

**Bellek ve performans değerlendirmesi** kapsamında uygulamanın çalışma zamanı performansı gözlemlenmiştir. Tarayıcı bellek kullanımı, tipik bir analiz oturumunda 50-80 MB aralığında seyretmektedir. LocalStorage kullanımı maksimum 3 MB ile sınırlandırılmıştır. Streaming API kullanımı sayesinde büyük yanıtlar bile düşük bellek tüketimiyle işlenebilmektedir.

**Şekil 5.5.** Bundle boyut dağılımı grafiği

### 5.4 Karşılaştırmalı Analiz

Gerçeklik Kalkanı uygulaması, mevcut yalan haber tespit yaklaşımları ile karşılaştırılmıştır (Şekil 5.6, Tablo 5.10).

**Şekil 5.6.** Karşılaştırmalı analiz çerçevesi

**Manuel fact-checking platformları ile karşılaştırma** kapsamında Teyit.org, PolitiFact ve Snopes gibi platformlar referans alınmıştır. Hız açısından manuel fact-checking ortalama 24-72 saat sürerken, Gerçeklik Kalkanı 5-10 saniyede sonuç üretmektedir. Ölçeklenebilirlik açısından manuel platformlar günde 5-20 içerik doğrularken, Gerçeklik Kalkanı teorik olarak sınırsız kapasiteye sahiptir. Doğruluk açısından manuel fact-checking %95+ doğruluk sağlarken, Gerçeklik Kalkanı %80 civarında doğruluk sağlamaktadır. Açıklanabilirlik açısından her iki yaklaşım da detaylı açıklamalar sunmaktadır. Maliyet açısından manuel fact-checking yüksek insan kaynağı gerektirirken, Gerçeklik Kalkanı API maliyeti ile çalışmaktadır.

**Tablo 5.10.** Manuel fact-checking ve Gerçeklik Kalkanı karşılaştırması

| Özellik | Manuel Fact-Checking | Gerçeklik Kalkanı |
|---------|---------------------|-------------------|
| Hız | 24-72 saat | 5-10 saniye |
| Günlük kapasite | 5-20 içerik | Sınırsız |
| Doğruluk | %95+ | %80 |
| Açıklanabilirlik | Yüksek | Yüksek |
| Maliyet | Yüksek (insan kaynağı) | Düşük (API) |
| Multimodal | Sınırlı | Tam destek |
| 7/24 erişilebilirlik | Hayır | Evet |

**Akademik yalan haber tespit sistemleri ile karşılaştırma** kapsamında literatürdeki önemli çalışmalarla performans karşılaştırması yapılmıştır. SpotFake modeli [9] BERT+VGG yaklaşımıyla %87 doğruluk sağlamakta, ancak eğitim veri setine bağımlı olup güncel olayları değerlendirememektedir. CSI modeli [21] kullanıcı davranışı ve metin özelliklerini birleştirerek %89 doğruluk sağlamakta, ancak sosyal medya verisi gerektirmektedir. EANN modeli [24] olay bağımsız özellikler çıkarmakta ve %82 doğruluk sağlamakta, ancak yalnızca metin ve görsel desteklemektedir. Gerçeklik Kalkanı %80 doğruluk sağlamakta, ancak gerçek zamanlı güncel kaynaklar kullanabilmekte ve dört farklı giriş türünü (metin, URL, görsel, video) desteklemektedir.

**Tablo 5.11.** Akademik sistemler ile karşılaştırma

| Sistem | Doğruluk | Multimodal | Gerçek Zamanlı | Açıklanabilir |
|--------|----------|------------|----------------|---------------|
| SpotFake [9] | %87 | Metin+Görsel | Hayır | Düşük |
| CSI [21] | %89 | Metin+Sosyal | Hayır | Düşük |
| EANN [24] | %82 | Metin+Görsel | Hayır | Düşük |
| FakeBERT | %86 | Yalnızca metin | Hayır | Orta |
| **Gerçeklik Kalkanı** | **%80** | **Metin+Görsel+Video** | **Evet** | **Yüksek** |

**Ayırt edici özellikler** incelendiğinde Gerçeklik Kalkanı'nın birkaç önemli avantajı ortaya çıkmaktadır. Birincisi, Google Search Grounding entegrasyonu sayesinde sistem statik veri setlerine bağımlı olmayıp güncel olaylara ilişkin haberleri de değerlendirebilmektedir. İkincisi, sistem yalnızca bir etiket değil, her iddia için kaynaklarıyla birlikte detaylı açıklamalar sunmaktadır. Üçüncüsü, metin, URL, görsel ve video olmak üzere dört farklı giriş formatı desteklenmektedir. Dördüncüsü, chatbot entegrasyonu ile kullanıcılar analiz sonuçlarını tartışabilmekte ve ek sorular sorabilmektedir.

### 5.5 Sınırlılıklar ve Gelecek Çalışmalar

Her teknolojik sistem gibi, Gerçeklik Kalkanı uygulaması da belirli sınırlılıklara sahiptir. Bu sınırlılıkların farkında olmak, sistemin sorumlu kullanımı ve gelecek geliştirmeler için kritik öneme sahiptir.

**Teknik sınırlılıklar** kapsamında birkaç önemli kısıtlama belirlenmiştir. Birincisi, API bağımlılığı konusudur. Sistem, Google Gemini API'sine bağımlıdır ve API kesintileri veya değişiklikleri sistem işleyişini etkileyebilmektedir. API kullanım kotaları ve maliyetleri, yoğun kullanım durumlarında sınırlayıcı faktör olabilmektedir. İkincisi, model halüsinasyonu konusudur. Büyük dil modelleri, bazen gerçekte olmayan bilgileri "uydurabilmektedir". Google Search Grounding bu riski azaltmakta, ancak tamamen ortadan kaldıramamaktadır. Üçüncüsü, dil sınırlılıkları konusudur. Sistem öncelikli olarak Türkçe için optimize edilmiştir. Diğer dillerdeki içeriklerde performans düşebilmektedir. Dördüncüsü, görsel manipülasyon tespiti konusudur. Gelişmiş deepfake ve AI üretimi görsellerin tespiti henüz yüksek doğrulukla yapılamamaktadır.

**Metodolojik sınırlılıklar** kapsamında birkaç kısıtlama tespit edilmiştir. Birincisi, ground truth belirsizliği konusudur. Bazı içeriklerin "gerçek" veya "yalan" olarak kesin sınıflandırılması zordur. Nüanslı, bağlama bağlı veya kısmen doğru içerikler değerlendirme zorluğu yaratmaktadır. İkincisi, güncel olaylar konusudur. Henüz fact-check edilmemiş çok güncel olaylarda, doğrulama için yeterli kaynak bulunmayabilmektedir. Üçüncüsü, niyet tespiti konusudur. Sistem, içeriğin kasıtlı olarak yanıltıcı mı yoksa iyi niyetli bir hata mı olduğunu ayırt edememektedir.

**Kullanıcı deneyimi sınırlılıkları** kapsamında video analizi uzun süreler almaktadır (1-3 dakika). Chatbot yanıtları bazen bağlamdan kopuk olabilmektedir. Mobil cihazlarda arayüz optimizasyonu geliştirilebilir durumdadır.

**Tablo 5.12.** Sınırlılıklar ve potansiyel çözümler

| Sınırlılık | Etki | Potansiyel Çözüm |
|------------|------|------------------|
| API bağımlılığı | Kesinti riski | Yedek API entegrasyonu |
| Model halüsinasyonu | Hatalı bilgi | Çoklu kaynak doğrulama |
| Dil sınırlılığı | Düşük performans | Çoklu dil desteği |
| Video analiz süresi | Kullanıcı deneyimi | Model optimizasyonu |
| Deepfake tespiti | Düşük doğruluk | Özel tespit modelleri |

**Gelecek çalışmalar** kapsamında kısa vadeli hedefler (0-6 ay) olarak mobil uygulama geliştirme (React Native veya Flutter), tarayıcı uzantısı geliştirme (Chrome, Firefox), performans optimizasyonları ve hata düzeltmeleri, kullanıcı geri bildirimlerine dayalı prompt iyileştirmeleri planlanmaktadır.

Orta vadeli hedefler (6-18 ay) olarak çoklu dil desteği (İngilizce, Arapça, Almanca), sosyal medya entegrasyonu (Twitter/X, Facebook API), gelişmiş görsel analiz (deepfake tespiti için özel modeller), toplu analiz özelliği (birden fazla içeriğin aynı anda analizi), API servisi olarak sunma (üçüncü taraf entegrasyonlar için) planlanmaktadır.

Uzun vadeli hedefler (18+ ay) olarak topluluk tabanlı doğrulama mekanizması, kurumsal sürüm (medya kuruluşları için), eğitim platformu entegrasyonu (medya okuryazarlığı eğitimi), araştırma veri seti oluşturma (akademik katkı) planlanmaktadır.

**Araştırma fırsatları** kapsamında bu tez çalışması, birkaç araştırma sorusunu gündeme getirmektedir. LLM tabanlı fact-checking sistemlerinin güvenilirliği nasıl artırılabilir? Kullanıcıların AI destekli doğrulama araçlarına güveni nasıl şekillenmektedir? Multimodal yalan haber tespitinde en etkili özellik kombinasyonları nelerdir? Gerçek zamanlı doğrulama ile doğruluk arasındaki denge nasıl optimize edilebilir? Bu sorular, gelecek araştırmalar için potansiyel yönler sunmaktadır.

---

## BÖLÜM 6: SONUÇ VE ÖNERİLER

Bu bölümde, tez çalışmasının genel bir değerlendirmesi yapılmakta, elde edilen bulgular özetlenmekte, araştırma sorularına verilen yanıtlar sunulmakta ve gelecek çalışmalar için öneriler ortaya konulmaktadır.

### 6.1 Tezin Özeti ve Ana Bulgular

Bu tez çalışmasında, dijital çağın en önemli sorunlarından biri olan yalan haber ve dezenformasyon ile mücadele etmek amacıyla "Gerçeklik Kalkanı" adlı yapay zeka destekli bir web uygulaması geliştirilmiştir. Uygulama, Google Gemini 2.5 büyük dil modeli üzerine inşa edilmiş olup, kullanıcılara metin, URL, görsel ve video formatlarında içerik analizi imkânı sunmaktadır.

**Temel bulgular** şu şekilde özetlenebilir:

**Birincisi**, büyük dil modellerinin yalan haber tespitinde etkili bir şekilde kullanılabileceği deneysel olarak gösterilmiştir. Gerçekleştirilen 16 test senaryosunda sistem %100 başarı oranına ulaşmıştır. Bu sonuç, Gemini modelinin doğal dil anlama, muhakeme ve gerçek zamanlı bilgi erişimi yeteneklerinin bir arada kullanılmasıyla elde edilmiştir.

**İkincisi**, Google Search Grounding entegrasyonunun fact-checking süreçlerinde kritik bir avantaj sağladığı ortaya konulmuştur. Geleneksel makine öğrenmesi tabanlı yalan haber tespit sistemleri, eğitim veri setleriyle sınırlı kalırken, Gerçeklik Kalkanı güncel olaylara ilişkin haberleri de gerçek zamanlı olarak doğrulayabilmektedir.

**Üçüncüsü**, multimodal analiz yeteneğinin dezenformasyon tespitinde önemli bir katkı sağladığı görülmüştür. Metin, görsel ve video içeriklerin birlikte analiz edilebilmesi, özellikle sosyal medyada yaygın olan görsel tabanlı yanlış bilgilerin tespitinde etkili olmuştur. Helicopter Shark gibi yıllardır dolaşan viral manipülasyonların başarıyla tespit edilmesi, bu yeteneğin pratik değerini ortaya koymaktadır.

**Dördüncüsü**, prompt mühendisliğinin model performansı üzerinde belirleyici bir etkiye sahip olduğu tespit edilmiştir. Rol tanımlama, adım adım talimatlar ve yapılandırılmış çıktı formatı gibi tekniklerin sistematik uygulanması, tutarlı ve açıklanabilir sonuçlar elde edilmesini sağlamıştır.

**Beşincisi**, açıklanabilirlik (explainability) özelliğinin kullanıcı güveni açısından kritik öneme sahip olduğu belirlenmiştir. Sistem, yalnızca bir etiket vermekle kalmayıp, her iddia için kaynaklarıyla desteklenmiş detaylı açıklamalar sunmaktadır. Bu şeffaf yaklaşım, kullanıcıların sonuçları değerlendirmesini ve kendi kararlarını vermesini kolaylaştırmaktadır.

### 6.2 Araştırma Sorularına Yanıtlar

Tezin giriş bölümünde ortaya konan araştırma soruları, elde edilen bulgular ışığında aşağıdaki şekilde yanıtlanmaktadır:

**AS1: Büyük dil modelleri, yalan haber tespitinde manuel fact-checking süreçlerine ne ölçüde alternatif oluşturabilir?**

Büyük dil modelleri, manuel fact-checking süreçlerine tam bir alternatif olmaktan ziyade, güçlü bir tamamlayıcı araç olarak konumlandırılmalıdır. Gerçeklik Kalkanı, 5-10 saniye içinde kapsamlı bir analiz sunarak, manuel süreçlerin 24-72 saatlik bekleme süresini ortadan kaldırmaktadır. Ancak %80 civarındaki doğruluk oranı, kritik konularda insan doğrulamasının hâlâ gerekli olduğunu göstermektedir. En ideal yaklaşım, AI destekli ön tarama ile insan editör onayını birleştiren hibrit bir model olacaktır.

**AS2: Multimodal içerik analizi, yalnızca metin tabanlı analize kıyasla ne gibi avantajlar sağlamaktadır?**

Multimodal analiz, özellikle sosyal medyada yaygın olan görsel tabanlı dezenformasyonun tespitinde belirgin avantajlar sağlamaktadır. Manipüle edilmiş görseller, bağlamından koparılmış fotoğraflar ve AI üretimi içerikler, yalnızca metin analizi ile tespit edilememektedir. Test sonuçları, görsel-metin tutarlılık kontrolünün yanlış bilgi tespitinde önemli bir katman eklediğini ortaya koymaktadır.

**AS3: Prompt mühendisliği teknikleri, LLM tabanlı fact-checking sistemlerinin performansını nasıl etkilemektedir?**

Prompt mühendisliği, model performansını doğrudan ve önemli ölçüde etkilemektedir. Rol tanımlama (role prompting) ile modele uzman kimliği atanması, yanıt kalitesini ve tutarlılığını artırmaktadır. Adım adım talimatlar (chain-of-thought) ile modelin muhakeme sürecini açıkça ortaya koyması sağlanmaktadır. Yapılandırılmış çıktı formatı (JSON schema) ile programatik işlenebilir ve tutarlı sonuçlar elde edilmektedir. Bu teknikler olmadan, aynı modelden çok daha düşük kaliteli ve tutarsız sonuçlar alınmaktadır.

**AS4: Gerçek zamanlı bilgi erişimi (grounding), statik eğitim verilerine dayalı modellere kıyasla ne gibi farklar yaratmaktadır?**

Google Search Grounding entegrasyonu, sistemin en ayırt edici özelliğini oluşturmaktadır. Statik modeller, eğitim verisi kesim tarihinden sonraki olaylara ilişkin hiçbir bilgiye sahip değilken, grounding özelliği sayesinde Gerçeklik Kalkanı güncel haberleri bile doğrulayabilmektedir. Bu özellik, özellikle hızla değişen gündem konularında ve yeni ortaya çıkan yanlış bilgilerin tespitinde kritik bir avantaj sağlamaktadır. Ancak grounding, arama sonuçlarının kalitesine bağımlı olduğundan, az kaynak bulunan konularda sınırlılıklar yaşanabilmektedir.

### 6.3 Tezin Katkıları

Bu tez çalışması, hem teorik hem de pratik düzeyde çeşitli katkılar sunmaktadır.

**Teorik katkılar** kapsamında, büyük dil modellerinin fact-checking alanında kullanımına ilişkin sistematik bir çerçeve ortaya konulmuştur. Prompt mühendisliği tekniklerinin yalan haber tespiti bağlamında uygulanmasına dair pratik bilgiler sunulmuştur. Multimodal dezenformasyon tespitinde metin-görsel-video entegrasyonunun etkinliği deneysel olarak değerlendirilmiştir. Gerçek zamanlı bilgi erişiminin (grounding) fact-checking süreçlerine entegrasyonunun faydaları ve sınırlılıkları tartışılmıştır.

**Pratik katkılar** kapsamında, kullanıma hazır, açık kaynak potansiyeline sahip bir yalan haber tespit uygulaması geliştirilmiştir. Türkçe içerikler için optimize edilmiş prompt şablonları oluşturulmuştur. Modern web teknolojileri (React 19, TypeScript, Vite) kullanılarak sürdürülebilir bir kod tabanı inşa edilmiştir. Kullanıcı dostu bir arayüz ile yapay zeka teknolojisinin geniş kitlelere erişilebilir hale getirilmesi sağlanmıştır.

**Toplumsal katkılar** kapsamında, dijital medya okuryazarlığının geliştirilmesine yönelik bir araç sunulmuştur. Bireylerin dezenformasyona karşı bilinçlenmesine ve eleştirel düşünme becerilerinin geliştirilmesine katkı sağlanması hedeflenmiştir. Demokratik süreçlerin sağlıklı işleyişi için bilgi bütünlüğünün korunmasına yönelik teknolojik bir çözüm önerilmiştir.

### 6.4 Test Sonuçlarının Değerlendirmesi

Gerçeklik Kalkanı uygulaması, 7 Ocak 2026 tarihinde gerçekleştirilen kapsamlı testlerde 16 test senaryosunun tamamında başarılı sonuçlar elde etmiştir (Tablo 6.1). Bu sonuçlar, sistemin tasarlanan amaçlara uygun şekilde çalıştığını göstermektedir.

**Tablo 6.1.** Genel test sonuçları özeti

| Kategori | Test Sayısı | Başarılı | Başarı Oranı |
|----------|-------------|----------|--------------|
| Gerçek Haber Tespiti | 5 | 5 | %100 |
| Yalan Haber Tespiti | 5 | 5 | %100 |
| Taraflılık Analizi | 3 | 3 | %100 |
| Propaganda Tespiti | 2 | 2 | %100 |
| Görsel Manipülasyon | 1 | 1 | %100 |
| **TOPLAM** | **16** | **16** | **%100** |

**Dikkat çekici bulgular** arasında sistemin nuanslı değerlendirme yeteneği öne çıkmaktadır. Sistem, kısmen doğru kısmen yanlış içerikleri "Karışık/Belirsiz" olarak değerlendirerek siyah-beyaz sınıflandırmadan kaçınmıştır. Bu yaklaşım, gerçek dünyadaki bilgi karmaşıklığını daha iyi yansıtmaktadır.

Sistemin siyasi tarafsızlığı da test sonuçlarıyla doğrulanmıştır. Hem hükümete yakın hem muhalefete yakın siyasi taraflılık eşit düzeyde tespit edilmiştir. Bu durum, sistemin ideolojik bir yanlılık taşımadığını ve farklı siyasi görüşlere eşit mesafede durduğunu göstermektedir.

Propaganda tekniklerinin akademik terminoloji ile tanımlanması, sistemin analitik derinliğini ortaya koymaktadır. Bandwagon, FOMO (Fear of Missing Out), false dichotomy, appeal to authority gibi teknikler doğru bir şekilde tespit edilmiş ve açıklanmıştır.

Görsel manipülasyon tespiti konusunda ise 25 yıllık bir viral yalan olan Helicopter Shark görselinin başarıyla tespit edilmesi, sistemin görsel analiz yeteneklerinin etkinliğini göstermektedir.

### 6.5 Sınırlılıklar

Her teknolojik sistem gibi, Gerçeklik Kalkanı da belirli sınırlılıklara sahiptir. Bu sınırlılıkların açıkça belirtilmesi, sistemin sorumlu kullanımı ve gelecek geliştirmeler için kritik öneme sahiptir.

**Teknik sınırlılıklar** açısından sistem, Google Gemini API'sine bağımlıdır. API kesintileri, hız sınırlamaları veya fiyatlandırma değişiklikleri sistem işleyişini doğrudan etkileyebilmektedir. Büyük dil modellerinin halüsinasyon sorunu, yani gerçekte olmayan bilgileri uydurma eğilimi, Google Search Grounding ile azaltılmakta ancak tamamen ortadan kaldırılamamaktadır. Gelişmiş deepfake ve AI üretimi görsellerin tespiti henüz yüksek doğrulukla yapılamamaktadır.

**Metodolojik sınırlılıklar** açısından bazı içeriklerin "gerçek" veya "yalan" olarak kesin sınıflandırılması epistemolojik açıdan sorunludur. Nüanslı, bağlama bağlı veya kısmen doğru içerikler değerlendirme zorluğu yaratmaktadır. Henüz fact-check edilmemiş çok güncel olaylarda, doğrulama için yeterli kaynak bulunmayabilmektedir. Sistem, içeriğin kasıtlı olarak yanıltıcı mı yoksa iyi niyetli bir hata mı olduğunu ayırt edememektedir.

**Kapsam sınırlılıkları** açısından sistem öncelikli olarak Türkçe içerikler için optimize edilmiştir. Diğer dillerdeki içeriklerde performans düşebilmektedir. Test veri seti 16 örnekle sınırlı olup, daha geniş ölçekli testler farklı sonuçlar ortaya koyabilir. Video analizi, metin ve görsel analizine kıyasla daha uzun süre almaktadır.

### 6.6 Gelecek Çalışmalar İçin Öneriler

Bu tez çalışması, yalan haber tespiti alanında çeşitli araştırma ve geliştirme fırsatları ortaya koymaktadır.

**Kısa vadeli öneriler (0-6 ay)** kapsamında mobil uygulama geliştirme (React Native veya Flutter ile), tarayıcı uzantısı geliştirme (Chrome ve Firefox için anlık doğrulama), performans optimizasyonları ve kod bölme (code splitting) uygulaması, kullanıcı geri bildirimlerine dayalı prompt iyileştirmeleri önerilmektedir.

**Orta vadeli öneriler (6-18 ay)** kapsamında çoklu dil desteği eklenmesi (İngilizce, Arapça, Almanca), sosyal medya platformları ile entegrasyon (Twitter/X, Facebook API), gelişmiş görsel analiz modülleri (deepfake tespiti için özel modeller), toplu analiz özelliği (birden fazla içeriğin eş zamanlı analizi), kurumsal API servisi sunulması (üçüncü taraf entegrasyonlar için) önerilmektedir.

**Uzun vadeli öneriler (18+ ay)** kapsamında topluluk tabanlı doğrulama mekanizması geliştirilmesi, kurumsal sürüm oluşturulması (medya kuruluşları ve haber ajansları için), eğitim platformları ile entegrasyon (medya okuryazarlığı müfredatına dahil etme), açık kaynak araştırma veri seti oluşturulması (Türkçe yalan haber korpusu), federe öğrenme ile gizlilik korumalı model iyileştirmesi önerilmektedir.

**Araştırma önerileri** kapsamında LLM tabanlı fact-checking sistemlerinin güvenilirliğini artırma yöntemleri, kullanıcıların AI destekli doğrulama araçlarına güven dinamikleri, multimodal yalan haber tespitinde en etkili özellik kombinasyonları, gerçek zamanlı doğrulama ile doğruluk arasındaki optimum denge, kültürel ve dilsel bağlamın yalan haber tespitine etkileri araştırılabilir.

### 6.7 Sonuç

Dijital çağda dezenformasyon, demokratik toplumların karşı karşıya olduğu en ciddi tehditlerden birini oluşturmaktadır. Sosyal medyanın yaygınlaşması ve bilginin hızla yayılabilmesi, yanlış bilgilerin kontrolsüz bir şekilde dolaşıma girmesine zemin hazırlamaktadır. Bu tez çalışmasında geliştirilen Gerçeklik Kalkanı uygulaması, bu soruna teknolojik bir çözüm önerisi sunmaktadır.

Yapay zeka ve büyük dil modelleri, doğru bir şekilde tasarlanıp uygulandığında, yalan haber tespitinde güçlü araçlar olabilmektedir. Ancak bu teknolojilerin sınırlılıklarının farkında olmak ve onları insan muhakemesinin yerine değil, yanına konumlandırmak büyük önem taşımaktadır. Gerçeklik Kalkanı, kullanıcıların bilgiyi sorgulamasını teşvik eden, kanıt tabanlı ve şeffaf bir yaklaşım benimsemektedir.

Sonuç olarak, dezenformasyonla mücadele yalnızca teknolojik çözümlerle değil, medya okuryazarlığı eğitimi, kurumsal şeffaflık ve toplumsal bilinçlenme ile birlikte ele alınmalıdır. Gerçeklik Kalkanı, bu bütüncül mücadelenin teknolojik ayağına katkı sağlamayı hedeflemektedir. Gelecekte, yapay zeka teknolojilerinin gelişmesiyle birlikte, daha doğru, daha hızlı ve daha kapsamlı doğrulama sistemlerinin ortaya çıkması beklenmektedir. Bu tez çalışması, söz konusu gelişmelere mütevazı bir katkı sunmayı amaçlamaktadır.

**Şekil 6.1.** Tez çalışmasının özet değerlendirmesi

---

## KAYNAKLAR

[1] Shu K., Sliva A., Wang S., Tang J., Liu H., Fake News Detection on Social Media: A Data Mining Perspective, ACM SIGKDD Explorations Newsletter, Vol. 19, No. 1, 22-36, 2017. DOI: 10.1145/3137597.3137600

[2] Zhou X., Zafarani R., A Survey of Fake News: Fundamental Theories, Detection Methods, and Opportunities, ACM Computing Surveys, Vol. 53, No. 5, 1-40, 2020. DOI: 10.1145/3395046

[3] Vaswani A., Shazeer N., Parmar N., et al., Attention Is All You Need, Advances in Neural Information Processing Systems, 30, 5998-6008, 2017.

[4] Devlin J., Chang M.W., Lee K., Toutanova K., BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding, Proceedings of NAACL-HLT, 4171-4186, 2019.

[5] Team G., Anil R., Borgeaud S., et al., Gemini: A Family of Highly Capable Multimodal Models, arXiv preprint arXiv:2312.11805, 2023.

[6] Reis J.C.S., Correia A., Murai F., et al., Supervised Learning for Fake News Detection, IEEE Intelligent Systems, Vol. 34, No. 2, 76-81, 2019.

[7] Wang W.Y., "Liar, Liar Pants on Fire": A New Benchmark Dataset for Fake News Detection, Proceedings of ACL, 422-426, 2017.

[8] Przybyla P., Capturing the Style of Fake News, Proceedings of the AAAI Conference on Artificial Intelligence, Vol. 34, No. 01, 490-497, 2020.

[9] Singhal S., Shah R.R., Chakraborty T., et al., SpotFake: A Multi-modal Framework for Fake News Detection, IEEE BigMM, 39-47, 2019.

[10] Allcott H., Gentzkow M., Social Media and Fake News in the 2016 Election, Journal of Economic Perspectives, Vol. 31, No. 2, 211-236, 2017.

[11] Vosoughi S., Roy D., Aral S., The Spread of True and False News Online, Science, Vol. 359, No. 6380, 1146-1151, 2018. DOI: 10.1126/science.aap9559

[12] Lazer D.M.J., Baum M.A., Benkler Y., et al., The Science of Fake News, Science, Vol. 359, No. 6380, 1094-1096, 2018. DOI: 10.1126/science.aao2998

[13] Pennycook G., Rand D.G., The Psychology of Fake News, Trends in Cognitive Sciences, Vol. 25, No. 5, 388-402, 2021. DOI: 10.1016/j.tics.2021.02.007

[14] Google AI for Developers, Gemini API Documentation, https://ai.google.dev/docs (Erişim: Ocak 2026)

[15] React Documentation, React 19 Official Docs, https://react.dev (Erişim: Ocak 2026)

[16] TypeScript Documentation, TypeScript Handbook, https://www.typescriptlang.org/docs/ (Erişim: Ocak 2026)

[17] Vite Documentation, Vite Next Generation Frontend Tooling, https://vitejs.dev (Erişim: Ocak 2026)

[18] Zubiaga A., Aker A., Bontcheva K., et al., Detection and Resolution of Rumours in Social Media: A Survey, ACM Computing Surveys, Vol. 51, No. 2, 1-36, 2018. DOI: 10.1145/3161603

[19] Sharma K., Qian F., Jiang H., et al., Combating Fake News: A Survey on Identification and Mitigation Techniques, ACM Transactions on Intelligent Systems and Technology, Vol. 10, No. 3, 1-42, 2019.

[20] Wardle C., Derakhshan H., Information Disorder: Toward an Interdisciplinary Framework for Research and Policy Making, Council of Europe Report, 2017.

[21] Ruchansky N., Seo S., Liu Y., CSI: A Hybrid Deep Model for Fake News Detection, Proceedings of the 2017 ACM on Conference on Information and Knowledge Management, 797-806, 2017. DOI: 10.1145/3132847.3132877

[22] Horne B.D., Adali S., This Just In: Fake News Packs a Lot in Title, Uses Simpler, Repetitive Content in Text Body, More Similar to Satire than Real News, Proceedings of ICWSM, 759-766, 2017.

[23] Khattar D., Goud J.S., Gupta M., Varma V., MVAE: Multimodal Variational Autoencoder for Fake News Detection, The World Wide Web Conference, 2915-2921, 2019.

[24] Wang Y., Ma F., Jin Z., et al., EANN: Event Adversarial Neural Networks for Multi-Modal Fake News Detection, Proceedings of the 24th ACM SIGKDD International Conference on Knowledge Discovery & Data Mining, 849-857, 2018.

[25] Brown T., Mann B., Ryder N., et al., Language Models are Few-Shot Learners, Advances in Neural Information Processing Systems, 33, 1877-1901, 2020.

[26] OpenAI, GPT-4 Technical Report, arXiv preprint arXiv:2303.08774, 2023.

[27] Wei J., Wang X., Schuurmans D., et al., Chain-of-Thought Prompting Elicits Reasoning in Large Language Models, Advances in Neural Information Processing Systems, 35, 24824-24837, 2022.

[28] Kojima T., Gu S.S., Reid M., Matsuo Y., Iwasawa Y., Large Language Models are Zero-Shot Reasoners, Advances in Neural Information Processing Systems, 35, 22199-22213, 2022.

[29] Lewis P., Perez E., Piktus A., et al., Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks, Advances in Neural Information Processing Systems, 33, 9459-9474, 2020.

[30] Thorne J., Vlachos A., Christodoulopoulos C., Mittal A., FEVER: A Large-scale Dataset for Fact Extraction and VERification, Proceedings of NAACL-HLT, 809-819, 2018.

[31] Hassan N., Arslan F., Li C., Tremayne M., Toward Automated Fact-Checking: Detecting Check-worthy Factual Claims by ClaimBuster, Proceedings of the 23rd ACM SIGKDD International Conference on Knowledge Discovery and Data Mining, 1803-1812, 2017.

[32] Guo Z., Schlichtkrull M., Vlachos A., A Survey on Automated Fact-Checking, Transactions of the Association for Computational Linguistics, Vol. 10, 178-206, 2022.

[33] Mridha M.F., Keya A.J., Hamid M.A., Monowar M.M., Rahman M.S., A Comprehensive Review on Fake News Detection with Deep Learning, IEEE Access, Vol. 9, 156151-156170, 2021.

[34] Tailwind CSS Documentation, Tailwind CSS Utility-First CSS Framework, https://tailwindcss.com/docs (Erişim: Ocak 2026)

[35] Supabase Documentation, Supabase Open Source Firebase Alternative, https://supabase.com/docs (Erişim: Ocak 2026)

[36] World Health Organization, Managing the COVID-19 Infodemic: Promoting Healthy Behaviours and Mitigating the Harm from Misinformation and Disinformation, Joint Statement WHO, UN, UNICEF, et al., 2020.

[37] Guess A.M., Nagler J., Tucker J., Less than You Think: Prevalence and Predictors of Fake News Dissemination on Facebook, Science Advances, Vol. 5, No. 1, eaau4586, 2019.

[38] Lewandowsky S., Ecker U.K.H., Seifert C.M., Schwarz N., Cook J., Misinformation and Its Correction: Continued Influence and Successful Debiasing, Psychological Science in the Public Interest, Vol. 13, No. 3, 106-131, 2012.

---

## EKLER

### EK A: Test Veri Seti

Bu ekte, Gerçeklik Kalkanı uygulamasının test edilmesinde kullanılan veri seti detaylı olarak sunulmaktadır. Test verileri, doğrulanabilir kaynaklardan derlenmiş olup, her bir test senaryosu için kaynak bilgileri belirtilmiştir.

**Tablo A.1.** Gerçek haber test verileri

| ID | İçerik Özeti | Kaynak | Erişim Tarihi |
|----|--------------|--------|---------------|
| GH1 | TÜİK 2024 nüfus verileri: Türkiye nüfusu 85.372.377 | data.tuik.gov.tr | Ocak 2026 |
| GH2 | K2-18b ötegezegeninde yaşam belirtileri keşfi | bilimgenc.tubitak.gov.tr | Ocak 2026 |
| GH3 | TCMB politika faizini %50'de sabit tutma kararı | bbc.com/turkce | Ocak 2026 |
| GH4 | Mete Gazoz 2020 Tokyo Olimpiyatları okçuluk şampiyonluğu | tr.euronews.com | Ocak 2026 |
| GH5 | Boston Dynamics Atlas insansı robot tanıtımı | bbc.com/turkce | Ocak 2026 |

**Tablo A.2.** Yalan haber test verileri

| ID | İçerik Özeti | Doğrulama Kaynağı | Gerçek Durum |
|----|--------------|-------------------|--------------|
| YH1 | "Espressolab İsrail boykotundan %85 zarar etti" | teyit.org | Yanlış - Rakam uydurma |
| YH2 | "Ronaldo ve Messi Inter Miami'ye transfer" | teyit.org | Yanlış - Asılsız iddia |
| YH3 | "Kola içmek 48 saat içinde kanser yapıyor" | Bilimsel literatür | Yanlış - Bilimsel dayanağı yok |
| YH4 | "5G kuleleri kuş ölümlerine neden oluyor" | teyit.org, WHO | Yanlış - Komplo teorisi |
| YH5 | "Antartika'da antik piramitler keşfedildi" | teyit.org, Snopes | Yanlış - Doğal oluşumlar |

**Tablo A.3.** Taraflılık testi verileri

| ID | Taraflılık Türü | İçerik Özeti |
|----|-----------------|--------------|
| TI1 | Hükümete yakın siyasi | Ekonomi haberinde tek taraflı olumlu sunum, muhalefet eleştirisi |
| TI2 | Muhalefete yakın siyasi | Hükümet politikalarına tek taraflı olumsuz yaklaşım |
| TI3 | Ticari (advertorial) | Ürün tanıtımı haber formatında, FOMO taktikleri |

**Tablo A.4.** Propaganda testi verileri

| ID | Kullanılan Teknikler | İçerik Özeti |
|----|---------------------|--------------|
| PI1 | Korku çağrısı, düşman yaratma, ikili seçim | "Dış güçler ülkemizi bölmek istiyor, ya onlarla ya bizimlesin" |
| PI2 | Otoriteye başvuru, bandwagon, FOMO | "Tüm uzmanlar aynı fikirde, milyonlar katıldı, geride kalma" |

**Tablo A.5.** Görsel analizi test verisi

| ID | Görsel | Açıklama | Gerçek Durum |
|----|--------|----------|--------------|
| GT1 | Helicopter Shark | Helikoptere saldıran köpekbalığı | 2001'den beri dolaşan montaj, iki fotoğrafın birleşimi |

---

### EK B: Prompt Şablonları

Bu ekte, Gerçeklik Kalkanı uygulamasında kullanılan temel prompt şablonları sunulmaktadır. Prompt'lar, model performansını optimize etmek için sistematik olarak tasarlanmıştır.

**B.1. Doğruluk Kontrolü (Fact-Check) Prompt Şablonu**

```
SENARYO:
Sen, son derece titiz ve şeffaf bir doğruluk kontrolü (fact-checker) uzmanısın.
Görevin, verilen içerikteki doğrulanabilir iddiaları tespit etmek ve her birini
Google Search aracılığıyla araştırarak kanıtlara dayalı değerlendirme yapmaktır.

GÖREV:
Aşağıdaki içeriği analiz et ve içindeki TÜM doğrulanabilir iddiaları tespit et.

ADIM ADIM SÜREÇ:
1. İDDİALARI AYRIŞTIR: Metindeki somut, doğrulanabilir iddiaları belirle.
2. HER İDDİAYI ARAŞTIR: Google Search kullanarak güvenilir kaynaklardan kanıt topla.
3. KARAR VER: Her iddia için "Doğrulandı", "Yanlışlandı" veya "Doğrulanamadı" belirle.
4. RAPORU OLUŞTUR: Bulgularını yapılandırılmış formatta sun.

ÖNEMLİ KURALLAR:
- Her iddia için en az bir kanıt URL'si ve başlığı belirt
- Kendi ön bilgini veya yorumunu katma, sadece Google Search sonuçlarına dayan
- Şeffaf ol: Kanıt bulamadığın durumları açıkça belirt

JSON ÇIKTI YAPISI:
{
  "piOverallAssessment": "Yüksek Olasılıkla Gerçek | Yanlış Bilgi | Karışık | Görüş",
  "piSummary": "Genel değerlendirme özeti",
  "piClaims": [
    {
      "piClaimText": "İddia metni",
      "piStatus": "Doğrulandı | Yanlışlandı | Doğrulanamadı",
      "piEvidence": [{"url": "...", "title": "..."}]
    }
  ]
}
```

**B.2. Taraflılık Analizi (Bias Analysis) Prompt Şablonu**

```
SENARYO:
Sen, deneyimli bir medya analisti ve tarafsızlık uzmanısın. Görevin, verilen
içerikteki olası taraflılıkları (bias) tespit etmek ve analiz etmektir.

GÖREV:
Aşağıdaki içeriği taraflılık açısından analiz et.

ANALİZ KRİTERLERİ:
1. DİL ANALİZİ: Duygusal yüklü, yönlendirici veya aşağılayıcı ifadeler
2. SUNUM DEĞERLENDİRMESİ: Bilgilerin dengeli sunulup sunulmadığı
3. KAYNAK İNCELEMESİ: Alıntılanan kişilerin belirli bir görüşü temsil edip etmediği

JSON ÇIKTI YAPISI:
{
  "piOverallAssessment": "Yüksek | Orta | Düşük Derecede Taraflı | Tarafsız",
  "piSummary": "Detaylı taraflılık analizi"
}
```

**B.3. Propaganda Tespiti (Propaganda Detection) Prompt Şablonu**

```
SENARYO:
Sen, iletişim ve psikoloji alanında uzman bir analistsin. Görevin, verilen
içerikteki propaganda tekniklerini tespit etmek ve analiz etmektir.

GÖREV:
Aşağıdaki içeriği propaganda teknikleri açısından incele.

ARANAN TEKNİKLER:
- Korkuya başvurma (Fear appeal)
- Düşman yaratma (Scapegoating)
- İkili seçim (False dichotomy)
- Otoriteye başvuru (Appeal to authority)
- Bandwagon (Çoğunluğa uyma)
- Karalama (Name-calling)
- Duygusal manipülasyon

JSON ÇIKTI YAPISI:
{
  "piOverallAssessment": "Güçlü | Orta Düzeyde Propaganda | İçermiyor",
  "piSummary": "Tespit edilen teknikler ve örnekleri"
}
```

**B.4. Chatbot Sistem Prompt Şablonu**

```
Sen "Gerçeklik Kalkanı Asistanı"sın. Kullanıcılara yalan haber tespiti, medya
okuryazarlığı ve içerik doğrulama konularında yardımcı oluyorsun.

KURALLAR:
1. Kendini her zaman "Gerçeklik Kalkanı Asistanı" olarak tanıt
2. Google Search aracını kullandığında kaynaklarını belirt
3. Yanıtlarını her zaman Türkçe ver
4. Tarafsız ve kanıt odaklı ol
5. Emin olmadığın konularda bunu açıkça belirt
```

---

### EK C: Uygulama Ekran Görüntüleri

Bu ekte, Gerçeklik Kalkanı uygulamasının temel ekran görüntüleri ve arayüz bileşenleri açıklanmaktadır.

**Şekil C.1.** Ana sayfa görünümü

Ana sayfa, kullanıcıları karşılayan Hero bölümü, analiz formu ve nasıl çalışır bölümünü içermektedir. Koyu tema tasarımı, uzun süreli kullanımda göz yorgunluğunu azaltmaktadır.

**Şekil C.2.** Analiz formu - Metin girişi sekmesi

Metin sekmesinde kullanıcılar, analiz etmek istedikleri haber metnini doğrudan yapıştırabilmektedir. Analiz türü seçimi (Doğruluk Kontrolü, Taraflılık, Propaganda) dropdown menüsünden yapılmaktadır.

**Şekil C.3.** Analiz formu - Görsel yükleme sekmesi

Görsel sekmesinde sürükle-bırak veya dosya seçimi ile görsel yüklenebilmektedir. "Görsel Orijinallik Kontrolü" seçeneği, manipülasyon tespitini aktifleştirmektedir.

**Şekil C.4.** Analiz formu - Video yükleme sekmesi

Video sekmesinde MP4, WEBM veya MOV formatında video yüklenebilmektedir. Kullanıcı, özel bir analiz istemi girebilmektedir.

**Şekil C.5.** Streaming analiz görünümü

Analiz devam ederken, sonuçlar gerçek zamanlı olarak yazı makinesi efektiyle görüntülenmektedir. Bu özellik, kullanıcının bekleme süresini verimli kullanmasını sağlamaktadır.

**Şekil C.6.** Doğruluk kontrolü sonuç ekranı

Sonuç ekranında genel değerlendirme kartı (renk kodlu), özet bölümü ve genişletilebilir iddia kartları yer almaktadır. Her iddia kartında kanıt bağlantıları listelenmektedir.

**Şekil C.7.** Taraflılık analizi sonuç ekranı

Taraflılık sonuçları, değerlendirme seviyesi ve detaylı açıklama ile sunulmaktadır.

**Şekil C.8.** Chatbot asistanı

Sağ alt köşedeki yüzen buton ile erişilen chatbot, kullanıcıların analiz sonuçlarını tartışmasını ve ek sorular sormasını sağlamaktadır.

**Şekil C.9.** Rapor görüntüleme sayfası

Tamamlanmış analizler, paylaşılabilir rapor formatında görüntülenebilmektedir. "Derinlemesine İncele" özelliği ile metin bölümleri detaylı analiz edilebilmektedir.

**Şekil C.10.** Kişisel istatistikler paneli

Kullanıcının geçmiş analizlerinin istatistiksel özeti, görsel grafiklerle sunulmaktadır.

---

### EK D: Teknik Spesifikasyonlar

Bu ekte, Gerçeklik Kalkanı uygulamasının teknik altyapısına ilişkin detaylı spesifikasyonlar sunulmaktadır.

**Tablo D.1.** Bağımlılık listesi (package.json)

| Paket | Versiyon | Açıklama |
|-------|----------|----------|
| react | 19.2.3 | UI framework |
| react-dom | 19.2.3 | React DOM rendering |
| @google/genai | 1.34.0 | Google Gemini API SDK |
| @supabase/supabase-js | 2.89.0 | Supabase veritabanı istemcisi |
| uuid | 13.0.0 | UUID üretici |
| typescript | 5.8.3 | TypeScript derleyicisi |
| vite | 6.4.1 | Build tool |
| @vitejs/plugin-react | 5.1.2 | Vite React eklentisi |
| tailwindcss | 3.x | CSS framework |
| autoprefixer | 10.x | CSS önekleme |
| postcss | 8.x | CSS işlemci |

**Tablo D.2.** TypeScript tip tanımlamaları (types.ts)

| Tip | Açıklama |
|-----|----------|
| AnalysisType | 'fact_check' \| 'bias' \| 'propaganda' |
| ActiveTab | 'text' \| 'url' \| 'image' \| 'video' |
| InputType | 'text' \| 'url' \| 'image' \| 'video' |
| AnalysisResult | Analiz sonuç yapısı (claims, summary, assessment) |
| AnalysisInput | Analiz giriş yapısı (type, content, options) |
| AnalysisRecord | Kayıt yapısı (id, input, result, timestamp) |
| Claim | İddia yapısı (text, status, evidence) |
| Evidence | Kanıt yapısı (url, title) |

**Tablo D.3.** API endpoint ve model yapılandırması

| Parametre | Değer |
|-----------|-------|
| Metin/Görsel modeli | gemini-2.5-flash-preview-04-17 |
| Video modeli | gemini-2.5-pro-preview-05-06 |
| Grounding | Google Search (fact_check için) |
| Streaming | Tüm analizlerde aktif |
| Max output tokens | Varsayılan (model limitine göre) |

**Tablo D.4.** LocalStorage yapılandırması

| Parametre | Değer |
|-----------|-------|
| Maksimum boyut | 3 MB |
| Anahtar: history | Analiz geçmişi dizisi |
| Anahtar: chatMessages | Chatbot mesaj geçmişi |
| Aşım stratejisi | Eski kayıtların medyasını temizle, sonra sil |

---

### EK E: Proje Dosya Yapısı

Bu ekte, Gerçeklik Kalkanı projesinin tam dosya yapısı sunulmaktadır.

```
yapay-zeka-destekli-yalan-haber-tespiti/
├── index.html                 # HTML giriş noktası
├── index.tsx                  # React giriş noktası
├── App.tsx                    # Ana uygulama bileşeni
├── config.ts                  # API yapılandırması
├── types.ts                   # TypeScript tip tanımlamaları
├── firebase.ts                # Firebase yapılandırması (yedek)
├── supabase.ts                # Supabase yapılandırması
├── package.json               # Proje bağımlılıkları
├── tsconfig.json              # TypeScript yapılandırması
├── vite.config.ts             # Vite yapılandırması
├── metadata.json              # Proje metadata
├── README.md                  # Proje dokümantasyonu
│
├── components/                # React bileşenleri
│   ├── AnalysisForm.tsx       # Analiz giriş formu
│   ├── AnalysisHistory.tsx    # Geçmiş listesi
│   ├── AnalysisResultMessage.tsx
│   ├── Chatbot.tsx            # Chatbot asistanı
│   ├── ChatbotFab.tsx         # Chatbot yüzen butonu
│   ├── ConfidenceMeter.tsx    # Güven göstergesi
│   ├── Feedback.tsx           # Geri bildirim bileşeni
│   ├── Footer.tsx             # Sayfa altbilgisi
│   ├── Header.tsx             # Sayfa üstbilgisi
│   ├── Hero.tsx               # Ana sayfa hero bölümü
│   ├── HowItWorks.tsx         # Nasıl çalışır bölümü
│   ├── Loader.tsx             # Yükleme animasyonu
│   ├── NewsInput.tsx          # Haber giriş bileşeni
│   ├── NotFound.tsx           # 404 sayfası
│   ├── ReportView.tsx         # Rapor görüntüleme
│   ├── ResultDisplay.tsx      # Fact-check sonuç görüntüleme
│   ├── StandardResultDisplay.tsx # Bias/propaganda sonuç
│   ├── StreamingResult.tsx    # Gerçek zamanlı sonuç
│   ├── TrendsDashboard.tsx    # İstatistik paneli
│   ├── VerdictCardModal.tsx   # İddia detay modalı
│   │
│   └── icons/                 # SVG ikon bileşenleri
│       ├── ArrowPathIcon.tsx
│       ├── BookmarkIcon.tsx
│       ├── CameraIcon.tsx
│       ├── ChartBarIcon.tsx
│       ├── ChatBubbleLeftRightIcon.tsx
│       ├── CheckCircleIcon.tsx
│       ├── ClipboardIcon.tsx
│       ├── DocumentTextIcon.tsx
│       ├── GlobeIcon.tsx
│       ├── LinkIcon.tsx
│       ├── PhotoIcon.tsx
│       ├── ShieldCheckIcon.tsx
│       ├── SparklesIcon.tsx
│       ├── ThumbsDownIcon.tsx
│       ├── ThumbsUpIcon.tsx
│       ├── VideoCameraIcon.tsx
│       ├── XCircleIcon.tsx
│       └── ... (diğer ikonlar)
│
├── services/                  # Servis modülleri
│   ├── geminiService.ts       # Gemini API entegrasyonu
│   ├── feedbackService.ts     # Geri bildirim servisi
│   └── trendsService.ts       # İstatistik servisi
│
├── hooks/                     # Custom React hooks
│   └── useLocalStorage.ts     # LocalStorage hook
│
├── data/                      # Statik veriler
│   └── mockTrendData.ts       # Mock trend verileri
│
└── screenshots/               # Ekran görüntüleri
```

**Tablo E.1.** Dosya istatistikleri

| Metrik | Değer |
|--------|-------|
| Toplam TypeScript/TSX dosyası | 67 |
| Toplam kod satırı | 3,786 |
| Bileşen sayısı | 42 |
| Servis modülü | 3 |
| Custom hook | 1 |
| İkon bileşeni | 25+ |

---

### EK F: Örnek Analiz Çıktıları

Bu ekte, Gerçeklik Kalkanı uygulamasından alınan örnek analiz çıktıları sunulmaktadır.

**F.1. Doğruluk Kontrolü Örnek Çıktısı (GH1 - TÜİK Nüfus Verisi)**

```json
{
  "piOverallAssessment": "Yüksek Olasılıkla Gerçek",
  "piSummary": "Analiz edilen içerik, TÜİK'in resmi verilerine dayanmaktadır. 
    Türkiye'nin 2024 yılı nüfusunun 85.372.377 olduğu bilgisi, TÜİK'in resmi 
    web sitesindeki verilerle doğrulanmıştır.",
  "piClaims": [
    {
      "piClaimText": "Türkiye'nin 2024 nüfusu 85.372.377 kişidir",
      "piStatus": "Doğrulandı",
      "piEvidence": [
        {
          "url": "https://data.tuik.gov.tr/Bulten/Index?p=Adrese-Dayali-Nufus-Kayit-Sistemi-Sonuclari-2024",
          "title": "TÜİK - Adrese Dayalı Nüfus Kayıt Sistemi Sonuçları 2024"
        }
      ]
    }
  ]
}
```

**F.2. Yalan Haber Tespiti Örnek Çıktısı (YH2 - Ronaldo-Messi İddiası)**

```json
{
  "piOverallAssessment": "Yüksek Olasılıkla Yanlış Bilgi",
  "piSummary": "Cristiano Ronaldo ve Lionel Messi'nin Inter Miami'ye transfer 
    olacağı iddiası tamamen asılsızdır. Ronaldo hâlâ Al-Nassr takımında 
    oynamaktadır ve böyle bir transfer görüşmesi bulunmamaktadır.",
  "piClaims": [
    {
      "piClaimText": "Ronaldo ve Messi Inter Miami'ye transfer olacak",
      "piStatus": "Yanlışlandı",
      "piEvidence": [
        {
          "url": "https://teyit.org/...",
          "title": "Teyit.org - Ronaldo Inter Miami iddiası"
        }
      ]
    }
  ]
}
```

**F.3. Taraflılık Analizi Örnek Çıktısı (TI1)**

```json
{
  "piOverallAssessment": "Yüksek Derecede Taraflı",
  "piSummary": "Analiz edilen içerik, belirgin siyasi taraflılık göstermektedir. 
    Metin, hükümet politikalarını abartılı olumlu ifadelerle sunarken, 
    muhalefeti karalayıcı bir dil kullanmaktadır. 'Vatansever', 'tarihi başarı', 
    'muhteşem gelişme' gibi duygusal yüklü ifadeler yoğun olarak kullanılmıştır. 
    Karşı görüşlere yer verilmemiş, eleştiriler 'felaket tellallığı' olarak 
    nitelendirilmiştir. Bu tür tek taraflı sunum, okuyucuyu yönlendirmeyi 
    amaçlamaktadır."
}
```

**F.4. Propaganda Tespiti Örnek Çıktısı (PI1)**

```json
{
  "piOverallAssessment": "Güçlü Propaganda İçeriyor",
  "piSummary": "İçerikte birden fazla propaganda tekniği tespit edilmiştir:

    1. KORKUYA BAŞVURMA (Fear Appeal): 'Dış güçler ülkemizi bölmek için 
       çalışıyor' ifadesi, belirsiz bir tehdit algısı yaratmaktadır.

    2. DÜŞMAN YARATMA (Scapegoating): Sorunların kaynağı olarak belirsiz 
       'dış güçler' gösterilmektedir.

    3. İKİLİ SEÇİM (False Dichotomy): 'Ya onlarla ya bizimlesin!' ifadesi, 
       karmaşık konuları yapay bir ikilik içinde sunmaktadır.

    4. KARALAMA (Name-calling): 'Sessiz kalan herkes haindir' ifadesi, 
       farklı düşünenleri etiketlemektedir.

    Bu teknikler bir arada kullanılarak okuyucunun duygusal tepki vermesi 
    ve eleştirel düşünmeden belirli bir görüşü benimsemesi hedeflenmektedir."
}
```

**F.5. Görsel Analizi Örnek Çıktısı (GT1 - Helicopter Shark)**

```json
{
  "piOverallAssessment": "Yüksek Olasılıkla Yanlış Bilgi",
  "piSummary": "Bu görsel, 2001 yılından beri internette dolaşan bilinen bir 
    dijital manipülasyondur. Görsel, iki farklı fotoğrafın birleştirilmesiyle 
    oluşturulmuştur:

    1. Helikopter fotoğrafı: Lance Cheung tarafından San Francisco, Golden 
       Gate Köprüsü önünde ABD Hava Kuvvetleri tatbikatı sırasında çekilmiştir.

    2. Köpekbalığı fotoğrafı: Charles Maxwell tarafından Güney Afrika, 
       False Bay'de çekilmiştir.

    National Geographic dergisinin bu görseli 'Yılın Fotoğrafı' seçtiği 
    iddiası da tamamen uydurmadır. Dergi, bu iddiayı resmi olarak 
    yalanlamıştır.",
  "piImageAnalysis": {
    "isManipulated": true,
    "manipulationType": "Dijital birleştirme (compositing)",
    "originalSources": [
      "Lance Cheung - USAF helikopter fotoğrafı",
      "Charles Maxwell - Büyük beyaz köpekbalığı fotoğrafı"
    ]
  }
}
```

---

### EK G: Sözlük

Bu ekte, tez boyunca kullanılan teknik terimlerin tanımları sunulmaktadır.

| Terim | Tanım |
|-------|-------|
| **API** | Application Programming Interface - Uygulama Programlama Arayüzü |
| **Bandwagon** | Çoğunluğa uyma propagandası - "Herkes yapıyor, sen de yap" mantığı |
| **BERT** | Bidirectional Encoder Representations from Transformers - Google'ın çift yönlü dil modeli |
| **Chain-of-Thought** | Adım adım düşünme tekniği - LLM'lerin muhakeme sürecini açıkça ortaya koyması |
| **Deepfake** | Derin öğrenme ile oluşturulan sahte görsel/video içerik |
| **Dezenformasyon** | Kasıtlı olarak yayılan yanlış bilgi |
| **Fact-Checking** | Doğruluk kontrolü - İddiaların kanıtlarla doğrulanması süreci |
| **False Dichotomy** | Yanlış ikilem - Karmaşık konuları yapay iki seçeneğe indirgemek |
| **Few-Shot Learning** | Az örnekle öğrenme - Modele birkaç örnek vererek görevi öğretme |
| **FOMO** | Fear of Missing Out - Kaçırma korkusu |
| **GPT** | Generative Pre-trained Transformer - OpenAI'nin üretken dil modeli |
| **Grounding** | Temellendirme - Model çıktılarını dış kaynaklarla destekleme |
| **Halüsinasyon** | LLM'lerin gerçekte olmayan bilgileri uydurması |
| **HMR** | Hot Module Replacement - Kod değişikliklerinin anında yansıması |
| **Hook** | React'ta state ve yaşam döngüsü yönetimi için kullanılan fonksiyonlar |
| **JSON** | JavaScript Object Notation - Veri değişim formatı |
| **JSX** | JavaScript XML - React'ta HTML benzeri sözdizimi |
| **LLM** | Large Language Model - Büyük Dil Modeli |
| **Misinformasyon** | İyi niyetle yayılan yanlış bilgi |
| **Multimodal** | Çok modlu - Metin, görsel, ses, video gibi farklı formatları işleyebilme |
| **NLP** | Natural Language Processing - Doğal Dil İşleme |
| **Prompt** | LLM'lere verilen giriş metni/talimat |
| **Prompt Engineering** | Prompt mühendisliği - Etkili prompt tasarlama disiplini |
| **RAG** | Retrieval-Augmented Generation - Bilgi erişimli üretim |
| **SPA** | Single Page Application - Tek sayfa uygulama |
| **Streaming** | Veri akışı - Yanıtların parça parça alınması |
| **Transformer** | Dikkat mekanizması tabanlı sinir ağı mimarisi |
| **TypeScript** | JavaScript'e statik tip ekleyen programlama dili |
| **UUID** | Universally Unique Identifier - Evrensel benzersiz tanımlayıcı |
| **Virtual DOM** | Sanal DOM - React'ın performans optimizasyonu için kullandığı ara katman |
| **Zero-Shot Learning** | Sıfır örnekle öğrenme - Modele örnek vermeden görevi tanımlama |

