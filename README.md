# Get Organized — Master Capture (Bible Anchor)
**Everything lands here first. Reviewed daily before any action.**
**Version:** 1.8 — 2025-08-12-22-30

## Version Log
- 1.8 — added entries for GitHub orgs separation, email and hosting plans, domain transfers, family tasks, and research prompts
- 1.7 — added task: Business Plan (Business → This Week); updated script paths (Downloads → /Users/tracysmith/Personal/LocalDownloads/Tracy, Repo → /Users/tracysmith/Personal/Projects/repos/sanity)
- 1.6 — housekeeping: test push after script reload; no content changes
- 1.5 — added task: Get to bed on time (Home → This Week); README push flow confirmed
- 1.4 — added task: Renew Quicken (Home → This Week)
- 1.3 — added Version Log section; kept git optional, continue using this thread as Bible, provide downloadable backups
- 1.2 — added: Refineo Logo, review Evernote checklist, update LWD README with site links, purchase LWD misspelling domains
- 1.1 — added: integrations research (GitHub, AI, best coding AI's)
- 1.0 — initial structure with Business, Home, Shared, and Daily Shutdown

---

## BUSINESS — Refineo Studios / LWD / MHC

### Today → High-leverage, under 60 min
- Re-review domain redirects, Cloudflare only (Refineo, LWD, Hudson Cage)
- Tighten “No-reply” behavior for groups, confirm reply-to addresses
- Add Subnote spacing rule decision to CSS notes (row-gap=6, subnote mt=2)
- Purge Cloudflare cache after deploy, sanity check home on mobile + desktop
- **Wish Pop Happy Birthday on Friday, August 15**
- **Ask Gil about his Boating Exam on Saturday**

### Tomorrow → 90–120 min blocks
- SPF/DKIM/DMARC: confirm alignment for refineostudios.com and leadingwhiledistracted.com
- Build “not-a-park” holding page template, link to LWD + Refineo
- Set up Terms, Privacy, Cookies stubs and link in footer
- Stephen: verify “Notify me” POST runs end-to-end, capture success/fail states

### This Week → Planned Work
- **Infrastructure & Automation**
  - Render infrastructure doc (`render.yaml`)
  - Explore automation for domain → registrar → DNS → Cloudflare → Render setup (checkbox-driven form intake, auto-fill setup details)
- **Showcases / Case Studies**
  - Build case study pages for Refineo, LWD, MHC (keep MHC internal for now)
- **Systems & Balance**
  - Define routine that allows Refineo work without burnout
- **LWD Book**
  - Create concrete progress plan for writing
- **Socials**
  - Setup socials for LWD
  - Finish socials for MHC & Refineo
- **Substack**
  - Refineo: account created, start content plan
  - LWD: decide if separate or combined with Refineo
  - MHC: create if viable
- **Ops**
  - Google Workspace for MHC
  - Sign up for Notion under Refineo email (test free version)
- **Other**
  - Update QuickBooks
  - Figure out Bonsai usage (client contracts/invoicing only)
  - Look at other integrations: GitHub, AI, best coding AI's, etc.
  - Refineo Logo
  - Review Evernote checklist we created
  - Update README for LWD with links to LWD websites
  - Purchase domains for misspellings of LWD (including `leadingwhiledistrscted.com`)
  - Business Plan
  - **LWD Email separation from Refineo (consider separate Workspace or low-cost/free email)**
  - **LWD Domains: Create Cloudflare account and remind to transfer in 30–45 days**
  - **ROS Domains: Transfer from Namecheap to Cloudflare in 30–45 days**
  - **MHC Render: Create account or consider Vercel**
  - **LWD Render: Create account or consider Vercel**
  - **Hosting: Compare Vercel vs Render**
  - **Laptop: Decide on what to use for LWD/MHC/ROS**
  - **Create temp logo for LWD**
  - **Review GitHub org vs separate accounts for LWD/ROS/MHC**
  - **Review Jeff Armstrong LinkedIn post**: https://www.linkedin.com/posts/jeff-armstrong-16b8a648_gpt-5-base-others-is-crap-without-these-activity-7360029829414490112-QorG
  - **LWD: Research and review papers and articles**
  - **Job: Think — What the ideal would look like, how to shape it, or if leaving is right**

---

## HOME / PERSONAL

### Today → High-leverage, under 60 min
- N/A (pull from Inbox each morning)

### Tomorrow → 90–120 min blocks
- Call Verizon for Apple One login issue, set up Apple One
- Order new UPS/battery for home office

### This Week → Planned Work
- Get to bed on time
- Renew Quicken
- Cord sort & label project
- Closet reorg
- Book health appointments:
  - Primary care
  - Renew ADHD prescription
  - Dermatology
  - Eye doctor
  - Hearing (or find new Jabra aid)
- Alpha Drive project:
  - Offload files to Alpha
  - Get personal files off work computer
  - iCloud & Google Drive sync/cleanup

---

## Shared / Ops Across Both
- DNS audit pass #2 after GoDaddy→Cloudflare transfers finish
  (prettychar.com, tracycsmith.com, refineostudios.com, leadingwhiledistracted.com)
- Centralize email groups/aliases doc: owner, purpose, reply-to, posting rules
- Repo hygiene: update README with includes, publish dir, cache-bust pattern
- Breadcrumb visual style, mobile first
- Subpages branding pass: spacing scale, type sizes, tile rhythm
- Map every domain → target URL, type (301/302), managed on Cloudflare
- Create “holding” page and wire it to any unused domains
- SPF: include only sender services in use, prune old vendors
- DKIM: verify selectors active, rotate if older than 12–18 months
- DMARC: start p=none with rua/ruf to monitoring inbox, plan move to quarantine

---

## Daily Shutdown Checklist (2-min ritual)
1. Capture loose thoughts into **Inbox dump**
2. Mark 1–3 “Today” for tomorrow morning
3. Commit/push if you touched code, purge CF cache if deployed
4. Jot blockers so I can remove them first thing

---

## Done (Temporary Holding for Completed Items)
_(Archive weekly)_