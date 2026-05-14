# 🌿 Akıllı Tarım: Derin Öğrenme Tabanlı Bitki Teşhis Sistemi

**Akıllı Tarım**, bitki hastalıklarını yaprak fotoğrafları üzerinden saniyeler içinde teşhis edebilen, internet bağımsız (offline) çalışan ve kenar bilişim (edge computing) odaklı bir yapay zeka projesidir.

🔗 **[Proje Tanıtım Sayfası ve Simülasyonu İçin Tıklayın](https://kcnsoftware.github.io/akilli-tarim-web/)**

---

## 🚀 Öne Çıkan Özellikler

* **Offline Analiz:** Hiçbir veri buluta gönderilmez. İnternetin çekmediği tarla koşullarında tam performans çalışır.
* **Donanım Optimizasyonu:** Intel i5-12450H işlemcinin **AVX2** ve **VNNI** komut setlerini kullanarak milisaniye seviyesinde tahmin hızı sunar.
* **36 Farklı Teşhis Sınıfı:** Farklı bitki türlerinde onlarca farklı patolojik durumu (hastalığı) yüksek doğrulukla ayırt edebilir.
* **Akıllı Sağlık Karnesi:** Modelin tahmin güvenini (Confidence Score) kullanıcıya dinamik bir bar ile gösterir ve ziraat literatürüne uygun tedavi önerileri sunar.

---

## 🛠️ Teknoloji Yığını

* **Dil:** Python
* **Yapay Zeka:** TensorFlow, Keras (CNN & Transfer Learning)
* **Arayüz & Arka Plan:** Flask (Web Framework)
* **Görüntü İşleme:** OpenCV, Pillow
* **Donanım Desteği:** Intel VNNI (Vector Neural Network Instructions)

---

## 📈 Çalışma Mantığı

1.  **Görüntü İşleme:** Yüklenen fotoğraf $224 \times 224$ piksel boyutuna normalize edilir.
2.  **Derin Analiz:** Evrişimli Sinir Ağı (CNN) katmanları yaprak üzerindeki leke ve deformasyonları tarar.
3.  **Hızlandırılmış Tahmin:** İşlemci üzerindeki AI hızlandırıcı birimler sayesinde analiz saniyeler içinde tamamlanır.
4.  **Raporlama:** Teşhis edilen hastalık adı, güven skoru ve ilk müdahale yöntemleri ekrana basılır.

---

## 🌍 Vizyon: Sürdürülebilir Gelecek

Bu projenin temel amacı:
* Yanlış ilaç kullanımını azaltarak **toprak kirliliğini önlemek**.
* Çiftçilerin maliyetlerini düşürerek **tarımsal verimliliği artırmak**.
* Teknolojiyi doğrudan üretim sahasına (tarlaya) indirmek.

---

## 👤 Geliştirici
**Kcn**
