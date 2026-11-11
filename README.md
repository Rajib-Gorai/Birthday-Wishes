# 🎁 WishCraft — Magical Animated Wishes & Greeting Cards Portal

A modern, animated celebration & wishing card web application with **5 distinct animated templates**, customizable **To**, **From**, **Headline**, **Heartfelt Message**, **Picture Option** (Upload with instant auto-compression, Curated Gallery, or Image URL), **Web Audio Melodies**, and **Interactive 3D Gift Box Unboxing**.

After creating a wish, it generates an instant, permanent shareable link (WhatsApp, Telegram, X/Twitter, Email, or QR Code) that requires **zero database setup** and is **100% ready to deploy to Vercel for free**.

---

## ✨ Features

- **5 Distinct Animated Celebration Templates**:
  1. 🎈 **Confetti Fiesta & Birthday Bash**: Floating 3D balloons, swaying party streamers, vibrant party gradient, confetti cannons.
  2. 🌟 **Starlight Magic & Celestial Romance**: Midnight cosmic sky, twinkling stars canvas, glowing fireflies, golden halo photo frame, gentle starlight shimmer.
  3. ⚡ **Neon Synthwave & Retro Arcade**: Perspective wireframe moving synth grid, pulsing neon glow typography, 8-bit arcade power-up sound, digital holographic photo frame.
  4. 💖 **Pastel Dream & Sweet Clouds**: Fluffy floating pastel clouds, cotton candy gradient, bouncing hearts, cute stickers, and bubbly playful cards.
  5. 🥂 **Champagne Royalty & Onyx Elegance**: Obsidian glass cards, gold foil filigree corners, rising effervescent champagne bubbles, golden confetti toasts.

- **Personalization**:
  - **To** (Recipient Name)
  - **From** (Sender Name)
  - **Headline / Title** (e.g., *Happy 25th Birthday!*, *Forever & Always*, *Huge Congratulations!*)
  - **Heartfelt Message** with AI-inspired prompt chips (Emotional, Witty & Funny, Poetic, Short & Punchy).
  - **Picture Option**:
    - **Upload Your Own Photo**: Automatically compressed & downscaled client-side with HTML5 Canvas so it fits directly into the shareable link.
    - **Curated Celebratory Gallery**: Birthday cakes with candles, balloons, champagne toasts, fireworks, roses, cute pets, sunsets, and galaxies.
    - **Custom Image Link**: Paste any direct URL.

- **Interactive 3D Gift Box Unbox Mode**:
  - Senders can toggle "Wrap as Interactive Gift Box".
  - Recipients see a shaking 3D surprise package with *"You received a surprise from [From]! Tap to Open 🎁"*.
  - Tapping plays a cheerful fanfare chime and bursts confetti everywhere before revealing the card!

- **Melody & Sound Effects Engine**:
  - Synthesized using browser native **Web Audio API** (`AudioContext`).
  - No external MP3 downloads or broken audio links!
  - 5 soundscapes: Festive Fanfare, Celestial Music Box, 8-bit Retro Arcade, Romantic Harp, Champagne Toast.

- **Instant Zero-Database Shareable Links**:
  - The entire card state is compressed into a URL hash using `lz-string`.
  - Shareable across WhatsApp, Telegram, Twitter, Email, or SMS.
  - Printable / scannable **QR Code generator** included.

---

## 🚀 How to Deploy on Vercel

### Method 1: Deploy with Vercel CLI (Fastest)

1. Open your terminal in this folder:
   ```bash
   cd wishcraft
   ```
2. Run:
   ```bash
   npx vercel
   ```
3. Follow the 3 quick prompts (defaults are pre-configured for Vite in `vercel.json`).
4. Your website is live worldwide with HTTPS!

### Method 2: Deploy via GitHub & Vercel Dashboard

1. Push this folder to a GitHub repository.
2. Go to [vercel.com/new](https://vercel.com/new).
3. Import your GitHub repository.
4. Framework Preset will auto-detect **Vite**.
5. Click **Deploy**!

---

## 💻 Local Development

```bash
# Install dependencies
npm install

# Start local dev server
npm run dev

# Build for production
npm run build

# Preview production build locally
npm run preview
```
