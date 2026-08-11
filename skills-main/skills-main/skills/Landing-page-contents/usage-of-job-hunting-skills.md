---
name: landing-page-writor
trigger: Use whenever the user asks to write, draft, or rewrite a landing page, sales page, or conversion-focused offer page copy
output: Plain text only — 7 labeled sections following the 7-Step Creative Framework. No HTML, CSS, or front-end code.
version: 1.0
author: Mohamed
---

# landing-page-writor

## 1. Name
`landing-page-writor`

---

## 2. Trigger (Description)
Use this skill whenever the user asks to:
- Write a landing page
- Create landing page copy
- Draft a sales page, offer page, or product page
- Write copy for any conversion-focused single-page layout
- Rewrite or improve existing landing page content

**Trigger commands:**
- "Write a landing page for [product/offer]"
- "Create landing page copy for [brand/service]"
- "Draft a sales page for [offer]"
- `/landing-page-writor` — forces activation

> ⚠️ **Never activate for:** blog posts, email sequences, social media captions, ad copy, or any multi-page website copy.

---

## 3. Output
- Plain text only. No HTML, CSS, Markdown formatting symbols, or front-end code of any kind.
- Output is structured as 7 labeled sections following the 7-Step Creative Framework (see Step-by-Step Instructions).
- Each section is separated by a clear section header in ALL CAPS.
- Tone is persuasive, clear, and benefit-driven — never fluffy or corporate.
- Length: Each section should be tight and purposeful. No padding, no filler.

---

## 4. Dependencies
- Product/offer name
- Target audience (who is the customer?)
- Core problem the product solves
- Key benefit or transformation promised
- Any existing brand voice notes, taglines, or messaging guidelines (optional)
- Desired CTA action (buy, sign up, book a call, etc.)

> If any of the above are missing, Claude must pause and ask before proceeding. Do not assume or hallucinate product details.

---

## 5. Step-by-Step Instructions & Human-in-the-Loop

**Before writing anything — ask these questions if not already provided:**
- What is the product or service?
- Who is the exact target audience?
- What is the #1 problem this solves?
- What is the desired CTA (e.g., Buy Now, Book a Call, Start Free Trial)?
- Any tone preferences or words to avoid?

Once confirmed, execute the 7-Step Creative Framework in order:

---

### STEP 1 — HOOK
Write a single, punchy opening line that stops the reader cold.
- Must speak directly to the reader's pain, desire, or identity.
- No generic openers. No "Welcome to [Brand]."
- Options: bold claim, provocative question, or pattern interrupt statement.
- Expected output: 1–2 sentences max.

---

### STEP 2 — PROBLEM
Agitate the core pain the reader is experiencing right now.
- Name the problem clearly. Make them feel seen.
- Use the reader's own language — speak like they think, not like a brand.
- Stack 2–3 specific symptoms or frustrations they face.
- Expected output: 2–4 short paragraphs or punchy single-line stacks.

---

### STEP 3 — SOLUTION
Introduce the product/service as the inevitable answer.
- Do not list features yet. Lead with what it does for them.
- Frame the solution as a shift, not just a product.
- Expected output: 1 strong positioning paragraph + product name introduction.

---

### STEP 4 — COPY ANGLE
This is the core persuasion layer. Choose and execute one dominant angle:
- **Authority Angle** — proven results, credentials, track record
- **Transformation Angle** — before vs. after story
- **Simplicity Angle** — easiest path to the outcome
- **Urgency/Scarcity Angle** — why act now, not later
- **Social Proof Angle** — others like you have done it

Build out this section with:
- 3–5 core benefit bullets (outcome-focused, not feature-focused)
- 1 mini proof block (stat, testimonial placeholder, or case result)
- Expected output: Bullet list + 1 short proof statement.

---

### STEP 5 — OBJECTION HANDLING
Pre-empt the top 2–3 reasons someone would NOT buy right now.
- Use a "You might be thinking..." or FAQ-style structure.
- Reframe each objection into a reason to move forward.
- Expected output: 2–3 objection-reframe pairs in plain text.

---

### STEP 6 — TRUST BUILDER
Establish credibility before the final CTA push.
- Options: founder story snippet, number of customers served, media mention placeholder, guarantee statement, or results data.
- Must feel earned, not boastful.
- Expected output: 1 short trust paragraph or 3-line credibility stack.

---

### STEP 7 — CTA (Call to Action)
Close with one clear, single action.
- One CTA only. No option paralysis.
- Reinforce the transformation in the button text or surrounding line.
- Add a micro-commitment line beneath the CTA (e.g., "No contracts. Cancel anytime." or "Takes 2 minutes to get started.")
- Expected output: CTA headline + button label copy + 1 micro-commitment line.

---

### Human-in-the-Loop Rule
At any point where product details are unclear, Claude must STOP and ask a specific question before continuing. Never invent product names, pricing, testimonials, or guarantees. Always flag assumptions explicitly.

---

## 6. Rules and Constraints

**DO:**
- Write in plain text only — no HTML, CSS, JavaScript, or front-end code
- Follow the 7-step framework in exact order, every time
- Label each section clearly in ALL CAPS
- Write as an 8-year experienced landing page copywriter — conversion-first, reader-first
- Use short sentences, active voice, and direct address ("you")
- Match tone to brand voice if provided

**DO NOT:**
- Generate any HTML, CSS, design mockups, or UI components — ever
- Skip or reorder any step in the 7-Step Creative Framework
- Use vague, corporate, or generic language ("innovative solution," "world-class")
- Write feature lists without tying each feature to a reader benefit
- Use more than one CTA in the final section
- Pad output with filler — every line must earn its place
- Assume product details not explicitly provided by the user
