İklim Dirençli Kentler: Karar Destek Modeli ve 3B Kentsel Morfoloji Uygulaması
Bu proje, İzmir Bayraklı bölgesi için iklim değişikliğine uyum sağlamayı, kentsel ısı adası etkilerini analiz etmeyi ve kentsel dönüşüm süreçlerinde "Karbon Risk Skoru" temelli veri odaklı kararlar almayı hedefleyen bir Web tabanlı CBS (Web-GIS) uygulamasıdır.

🚀 Proje Hakkında
Günümüz kentlerinde artan betonlaşma ve iklim krizi, kentsel ısı adası (UHI) ve karbon emisyonu gibi sorunları derinleştirmektedir. Bu platform, karar vericilerin mahalle ve sokak bazında karbon yutak alanlarını, yüzey sıcaklıklarını ve kentsel morfolojik riskleri interaktif bir harita üzerinde sorgulayabilmesi amacıyla geliştirilmiştir.

🛠 Kullanılan Teknolojiler
Harita Kütüphanesi: Mapbox GL JS (3B görselleştirme ve yüksek performanslı render için).

Veri İşleme: QGIS (Raster-to-Vector, Koordinat Standardizasyonu).

Frontend: HTML5, CSS3 (Glassmorphism arayüz tasarımı), JavaScript.

Backend: Node.js (Gelecek fazlarda veri entegrasyonu için yapılandırıldı).

📊 Proje Fazları ve Analizler
Projemiz 5 ana aşamadan oluşmaktadır:

İndeksleme: Sentinel-2 uydu görüntüleri ile NDVI (Karbon Yutak) ve LST (Yüzey Sıcaklığı) hesaplamaları.

Yapay Zeka: K-Means kümeleme algoritması ile otomatik risk bölgelemesi.

Mekânsal Çakıştırma: TÜİK demografik verileri ve yapısal indekslerin overlay (çakıştırma) analizi.

Web-CBS Arayüzü: Karar destek dashboard'u.

Raporlama: Yerel yönetimler için stratejik müdahale önerileri.

⚙️ Kurulum ve Çalıştırma
Projeyi kendi bilgisayarınızda çalıştırmak için:

Depoyu bilgisayarınıza klonlayın veya zip dosyasını çıkarın.

index.html dosyasının bulunduğu ana dizinde olduğunuzdan emin olun.

VS Code kullanıyorsanız "Live Server" eklentisini kurun.

index.html dosyasına sağ tıklayıp "Open with Live Server" seçeneğini seçin.

Not: Harita katmanlarının yüklenmesi için aktif bir internet bağlantısı ve geçerli bir Mapbox Access Token gereklidir.

👥 Ekip
Oğuz Baran Özalp - Web CBS Entegrasyonu ve Veri Yönetimi

Doğa Durak - Karbon İndeksleme ve Yapay Zeka Modelleme

Ahmet Orbay - 3B Kentsel Modelleme

Seda Sakar - 3B Morfoloji ve İndeksleme

Hasan Efe Şabanfakı - Klimatik ve Hidrolojik Analizler

Sanem Burcu Pekel - Sosyolojik Analiz ve Kurum Görüşmeleri
