# CMS Recommendation for Your Travel Agency

## Executive Summary (Non‑Technical)

- You asked for a modern CMS with fast publishing, rich content (images, blocks, relations), and an editor experience that non‑developers can use comfortably.
- Two best overall options: Storyblok (most visual, easiest for editors) and Sanity (most flexible and scalable for developers and content teams).
- Updated ranking (based on your needs and budget):
  1) Storyblok, 2) Sanity, 3) Strapi, 4) Prismic, 5) Directus

### Video walkthroughs (for stakeholders)
- General presentation (embedded)
  
  <div style="position: relative; padding-bottom: 56.25%; height: 0;">
    <iframe
      src="https://www.loom.com/embed/0ceef9bd79004e9a849075daefb46797?sid=735d61d4-621b-4079-8ccf-edebd5a7a0e9"
      frameborder="0"
      webkitallowfullscreen
      mozallowfullscreen
      allowfullscreen
      style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border-radius: 12px;"
    ></iframe>
  </div>
  
  Fallback link: [Loom video](https://www.loom.com/share/0ceef9bd79004e9a849075daefb46797?sid=735d61d4-621b-4079-8ccf-edebd5a7a0e9)
  
  Source: [Loom](https://www.loom.com/share/0ceef9bd79004e9a849075daefb46797?sid=735d61d4-621b-4079-8ccf-edebd5a7a0e9)
- Sanity (2 short videos): see the Loom folder
  - Link: [Loom folder](https://loom.com/share/folder/f95792d3fc724895bf343113d82456e9)
- Storyblok (1 video): see the Loom folder
  - Link: [Loom folder](https://loom.com/share/folder/f95792d3fc724895bf343113d82456e9)
- Strapi (2 short videos): see the Loom folder
  - Link: [Loom folder](https://loom.com/share/folder/f95792d3fc724895bf343113d82456e9)

Note: If you want inline embeds, share each specific Loom video URL and we’ll replace the folder links with embedded players.

### Why these three?
- Storyblok: true visual editing (what‑you‑see‑is‑what‑you‑get), excellent for marketing and landing pages.
- Sanity: powerful content modeling and relationships, rich text with embedded blocks, great Nuxt integration and fast previews.
- Strapi: solid self‑host or cloud option with strong relations and roles; feels like a traditional CMS.

---

## Your Current Pain Points (from discussions)

- Slow publishing (static site builds, long deploys)
- Markdown/techy authoring that’s not friendly for non‑dev staff
- Limited rich content (hard to embed galleries, maps, or complex blocks)
- No easy way to link content (e.g., tours ↔ destinations ↔ guides)

What you need instead: instant preview/publish, rich text with embedded media/blocks, friendly editor UI, and first‑class relationships between content.

---

## TL;DR Recommendations

- Best overall for your needs: Sanity or Storyblok
  - Want the most visual editor and fastest non‑dev onboarding? Choose Storyblok
  - Want maximum flexibility, strong relations, and a great Nuxt developer experience? Choose Sanity
- Prefer self‑hosted control with a traditional admin and strong roles? Consider Strapi (now our 3rd choice)

---

## Platform Snapshots (Business‑First)

### 1) SANITY
What it is: Modern content platform used by brands like PUMA, Figma, Nike

Pros
- Real‑time preview; changes show instantly
- Excellent image handling and CDN
- Powerful relations and Portable Text (embed blocks/references)
- Scales well; great Nuxt integration (@nuxtjs/sanity) and live preview

Cons
- Editor UI is form‑based (less visual than Storyblok)
- GROQ query language adds a small learning curve

Indicative Pricing (10 people)
- Free plan to start; Growth around $150/mo
- Typical total with assets: ~$170–180/mo

Best for you if
- You want flexible modeling (tours, destinations, guides) and fast preview, and your team is OK with a polished, form‑based editor instead of drag‑and‑drop page building.

--- 

### 2) STORYBLOK
What it is: Visual content platform used by Adidas, Tesla, Marc O’Polo

Pros
- Visual editor: see exactly how pages look while editing
- Drag‑and‑drop content blocks; great for landing pages and campaigns
- Strong localization and component reuse

Cons
- More opinionated around components/blocks; needs some upfront planning
- Less ad‑hoc querying vs GROQ (at very complex scale)

Indicative Pricing (10 people)
- Team plan ≈ €299/mo (~$330) with 10 users and 100GB assets

Best for you if
- Marketing teams need maximum autonomy and speed building pages visually.

---

### 3) STRAPI (Updated to 3rd Choice)
What it is: Open‑source CMS you can self‑host or use Strapi Cloud

Pros
- Traditional admin panel; strong relations, components, dynamic zones
- RBAC/permissions, workflows, plugins (enterprise features available)
- Works with SQL/SQLite/Postgres; REST/GraphQL APIs

Cons
- If self‑hosted, you manage ops, scaling, backups, security updates
- Real‑time preview and rich block embeds require setup

Indicative Pricing (10 people)
- Self‑hosted: infra costs (~$50–200/mo) + maintenance
- Strapi Cloud Pro ≈ $99/mo (10 seats); Team/Enterprise higher

Best for you if
- You want ownership/control and a familiar CMS feel, and you’re OK with either managing infrastructure or paying for managed cloud.

---

### 4) PRISMIC
What it is: Marketing‑focused CMS with slice‑based editing

Pros
- Slices for reusable page sections; good editor UX
- Solid previews, hosted CDN

Cons
- More constrained content modeling for complex relationships
- User and repo limits can push you to higher tiers

Indicative Pricing (10 people)
- Often requires higher tier (~$450/mo) for the seats/features you’d need

Best for you if
- Your priority is campaign/marketing pages with predictable slice libraries and you’re comfortable with the pricing.

---

### 5) DIRECTUS
What it is: Data‑first, database‑driven headless CMS

Pros
- Works over your database; strong relational modeling and permissions
- Good for data‑heavy internal tools and dashboards

Cons
- Rich text and embedded blocks require patterns and setup
- Not focused on visual page building for marketers

Indicative Pricing
- Self‑hosted (infra cost) or Directus Cloud Team ≈ $349/mo for 15 users

Best for you if
- You want a data‑centric CMS over an existing DB and are less focused on marketing workflows.

---

## Feature Comparison (Plain‑English)

| Feature | Sanity | Storyblok | Strapi | Prismic | Directus |
|---------|--------|-----------|--------|---------|----------|
| Ease of use for non‑devs | ⭐⭐⭐ Good | ⭐⭐⭐⭐⭐ Excellent | ⭐⭐⭐ Good | ⭐⭐⭐⭐ Very Good | ⭐⭐ Moderate |
| Visual page building | ❌ No | ✅ Yes | ❌ No | 🔶 Limited | ❌ No |
| Publishing speed | ⚡ Instant | ⚡ Instant | 🔶 Depends | ⚡ Instant | 🔶 Depends |
| Image management (7GB) | ✅ Excellent | ✅ Excellent | 🔶 Basic | ✅ Good | 🔶 Basic |
| Multi‑language | ✅ Excellent | ✅ Excellent | ✅ Good | ✅ Very Good | ✅ Good |
| Content relationships | ✅ Excellent | ✅ Excellent | ✅ Excellent | 🔶 Limited | ✅ Excellent |
| Team collaboration | ✅ Good | ✅ Excellent | ✅ Good | ✅ Good | 🔶 Basic |
| Mobile editing | ✅ Yes | ✅ Yes | ✅ Yes | ✅ Yes | 🔶 Limited |
| Scheduling | ✅ Yes | ✅ Yes | ✅ Yes | ✅ Yes | ❌ No |

Notes
- “Visual page building” = edit like PowerPoint with immediate on‑screen changes. Sanity is form‑based, but with live preview it still feels fast.
- “Publishing speed” depends on your hosting architecture; all recommended hosted options are fast with preview.

---

## Total Cost of Ownership (Approximate, Monthly)

| Platform | Software Cost | Additional Storage | One‑time Dev Setup | Monthly Total |
|----------|----------------|--------------------|--------------------|---------------|
| Storyblok | ~$330 | Included | ~$2–3k | ~$330 |
| Sanity | ~$150 | ~$20–30 | ~$2–3k | ~$170–180 |
| Strapi (Cloud) | $99–499 | Varies | ~$3–5k | $99–499 |
| Prismic | ~$450 | Included | ~$2–3k | ~$450 |
| Directus (Cloud) | ~$349 | Included | ~$3–5k | ~$349 |

---

## Migration & Timeline (From Nuxt Content/Studio)

| Target | Difficulty | Timeline | Business Disruption |
|--------|------------|----------|---------------------|
| Sanity | Moderate | 4–6 weeks | Minimal |
| Storyblok | Easy–Moderate | 3–4 weeks | Minimal |
| Strapi | Hard (if self‑host) | 6–8 weeks | Moderate |
| Prismic | Moderate | 4–5 weeks | Minimal |
| Directus | Hard | 6–8 weeks | Moderate |

Key migration tasks
- Map your current content (tours, destinations, guides, reviews) to the new model
- Define rich text + embedded blocks (images, callouts, code, galleries)
- Set up preview workflows and editorial roles early
- Backfill content and validate URLs before go‑live

---

## Final Recommendation (Updated Ranking)

1) Storyblok — Best for non‑technical editors and rapid page building. If your team values visual editing and autonomy most, this delivers immediate productivity.
2) Sanity — Best balance of flexibility, performance, and cost. If you need rich relations and scalable content with a great Nuxt stack, choose this.
3) Strapi — Strong traditional CMS with roles/permissions; good choice if you prefer more control or self‑hosting (or a managed Strapi Cloud) and accept more setup.
4) Prismic — Polished marketing workflows and slices; higher ongoing price at the tier you’d likely need.
5) Directus — Best if you’re truly database‑driven and less focused on marketing/editorial page building.

Next steps
- Schedule short demos for Storyblok and Sanity (free trials)
- Prototype 5–10 real tours/destinations
- Collect editor feedback from 2–3 team members on each platform
- Confirm budget approvals and plan the migration (3–6 weeks typical)

---

If you share a bit more about your localization needs, team roles, and expected content growth this year, we can lock the final choice and draft the implementation plan (preview, roles, content model, and migration runbook).


