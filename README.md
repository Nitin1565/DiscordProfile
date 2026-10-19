# SunGodNika // Bio

A high-end aesthetic bio-link page themed after Sun God Nika and Valorant Neon with live Discord presence, particle canvas, audio player, and background video.

---

## ⚡ Adding Custom Music & Custom Background Video

All customizations can be configured in **[config.js](config.js)**:

### 1. Custom Background Video
- **Local video file**:
  1. Drop your video file (e.g. `bg.mp4`) into the [`public/`](public/) directory.
  2. Open [config.js](config.js) and set:
     ```javascript
     videoUrl: "/bg.mp4",
     ```
- **Online video URL**:
  Set `videoUrl` in [config.js](config.js) to any direct MP4 or WebM URL:
  ```javascript
  videoUrl: "https://your-domain.com/video.mp4",
  ```

### 2. Custom Music / Audio
- **Local music file**:
  1. Drop your audio file (e.g. `music.mp3`) into the [`public/`](public/) directory.
  2. Open [config.js](config.js) and set:
     ```javascript
     audioUrl: "/music.mp3",
     trackTitle: "My Favorite Song",
     trackArtist: "Artist Name",
     trackCover: "/cover.jpg", // optional cover art in public/
     ```
- **Online audio URL**:
  Set `audioUrl` in [config.js](config.js) to any direct audio stream or MP3 URL:
  ```javascript
  audioUrl: "https://your-domain.com/song.mp3",
  ```
- **Procedural Synth Engine**:
  Leave `audioUrl: ""` to use the built-in procedural Drums of Liberation & Neon Phonk synthesizer engine!

---

## 🚀 Running the Project Locally

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the development server:
   ```bash
   npm run dev
   ```

3. Open [http://localhost:3000](http://localhost:3000) in your browser.
