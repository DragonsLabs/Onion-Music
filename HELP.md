# Onion Music - Help & Troubleshooting Guide

Welcome to the **Onion Music** help and support guide! If you are encountering issues, have questions about setup, or want to get the most out of your music client, this document provides answers and solutions.

---

## 💡 Frequently Asked Questions (FAQ)

### 1. Is MicroG RE required to use Onion Music?
**No.** Onion Music works fully out of the box in Incognito/Guest mode. You can search, stream, browse public playlists, covers, and remixes without signing in. **MicroG RE** is only needed if you want to sign in to your Google account to access your private playlists, library, and personalized recommendations.

### 2. Is Onion Music free and ad-free?
**Yes.** Onion Music is 100% free, open-source (GPL-3.0), and contains zero ads, trackers, or telemetry.

### 3. How does the Song Downloader work?
The app utilizes the integrated `ytdlnis` engine to download tracks locally. Downloaded tracks can be played within Onion Music using the built-in local player or through any offline media player on your device.

### 4. Can I adjust playback speed without changing pitch?
**Yes.** Onion Music features an independent pitch/speed control engine. You can slow down or speed up any track without altering the natural pitch of the voice or instruments.

---

## 🛠️ Common Issues & Troubleshooting

### Issue 1: "Unable to sign in with Google / MicroG RE error"
* **Solution:**
  1. Ensure you have installed [MicroG RE](https://github.com/morpheapp/microg-RE) on your device before logging in.
  2. Open your phone's **Settings > Apps > MicroG RE** and ensure background battery optimization is set to **Unrestricted**.
  3. Clear cache for both MicroG RE and Onion Music, then retry signing in.

### Issue 2: Audio stops playing in the background or when screen turns off
* **Solution:**
  1. Make sure **Foreground Service** permissions are allowed for Onion Music.
  2. Go to your Android device **Settings > Apps > Onion Music > Battery** and change battery usage to **Unrestricted** or **Don't Optimize**.
  3. Ensure persistent notifications are enabled (Android 13+ requires notification permissions to display media controls).

### Issue 3: Local music files are not showing up
* **Solution:**
  1. Open Onion Music and grant storage / audio media access when prompted.
  2. Check app settings to ensure the target folder containing your local music is included in the media scanner path.
  3. Go to **Settings > Clear Cache** and restart the app to force a rescan.

### Issue 4: Updates are not checking automatically
* **Solution:**
  1. Onion Music checks for updates once every 24 hours via GitHub API.
  2. Ensure your device is connected to the internet and **INTERNET** permission is active.
  3. You can manually check for updates anytime in **Settings > About > Check for Updates**.

---

## 📩 Further Assistance & Bug Reports

If your issue is not listed above or you encountered a bug:

1. Visit our **GitHub Issues** page: [https://github.com/DragonsLabs/Onion-Music/issues](https://github.com/DragonsLabs/Onion-Music/issues)
2. Search existing issues to see if a solution has already been posted.
3. If not, open a **New Issue** detailing your device model, Android version, and steps to reproduce the problem.

*Maintained with ❤️ by **DragonLabs** ([https://github.com/DragonsLabs](https://github.com/DragonsLabs))*
