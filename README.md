# 👩💻 Ankita Das — Portfolio

[![GitHub Pages](https://img.shields.io/badge/Live-GitHub%20Pages-6d5acd?style=for-the-badge&logo=github)](https://ankitadas1999.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-ankita--das--2012-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/ankita-das-2012/)

My personal portfolio website showcasing my experience, projects, skills, and certifications as a Software Engineer and MS Computer Science student at Northeastern University.

## 🚀 Live Site

**[ankitadas1999.github.io](https://ankitadas1999.github.io)**

> Replace with your actual GitHub Pages URL.

## ✨ Features

- 🌗 **Dark / Light Theme** — toggle with localStorage persistence
- 🎨 **Particle Background** — animated canvas with connecting lines
- ⌨️ **Typewriter Effect** — cycling hero titles
- 📜 **Scroll Animations** — elements reveal on scroll using Intersection Observer
- 🔢 **Animated Counters** — stats count up when they enter the viewport
- 🖱️ **Cursor Glow** — subtle radial gradient follows the mouse
- 📱 **Fully Responsive** — mobile-first with hamburger menu
- 🧭 **Smart Navbar** — auto-hides on scroll down, highlights active section

## 🛠️ Tech Stack

| Layer       | Technology                   |
| ----------- | ---------------------------- |
| Structure   | HTML5                        |
| Styling     | CSS3 (Custom Properties)     |
| Interactivity | Vanilla JavaScript (ES6+)  |
| Fonts       | Google Fonts (Inter, Fira Code) |
| Icons       | Font Awesome 6               |
| Hosting     | GitHub Pages                 |

## 📂 Project Structure

```text
.
├── index.html    # Main HTML — all sections
├── style.css     # Theming, layout, animations
├── script.js     # Particles, typewriter, scroll effects
└── README.md
```

## 🏁 Getting Started

### Prerequisites

No build tools or dependencies required — just a browser.

### Run Locally

```bash
# Clone the repository
git clone https://github.com/ankita-das/ankita-das.github.io.git
cd ankita-das.github.io

# Open in your browser
open index.html
# or use a live server (e.g., VS Code Live Server extension)
```

### Deploy to GitHub Pages

1. Make sure the repository is named `<your-username>.github.io`.
2. Push your code to the `main` branch.
3. Go to **Settings → Pages → Source** and select `main` / `root`.
4. Your site will be live at `https://<your-username>.github.io` within a minute.

## 🎨 Customization

### Theme Colors

Edit the CSS custom properties in `style.css` under `[data-theme="dark"]` and `[data-theme="light"]`:

```css
[data-theme="dark"] {
  --accent: #6d5acd;        /* Primary accent */
  --accent-light: #8b7ae0;  /* Hover / highlights */
  --bg-primary: #0a0a0f;    /* Page background */
  /* ... */
}
```

### Typewriter Titles

Edit the `titles` array in `script.js`:

```js
const titles = [
  "Senior Software Engineer",
  "Cloud Architecture Enthusiast",
  "AI & ML Explorer",
  "Full-Stack Developer",
];
```

### Adding a New Project

Copy an existing `project-card` block in the Projects section of `index.html` and update the title, description, tech tags, and links.

### Adding a Custom Domain

1. Purchase a domain (e.g., from Namecheap, Google Domains).
2. Add a `CNAME` file to the repo root containing your domain:
   ```text
   ankitadas.com
   ```
3. Configure DNS records per [GitHub's docs](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site).

## 📄 Sections

| #  | Section    | Description                              |
| -- | ---------- | ---------------------------------------- |
| 01 | About      | Bio, tech list, animated stat cards      |
| 02 | Education  | Northeastern University, NIT Rourkela    |
| 03 | Experience | Timeline with John Deere & Blitz Jobs    |
| 04 | Skills     | Categorized skill tags with hover effects|
| 05 | Projects   | Turf Booking, Face Mask Detection, Cloud |
| 06 | Awards     | AWS Cert, Hackathon Winner, Innovation   |
| 07 | Contact    | Email CTA, social links                  |

## 📬 Contact

- **Email:** [dasankita1220@gmail.com](mailto:dasankita1220@gmail.com)
- **LinkedIn:** [linkedin.com/in/ankita-das-2012](https://linkedin.com/in/ankita-das-2012/)

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

---

⭐ If you found this helpful, give the repo a star!