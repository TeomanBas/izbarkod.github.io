# İZ Barkod – tek sayfalık statik site

## İçerik
- index.html: Sayfa içeriği, metinler, bağlantılar
- style.css: Renkler, tasarım, mobil uyum
- script.js: Alt bilgi yılını günceller
- assets/afis.png: Gönderdiğiniz tanıtım görseli
- assets/favicon.svg: Tarayıcı sekmesi simgesi

## Yayına alma
Bu klasörün içindeki dosyaları (index.html dahil) Apache `htdocs` veya Nginx `root` dizinine kopyalayın. Dosya dizin yapısını koruyun. PHP, Node.js, Composer veya veritabanı gerekmez.

Test: `python3 -m http.server 8080` ile açıp `http://localhost:8080` adresini ziyaret edin.

## Özelleştirme
Telefon numarası / WhatsApp numarası / konum / web adresi için `index.html` içindeki ilgili metin ve `tel:`, `wa.me` bağlantılarını düzenleyin.
Renkler için `style.css` başındaki `:root` değişkenlerini kullanın.

Not: 7/24 destek ifadesi tanıtım görselinden alınmıştır. Gerçek hizmet saatleri farklıysa bu ifadeyi güncelleyin. WhatsApp bağlantısı, görseldeki GSM numarasının WhatsApp'ta kayıtlı olduğu doğrulanmadan hazırlanmıştır.
