---

# 🐫 TeosEgypt-DomainPlatform

TeosEgypt-DomainPlatform adalah platform pendaftaran domain Web3 terdesentralisasi berbasis Solana yang memungkinkan pengguna mendaftarkan, mengelola, dan memperdagangkan domain .teos sebagai NFT. Dibangun oleh Elmahrosa Internasional, platform ini menyatukan teknologi blockchain mutakhir dengan kekayaan warisan budaya Mesir Kuno.

![TeosEgypt Showcase](public/screenshots/teosegypt-cover.png)

---

## 📌 Ringkasan Fitur

- 🔐 Pendaftaran Domain Terdesentralisasi
- 🏛️ Integrasi Branding Budaya Mesir
- 💸 Dukungan Pembayaran Multi-token (termasuk $TEOS Egypt)
- 🛍️ Integrasi Marketplace NFT (Magic Eden)
- 🌐 Dukungan Multibahasa
- 👛 Integrasi Dompet (Phantom, Solflare)
- 📱 Desain UI/UX Responsif Bertema Mesir
- 📤 Penyimpanan Metadata NFT di IPFS/Arweave

---

## 🛠️ Teknologi yang Digunakan

| Komponen | Teknologi |
|---------|------------|
| Kontrak Pintar | `Rust`, `Anchor Framework` |
| Frontend | `Next.js`, `React`, `TailwindCSS` |
| Backend | `Node.js`, `Express.js`, `TypeScript` |
| Blockchain Layer | `Solana`, `@solana/web3.js`, `SPL-Token`, `Anchor` |
| Dompet & NFT | `Phantom`, `Solflare`, `Magic Eden` |
| Basis Data | `PostgreSQL`, `Redis` |
| Penyimpanan Terdesentralisasi | `IPFS`, `Arweave` |

---

## 📁 Struktur Proyek

TeosEgypt-DomainPlatform/ │ ├── contracts/              # Program Solana (Rust + Anchor) ├── frontend/               # Aplikasi web (Next.js + TailwindCSS) ├── backend/                # Layanan backend API (Node.js) ├── migrations/             # Anchor migration scripts ├── scripts/                # Deployment / utilitas ├── docker/                 # Docker konfigurasi ├── docs/                   # Dokumentasi teknis └── README.md               # Dokumentasi utama proyek

---

## ⚙️ Prasyarat

- Node.js v18+
- Rust Stable
- Solana CLI (`solana --version`)
- Anchor CLI (`anchor --version`)
- Docker (opsional)
- Yarn atau NPM

---

## 🚀 Instalasi & Penggunaan

### 1. Kloning Repositori
```bash
git clone https://github.com/Elmahrosa/TeosEgypt-DomainPlatform.git
cd TeosEgypt-DomainPlatform

2. Jalankan Local Solana

solana-test-validator

3. Deploy Program (Anchor)

cd contracts
anchor build
anchor deploy

4. Jalankan Frontend

cd frontend
npm install
npm run dev

5. Jalankan Backend

cd backend
npm install
npm run dev


---

🧪 Pengujian

Kontrak Pintar

cd contracts
anchor test

Frontend (Next.js)

cd frontend
npm run test

Backend

cd backend
npm run test


---

📦 Docker Support (Opsional)

Jalankan seluruh stack menggunakan Docker:

docker-compose up --build

Edit docker-compose.yml untuk koneksi Solana, Redis, dan PostgreSQL.


---

🧠 Roadmap

[x] Pendaftaran domain .teos sebagai NFT

[x] Integrasi Magic Eden

[ ] Subdomain support (user.domain.teos)

[ ] Integrasi Oracle untuk validasi nama domain

[ ] DNSBridge untuk akses Web2 ke domain .teos

[ ] Tata Kelola DAO berbasis $TEOS token



---

🛡️ Keamanan

✅ Validasi domain name sebelum mint

✅ Pencegahan duplikasi token .teos

🔒 Enkripsi koneksi wallet

📋 Audit keamanan eksternal (dalam rencana)



---

🤝 Kontribusi

Kami menyambut kontribusi! Silakan baca CONTRIBUTING.md untuk panduan kontribusi.

git checkout -b fitur-baru
git commit -m "feat: tambahkan fitur x"
git push origin fitur-baru


---

📄 Lisensi

Lisensi: MIT License.
Lihat LICENSE untuk detail.


---

📞 Kontak & Komunitas

🌍 Situs resmi: https://teosegypt.io

💬 Discord: Elmahrosa Dev Hub

🐦 Twitter: @teosegypt
