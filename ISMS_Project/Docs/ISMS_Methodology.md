# ISMS Development Methodology (ISO/IEC 27001:2022)

## Overview
This methodology describes the end-to-end process to develop, approve, implement, monitor and continuously improve Information Security Policies aligned with ISO/IEC 27001:2022.

## Principles
- Risk-based approach
- Alignment with ISO/IEC 27001 clauses and Annex A controls
- Clear governance and accountability (RACI)
- Integration with business processes and tools
- Continuous improvement and evidence-based controls

## Phases (Policy Development Lifecycle)
### Phase 0 — Preparation
- Appoint ISMS Manager and Sponsor (CISO/CEO)
- Define scope and boundaries of the ISMS
- Identify interested parties and legal/regulatory requirements

### Phase 1 — Context & Requirements
- Document internal/external issues (Clause 4.1)
- Map interested parties and their needs (Clause 4.2)
- Define ISMS scope (Clause 4.3)
- Collect applicable contractual, legal, regulatory requirements

### Phase 2 — Risk Assessment & Control Selection
- Conduct information security risk assessment (Clause 8.2)
- Produce Risk Register and Risk Treatment Plan
- Map risks to Annex A controls and select control set for SoA

### Phase 3 — Policy Framework Design
- Design 4-tier policy architecture:
  - Tier 1: Enterprise Information Security Policy (EISP)
  - Tier 2: Issue-specific policies (Access, Cryptography, etc.)
  - Tier 3: Procedures and SOPs
  - Tier 4: Technical standards and baselines
- Define policy owners, reviewers, approval levels

### Phase 4 — Drafting & Alignment
- Use Policy Template for consistency
- Each policy: Purpose, Scope, Roles, Requirements, Exceptions, Evidence
- Map each clause to ISO 27001 clauses and Annex A controls

### Phase 5 — Review, Approval & Publication
- Technical, legal, and business review
- Executive approval by the ISSC or Sponsor
- Publish to central Policy Repository & communicate to employees

### Phase 6 — Implementation & Integration
- Integrate with IAM, SIEM, DLP, HR onboarding/offboarding, vendor processes
- Implement enforcement via tools (IAM, MDM, GPO)
- Conduct role-based training and collect acknowledgements

### Phase 7 — Monitoring, Audit & Improvement
- Periodic review at least annually and upon trigger events
- Internal audit per Clause 9.2, management review 9.3
- Update SoA and Risk Register after changes

## Deliverables
- Policy documents (Tier 1–2)
- Procedures and standards (Tier 3–4)
- Statement of Applicability (SoA)
- Risk Register & Treatment Plan
- RACI matrix and evidence artifacts

## Implementation Tips
- Keep policies short and enforceable (1–3 pages ideal)
- Use references to detailed procedures (avoid long operational steps inside policy)
- Maintain version control (use Git)

