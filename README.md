# Anthony Malon
**Digital product manager · AI-assisted product delivery**
Dubai · [LinkedIn](https://www.linkedin.com/in/anthonymalon) · anthony@malonadvisory.com

10 years in product management in complex, advanced IT environments, leading cloud migration, API integration and the digitalisation of the customer journey.

Today I define the product, write the requirements, prioritise the backlog and steer delivery, using AI coding agents as the build team. Every project below starts the way a bank product should: a written problem, named users, user stories with acceptance criteria, and a release plan, before any code.

## How I run a product
| Step | What I produce |
|---|---|
| Requirements | PRD (problem, users, must-haves, out of scope, open questions I raise with the client) |
| Backlog | Numbered feature list, each with an acceptance test a non-technical person can run, tagged v1 or later |
| Experience | Design brief and screen-by-screen rules (screen contracts), signed off before building |
| Delivery | Plan per feature, small build steps, automatic checks (types, lint, tests, build) that must pass |
| Release | Work split into parallel lanes with clear folder owners and one architect for shared parts |
| Assurance | Second-model review of every change; I judge each finding against the brief, not blindly |

## Governing AI work (what I do in practice)
- Secrets stay on the server and out of the code; no real personal data in prompts, tests, logs or screenshots.
- No test or check is weakened to get a pass; if a check is wrong, I say why.
- Money handled by one tested module (whole fils, no rounding drift), not scattered through screens.
- A human (me) approves plans, owns priorities and decides what ships. Nothing merges without my say.

## AI knowledge I bring to product management
- **Turning intent into agent-ready work:** I write the briefs, requirements and acceptance criteria that AI coding agents build from, and I judge the output against them.
- **Human in control:** agents propose, I decide. Plans are approved before building, and nothing merges or goes live without my explicit approval.
- **Independent review:** a second AI model reviews each change. I treat its findings as claims to verify against the brief and the running product, not as orders.
- **Testing AI behaviour:** I know the risks specific to AI features and check for them: prompt injection, AI actions taken without human approval, unvalidated model output, and personal data leaking into logs. For AI solutions I use written test cases with a pass rate and a cost per request.
- **Cost and value awareness:** I track what an AI request costs against the value it creates, which is how I'd prioritise AI use cases by ROI.
- **Knowing the limits:** I use AI where it is strong (drafting, building, checking) and keep people on judgement, approvals and anything touching money or customer data.

## Featured projects

### 1. Tutor booking app: a paid year-long programme
*In build · Next.js, Supabase, Stripe (test mode), Resend, Vercel*
- **Problem:** booking a tutor means back-and-forth messages to find a time, then separate payment.
- **Users:** students or parents, tutors, the business owner (admin).
- **Product decisions:** one product (52 weekly lessons with one tutor), one price for all (AED 20,000, 5% VAT included), instant confirmation, no tutor approval. Refund rule set before building: full refund if no lesson taken, otherwise per unused lesson. No double-booking of a slot. Times stored in UTC and shown in each person's time zone. Role-based access (student, tutor, admin).
- **Delivered so far:** PRD, 18 v1 stories with acceptance checks, screen contracts and design system, database schema, unit-tested money, refund and time logic, and briefs for two parallel build lanes.
- **Outcome:** not live yet. No results claimed.
- **Code and documents:** https://github.com/Anthomalone/ai-agency-tutor-booking (PRD in `docs/`, design in `design/`)

### 2. Island travel inquiry site: customer journey and staff workflow
*In build · Next.js, Supabase, Resend, Cloudflare Turnstile, Vercel*
- **Problem:** travellers want meaningful island trips but planning and trusting options takes time.
- **Users:** travellers (no account) and agency staff.
- **Product decisions:** 11 stories in v1, 9 deliberately parked (AI companion, map, mobile app, French). Recommendations use transparent scoring, max three, each with a "why it fits" line and an "indicative only" note. Duplicate-submit protection. Staff sign in by email link, approved list only, with an inquiry status pipeline.
- **Outcome:** not live yet. No results claimed.

### 3. Quote builder: shipped and live
*Live · HTML and JavaScript, Vercel*
- A working quote tool: price by area and finish level, optional extras, 5% VAT, quote number and 14-day validity. All rates sit in one file so the owner can update prices without touching logic.
- https://rimal-quote.vercel.app *(include only if cleared; shows a company name)*

## Skills
Product strategy and roadmap · PRDs, user stories, acceptance criteria · backlog prioritisation · release planning · UX collaboration · QA mindset · AI-assisted development and review · Stripe payments and refunds logic · stakeholder communication.

*The island travel repository is private. I'm happy to walk through it live.*
