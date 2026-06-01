# whoami - Rob Aitchison's Portfolio

A modern portfolio website built with [Astro](https://astro.build) and [Tailwind CSS](https://tailwindcss.com) to showcase software projects, design work, artwork, and photography.

## 🚀 Quick Start

### Development

```bash
npm install
npm run dev
```

Visit `http://localhost:3000/whoami` in your browser.

### Build

```bash
npm run build
```

The built site will be in the `dist/` directory.

### Preview

```bash
npm run preview
```

## 📁 Project Structure

```
src/
├── components/       # Reusable components
├── layouts/         # Page layouts
├── pages/           # Route pages
│   ├── index.astro         # Home page
│   ├── about.astro         # About page
│   ├── portfolio.astro     # Portfolio gallery
│   └── contact.astro       # Contact page
├── styles/          # Global styles
└── content/         # Content collections (ready for expansion)
```

## 📄 Pages

- **Home** - Hero section with intro and call-to-action
- **Portfolio** - Gallery showcase with category filtering
- **About** - Bio, skills, and social links
- **Contact** - Contact form and contact information

## 🎨 Customization

### Colors & Styling

Edit `src/styles/globals.css` for color customization and `tailwind.config.mjs` for extended theme configuration.

### Portfolio Items

Update the `portfolioItems` array in `src/pages/portfolio.astro` to add your projects, artwork, and photos. Categories available:
- `software` - Software projects
- `design` - Design work
- `art` - Artwork
- `photography` - Photography

### Content Collection

Ready to add a content collection for blog posts or detailed project pages. Create collections in `src/content/` and use Astro's collection APIs.

## 🚀 Deployment

### GitHub Pages

This project is configured for automatic deployment to GitHub Pages via GitHub Actions.

**Setup:**
1. Ensure repository is public or GitHub Pages is enabled
2. Push to `main` branch
3. GitHub Actions will automatically build and deploy

**Configuration:**
- Site: `https://rob-raitch.github.io`
- Base: `/whoami`

To deploy to a different location, update `astro.config.mjs`:
```javascript
site: 'https://your-domain.com',
base: '/path',
```

## 📦 Technologies

- **Astro 6** - Static site generation
- **TypeScript** - Type safety
- **Tailwind CSS 3** - Utility-first CSS
- **GitHub Actions** - CI/CD deployment

## 📝 Background

This portfolio site was created to support an artist residency application. It showcases work across multiple disciplines: software development, design, art, and photography.

For more about me, visit my [LinkedIn profile](https://www.linkedin.com/in/raitch).

## 📄 License

Licensed under the ISC License.
