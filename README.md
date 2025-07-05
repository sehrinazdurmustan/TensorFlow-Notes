# TensorFlow Fashion MNIST Görüntü Sınıflandırma

Bu proje, TensorFlow kullanarak Fashion MNIST veri seti ile görüntü sınıflandırma yapan bir derin öğrenme uygulamasıdır.

## 📋 Proje İçeriği

- **Veri Seti**: Fashion MNIST (28x28 piksel, 10 kategori)
- **Model**: Sequential Neural Network (Dense katmanlar)
- **Kategoriler**: T-shirt, Pantolon, Kazak, Elbise, Palto, Sandal, Gömlek, Sneaker, Çanta, Bot

## 🛠️ Teknolojiler

- **TensorFlow 2.x**
- **NumPy**
- **Matplotlib**
- **Python 3.7+**

## 📊 Model Mimarisi

```python
model = tf.keras.Sequential([
    tf.keras.layers.Flatten(input_shape=(28, 28)),
    tf.keras.layers.Dense(128, activation='relu'),
    tf.keras.layers.Dense(10)
])
```

## 🎯 Performans

- **Eğitim Doğruluğu**: ~%90
- **Test Doğruluğu**: ~%87
- **Epoch Sayısı**: 10

## 🚀 Nasıl Çalıştırılır

1. Gerekli kütüphaneleri yükleyin:
```bash
pip install tensorflow numpy matplotlib
```

2. Jupyter Notebook'u açın:
```bash
jupyter notebook
```

3. `Görüntü Sınıflandırma.ipynb` dosyasını çalıştırın

## 📁 Dosya Yapısı

```
TensorFlow Notes/
├── Görüntü Sınıflandırma.ipynb
├── README.md
└── .gitignore
```

## 📚 Öğrenilen Konular

- Derin öğrenme temelleri
- TensorFlow/Keras kullanımı
- Görüntü ön işleme
- Model eğitimi ve değerlendirme
- Softmax aktivasyon fonksiyonu
- Adam optimizer

## 👨‍💻 Geliştirici

Bu proje, TensorFlow öğrenme sürecimin bir parçasıdır.

## 📄 Lisans

Bu proje eğitim amaçlıdır ve açık kaynak kodludur.
