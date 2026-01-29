# Messaging House - People

The People defines our target audience with relevant characteristics nad behaviors to align messaging to.

Use this section to ensure precision and resonance. Messaging should only target audiences that meet ICP criteria, then be tailored by segment and persona when applicable.

## Messaging Blocks

### Ideal Customer Profile (ICP)

The ICP criteria defines good fit / bad fit accounts. 

#### Disqualifying Conditions

Non-Technical Products: Companies selling simple SaaS products (e.g., project management, simple CRM) where the UI is the entire value prop and backend logic is irrelevant.

Early Stage / Pre-Product: Startups without a functioning API or defined use cases; Coast amplifies value, it doesn't invent it.

Low Deal Velocity / B2C: High-volume, low-touch transactional sales where a demo is not part of the buying journey (e.g., $10/mo consumer apps).

On-Prem Only / Air-Gapped: Organizations that strictly cannot use cloud-based SaaS tools for any part of their sales motion (though Coast offers on-prem options, "Cloud-hostile" cultures are bad fits).

#### Characteristics

API-First or "API-Heavy": The core product value is delivered via API, SDK, or backend integration (Fintech, DevTools, Infrastructure, Headless Commerce).

Technical Complexity: The product involves "invisible" processes like data enrichment, payments, fraud detection, or identity verification that are hard to visualize.

Complex Buying Committee: Sales involve both business stakeholders (VP/C-Level) and technical evaluators (Developers, Architects, Security).

Enterprise Aspirations: The company is selling (or moving upmarket) to mid-market and enterprise accounts where security, compliance, and "proof" are required.

#### Behaviors

"Demo Lag": Significant delays (days/weeks) between a discovery call and a technical demo due to engineering scheduling.

Engineering Bottlenecks: Sales/SE leaders complaining that engineering resources are being drained by "sales support" tasks like building custom environments.

Low Conversion on Technical Demos: Deals stalling after the demo stage because the prospect "didn't get it" or didn't trust the slide-ware.

Hiring Aggressively for SEs: A rapid ramp-up in Solutions Engineering headcount to cope with demo volume, rather than strategic technical work.

#### Environment

Modern Tech Stack: Utilizes REST/GraphQL APIs, webhooks, and modern auth standards (OAuth/JWT).

Cloud-Native: Comfortable with SaaS tools in their GTM stack (Salesforce, HubSpot, etc.).

Collaborative GTM: Sales, Marketing, and Product teams work closely together on the narrative, but currently use disjointed tools (Figma for design, Postman for API, Slides for story).

#### Maturity

Growth to Late Stage: Typically Series A through Public companies. They have finding Product-Market Fit behind them and are now focused on scaling efficiency and consistency. They have a dedicated Sales or SE team.

### Customer Journey

Awareness
Goal: Frame the "invisibility problem" and make them realize the cost of their current manual/static demo process.

Walk Away Feeling: "I didn't realize how much revenue we're losing because buyers can't see our API value. Slides aren't enough."

Key Messaging: "The API Sales Paradox: The more powerful your product, the harder it is to sell." "Stop asking prospects to imagine."

Best Proof: Industry trends on buyer behavior (technical buyers demanding hands-on access); Analogies to "test driving" a car vs. reading the manual.

2. Consideration
Goal: Differentiate Coast from generic screen-capture tools and validate that a "simulation" is better than a "production build."

Walk Away Feeling: "Coast isn't just a click-through tool; it actually simulates the backend complexity we need to show. This could replace our custom engineering builds."

Key Messaging: "Frontend UX + Backend Logic = The Complete Story." "Mock intelligent responses without writing code." "Enterprise-ready with SOC 2."

Best Proof: Technical capabilities deep-dive (showing webhooks/payloads in action); Comparison charts (Coast vs. Homegrown vs. Static).

3. Evaluation (The Pilot)
Goal: Prove ease of use and time-to-value. Show them how quickly they can build a demo that would have taken engineering weeks.

Walk Away Feeling: "I built this in an afternoon, and it looks exactly like our product. My team can actually use this."

Key Messaging: "Build once, reuse forever." "Personalize for every prospect in seconds."

Best Proof: The "45-day opt-out" trial structure; Case studies of rapid implementation (Lean Tech: 1 week → 1 hour).

4. Decision & Purchase
Goal: De-risk the investment for the executive buyer by highlighting efficiency gains, security, and revenue impact.

Walk Away Feeling: "This is a no-brainer for scaling our sales efficiency and protecting engineering time. The ROI is clear."

Key Messaging: "Shift engineering focus back to product." "Shorten sales cycles by 20%." "Consolidate GTM tools."

Best Proof: ROI Calculator (Engineering hours saved + Deal velocity increased); Enterprise success stories (Galileo, Spreedly).

5. Adoption & Advocacy
Goal: Embed Coast into daily workflows (Sales calls, Marketing sites, Onboarding) and turn users into champions.

Walk Away Feeling: "I can't imagine going back to the old way. This is our standard for how we go to market."

Key Messaging: "Enable self-service buying." "Turn demos into data."

Best Proof: Internal adoption stats (number of demos created/shared); "Wall of Love" quotes from their own team.


### Persona Profiles

Personas are the specific people we aim to speak directly to with our messaging - from executives to practitioners. 

When specific personas are related to your task workflow, extract the respective profile in `/messaging/personas/` for in-depth messaging.

| Persona | File | Description |
| :--- | :--- | :--- |
| **Solutions Engineers (SEs)** | `se-persona.md` | The primary users. They want to stop building "duct-tape" demos, reduce repetitive work, and scale their technical impact. |
| **Product Managers (PMs)** | `pm-persona.md` | Key influencers. They want consistent product storytelling, faster feedback loops, and to ensure the "right" story is told. |
| **Account Executives (AEs)** | `ae-persona.md` | The beneficiaries. They want independence, speed to first value, and tools that help them close deals faster without waiting on SEs. |
| **Executives (CRO/CTO)** | `exec-persona.md` | The budget holders. They care about GTM efficiency, shortening sales cycles, and minimizing engineering distraction. |



### Segment Profiles

Segments define company-level groupings that carry specific considerations beyond what is already covered across the ICP and core messaging elements.

When specific segments are related to your task workflow, extract the respective profile in `/messaging/segments/` for in-depth messaging.

| Segment | File | Description |
| :--- | :--- | :--- |
| **Fintech & Payments** | `fintech-segment.md` | Highly regulated, complex data flows (KYC, AML, ledgers). Trust and security are paramount. |
| **Identity & Fraud** | `identity-segment.md` | "Invisible" value props that require showing risk scores, decision logic, and real-time verification. |
| **Enterprise SaaS** | `enterprise-saas.md` | Large buying committees, strict compliance needs (SOC 2), and requirement for multi-product platform storytelling. |

## Rules

- ICP defines eligibility — if ICP conditions are not met, assume no fit, urgency, or budget
- Validate ICP fit before refining to specific segments and personas
- Do not invent personas or segments beyond those defined

## Guidelines

- Use ICP signals to determine whether urgency is inferred or needs to be established
- Personas influence tone, direction, and value emphasis — not positioning
- Segments should adapt context and emphasis, not redefine value propositions or audience fit
