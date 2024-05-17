# Face-Expression-Classification-with-CNN
Bu proje, derin öğrenme kullanarak insan yüz ifadelerini sınıflandırmayı amaçlamaktadır. Proje kapsamında, iki yüz ifadesini ayırt etmek için bir Convolutional Neural Network (CNN) modeli geliştirilmiş ve eğitilmiştir. Model, Kaggle'da bulunan "Face Expression Recognition Dataset" kullanılarak eğitilmiştir.

Tüm kodlamalar Jupyter Notebook ortamında yapılmıştır. 
Aşağıdaki adımlar takip edilmiştir:
İlk Model Eğitimi: Dropout veya data augmentation uygulanarak, 50 epoch boyunca eğitilen CNN modeli için train ve validation accuracy grafikleri çizdirilmiş ve yorumlanmıştır.
Dropout Uygulaması: Sadece dropout uygulanarak model tekrar eğitilmiş ve grafikleri çizdirilmiştir.
Data Augmentation: Sadece data augmentation uygulanarak model tekrar eğitilmiş ve grafikleri çizdirilmiştir.
Dropout ve Augmentation Uygulanmadan: Hem dropout hem de data augmentation uygulanmadan model tekrar eğitilmiş ve grafikleri çizdirilmiştir.
En Başarılı Modelin Seçilmesi: Tüm modellerin performansları karşılaştırılarak en başarılı model seçilmiştir.
Modelin Test Edilmesi: En başarılı model, PC kamerası veya mobil cihaz kamerası ile test edilmiştir. Model, gerçek zamanlı olarak yüz ifadelerini tanımlamaktadır.
