# ✦ Bakrid Festival Surprise Website ✦
## Ultra-Premium Cinematic Experience

---

## 📂 Project Structure

```
bakrid-festival/
└── index.html          ← Complete self-contained website (all in one file)
```

This is a **single-file architecture** — all HTML, CSS, JavaScript, Three.js, GSAP, and animations are bundled into one `index.html`. No build step required.

---

## ✨ What's Inside

### 7 Cinematic Sections
| # | Section | Features |
|---|---------|----------|
| 1 | **Hero** | Three.js star field, crescent rings, mouse-parallax, GSAP reveal |
| 2 | **Festival Wishes** | 6 glassmorphism cards with 3D tilt + hover glow |
| 3 | **Sacred Story** | SVG mosque illustration, parallax scroll, animated quote |
| 4 | **Memories Gallery** | Masonry grid, hover zoom, lightbox popup, cinematic overlays |
| 5 | **Countdown** | Live timer since Eid, animated canvas starfield |
| 6 | **Surprise Message** | Floating hearts/stars, ambient orbs, text reveal |
| 7 | **Gift Reveal** | Animated gift box, confetti explosion, personal message |

### Advanced Features Included
- ✅ Three.js 3D starfield + floating particles (Hero)
- ✅ Custom gold cursor + magnetic follower
- ✅ Scroll progress indicator (gold gradient bar)
- ✅ Lenis ultra-smooth scrolling
- ✅ GSAP ScrollTrigger animations on every section
- ✅ 3D card tilt effect (mouse tracking)
- ✅ Magnetic button effect
- ✅ Canvas particle systems (3 sections)
- ✅ Confetti explosion on gift reveal
- ✅ Gallery lightbox popup
- ✅ Live countdown/count-up timer
- ✅ Floating hearts animation (Surprise section)
- ✅ SVG mosque illustration (hand-crafted)
- ✅ SVG decorative dividers between sections
- ✅ Audio toggle control
- ✅ Cinematic loader with animated progress
- ✅ Responsive mobile navigation
- ✅ Mouse-follow radial light in Hero
- ✅ Glassmorphism cards
- ✅ Animated parallax scrolling
- ✅ Gradient glow text effects
- ✅ Full mobile responsiveness

---

## 🚀 Setup Guide

### Option 1 — Open Directly (Fastest)
```bash
# Just double-click index.html in your file browser
# Or drag it into Chrome/Firefox/Edge
```
> ⚠️ Some browsers block audio autoplay locally. That's normal — click the 🔇 button to play music.

### Option 2 — Local Server (Recommended for best experience)
```bash
# Using Python (built into most systems)
cd bakrid-festival
python3 -m http.server 8080
# Then open: http://localhost:8080

# Using Node.js
npx serve .
# Then open: http://localhost:3000

# Using VS Code
# Install "Live Server" extension → right-click index.html → "Open with Live Server"
```

---

## 🌐 Deployment Guide

### GitHub Pages (Free)

1. Create a new repository on GitHub (e.g. `eid-surprise`)
2. Upload `index.html` to the repo root
3. Go to **Settings → Pages → Branch: main → / (root) → Save**
4. Your site is live at: `https://yourusername.github.io/eid-surprise`

```bash
# Via command line
git init
git add index.html
git commit -m "✨ Eid Mubarak surprise website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/eid-surprise.git
git push -u origin main
```

### Netlify (Easiest, with drag & drop)

1. Go to [netlify.com](https://netlify.com) → Sign up free
2. Drag the entire `bakrid-festival` folder onto the Netlify dashboard
3. Done! You get a live URL instantly like: `https://happy-eid-xyz.netlify.app`
4. Optionally set a custom subdomain in **Site settings → Domain management**

```bash
# Via Netlify CLI
npm install -g netlify-cli
cd bakrid-festival
netlify deploy --prod --dir .
```

### Vercel (Fastest CDN)

```bash
npm install -g vercel
cd bakrid-festival
vercel --prod
# Follow prompts → live in seconds
```

Or visit [vercel.com](https://vercel.com) → New Project → Import from GitHub

---

## 🎨 Customization Guide

### Change the Recipient's Name
Search for `"My Dear Friend"` or `"my beautiful friend"` in `index.html` and replace with the actual name.

### Change the Personal Message
Find the `#gift` section and edit the `gift-message-text` paragraph.

### Change the Surprise Message
Find `id="surprise-text"` and edit the quoted text.

### Change Colors (CSS Variables)
At the top of `<style>`, edit:
```css
--gold: #C9A84C;         /* Main gold */
--gold-light: #F0D080;   /* Lighter gold */
--gold-bright: #FFE87C;  /* Highlight gold */
```

### Change Eid Date
In the JavaScript section, find:
```javascript
var EID_DATE = new Date(2026, 4, 27, 0, 0, 0);
```
Update to the correct date for your year.

### Add Background Music
Replace the audio source URL or add a local file:
```html
<audio id="bg-audio" loop crossorigin="anonymous">
  <source src="your-music.mp3" type="audio/mpeg">
</audio>
```
Royalty-free Eid/Islamic nasheeds available at:
- pixabay.com/music (search "nasheed" or "eid")
- freesound.org
- incompetech.com

### Add Real Photos to Gallery
Replace the SVG gallery backgrounds with real images:
```html
<div class="gallery-bg" style="background-image: url('your-photo.jpg'); background-size: cover;">
```

---

## 📱 Mobile Experience

The site is fully responsive:
- Hamburger menu on mobile (≤768px)
- Custom cursor hidden on touch devices
- Stacked layouts for small screens
- Touch-friendly interactions
- Optimized Three.js (pixel ratio capped at 2×)

---

## 🛠 Tech Stack

| Technology | Purpose |
|-----------|---------|
| HTML5 | Structure |
| CSS3 | Styling, animations, glassmorphism |
| Three.js r128 | 3D starfield, particle systems |
| GSAP 3.12 | Timeline & scroll animations |
| ScrollTrigger | Scroll-based reveals |
| Lenis 1.0 | Buttery smooth scrolling |
| Google Fonts | Cinzel Decorative + Cormorant Garamond + Josefin Sans |

All libraries loaded from CDN — no npm install needed.

---

## 💌 Share With Your Friend

Once deployed, share the link as:
- A WhatsApp/Telegram message: *"I made something special for you this Eid ☾ [link]"*
- An Instagram story with the link in bio
- A simple email with the URL

---

*بارك الله فيكم — May Allah bless you always ✦*
