# Panshul Parth — Personal Portfolio Website

> **Future Interns — Full Stack Web Development | Task 1**

A clean, modern, and fully responsive personal portfolio website built with pure HTML5, CSS3, and Vanilla JavaScript. No frameworks, no build tools — deploy-ready for GitHub Pages.

---

## Live Demo

**URL:** `https://panshulparth.github.io/FUTURE_FS_01/`

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Structure | HTML5 (semantic markup) |
| Styling | CSS3 (custom properties, flexbox, grid, animations) |
| Logic | Vanilla JavaScript (ES6+) |
| Fonts | Google Fonts — Inter, Fira Code |
| Hosting | GitHub Pages |

---

## Features

- **Sticky Navbar** with active-link highlighting and mobile hamburger menu
- **Hero Section** with typewriter animation cycling through roles
- **About & Resume** section with animated skill bars and coursework
- **Projects Grid** with hover effects and scroll-triggered animations
- **Contact Form** with client-side validation and simulated submission alert
- **Fully Responsive** — tested on mobile, tablet, and desktop
- **SEO-Friendly** — meta tags, Open Graph, semantic HTML
- **Dark Theme** with gradient accents and glassmorphism elements
- **Smooth Scrolling** with Intersection Observer for scroll animations

---

## Project Structure

```
FUTURE_FS_01/
├── index.html      # Main HTML file with all sections
├── style.css       # All styles, CSS variables, and media queries
├── script.js       # Typewriter effect, nav, animations, form logic
└── README.md       # Project documentation
```

---

## Sections

| Section | Description |
|---------|-------------|
| Home / Hero | Introduction with animated typewriter role text |
| About & Resume | Education, skills with animated bars, and coursework |
| Projects | Carbon Spending Tracker + Hackathon Experiences |
| Contact | Validated form with simulated JS alert submission |

---

## Deploy to GitHub Pages — Step by Step

### Prerequisites
- A GitHub account
- Git installed on your machine

### Step 1 — Create the Repository

1. Go to [github.com](https://github.com) and sign in.
2. Click **"New"** to create a new repository.
3. Name it exactly: `FUTURE_FS_01`
4. Set it to **Public**.
5. Do **not** initialize with a README (you already have one).
6. Click **"Create repository"**.

### Step 2 — Push Your Code

Open your terminal in the project folder and run:

```bash
git init
git add .
git commit -m "Initial commit: Portfolio website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/FUTURE_FS_01.git
git push -u origin main
```

Replace `YOUR_USERNAME` with your actual GitHub username.

### Step 3 — Enable GitHub Pages

1. Go to your repository on GitHub.
2. Click **Settings** (top tab).
3. Scroll down to the **"Pages"** section in the left sidebar.
4. Under **"Branch"**, select `main` and folder `/ (root)`.
5. Click **Save**.

### Step 4 — Access Your Live Site

GitHub will display a banner with your live URL:

```
https://YOUR_USERNAME.github.io/FUTURE_FS_01/
```

It may take **1–5 minutes** for the site to go live after enabling Pages.

---

## Customization

To update content, open `index.html` and edit:
- **Name / role** in the hero section
- **Project cards** in the `#projects` section
- **Contact details** in the `#contact` section

To update the typewriter roles, open `script.js` and edit the `roles` array.

---

## Author

**Panshul Parth**
B.Tech Computer Science Engineering — 2nd Year
Full Stack Web Developer & Software Engineering Enthusiast

---

*Built with ❤️ for Future Interns — Task 1 (2026)*
