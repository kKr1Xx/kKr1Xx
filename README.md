<h1 align="center">Hi, I'm Kris 👋</h1>

<p align="center">
  <img alt="Developer from Italy · Building Zona FVG · Web, iOS, Android" src="https://readme-typing-svg.demolab.com?font=DM+Sans&weight=600&size=22&duration=3200&pause=1200&color=7F77DD&center=true&vCenter=true&width=640&lines=Developer+from+Italy;I+build+products+end+to+end;Web+%C2%B7+iOS+%C2%B7+Android+%C2%B7+Database">
</p>

<p align="center">
  I like taking an idea all the way to something people actually open on their phone: the database, the website, the native apps and the server underneath.
  <br>
  Right now that idea is <b><a href="https://zonafvg.it">Zona FVG</a></b>.
</p>

<br>

<p align="center">
  <a href="https://zonafvg.it">
    <picture>
      <source media="(prefers-color-scheme: light)" srcset="assets/zona-logo-light.webp">
      <img src="assets/zona-logo.webp" alt="Zona FVG" width="360">
    </picture>
  </a>
</p>

<p align="center">
  Stop asking "what's on tonight?"<br>
  The events platform for Friuli Venezia Giulia: concerts, club nights, festivals, venues and DJs.
</p>

<p align="center">
  <a href="https://zonafvg.it"><img alt="Website" src="https://img.shields.io/website?url=https%3A%2F%2Fzonafvg.it&label=zonafvg.it&up_message=online&down_message=offline&style=flat&color=7f77dd"></a>
  <img alt="Events" src="https://img.shields.io/badge/events-1%2C300%2B-7f77dd">
  <img alt="Venues" src="https://img.shields.io/badge/venues-100%2B-7f77dd">
  <img alt="DJs" src="https://img.shields.io/badge/DJs-70-7f77dd">
  <img alt="iOS: approved by Apple, release pending" src="https://img.shields.io/badge/iOS-approved%20%C2%B7%20release%20pending-lightgrey?logo=apple&logoColor=white">
</p>

<p align="center">
  <a href="https://zonafvg.it"><img src="assets/zona-mosaic.webp" alt="Zona FVG: the home page with search and this week's events, and below it the events, venues and DJs pages" width="820"></a>
</p>

<p align="center">
  <a href="https://zonafvg.it"><img alt="Open zonafvg.it" src="https://img.shields.io/badge/Open-zonafvg.it-7f77dd?style=for-the-badge"></a>
  &nbsp;
  <a href="https://www.instagram.com/zonafvg/"><img alt="Zona on Instagram" src="https://img.shields.io/badge/Instagram-@zonafvg-E4405F?style=for-the-badge&logo=instagram&logoColor=white"></a>
  &nbsp;
  <a href="https://www.tiktok.com/@zonafvg"><img alt="Zona on TikTok" src="https://img.shields.io/badge/TikTok-@zonafvg-000000?style=for-the-badge&logo=tiktok&logoColor=white"></a>
</p>

<br>

### What I built in it

I took over an existing WordPress/Voxel site, migrated its data, redesigned the whole product and put it live on **21 September 2026**. Since then it has had roughly 4,800 visits and 12,800 page views, and there are around 1,150 people following it on Instagram. The code is in a private repo, so here is the tour instead.

- **The site.** Search and filter events by place, date, time, mood, age, dress code and price. Venue and DJ pages, a map, saved events, follows and notifications.
- **A dashboard for the people behind the nights.** Owners, venue managers and DJs each get their own permissions, event editing that locks so two people never overwrite each other, collaborations between venues, and analytics.
- **Two native apps.** Swift/SwiftUI for iOS, Kotlin/Compose for Android, no cross-platform layer. Both are built from one written spec and one design-token file, so they behave the same for the user. The iOS app is approved by Apple and about to be released.
- **A social bot.** It reads the public Instagram and Facebook posts of venues and turns them into event drafts I can review, so nobody retypes a flyer.
- **My own analytics.** Visits, searches and page views counted in-house, with no third-party tracker.

A few choices I'm happy with:

- **Security lives in the database.** Roles are read from the `profiles` table, never from token claims, and every table has Row Level Security before it is ever used.
- **Designed from measurements, not guesses.** Every value in the interface comes from a documented design system.
- **No lock-in.** It runs in a container on my own VPS behind Cloudflare, with nothing that only works on one vendor's platform.

<br>

### Stack

<p align="center">
  <img alt="Next.js, React, TypeScript, Tailwind, Supabase, Postgres, Swift, Kotlin, Docker, Cloudflare, GitHub Actions, pnpm" src="https://skillicons.dev/icons?i=nextjs,react,ts,tailwind,supabase,postgres,swift,kotlin,docker,cloudflare,githubactions,pnpm&perline=12">
</p>

Next.js 16 (App Router) · Supabase with Postgres and PostGIS · Tailwind v4 · shadcn/ui · Motion · Turborepo · Coolify

<br>

### Before Zona

**Ensoul.** I spent almost a year there as an intern. My job was to test and prototype new technologies for the company, including the very first experiments with bringing AI into their workflow.
<br>

### Say hello

I'm not looking for a job, but I'm always up for an interesting proposal.

<p>
  <a href="mailto:tartari524@gmail.com"><img alt="Email me" src="https://img.shields.io/badge/Email-tartari524%40gmail.com-7f77dd?style=for-the-badge&logo=gmail&logoColor=white"></a>
</p>
