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

<div align="center">

<table>
<tr>
<td align="center">

<b>Install Gixplay (TWA / PWA)</b><br><br>
<img src="https://ik.imagekit.io/sbsjhivv8/Download.gif" width="260" />

</td>
<td align="center">

<b>Search Using URL & Create Playlists</b><br><br>
<img src="https://ik.imagekit.io/sbsjhivv8/VN20260111_105716-ezgif.com-video-to-gif-converter.gif" width="260" />

</td>
</tr>
</table>

</div>


<hr style="border: 1px solid #38B2AC;" />

<div align="center">

### Source code will be revealed at **300 stars**

Help us reach the goal by starring this repository!

[![Star this repo](https://img.shields.io/badge/⭐_Star_This_Repo-238636?style=for-the-badge&logo=github&logoColor=white)](https://github.com/X0U8/Gixplay-)

**Current Progress:**

![Stars](https://img.shields.io/github/stars/X0U8/Gixplay-?style=for-the-badge&color=yellow)

</div>
<hr style="border: 1px solid #38B2AC;" />

### How To Use All Features 
<div align="center">
<table>
  <tr>
    <td width="35%" align="center">
      <img src="https://ik.imagekit.io/sbsjhivv8/IMG-20260111-WA0004.jpg" width="100%">
    </td>
    <td>
      <strong style="color:#9CA3AF">How to Use Stable Search Page</strong>
      <ul>
  <li>The stable page uses the official YouTube Search API for searching songs and videos</li>
  <li>YouTube charges around 100 API units for each search request, which is why this page only allows one search per hour</li>
  <li>This limit helps control API usage and prevents exceeding the daily quota</li>
  <li>For additional searches, users can switch to a second search server that performs YouTube searching using a Python backend</li>
  <li>On the top right corner of the page, there is a button called “Switch Search Server”</li>
  <li>Clicking this button allows the user to move to the different search server powered by the Python-based backend</li>
  <li>Below the switch button, there is an option for direct search using a YouTube URL</li>
  <li>To use direct search, the user can go to YouTube, search for the desired video, click the share button, copy the link, and paste it into the input field</li>
  <li>After pasting the link, the app fetches the video details and allows the user to add the video to a playlist</li>
  <li>This direct search process is demonstrated in the video shown above</li>
  <li>Below the direct URL search option, there is a button to search using the official YouTube API</li>
  <li>This official API-based search is restricted to only once per hour due to API cost and quota limitations</li>
      </ul>
    </td>
  </tr>

  <tr>
    <td align="center">
      <img src="https://ik.imagekit.io/sbsjhivv8/IMG-20260111-WA0002.jpg" width="100%">
    </td>
    <td>
      <strong>Showing Server Offline In Second Search Server</strong>
      <ul>
  <li>This page allows users to search directly using the song name or artist name</li>
  <li>A Python backend server is running in the background to perform these searches</li>
  <li>This search system is completely free to use for users</li>
  <li>Since web servers are costly to maintain, the backend server may sometimes go offline automatically</li>
  <li><strong>If the server shows offline, still try searching and wait for 30 to 40 seconds maximum — the server will automatically start again and you will be able to search normally</strong></li>
  <li>This temporary auto-shutdown behavior helps reduce server costs</li>
  <li>If the server is still not online after one minute, try reloading or reopening the app and then check again</li>
  <li>If it still shows offline, it likely means the server is temporarily closed due to high traffic</li>
  <li>In that case, users can switch to the stable search page and continue searching using the official YouTube search system</li>
</ul>
    </td>
  </tr>

  <tr>
    <td align="center">
      <img src="https://ik.imagekit.io/sbsjhivv8/IMG-20260111-WA0003.jpg" width="100%">
    </td>
    <td>
      <strong>How to Use Second Search Server</strong>
      <ul>
  <li>To use the second search server, first ensure the server status is online</li>
  <li>Enter your search keyword directly and click the search button</li>
  <li>To protect the system from bots and automated abuse, a small math question will appear before the search is processed</li>
  <li>This verification step helps reduce misuse of the free backend service</li>
  <li>After verification, users can search normally and add music directly to playlists, just like on the stable search page</li>
  <li>Below the search section, there is a button labeled <strong>Switch to Stable</strong> to return to the main search page at any time</li>
        </ul>
    </td>
  </tr>

  <tr>
    <td align="center">
      <img src="https://ik.imagekit.io/sbsjhivv8/IMG-20260111-WA0005.jpg" width="100%">
    </td>
    <td>
      <strong>How to Use Playlist</strong>
      <ul>
        <li>Create or join rooms</li>
        <li>Short room codes</li>
        <li>No login required</li>
      </ul>
    </td>
  </tr>

  <tr>
    <td align="center">
      <img src="https://via.placeholder.com/300x200/0b0b0b/38B2AC?text=Preview+5" width="100%">
    </td>
    <td>
      <strong>Shared Queue</strong>
      <ul>
        <li>Everyone can add songs</li>
        <li>Auto play next track</li>
        <li>Real-time sync</li>
      </ul>
    </td>
  </tr>

  <tr>
    <td align="center">
      <img src="https://via.placeholder.com/300x200/0b0b0b/38B2AC?text=Preview+6" width="100%">
    </td>
    <td>
      <strong>Playback Controls</strong>
      <ul>
        <li>Play, pause, seek sync</li>
        <li>Background playback</li>
        <li>Mobile optimized controls</li>
      </ul>
    </td>
  </tr>

  <tr>
    <td align="center">
      <img src="https://via.placeholder.com/300x200/0b0b0b/38B2AC?text=Preview+7" width="100%">
    </td>
    <td>
      <strong>Listening Analytics</strong>
      <ul>
        <li>Daily and weekly stats</li>
        <li>Streak tracking</li>
        <li>Heatmap view</li>
      </ul>
    </td>
  </tr>

  <tr>
    <td align="center">
      <img src="https://via.placeholder.com/300x200/0b0b0b/38B2AC?text=Preview+8" width="100%">
    </td>
    <td>
      <strong>Data Export</strong>
      <ul>
        <li>One file backup</li>
        <li>Includes playlists and history</li>
        <li>No cloud dependency</li>
      </ul>
    </td>
  </tr>

  <tr>
    <td align="center">
      <img src="https://via.placeholder.com/300x200/0b0b0b/38B2AC?text=Preview+9" width="100%">
    </td>
    <td>
      <strong>Data Import</strong>
      <ul>
        <li>Restore full library</li>
        <li>Fast local processing</li>
        <li>Offline supported</li>
      </ul>
    </td>
  </tr>

  <tr>
    <td align="center">
      <img src="https://via.placeholder.com/300x200/0b0b0b/38B2AC?text=Preview+10" width="100%">
    </td>
    <td>
      <strong>Privacy First Design</strong>
      <ul>
        <li>No accounts</li>
        <li>No tracking</li>
        <li>No remote storage</li>
      </ul>
    </td>
  </tr>
</table>

<hr style="border: 1px solid #38B2AC;" />

</div>

### Key Features

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

 ## Support

If you find this project helpful, consider supporting me:

[![Buy Me A Chai](https://buymeachai.ezee.li/assets/images/buymeachai-button.png)](https://buymeachai.ezee.li/x0u8)


<div align="center">
  <p>© Gixplay — Personal music, shared moments, full control.</p>
</div>
