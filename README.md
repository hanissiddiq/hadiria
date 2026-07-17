# Hadiria - Platform Manajemen Kehadiran Modern

[![Framework: Next.js](https://shields.io)](https://nextjs.org)
[![Database: Supabase](https://shields.io)](https://supabase.com)

**Hadiria** adalah sistem manajemen kehadiran dan personalia modern yang dibangun sebagai wujud replikasi dan pembaruan (*re-engineering*) dari platform **SmartPPNPN**. Aplikasi ini dirancang ulang untuk menghadirkan performa yang lebih cepat, antarmuka intuitif, serta pengelolaan data yang real-time dan aman.

---

## 🚀 Teknologi Utama

Aplikasi ini mengadopsi *tech stack* modern untuk menjamin efisiensi dan skalabilitas:

- **Front-end:** [Next.js](https://nextjs.org) (React Framework) – Untuk performa optimal, rendering cepat, dan antarmuka yang responsif di perangkat seluler.
- **Back-end & Database:** [Supabase](https://supabase.com) – Menyediakan basis data PostgreSQL dengan fitur *Real-time sync*, otentikasi aman, dan penyimpanan berkas digital.

---

## ✨ Fitur Unggulan

- **Replikasi SmartPPNPN:** Membawa fungsi inti pelaporan kehadiran staf ke dalam alur kerja yang lebih ringkas.
- **Pencatatan Real-Time:** Sinkronisasi data absensi (masuk, pulang, izin) secara instan melalui Supabase.
- **Dasbor Admin & Verifikator:** Kemudahan pemantauan dan validasi rekapitulasi kehadiran staf secara berkala.
- **Optimasi Seluler:** Antarmuka yang ringan dan ramah diakses melalui peramban *smartphone*.

---

## 🛠️ Persyaratan Sistem

Sebelum memulai instalasi, pastikan perangkat Anda telah terpasang:
- [Node.js](https://nodejs.org) (Versi LTS terbaru)
- Akun [Supabase](https://supabase.com) aktif

---

## 💻 Memulai Instalasi

Ikuti langkah-langkah berikut untuk menjalankan proyek di lingkungan lokal:

### 1. Klon Repositori
```bash
git clone https://github.com
cd hadiria
```

### 2. Instal Dependensi
```bash
npm install
# atau
yarn install
# atau
pnpm install
```

### 3. Konfigurasi Variabel Lingkungan
Buat berkas `.env.local` pada direktori utama proyek, lalu masukkan kredensial Supabase Anda:
```env
NEXT_PUBLIC_SUPABASE_URL=isi_dengan_url_supabase_anda
NEXT_PUBLIC_SUPABASE_ANON_KEY=isi_dengan_anon_key_supabase_anda
```

### 4. Jalankan Server Pengembangan
```bash
npm run dev
# atau
yarn dev
# atau
pnpm dev
```
Buka [http://localhost:3000](http://localhost:3000) pada peramban Anda untuk melihat hasilnya.

---

## 🔒 Keamanan & Lisensi

Proyek ini dikembangkan dengan standar keamanan enkripsi data dari Supabase. Seluruh hak cipta kode dan aset di dalamnya tunduk pada kebijakan privasi instansi pengembang.
