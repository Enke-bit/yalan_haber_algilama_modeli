# Yalan Haber Algılama Modeli
Bu proje, yalan haberleri tespit etmek için NLTK ve lojistik regresyon (Logistic Regression) kullanarak geliştirilmiş bir model içerir. Model, haberlerin gerçek mi yoksa sahte mi olduğunu belirlemeye yönelik bir sınıflandırma yapmaktadır.

## Veri Kümesi
Kullanılan veri seti, aşağıdaki sütunları içermektedir:

- id: Bir haber makalesi için benzersiz kimlik.
- title: Haber makalesinin başlığı.
- author: Haber makalesinin yazarı.
- text: Makalenin metni (eksik olabilir).
- label: Haberlerin gerçek mi yoksa sahte mi olduğunu belirten etiket:
- 1: Sahte haberler
- 0: Gerçek haberler

## Kullanılan Kütüphaneler
Proje, aşağıdaki Python kütüphanelerini kullanmaktadır:

- numpy
- pandas
- re
- nltk (stopwords ve PorterStemmer)
- sklearn (TfidfVectorizer, train_test_split, LogisticRegression, accuracy_score)
- Model Performansı
- Eğitim Verisi Doğruluk Skoru: 0.9871
- Test Verisi Doğruluk Skoru: 0.9791
- Genel Yapı
- Veri Yükleme ve Ön İşleme:

## Metin verileri temizlenir ve ön işleme tabi tutulur.
TF-IDF vektörizasyonu kullanılarak metin özellikleri çıkarılır.
Model Eğitimi:

## Eğitim verisi kullanılarak lojistik regresyon modeli eğitilir.
Model Değerlendirme:

Modelin doğruluğu, hem eğitim hem de test veri setlerinde değerlendirilir.
 
 ## Lisans
Bu proje, lisans dosyasına uygun olarak lisanslanmıştır. Lisans bilgilerini okumak için lütfen lisans dosyasını kontrol ediniz.

## Destek
Herhangi bir sorunuz veya geri bildiriminiz varsa, lütfen GitHub üzerindeki sorunlar bölümünü kullanarak bize ulaşın. Yardımcı olmaktan memnuniyet duyarız!

## veri seti
https://www.kaggle.com/c/fake-news/data?select=train.csv 
linkden ulaşabilirsiniz.

