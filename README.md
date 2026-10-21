# Ariyan Ahmed — Personal Portfolio

A dark, futuristic-editorial portfolio built with Next.js App Router, TypeScript, Framer Motion and Lucide icons.

## Run locally

Requirements: Node.js 18.17+ and npm.

```bash
npm install
npm run dev
```

Open http://localhost:3000.

For a production build:

```bash
npm run build
npm start
```

## What's included

- Responsive navigation and mobile menu
- Animated hero with abstract CSS artwork
- Scroll progress, reveal animations and marquee ticker
- Filterable project gallery
- Expandable case-study modal for every project
- Technical skills grouped by discipline
- Digital products, hardware and experiments section
- About and contact sections
- Reduced-motion support
- Basic metadata and Open Graph details

## Personalise before publishing

Some project information is based on details previously supplied, while outcomes, links and media that have not been verified are clearly described as items to add.

1. Update project details and URLs in `app/page.tsx`.
2. Replace the CSS-generated project visuals with real screenshots, gameplay footage, product UI or hardware photographs.
3. Replace the generic LinkedIn URL with your profile URL.
4. Verify the contact email and add any preferred social links.
5. Add a CV PDF in `public/` and a download link if you want a CV CTA.
6. Update the domain in `app/layout.tsx` if you publish somewhere other than `ariyanahmed.com`.

The portfolio currently uses custom CSS illustrations rather than invented screenshots of your actual work. The project case studies explicitly flag where live links, measured outcomes and final captures need to be supplied.

## Suggested deployment

Deploy to Vercel or another host that supports Next.js. Set up a custom domain and add analytics only after configuring the appropriate privacy and consent requirements.
