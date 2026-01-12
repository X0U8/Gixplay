<div align="center">
  <img src="https://ik.imagekit.io/sbsjhivv8/IMG-20260107-WA0003.jpg" alt="Gixplay Logo" width="120" style="border-radius: 50%; border: 2px solid #38B2AC;" />
  <h1>GIXPLAY</h1>
  <p><strong>A mobile-first, YouTube-powered music streaming PWA with a pure black theme, offline capabilities, shared rooms, and deep personal analytics.</strong></p>
  <p>Playback System Optimized for Samsung Internet</p>

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

---

<div align="center">

###  Installation Options

</div>

<div align="center">

<table>
<tr>
<td align="center" width="50%">

<b>Standard PWA Install (Fast & Simple)</b><br>
<small>No background audio (browser limitation)</small><br><br>

<img src="https://ik.imagekit.io/sbsjhivv8/Download.gif" width="260" />

<br><br>
Open site → Install from browser menu

</td>

<td align="center" width="50%">

<b>APK Install (Background Audio Supported)</b><br>
<small>Powered by Samsung Internet</small><br><br>

<a href="https://github.com/X0U8/Gixplay-/releases" target="_blank">
  <img src="https://img.shields.io/badge/Download%20APK-GitHub%20Releases-black?style=for-the-badge&logo=github" />
</a>

<br><br>

<img src="https://ik.imagekit.io/sbsjhivv8/VN20260112_115416.gif?updatedAt=1768199503182" width="260" />

</td>
</tr>
</table>

</div>

---

<div align="center">

###  Search Music & Create Playlists

<img src="https://ik.imagekit.io/sbsjhivv8/VN20260111_105716-ezgif.com-video-to-gif-converter.gif" width="260" />

</div>

---

> **Note:**  
> Background audio playback is technically restricted in most browsers.  
> The APK version uses Samsung Internet to enable reliable background music playback without server-side streaming or media extraction.

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
  <li>
    The Playlist page is simple, clean, and very easy to use. After searching for songs, you will see a <b>+ icon</b> beside each track that allows you to add it directly to a playlist with one tap.
  </li>

  <li>
    You can also add songs while music is already playing by clicking the <b>+ icon</b> from the player screen and saving the current track instantly.
  </li>

  <li>
    All playlists are stored <b>completely locally on your device</b>. Nothing is uploaded to any server, so your music data always stays private.
  </li>

  <li>
    Playlists can be shared easily. When you press the share button, the required playlist data is converted into JSON and copied to your clipboard and share it anywhere you like.
  </li>

  <li>
    <b>We strongly suggest using playlists</b> — they help users find and play music much faster, and also help reduce search costs, keeping the app smooth and efficient for everyone.
  </li>

  <li>
    Just like other music apps, playlists support normal play mode (songs play one by one), shuffle mode (random order), and repeat options where you can loop a single song or loop the entire playlist forever.
  </li>
</ul>
    </td>
  </tr>

  <tr>
    <td align="center">
      <img src="https://ik.imagekit.io/sbsjhivv8/IMG-20260112-WA0003.jpg" width="100%">
    </td>
    <td>
      <strong>How to Share Playlist</strong>
      <ul>
  <li>
    To share a playlist, open the playlist page and tap the <b>Share</b> button. A JSON code of the playlist will be copied to your clipboard, which you can then share anywhere you like (chat, notes, message, etc.).
  </li>

  <li>
    On the receiving side, go to the Playlists page and tap the <b>+</b> button to create a new playlist.
  </li>

  <li>
    You will see two fields: one for the playlist name and another for pasting the playlist JSON code.
  </li>

  <li>
    Pasting the JSON is <b>optional</b>. If you only enter a name and create the playlist, it will be created as an empty playlist without any songs.
  </li>

  <li>
    If you paste the shared JSON code and then press create, the playlist will be generated instantly and all songs will be added automatically.
  </li>
</ul>
    </td>
  </tr>

  <tr>
    <td align="center">
      <img src="https://ik.imagekit.io/sbsjhivv8/IMG-20260112-WA0004.jpg?updatedAt=1768210654750" width="100%">
    </td>
    <td>
      <strong>How to Creat or Join a Room For Listening Together</strong>
      <ul>
  <li>
    To listen to music together, go to the <b>Room</b> page. You will find the room button at the top of the Playlists page, right beside the <b>+</b> icon (which is used to create a new playlist).
  </li>

  <li>
    On the Room page, you will see two options: one to <b>create a new room</b> and another to <b>enter a room code</b> to join an existing room.
  </li>

  <li>
    Below these options, there is a live activity log box. Since rooms are connected to a server, this log shows what is happening in real time.
  </li>

  <li>
    Although the server is very reliable, smooth, and almost never fails, in case creating or joining a room does fail for any reason, the exact error or status will appear in the log box so you can see what went wrong.
  </li>

  <li>
    You can simply retry again if it fails, and it will usually work immediately.
  </li>

  <li>
    Once a room is successfully created, the room code will be displayed at the top of the room player page so you can easily share it with friends.
  </li>
</ul>
    </td>
  </tr>

  <tr>
    <td align="center">
      <img src="https://ik.imagekit.io/sbsjhivv8/IMG-20260112-WA0005.jpg?updatedAt=1768210806868" width="100%">
    </td>
    <td>
      <strong>What Are the Features Present on Room</strong>
      <ul>
  <li>
    <b>Room Code:</b> At the top of the room page, you will always find the unique room code for that room, which you can share with others to join.
  </li>

  <li>
    <b>User Identity:</b> When opening the room feature for the first time on a device, the user is asked to enter a name. This name is saved locally on the device and used inside the room.
    <br />
    <b>Note:</b> Once the name is set, it cannot be changed later from the app.
  </li>

  <li>
    <b>Inbuilt Chat System:</b> There is a built-in chat system where users in the room can talk to each other. This helps everyone communicate without switching to any other chatting app.
  </li>

  <li>
    <b>Live Activity Logs:</b> Below the chat section, there is a live log area where users can see real-time actions such as who played a song, paused it, resumed it, or jumped to a different timestamp.
  </li>

  <li>
    <b>Play Music / Video Together:</b> Users can play music or videos together. Just copy a YouTube URL and paste it into the room — the video will start playing instantly for everyone in the room.
  </li>

  <li>
    <b>Queue Songs:</b> While a song is already playing, users can paste another YouTube URL to add it to the queue. The queued video will appear on the page for everyone, and the action will also be shown in the live logs.
  </li>

  <li>
    <b>No Member or Playback Limits:</b> There is no limit on how many people can join a room and no limit on how many videos can be played or queued — feel free to enjoy without restrictions.
  </li>

  <li>
    <b>Room Cleanup:</b> When everyone is done, please delete the room using the delete button on the top-right corner of the room screen. This helps keep things clean and avoids unused rooms staying active.
  </li>
</ul>
    </td>
  </tr>

  <tr>
    <td align="center">
      <img src="https://ik.imagekit.io/sbsjhivv8/IMG-20260112-WA0008.jpg?updatedAt=1768212448601" width="100%">
    </td>
    <td>
      <strong>What is Analytics</strong>
      <ul>
  <li>
    <b>Overview at the Top:</b> The analytics page starts with three important stats:
    <br />• <b>Total Plays</b> – counts how many times you played audio. Each play adds +1, but there is a 30-second cooldown. If you replay within 30 seconds, it will not be counted. This helps keep the data accurate and avoids fake or accidental repeats.
    <br />• <b>Total Active Days</b> – shows how many different days you have used the app to listen to music.
    <br />• <b>Joining Date</b> – the date when you first started using the app.
  </li>

  <li>
    <b>Listening Habit Graph:</b> Below the stats, there is a detailed line graph showing <b>Total Plays vs Time</b>. This helps visualize your listening habit clearly.
    Users can switch between <b>daily, monthly, or yearly</b> views to understand their activity in different time ranges.
  </li>

  <li>
    <b>Yearly Heatmap:</b> Under the graph, there is a full yearly heatmap that shows how active you were on each day of the year.
    Users can also switch between different years to view past listening activity patterns.
  </li>

  <li>
    <b>Top Tracks & Artists:</b> Next, the app shows your <b>Top 10 tracks</b> and <b>Top 10 artists</b>.
    <br />
    Artists are detected using the YouTube channel name (since most songs are uploaded by official channels), and track names come from the YouTube video titles.
  </li>

  <li>
    <b>Load All Option:</b> If you have listened to more than 10 tracks or artists, a <b>"Load All"</b> button will appear.
    Clicking it lets you view the complete list of all tracks or artists you have listened to.
    Beside each track or artist name, the app shows <b>how many times</b> you played it.
  </li>

  <li>
    <b>Data Management:</b> At the bottom of the analytics page, there is a data management section where users can <b>export</b> or <b>import</b> their analytics data.
    This allows full control over your listening history and statistics.
    More details about how importing and exporting works are explained in the section below.
  </li>
</ul>
    </td>
  </tr>

  <tr>
    <td align="center">
      <img src="https://ik.imagekit.io/sbsjhivv8/IMG-20260112-WA0009.jpg?updatedAt=1768212448659" width="100%">
    </td>
    <td>
      <strong>How to Export & Import Data Of Analytics</strong>
      <ul>
  <li>
    <b>Import & Export Analytics Data:</b> Analytics data can be shared or backed up in the same way as playlists.
    To export, simply click the <b>Export</b> button and the app will copy an <b>encrypted data string</b> to your clipboard.
  </li>

  <li>
    To import data, click the <b>Import</b> button. A modal will open where you can paste the encrypted text and confirm.
    <br />
    <b>Important:</b> importing will <b>override your existing analytics data</b>, so make sure to export your current data first if you want a backup.
  </li>

  <li>
    <b>Secure by Design:</b> This app uses its own <b>encryption system</b> to process analytics data, so users cannot easily modify or fake the data manually.
  </li>

  <li>
    The exported file contains <b>everything</b> related to analytics:
    <br />• All tracks
    <br />• All artists
    <br />• Full yearly heatmaps
    <br />• Total plays, active days, joining date
    <br />• And all other statistics shown on the analytics page
  </li>
</ul>
    </td>
  </tr>

  <tr>
    <td align="center">
      <img src="https://ik.imagekit.io/sbsjhivv8/IMG-20260112-WA0006.jpg?updatedAt=1768212448706" width="100%">
    </td>
    <td>
      <strong>Why Gixplay is Different</strong>

<ul>
  <li>
    <b>True Local-First Design:</b> Unlike most music apps that depend on accounts, cloud sync, and remote servers,
    Gixplay stores <b>everything locally on your device</b>. Your playlists, listening history, analytics, room identity,
    and preferences never leave your phone or browser.
  </li>

  <li>
    <b>No Accounts, No Lock-in:</b> You never need to sign up, verify an email, or remember a password.
    You can open the app and start listening instantly.
    Your data belongs to you, not to a company database.
  </li>

  <li>
    <b>Zero Tracking & Less Ads:</b> Gixplay does not track your behavior, does not build profiles,
    and does not show ads. But YouTube Sometimes show ads But That's also lesser than usual. There are no hidden scripts collecting usage data in the background.
  </li>

  <li>
    <b>Built for Speed:</b> The app is lightweight and optimized for mobile devices.
    No heavy SDKs, no unnecessary background services, and no large startup delays.
    It opens fast and stays responsive even on low-end phones.
  </li>

  <li>
    <b>YouTube as the Music Source:</b> Instead of maintaining a closed music catalog,
    Gixplay lets you play anything available on YouTube.
    You can paste a link instantly and start listening without waiting for indexing or approval.
  </li>

  <li>
    <b>Room System for Shared Listening:</b> Gixplay allows users to create rooms and listen together in real-time
    using short room codes — without creating accounts or sharing personal information.
    No other mainstream music app offers this in such a lightweight and private way.
  </li>

  <li>
    <b>Deep Personal Analytics:</b> Most apps collect analytics for companies.
    Gixplay creates analytics <b>for the user</b>.
    You get detailed insights like play counts, active days, yearly heatmaps, top tracks, and artists —
    all generated locally and visible only to you.
  </li>

  <li>
    <b>Full Data Ownership:</b> You can export your playlists and analytics at any time,
    move them to another device, or keep them as a personal backup.
    There is no vendor lock-in and no risk of losing your data because a service shuts down.
  </li>

  <li>
    <b>Designed for Personal & Small Groups:</b> Gixplay is not built for mass monetization.
    It is built for individuals and friends who want a simple, fast, private, and controllable music experience.
  </li>

  <li>
    <b>No Algorithm Control:</b> There is no recommendation system pushing content.
    You decide what to listen to, when to listen, and how to organize your music.
  </li>

  <li>
    <b>Transparent & Predictable:</b> What you see is what you get.
    No surprise UI changes, no forced features, no hidden data collection.
  </li>

  <li>
    <b>Completely Free to Use:</b> Glixar is Completely Free , No Charges For Any Feature. 
    It'll be Maintained for upcoming years and It'll be Open Source Soon.
  </li>
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
