# Bing Search Automator

## 🚀 Overview
This **Tampermonkey userscript** automates **Bing searches** with a typing effect, clears the search box before each search, and introduces random delays to mimic natural browsing behavior.

## 📂 Features
- ✅ **Automated Bing searches** with random words.
- ✅ **Typing effect** to simulate human input.
- ✅ **Clears search box** before each search.
- ✅ **Randomized delays** between searches.
- ✅ **Simulates Enter key press** for realistic search execution.

## 🛠 Installation & Setup
### **1️⃣ Install Tampermonkey Extension**
- **Google Chrome / Edge**: [Tampermonkey](https://www.tampermonkey.net/)
- **Mozilla Firefox**: [Tampermonkey Add-on](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/)

### **2️⃣ Install the Script**
1. Open **Tampermonkey Dashboard**.
2. Click **Create a new script**.
3. Copy and paste the script from `bing_search_automator.user.js`.
4. Click **Save** and enable the script.

### **3️⃣ Run the Script**
- Visit **[Bing](https://www.bing.com/)**.
- The script will automatically start searches with **randomized words and delays**.

## ⚙ Configuration
The script contains a **predefined list of words**:
```javascript
const words = ["Abandon", "Benevolent", "Culture", "Diverse", "Eloquent", "Fathom", "Generous", "Harmony", "Innovate", "Jubilant", "Keen", "Luminous", "Mystique"];
```
- You can **modify or extend the list** to customize search behavior.

## 🔥 How It Works
1. **Chooses a random word** from the predefined list.
2. **Clears the search box** before typing.
3. **Types the search term letter by letter** (mimicking human typing).
4. **Presses Enter** to trigger the search.
5. **Introduces random delays** (between 10 to 15 seconds) before starting the next search.

## 🛠 Troubleshooting
### **Issue: Script not running?**
✅ Ensure Tampermonkey is **installed and enabled**.
✅ Verify the script is **enabled** in the Tampermonkey dashboard.
✅ Reload the Bing page (`Ctrl + R`).

### **Issue: Search box not found?**
✅ Check if Bing has updated its search box ID.
✅ Modify this line in the script:
```javascript
document.getElementById('sb_form_q');
```
Replace `'sb_form_q'` with the new **Bing search box ID**.

## 📜 License
This project is licensed under the **MIT License**.

## 🤝 Contributing
Feel free to submit **issues** or **pull requests** to improve this script.

---
### 👨‍💻 Author
[My Profile](https://github.com/letsconfuse)

