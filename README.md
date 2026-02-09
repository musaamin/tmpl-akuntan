# Template Website Kantor Akuntan Publik

Website profil untuk Kantor Akuntan Publik.

## Fitur Website

- **Desain Modern & Premium** - Tampilan profesional dengan warna biru tua dan emas
- **Fully Responsive** - Tampilan optimal di desktop, tablet, dan mobile
- **Navigasi Interaktif** - Menu mobile dengan Alpine.js
- **Form Kontak WhatsApp** - Kirim pesan langsung ke WhatsApp Web
- **Smooth Scrolling** - Navigasi halus antar section
- **Social Media Links** - Facebook, Instagram, TikTok, YouTube di footer

## Struktur Folder

```
akuntan/
├── index.html
├── README.md
└── assets/
    ├── css/
    │   └── tailwind.css
    ├── js/
    │   └── alpine.js
    └── images/
        ├── hero-accounting.jpg
        ├── service-tax.jpg
        ├── service-audit.jpg
        ├── service-consulting.jpg
        ├── team-accountant.jpg
        ├── team-dewi.jpg
        └── team-ahmad.jpg
```

## Teknologi

- **Tailwind CSS** - Framework CSS (local file)
- **Alpine.js** - Framework JavaScript lightweight (local file)
- **HTML5** - Struktur markup
- **Google Fonts** - Font Inter

## Section Website

1. **Hero** - Banner utama dengan statistik
2. **Layanan** - Perpajakan, Audit & Assurance, Konsultasi Bisnis
3. **Tentang Kami** - Profil perusahaan dan keunggulan
4. **Tim** - Profil partner dan tim profesional
5. **Kontak** - Informasi kontak dan form WhatsApp
6. **Footer** - Links dan social media

## Kontak WhatsApp

Form kontak terintegrasi dengan WhatsApp Web:
- Nomor default: +62 812 3456 7890
- Ganti nomor di JavaScript line: `const whatsappNumber = '6281234567890'`
