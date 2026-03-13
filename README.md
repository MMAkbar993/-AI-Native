# AI-Native Developer / Content Architect Landing Page

This is a single-page, AI-native portfolio / offer page built from the prompt you provided. It is designed to showcase an **AI-Native Developer & Content Architect** specializing in **Whop affiliate landing pages**, "vibe coding," and multi-repo GitHub workflows.

The stack is intentionally simple: **static HTML + Tailwind via CDN**, so you can drop it into any GitHub Pages or Vercel setup.

## Features

- **Mobile-first layout** optimized for the TikTok-to-checkout flow.
- **Hero + Mission + Capabilities + Workflow + Contact** sections.
- Tailwind-based **dark UI** with gradient accents and card-style sections.
- Placeholder “social proof” / short-form video grid that you can wire up to actual TikTok, Reels, or Shorts embeds.
- Simple contact form (front-end only by default) ready to integrate with your preferred backend or form tool.

## Getting Started

1. Open `index.html` in your browser (double-click or drag into a browser window).
2. Customize the text content to match your name/brand:
   - Hero headline and subcopy
   - Mission, capabilities, workflow steps
   - Contact copy and placeholders for URLs (e.g., `joinbeatthebooks.com`)
3. Replace the placeholder "social proof" blocks with real embeds:
   - TikTok, YouTube Shorts, and Instagram Reels iframe/embed codes.

## Deploying

### GitHub Pages

1. Create a new GitHub repository.
2. Add `index.html` and `README.md`.
3. Push to GitHub.
4. Enable GitHub Pages in the repository settings (deploy from `main` or `docs`).

### Vercel

1. Create a new Vercel project and connect it to your repository.
2. Vercel will detect it as a static site and deploy automatically.

## Customization Ideas

- Split this page into a template and generate **30–40 variants** using CSV/JSON + a small script.
- Wire the contact form to:
  - A serverless function (e.g., Vercel Functions)
  - A form backend service (e.g., Formspree, Basin) or your own API.
- Add analytics (Plausible, Umami, GA4) to track click-throughs to Whop affiliate links.

You can now use this as the base "vibe" for your AI-native Whop affiliate landing page ecosystem.

