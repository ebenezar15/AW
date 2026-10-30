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
| | Solution finder | 20 scenarios (static site, WordPress, web app, mobile backend, e-commerce, SaaS, migration, backup/DR, SAP, virtual desktops, contact center, data lake, GenAI assistant, school, university, healthcare, SMB, government, media, startup) each with a clickable architecture, deployment steps, criteria, cost/complexity and partner opportunity; challenge-to-solution map (14 business challenges); hosting chooser; deployment lifecycle and methods |
| | Cloud economics | CapEx vs OpEx, six advantages, Cloud Value Framework, 3-year TCO calculator, cost-lever chart, FinOps lifecycle |
| | AI on AWS | AI vocabulary, the AWS GenAI stack, RAG flow, value-vs-feasibility use-case matrix, GenAI cost estimator, responsible AI |
| | How businesses use AWS | Nine industries with workloads, services, outcomes and buying criteria; common workloads; buying triggers; how customers choose |
| | Cloud Practitioner prep | Exam facts and domain weights (also AI Practitioner), flashcards, 7 Rs, support plans, cost tools, 4-week plan |
| Partner business | How the business runs | Revenue streams, illustrative P&L waterfall, partner flywheel, consultant economics calculator, operating rhythm |
| | Partner services catalog | Customer journey orbit across services, 18 partner services (advise, build, protect, run, grow) each with flow, deliverables, AWS services, pricing, duration, KPIs, proof of expertise and a use case; common engagement backbone; pricing models; packaged offers |
| | Cloud migration | Why migrate, MAP phases, 7 Rs effort/benefit chart, 7R decision helper, migration factory, wave plan Gantt, workload types, roles, risks, 4 use cases with before/after, success metrics, what comes next |
| | Partner Network | Partner Paths, tier ladder, programs |
| | Portals & programs | Partner Central, ACE, APFP, AMMP, PSF and more; deal journey; lead sources; certifications |
| | Who's who & RACI | AWS, partner and customer roles; RACI matrix |
| | Partner vs AWS roles | Side-by-side counterparts by function, what each is measured on, joint deal handoffs |
| | GTM & co-sell | ACE stages, motions, MAP phases, plays |
| | Opportunity lifecycle | Swimlane timelines (customer, AWS, partner, other parties) for 7 scenarios: partner-originated co-sell, AWS referral, MAP migration, Marketplace private offer, non-partner vendor, resale & managed services, BVR expansion; each step with system, output, owner and timing; directory of 29 roles; who-maintains-what table |
| | Sales essentials | Why change/now/AWS/us, MEDDICC, discovery questions, objection handling, content per deal stage, pricing models |
| | Business value realisation | Promised vs realised value, 8-stage value lifecycle, value drivers with KPIs and data sources, value tree, editable value scorecard with promised/realised value, ROI and payback, worked example, reporting templates and cadence, roles, pitfalls |
| | BVR pit stops | AWS Business Value Realization motion: enrollment, nomination prerequisites, Value Realization Plan, the five pit stops (Activate, Adapt, Scaled adoption, Retain & attest, Recommend & expand), three worked examples, activity statuses, weekly adoption report, disbursements via PO and Amazon Payee Central, team roles |
| | Funding programs | Request-to-payout flow, program table, rejection reasons |
| Your job | RevOps | Lead-to-cash, weighted pipeline calculator, metrics, systems map |
| | KPIs & tracking | How to set KPIs, leading vs lagging, KPI tree, 27-KPI library, editable KPI tracker with status and copyable update |
| | AdminOps & QuickBooks | Invoice lifecycle, Marketplace payout and DSO calculators, month-end close checklist |
| | Video & content | Production pipeline, formats, brand rules, measurement |
| | Digital marketing | Success factors, 8-step process, personas (incl. AWS sellers), platform priorities, content by funnel stage, weekly rhythm, funnel/ROI calculator, metrics, attribution, UTM link builder, 90-day plan, 18 creative ideas |
| | Sales & success enablement | How video/AdminOps/RevOps help sales, enablement kit, closing checklist, deal accelerators and stallers, ABM, customer success lifecycle, health score, QBR agenda, advocacy ladder |
| Reference | Calendar & history, Glossary, Quiz | Annual AWS calendar, milestones, revenue chart, 130+ terms, 30 questions |
| Career | Grow & contribute | 30-60-90 plan, use cases, rules, habits, impact metrics |
| | Recognition & growth | Ownership register with health and review dates, maintenance standards, work log (brag document) with copyable review summary, impact calculators (time, cash from DSO, money recovered), performance factors, visibility habits, 8-step raise/promotion process with phrases, pay structure and compa-ratio, career paths, quarterly self-review |

Every step-by-step flow has a “Play walkthrough” button, architecture diagrams have “Trace the flow”, and key processes have animated pipelines (orbit loop, BVR racetrack, portal hub, request journey). Motion turns off automatically for viewers who prefer reduced motion.

Checklists, the KPI tracker, ownership register, work log and quiz scores are saved in your browser only.

## Editing

The app source is `app/partner-field-guide.html` (content is in plain JavaScript arrays near the top of the script). After editing, run `./build.sh` to regenerate `index.html`.

AWS program names, tier thresholds, fees and funding rules change often. Treat the app as a map and confirm specifics in AWS Partner Central.
