# CNN ile Gerçek Zamanlı Rakam Sınıflandırma Projesi

Bu proje, gerçek zamanlı rakam sınıflandırma için derin öğrenme ve bilgisayar görüşü tekniklerini kullanmaktadır. Projenin eğitim kısmı `mnist_opencv_cnn.py` dosyasında yer almakta olup, CNN modelini MNIST veri seti üzerinde eğitmektedir. Projenin kullanımı için `mnist_video_capture.py` dosyası kullanılarak gerçek zamanlı rakam tanıma işlemi gerçekleştirilebilir.


# Eğitim
Modeli eğitmek için aşağıdaki komutu çalıştırın:

`python mnist_opencv_cnn.py`

Bu komut, CNN modelini eğitecek ve ağırlıkları kaydedecektir.

# Gerçek Zamanlı Tanıma
Eğitilmiş modeli kullanarak gerçek zamanlı rakam tanıma yapmak için:

`python mnist_video_capture.py`
