# MacBook Pro Clone - Apple Intelligence Ready 💻

[![React](https://img.shields.io/badge/React-19-blue.svg)](https://reactjs.org/)
[![Three.js](https://img.shields.io/badge/Three.js-r182-black.svg)](https://threejs.org/)
[![GSAP](https://img.shields.io/badge/GSAP-3.14-green.svg)](https://greensock.com/gsap/)
[![Vite](https://img.shields.io/badge/Vite-7.0-purple.svg)](https://vitejs.dev/)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-4.0-38B2AC.svg)](https://tailwindcss.com/)

A high-performance, visually stunning Apple MacBook Pro clone built with **React**, **Three.js**, and **GSAP**. This project recreates the premium experience of Apple's website, featuring interactive 3D models, smooth scroll-triggered animations, and a responsive design.

![Apple Banner](https://www.apple.com/v/macbook-pro/al/images/overview/welcome/hero_endframe__b6f9v9o99uue_large.jpg)

## 🚀 Features

- **Interactive 3D Model Viewer**: Explore the MacBook Pro in 14" and 16" sizes with real-time color switching (Space Grey & Dark Metal).
- **GSAP Scroll Animations**: Silky smooth transitions and scroll-bound animations that bring the page to life.
- **Dynamic Feature Showcase**: A custom 3D model scroll-experience where the screen texture changes based on the feature being highlighted.
- **Bento-style Highlights**: Modern masonry layout showcasing the core performance metrics of the M4 chip.
- **Performance-First**: Optimized assets and lazy-loaded 3D components for a snappy experience.
- **Fully Responsive**: Tailored experience for Desktop, Tablet, and Mobile devices.

## 🛠️ Tech Stack

- **Frontend**: [React 19](https://react.dev/)
- **3D Graphics**: [@react-three/fiber](https://docs.pmnd.rs/react-three-fiber) & [@react-three/drei](https://docs.pmnd.rs/drei)
- **Animations**: [GSAP](https://greensock.com/) (GreenSock Animation Platform)
- **Styling**: [Tailwind CSS 4](https://tailwindcss.com/)
- **State Management**: [Zustand](https://github.com/pmndrs/zustand)
- **Build Tool**: [Vite](https://vitejs.dev/)

## 📦 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher recommended)
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/apple-clone.git
   cd apple-clone/main_app
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Run the development server**
   ```bash
   npm run dev
   ```

4. **Build for production**
   ```bash
   npm run build
   ```

## 📂 Project Structure

```text
src/
├── components/         # React components (Hero, Navbar, Features, etc.)
│   ├── models/         # 3D Model components (GLTF/JSX)
│   └── three/          # Three.js specific helpers (Lights, Switcher)
├── constants/          # Site-wide static data and configurations
├── store/              # Zustand state management
├── App.jsx             # Main application entry
└── main.jsx            # React DOM rendering
```

## ✨ Improvements Made

- ✅ **Dynamic Footer**: Automatic year updates.
- ✅ **Accessibility**: Improved image alt tags for better SEO and screen readers.
- ✅ **Performance**: Optimized GSAP ScrollTrigger instances and 3D model loading states.

## 📄 License

This project is for educational purposes. All rights to the Apple brand and product designs belong to Apple Inc.

---
