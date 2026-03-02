<div align="center">
  <img src="https://github.com/user-attachments/assets/daae5e97-8f5c-4e6b-beaa-0e889d9a2b1c" width="120" height="120" alt="CF Stopwatch Icon">
  
  <h1>CF Stopwatch</h1>
<p><sub>by <b>Pratik Rakhecha</b></sub></p>
  <p><strong>Precision time-tracking for competitive programmers.</strong></p><a href="https://addons.mozilla.org/en-US/firefox/addon/cf-stopwatch/">
  <img src="https://img.shields.io/badge/Firefox-FF7139?style=for-the-badge&logo=Firefox-Browser&logoColor=white" />
</a>

<a href="./cf-stopwatch-chrome.zip">
  <img src="https://img.shields.io/badge/Google%20Chrome-4285F4?style=for-the-badge&logo=GoogleChrome&logoColor=white" />
</a>
  <br><br>
  <img src="https://github.com/user-attachments/assets/5fc139fb-5a2f-49e3-a2a3-1d6f01ca619c" width="34.7%" />
  <img src="https://github.com/user-attachments/assets/c7192848-26a4-4fd1-9f15-92818ae3ae36" width="33%" />
  <img src="https://github.com/user-attachments/assets/0c91d966-668f-463a-9b37-e230b7da25f9" width="30%" />
</div>

CF Stopwatch is a lightweight browser extension that seamlessly integrates into Codeforces problem pages. It helps you track your solve times with zero manual effort, allowing you to focus entirely on the logic.

---

## ✨ Key Features

* **🛡️ Anti-Panic Buffer:** A 60-second delay before the timer starts gives you time to read the problem without "clock-stress."
* **🏁 Intelligent Auto-Stop:** Automatically detects an **Accepted** verdict via the Codeforces API and stops the clock.
* **🔄 Multi-Attempt Support:** Reset the timer for new attempts; it ignores past AC verdicts to ensure accurate tracking.
* **💾 Smart Persistence:** Your progress is saved locally. If you close the tab, the timer pauses and resumes exactly where it left off when you return.
* **🎨 Adaptive UI:** Dynamically reads CSS variables from Codeforces to blend perfectly with Light, Dark, or Custom themes.

---

## 🚀 Installation

### **Chrome / Chromium**

1. Download the `cf-stopwatch-chrome` folder.
2. Navigate to `chrome://extensions`.
3. Enable **Developer mode** (top right).
4. Click **Load unpacked** and select the extension folder.

### **Firefox**
Add ons: [download](https://addons.mozilla.org/en-US/firefox/addon/cf-stopwatch/)

---

## 🛠️ How It Works

The extension uses the official Codeforces API to monitor your progress:

* **Polling:** It checks `codeforces.com/api/user.status` every 5 seconds.
* **Requirement:** You must be **logged in** to your Codeforces account for the auto-stop feature to function.
* **Zero Background Noise:** The timer only runs when the specific problem tab is active and open.

---

## 📂 Project Structure

```
cf-stopwatch-firefox/   cf-stopwatch-chrome/
├── manifest.json       ├── manifest.json  (MV3)
├── content.js          ├── content.js
└── content.css         └── content.css
```
---

## 📜 License & Copyright

**Copyright © 2026 [PRATIK MANISH RAKHECHA/pratikrkcha]**

This project is licensed under the **MIT License**. You are free to use, modify, and distribute this software, provided that the original copyright notice and permission notice are included in all copies.

---

**Find this helpful?** Give it a ⭐ to support the project!
