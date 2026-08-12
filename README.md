# AWS Certified Cloud Practitioner (CLF-C02) — Study Plan

**Exam date:** Friday, Sept 11, 2026
**Training starts:** Thursday, Aug 6, 2026 (34 available study days — Aug 7 and Aug 8 unavailable, Aug 9 missed)
**Resources:** AWS Skill Builder (Individual subscription, $29/mo — see [Subscription options](#subscription-options)) + Pocket Prep app

> **Schedule note:** Fri 8/7 and Sat 8/8 were unavailable; every day after 8/6 shifted later by 2 days to absorb the gap, and 2 of the original 5 rest days (Week 1 and Week 3) were dropped to keep the exam date fixed at 9/11. Sun 8/9's session didn't happen — its content moved to Mon 8/10, and everything through 8/17 shifted one day later to absorb it, dropping the Week 2 rest day (formerly Mon 8/17) to keep the exam date fixed at 9/11. Everything from 8/18 onward is unchanged.

> **Resource note (verified against Skill Builder, Aug 2026):** AWS Cloud Practitioner Essentials was overhauled in June 2025 and now has 13 modules, not the ~4 this plan originally assumed — citations below are remapped to the real module numbers, occasionally out of native course order to match the week's domain. The old "Exam Prep Standard Course" is flagged **[RETIRING]** on Skill Builder as of this writing, so it's dropped as a resource in favor of the Essentials modules directly, which now cover every domain, not just Domain 1.
>
> **Individual subscription** ($29/mo or $449/yr), started Tue 8/11 — this unlocks the Official Practice Exam and the full 200+ lab Builder Labs catalog, both used below where hands-on practice adds real value on top of the Essentials videos. Everything else in the plan (Essentials, Official Pretest, Official Practice Question Set) is free either way. See [Subscription options](#subscription-options).
>
> **Pocket Prep note (verified in-app, Aug 2026):** there is no "Diagnostic Test," "Pre-Assessment," "Flashcards," or dedicated full-exam-simulation feature — none of those exist as distinct modes for this exam, confirmed in-app. Every reference below is remapped to real mode names: **Build Your Own Quiz** (5–100 questions, filterable by domain — used for the domain-quiz, baseline, and full-exam-simulation citations, self-timed with an external clock where a timed simulation matters) and **Weakest Subject Quiz** (used in place of flashcards for rest-day light review). All quiz modes require Pocket Prep Premium; see the pricing note in [Resources](#resources).

## Exam blueprint

| Domain | Weight |
|---|---|
| 1. Cloud Concepts | 24% |
| 2. Security and Compliance | 30% |
| 3. Cloud Technology and Services | 34% |
| 4. Billing, Pricing, and Support | 12% |

## Week 1 — Aug 6, 9–14 — Domain 1: Cloud Concepts

- **Thu 8/6** — Set up: create Skill Builder account, install Pocket Prep, read the CLF-C02 exam guide content outline start to finish. *(Pocket Prep: Build Your Own Quiz — all subjects selected, ~40 Q, untimed, to baseline yourself)*
- **Fri 8/7** — Unavailable.
- **Sat 8/8** — Unavailable.
- **Sun 8/9** — Missed.
- **Mon 8/10** — Intro to the cloud & compute in the cloud. *(Essentials Module 1: Introduction to the Cloud + Module 2: Compute in the Cloud — free)*
- **Tue 8/11** — Global infrastructure: Regions, AZs, edge locations. *(Essentials Module 4: Going Global + whitepaper ["Overview of Amazon Web Services"](https://docs.aws.amazon.com/whitepapers/latest/aws-overview/introduction.html))*
- **Wed 8/12** — Cloud value proposition; first pass on the Well-Architected Framework. *(Essentials Module 13: Well-Architected Solutions — taken out of order to match this week's Domain 1 focus)*
- **Thu 8/13** — Quiz + review every explanation, right or wrong. *(Pocket Prep: Build Your Own Quiz — Domain 1 only, untimed)*
- **Fri 8/14** — Recap: re-read Domain 1 bullets in the exam guide. *(Pocket Prep: Build Your Own Quiz — Domain 1 only, second pass, target ≥80%)*

## Week 2 — Aug 15–21 — Domain 2: Security & Compliance (+ start of Domain 3)

- **Sat 8/15** — Shared Responsibility Model in depth. *(Essentials Module 9: Security — free)*
- **Sun 8/16** — IAM: users, groups, roles, policies, MFA, root account best practices. *(AWS docs: IAM overview + Builder Labs: browse the catalog for an IAM hands-on lab, e.g. creating users/policies)*
- **Mon 8/17** — Security services survey: GuardDuty, Inspector, Macie, Shield, WAF, Security Hub, KMS. *(Essentials Module 9: Security, continued + AWS "What is…" pages)*
- **Tue 8/18** — Compliance programs and AWS Artifact; AWS vs. customer responsibility for GDPR/HIPAA-type frameworks. *(Essentials Module 10: Monitoring, Compliance, and Governance — compliance section)*
- **Wed 8/19** — Quiz + review every explanation. *(Pocket Prep: Build Your Own Quiz — Domain 2 only, untimed)*
- **Thu 8/20** — Recap Domain 2 against the exam guide bullets. *(Pocket Prep: Build Your Own Quiz — Domain 2 only, second pass, target ≥80%)*
- **Fri 8/21** — Compute: EC2 instance families, Lambda, Elastic Beanstalk, containers at a glance (ECS/EKS/Fargate). *(Essentials Module 3: Exploring Compute Services + Builder Lab: "Introduction to Amazon EC2")*

## Week 3 — Aug 22–28 — Domain 3: Compute, Storage, Networking & Management

- **Sat 8/22** — Storage: S3 storage classes, EBS vs. EFS, Storage Gateway, Snow Family (conceptual). *(Essentials Module 6: Storage + Builder Lab: "Introduction to Amazon S3")*
- **Sun 8/23** — Networking: VPC, subnets, internet/NAT gateways, Route 53, CloudFront, Direct Connect. *(Essentials Module 5: Networking + Builder Lab: "Introduction to Amazon VPC")*
- **Mon 8/24** — Databases: RDS, Aurora, DynamoDB, Redshift — relational vs. NoSQL vs. warehouse, conceptually. *(Essentials Module 7: Databases + Builder Labs: browse the catalog for a DynamoDB or RDS hands-on lab)*
- **Tue 8/25** — Quiz on compute/storage/network/database subset. *(Pocket Prep: Build Your Own Quiz — Domain 3 only, untimed)*
- **Wed 8/26** — Recap the week; re-skim any service overview page that still feels unfamiliar.
- **Thu 8/27** — Management & monitoring: CloudWatch, CloudTrail, AWS Config, Trusted Advisor, Systems Manager. *(Essentials Module 10: Monitoring, Compliance, and Governance — monitoring section)*
- **Fri 8/28** — Migration & deployment: CloudFormation, Snow Family, DMS, Organizations; light pass on ML/analytics awareness. *(Essentials Module 12: Migrating to the AWS Cloud + Module 8: AI/ML and Data Analytics — free)*

## Week 4 — Aug 29–Sep 4 — Domain 4: Billing, Pricing & Support (+ start of full review)

- **Sat 8/29** — Pricing models: On-Demand vs. Reserved vs. Spot vs. Savings Plans. Build one estimate hands-on. *(Essentials Module 11: Pricing and Support + AWS Pricing Calculator — free)*
- **Sun 8/30** — Rest day, light review only. *(Pocket Prep: Weakest Subject Quiz — Domain 4 focus)*
- **Mon 8/31** — Support plans (Basic/Developer/Business/Enterprise); billing tools: Cost Explorer, Budgets, Consolidated Billing. *(Essentials Module 11: Pricing and Support, continued + whitepaper ["How AWS Pricing Works"](https://docs.aws.amazon.com/whitepapers/latest/how-aws-pricing-works/introduction.html))*
- **Tue 9/1** — Quiz on remaining Domain 3 topics + Domain 4 quiz. *(Pocket Prep: Build Your Own Quiz — Domains 3 & 4, untimed)*
- **Wed 9/2** — Recap Domains 3 & 4 against the exam guide bullets.
- **Thu 9/3** — Take the official free practice set, then review every question. *(Skill Builder: Official Practice Question Set, 20 Q, free)*
- **Fri 9/4** — First full-length timed exam simulation; review every miss in detail. *(Pocket Prep: Build Your Own Quiz — all domains, 65 Q to match the real exam, self-timed to 90 min with an external clock — there's no dedicated exam-simulation mode)*

## Week 5 — Sep 5–11 — Full review, practice exams & exam day

- **Sat 9/5** — Targeted re-study of the 1–2 weakest domains from Friday's exam.
- **Sun 9/6** — Rest day, light review only. *(Pocket Prep: Weakest Subject Quiz)*
- **Mon 9/7** — Second full-length timed exam; compare score trend against last Friday. *(Pocket Prep: Build Your Own Quiz — all domains, 65 Q, self-timed to 90 min)*
- **Tue 9/8** — Closest simulation to the real thing — treat it like exam day. *(Skill Builder: Official Practice Exam, 50 Q, timed — included with your Individual subscription)*
- **Wed 9/9** — Review every miss; re-skim the Well-Architected Framework's 6 pillars and the shared-responsibility diagram. *(Essentials Module 13: Well-Architected Solutions, re-watch — free)*
- **Thu 9/10** — Light review only, no new material. Weakest Subject Quiz (Pocket Prep) on your weakest domain, one top-to-bottom skim of the exam guide outline. Confirm exam logistics. Sleep early.
- **Fri 9/11 — EXAM DAY** — Check in (or complete online proctoring check-in) 30 minutes early. No new material — trust the prep.

## Resources

**Official AWS**
- AWS Cloud Practitioner Essentials — Skill Builder, free, self-paced, 13 modules (Introduction to the Cloud, Compute in the Cloud, Exploring Compute Services, Going Global, Networking, Storage, Databases, AI/ML and Data Analytics, Security, Monitoring/Compliance/Governance, Pricing and Support, Migrating to the AWS Cloud, Well-Architected Solutions) — covers all 4 exam domains, not just Domain 1; this plan pulls modules out of native order to match each week's domain focus
- Official Pretest — Skill Builder, free — used Day 1 to baseline each domain
- CLF-C02 Exam Guide (PDF) — content outline & domain weightings
- Official Practice Question Set — Skill Builder, free, 20 questions
- Official Practice Exam — Skill Builder, 50 questions, timed — included with the Individual subscription
- AWS Builder Labs — Skill Builder, 200+ hands-on sandboxed labs with Individual subscription (10 foundational labs, incl. EC2/S3/VPC intros, are free even without one); used on Compute, Storage, Networking, Database, and IAM days above for hands-on reinforcement
- Whitepapers: [*Overview of Amazon Web Services*](https://docs.aws.amazon.com/whitepapers/latest/aws-overview/introduction.html), [*AWS Well-Architected Framework*](https://docs.aws.amazon.com/wellarchitected/latest/framework/welcome.html) (the standalone PDF is archived — this is now living documentation, updated continuously rather than versioned), [*How AWS Pricing Works*](https://docs.aws.amazon.com/whitepapers/latest/how-aws-pricing-works/introduction.html)
- AWS Pricing Calculator — hands-on tool, free

> The old "Exam Prep Standard Course: AWS Certified Cloud Practitioner (CLF-C02)" is marked **[RETIRING]** on Skill Builder as of Aug 2026 and is intentionally not used above — the Essentials modules now cover the same ground and are more likely to stay current.

### Subscription options

Verified against [skillbuilder.aws/subscriptions](https://skillbuilder.aws/subscriptions) and AWS's training FAQ, Aug 2026:

| Tier | Price | Includes |
|---|---|---|
| **Free** | $0 | 500+ on-demand courses, incl. the full Cloud Practitioner Essentials (all 13 modules), Official Pretest, Official Practice Question Set (20 Q), 10 foundational Builder Labs |
| **Individual** ✅ *(this plan)* | $29/month or $449/year | Everything in Free, plus practice exams for select certifications (incl. the CLF-C02 Official Practice Exam), the full 200+ lab Builder Labs catalog, AWS Cloud Quest, AWS Jam |
| **Team** | $449/seat/year, 5-seat minimum | Same content as Individual, plus team management, progress reporting, and SSO — not relevant for solo study |

Individual subscription started **Tue 8/11**, running through exam day (Aug 11 – Sep 11, ~4.5 weeks). At $29/mo that's about $29–58 depending on billing timing, well under the $449 annual rate — cancel after exam day unless you plan to keep using Skill Builder. The subscription is what unlocks the Official Practice Exam (Tue 9/8) and the Builder Labs used on the Storage/Networking/Database/IAM days above (the earlier IAM survey on 8/16 falls after the subscription start, so no gap in coverage); everything else in the plan is free regardless of tier.

**Pocket Prep** — verified modes, Aug 2026 (all require Premium; a 30-question free trial is available otherwise): Question of the Day, Quick 10 Quiz, Timed Quiz (5/10 min), Level Up Quiz, Weakest Subject Quiz, Missed Questions Quiz, Build Your Own Quiz (5–100 Q, filterable by domain). There is no flashcards feature and no dedicated full-exam-simulation mode for this exam — both confirmed in-app.
- Build Your Own Quiz, filtered to one domain — untimed, Weeks 1–4
- Weakest Subject Quiz — rest-day light review (replaces the flashcards this plan originally assumed)
- Build Your Own Quiz, all domains, 65 Q, self-timed to 90 min with an external clock — Week 5 exam simulations (replaces the "full-length mock exam" this plan originally assumed existed as a distinct mode)
- Missed Questions Quiz — after every quiz and exam, read the explanation even on correct answers

**Pocket Prep Premium pricing:** $20.99/month ✅ *(this plan)*, $49.99/3 months (~$16.99/mo), or $124.99/year (~$10.99/mo). On the monthly plan — remember to cancel after exam day, since a 5-week window is ~2 billing cycles (~$42 total) rather than committing to the 3-month rate.

## Progress log

| Date | Item | Result |
|---|---|---|
| Mon 8/10 | Essentials Module 1: Introduction to the Cloud — knowledge check | 88% ✅ |
| Tue 8/11 | Essentials Module 2: Compute in the Cloud — knowledge check | 93% ✅ |
| Tue 8/11 (afternoon) | Individual subscription started | ✅ |
| Tue 8/11 | Pocket Prep Premium started (monthly plan, $20.99/mo) | ✅ |
| Tue 8/11 | Essentials Module 4: Going Global — knowledge check | 83% ✅ |
| Tue 8/11 | Whitepaper "Overview of Amazon Web Services" — read | ✅ |
| Wed 8/12 | Essentials Module 13: Well-Architected Solutions — knowledge check | 100% ✅ |

## Exam-day checklist

- [ ] Confirmation email reviewed — registered exam is CLF-C02
- [ ] Government-issued photo ID name matches registration exactly
- [ ] Testing center address confirmed, or online proctoring system check completed
- [ ] Plan to arrive / check in 30 minutes before the scheduled start
- [ ] Phone, smartwatch, and notes stowed away — not on the desk or in the room
