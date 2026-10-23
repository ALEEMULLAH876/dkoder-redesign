# DKoder — Make Your Next Move

An original, responsive frontend redesign concept inspired by the DKoder learning and hackathon platform. Built for a frontend design challenge using React, Vite, modern CSS and Lucide icons.

> **Concept disclaimer:** This is an independent design concept, not the official DKoder website. It does not connect to DKoder's private systems, authentication, courses, events, or APIs. The name is used to identify the redesign challenge; this project is not endorsed by DKoder.

## Design direction

- **Palette:** warm paper `#FBF8EF`, charcoal `#20211D`, purposeful DKoder-inspired yellow `#F8C934`, with muted lime, peach and blue accents.
- **Visual language:** editorial typography, bold grid, outlined components, tactile offset shadows, hand-made-looking geometric illustrations and restrained colour.
- **Experience:** mobile-first navigation, searchable learning paths, expandable path details, event information interactions, FAQ accordion, and a local-only email form demo.
- **Accessibility:** semantic sections, visible keyboard focus, labels, accessible button names, status messages, and reduced-motion support.

## Run locally

Requirements: Node.js 18+ and npm.

```bash
npm install
npm run dev
```

Open the local URL shown by Vite.

## Production build

```bash
npm run build
npm run preview
```

Vite outputs the deployable site into `dist/`.

## Deploy

### Vercel
1. Push this folder to a **public GitHub repository**.
2. Import the repository in Vercel.
3. Framework preset: **Vite**. Build command: `npm run build`. Output directory: `dist`.
4. Deploy and open the generated URL on both mobile and desktop before submitting.

### Netlify
Build command: `npm run build`; publish directory: `dist`.

## Project structure

```text
dkoder-redesign/
├── index.html
├── package.json
├── README.md
├── .gitignore
├── public/
│   └── favicon.svg
└── src/
    ├── main.jsx
    └── styles.css
```

## Before submitting

- Run `npm install` and `npm run build` and fix any errors.
- Test mobile, tablet and desktop layouts.
- Confirm all links and interactive states behave as intended.
- Include the public GitHub repository URL and live deployment URL in the competition form.
- Do not claim that the demo has a real backend, real users, live courses or working account authentication.

## Credits

React, Vite and Lucide React are used as development libraries. Google Fonts are loaded from Google Fonts when online. No external image assets are required; the hero and event artwork are CSS-based.
