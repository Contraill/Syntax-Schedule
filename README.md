# 📅 Syntax Schedule Templates

Print-ready weekly schedule templates (A4) built with pure **HTML + CSS**.

This repository includes multiple visual timetable templates:

- `Syntax Schedule.html` → main IT schedule template
- `PhysioFlow.html` → physiotherapy-focused schedule template

No framework, no build step — just open in browser and print.

---

## 🚀 Quick Start

1. Clone or download the repo
2. Open one of these files in your browser:
   - `Syntax Schedule.html`
   - `PhysioFlow.html`
3. Edit course blocks directly in the HTML
4. Print to PDF / paper (A4)

---

## 🧩 How to Edit a Class Block

Each lesson is one `<div class="class-block ...">` item.

Example:

```html
<div class="class-block Blue" style="grid-column:2; grid-row:3">
  <div class="class-text">ITEC413
    <div class="classroom">CT 223</div>
  </div>
</div>
```

### Grid Mapping

- **Columns (days)**
  - `2 = Monday`
  - `3 = Tuesday`
  - `4 = Wednesday`
  - `5 = Thursday`
  - `6 = Friday`

- **Rows (time slots)**
  - `2 = 08:30`
  - `3 = 09:30`
  - `4 = 10:30`
  - `5 = 11:30`
  - `6 = 12:30`
  - `7 = 13:30`
  - `8 = 14:30`
  - `9 = 15:30`
  - `10 = 16:30`
  - `11 = 17:30` *(if used in file)*

---

## 🎨 Color System

Block colors are controlled by CSS classes (e.g. `Blue`, `Purple`, `Green`, ...).

To add a new color:

1. Copy an existing color rule in CSS
2. Rename it
3. Use that class name in your block

---

## 🖨️ Print Settings (Important)

For best output:

- Enable **Background graphics**
- Scale: **100% / Actual size**
- Margins: **Default** or **None**
- Paper: **A4**

---

## 📁 File Overview

- `Syntax Schedule.html` — dark IT-style timetable
- `PhysioFlow.html` — cleaner health-science timetable variant

---

## ✅ Notes

- Both templates are standalone static files
- Safe to edit in any text editor (VS Code, Sublime, etc.)
- You can duplicate templates for each semester/program

## 🧪 Print Tip (Tested)

If the layout spills into a second page:

- Set print **Scale to 93%**
- Print only **Page 1**

This keeps the schedule clean on a single A4 page.

