<div align="center">

<!-- Header Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0C4A6E,45:0284C7,80:38BDF8,100:0EA5E9&height=210&section=header&text=Bookan%20Mobile%20App&fontSize=44&fontColor=F8FAFC&fontAlignY=38&desc=Social%20Book%20Discovery%20%E2%80%A2%20Quote%20Sharing%20%E2%80%A2%20Flutter%20%2B%20Firebase&descSize=16&descAlignY=62&animation=fadeIn" alt="Bookan Mobile App Banner" width="100%" />

<!-- Typing Animation -->
<a href="https://github.com/yorukokan/bookan-mobile-app">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=2600&pause=900&color=38BDF8&center=true&vCenter=true&width=780&lines=Flutter+%2B+Firebase+Social+Book+%26+Quote+Mobile+App;14+Categories+%E2%80%A2+Google+Books+API+%E2%80%A2+Real-Time+Firestore+Feed;Kitap+Ke%C5%9Ffi+%E2%80%A2+Al%C4%B1nt%C4%B1+Payla%C5%9F%C4%B1m%C4%B1+%E2%80%A2+Ki%C5%9Fisel+Okuma+Listeleri;Cross-Platform+Android+%26+iOS+Experience+with+Material+3" alt="Typing Animation" />
</a>

<br/>

<!-- Quick Action Pills -->
<p>
  <img src="https://img.shields.io/badge/Flutter-3.x%20%C2%B7%20Dart-02569B?style=for-the-badge&logo=flutter&logoColor=white&labelColor=0B0F19" alt="Flutter" />
  <a href="https://github.com/yorukokan/bookan-web-app">
    <img src="https://img.shields.io/badge/Bookan_Web_App-Companion_Repo-0284C7?style=for-the-badge&logo=googlechrome&logoColor=white&labelColor=0B0F19" alt="Bookan Web App" />
  </a>
  <a href="https://github.com/yorukokan">
    <img src="https://img.shields.io/badge/GitHub-yorukokan-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=0B0F19" alt="GitHub" />
  </a>
  <a href="https://linkedin.com/in/okanyoruk">
    <img src="https://img.shields.io/badge/LinkedIn-okanyoruk-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0B0F19" alt="LinkedIn" />
  </a>
  <a href="mailto:okanyoruk.tr@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0B0F19" alt="Email" />
  </a>
</p>

</div>

---

## 🎯 Overview · Proje Özeti

<table>
<tr>
<td width="50%" valign="top">
<h3>🇬🇧 English</h3>

**Bookan Mobile App** is a cross-platform social reading and quote-sharing application built with **Flutter**, **Firebase**, and the **Google Books API**. Designed as the mobile companion to <a href="https://github.com/yorukokan/bookan-web-app"><b>bookan-web-app</b></a>, it turns solitary reading into an interactive community experience on **Android** and **iOS**.

<ul>
  <li><b>Discover &amp; Search:</b> Browse 14 curated Turkish book categories or search titles, authors, and genres via Google Books API v1.</li>
  <li><b>Social Quote Feed:</b> Publish favorite passages with auto-fetched book covers, toggle likes, and join real-time comment threads powered by Cloud Firestore streams.</li>
  <li><b>Personal Library:</b> Rate books (1–5 stars), mark completed reads, save favorites, and organize custom reading lists with swipe-to-remove controls.</li>
  <li><b>Session &amp; Profile Sync:</b> Email/password auth with <code>SharedPreferences</code> Remember Me persistence and Firestore <code>WriteBatch</code> profile propagation across past posts.</li>
</ul>
</td>
<td width="50%" valign="top">
<h3>🇹🇷 Türkçe</h3>

**Bookan Mobile App**, **Flutter**, **Firebase** ve **Google Books API** ile geliştirilmiş çapraz platformlu bir sosyal kitap keşif ve alıntı paylaşım uygulamasıdır. <a href="https://github.com/yorukokan/bookan-web-app"><b>bookan-web-app</b></a> projesinin mobil eşleniği olarak **Android** ve **iOS** üzerinde akıcı bir okuma topluluğu deneyimi sunar.

<ul>
  <li><b>Keşif ve Arama:</b> Google Books API v1 üzerinden 14 seçili Türkçe kategoride kitapları keşfedin; başlık, yazar veya tür bazında anlık arama yapın.</li>
  <li><b>Sosyal Alıntı Akışı:</b> Kapak görseli otomatik tamamlanan alıntılar paylaşın; Cloud Firestore akışlarıyla anlık beğeni ve yorum etkileşimine katılın.</li>
  <li><b>Kişisel Kütüphane:</b> Kitaplara 1–5 yıldız puan verin, okunanları ve favorileri yönetin, kaydırarak çıkarma destekli özel okuma listeleri oluşturun.</li>
  <li><b>Oturum ve Profil Senkronizasyonu:</b> <code>SharedPreferences</code> tabanlı Beni Hatırla oturum yönetimi ve <code>WriteBatch</code> ile profil güncellemelerinin eski gönderilere toplu yansıtılması.</li>
</ul>
</td>
</tr>
</table>

---

## ✨ Key Features · Öne Çıkan Özellikler

<table>
<tr>
<td width="50%" valign="top">
<h4>🔍 Book Discovery &amp; 14 Categories · Kitap Keşfi ve 14 Kategori</h4>
<b>EN:</b> Browse 14 curated categories (Fiction, Classics, Sci-Fi, Fantasy, Philosophy, History, Poetry, etc.) or run instant keyword searches with Turkish language filtering (<code>langRestrict=tr</code>) and cover-validated 2-column grids.<br/>
<b>TR:</b> Roman, Klasik, Bilim Kurgu, Fantastik, Felsefe, Tarih, Şiir dahil 14 kategoride gezinin veya anlık arama yapın; Türkçe filtreleme (<code>langRestrict=tr</code>) ve 2 sütunlu kapak ızgarası ile kitapları inceleyin.<br/><br/>
<code>home_page.dart</code> · <code>book_service.dart</code> · <code>book_model.dart</code>
</td>
<td width="50%" valign="top">
<h4>💬 Real-Time Quote Feed &amp; Comments · Canlı Alıntı Akışı ve Yorumlar</h4>
<b>EN:</b> Live community feed via Firestore <code>StreamBuilder</code>. Share quotes directly from a book detail screen or via a bottom sheet that auto-fetches book covers and authors from Google Books API, plus like toggling and collapsible live comments.<br/>
<b>TR:</b> Firestore <code>StreamBuilder</code> ile gerçek zamanlı topluluk akışı. Kitap detayından veya Google Books API ile kapak ve yazar bilgisini otomatik çeken hızlı pencereden alıntı paylaşın; beğenin ve canlı yorum yapın.<br/><br/>
<code>quotes_page.dart</code> · <code>add_quote_page.dart</code> · <code>firestore_service.dart</code>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h4>📚 Personal Library &amp; Custom Lists · Kişisel Kütüphane ve Özel Listeler</h4>
<b>EN:</b> Track completed books (<code>okunanlar</code>), bookmark favorites (<code>favoriler</code>), create custom reading lists (<code>listeler</code>), swipe to remove books with <code>Dismissible</code>, or delete entire lists with confirmation dialogs.<br/>
<b>TR:</b> Okunan kitapları (<code>okunanlar</code>) ve favorileri (<code>favoriler</code>) takip edin; özel okuma listeleri (<code>listeler</code>) oluşturun, <code>Dismissible</code> ile kaydırarak kitap çıkarın veya listeyi tek tıkla silin.<br/><br/>
<code>book_detail.dart</code> · <code>read_books_page.dart</code> · <code>list_detail_page.dart</code>
</td>
<td width="50%" valign="top">
<h4>⭐ 5-Star Book Rating · 5 Yıldızlı Kitap Puanlama</h4>
<b>EN:</b> Interactive 5-star rating bar on every book detail page that persists per-user scores in Cloud Firestore (<code>users/{uid}/ratings/{bookId}</code>) and restores them automatically on revisit.<br/>
<b>TR:</b> Her kitap detay sayfasında etkileşimli 5 yıldızlı puanlama çubuğu. Kullanıcı puanları Cloud Firestore'da (<code>users/{uid}/ratings/{bookId}</code>) saklanır ve sayfa açıldığında otomatik yüklenir.<br/><br/>
<code>book_detail.dart</code> · <code>firestore_service.dart</code>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h4>🔐 Auth &amp; Remember Me Session · Kimlik Doğrulama ve Beni Hatırla</h4>
<b>EN:</b> Firebase Email/Password sign-in, registration with Firestore user profile creation, password-reset email dialog, and startup session gating (<code>AuthKontrol</code>) backed by <code>SharedPreferences</code>.<br/>
<b>TR:</b> Firebase E-posta/Şifre ile giriş, kayıt sırasında Firestore kullanıcı profili oluşturma, şifre sıfırlama bağlantısı gönderme ve <code>SharedPreferences</code> destekli <code>AuthKontrol</code> açılış oturum denetimi.<br/><br/>
<code>main.dart</code> · <code>login_page.dart</code> · <code>register_page.dart</code> · <code>auth_service.dart</code>
</td>
<td width="50%" valign="top">
<h4>👤 Profile, Stats &amp; Batch Sync · Profil, İstatistikler ve Toplu Senkronizasyon</h4>
<b>EN:</b> Real-time counters for Read, Quotes, Favorites, and Lists; avatar picker, username and bio editor; swipe-to-delete personal quotes; and Firestore <code>WriteBatch</code> syncing updated profile names/avatars to all past feed posts.<br/>
<b>TR:</b> Okunan, Alıntı, Favori ve Liste için canlı sayaçlar; avatar seçici, kullanıcı adı ve biyografi düzenleme; kaydırarak silinebilen alıntılarım sayfası ve <code>WriteBatch</code> ile eski gönderilerin toplu güncellenmesi.<br/><br/>
<code>profile_page.dart</code> · <code>my_quotes_page.dart</code> · <code>firestore_service.dart</code>
</td>
</tr>
</table>

---

## 🏗️ Architecture · Mimari

```text
lib/main.dart (Firebase.initializeApp + Material 3 Theme)
       │
       ▼
  AuthKontrol ──► SharedPreferences ('beniHatirla') + FirebaseAuth.currentUser
       │
       ├──[Unauthenticated]──► views/auth/ (LoginPage ◄──► RegisterPage)
       │                              │
       │                              ▼
       │                     services/auth_service.dart ──► Firebase Auth + Firestore (users)
       │
       └──[Authenticated]────► views/navigation/navigation_bar.dart (MainScaffold)
                                      │
          ┌───────────────────────────┼───────────────────────────┐
          ▼                           ▼                           ▼
   views/home/                 views/quotes/               views/profile/
   HomePage                    QuotesPage                  ProfilePage
   (14 Categories + Search)    (Live Feed + QuoteCard)     (Stats, Favorites, Lists)
          │                           │                     ├── ReadBooksPage
          ▼                           │                     ├── MyQuotesPage
   views/book/                        │                     └── ListDetailPage
   BookDetail ──► AddQuotePage        │                           │
          │                           │                           │
          └──────────────┬────────────┴───────────────────────────┘
                         │
          ┌──────────────┴──────────────┐
          ▼                             ▼
 services/book_service.dart    services/firestore_service.dart
 (HTTP GET + BookModel)        (Streams, CRUD, WriteBatch)
          │                             │
          ▼                             ▼
 Google Books API v1           Cloud Firestore
 (googleapis.com/books/v1)     ├── users/{uid}
                               │   ├── favoriler/{bookId}
                               │   ├── okunanlar/{bookId}
                               │   ├── ratings/{bookId}
                               │   └── listeler/{listeId}/kitaplar/{bookId}
                               └── feed/{quoteId}
                                   └── comments/{commentId}
```

---

## 🛠️ Tech Stack · Teknoloji Yığını

<div align="center">

<p>
  <img src="https://img.shields.io/badge/Flutter-3.x-02569B?style=for-the-badge&logo=flutter&logoColor=white&labelColor=0D1117" alt="Flutter" />
  <img src="https://img.shields.io/badge/Dart-%5E3.9.2-0175C2?style=for-the-badge&logo=dart&logoColor=white&labelColor=0D1117" alt="Dart" />
  <img src="https://img.shields.io/badge/Material_3-UI_System-757575?style=for-the-badge&logo=materialdesign&logoColor=white&labelColor=0D1117" alt="Material 3" />
  <img src="https://img.shields.io/badge/Firebase_Auth-6.1.3-FFCA28?style=for-the-badge&logo=firebase&logoColor=black&labelColor=0D1117" alt="Firebase Auth" />
  <img src="https://img.shields.io/badge/Cloud_Firestore-6.1.1-FFA611?style=for-the-badge&logo=firebase&logoColor=black&labelColor=0D1117" alt="Cloud Firestore" />
</p>
<p>
  <img src="https://img.shields.io/badge/Google_Books_API-v1-4285F4?style=for-the-badge&logo=google&logoColor=white&labelColor=0D1117" alt="Google Books API" />
  <img src="https://img.shields.io/badge/HTTP_Client-1.6.0-0EA5E9?style=for-the-badge&logo=dart&logoColor=white&labelColor=0D1117" alt="HTTP" />
  <img src="https://img.shields.io/badge/SharedPreferences-2.5.4-38BDF8?style=for-the-badge&logo=flutter&logoColor=white&labelColor=0D1117" alt="SharedPreferences" />
  <img src="https://img.shields.io/badge/Android-Supported-3DDC84?style=for-the-badge&logo=android&logoColor=black&labelColor=0D1117" alt="Android" />
  <img src="https://img.shields.io/badge/iOS-Supported-000000?style=for-the-badge&logo=apple&logoColor=white&labelColor=0D1117" alt="iOS" />
</p>

</div>

---

## 📂 Project Structure · Proje Yapısı

```text
bookan-mobile-app/
├── android/                         # Android Gradle & FlutterFire configuration
├── ios/                             # iOS Runner & Bundle configuration
├── assets/
│   └── images/                      # App icon, brand logo & default profile avatar
├── lib/
│   ├── main.dart                    # App entry point, Material 3 theme & AuthKontrol
│   ├── firebase_options.dart        # FlutterFire generated Android/iOS options
│   ├── core/
│   │   └── constants/
│   │       └── colors.dart          # AppColors vintage palette (renk1..renk5)
│   ├── models/
│   │   └── book_model.dart          # BookModel JSON parser & HTTPS thumbnail mapper
│   ├── services/
│   │   ├── auth_service.dart        # Sign-in, registration, sign-out & password reset
│   │   ├── book_service.dart        # Google Books API v1 category & search client
│   │   └── firestore_service.dart   # Library CRUD, ratings, feed, comments & batch sync
│   └── views/
│       ├── auth/
│       │   ├── login_page.dart      # Login form, Remember Me & password reset dialog
│       │   └── register_page.dart   # Account creation screen
│       ├── navigation/
│       │   └── navigation_bar.dart  # MainScaffold 3-tab BottomNavigationBar
│       ├── home/
│       │   └── home_page.dart       # Search bar, 14 category chips & 2-column book grid
│       ├── book/
│       │   ├── book_detail.dart     # Cover, 5-star rating, read/fav/list actions & info
│       │   └── add_quote_page.dart  # Book-linked quote composer for Firestore feed
│       ├── quotes/
│       │   └── quotes_page.dart     # Live community quote feed, quick share & comments
│       └── profile/
│           ├── profile_page.dart    # Profile header, live stats, favorites, lists & settings
│           ├── read_books_page.dart # Completed books live list
│           ├── list_detail_page.dart# Custom list detail with swipe-to-remove & delete
│           └── my_quotes_page.dart  # User's own quotes with swipe-to-delete
├── test/
│   └── widget_test.dart             # Default Flutter widget test scaffold
├── firebase.json                    # FlutterFire CLI platform mapping
├── analysis_options.yaml            # flutter_lints static analysis configuration
└── pubspec.yaml                     # Dependencies, assets & launcher icon config
```

---

## 🚀 Getting Started · Kurulum ve Çalıştırma

### Prerequisites · Gereksinimler

- **Flutter SDK** (Dart SDK `^3.9.2`)
- **Android Studio** or **VS Code** with Flutter & Dart extensions
- An active **Firebase** project (Authentication: Email/Password + Cloud Firestore enabled)
- Optional: **FlutterFire CLI** (`dart pub global activate flutterfire_cli`)

### Installation & Run · Kurulum ve Başlatma

```bash
# 1. Clone the repository · Repoyu klonlayın
git clone https://github.com/yorukokan/bookan-mobile-app.git
cd bookan-mobile-app

# 2. Install Flutter dependencies · Bağımlılıkları yükleyin
flutter pub get

# 3. Configure Firebase for your own project (Android & iOS) · Firebase yapılandırmasını bağlayın
flutterfire configure

# 4. Run the application · Uygulamayı çalıştırın
flutter run
```

> **Note · Not:**
> - **EN:** `BookService` queries the public Google Books API v1 endpoint (`https://www.googleapis.com/books/v1/volumes`) without requiring a separate `.env` key. If you connect your own Firebase project, running `flutterfire configure` regenerates `lib/firebase_options.dart` and `android/app/google-services.json` (plus iOS configuration).
> - **TR:** `BookService`, Google Books API v1 genel uç noktasını (`https://www.googleapis.com/books/v1/volumes`) ayrı bir `.env` anahtarı gerektirmeden kullanır. Kendi Firebase projenizi bağlamak için `flutterfire configure` komutunu çalıştırarak `lib/firebase_options.dart` ve platform yapılandırma dosyalarını güncelleyebilirsiniz.

---

<div align="center">

<!-- Footer Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0C4A6E,45:0284C7,80:38BDF8,100:0EA5E9&height=100&section=footer" alt="Footer Banner" width="100%" />

<sub>⚡ <b>Okan Yörük</b> · Bookan Mobile App · <a href="https://github.com/yorukokan">github.com/yorukokan</a></sub>

</div>
