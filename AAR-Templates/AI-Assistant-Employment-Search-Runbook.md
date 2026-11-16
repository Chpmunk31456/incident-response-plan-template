# AI Assistant Employment-Search Runbook (AAR Control)
Version: 2026-11-16
Classification: Public process controls only. Do not put identifiable applicant or confidential records in this public repository.

## Objective
Find genuinely NEW, employer-verified roles that meet the candidate's actual qualifications and work-authorization constraints. Prevent repeats and false "verified" labels.

## Mandatory PRE-SEARCH sequence (fail closed)
1. Read current instructions and conversation context.
2. Retrieve THIS GitHub AAR Master Memory Index, Decision Register, Memory and Error Register, Context Recovery Procedure, and Verification Checklist. If inaccessible, report an AAR coverage gap.
3. Search available long-term memory/Engram and current application trackers, previous chat history and authorized application/rejection correspondence. Maintain the private evidence in private systems, not public GitHub.
4. Build a canonical excluded-ID set: employer + normalized title + employer ATS requisition/job ID + canonical official URL. Include aliases, mirrored job boards, prior recommendations reviewed/passed, submissions, rejections, closed roles, active recruiter submissions. Different requisitions at the same employer are not automatically duplicates.
5. Resolve conflicts using dated employer receipts/user corrections, with latest explicit user instruction overriding obsolete search rules. Missing history is UNKNOWN, never proof of NEW.
6. Only THEN search employers, recruiters and public discovery sites; recheck duplicates before publishing EACH recommendation.

## Candidate screening hard gates
- Original official employer career page/ATS is live and accepting an application (or verified authorized recruiter original opening); stale indexed/aggregator page is discovery only.
- Exact authorized work location must match the PRIVATE user profile, independently evaluated for each approved country; terms such as 'remote', 'LATAM', 'worldwide' or 'US-remote' are not enough. Hybrid and onsite exceptions must satisfy the user's latest private documented location/immigration rules.
- Legal compensation structure must match the user's current approved private employment rules. Full-time hours alone do not prove employee status; independently verify payroll/EOR feasibility. Unapproved independent contracting is not eligible. Unknown legal structure means VERIFY FIRST, not APPLY.
- Genuine mandatory qualifications: prior experience, platforms, industry, degree, language and licenses; no invented coding, SaaS tenure or professional certifications. English and Spanish only; Portuguese not claimed. Exclude hard unsupported requirements. Fit must be at least 85% substantively demonstrated; percentages are qualitative estimates.
- Compensation must meet the PRIVATE user-specific net threshold when evidence is available. Never publish their actual threshold in this public repository. Unpublished pay means UNVERIFIED, not a confirmed pass.
- No existing application, prior reviewed/declined posting or rejection. A repost or job-board mirror never becomes new merely because the URL changes.

## Candidate skills and search scope
Retrieve the full verified career evidence and latest eligibility requirements from the PRIVATE master CV, Engram, and private job-search records. Search relevant adjacent duties and transferable skill families, not just familiar job titles. Never invent mandatory credentials, language proficiency, industry tenure, coding experience, or salary. Do not store a personal career biography in this public runbook.

## Discovery hierarchy and stop rules
- Favor first-party employer/ATS URLs and free official recruiter jobs.
- Use free public web engines, Google Jobs/indexed results, and relevant available connected employment plugins as discovery only. Do not buy subscriptions or credits, use pay-to-apply boards or enable auto-apply.
- Prefer new vacancies posted within the last 7–14 days, but check active older ones as needed. Search worldwide then LATAM then Colombia/Venezuela, preserving actual country qualification.
- If an integration times out, has unsupported geo, inaccessible auth or zero results, report EXACT condition. Make one bounded correction, switch to another source and never imply that all plugins ran.
- No emails, applications or recruiter outreach without user instruction. Do not repeat questions already answered.

## Publication gate
For every result show: employer, exact title and requisition, first-party live URL, date checked, authorized work-country eligibility independently, work mode, full-time employee/payroll status, mandatory qualification fit/evidence gaps, pay, previously-applied check, and decision:
**APPLY** = every hard gate evidenced; **VERIFY FIRST** = genuinely promising but a material gate unknown; **EXCLUDE** = a hard gate failed; **DUPLICATE** = prior reviewed/applied/rejected/passed/closed.
For 'next job' show at most ONE APPLY posting; otherwise say "No fully verified new qualified job found" and optionally present a clearly separate verification lead only if the user wants it. Do not call unknown a pass.

## AAR failure capture
If an old role is surfaced as new: stop; log cause (which source not checked), privately record the excluded requisition and user-confirmed status, update error/corrective-action register WITHOUT private details, validate that the next search performs AAR + history recovery first. Explicitly acknowledge residual gaps: this is a manual retrieval gate, not automatic GitHub-to-chat synchronization.

## Final audit record
Record: AAR consulted? Memory/Engram checked? Application tracker/Gmail checked? Source coverage? Official ATS re-opened? Colombia/Venezuela eligibility evidence? Payroll evidence? Compensation? Exact ID duplicate clearance? Verified new APPLY count? What remains unverified?
