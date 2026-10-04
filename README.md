# TermRunway-Web 💸

> **Original web prototype of TermRunway — now discontinued.**

> ⚠️ **Project Status: Discontinued / Archived Prototype**
>
> This repository contains the original web version of TermRunway.
>
> After evaluating the limitations of the web approach for the intended student-finance use case, development of this version was stopped. The product was redesigned as a **native, offline-first Android application** with a stronger focus on privacy, reliability, and the actual student workflow.
>
> 🚀 **Current product:** [TermRunway-Android](https://github.com/BoyidapuMaheshBabu/TermRunway-Android)
>
> This repository is preserved as part of the product's development history and learning journey.

## 📌 Why the Project Changed

The web version was useful for exploring the original product idea and learning how to build a student budgeting application.

During development, however, the project exposed limitations around the intended use case:

- financial data was dependent on browser storage
- the experience was tied to the browser environment
- long-term product direction required a more dedicated mobile experience
- privacy and offline-first usage became higher priorities
- the product needed a more focused architecture for daily student use

Instead of continuing to add features to the web prototype, I chose to **rethink the product and rebuild it as a native Android application**.

That decision became the foundation for the current TermRunway product.

## 💡 What the Web Prototype Did

The original TermRunway web application helped students understand their income, expenses, remaining balance, and practical daily spending limits for a semester or month.

### Original Highlights

- Semester and monthly budgeting
- Multiple income sources and expense categories
- Automatic balance and daily spending-limit calculations
- Browser-based persistence with `localStorage`
- Input validation and edge-case handling
- Responsive mobile, tablet, and desktop layouts
- Progressive planning and dashboard workflow
- Edit and reset controls with confirmation
- Print / PDF-friendly budget summary

### Original Flow

```text
Income + Expenses
       ↓
Remaining Balance
       ↓
Time Remaining
       ↓
Daily Spending Limit
```

The application handled cases such as missing dates, expired periods, zero income, expenses exceeding available funds, and invalid numeric input.

## 🧠 What I Learned

This project was an important practical learning stage before the Android version.

Key areas explored:

- application logic and calculations
- input validation and edge cases
- date handling
- JSON-based data representation
- browser `localStorage` and persistence
- responsive layouts
- browser print functionality
- maintaining and improving an existing application
- evaluating product limitations instead of endlessly extending an approach
- making architecture decisions based on the actual use case

The most important lesson was that **building a product is not only about adding features; it is also about recognizing when the current approach is no longer the right foundation.**

## 🤖 AI-Assisted Development

TermRunway-Web was built incrementally with AI assistance.

I used AI as a development and learning tool to explore unfamiliar implementation details, generate or modify code, understand errors, and iterate on features.

The project is **not presented as line-by-line manual coding without AI assistance**. Its value for me is in building, encountering problems, learning what was needed, testing, evaluating limitations, and improving the product direction.

## 🛠️ Technology

- HTML5
- CSS3
- Vanilla JavaScript
- JSON
- Browser `localStorage`
- DOM APIs
- Git
- GitHub
- Netlify

## 📁 Original Project Structure

```text
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

## 🔬 Development History

TermRunway started as a web-based budgeting concept.

The development path was:

```text
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

The Android version is now the **active development project**.

## 👨‍💻 Developer

**Boyidapu Mahesh Babu**  
Diploma in Computer Science Engineering student

GitHub: [@BoyidapuMaheshBabu](https://github.com/BoyidapuMaheshBabu)

---

**Preserved as the original TermRunway web prototype and part of the product's development history.**
