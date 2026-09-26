<div align="center">

  <h1>📖 Bookan Mobile App</h1>
  <p><strong>Kitap severlerin buluştuğu, ilham verici alıntıların ve yeni keşiflerin paylaşıldığı sosyal mobil platform.</strong></p>

  <!-- Rozetler -->
  <p>
    <img src="https://img.shields.io/badge/Flutter-%2302569B.svg?style=for-the-badge&logo=Flutter&logoColor=white" alt="Flutter" />
    <img src="https://img.shields.io/badge/Dart-%230175C2.svg?style=for-the-badge&logo=dart&logoColor=white" alt="Dart" />
    <img src="https://img.shields.io/badge/firebase-%23FFA611.svg?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase" />
    <img src="https://img.shields.io/badge/Google%20Books%20API-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Google Books API" />
  </p>

</div>

---

## 📌 Proje Hakkında

**Bookan**, kitap okuma kültürünü sosyal bir deneyime dönüştürmek amacıyla geliştirilmiş modern bir mobil uygulamadır. Kullanıcılar yalnızca kitap keşfetmekle kalmaz; okudukları eserlerden altını çizdikleri etkileyici cümleleri ve ilham verici alıntıları paylaşarak diğer kitap severlerle dinamik bir etkileşim kurabilirler.

Web sürümündeki topluluk odaklı vizyon, mobil tarafta **Flutter**, **Firebase** ve **Google Books API** gücüyle yüksek performanslı ve akıcı bir kullanıcı deneyimine taşınmıştır.

---

## ✨ Temel Özellikler

* **🔍 Kapsamlı Kitap Keşfi (Google Books API):** Milyonlarca kitaba ait yazar, yayınevi, sayfa sayısı, özet ve kapak görsellerine anında erişim ve arama.
* **✍️ Alıntı Paylaşımı:** Okunan kitaplardan etkileyici kısımları, sayfa ve kitap bilgisiyle birlikte topluluk akışında paylaşabilme.
* **❤️ Sosyal Etkileşim:** Paylaşılan alıntıları beğenme, yorum bırakma ve diğer okurlarla fikir alışverişinde bulunma.
* **📚 Kişisel Kütüphane & Okuma Listeleri:** Okunanlar, okunacaklar ve favori kitapları profilde düzenli bir şekilde listeleme.
* **🔐 Güvenli Kimlik Doğrulama:** Firebase Authentication ile hızlı kayıt olma, güvenli oturum açma ve oturum yönetimi.
* **⚡ Gerçek Zamanlı Veri:** Cloud Firestore altyapısı sayesinde anlık güncellenen beğeniler, yorumlar ve akış verileri.

---

## 🛠️ Teknoloji Yığını

| Alan | Teknoloji / Kütüphane | Açıklama |
| :--- | :--- | :--- |
| **Framework** | [Flutter](https://flutter.dev/) | Çapraz platform (iOS / Android) mobil uygulama geliştirme |
| **Programlama Dili** | [Dart](https://dart.dev/) | Güçlü tipli, nesne yönelimli modern programlama dili |
| **Kimlik Doğrulama** | Firebase Auth | Kullanıcı oturum ve güvenlik yönetimi |
| **Veritabanı** | Cloud Firestore | NoSQL, gerçek zamanlı ve ölçeklenebilir bulut veritabanı |
| **Medya Depolama** | Firebase Storage | Profil fotoğrafları ve kullanıcı medyaları |
| **Harici Servis** | Google Books API | Kitap metaverileri ve arama motoru entegrasyonu |

---

## 📂 Klasör Yapısı

```plaintext
lib/
├── core/             # Sabitler, temalar, network ve yardımcı fonksiyonlar (utils)
├── models/           # Kitap, kullanıcı ve alıntı veri modelleri
├── services/         # Firebase ve Google Books API servis entegrasyonları
├── viewmodels/       # Durum yönetimi (State Management) katmanı
├── views/            # Ekranlar (Screens)
│   ├── auth/         # Giriş ve kayıt ekranları
│   ├── home/         # Ana akış ve alıntı akışı
│   ├── book_detail/  # Kitap detay ve arama ekranları
│   └── profile/      # Kullanıcı profili ve kütüphane listeleri
└── widgets/          # Yeniden kullanılabilir özel arayüz bileşenleri
```

---

## 🚀 Kurulum ve Çalıştırma

Projeyi yerel ortamınızda çalıştırmak için aşağıdaki adımları takip edebilirsiniz:

### Gereksinimler

* [Flutter SDK](https://docs.flutter.dev/get-started/install) (3.x veya üzeri)
* Dart SDK
* Android Studio veya VS Code (Flutter eklentileri kurulu)
* Aktif bir Firebase projesi

### Adımlar

1. **Repoyu klonlayın:**
   ```bash
   git clone https://github.com/yorukokan/Bookan-Mobile-App.git
   cd Bookan-Mobile-App
   ```

2. **Bağımlılıkları yükleyin:**
   ```bash
   flutter pub get
   ```

3. **Firebase Yapılandırması:**
   * Firebase konsolunda yeni bir proje oluşturun ve Android/iOS uygulamalarınızı ekleyin.
   * `FlutterFire CLI` kullanarak konfigürasyonu otomatik yapın:
     ```bash
     flutterfire configure
     ```
   * Veya `google-services.json` (Android) ve `GoogleService-Info.plist` (iOS) dosyalarını ilgili dizinlere yerleştirin.

4. **API Anahtarları:**
   * Gerekliyse Google Books API anahtarınızı ilgili servis dosyasına (`services/book_service.dart`) veya `.env` yapılandırmanıza ekleyin.

5. **Uygulamayı başlatın:**
   ```bash
   flutter run
   ```

---
