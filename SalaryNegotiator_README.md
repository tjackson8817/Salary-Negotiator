# Salary Negotiator

A single self-contained HTML tool that turns a real offer, real market data, real research on a specific company, and your real qualifications into an actual negotiation plan and counter-offer draft — not generic "just ask for more" advice.

**[Open the live tool](https://tjackson8817.github.io/Salary-Negotiator/salary_negotiator.html)**

No install, no account, nothing sent anywhere — it's a static form that assembles text entirely in your browser.

## Fifth tool in the funnel — Step 5 · Negotiate

Alongside:
- **[Target-Company-Prompt-Builder](https://tjackson8817.github.io/Target-Company-Prompt-Builder/prompt_builder.html)** — Step 1, researches and ranks companies
- **[Job-Posting-Finder](https://tjackson8817.github.io/Job-Posting-Finder/job_posting_finder.html)** — Step 2, checks who's actively hiring
- **[Resume-Cover-Letter-Builder](https://tjackson8817.github.io/Resume-Cover-Letter-Builder/resume_cover_letter_tailoring.html)** — Step 3a, tailors your documents
- **[Outreach-Message-Builder](https://tjackson8817.github.io/Outreach-Message-Builder/outreach_message_builder.html)** — Step 3b, drafts your outreach
- **[Interview-Prep-Guide-Builder](https://tjackson8817.github.io/Interview-Prep-Guide-Builder/interview_prep_guide_builder.html)** — Step 4, preps you for the actual interview

This tool is the direct sequel to Interview Prep Guide Builder's Recruiter Screen mode. That mode coaches you to state a salary *range* before an offer exists, explicitly framed as "not a negotiation yet." This tool picks up once a real offer is actually on the table.

## The one guardrail that matters most

Every tool in this family has a "don't fabricate" rule. This one has real-world teeth the others don't: **the tool never invents or exaggerates a competing offer.** A fabricated story in a draft message is bad output. A fabricated competing offer used in a real negotiation is a lie told to a real employer — one that can unravel and cost you the offer. If you don't have a competing offer, leave the field blank; the tool works fine without one and will not imply one exists.

## Quick start

1. Open `salary_negotiator.html` (via GitHub Pages, or download and double-click it).
2. Fill in the company, role, and location.
3. Paste your resume (or plan to attach it when you paste the prompt into Claude).
4. Paste or describe whatever you actually have of the offer so far — partial is fine.
5. Optionally: your target number, what matters most to you beyond salary, and a real competing offer if you have one.
6. Copy the generated prompt and paste it into a new Claude chat.
7. Review the guide, especially the Quick Reference summary at the top, before your actual negotiation conversation.

## What the guide covers

1. **Market Data Snapshot** — real, sourced compensation research for the role/level/location, treating BLS.gov and the current-year Robert Half Salary Guide as primary sources (methodologically transparent, not self-reported) and Salary.com/Payscale/levels.fyi/Glassdoor as secondary, directional data points, plus comparable disclosed job-posting ranges.
2. **Company-Specific Compensation Research** — what this specific employer pays, where findable; says so plainly when it's thin rather than passing off general market data as company-specific.
3. **Total Compensation Translation** — base, bonus, equity, sign-on, benefits, and more translated into one comparable number, compared against a competing offer only if you actually gave one.
4. **Your Differentiators** — pulled from your actual resume, never invented.
5. **Negotiation Levers Beyond Base Salary** — sign-on, equity, review timeline, relocation, start date, title — weighted toward what you said matters most.
6. **The Counter — Framing Options** — 2-3 real phrasing options for the ask.
7. **A Written Counter-Offer Draft** — an actual email or talking points, grounded in real numbers only.
8. **Negotiation Etiquette Notes** — practical reminders, including why honesty about competing offers is strategically safer, not just ethically required.

## Files in this repo

| File | What it is |
|---|---|
| `salary_negotiator.html` | The interactive tool. Open it directly in any browser, or use the GitHub Pages link above. |
| `Salary_Negotiator_User_Guide.md` / `.docx` / `.doc` | Full usage guide, three formats, same content. |
| `sample_no_competing_offer_prompt.txt` | Real example of the generated prompt with no competing offer given — shows the explicit "do not invent one" language. |
| `sample_with_competing_offer_prompt.txt` | Real example of the generated prompt with a real competing offer given — shows the comparison logic activating. |
| `Example_Salary_Negotiation_Output.docx` | **Illustrative only** — hand-written to demonstrate the guide's format and structure, not the output of an actual research run. See the disclaimer on its first page before treating any figure in it as real. |

## Notes

- This repo can be public or private — GitHub Pages on the free tier requires a public repo (or a paid plan for private-repo Pages).
- Requires Web search in Claude for market and company-specific research; Code execution and file creation is always needed, since every guide now comes back as a downloadable Word document.
- The generated prompt opens with an explicit "execute this directly, don't ask clarifying questions" instruction, aimed at other AI tools (e.g. ChatGPT) that sometimes respond with questions instead of just running the task.
- Every dollar figure and source the guide cites is expected to come from real search results. If you notice the output presenting a number without a source, that's worth flagging — it shouldn't happen by design.
