# 🎮 SaveForge Studio - Online Formula Library

[ [ภาษาไทย](#-ภาษาไทย-thai) | [English](#-english) ]

---

## 🇹🇭 ภาษาไทย (Thai)

คลังสูตรโกงเซฟเกมออนไลน์อย่างเป็นทางการสำหรับใช้งานร่วมกับ **SaveForge Studio**
รองรับสูตรเซฟเกมทั้ง **PlayStation 4 (PS4)** และ **PlayStation 3 (PS3)**

### 📊 ข้อมูลสรุปคลังสูตร (Catalog Summary)
- **PS4 Formulas:** 212 ไฟล์ (`.savepatch`)
- **PS3 Formulas:** 1,789 ไฟล์ (`.savepatch`)
- **รวมไฟล์สูตรทั้งหมด:** **2,001 ไฟล์**
- **ความปลอดภัย (Security):** ทุกไฟล์และรายการสูตรได้รับการคำนวณ SHA-256 และลงลายเซ็นดิจิทัล **RSA-SHA256 (3072-bit)** กำกับไว้ใน `catalog/formula-catalog.json`

### 🚀 วิธีการซิงค์สูตรเข้าโปรแกรม SaveForge Studio
1. เปิดโปรแกรม **SaveForge Studio**
2. ไปที่หน้าต่าง **"คลังสูตร" (Patch Library)**
3. กดปุ่มสีฟ้า **"อัปเดตคลังออนไลน์" (Update online library)**
4. โปรแกรมจะตรวจสอบลายเซ็นดิจิทัลและดาวน์โหลดสูตรใหม่ล่าสุดมายังเครื่องของคุณโดยอัตโนมัติ

### 📁 โครงสร้างโฟลเดอร์ในคลังสูตร
```text
SaveForge-Studio-Formula-Library/
├── catalog/
│   └── formula-catalog.json      # รายการสูตรทั้งหมดพร้อมลายเซ็นดิจิทัล RSA 3072-bit
├── patches/
│   ├── ps4/                      # รวมไฟล์สูตรเกม PS4 (CUSAxxxxx.savepatch)
│   └── ps3/                      # รวมไฟล์สูตรเกม PS3 (BLUS/BLES/NPUB/NPEB.savepatch)
└── README.md
```

---

## 🇬🇧 English

Official online formula and cheat patch repository for **SaveForge Studio**.
Supporting save modifications across **PlayStation 4 (PS4)** and **PlayStation 3 (PS3)** titles.

### 📊 Summary of Formulas
- **PS4 Formulas:** 212 files (`.savepatch`)
- **PS3 Formulas:** 1,789 files (`.savepatch`)
- **Total Formulas:** **2,001 files**
- **Security & Integrity:** Every patch file and catalog manifest is hashed with SHA-256 and cryptographically signed with **RSA-SHA256 (3072-bit)** in `catalog/formula-catalog.json`.

### 🚀 How to Sync with SaveForge Studio
1. Launch **SaveForge Studio**.
2. Open the **"Patch Library"** window.
3. Click the cyan button **"Update online library"**.
4. The client will verify the cryptographic RSA signature and download the latest formula database automatically.

### 📁 Directory Layout
```text
SaveForge-Studio-Formula-Library/
├── catalog/
│   └── formula-catalog.json      # Verified manifest signed with RSA 3072-bit private key
├── patches/
│   ├── ps4/                      # PS4 save patch definitions (CUSAxxxxx.savepatch)
│   └── ps3/                      # PS3 save patch definitions (BLUS/BLES/NPUB/NPEB.savepatch)
└── README.md
```

---

## 🛡️ License & Attribution
- Save patch data adapted and cataloged under GNU General Public License v3.0 (GPL-3.0) via Apollo Save Patches database.
- Designed and maintained for use with [SaveForge Studio](https://github.com/nikonboy2532-stack/SaveForge-Studio).
