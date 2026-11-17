# Operation — Harness Extension Sell

Knowledge base komersial dan operasional untuk **Harness Extension Sell**, paket standar
browser extension buatan [PT. Sainskerta Solusi Nusantara](https://sainskerta.net) — software house
& AI partner berbasis di Gedung Graha Mampang Lt. 3, Jakarta Selatan, beroperasi sejak 2013.

Harness Extension Sell bukan sebuah extension, melainkan **paket produksi** untuk membuat dan
menjual extension Manifest V3 secara berulang. Isinya nyata dan dapat dibaca langsung di
repositori: `STANDARDS.md` v1.5 (kontrak teknis: maks 300 LoC per berkas, paket di bawah 500 KB,
sidebar kanan 25 persen viewport dengan mode rail/sidebar/fullscreen, Full Settings, RPA,
konektivitas web/desktop/terminal, Platform Bridge dengan ingest token, LLM multi-provider,
scraping dan pipeline IndexedDB, SecretVault AES-GCM, onboarding, lisensi, checklist acceptance),
`AGENTS.md`, `UX_FLOW.md` (tutorial 12 langkah), `BUSINESS_PLAYBOOK.md` (katalog ide 20 sektor
bisnis), `PROMPT_TEMPLATE.md`, `.env.example`, `.gitignore`, halaman jual `landing/index.html`,
kit merek di `brand/`, dan aset promosi di `promo/`. Skema komersialnya tertulis di bagian 9
standar: lisensi offline ber-signature Ed25519 dengan edition Free/Pro/bundle/enterprise,
bundling kode lisensi pada buku atau video lewat `bundleId`, trial Pro 14 hari tanpa kartu,
grace offline minimal 14 hari, white-label dari satu berkas konfigurasi merek, dan larangan
mengunci data pengguna maupun telemetry diam-diam. Produk ini tidak memiliki backend: pemrosesan
berjalan on-device, konektor default OFF, dan hanya loopback untuk jalur desktop/terminal.

Seluruh dokumen di folder ini disusun dari fakta yang terbaca di repositori dan dari riset
kompetitor nyata yang sumbernya dicantumkan di tiap dokumen. Positioning yang dipakai: **B2B**
untuk agensi digital, software house, serta asosiasi/instansi (lisensi tim, pilot sektoral,
white-label), dan **B2C** untuk developer indie, freelancer, kreator kursus, dan penulis teknis
(lisensi individu serta bundling konten).

> **Catatan penting.** Harga, target pasar, paket lisensi tim/enterprise, nilai RTO/RPO, ambang
> skor kualifikasi, dan target SLA dalam dokumen ini berstatus **usulan — perlu validasi
> manajemen**. Harga yang benar-benar sudah ada di repo hanyalah harga edition pada
> `landing/index.html` (Free Rp 0, Pro Rp 299 ribu, Bundle Buku + Pro Rp 449 ribu sekali bayar),
> dan landing itu sendiri menandainya sebagai contoh yang perlu disesuaikan. Beberapa hal yang
> muncul sebagai prasyarat komersial belum terdapat di repositori dan ditandai jujur di dalam
> dokumen terkait: tidak ada implementasi extension rujukan maupun `demo/index.html`, tidak ada
> berkas `LICENSE`, tidak ada alat penerbit kunci/registry seat/prosedur rotasi Ed25519, tidak
> ada checksum artefak rilis, serta metadata ukuran aset di `README.md` berbeda dari berkas
> sebenarnya di `promo/`.

## 01-Business-Strategy

| Dokumen | Isi Singkat |
|---|---|
| [01-Business-Model-Canvas](01-Business-Strategy/01-Business-Model-Canvas.docx) | Sembilan blok model dan arus pendapatan berlapis |
| [02-ICP-dan-Segmentasi-Pasar](01-Business-Strategy/02-ICP-dan-Segmentasi-Pasar.docx) | Pembeli lapis satu, segmen hilir, dan yang tidak dikejar |
| [03-Analisis-Kompetitor](01-Business-Strategy/03-Analisis-Kompetitor.docx) | Cloud robot, agen browser, RPA, boilerplate, lisensi |
| [04-Analisis-SWOT](01-Business-Strategy/04-Analisis-SWOT.docx) | Kekuatan, kesenjangan repo, peluang kanal, ancaman |

## 02-Sales

| Dokumen | Isi Singkat |
|---|---|
| [05-Proposal-Penjualan-B2B-Agensi](02-Sales/05-Proposal-Penjualan-B2B-Agensi.docx) | Lisensi tim, pilot sektoral, dan white-label |
| [05-Proposal-Penjualan-B2C-Developer](02-Sales/05-Proposal-Penjualan-B2C-Developer.docx) | Developer indie, freelancer, dan kreator konten |
| [06-Statement-of-Work](02-Sales/06-Statement-of-Work.docx) | Lingkup, fase, pengecualian, dan kriteria terima |
| [07-Pricing-dan-Packaging](02-Sales/07-Pricing-dan-Packaging.docx) | Harga existing landing dan usulan paket lisensi |
| [08-Sales-Playbook-dan-Battlecard](02-Sales/08-Sales-Playbook-dan-Battlecard.docx) | Alur kualifikasi, keberatan, dan kartu tempur |
| [09-Product-Datasheet](02-Sales/09-Product-Datasheet.docx) | Spesifikasi wajib, modul, edition, dan batasan |

## 03-Pre-Sales

| Dokumen | Isi Singkat |
|---|---|
| [10-Discovery-Questionnaire](03-Pre-Sales/10-Discovery-Questionnaire.docx) | Kuesioner kebutuhan, seleksi sektor, dan skor |
| [11-Demo-Script-dan-PoC-Plan](03-Pre-Sales/11-Demo-Script-dan-PoC-Plan.docx) | Demo 30 menit dan PoC sepuluh hari kerja |
| [12-Technical-Proposal](03-Pre-Sales/12-Technical-Proposal.docx) | Rancangan extension turunan dan prasyarat pelanggan |
| [13-ROI-dan-Business-Case](03-Pre-Sales/13-ROI-dan-Business-Case.docx) | Tiga kasus bisnis dengan asumsi yang dinyatakan |

## 04-IT-Communication

| Dokumen | Isi Singkat |
|---|---|
| [14-Arsitektur-Solusi](04-IT-Communication/14-Arsitektur-Solusi.docx) | Lapisan penerbitan, modul turunan, dan aliran data |
| [15-Arsitektur-Keamanan-dan-Threat-Model](04-IT-Communication/15-Arsitektur-Keamanan-dan-Threat-Model.docx) | Aset, batas kepercayaan, dan kesenjangan kunci |
| [16-Privasi-Data-dan-Kepatuhan](04-IT-Communication/16-Privasi-Data-dan-Kepatuhan.docx) | Peran pengendali data dan pemetaan UU PDP |

## 05-Resilience-Operations

| Dokumen | Isi Singkat |
|---|---|
| [17-Business-Continuity-Plan](05-Resilience-Operations/17-Business-Continuity-Plan.docx) | Kontinuitas rilis, kunci, checkout, dan akun |
| [18-Disaster-Recovery-Plan](05-Resilience-Operations/18-Disaster-Recovery-Plan.docx) | RPO/RTO aset serta pemulihan rotasi kunci |
| [19-SOP-Insiden-dan-Breach-Response](05-Resilience-Operations/19-SOP-Insiden-dan-Breach-Response.docx) | Deteksi sampai notifikasi dan playbook khusus |
| [20-SLA-dan-Model-Dukungan](05-Resilience-Operations/20-SLA-dan-Model-Dukungan.docx) | Tingkatan layanan, cakupan, dan operasional lisensi |

## Cara Membaca Suite Ini

1. Mulai dari `01` sampai `04` untuk memahami bentuk produk dan apa yang belum ada di repo.
2. Lanjut ke `02-Sales` untuk materi yang dipakai langsung di depan calon pembeli.
3. Gunakan `03-Pre-Sales` saat menyiapkan discovery, demo, PoC, dan perhitungan manfaat.
4. Baca `04-IT-Communication` bersama tim keamanan, DPO, dan reviewer teknis pelanggan.
5. Tutup dengan `05-Resilience-Operations` untuk kontrak dukungan dan kesiapan insiden.

Tiga keputusan yang berulang di seluruh dokumen dan wajib diambil manajemen sebelum
komersialisasi dibuka: menetapkan bentuk lisensi atas isi paket (repo ini belum memuat berkas
`LICENSE`), membangun satu implementasi extension rujukan yang terbukti lolos checklist
acceptance, serta menetapkan kebijakan penjagaan dan rotasi kunci Ed25519 beserta registry
penerbitan, karena verifikasi offline tidak dapat mencabut kunci yang sudah beredar.

## Penerbit

PT. Sainskerta Solusi Nusantara — Gedung Graha Mampang Lt. 3, Jakarta Selatan
hello@sainskerta.id · +62 813-5988-3131 · sainskerta.net

Dokumen bersifat rahasia dan hanya untuk pemakaian internal serta prospek bisnis yang
telah menandatangani perjanjian kerahasiaan.

© 2026 PT. Sainskerta Solusi Nusantara · hello@sainskerta.id · sainskerta.net
