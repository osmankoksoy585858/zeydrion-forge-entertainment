# Zeydrion Forge Entertainment — web sitesi

## Dosyalar
- `index.html`: Ana sayfa
- `style.css`: Siyah/kırmızı tasarım ve mobil uyumluluk
- `script.js`: Mobil menü ve otomatik yıl
- `CNAME`: Özel alan adı yapılandırması

## GitHub Pages ile yayınlama
1. ZIP'i bilgisayarında veya telefonunda çıkart.
2. Depodaki **Add file → Upload files** yoluyla ZIP'in içindeki dosyaları yükle. ZIP dosyasının kendisini değil, içindeki dosyaları yükle.
3. Dosyaların deponun ana dizininde (root) olduğundan emin ol.
4. **Commit changes** ile kaydet.
5. **Settings → Pages** bölümüne gir.
6. **Deploy from a branch** seç.
7. Ekran görüntündeki varsayılan dal `ana` ise `ana` dalını, klasör olarak `/(root)` seç ve kaydet.
8. GitHub Pages bir `github.io` adresi oluşturur. Yayına alınması birkaç dakika sürebilir.

## Özel alan adı
`CNAME` dosyası `zeydrionforgeentertainment.com` alan adını içerir. GitHub Pages → Settings → Pages → Custom domain alanında da aynı alan adını girip kaydet.

Alan adının DNS yönetim panelinde şu kayıtları yapılandır:
- A kayıtları (ana alan adı `@`): `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
- İsteğe bağlı AAAA kayıtları: `2606:50c0:8000::153`, `2606:50c0:8001::153`, `2606:50c0:8002::153`, `2606:50c0:8003::153`
- `www` için CNAME: GitHub kullanıcı adın + `.github.io` (ör. `KULLANICIADIN.github.io`)

DNS değişikliklerinin yayılması zaman alabilir. GitHub Pages ayarlarında HTTPS kullanılabilir olduğunda **Enforce HTTPS** seçeneğini aç.

## Yayınlamadan önce
- `index.html` içindeki örnek e-posta adresini kendi aktif e-posta adresinle değiştir.
- Oyun kartlarına gerçek ekran görüntülerini ekle.
- Stüdyo logosu ve sosyal medya bağlantılarını ekle.
- Alan adının gerçekten satın alınmış ve DNS yönetiminin sende olduğundan emin ol.
