# 🏆 Devlynix Certificate Studio

A premium, professional, and highly customizable certificate generator. Create stunning certificates for events, hackathons, and corporate awards in seconds.

![Certificate Preview](https://img.shields.io/badge/Status-Premium-gold?style=for-the-badge)
![Built With](https://img.shields.io/badge/Built%20With-HTML%20%7C%20CSS%20%7C%20JS-blue?style=for-the-badge)

---
Demo:  https://devlynixcertificatemaker.netlify.app/
## ✨ Top Features

- **🎨 6 Premium Templates**:
  - **Classic**: Traditional gold-bordered prestige.
  - **Modern**: Clean, left-aligned, and geometric.
  - **Minimal**: Contemporary simplicity with wide whitespace.
  - **Elegant**: Deep navy dark mode with gold accents.
  - **Creative**: Vibrant, playful, and colorful.
  - **Professional**: Sharp, crisp, and corporate-standard.
- **🔍 Dynamic QR Code**: Every certificate includes a scannable QR code for authenticity verification.
- **⚡ Bulk Generation**: Generate hundreds of certificates at once using CSV or **Excel (.xlsx)** upload.
- **🤝 Advanced Partner Management**: Add up to 4 partners/sponsors with **individual categories** (e.g., Sponsored By, Supported By, Media Partner).
- **📱 Mobile Responsive**: Fully optimized for mobile devices with a slide-up full-screen preview.
- **⚙️ Award Manager**: Easily add, edit, and manage custom award categories.
- **🖼️ High Quality Export**: Export as high-resolution PNG or print-ready PDF.

---

## 🚀 How to Deploy

Deploying your own instance is incredibly easy:

### Through GitHub & Netlify (Recommended)
1. **Create a Repository**: Create a new repository on GitHub.
2. **Push Files**: Push only the following essential files:
   - `index.html` (The main application)
   - `README.md` (This documentation)
   - *Note: Do NOT push `.bak` files or `.py` scripts (like build.py) as they are only for local development.*
3. **Netlify**: Log in to [Netlify](https://www.netlify.com/).
4. **Import from Git**: Click "Add new site" -> "Import an existing project".
5. **Connect**: Select your GitHub repository.
6. **Deploy**: Leave build settings blank and click **Deploy**.
7. **Live!**: Your site will be live at a custom `.netlify.app` URL.

---

## 📖 User Guide

### 1. Basic Usage
- Fill in the **Editor** tab with event details, names, and signatory info.
- Upload images for logos, MSME certifications, stamps, and signatures.
- Toggle between the 6 templates to find the perfect look.

### 2. Bulk Generation (The Pro Way)
You can generate certificates for a large list of participants in two ways:

#### A. Using Excel (Recommended)
1. Create an Excel sheet (`.xlsx`).
2. The columns should be in this order: **Name, Award Category, Project Name**.
   - *Example*:
     | Name | Award | Project |
     | :--- | :--- | :--- |
     | Yash Harfode | Grand Winner | NivaranAI |
     | Yash Harfode | 1st Runner Up | Devlynix |
3. Go to the **Bulk** tab in the app.
4. Click **"📊 Upload Excel Data (.xlsx)"** and select your file.
5. Click **"⚡ Generate All & Download ZIP"**.

#### B. Using CSV Text
1. In the **Bulk** tab, paste your data in comma-separated format:
   ```csv
   Name, Award, Project
   John Doe, Best Innovation, SmartHome
   Jane Smith, Participant, HackProject
   ```
2. Click **"⚡ Generate All & Download ZIP"**.

---

## 🛠️ Tech Stack
- **HTML5 / CSS3**: Vanilla styling with modern flexbox/grid.
- **JavaScript (ES6)**: Real-time rendering and state management.
- **Libraries**:
  - `html2canvas`: High-fidelity image rendering.
  - `jszip`: For bundling bulk certificates into ZIP files.
  - `xlsx (SheetJS)`: Parsing Excel files directly in the browser.
  - `qrcodejs`: Dynamic verification code generation.

---

Developed with ❤️ by **Devlynix Team**
