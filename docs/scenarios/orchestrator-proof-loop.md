# Scenario: Orchestrator Proof Loop

## Flow

1. A user submits a bounded task.
2. The orchestrator selects tools or sub-agents.
3. Each output is checked against build/test, verifiability, human score, correction time, and failure reason.
4. The result is summarized with an evidence level.
5. A human decides whether the output is accepted, revised, or rejected.

## Public Output

A proof card with task class, evidence level, result status, human decision, and redacted measurement. No prompt, trace, token, endpoint, local path, or private tool definition is included.
