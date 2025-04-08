# 🔐 Keykeep – Güvenli ve Yerel Şifre Saklama Uygulaması

Keykeep, çevrimdışı çalışan, tamamen yerel veri saklamaya dayalı güvenli bir şifre yöneticisidir. Kullanıcıların çeşitli platformlara ait şifrelerini şifrelenmiş biçimde cihazlarında saklamalarını sağlar. Uygulama, güvenlik ve mahremiyet odaklı olarak geliştirilmiştir.

---

## 📌 Problemin Tanımı

Günümüzde kullanıcıların birçok dijital platformda hesap oluşturması gerekmektedir ve her biri için farklı, güçlü şifreler oluşturmak önemlidir. Ancak bu şifrelerin güvenli bir şekilde saklanması ve hatırlanması büyük bir problemdir. Çevrimdışı, yerel olarak çalışan ve kullanıcı verilerini bulutta değil, cihazda saklayan güvenli bir uygulama eksikliği, özellikle internete sürekli erişimi olmayan ya da bulut güvenliğine şüpheyle yaklaşan kullanıcılar için ciddi bir sorundur.
Keykeep, bu problemi çözmek amacıyla geliştirilmiş, cihaz içinde şifrelenmiş bir yapıda çalışan yerel bir şifre saklama uygulamasıdır.

---

## 🎯 Hedef Kitle

- Güçlü ve çeşitli şifreler kullanan bireyler  
- Bulut tabanlı hizmetlere güven duymayan kullanıcılar  
- İnternet erişimi kısıtlı ortamlarda çalışanlar  
- Dijital güvenliğe ve gizliliğe önem veren teknoloji kullanıcıları

---

## ⚙️ Uygulama Özellikleri

- 🔒 Şifrelenmiş yerel veri saklama  
- 🔐 Ana şifre ile giriş ve uygulama kilitleme  
- 🗂 Şifreleri kategoriye göre düzenleme (E-posta, Banka, Sosyal Medya vb.)  
- ➕ Yeni şifre ekleme, düzenleme ve silme  
- ⏳ Otomatik zaman aşımı ile uygulama kilitleme  
- 🌙 Karanlık mod desteği  
- 📁 Şifrelenmiş dışa aktarma / yedekleme (opsiyonel)

---

## 👤 Kullanıcı Senaryosu

> Ahmet, farklı platformlarda birçok hesabı olan bir kullanıcıdır. Keykeep uygulamasını indirdikten sonra kendine özel bir ana şifre belirler. Uygulamaya giriş yaptıktan sonra e-posta, banka ve sosyal medya hesapları için farklı kategoriler oluşturur. Daha önceden oluşturduğu şifre ve kullanıcı adlarını oluşturduğu kategori içerisine girerek, kolayca bulabilir hale gelir.
Telefonu elinden bıraktığında 1 dakika içinde uygulama otomatik olarak kilitlenir. Böylece başkalarının erişimi engellenir. İnternete ihtiyaç duymadan şifrelerini kontrol eder.


---

## 🧪 Kullanılan Teknolojiler

- **Android Studio**  
- **Kotlin** 
- **Room Database** – Yerel veri saklama  
- **AES Encryption** – Güvenli şifreleme  
- **SharedPreferences** (isteğe bağlı) – Ayarlar ve ana şifre için  
- **Jetpack Compose** (isteğe bağlı) – Modern UI desteği  

---

## 🗓 Tahmini Zaman Çizelgesi

| Hafta     | Yapılacak İşler                                                      |
|-----------|----------------------------------------------------------------------|
| 1. Hafta  | Proje planı ve tasarımı, kullanıcı arayüzü taslağı                   |
| 2. Hafta  | Veritabanı modeli ve şifreleme altyapısı geliştirme                 |
| 3. Hafta  | Ana şifre girişi ve doğrulama sistemi                                |
| 4. Hafta  | Şifre ekleme/silme/güncelleme işlemleri                              |
| 5. Hafta  | Şifre üretici modülü ve kategori sistemi                             |
| 6. Hafta  | Otomatik kilitlenme ve güvenlik özellikleri                          |
| 7. Hafta  | Arayüz iyileştirmeleri ve karanlık mod desteği                       |
| 8. Hafta  | Testler, hata ayıklama ve dokümantasyon                              |
| 9. Hafta  | Sunum ve proje teslimi                                               |

---

## ✅ Sonuç ve Katkı

Keykeep, kullanıcıların şifrelerini tamamen cihazlarında ve güvenli bir biçimde saklamalarını sağlayan özgün ve kullanıcı dostu bir uygulamadır. Bu proje, kullanıcı gizliliğine duyarlı, çevrimdışı kullanılabilen ve modern güvenlik standartlarına uygun bir mobil uygulama örneğidir.

---


