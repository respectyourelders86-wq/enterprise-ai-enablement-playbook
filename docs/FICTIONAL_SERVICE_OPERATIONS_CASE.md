# Fictional Service Operations Case

## Scenario

Harbour Service Group is a fictional organisation with distributed service teams. Staff search across approved procedures, service guides, and internal knowledge articles to answer routine operational questions. Information is difficult to navigate, and users are not always sure which source is current.

The organisation is considering a read-only knowledge assistant that retrieves relevant approved material, provides a concise response, cites its sources, and routes uncertain or sensitive questions to a human owner.

This is a conceptual example. It does not describe a real organisation, implementation, or result.

## Questions To Answer Before a Pilot

### Business and Users

- Which questions consume the most time or create inconsistent answers?
- Who owns the process and the underlying guidance?
- Which user groups are included, and what training do they need?
- What decision remains the user's responsibility?

### Knowledge Readiness

- Which sources are authoritative?
- Who resolves conflicting or outdated guidance?
- How will source ownership, version, and review date be recorded?
- What content must be excluded because of sensitivity or access restrictions?

### Workflow Design

- Where will users ask questions?
- What evidence will be displayed with each answer?
- How will the assistant state uncertainty or missing evidence?
- How can users correct, reject, or escalate an answer?
- What is the fallback when the service or source is unavailable?

## Proposed Controls

- Read-only access to a named set of approved sources.
- Existing user identity and access rules apply to every retrieval.
- Source citations and review dates accompany responses.
- No autonomous update, approval, transaction, or external communication.
- Clear uncertainty state when evidence is missing, stale, or conflicting.
- Human escalation for sensitive, exceptional, or policy-related questions.
- Logged service events and user feedback without unnecessary personal content.
- A named owner can pause the pilot if a stop condition is met.

## Bounded Pilot

The pilot could include one service team, a limited set of reviewed documents, and a defined question category. A representative test set should include routine questions, ambiguous wording, outdated material, conflicting sources, restricted content, and questions outside scope.

## Measures To Monitor

- usefulness ratings from pilot users;
- proportion of answers with adequate source support;
- correction, rejection, and escalation rates;
- source freshness and unresolved conflicts;
- response latency and service availability;
- support effort and reported incidents;
- cost per completed knowledge request.

These are proposed measures. No performance outcome is claimed.

## Scale-Up Decision

Scale-up should require evidence that users find the workflow useful, source controls work, sensitive information remains protected, uncertainty is handled appropriately, support ownership is established, and operating cost is understood. Otherwise, refine the workflow or stop the pilot.


