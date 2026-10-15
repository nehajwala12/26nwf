# CreditSwan · 26North master demo

Prepared for 26North Partners, with Andrew Lindquist as the signed-in user. Built 15 October 2026 in the same format as the CreditSwan Microsoft 365 demo (`CreditSwan_Demo_Vercel.zip`).

## What is in it

| File | What it is |
|---|---|
| `index.html` | The demo: a simulated Microsoft 365 window (SharePoint, Teams, Outlook, Excel, Word, Planner, Power Automate, Copilot) with a 40-step guided tour |
| `creditswan-overview.html` | The 14-page CreditSwan overview, cover set to 26North Partners · Andrew Lindquist |
| `onelife-packet.html` | The Onelife Fitness packet (V2), also embedded in the demo's Portfolio site |
| `Veterinary_care_Diligence_File_Oct-26.pdf` / `.xlsx` | The synthetic sample Diligence File the demo opens and downloads |
| `vercel.json` | Clean URLs and `noindex, nofollow` |
| `markdown/` | The Markdown edition in the "super demos" format: Onelife credit diligence, Onelife company diagnostic, and One evidence set for equity, credit and insurance |
| `evidence-baseline.md` | The one illustrative number set every part of the demo uses |

## Round 2 changes (15 October 2026)

- The One evidence set diagram is readable again (light text on the dark box had picked up the chart halo).
- Deal knowledge now follows 26North's focus: industrials, building products, aerospace and defence, distribution, business services, software, media and live events, healthcare services, and financial and insurance services, with consumer services kept for vet care and fitness. Pipeline deals are sized to 26North's market ($26–88M borrower EBITDA, 4.5–5.75x, S+475–575). Example deals and sponsors remain synthetic.
- Every SharePoint page carries about three times the graphs it had: roughly 240 across the hub, Portfolio, Onelife, Deal knowledge and One evidence set pages, up from about 70. Modelled exhibits carry an ILLUSTRATIVE DATA badge, and assumptions sit at the bottom of each page.
- The Diligence File follows the current CreditSwan brand: About CreditSwan is tab 02, assumptions moved to the bottom of each tab, stamps read For 26North Partners · Refreshed 15 Oct 2026 · Confidential, and the file is written for 26North rather than a placeholder lender. The downloadable PDF and workbook still name the original placeholder lender.

## The tour

- Steps 1–18: the platform as before (command center, knowledge graph, pipeline, Diligence File, Copilot, deal-room change, monthly package check, covenant workbook), now as 26North's hub with Andrew as the user.
- Steps 19–28: Onelife Fitness after close. The portfolio monitor, a 15-finding diagnostic, the full Onelife packet in SharePoint, the 27-monitor Monday board, the value-bridge levers ($75M → ~$92M), a new capex-gate tab (new builds against conversions), the breach flow, the Teams board, Planner and the Word board note.
- Steps 29–37: One set of evidence for equity, credit and insurance (demo angle #3). A new SharePoint site with seven tabs: overview, fact base (F-01–F-20 with lineage), this morning's restatement (replayable), equity view, credit view, insurance view, and permissions and walls. Plus a roll-out page across 26North holdings. It also adds a Teams channel with three audience notes, an insurance holdings note in Word, a Power Automate flow and a Copilot answer.
- Steps 38–40: model choice, the decision on the command center, the CreditSwan overview.

Use the arrow keys or the tour buttons. "Play" runs it hands-free. "Reset" goes back to step 1.

## Deploy to Vercel

The demo is a static site with no build step.

1. `npm i -g vercel` (once), then from this folder run `vercel deploy --prod`. Or drag the folder into a new project at vercel.com.
2. Framework preset: Other. No build command, and the output directory is the folder root.
3. `vercel.json` already sets clean URLs and keeps the site out of search engines.

Locally, open `index.html` in a browser. The PDF and workbook download links work once the site is served, for example with `npx serve .`.

## What is real and what is illustrative

- **Public and sourced:** 26North's businesses and AUM, the Onelife deal (October 2024, from Delos Capital, ~$500M reported value), and Onelife's clubs, markets, build budgets and pricing.
- **Illustrative model:** every Onelife operating figure, the weekly board, the debt and covenant, and the insurance holding. Onelife publishes no financials and its debt is not disclosed. The $1 joining offer is a demo scenario; Onelife actually offers free passes.
- **Synthetic:** the direct lending borrowers (Juniper, Saffron and others), the veterinary care Diligence File and the colleagues in Teams and Outlook.
- **Simulated:** the Microsoft 365 window, with no live connection to any tenant.
- **Affiliate flag:** whether a 26North lender or insurer may hold debt of a 26North portfolio company is a question for counsel. The demo shows the evidence, not an allocation.
