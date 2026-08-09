---
layout: default
title: Gizlilik Politikası
permalink: /privacy-tr/
---

# İlaçVakti — Gizlilik Politikası

**Son güncelleme:** 2 Ağustos 2026

İlaçVakti, Eczacı **Mehmet Tuğberk Özsoy** tarafından geliştirilen, kullanıcıların ilaç takibini kolaylaştıran bir mobil uygulamadır. Kullanıcılarımızın gizliliği temel önceliğimizdir; bu politika hangi verilerin nasıl işlendiğini şeffafça açıklar.

İngilizce sürüm: [privacy-en](/ilacvakti-legal/privacy-en/)

---

## 1. Toplanmayan Veriler

İlaçVakti kullanıcılarından kişisel kimlik bilgisi (ad, e-posta, telefon, kimlik no, doğum tarihi vb.) **toplamaz**, kendi sunucularına göndermez ve üçüncü taraflarla paylaşmaz. Hesap oluşturma gerektirmez; uygulama tamamen **anonim** çalışır.

Toplanmayan veriler ayrıntılı liste:
- ❌ Reklam veya analitik takibi
- ❌ Üçüncü taraf analytics servisleri (Google Analytics, Facebook Pixel vb.)
- ❌ Konum bilgisi
- ❌ Kişi listesi, takvim
- ❌ Ses kaydı saklama (mikrofon yalnız isteğe bağlı sesli girişte açılır, bkz. 3.6)
- ❌ Hesap oluşturma, e-posta, telefon
- ❌ Apple Health verisi **okunmaz** (isteğe bağlı, yalnız-yazma senkron için bkz. 3.5)

---

## 2. Yerel Depolama (Cihazda Saklanan Veriler)

Uygulamaya girdiğiniz tüm bilgiler **yalnızca cihazınızın dahili hafızasında** saklanır:

- İlaç adları, dozajları, hatırlatma saatleri
- Profil isimleri (sizin verdiğiniz adlar) ve opsiyonel profil fotoğrafı
- İlaç stok bilgileri ve fotoğrafları
- Tedavi geçmişi, alındı/atlandı kayıtları
- Streak ve rozet bilgileri
- Manuel eklenen sağlık raporları ve notları
- Tema, dil, bildirim sesi ve ayar tercihleri

Uygulamayı sildiğinizde bu verilerin tümü cihazınızla birlikte silinir.

---

## 3. İzinler

### 3.1 Bildirimler
İlaç hatırlatıcıları için bildirim izni istenir. Bildirimler cihazınızda **yerel olarak zamanlanır**; sunucuya bağlı değildir.

### 3.2 Kamera
Sadece *"İlaç Ekle"* ekranında, ilaç kutusu üzerindeki barkod/QR kodları taramak veya ilaç fotoğrafı çekmek için kamera izni istenir. Kamera görüntüsü sunucuya gönderilmez.

### 3.3 Fotoğraflar
İsteğe bağlı olarak ilaç veya profil fotoğrafı eklemek için galeri erişimi istenir. Seçtiğiniz fotoğraflar yalnızca cihazınızın uygulama dahili klasörüne kopyalanır.

### 3.4 İlaç Veritabanı Sorgulama
İlaç kutusu üzerindeki barkod/karekodu taradığınızda veya bir ilacı adıyla aradığınızda, ilaç adı ve bilgilerini (prospektüs, ambalaj, son kullanma tarihi vb.) getirmek için yalnızca ilgili **barkod/ürün kodu veya ilaç adı** resmi bir ilaç veritabanı servisine gönderilir. Hangi servisin kullanılacağı cihaz bölgenize bağlıdır: **NosyAPI** (Türkiye), **ABD FDA openFDA** veritabanı (Amerika Birleşik Devletleri) veya **AEMPS CIMA** (İspanya). Bu sorguya hiçbir kişisel bilgi (adınız, profil bilgisi, sağlık verisi, fotoğraf veya kamera görüntüsü) eklenmez — yalnızca taranan kod veya arama terimi iletilir. Bu özellik isteğe bağlıdır; kullanmazsanız hiçbir veri gönderilmez.

İzinleri iOS *Ayarlar &gt; İlaçVakti* üzerinden istediğiniz zaman iptal edebilirsiniz.

### 3.5 Apple Health (HealthKit) — İsteğe Bağlı Yazma
Premium kullanıcılar dilerse *Ayarlar → Apple Health'e kaydet* seçeneğini açarak, uygulamada girdikleri **tansiyon, kan şekeri ve nabız** ölçümlerinin Apple Sağlık (Health) uygulamasına da **yazılmasını** sağlayabilir. Bu özellik **tamamen isteğe bağlıdır** ve varsayılan olarak **kapalıdır**.

- İlaçVakti, Health verilerinizi **okumaz**; erişim yalnızca **yazma** yönündedir ve iOS'un izin ekranıyla açıkça onaylanır.
- Yalnızca **kendi profilinize** ait ölçümler yazılır; aile üyesi profillerinin verileri yazılmaz.
- Veriler doğrudan cihazınızdaki Health deposuna gider; **hiçbir sunucuya gönderilmez**. Health verileriniz Apple tarafından şifrelenir.
- Uygulamada bir ölçümü siler veya düzenlerseniz, Health'e yazılmış kopyası da güncellenir/silinir.
- İzni istediğiniz zaman iOS *Ayarlar → Sağlık → Veri Erişimi ve Aygıtlar → İlaçVakti* üzerinden geri alabilirsiniz.
- Sağlık verileri hiçbir koşulda reklam, pazarlama veya analitik amaçla kullanılmaz (Apple App Store Kural 5.1.3 uyumlu).

### 3.6 Mikrofon ve Konuşma Tanıma — İsteğe Bağlı
Ölçüm ekleme ekranındaki mikrofon simgesine dokunduğunuzda tansiyon veya kan şekeri değerinizi **konuşarak** girebilirsiniz. Bu özellik **tamamen isteğe bağlıdır**; simgeye dokunmadığınız sürece mikrofon hiçbir zaman açılmaz.

- Konuşmanız **cihazınızın üzerinde** yazıya çevrilir; uygulama iOS'un cihaz-üstü konuşma tanımasını **zorunlu** kılar. **Ses hiçbir sunucuya gönderilmez** — özellik uçak modunda da çalışır.
- **Ses kaydı tutulmaz.** Konuşma yazıya çevrildikten sonra ses verisi saklanmaz; yalnızca tanınan sayılar ekrandaki alanlara yazılır.
- Tanınan değer **doğrudan kaydedilmez**: alana yazılır ve siz görüp **Kaydet**'e basana kadar kayda geçmez.
- Mikrofon yalnız bu ekranda ve yalnız siz başlattığınızda etkinleşir; arka planda dinleme yapılmaz.
- İzni istediğiniz zaman iOS *Ayarlar &gt; İlaçVakti* üzerinden geri alabilirsiniz.

---

## 4. Çökme Raporları (Sentry)

Uygulamanın istikrarını artırmak için anonim çökme raporları **Sentry** servisi aracılığıyla toplanır.

**Toplanan:**
- Çökme zamanı, cihaz modeli, iOS sürümü, uygulama sürümü
- Hata mesajı ve teknik stack trace
- Çökmeden önceki teknik bilgiler (örn. açılan ekranlar)

**Toplanmayan:**
- Kullanıcı adı, e-posta, IP adresi (`sendDefaultPii` kapalı)
- Ekran görüntüsü, kişisel ilaç verileri, sağlık bilgileri
- Fotoğraflar veya rapor içerikleri

Sentry verileri yalnızca uygulama iyileştirmesi için kullanılır; pazarlama veya reklam için **asla** kullanılmaz. Sentry verileri en fazla **90 gün** saklanır.

Sentry gizlilik politikası: <https://sentry.io/privacy/>

---

## 5. Premium Abonelik ve RevenueCat

İlaçVakti isteğe bağlı **Premium aboneliği** sunar:

| Plan | Fiyat | Özellik |
|---|---|---|
| Aylık | yaklaşık ₺49,99 ($0.99) | Otomatik yenilenir |
| Yıllık | yaklaşık ₺299,99 ($5.99) | **7 gün ücretsiz deneme** dahil, otomatik yenilenir |

### Abonelik Yönetimi
- Abonelik otomatik yenilenir; mevcut dönem bitiminden en az **24 saat önce** iptal edilmezse ücret iTunes hesabınızdan tahsil edilir.
- İptal yolu: iOS *Ayarlar → Apple ID → Abonelikler*.
- **Family Sharing** etkindir — bir abonelik 5 aile üyesine kadar paylaşılabilir.
- Ödeme Apple tarafından işlenir; İlaçVakti kart bilgisine erişmez.

### Eski Sürüm Kullanıcıları İçin Ömür Boyu Ücretsiz
Sürüm **2.0.1 (build 5) ve öncesini** yüklemiş kullanıcılar otomatik olarak **ömür boyu Premium kullanma hakkına** sahiptir. Bu, Apple makbuzu üzerindeki `originalApplicationVersion` alanı ile cihazda anonim olarak doğrulanır.

### RevenueCat (Abonelik Doğrulama)
Abonelik durumunu doğrulamak için **RevenueCat** servisi kullanılır. Apple ID'nizden türetilmiş anonim bir tanımlayıcı (App User ID) ve Apple makbuz verisi RevenueCat'e gönderilir. Adınız, e-postanız veya kişisel bilgileriniz **paylaşılmaz**.

RevenueCat gizlilik politikası: <https://www.revenuecat.com/privacy/>

### Kullanım Koşulları
Apple Standart EULA geçerlidir: <https://www.apple.com/legal/internet-services/itunes/dev/stdeula/>

---

## 6. Veri Paylaşımı

İlaçVakti kullanıcı verilerini **hiçbir üçüncü tarafla paylaşmaz, satmaz veya pazarlama amacıyla kullanmaz**. Tek istisnalar:

- Bölüm 3.4'te belirtilen ilaç veritabanı sorgulamaları (NosyAPI / ABD FDA openFDA / AEMPS CIMA) — yalnızca taranan kod veya aranan ilaç adı iletilir, kişisel veri içermez.
- Bölüm 4'te belirtilen anonim çökme raporları (Sentry).
- Bölüm 5'te belirtilen anonim abonelik doğrulama verisi (RevenueCat + Apple).

---

## 7. KVKK Kapsamındaki Haklarınız

6698 sayılı Kişisel Verilerin Korunması Kanunu (KVKK) Madde 11 uyarınca aşağıdaki haklara sahipsiniz:

- Kişisel verilerinizin işlenip işlenmediğini öğrenme,
- İşlenmişse buna ilişkin bilgi talep etme,
- Verilerin düzeltilmesini veya silinmesini isteme,
- Aktarıldığı üçüncü kişileri bilme,
- Otomatik sistemlerle yapılan analiz sonucunda aleyhinize çıkan sonuca itiraz etme,
- Zararın giderilmesini talep etme.

Bu haklarınızı kullanmak için <ilacvaktidestek@gmail.com> adresine başvurabilirsiniz. Talepleriniz en geç **30 gün** içinde yanıtlanır.

---

## 8. AB Kullanıcıları için GDPR

AB'de ikamet ediyorsanız, GDPR kapsamında **erişim, düzeltme, silme, işlemeye itiraz ve veri taşınabilirliği** haklarına sahipsiniz. Veri işleme hukuki dayanağımız: uygulama hizmetinin sağlanması için gereklilik (GDPR Madde 6(1)(b)) ve hata raporlama için meşru menfaat (Madde 6(1)(f)).

---

## 9. Çocukların Gizliliği

Uygulama **4+ yaş** olarak derecelendirilmiştir. 13 yaşından küçük çocuklardan bilerek veri toplanmaz. Veliler çocuk profili (aile üyesi) eklerse, profil bilgileri yalnızca cihazda yerel olarak saklanır.

---

## 10. Veri Güvenliği

Verileriniz çoğunlukla cihazınızda saklandığı için iOS'un sunduğu donanımsal şifreleme (Secure Enclave) ile korunur. Üçüncü taraf hizmetlerle iletişim HTTPS üzerinden şifreli gerçekleşir.

---

## 11. Politika Değişiklikleri

Bu politika zaman zaman güncellenebilir; önemli değişiklikler uygulama içi bildirim veya yeni sürüm açıklamalarıyla duyurulur. *Son güncelleme* tarihini düzenli kontrol etmeniz önerilir.

---

## 12. İletişim

E-posta: <ilacvaktidestek@gmail.com>
