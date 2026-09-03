**SALE FISH**

MARKETING AND CONSULTING

# Salary Negotiator

*User Guide*

**Live Tool:** [https://tjackson8817.github.io/Salary-Negotiator/salary_negotiator.html](https://tjackson8817.github.io/Salary-Negotiator/salary_negotiator.html)

Created By: Tom Jackson
August 12, 2026

This tool is a single web page (salary_negotiator.html) that turns a real offer, real market data, real research on a specific company, and your real qualifications into an actual negotiation plan and counter-offer draft. Like the other tools in this family, it runs entirely in your browser: no install, no account, nothing sent anywhere until you copy the prompt and paste it into a Claude chat yourself.

## Claude Settings You'll Need Before You Start

| Setting | Why you need it / Where to find it |
|---|---|
| Web search | Needed for market compensation research and company-specific compensation research — both sections require real, sourced data, not an estimate. |
| Code execution and file creation | Only needed if you choose the downloadable Word document output format. |

## 1. How This Fits With the Other Tools

This is Step 5 in the funnel, the direct sequel to Interview Prep Guide Builder's Recruiter Screen mode. That mode coaches you to state a salary range *before* an offer exists, explicitly framed as "not a negotiation yet." This tool picks up once a real offer is actually on the table and it's time to negotiate for real.

## 2. The One Guardrail That Matters Most

Every tool in this family has a "don't fabricate" rule. This one is built around the sharpest version of it: **the tool never invents or exaggerates a competing offer.**

A fabricated story in a draft thank-you message is bad output you'd catch and fix. A fabricated competing offer used in an actual negotiation is a lie told to a real employer — one that can unravel if they ask a follow-up question, and cost you the offer entirely, not just look bad. If you don't have a competing offer, leave that field blank. The tool is built to work perfectly well without one, and will not imply, hint at, or invent one anywhere in the guide it produces.

This shows up in the generated prompt in four separate places: the field prompt itself, the field's own description if left blank, the CRITICAL guardrails block at the end, and a reminder inside the Negotiation Etiquette Notes section about why honesty here is strategically safer, not just ethically required.

## 3. The Role & Company

| Field | What to put in it |
|---|---|
| Company | The employer's name. |
| Role / job title | The specific title you're negotiating for. |
| Location | Compensation varies heavily by location — this grounds both the general market research and the company-specific research. |

## 4. Your Background

**Your resume** — paste the full text, or attach the file directly when you paste the prompt into Claude instead. This is what the guide's Differentiators section draws from — it's the only source the tool is allowed to use when identifying qualifications that justify landing above the initial number.

## 5. The Offer

- **Paste or describe the offer so far** — whatever you actually have. Doesn't need to be formatted; an email or a summary of a verbal offer is fine, and partial information is fine too. The more complete this is, the more precise the total-compensation translation can be, but the guide still produces useful research and differentiator sections even with nothing here yet.
- **Your target or walk-away number** (optional) — gives the guide something concrete to negotiate toward.
- **What matters most to you beyond salary** (optional) — e.g. "remote flexibility matters more to me than a few thousand more base." This directly weights which levers the guide prioritizes in Section 5 of the output if base salary itself turns out to be capped.

## 6. Competing Offer (Optional)

Paste or describe a real competing offer, if you actually have one. The hint text under this field says it plainly: leaving it blank is completely normal, and doing so is not a weaker use of the tool — it's the honest and expected default. Do not round up or embellish a real competing offer's numbers either; use the actual figures.

## 7. What the Guide Builds

1. **Market Data Snapshot** — real, current compensation research for the role, seniority level, and location, following a specific source hierarchy rather than treating every site as equally reliable: the U.S. Bureau of Labor Statistics (bls.gov) and the current-year Robert Half Salary Guide are treated as **primary** sources when they cover the role, since both are methodologically transparent rather than purely self-reported. Salary.com, Payscale, SalaryExpert, and levels.fyi/Glassdoor are used as **secondary, directional** data points to build a range around those primary figures, not as the sole basis for a number. Comparable job postings with disclosed ranges (increasingly required by state pay-transparency laws) are checked too — often the single most negotiation-relevant data point, since they reflect actual budget for this exact role. The guide names which source each figure came from, and flags plainly if a range leans heavily on secondary sources because primary data wasn't available for this role. Never a guessed number presented as if it were sourced.
2. **Company-Specific Compensation Research** — what this specific employer pays, searched directly (company-filtered Glassdoor/levels.fyi, public H-1B LCA disclosure data where applicable, Blind mentions, recent compensation-related news). This is often thinner than general market data. If nothing solid turns up, the guide says so plainly rather than quietly substituting the general market figures from Section 1.
3. **Total Compensation Translation** — every offer component (base, bonus target, equity/RSU value and vesting schedule, sign-on bonus, 401k match, benefits value, PTO, remote-work value, relocation) translated into one comparable total-comp number. If you gave a competing offer, the same translation is done for it and the two are compared directly — this comparison only happens if you actually provided one.
4. **Your Differentiators** — qualifications pulled only from your actual resume, framed as reasons to land above the initial number. If your resume doesn't strongly support a differentiator that would help, the guide says so honestly rather than manufacturing one.
5. **Negotiation Levers Beyond Base Salary** — a checklist of what else can move if base salary itself is capped: sign-on bonus, additional equity, accelerated review timeline, relocation assistance, start-date flexibility, title. Weighted toward whatever you said matters most to you.
6. **The Counter — Framing Options** — 2-3 concrete phrasing options for the actual ask, tied to the real data and differentiators established above, written to sound like something a real person would say rather than a negotiation-textbook script.
7. **A Written Counter-Offer Draft** — an actual email or a set of talking points for a call, grounded firmly in the real numbers and differentiators established above. Never references a competing offer, dollar figure, or qualification that wasn't actually given.
8. **Negotiation Etiquette Notes** — practical reminders: don't negotiate against yourself, get the final agreed number in writing before resigning anywhere else, calibrate how hard to push against how genuinely excited you are about the role, and why honesty about competing offers is strategically safer, not just the ethical baseline.

## 8. Output Format

- **Downloadable Word document** (default) — a reference guide you'll want on hand during the actual negotiation call or email exchange, with a one-page Quick Reference summary (market range, total-comp translation, top framing options) at the very top.
- **Table in chat** — the same content, presented directly in the response instead.

## 9. Typical Workflow, Start to Finish

1. Fill in company, role, and location.
2. Paste your resume.
3. Paste or describe whatever you have of the offer — even partial.
4. Fill in your target number and priorities if you have them.
5. Only fill in Competing Offer if you actually have one, with real figures.
6. Copy the generated prompt, paste it into a new Claude chat.
7. Review the Quick Reference summary and the full guide before your actual conversation.

## 10. Quick Troubleshooting

| Problem | Fix |
|---|---|
| Prompt panel shows placeholder text | Fill in at least the company or the role. |
| The Total Compensation section feels incomplete | Check how much detail you actually gave in "the offer so far" — the guide can only translate what it's told; missing pieces (like an unspecified vesting schedule) get flagged as needing clarification from the employer rather than assumed. |
| No competing-offer comparison in my output | Expected if you left that field blank — the guide doesn't fabricate one to fill the section. |
| Company-specific research came back thin | An honest, expected outcome for many companies, especially smaller or private ones — not a bug. The guide should say so plainly rather than substituting general market data. |
| I want to update the guide after a real conversation happened | Re-run the tool with the new offer numbers from the employer's counter, to prep for the next round. |
| In ChatGPT, it asks clarifying questions instead of running the task | The prompt opens with an explicit "execute this directly" instruction — restate it more bluntly as a follow-up if needed. |
