# Mohammed Mahir — Data Analyst Portfolio
 
> *"Turning raw data into clear decisions."*
 
A sleek, dark-themed personal portfolio built with pure HTML, CSS, and vanilla JavaScript — no frameworks, no dependencies, just fast and sharp.
 
---
 
## ✦ Live Preview
 
![Portfolio Preview](https://img.shields.io/badge/Status-Live-00ff6a?style=for-the-badge&labelColor=020402)
![HTML](https://img.shields.io/badge/HTML5-020402?style=for-the-badge&logo=html5&logoColor=00ff6a)
![CSS](https://img.shields.io/badge/CSS3-020402?style=for-the-badge&logo=css3&logoColor=00ff6a)
![JavaScript](https://img.shields.io/badge/JavaScript-020402?style=for-the-badge&logo=javascript&logoColor=00ff6a)
 
---
 
## ✦ Features
 
| Feature | Description |
|---|---|
| 🖱 **Custom Cursor** | Magnetic dot + ring cursor with hover scale effects |
| 🌐 **Grid Background** | Subtle green-tinted grid overlay for a terminal aesthetic |
| 📺 **Scanline Overlay** | CRT-style scanlines for a retro-data feel |
| 🔢 **Counter Animation** | Stats count up on scroll into view |
| 📊 **Skill Bars** | Animated fill bars triggered on intersection |
| ✨ **Scroll Reveal** | Elements fade and slide in as you scroll |
| 💬 **Contact Form** | Validated form with toast notification feedback |
| 📐 **Responsive Design** | Mobile-friendly layout with adaptive grid |
| 🔗 **Active Nav Highlight** | Navigation links highlight based on current section |
 
---
 
## ✦ Sections
 
```
MM://portfolio
│
├── Hero          — Name, tagline, animated orbital graphic
├── Stats Bar     — Years experience, projects, tools, data-driven %
├── About         — Bio + terminal-style JSON profile card
├── Skills        — 7 tool cards with animated proficiency bars
├── Projects      — 3 featured project cards with tags
└── Contact       — Info panel + message form with toast feedback
```
 
---
 
## ✦ Tech Stack
 
```json
{
  "markup":     "HTML5",
  "styling":    "CSS3 (custom properties, clip-path, animations)",
  "scripting":  "Vanilla JavaScript (ES6+)",
  "fonts":      ["Space Mono", "Syne"],
  "apis":       ["IntersectionObserver", "requestAnimationFrame"],
  "deps":       "None"
}
```
 
---
 
## ✦ Design System
 
```css
--black:       #020402   /* Base background     */
--green:       #00ff6a   /* Primary accent      */
--green-dim:   #22c55e   /* Secondary accent    */
--text:        #c8ffd9   /* Body text           */
--text-muted:  #5a8c68   /* Subdued text        */
--mono:        'Space Mono', monospace
--display:     'Syne', sans-serif
```
 
The palette is built around a single neon green accent against near-black — intentionally minimal, high-contrast, and data-terminal inspired.
 
---
 
## ✦ Project Structure
 
```
portfolio/
└── index.html        # Single-file portfolio (HTML + CSS + JS)
```
 
Everything lives in one file — no build steps, no bundler, no config. Open and ship.
 
---
 
## ✦ Getting Started
 
```bash
# Clone the repo
git clone https://github.com/yourusername/portfolio.git
 
# Open in browser
open index.html
# — or just drag index.html into any browser
```
 
No install. No `npm install`. No waiting.
 
---
 
## ✦ Customization Guide
 
### Update personal info
Find the `analyst.json` terminal block in the **About** section and edit the values:
```html
"name":     "Your Name"
"role":     "Your Role"
"location": "Your City, Country"
```
 
### Update stats
In the **Stats Bar**, change `data-target` on each `.stat-number`:
```html
<div class="stat-number" data-target="1">0</div>   <!-- Years exp    -->
<div class="stat-number" data-target="20">0</div>  <!-- Projects     -->
```
 
### Add/remove skill cards
Duplicate a `.skill-card` block in the **Skills** section and update the icon, name, level, and `data-width` (0–100):
```html
<div class="skill-fill" data-width="85"></div>
```
 
### Add projects
Duplicate a `.project-card` block in the **Projects** section. Update the number, title, description, and `.tag` spans.
 
### Update contact details
Edit the `.contact-value` elements in the **Contact** section with your real email and location.
 
---
 
## ✦ Skills Showcased
 
- 🐍 Python — Advanced (90%)
- 🗄️ SQL — Advanced (88%)
- 📊 Power BI — Proficient (82%)
- 📈 Excel — Advanced (85%)
- 📐 Statistics — Proficient (78%)
- 🧹 Data Cleaning — Expert (92%)
- 🤖 Machine Learning — Intermediate (70%)
---
 
## ✦ Projects Featured
 
1. **Sales Dashboard** — Power BI / DAX / SQL · Reduced reporting time by 60%
2. **Data Cleaning Pipeline** — Python / Pandas / NumPy · Improved data accuracy by 40%
3. **SQL Analysis Engine** — SQL / PostgreSQL · Million-row dataset analytics
---
 
## ✦ Contact
 
| Channel | Details |
|---|---|
| 📧 Email | mahirbelim1974@gmail.com |
| 📍 Location | Indore, Madhya Pradesh, India |
| 🟢 Status | Available for opportunities |
 
---
 
## ✦ License
 
This portfolio is open for inspiration and personal use. If you build something from it, a credit is appreciated — not required.
 
---
 
<div align="center">
  <sub>Built with obsession over details · © 2026 Mohammed Mahir</sub>
</div>
