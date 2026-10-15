# Installation Guide for Onion Music

This guide covers the requirements, build instructions, and installation steps for **Onion Music**, developed by **DragonLabs**.

---

## 1. System Requirements

### For Users (Installing APK)
* **Android Version:** Android 7.1.2 (API 25) or higher.
* **Storage:** ~30 MB free space.
* **Optional:** [MicroG RE](https://github.com/morpheapp/microg-RE) installed on your device if you wish to log in and sync your YouTube Music account.

### For Developers (Building from Source)
* **IDE:** [Android Studio](https://developer.android.com/studio) Ladybug or newer.
* **SDK:** Android SDK API 25+.
* **JDK:** Java Development Kit (JDK) 17 or higher.
* **Build System:** Gradle (included via wrapper).

---

## 2. Installing Pre-built APK

If you want to use the app directly without compiling the code:

1. Go to the official [**Releases**](https://github.com/DragonsLabs/Onion-Music/releases/latest) page.
2. Download the latest **`app-release.apk`** file.
3. (Optional) Install [MicroG RE](https://github.com/morpheapp/microg-RE) first if you plan to sign in with your Google/YouTube account.
4. Open the downloaded APK on your Android device.
5. If prompted by your system, enable **"Install from unknown sources"** for your file manager or browser.
6. Tap **Install** and open **Onion Music**.

---

## 3. Building from Source

To compile the application yourself using Android Studio or the command line:

### Step 1: Clone the Repository
Open your terminal and run the following command to clone the repository:

```bash
git clone [https://github.com/DragonsLabs/Onion-Music.git](https://github.com/DragonsLabs/Onion-Music.git)
cd Onion-Music

```

### Step 2: Open in Android Studio

1. Launch Android Studio.
2. Select **File > Open** and choose the cloned `Onion-Music` folder.
3. Wait for Android Studio to sync the Gradle dependencies automatically.

### Step 3: Build and Run

You can build the debug APK directly via the terminal:

```bash
# For Windows
gradlew.bat assembleDebug

# For macOS / Linux
./gradlew assembleDebug

```

> **APK Location:** Once the build is successful, the output APK will be available at:
> `app/build/outputs/apk/debug/app-debug.apk`

Alternatively, connect your Android device (with USB Debugging enabled) or start an emulator in Android Studio, and click the **▶ Run** button.
