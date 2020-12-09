# Uzun vadeli temettü yatırımcılığı için düzenlenmiş bir Excel dosyası

Bu dosya, kendi uzun vadeli temettü yatırımcılığı sürecime ait tüm verilerimin takibi için oluşturulmuştur. 
Twitter'daki takipçilerimin talebi üzerine burdan paylaşılmıştır. 

[DOSYAYI İNDİR](https://github.com/finansal-ozgur/temettu_excel/blob/master/temettu_paylasim.xlsm?raw=true)

[ORNEK GRAFİK DOSYASI](https://github.com/finansal-ozgur/temettu_excel/blob/master/ornek_grafik.xlsx?raw=true)

## Özellikler

#### Portföy 

Bu sekmede tüm portöye ait özet bilgiler yer almaktadır. Birçok veri hesaplanarak otomatik doldurulmaktadır. 
Mevcut lot sayısı, maliyet, kar bilgileri tamamen otomatik hesaplanmaktadır. 

- Mavi bölgede hisse bilgileri ve kar zarar bilgileri yer almaktadır. 
- Yeşil bölgede birçok parametreye göre alım sıralaması hesaplanmaktadır. Uymak zorunda değilsiniz. 
- Sarı bölgede ise özet temettü bilgileri yer almaktadır. 
- Aşağıdaki butonlu kısımda tarih değiştirilerek o tarihteki portföy görüntülenebilir. 
- Alış ve Satış işlemleri aşağıdaki butonlarla yapılabilmektedir. Sil butonları ise son işlemi silmek için koyuldu. Simülasyon yapmak için kullanabilirsiniz. 
- Altta kalan yeşil bölgede ise hisselerin sektöre ve gruplara göre dağılımı gösterilmektedir. 

#### Alımlar ve Satımlar

Bu sekmede tüm hisse senedi alım/satım işlemleri yer almaktadır. Portföy sekmesindeki alım/satım butonu bu tabloya veri eklemektedir. 
Bu veri ise birçok hesaplama için kullanılmaktadır. Bu sekme de manuel yapılacak tek işlem vardır. 
Son satırda silinebilir alanına H yazdıgınızda sil butonu çalışmaz. Simülasyon dısındaki gercek işlemleriniz için bunu yapabilirsiniz. 
Böylece hata yapma şansı kalmaz. 

#### Temettüler

Bu sekmede hisseler için açıklanan temettü verileri girilmelidir. Tarih, Hisse ve Brüt temettü dısında giriş yapmanıza gerek yok. 
Sadece bazı hisselerde stopaj oranı %15 dısında ise özel net kısmına net temettü tutarını yazabilirsiniz. 

#### Aylık Rapor

Burası otomatik değil. Manuel olarak aylık diger sekmelerden kopyalıyorum. 

#### Parametreler

Bu sekmede hesaplamalarda kullanılan komisyon gibi bazı bilgiler yer almaktadır. Kendinize göre giriş yapabilirsiniz. 

## Sık Sorulan Sorular

##### Kendi hisse senetlerimi nereye yazacagım?
Portfoydeki 16 hisse senedi yerine kendi hisselerinizi yazabilirsiniz. Gerektikçe satır ekleyebilir veya silebilirsiniz. 
Birçok alan sizin hisselerinize göre otomatik düzenlenecektir. 

##### Mevcut alım/satım işlemlerimi nasıl girecegim?
Alım satım sekmelerindeki tablolara toplu veri yapışıtarabilirsiniz. Formata uyun yeter. 

##### Güncel fiyatlar nasıl alınıyor?
Güncelle butonuna bastığınız zaman isyatirim'dan çekmeye çalışıyor. Bazen hata alabiliyor. 
