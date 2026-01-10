# Heart Disease Veri Analizi Projesi

Bu proje, Veri Analizi dersi kapsamında dönem boyunca öğrenilen teorik bilgilerin pratiğe dökülmesi amacıyla hazırlanmıştır.

## Veri Seti
Projede Kaggle platformundan alınan **Heart Disease Dataset** kullanılmıştır.  
Veri seti, bireylerin çeşitli sağlık ölçümlerine göre kalp hastalığına sahip olup olmadığını göstermektedir.

## Problem Tanımı
Bu proje bir **sınıflandırma (classification)** problemidir.  
Amaç, verilen özellikler kullanılarak bir bireyin kalp hastalığına sahip olup olmadığını (`target` değişkeni) tahmin etmektir.

## Kullanılan Yöntemler
- Veri keşfi ve ön işleme (EDA)
- Eksik veri ve temel istatistik analizi
- Veri görselleştirme
- StandardScaler ile veri ölçeklendirme
- Logistic Regression modeli ile sınıflandırma
- Model değerlendirme:
  - Accuracy
  - Confusion Matrix
  - Classification Report

## Sonuçlar
Kurulan Logistic Regression modeli test verisi üzerinde yaklaşık **%79.5 doğruluk (accuracy)** elde etmiştir.  
Elde edilen sonuçlar, seçilen değişkenlerin kalp hastalığı tahmininde anlamlı bir katkı sağladığını göstermektedir.

## Kullanılan Araçlar
- Python
- Jupyter Notebook (Anaconda)
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
