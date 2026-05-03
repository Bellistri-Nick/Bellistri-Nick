# Nick Bellistri — Product Manager

Senior PM at HubSpot working on Marketing Studio — campaign creation, AI-generated assets, and AI output quality. Previously at Orum, Addepar, and John Hancock.

15+ years building B2B SaaS products across AI/ML, fintech, and marketing technology.

---

## Claude Code Skills for Product Managers

A collection of open-source skills for [Claude Code](https://claude.ai/code) — each one handles a specific PM workflow with structured output and no fluff.

Install any skill by copying its folder into `~/.claude/skills/`, then just ask Claude to do the thing.

| Skill | What it does |
|---|---|
| [PM Resume Review](https://github.com/Bellistri-Nick/PMResumeReviewer) | Three-panel review (Recruiter, Hiring Manager, CPO) with scores, specific citations, and rewrite offers |
| [PRD Reviewer](https://github.com/Bellistri-Nick/ProductManagerPRDReviewer) | Scored rubric review through Peer PM, Lead PM, and CPO lenses — supports custom reviewer voices |
| [Cover Letter Generator](https://github.com/Bellistri-Nick/ProductManagerCoverLetterGenerator) | Voice-matched cover letter from resume + JD, with hiring lens check and targeted revisions |
| [User Interview Synthesis](https://github.com/Bellistri-Nick/ProductManagerTranscriptAnalysis) | Raw notes → themes, pain points, opportunity areas, frequency counts, JTBD/OST framing |
| [OKR Writer](https://github.com/Bellistri-Nick/ProductManagerOKRWriter) | Generate OKRs from strategy context, or review and rewrite existing ones — catches task KRs, vanity metrics, and unmeasurable objectives |
| [Competitive Teardown](https://github.com/Bellistri-Nick/ProductManagerCompetitiveAnalysis) | G2 reviews + website copy → capabilities analysis, customer sentiment, gap analysis, strategic implications |

### Quick install (macOS / Linux)

```bash
git clone https://github.com/Bellistri-Nick/<repo-name>
cp -r <repo-name> ~/.claude/skills/<skill-name>
```

### Quick install (Windows)

```powershell
git clone https://github.com/Bellistri-Nick/<repo-name>
Copy-Item -Recurse <repo-name> "$env:USERPROFILE\.claude\skills\<skill-name>"
```

Restart Claude Code after installing. Each skill auto-triggers from natural language — no slash commands needed.

---

Built with [Claude Code](https://claude.ai/code).
