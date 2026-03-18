# 🏗️ İnşaat Pro

**Gayrimenkul & İnşaat Proje Analiz Uygulaması** — Tek sayfalık, PWA destekli mobil uygulama.

## ✨ Özellikler

| Modül | Açıklama |
|---|---|
| 📋 Proje & Parsel | İl/İlçe seçimi, ada-parsel, TAKS/KAKS otomatik hesap |
| 🏘️ Yapı Tipi & KK | 6 yapı tipi, kat karşılığı hesabı, arsa/müteahhit payı |
| 🎯 Optimizer | Max Değer / Max Adet / Dengeli daire dağılım optimizasyonu |
| 🏗️ 3D Kesit | Canvas tabanlı gerçek zamanlı bina kesit görünümü |
| 🗺️ Harita | Leaflet/OpenStreetMap ile konum seçimi ve arama |
| 📊 SWOT + ROI | Otomatik proje güçlü/zayıf analizi + ROI hesabı |
| 🎮 Simülatör | Basit (slider) ve Pro (enflasyon/faiz dahil) modları |
| 📚 Rehber | TAKS, KAKS, Kat Karşılığı, Deprem Yön., Ruhsat... |
| 📤 Çıktı | Yazdır, WhatsApp, CSV export, link paylaşım, Ana ekrana ekle |
| 📅 Timeline | Otomatik proje zaman planı (7 aşama) |

## 🚀 Kullanım

```bash
# 1. Klonla
git clone https://github.com/kullanici-adi/insaat-pro.git

# 2. Bir klasör aç ve çalıştır (herhangi bir web sunucu)
cd insaat-pro
npx serve .
# veya dosyayı direkt tarayıcıda aç
open index.html
```

## 📱 PWA – Ana Ekrana Ekleme

- **Android Chrome:** Sağ üst menü → "Ana ekrana ekle"
- **iOS Safari:** Paylaş → "Ana Ekrana Ekle"
- **Desktop Chrome:** URL çubuğundaki install ikonu

## 🛠️ Teknolojiler

- Vanilla HTML/CSS/JavaScript (sıfır bağımlılık)
- [Leaflet.js](https://leafletjs.com/) — harita
- [OpenStreetMap](https://openstreetmap.org/) — harita verisi
- [Nominatim API](https://nominatim.openstreetmap.org/) — geocoding
- Google Fonts: Syne + DM Sans

## 🌓 Tema / Dil

- 🌙 Dark / ☀️ Light mod
- 🇹🇷 Türkçe / 🇬🇧 English
- 🎓 Uzman / 🟢 Basit mod

## 📄 Lisans

MIT License — Özgürce kullanın, forklayın, geliştirin.
