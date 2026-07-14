<div align="center">
  <img src="https://img.shields.io/badge/JAVASCRIPT-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" alt="JavaScript" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/SPOTIFY_API-1DB954?style=for-the-badge&logo=spotify&logoColor=white" alt="Spotify API" />
  
  <br/>
  <br/>

  <h1>⚡ Pulse Music</h1>
  <p><b>A high-fidelity, frontend-only music streaming client driven by the Spotify and Wikipedia REST APIs.</b></p>
  
  <a href="https://pulse-awazii.netlify.app/"><strong>🛑 View Live Demo</strong></a>
</div>

<br/>

> **Pulse** is a complex, strict client-side web application designed to deliver a premium music browsing experience. It demonstrates advanced DOM manipulation, multi-API data orchestration, and custom media control logic without relying on heavy frontend frameworks or a custom backend.

---

## 📸 Interface Preview

<img width="1907" height="917" alt="Screenshot 2026-07-14 084039" src="https://github.com/user-attachments/assets/8b2ed1b9-2a90-4f7b-9a7a-fdc6c585ca93" />


---

## 🧠 Frontend Architecture & Logic

Building a comprehensive music client in Vanilla JS requires precise synchronization between asynchronous network payloads, browser media APIs, and the DOM.

### 1. Dual-API Data Aggregation
Engineered a robust data layer using the Fetch API to asynchronously retrieve and merge data from two distinct sources: the **Spotify API** (handling tracks, daily mixes, and albums) and the **Wikipedia API** (fetching extended artist context and details). This required complex JSON parsing, error handling, and loading state management.

### 2. Advanced Queue & Playback Engine
Bypassed standard HTML5 `<audio>` limitations by engineering a completely custom playback interface. Built complex data structures in pure JavaScript to handle a dynamic **Queue System**, complete with custom algorithmic logic for **Shuffle** and **Repeat** functionalities, ensuring state consistency during playback.

### 3. Dynamic DOM Rendering
Implemented modular JavaScript functions to dynamically generate highly relational UI views, including "Recently Played", "Daily Mixes", "Most Played", and dedicated "Album Pages." The UI is fully responsive, utilizing CSS Grid and Flexbox to maintain a native-app feel across all device sizes.

---

## 🚀 Core Features

- **Multi-API Integration:** Live catalog fetching via Spotify, enriched with artist details from Wikipedia.
- **Custom Playback Controls:** Full media suite including play, pause, seek, volume, shuffle, and repeat.
- **Dynamic Queue System:** Add, remove, and track upcoming songs in real-time.
- **Algorithmic Feeds:** Auto-generated UI states for Daily Mixes and user-specific listening history.
- **Responsive Layout:** Pixel-perfect scaling from desktop down to mobile viewports.

---
