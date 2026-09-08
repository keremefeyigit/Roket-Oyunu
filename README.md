# 🚀 HTML5 Roket & Radar Hedef Kilitlenme Oyunu

[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![HTML5 Canvas](https://img.shields.io/badge/HTML5-Canvas-orange.svg)](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
[![Security: Hardened](https://img.shields.io/badge/Security-Hardened%20(CSP%20%2B%20XSS%20Safe)-brightgreen.svg)](#-güvenlik-standartları)
[![License: CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg)](LICENSE)

HTML5 Canvas ve saf JavaScript (ES6+) kullanılarak geliştirilmiş, 2D dinamik fizik motoru, 360° döner radar tarama mekaniği ve hedef kilitlenme simülasyonu sunan interaktif bir tarayıcı oyunudur.

---

## 🎮 Oyun Özellikleri

- **360° Döner Radar Sistemi:** Gerçek zamanlı tarama çizgisi, dinamik mesafe halkaları ve blip hedef izleme.
- **Ekran Dışı Hedef Tespiti:** Görüş açısının dışındaki hedefler için dinamik vektör okları ve anlık mesafe ($m$) göstergesi.
- **Parazit & Savunma Karşı Tedbirleri:** Düşman uçağının kaçış manevraları, radar parazitleri ve flare efektleri.
- **Dinamik Sarsıntı & Fizik:** Ateşleme, ivmelenme ve patlama anlarında ekran sarsıntısı (Screen Shake) ve vektörel itki simülasyonu.
- **Lider Tablosu:** En iyi 5 pilot skorunun yerel depolamada saklandığı güvenli skor tablosu.

---

## 🛡️ Güvenlik Standartları

Proje public kullanıma sunulurken güvenlik sıkılaştırmasından geçirilmiştir:
- **XSS (Cross-Site Scripting) Koruması:** Kullanıcı girdileri ve lider tablosu `innerHTML` yerine güvenli DOM manipülasyonu ve `textContent` ile sanitize edilerek işlenir.
- **CSP (Content Security Policy):** Sayfa başlığında tanımlı sıkı Content Security Policy ile zararlı betik yürütmeleri ve `'unsafe-eval'` direktifleri engellenmiştir.
- **Yerel ve İstemci Tabanlı:** Harici şüpheli kütüphaneler içermez, tamamen izole ve güvenli çalışır.

---

## 🛠️ Teknolojiler

- **Programlama Dili:** Saf JavaScript (Vanilla ES6+)
- **Grafik Motoru:** HTML5 2D Canvas API
- **Stil & Tasarım:** Saf CSS3 (Retro Radar UI)
- **Bağımlılık:** Sıfır dış bağımlılık (Zero dependency)

---

## 🚀 Nasıl Çalıştırılır?

Projeyi çalıştırmak için herhangi bir paket yöneticisine veya sunucuya ihtiyaç yoktur:
1. Repoyu bilgisayarınıza indirin veya klonlayın:
   ```bash
   git clone https://github.com/keremefeyigit/roket-oyunu.git
   ```
2. `index.html` dosyasını herhangi bir modern web tarayıcısında (Chrome, Firefox, Safari, Edge) çift tıklayarak açın.

---

## 📜 Lisans ve Telif Hakları

Bu proje **Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0)** lisansı ile korunmaktadır.

- **İndirme ve Oynama Serbesttir:** Projeyi kişisel/eğitim amaçlı olarak bilgisayarınıza indirebilir, kodları inceleyebilir ve yerel olarak oynayabilirsiniz.
- **Değiştirme ve Yeniden Dağıtım Yasaktır:** Proje kodları üzerinde değişiklik yapılması, çatallanıp türev projeler üretilmesi veya değiştirilmiş sürümlerin dağıtılması yasaktır.
- **Ticari Kullanım Yasaktır:** Kodlar veya materyaller hiçbir şekilde ticari amaçla satılamaz veya gelir getiren servislerde kullanılamaz.

Detaylar için [LICENSE](LICENSE) dosyasına göz atabilirsiniz.
