# GrantPilot — AI Grant Ops Marketplace

**Live app: https://app-limalabs.vercel.app**

GrantPilot pairs small nonprofits, neighborhood associations, and municipal grant teams with vetted human grant specialists augmented by AI to automate the full grant lifecycle.

## The Problem

Organizations spend **200–400 hours/year** on grant *operations* — not strategy, just mechanics:

- Reading 40–80 page RFPs and extracting eligibility, required sections, deadlines
- Drafting 5–12 narrative sections tailored to each funder's language
- Building OMB-compliant budgets with line-item justification
- Populating compliance forms (SF-424, certifications, attachments)
- Tracking submission portals (Grants.gov, Fluxx, eCivis) and renewal timelines

## What GrantPilot Does

| Feature | Description |
|---------|-------------|
| 📋 RFP Parser | Extracts eligibility, scoring rubric, required sections, deadlines from uploaded PDFs |
| ✍️ Narrative Generator | 50+ funder-specific templates (CDBG, SAMHSA, NEH, DOJ, USDA, EPA, AmeriCorps, etc.) |
| 💰 Budget Builder | OMB-compliant line-item budgets with justification narratives |
| ✅ Compliance Tracker | Auto-generated checklists with form-population guidance |
| 🏆 Win Score | Predictive 0–100 score: eligibility match, narrative completeness, budget quality, QA status |
| 👥 Specialist Marketplace | Connect with vetted grant writers for human QA review before submission |

## Tech Stack

- **Frontend**: Next.js 14 App Router, TypeScript, Tailwind CSS
- **Backend**: Supabase (PostgreSQL + Row Level Security + Edge Functions)
- **AI**: OpenAI for RFP parsing, narrative generation, and compliance checking
- **Deployment**: Vercel (edge runtime)

## Business Model

- **Fixed-price packages**: $500 (discovery + first draft), $2,500 (full submission package)
- **Subscription**: $199/month for pipeline management (track 20+ grants, renewal alerts)
- **Specialist marketplace**: 20% platform fee on specialist engagements

## Target Customers

- Small nonprofits (annual budgets $50K–$5M) applying for 5–25 grants/year
- Neighborhood associations applying for CDBG and community foundation grants  
- Municipal economic development teams managing ARPA, EDA, and HUD grants

## Resources

- [Grant Narrative Templates](/resources) — Free NEH, CDBG, SAMHSA templates
- [SF-424 Guide](/resources/sf-424-guide) — Federal form instructions
- [ARPA Checklist](/resources/municipal-arpa-grant-checklist) — Municipal grant compliance
- [Budget Examples](/resources/budget-justification-examples) — Sample budget justifications

## Development

Built with customer discovery insights from 40+ interviews with nonprofit EDs, city grant managers, and grant consultants.

## Links

- 🌐 **Live App**: https://app-limalabs.vercel.app
- 📝 **Sign up free**: https://app-limalabs.vercel.app/signup
- 📚 **Resources**: https://app-limalabs.vercel.app/resources
- 📖 **Docs**: https://app-limalabs.vercel.app/docs
