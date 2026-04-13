# 🌸 Jagruti Mane — Personal Portfolio Website

A beginner-friendly personal portfolio website built with **HTML and CSS only** — no JavaScript needed!

---

## 📁 Files in This Project

| File | What it does |
|------|-------------|
| `index.html` | The main web page (structure & content) |
| `style.css` | All the colours, fonts, and layout |
| `profile.svg` | Fallback placeholder image (shown if your photo is missing) |
| `IMG-20260402-WA0006.jpg` | **Your profile photo** — upload this file to the repository! |
| `README.md` | This guide |

---

## 🚀 How to View the Website

1. Download or clone this repository to your computer.
2. Open the `index.html` file in any web browser (Chrome, Firefox, Edge, etc.).
3. That's it! You'll see your portfolio live.

---

## 📸 IMPORTANT — Add Your Photo

The website is ready to display your photo. To make it appear:

1. Upload your photo file named **`IMG-20260402-WA0006.jpg`** to this repository  
   *(GitHub → Add file → Upload files → choose your photo → Commit)*
2. Refresh the page — your photo will appear automatically!

> If you want to use a different file name, open `index.html` and find the two lines that say `src="IMG-20260402-WA0006.jpg"` and change both to your file name.

---

## ✏️ How to Edit the Content

All edits are made inside the **`index.html`** file. Open it in any text editor (Notepad, VS Code, etc.) and look for the comments that start with `<!-- =====` — they explain every section.

### 1. Change your name or title
Find the hero section in `index.html`:
```html
<h1 class="hero-name">Jagruti Mane</h1>
<p class="hero-title">Aspiring Web Developer &amp; Creative Thinker</p>
```
Change the text between the tags to whatever you like.

---

### 2. Edit the About Me section
Find the `<section id="about">` block and change the paragraph text:
```html
<p>
  Hi! I'm <strong>Jagruti Mane</strong> — write your own bio here!
</p>
```

---

### 3. Add or remove a Skill
Skills are displayed as cards with a progress bar. To add a new skill, copy a `skill-card` block and update the icon, name, percentage, and bar width:
```html
<div class="skill-card">
  <div class="skill-top">
    <span class="skill-icon">⭐</span>
    <span class="skill-name">Your Skill</span>
    <span class="skill-pct">70%</span>
  </div>
  <div class="skill-bar-bg">
    <div class="skill-bar-fill" style="width: 70%;"></div>
  </div>
</div>
```

---

### 4. Add a new Project
Inside the `<section id="projects">` block, copy and paste this project card template:
```html
<div class="project-card">
  <div class="project-emoji">⭐</div>
  <h3>Your Project Title</h3>
  <p>A short description of your project and what you built.</p>
  <div class="project-tags">
    <span>HTML</span><span>CSS</span>
  </div>
  <a href="https://github.com/yourusername/yourproject" class="project-link">View Project →</a>
</div>
```
Replace the emoji, title, description, tags, and link with your actual project details.

---

### 5. Update Contact Information
Find the `<section id="contact">` block. Update each `<a href="...">` link:

- **Email:** Change `your.email@example.com` to your real email address.
- **LinkedIn:** Change the URL to your LinkedIn profile link.
- **GitHub:** Change the URL to your GitHub profile link.

---

## 🎨 How to Change Colours

Open `style.css` and look for the colour section at the top. The comment block explains which colours to change:

- Main purple: `#7c3aed`
- Lighter purple: `#9d4edd`
- Background: `#f5f0ff`
- Dark headings: `#1e1b4b`

Replace any of these values with a new colour code. Find colour codes at [coolors.co](https://coolors.co) or [htmlcolorcodes.com](https://htmlcolorcodes.com).

---

## 📱 Responsive Design

The website automatically adjusts to look great on mobile phones, tablets, and desktops — no extra work needed!

---

## 💡 Tips for Beginners

- Save your file after every change, then **refresh the browser** to see the update.
- If something looks wrong, press **Ctrl + Z** to undo the last change.
- Use [W3Schools HTML Tutorial](https://www.w3schools.com/html/) to learn more HTML basics.
- Use [W3Schools CSS Tutorial](https://www.w3schools.com/css/) to learn how to style further.

---

Made with ❤️ using HTML & CSS.
