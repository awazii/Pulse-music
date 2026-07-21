<div align="center">
  <img src="https://img.shields.io/badge/JAVASCRIPT-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" alt="JavaScript" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/SPOTIFY_API-1DB954?style=for-the-badge&logo=spotify&logoColor=white" alt="Spotify API" />

  <br/>
  <br/>
  <h1>⚡ Pulse Music</h1>
  <p><b>A high-fidelity, frontend-only music streaming client, powered by a unified dataset built from the Spotify and Wikipedia APIs.</b></p>

  <a href="https://pulse-awazii.netlify.app/"><strong>🛑 View Live Demo</strong></a>
</div>
<br/>

> **Pulse** is a complex, strict client-side web application designed to deliver a premium music browsing experience. It demonstrates advanced DOM manipulation, a custom multi-API data pipeline, and custom media control logic without relying on heavy frontend frameworks or a custom backend.

---

## 📸 Interface Preview
<img width="1907" height="917" alt="Screenshot 2026-07-14 084039" src="https://github.com/user-attachments/assets/8b2ed1b9-2a90-4f7b-9a7a-fdc6c585ca93" />

---

## 🧠 Frontend Architecture & Logic

Building a comprehensive music client in Vanilla JS requires precise synchronization between structured data, browser media APIs, and the DOM.

### 1. Dual-API Data Pipeline
Engineered a data-generation pipeline using the Fetch API to pull and merge data from two distinct sources: the **Spotify API** (track metadata, credits, album art) and the **Wikipedia API** (extended artist bios and context). This pipeline authenticates with Spotify's client-credentials flow, resolves per-track and per-artist details, and consolidates everything into a single structured `songs.json` dataset — which the live app then loads as its single source of truth, keeping the deployed client fast and framework-free.

### 2. Advanced Queue & Playback Engine
Bypassed standard HTML5 `<audio>` limitations by engineering a completely custom playback interface. Built complex data structures in pure JavaScript to handle a dynamic **Queue System**, complete with custom algorithmic logic for **Shuffle** and **Repeat** functionalities, ensuring state consistency during playback.

### 3. Dynamic DOM Rendering
Implemented modular JavaScript functions to dynamically generate highly relational UI views, including "Recently Played", "Daily Mixes", "Most Played", and dedicated "Album Pages." The UI is fully responsive, utilizing CSS Grid and Flexbox to maintain a native-app feel across all device sizes.

---

## 🚀 Core Features

- **Multi-API Data Pipeline:** Track catalog built from Spotify, enriched with artist bios from Wikipedia, consolidated into one unified dataset.
- **Custom Playback Controls:** Full media suite including play, pause, mute, seek, volume, shuffle, and repeat.
- **Dynamic Queue System:** Add, remove, and track upcoming songs in real-time.
- **Algorithmic Feeds:** Auto-generated UI states for Daily Mixes, Most Played, and user-specific listening history.
- **Responsive Layout:** Pixel-perfect scaling from desktop down to mobile viewports.
