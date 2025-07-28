# 🌟 Web Portfolio - Yoga Pratama

## 📋 Deskripsi Project

Project ini adalah website portfolio pribadi yang dibuat sebagai tugas mata kuliah **Sistem dan Teknologi Informasi** di **UNISNU Jepara**. Website ini menampilkan informasi pribadi, tugas-tugas yang telah dikerjakan, dan kontak sosial media.

### 👨‍💻 Tentang Pembuat
- **Nama**: Yoga Pratama
- **NIM**: 231240001363
- **Institusi**: UNISNU Jepara
- **Mata Kuliah**: Sistem dan Teknologi Informasi

---

## 🎯 Tujuan Project

Project ini dibuat untuk:
- Memenuhi tugas mata kuliah Sistem dan Teknologi Informasi
- Menampilkan portfolio pribadi dan tugas-tugas yang telah dikerjakan
- Menerapkan konsep web development dasar (HTML, CSS, JavaScript)
- Membuat website responsive yang dapat diakses di berbagai device

---

## ✨ Fitur Utama

### 🏠 **Home Section**
- Hero section dengan background image
- Introduction singkat tentang pembuat
- Call-to-action button untuk melihat tugas

### 👤 **About Section**
- Informasi pribadi lengkap
- Foto profil
- Deskripsi background dan keluarga
- Motivasi dan hobi

### 📚 **Tugas Section**
- Menampilkan 3 tugas utama:
  - **Tugas 1**: Ms. Word latihan soal
  - **Tugas 2**: Ms. Word mengetik 10 jari
  - **Tugas 3**: Ms. Excel penerapan formula
- Link langsung ke Google Docs untuk setiap tugas
- Thumbnail untuk setiap tugas

### 📞 **Footer**
- Kontak sosial media (WhatsApp, Instagram, Twitter, Facebook)
- Navigation links
- Copyright information

---

## 🛠️ Teknologi yang Digunakan

### **Frontend Technologies**
- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling dengan custom properties
- **JavaScript**: DOM manipulation dan interactivity

### **External Libraries**
- **Google Fonts**: Poppins font family
- **Feather Icons**: Icon library untuk UI elements
- **Google Docs**: External storage untuk tugas-tugas

### **Design System**
- **Color Palette**:
  - Primary: `#b6895b` (Coklat keemasan)
  - Background: `#010101` (Hitam)
  - Text: `#fff` (Putih)
- **Typography**: Poppins (100, 300, 400, 700 weights)
- **Layout**: Flexbox dan CSS Grid
- **Responsive**: Mobile-first approach

---

## 📁 Struktur Project

```
Web-STI-Yoga-main/
├── index.html              # File HTML utama
├── README.md              # Dokumentasi project
├── css/
│   └── style.css         # Stylesheet utama
├── js/
│   └── script.js         # JavaScript functionality
└── img/
    ├── Yoga.jpg          # Background hero section
    ├── tentang-saya.jpg  # Foto profil
    └── Tugas/
        ├── 1.jpg         # Thumbnail tugas 1
        ├── 2.jpg         # Thumbnail tugas 2
        └── 3.jpg         # Thumbnail tugas 3
```

---

## 🚀 Cara Menjalankan Project

### **Prerequisites**
- Web browser modern (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code, Sublime Text, dll)

### **Setup Instructions**

1. **Clone atau Download Project**
   ```bash
   # Jika menggunakan Git
   git clone [repository-url]
   
   # Atau download ZIP file dan extract
   ```

2. **Buka Project**
   ```bash
   cd Web-STI-Yoga-main
   ```

3. **Jalankan Website**
   - Double click pada file `index.html`
   - Atau buka dengan web browser
   - Atau gunakan live server extension di VS Code

### **Development Setup**
```bash
# Install live server (optional)
npm install -g live-server

# Jalankan dengan live server
live-server
```

---

## 📱 Responsive Design

Website ini dirancang dengan **mobile-first approach** dan mendukung berbagai ukuran layar:

### **Breakpoints**
- **Desktop** (>1366px): Font size 75%
- **Tablet** (768px-1366px): Font size 62.5%
- **Mobile** (<450px): Font size 55%

### **Mobile Features**
- Hamburger menu untuk navigation
- Touch-friendly interactions
- Optimized layouts untuk small screens
- Smooth animations dan transitions

---

## 🎨 Komponen UI/UX

### **Navigation**
- Fixed navbar dengan semi-transparent background
- Smooth hover effects
- Mobile-responsive hamburger menu
- Active state indicators

### **Hero Section**
- Full viewport height design
- Background image dengan gradient overlay
- Call-to-action button dengan hover animation
- Typography hierarchy

### **Content Sections**
- Two-column layout untuk about section
- Card-based layout untuk tugas section
- Consistent spacing dan typography
- Interactive hover effects

### **Footer**
- Social media links dengan icons
- Navigation links
- Copyright information
- Consistent branding

---

## 🔧 JavaScript Functionality

### **Mobile Navigation**
```javascript
// Toggle hamburger menu
const navbarnav = document.querySelector(".navbar-nav");
document.querySelector("#hamburger-menu").onclick = () => {
  navbarnav.classList.toggle("active");
};

// Close menu when clicking outside
document.addEventListener("click", function (e) {
  if (!hamburger.contains(e.target) && !navbarnav.contains(e.target)) {
    navbarnav.classList.remove("active");
  }
});
```

### **Features**
- Mobile menu toggle
- Click outside to close
- Smooth transitions
- Event delegation

---

## 📊 Performance & Optimization

### **Current Performance**
- ✅ Lightweight implementation
- ✅ Minimal external dependencies
- ✅ Semantic HTML structure
- ✅ CSS custom properties
- ✅ Progressive enhancement

### **Optimization Opportunities**
- 🔄 Image compression (Yoga.jpg: 3.1MB)
- 🔄 Lazy loading implementation
- 🔄 CSS minification
- 🔄 JavaScript bundling
- 🔄 Service worker implementation

---

## 🎓 Educational Context

### **Learning Objectives**
Project ini mencakup konsep-konsep fundamental web development:

1. **HTML5 Semantic Structure**
   - Proper document structure
   - Semantic elements
   - Accessibility considerations

2. **CSS3 Modern Features**
   - Custom properties (CSS variables)
   - Flexbox layouts
   - Media queries
   - Transform animations
   - Pseudo-elements

3. **JavaScript Basics**
   - DOM manipulation
   - Event handling
   - Class toggling
   - Mobile interactions

4. **Responsive Design**
   - Mobile-first approach
   - Breakpoint management
   - Touch interactions
   - Performance optimization

### **Assignment Requirements**
- ✅ Personal portfolio website
- ✅ Responsive design
- ✅ Modern web technologies
- ✅ Assignment showcase
- ✅ Professional presentation

---

## 🔗 External Links

### **Tugas Links**
- [Tugas 1 - Ms. Word Latihan Soal](https://docs.google.com/document/d/1Sz1UV-YNzcfwCMgxvWusAmE7ABW7Srtj/edit?usp=drivesdk&ouid=107015380191050895739&rtpof=true&sd=true)
- [Tugas 2 - Ms. Word Mengetik 10 Jari](https://docs.google.com/document/d/1SzoTOS7NzHopya8o3ETDtADNJDmrxSr7/edit?usp=drivesdk&ouid=107015380191050895739&rtpof=true&sd=true)
- [Tugas 3 - Ms. Excel Penerapan Formula](https://docs.google.com/spreadsheets/d/1T5phIw8-ifOrkSN-q4jqaNmuEve-s9gr/edit?usp=drivesdk&ouid=107015380191050895739&rtpof=true&sd=true)

### **Social Media**
- **WhatsApp**: [Contact via WhatsApp](https://wa.me/qr/M55WCOL3S7KYI1)
- **Instagram**: [@yxpratama_](https://instagram.com/yxpratama_?igshid=MzRlODBiNWFlZA==)
- **Twitter**: [@Yogapratama05](https://x.com/Yogapratama05?t=kXI9yCHyiKxEpYDXvcXqyw&s=09)
- **Facebook**: [Yoga Pratama](https://www.facebook.com/profile.php?id=100027992505873&mibextid=ZbWKwL)

---

## 🐛 Troubleshooting

### **Common Issues**

1. **Images not loading**
   - Pastikan semua file gambar ada di folder `img/`
   - Check file permissions

2. **Styles not applying**
   - Verify CSS file path: `css/style.css`
   - Check browser console for errors

3. **JavaScript not working**
   - Ensure `js/script.js` is loaded
   - Check browser console for errors

4. **Mobile menu not working**
   - Verify Feather Icons library is loaded
   - Check JavaScript console for errors

### **Browser Compatibility**
- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ⚠️ Internet Explorer (not supported)

---

## 📈 Future Enhancements

### **Potential Improvements**
- [ ] Add dark/light theme toggle
- [ ] Implement smooth scrolling animations
- [ ] Add loading animations
- [ ] Implement contact form
- [ ] Add blog section
- [ ] Integrate with CMS
- [ ] Add SEO optimization
- [ ] Implement PWA features

### **Technical Upgrades**
- [ ] Convert to React/Vue.js
- [ ] Implement TypeScript
- [ ] Add unit tests
- [ ] Implement CI/CD pipeline
- [ ] Add performance monitoring

---

## 📝 License

This project is created for educational purposes as part of the **Sistem dan Teknologi Informasi** course at **UNISNU Jepara**.

**Created by**: Yoga Pratama  
**NIM**: 231240001363  
**Year**: 2023  
**Institution**: UNISNU Jepara

---

## 🙏 Acknowledgments

- **UNISNU Jepara** - Educational institution
- **Google Fonts** - Typography
- **Feather Icons** - Icon library
- **Google Docs** - Document hosting
- **Instructors** - Course guidance

---

## 📞 Contact

Untuk pertanyaan atau feedback tentang project ini, silakan hubungi:

- **Email**: [Contact via social media]
- **WhatsApp**: [WhatsApp Link](https://wa.me/qr/M55WCOL3S7KYI1)
- **Instagram**: [@yxpratama_](https://instagram.com/yxpratama_?igshid=MzRlODBiNWFlZA==)

---

**⭐ Jika project ini membantu, jangan lupa untuk memberikan star!**

---

*Last updated: December 2023* 