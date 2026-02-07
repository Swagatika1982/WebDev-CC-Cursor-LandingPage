# WebDev-CC-Cursor-LandingPage
# Cursor Landing Page Clone (HTML + CSS)

This project is a **static recreation** of the Cursor marketing landing page layout using **only HTML + CSS** (no JS).  
It focuses on matching the **structure, spacing, dark theme, glow background, and section layout**.

---

## ✅ Sections Recreated

### 1) Global Background + Theme
- Dark theme base (`--bg`)
- Blurred glow blobs (3 background “blob” shapes)
- Bottom shade gradient overlay for depth

### 2) Header / Navbar
- Brand area (logo + “CURSOR” text)
- Navigation links (Product, Enterprise, Pricing, Resources)
- Action buttons (Sign in, Download)
- Sticky header with blur (`backdrop-filter`)

### 3) Hero Section
- Main hero headline text
- Primary CTA button (Download for Windows)
- Hero demo area:
  - **Background image** (`.hero-bg`)
  - **Solid black overlay card** on top (`.hero-card`)
  - Image placed inside the card

### 4) “Trusted by” Logos Strip
- Heading text
- 8 logo tiles in a grid layout (`.logos`, `.logoBox`)

### 5) Feature Sections (3 Rows)
- Alternating text + image layout (`.featureRow`)
- Title + description + link line
- Feature images (feature01/02/03)

### 6) Testimonials Grid
- 6 testimonial cards in a 3x2 grid (`.grid-container-test`)
- Quote text + avatar + name/title line

### 7) “Stay on the Frontier” Cards
- Section heading
- 3 column card-style blocks (text + small images)

### 8) Changelog Section
- Heading + 4 changelog cards (date + title)
- “See what’s new” link

### 9) Join Us + Highlights
- Join-us section with text + image
- “Recent Highlights” list content layout

### 10) Final CTA + Footer
- Final “Try it now” CTA
- Footer grid columns:
  - Product, Resources, Company, Legal, Connect
- Footer bottom bar (copyright + language)

---

## 🎨 Fonts Used

Your CSS uses the **system UI sans-serif stack** (fast + clean, similar modern SaaS styling):

```css
font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;

📁 Project Structure (Suggested)
Cursor-LP-SS/
├─ index.html
├─ src/
│  ├─ style.css
│  └─ images/
│     ├─ hero-pic-cursor.webp
│     ├─ heropic01.png
│     ├─ feature01.png
│     ├─ feature02.png
│     ├─ feature03.png
│     └─ ...
└─ README.md

▶️ How to Run

Since this is plain HTML/CSS:

Open index.html directly in the browser
OR

Use VS Code Live Server extension for best results.
