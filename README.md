# Equal Symbol (=) - The Most Balanced Website

An exaggerated, slightly obsessive, but entirely serious deep-dive into the equal symbol. Built with Astro, Tailwind CSS 5, and way too much enthusiasm.

## 🚀 Features

- **Exhaustive Symbol Variations**: 16+ equal symbol variants with copy-to-clipboard functionality
- **Comprehensive Unicode Reference**: Complete tables with Unicode, HTML codes, and Alt codes
- **Rich Historical Context**: From Robert Recorde's 1557 invention to modern usage
- **Philosophical Exploration**: Mathematical truth, geometric perfection, and cultural significance
- **Cross-Disciplinary Applications**: Mathematics, Physics, Chemistry, Computer Science, and more
- **Interactive FAQ**: Everything you never knew you wanted to know about "="
- **Modern Design**: Purple-pink gradients, backdrop blur, and smooth animations
- **Static Site**: Blazing fast, compiles to pure HTML/CSS/JS

## 🛠️ Tech Stack

- **Astro 5.14.1**: Lightweight static site generator
- **Tailwind CSS 5**: Modern utility-first CSS framework
- **pnpm**: Fast, disk space efficient package manager

## 📦 Getting Started

### Prerequisites

- Node.js 18+
- pnpm (install with `npm install -g pnpm`)

### Installation

```bash
# Install dependencies
pnpm install

# Start development server
pnpm dev

# Build for production
pnpm build

# Preview production build
pnpm preview
```

## 🌐 Development

The dev server will start at `http://localhost:4321/`

### Project Structure

```
equalsymbol/
├── src/
│   ├── pages/
│   │   └── index.astro       # Main page
│   └── styles/
│       └── global.css         # Global styles with Tailwind
├── public/                    # Static assets
├── astro.config.mjs          # Astro configuration
├── package.json
└── README.md
```

## 🎨 Design Philosophy

This site takes the concept of "symbol reference pages" and cranks it to 11. It's:
- **Over-the-top** but academically accurate
- **Visually stunning** with gradients and animations
- **Comprehensive** with 10+ major sections
- **Interactive** with copy-to-clipboard for all symbols
- **Accessible** with semantic HTML and ARIA labels

## 📚 Content Sections

1. **Hero** - Giant animated equal symbol
2. **Stats** - Ridiculous but true statistics
3. **Introduction** - What is the equal symbol?
4. **Symbol Variations** - 16 clickable symbol cards
5. **Unicode Reference** - Complete technical table
6. **Historical Deep Dive** - Timeline from 1557 to present
7. **Philosophy** - Mathematical, geometric, cultural, computational
8. **Usage Guide** - Desktop, mobile, programming
9. **Applications** - 6 disciplines with detailed use cases
10. **FAQ** - 6 frequently asked questions
11. **Fun Facts** - Etymology, Einstein, history

## 🚢 Deployment

### GitHub Pages with Custom Domain (Automatic CI/CD)

This project is configured to automatically deploy to GitHub Pages with the custom domain **equalsymbol.com** when you push to the `master` branch.

**Setup Instructions:**

1. **Configure DNS for your domain:**
   - Add an `A` record pointing to GitHub Pages IPs:
     - `185.199.108.153`
     - `185.199.109.153`
     - `185.199.110.153`
     - `185.199.111.153`
   - Or add a `CNAME` record pointing to `paillat-dev.github.io`

2. **Push your code to GitHub:**
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin master
   ```

3. **Enable GitHub Pages in your repository:**
   - Go to **Settings** → **Pages**
   - Under **Source**, select **GitHub Actions**
   - Under **Custom domain**, enter `equalsymbol.com`
   - Check **Enforce HTTPS** (recommended)

4. **Automatic deployment:**
   - The site will automatically build and deploy on every push to `master`
   - Build workflow: `.github/workflows/deploy.yml`
   - Live URL: **https://equalsymbol.com**

**CI/CD Workflow includes:**
- ✅ Automatic builds on push to master
- ✅ pnpm caching for fast builds
- ✅ Astro static site generation
- ✅ Automatic deployment to GitHub Pages
- ✅ Custom domain configuration (CNAME file in `public/`)

### Manual Build

```bash
pnpm build
# Output in dist/
```

### Other Deployment Options

Deploy to:
- Vercel
- Netlify
- Cloudflare Pages
- Any static host

## 📄 License

This is a portfolio/demonstration project. Use freely with attribution.

## 🙌 Acknowledgments

Inspired by delta-symbol.com, infinity-symbol.com, and the entire Greek symbols family of websites.

Special thanks to Robert Recorde (1510-1558) for inventing the equal symbol in 1557.

## 👨‍💻 Credits

Created with Claude Code (Claude Sonnet 4.5) by Anthropic.

---

**Built with passion, precision, and perhaps too much cyber-coffee.**
