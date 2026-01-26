# 🚀 VS Code Extensions I Use

This repo contains my **personal VS Code setup**, mainly focused on **frontend development** (HTML, CSS, JS, TS, React, Tailwind) with productivity, clean UI, and better DX in mind.

Below is a curated list of the **VS Code extensions I actively use**, along with what each one does 👇

---

## ✨ Productivity & Editor Enhancements

### 🔁 Auto Rename Tag

**Publisher:** Jun Han
Automatically renames the **closing HTML/XML tag** when you edit the opening tag (and vice versa).

---

### 📁 Project Manager

**Publisher:** Alessandro Fragnani
Easily **open and switch between multiple projects**. Also great for bookmarking important workspaces.

---

### 💬 Better Comments

**Publisher:** Aaron Bond
Adds **color-coded comments** for better readability:

* `// !` Alerts / Warnings
* `// ?` Questions
* `// TODO` Todos
* `// *` Highlights

---

### 🎨 Peacock

**Publisher:** John Papa
Changes the **VS Code window color** per project – super helpful when working with multiple repos at once.

---

## 🎯 Formatting & Code Quality

### 🧹 Prettier – Code Formatter

Formats code automatically to keep it **clean and consistent**.

---

### 🚨 Error Lens

Shows **errors and warnings inline**, right where the problem is – no need to check the Problems panel constantly.

---

### 🧠 Code Spell Checker

**Publisher:** Street Side Software
Catches spelling mistakes in comments, strings, and variable names.

---

## 🔍 Git & Performance Insights

### 🧬 GitLens

Supercharges Git inside VS Code:

* Inline blame
* Commit history
* Author insights

---

### 📦 Import Cost

Displays the **size of imported packages** directly in the editor – helps keep bundles lightweight.

---

## 🌐 Development & Debugging

### ⚡ JavaScript (ES6) Code Snippets

**Publisher:** Charalampos Karypidis
Provides handy **ES6+ JavaScript snippets** to write code faster with less typing.

---

## 🌐 Development & Debugging

### 🌍 Live Server

**Publisher:** Ritwick Dey
Launches a **local development server** with live reload for HTML/CSS/JS projects.

---

### ▶️ Code Runner

**Publisher:** Jun Han
Run snippets of code (JS, TS, Python, etc.) directly inside VS Code.

---

### 🔌 Quokka.js

Instant feedback for **JavaScript / TypeScript** – shows output and values inline as you type.

---

### 🖥️ Remote – SSH

Connect to and work on **remote machines via SSH** directly from VS Code.

---

## 🎨 UI, Media & Visualization

### 🧩 Material Icon Theme

**Publisher:** Philipp Kief
Beautiful and meaningful **file & folder icons**.

---

### 🌙 One Dark Pro

A clean, popular **dark theme** inspired by Atom.

---

### 🖼️ Image Preview

**Publisher:** Kiss
Preview images directly inside VS Code.

---

### 📄 vscode-pdf

View PDF files without leaving the editor.

---

### 🌈 Rainbow CSV

**Publisher:** mechatroner
Colorizes CSV columns for better readability.

---

### 📊 Excel Viewer

**Publisher:** GrapeCity
View Excel files (`.xlsx`, `.xls`) directly in VS Code.

---

### 🧠 Draw.io Integration

Create **flowcharts and diagrams** inside VS Code.

---

### 📸 Polacode

Generate **beautiful screenshots of your code** for sharing on social media or documentation.

---

## ⚙️ API & Testing

### 📬 Postman

Used for **API testing and development**.

---

## 🎨 Custom CSS & JS (VS Code UI Tweaks)

This setup uses **Custom CSS and JS Loader** to deeply customize the VS Code UI (fonts, spacing, animations, visuals, etc.).

### 🔌 Required Extension

**Custom CSS and JS Loader** – *be5invis*

### 📂 File Structure Example

```
C:/Users/Name/Documents/Documents/vscode-setup/
├── vscode-styles.css
└── vscode-script.js
```

### ⚙️ VS Code Configuration

Add the following to your `settings.json`:

```json
"vscode_custom_css.imports": [
  "file:///C:/Users/Name/Documents/Documents/vscode-setup/vscode-styles.css",
  "file:///C:/Users/Name/Documents/Documents/vscode-setup/vscode-script.js"
]
```

### ▶️ How to Enable

1. Install **Custom CSS and JS Loader**
2. Update `settings.json` with the paths above
3. Run command:

   * `Enable Custom CSS and JS`
4. Restart VS Code completely

> ⚠️ Note: VS Code updates may disable custom CSS. Just re-run **Enable Custom CSS and JS** after updates.

---

## 📦 Included Configuration Files

This repository **includes everything needed to use the setup directly**:

* `settings.json` – full VS Code configuration
* `vscode-styles.css` – custom UI styles
* `vscode-script.js` – custom JS tweaks

### ▶️ How to Use This Repo

1. Clone or download this repository
2. Copy `settings.json` into your VS Code **User Settings**
3. Keep `vscode-styles.css` and `vscode-script.js` in the same folder structure
4. Install required extensions
5. Run **Enable Custom CSS and JS** command
6. Restart VS Code

That’s it — no extra configuration required.

---

Happy coding! 🚀
