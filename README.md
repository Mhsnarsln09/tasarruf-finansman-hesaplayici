# Tasarruf Finansman Hesaplayıcı

Türkiye'deki tasarruf finansman teklif örneklerine göre hazırlanmış, mobil uyumlu statik HTML hesaplayıcıdır.

## Özellikler

- Plan / tasarruf tutarı girişi
- Peşinat girişi
- Aylık ödeme girişi veya otomatik aylık ödeme tahmini
- Artışlı / artışsız ödeme planı seçimi
- Organizasyon ücreti hesaplama
- En iyi ve en kötü senaryo teslim / tahsisat ayı gösterimi
- Aylık ödeme planı tablosu
- Mobilde kart görünümü
- CSV çıktısı
- Yazdırılabilir ödeme planı

## Kullanım

Bu proje tek dosyalık statik bir uygulamadır. Bilgisayarında çalıştırmak için `index.html` dosyasını tarayıcıda açman yeterlidir.

Yerel sunucu ile çalıştırmak istersen:

```bash
python3 -m http.server 8080
```

Sonra tarayıcıdan şu adresi aç:

```text
http://localhost:8080
```

## GitHub'a yükleme

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/KULLANICI_ADI/tasarruf-finansman-hesaplayici.git
git push -u origin main
```

GitHub CLI kullanıyorsan:

```bash
gh repo create tasarruf-finansman-hesaplayici --public --source=. --remote=origin --push
```

## GitHub Pages yayına alma

1. GitHub reposunda **Settings** sekmesine gir.
2. **Pages** menüsünü aç.
3. **Build and deployment** bölümünde **Deploy from a branch** seç.
4. Branch olarak `main`, klasör olarak `/root` seç.
5. Kaydet.

Birkaç dakika sonra GitHub Pages linki aktif olur.

## Önemli uyarı

Bu uygulama, örnek teklif PDF'lerindeki oran ve ödeme planı mantığına göre hazırlanmış tahmini bir hesaplayıcıdır. BDDK mevzuatı ve şirketlerin tip sözleşme çerçevesi dikkate alınsa da nihai teslim / tahsisat tarihi, ilgili tasarruf finansman şirketiyle imzalanacak sözleşmeye, müşteri ödeme performansına ve şirketin yürürlükteki tarifesine bağlı olarak değişebilir.

Organizasyon ücreti peşin tahsil edilebilir veya şirket tarifesine göre taksitlendirilebilir. Bu ücret, tasarruf birikimi gibi değerlendirilmemelidir.

## Lisans

MIT
# tasarruf-finansman-hesaplayici
