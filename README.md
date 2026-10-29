# Partner Field Guide

An interactive, single-page learning app about AWS from a partner company's point of view, for someone starting out in video, AdminOps (QuickBooks) and RevOps and growing to an advanced level.

Open `index.html` in any browser. No install or build step needed.

## Chapters

| Group | Chapter | What's inside |
|-------|---------|---------------|
| Orientation | Start here | Learning levels, the partner business loop, 90-day checklist |
| Learn AWS | Cloud & AWS basics | Global infrastructure diagram, shared responsibility toggle, pricing models, Well-Architected pillars |
| | Service explorer | ~57 services in plain English with search and filters |
| | Technical essentials | Clickable architecture diagrams (web app, serverless, data pipeline, video pipeline), compute/database/storage decision guides, disaster recovery (RPO/RTO), security checklist, DevOps |
| | Cloud economics | CapEx vs OpEx, six advantages, Cloud Value Framework, 3-year TCO calculator, cost-lever chart, FinOps lifecycle |
| | AI on AWS | AI vocabulary, the AWS GenAI stack, RAG flow, value-vs-feasibility use-case matrix, GenAI cost estimator, responsible AI |
| | How businesses use AWS | Nine industries with workloads, services, outcomes and buying criteria; common workloads; buying triggers; how customers choose |
| | Cloud Practitioner prep | Exam facts and domain weights (also AI Practitioner), flashcards, 7 Rs, support plans, cost tools, 4-week plan |
| Partner business | How the business runs | Revenue streams, illustrative P&L waterfall, partner flywheel, consultant economics calculator, operating rhythm |
| | Partner Network | Partner Paths, tier ladder, programs |
| | Portals & programs | Partner Central, ACE, APFP, AMMP, PSF and more; deal journey; lead sources; certifications |
| | Who's who & RACI | AWS, partner and customer roles; RACI matrix |
| | Partner vs AWS roles | Side-by-side counterparts by function, what each is measured on, joint deal handoffs |
| | GTM & co-sell | ACE stages, motions, MAP phases, plays |
| | Sales essentials | Why change/now/AWS/us, MEDDICC, discovery questions, objection handling, content per deal stage, pricing models |
| | Funding programs | Request-to-payout flow, program table, rejection reasons |
| Your job | RevOps | Lead-to-cash, weighted pipeline calculator, metrics, systems map |
| | KPIs & tracking | How to set KPIs, leading vs lagging, KPI tree, 27-KPI library, editable KPI tracker with status and copyable update |
| | AdminOps & QuickBooks | Invoice lifecycle, Marketplace payout and DSO calculators, month-end close checklist |
| | Video & content | Production pipeline, formats, brand rules, measurement |
| Reference | Calendar & history, Glossary, Quiz | Annual AWS calendar, milestones, revenue chart, 100+ terms, 18 questions |
| Career | Grow & contribute | 30-60-90 plan, use cases, rules, habits, impact metrics |

Checklists, the KPI tracker and quiz scores are saved in your browser only.

## Editing

The app source is `app/partner-field-guide.html` (content is in plain JavaScript arrays near the top of the script). After editing, run `./build.sh` to regenerate `index.html`.

AWS program names, tier thresholds, fees and funding rules change often. Treat the app as a map and confirm specifics in AWS Partner Central.
