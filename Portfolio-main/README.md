# Modern Personal Portfolio Website

A clean, responsive, and high-performance personal portfolio website built with pure semantic HTML5, modern Vanilla CSS, and lightweight JavaScript. Designed for developers, software engineers, and designers.

Ready to deploy directly to **Vercel** with zero build configuration!

---

## 🚀 Features

- **Header / Navigation Bar**:
  - Sticky glassmorphic design with active section highlighting on scroll
  - Mobile responsive slide-down menu with animated hamburger toggle
  - Dark / Light mode switcher with `localStorage` persistence (defaults to sleek dark mode)
- **Hero Section**:
  - Available status indicator badge with pulse animation
  - Name, role title, and introduction
  - Quick action buttons ("View Projects" and "Contact Me") with smooth scroll
  - Key statistics counter banner (Years of Experience, Projects, Satisfaction)
- **About Section**:
  - Clean personal bio card with avatar badge and downloadable resume button
  - Core philosophy cards highlighting Clean Architecture, Modern Frontend, and Fast Delivery
- **Skills Section**:
  - Categorized skill cards (Frontend, Backend & APIs, Databases, DevOps & Tools)
  - Interactive skill pills with subtle hover scaling
- **Projects Section**:
  - 3 featured project cards with realistic browser mockup headers
  - Tag pills for technologies used
  - Direct GitHub ("Code") and "Live Demo" buttons
- **Contact Section**:
  - One-click copy email button with animated toast notification
  - Direct "Send Email" mailto button
  - Social media link cards for GitHub, LinkedIn, and Twitter / X
- **Footer**:
  - Automatic copyright year
  - "Back to Top" smooth scroll button
- **Production & Performance**:
  - Zero heavy framework or runtime dependencies
  - Inline SVGs (sharp on all DPI screens, zero network requests)
  - Google Fonts (`Inter` & `Outfit`) with preconnect
  - `vercel.json` preconfigured with HTTP security headers and immutable asset caching

---

## 🛠️ Personalization Checklist

Search and replace the placeholders across [index.html](file:///Users/sumansaurav/Desktop/aditya/index.html):

| Placeholder | Description | Where to find |
|---|---|---|
| `[YOUR NAME]` | Your full name | `<title>`, navbar logo, hero header, about section, footer |
| `[YOUR ROLE]` | Your title (e.g., *Full Stack Developer*, *Frontend Engineer*) | `<title>`, hero subtitle, about header |
| `[Your Location / Remote]` | Your city or remote availability | About section bio text |
| `your.email@example.com` | Your contact email | Contact email span and `mailto:` link |
| `https://github.com/yourusername` | Your GitHub profile link | Contact section & project links |
| `https://linkedin.com/in/yourusername` | Your LinkedIn profile link | Contact section |
| `https://twitter.com/yourusername` | Your Twitter / X profile link | Contact section |
| Projects & Demos | Replace TaskFlow, CryptoPulse, and Aura with your own work | `<article class="project-card">` blocks |

---

## 💻 Local Preview

You can open `index.html` directly in any web browser, or run a local static server:

### Option A: Using Python (Pre-installed on macOS/Linux)
```bash
python3 -m http.server 3000
```
Then visit `http://localhost:3000`.

### Option B: Using Node `npx serve`
```bash
npx -y serve .
```

---

## 🌐 Deploying to Vercel

### Method 1: Using the Vercel Dashboard (Easiest)
1. Push this folder to a GitHub repository:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio commit"
   git branch -M main
   # Add your remote repo and push:
   # git remote add origin https://github.com/<your-username>/<your-repo-name>.git
   # git push -u origin main
   ```
2. Go to [vercel.com/new](https://vercel.com/new).
3. Import your GitHub repository.
4. Leave all build settings as default (Framework Preset: **Other**).
5. Click **Deploy**. Your site will be live within seconds!

### Method 2: Using the Vercel CLI
```bash
npx vercel
```
Follow the interactive CLI prompts to deploy directly.
