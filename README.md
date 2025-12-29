# Snehtiger Patel — Portfolio (Astro + Tailwind starter)

This is a minimal Astro starter tailored for a personal portfolio. It includes pages: Home, About, Projects, Blog, Contact and a sample resume link.

Prerequisites
- Node.js 18+ (recommended)
- Git

Local development
1. Install dependencies
   npm install

2. Start dev server
   npm run dev
   Open http://localhost:3000

Build
- npm run build
- npm run preview

Customizations
- Replace copy (name, bio, links) in src/pages/*.astro and src/components/Layout.astro
- Add resume.pdf to /public/resume.pdf
- Update social links in src/components/Layout.astro footer
- Replace Formspree action in src/pages/contact.astro with your endpoint

Deploy to Vercel (recommended)
1. Push this project to GitHub
2. Create a new project in Vercel and import the GitHub repo
3. Vercel detects Astro automatically; default build command `npm run build` and output dir is handled by Astro
4. Add custom domain in Vercel settings and point DNS

Tips
- Add metadata and Open Graph images for better link previews.
- Use GitHub Pages or Netlify if you prefer — Vercel provides the easiest continuous deploy experience.
- If you want, I can push this into a repo for you and connect Vercel automatically.
