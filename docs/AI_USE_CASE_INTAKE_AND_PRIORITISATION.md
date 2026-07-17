# AI Use Case Intake and Prioritisation

Use this template before selecting a model, vendor, or technical design. The goal is to establish whether the problem is valuable, suitable for AI assistance, and safe enough to test.

## 1. Business Need

| Field | Questions |
|---|---|
| Problem statement | What is difficult, slow, inconsistent, or error-prone today? |
| Current workflow | What steps, tools, handoffs, and decisions are involved? |
| Owner | Who is accountable for the process and its outcome? |
| Affected users | Who performs, receives, reviews, or depends on the work? |
| Frequency and impact | How often does the problem occur and why does it matter? |
| Desired change | What should become easier, faster, clearer, or more reliable? |

## 2. Knowledge and Data Readiness

- What sources are required?
- Which source is authoritative when information conflicts?
- Is the material current, complete, searchable, and consistently structured?
- What sensitivity, retention, residency, copyright, or consent requirements apply?
- Who may access each source and who approves that access?
- Can answers cite or link back to their supporting sources?

## 3. Workflow and Human Review

- Which step is suitable for AI assistance?
- Which decisions must remain human-owned?
- What action is prohibited without approval?
- How can a user correct, reject, or escalate an output?
- What happens when the service is unavailable or uncertain?

## 4. Risk Review

Consider privacy, security, safety, bias, accuracy, legal obligations, records management, third-party risk, reputational impact, and operational dependency.

Record each material risk with:

| Risk | Likelihood | Impact | Control | Owner | Residual risk |
|---|---:|---:|---|---|---|
| Example: unsupported answer is treated as policy | Medium | High | Source citations, human review, clear uncertainty state | Process owner | Medium |

## 5. Pilot Definition

| Field | Decision |
|---|---|
| Pilot users | A small, representative group |
| Included workflow | One bounded task or decision-support step |
| Excluded activity | Autonomous or irreversible action |
| Approved information | Named sources only |
| Duration | Long enough to observe normal use and exceptions |
| Support owner | Person responsible for questions and incidents |
| Stop conditions | Events that pause the pilot immediately |

## 6. Success Measures

Agree measures before the pilot. Possible measures include:

- task completion time;
- answer usefulness and source coverage;
- correction, rejection, and escalation rates;
- user confidence and adoption;
- operational incidents or policy exceptions;
- cost per completed workflow;
- service latency, availability, and freshness.

These are measurement categories, not claimed results.

## 7. Prioritisation Score

Score each dimension from 1 (low) to 5 (high).

| Dimension | Score | Notes |
|---|---:|---|
| Business value |  |  |
| User need |  |  |
| Knowledge readiness |  |  |
| Workflow clarity |  |  |
| Ease of human review |  |  |
| Delivery feasibility |  |  |
| Risk manageability |  |  |
| Measurement readiness |  |  |

Do not use the total as an automatic decision. A high-impact safety, privacy, or access concern can override the score.

## 8. Decision Path

- **Proceed to discovery:** valuable problem, named owner, and enough evidence to investigate.
- **Proceed to bounded pilot:** sources, access, controls, measures, support, and stop conditions are approved.
- **Refine:** the opportunity is useful but knowledge, workflow, or control readiness is incomplete.
- **Hold:** ownership, authority, safety, or evidence is insufficient.
- **Do not proceed:** the risk or operating model is unsuitable for AI assistance.


