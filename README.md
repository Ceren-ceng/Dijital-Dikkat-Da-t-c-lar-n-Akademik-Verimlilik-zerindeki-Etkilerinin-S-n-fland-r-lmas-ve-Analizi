# Dijital Dikkat Dağıtıcıların Akademik Verimlilik Üzerindeki Etkilerinin Sınıflandırılması ve Analizi

Bu proje, öğrencilerin akademik verimliliği ile dijital dikkat dağıtıcılar arasındaki ilişkiyi veri analizi ve makine öğrenmesi yöntemleri kullanarak incelemek amacıyla geliştirilmiştir. Çalışmada aynı veri seti üzerinde iki farklı yaklaşım uygulanmıştır:

- **Regresyon analizi**
- **Kümeleme (Clustering) analizi**

Amaç, dijital dikkat dağıtıcıların akademik performans ve verimlilik üzerindeki etkilerini hem **tahminleme** hem de **örüntü keşfi** açısından değerlendirmektir.

---

## Proje Amacı

Günümüzde öğrencilerin çalışma süreçleri; sosyal medya, telefon kullanımı, ekran süresi, odak kaybı ve dijital alışkanlıklar gibi birçok dikkat dağıtıcı unsurdan etkilenmektedir. Bu proje kapsamında:

- öğrencilerin verimlilik durumlarını etkileyen faktörler analiz edilmiş,
- ilgili değişkenler arasındaki ilişkiler incelenmiş,
- regresyon modeli ile belirli bir hedef değişken tahmin edilmeye çalışılmış,
- kümeleme yöntemi ile benzer özelliklere sahip öğrenci profilleri gruplandırılmıştır.

Bu yönüyle çalışma, hem **denetimli öğrenme (supervised learning)** hem de **denetimsiz öğrenme (unsupervised learning)** yaklaşımını bir arada içermektedir.

---

## Kullanılan Yaklaşımlar

### 1. Regresyon Analizi
Regresyon bölümünde, veri setindeki bağımsız değişkenler kullanılarak öğrencilerin akademik verimlilik ya da ilişkili hedef değişkenlerinin tahmin edilmesi amaçlanmıştır.

Bu analiz ile:
- değişkenler arasındaki doğrusal/doğrusal olmayan ilişkiler gözlemlenmiş,
- model performansı değerlendirilmiş,
- tahmin başarısı üzerinden veri setinin yapısı yorumlanmıştır.

### 2. Kümeleme Analizi
Kümeleme bölümünde öğrenciler benzer özelliklerine göre gruplandırılmıştır. Böylece veri setinde doğal olarak oluşan profiller keşfedilmiştir.

Bu analiz ile:
- öğrenciler benzer davranış kalıplarına göre segmentlere ayrılmış,
- kümeler arasındaki temel farklılıklar incelenmiş,
- dikkat dağıtıcılık ve verimlilik ilişkisi keşifsel veri analizi kapsamında değerlendirilmiştir.

---

## Veri Seti Hakkında

Projede aşağıdaki veri seti kullanılmıştır:

- `student_productivity_distraction_dataset_20000.csv`

Bu veri seti, öğrencilerin akademik verimliliği ile dijital dikkat dağıtıcılar arasındaki ilişkiyi incelemek amacıyla oluşturulmuş gözlemler içermektedir. Veri setindeki değişkenler, öğrencilerin çalışma alışkanlıkları, dikkat düzeyleri, görev tamamlama durumları ve dijital dikkat dağıtıcı maruziyetleri gibi alanlara odaklanmaktadır.

Veri seti üzerinde yapılan işlemler genel olarak şunlardır:

- veri okuma
- ön inceleme
- eksik/veri tipi kontrolü
- görselleştirme
- modelleme
- sonuçların yorumlanması

---

## Proje Dosya Yapısı

Projede yer alan temel dosyalar aşağıda verilmiştir:

### Notebook Dosyaları
- `regresyon.ipynb`  
  Regresyon analizinin gerçekleştirildiği Jupyter Notebook dosyasıdır.

- `kümeleme.ipynb`  
  Kümeleme analizinin gerçekleştirildiği Jupyter Notebook dosyasıdır.

### Veri Dosyaları
- `student_productivity_distraction_dataset_20000.csv`  
  Projede kullanılan ana veri setidir.

- `ogrenci_kumeleme_sonuclari.csv`  
  Kümeleme analizi sonucunda, her gözlemin ait olduğu küme bilgisini içeren çıktı dosyasıdır.

---

## Kullanılan Teknolojiler ve Kütüphaneler

Bu projede Python tabanlı veri bilimi ve makine öğrenmesi araçları kullanılmıştır. Kullanılan temel teknolojiler şunlardır:

- **Python**
- **Jupyter Notebook**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn** (kullanıldıysa)
- **Scikit-learn**

> Not: Eğer notebook içinde farklı kütüphaneler kullanıldıysa bu liste proje içeriğine göre güncellenebilir.

---

## Uygulama Adımları

Projede genel olarak şu adımlar izlenmiştir:

1. Veri setinin içe aktarılması
2. Veri setinin genel yapısının incelenmesi
3. Gerekli ön işleme adımlarının uygulanması
4. Değişken ilişkilerinin analiz edilmesi
5. Regresyon modelinin kurulması ve değerlendirilmesi
6. Kümeleme algoritmasının uygulanması
7. Küme sonuçlarının yorumlanması
8. Sonuçların görselleştirilmesi ve dışa aktarılması

---

## Nasıl Çalıştırılır?

### 1. Depoyu klonlayın
```bash
git clone https://github.com/Ceren-ceng/Dijital-Dikkat-Dagiticilarin-Akademik-Verimlilik-uzerindeki-Etkilerinin-Siniflandirilmasi-ve-Analizi.git
