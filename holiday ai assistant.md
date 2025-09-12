# Proje Fikri: Yapay Zeka Destekli Kişisel Tatil Asistanı

## 1. Projenin Ana Fikri

Kullanıcıların belirlediği bütçe, tarih aralığı, kişi sayısı ve tatil konsepti (macera, dinlenme, kültür, vb.) gibi temel kriterlere dayanarak, uçtan uca kişiselleştirilmiş bir tatil planı oluşturan yapay zeka destekli bir mobil uygulama geliştirmek.

Uygulama, sadece otel veya uçak listelemek yerine; konaklama, ulaşım, yeme-içme, gezilecek yerler ve yapılacak aktiviteleri içeren bütüncül, optimize edilmiş ve uygulanabilir bir seyahat programı sunmayı hedefler.

## 2. Çözülen Problem

- **Planlama Karmaşıklığı:** Tatil planlamak, onlarca web sitesini (otel, uçak, aktivite, forum) araştırma, karşılaştırma ve bütçeye uygun hale getirme süreçleri nedeniyle zaman alıcı ve streslidir.
    
- **Bütçe Yönetimi:** Belirlenen bütçeye sadık kalarak tatmin edici bir tatil planı oluşturmak zordur.
    
- **Güvenilirlik ve Keşif:** Popüler ve bilinen seçeneklerin dışına çıkmak riskli gelebilir. Gezginler, daha önce başkaları tarafından denenmiş ve beğenilmiş yerel deneyimleri keşfetmekte zorlanabilir.
    

## 3. Hedef Kitle

- Planlama sürecinden bunalan, "az parayla en iyi tatili nasıl yaparım?" diye düşünen gezginler.
    
- Öğrenciler, yeni mezunlar ve bütçesi kısıtlı genç profesyoneller.
    
- Farklı ve otantik deneyimler arayan ancak nereden başlayacağını bilemeyen maceraperestler.
    

## 4. Uygulamanın Temel Özellikleri ve İşleyişi

### A. Plan Oluşturma Aşaması

1. **Veri Girişi:** Kullanıcı bütçesini, tarihlerini, kişi sayısını, ilgi alanlarını (doğa, tarih, eğlence, gastronomi vb.) ve istediği tatil türünü uygulamaya girer.
    
2. **Yapay Zeka Analizi:** AI, bu verileri işleyerek anlık olarak internetteki verileri (uçak/otel fiyatları, etkinlik takvimleri, hava durumu, yerel bloglar) tarar.
    
3. **Plan Sunumu:** Sistem, kullanıcıya en az bir adet A'dan Z'ye düşünülmüş, günlük aktivite dökümleri, konaklama önerileri ve hatta yemek yenebilecek yerleri içeren bir "yol haritası" ve "yapılacaklar listesi" sunar.
    

### B. Geri Bildirim ve Öğrenme Döngüsü (Akıllı Sistem)

Bu, projenin en ayırt edici özelliğidir:

1. **Deneyim ve Puanlama:** Kullanıcılar, oluşturulan planı ne kadar takip ettiklerini uygulama üzerinden işaretler.
    
    - **Tam Uyum & Beğeni:** Bir kullanıcı sunulan plana birebir uyduysa ve deneyimini yüksek puanla oyladıysa, bu planın "güven skoru" artar ve gelecekteki benzer profilli kullanıcılara daha üst sıralarda önerilir.
        
    - **Sapma ve Alternatif Öneri:** Kullanıcı plandan saptıysa (örneğin, önerilen restoran yerine daha ucuz ve lezzetli bir yer bulduysa), bu değişikliği "alternatif öneri" olarak sisteme girebilir.
        
2. **Veriyle Gelişen Zeka:** Yapay zeka, bu geri bildirimleri (hem beğenileri hem de alternatif önerileri) sürekli olarak analiz eder. Böylece:
    
    - Popülerleşen ve yüksek puan alan planlar birer "konsept" haline gelir.
        
    - Kullanıcıların yaptığı mantıklı ve bütçe dostu değişiklikler, gelecekteki plan önerilerine otomatik olarak dahil edilir.
        
    - Sistem, zamanla hangi otellerin fiyat/performans sunduğunu, hangi aktivitelerin gerçekten beğenildiğini "kullanıcı verisiyle" öğrenir.
        

## 5. Gelir Modeli

- **Satış Ortaklığı (Affiliate):** Uygulama üzerinden yapılan otel, uçak bileti ve aktivite rezervasyonlarından komisyon alınması.
    
- **Freemium Model:** Temel planlama ücretsiz sunulurken, daha detaylı planlar, esnek plan değiştirme seçenekleri veya "yerel uzman desteği" gibi özellikler için premium üyelik satılması.
    
- **İşletme Ortaklıkları:** Yerel restoran, kafe veya butik işletmelerle anlaşılarak planlara dahil edilmeleri karşılığında sponsorluk alınması.
    

## 6. Teknik İhtiyaçlar ve Yaklaşım

- **Platform:** Mobil (iOS/Android).
    
- **Veri Kaynakları:** Çeşitli API' entegrasyonları (Booking, Skyscanner, Foursquare, AccuWeather vb.).
    
- **Yapay Zeka:** Kişiselleştirme, optimizasyon ve öneri motoru için makine öğrenmesi modelleri kullanılacak. Özellikle kullanıcı geri bildirimlerinden öğrenecek bir model (pekiştirmeli öğrenme veya benzeri bir yaklaşım) kritik öneme sahip.
    
- **Veritabanı:** Kullanıcı profillerini, oluşturulan planları, geri bildirimleri ve puanlamaları saklamak için ölçeklenebilir bir veritabanı yapısı.