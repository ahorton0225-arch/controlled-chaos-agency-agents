# Controlled Chaos Full Agent Capability Map

This map treats the repo as an agency bench, not a single prompt library. Use only the agents needed for the current stage. For video ideas, most agents should inform, attack, or approve ideas rather than generate finished scripts.

## Division-by-division capability map

| Division | What the division is good for | Helps Controlled Chaos now | Helps later | Avoid for video ideas | Reviewer-only use |
|---|---|---|---|---|---|
| `academic/` | Human behavior, culture, narrative, history, geography. | `academic/academic-psychologist.md` for motivation/identity; `academic/academic-narratologist.md` for story tension; `academic/academic-anthropologist.md` for gym culture rituals. | `academic/academic-historian.md`, `academic/academic-geographer.md` for deeper market/culture research. | Do not use as primary TikTok generators; they can over-intellectualize. | Use psychology/narrative agents to challenge shallow audience insight. |
| `design/` | Brand, UX, visual storytelling, personas, UI, inclusive visuals. | `design/design-brand-guardian.md`, `design/design-visual-storyteller.md`, `design/design-persona-walkthrough.md`, `design/design-ux-researcher.md`. | `design/design-ui-designer.md`, `design/design-ux-architect.md`, `design/design-image-prompt-engineer.md` for website/app assets. | Avoid UI/image agents for raw video ideas unless the task is visual design. | Brand guardian should review tone, cringe risk, and visual fit. |
| `engineering/` | Software, architecture, AI systems, prompts, review, reliability. | `engineering/engineering-prompt-engineer.md` for council prompts; `engineering/engineering-code-reviewer.md` as structured QA reviewer. | `engineering/engineering-frontend-developer.md`, `engineering/engineering-backend-architect.md`, `engineering/engineering-software-architect.md`, `engineering/engineering-ai-engineer.md`, `engineering/engineering-sre.md`. | Avoid as creative generators; they will make content too systems-like. | Use for future tool/workflow reliability and Replit planning. |
| `finance/` | Margins, FP&A, bookkeeping, tax, investment analysis. | `finance/finance-fpa-analyst.md` when judging sales potential and margin-sensitive offers. | `finance/finance-bookkeeper-controller.md`, `finance/finance-financial-analyst.md`, `finance/finance-tax-strategist.md`. | Avoid for creative ideation. | Review discount/offer economics only. |
| `game-development/` | Game mechanics, levels, narratives, audiovisual systems. | `game-development/game-designer.md`, `game-development/narrative-designer.md`, `game-development/level-designer.md` for loadout screens, challenges, game-show mechanics, character constraints. | Engine-specific agents later if building interactive demos. | Avoid engine-specific agents for normal videos. | Use game designer to make formats more playable/commentable. |
| `gis/` | Geographic/spatial analysis. | Usually not needed for video ideas. | Local gym outreach, campus clustering, territory mapping. | Avoid for video idea generation. | Reviewer only for local expansion strategy. |
| `marketing/` | Social, TikTok, content, SEO, growth, community, video optimization. | `marketing/marketing-tiktok-strategist.md`, `marketing/marketing-content-creator.md`, `marketing/marketing-short-video-editing-coach.md`, `marketing/marketing-video-optimization-specialist.md`, `marketing/marketing-social-media-strategist.md`, `marketing/marketing-growth-hacker.md`, `marketing/marketing-instagram-curator.md`, `marketing/marketing-reddit-community-builder.md`. | `marketing/marketing-email-strategist.md`, `marketing/marketing-seo-specialist.md`, `marketing/marketing-pr-communications-manager.md`, `marketing/marketing-agentic-search-optimizer.md`. | Avoid platform agents for irrelevant markets unless expanding there. | TikTok/content fight for attention; video optimization fights for pacing. |
| `paid-media/` | Paid social, creative testing, PPC, tracking, audits. | `paid-media/paid-media-creative-strategist.md`, `paid-media/paid-media-paid-social-strategist.md`, `paid-media/paid-media-auditor.md`, `paid-media/paid-media-tracking-specialist.md`. | `paid-media/paid-media-ppc-strategist.md`, `paid-media/paid-media-search-query-analyst.md`, `paid-media/paid-media-programmatic-buyer.md`. | Avoid as sole creative source; can make content too ad-like. | Review conversion, offer clarity, thumb-stop, and testability. |
| `product/` | Product management, research, feedback, behavior. | `product/product-feedback-synthesizer.md`, `product/product-trend-researcher.md`, `product/product-behavioral-nudge-engine.md`, `product/product-manager.md`. | Product roadmap, quiz refinement, reorder flows, personalization logic. | Avoid if it turns videos into feature lectures. | Review whether idea makes the product truth understandable. |
| `project-management/` | Planning, experiments, status, production operations. | `project-management/project-management-experiment-tracker.md`, `project-management/project-management-project-shepherd.md`, `project-management/project-management-studio-producer.md`, `project-management/project-manager-senior.md`. | Dashboards, calendars, production sprints. | Avoid for creative generation. | Use after winners are selected to create queue/status. |
| `sales/` | Outbound, offers, discovery, pipeline, account strategy. | `sales/sales-outbound-strategist.md`, `sales/sales-offer-lead-gen-strategist.md`, `sales/sales-discovery-coach.md`, `sales/sales-coach.md`. | Gym partnerships, influencer deals, B2B campus/gym outreach. | Avoid as pure TikTok idea generator. | Review conversion reason and outreach variants. |
| `security/` | Security architecture, compliance, incidents, appsec. | `security/security-compliance-auditor.md`, `security/security-appsec-engineer.md` for risk review if claims/data/security are involved. | `security/security-architect.md`, `security/security-cloud-security-architect.md`, `security/security-incident-responder.md`. | Avoid for creative generation. | Review customer-data and future app risk. |
| `spatial-computing/` | XR, immersive interfaces, spatial UX. | Not needed for current phone videos. | Future AR/interactive gym experiences. | Avoid for current video ideas. | Reviewer only for future immersive concepts. |
| `specialized/` | Cross-functional business, operations, compliance-adjacent, support, workflow, privacy. | `specialized/business-strategist.md`, `specialized/customer-success-manager.md`, `specialized/customer-service.md`, `specialized/operations-manager.md`, `specialized/specialized-workflow-architect.md`, `specialized/specialized-strategy-duel-agent.md`, `specialized/data-privacy-officer.md`, `specialized/healthcare-marketing-compliance.md`, `specialized/sales-outreach.md`. | `specialized/chief-financial-officer.md`, `specialized/supply-chain-strategist.md`, `specialized/specialized-pricing-analyst.md`. | Avoid broad specialized agents as first-pass creative generators. | Use strategy duel, workflow architect, privacy/compliance as reviewers. |
| `support/` | Support responses, legal checks, analytics, summaries, infrastructure, finance tracking. | `support/support-support-responder.md`, `support/support-legal-compliance-checker.md`, `support/support-analytics-reporter.md`, `support/support-executive-summary-generator.md`. | Support desk, refund/replacement workflows, reporting. | Avoid support agents for raw creative. | Review customer trust, claims, support burden, and reporting. |
| `testing/` | Reality checks, evidence, performance, accessibility, workflow tests. | `testing/testing-reality-checker.md`, `testing/testing-evidence-collector.md`, `testing/testing-workflow-optimizer.md`, `testing/testing-test-results-analyzer.md`, `testing/testing-accessibility-auditor.md`. | API/performance testing later. | Avoid as idea generators. | Must kill weak, generic, risky, or unfilmable ideas. |

## Role groups for the video council

### 1. Customer Insight Agents
- `academic/academic-psychologist.md` — motivation, identity, hidden frustration.
- `academic/academic-anthropologist.md` — gym rituals, status, subculture behavior.
- `design/design-persona-walkthrough.md` — viewer empathy and scenario walkthroughs.
- `design/design-ux-researcher.md` — objections, decision friction, qualitative questions.
- `product/product-feedback-synthesizer.md` — review/comment synthesis.
- `product/product-trend-researcher.md` — category trends and buyer behavior.
- `sales/sales-discovery-coach.md` — objection discovery and buyer language.

### 2. Creative Strategy Agents
- `marketing/marketing-tiktok-strategist.md` — platform-native attention and culture.
- `marketing/marketing-content-creator.md` — hooks, captions, creator voice.
- `marketing/marketing-social-media-strategist.md` — cross-platform positioning.
- `marketing/marketing-growth-hacker.md` — loops, challenges, comment engines.
- `paid-media/paid-media-creative-strategist.md` — creative hypotheses and paid angles.
- `paid-media/paid-media-paid-social-strategist.md` — paid social fit.

### 3. Entertainment/Format Agents
- `game-development/game-designer.md` — game mechanics, rules, choices, scoring.
- `game-development/narrative-designer.md` — character, conflict, premise, payoff.
- `design/design-visual-storyteller.md` — visual metaphors and first-frame scenes.
- `marketing/marketing-tiktok-strategist.md` — trend-native format adaptation.
- `marketing/marketing-reddit-community-builder.md` — argument/comment-bait instincts.

### 4. Production Agents
- `marketing/marketing-short-video-editing-coach.md` — pacing, cuts, subtitles, filming sequence.
- `marketing/marketing-video-optimization-specialist.md` — retention, first frame, rewatch loops.
- `project-management/project-management-studio-producer.md` — shoot planning and asset readiness.
- `design/design-visual-storyteller.md` — frames, props, visual clarity.

### 5. Conversion/Sales Agents
- `paid-media/paid-media-creative-strategist.md` — ad conversion logic.
- `sales/sales-offer-lead-gen-strategist.md` — reason to act and offer angle.
- `sales/sales-discovery-coach.md` — objection handling.
- `product/product-behavioral-nudge-engine.md` — CTA, quiz clicks, behavior triggers.
- `product/product-manager.md` — product clarity and feature-to-benefit translation.

### 6. Brand/Trust Agents
- `design/design-brand-guardian.md` — Controlled Chaos voice, look, and cringe filter.
- `support/support-support-responder.md` — trust-building customer language.
- `specialized/customer-success-manager.md` — post-purchase reality and customer tone.
- `marketing/marketing-content-creator.md` — natural, non-corporate script style.

### 7. Compliance/Risk Agents
- `support/support-legal-compliance-checker.md` — claim and legal risk review.
- `specialized/healthcare-marketing-compliance.md` — health/supplement-adjacent caution.
- `specialized/data-privacy-officer.md` — quiz/customer data risk.
- `security/security-compliance-auditor.md` — future app and process compliance.
- `testing/testing-evidence-collector.md` — substantiation trail.

### 8. Reality/QA Agents
- `testing/testing-reality-checker.md` — kill generic, weak, unfilmable, or risky ideas.
- `testing/testing-workflow-optimizer.md` — improve process quality.
- `testing/testing-test-results-analyzer.md` — evaluate test outcomes.
- `paid-media/paid-media-auditor.md` — creative fatigue and conversion sanity.

### 9. Operations/Execution Agents
- `project-management/project-management-experiment-tracker.md` — idea tests and learnings.
- `project-management/project-management-project-shepherd.md` — owners, dates, status.
- `project-management/project-management-studio-producer.md` — filming queue.
- `specialized/operations-manager.md` — SOPs and repeatability.
- `support/support-analytics-reporter.md` — reporting and summaries.

### 10. Future Company Agents
- Website/app: `engineering/engineering-frontend-developer.md`, `engineering/engineering-backend-architect.md`, `engineering/engineering-software-architect.md`, `engineering/engineering-ai-engineer.md`, `engineering/engineering-sre.md`, `security/security-architect.md`.
- Website conversion: `design/design-ux-architect.md`, `design/design-ui-designer.md`, `marketing/marketing-seo-specialist.md`, `marketing/marketing-agentic-search-optimizer.md`.
- Support/ops: `specialized/customer-service.md`, `specialized/retail-customer-returns.md`, `specialized/supply-chain-strategist.md`, `support/support-finance-tracker.md`.
- Finance/business: `finance/finance-fpa-analyst.md`, `finance/finance-bookkeeper-controller.md`, `specialized/chief-financial-officer.md`, `specialized/specialized-pricing-analyst.md`, `specialized/business-strategist.md`.
