# Channel SEO — YouTube Channel SEO

Web statis (tanpa backend) untuk menganalisis channel YouTube dan menyiapkan materi branding channel.

## Fitur

- **Statistik channel** — negara, total video, total views, subscriber (via YouTube Data API v3)
- **Avatar Studio** — prompt avatar channel
- **Bio Generator** — bio channel (opsional: AI via Gemini API)
- **Hashtag & Midjourney prompt** — hashtag dan prompt gambar

## Cara pakai

1. Tempel link channel YouTube (@handle, /channel/UC..., /user/..., atau link video).
2. Masukkan YouTube Data API key di Pengaturan (key tersimpan di localStorage browser, tidak dikirim ke server mana pun).
3. Klik proses — statistik dan materi branding muncul di bawah.

## Catatan

- Tanpa API key, ekstraksi tidak bisa jalan (YouTube Data API wajib).
- Key hanya tersimpan per browser — di perangkat lain perlu ditempel sekali lagi.
- Live: https://channel-seo.pages.dev
