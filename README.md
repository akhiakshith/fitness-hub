# 🏋️ Fitness Hub — Interactive Training & Diagnostic Dashboard

A premium, front-end training application built around a high-tech obsidian carbon dark theme with glowing neon-orange accents. It features interactive muscle map body scanners, workout planners, and diagnostic health calculators.

---

## ⚡ Main Features

### 1. Interactive Anatomy Scanners
- **Gender-Specific Maps:** Integrated dual SVG-mapped anatomical diagrams for both **male** and **female** physiological frames.
- **Muscle-Targeted Navigation:** Interactive polygon areas on the chest, biceps, abs, thighs, and calves link directly to targeted exercise guides.

### 2. Muscle Training Databases
- Clean, grid-based selectors for compound and isolation movements.
- Detailed step-by-step instructions (e.g. Barbell Bench Press, Cable Chest Press, Dumbbell Incline Flys).
- **Embedded Telemetry Video Players:** High-quality autoplaying loops demonstrating correct form and execution.

### 3. Integrated Health Calculators
- **Calorie Calculator:** Computes estimated baseline daily caloric needs based on a customized Harris-Benedict mathematical formula.
- **BMI Calculator:** Evaluates height-to-weight body mass index scores and outputs categorized fitness brackets (e.g. Underweight, Normal, Overweight, Obese).

### 4. Branded Form Entry
- Premium glassmorphic Sign-in interface (`login.html`) with customized term panels and client credential handling.

---

## 🛠️ Tech Stack & Design Architecture

- **Interface:** HTML5, custom-styled SVG Image Maps
- **Styling:** CSS3 (floating blur headers, obsidian carbon variables, glowing active states)
- **Interactive Scripting:** JavaScript (validation, math engines, slide animation triggers)
- **Typography:** Google Fonts (`Outfit` & `Space Grotesk`)

```
fitness-hub/
├── fitnesshub.html      # Main interactive home dashboard
├── calorie.html         # Calorie intake calculator
├── bmi.html             # Body Mass Index calculator
├── login.html           # Sign-in portal with Terms overlay
├── style1.css           # Global dashboard style configurations
├── female.css           # Layouts for female exercise index pages
├── male.css             # Layouts for male exercise index pages
├── substyle.css         # Styling for nutritional/misc subpages
├── F[muscle].html       # Female targeted muscle guides (e.g., Fchest.html)
├── M[muscle].html       # Male targeted muscle guides (e.g., Mchest.html)
└── assets/              # Loop videos and graphics
```

---

## 🚀 Launch Instructions

Since the dashboard is composed of client-side static web technologies, it can be launched directly:

1. Open `fitnesshub.html` in any modern web browser.
2. Alternatively, run a simple local web server from the project directory:
   ```bash
   python -m http.server 8000
   ```
   Open `http://localhost:8000/fitnesshub.html` to explore the interactive anatomy map.
