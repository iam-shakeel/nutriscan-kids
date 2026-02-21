# 🍎 NutriScan Kids

AI-Powered Child Snack Health Evaluator for Pakistan

---

## ⚡ Setup (3 Steps)

### Step 1 — Add your API Key
Open `src/utils/analyzeSnack.js` and replace line 7:
```js
export const GROQ_API_KEY = "YOUR_GROQ_API_KEY_HERE";
```
With your actual key:
```js
export const GROQ_API_KEY = "gsk_xxxxxxxxxxxxxxxxxxxxxxxxxxxx";
```
👉 Get free key at: https://console.groq.com

### Step 2 — Install & Run
```bash
npm install
npm run dev
```

### Step 3 — Open Browser
Visit: http://localhost:5173

---

## 📁 Files
```
src/
├── App.jsx               ← All UI components
├── App.css               ← All styles
├── index.css             ← Global styles
├── main.jsx              ← React entry
└── utils/
    └── analyzeSnack.js   ← 🔑 PUT YOUR API KEY HERE + AI engine
```

---

## ✅ Model Used
`meta-llama/llama-4-scout-17b-16e-instruct` (Llama 4 Scout Vision — current & free on Groq)
