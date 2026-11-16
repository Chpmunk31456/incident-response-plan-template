# AI Assistant Memory and Error Register

## 1. Purpose

This document serves as an external reference for AI-assisted work.

Its objectives are to:

- Preserve important decisions and verified information.
- Record assistant mistakes and their corrections.
- Reduce repeated errors.
- Improve continuity between conversations.
- Support evidence-based decisions.
- Track corrective and preventive actions.

This register supplements AI memory. It does not automatically
synchronize with an assistant's internal memory.

## 2. Operating Principles

1. Accuracy takes priority over speed.
2. Verify information before presenting it as fact.
3. Never invent sources, qualifications, results, or completed actions.
4. Distinguish confirmed information from assumptions.
5. Check previous decisions before repeating work.
6. Preserve user corrections.
7. Acknowledge uncertainty.
8. Do not claim a task is completed without evidence.
9. Use authoritative sources whenever possible.
10. Protect confidential and personal information.

## 3. Memory Recovery Procedure

When beginning work that depends on previous decisions:

1. Identify the relevant task or project.
2. Consult available conversation context.
3. Retrieve relevant external reference documents.
4. Identify the latest verified decisions.
5. Check the Error Register for previous mistakes.
6. Resolve conflicting information using dated evidence.
7. Confirm important unresolved assumptions.
8. Continue the task using verified information.

If the repository cannot be accessed, disclose that limitation.

## 4. Error Register

| Error ID | Date | Task | Error | Correct Information | Root Cause | Prevention Rule | Evidence | Status |
|---|---|---|---|---|---|---|---|---|
| ERR-001 | 2026-11-16 | Employment search | Previously surfaced expired or inaccessible job postings. | Treat employer application page as authoritative; if unavailable mark CLOSED or UNVERIFIED, not APPLY. | Verification gap; exact cause not established. | Reopen employer ATS and confirm application availability before recommendation. | User-reported closed postings in conversation; no private correspondence reproduced. | Open |
| ERR-002 | 2026-11-16 | Employment search | Previously repeated opportunities already reviewed or submitted. | Check current application/review history before labeling an opportunity new. | Context reconciliation gap; exact cause not established. | Deduplicate by employer, job title, requisition and canonical URL. | User corrections in conversation. | Open |
| ERR-003 | 2026-11-16 | Context continuity | Earlier decisions were not consistently carried into later work. | Retrieve current project decisions, previous corrections and authoritative records when context is missing. | Incomplete context retrieval; exact cause not established. | Apply context-recovery checklist and state when retrieval is unavailable. | User corrections in conversation. | Open |
| ERR-005 | 2026-11-16 | Employment search | Previously applied BairesDev Senior Technical Program Manager resurfaced as a supposedly new opening. | User confirms already applied; private application history is authoritative, not absence from an abbreviated tracker. | AAR pre-search and cross-system deduplication not performed before recommendation. | Use the employment-search runbook; check AAR, memory, Engram, full application history and employer+requisition+alias before surfacing. | User correction in conversation; detailed application evidence belongs in private records. | Open |
| ERR-004 | 2026-11-16 | Deliverables | Completion claims risk being made without independently verifying output or repository changes. | Confirm file existence, commit result or application receipt before claiming completion. | Verification control gap; occurrence and scope require case-specific review. | Use explicit completion evidence and distinguish user-reported from independently verified. | Conversation-derived prevention requirement. | Open |

## 5. Error Categories

- Memory or context loss
- Incorrect factual information
- Unsupported assumptions
- Repeated recommendations
- Incorrect qualifications assessment
- Outdated information
- Broken or unverified links
- Incomplete research
- Incorrect document formatting
- Failure to follow instructions
- Incorrect task completion claims
- Privacy or confidentiality concerns

## 6. Root Cause Analysis

For significant errors, document:

**Error ID:**

**What happened?**

**What should have happened?**

**What evidence was available?**

**What evidence was overlooked?**

**What caused the error?**

**What remains uncertain?**

**What corrective action is required?**

## 7. Corrective Action Register

| Action ID | Related Error | Corrective Action | Owner | Due Date | Verification Method | Status |
|---|---|---|---|---|---|---|
| CA-001 | ERR-001 | Verify current employer-hosted application before recommending. | AI assistant | Before each recommendation | Confirm active employer application and eligibility | Active |
| CA-002 | ERR-002 | Reconcile application and previously reviewed history. | AI assistant | Before each search result | No duplicates in new recommendations | Active |
| CA-003 | ERR-003 | Retrieve project decisions and corrections when context is incomplete. | AI assistant | At relevant task start | Cite or identify recovered records | Active |
| CA-005 | ERR-005 | Execute mandatory pre-search AAR context recovery and private cross-system application/review deduplication; reject incomplete-history claims of NEW. | AI assistant | Before every job suggestion | Audit checklist with dated lookup and exact requisition / aliases; no repeated applied jobs | Active |
| CA-004 | ERR-004 | Verify artifact or action before claiming success. | AI assistant | Before reporting completion | File, commit or receipt evidence | Active |

## 8. Lessons Learned

### STOP

Identify behaviors or processes that should be discontinued.

### START

Identify verification procedures or safeguards to introduce.

### CONTINUE

Identify effective practices worth maintaining.

## 9. Important Decisions Register

| Decision ID | Date | Project | Decision | Supporting Evidence | Current Status |
|---|---|---|---|---|---|
| DEC-001 | | | | | Active |
| DEC-002 | | | | | Active |

## 10. Source Verification

Before relying on external information:

- Confirm the source exists.
- Confirm the information is current when necessary.
- Prefer original or authoritative sources.
- Check whether the source supports the specific claim.
- Record uncertainty or conflicting evidence.
- Avoid presenting unverified information as confirmed.

## 11. Task Completion Verification

Before reporting completion:

1. Identify the requested deliverable.
2. Verify that the action actually occurred.
3. Confirm that generated files exist.
4. Confirm that repository changes were committed.
5. Check the result against the original requirements.
6. Clearly identify incomplete work.

## 12. Review and Maintenance

**Register Owner:**

**Last Review Date:**

**Next Review Date:**

**Outstanding Errors:**

**Outstanding Corrective Actions:**

**Verified Improvements:**

## 13. Confidentiality

Do not store passwords, API keys, personal identification
numbers, private communications, sensitive employment
records, medical information, or confidential incident
evidence in this public repository.

Use approved private storage for sensitive information.

## 14. Limitations

This register is an external knowledge resource.

An AI assistant must retrieve and review its contents
before using them.

The register does not guarantee automatic recall,
persistent internal memory, or error-free responses.
