# TR
# Lookscout — Web Uygulaması Açılış Sayfası
Lookscout markası için tasarlanmış, saf HTML ve CSS kullanılarak geliştirilmiş tam duyarlı bir kurumsal açılış sayfası. Navigasyon, özellik kartları, blog yazıları, müşteri yorumu ve footer gibi tüm temel bölümleri kapsar.

## Canlı Önizleme

[Projeyi deploy edildikten sonra canlı önizlemesi.](https://dursunkokturk.github.io/Front-End-School-Responsive-Project-Lookscout-Pricing-Page/)


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
lookscout/ <br>
├── index.html <br>
└── assets/ <br>
    ├── css/ <br>
    │   └── lookscout.css <br>
    └── img/ <br>
        ├── avatars/ <br>
        │   ├── avatar.png <br>
        │   ├── avatar-man.png <br>
        │   └── avatar-woman.png <br>
        ├── icons/ <br>
        │   ├── icon-organization.png <br>
        │   ├── icon-process.png <br>
        │   ├── icon-analize.png <br>
        │   ├── icon-connection.png <br>
        │   ├── icon-integration.png <br>
        │   ├── icon-workflow.png <br>
        │   ├── icon-explere.png <br>
        │   ├── icon-bulb.png <br>
        │   ├── icon-ship.png <br>
        │   ├── icon-check.png <br>
        │   └── icon-right.png <br>
        ├── logos/ <br>
        │   ├── logo-company.png <br>
        │   ├── logo-company-dark.png <br>
        │   ├── logo-gitlab.png <br>
        │   ├── logo-slack.png <br>
        │   ├── logo-slack-black.png <br>
        │   ├── logo-netflix.png <br>
        │   ├── logo-paypal.png <br>
        │   ├── logo-paypal-blue.png <br>
        │   ├── logo-verge.png <br>
        │   ├── logo-google.png <br>
        │   ├── logo-google-letter.png <br>
        │   ├── logo-pinterest.png <br>
        │   ├── logo-mailchimp.png <br>
        │   ├── logo-facebook.png <br>
        │   ├── logo-apple.png <br>
        │   └── logo-instagram.png <br>
        ├── wall.png <br>
        ├── wall-computer.png <br>
        ├── photo-grass.png <br>
        ├── photo-radiator.png <br>
        ├── photo-desk-chair.png <br>
        ├── burger-menu.png <br>
        └── chevron-down.png <br>

## Kurulum
Proje herhangi bir bağımlılık gerektirmez. Klonladıktan sonra doğrudan tarayıcıda açabilirsiniz.
bash# Repoyu klonlayın
git clone https://github.com/kullanici-adi/lookscout-landing.git

### Proje klasörüne girin
cd lookscout-landing

### index.html dosyasını tarayıcıda açın
open index.html

## Tasarım Detayları

- Renk Paleti:

    - #2663FD — Ana mavi (navbar, hero arka planı)
    - #437EF7 — Açık mavi (butonlar, bağlantılar)
    - #151B28 — Koyu lacivert (karanlık bölümler, footer)
    - #5F6D7E — Gri (gövde metni)
    - #A5ACBA — Açık gri (karanlık arka plan metinleri)


- Font: Inter
