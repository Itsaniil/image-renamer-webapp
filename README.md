# Image Renamer Web Application

## 📌 Overview
This is a simple, offline-capable web application that allows users to **upload, preview, rename, and download multiple images** without losing quality.  
It runs entirely in your browser, meaning **no images are uploaded to any server**, ensuring complete privacy and fast performance.

---

## ✨ Key Features
1. **Upload multiple images at once** – Select or drag & drop multiple files.
2. **Preview images before renaming** – See thumbnails of uploaded images.
3. **Automatic renaming in sequence** – Files are renamed in order like: img_1.jpg, img_2.jpg, img_3.jpg ...
4. **Custom start number & prefix** – Choose your own prefix and starting number (e.g., `photo_5` → `photo_5.jpg`).
5. **Drag-and-drop reordering** – Rearrange images before renaming.
6. **Theme toggle** – Switch between Light Mode and Dark Mode.
7. **Download as ZIP** – Get all renamed images in one `.zip` file.
8. **Maintain original image quality** – No compression applied.
9. **Offline usage** – Works without internet once opened.

---

## 🛠️ How It Works
1. **Open the HTML file** in your browser.
2. **Upload images** by clicking the upload area or dragging & dropping them.
3. **Preview your images** in the gallery.
4. **Rearrange images** by dragging them into your preferred order.
5. **Set a prefix and starting number** (optional).
6. **Click "Rename & Download"** – the app will:
- Rename files in the selected order.
- Package them into a ZIP file.
- Trigger the download automatically.
7. **Enjoy your renamed images** with the same quality as the originals.

---

## 📂 Folder Structure
/Image-Renamer-App
│── index.html # Main HTML file
│── style.css # Styling for the app
│── script.js # JavaScript logic
│── README.md # This file
│── jszip.min.js # JSZip library for creating ZIP files

---

## 💻 Technologies Used
- **HTML5** – Page structure & content.
- **CSS3** – Styling and theme support.
- **JavaScript (ES6)** – Image preview, renaming, drag-and-drop, ZIP creation.
- **[JSZip](https://stuk.github.io/jszip/)** – Library for packaging files into a ZIP.

---

## 📦 Installation
No installation required. Just:
1. **Download the project folder**.
2. **Open `index.html`** in any modern browser (Chrome, Edge, Firefox, etc.).
3. Start using it immediately.

---

## 🌐 Browser Compatibility
✅ Chrome  
✅ Firefox  
✅ Edge  
✅ Safari  

---

## 📝 Notes
- The app works completely offline once loaded.
- All image processing happens locally in your browser.
- Drag-and-drop order determines final rename sequence.

---

## 📄 License
This project is free to use and modify for personal or commercial use.

