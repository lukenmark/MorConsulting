# Mor Consulting Landing Page

## What This Project Is
Landing page for Mor Consulting (Marketing. Optimization. Revenue), owned by Luke.
Sells AI voice agent services to small business owners (automotive shops, salons).
Submitting the form triggers Samantha (AI voice agent) to call the prospect immediately.

- Live site: https://morconsulting.co
- GitHub: https://github.com/lukenmark/MorConsulting
- Deployed on: Vercel (auto-deploys on push to main)

## How to Deploy
git add . → git commit -m "message" → git push origin master:main
Vercel updates the live site within 60 seconds.

## Tech Stack
- Frontend: Single index.html file — all CSS and JS live in this one file. No framework.
- Hosting: Vercel
- Domain: Namecheap → pointing to Vercel
- CRM + Voice AI + Calendar + Forms: GoHighLevel (GHL)
- Version control: GitHub

## File Structure
Single file project — keep it this way:
- index.html (everything lives here)
- logo-variations.html

## Design System
- Background: #F5F2EE (warm off-white)
- Primary green: #3D6B4F
- Dark green: #2A4A2E
- Sage accent: #7A9E87
- Text: #1C1C1C (charcoal)
- Font: Inter (Google Fonts)

## Page Sections (top to bottom)
1. Sticky nav — MOR logo left, "Book a Call" button right
2. Hero — rotating Unsplash backgrounds, animated 7-bar waveform, headline + subheadline
3. GHL form embed — name + phone, off-white background
4. How It Works — 3 step cards
5. Who We Serve — sage green background, 4 industry cards
6. Footer — MOR logo, earth green border

## Key Copy
- Headline: "Never Miss a Call. Never Lose a Lead."
- Subheadline: "Our AI answers your phones 24/7, handles questions, and books appointments — while you focus on running your business."
- CTA Button: "Hear How It Sounds"

## GHL Integration
- Form ID: jGrxMvCh5QoVhZN1B1M9
- On submit: GHL triggers Samantha (Voice AI) to call the prospect instantly
- Samantha runs a 3-act sales script and books a 15 min discovery call with Luke
- Calendar: 15 Min Discovery Call (Google Meet)
- Confirmation SMS sent after booking

## Important Rules — Always Follow These
- NEVER add API keys to index.html
- NEVER replace the GHL form with a custom HTML form
- NEVER paste code directly into GHL — always push to GitHub
- ALWAYS keep the single file structure (no separate CSS or JS files)
- ALWAYS keep consent language below the form button

## Owner Info
- Owner: Luke
- Email: luke.morconsulting@gmail.com / luke@morconsulting.com
- GitHub: lukenmark
