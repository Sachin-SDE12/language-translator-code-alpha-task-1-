# 🌐 Language Translation Tool

> **CodeAlpha AI Internship — Task 1**

A clean, responsive AI-powered Language Translation Tool that translates text across 20+ languages instantly — built with vanilla HTML, CSS, and JavaScript using the free MyMemory Translation API. No API key required.

---

## 🔗 Live Demo

👉 **[Try it Live](https://Sachin-SDE12.github.io/CodeAlpha_LanguageTranslationTool/)**

---

## ✨ Features

- 🌍 **20+ Languages** — English, Hindi, French, German, Spanish, Japanese, Arabic, Chinese, and more
- ⚡ **Instant Translation** — Real-time results powered by MyMemory API
- 🔄 **Swap Languages** — Switch source and target language in one click
- 📋 **Copy to Clipboard** — Copy translated text instantly
- 🔊 **Text-to-Speech** — Listen to the translated output
- 🗑️ **Clear Button** — Reset everything with one click
- 📱 **Fully Responsive** — Works on mobile, tablet, and desktop
- ⌨️ **Keyboard Shortcut** — `Ctrl + Enter` to translate

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Structure & Markup |
| CSS3 | Styling & Animations |
| JavaScript (ES6+) | Logic & API calls |
| MyMemory API | Free Translation Engine |
| Web Speech API | Text-to-Speech feature |
| GitHub Pages | Live Deployment |

---

## 📂 Project Structure

```
CodeAlpha_LanguageTranslationTool/
│
├── index.html       # Main app file (HTML + CSS + JS)
└── README.md        # Project documentation
```

---

## 🚀 How to Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/Sachin-SDE12/CodeAlpha_LanguageTranslationTool.git
   ```

2. **Open the project folder**
   ```bash
   cd CodeAlpha_LanguageTranslationTool
   ```

3. **Open `index.html` in your browser**
   ```bash
   # Just double-click index.html
   # OR use VS Code Live Server extension
   ```

> No npm install, no dependencies, no setup — just open and use! ✅

---

## 🌐 Supported Languages

| Language | Code | Language | Code |
|---|---|---|---|
| English | `en` | Arabic | `ar` |
| Hindi | `hi` | Chinese (Simplified) | `zh` |
| French | `fr` | Japanese | `ja` |
| German | `de` | Korean | `ko` |
| Spanish | `es` | Turkish | `tr` |
| Italian | `it` | Dutch | `nl` |
| Portuguese | `pt` | Polish | `pl` |
| Russian | `ru` | Bengali | `bn` |
| Tamil | `ta` | Telugu | `te` |
| Urdu | `ur` | Swedish | `sv` |

---

## 📸 Screenshots

> *(Add screenshots of your project here)*
>
> To add: Take a screenshot → upload to your repo → replace this section with:
> `![Screenshot](screenshot.png)`

---

## 💡 How It Works

1. User enters text in the input box
2. User selects source and target language
3. On clicking **Translate** (or pressing `Ctrl+Enter`), the app sends a `GET` request to the MyMemory API
4. The API returns the translated text
5. Result is displayed with options to copy or listen via Text-to-Speech

```
User Input  →  MyMemory API  →  Translated Output  →  Copy / TTS
```

---

## 🔗 API Used

**MyMemory Translation API** — Free, no authentication required

```
https://api.mymemory.translated.net/get?q={text}&langpair={src}|{tgt}
```

- ✅ Free to use
- ✅ No API key needed
- ✅ Supports 50+ language pairs

---

## 👤 Author

**Sachin**
- 🎓 BCA Graduate — Maharishi University of Information Technology, Lucknow
- 💼 CodeAlpha AI Internship Participant
- 🐙 GitHub: [@Sachin-SDE12](https://github.com/Sachin-SDE12)

---

## 🏢 About CodeAlpha

This project was built as **Task 1** of the **CodeAlpha Artificial Intelligence Internship Program**.

🌐 [www.codealpha.tech](https://www.codealpha.tech)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

⭐ **If you found this useful, please star the repository!**
