# Controlled Chaos Agent Map

## Repo structure inspected
Agents are organized as top-level divisions, with each agent stored as a Markdown file with frontmatter. The source-of-truth divisions are: academic, design, engineering, finance, game-development, gis, marketing, paid-media, product, project-management, sales, security, spatial-computing, specialized, support, and testing.

## Task-to-agent map
| Controlled Chaos task | Primary agent | Supporting agents |
|---|---|---|
| TikTok/Reels/Shorts content | `marketing/marketing-tiktok-strategist.md` | `marketing/marketing-content-creator.md`, `marketing/marketing-video-optimization-specialist.md`, `marketing/marketing-short-video-editing-coach.md` |
| Paid ad creative | `paid-media/paid-media-creative-strategist.md` | `paid-media/paid-media-paid-social-strategist.md`, `paid-media/paid-media-auditor.md`, `paid-media/paid-media-tracking-specialist.md` |
| Short-form editing | `marketing/marketing-short-video-editing-coach.md` | `marketing/marketing-video-optimization-specialist.md`, `design/design-visual-storyteller.md` |
| Organic social growth | `marketing/marketing-social-media-strategist.md` | `marketing/marketing-growth-hacker.md`, `marketing/marketing-instagram-curator.md` |
| Brand strategy | `design/design-brand-guardian.md` | `design/design-visual-storyteller.md`, `marketing/marketing-content-creator.md` |
| Product marketing | `product/product-manager.md` | `product/product-feedback-synthesizer.md`, `product/product-trend-researcher.md`, `product/product-behavioral-nudge-engine.md` |
| Website conversion | `design/design-ux-architect.md` | `design/design-ui-designer.md`, `marketing/marketing-content-creator.md`, `product/product-behavioral-nudge-engine.md` |
| Sales/outreach | `sales/sales-outbound-strategist.md` | `specialized/sales-outreach.md`, `sales/sales-offer-lead-gen-strategist.md` |
| Influencer outreach | `marketing/marketing-tiktok-strategist.md` | `marketing/marketing-social-media-strategist.md`, `sales/sales-outbound-strategist.md` |
| Customer support | `support/support-support-responder.md` | `specialized/customer-success-manager.md`, `specialized/retail-customer-returns.md`, `support/support-legal-compliance-checker.md` |
| Operations/SOPs | `specialized/operations-manager.md` | `project-management/project-management-studio-operations.md`, `project-management/project-management-project-shepherd.md`, `testing/testing-workflow-optimizer.md` |
| Product research | `product/product-trend-researcher.md` | `product/product-feedback-synthesizer.md`, `design/design-ux-researcher.md` |
| Coding/development | `engineering/engineering-frontend-developer.md` | `engineering/engineering-backend-architect.md`, `engineering/engineering-software-architect.md`, `engineering/engineering-ai-engineer.md`, `engineering/engineering-prompt-engineer.md` |
| QA/testing | `testing/testing-reality-checker.md` | `engineering/engineering-code-reviewer.md`, `testing/testing-api-tester.md`, `testing/testing-evidence-collector.md`, `security/security-appsec-engineer.md` |
| Business strategy | `specialized/business-strategist.md` | `specialized/specialized-chief-of-staff.md`, `project-management/project-manager-senior.md`, `specialized/specialized-pricing-analyst.md`, `finance/finance-fpa-analyst.md` |

## Agent teams
### Marketing Ad Team
- TikTok/Reels/Shorts strategist: `marketing/marketing-tiktok-strategist.md`
- Paid media creative strategist: `paid-media/paid-media-creative-strategist.md`
- Short-form video/editing expert: `marketing/marketing-short-video-editing-coach.md`
- Content creator/copywriter: `marketing/marketing-content-creator.md`
- Brand strategist: `design/design-brand-guardian.md`
- Reality checker: `testing/testing-reality-checker.md`

### Website Conversion Team
- Conversion copywriter: `marketing/marketing-content-creator.md`
- UX/design strategist: `design/design-ux-architect.md`
- Product marketer: `product/product-manager.md`
- Brand strategist: `design/design-brand-guardian.md`
- Reality checker: `testing/testing-reality-checker.md`

### Outreach Team
- Sales strategist: `sales/sales-outbound-strategist.md`
- Growth marketer: `marketing/marketing-growth-hacker.md`
- Copywriter: `marketing/marketing-content-creator.md`
- Brand strategist: `design/design-brand-guardian.md`

### Operations Team
- Operations manager: `specialized/operations-manager.md`
- QA/checklist agent: `testing/testing-workflow-optimizer.md`
- Customer support agent: `specialized/customer-service.md`
- Process improvement agent: `project-management/project-management-studio-operations.md`

### Coding/System Team
- Frontend developer: `engineering/engineering-frontend-developer.md`
- Backend architect: `engineering/engineering-backend-architect.md`
- QA/testing agent: `testing/testing-api-tester.md`
- Security/reliability reviewer: `security/security-appsec-engineer.md` and `engineering/engineering-sre.md`


## Audit notes on fit
- Strong fits: TikTok, paid creative, short-form editing, brand guardian, UX architect, outbound sales, operations manager, reality checker, and frontend/backend engineering agents map cleanly to Controlled Chaos needs.
- Replacements made after audit: paid media should include `paid-media/paid-media-tracking-specialist.md` for pixels/UTMs/creative measurement; operations should include `project-management/project-management-project-shepherd.md` for owner/date/status follow-through; QA should include `testing/testing-evidence-collector.md` so claims and decisions are traceable.
- Watchlist weak fits: `specialized/customer-service.md` is broad, so pair it with `support/support-support-responder.md` and `support/support-legal-compliance-checker.md` for supplement-support caution; `product/product-manager.md` is broad, so pair it with `product/product-feedback-synthesizer.md` and real customer quiz feedback.
- Missed but useful later: `specialized/data-privacy-officer.md` for quiz/customer data handling, `security/security-architect.md` for future app architecture, `finance/finance-bookkeeper-controller.md` for margins/bookkeeping, and `marketing/marketing-email-strategist.md` for post-purchase flows.
