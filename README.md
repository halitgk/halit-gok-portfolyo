# Halit Gök — Portfolyo

Bu klasör, portfolyo sitesinin GitHub Pages'te yayınlanmaya hazır statik halidir.

## İçerik

- `index.html` — tüm sayfa (tek dosya, harici bağımlılık yok)
- `images/` — sayfadaki 36 görselin tamamı (yerel, göreli yollarla bağlı)

## Yayınlama adımları

1. GitHub'da yeni ve boş bir repo oluştur (örn. `halit-gok-portfolyo`).
2. Bu klasördeki **tüm dosyaları** (`index.html` ve `images/` klasörü) reponun kök dizinine yükle.
   - Web arayüzünden: repo sayfasında "Add file" → "Upload files" ile sürükle-bırak.
   - Veya komut satırından:
     ```bash
     git clone https://github.com/<kullanici-adin>/halit-gok-portfolyo.git
     cp -r index.html images halit-gok-portfolyo/
     cd halit-gok-portfolyo
     git add index.html images
     git commit -m "Portfolyo sitesini ekle"
     git push
     ```
3. Repo sayfasında **Settings → Pages**'e git.
4. "Source" olarak `main` dalını ve `/ (root)` klasörünü seç, **Save**'e bas.
5. Birkaç dakika içinde site şu adreste yayında olur:
   `https://<kullanici-adin>.github.io/halit-gok-portfolyo/`

## Not

`index.html` dosya adını değiştirme — GitHub Pages ana sayfayı bu isimle arar.
