# Nick Bellistri

Senior PM at HubSpot on Marketing Studio: campaign creation, AI-generated assets, and AI output quality. Previously Orum, Addepar, and John Hancock. 15+ years across B2B SaaS, AI/ML, fintech, and marketing technology.

I build what I spec. Everything below is public and working, and most of it started as something I needed for my own workflow before I packaged it.

---

## Claude Code Skills for Product Managers

A collection of open-source skills for [Claude Code](https://claude.ai/code). Each one handles a specific PM workflow with structured output and no fluff.

Install any skill by copying its folder into `~/.claude/skills/`, then just ask Claude to do the thing.

### AI Quality & Evals

| Skill | What it does |
|---|---|
| [Eval Framework Builder](https://github.com/Bellistri-Nick/ProductManagerEvalFrameworkBuilder) | Turns an AI feature description into a complete eval framework: quality dimensions, a scored rubric with anchors, golden set structure, ship/no-ship thresholds, and an optional automated judge prompt |
| [AI Quality Scorecard](https://github.com/Bellistri-Nick/ProductManagerAIQualityScorecard) | Scores a single AI-generated output against quality criteria, cites the evidence, gives a ship/no-ship verdict, and rewrites the weakest dimension |

### Job Search & Career

| Skill | What it does |
|---|---|
| [Job Scout](https://github.com/Bellistri-Nick/job-scout) | Self-hosted job search agent. Scans public ATS boards and remote job boards on a schedule, scores every posting against your resume, and emails a ranked digest. Unit tested |
| [AI Job Search](https://github.com/Bellistri-Nick/ai-job-search) | *Fork of [MadsLorentzen/ai-job-search](https://github.com/MadsLorentzen/ai-job-search).* End-to-end job search framework built on Claude Code: evaluate postings, tailor CVs, write cover letters, prep interviews |
| [PM Resume Review](https://github.com/Bellistri-Nick/PMResumeReviewer) | Three-panel review (Recruiter, Hiring Manager, CPO) with scores, specific citations, and rewrite offers |
| [LinkedIn Profile Reviewer](https://github.com/Bellistri-Nick/ProductManagerLinkedInReviewer) | Three-panel review (Recruiter, Hiring Manager, Head of Product) that scores each section, quotes weaknesses, and delivers a prioritized rewrite list |
| [Cover Letter Generator](https://github.com/Bellistri-Nick/ProductManagerCoverLetterGenerator) | Voice-matched cover letter from resume + JD, with hiring lens check and targeted revisions |
| [Case Study Builder](https://github.com/Bellistri-Nick/ProductManagerCaseStudyBuilder) | Turns raw project experience into a portfolio-ready case study: full write-up, LinkedIn article version, and interview talking-points outline |
| [Take-Home Case Builder](https://github.com/Bellistri-Nick/ProductManagerTakeHomeCaseStudyBuilder) | Runs a PM take-home end to end, from raw prompt to finished deck, with an adversarial check and every number traced to a primary source |
| [Take-Home Assignment Reviewer](https://github.com/Bellistri-Nick/ProductManagerTakeHomeCaseStudyReviewer) | Reviews PM take-home submissions before you send them: five-dimension scoring, two hiring panel voices, fixes ranked by impact and time-to-fix |

### Product Work

| Skill | What it does |
|---|---|
| [PRD Writer](https://github.com/Bellistri-Nick/ProductManagerPRDWriter) | Writes a PRD from scratch through an adaptive PM intake interview, then drafts against PM best practices. Pairs with PRD Reviewer |
| [PRD Reviewer](https://github.com/Bellistri-Nick/ProductManagerPRDReviewer) | Scored rubric review through Peer PM, Lead PM, and CPO lenses. Supports custom reviewer voices |
| [User Interview Synthesis](https://github.com/Bellistri-Nick/ProductManagerTranscriptAnalysis) | Raw notes → themes, pain points, opportunity areas, frequency counts, JTBD/OST framing |
| [OKR Writer](https://github.com/Bellistri-Nick/ProductManagerOKRWriter) | Generate OKRs from strategy context, or review and rewrite existing ones. Catches task KRs, vanity metrics, and unmeasurable objectives |
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

Restart Claude Code after installing. Each skill auto-triggers from natural language. No slash commands needed.

---
