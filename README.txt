Elite Division III Student-Athlete Planner — Version 2.1
==========================================================

Version 2.1 replaces the mostly additive Version 2.0 decision logic with an evidence hierarchy and override rules.

EVIDENCE HIERARCHY
1. Hard constraints / overrides
2. Admissions evidence: pre-read + confirmed coach support
3. Recruiting evidence: active/priority status and substantive coach contact
4. Program need: position/event need and roster situation
5. Athletic fit
6. Academic fit
7. Student priorities

KEY OVERRIDES
- Sport not offered => not an athletic option.
- Negative pre-read => reconsider as a supported recruiting target regardless of lower-level positive signals.
- Positive pre-read + confirmed strong support + active/priority recruiting => high-priority opportunity.
- Reach + coach interest without strong admissions evidence => remains an admissions Reach.
- Athletic level below program / no realistic varsity opportunity => athletic reach or academic-only decision.
- ED expectation without confirmed strong support => warning.

NEW DECISION STATES
- High-Priority Athletic / Admissions Opportunity
- Promising — Awaiting Admissions Evidence
- Promising — Need Coach Clarification
- Academic + Athletic Fit
- Academic Option / Walk-On Path
- Admissions Reach — Recruiting Unconfirmed
- Athletic Reach
- Reconsider
- Insufficient Information

Each college now produces:
- Current decision state
- Why the app reached that state
- Counselor warnings
- Next decision point
- Recommended next steps

The app remains entirely client-side and requires no database or LLM.

GitHub Pages deployment:
Upload index.html, .nojekyll, and assets/elite-seal.png while preserving the assets folder. In Settings > Pages choose Deploy from a branch, main, /(root).
