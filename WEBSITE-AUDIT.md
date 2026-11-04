# InventCare website audit — November 3, 2026

Scope: preserve existing branding, lead with finding personal injury doctors and attorneys, retain the supplied brief's medical-legal coordination services. External connections deferred by the owner.

## Completed

- Ten core pages: Home, Search, Join Our Network, Contact, About, Law Firms, Medical Providers, Urgent Care, TBI & Diagnostics, Coverage.
- Original colors, photography, typography and editorial layouts retained and extended.
- Founder, mission, values, provider placement, law-firm support, urgent care / EMC coordination, TBI and diagnostic pathways covered.
- Desktop Explore menu, scrollable mobile menu and footer links expose the additional pages.
- Audience-specific inquiry paths; law-firm inquiry selection carries into Contact.
- Interactive schematic map covers 50 states plus DC, with an accessible select alternative. Selection carries into Search. No unverified availability is claimed.
- Search filters and request fallback; no fabricated directory records.
- Click-to-call, email, Instagram and supplied business/intake hours.
- Form validation, labeled fields, keyboard focus, skip-to-content link and reduced-motion support.
- Email-draft status no longer claims a request was sent or a draft definitely opened.

## Verification

- Vite production build passes.
- All nine interior pages render in React; local image references and internal destination routes pass checks.
- Browser verified: mobile menu exposes all ten pages; mobile Law Firms layout; law-firm CTA prefills inquiry category; coverage selection prefills search location; schematic map renders at normal preview width.
- Earlier browser verification confirmed Search-to-Contact preference handoff.
- No email was sent during verification.

## Deferred connections and launch inputs

- CRM, actual form delivery, secure patient/case intake, automated routing and notifications.
- Verified provider/attorney directory and per-location availability data.
- Google Analytics, Meta Pixel, lead-source attribution and call tracking.
- Validate ownership and intended use of call.inventcares.com before linking/integration.
- Final domain/hosting setup, HTTPS and route fallback configuration. Current Vite preview supports direct page URLs; production host must support SPA fallback to index.html.
- Business address to be supplied; no address invented.
- Final state/city landing-page content and verified location claims can expand from the Coverage and service pages.
- QR codes need the final public domain before production print assets are generated.

Current forms open email drafts only. This is a local website build, not a connected intake or case-management system.
