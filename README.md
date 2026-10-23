# Assignment-02 – Sippline Landing Page (CSS `clip-path`)

A landing page for **Sippline drinking shields – the "Glass ka Mask"**, recreated from the TuteDude CSS assignment design using the CSS `clip-path` property.

## 🔗 Live Demo

**Deploy link:** https://pranavpatkari.github.io/Assignment-02/

## 📁 Project Structure

```
Assignment-02/
├── index.html
├── style.css
├── images/
│   └── glass-mask.svg
└── README.md
```

## ✂️ Where `clip-path` is used

| Element | `clip-path` | Purpose |
|---|---|---|
| `.diamond-frame` | `polygon(50% 0, 100% 50%, 50% 100%, 0 50%)` | White diamond frame, partly running off the right edge |
| `.diamond-gap` | same diamond polygon | Thin tinted ring between frame and photo |
| `.diamond-img` | same diamond polygon | Cuts the product image into a diamond (morphs on hover) |
| `.corner-top` | `polygon(100% 0, 100% 100%, 0 0)` | Orange triangle, top-right corner |
| `.corner-bottom` | `polygon(100% 0, 100% 100%, 0 100%)` | Orange triangle, bottom-right corner |
| `.shape-1`, `.shape-3` | `inset(0 round 120px)` | Faint rounded blocks in the background |
| `.shape-2` | `polygon(0 55%, 70% 30%, 85% 100%, 0 100%)` | Faint slanted band behind the text |

The diamond polygon is stored once as a CSS variable (`--diamond`) and reused.

## ✅ Features

- Orange gradient hero with navbar (Shop, About, Blogs, Contact) and **Buy Now** button
- Heading, description and **Buy the Glass Mask!** call-to-action
- Responsive: on tablets/phones the diamond moves below the text
- Montserrat font from Google Fonts

## ▶️ Run Locally

Open `index.html` in a browser, or:

```bash
python3 -m http.server 8000
```

## 🚀 Deploy (GitHub Pages)

Settings → Pages → *Deploy from a branch* → `main` / `(root)` → Save.

## 👤 Author

**Pranav Patkari** – [GitHub](https://github.com/pranavpatkari)
