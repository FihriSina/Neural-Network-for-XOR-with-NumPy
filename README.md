# Neural Network for XOR with NumPy

This project implements a basic neural network using only NumPy to solve the XOR logic problem. It demonstrates key concepts of neural networks including forward propagation, backpropagation, and weight updates.

## Features

* 2-input, 2-hidden, 1-output layer neural network
* Sigmoid activation function and its derivative
* Manual implementation of forward and backward propagation
* Mean Squared Error (MSE) loss function
* XOR dataset training and evaluation

## File

* `ann_assignment.py`: The complete neural network implementation, including training loop and output.

## How to Run

1. Install the required dependency:

   ```bash
   pip install numpy
   ```

2. Run the Python script:

   ```bash
   python ann_assignment.py
   ```

## Example Output

After training, the network predicts values close to the expected XOR outputs:

```
Input: [0, 0] -> Prediction: ~0.01
Input: [0, 1] -> Prediction: ~0.98
Input: [1, 0] -> Prediction: ~0.98
Input: [1, 1] -> Prediction: ~0.02
```

## Purpose

This project is intended as a learning tool to understand how neural networks function at a low level, without using machine learning libraries like TensorFlow or PyTorch.

## Notes

* All weights and biases are initialized randomly.
* You can experiment with the learning rate and number of training epochs to observe their effect on training performance.

## Resources

* [NumPy Documentation](https://numpy.org/doc/)
* [Artificial Neural Network - Wikipedia](https://en.wikipedia.org/wiki/Artificial_neural_network)
* [XOR Gate - Wikipedia](https://en.wikipedia.org/wiki/XOR_gate)

---


# NumPy ile XOR için Yapay Sinir Ağı

Bu proje, yalnızca NumPy kullanılarak XOR mantık problemini çözmek üzere basit bir yapay sinir ağı uygular. Proje, ileri yayılım (forward propagation), geri yayılım (backpropagation) ve ağırlık güncellemeleri gibi temel yapay sinir ağı kavramlarını göstermektedir.

## Özellikler

* 2 girişli, 2 gizli nöronlu, 1 çıkışlı ağ mimarisi
* Sigmoid aktivasyon fonksiyonu ve türevi
* İleri ve geri yayılım algoritmalarının manuel uygulanması
* Ortalama Kare Hata (MSE) ile kayıp hesaplama
* XOR veri kümesi üzerinde eğitim ve değerlendirme

## Dosya

* `ann_assignment.py`: Eğitim döngüsü ve çıktılar dahil olmak üzere tüm sinir ağı uygulamasını içerir.

## Nasıl Çalıştırılır

1. Gerekli bağımlılığı yükleyin:

   ```bash
   pip install numpy
   ```

2. Python dosyasını çalıştırın:

   ```bash
   python ann_assignment.py
   ```

## Örnek Çıktı

Eğitim tamamlandıktan sonra ağ aşağıdaki gibi tahminler üretir:

```
Girdi: [0, 0] -> Tahmin: ~0.01
Girdi: [0, 1] -> Tahmin: ~0.98
Girdi: [1, 0] -> Tahmin: ~0.98
Girdi: [1, 1] -> Tahmin: ~0.02
```

## Amacı

Bu proje, makine öğrenmesi kütüphaneleri (TensorFlow, PyTorch vb.) kullanmadan yapay sinir ağlarının nasıl çalıştığını daha iyi anlamak için öğrenim amacıyla hazırlanmıştır.

## Notlar

* Tüm ağırlıklar ve biaslar rastgele başlatılır.
* Öğrenme oranı ve epoch sayısı gibi hiperparametreleri değiştirerek performans üzerindeki etkilerini gözlemleyebilirsiniz.

## Kaynaklar

* [NumPy Belgeleri](https://numpy.org/doc/)
* [Yapay Sinir Ağı - Vikipedi](https://tr.wikipedia.org/wiki/Yapay_sinir_a%C4%9F%C4%B1)
* [XOR Kapısı - Vikipedi](https://tr.wikipedia.org/wiki/XOR_kap%C4%B1s%C4%B1)

---


