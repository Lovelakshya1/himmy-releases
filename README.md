# Himmy Anime

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Android_7.0+-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Platform" />
  <img src="https://img.shields.io/badge/Language-Kotlin_•_Jetpack_Compose-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" alt="Language" />
  <img src="https://img.shields.io/badge/Architecture-Material_3_•_Clean_Bento-00C4B4?style=for-the-badge" alt="Architecture" />
  <img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="License" />
  <img src="https://img.shields.io/badge/Experience-100%25_Ad--Free-FF6B6B?style=for-the-badge" alt="Ad-Free" />
</p>

---

**Himmy Anime** is an elegant, modern, and ad-free entertainment client for Android. Built with Jetpack Compose and Material 3, it brings together high-definition anime streaming, direct episode downloads, a built-in multi-source manga reader, real-time anime news, anime theme music playback, and seamless AniList cloud synchronization in a unified, editorial experience.

---

## Heritage and Origins

Himmy Anime initially started as a fork of the base architecture from the discontinued project **Corn Castle**. While that upstream project was retired, its initial structural base provided the starting point. Since then, the codebase has undergone an end-to-end rewrite: replacing legacy components with Jetpack Compose, creating an all-new Japanese Bento grid design language, integrating an advanced manga reading engine, embedding real-time news and music services, and building high-speed download engines.

---

## App Previews

<div align="center">

### Home, Discovery and Search

| Home and Live Mesh | Bento Discovery Grid | Advanced Filters |
| :---: | :---: | :---: |
| <img src="https://raw.githubusercontent.com/Lovelakshya1/himmy-releases/main/Previews/Screenshot_20260921-184611.Himmy%20Anime.png" width="220" alt="Home Feed and Aurora Header" /> | <img src="https://raw.githubusercontent.com/Lovelakshya1/himmy-releases/main/Previews/Screenshot_20260921-184704.Himmy%20Anime.png" width="220" alt="Bento Discovery Grid" /> | <img src="https://raw.githubusercontent.com/Lovelakshya1/himmy-releases/main/Previews/Screenshot_20260921-184716.Himmy%20Anime.png" width="220" alt="Search Filter Sheet" /> |

### Anime Details, Playlists and Franchise Guides

| Details and Countdown | Episode Playlist | Watch Order and Cast |
| :---: | :---: | :---: |
| <img src="https://raw.githubusercontent.com/Lovelakshya1/himmy-releases/main/Previews/Screenshot_20260921-184622.Himmy%20Anime.png" width="220" alt="Anime Details Screen" /> | <img src="https://raw.githubusercontent.com/Lovelakshya1/himmy-releases/main/Previews/Screenshot_20260921-184629.Himmy%20Anime.png" width="220" alt="Episode List" /> | <img src="https://raw.githubusercontent.com/Lovelakshya1/himmy-releases/main/Previews/Screenshot_20260921-184636.Himmy%20Anime.png" width="220" alt="Watch Order and Staff" /> |

### Video Player and Next-Gen Manga Reader

| Cinematic Edge-to-Edge Player | Next-Gen Manga Reader |
| :---: | :---: |
| <img src="https://raw.githubusercontent.com/Lovelakshya1/himmy-releases/main/Previews/Screenshot_20260921-184830.Himmy%20Anime.png" width="220" alt="Video Player and Dual Servers" /> | <img src="https://raw.githubusercontent.com/Lovelakshya1/himmy-releases/main/Previews/Screenshot_20260921-185038.Himmy%20Anime.png" width="220" alt="Manga Reader with Color Shaders" /> |

### Real-Time News and Airing Schedule

| Anime News Magazine | Airing Radar and Schedule |
| :---: | :---: |
| <img src="https://raw.githubusercontent.com/Lovelakshya1/himmy-releases/main/Previews/Screenshot_20260920-181850.Himmy%20Anime.png" width="220" alt="Anime News Feed" /> | <img src="https://raw.githubusercontent.com/Lovelakshya1/himmy-releases/main/Previews/Screenshot_20260921-184722.Himmy%20Anime.png" width="220" alt="Airing Schedule Radar" /> |

### MySpace and Personalization Suite

| MySpace Dashboard | Avatar and Profile Studio |
| :---: | :---: |
| <img src="https://raw.githubusercontent.com/Lovelakshya1/himmy-releases/main/Previews/Screenshot_20260921-184725.Himmy%20Anime.png" width="220" alt="MySpace Dashboard" /> | <img src="https://raw.githubusercontent.com/Lovelakshya1/himmy-releases/main/Previews/Screenshot_20260921-184752.Himmy%20Anime.png" width="220" alt="Avatar Studio" /> |

</div>

---

## Key Features

### Real-Time Anime News Feed
- **Multi-Source Aggregation:** Browse breaking news, licensing announcements, industry interviews, and release dates curated from Crunchyroll, Anime News Network (ANN), MyAnimeList (MAL), and Anime Corner.
- **Editorial Layout:** Modern Japanese magazine-style cards with quick-read article overlays and direct external source links.
- **Source Filtering:** Switch between specific news outlets or view a unified feed.

### Anime Theme Music and Soundtracks
- **Curated Openings and Endings:** Stream full anime openings (OP) and endings (ED) in high fidelity with synchronized video and audio.
- **Background and Mini Player:** Keep listening while browsing other sections of the app with an interactive floating mini player.
- **ExoPlayer Engine:** Powered by AndroidX Media3 for seamless seeking, loop modes, and low-latency audio buffering.

### Built-in Multi-Provider Manga Reader
- **Multiple Manga Providers:** Read manga titles directly via MangaPill, MangaKatana, MangaDex, and WeebCentral.
- **Reading Modes:** Seamless Webtoon vertical continuous scroll, Paged Left-to-Right, and Paged Right-to-Left (traditional Japanese format).
- **GPU Color Shaders:** Read comfortably anytime with custom shaders including Sepia, Invert Dark Mode, Night Warmth, and Monochrome.
- **Chapter Navigation:** Quick drawer for instant jumping between chapters, scanlator groups, and release dates.

### Cinematic Edge-to-Edge Video Player
- **Borderless Fullscreen:** True immersive playback utilizing Android edge-to-edge windowing.
- **Dual-Server Streams:** High-speed streaming pipelines with automatic failover (Eenie and Meenie servers).
- **Sub and Dub Support:** Effortlessly toggle between original Japanese audio with subtitles and English dubs.
- **Watch History Tracker:** Automatically tracks your episode timestamp and marks completed episodes on your profile.

### Dual-Engine Direct Downloads
- **Background Downloads:** Continue downloading episodes in the background while switching apps or with the screen locked.
- **Floating Download Capsule:** Global mini progress capsule to pause, resume, and monitor download speeds anywhere in the app.
- **Resolution Badges:** Download in 1080p Full HD, 720p HD, 480p, or 360p with estimated file size indicators.
- **Standard Video Containers:** Exported in standard `.mkv` and `.mp4` formats ready for any external player.

### Airing Radar and Broadcast Schedule
- **Weekly Schedule:** Day-by-day airing calendar displaying when each episode airs in your local timezone.
- **Live Countdown Timers:** Dedicated countdown clocks for upcoming broadcasts.

### Native AniList Synchronization
- **One-Click OAuth:** Fast, secure token-based authentication.
- **Two-Way Progress Sync:** Automatically updates your watching progress, scores, and list status to your AniList account.
- **Custom Lists:** Full access to your Planning, Watching, Completed, Paused, and Dropped lists directly from the dashboard.

### MySpace Deep Customization
- **Theme Palettes:** Choose from multiple curated color palettes (Teal, Rose Quartz, Cyberpunk Neon, Sunset Orange, Deep Violet, and more).
- **Typography Engine:** Select custom typography (JetBrains Mono, Inter, Poppins, Outfit).
- **Profile Studio:** Custom avatars, anime character presets, profile banners, and background tinting.

### Built-in Self Updater
- **Automated Update Checker:** Check for new releases with one tap.
- **Editorial Release Notes:** Changelogs rendered with rich media and screenshots.
- **In-App Package Installer:** Downloads the APK with a live speed meter and prompts Android's native installer with automatic cache cleanup.

---

## Installation

1. Navigate to the **[Releases](../../releases/latest)** section of this repository.
2. Download the latest **`app-release.apk`** file.
3. Open the downloaded file on your Android device.
4. If prompted, allow installation from unknown sources in your device settings.
5. Tap **Install** and launch the app.

> **System Requirements:** Android 7.0 (Nougat, API Level 24) or higher.

---

## How to Update

You can keep Himmy Anime up to date in two ways:

1. **Inside the App (Recommended):**
   - Open **Himmy Anime** $\rightarrow$ Navigate to the **MySpace** tab.
   - Tap **Check Updates** in the App Updates card.
   - Tap **Download and Install** to update automatically.
2. **From GitHub Releases:**
   - Download the newest `.apk` from the **[Releases](../../releases)** tab and install it over your existing build (all watch history, bookmarks, and settings are preserved).

---

## Permissions Overview

| Permission | Purpose |
| :--- | :--- |
| `INTERNET` / `ACCESS_NETWORK_STATE` | Streaming video and music, downloading manga pages, fetching metadata, and syncing with AniList. |
| `FOREGROUND_SERVICE` / `DATA_SYNC` | Keeping episode downloads active when switching apps or locking the device. |
| `POST_NOTIFICATIONS` | Displaying live download progress and playback controls in the Android notification drawer. |
| `REQUEST_INSTALL_PACKAGES` | Prompting the Android package installer for direct in-app updates. |

---

## Disclaimer

- **Himmy Anime** is an open-source client application created for educational and personal use only.
- This application does not host, store, or distribute any media content on its own servers. All media streams, manga scans, and downloads are indexed from publicly available third-party services.
- All anime titles, images, character names, and trademarks belong to their respective copyright owners.
- If you have copyright concerns regarding specific content, please contact the third-party providers hosting the material directly.

---

<p align="center">
  Crafted with care for anime and manga lovers worldwide.
</p>
