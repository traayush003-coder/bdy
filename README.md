# Happy Birthday Dr. Abhi 🪷❤️

A premium, highly interactive, magical storybook birthday website created with love from **Ashu** to **Dr. Abhi** on their **24th Birthday (20 July 2026)**.

The website feels like a Disney-style fairytale, featuring a continuous morning sky and pink lotus pond environment, cute animations, and clinical references celebrating Dr. Abhi's medical career.

## ✨ Features

- 🎹 **Web Audio API Celestial Music Box**: Synthesizes a beautiful, copyright-free arpeggiating lullaby with natural stereo-delay and echo feedback, ensuring a bulletproof music playback experience.
- 🎨 **Magical Lotus Pond (2D HTML5 Canvas)**: A custom-built high-performance background drawing water ripples, slowly drifting lily pads, blooming interactive pink lotuses releasing floating hearts, butterflies, fireflies, and custom cursor trails.
- ⚡ **Interactive Pikachu Welcome**: Pikachu wearing a stethoscope waves and chats in a glassmorphic bubble, reacting with yellow electric sparks and cute bounces when tapped.
- 🩺 **Doctor Appreciation**: Features an animated ECG heartbeat pulse, a rotating DNA double helix, and molecular icons paying homage to Dr. Abhi's healing touch.
- 📅 **Memory Timeline**: Elegant cloud-shaped cards detailing core chapters of the journey (First Conversation, First Smile, Cold Winter Night, Keeping Warm).
- ✉️ **Sealed Love Letter**: A classic pink envelope with a red wax heart seal. Clicking opens the envelope to reveal a beautiful handwritten cursive love letter using Google's Italianno font.
- 🖼️ **Polaroid Gallery & Lightbox**: Dynamic scatter-rotated polaroids with hovering lifts and an expandable lightbox viewing the customized illustrations in full fidelity.
- 🎂 **3D-Look Birthday Cake**: A layered CSS birthday cake with flickering candles. Tapping "Make a Wish" blows them out with smoke, triggering massive Canvas Confetti bursts and golden stars rainfall.
- 🪷 **Cinematic Climax Finale**: Sequential message fades combined with rising hearts forming a grand dedication card.

---

## 🛠️ Technology Stack

- **React 19 + TypeScript**: Modern functional hook architecture.
- **Vite**: Ultra-fast next-generation build tool.
- **Tailwind CSS v4**: Utility-first premium styling.
- **Motion/React**: High-fidelity physics-based spring animations.
- **Canvas Confetti**: Celebration explosions.
- **HTML5 2D Canvas**: Immersive, performance-optimized visual particle field.

---

## 🚀 Local Setup & Development

To run this project locally, make sure you have [Node.js](https://nodejs.org) installed, and follow these steps:

1. **Install dependencies**:
   ```bash
   npm install
   ```

2. **Run the development server**:
   ```bash
   npm run dev
   ```
   Open [http://localhost:3000](http://localhost:3000) in your browser.

3. **Verify/Type-check the app**:
   ```bash
   npm run lint
   ```

4. **Build for production**:
   ```bash
   npm run build
   ```

---

## 🌐 Deployment Instructions

### 1. GitHub Pages
1. Install `gh-pages` helper:
   ```bash
   npm install -D gh-pages
   ```
2. In `vite.config.ts`, add the repository name as the base directory:
   ```typescript
   export default defineConfig({
     base: '/your-repo-name/',
     // other configs...
   });
   ```
3. Add a deploy script to `package.json`:
   ```json
   "scripts": {
     "predeploy": "npm run build",
     "deploy": "gh-pages -d dist"
   }
   ```
4. Run deployment:
   ```bash
   npm run deploy
   ```

### 2. Vercel
1. Import your repository into the [Vercel Dashboard](https://vercel.com).
2. Use the **Vite** framework preset.
3. Keep standard settings (Build: `npm run build`, Output Directory: `dist`).
4. Click **Deploy**.

### 3. Netlify
1. Log into [Netlify](https://netlify.com) and click **Add new site** -> **Import from GitHub**.
2. Select your repository.
3. Configure:
   - Build command: `npm run build`
   - Publish directory: `dist`
4. Click **Deploy site**.

---
Created with infinite adoration by **Ashu** for **Dr. Abhi** 🪷❤️.
