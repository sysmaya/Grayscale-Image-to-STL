# 🏔️ Image Heightmap Grayscale → STL Generator

Convert any grayscale image into a **3D STL model** directly in your browser.  
This tool runs **100% client-side** using [Three.js](https://threejs.org) — no server uploads, no registration, and no data tracking.  

It’s ideal for creating reliefs and heightmaps for **CNC milling**, **3D printing**, or **artistic bas-reliefs**.

---

## 🌐 Live Demo

👉 **Try it now:**  
[https://online-tools.muisca.co/en/tools/generators/heightmap-grayscale-to-stl](https://online-tools.muisca.co/en/tools/generators/heightmap-grayscale-to-stl)

![Preview](https://online-tools.muisca.co/images/generadores-heightmap-grayscale-a-stl.png)

---

## ✨ Features

- 🖼️ Load **JPG** or **PNG** images directly from your computer  
- 🎚️ Adjust **height scale**, **brightness**, and **contrast** before generating  
- 💡 Real-time lighting and material preview using Three.js  
- 🎨 Change the color of the model interactively  
- 💾 Export your creation as an **STL** file ready for printing or CNC  
- 🧠 All processing is done **locally in your browser** — your images never leave your device  
- ⚡ Built with performance and simplicity in mind  

---

## 🧩 How It Works

1. Select an image in grayscale (white = high, black = low).  
2. Adjust parameters such as height, brightness, and contrast.  
3. Click **Generate 3D** — the tool creates a heightmap mesh in real-time.  
4. Download the resulting **STL** file for CNC or 3D printing.  

Under the hood, the tool:
- Converts the image to grayscale (if not already).  
- Maps pixel luminance to Z-axis displacement.  
- Uses a custom **Three.js plane geometry** to create the relief mesh.  

---

## 🛠️ Built With

- [Three.js](https://threejs.org/) — 3D rendering engine  
- [JavaScript ES Modules](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules)  
- [Bootstrap 4.4.1](https://getbootstrap.com/) — UI layout  
- ❤️ Pure client-side logic — no backend required  

---


## 🚀 Quick Start (for developers)

If you want to host your own version locally:

```bash
git clone https://github.com/YOUR_USERNAME/heightmap-grayscale-to-stl.git
cd heightmap-grayscale-to-stl
# Open index.html in your browser

