<div align="center">

# Chat THT for Android

**TurkHackTeam topluluğu için Revolt tabanlı Android sohbet uygulaması.**

[![GitHub Releases](https://img.shields.io/github/v/release/ThT0AltayHR/chat-tht-android?label=İndir&style=for-the-badge)](https://github.com/ThT0AltayHR/chat-tht-android/releases/latest)

> Geliştirici: **AltayHR** | [turkhackteam.org](https://www.turkhackteam.org) | [thtakademi.com.tr](https://thtakademi.com.tr)

</div>

---

## Özellikler

| Özellik | Açıklama |
|---------|----------|
| 💬 **Mesajlaşma** | Gerçek zamanlı metin, medya ve dosya paylaşımı |
| 🖼️ **Medya Desteği** | Fotoğraf, video ve dosya gönderimi; ekran içi görüntüleyici |
| 🎙️ **Sesli Kanallar** | Sesli konuşma kanallarına katılım |
| 🔔 **Bildirimler** | Push bildirimleri; kanal bazlı bildirim tercihleri |
| 🌐 **Sunucu & Kanal Yönetimi** | Sunucu oluşturma, kanal yönetimi, rol ve izin sistemi |
| 👥 **Arkadaş Sistemi** | Arkadaş ekleme/çıkarma, DM, engelleme |
| 🎨 **Görünüm Ayarları** | Karanlık/aydınlık mod, özel köşe radyusu, renk teması |
| 🔐 **İki Faktörlü Kimlik Doğrulama** | TOTP ve kurtarma kodu desteği |
| 📱 **Uyarlanabilir Tasarım** | Material You / Jetpack Compose tabanlı modern arayüz |
| 🔗 **Ayarlar → Topluluk** | Doğrudan turkhackteam.org ve thtakademi.com.tr linkleri |
| 🌍 **Çoklu Dil** | 40+ dil desteği |
| 🧪 **Deneyseller** | Labs ve deneysel özellik paneli |

---

## İndirme

**En güncel APK her zaman burada:**

```
https://github.com/ThT0AltayHR/chat-tht-android/releases/latest
```

GitHub Releases sayfasından `ChatTHT-vX.X.X.apk` dosyasını indirin.

---

## Kurulum (Geliştirici)

1. [Android Studio](https://developer.android.com/studio) yükleyin (en güncel sürüm)
2. Depoyu klonlayın:
   ```bash
   git clone https://github.com/ThT0AltayHR/chat-tht-android.git
   cd chat-tht-android
   ```
3. `app/google-services.json.example` dosyasını `app/google-services.json` olarak kopyalayın
4. `stoatbuild.properties.example` → `stoatbuild.properties` olarak kopyalayın
5. Android Studio'da `app` modülünü çalıştırın

---

## Teknoloji Yığını

- **Kotlin** + **Jetpack Compose** — Modern Android UI
- **Ktor** — Ağ katmanı (Revolt API)
- **Dagger/Hilt** — Bağımlılık enjeksiyonu
- **SQLDelight** — Yerel veritabanı
- **Firebase Cloud Messaging** — Push bildirimleri
- **Material 3** — Tasarım sistemi (kırmızı/koyu THT renk paleti)

---

## Gizlilik

Bu uygulama **hiçbir kullanıcı verisini** üçüncü taraflarla paylaşmaz.  
Revolt API sunucuları ile iletişim kurar; sunucu seçimi kullanıcıya aittir.

---

## Lisans

Bu proje [Stoat for Android](https://github.com/stoatchat/for-android) açık kaynak projesini temel almaktadır.  
Kaynak kodu [GPL-3.0](https://www.gnu.org/licenses/gpl-3.0.html) lisansı ile dağıtılmaktadır.

---

<div align="center">

Geliştirici: **AltayHR** • TurkHackTeam

[turkhackteam.org](https://www.turkhackteam.org) • [thtakademi.com.tr](https://thtakademi.com.tr)

</div>
