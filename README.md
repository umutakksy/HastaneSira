Hastane Sıra Yönetim Sistemi
Bu proje, hastaneler ve klinikler için geliştirilmiş basit ama etkili bir web tabanlı sıra yönetim sistemidir. HTML, CSS ve JavaScript kullanarak tarayıcının yerel depolama alanı (localStorage) üzerinden sekreter, doktor ve hastane genel ekranları arasında gerçek zamanlı senkronizasyon sağlar.

Özellikler
Ana Giriş Sayfası: Kullanıcıların (Sekreter, Doktor, Hastane Ekranı) sisteme kolayca erişebilmesi için tek bir başlangıç noktası. Her ekran ayrı bir tarayıcı sekmesinde açılır.
Sekreter Ekranı:
Yeni hastaları sisteme kaydetme.
Hasta adı, TC Kimlik numarası ve öncelik seviyesi (Normal, Acil, Öncelikli) girişi.
Kaydedilen hastalar anında doktor ve hastane ekranlarına yansır.
Doktor Ekranı:
Sırada bekleyen hastaları öncelik sırasına (Acil > Öncelikli > Normal) göre listeleyen dinamik ekran. Aynı öncelikteki hastalar kayıt zamanına göre sıralanır.
"Sonraki Hastayı Çağır" butonu ile sıradaki ilk hastayı otomatik çağırma.
Her hastanın yanında bulunan "Çağır" butonu ile belirli bir hastayı manuel olarak çağırma yeteneği.
Hasta çağrıldığında liste otomatik olarak güncellenir.
Hastane Ekranı:
Hastanenin bekleme alanlarında gösterilmek üzere tasarlanmış büyük ekran.
Sol tarafta çağrılan hastalar listesi, sağ tarafta ise sırada bekleyen hastalar listesi.
Yeni bir hasta çağrıldığında, ekranın üst kısmında hastanın adının belirip 3 saniye boyunca yanıp sönen bir anons görünür.
Çağrılan hastalar listesindeki en son hasta bilgisi de yanıp sönen efekt ile vurgulanır.
Tüm ekranlar arasında gerçek zamanlı senkronizasyon (localStorage ve storage olayı ile) sayesinde F5 atmaya gerek kalmadan güncellemeler anında yansır.
Kullanılan Teknolojiler
HTML5: Uygulamanın yapısal iskeleti.
CSS3: Uygulamanın görsel tasarımı ve animasyonları.
JavaScript (ES6+): Dinamik etkileşimler, localStorage yönetimi ve ekranlar arası senkronizasyon.
