# Privacy Policy for Onion Music

**Effective Date:** October 15, 2026  
**Developer:** DragonLabs ([https://github.com/DragonsLabs](https://github.com/DragonsLabs))  
**Repository:** [https://github.com/DragonsLabs/Onion-Music](https://github.com/DragonsLabs/Onion-Music)

At **DragonLabs**, we take your privacy very seriously. **Onion Music** is designed from the ground up as a privacy-focused, ad-free, and transparent open-source YouTube Music client.

This Privacy Policy explains how Onion Music handles your data, permissions, and third-party integrations.

---

## 1. Zero Personal Data Collection

* **No Tracking or Analytics:** Onion Music does **not** collect, store, transmit, or sell any personal data, usage telemetry, crash logs, or unique device identifiers.
* **No Server Infrastructure:** DragonLabs does not maintain any private tracking servers, databases, or analytics endpoints. All application features operate locally on your device or interact directly with third-party public endpoints (e.g., YouTube / GitHub APIs).

---

## 2. Local Storage & On-Device Data

All data generated within Onion Music remains **100% on-device**:

* **Local Playlists & History:** Your local playlists, listening history, search queries, and application settings are stored strictly on your device using an encrypted local SQLite/Room database.
* **Cache Management:** Downloaded audio cache, album artwork, and temporary data reside in your device's internal storage and can be cleared at any time via the app settings.

---

## 3. Third-Party Services & Integrations

### A. YouTube & Google Services
Onion Music fetches music streams, metadata, public playlists, and covers directly from public YouTube / YouTube Music endpoints. Your interactions with public streams are subject to YouTube's public network protocols.

### B. MicroG RE Integration
* MicroG RE ([https://github.com/morpheapp/microg-RE](https://github.com/morpheapp/microg-RE)) is an optional, open-source framework used for Google account authentication and YouTube Music library synchronization.
* If you choose to sign in via MicroG RE, your login credentials and authentication tokens are processed securely and stored locally via MicroG RE protocols. DragonLabs has no access to your Google account credentials or personal tokens.

### C. ytdlnis / Media Downloader Engine
The integrated `ytdlnis` engine processes media downloading requests locally on your device. Downloaded media files are stored strictly within your local device storage.

### D. Automated Release & Update Checks
Every 24 hours, Onion Music makes a lightweight API request to GitHub Releases (`https://api.github.com/repos/DragonsLabs/Onion-Music`) to check for app updates and live release notes. No personal info or user ID is sent during this check.

---

## 4. Android App Permissions

Onion Music only requests the minimum set of permissions necessary to function properly:

| Permission | Purpose |
|---|---|
| `INTERNET` | Required to stream audio, fetch music metadata, and check for app updates. |
| `FOREGROUND_SERVICE` | Required to keep audio playing smoothly in the background when the screen is off. |
| `READ_MEDIA_AUDIO` / `READ_EXTERNAL_STORAGE` | Required exclusively to scan and play locally stored music files on your device. |
| `POST_NOTIFICATIONS` | Required (Android 13+) to display persistent media playback notification controls. |

Onion Music **never** requests sensitive permissions such as Location, Camera, Contacts, or Microphone.

---

## 5. Open Source Transparency

Onion Music is completely open-source under the **GNU General Public License v3.0 (GPL-3.0)**. You can review the entire codebase, verify security practices, or build the app directly from source at our GitHub repository:

👉 [https://github.com/DragonsLabs/Onion-Music](https://github.com/DragonsLabs/Onion-Music)

---

## 6. Changes to This Privacy Policy

We may update our Privacy Policy from time to time as new features are added. Any changes will be published directly in this repository along with an updated effective date.

---

## 7. Contact Us

If you have any questions, security disclosures, or concerns regarding privacy in Onion Music, feel free to open an issue or contact us via GitHub:

* **DragonLabs GitHub:** [https://github.com/DragonsLabs](https://github.com/DragonsLabs)
