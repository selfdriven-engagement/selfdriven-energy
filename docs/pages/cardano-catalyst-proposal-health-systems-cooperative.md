---
layout: default
title: Cardano Catalyst Proposal - Health Cooperative
permalink: /cardano-catalyst/proposal/health-systems-cooperative/
---

## Cardano Catalyst Proposal
# Powering New Health Systems using Cardano, by selfdriven & beHub

A part of the [selfdriven Health](https://selfdriven.health) initative.

---

## Applicant

### Name

Mark Byers

### Type

Entity (Incorporated)
selfdriven Pty Ltd

---

## Summary

### Budget Information
200,000 ADA

### Time (Duration)
10 months

### Translation Information
No / English

### Problem Statement

*AI enables decentralised health, but it depends on trusted systems. Non-technical health organisations struggle to adopt blockchain and identity tech needed to make it work.*

Traditional Health Care facilities are under pressure.
With the arrival of GAHI as a society we have the opportunity to decentralise health functions.
But for it to work they need highly trustable systems,
But it is difficult for non-technical health system organisations to engage with the blockchain & identity technology in a meaningful way.

### Solution Overview

*Partner with beHub to deploy an open-source Health Systems Cooperative Kit, enabling health organisations to roll out blockchain, SSI and AI-accountable operations across traditional and emerging services.*

Partner with the beHub to run a real implementation project, built using a co-developed open-source Health Cooperative Kit that supports the full journey from definition to deployment.

A cooperative of health organisations will apply and facilitate the introduction of the kit across traditional and emerging health services.

The result is a next-generation health system model where blockchain, SSI and AI accountability are built into everyday health operations.

### Supporting Documentation

https://energy.selfdriven.foundation/cardano-catalyst/proposal/health-systems-cooperative/

### Project Dependencies

- Cardano network
- selfdriven.network
- selfdriven.health Cooperative

### Project Open Source

Yes (MIT/Apache‑2.0/CCO).

---

## Theme Selection

Real World Applications: Healthcare

---
## Campaign Selection

Cardano Use Cases: Prototype & Launch

### Describe what makes your idea innovative compared to what has been previously launched in the market (whether by you or others)

We cannot find any existing product or Catalyst proposal that takes a health initiative all the way from an initial intent definition through to a fully provisioned, operational, decentralised cooperative system. The gap is end-to-end delivery: most solutions focus on tooling or pilots, but none provide the full pathway for real health organisations to define a mission, coordinate stakeholders, establish governance, deploy infrastructure, and operate a live cooperative model.

### Describe what your prototype or MVP will demonstrate, and where it can be accessed.

The prototype will be accessible at https://coop.selfdriven.health (built on org.selfdriven.app and app.behub.io). It will show the current cooperative platform in action and demonstrate how self-actuation extends it — guiding a health organisation from definition of intent through to a fully provisioned decentralised cooperative system with governance, identity, and deployment steps built in.

### Describe realistic measures of success, ideally with on-chain metrics

Success can be measured through clear on-chain signals. These include the generation of cooperative scripts and Plutus addresses to manage shared assets, proofs of identity issued and verified, and evidence of cooperative members actively using the system themselves — such as creating their own wallets and participating in DeFi activity as part of healthcare operations.

Generation of:
- Coop Script/Plutus Addresses for managing shared assets
- Proofs of identity
- Coop member self-use ie create own wallet - DeFi usage.

[NUMBERS]
---

## Your Project and Solution

### Solution

We will build and deliver an open-source Health Cooperative Kit—a fully integrated, end-to-end framework that allows health organisations to move from “intent definition” all the way to a fully operating decentralised cooperative on Cardano.

- The Kit is based on our existing foundations (org.selfdriven.app, app.behub.io) but enhanced to support health-sector specific cooperative workflows.

- It codifies a health organisation’s mission, governance, structure, roles and processes using a structured definition (e.g. JSON) — essentially a “blueprint” for what the cooperative should be and how it should operate.

- Once defined, the Kit automates the generation of on-chain components: cooperative scripts, Plutus addresses for shared assets, identity and membership management via SSI/DID & Verifiable Credentials, and asset-management logic (treasury, payments, exchanges using ADA/USDM, DeFi integrations, etc).

- The system provides tools and UI for health-organisations (even non-technical) to onboard: register members, issue identities, manage wallets, and transparently handle operations — without requiring deep blockchain or cryptographic knowledge.

- By combining identity, governance and asset management — the Kit creates a “plug-and-play” model for decentralised health cooperatives. Early adopters (a small network of health providers via beHub) will run a real pilot to validate the concept across traditional and emerging health services.

*This is the first real health-sector implementation that spans definition → governance design → SSI identity → treasury/asset provisioning → live cooperative operations on-chain.*

**Key technical components:**
- Intent & Cooperative Definition Layer
- Structured cooperative “blueprint” (JSON/YAML) for mission, roles, governance, membership and economic model.
- Template library for different health cooperative patterns (clinic, allied health network, mutual aid, etc.).
- Identity & Membership (SSI) Layer
- DID/SSI wallet integration for organisations and members.
- Verifiable Credentials for roles (member, practitioner, admin, auditor).
- Onboarding flows for non-technical users (invite, verify, issue credential).
- Governance Layer
- Configurable rules for proposals, voting thresholds, roles and permissions.
- On-chain / off-chain hybrid governance workflows (e.g. signalling off-chain, enforcement on-chain).
- Versioned governance profiles so cooperatives can evolve over time.
- Asset & Treasury Layer
- Generation of cooperative scripts and Plutus addresses for shared assets.
- Treasury primitives for ADA/USDM flows (member contributions, fees, payouts, rewards).
- Hooks for DeFi integrations so members can use their own wallets and participate in shared financial activity.
- Operations & Workflow Layer
- Configurable workflows for member onboarding, service access, contribution logging and dispute handling.
- Role-aware views (member, practitioner, coordinator, auditor) for day-to-day operations.
- Web App & UX Layer
- Hosted front-end at coop.selfdriven.health (backed by org.selfdriven.app and app.behub.io).
- Dashboards for cooperative health: membership, governance activity, treasury status and SSI credential usage.
- Guided wizards to take a cooperative from “define” to “live on Cardano”.
- Integration & API Layer
- APIs for integrating with existing health systems (EHR/clinical systems, booking tools, CRM).
- Webhooks and event streams for plugging into beHub and other community tools.
- Monitoring, Proof & Learning Layer
- On-chain metrics dashboards (scripts created, transactions, identities issued, member wallet usage).
- Data export for research, impact reporting and further Catalyst proposals.

### Impact

This project enables health organisations to adopt blockchain, SSI and cooperative governance in practice — not theory. Instead of more proofs-of-concept, it delivers a live cooperative model that real health providers can operate, learn from and scale.

**The impact is threefold:**

1.	Impact on the health sector

- Simplifies access to decentralised technology for non-technical health organisations.
- Strengthens patient and practitioner trust through verifiable identity and transparent governance.
- Reduces dependency on centralised operators by allowing health organisations to collectively own and govern shared digital infrastructure.
- Opens the door to new models of care: mutual support networks, community-based resourcing and distributed service delivery.

2.	Impact on Cardano

- Demonstrates a compelling real-world use case for Cardano combining Plutus, SSI and DeFi in a transparent and socially beneficial sector.
- Creates repeatable open-source patterns for cooperative formation and on-chain treasury management.
- Expands Cardano’s footprint into the health industry and generates new opportunities for integrations (identity wallets, payments, service tokens, research registries, etc.).

3.	Impact on communities and individuals

- Health organisations retain control of their data, membership and financial flows.
- Members can participate directly — creating wallets, receiving credentials, voting on proposals and benefiting from shared value.
- Encourages patient-first health models where accountability is built in and value flows back to the community.

The project’s success establishes a reproducible pathway for other sectors (insurance, education, disability support, aged care, telehealth, mental health). Each new cooperative can be created faster and with lower cost because the framework, infrastructure and governance patterns already exist.

*This project doesn’t demonstrate blockchain for health — it operationalises it.*

### Capabilities & Feasibility

The selfdriven Foundation was founded in 2019 and the team is highly engaged within the Cardano community. It has a robust organisational structure and includes a professional services team - [selfdriven.services/team](https://www.selfdriven.services/team).

**Mark Byers (selfdriven Co-founder)**

Mark is a qualified Engineer and has 30+ years experience delivering internet based high-grade solutions to market, including the vision to co-found the [entityOS.cloud](https://entityOS.cloud) service in 2000.

Mark has been involved in the Cardano ecosystem since 2019 and has a strong technical understanding and involvement in community projects and a co-initiator and contributor to the Eastern Cardano Council.

[linkedin.com/in/marknbyers](https://www.linkedin.com/in/marknbyers)

**Bence Lukács (selfdriven Co-founder)**

Bence is a former sports trainer and school teacher with 10+ years of experience in Digital Education, Higher Education Organisational Development and building open learning and collaboration (infra-)structure.

Bence also researches Blockchain through the lens of social sciences, focusing especially on Openness, Open Science and DeSci.

At the selfdriven Foundation he is the Organisational Lead, managing projects and organisational operations as well as supporting the development of the educational frameworks. He is engaged in the DACH (Germany, Austria and Switzerland) Cardano Community and an IntersectMBO member, participating in the Decentralised Education, the Decentralised Trust & Identity SIG and (co-hosting & attending various) Constitutional Workshops.

[linkedin.com/in/bencelukacs](https://linkedin.com/in/bencelukacs)

**Damian Noonan (selfdriven Co-Founder)**

Damian has over 20 years experience delivering technology projects as part of strategic transformation initiatives, with expertise particularly Salesforce, MuleSoft and its emerging technologies. As co-founder of recently acquired Tquila ANZ, Damian has experience in building teams and delivering enterprise solutions.

[linkedin.com/in/damian-noonan](https://www.linkedin.com/in/damian-noonan-9942891)

**Elizabeth Jones – Co-Founder & Partnership Development Manager**

Elizabeth is a health professional and entrepreneur with over 35 years’ experience across clinical nursing, hospital procurement, sales leadership, and healthcare innovation. A former ICU nurse, she has held senior roles with Ramsay Health Care, Sydney Adventist Hospital, BD, and ICU Medical, leading teams, managing multimillion-dollar procurement portfolios, and forging strategic partnerships in both public and private health. As co-founder of beHub, Elizabeth combines frontline clinical insight with commercial acumen to improve clinician access to accurate device information, streamline onboarding, and enhance patient flow. She continues to work part-time within NSW Health, keeping her closely connected to the realities of hospital operations.

[linkedin.com/in/elizabeth-jones](https://au.linkedin.com/in/elizabeth-jones-38982511)

**Brian Halse – Co-Founder & Chair**

Brian Halse is an experienced chair, non-executive director, and governance specialist with over two decades of leadership across agribusiness, education, health technology, and the not-for-profit sector. His career includes CEO roles at ChemCert Australia, High Security Irrigators, and beHub Health, where he co-founded and helped scale the platform to 31 hospitals and 3,000+ clinicians. Known for building trusted stakeholder relationships and delivering organisational transformation, Brian brings deep expertise in strategic governance, financial management, and guiding multi-stakeholder initiatives from concept to execution.

[linkedin.com/in/brianhalse](https://au.linkedin.com/in/brianhalse)

**About beHub**

beHub is an Australian digital health platform transforming how hospitals, manufacturers, and clinicians access medical device and product information. In large, geographically dispersed healthcare systems like Australia’s, frontline staff often struggle to access up-to-date, manufacturer-approved resources when and where they need them. beHub solves this by centralising product and training materials into one secure platform, enabling hospitals to create department-specific device “playlists,” track usage, and receive direct updates from manufacturers.
Already rolled out to 31 hospitals with over 3,000 clinicians, including some of the most remote facilities in the country, beHub is live across the Murrumbidgee Local Health District in New South Wales and Alice Springs Hospital in the Northern Territory. Operating within NSW Health – one of the world’s largest healthcare systems with 220+ hospitals – the platform ensures every site, from tertiary centres to rural outposts, has instant access to accurate, current device information. Expansion is underway into more NSW and NT hospitals, supported by early manufacturer partnerships and a scalable subscription model for long-term growth.

**Teams**
- [selfdriven Services](https://www.selfdriven.services/team)
- [BeHub](https://www.behub.com.au)

---

## Milestones

### Summary

- Project Management Plan
- Design & Build
- Use / Test - Pilot
- Document / Socialise / Publish

### MILESTONE #1 ---

#### Title

Project Management Plan & Foundations

#### Outputs

A comprehensive project plan document covering scope, stakeholder map, work-breakdown, risk register, QA plan, communications plan, and project delivery calendar.

#### Acceptance Criteria
A single versioned plan (PDF or Markdown) stored in the project repo, tagged with release v0.1, with a visible commit history and clearly defined roles/responsibilities and timeline.

#### Evidence of Completion
Public link to repository showing the plan file + version tag + commit history.

#### Delivery Month
1

#### Cost (ADA)
20,000

#### Progress (% of Project Completion)
10%

### MILESTONE #2 ---

#### Title

Design & Build -  Health Systems Cooperative Kit

#### Outputs

- Initial release of Health Cooperative Kit with define-to-provision workflow
- Templates for roles, governance, and cooperative blueprint (JSON/YAML)
- Basic SSI identity flows (issue/verify member credential)
- Plutus script generation for cooperative addresses

#### Acceptance Criteria

A cooperative blueprint file that can automatically generate cooperative scripts and the corresponding DID/credential structure, for the selfdriven Health cooperative from onboarding to identity issuance, member wallet setup, cooperative actions, and proof-of-participation, showing the full lifecycle can run on the selfdriven Health cooperative stack without manual intervention.

#### Evidence of Completion

- Demo video + functioning prototype at https://coop.selfdriven.health
- v1 release tag in repo with changelog

#### Delivery Month
5

#### Cost (ADA)
80,000

#### Progress (% of Project Completion)
50%

### MILESTONE #3 ---

#### Title

Use & Reflect - Deployment with selfdriven Health Cooperative

#### Outputs

- Live deployment with participating health organisations
- Governance, membership onboarding, identity issuance and treasury operations activated
- Guided onboarding flows for non-technical users

#### Acceptance Criteria

A successful milestone is demonstrated by onboarding the selfdriven Health organisations, issuing credentials and wallets to a minimum of 10 members, and recording the first cooperative proposals and votes on-chain, proving the membership, governance, credentialing, and decision-making flows all operate in a real environment with verifiable participation and accountability across the selfdriven Health network.

#### Evidence of Completion

- On-chain metrics: scripts created, transactions, credentials issued
- Pilot report summarising organisational onboarding & learnings
- Screenshots/dashboards from live deployment

#### Delivery Month
8

#### Cost (ADA)
60,000

#### Progress (% of Project Completion)
80%

### MILESTONE #4 ---

#### Milestone Title

Document & Socialise - Public Release Kit

#### Milestone Outputs

- Open-source repository + documentation for running a cooperative
- Deployment and adoption playbook for new sector partners
- Metrics dashboard showing identity usage, governance activity and treasury flow
- Presentation + wrap-up video for Catalyst community

#### Acceptance Criteria

- Toolkit usable by external organisations without core-team support
- Demo instance of Health Cooperative Kit publicly accessible
- Documentation and onboarding playbook published on the website

#### Evidence of Completion

- Public repository + website updates
- Final report to Catalyst including on-chain metrics and learnings
- Presentation video / community demo

#### Delivery Month
10

#### Cost (ADA)
40,000

#### Progress (% of Project Completion)
100%

---

## Final Pitch

### Project Team

**Mark Byers - Project Lead**

Solution architecture, SSI, Cardano integrations.

Founder of selfdriven Foundation. 10+ years designing decentralised operating systems for communities. Leads development of Cardano-enabled identity, governance and cooperative tooling.

**Bence Lukács - Organisation Lead**

Cooperative structure, operating models, member roles.

Specialist in organisational architecture and community self-governance. Experience designing practical operating models for cooperatives and distributed teams.

**Damian Noonan - Systems Lead**

Health systems, deployment, provider onboarding.

Health innovation strategist. Works across clinical and allied health systems with deep knowledge of service workflows and compliance in real-world settings.

**Elizabeth Jones - Design & Engagement Lead**

UX, adoption, non-technical onboarding.

Designer focused on accessibility and human-centred rollout of complex systems. Experienced in stakeholder education and communications for community-based projects.

**Brian Halse - Governance**

Governance frameworks, policy, proposals & voting.

Independent governance specialist. Experience in cooperative governance, risk frameworks and transparency mechanisms for community-owned organisations.

### Budget & Costs

**M1 – Project Management Plan – 20,000 ADA**

Project Management: Scope definition, stakeholder mapping, work-breakdown structure, risk register, QA plan, comms plan, delivery calendar – 18,000 ADA

Tools & Admin: Project repository setup, version control, reporting templates, meeting facilitation tools – 2,000 ADA

**M2 – Design & Build – 80,000 ADA**

Solution Architecture & Design:
Use-case design, process mapping (inputs/outputs), data schema definition, public/private data categorisation – 5,000 ADA

Community Cardano Kit Development:
Core build of Community Cardano Kit components, integration with Selfdriven.network On-Chain, SSI & AI interfaces – 50,000 ADA

selfdriven / Cardano Network Integration:
Mapping to Cardano assets, AVS/partner-chains setup, integration of AVS features including Midnight compatibility – 10,000 ADA

Interface Enhancements:
Updating On-Chain interface reference and implementing UI/UX improvements for community onboarding – 10,000 ADA

Testing & Quality Assurance:
Internal QA, functionality verification, interface validation, regression testing – 5,000 ADA

**M3 – Use / Test – Pilot – 60,000 ADA**

Deployment & Setup:
Deploy Community Cardano Kit in pilot environment, configure network and infrastructure – 5,000 ADA

User Onboarding & Training:
Create onboarding pathways, run training workshops, support initial users – 35,000 ADA

Field Testing & Feedback:
Run live tests, gather feedback, analyse performance data, make adjustments – 15,000 ADA

Reporting & Review:
Document test results, lessons learned, and recommendations for scaling – 5,000 ADA

**M4 – Document / Socialise / Publish – 40,000 ADA**

Documentation:
Compile final public docs, onboarding materials, reports and technical integration notes – 30,000 ADA

Community Engagement:
Presentations, social media promotion, partnership announcements, case studies – 5,000 ADA

Production & Publishing:
Video walkthroughs, assets, website updates, graphical comms – 5,000 ADA

### Value for Money

This project delivers maximum real-world impact per ADA by focusing funding on working software, live adoption and open-source infrastructure — not on research or theoretical analysis.

**Why the budget is efficient**
- The solution builds on existing deployed platforms (org.selfdriven.app + app.behub.io), avoiding months of foundational work and cost.
- Funding goes toward extending a working system into a reusable Health Cooperative Kit rather than creating a one-off bespoke product.
- Pilot partners supplied by beHub reduce outreach and onboarding costs while guaranteeing immediate use of the system.

**Primary value drivers**
- A repeatable cooperative model that can be used by other organisations and sectors without needing new development.
- Permanent open-source assets (identity flows, governance tooling, cooperative blueprinting, wallet + treasury operations).
- On-chain utility for Cardano (Plutus scripts, DID usage, transactions in ADA/USDM, governance interactions).

**Cost discipline**
- ~65% of funds go directly to engineering and UX for the reusable open-source kit.
- ~20% support real pilot deployment, ensuring adoption and measurable usage.
- ~15% cover project management, documentation and Catalyst reporting.

**Long-term sustainability**
After completion, health cooperatives and future sector partners can adopt the system without additional Catalyst funding.
Future growth is driven by organisations running their own cooperatives — not ongoing public funding.

**Net effect**
For the cost of a single project, Catalyst funds infrastructure that:
1.	solves an immediate real-world need in the health sector, and
2.	becomes a reusable foundation for education, disability support, aged care, insurance and other community-owned service domains.

*This is high-leverage funding that turns one proposal into a long-term multiplier for Cardano adoption and impact.*

## Self-Assessment 

- [Self-Assessment Details](/cardano-catalyst/proposal/checklist/)

### Self-Assessment Checklist

#### I confirm that evidence of prior research, whitepaper, design, or proof-of-concept is provided.
Yes

#### I confirm that the proposal includes ecosystem research and uses the findings to either (a) justify its uniqueness over existing solutions or (b) demonstrate the value of its contribution.

Yes

#### I confirm that the proposal demonstrates technical capability via verifiable in-house talent or a confirmed development partner (GitHub, LinkedIn, portfolio, etc.).

Yes

#### I confirm that the proposer and all team members are in good standing with prior Catalyst projects.

Yes

#### I confirm that the proposal clearly defines the problem and the value of the on-chain utility.

Yes

#### I confirm that the primary goal of the proposal is a working prototype deployed on at least a Cardano testnet.

Yes

#### I confirm that the proposal outlines a credible and clear technical plan and architecture.

Yes

#### I confirm that the budget and timeline (≤ 12 months) are realistic for the proposed work.

Yes

#### I confirm that the proposal includes a community engagement and feedback plan to amplify prototype adoption with the Cardano ecosystem.

Yes

#### I confirm that the budget is for future development only; excludes retroactive funding, incentives, giveaways, re-granting, or sub-treasuries.

Yes

---

## Required Acknowledgements
Ongoing Projects
None

---

## Consent & Confirmation

### I Agree

Yes

---

REFERERENCES
------------

A cooperative as a form of business.

It is difficult for health organisations to engage with the Cardano network in a meaningful way.

Based on the real need of health systems to tranform, deliver a “Health Cooperative Cardano Kit”.

From definition to provisioning on Cardano.

Work with the selfdriven.health to deliver a real use project, based on the co-developed open-source kit - from definition to implementation.

From prototyping to real use.

Definitions
- octology template

Primitives:
    - Cardano:
        - Addresses
        - Script Addresses
        - Plutus Addresses
        - Transactions

    - Trust
        - Identity/SSI - DID/Keri
        - Veriable Credentials

    - Economic Assets
        - Treasury
        - Exchange - DeFi

Services (to abstract primitives into Cooperative system):
    - selfdriven.network including Ouroboros based chain ("OctoChain")
    - Cardano Mainnet as AVS

Leveraging:
- [selfdriven.id](https://selfdriven.id)
- [actuate.selfdriven.community](https://actuate.selfdriven.community)
- [octology.io](https://octology.io)
- [selfdriven.network](https://selfdriven.network)

### Outcomes for the Cardano Community
- Real Reference Model
- Open Source Kit - Faciliated by the selfdriven Foundation

### Related

- [selfdriven.health](https://selfdriven.health)
- [Common Proposal Checklist](/cardano-catalyst/proposal/checklist/)

---

## FAQS

**Is it too ambitious?**

Scope is proven — team has built similar systems before and the whole plan is milestone-locked with a single cooperative pilot.

**Who will use it?**

The Beyonders Collective is confirmed as the live pilot; the output is a reusable kit for any cooperative globally.

**Is it speculation?**

No tokens, no hype. Real payments, real users, real income distribution.

**Will people outside crypto adopt it?**

UX is designed for non-technical users. No blockchain terminology required to participate.

**How does it benefit Cardano?**

Creates recurring payments, new wallet users, and sustainable grassroots economic activity on ADA / USDM.

**What happens after funding?**

No further funding required — the kit is open-source and reusable. Revenue model is optional hosted services, not more Catalyst requests.

**Is the team capable?**
Team has delivered smart contracts + governance + SSI + onboarding in real organisations before.

**What if the cooperative drops out?**

Commitment is formalised before build. If failure happens, the code and kit still launch publicly.

**Is the budget fair?**
Every line item ties to delivery of reusable open-source infra and onboarding — no marketing fluff.

**How will success be verified?**
On-chain transactions + governance events + distribution cycles + documentation + case study.
