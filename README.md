# Tasarruf Finansman Hesaplayıcı

Türkiye'deki tasarruf finansman teklif örneklerine göre hazırlanmış, mobil uyumlu statik HTML hesaplayıcıdır.

## Özellikler

- Plan / tasarruf tutarı girişi
- Peşinat girişi
- Aylık ödeme girişi veya otomatik aylık ödeme tahmini
- Kullanıcının belirlediği ay sayısına göre sabit vadeli plan oluşturma
- Sayısal alanlarda otomatik Türkçe binlik ayırıcı maskesi
- Artışlı / artışsız ödeme planı seçimi
- Organizasyon ücreti hesaplama
- En iyi ve en kötü senaryo teslim / tahsisat ayı gösterimi
- Aylık ödeme planı tablosu
- Mobilde kart görünümü
- CSV çıktısı
- Yazdırılabilir ödeme planı

## Kullanım

Bu proje tek dosyalık statik bir uygulamadır. Bilgisayarında çalıştırmak için `index.html` dosyasını tarayıcıda açman yeterlidir.

Sonra tarayıcıdan şu adresi aç:

```text
https://tasarruf-finansman-hesaplayici.vercel.app/
```

## Önemli uyarı

Bu uygulama, örnek teklif PDF'lerindeki oran ve ödeme planı mantığına göre hazırlanmış tahmini bir hesaplayıcıdır. BDDK mevzuatı ve şirketlerin tip sözleşme çerçevesi dikkate alınsa da nihai teslim / tahsisat tarihi, ilgili tasarruf finansman şirketiyle imzalanacak sözleşmeye, müşteri ödeme performansına ve şirketin yürürlükteki tarifesine bağlı olarak değişebilir.

Organizasyon ücreti peşin tahsil edilebilir veya şirket tarifesine göre taksitlendirilebilir. Bu ücret, tasarruf birikimi gibi değerlendirilmemelidir.

## Lisans

MIT
