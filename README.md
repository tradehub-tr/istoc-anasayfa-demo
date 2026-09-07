# iStoc anasayfa blok düzeni önizlemesi

Amazon tarzı blok düzeninin iStoc anasayfasına uyarlanmış statik önizlemesi.
Header ve footer mevcut storefront ile aynı; gövde yeni blok düzeni.

- Tek sayfa: `index.html` + `data.js` (gerçek alpha.istoc.com ilan verisi)
- Tailwind CSS v4 (tarayıcı CDN) + Alpine.js 3.15 (CDN), derleme yok
- Görseller `img/`, istoc-sans fontu `fonts/`

Yerel önizleme: `python3 -m http.server 8000` → http://localhost:8000
