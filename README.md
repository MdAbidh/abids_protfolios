# Abid Hossain — Personal Portfolio

A premium, fully responsive personal portfolio built with pure HTML, CSS, and minimal Vanilla JavaScript. No frameworks. No build steps. Ready for GitHub Pages.

## 🚀 Live Deployment

Deploy instantly to GitHub Pages — no build process required.

## 📁 Project Structure

```
abid-portfolio/
├── index.html          ← Main HTML file
├── css/
│   └── style.css       ← All styles (design system, components, responsive)
├── assets/
│   ├── images/
│   │   └── profile.jpg ← Add your profile photo here
│   ├── icons/          ← Optional custom SVG icons
│   └── animations/     ← Optional Lottie JSON files
└── README.md
```

## 🖼️ Adding Your Profile Photo

1. Place your photo as `assets/images/profile.jpg`
2. Recommended: **500×500px** square, JPG or PNG
3. The image auto-crops to a circle with a green ring border

## 🎨 Design System

- **Fonts:** Syne (headings) + DM Sans (body)
- **Colors:** White base + Premium Green (`#22c55e`)
- **Effects:** Glassmorphism cards, gradient accents, subtle animations
- **Icons:** Inline SVG (Lucide-style) + DevIcons CDN

## 📬 Contact Form Setup

The form uses [FormSubmit](https://formsubmit.co/) — no backend needed:

1. Replace `abid@example.com` in the form `action` with your real email
2. On first submission, FormSubmit sends a confirmation email
3. Confirm and it works forever — free

## 🌐 GitHub Pages Deployment

```bash
# 1. Create a GitHub repo named: yourusername.github.io
# 2. Push all files to the main branch
git init
git add .
git commit -m "Launch portfolio"
git remote add origin https://github.com/yourusername/yourusername.github.io.git
git push -u origin main
# 3. Go to Settings → Pages → Deploy from main branch
```

## ✏️ Customization

All colors are CSS variables in `:root` inside `style.css`. Change `--green-500` to any color to re-theme the entire site.

To add real project screenshots, place images in `assets/images/` and replace the `.project-placeholder` divs with `<img>` tags.

## 📄 License

MIT — free to use and customize.

---

Built with ❤️ by Md. Abid Hossain | Dhaka, Bangladesh
