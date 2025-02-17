Here’s a **cool and professional README** for your **Telegram Media Downloader** script:

---

# Telegram Media Downloader

Unlock the ability to download **images**, **GIFs**, **videos**, and **voice messages** from private Telegram channels and chats where downloading is restricted. This user script brings back the download functionality on the **Telegram webapp**, even in places where it's normally disabled.

## 🚀 Overview

**Telegram Media Downloader** is a user script that restores the download option for images, GIFs, videos, and voice messages in **Telegram Web**. It allows users to bypass restrictions on content saving in private channels, providing a seamless experience for Telegram users who want to save media content.

**Note:** Some features may only work on specific versions of the Telegram webapp (e.g., Audio message downloads are available only on the K version of the webapp).

---

## 💻 What Are User Scripts?

User scripts let you **customize your browsing experience**! Once installed, they automatically enhance websites by adding features, improving usability, or removing unwanted elements. Scripts from platforms like **Greasy Fork** are written by other users and shared for free!

---

## 🔧 Installation

### **Greasy Fork Installation**

1. **Install a User Script Manager**:
   - **Chrome**: Tampermonkey or Violentmonkey
   - **Firefox**: Greasemonkey, Tampermonkey, or Violentmonkey
   - **Safari**: Tampermonkey or Userscripts
   - **Microsoft Edge**: Tampermonkey or Violentmonkey
   - **Opera**: Tampermonkey or Violentmonkey
   - **Maxthon**: Violentmonkey

2. **Install the Script**:
   - Go to **Greasy Fork**: [Telegram Media Downloader on Greasy Fork](https://greasyfork.org/scripts/446342-telegram-media-downloader)
   - Click **Install** to add the script to your user script manager.

---

### **Manual Installation**

1. **Install a User Script Manager** (refer to the list above).
2. Open the **Tampermonkey Dashboard**.
3. Drag & drop the file `src/tel_download.js` into the dashboard.
4. Click the **Install** button.

---

## 📂 How to Use

This script works only on **Telegram Web** and is **inactive** in chats or channels where content saving is allowed.

For channels and chats with restricted media downloads, the script adds a **download button** for images, GIFs, videos, and voice messages. You can download them just like you would with Telegram’s built-in download button.

### **Features**
- **Download Images, GIFs, Videos, and Stories**
- **Progress Bar for Video Downloads**
- **No Progress Bar for Images & Audio** (since they download quickly)

---

### **Supported Webapp Versions**
- **WebK (K Version)**: [https://webk.telegram.org](https://webk.telegram.org)
- **WebZ (Z Version)**: [https://webz.telegram.org](https://webz.telegram.org)

This script should work on both versions. If you're using a different version of Telegram Web and it's not working, please [raise an issue on GitHub](https://github.com/Neet-Nestor/Telegram-Media-Downloader).

---

## 📊 Check Download Progress

- **Videos**: A progress bar will appear at the **bottom-right** corner once the download begins.
- **Images & Audios**: Downloads will begin immediately, but there won't be a visible progress bar.

You can also check the progress in **DevTools** by looking at the console logs.

---

## 🤝 Contributing

We welcome contributions! If you'd like to improve the script, follow the steps below.

### **Reporting Issues**
- Check if the issue has already been reported in the [Issues tab](https://github.com/Neet-Nestor/Telegram-Media-Downloader/issues).
- If not, create a new issue with a descriptive title and include any relevant screenshots or logs.

### **Submitting Pull Requests**
1. **Fork** the repository by clicking the **Fork** button.
2. **Clone** your fork to your local machine:
   ```bash
   git clone https://github.com/YOUR-USERNAME/Telegram-Media-Downloader.git
   cd Telegram-Media-Downloader
   ```
3. **Create a new branch** for your changes:
   ```bash
   git checkout -b feature-or-bugfix-name
   ```
4. **Make your changes** and **test** the script on both Telegram WebK and WebZ versions.
5. **Commit** your changes:
   ```bash
   git commit -m "Fix issue or add feature"
   ```
6. **Push** your branch:
   ```bash
   git push origin feature-or-bugfix-name
   ```
7. Go to **GitHub**, select your branch, and click **New Pull Request**.

---

### **Development Guidelines**
- Keep your code **clean** and well-documented.
- Follow the **existing coding style**.
- Test your changes on both **Telegram WebK** and **WebZ** versions.
- Ensure compatibility with **Tampermonkey** and **Violentmonkey**.

---

## 🌍 Help with Translations

Help us make Telegram Media Downloader available to users worldwide! If you'd like to translate this script or its documentation, please follow these steps:

1. Check for existing translations in the `docs/greasyfork` folder.
2. Add a new file in `docs/` with the appropriate language code (e.g., `docs/fr-FR.md` for French).
3. Translate the content from `docs/greasyfork/en-US.md` into your language while preserving the formatting.

---

## 📄 License

This project is licensed under the **GNU GPLv3 License**. See the [LICENSE file](LICENSE) for details.

---

**Telegram Media Downloader** is open-source and built with 💖 by the community!

---

### **Screenshots**
Include some example screenshots of how the download button appears in Telegram Web with this script!

---

This README provides a polished, professional overview while still keeping it engaging. It includes all essential details like installation, usage, and contributing, and it offers a clear path for users and developers to get involved.

Let me know if you need any more adjustments! 🚀
