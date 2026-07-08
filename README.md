# Enterprise Agentic Workflows

This repository shares reference implementations for enterprise agentic workflows with orchestration, evaluation, governance, observability, and human-in-the-loop controls.

These implementations explore how agentic workflows can be designed for enterprise use cases by combining functional workflow design, technical architecture, control-plane concepts, and operational guardrails.

## Focus Areas

- Functional workflow overview
- Technical architecture overview
- Agent orchestration
- Workflow state management
- Evaluation and governance
- Human-in-the-loop approvals
- Observability across agent decisions, workflow steps, and execution outcomes
- Control-plane concepts for governing safe, auditable, and policy-aligned agentic workflows

## Reference Implementations

### Business workflow references

- [Media Buying Agentic Workflow Reference Implementation](./media-buying-agentic-workflow-reference-implementation.md) — governed agentic workflow for campaign strategy, planning, activation, optimization, reporting, human approvals, evaluation, observability, and simulated MCP-based platform execution.

- [Data Stewardship Agentic Workflow Reference Implementation](./data-stewardship-agentic-workflow-reference-implementation.md) — governed AI-assisted data-product onboarding pattern with deterministic profiling, bounded specialist agents, typed artifacts, policy decisions, human approval, evaluation, and simulated MCP-based catalog publication.

### Engineering workflow references

- [Role-Based Agentic Software Delivery Reference Implementation](./role-based-agentic-software-delivery-reference-implementation.md) — governed engineering workflow showing how role-based AI Agents assist feature delivery across requirements, architecture, implementation, review and testing, including fully autonomous feature implementation capability with enterprise human check-ins where needed.

## Why This Repository

Agentic AI workflows are moving beyond prompt-response interactions. In
enterprise environments, generating a good response is not enough. Agents must
operate within explicit business processes, decision rights, approval paths,
policy boundaries, and measurable quality controls.

This repository explores the engineering and operating-model patterns required
to move from capable agents to workflows that are governable, observable,
auditable, and suitable for enterprise adoption.

## Current Status

This repository currently includes governed agentic reference implementations for Media Buying, Data Stewardship, and Role-Based Agentic Software Delivery. Additional workflows, architecture details, and implementation patterns will be added over time.