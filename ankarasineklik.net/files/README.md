# Ankara Pınar Marangoz Pentamir Servisi

HTML/CSS ile yapılmış statik web sitesi.

## Deployment

Bu proje Vercel üzerinde deploy edilmek için hazırlanmıştır.

### Yerel geliştirme

```bash
npm install
npm run dev
```

### Vercel'e deploy etme

1. Vercel hesabınızı GitHub ile bağlayın
2. Bu repository'yi import edin
3. Otomatik deployment başlayacaktır

Veya Vercel CLI ile:

```bash
npm install -g vercel
vercel
```

### Dosya yapısı

- `index.html` - Ana sayfa
- `assets/` - CSS, JS, resim dosyaları
- `*.html` - Diğer sayfalar
- `vercel.json` - Vercel konfigürasyonu
- `package.json` - NPM konfigürasyonu