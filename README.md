# csc.pduam.cdn

> Public CDN repository for the **Department of Computer Science**, Pandit Deendayal Upadhyaya Adarsha Mahavidyalaya (PDUAM), Amjonga, Assam.

Images and media assets stored here are served via [jsDelivr](https://www.jsdelivr.com/) CDN for use on the official CS Department website.

---

## 📁 Folder Structure

```
csc.pduam.cdn/
└── uploads/
     images/
        ├── gallery/        → all gallery photos
        ├── events/         → event posters & photos
        ├── faculty/        → faculty profile photos
        ├── alumni/         → alumni photos
        ├── archives/       → archive images
        ├── students/       → student photos
        ├── tribute/        → tribute page images
        ├── index/          → homepage slideshow/banner images
        └── og/             → og-image.jpg, og-image.png

    ├── files/
    │   ├── notifications/  → all PDFs (notices, circulars)
    │    │                     2245-202408191302..., DdIGILIFE_Wall_magaz...
    │    └── documents/      → any other downloadable files
    └── assets/
        └── logos/            # Department logos & branding
```

---

## 🔗 CDN URL Format

```
https://cdn.jsdelivr.net/gh/cscpduam-alt/csc.pduam.cdn@main/uploads/filename.webp
```

---

## ⚙️ How it works

- Assets are uploaded via a self-hosted [Picser](https://github.com/sh20raj/picser) instance
- Files are committed to this repository automatically via GitHub API
- jsDelivr serves the files globally via its CDN network
- Used for gallery images, event posters, faculty photos, and slideshow banners on the department website

---

## 🌐 Used By

- [PDUAM CS Department Website](https://csc.pduam.dpdns.org)

---

## 📌 Note

This repository is **public** as required by jsDelivr for CDN delivery.  
Do **not** upload sensitive or private files here.

---

## 🛠️ Note for Maintainers

**Always compress images before uploading** to keep the repository size minimal and ensure fast CDN delivery.

Recommended free tools:

| Tool | Link | Best For |
|------|------|----------|
| **Squoosh** | [squoosh.app](https://squoosh.app) | Single image, best quality control, export as WebP |
| **TinyPNG** | [tinypng.com](https://tinypng.com) | Bulk PNG/JPG compression, simple drag & drop |
| **Compressor.io** | [compressor.io](https://compressor.io) | Quick single image, supports WebP/JPEG/PNG/SVG |

**Tips:**
- Always export as **WebP** format — smallest size, best quality
- Target file size: **under 200KB** per image
- Raw phone photos (3–8MB) should be compressed down to **80–150KB** before uploading

---

*Maintained by the Department of Computer Science, PDUAM, Amjonga, Assam.*
