# Veri-Bilimi-Python
# 🚢 Titanic Veri Seti ile Hayatta Kalma Tahmini

Bu proje, Titanic kazasına ait yolcu verileri üzerinden **veri analizi**, **görselleştirme** yapılmasını amaçlamaktadır. Proje kapsamında veri ön işleme, keşifsel veri analizi (EDA), görselleştirme ve modelleme adımları gerçekleştirilmiştir.

---

## 📁 Veri Seti

Kaggle’ın en çok bilinen klasik veri setlerinden biri olan **Titanic: Machine Learning from Disaster** veri seti kullanılmıştır.

| Değişken    | Açıklama                                   |
|-------------|---------------------------------------------|
| `PassengerId` | Yolcu numarası                           |
| `Survived`    | Hayatta kalma durumu (0 = Hayır, 1 = Evet)|
| `Pclass`      | Bilet sınıfı (1, 2, 3)                    |
| `Name`        | Yolcunun adı                             |
| `Sex`         | Cinsiyet                                  |
| `Age`         | Yaş                                       |
| `SibSp`       | Gemideki kardeş/eş sayısı                |
| `Parch`       | Gemideki ebeveyn/çocuk sayısı           |
| `Ticket`      | Bilet numarası                            |
| `Fare`        | Bilet ücreti                              |
| `Cabin`       | Kamara numarası                           |
| `Embarked`    | Biniş limanı (C = Cherbourg, Q = Queenstown, S = Southampton) |

---

## 🛠 Kullanılan Araçlar

- Python 3
- pandas, numpy
- seaborn, matplotlib
- scikit-learn

---

## 🔍 Proje Adımları

### 1. Veri Temizleme & Ön İşleme
- Eksik verilerin (`Age`, `Cabin`, `Embarked`) doldurulması
- Kategorik değişkenlerin sayısal hale getirilmesi (`Label Encoding`, `One-Hot Encoding`)
- Yeni değişkenler türetme (örneğin: `FamilySize = SibSp + Parch + 1`)

### 2. Keşifsel Veri Analizi (EDA)
- Cinsiyet, yaş, sınıf, biniş limanı gibi değişkenlerin hayatta kalma oranı ile ilişkisi incelendi.
- Korelasyon analizi ve sayısal verilerin dağılımları analiz edildi.

### 3. Görselleştirme
- `seaborn` ve `matplotlib` ile grafikler:
  - Yaşa göre hayatta kalma dağılımı
  - Cinsiyet-sınıf hayatta kalma ilişkisi
  - Pclass ile Fare ilişkisi


