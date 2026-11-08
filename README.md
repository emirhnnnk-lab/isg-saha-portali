# İSG Saha Portalı (demo)

> **EN summary:** Demo of an occupational health & safety (OHS) field portal for safety-service providers: role-based views (specialist, manager, client company), visit planning, field reports with risk ratings, task flow, bulletins and CSV import. HTML/Tailwind/vanilla JS with Supabase Realtime (disabled in the demo). All data is sample data. Full English version: [README.en.md](README.en.md).

İş sağlığı ve güvenliği (İSG) hizmeti veren firmalarda iş şöyle dönüyor: uzman sahaya gidiyor, tespitlerini yazıyor; müdür kimin nereye gideceğini planlıyor; hizmet alan firma da kendi durumunu görmek istiyor. Genelde bunların hepsi Excel'lerde, WhatsApp gruplarında ve kâğıtta dağınık duruyor. Bu portal üç rolü tek bir ekranda topluyor.

> Bu repo **demo sürümü**. Bütün firma adları, kişiler ve tutarlar örnek veri.

## Neler var
- **Role göre ekran:** İSG uzmanı, saha müdürü ve firma kendi görünümünü görüyor.
- **Firma takibi:** ziyaret planı, ilerleme yüzdesi, cari bakiye.
- **Saha raporu:** tespit, risk derecesi, alınacak önlem ve son tarih; tek tuşla rapor.
- **Görev akışı:** müdürden uzmana iş emri ve durum takibi.
- **Bültenler:** sahaya yönelik güvenlik duyuruları.
- **Toplu içe aktarma:** firma listesini CSV ile yükleme ve önizleme.
- **Anlık senkron:** Supabase Realtime ile herkes aynı veriyi anında görüyor (demo sürümünde kapalı; veriler tarayıcıda tutuluyor).

## Teknoloji
HTML · Tailwind CSS · düz JavaScript · Supabase (Postgres + Realtime) · Vercel

## Çalıştırma
`index.html` dosyasını tarayıcıda açmak yeterli. Anlık senkron için `supabaseUrl` ve `supabaseAnonKey` alanlarına kendi Supabase projenizin bilgilerini girin.

---
Geliştiren: **Emirhan Karaca**
