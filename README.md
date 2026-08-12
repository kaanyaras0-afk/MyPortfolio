# Kaan Yaraş - Portfolyo Web Sitesi

Bilgisayar Mühendisliği öğrencisi olarak projelerimi, özgeçmişimi ve iletişim bilgilerimi sergilemek için hazırladığım kişisel portfolyo web sitesi.

## 🔗 Canlı Demo
👉 [https://kaanyaras0-afk.github.io/MyPortfolio/](https://kaanyaras0-afk.github.io/MyPortfolio/)

## 📋 Özellikler
- **Duyarlı (responsive) navigasyon menüsü** — küçük ekranlarda hamburger menüye dönüşen mobil uyumlu tasarım
- **Aktif menü renklendirme** — sayfada hangi bölümdeysen ilgili menü öğesi otomatik olarak renklenir, tıklandığında da renkli kalır
- **Yumuşak kaydırma (smooth scroll)** — menüye tıklayınca sayfa ilgili bölüme aniden zıplamak yerine yumuşak şekilde kayar
- **Portfolyo bölümü** — GitHub projelerine doğrudan yönlendiren, üzerine gelince efekt gösteren proje kartları
- **Hakkımda bölümü** — kısa özgeçmiş
- **İletişim formu** (şimdilik sadece arayüz, backend'e bağlı değil)
- **Tam duyarlı tasarım** — mobil, tablet ve masaüstü ekranlarda uyumlu çalışır

## 🛠️ Kullanılan Teknolojiler
- **HTML5** — sayfa yapısı
- **CSS3** — özel stiller, medya sorgularıyla duyarlı tasarım
- **JavaScript (jQuery)** — mobil menü açma/kapama, aktif menü takibi, kaydırma algılama
- **[Font Awesome](https://fontawesome.com/)** — ikonlar
- **Google Fonts** — Lato ve Montserrat

## 📁 Proje Yapısı
```
├── index.html      # Ana sayfa HTML yapısı
├── stylee.css      # Stil ve düzen dosyası
└── images/         # Profil fotoğrafı ve proje görselleri
```

## ✨ Aktif Menü Renklendirme Nasıl Çalışıyor?
Küçük bir jQuery script'i iki olayı dinliyor:
1. **Tıklama** — bir menü linkine tıklandığında, hemen `active-link` sınıfı o linke ekleniyor.
2. **Kaydırma** — kullanıcı sayfayı kaydırdıkça, script hangi `<section>`'ın görünür olduğunu kontrol ediyor ve ilgili menü öğesine otomatik olarak `active-link` sınıfını ekliyor.

`active-link` sınıfı `stylee.css` içinde tanımlanmış ve linkin rengini değiştirerek hangi bölümde olduğuna dair net bir görsel geri bildirim veriyor.

## 📌 Bölümler
- **Portfolio** — GitHub projelerinin sergilendiği bölüm
- **About** — özgeçmiş ve kısa tanıtım
- **Contact** — basit bir iletişim formu

## 📧 İletişim
Sitedeki iletişim formu ya da footer'daki sosyal medya bağlantıları üzerinden ulaşabilirsiniz.

## 📄 Lisans
Bu proje inceleme ve öğrenme amaçlı açık bir şekilde paylaşılmıştır. Kodları incelemekten çekinme.

---
*Frontend web geliştirme öğrenme sürecimin bir parçası olarak geliştirilmiştir.*
