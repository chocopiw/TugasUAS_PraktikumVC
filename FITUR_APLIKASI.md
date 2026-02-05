# 📊 Dokumentasi Fitur Aplikasi Dashboard

## Informasi Proyek

**Nama Proyek:** TugasUAS_PraktikumVC  
**Tujuan:** Aplikasi Dashboard dengan Praktikum Version Control System (Git)  
**Tahun:** 2026  
**Status:** ✅ Sudah Dikembangkan & Diperbarui

---

## 🏗️ Struktur Proyek

```
TugasUAS_PraktikumVC/
├── index.html                # Halaman utama (Landing Page)
├── dashboard.html            # Halaman dashboard dengan fitur interaktif
├── tentang.html              # Halaman informasi aplikasi
├── README.md                 # Dokumentasi umum
├── pembagian _tugas.md       # Pembagian tugas tim
├── FITUR_APLIKASI.md         # File ini - Dokumentasi lengkap fitur
└── css/
    └── styles.css            # Styling CSS untuk seluruh aplikasi
```

---

## ✨ Fitur-Fitur Aplikasi

### 🏠 **1. Halaman Home (index.html)**

**Deskripsi:**
- Halaman landing page yang menyambut pengguna
- Menampilkan overview aplikasi
- Menu navigasi ke semua halaman

**Komponen:**
- Hero section dengan sambutan
- Menu list dengan styling modern
- Navigation bar yang responsif
- Footer dengan informasi copyright

**Fitur:**
- ✅ Responsive design (desktop, tablet, mobile)
- ✅ Gradient background yang menarik
- ✅ Link navigasi yang interaktif
- ✅ Fully accessible

---

### 📈 **2. Halaman Dashboard (dashboard.html)**

**Deskripsi:**
- Aplikasi dashboard utama dengan fitur lengkap
- Multiple tabs untuk menampilkan berbagai data
- Sidebar navigation untuk switching antar section

#### **Tab 1: Overview** 📊
- **Kartu Statistik:**
  - Total Pengguna: 1,234
  - Status Aktif: 87%
  - Total Penjualan: ₿ 3.2k

- **Tabel Aktivitas Terbaru:**
  - Waktu kejadian
  - Jenis kegiatan (Login, Upload, Update)
  - User yang melakukan aktivitas

#### **Tab 2: Statistics** 📉
- **Metrik Sistem:**
  - CPU Usage: 45%
  - Memory Usage: 62%
  - Storage Usage: 78%
  - Info Uptime: 99.8%

#### **Tab 3: User Management** 👥
- **Tabel Pengguna Lengkap:**

| No | Nama | Email | Status | Terdaftar |
|----|------|-------|--------|-----------|
| 1 | Ani Wijaya | ani@example.com | ✅ Aktif | 2024-01-15 |
| 2 | Budi Santoso | budi@example.com | ✅ Aktif | 2024-02-10 |
| 3 | Clara Dewi | clara@example.com | ❌ Tidak Aktif | 2024-01-20 |
| 4 | Dedi Pratama | dedi@example.com | ✅ Aktif | 2024-03-05 |

**Fitur:**
- Status badge (Aktif/Tidak Aktif)
- Hover effects pada baris tabel
- Responsive table

#### **Tab 4: Settings** ⚙️
- **Pengaturan Sistem:**
  - ✅ Notifikasi Email (Checkbox)
  - 🌙 Mode Gelap (Dark Mode Toggle)
  - 🌍 Pemilihan Bahasa (Dropdown)
  - 💾 Tombol Simpan Pengaturan

**Fitur Interaktif:**
- ✅ Dark Mode toggle yang berfungsi
- ✅ Pengaturan dapat disimpan
- ✅ Form validation ready

---

### 📖 **3. Halaman Tentang (tentang.html)**

**Deskripsi:**
- Halaman informasi lengkap tentang aplikasi
- Menjelaskan fitur dan teknologi yang digunakan
- Detail proyek dan tim pengembang

**Konten:**
1. **Deskripsi Aplikasi**
   - Penjelasan tujuan aplikasi
   - Kegunaan dalam praktikum VCS

2. **Fitur Utama**
   - Dashboard Overview
   - Statistik Sistem
   - Manajemen Pengguna
   - Pengaturan Aplikasi
   - Log Aktivitas Real-time

3. **Teknologi yang Digunakan**
   - HTML5
   - CSS3
   - JavaScript
   - Git Version Control

4. **Informasi Proyek**
   - Nama & Tujuan
   - Tahun Pengembangan
   - Status Proyek

---

## 🎨 **Fitur UI/UX**

### **Navigation System**
```
┌─────────────────────────────────────┐
│  Home  │  Dashboard  │  Tentang     │  ← Topbar
├─────────────────────────────────────┤
│ Sidebar │        Main Content       │
│ - Overview                           │
│ - Stats                              │
│ - Users                              │
│ - Settings                           │
└─────────────────────────────────────┘
```

### **Color Scheme**
- Primary Color: Blue (#2563eb)
- Success Color: Green (#10b981)
- Danger Color: Red (#ef4444)
- Warning Color: Amber (#f59e0b)
- Background: Light (#f4f7fb) / Dark Mode (#1a202c)

### **Responsive Breakpoints**
- Desktop: Full sidebar + main content
- Tablet: Sidebar berubah horizontal
- Mobile: Stack vertikal, menu scroll

---

## 🔧 **Teknologi & Framework**

### **Frontend Stack**
- **HTML5** - Semantic markup
- **CSS3** - Grid, Flexbox, CSS Variables
- **JavaScript (Vanilla)** - No dependencies
  - Event listeners
  - DOM manipulation
  - Dark mode toggle
  - Section switching

### **Features Implementasi**

```javascript
// Sidebar Navigation
document.querySelectorAll('.sidebar-item').forEach(item => {
  item.addEventListener('click', function() {
    // Switch active section
  });
});

// Dark Mode Toggle
document.getElementById('darkModeToggle').addEventListener('change', function() {
  document.body.classList.toggle('dark-mode');
});
```

---

## 📱 **Responsive Design**

### **Desktop (> 768px)**
- ✅ Sidebar di sebelah kiri (220px)
- ✅ Main content fleksibel
- ✅ Full navigation visible

### **Tablet (max-width: 768px)**
- ✅ Sidebar berubah horizontal
- ✅ Menu scroll horizontal
- ✅ Content tetap readable

### **Mobile (< 480px)**
- ✅ Stack layout vertikal
- ✅ Touch-friendly buttons
- ✅ Optimized spacing

---

## 🎯 **Cara Menggunakan Aplikasi**

### **Step 1: Akses Halaman Home**
```
1. Buka index.html di browser
2. Baca sambutan dan overview aplikasi
3. Lihat menu populer
```

### **Step 2: Navigasi ke Dashboard**
```
1. Klik link "Dashboard" di menu atau navbar
2. Halaman dashboard.html akan terbuka
3. Sidebar menampilkan 4 menu utama
```

### **Step 3: Jelajahi Fitur**
```
Dashboard:
├── Overview - Lihat summary data
├── Stats - Lihat statistik sistem
├── Users - Kelola daftar pengguna  
└── Settings - Ubah preferensi
```

### **Step 4: Tips Penggunaan**
```
✅ Klik menu sidebar untuk switching content
✅ Gunakan Dark Mode di Settings untuk tema gelap
✅ Hover di atas kartu untuk melihat effect
✅ Klik Tentang untuk info lebih lanjut
```

---

## 🚀 **Performance & Optimization**

- ✅ Minimal CSS selectors
- ✅ Efficient JavaScript DOM queries
- ✅ CSS Variables untuk easy theming
- ✅ Mobile-first responsive design
- ✅ No external dependencies
- ✅ Fast page load time

---

## 🐛 **Known Features & Status**

| Fitur | Status | Catatan |
|-------|--------|---------|
| Home Page | ✅ Complete | Landing page responsif |
| Dashboard Navigation | ✅ Complete | Sidebar yang interaktif |
| Overview Tab | ✅ Complete | Data cards + activity log |
| Stats Tab | ✅ Complete | System metrics |
| Users Tab | ✅ Complete | User management table |
| Settings Tab | ✅ Complete | Preferences & dark mode |
| Tentang Page | ✅ Complete | Dokumentasi aplikasi |
| Dark Mode | ✅ Complete | Toggle di Settings |
| Responsive Design | ✅ Complete | Desktop/Tablet/Mobile |
| CSS Styling | ✅ Complete | Modern & clean design |

---

## 📚 **Dokumentasi Git**

```bash
# Clone repository
git clone <repository-url>

# Add changes
git add .

# Commit changes
git commit -m "Update aplikasi dengan fitur lengkap"

# Push ke remote
git push origin main

# Pull latest changes
git pull origin main
```

---

## 👥 **Tim Pengembang**

**Kontributor:**
- **M Zhainal Firdaus** (NIM: 301220041) - Struktur Project & Dashboard
- **Sofy Nur Kholifah** (NIM: 301220018) - Fitur about.html & Update

---

## 📝 **Update Log**

### **V2.0 - Perbaruan Terbaru**
- ✅ Added JavaScript interactivity
- ✅ Implemented Dark Mode
- ✅ Created About page
- ✅ Enhanced CSS styling
- ✅ Responsive design improvements
- ✅ Added badges & status indicators
- ✅ Complete documentation

### **V1.0 - Initial Release**
- ✅ Basic dashboard structure
- ✅ HTML layout
- ✅ CSS styling

---

## ⚙️ **Pengaturan & Konfigurasi**

### **CSS Variables** (di styles.css)
```css
:root {
  --bg: #f4f7fb;              /* Background */
  --card: #fff;               /* Card background */
  --accent: #2563eb;          /* Primary color */
  --success: #10b981;         /* Success color */
  --danger: #ef4444;          /* Error color */
  --border: #eceff5;          /* Border color */
}
```

### **Dark Mode Variables**
Otomatis di-apply ketika class `dark-mode` ditambahkan ke body

---

## 🎓 **Learning Outcomes**

Dari praktikum ini, peserta belajar:
- ✅ Git & Version Control System
- ✅ HTML5 Semantic Markup
- ✅ CSS3 Modern Styling (Grid, Flexbox)
- ✅ Responsive Web Design
- ✅ JavaScript DOM Manipulation
- ✅ UI/UX Best Practices
- ✅ Collaborative Development

---

## 📞 **Support & Contact**

Untuk pertanyaan atau bantuan:
- Buka halaman "Tentang" untuk informasi
- Periksa dokumentasi ini untuk panduan lengkap

---

**© 2026 TugasUAS Praktikum VC**  
*Dokumentasi Lengkap Aplikasi Dashboard*
