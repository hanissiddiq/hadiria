# Hadiria - Platform Manajemen Kehadiran Modern

[![Framework: Next.js](https://img.shields.io/badge/Framework-Next.js-000000?logo=next.js&logoColor=white)](https://nextjs.org)
[![Database: Supabase](https://img.shields.io/badge/Database-Supabase-3ECF8E?logo=supabase&logoColor=white)](https://supabase.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

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


### 5, Preview Apps
Preview User (Pegawai) <br>
---
<img width="289" height="530" alt="image" src="https://github.com/user-attachments/assets/0c686e53-3996-4931-96ad-3dd9e77078c5" />
<img width="288" height="527" alt="image" src="https://github.com/user-attachments/assets/d5c57a05-670f-4b8c-b5d3-648404562562" /><br>
<img width="292" height="530" alt="image" src="https://github.com/user-attachments/assets/1d7abdfa-0b5c-4efd-9487-bf2a3c13a9e4" />
<img width="288" height="525" alt="image" src="https://github.com/user-attachments/assets/70ec15f4-22a0-4f8c-a97a-1b0f0a39c2ee" /><br>
<img width="287" height="523" alt="image" src="https://github.com/user-attachments/assets/7cfd0d3a-79da-4166-81ce-0c989858cdaa" />
<img width="285" height="528" alt="image" src="https://github.com/user-attachments/assets/450941a1-4f3a-4720-a4f4-9d2d845ff6c1" /><br>
<img width="456" height="679" alt="image" src="https://github.com/user-attachments/assets/de78a737-c774-4573-a874-7ca86b7b0fef" /><br>

---


preview admin <br>
---
<img width="1365" height="685" alt="image" src="https://github.com/user-attachments/assets/f3b81ad3-1a68-49f7-8924-035c9c3d4dd6" /><br>
<img width="1036" height="529" alt="image" src="https://github.com/user-attachments/assets/b1dae758-af7d-48dd-87ee-277eb14fc394" /><br>
<img width="1037" height="523" alt="image" src="https://github.com/user-attachments/assets/f536332e-9ed8-4f34-92e8-9517f642893c" /><br>
<img width="1035" height="525" alt="image" src="https://github.com/user-attachments/assets/8c7a48c2-712e-41a0-b2df-bd272a48e334" /><br>
<img width="1036" height="527" alt="image" src="https://github.com/user-attachments/assets/f85a5567-5194-4d90-b727-c1090310d768" /><br>
<img width="1037" height="525" alt="image" src="https://github.com/user-attachments/assets/30cf519c-3bee-4977-9e34-38e320e6a294" /><br>
<img width="1037" height="527" alt="image" src="https://github.com/user-attachments/assets/f37dd952-d812-467d-a1aa-bdb7da871e2e" /><br>
---

---

## 🔒 Keamanan & Lisensi

Proyek ini dikembangkan dengan standar keamanan enkripsi data dari Supabase. Seluruh hak cipta kode dan aset di dalamnya tunduk pada kebijakan privasi instansi pengembang.
