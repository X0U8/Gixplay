<div align="center">
  <img src="https://ik.imagekit.io/sbsjhivv8/IMG-20260107-WA0003.jpg" alt="Gixplay Logo" width="120" style="border-radius: 50%; border: 2px solid #38B2AC;" />
  <h1>GIXPLAY</h1>
  <p><strong>A mobile-first, YouTube-powered music streaming PWA with a pure black theme, offline capabilities, shared rooms, and deep personal analytics.</strong></p>

  <p>
    <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
    <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
    <img src="https://img.shields.io/badge/IndexedDB-005395?style=for-the-badge&logo=sqlite&logoColor=white" />
    <img src="https://img.shields.io/badge/PWA-5A0FC8?style=for-the-badge&logo=pwa&logoColor=white" />
  </p>
</div>

<hr style="border: 1px solid #38B2AC;" />

## About Gixplay

**Gixplay** is a privacy-first, mobile-optimized music streaming Progressive Web App designed for personal and small-group use.  
It allows users to search, play, and organize music sourced from YouTube while keeping **all personal data fully local** to the device.

| NO ACCOUNTS | NO CLOUD PROFILES | NO ADS | NO TRACKING |
| :---: | :---: | :---: | :---: |

Your playlists, listening history, analytics, and identity stay on your device.

<hr style="border: 1px solid #38B2AC;" />

<div align="center">

### Source code will be revealed at **300 stars**

Help us reach the goal by starring this repository!

[![Star this repo](https://img.shields.io/badge/⭐_Star_This_Repo-238636?style=for-the-badge&logo=github&logoColor=white)](https://github.com/X0U8/Gixplay-)

**Current Progress:**

![Stars](https://img.shields.io/github/stars/X0U8/Gixplay-?style=for-the-badge&color=yellow)

</div>

## Key Features
njn

| Category | Feature Detail |
| :--- | :--- |
| **Streaming** | **YouTube-Based Playback**: Search for tracks or instantly add music using direct YouTube URLs. |
| **UI** | **Pure Black OLED Interface**: Minimal, distraction-free UI optimized for night usage and battery saving. |
| **Storage** | **Local-Only Data**: Playlists, tracks, analytics, and user identity are stored in IndexedDB / localStorage. |
| **App** | **Installable Progressive Web App**: Runs like a native app with offline access to saved data. |
| **Playback** | **Background Audio Support**: Audio continues while the app is minimized (browser dependent). |
| **Playlists** | **Fast Management**: Create, edit, and manage playlists with gesture-based controls. |
| **Analytics** | **Listening Insights**: Weekly, monthly, and yearly charts, streak tracking, and activity heatmaps. |
| **Backup** | **Data Portability**: Export and import the complete local library using a single file. |
| **Privacy** | **Zero Tracking**: No login, no telemetry, no remote analytics, no user profiling. |

<hr style="border: 1px solid #38B2AC;" />

## Rooms (Shared Listening)

Gixplay includes a **real-time shared room feature** that allows multiple users to listen together.

### How Rooms Work
* Users enter a **display name** (stored locally on their device)
* A room can be **created or joined using a short code**
* Any participant can:
  * Paste a YouTube URL
  * Start playback
  * Pause or resume the current track
  * Add songs to the queue

**Note:** There is **no host system** — every participant has equal control.

### Playback Sync
The following are synchronized across all connected devices in real time:
* The currently playing track
* Playback state (play / pause)
* Seek position
* Queue order

If one user changes the track, seeks to a new timestamp, or pauses playback, all connected devices update automatically.

### Queue System
* If a track is already playing, newly added tracks go into a shared queue.
* When the current song ends, the next track auto-plays.
* If no song is playing, users can manually select a queued track to start playback.

### Live Activity Log
* Actions like *“played a song”*, *“added to queue”*, *“paused playback”* appear in a live log.
* Each user name is color-coded consistently.
* Logs exist only for the session and are not permanently stored.

<hr style="border: 1px solid #38B2AC;" />

## Architecture Overview

> **Search & Metadata** > Uses public YouTube data endpoints for discovery and metadata.

> **Playback Engine** > Controlled YouTube iframe player used for streaming and background audio.

> **Local Database** > IndexedDB stores tracks, playlists, analytics, and playback history.

> **Room Sync Engine** > Lightweight real-time database syncs room state (track, position, status, queue).

> **Analytics System** > Playback events are processed locally to generate insights without external services.

<hr style="border: 1px solid #38B2AC;" />

## Platform Support

* **Android** browsers
* **iOS** browsers
* **Desktop** browsers
* **Installable PWA**
* **Trusted Web Activity (TWA)** compatible

<hr style="border: 1px solid #38B2AC;" />

## Usage Notice
Gixplay is intended for **personal and educational use**. It does not host media, does not redistribute content, and relies on publicly accessible YouTube playback mechanisms. All rights belong to their respective content owners.

## Project Status
* Actively developed
* Private distribution
* Still Not open source

 ## ☕ Support

If you find this project helpful, consider supporting me:

[![Buy Me A Chai](https://buymeachai.ezee.li/assets/images/buymeachai-button.png)](https://buymeachai.ezee.li/x0u8)


<div align="center">
  <p>© Gixplay — Personal music, shared moments, full control.</p>
</div>
