# Kübra Öztük - kbrztrk.kbr@gmail.com
# Proje Adı: Yan Etki Analizi
Bu proje, Olası yan etkilerin çeşitli özellikler ile arasındaki ilişkileri analiz etmeyi amaçlayan bir veri analizi çalışmasıdır.
## Gereksinimler
- Python 3.x
- Gerekli Python paketleri:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
## Veri Seti
- `Kullanici_id`: Kişiye ait benzersiz kimlik numarası (int64)
- `Cinsiyet`: Kişiye ait cinsiyet bilgisi (object)
- `Doğum_Tarihi`: Kişiye ait doğum tarihi (datetime64[ns])
- `Uyruk`: Kişiye ait uyruk (object)
- `Il`: Türkiye'ye ait iller (object)
- `Ilac_Adi`: Kişinin kullandığı ilacın adı (object)
- `Ilac_Baslangic_Tarihi`: Kişinin ilaç kullanmaya başladığı tarih (datetime64[ns])
- `Ilac_Bitis_Tarihi`: Kişinin ilaç kullanmayı bıraktığı tarih (datetime64[ns])
- `Yan_Etki`: İlaç kullanımına bağlı olarak ortaya çıkan yan etki (object)
- `Yan_Etki_Bildirim_Tarihi`: İlaç kullanımına bağlı olarak ortaya çıkan yan etkinin bildirilme tarihi (datetime64[ns])
- `Kronik Hastaliklarim`: Kişinin sahip olduğu kronik hastalıklar (object)
- `Baba Kronik Hastaliklari`: Kişinin babasının sahip olduğu kronik hastalıklar (object)
- `Anne Kronik Hastaliklari`: Kişinin annesinin sahip olduğu kronik hastalıklar (object)
- `Kiz Kardes Kronik Hastaliklari`: Kişinin kız kardeşinin sahip olduğu kronik hastalıklar (object)
- `Erkek Kardes Kronik Hastaliklari`: Kişinin erkek kardeşinin sahip olduğu kronik hastalıklar (object)
- `Alerjilerim`: Kişinin alerjileri (object)
- `Kan Grubu`: Kişinin kan grubu (object)
- `Kilo`: Kullanıcının kilosu (kg) (float64)
- `Boy`: Kullanıcının boyu (cm) (float64)
