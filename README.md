# 📊 TugasUAS_PraktikumVC - Dashboard Application

![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![Version](https://img.shields.io/badge/Version-2.0-blue)
![License](https://img.shields.io/badge/License-MIT-green)

Aplikasi Dashboard web interaktif untuk praktikum **Version Control System (Git)** dengan fitur lengkap dan desain modern.

---

## 🎯 Deskripsi Proyek

Proyek ini adalah **aplikasi web dashboard** yang menampilkan:
- 📊 Overview dan statistik sistem
- 👥 Manajemen pengguna
- ⚙️ Pengaturan sistem
- 📝 Log aktivitas real-time
- 🌙 Dark mode support
- 📱 Responsive design

**Teknologi:** HTML5 • CSS3 • JavaScript (Vanilla) • Git

---

## 📂 Struktur File

```
TugasUAS_PraktikumVC/
├── 📄 index.html              # Halaman home/landing page
├── 📄 dashboard.html          # Halaman dashboard utama
├── 📄 tentang.html            # Halaman tentang aplikasi
├── 📄 README.md               # File ini
├── 📄 FITUR_APLIKASI.md       # Dokumentasi lengkap fitur
├── 📄 pembagian _tugas.md     # Pembagian tugas tim
└── 📁 css/
    └── 📄 styles.css          # Stylesheet untuk semua halaman
```

---

## 🚀 Quick Start

### 1. Clone Repository
```bash
git clone <repository-url>
cd TugasUAS_PraktikumVC
```

### 2. Buka di Browser
```bash
# Gunakan Live Server atau buka langsung
index.html
```

### 3. Navigasi Aplikasi
- **Home** → Landing page aplikasi
- **Dashboard** → Aplikasi dashboard dengan fitur lengkap
- **Tentang** → Informasi aplikasi

---

## ✨ Fitur Utama

### 🏠 **Home Page (index.html)**
- Hero section yang menarik
- Menu navigasi responsif
- Desain modern dengan gradient background
- Link ke semua halaman aplikasi

### 📊 **Dashboard (dashboard.html)**
- **4 Menu Utama di Sidebar:**
  1. **Overview** - Summary data & aktivitas terbaru
  2. **Stats** - Statistik CPU, Memory, Storage
  3. **Users** - Daftar dan manajemen pengguna
  4. **Settings** - Pengaturan dark mode & bahasa

- **Fitur Interaktif:**
  - ✅ Sidebar navigation dengan active state
  - ✅ Dark mode toggle
  - ✅ Responsive tables dengan badge status
  - ✅ Smooth transisi antar section

### 📖 **About Page (tentang.html)**
- Deskripsi lengkap aplikasi
- Daftar fitur yang tersedia
- Info teknologi yang digunakan
- Data proyek dan tahun pengembangan

---

## 🎨 Design Features

### **Color Scheme**
| Warna | Kode | Penggunaan |
|-------|------|-----------|
| Primary | `#2563eb` | Accent & buttons |
| Success | `#10b981` | Status aktif |
| Danger | `#ef4444` | Status error |
| Background | `#f4f7fb` | Body background |
| Dark | `#0f172a` | Topbar & sidebar |

### **Typography**
- Font: Segoe UI, Roboto, Arial, Sans-serif
- Responsive font sizes
- Semantic heading hierarchy

### **Responsive Breakpoints**
- 📱 Mobile: < 480px (Single column)
- 📱 Tablet: 480px - 768px (Flexible)
- 💻 Desktop: > 768px (Sidebar + Main)

---

## 🛠️ Technologies Used

```
Frontend:
├── HTML5       - Semantic markup
├── CSS3        - Grid, Flexbox, Variables
├── JavaScript  - DOM manipulation
└── Git         - Version control
```

### **Browser Support**
- Chrome/Edge (Latest)
- Firefox (Latest)
- Safari (Latest)
- Mobile browsers (iOS/Android)

---

## 📋 Fitur Detail

### **Home Page**
```
✅ Responsive hero section
✅ Grid menu layout
✅ Hover effects pada tombol
✅ Mobile-friendly navigation
```

### **Dashboard**
```
✅ Sidebar dengan 4 menu utama
✅ Dynamic section switching
✅ Card grid layout untuk metrics
✅ Data tables dengan styling
✅ Dark mode toggle (Settings)
✅ Status badges (Active/Inactive)
```

### **About Page**
```
✅ Overview aplikasi
✅ Feature list dengan checkmark
✅ Technology stack info
✅ Project details
```

### **CSS Features**
```
✅ CSS Variables untuk theming
✅ Flexbox & Grid layout
✅ Media queries responsif
✅ Dark mode support
✅ Smooth transitions & animations
✅ Box shadows & hover effects
```

### **JavaScript Features**
```
✅ Event listeners untuk menu
✅ Active state management
✅ Dark mode toggle
✅ DOM class manipulation
✅ No external dependencies
```

---

## 🎮 Cara Menggunakan

### **Navigasi Home**
1. Buka `index.html`
2. Lihat hero section dengan informasi proyek
3. Klik menu "Dashboard" atau "Tentang"

### **Navigasi Dashboard**
1. Buka `dashboard.html`
2. Sidebar menampilkan 4 opsi menu
3. Klik menu untuk melihat konten berbeda:
   - **Overview** - Data & aktivitas
   - **Stats** - Statistik sistem
   - **Users** - Daftar pengguna
   - **Settings** - Pengaturan

### **Dark Mode**
1. Pergi ke tab "Settings" di dashboard
2. Centang checkbox "Mode Gelap"
3. Tema akan berubah ke dark mode

### **Tentang Aplikasi**
1. Klik menu "Tentang" di navbar
2. Baca deskripsi dan fitur aplikasi
3. Lihat info teknologi & proyek

---

## 🔍 Code Examples

### **Sidebar Navigation JavaScript**
```javascript
document.querySelectorAll('.sidebar-item').forEach(item => {
  item.addEventListener('click', function() {
    // Hide all sections
    document.querySelectorAll('.content-section').forEach(s => 
      s.classList.remove('active')
    );
    // Show clicked section
    document.getElementById(this.dataset.section).classList.add('active');
  });
});
```

### **Dark Mode Toggle**
```javascript
document.getElementById('darkModeToggle').addEventListener('change', function() {
  document.body.classList.toggle('dark-mode');
});
```

### **CSS Variables**
```css
:root {
  --accent: #2563eb;
  --bg: #f4f7fb;
  --card: #fff;
}

/* Dark mode */
body.dark-mode {
  --bg: #1a202c;
  --card: #2d3748;
}
```

---

## 📱 Responsive Design

### **Desktop (> 768px)**
```
┌─────────────────────────────────┐
│         Navigation Bar          │
├─────────┬───────────────────────┤
│Sidebar  │    Main Content       │
│ 220px   │    (flex: 1)          │
├─────────┴───────────────────────┤
│         Footer                  │
└─────────────────────────────────┘
```

### **Mobile (< 768px)**
```
┌─────────────────────────────────┐
│    Navigation Bar (Compact)     │
├─────────────────────────────────┤
│    Sidebar (Horizontal Scroll)  │
├─────────────────────────────────┤
│      Main Content (Full)        │
├─────────────────────────────────┤
│         Footer                  │
└─────────────────────────────────┘
```

---

## 🐛 Troubleshooting

### **Dashboard tidak membuka**
- Pastikan file `css/styles.css` ada
- Periksa path file di link tag

### **Dark mode tidak berfungsi**
- Pastikan JavaScript dijalankan
- Cek browser console untuk error

### **Sidebar tidak responsif**
- Clear browser cache (Ctrl+Shift+R)
- Reload halaman

### **Styling tidak muncul**
- Verifikasi path CSS relatif
- Periksa file styles.css tidak corrupt

---

## 🎓 Learning Outcomes

Dari proyek ini, Anda belajar:

- ✅ **Version Control (Git)**
  - Commit, push, pull
  - Branch management
  - Collaboration

- ✅ **HTML5**
  - Semantic markup
  - Form elements
  - Accessibility

- ✅ **CSS3**
  - Grid & Flexbox
  - Responsive design
  - CSS Variables
  - Dark mode

- ✅ **JavaScript**
  - DOM manipulation
  - Event handling
  - State management

- ✅ **Web Design**
  - UI/UX principles
  - Color theory
  - Typography

---

## 👥 Tim Pengembang

### **Kontributor Utama:**

| Nama | NIM | Tugas |
|------|-----|-------|
| **M Zhainal Firdaus** | 301220041 | Struktur Project, Dashboard |
| **Sofy Nur Kholifah** | 301220018 | About Page, Improvements |

---

## 📅 Version History

### **V2.0 (Current) - Enhanced**
- ✅ JavaScript interactivity
- ✅ Dark mode support
- ✅ Complete about page
- ✅ Enhanced CSS styling
- ✅ Responsive improvements
- ✅ Full documentation

### **V1.0 - Initial**
- ✅ Basic dashboard structure
- ✅ HTML layout
- ✅ Simple CSS styling

---

## 📚 Documentation Files

1. **README.md** (Anda di sini)
   - Project overview & quick start
   
2. **FITUR_APLIKASI.md**
   - Dokumentasi lengkap semua fitur
   - Code examples
   - Technical details

3. **pembagian _tugas.md**
   - Pembagian tugas tim
   - Kontribusi individual

---

## 🤝 Contributing

Untuk berkontribusi:

1. Fork repository
2. Buat branch feature (`git checkout -b feature/AmazingFeature`)
3. Commit perubahan (`git commit -m 'Add some AmazingFeature'`)
4. Push ke branch (`git push origin feature/AmazingFeature`)
5. Open Pull Request

---

## 📞 Support & Contact

Pertanyaan atau saran? Silakan:
- Buat issue di repository
- Hubungi tim pengembang
- Kunjungi halaman "Tentang" untuk info lengkap

---

## 📄 License

Proyek ini menggunakan **MIT License**. Bebas digunakan untuk keperluan akademik dan komersial.

---

## 🎉 Terima Kasih

Terima kasih telah menggunakan aplikasi dashboard ini. Semoga bermanfaat untuk pembelajaran Anda tentang **Git dan Web Development**!

---

**© 2026 TugasUAS Praktikum VC**  
*Dashboard Application v2.0*  
*Happy Coding! 🚀*