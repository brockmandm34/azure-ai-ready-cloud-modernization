## Proof of Concept

This repository includes a lightweight proof of concept for the first AI pilot recommended in the modernization roadmap: an internal knowledge assistant using approved operational documents.

The POC is designed to show how a customer could move from architecture planning into a controlled technical pilot without giving AI unrestricted access to internal data.

### POC Scenario

Contoso Operations wants to help employees find answers from approved operational policies, reporting guides, and workflow procedures.

Instead of connecting an AI assistant to every internal file or data source, the POC uses a small approved document set and defines a governed retrieval, prompting, and evaluation pattern.

### POC Pattern

```text
Approved Documents
        ↓
Document Ingestion
        ↓
Azure AI Search Index
        ↓
Azure OpenAI / Azure AI Foundry Assistant
        ↓
Grounded Answer with Source Reference
        ↓
User Feedback and Review
```

### POC Artifacts

The `poc/` folder includes:

- Sample approved documents
- Conceptual Azure AI Search index schema
- Governed system prompt
- Evaluation questions
- Results template for testing answer quality and escalation behavior

### Governance Principles

The assistant should:

- Answer only from approved sources
- Avoid making unsupported claims
- Refer users back to source documents when uncertain
- Flag sensitive or unclear requests for human review
- Capture feedback for evaluation
- Be monitored for usage, latency, cost, and risk

### POC Success Criteria

The POC is successful if:

- Users can ask questions about approved documents
- Answers are grounded in the provided sources
- Unsupported questions are handled safely
- Feedback can be collected
- Risks and limitations are documented
- The pattern can be reviewed before production rollout

See [`poc/README.md`](poc/README.md).
