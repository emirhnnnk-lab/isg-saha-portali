# İSG Saha Portalı (Demo)

> **EN summary:** Demo of an occupational health & safety (OHS) field portal for safety-service providers: role-based views (specialist, manager, client company), visit planning, field reports with risk ratings, task flow, bulletins and CSV import. HTML/Tailwind/vanilla JS with Supabase Realtime (disabled in the demo). All data is sample data.

OSGB'ler için dış saha iş sağlığı ve güvenliği (İSG) yönetim portalı. Uzman, müdür ve firma rollerini tek bir arayüzde birleştirir.

> Bu repo **demo sürümüdür**. Tüm firma adları, kişiler ve tutarlar örnek veridir.

## Özellikler
- **Rol bazlı panel:** İSG uzmanı, saha müdürü ve firma görünümü
- **Firma takibi:** Ziyaret planı, ilerleme yüzdesi, cari bakiye
- **Saha raporu:** Tespit, risk derecesi, alınacak önlem ve termin; tek tuşla rapor
- **Görev akışı:** Müdürden uzmana iş emri, durum takibi
- **Bültenler:** Sahaya yönelik güvenlik duyuruları
- **CSV içe aktarma:** Firma listesini toplu yükleme ve önizleme
- **Gerçek zamanlı senkron:** Supabase Realtime (demo sürümde kapalı, veriler tarayıcıda saklanır)

## Teknoloji
HTML · Tailwind CSS · Vanilla JavaScript · Supabase (Postgres + Realtime) · Vercel

## Çalıştırma
`index.html` dosyasını tarayıcıda açmanız yeterli. Canlı senkron için `supabaseUrl` ve `supabaseAnonKey` alanlarına kendi Supabase projenizin bilgilerini girin.

---
Geliştiren: **Emirhan Karaca** — yapay zekâ destekli otomasyon ve ürün geliştirme
