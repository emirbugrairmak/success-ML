# English

In this project, I developed a basic machine learning model that predict whether students pass or fail base on their scores.

## Steps:
- I analysed the data and calculated the average score.
- If the average score was 60 or higher, the student was labelled "passed".Otherwise, the student labelled "failed".
- I converted the categorial data into the numeric data.
- In the model, 'average_score' was not included in training. It was only used for labelling.
- I split the data into training and test sets.
- I trained a classification model by using `LogisticRegression`.
- I measured model's accuracy with `accuracy_score`.

## Technologies Used:
- Python
- Pandas
- Scikit-learn
- Google Colab

## Goal:
I developed this project to learn and apply basics of the supervised learning.





# Türkçe

Bu projede, öğrencilerin sınav performanslarına göre dersten geçip geçmeyeceklerini tahmin eden basit bir makine öğrenmesi modeli geliştirdim.

## Kullanılan Adımlar:
- Veriyi inceledim ve ortalama başarı puanı (`average_score`) hesapladım.
- Ortalama 60 ve üzeri olan öğrencileri "başarılı" (1), diğerlerini "başarısız" (0) olarak etiketledim.
- Kategorik verileri sayısal verilere dönüştürdüm (gender, race/ethnicity vb.).
- `average_score` modelde öğrenmeye dahil edilmedi, sadece etiket için kullanıldı.
- Veriyi eğitim ve test seti olarak böldüm.
- `LogisticRegression` kullanarak sınıflandırma modeli eğittim.
- Modelin doğruluk oranı `accuracy_score` ile ölçüldü.

## Kullanılan Teknolojiler:
- Python
- Pandas
- Scikit-learn
- Google Colab

## Amaç:
Bu projeyi, denetimli öğrenmenin temel kavramlarını (veri hazırlama, etiketleme, model eğitme ve değerlendirme) öğrenmek ve uygulamak için geliştirdim.
