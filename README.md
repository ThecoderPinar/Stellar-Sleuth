﻿# Astronomik Nesne Sınıflandırma Projesi


Bu proje, gözleme dayalı astronomik nesnelerin (yıldızlar, galaksiler ve kuasarlarda) spektral özelliklerine dayalı olarak sınıflandırılmasını içermektedir. Sloan Dijital Gökyüzü Taraması (SDSS) veri kümesi kullanılarak gerçekleştirilen bu proje, gözleme dayalı astronomi alanında önemli bir uygulamayı temsil etmektedir.

## Proje Amaçları

- Astronomik nesnelerin spektral özelliklerine dayalı olarak sınıflandırılması.
- Veri görselleştirmesi ile önemli ilişkilerin anlaşılması.
- K-Means kümeleme algoritması kullanılarak verinin kümelere ayrılması.

## Kullanılan Teknolojiler

Proje, aşağıdaki ana teknoloji ve araçları içermektedir:

- **Python**: Proje kodu Python programlama dili kullanılarak yazılmıştır.
- **Pandas**: Veri manipülasyonu ve analizi için Pandas kütüphanesi kullanılmıştır.
- **Seaborn ve Matplotlib**: Veriyi görselleştirmek için Seaborn ve Matplotlib grafik kütüphaneleri kullanılmıştır.
- **Scikit-Learn**: K-Means kümeleme modelini oluşturmak için Scikit-Learn kütüphanesi kullanılmıştır.
- **Jupyter Notebook**: Veri analizi ve kod geliştirme için Jupyter Notebook kullanılmıştır.

## Veri Kaynağı

Bu proje, 100.000 gözlem verisini içeren SDSS17 (Sloan Digital Sky Survey 17. veri sürümü) veri kümesini kullanmaktadır. Veri kümesi, farklı astronomik nesneleri tanımlayan 17 özellik sütunu içermektedir.

## Kurulum

1. Bu projeyi klonlayın:
git clone https://github.com/ThecoderPinar/Stellar-Sleuth


2. Proje dizinine gidin:
cd Stellar-Sleuth


3. Gereksinimleri yükleyin:
pip install -r requirements.txt



## Proje Yapısı

Proje dizini aşağıdaki dosyaları içermektedir:

,- `star_classification.csv`: SDSS17 veri kümesini içeren CSV dosyası.
- `README.md`: Proje açıklama dosyası (bu dosya).
- `requirements.txt`: Projeyi çalıştırmak için gerekli Python paketlerinin listesi.


## Kullanım

Proje kodunu çalıştırmak için aşağıdaki adımları izleyin:

1. `classification.ipynb` dosyasını çalıştırın:


## Lisans

Bu proje [MIT Lisansı](LICENSE) altında lisanslanmıştır.

---

Projeyle ilgili herhangi bir sorunuz veya geri bildiriminiz varsa, lütfen iletişime geçmekten çekinmeyin.
