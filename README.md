# TermRunway-Web 💸

> **The original TermRunway web prototype — preserved as product history.**

> ⚠️ **Status: Discontinued / Historical Prototype**

The web version helped explore the original budgeting concept. After evaluating the product fit, it was replaced by a **native, offline-first Android application** with stronger alignment to the intended student workflow.

🚀 **Current product:** [TermRunway-Android](https://github.com/BoyidapuMaheshBabu/TermRunway-Android)

---

## 🧭 Why It Changed

The prototype helped expose important product constraints:

- browser storage was not the ideal long-term foundation
- the experience was tied to the browser environment
- phone-first usage became more important
- privacy and offline-first behavior became core priorities
- the product needed a more focused architecture

Instead of continuing to add features to the web version, the product direction was reconsidered.

> **A useful engineering decision is sometimes knowing when to change the foundation.**

## 💡 What the Prototype Explored

| Area | Original capability |
|---|---|
| 💰 Budgeting | Semester and monthly budgeting |
| 📊 Calculations | Balance and daily spending limits |
| 🗂️ Categories | Multiple income and expense categories |
| 💾 Persistence | Browser `localStorage` |
| 🛡️ Validation | Input validation and edge cases |
| 📱 UI | Responsive layouts |
| 🧾 Output | Print / PDF-friendly summary |

### Original Flow

```
Income + Expenses
       ↓
Remaining Balance
       ↓
Time Remaining
       ↓
Daily Spending Limit
```

The prototype also explored missing dates, expired periods, zero income, expenses exceeding available funds, invalid numeric input, editing and reset flows.

## 🧠 What It Taught Me

This project was an important product and engineering learning stage.

It exposed practical lessons around:

- application logic and calculations
- input validation and edge cases
- date handling
- JSON data representation
- browser persistence
- responsive layouts
- product evaluation
- deciding when an architecture no longer fits the problem

The most important lesson:

> **Building a product is not only about adding features. It is also about recognizing when the current approach is no longer the right foundation.**

## 🤖 AI-Assisted Development

AI was used throughout the prototype as a development and learning tool for:

- exploring unfamiliar implementation details
- generating or modifying code
- understanding errors
- iterating on features
- debugging and experimentation

The project is intentionally **not presented as line-by-line manual coding**. Its value is in the engineering process: build → encounter problems → learn → test → evaluate → improve.

## 🛠️ Technology

**HTML5** · **CSS3** · **Vanilla JavaScript** · **JSON** · **localStorage** · **DOM APIs** · **Git** · **GitHub** · **Netlify**

## 📁 Original Structure

```
TermRunway-Web/
├── index.html
├── home.html
├── css/
│   ├── styles.css
│   └── home.css
├── js/
│   └── script.js
└── README.md
```

## 🔄 Development History

```
Idea
  ↓
Web Prototype
  ↓
Build + Test
  ↓
Identify Limitations
  ↓
Reconsider Product Architecture
  ↓
Native Android Product
```

The Android repository is now the **active implementation project**.

## 👨‍💻 Developer

**Boyidapu Mahesh Babu**  
Diploma in Computer Science Engineering student

[GitHub Profile](https://github.com/BoyidapuMaheshBabu)

---

> Preserved as the original TermRunway prototype and part of the product's development history. 🕰️
