# Yapay Zeka ile Bilgisayarlı Görü

Bu repo, bilgisayarlı görü üzerine çeşitli konuları içeren projeleri ve uygulamaları kapsamaktadır. Yapay zeka teknikleriyle, bilgisayarlı görü alanındaki çeşitli görevleri çözmek için TensorFlow, Keras, OpenCV gibi araçlar kullanılmıştır. Her klasör, belirli bir konu başlığını ve o konuya ait projeleri içerir.

## İçindekiler

1. [Introduction to Computer Vision](#introduction-to-computer-vision)
2. [Keras Callbacks API](#keras-callbacks-api)
3. [Fire Detection](#fire-detection)
4. [Hyperparameter Tuning](#hyperparameter-tuning)
5. [OpenCV DNN](#opencv-dnn)
6. [Keras OCR](#keras-ocr)
7. [MediaPipe](#mediapipe)
8. [Autoencoder](#autoencoder)

---

### 1. Introduction to Computer Vision

Bu bölüm, bilgisayarlı görüye giriş niteliğinde olup, temel sınıflandırma modelleri ve çeşitli veri setleri ile çalışmayı kapsamaktadır.

- **Datasets**: Farklı veri setleri ile deneyler yapmayı içerir (ör. kedi-köpek sınıflandırma).
- **Models**: Önceden eğitilmiş modellerle sınıflandırma işlemleri.
- ### Model Results

| Model   | Prediction          | Confidence |
|---------|---------------------|------------|
| ResNet50| cabbage_butterfly    | 0.782488   |
| VGG16   | cabbage_butterfly    | 0.83566654 |
| VGG19   | cabbage_butterfly    | 0.9452888  |

- **Data Augmentation**: Görüntülerin çeşitli tekniklerle çoğaltılması ve bu görüntüler üzerinde model eğitimi yapılması.

<p align="center">
  <img src="https://github.com/user-attachments/assets/92930af8-3e91-4233-823f-2c4eab7e4dbe" alt="image" width="350"/>
  <img src="https://github.com/user-attachments/assets/f0704e33-9fd0-43e0-b367-2ff01e9eff83" alt="image" width="350"/>
</p>



---

### 2. Keras Callbacks API

Bu bölümde, Keras'ın `Callback` fonksiyonlarını kullanarak model eğitimi esnasında çeşitli işlemleri nasıl otomatikleştirebileceğinizi öğrenirsiniz. `TensorBoard` ile eğitim sürecini görselleştirmek için loglar tutulmaktadır.

- **Logs**: Eğitim ve doğrulama verileri ile TensorBoard logları.
- **Models**: Eğitim sırasında elde edilen modeller.

---

### 3. Fire Detection

Bu proje, yangın tespiti için derin öğrenme modellerinin kullanılmasını içerir. Veriler, yangın ve yangın olmayan görüntüler şeklinde sınıflandırılarak model eğitimi gerçekleştirilmiştir.

- **Dataset**: Yangın ve normal durumlar için eğitim ve doğrulama verileri.
- **Models**: Eğitim sonucu elde edilen yangın tespit modelleri.
- **Results**: Model sonuçları ve performans raporları.
<p align="center">
  <img src="https://github.com/user-attachments/assets/528b1cc1-9b5a-4064-9fc8-4bec0900c2c3" alt="image" width="350"/>
  </p>
- **Test**: Test verileri üzerinde denemeler.

---

### 4. Hyperparameter Tuning

Bu bölüm, model performansını iyileştirmek için hiperparametre optimizasyonu üzerine odaklanmaktadır. Hiperparametre ayarlarının farklı denemeler ile optimize edilmesi hedeflenmiştir.

- **Datasets**: Kedi-köpek veri seti kullanılarak yapılan eğitim ve test verileri.
- **Models**: Hiperparametre ayarları ile optimize edilmiş modeller.
- **Parameter Tuning**: Farklı hiperparametre denemeleri (trial_0, trial_1, trial_2).

---

### 5. OpenCV DNN

Bu klasör, OpenCV'nin Derin Sinir Ağı (DNN) modülünü kullanarak görüntü ve video verilerinin analiz edilmesi üzerine odaklanmaktadır. Sınıflandırma, nesne tespiti, derinlik tahmini gibi konular ele alınmıştır.

- **Classification**: Görüntü sınıflandırma işlemleri.
- **Object Detection**: Görüntü ve videolarda nesne tespiti.


<p align="center">
  <img src="https://github.com/user-attachments/assets/6dc15890-7834-4457-a1cf-b73f0862bd88" alt="image3" width="200"/>
  <img src="https://github.com/user-attachments/assets/c2bbe40f-5792-40a9-8427-a0d906df7b7d" alt="image4" width="200"/>
</p>


- **Depth Estimation**: Derinlik tahmini modelleri.
- **Face Detection**: Yüz tespiti ve analizi.

---

### 6. Keras OCR

Bu projede, Keras kullanarak optik karakter tanıma (OCR) işlemleri gerçekleştirilmiştir. Görüntülerdeki metinleri tanımak ve çıkartmak için eğitimli modeller kullanılmıştır.
<p align="center">
  <img src="https://github.com/user-attachments/assets/5f861022-21b0-4868-b262-e19581dc3cc0" alt="image" width="350"/>
  </p>

---

### 7. MediaPipe

Google'ın geliştirdiği MediaPipe kütüphanesi kullanılarak, görüntü işleme ve bilgisayarlı görü uygulamaları gerçekleştirilmiştir. Bu kütüphane, el ve yüz takibi gibi çeşitli görevlerde kullanılmıştır.

---

### 8. Autoencoder

Bu bölüm, otomatik kodlayıcılar (autoencoder) kullanarak veri sıkıştırma ve veri temsili öğrenme konularını kapsamaktadır. Otomatik kodlayıcılar, görüntülerin boyutunu küçültmek veya gürültüyü gidermek amacıyla kullanılır.
<p align="center">
  <img src="https://github.com/user-attachments/assets/489121b3-889f-4b67-a133-9c0d3d88009c" alt="image" width="350"/>
  </p>

---

## Kurulum

Projeyi klonladıktan sonra gerekli Python paketlerini kurmak için:

```bash
git clone https://github.com/kullanici/yapay_zeka_bilgisayarli_goru.git
cd yapay_zeka_bilgisayarli_goru
pip install -r requirements.txt
