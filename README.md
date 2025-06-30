# 📊 Bitcoin ve Ethereum Fiyat & Volatilite Analizi (2018–2025)

---

>## ⚠️ Uyarı
>❗️ **Bu çalışma, Python programlama dili kullanılarak veri analizi becerilerini geliştirmek amacıyla hazırlanmıştır.**  
>**Gerçek yatırım tavsiyesi içermez. Hiçbir ticari amaç taşımamaktadır.**

---

Bu projede, Bitcoin (BTC) ve Ethereum (ETH) kripto paralarının 2018–2025 yılları arasındaki fiyat hareketleri analiz edilmiştir.  
Amaç, bu iki dijital varlığın zaman serisi üzerinden fiyat, getiri, risk ve korelasyon ilişkisini incelemek ve ileriye dönük fiyat tahmini yapmaktır.

---

## 🔍 Proje İçeriği

- Günlük, aylık ve yıllık getiri hesaplamaları  
- Normalize fiyat karşılaştırmaları  
- Kümülatif getiri hesaplamaları  
- Günlük ve yıllık volatilite analizleri  
- Zamanla değişen oynaklık (rolling volatility)  
- BTC–ETH arasındaki korelasyon ve heatmap analizi  
- Zaman içinde korelasyon değişimi (rolling correlation)  
- Facebook Prophet ile ileriye dönük 180 günlük fiyat tahmini (BTC ve ETH)

---

## 📁 Kullanılan Teknolojiler

- Python  
- pandas, numpy, matplotlib, seaborn, plotly  
- yfinance  
- prophet (Facebook Prophet)

---

## 📥 Veri Kaynağı

Veriler `yfinance` kütüphanesi kullanılarak [Yahoo Finance](https://finance.yahoo.com/) üzerinden alınmıştır:

- **BTC-USD** → Bitcoin (USD bazında)
- **ETH-USD** → Ethereum (USD bazında)
- Tarih aralığı: `01.01.2018 – 01.07.2025`

---


## 👤 Hazırlayan

**Deniz Atabey**  

---
