
<h1 align="center">🚌 AMASYA DİJİTAL OTOBÜS SİSTEMİ</h1>     
<br>
</p>
</p>
 <h2 align="center">📌 Proje Açıklaması</h2>
<br>
<br>

</p>
<p align = "center">
 <h3 align="center">Amasya Dijital Otobüs Sistemi, Amasya'daki otobüs hatlarını dijital ortama taşıyan modern bir sistemdir. Kullanıcılar bu sistem sayesinde durak bilgilerine, otobüs saatlerine ve harita üzerinde yönlendirme özelliklerine kolayca erişebilirler. Bu proje, şehir içi ulaşımı daha erişilebilir, verimli ve kullanıcı dostu hale getirmeyi amaçlamaktadır.</h3> 
</p>
<br>
  <a href="https://github.com/ByteMe-CodeFest">
<a>
  <p align = "center">
<a href="https://github.com/ByteMe-CodeFest/bus-map" target="_blank">Otobüs Dokümantasyonunu Keşfedin</a>
  </p>
</a>
<br>
    
<h2 align="center">🚀 Özellikler</h2>


<h3 align="border">🏠 Ana Sayfa</h3>
</p>
📌 Proje hakkında açıklayıcı ve bilgilendirici bir metin içerir.
<br>
<br>
<h3 align="border">🗺️ Harita</h3>

📌 Mapbox tabanlı harita ile otobüs sisteminin görselleştirilmesi.</p>📌 Saatin kaç olduğuna göre tema değişir.</p>📌 "Neredeyim" butonu ile kullanıcı mevcut konumuna dönebilir.</p>📌 Durak işaretleri ve sıradaki iki otobüsün varış süresi görüntülenir.</p>📌 Seçilen durağa Google Maps yönlendirmesi yapılır.
</p>
<br>

<h3 align="border">⏰ Otobüs Saatleri</h3>
</p>
📌 Otobüs hatları numaralandırılmıştır.</p>📌 İlk ve son durak saatleri listelenmiştir.</p>📌 (Geliştirme Aşamasında) Her duraktan geçen otobüs hatlarının gösterilmesi planlanmaktadır.
</p>
<br>

<h3 align="border">💳 Ödeme</h3>
📌 Elmakart için örnek bir ödeme sayfası oluşturulmuştur.</p>📌 Kullanıcı belirli veya özel miktarlarda ödeme yapabilir.</p>📌 Kredi kartı bilgileri için giriş alanları eklenmiştir (gerçek ödeme entegrasyonu bulunmamaktadır).
</p>
<br>
<h3 align="border">ℹ️ Hakkımızda</h3>
📌 Projeye katkıda bulunan kişiler listelenmiştir.</p>📌 Projenin amacı, hedef kitlesi ve iletişim bilgileri sunulmuştur.
</p>
<br>
<h2 align="center">🔥 Gelecek Güncellemeler</h2>

📌 Otobüslerin gerçek zamanlı konumlarının haritada gösterilmesi.</p>📌 Kullanıcılara otobüs yaklaşırken bildirim gönderme özelliği.</p>📌 Kullanıcıların durak hataları veya saat bilgilerini bildirebileceği bir geri bildirim sistemi.</p>📌 Daha gelişmiş rota planlama özelliği eklenmesi.</p>📌 Uygulamayı kullanarak otobuse binen kullanıcılardan alınan verilerle otobüsün anlık konum takibi ve ortalama varış suresinin yeniden hesaplanmasının otomatikleştirilmesi.
<br>
<br>
<h2 align="center">🛠️ Kurulum</h2>

- 📥 Projeyi Klonlayın:

      git clone https://github.com/ByteMe-CodeFest/bus-map.git
      

<br>
</p>

- ▶️ Projeyi Başlatın:
  </p>
Projeyi çalıştırmak için CTRL+1 veya F5 tuşuna basarak web tarayıcınızda açabilirsiniz.

 <br>
 <br>

- 🌍 Mapbox API Anahtarı Tanımlama:
  <br>
  <br>
Projede harita özelliklerini kullanabilmek için Mapbox API anahtarınızı tanımlamanız gerekmektedir. Bunu yapmak için aşağıdaki adımları takip edin: <br>

 config.js dosyasının içerisine api keyinizi ekleyin. (Örnek bir config.js dosyası projede mevcuttur.)
<br>
config.js dosyanızın içeriği şu şekilde olmalıdır:
<br>
<br>

    mapboxgl.accessToken = 'YOUR_API_KEY'; 
  <br>
"YOUR_API_KEY" kısmına kendi API anahtarınızı eklemelisiniz. API anahtarı almak için <a href="https://mapbox.com" target="_blank">buraya</a> tıklayın.



