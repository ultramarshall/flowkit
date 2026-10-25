<div align="center">

# ⚡ Flowkit — IBM App Connect Enterprise (ACE) Studio

**Modern, Standalone Visual Studio & ESQL Editor for IBM App Connect Enterprise v11 & v12**

[![GitHub Pages](https://img.shields.io/badge/Website-GitHub%20Pages-3b82f6?logo=github&logoColor=white)](https://ultramarshall.github.io/flowkit/)
[![Release](https://img.shields.io/badge/Release-v0.1.0--alpha-orange?logo=github)](https://github.com/ultramarshall/flowkit-master/releases)
[![Binary](https://img.shields.io/badge/Distribution-Native%20Binaries%20Only-emerald)](https://ultramarshall.github.io/flowkit/#download)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

🌐 **Live Product Website & Feature Showcase:**  
👉 **[https://ultramarshall.github.io/flowkit/](https://ultramarshall.github.io/flowkit/)**

---

### 🖥️ Application Overview
<img src="assets/images/flowkit-ide-overview.png" alt="Flowkit IDE Overview" width="100%" style="border-radius: 12px; box-shadow: 0 10px 30px rgba(0,0,0,0.5);" />

</div>

---

## 📦 Unduh Installer Binary (Official Desktop Releases)

Flowkit didistribusikan secara eksklusif dalam format **installer binary native** yang telah diproteksi (*obfuscated & asar packaged*). Tidak ada dependensi node, kompilasi manual, atau arsip sumber kode `.tar.gz`.

| Platform / Sistem Operasi | Format Binary | Arsitektur | Tautan Unduhan Langsung |
| :--- | :--- | :--- | :--- |
| **Linux (Debian / Ubuntu / Mint)** | **`.deb`** Installer | `amd64 / x86_64` | [📥 Unduh flowkit_0.1.0_amd64.deb](https://github.com/ultramarshall/flowkit-master/releases/download/v0.1.0-alpha/flowkit_0.1.0_amd64.deb) |
| **Linux Universal (Arch/Fedora/RHEL)** | **`.AppImage`** Portable | `x86_64` | [📥 Unduh Flowkit-0.1.0.AppImage](https://github.com/ultramarshall/flowkit-master/releases/download/v0.1.0-alpha/Flowkit-0.1.0.AppImage) |
| **Microsoft Windows (10 & 11)** | **`.exe`** NSIS Installer | `x64` | [📥 Unduh Flowkit-Setup-0.1.0.exe](https://github.com/ultramarshall/flowkit-master/releases/download/v0.1.0-alpha/Flowkit-Setup-0.1.0.exe) |
| **Apple macOS (Silicon & Intel)** | **`.dmg`** Disk Image | `Universal` | [📥 Unduh Flowkit-0.1.0.dmg](https://github.com/ultramarshall/flowkit-master/releases/download/v0.1.0-alpha/Flowkit-0.1.0.dmg) |

---

## 📸 Capture Fitur Unggulan (Feature Showcase)

### 1. Right-Click Precision Node Alignment (Rata X & Rata Y)
Rapikan graf alur pesan tanpa dragging manual. Seleksi node, klik kanan, dan pilih alignment instan (Rata Kiri, Rata Tengah, Rata Kanan, Rata Atas, Rata Bawah, serta Sebar Merata).

<div align="center">
  <img src="assets/images/flowkit-node-alignment.png" alt="Node Alignment" width="90%" style="border-radius: 8px;" />
</div>

---

### 2. Live Integration Server Explorer (Admin REST API v2)
Panel explorer bergaya dockable VSCode untuk memonitor Integration Node (`CORENODE`) dan Server (`RANODE`). Mulai, hentikan, restart message flow, serta deploy BAR langsung secara visual.

<div align="center">
  <img src="assets/images/flowkit-integration-explorer.png" alt="Integration Server Explorer" width="90%" style="border-radius: 8px;" />
</div>

---

### 3. Dynamic Side-Labels & Touchpad Panning
Pilihan mode label samping yang melebar dinamis mengikuti panjang label node dengan icon flush tanpa batas, didukung navigasi touchpad dua jari untuk pan bebas di seluruh kanvas.

<div align="center">
  <img src="assets/images/flowkit-side-label.png" alt="Dynamic Side-Label Nodes" width="90%" style="border-radius: 8px;" />
</div>

---

## 🚀 Panduan Instalasi Cepat

### Linux (Ubuntu / Debian / Mint)
```bash
sudo dpkg -i flowkit_0.1.0_amd64.deb
flowkit
```

### Linux Portable (AppImage)
```bash
chmod +x Flowkit-0.1.0.AppImage
./Flowkit-0.1.0.AppImage
```

### Windows (10 / 11)
1. Unduh `Flowkit-Setup-0.1.0.exe`.
2. Jalankan berkas installer dan ikuti petunjuk wizard.
3. Buka Flowkit melalui Desktop Shortcut atau Start Menu.

### Apple macOS
1. Unduh `Flowkit-0.1.0.dmg`.
2. Buka berkas `.dmg`, lalu tarik (*drag*) icon **Flowkit** ke folder **Applications**.
3. Buka Flowkit dari Launchpad atau Spotlight (`Cmd + Space`).

---

## 📄 Lisensi
Dilisensikan di bawah [MIT License](LICENSE).
Dikembangkan untuk modernisasi dan akselerasi operasional middleware IBM App Connect Enterprise.
