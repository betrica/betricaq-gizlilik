# 🌸 BETRICAQ – KULLANIM KOŞULLARI, GİZLİLİK POLİTİKASI VE KVKK AYDINLATMA METNİ

> **Yürürlük / Son Güncelleme:** 22 Kasım 2026  
> **Uygulama:** Betricaq Müzik Asistanı (`v1.0`)  
> **Platform:** [MicUp](https://micup.gg/)  
> **Dil Desteği:** Türkçe & English (Otomatik Uygulama Dili Algılama)  
> **Destek Sunucusu:** [Betricaq Support](https://micup.gg/invite/wybhDhiJ)

---

## 📑 İçindekiler / Table of Contents
- [🇹🇷 Türkçe Yasal Metin, Gizlilik ve KVKK Aydınlatma Metni](#-türkçe-yasal-metin-gizlilik-ve-kvkk-aydınlatma-metni)
  - [1. Hizmet Tanımı ve Kullanım Koşulları](#1-hizmet-tanımı-ve-kullanım-koşulları)
  - [2. Sıfır Kayıt (Zero-Log) Gizlilik Politikası](#2-sıfır-kayıt-zero-log-gizlilik-politikası)
  - [3. 6698 Sayılı KVKK Aydınlatma Metni](#3-6698-sayılı-kvkk-aydınlatma-metni)
  - [4. Telif Hakları, 5846 Sayılı FSEK ve Uyar-Kaldır](#4-telif-hakları-5846-sayılı-fsek-ve-uyar-kaldır)
  - [5. Sorumluluk Sınırı ve Politika Değişiklikleri](#5-sorumluluk-sınırı-ve-politika-değişiklikleri)
- [🇬🇧 English Terms of Service, Privacy Policy & Copyright Notice](#-english-terms-of-service-privacy-policy--copyright-notice)
  - [1. Terms of Service](#1-terms-of-service)
  - [2. Zero-Log Privacy Policy (KVKK & GDPR Aligned)](#2-zero-log-privacy-policy-kvkk--gdpr-aligned)
  - [3. Copyright & DMCA Takedown Policy](#3-copyright--dmca-takedown-policy)
  - [4. Limitation of Liability & Updates](#4-limitation-of-liability--updates)
- [📬 İletişim & Destek / Contact & Support](#-i̇letişim--destek--contact--support)

---

## 🇹🇷 TÜRKÇE YASAL METİN, GİZLİLİK VE KVKK AYDINLATMA METNİ

### 1. Hizmet Tanımı ve Kullanım Koşulları
**Betricaq**, MicUp topluluklarının sesli odalarında yüksek kaliteli müzik ve oynatma listesi dinleyebilmesi amacıyla geliştirilmiş bağımsız bir gerçek zamanlı ses aktarım asistanıdır. Betricaq'ı bir sunucuya ekleyen yöneticiler ve herhangi bir slash (`/`) veya ön ek komutunu kullanan tüm üyeler, işbu koşulları kabul etmiş sayılır.

* **Gerçek Zamanlı Köprüleme:** Betricaq bir dosya barındırma, indirme veya müzik arşivi hizmeti değildir. Kullanıcının ilettiği şarkı adı, YouTube/Spotify bağlantısı veya oynatma listesi üzerinden kamuya açık kaynaklardaki ses akışını anlık olarak sesli odaya iletir.
* **Hizmet Sürekliliği:** Bot yüksek erişilebilirlik hedefiyle işletilir; ancak bakım çalışmaları, MicUp platform güncellemeleri veya üçüncü taraf kaynak kısıtlamaları nedeniyle geçici kesintiler yaşanabilir. Geliştirici ekip, önceden bildirimde bulunmaksızın özellikleri güncelleme, değiştirme veya sonlandırma hakkını saklı tutar.
* **Adil ve Hukuka Uygun Kullanım:** Komut spam'i yapmak, otomatik betiklerle hizmete aşırı yük bindirmek, yasa dışı, hakaret veya nefret içerikli ses yayınlarını kasıtlı olarak aktarmak yasaktır. Kötüye kullanım tespit edilen kullanıcıların veya sunucuların Betricaq erişimi geçici ya da kalıcı olarak engellenebilir.

---

### 2. Sıfır Kayıt (Zero-Log) Gizlilik Politikası
Betricaq, **veri minimizasyonu** ve **kalıcı veritabanısız (zero-log)** çalışma prensibiyle tasarlanmıştır.

| Veri Kategorisi | İşlenme Durumu | Saklama Ortamı & Süresi |
| :--- | :--- | :--- |
| Mikrofon / Sesli Oda Konuşmaları | ❌ Asla dinlenmez, kaydedilmez, analiz edilmez | Saklanmaz |
| Komut Dışı Sohbet Mesajları | ❌ Okunmaz, işlenmez, arşivlenmez | Saklanmaz |
| Gerçek Ad, E-posta, Telefon, IP, Konum | ❌ Talep edilmez ve toplanmaz | Saklanmaz |
| Sunucu / Kanal ID ve Ses Odası Durumu | ✅ Yalnızca aktif oynatma ve oda çakışma koruması için | Geçici Bellek (RAM) – Oturum bitince silinir |
| Kullanıcı Görünen Adı & Dil Tercihi (`locale`) | ✅ Kart üzerinde istek sahibini göstermek ve TR/EN dil uyumu için | Geçici Bellek (RAM) – Yeniden başlatmada silinir |
| Arama Sorgusu / Şarkı & Playlist Bağlantısı | ✅ İstenen parçayı açık medya kaynağında bulmak için anlık iletilir | Kalıcı olarak saklanmaz |

* **Yalnızca Çıkış (Output-Only) Ses Bağlantısı:** Betricaq sesli odalarda yalnızca müzik yayını yapar; kullanıcıların ses akışlarını almaz veya kaydetmez.
* **Otomatik Temizleme:** Oynatma durdurulduğunda, bot ses kanalından ayrıldığında veya uygulama yeniden başlatıldığında geçici bellekteki tüm oturum ve kuyruk verileri geri döndürülemez biçimde temizlenir.

---

### 3. 6698 Sayılı KVKK Aydınlatma Metni
6698 sayılı Kişisel Verilerin Korunması Kanunu (**"KVKK"**) uyarınca, Betricaq Müzik Asistanı kullanımı sırasında anlık olarak işlenen asgari teknik verilere ilişkin aydınlatma bilgileri aşağıdadır:

* **Veri Sorumlusu:** Betricaq Geliştirici ve Topluluk Yönetimi Ekibi.
* **İşleme Amacı ve Hukuki Sebep:** Komut çağrısı sırasında platform tarafından iletilen asgari teknik tanımlayıcılar; KVKK Madde 5/2-c (*sözleşmenin / hizmetin doğrudan ifası için gerekli olması*) ve Madde 5/2-f (*ilgili kişinin temel hak ve özgürlüklerine zarar vermemek kaydıyla veri sorumlusunun meşru menfaati*) kapsamında yalnızca ses akışını başlatmak, görsel müzik kartı üretmek, uygulama diline göre (TR/EN) yanıt vermek ve ses odası çakışmalarını engellemek amacıyla işlenir.
* **Aktarım:** Hiçbir kullanıcı verisi reklam ağları, veri analiz servisleri, veri komisyoncuları veya ticari üçüncü taraflarla paylaşılmaz ve satılmaz.
* **İlgili Kişinin Hakları (KVKK Madde 11):** Her kullanıcı; veri işlenip işlenmediğini öğrenme, işlenmişse bilgi talep etme, işlenme amacını sorgulama ve verilerin silinmesini/imhasını isteme haklarına sahiptir. Betricaq kalıcı bir veritabanı tutmadığından, bot kullanımının sonlandırılmasıyla birlikte geçici oturum kayıtları kendiliğinden ortadan kalkar. Talepleriniz için destek sunucumuz üzerinden ekibimize ulaşabilirsiniz.

---

### 4. Telif Hakları, 5846 Sayılı FSEK ve Uyar-Kaldır
* Betricaq sunucularında telifli hiçbir ses, video, albüm veya oynatma listesi dosyası depolanmaz ya da dağıtılmaz; tüm akışlar üçüncü taraf açık medya platformlarından gerçek zamanlı olarak aktarılır.
* Aktarılan içeriklerin telif ve hukuki sorumluluğu, içeriği barındıran kaynak platforma ve çalma komutunu başlatan kullanıcıya aittir.
* **Uyar-Kaldır (Takedown):** 5846 sayılı Fikir ve Sanat Eserleri Kanunu (FSEK) kapsamında hak sahibi olduğunuz bir içeriğin Betricaq üzerinden aktarılmasını istemiyorsanız, ilgili URL'yi destek sunucumuz aracılığıyla iletmeniz halinde söz konusu bağlantı bot genelinde kalıcı olarak engellenir.

---

### 5. Sorumluluk Sınırı ve Politika Değişiklikleri
* Betricaq *"olduğu gibi" (as-is)* sunulmaktadır. Üçüncü taraf medya kaynaklarından, MicUp altyapısından veya internet bağlantısından kaynaklanan kesintilerden geliştirici ekip sorumlu tutulamaz.
* Bu metin ihtiyaç halinde güncellenebilir. Güncellenen tarih sayfanın en üstünde belirtilir ve botun kullanılmaya devam edilmesi güncel koşulların kabulü anlamına gelir.

---

## 🇬🇧 ENGLISH TERMS OF SERVICE, PRIVACY POLICY & COPYRIGHT NOTICE

### 1. Terms of Service
**Betricaq** is an independent real-time audio streaming assistant built for [MicUp](https://micup.gg/) communities. By adding Betricaq to a server or invoking any slash (`/`) or prefix command, you agree to the following terms:

* **Real-Time Audio Bridging:** Betricaq is not a media host, downloader, or music archive. It bridges live audio streams from public third-party sources (such as YouTube and Spotify metadata lookups) directly into your voice channel.
* **Availability:** The service is provided on an *"as-is"* and *"as-available"* basis without warranty of uninterrupted uptime. Features may be updated, modified, or discontinued at any time.
* **Acceptable Use:** Command spamming, automated flooding, exploiting rate limits, or intentionally streaming unlawful, abusive, or harmful content is strictly prohibited and may lead to temporary or permanent access restrictions.

---

### 2. Zero-Log Privacy Policy (KVKK & GDPR Aligned)
Betricaq is engineered around **strict data minimization** and **zero persistent storage**:

| Data Category | Handling Policy | Storage & Retention |
| :--- | :--- | :--- |
| Voice Channel / Microphone Audio | ❌ Never listened to, recorded, or analyzed | Never stored |
| Non-Command Chat Messages | ❌ Ignored and never logged | Never stored |
| Personal Info (Name, Email, IP, Location) | ❌ Never requested or collected | Never stored |
| Guild / Channel IDs & Voice State | ✅ Used strictly to route audio and prevent room conflicts | Volatile RAM only – cleared on session end |
| Display Name & App Locale (`tr` / `en`) | ✅ Used to credit song requests and localize responses | Volatile RAM only – cleared on restart |
| Search Queries / Track & Playlist URLs | ✅ Forwarded live to resolve media streams | Never persistently stored |

* **Output-Only Voice Engine:** Betricaq only transmits outgoing audio to voice channels and never captures incoming voice streams.
* **No Data Selling or Tracking:** No user or server data is ever sold, rented, or shared with advertisers, analytics trackers, or third-party brokers.
* **User Rights:** Under KVKK (Law No. 6698) and GDPR principles, you have the right to inquire about and request deletion of your data. Because Betricaq maintains no permanent database, ending your session automatically removes all transient state.

---

### 3. Copyright & DMCA Takedown Policy
* Betricaq does not host, cache, or distribute copyrighted audio or video files. All streams originate in real time from public third-party platforms.
* Responsibility for requested content rests with the hosting platform and the user initiating playback.
* **Takedown Requests:** Copyright holders who wish to prevent specific URLs from being streamed via Betricaq may contact our support team with the relevant link(s) for prompt permanent URL filtering.

---

### 4. Limitation of Liability & Updates
* To the maximum extent permitted by applicable law, the Betricaq Development Team shall not be liable for any indirect or incidental damages, service interruptions, or third-party platform changes.
* We may revise this notice periodically. The latest revision date is displayed at the top of this document, and continued use of Betricaq constitutes acceptance of the updated terms.

---

## 📬 İLETİŞİM & DESTEK / CONTACT & SUPPORT

* **MicUp Destek Sunucusu / Support Server:** [Betricaq Support]([https://micup.gg/invite/IN33KpwG](https://micup.gg/invite/wybhDhiJ))
* **Geliştirici Ekip / Maintainer:** Betricaq Development betrica
