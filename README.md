# İdare Hukuku Sınav Sistemi

Bu proje, "Kamusal Alan İdare Hukuku" kitabının 171-220 sayfaları için interaktif sınav soruları içermektedir.

## Özellikler

### 📚 Soru Türleri
- **Çoktan Seçmeli:** 5 şıklı sorular
- **Doğru/Yanlış:** İki seçenekli sorular  
- **Boşluk Doldurma:** Metin tamamlama soruları

### 🎯 Sınav Sistemi Özellikleri
- Her sayfa için özel hazırlanmış sorular
- Kaynak görsel ile soru eşleştirmesi
- Anında geri bildirim ve açıklama
- LocalStorage ile ilerleme takibi
- Başarı oranı hesaplama
- Rastgele soru seçimi

### 🖥️ Teknik Özellikler
- Responsive tasarım (mobil uyumlu)
- Modern CSS3 ve JavaScript
- LocalStorage veri saklama
- Navigasyon sistemli sayfa geçişleri

## Dosya Yapısı

```
/Users/web3alkan/Desktop/idare/
├── index.html                 # Ana sayfa
├── style.css                  # CSS stilleri
├── soru-171.html             # Soru sayfaları (171-220)
├── soru-172.html
├── ...
├── soru-220.html
├── generate_questions.py     # Soru üretim scripti
├── generate_all_questions.py # Toplu üretim scripti
└── README.md                 # Bu dosya
```

## Soru Dağılımı

**Toplam:** 50 Soru (Sayfa 171-220)

**Konu Başlıkları:**
- Kamulaştırma Usul ve İlkeleri
- Lehe Kamulaştırma  
- Satın Alma Usulünün Denenmesi
- İdari Şerh İşlemleri
- Mahkeme Süreci
- Vazgeçme ve Geri Alma
- İdari Yargı Süreci
- İdare Hukuku Genel İlkeleri

## Kullanım

1. `index.html` dosyasını web tarayıcısında açın
2. Soru kartlarından istediğiniz soruyu seçin
3. Soruyu yanıtlayın ve sonucu görün
4. İlerlemeniz otomatik olarak kaydedilir

## Soru Özellikleri

### Çoktan Seçmeli Sorular
- 5 seçenekli (A, B, C, D, E)
- Tek doğru cevap
- Seçenekler karıştırılmış
- Açıklayıcı geri bildirim

### Doğru/Yanlış Soruları  
- İki seçenekli (Doğru/Yanlış)
- İfade bazlı sorular
- Kavramsal anlayış testi

### Boşluk Doldurma
- Tek kelime/sayı cevapları
- Büyük/küçük harf duyarsız
- Enter tuşu ile cevaplama

## İlerleme Takibi

- Tamamlanan sorular yeşil renkte
- Yanlış cevaplanan sorular kırmızı renkte  
- Başarı oranı hesaplama
- Toplam istatistikler
- İlerleme sıfırlama seçeneği

## Teknik Detaylar

- **Frontend:** HTML5, CSS3, JavaScript (ES6+)
- **Veri Saklama:** LocalStorage API
- **Tasarım:** Responsive Grid Layout
- **Tarayıcı Desteği:** Modern tarayıcılar
- **Çoklu Dil:** Türkçe

## Geliştirici Notları

Sorular, sayfa içeriklerine göre özel olarak hazırlanmış ve İdare Hukuku müfredatına uygun olarak tasarlanmıştır. Her soru, ilgili sayfanın kaynak görseliyle birlikte sunularak öğrenme deneyimi güçlendirilmiştir.

## Lisans

Bu proje eğitim amaçlı olarak hazırlanmıştır.