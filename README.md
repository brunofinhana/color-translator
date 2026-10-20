# Color Translator 🎨🦎

A lightweight, accessible web application that translates HEX color codes into plain English color names and vice-versa.

## 💡 Context & Purpose

Working with digital colors can be challenging for non-designers and individuals with color blindness (daltonism). **Color Translator** bridges this gap by providing an instant, visual translation between hexadecimal codes (e.g., `#FF0000`) and human-readable color names (e.g., `Red`).

## ✨ Key Features

* **Bi-Directional Lookup:** Translates HEX codes to color names and color names to HEX codes.
* **Dynamic Preview:** Instantly updates the page background color to reflect the active color input.
* **High Contrast UI:** Utilizes CSS `mix-blend-mode: difference` to maintain text legibility regardless of background brightness.
* **Responsive & Minimalist:** Built with a clean interface that adapts to mobile and desktop screen sizes.
* **Keyboard Navigation:** Triggers translations via the "Go" button or by pressing `Enter`.
* **Hidden Easter Eggs:** Interactive surprises when searching for classic rock band names.

## 🛠️ Tech Stack & Concepts Applied

### Frontend
* **HTML5:** Semantic elements and viewport meta tags for responsive layouts.
* **CSS3:**
  * **CSS Grid & Flexbox:** Used for page layout and element alignment.
  * **Blend Modes:** Applied `mix-blend-mode: difference` for high contrast UI readability.
  * **Media Queries:** Designed for mobile responsiveness.
* **Vanilla JavaScript:**
  * **DOM Manipulation:** Reads user inputs and dynamically alters page content and styles.
  * **Event Listeners:** Listens for mouse clicks and keyboard `Enter` key presses.
  * **Control Flow:** Employs `switch` statements to map colors and handle edge cases.

## 🎵 Easter Eggs

Try typing some classic band names into the search input:
* `BLACK SABBATH`
* `PINK FLOYD`
* `GREEN DAY`
* `RED HOT CHILI PEPPERS`
* `WHITESNAKE`

## 🚀 How to Run Locally

1. Clone or download this repository.
2. Open `index.html` directly in any web browser. No build steps or server configurations required!

---

**Created by Bruno Finhana**
