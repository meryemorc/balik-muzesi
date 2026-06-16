# 🐠 Balık Müzesi AR

**ELSAM — Elazığ Su Ürünleri Araştırma Enstitüsü**  
Yazılım Mühendisliği Güncel Konular Dersi | 2026

[![GitHub Pages](https://img.shields.io/badge/Demo-Canli-brightgreen)](https://meryemorc.github.io/balik-muzesi)
[![Durum](https://img.shields.io/badge/Durum-Tamamlandi-brightgreen)]()
[![THS](https://img.shields.io/badge/THS-9-blue)]()

---

## 📌 Proje Hakkında

Bu proje, ELSAM Balık Müzesi ziyaretçilerinin müzedeki kitap sayfalarını telefonlarıyla okutarak **3D hayvan modelleri** ve bilgiler görebileceği bir **Web AR (Artırılmış Gerçeklik)** uygulamasıdır.

- ✅ Uygulama indirmeye gerek yok — tarayıcıdan çalışır
- ✅ iPhone Safari ve Android Chrome'da çalışır
- ✅ QR kod ile anında erişim
- ✅ 10 farklı deniz ortamı, 10 farklı 3D model
- ✅ 10 kategorili, 40 sorulu quiz modülü
- ✅ GitHub Pages ile HTTPS üzerinden yayında

---

## 🚀 Canlı Demo

```
https://meryemorc.github.io/balik-muzesi
```

---

## 🛠️ Kullanılan Teknolojiler

| Teknoloji | Versiyon | Görev |
|-----------|----------|-------|
| HTML5 / CSS3 / JavaScript | — | Temel web altyapısı |
| A-Frame | 1.4.2 | 3D model render ve AR sahnesi |
| MindAR.js | 1.2.5 | Kitap sayfası tanıma (Image Tracking) |
| Three.js | 0.150.0 | Serbest AR modu 3D render |
| GitHub Pages | — | Ücretsiz HTTPS yayınlama |
| Sketchfab | — | Ücretsiz 3D model kaynağı (.glb) |

---

## 📁 Proje Yapısı

```
balik-muzesi/
├── index.html                    # Ana menü (grid tasarım, 4 tema grubu)
├── quiz.html                     # Quiz senaryosu (10 kategori, 40 soru)
├── hakkinda.html                 # Proje ve ekip hakkında
├── serbest.html                  # Serbest AR modu (kamerasız 3D)
│
├── # 🧊 Soğuk Sular
├── kuzey-kutup.html              # Katil balina modeli
├── guney-kutup.html              # Penguen modeli
│
├── # 🐠 Tropikal Sular
├── mercan-resifi.html            # Palyaço balığı modeli
├── acik-deniz.html               # Kambur balina modeli
├── akvaryum.html                 # Yunus modeli
│
├── # 🌑 Gizemli Derinlikler
├── derinlerde.html               # Köpekbalığı modeli
├── kayip-sehir.html              # Ahtapot modeli
├── gemi-batigi.html              # Beyaz köpekbalığı modeli
│
├── # 🌿 Yeşil Sular
├── su-alti-ormani.html           # Deniz samuru modeli
├── deniz-cayiri.html             # Deniz ineği modeli
│
├── # Image Target Dosyaları
├── MercanResifiTargets.mind
├── AçıkDenizTargets.mind
├── KuzeykutupTargets.mind
├── GüneykutupTargets.mind
├── DerinlerdeTargets.mind
├── kayıpsehirTargets.mind
├── gemiBatıgıTargets.mind
├── SuALtıOTargets.mind
├── DenizTabanıTargets.mind
├── AkvaryumdaTargets.mind
│
└── # 3D Modeller (.glb)
    ├── clownfish.glb
    ├── realistic_shark.glb
    ├── white_shark_from_depth.glb
    ├── humpback_whale.glb
    ├── orca__killer_whale.glb
    ├── dolphin.glb
    ├── sky_otter.glb
    ├── manatee.glb
    ├── thorny_octopus.glb
    └── african_penguin_spheniscus_demersus_low_poly.glb
```

---

## 🎯 Tamamlanan Senaryolar

| # | Senaryo | Açıklama | Durum |
|---|---------|----------|-------|
| S1 | Kitap Sayfası Okutma | 10 sayfa → 10 farklı 3D model + bilgi paneli | ✅ Tamamlandı |
| S2 | Quiz Modülü | 10 kategori, 40 soru, skor ekranı | ✅ Tamamlandı |
| S3 | Ana Menü Navigasyonu | 4 tema grubu, 10 ortam kartı | ✅ Tamamlandı |
| S4 | Serbest AR Modu | Kamerasız, su altı arka planlı 3D model sahnesi | ✅ Tamamlandı |

---

## 👥 Ekip ve Sorumluluklar

| İsim | No | Görev | Ölçülebilir Sorumluluk |
|------|----|-------|------------------------|
| **İslim Öcalan** | 225541081 | AR Geliştirici | 10 .mind dosyası, MindAR entegrasyonu, 10 HTML sayfası, bilgi paneli JS kodu |
| **Ece Bahar** | 225541014 | 3D Model & İçerik | 10 .glb model temini, scale/pozisyon ayarları, kitap fotoğrafları, bilgi metinleri |
| **Deniz Yalçın** | 225541017 | Quiz & İçerik | 10 kategori 40 soru, quiz.html geliştirme, geri bildirim mekanizması, skor ekranı |
| **Meryem Oruç** | 225541059 | Proje Yöneticisi | GitHub yönetimi, GitHub Pages deploy, ana menü tasarımı, test koordinasyonu, PR review |

---

## 📱 Nasıl Kullanılır?

1. Müzedeki **QR kodu** telefon kamerasıyla okut
2. Tarayıcı otomatik açılır — uygulama indirme gerekmez
3. Ana menüden bir **ortam** seç (Mercan Resifi, Kuzey Kutup vb.)
4. **Kamera iznine** izin ver
5. Telefonu **kitap sayfasına** tut
6. **3D model** belirir ve bilgi paneli açılır!

---

## 📄 Dökümanlar

| Döküman | Açıklama |
|---------|----------|
| `docs/SWOT.pdf` | SWOT Analizi |
| `docs/RAMS.pdf` | RAMS Analizi (Reliability, Availability, Maintainability, Safety) |
| `docs/THS_report.pdf` | Teknik Hazırlık Seviyesi Raporu (THS-9) |
| `docs/Requirements.pdf` | Gereksinim Dökümanı (FR + NFR + Ekip Sorumlulukları) |
| `docs/UserScenario.pdf` | Kullanıcı Senaryoları (4 Use Case) |

---

## ✅ Proje Durumu

| Kriter | Hedef | Sonuç |
|--------|-------|-------|
| Sayfa tanıma başarısı | Min. %80 | ✅ Geçti |
| Cihaz uyumluluğu | iPhone + Android | ✅ Geçti |
| Quiz soruları | Min. 40 soru | ✅ 40 soru |
| AR ortam sayısı | Min. 10 | ✅ 10 ortam |
| HTTPS yayın | Zorunlu | ✅ GitHub Pages |
| QR erişim | Maks. 3 adım | ✅ Geçti |

---

*ELSAM Balık Müzesi AR | Yazılım Mühendisliği Güncel Konular | 2026*
