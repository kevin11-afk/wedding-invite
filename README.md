# 💍 Virat & Anushka Wedding Invitation Website

A premium, interactive South Indian wedding invitation website built using pure **HTML, CSS, and JavaScript**.

This project delivers a cinematic and elegant digital wedding experience with smooth animations, cultural design elements, and interactive media.

---

## ✨ Features

### 🎬 Hero Section

* Animated temple-style entrance
* Opening doors animation
* Couple silhouette with divine glow
* Smooth scroll-based storytelling

### 📖 Our Story

* Elegant couple introduction layout
* Timeline-based love story
* Image frame with custom upload support

### 🖼️ Gallery

* Grid-based responsive layout
* Supports both **images and videos**
* Click to open fullscreen **lightbox**
* Auto-playing video inside modal

### 👨‍👩‍👧 Family Section

* Separate bride & groom family sections
* Upload photos dynamically
* Interactive hover effects

### 📅 Events Section

* Wedding events displayed as premium cards
* Smooth hover animations
* Fully responsive layout

### 📩 RSVP Form

* Clean and modern form UI
* Attendance selection (Yes / No)
* Submission success state

### 📍 Location Section

* Embedded Google Map
* Venue details with directions button

### 🎵 Extras

* Background music toggle button
* Floating "Save the Date" badge
* Falling petals animation
* Smooth scroll navigation

---

## 🛠️ Tech Stack

* **HTML5**
* **CSS3 (Custom Design System)**
* **Vanilla JavaScript (No frameworks)**

---

## 📂 Project Structure

### ✅ Option 1: Single HTML File (Recommended)

```
project/
│
├── index.html   (contains HTML + CSS + JS)
└── README.md
```

👉 All styles and scripts are included inside one file using:

```html
<style>...</style>
<script>...</script>
```

---

### ✅ Option 2: Separate Files (Modular Structure)

```
project/
│
├── index.html
├── images/
│   ├── couple_image.webp
│   ├── gallery images...
│   └── videos...
├── css/
│   └── styles.css
├── js/
│   └── script.js
└── README.md
```

👉 Link them in HTML:

```html
<link rel="stylesheet" href="css/styles.css">
<script src="js/script.js"></script>
```

---

## 🚀 How to Run

1. Download or clone the project
2. Place your images & videos inside the `images/` folder (if using modular structure)
3. Open `index.html` in your browser

```bash
git clone <your-repo-link>
cd project
open index.html
```

---

## ⚠️ Important Notes

### 🎥 Video Not Playing Fix

* Use simple file names (avoid spaces & emojis)
* Example:

  ```
  virushka.mp4
  ```
* Ensure correct path:

  ```html
  <video src="images/virushka.mp4"></video>
  ```

---

### 🖼️ Image Not Showing

* Check file path
* Ensure image exists inside `images/` folder
* Use correct extensions (`.jpg`, `.png`, `.webp`)

---

### 🔊 Autoplay Restrictions

Browsers may block autoplay unless:

* `muted` is enabled
* User interacts with the page

---

## 🎨 Customization

You can easily customize:

* 💑 Couple names
* 📅 Wedding date
* 📍 Location & map
* 🖼️ Gallery content
* 🎵 Background music
* 🎨 Colors (CSS variables in `:root`)

---

## 🌟 Future Improvements

* Swipe-based mobile gallery
* Video reels-style scrolling
* Backend RSVP storage (Firebase / FastAPI)
* Dynamic content using JSON
* Multi-language support

---

## 📸 Preview

Aesthetic South Indian wedding theme with:

* Temple-inspired visuals
* Gold & maroon palette
* Cinematic animations

---

## 🤝 Credits

Designed & Developed by **Kavinilavan**
Inspired by modern Indian wedding aesthetics.

---

## 📜 License

This project is open for personal and educational use.

---

> “Two souls, one story, one forever.” 💛
