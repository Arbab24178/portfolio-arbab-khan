# Arbab Khan - AI Expert Portfolio

## Project Overview

A modern, responsive portfolio website built with **Next.js 15**, **TypeScript**, **Tailwind CSS**, and **Framer Motion** for Arbab Khan - an AI Expert and Software Engineer.

### Features

- **Modern UI/UX**: Dark theme with gradient accents, glass morphism effects, and smooth animations
- **Responsive Design**: Fully responsive across all device sizes
- **Interactive Animations**: Powered by Framer Motion for engaging user experience
- **SEO Optimized**: Meta tags and Open Graph support for better discoverability

### Tech Stack

| Technology | Purpose |
|------------|---------|
| Next.js 15 | React framework with App Router |
| TypeScript | Type-safe JavaScript |
| Tailwind CSS | Utility-first styling |
| Framer Motion | Animation library |
| PostCSS | CSS processing |

## Project Structure

```
portfolio/
├── src/
│   ├── app/
│   │   ├── globals.css      # Global styles and Tailwind setup
│   │   ├── layout.tsx       # Root layout with metadata
│   │   └── page.tsx         # Main homepage component
│   └── components/
│       ├── Navbar.tsx       # Navigation with mobile menu
│       ├── Hero.tsx         # Hero section with animated elements
│       ├── About.tsx        # About section with education info
│       ├── Skills.tsx       # Skills with progress bars
│       ├── Experience.tsx   # Work experience timeline
│       ├── Projects.tsx     # Featured projects showcase
│       ├── Contact.tsx      # Contact form and info
│       └── Footer.tsx       # Footer with social links
├── public/                  # Static assets
├── package.json
├── tsconfig.json
├── tailwind.config.js
├── postcss.config.js
└── next.config.js
```

## Building and Running

### Development

```bash
npm run dev
```

Opens the development server at `http://localhost:3000`

### Production Build

```bash
npm run build
npm start
```

### Linting

```bash
npm run lint
```

## Key Sections

1. **Hero**: Animated introduction with floating elements and social links
2. **About**: Education background and personal introduction
3. **Skills**: Categorized skills with animated progress bars
4. **Experience**: Timeline of work experience and education
5. **Projects**: Featured projects with tags and descriptions
6. **Contact**: Contact form and social media links

## Customization

### Update Personal Information

Edit the component files in `src/components/` to update:
- Contact information in `Contact.tsx`
- Work experience in `Experience.tsx`
- Projects in `Projects.tsx`
- Skills in `Skills.tsx`

### Styling

Modify `tailwind.config.js` to change:
- Color scheme (primary, secondary, dark, etc.)
- Animations
- Font families

## Deployment

The portfolio can be deployed to:
- **Vercel** (recommended for Next.js)
- **Netlify**
- **GitHub Pages**
- Any Node.js hosting platform

## Contact Information

- **Email**: arbabkhan4165@gmail.com
- **Location**: Karachi, Pakistan
- **GitHub**: github.com/arbabkhan
- **LinkedIn**: linkedin.com/in/arbabkhan
