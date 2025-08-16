# LunarDescent
This is a project that I developed myself for my Masters thesis, namely creating a Multiplayer FPS game that implements Blockchain Technology for all transactions.


# Lunar Descent — Game Design Document (GDD)

## 1. Game Overview

### 1.1 Konsep
**Lunar Descent** adalah game **multiplayer first-person shooter (FPS)** berbasis teknologi **blockchain**. Pemain berpartisipasi dalam pertempuran intens melawan pemain lain untuk mencapai kemenangan. Integrasi blockchain memastikan keamanan, transparansi, dan kepemilikan penuh atas aset digital dalam game.

**Fitur Utama:**
- Pertempuran FPS intens & kompetitif
- Ekonomi dalam game berbasis blockchain (Ethereum + NFT)
- Fitur sosial & komunitas
- Kustomisasi senjata dan karakter

### 1.2 Genre
- Multiplayer FPS
- Blockchain-powered
- Kompetitif, aksi cepat, berbasis skill

### 1.3 Target Pemain
- Pemain FPS multiplayer
- Penggemar teknologi blockchain & NFT
- Pasar kompetitif (eSports) dan pemain kasual

### 1.4 Platform
- PC / Desktop (Windows, MacOS)
- 3D Graphics menggunakan Unity Engine

### 1.5 Visual Style
- Realistis dan mendalam
- Grafis berkualitas tinggi
- Tema futuristik dengan sentuhan cyberpunk

---

## 2. Gameplay

### 2.1 Mode Permainan
1. **Team Battle** – Pertarungan berbasis tim
2. **Free-for-All** – Semua pemain saling berhadapan
3. **Objective Missions** – Misi dengan target spesifik

### 2.2 Integrasi Blockchain
- **Platform:** Ethereum
- **Aset Digital:** NFT (senjata, skin, aksesoris)
- **Kepemilikan & Perdagangan:** Pemain dapat memperjualbelikan aset di marketplace blockchain
- **Proof of Stake (PoS):** Validasi transaksi real-time

### 2.3 Ekonomi Game
- Earn-to-Play: Pemain mendapatkan aset melalui gameplay
- Marketplace Terbuka
- Token In-Game untuk transaksi

### 2.4 Customization
- Upgrade senjata & kemampuan karakter
- Kustomisasi visual (skin, aksesoris)
- Semua progres tercatat di blockchain

---

## 3. Core Game Loop
1. Masuk Game → Login / buat nickname
2. Pilih Mode → Team Battle / FFA / Objective
3. Bertarung → Kumpulkan poin & aset
4. Dapatkan Reward → NFT / token
5. Trade / Upgrade → Gunakan atau jual aset
6. Ulangi → Tingkatkan skill & koleksi

---

## 4. Fitur Utama
- FPS Multiplayer dengan real-time combat
- Ekonomi Terdesentralisasi
- NFT Marketplace
- Progression System berbasis blockchain
- Komunitas & Turnamen

---

## 5. Use Case Diagram & Description

### 5.1 Use Case Diagram
![Use Case Diagram](./diagram/usecase.png)

### 5.2 Use Case Description
| No | Nama Use Case | Aktor | Deskripsi Singkat |
|----|--------------|-------|-------------------|
| 1 | Input Nickname | Pemain | Pemain memasukkan nama yang akan digunakan dalam game |
| 2 | Play Game | Pemain | Memulai pertandingan |
| 3 | Shop | Pemain | Membeli item atau aset dalam game |
| 4 | Settings | Pemain | Mengatur kontrol, audio, dan grafis |
| 5 | Help | Pemain | Melihat tutorial dan panduan |
| 6 | Create Room | Pemain | Membuat ruang permainan |
| 7 | Join Room | Pemain | Bergabung ke ruang permainan dengan kode |

Detail skenario ada di [`/docs/usecase_detail.md`](./usecase_detail.md)

---

## 6. Activity Diagram
![Activity Diagram](./diagram/activity.png)

---

## 7. Class Diagram
![Class Diagram](./diagram/class.png)

**Class Utama:**
- Wallet (Balance, Address, PrivateKey, PublicKey, CreateTransaction, SignTransaction, GetBalance, SyncWithBlockchain)
- Transaction
- Marketplace
- Map
- Character
- Level

---

## 8. UI / Screen Design

### 8.1 Main Menu
- Menu: Play, Settings, Armory, Store
- Friend List panel
- Currency display

### 8.2 Room Screen
- Create Room & Join Room buttons
- Back button, Settings icon

### 8.3 Store
- Item list & preview
- Currency display
- Navigation arrows

### 8.4 Armory
- Weapon categories (Pistols, Rifles, Shotguns)
- Preview panel

### 8.5 Settings
- Audio settings
- Control sensitivity
- Graphics quality
- Crosshair & enemy colors

### 8.6 Gameplay
- First-person view
- Mini-map & compass
- HUD dengan ammo, health, dan objectives

---

## 9. Peningkatan & Inovasi
- Proof of Stake (PoS) untuk validasi transaksi real-time
- NFT sebagai aset game yang dapat diperdagangkan
- Sistem reward transparan dan adil

---


