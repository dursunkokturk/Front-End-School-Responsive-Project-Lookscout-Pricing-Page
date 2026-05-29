# TR
# Lookscout — Web Uygulaması Açılış Sayfası
Lookscout markası için tasarlanmış, saf HTML ve CSS kullanılarak geliştirilmiş tam duyarlı bir kurumsal açılış sayfası. Navigasyon, özellik kartları, blog yazıları, müşteri yorumu ve footer gibi tüm temel bölümleri kapsar.

## Canlı Önizleme

Projeyi deploy ettikten sonra linki buraya ekleyin.


## Özellikler

- Duyarlı Navigasyon — Mobil/tablette hamburger menü, masaüstünde tam menü çubuğu
- Hero Bölümü — Destekçi marka logolarıyla birlikte CTA ve açıklayıcı metin
- 6 Özellik Kartı — İkon, başlık ve bağlantıyla iş organizasyonu, analitik, entegrasyon gibi başlıklar
- Koşullu Görsel — Masaüstünde farklı, mobil/tablette farklı klavye görseli (CSS active / not-active sınıfları ile)
- Karanlık Bölümler — #151B28 arka planlı özellikler ve footer alanları
- Blog Kartları — Mobilde 1, tablette 2, masaüstünde 3 sütunlu ızgara; üçüncü kart mobilden gizlenir
- Müşteri Yorumu — Avatar, isim ve unvanla birlikte alıntı bölümü
- E-posta Abonelik Formu — Güvenlik, destek ve anlaşma onay ikonlarıyla birlikte
- Footer — Kaynaklar ve Ürünler bağlantıları, e-posta girişi ve sosyal medya ikonları
- Saf HTML & CSS — JavaScript veya harici kütüphane kullanılmaz


## Duyarlı Düzenler
, > , , 

| Ekran    | Genişlik         | Öne Çıkan Değişiklikler                             |
| -------- |------------------| ----------------------------------------------------|
| Mobil    | 375px Varsayılan | Tek sütun, Hamburger menü                           |
| Tablet   | > 767px          | 2 sütunlu grid, Gizli üçüncü blog kartı             |
| Masaüstü | > 1109px         | 3 sütunlu grid, tam navbar, koşullu görsel değişimi |


## Teknolojiler

| Teknoloji    | Açıklama                                   |
| ------------ |--------------------------------------------|
| HTML5        | Semantik sayfa yapısı                      |
| CSS3         | Grid, Flexbox, @media sorguları            |
| Google Fonts | Inter yazı ailesi                          |

## Proje Yapısı
lookscout/
├── index.html
└── assets/
    ├── css/
    │   └── lookscout.css
    └── img/
        ├── avatars/
        │   ├── avatar.png
        │   ├── avatar-man.png
        │   └── avatar-woman.png
        ├── icons/
        │   ├── icon-organization.png
        │   ├── icon-process.png
        │   ├── icon-analize.png
        │   ├── icon-connection.png
        │   ├── icon-integration.png
        │   ├── icon-workflow.png
        │   ├── icon-explere.png
        │   ├── icon-bulb.png
        │   ├── icon-ship.png
        │   ├── icon-check.png
        │   └── icon-right.png
        ├── logos/
        │   ├── logo-company.png
        │   ├── logo-company-dark.png
        │   ├── logo-gitlab.png
        │   ├── logo-slack.png
        │   ├── logo-slack-black.png
        │   ├── logo-netflix.png
        │   ├── logo-paypal.png
        │   ├── logo-paypal-blue.png
        │   ├── logo-verge.png
        │   ├── logo-google.png
        │   ├── logo-google-letter.png
        │   ├── logo-pinterest.png
        │   ├── logo-mailchimp.png
        │   ├── logo-facebook.png
        │   ├── logo-apple.png
        │   └── logo-instagram.png
        ├── wall.png
        ├── wall-computer.png
        ├── photo-grass.png
        ├── photo-radiator.png
        ├── photo-desk-chair.png
        ├── burger-menu.png
        └── chevron-down.png

🚀 Kurulum
Proje herhangi bir bağımlılık gerektirmez. Klonladıktan sonra doğrudan tarayıcıda açabilirsiniz.
bash# Repoyu klonlayın
git clone https://github.com/kullanici-adi/lookscout-landing.git

# Proje klasörüne girin
cd lookscout-landing

# index.html dosyasını tarayıcıda açın
open index.html

🎨 Tasarım Detayları

Renk Paleti:

#2663FD — Ana mavi (navbar, hero arka planı)
#437EF7 — Açık mavi (butonlar, bağlantılar)
#151B28 — Koyu lacivert (karanlık bölümler, footer)
#5F6D7E — Gri (gövde metni)
#A5ACBA — Açık gri (karanlık arka plan metinleri)


Font: Inter
