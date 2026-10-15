<div align="center">

<!-- LOGO -->
<img src="logo.png" width="120" alt="Logo"/>

<h1>ONION MUSIC</h1>

<!-- BADGES -->
[![Download](https://img.shields.io/badge/Android-Download-0D47A1?style=for-the-badge&logo=android&logoColor=white&labelColor=3DDC84)](https://github.com/DragonsLabs/Onion-Music/releases/latest)
[![License MIT](https://img.shields.io/badge/License-MIT-A31F34?style=for-the-badge&labelColor=A8A9AD)](https://github.com/DragonsLabs/Onion-Music?tab=MIT-1-ov-file)

<p>A feature-rich, ad-free YouTube Music client with background playback, built using Google AI Studio.</p>

<!-- BADGES -->
[![API 25+](https://img.shields.io/badge/API-25%2B-brightgreen?style=for-the-badge&logo=android&logoColor=white&labelColor=00838F)](https://android-arsenal.com/api?level=25)
[![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)](https://kotlinlang.org)
[![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white)](https://developer.android.com/jetpack/compose)
[![Material 3](https://img.shields.io/badge/Material_3-6750A4?style=for-the-badge&logo=material-design&logoColor=white)](https://m3.material.io)
[![MicroG RE](https://img.shields.io/badge/MicroG-RE_Supported-FF0000?style=for-the-badge&logo=youtubemusic&logoColor=white)](https://github.com/morpheapp/microg-RE)
[![Latest Release](https://img.shields.io/github/v/release/DragonsLabs/Onion-Music?style=for-the-badge)](https://github.com/DragonsLabs/Onion-Music/releases/latest)

</div>

---

## ![](https://img.shields.io/badge/Table_of_Contents-0D2048?style=flat-square&logo=googledocs&logoColor=4285F4) 

- [Screenshots](#screenshots)
- [Features](#features)
- [Supported Languages](#supported-languages)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [How to Build](#how-to-build)
- [Permissions](#permissions)
- [Contributing](#contributing)
- [Changelog](#changelog)
- [FAQ](#frequently-asked-questions-faq)
- [Licence](#licence)

---

## ![](https://img.shields.io/badge/Screenshots-1B3A2D?style=flat-square&logo=android&logoColor=3DDC84) 

| Home | Player | Search | Settings |
|------|--------|--------|----------|
| ![Home](Screenshots/Home.png) | ![Player](Screenshots/Player.png) | ![Search](Screenshots/Search.png) | ![Settings](Screenshots/Settings.png) |

---

## ![](https://img.shields.io/badge/Features-2D1B4E?style=flat-square&logo=materialdesign&logoColor=B39DDB) 

- **100% Ad-Free & Background Playback:** Stream all YouTube & YouTube Music tracks, covers, remixes, music videos, slowed, and speeded-up versions seamlessly.
- **MicroG RE Integration:** Full YouTube Music ecosystem access and Google account library synchronization via [MicroG RE](https://github.com/morpheapp/microg-RE).
- **Independent Pitch & Speed Control:** Speed up or slow down tracks directly inside the app without changing pitch globally.
- **Song Downloader:** Integrated media downloading powered by `ytdlnis`.
- **Local Music Player:** Play songs stored on your device local storage alongside streamed tracks.
- **Responsive Layouts:** Tailored, optimized UI designs for phones, tablets, and foldable devices.
- **Built-in Equalizer:** Independent audio processing and equalizer controls.
- **Public Content Discovery:** Explore public playlists, covers, remixes, profiles, music videos, slowed, and speedup tracks across YouTube.
- **Smart Queue & Playlist Manager:** Dynamic queue reordering, creation, and local/cloud playlist management.
- **Material 3 Design & Dark Mode:** Clean, fully customizable UI supporting Material Design and OLED Dark Mode.
- **Automated Update Checks:** Every 24 hours, the app automatically checks for new releases and live changelogs.
- **Multi-Language Support:** Localized across 5 major languages out of the box.

---

## ![](https://img.shields.io/badge/Supported_Languages-0D2048?style=flat-square&logo=googletranslate&logoColor=4285F4) 

The application currently supports **5 core languages**:

| # | Flag | Language | Code |
|---|------|----------|------|
| 1 | 🇹🇷 | Türkçe | `tr` |
| 2 | 🇬🇧 | English | `en` |
| 3 | 🇪🇸 | Español | `es` |
| 4 | 🇩🇪 | Deutsch | `de` |
| 5 | 🇫🇷 | Français | `fr` |

---

## ![](https://img.shields.io/badge/Technologies_Used-1A0F3A?style=flat-square&logo=kotlin&logoColor=7F52FF) 

| Technology | Explanation |
|-----------|-------------|
| [Kotlin Coroutines & Flow](https://kotlinlang.org/docs/coroutines-overview.html) | Asynchronous task management and reactive UI state streams |
| [Jetpack Compose](https://developer.android.com/jetpack/compose) | Modern declarative UI framework with adaptive layouts for phones, tablets, and foldables |
| [ExoPlayer / Media3](https://developer.android.com/guide/topics/media/media3) | Low-latency audio playback, background service management, and custom audio effects/equalizer |
| [MicroG RE Integration](https://github.com/morpheapp/microg-RE) | Google account authentication and YT Music sync capabilities |
| [ytdlnis Engine](https://github.com/deniscerri/ytdlnis) | Integrated media downloader engine for offline song saving |
| [Room Database](https://developer.android.com/training/data-storage/room) | Offline local history, playlist management, and app cache management |
| [KSP & Retrofit](https://square.github.io/retrofit/) | Modern REST API client infrastructure for update checks and metadata fetching |

---

## ![](https://img.shields.io/badge/Installation-1B3A2D?style=flat-square&logo=android&logoColor=3DDC84) 

### Requirements
- Android **7.1.2 (API 25)** or higher
- [MicroG RE](https://github.com/morpheapp/microg-RE) (Optional, required for Google account syncing)

### Steps

1. Go to the [**Releases**](https://github.com/DragonsLabs/Onion-Music/releases/latest) page
2. Download the latest **`.apk`** file
3. Install MicroG RE on your device if you wish to log in to your Google account
4. Open the downloaded `.apk` file and grant installation permissions if prompted
5. Tap **Install** and launch **Onion Music**

---

## ![](https://img.shields.io/badge/How_to_Build-1A0F3A?style=flat-square&logo=kotlin&logoColor=7F52FF) 

### Requirements
- [Android Studio](https://developer.android.com/studio) Ladybug or newer
- JDK 17+
- Android SDK API 25+

### Steps

```bash
# 1. Clone the repository
git clone https://github.com/DragonsLabs/Onion-Music.git

# 2. Open the project in Android Studio
# File → Open → select the cloned folder

# 3. Let Gradle sync finish

# 4. Run on emulator or physical device
# Press the ▶ Run button or use:
./gradlew assembleDebug
```

### ✅ Runtime Permissions

| Permission | Reason |
| --- | --- |
| `READ_MEDIA_AUDIO` / `READ_EXTERNAL_STORAGE` | Required to play locally stored audio files |
| `POST_NOTIFICATIONS` | Required to show persistent media playback controls (Android 13+) |

### ⚙️ Normal Permissions

| Permission | Reason |
| --- | --- |
| `INTERNET` | To stream music, fetch metadata, and check for app updates |
| `FOREGROUND_SERVICE` | To keep audio playing smoothly in the background |

---

Contributions are strictly managed by **DragonLabs**:

1. **Fork** this repository
2. **Create** your feature branch (`git checkout -b feature/amazing-feature`)
3. **Commit** your changes (`git commit -m "feat: add amazing feature"`)
4. **Push** to the branch (`git push origin feature/amazing-feature`)
5. **Open** a Pull Request

---

###  — Initial Release

* Initial public release of Onion Music.
* Background playback & ad-free streaming engine.
* MicroG RE integration and YouTube Music account syncing.
* Custom pitch-independent speed/slowdown controls.
* Song downloader via `ytdlnis`.
* Support for tablet, phone, and foldable responsive UI.
* Built-in standalone audio equalizer.
* Multi-language support (TR, EN, DE, FR, ES).

---

## 💡 Why Onion Music?

Unlike default music streaming solutions that lock core functions behind paywalls or throttle background playback:

* **Ad-Free & Background Ready:** Listen to music, remixes, and covers continuously without interruptions or forced video displays.
* **Privacy & MicroG Choice:** Log in using open MicroG RE infrastructure without risking account flags or needing official GApps.
* **Custom Sound Engine:** Adjust playback speeds and equalization levels independently from system settings.
* **Open-Source Stack:** Designed and maintained transparently by **DragonLabs** and co-developed using **Google AI Studio**.

---

## ❓ Frequently Asked Questions (FAQ)

### Is MicroG RE required to use Onion Music?

No. You can use Onion Music in guest/incognito mode to search and play public tracks, covers, and playlists. MicroG RE is only required if you want to sync your private YouTube Music playlists and account data.

### Is Onion Music free and open-source?

Yes, Onion Music is 100% open-source, free, and developed under the MIT License by [DragonLabs](https://github.com/DragonsLabs).

---

This project is maintained by **DragonLabs** and licensed under the **MIT License** — see the [LICENSE](https://opensource.org/licenses/MIT) page for details.
