# 🎓 Vidya — Karnataka SSLC AI Tutor

> **For students:** Just open the link — no setup needed!

An AI-powered tutor for Karnataka SSLC Class 10 students (2025-26), built on official DSERT textbooks and KSEAB blueprints.

## 🔧 For the owner: Adding your API key

Open `index.html` and find line ~5:
```js
const VIDYA_API_KEY = 'PASTE_YOUR_GEMINI_KEY_HERE';
```
Replace with your key from [aistudio.google.com/apikey](https://aistudio.google.com/apikey)

### 🔒 Secure your key (important!)
Since the key is in a public file, **restrict it** to your domain only:
1. Go to [Google Cloud Console](https://console.cloud.google.com) → **APIs & Services** → **Credentials**
2. Click your API key → **Application restrictions** → **HTTP referrers**
3. Add: `https://YOUR-USERNAME.github.io/*`

This means your key only works on your GitHub Pages site — useless if stolen.

## 🚀 Deploy to GitHub Pages
1. Create a **public** repo on GitHub
2. Upload `index.html` + `README.md`
3. Go to **Settings** → **Pages** → Deploy from `main` branch → `/ (root)`
4. Live at: `https://YOUR-USERNAME.github.io/REPO-NAME/`

## ✨ Features
- All SSLC subjects: Maths, Science, Social Science, English FL, Hindi, Kannada
- Official KSEAB 2025-26 blueprints with exact chapter-wise marks
- Interactive quiz mode — MCQ buttons + written answer inputs
- Step-by-step Maths solutions with mark scheme
- Upload question papers / blueprints for analysis
- Formulas & Notes reference tab

## 📅 Exam 1: March 18, 2026
