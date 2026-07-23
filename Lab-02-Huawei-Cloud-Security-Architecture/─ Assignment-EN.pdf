What you'll learn
Writing under a real constraint — a real customer, a real regulation, a real word count — is the fastest way to consolidate everything you've learned across both sessions. This task asks you to write the article a consultant would deliver at the end of a Huawei Cloud security assessment, with a real architecture, a real risk register, and real recommendations.


The brief
Fictional customer — "PayCarry Türkiye"
PayCarry is a Series-B fintech in Türkiye, processing 15,000 transactions per day for small merchants. They are 18 months from PCI DSS Level 1 certification renewal and currently host on a competitor cloud. They are seriously evaluating a migration to Huawei Cloud (TR-Istanbul) and want a written architecture that addresses two CEO-level concerns: (1) "How do we get to zero CVEs in production?" and (2) "How do we generate audit evidence continuously, instead of scrambling once a year?" The CEO is technical but not a security specialist.


What to write
Produce a 1,500-2,000 word article with the following six sections. Word counts are guides, not absolutes.
Section 1 — Executive Summary (~150 words)
Three short paragraphs:
•	The problem PayCarry is trying to solve, in one sentence.
•	Your headline recommendation — the architecture or workflow change you'd lead with.
•	What "good" looks like 90 days after the work starts.
Section 2 — Architecture Overview (~400 words)
Describe the proposed Huawei Cloud architecture across four layers. Include a diagram (hand-drawn scan, draw.io, or a clear ASCII sketch is fine).
•	Dev layer: CodeArts Repo, CodeArts Inspector (SAST + SCA + IaC), pre-commit policies.
•	Build/test layer: CodeArts Pipeline gates, signed artifacts in SWHR, DAST in staging.
•	Runtime layer: ECS hosts behind ELB, protected by HSS Enterprise; KMS-managed keys; WAF in front.
•	Governance layer: SecMaster with the PCI DSS compliance pack, CTS for audit, LTS for telemetry, Compliance Center for evidence export.
Section 3 — How we get to "zero CVEs in production" (~400 words)
Explain the shift-left + runtime defense-in-depth approach. Cover at minimum:
•	Why catching a CVE in CodeArts Inspector is 100x cheaper than in production (reference the cost curve from Session 2).
•	How HSS's one-click fix works, and what the runtime safety net (snapshot-before-fix) gives you.
•	Honest caveat: "zero CVEs" is a goal, not a guarantee — explain emergency vulnerabilities (Log4Shell-class) and the 48-hour HSS update window.
Section 4 — How we get continuous PCI DSS evidence (~400 words)
Walk through:
•	Subscribing to SecMaster's PCI DSS compliance pack; auto-scan cadence and what it covers automatically vs. manually.
•	One concrete example — pick PCI DSS Requirement 1 (firewall) OR Requirement 8 (identify and authenticate users) — and show how Huawei Cloud services map directly to clauses in that requirement.
•	How Compliance Center makes auditor evidence collection a download rather than a project.
•	Honest caveat: which PCI clauses still require manual attestation that no cloud can automate (policies, training, etc.).
Section 5 — Risk Register (~200 words + a table)
Identify the top five risks of this architecture. For each, score Probability (Low/Med/High) and Impact (Low/Med/High), and describe the mitigation. Format as a table. Examples of legitimate risks to consider:
•	Talent pool — fewer engineers with Huawei Cloud experience in Türkiye than AWS.
•	Regional service parity — not every SecMaster feature is in TR-Istanbul on day one.
•	Migration timing — PCI re-cert window vs. cloud migration timeline.
•	Geopolitical procurement review — some partners may require their own assessment.
•	Lock-in to Huawei-specific tools (CodeArts Inspector) — what's the exit story?
Section 6 — Next 90 Days (~150 words + a checklist)
Provide a week-by-week plan for the first 90 days. Include at least:
•	Week 1-2: account setup, IAM, network landing zone.
•	Week 3-6: pilot workload migration with HSS + SecMaster baseline turned on.
•	Week 7-10: full CodeArts pipeline with Inspector gates wired in.
•	Week 11-13: PCI DSS compliance pack subscribed, first scan, gap remediation, mock audit.
Style guide for the article
•	Audience: PayCarry's CEO and CTO. Technical but not security specialists.
•	Voice: Confident, plain English, no marketing fluff. Imagine you're being paid €25,000 for this document — write to that standard.
•	Citations: Reference specific Huawei Cloud docs URLs at least 6 times across the article.
•	Honesty: Include at least two honest trade-offs or caveats — a CEO who can't see weaknesses won't trust the document.
•	Length: 1,500-2,000 words, plus the diagram and the risk register table. Excess length is penalized.
Deliverables
•	The article itself (Word or PDF), 1,500-2,000 words, formatted with clear section headings.
•	An architecture diagram (any format — hand-drawn photo, draw.io, even ASCII art) embedded in or attached to the article.
•	A risk register table with 5 rows, each containing risk + probability + impact + mitigation.
•	A sources list with at least 8 URLs from Huawei Cloud docs, PCI Security Standards Council, or independent analyst sources.
Stretch goal (optional)
Record a 5-minute video walking the CEO through your article — as if you were presenting it on a call. The constraint of explaining your own architecture out loud is brutal but instructive.
Self-evaluation question
Once you've finished, read the article cold the next morning and ask yourself: "If I were the PayCarry CEO, would this document make me sign the migration contract?" If the answer is "maybe," rewrite the executive summary.
