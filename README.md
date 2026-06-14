# Hamming Error-Correcting Code Simulator

Bu proje, bilgisayar mimarisi ve bellek yönetimi konseptlerini görselleştirmek amacıyla geliştirilmiş, tarayıcı tabanlı interaktif bir **Hamming Kodu** simülatörüdür. 

Sistem, girilen veriler için eşlik (parity) bitlerini hesaplayarak belleğe yazar, kullanıcı tarafından yapay olarak oluşturulan veri bozulmalarını **Sendrom (Syndrome)** analizi ile tespit eder ve otomatik olarak onarır.

---

<img width="800" alt="arayuz" src="https://github.com/user-attachments/assets/d2a9b169-ccdd-48f8-86b2-0462c090d09e" />

## 🚀 Özellikler

- **Dinamik Veri Uzunluğu Desteği:** 8, 16 ve 32 bitlik veriler için matematiksel formüllere dayalı otomatik eşlik biti (parity bit) hesaplaması ve bellek bloğu oluşturma.
- **Görsel Bellek Yönetimi:** HTML5 Canvas API kullanılarak bellek bloklarının neon/siber temalı, interaktif ve dinamik gösterimi.
- **Yapay Hata Simülasyonu:** Kullanıcının bellek hücrelerine doğrudan tıklayarak (0 değerini 1, 1 değerini 0 yaparak) yapay veri bozulmaları (bit errors) oluşturabilmesi.
- **Sendrom (Syndrome) Analizi:** Hatalı bitin, arka planda uygulanan XOR işlemleriyle anında tespit edilmesi.
- **Otomatik Düzeltme (Corrector):** Tespit edilen hatalı bitin sistem tarafından otomatik olarak tersine çevrilerek orijinal verinin kurtarılması.
- **Canlı Sistem Logları:** Yapılan tüm işlemlerin, hesaplamaların ve hata tespit/düzeltme uyarılarının anlık olarak takip edilebildiği entegre terminal ekranı.

<img width="800" alt="hata" src="https://github.com/user-attachments/assets/f9e14bef-b638-4cee-996b-8f8e2c1c12ec" />

## 🛠️ Kullanılan Teknolojiler

- **HTML5 & CSS3:** Siber güvenlik / terminal konseptli, tamamen duyarlı (responsive) arayüz tasarımı.
- **JavaScript (Vanilla):** Hamming kodu algoritması, bit operasyonları ve DOM manipülasyonları.
- **Canvas API:** Bellek hücrelerinin dinamik çizimi ve etkileşim (click) olaylarının yönetimi.
- **Tipografi:** JetBrains Mono (Terminal ve kod okunabilirliğini artırmak için).

## ⚙️ Nasıl Çalıştırılır?

Proje tamamen istemci tarafında (client-side) çalışmaktadır ve herhangi bir paket yöneticisine veya sunucu kurulumuna ihtiyaç duymaz.

1. Proje dosyalarını bilgisayarınıza indirin veya klonlayın:
   ```bash
   git clone [https://github.com/KULLANICI_ADIN/hamming-code-simulator.git](https://github.com/KULLANICI_ADIN/hamming-code-simulator.git)
