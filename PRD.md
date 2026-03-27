# Jerry Does — Product Requirements Document

## Project Overview
**Product:** "Jerry Does the Last 20%" — Guide + Landing Page
**Timeline:** Deliver by 8am Saturday, March 28, 2026
**Goal:** Complete guide (40-50 pages) + live landing page with Stripe checkout

---

## Part 1: Guide Content (Jerry writes directly)

### Structure:
1. **The 80% Problem** — Why vibe-coded apps die before revenue
2. **The Jerry System** — How an AI finishes what you start
3. **Case Study** — This guide's own launch as proof
4. **Templates** — SOUL.md, IDENTITY.md, MEMORY.md, HEARTBEAT.md, TOOLS.md

### Deliverables:
- `guide/00-intro.md`
- `guide/01-the-problem.md`
- `guide/02-the-system.md`
- `guide/03-case-study.md`
- `guide/04-templates.md`
- `guide/05-appendix.md`

### Output Format:
- Markdown files (convert to PDF in morning)
- 40-50 pages when formatted
- Include code blocks, diagrams (ASCII/mermaid), screenshots

---

## Part 2: Landing Page (Ralph loop builds)

### Tech Stack:
- React + TypeScript + Vite
- Tailwind CSS (match EAST.HUB style)
- Stripe Checkout integration
- Deploy to Vercel

### Requirements:

#### Hero Section:
- Headline: "Jerry Does the Last 20%"
- Subheadline: "How an AI Agent Takes Vibe-Coded Apps to Revenue"
- CTA: "Get the Guide — $29 (Early Bird)"

#### Problem Section:
- "You build fast. But you don't ship."
- 3-column layout: Build → Gap → Revenue
- Visual representation of the 80/20 gap

#### Solution Section:
- "Meet Jerry: The AI that finishes what you start"
- Bullet points: What's included in the guide
- Social proof placeholder (will add testimonials post-launch)

#### Pricing:
- Early Bird: $29 (first 50 buyers)
- Standard: $49 (after early bird sells out)
- Stripe Checkout integration (both test and live modes)

#### What's Included:
- 40-50 page guide (PDF)
- All templates (SOUL.md, IDENTITY.md, etc.)
- Real-time updates as Jerry launches EAST.HUB
- Discord/Telegram community access

#### FAQ Section:
- "Is this just another AI guide?" (No — it's about finishing, not starting)
- "Do I need OpenClaw?" (Helpful but not required)
- "Refund policy?" (30-day money-back guarantee)

#### Footer:
- Links: @jerrydoesops (X/Twitter)
- Email: jerrydoesops@gmail.com
- "Built by Nico + Jerry"

### Stripe Integration:
- Product: "Jerry Does the Last 20%"
- Prices:
  - Early Bird: price_XXXXX ($29)
  - Standard: price_XXXXX ($49)
- Success URL: /success
- Cancel URL: /

### Design Requirements:
- Match EAST.HUB aesthetic (clean, modern, tech-forward)
- Mobile responsive
- Fast loading (< 2s)
- Clear CTA above the fold

### Deployment:
- Domain: jerrydoes.com (register if needed, or use Vercel subdomain temporarily)
- Environment variables for Stripe keys
- Analytics: Simple page view tracking

---

## Part 3: Launch Strategy Document

### Content:
- X/Twitter launch sequence (3-5 posts)
- OpenClaw community announcement
- Product Hunt submission plan
- Email to early supporters
- Revenue projections (conservative, realistic, optimistic)

---

## Success Criteria

### By 8am Saturday:
- ✅ Complete guide content (all 6 markdown files)
- ✅ Landing page live with working Stripe checkout
- ✅ Launch strategy document ready
- ✅ Domain configured (jerrydoes.com or Vercel subdomain)

### Post-Delivery:
- Nico reviews guide content
- Test Stripe checkout (both early bird and standard)
- Final approval before Sunday launch

---

## Technical Notes

### Stripe Setup:
Use existing Stripe account (acct_1TELcn2NZAiunRo6):
- Test keys for development
- Live keys for production (Nico has access)

### File Structure:
```
jerrydoes/
├── guide/
│   ├── 00-intro.md
│   ├── 01-the-problem.md
│   ├── 02-the-system.md
│   ├── 03-case-study.md
│   ├── 04-templates.md
│   └── 05-appendix.md
├── landing-page/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── README.md
├── launch-strategy.md
└── PRD.md (this file)
```

---

## Constraints

- No bloat: Keep guide focused and actionable
- No fluff: Every section must provide value
- Visual hierarchy: Use headings, lists, code blocks effectively
- Authenticity: This is our real story, not aspirational BS

---

## Open Questions
- Domain: Register jerrydoes.com now or use Vercel subdomain temporarily?
- Early bird counter: Show "X/50 remaining" on landing page?
- Pre-launch email list: Capture emails before launch?

---

**Assigned to:**
- Guide writing: Jerry (direct execution)
- Landing page: Ralph loop + Codex
- Launch strategy: Jerry

**Deadline:** 8am Saturday, March 28, 2026
