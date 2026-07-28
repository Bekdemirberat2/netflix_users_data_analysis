📊 Netflix Subscriber Data - Exploratory Data Analysis (EDA)

Bu proje, Netflix kullanıcı veri seti üzerinden US, Spain ve Canada pazarlarını kapsayan; abonelik tipi, cihaz tercihi, yaş/cinsiyet dağılımı ve finansal metrikleri içeren kapsamlı bir analizdir.

📌 Bölgesel Analiz Özetleri

1. United States (US)

. Abonelik Tipi: Basic plan lider konumdadır.
. Yaş ve Cinsiyet: Erkek kullanıcı sayısı kadınlardan fazladır. Ortalama yaş 38, standart sapma 7’dir.
. Cihaz Tercihi: Sıralama: Laptop, Smartphone, Tablet, Smart TV.
. Finansal Veriler: Ortalama ödeme süresi 324 gün (Standart sapma: 114). Beklenen ortalama gelir 4022 $(Standart sapma: 1515$).


2. Spain

. Abonelik Tipi: Premium plan en çok tercih edilen türdür.

. Yaş ve Cinsiyet: Kadın kullanıcı sayısı erkeklerden fazladır. Ortalama yaş 38, standart sapma 7’dir.

. Cihaz Tercihi: Sıralama: Smart TV, Tablet, Laptop, Smartphone.

. Finansal Veriler: Ortalama ödeme süresi 320 gün (Standart sapma: 114). Beklenen ortalama gelir 4021 $(Standart sapma: 1552$).


3. Canada

. Abonelik Tipi: Basic plan ağırlıktadır; ardından Premium ve Standart planlar gelir.

. Yaş ve Cinsiyet: Erkek kullanıcı sayısı kadınlardan fazladır. Ortalama yaş 38, standart sapma 7’dir.

. Cihaz Tercihi: Sıralama: Tablet, Smartphone, Smart TV, Laptop.

. Finansal Veriler: Ortalama ödeme süresi 323 gün (Standart sapma: 114). Beklenen ortalama gelir 4014 $(Standart sapma: 1506$).

🚫 PROJE KAPANIŞI VE YATIRIM KARARI
Kapsam: Belirlenen üç ana pazar (US, Spain, Canada) detaylı şekilde analiz edilmiştir.

⚠️ TEKNİK NOT: VERİ SETİ HAKKINDA

Analiz edilen veri setinin genelinde (tüm ülkelerde), standart sapma ve ortalama değerlerinin ülkeler arasında birbirini tekrar ettiği, verilerin organik dağılım göstermediği tespit edilmiştir. 
Veri setinin sentetik (yapay üretilmiş) olması nedeniyle, ek bölgelerin analiz edilmesinin istatistiksel bir değeri bulunmamaktadır. 
Proje bu aşamada sonlandırılmıştır.

#Projeyi İndirmek İçin:

Bash

#1. Projeyi Klonlayın Öncelikle bu depoyu yerel makinenize çekin:

git clone https://github.com/Bekdemirberat2/netflix_users_data_analysis
cd netflix_users_data_analysis

#2. Sanal Ortam Oluşturun ve Aktif Edin (Tavsiye Edilen) Projelerin kütüphane bağımlılıklarının temiz kalması için bir sanal ortam oluşturun:

Bash

Windows için: python -m venv venv venv\Scripts\activate

macOS / Linux için: python3 -m venv venv source venv/bin/activate

#3. Gerekli Kütüphaneleri Yükleyin

Projede analiz, veri manipülasyonu ve görselleştirme için kullanılan tüm bağımlılıkları tek tıkla kurun:

Bash pip install -r requirements.txt

#4. Jupyter Notebook'u Başlatın

Her şey hazır olduğunda analiz dosyasını açmak için yerel sunucuyu tetikleyin:

Bash jupyter notebook Açılan tarayıcı ekranından proje dosyanıza (.ipynb) tıklayarak tüm kod bloklarını sırasıyla (Shift + Enter) çalıştırabilir, makroekonomik analizlerin ve grafiklerin üretim sürecini canlı olarak gözlemleyebilirsiniz.
