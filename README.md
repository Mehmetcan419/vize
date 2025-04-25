# vize# 
El Hareketleri ile Ekran Parlaklığı Kontrolü
Bu projede, bilgisayar kamerasından alınan görüntü üzerinden **baş parmak** ile **işaret parmağı** arasındaki mesafe tespit edilerek, ekran parlaklığı otomatik olarak ayarlanır. 
El yumruk şeklindeyse parlaklık azalır, açık ise parlaklık artar.
---
Özellikler
- MediaPipe ile gerçek zamanlı el tespiti ve parmak ucu takibi
- OpenCV ile canlı video görüntüsü
- "screen_brightness_control" ile ekran parlaklığı ayarı için bu komutu kullandım.
- Python ile platform bağımsız çalışan sistem
## 🔧 Kurulum
### 1. Python Kurulumu
Proje Python 3.11 ile miniconda'dan aşağıdaki kütüphaneleri yükledim ve python 3.11 kullandım.
### 2. Gerekli Kütüphaneler
Projenin bulunduğu klasörde aşağıdaki komut ile gerekli tüm paketleri yükleyin:
# Aşağıdaki komutlar kütüphane kurulumu içindir.
```bash
pip install opencv-python
pip install mediapipe
pip install screen_brightness_control

