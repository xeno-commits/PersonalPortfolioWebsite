# Dev Log – Personal Portfolio Website

## 2026-02-18
- Initialized portfolio project from scratch in VS Code
- Structured base layout using semantic HTML sections (Hero, Projects, Experience, Contact)
- Built responsive layout using Flexbox and custom CSS
- Designed reusable button styles and card components
- Implemented navigation bar with mobile hamburger toggle
- Added placeholder project cards and experience grid
- Structured CSS with breakpoints for mobile responsiveness
- Tested layout scaling across desktop and mobile viewports
- Pushed initial static build to GitHub repository

## 2026-02-20
- Converted static UI buttons from <div> to semantic <a> tags
- Wired up external links with proper target and rel attributes
- Implemented secure contact form using Formspree
- Added required name, email, and message fields
- Preserved original styling while fixing anchor color inheritance
- Created feature branch `feature/contact-and-links`
- Merged updates into `main`
- Resolved remote push rejection using `git pull --rebase origin main`
- Learned proper semantic HTML usage and Git branch workflow discipline

## 2026-02-22 v1.0
- Refined contact form layout and icon alignment
- Fixed mobile layout for project cards and buttons
- Adjusted spacing and typography on small screens
- Configured GitHub Pages deployment from `main`
- Connected custom domain `gregory-dean.com` via Cloudflare
- Verified HTTPS and automatic deploys on push
- Updated experience section to reflect real roles and lab work
- Finalized README and repo documentation
  
## 2026-02-23 v1.2
- Optimized site for improved Lighthouse performance (mobile audit)
- Implemented lazy loading on non-critical images (`loading="lazy"`, `decoding="async"`)
- Refined alt text for improved accessibility and semantic clarity
- Added `aria-hidden="true"` to decorative icons to reduce screen reader noise
- Replaced inline `onclick` handlers with `addEventListener` and null checks
- Eliminated console warnings and verified clean production runtime
- Standardized secure external linking with `rel="noopener noreferrer"`
- Updated UI labels ("Download CV" → "Download Resume")
- Improved meta description for stronger SEO alignment
- Re-tested production domain on GitHub Pages
- Achieved Lighthouse scores: 94 Performance / 98 Accessibility / 100 Best Practices / 100 SEO
- Committed and deployed performance-focused iteration to `main`
