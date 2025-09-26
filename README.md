# asl_alphabet_project
# ASL Alphabet CNN Sınıflandırma Projesi

## Projenin Amacı
Bu proje, Amerikan İşaret Dili (ASL) alfabesindeki harfleri ve bazı özel sembolleri sınıflandırmak için bir Convolutional Neural Network (CNN) modeli geliştirmeyi amaçlamaktadır. Proje ile derin öğrenme, veri ön işleme, model geliştirme, değerlendirme ve yorumlama konularında pratik kazanılmıştır.

## Veri Seti
- **Veri:** [ASL Alphabet Dataset](https://www.kaggle.com/datasets/grassknoted/asl-alphabet)
- **İçindekiler:** 29 sınıf (26 harf + `space`, `del`, `nothing`)  
- **Örnek Sayısı:** Her sınıftan yaklaşık 1000 görsel kullanıldı (küçük dataset ile hızlı eğitim amacıyla)

## Kullanılan Yöntemler
1. **Veri Ön İşleme ve Augmentation**  
2. **CNN Modeli**  
3. **Model Eğitimi**  
4. **Model Değerlendirme**

## Elde Edilen Sonuçlar
- Model, test setinde yüksek doğruluk sağlandı ve overfitting gözlemlenmedi.  
- Her sınıfın performansı Confusion Matrix ve Classification Raporu ile analiz edildi.  
- Model küçük dataset ile hızlı çalışacak şekilde optimize edildi.  

## Kaggle Notebook
-https://www.kaggle.com/code/bilgeguler/asl-alphabet

---

