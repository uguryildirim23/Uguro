# Uğuro — E-Kitap Okuyucu

## Telefonuna Uygulama Olarak Yükleme (5 Dakika)

Android Studio, npm, bilgisayar gerekmiyor. Sadece telefon ve GitHub hesabı yeterli.

---

### ADIM 1 — GitHub Hesabı Aç (zaten varsa atla)

1. Telefonunda Chrome'dan şuraya git: **github.com**
2. **Sign up** butonuna dokun
3. E-posta, şifre gir, hesabı oluştur

---

### ADIM 2 — Bu Dosyaları GitHub'a Yükle

1. GitHub'da sağ üstte **+** butonuna dokun → **New repository**
2. Repository name: **uguro** yaz
3. **Public** seçili olsun
4. **Create repository** butonuna dokun
5. Açılan sayfada **"uploading an existing file"** linkine dokun
6. ZIP'ten çıkan **tüm dosyaları** sürükle/yükle:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`
7. **Commit changes** butonuna dokun

---

### ADIM 3 — GitHub Pages'i Aç

1. Repository sayfasında **Settings** sekmesine git
2. Sol menüden **Pages** seç
3. **Source** kısmında **"Deploy from a branch"** seç
4. **Branch** kısmında **"main"** seç, klasör **"/ (root)"** kalsın
5. **Save** butonuna dokun
6. 1-2 dakika bekle, sayfa yenilenince üstte yeşil bir link belirecek:
   **https://KULLANICIADIN.github.io/uguro/**

---

### ADIM 4 — Ana Ekrana Ekle

1. O linki **Chrome**'da aç
2. Sağ üstte **⋮** (üç nokta) menüsüne dokun
3. **"Ana ekrana ekle"** seçeneğine dokun
4. **"Yükle"** veya **"Ekle"** butonuna dokun

✅ Ana ekranında **Uğuro** ikonu belirecek.
Dokunduğunda uygulama gibi tam ekran açılır, internetsiz de çalışır!

---

## Dosya Listesi

| Dosya | Açıklama |
|-------|----------|
| `index.html` | Ana uygulama dosyası |
| `manifest.json` | PWA yapılandırması (ikon, isim, tema) |
| `sw.js` | Service Worker (çevrimdışı çalışma) |
| `icon-192.png` | Uygulama ikonu (küçük) |
| `icon-512.png` | Uygulama ikonu (büyük) |
