# Alvarado / Villa Handyman Services LLC — spec-site preview

- **Suggested slug:** `alvaradohandyman`
- **Target host (not live, do not claim it is):** alvaradohandyman.capitalreconsulting.com
- **Current public site:** https://lalvaradohandyman.wixsite.com/website
- **Site path:** `/workspace/previews/alvaradohandyman/index.html`
- **One-line note (Outreach):** Replaced the default Wix “website” subdomain — smashed headline “Handyman ServiceAurora, Co” and Start Now chrome — with an Aurora porch-note site for Luis: per-the-job pricing, the published service list, mailto lalvaradohandyman@gmail.com (no phone printed).

This folder is a static preview only. Do not deploy. Do not treat the target host as live.

## What changed vs their current site

Stripped the Wix “This site was designed with the .com website builder / Start Now” chrome and the heading smash “Handyman ServiceAurora, Co.” Rebuilt a mobile-first four-page neighborhood shop as a porch note: cedar header, sage fence accent, mailbox-rust email buttons, Fraunces + Outfit, a sticky email dock on phones, and one compressed photo from their live page.

## Facts used (with sources)

| Fact | Source |
| --- | --- |
| Brand **Alvarado / Villa Handyman Services LLC** | Live page title |
| Heading smash **Alvarado/ Villa Handyman ServiceAurora, Co** — cleaned in the H1 to **Handyman service, Aurora, CO** | Homepage H1 |
| **My name is Luis** and in **June of 2020** my wife and I opened up our neighborhood Handyman Service company due to the pandemic | Homepage body |
| **I enjoy helping my neighbors by providing high utility workmanship.** | Homepage body |
| **NO hourly min required we charge per the job not by the hour** | Homepage body |
| Services: ceramic tile repair; countertops install / take down / repair; curtain hanging; door installation & repair; dryer vent cleaning & install; drywall install & repairs; fan installation; flooring installation & repairs; general maintenance; gutter cleaning and repairs; lockset adjustments / install; molding install; paint removal; painting; sealing driveways; shelving; staining furniture; swapping a toilet | Homepage “Services provided” |
| Small repairs: decks, fence fixing / locks, lawn-care, small leaks | Homepage “Small repairs on the following” |
| **“And thing else msg. me, I love new projects and always up for a challenge.”** — cleaned in running copy; original quoted | Homepage close |
| Email **lalvaradohandyman@gmail.com** (visible mailto) | Homepage |
| City **Aurora, CO** | Homepage heading |

## Facts deliberately omitted

- **Phone** — none printed on the live page. A `businessPhone` value exists only in hidden Wix site JSON. Preview does not invent or display a number. Mailto only.
- **Last name** — live page prints **Luis** only. Brand is Alvarado / Villa; owner is first name only.
- **Street address** — not on the live page.
- **Hours, reviews, license/insurance, extra cities** — not printed.
- **LinkedIn / Nextdoor extras** (TV mounting, pressure washing, extra service cities, a call/text number) — not on the live Wix page.
- **Wix Facebook icon** (`facebook.com/Alvaradohomeimprovements`) and Facebook PNG chrome.
- **Template leftover** “The Best in the Business.”
- **Wix “Start Now” / builder credit.**
- **Any claim this preview is live** at alvaradohandyman.capitalreconsulting.com.

## Pages

- `index.html` — porch-note hero, cleaned Aurora headline, per-job pricing, service snapshot, Luis’s published quotes, mailto
- `services.html` — the full published menu plus small deck / fence / lawn / leak repairs
- `about.html` — June 2020 origin, wife and I, high-utility workmanship
- `contact.html` — mailto, estimate form (mailto draft)

Forms open a mail draft to lalvaradohandyman@gmail.com. They do not post to Wix.

## Images

One photo: `assets/tools.jpg` (75KB JPEG, from `Handman Tools.jpg` on the live Wix page). Captioned as a photo from their site, **not** a named job. Logo is a fresh SVG porch-plaque mark (sage house, rust mailbox flag), plus tiny favicon / apple-touch PNGs.

## JSON-LD

`HomeAndConstructionBusiness` on the homepage only, verified fields: name, email, live URL, Aurora CO, founder Luis, areaServed, description, the one image. **No telephone.** No aggregateRating, no street, no invented geo.

## Blockers

- No phone printed — contact is email only.
- No street address, hours, or reviews on the live page.
- The tools photo is the Wix page background (stock-looking shop wall), kept as site texture and captioned honestly.
