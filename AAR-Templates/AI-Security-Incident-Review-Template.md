# AI Security Incident After-Action Review (AAR)

## 1. Incident Identification

**Incident ID:**
**Incident Title:**
**Incident Date:**
**Detection Date:**
**Incident Severity:** Critical / High / Medium / Low
**Affected AI System:**
**AI System Owner:**
**Incident Commander:**
**AI Governance Lead:**
**Security Lead:**
**AAR Owner:**
**Review Date:**
**Status:** Draft / In Review / Reviewed / Closed

## 2. Executive Summary

Provide a concise, evidence-based summary addressing:

- What happened?
- How was the incident detected?
- Which AI systems and business processes were affected?
- What was the impact on confidentiality, integrity, availability, safety, or reliability?
- How was the incident contained?
- What is the recovery status?
- What residual risks remain?
- What management decisions are required?

Distinguish confirmed findings from preliminary assessments.

## 3. AI System Profile

**System Name:**
**Business Purpose:**
**AI System Inventory ID:**
**System Owner:**
**Model Provider:**
**Model Name and Version:**
**Deployment Environment:**
**Data Classification:**
**Applicable Jurisdictions:**
**Third-Party Dependencies:**

### AI Architecture

Identify applicable components:

- Foundation models and LLMs
- Retrieval-Augmented Generation (RAG)
- Vector databases
- Embedding models
- AI agents and orchestration frameworks
- Tool and API integrations
- External data sources
- Model hosting infrastructure
- Monitoring and logging services

Reference approved architecture documentation.

## 4. Incident Classification

Select all applicable incident categories:

- Prompt injection
- Indirect prompt injection
- Sensitive information disclosure
- Unauthorized tool execution
- Excessive agent permissions
- Model or data poisoning
- Model integrity compromise
- Model extraction
- Insecure output handling
- RAG retrieval manipulation
- Vector database compromise
- AI supply-chain compromise
- Third-party AI service failure
- Unsafe or unauthorized automated decisions
- AI-generated misinformation
- Model performance degradation
- Other

**Primary Incident Category:**

**Secondary Categories:**

## 5. Incident Timeline

| Date/Time (UTC) | Event | AI Component | Evidence Reference | Business Impact |
|---|---|---|---|---|
| | | | | |
| | | | | |
| | | | | |

Include detection, escalation, containment, investigation,
recovery, and management notification milestones.

## 6. Security and Privacy Impact Assessment

| Impact Area | Description | Severity | Evidence Reference |
|---|---|---|---|
| Confidentiality | | | |
| Integrity | | | |
| Availability | | | |
| Privacy | | | |
| Model Reliability | | | |
| Human Safety | | | |
| Business Operations | | | |
| Regulatory Exposure | | | |
| Customer Trust | | | |

### Data Exposure

**Data Categories Potentially Exposed:**

**Confirmed Exposure:**

**Affected Individuals or Organizations:**

**Data Protection Officer Notified:** Yes / No / N/A

**Legal Assessment Required:** Yes / No / Under Review

## 7. AI Agent and Tool Security

Complete this section if the incident involved AI agents.

**Agent Name:**
**Agent Purpose:**
**Authorized Tools:**
**Actual Tools Used:**
**Permission Scope:**
**Human Approval Requirements:**

### Agent Behavior Assessment

Evaluate:

- Unauthorized tool invocation
- Excessive privileges
- Cross-system access
- Unauthorized data retrieval
- Tool output manipulation
- Missing human approval
- Inadequate execution boundaries
- Unsafe autonomous actions
- Insufficient audit logging

### Agent Containment

Document approved containment actions.

Do not perform untested changes to production
AI systems without appropriate authorization.

## 8. RAG and Vector Database Assessment

Complete this section when applicable.

**Knowledge Sources:**
**Vector Database:**
**Embedding Model:**
**Retrieval Controls:**
**Document Access Controls:**

Evaluate:

- Unauthorized document ingestion
- Malicious retrieved content
- Retrieval permission bypass
- Data contamination
- Cross-tenant information exposure
- Inadequate source validation
- Sensitive data leakage
- Incomplete retrieval audit trails

## 9. Root Cause Analysis

### Primary Root Cause

Document the underlying cause supported by evidence.

### Contributing Factors

Consider:

- Inadequate AI risk assessment
- Weak access controls
- Missing input validation
- Insufficient output validation
- Inadequate human oversight
- Unsafe tool permissions
- Weak model or dataset governance
- Incomplete monitoring
- Third-party security weaknesses
- Inadequate change management

### Five Whys Analysis

1. Why did the incident occur?
2. Why did the underlying condition exist?
3. Why did existing controls not prevent it?
4. Why was the incident not detected sooner?
5. Why did response or governance processes fail to address the risk?

### Evidence

Reference approved evidence sources.

### Unresolved Questions

Document findings requiring additional investigation.

## 10. AI Security Control Assessment

| Control Area | Existing Control | Effectiveness | Identified Gap | Improvement |
|---|---|---|---|---|
| AI Asset Inventory | | | | |
| Access Management | | | | |
| Prompt Security | | | | |
| Data Protection | | | | |
| Agent Permissions | | | | |
| Tool Authorization | | | | |
| Model Integrity | | | | |
| Third-Party Risk | | | | |
| Logging and Monitoring | | | | |
| Human Oversight | | | | |
| Change Management | | | | |
| Incident Response | | | | |

## 11. Detection and Response Effectiveness

Evaluate:

- Detection coverage
- AI-specific monitoring
- Security alerting
- Incident escalation
- SOC and AI team coordination
- Evidence preservation
- Containment effectiveness
- Model or agent suspension procedures
- Recovery validation
- Executive communications

### Performance Metrics

**Mean Time to Detect:**

**Mean Time to Respond:**

**Time to Containment:**

**Time to Recovery:**

**Monitoring Gaps Identified:**

## 12. Recovery and Validation

Document:

- Restoration of affected AI services
- Model and configuration integrity verification
- Dataset and retrieval-source validation
- Agent permission review
- Tool integration testing
- Security regression testing
- Output quality and reliability assessment
- Human oversight validation
- Business owner approval

**Recovery Owner:**

**Recovery Verification Date:**

**Business Owner Approval:**

**Security Approval:**

## 13. AI Governance and Regulatory Assessment

Evaluate applicable requirements and guidance:

- ISO/IEC 42001
- NIST AI Risk Management Framework
- NIST Cybersecurity Framework 2.0
- ISO/IEC 27001
- OWASP guidance for LLM and agentic AI applications
- Applicable EU AI Act obligations
- Applicable privacy and data protection laws
- Contractual and third-party requirements

### Governance Findings

**AI Risk Assessment Updated:** Yes / No

**AI Inventory Updated:** Yes / No

**AI Impact Assessment Required:** Yes / No

**Third-Party Assessment Required:** Yes / No

**Regulatory Notification Required:** Yes / No / Under Review

**Legal Review Completed:** Yes / No

## 14. Corrective and Preventive Actions

| Action ID | Finding | Priority | Corrective Action | Owner | Due Date | Status |
|---|---|---|---|---|---|---|
| AI-001 | | Critical | | | | Open |
| AI-002 | | High | | | | Open |
| AI-003 | | Medium | | | | Open |

Transfer approved actions to:

AAR-Templates/Corrective-Action-Register.md

Each action should have measurable verification criteria.

## 15. Lessons Learned

### STOP

Identify ineffective or unsafe practices to discontinue.

### START

Identify new AI security controls, monitoring,
governance processes, or training requirements.

### CONTINUE

Identify effective practices that should be maintained.

## 16. Management Review

**AI Governance Lead:**

**Security Lead:**

**Privacy Officer:**

**Business Owner:**

**Executive Sponsor:**

**Review Date:**

**Outstanding Risks:**

**Management Decisions:**

## 17. Closure

**Incident Investigation Completed:** Yes / No

**Root Cause Confirmed:** Yes / No

**Recovery Verified:** Yes / No

**Corrective Actions Assigned:** Yes / No

**Residual Risks Reviewed:** Yes / No

**Regulatory Obligations Reviewed:** Yes / No

**Management Approval Obtained:** Yes / No

**Closure Date:**

**Approved By:**

Outstanding corrective actions must remain tracked
until independently verified and formally closed.

## 18. Confidentiality

This template is intended for AI security governance,
incident response, and operational resilience.

Do not publish:

- Sensitive prompts or system instructions
- API keys or credentials
- Private datasets
- Confidential model configurations
- Sensitive RAG documents
- Internal security vulnerabilities
- Personal information
- Actual incident evidence

Store confidential incident records in approved,
access-controlled systems.
