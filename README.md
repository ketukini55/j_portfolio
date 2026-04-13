# 🌸 Jagruti Mane — Personal Portfolio Website

A beginner-friendly personal portfolio website built with **HTML and CSS only** — no JavaScript needed!

---

## 📁 Files in This Project

| File | What it does |
|------|-------------|
| `index.html` | The main web page (structure & content) |
| `style.css` | All the colours, fonts, and layout |
| `profile.svg` | Placeholder profile image (replace with your own photo) |
| `README.md` | This guide |

---

## 🚀 How to View the Website

1. Download or clone this repository to your computer.
2. Open the `index.html` file in any web browser (Chrome, Firefox, Edge, etc.).
3. That's it! You'll see your portfolio live.

---

## ✏️ How to Edit the Content

All edits are made inside the **`index.html`** file. Open it in any text editor (Notepad, VS Code, etc.) and look for the comments that start with `<!-- =====` — they explain every section.

### 1. Change your name or tagline
Find this part in `index.html`:
```html
<h1>Jagruti Mane</h1>
<p class="tagline">Aspiring Developer &amp; Creative Thinker</p>
```
Change the text between the tags to whatever you like.

---

### 2. Add your profile photo
1. Copy your photo into the same folder as `index.html`.
2. Rename your photo to `profile.jpg` **OR** update the `src` attribute in the HTML:
```html
<img src="profile.jpg" alt="Photo of Jagruti Mane" />
```
Change `profile.svg` to your actual file name (e.g. `profile.jpg` or `my-photo.png`).

---

### 3. Edit the About Me section
Find the `<section id="about">` block and change the paragraph text:
```html
<p>
  Hi! I'm <strong>Jagruti Mane</strong> — write your own bio here!
</p>
```

---

### 4. Add or remove a Skill
Skills are displayed as colourful badges. To add one, copy this line inside the `<div class="skills-grid">` section:
```html
<span class="skill-badge">Your New Skill</span>
```

---

### 5. Add a new Project
Inside the `<section id="projects">` block, copy and paste this project card template:
```html
<div class="project-card">
  <h3>Your Project Title</h3>
  <p>A short description of your project and what you built.</p>
  <a href="https://github.com/yourusername/yourproject">View Project →</a>
</div>
```
Replace the title, description, and link with your actual project details.

---

### 6. Update Contact Information
Find the `<section id="contact">` block. Update each `<a href="...">` link:

- **Email:** Change `your.email@example.com` to your real email address.
- **LinkedIn:** Change the URL to your LinkedIn profile link.
- **GitHub:** Change the URL to your GitHub profile link.

To add a new contact method, copy one `<li>` block and update the emoji icon, link text, and URL.

---

## 🎨 How to Change Colours

Open `style.css` and look for the colour codes (they look like `#6c3fc5`).

The main purple colour is `#6c3fc5` and the pink accent is `#b06ab3`. Replace these with any colour you like. You can find colour codes at [coolors.co](https://coolors.co) or [htmlcolorcodes.com](https://htmlcolorcodes.com).

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
