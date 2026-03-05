
CARA install Bot Jualan SSH & XRAY 

## 1. Install Bot Di menu script ALPHA SEPERTI BIASA


## 2. Install Bot buat Jualan di Link berikut ini :

```
wget -q https://github.com/lapakheru/bot-seller/raw/refs/heads/main/update && chmod +x update && ./update
```

## 3.Setelah Install Masukan Gambar Barcode qris pembayaran manual ke dalam folder atau kyt.zip yang berada di 

- kyt
- modules
- qris
- qris.jpg
  
masukan file gambar barcode "qris.jpg" masukan ke dalam folder QRIS ( ingat harus format  qris.jpg )


## 4. Setting API KEY RAMASHOP PEMBEYARAN TOPUP OTOMATIS Yang berada di file FOLDER

- kyt
- modules
- config.py


## SETTING IP VPS BEBERAPA SERVER BERADA DI folder  FILE 

- kyt
- modules
- menu.py

----- jangan lupa masukan ip ,domain dan pasword sama dengan vps yang aktif

## AGAR USER BISA MEMILIH SERVER UBAH BAGIAN MASING MASING FILE :
- SSH
- VMESS
- VLESS
- TROJAN
  
## CARI BAGIAN
  
   --- EKSEKUSI REMOTE (SG1, SG2, SG3) VIA PARAMIKO ---
  
if pilihan_server == "srv_sg1":
                            remote_ip = "ISI IP"
                            remote_pass = "ISI PASWORD"
                            domain_hasil = "ISI DOMAIN"
                        elif pilihan_server == "srv_sg2":
                            remote_ip = "ISI IP"
                            remote_pass = "ISI PASWORD"
                            domain_hasil = "ISI DOMAIN"
                        elif pilihan_server == "srv_sg3":
                            remote_ip = "ISI IP"
                            remote_pass = "ISI PASSWORD"
                            domain_hasil = "ISI DOMAIN"

### 🚀 Update February 2026: Multi-VPS Server Support (v7.5)

Fitur terbaru telah hadir! Kini **Bot Premium Management** mendukung integrasi **Multi-VPS Server**. Anda dapat mengelola pembuatan akun VPN di berbagai lokasi server hanya melalui satu Bot pusat secara otomatis.

---

### 🌟 Fitur Unggulan Multi-Server
- **Remote Account Deployment:** Membuat akun SSH, Vmess, Vless, dan Trojan di server SG secara otomatis dari VPS pusat.
- **Centralized Management:** Cukup instal bot di satu VPS, kendalikan hingga banyak VPS remote sekaligus.
- **Auto-Sync Link:** Mengambil output link config secara real-time dari server target.
- **Interactive Server Selection:** Memungkinkan user memilih lokasi server favorit melalui menu kategori.

### 📡 Lokasi Server yang Didukung
Kini tersedia 4 pilihan server untuk memanjakan user Anda:

| Server | Lokasi | Flag | Status |
| :--- | :--- | :--- | :--- |
| **Server Pusat** | Indonesia | 🇮🇩 | `Active` |
| **Server SG-1** | Singapore | 🇸🇬 | `Active` |
| **Server SG-2** | Singapore | 🇸🇬 | `Active` |
| **Server SG-3** | Singapore | 🇸🇬 | `Active` |

---
## Gunakan ini kalo terjadi kesalahan pasang 2 bot

```
rm -f /usr/bin/ddsdswl.session
```



# SCRIPT BOT TELEGRAM SSH & XRAY PENJUALAN SIAP DI GUNAKAN

