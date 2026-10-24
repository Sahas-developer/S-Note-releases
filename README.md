<p align="center">
  <img src="assets/logo.png" alt="S-Note Logo" width="130" />
</p>

<h1 align="center">S-Note</h1>

<p align="center">
  <strong>A modern, blazing-fast, and distraction-free digital notebook for stylus, tablet, mouse, and keyboard.</strong>
</p>

<p align="center">
  <a href="https://github.com/Sahas-developer/S-Note-releases/releases/latest">
    <img src="https://img.shields.io/badge/Release-v0.2.1-7c3aed?style=for-the-badge&logo=github&logoColor=white" alt="Latest Release" />
  </a>
  <a href="#-download--install">
    <img src="https://img.shields.io/badge/Platform-Windows%20%7C%20Android-0078d4?style=for-the-badge&logo=windows&logoColor=white" alt="Platforms" />
  </a>
  <a href="#-privacy--offline-first">
    <img src="https://img.shields.io/badge/Privacy-100%25%20Offline%20First-2ea44f?style=for-the-badge&logo=shield&logoColor=white" alt="Offline First" />
  </a>
  <a href="https://github.com/Sahas-developer/S-Note-releases/stargazers">
    <img src="https://img.shields.io/badge/License-Free-blue?style=for-the-badge" alt="Free License" />
  </a>
</p>

<p align="center">
  <a href="#-download--install"><b>Download Now</b></a> •
  <a href="#-key-features"><b>Key Features</b></a> •
  <a href="#-screenshots--showcase"><b>Screenshots</b></a> •
  <a href="#-whats-new-in-v021"><b>What's New</b></a> •
  <a href="#-cloud-sync--backups"><b>Cloud & Backups</b></a>
</p>

---

## 📸 Screenshots & Showcase

<p align="center">
  <img src="assets/banner.jpg" alt="S-Note Banner" width="85%" style="border-radius: 12px; box-shadow: 0 8px 30px rgba(0,0,0,0.3);" />
</p>

<details open>
<summary><b>👀 Click to explore Feature Screenshots</b></summary>
<br/>

| 🖋️ **Natural Inking & Study Tape** | 👥 **Real-Time Collaboration** |
|:---:|:---:|
| <img src="assets/screenshots/preview-inking.svg" alt="Study Tape & Inking" width="100%"/><br/>*Fluorescent pens, pencils &amp; tap-to-reveal study tape* | <img src="assets/screenshots/preview-collab.svg" alt="Real-time Collaboration" width="100%"/><br/>*Multi-user live syncing with laser pointer* |

| 📐 **3D Geometric Shapes** | ♾️ **Infinite Canvas & Templates** |
|:---:|:---:|
| <img src="assets/screenshots/preview-shapes.svg" alt="3D Shapes" width="100%"/><br/>*Cuboids, spheres, pyramids, and angle guide* | <img src="assets/screenshots/preview-canvas.svg" alt="Infinite Canvas" width="100%"/><br/>*Cornell notes, planners, and unbounded canvas* |

> 💡 *Note: To view all screenshots in full resolution, check out the [`assets/screenshots`](assets/screenshots) folder.*
</details>

---

## ⚡ Why S-Note?

Most digital note-taking applications today are bloated with expensive recurring monthly subscriptions, locked behind proprietary cloud formats, or built on heavy Electron runtimes that drain your battery.

**S-Note is built differently:**
- 🚀 **Blazing Fast Native Performance:** Built with **Rust (Tauri)** and **React 19**, giving you instantaneous startup, ultra-low latency inking, and minimal RAM usage.
- 🔒 **100% Offline-First & Private:** Your notes live locally on your device. No forced accounts or third-party tracking.
- 🤝 **Peer-to-Peer Live Collaboration:** Share a room code and write notes together in real time with classmates or colleagues.
- 🧪 **Designed for Serious Learning:** Includes specialized tools like **Study Tape** for active recall, **3D Shape Modeling** for STEM subjects, and **Smart PDF Inversion** for late-night studying.

---

## ⬇️ Download & Install

Choose the build for your device from our [Releases Page](https://github.com/Sahas-developer/S-Note-releases/releases/latest):

| Platform | Type | Download Link | Version |
| :--- | :--- | :--- | :--- |
| **Windows 10 / 11** (64-bit) | Setup Installer (`.exe`) | [⬇️ **Download S-Note Installer**](https://github.com/Sahas-developer/S-Note-releases/releases/download/v0.2.1/S-Note_0.2.1_x64-setup.exe) | `v0.2.1` |
| **Windows 10 / 11** (Portable) | Standalone Executable | [⬇️ **Download Portable App**](https://github.com/Sahas-developer/S-Note-releases/releases/download/v0.2.1/S-Note.exe) | `v0.2.1` |
| **Android & Tablets** (Samsung / Universal) | Universal APK (`.apk`) | [⬇️ **Download Android APK**](https://github.com/Sahas-developer/S-Note-releases/releases/download/v0.2.1/S-Note.apk) | `v0.2.1` |

> 🔄 **Automatic Updates:** S-Note features a built-in silent background updater. Once installed, it will automatically alert you whenever a new release is available!

---

## ✨ Key Features

### 🖋️ Ultra-Responsive Digital Inking
- **Precision Pen Physics:** Designed for active styluses (S-Pen, Surface Pen, Apple Pencil, Wacom) with pressure dynamics, tilt sensitivity, and palm rejection.
- **Multiple Writing Instruments:**
  - **Ballpoint Pen:** Clean, consistent strokes for rapid handwriting.
  - **Fountain Pen:** Dynamic line-weight variation with realistic flex dynamics.
  - **Pencil Engine:** Realistic graphite shading textures (2B Dark, HB Medium, 2H Light, Burnt Umber, Sepia, White Chalk).
  - **Brush & Highlighter:** Semi-transparent pastel and fluorescent markers that highlight behind ink.
- **Catmull-Rom Cubic Bezier Smoothing:** Real-time stroke stabilization eliminates jitter and keeps writing crisp at any zoom level.

### 🧪 Study Tape (Active Recall Flashcards)
- Conceal important answers, formulas, vocabulary, or diagrams under colorful study tape.
- **Tap to Reveal:** Simply tap on any tape strip during revision to reveal what's underneath!
- Perfect for students preparing for medical, engineering, or board examinations.

### 👥 Real-Time Multiplayer Collaboration
- Connect instantly with peers over encrypted WebSockets / WebRTC room sessions.
- **Zero-Lag Laser Pointer:** Present, lecture, and draw attention to diagrams in real time without leaving permanent marks.
- **Live Peer Cursors:** See exactly where your collaborators are writing with colored user badges.

### 📐 2D & 3D Smart Geometry (Draw & Hold)
- **Instant Vector Snapping:** Sketch roughly and hold your pen to automatically convert strokes into perfect geometric shapes.
- **Full 3D Primitives Support:**
  - Cuboids, Cubes, Spheres, Cylinders, Cones, Tetrahedrons, Square Pyramids, and Hexagonal Pyramids.
- **2D Primitives & Math Symbols:**
  - Lines, Directional Arrows, Circles, Ellipses, Right/Equilateral Triangles, Parabolas, Semicircles, and Square Root (√) symbols.
- **Geometry Customization:** Adjustable corner rounding (smooth edges), fill colors, opacity, and snap-to-angle guides.

### ♾️ Dual Canvas Experience
- **Paginated Notebooks:** Familiar multi-page notebook experience with standard page sizes (A4, A3, A5, Letter, Square) in Portrait or Landscape.
- **Infinite Canvas Mode:** An unbounded 2D plane with infinite zoom and panning — ideal for mind-mapping, architecture diagrams, and brainstorm sessions.
- **Extensive Paper Templates:** Blank, Ruled (Narrow/Wide), Dot Grid, Math Graph Grid, Cornell Notes, Legal, Three-Column, Weekly Planner, Monthly Planner, and Music Staffs.

### 📑 High-Performance PDF Annotation & Vector Export
- **Import Multi-Page PDFs:** Open textbooks, lecture handouts, and exam papers in seconds.
- **Smooth Zoom & Pan:** Optimized PDF canvas caching ensures buttery-smooth 60fps scrolling on large documents.
- **Vector PDF Export:** Export your annotated notes into vector-sharp PDFs with zero resolution loss.

### 🌓 Dark Mode & Smart Color Inversion
- Switch seamlessly between Light, Dark, and System UI themes.
- **Smart PDF Inversion:** Invert glaring white PDF pages into eye-friendly dark sheets while preserving your colored inks and highlights.

### ☁️ Cloud Sync & Local Backups
- **Google Drive Integration:** Sign in with Google to sync your notebooks across devices automatically.
- **One-Click Local Backups:** Export and restore your complete notebook library in open JSON format.
- **Built-in Trash Bin:** Accidentally deleted a notebook? Recover it anytime from the built-in trash bin.

### 🪄 Natural Gestures & Precision Tools
- **Scribble to Erase:** Scratch back-and-forth over any text or stroke to delete it instantly.
- **SHM Harmonic Filtering:** Intelligent physics detection distinguishes intentional scratch gestures from fast cursive writing.
- **Smart Lasso Selection:** Select handwritten notes, images, text, or shapes. Move, scale, duplicate, rotate, or recolor elements in one tap.

---

## 🆕 What's New in v0.2.1

- 🧊 **3D Shapes Upgrade:** Added 3D Cuboids, Cylinders, and Pyramids with smooth corner rounding and customizable edge curvature.
- 🎯 **Laser Pointer Optimization:** Completely eliminated latency and jitter for laser pointers in live collaboration rooms.
- 🎨 **Redesigned Color Palette:** Refined swatch sizing and quick-pick favorite color presets.
- ✏️ **Stabilization Tuning:** Enhanced stroke stabilizer algorithm for smoother cursive handwriting.
- 🧹 **Eraser Precision:** Fixed standard eraser stroke-splitting and eraser filters.

---

## 🛠️ Tech Stack & Architecture

- **Frontend:** [React 19](https://react.dev/), [TypeScript](https://www.typescriptlang.org/), [Vite](https://vitejs.dev/)
- **Desktop Runtime:** [Tauri 2](https://tauri.app/) (Lightweight Rust backend)
- **PDF Engine:** [PDF.js](https://mozilla.github.io/pdf.js/) & [jsPDF](https://github.com/parallax/jsPDF)
- **Real-Time Collaboration:** [Yjs](https://github.com/yjs/yjs), WebRTC & WebSockets
- **Icons:** [Lucide Icons](https://lucide.dev/)

---

## 🤝 Contributing & Community

We welcome contributions, feature requests, and bug reports!
- 🐛 Found a bug? Open an [Issue](https://github.com/Sahas-developer/S-Note-releases/issues).
- 💡 Have an idea? Submit a [Feature Request](https://github.com/Sahas-developer/S-Note-releases/discussions).
- ⭐ **Show your support:** If you find S-Note helpful, please consider **starring this repository**! It helps more students and creators discover the project.

---

<p align="center">
  Made with ❤️ for students, thinkers, and creators everywhere.
</p>
