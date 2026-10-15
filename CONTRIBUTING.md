# Contributing to Onion Music

Thank you for your interest in contributing to **Onion Music**, developed by **DragonLabs**! We welcome contributions from the open-source community to help make this the best ad-free YouTube Music client.

Please follow these guidelines to ensure a smooth contribution process.

---

## 1. Code of Conduct

By participating in this project, you agree to abide by our terms:
* Be respectful and constructive in issues and pull requests.
* Keep discussions focused on improving the application and respecting user privacy.

---

## 2. How Can You Contribute?

* **Reporting Bugs:** Open an issue if you encounter crashes, UI glitches, or playback errors. Please include your Android version, device model, and steps to reproduce.
* **Suggesting Enhancements:** Have an idea for a new feature? Open an issue tagged as an `enhancement` to discuss it before implementation.
* **Fixing Issues & Coding:** Submit Pull Requests (PRs) to fix existing bugs or implement approved features.
* **Translations:** Help localize Onion Music into more languages.

---

## 3. Development Workflow

If you want to write code and submit a pull request, follow these steps:

1. **Fork** the repository (`https://github.com/DragonsLabs/Onion-Music`).
2. **Clone** your fork locally:
   ```bash
   git clone [https://github.com/DragonsLabs/Onion-Music.git](https://github.com/DragonsLabs/Onion-Music.git)
   cd Onion-Music

```

3. **Create a new branch** for your feature or bug fix:
```bash
git checkout -b feature/your-feature-name
# or for bug fixes:
git checkout -b fix/issue-description

```


4. **Make your changes** following Kotlin and Jetpack Compose best practices.
5. **Test your code** thoroughly on an emulator or physical device (API 25+).
6. **Commit your changes** using clear commit messages:
```bash
git commit -m "feat: add custom equalizer preset support"

```


7. **Push to your fork:**
```bash
git push origin feature/your-feature-name

```


8. **Open a Pull Request** on GitHub targeting the main repository.

---

## 4. Coding Style Guidelines

* **Language:** Kotlin (Latest stable version).
* **UI Framework:** Jetpack Compose & Material 3.
* **Architecture:** Follow clean MVVM principles with Kotlin Coroutines and Flows.
* **Formatting:** Keep code clean, well-commented, and adhere to standard Kotlin coding conventions.

---

## 5. License Agreement

By contributing to Onion Music, you agree that your contributions will be licensed under the **GNU General Public License v3.0 (GPL-3.0)** governing this project.
