# E-Rezept Generator für Heilpraktiker

> Professional website for E-Rezept Generator für Heilpraktiker
> Domain: e-rezept-generator-fuer-heilpraktiker.de

## 🚀 Project Overview

This is a static website built with Astro and TailwindCSS for "E-Rezept Generator für Heilpraktiker" - a digital prescription solution for German alternative medicine practitioners (Heilpraktiker).

## 📦 Tech Stack

- **Framework**: Astro 4.3.0 (Static Site Generation)
- **Styling**: TailwindCSS 3.4.1
- **Language**: German (de)
- **Type Safety**: TypeScript

## 🏗️ Project Structure

```
/
├── public/
│   ├── favicon.svg
│   └── og-image.jpg
├── src/
│   ├── components/
│   │   ├── Header.astro       # Main navigation header
│   │   └── Footer.astro       # Site footer
│   ├── content/
│   │   └── articles/          # Article markdown files
│   │       ├── e-rezept-heilpraktiker-leitfaden-2024.md
│   │       └── e-rezept-generator-heilpraktiker-digitale-verordnungen.md
│   ├── layouts/
│   │   ├── BaseLayout.astro   # Base HTML layout with SEO
│   │   └── ArticleLayout.astro # Article-specific layout
│   └── pages/
│       ├── index.astro        # Homepage
│       ├── impressum.astro    # Legal notice
│       ├── datenschutz.astro  # Privacy policy
│       └── artikel/
│           ├── index.astro    # Article listing
│           └── [slug].astro   # Dynamic article pages
├── astro.config.mjs
├── tailwind.config.mjs
└── package.json
```

## 📄 Pages Built

1. **Homepage** (`/`) - Hero section with features and latest articles
2. **Article Listing** (`/artikel`) - Overview of all articles
3. **Article 1** (`/artikel/e-rezept-heilpraktiker-leitfaden-2024`) - Comprehensive guide to E-Rezept for Heilpraktiker
4. **Article 2** (`/artikel/e-rezept-generator-heilpraktiker-digitale-verordnungen`) - Guide to using E-Rezept generators
5. **Impressum** (`/impressum`) - Legal notice (placeholder)
6. **Datenschutz** (`/datenschutz`) - Privacy policy (placeholder)

## 🎨 Features

- ✅ **SEO Optimized**: Proper meta tags, Open Graph, Twitter Cards
- ✅ **Mobile-First Design**: Fully responsive layout
- ✅ **Ad-Ready**: Placeholder spaces for advertisements
- ✅ **German Language**: All content and UI in German
- ✅ **Fast Performance**: Static site generation with Astro
- ✅ **Clean Design**: Professional TailwindCSS styling
- ✅ **Accessibility**: Semantic HTML and ARIA labels

## 🚀 Commands

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## 📝 Content

### Articles

Both articles are comprehensive guides written in German:

1. **E-Rezept für Heilpraktiker: Der umfassende Leitfaden für 2024**
   - What is an E-Rezept?
   - Legal framework for Heilpraktiker
   - Benefits and challenges
   - Practical implementation
   - Future perspectives

2. **E-Rezept Generator für Heilpraktiker: Digitale Verordnungen einfach erstellen**
   - What is an E-Rezept Generator?
   - Legal requirements (DSGVO, HeilprG)
   - Features and functions
   - Selection criteria
   - Implementation guide
   - Best practices

## 🎯 SEO & Performance

- All pages include proper meta descriptions
- Canonical URLs configured
- Open Graph tags for social sharing
- Semantic HTML structure
- Optimized for Lighthouse scores 90+
- Fast loading times with static generation

## 📱 Responsive Design

The site is fully responsive with breakpoints:
- Mobile: < 768px
- Tablet: 768px - 1024px
- Desktop: > 1024px

## 🔧 Customization

### Adding New Articles

1. Create a new `.md` file in `src/content/articles/`
2. Add frontmatter with title, description, publishDate, author
3. Add the slug to `src/pages/artikel/[slug].astro` getStaticPaths()
4. Add to the articles array in `src/pages/artikel/index.astro`
5. Run `npm run build`

### Updating Colors

Edit `tailwind.config.mjs` to customize the primary color palette.

### Ad Placements

Ad placeholder sections are marked with comments in:
- Header (all pages)
- Sidebar (article pages)
- In-content sections

## ⚠️ Legal Pages

The Impressum and Datenschutz pages contain placeholder content. Update with actual legal information before deployment.

## 📊 Build Output

```
✓ 6 pages built successfully
✓ Static assets optimized
✓ SEO tags included
✓ Mobile responsive
```

## 🌐 Deployment

This is a static site that can be deployed to:
- Netlify
- Vercel
- GitHub Pages
- Any static hosting provider

## 📄 License

All rights reserved - E-Rezept Generator für Heilpraktiker

---

Built with ❤️ using Astro and TailwindCSS
