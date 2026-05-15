# 🃏 Coder Card — DOM Exercise

A hands-on practice project for DOM manipulation using HTML, CSS, and vanilla JavaScript.

![Project preview](/assets/img/screenshot.png)

---

## 📌 Description

An interactive interface that simulates a developer profile card. It allows you to update card content, toggle its visual state, and change colors — all through DOM events, with no external libraries.

---

## 🎯 Concepts Practiced

| Concept | Where it's applied |
|---|---|
| `getElementById` / `querySelectorAll` | Element selection |
| `textContent` | Updating card text |
| `classList.toggle` | Toggling active/inactive visual state |
| `style.backgroundColor` | Color change via buttons |
| `addEventListener` | click, mouseover, mouseout, keydown |
| `input.value` + `.trim()` | Reading and sanitizing input |
| `.inactivo` CSS class | Visual feedback for inactive state |
| CSS `transition` | Smooth animation on color changes |

---

## 🗂️ Project Structure

```
coder-card/
├── index.html
├── styles.css
└── script.js
```

---

## ⚙️ Features

### Step 3 — Changing content with `textContent`
- **Change to Luis Pérez** → replaces the name, language, and status shown on the card.
- **Back to Ana García** → restores the original values.

### Step 4 — Class toggling with `classList`
- **Activate / Deactivate** → adds or removes the `.inactivo` class, which applies reduced opacity and a red border.

### Color change
- Two circular buttons (blue and green) update the card's `backgroundColor` via `style.backgroundColor`.
- `querySelectorAll` + `forEach` is used to attach the event listener to both buttons in a single block.

### Card hover effect
- When the mouse enters the card, the name turns blue (`mouseover`).
- When it leaves, the color resets by assigning `''` to the inline style (`mouseout`).

### Extra challenge — Custom name input
- A text field lets you type any name and apply it with the **Apply** button or by pressing **Enter**.
- The input is validated with `.trim()` before updating the DOM to prevent empty values.

---

## 🚀 How to Run

No installation or server required. Open `index.html` directly in your browser.

```bash
# Quick option from the terminal
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

---

## 🛠️ Technologies

- HTML5
- CSS3 (transitions, dynamic classes)
- Vanilla JavaScript (ES6)

