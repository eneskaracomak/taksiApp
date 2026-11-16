# Yozgat 600 Evler Taksi — tek sayfa site

Statik site: `index.html` + `img/` + `robots.txt` + `sitemap.xml`. Derleme yok; klasörü olduğu gibi herhangi bir hostinge yükle.

- `images/` → WhatsApp'tan gelen orijinal fotoğraflar (yayına gerek yok)
- `img/` → web için küçültülmüş, SEO isimli fotoğraflar

## Yayına almadan önce değiştir

1. **Alan adı**: `https://www.yozgat600evlertaksi.com` her yerde yer tutucu. Gerçek alan adıyla değiştir
   (`index.html` canonical / og / JSON-LD, `robots.txt`, `sitemap.xml`).
2. **Adres ve harita**: Şu an "600 Evler Taksi Durağı, Yozgat Merkez" yazıyor ve harita arama sorgusuyla açılıyor.
   Durağın tam adresini yaz; Google Haritalar'da durağı bul → Paylaş → Harita yerleştir → iframe `src`'sini `#konum` içindeki iframe'e koy.
3. **Telefon**: Her yerde `0532 157 00 40` (`+905321570040`). Değişirse `index.html` içinde bu iki biçimi ara/değiştir.

## Google'da üste çıkmak için (siteden daha önemli)

1. **Google İşletme Profili** aç (business.google.com): ad "600 Evler Taksi", kategori "Taksi servisi",
   aynı telefon, 7/24 saat, fotoğraflar, site linki. Haritalarda "yozgat taksi" aramalarını bu getirir.
2. Müşterilerden **Google yorumu** iste — sıralamada en etkili şey.
3. **Google Search Console**'a siteyi ekle, `sitemap.xml`'i gönder.
4. Ad / adres / telefon her yerde (site, Google, Instagram, kartvizit) **birebir aynı** olsun.
5. Instagram / Facebook sayfası varsa siteye link ver, siteden de oraya.
