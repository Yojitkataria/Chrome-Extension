# 🔖 Tab Title Viewer - Chrome Extension

This Chrome Extension fetches and displays the title of the currently active browser tab. It's a lightweight and simple utility built using HTML, CSS, JavaScript, and Chrome's Extension APIs.

---

## 📌 Features

- ✅ One-click to get the current tab's title
- ✅ Lightweight popup UI
- ✅ Works instantly without needing extra permissions

---

## 📁 Project Structure

Chrome-Extension/
├── manifest.json # Extension configuration
├── popup.html # UI for the extension popup
├── popup.js # Logic to get current tab title
└── image.png # Icon used in the extension


---

## 🚀 How to Run Locally

1. **Clone the repository** or download the files:
   ```bash
   git clone https://github.com/Yojitkataria/Chrome-Extension.git
2. Open Chrome, go to chrome://extensions/

3. Enable Developer Mode (top-right)

4. Click "Load Unpacked" and select the Chrome-Extension folder

5. Click the extension icon and press the "Get Title" button in the popup


🧠 What I Learned
Understanding how Chrome extensions work (Manifest v3)

Manipulating browser tabs using Chrome APIs

Dynamically interacting with the DOM in JavaScript

Structuring and packaging browser extensions


<img width="301" height="210" alt="image" src="https://github.com/user-attachments/assets/adff39c8-ea8c-4345-abc2-226d2ab3e4a3" />

<img width="1212" height="746" alt="image" src="https://github.com/user-attachments/assets/6e958f0b-7247-4e3d-ac75-fe3937de0919" />



🖼️ Visual Diagram

<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/1d5d3c8c-8880-4da6-8f06-1ca1c1f80699" />

Working🥇
The system uses Chrome Extension APIs to register the extension using a manifest file. When a user clicks on the extension icon, a popup UI is displayed. A button inside the popup triggers a JavaScript function, which uses chrome.tabs.query() to access the title of the currently active tab. The title is then dynamically displayed within the popup. This architecture separates concerns into manifest (configuration), UI (HTML), logic (JS), and browser APIs (Chrome).


📜 License
This project is open-source and free to use for learning purposes.

🙋‍♂️ Author
Yojit Kataria
GitHub: @Yojitkataria

