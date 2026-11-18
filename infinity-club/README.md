<div align="center">

# ♾️ Infinity Club

**The official web presence of Infinity Club — Faculty of MI, University of El Bashir El Ibrahimi.**

![React](https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-r185-black?style=for-the-badge&logo=three.js&logoColor=white)
![Blender](https://img.shields.io/badge/Blender-3D%20%26%20Animation-F5792A?style=for-the-badge&logo=blender&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-Backend-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-Build-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-crimson?style=for-the-badge)

</div>

---

## 📸 Preview

| 3D Model Hero | Flipping Event Cards | Video Registration |
|:---:|:---:|:---:|
| ![3D Queen Model](src/assets/3D%20model.png) | ![Flipping Cards](src/assets/flipping%20cards.png) | ![Video Transformation](src/assets/vid%20transformation.png) |

| **Tablet View** | **Mobile View** |
|:---:|:---:|
| ![iPad Responsive](src/assets/ipad%20responsive.png) | ![Phone Responsive](src/assets/phone%20responsive.png) |

---

## ✨ Features

- ♾️ **Hand-crafted 3D Queen** — fully modeled, textured, and animated in Blender, then brought to life in the browser via Three.js
- 🎬 **Pawn-to-Queen Transformation** — a video of a pawn promoting to a queen, echoing the club's motto *"promote your skills with us, just like a pawn promotes to a queen"*
- 🃏 **Flipping Event Cards** — CSS 3D card flip revealing event details on hover
- 📋 **Member Registration** — form with live validation, persisted to Supabase
- 📱 **Fully Responsive** — fluid layout across desktop, tablet, and mobile
- 🔗 **Connect Section** — one-click copy for email and campus location

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend Framework | React 19 |
| **3D Modeling & Animation** | **Blender** — mesh sculpting, PBR texturing & animation |
| 3D Web Rendering | Three.js r185 + GLTFLoader |
| Backend / Database | Supabase |
| Build Tool | Vite 8 |
| Styling | Vanilla CSS (custom properties) |
| Linting | ESLint + React Hooks plugin |

---

## ⚙️ Technical Highlights

- 🧊 **Built from scratch in Blender** — the queen piece was fully sculpted, PBR-textured and animated entirely in Blender before a single line of web code was written; exported as `.glb` with embedded textures and animation clips
- 🔁 **Blender → Three.js pipeline** — the GLB is loaded via `GLTFLoader` and the embedded `AnimationMixer` clip played in a real-time loop — bridging Blender's offline render world with live WebGL

---

## 🚀 Running Locally

```bash
git clone https://github.com/your-org/infinity-club.git
cd infinity-club
npm install && npm run dev
```

> Copy `.env.example` to `.env` and fill in `VITE_SUPABASE_URL` and `VITE_SUPABASE_ANON_KEY` before starting.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
