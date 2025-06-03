🏥 Hastane Sıra Yönetim Sistemi
Bu proje, hastaneler ve klinikler için geliştirilmiş basit ama etkili bir web tabanlı sıra yönetim sistemidir. HTML, CSS ve JavaScript ile oluşturulmuş olup, tarayıcının localStorage özelliğini kullanarak sekreter, doktor ve hastane ekranları arasında gerçek zamanlı senkronizasyon sağlar. Sunucuya ihtiyaç duymaz, tamamen tarayıcı üzerinde çalışır.

🚀 Özellikler
🔐 Ana Giriş Sayfası
Sekreter, Doktor ve Hastane Ekranı için tek bir başlangıç noktası.

Her ekran ayrı bir sekmede açılarak bağımsız çalışabilir.

👩‍💼 Sekreter Ekranı
Yeni hasta kaydı yapar: Ad, TC Kimlik Numarası ve Öncelik Seviyesi (Normal, Öncelikli, Acil) bilgilerini alır.

Eklenen hastalar anında doktor ve hastane ekranlarına yansıtılır.

🧑‍⚕️ Doktor Ekranı
Hastaları öncelik sırasına göre (Acil > Öncelikli > Normal) listeler.

Aynı öncelik seviyesindeki hastalar kayıt zamanına göre sıralanır.

"Sonraki Hastayı Çağır" butonu ile sıradaki hastayı otomatik çağırır.

Her hasta için manuel çağırma özelliği bulunur.

Hasta çağrıldığında liste otomatik güncellenir.

🖥️ Hastane Ekranı
Bekleme salonu ekranı olarak tasarlanmıştır.

Sol kısımda çağrılan hastalar, sağ kısımda bekleyen hastalar görünür.

Yeni bir hasta çağrıldığında, ekranın üst kısmında 3 saniye boyunca yanıp sönen bir anons görüntülenir.

En son çağrılan hasta, liste içinde yanıp sönerek vurgulanır.

🔄 Gerçek Zamanlı Senkronizasyon
Tüm ekranlar arasında anlık veri paylaşımı yapılır.

Tarayıcıda localStorage ve storage olayları ile sağlanır.

Sayfaları yenilemeye gerek kalmaz; tüm değişiklikler anında yansır.
