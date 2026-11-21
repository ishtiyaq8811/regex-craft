# 🔍 RegexCraft Studio — Visual Regex Engine & Test Studio

A powerful, modern, client-side regular expression studio and visual debugger built with pure HTML5, CSS3, and Vanilla JavaScript. Features real-time structural syntax tokenization, interactive match highlighting, capture group inspection, string substitution, curated presets, and multi-language code export with zero external libraries or network dependencies!

![Tool Status](https://img.shields.io/badge/Status-Complete-brightgreen)
![Pure Tech](https://img.shields.io/badge/Tech-HTML5%20%7C%20CSS3%20%7C%20Vanilla%20JS-orange)
![Privacy](https://img.shields.io/badge/Privacy-100%25%20Client--Side%20Offline-success)
![External AI Keys](https://img.shields.io/badge/External%20AI%20Keys-Zero%20Required-blue)
![License](https://img.shields.io/badge/License-MIT-blueviolet)

---

## ✨ Key Features

- **🧩 Real-Time Structural Syntax Breakdown:**
  - Tokenizes regular expression syntax on-the-fly into categorized visual semantic chips.
  - Automatically identifies anchors (`^`, `$`), character sets (`[...]`), quantifiers (`+`, `*`, `{n,m}`), capture groups (`(...)`), named groups (`(?<name>...)`), lookaheads (`(?=...)`, `(?!...)`), and escape characters (`\d`, `\w`, `\b`).
- **📝 Live Match Highlighting & High-Speed Execution:**
  - Dual-layer overlay that highlights all matched text in real-time with sub-millisecond execution benchmarking.
  - Zero-lag performance tracking with infinite zero-length match loop protection.
- **🔬 Match & Capture Group Inspector:**
  - Interactive tabular breakdown of every matched string, character index boundaries (`start..end`), and all sub-group captures (`$1`, `$2`, etc.).
- **🔄 In-Place String Substitution & Replacement:**
  - Real-time string replacement with support for group tokens (`$1`, `$2`), full match (`$&`), before match (`$\``), and after match (`$'`).
  - One-click copy for the transformed output text.
- **⭐ Curated Production Presets:**
  - One-click loadable presets for common patterns:
    - **Email Address (RFC 5322 compatible)**
    - **HTTP / HTTPS URL**
    - **IPv4 Address**
    - **UUID v4**
    - **ISO 8601 Date (`YYYY-MM-DD`)**
    - **Hex Color Code (`#RGB` / `#RRGGBB`)**
    - **Semantic Version (SemVer)**
    - **Password Strength Validator**
- **💻 Multi-Language Code Exporter:**
  - Generates ready-to-run copy-pasteable code snippets for:
    - **JavaScript** (`RegExp.exec()`)
    - **Python** (`re.finditer()`)
    - **Go** (`regexp.MustCompile()`)
    - **Rust** (`regex::Regex`)
    - **Java** (`Pattern` / `Matcher`)
    - **PHP** (`preg_match_all()`)
- **🌓 Dark & Light Mode Theme:**
  - Beautiful glassmorphic UI with theme toggle and state persistence in `localStorage`.
- **🔒 100% Client-Side Privacy:**
  - Runs completely inside the browser. Your regular expressions and test strings are never sent over the network.
  - Requires no AI API key, account, or external backend.

---

## 🚀 How to Run Locally

Simply open `index.html` directly in any modern browser (Chrome, Edge, Firefox, Safari):

```bash
# Optional: serve locally with any static web server
npx serve .
# Or open directly
start index.html
```

---

## 🌐 GitHub Pages Deployment

1. Go to your repository **Settings** > **Pages**.
2. Under **Build and deployment**, select `Deploy from a branch`.
3. Choose branch `main` and folder `/ (root)`, then click **Save**.
4. Your tool will be live at:
   `https://ishtiyaq8811.github.io/regex-craft/`

---

## 📄 License

MIT License. Free for open-source and commercial use.
