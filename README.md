# Bernardo Demier

**Applied AI · Agent systems · Security engineering**

I build tools for the practical questions behind AI products: which context should an agent see, how do we evaluate its behavior, and what should happen before it acts?

My work connects software engineering, computational methods, and defensive security. These projects make the implementation, evidence, and limitations easy to inspect.

**[Try the live demos →](https://bernardo-demier-ai-lab.fancy-fly-9200.chatgpt.site/)** No installation or account required. Explore synthetic examples or change the inputs directly in your browser.

## Integrated systems

| Project | Engineering problem | Try it |
| --- | --- | --- |
| [Agent Runtime Lab](https://github.com/demier-demier/agent-runtime-lab) | Durable workflow state, approval binding, worker fencing, and recovery across a side-effect boundary. | [Run, interrupt, and recover](https://bernardo-demier-ai-lab.fancy-fly-9200.chatgpt.site/agent-runtime-lab/) |
| [Policy RAG Lab](https://github.com/demier-demier/policy-rag-lab) | Hybrid retrieval with authorization before ranking, document versions, transactional indexes, and citation revalidation. | [Search, revoke, and revalidate](https://bernardo-demier-ai-lab.fancy-fly-9200.chatgpt.site/policy-rag-lab/) |

The public labs use synthetic data and simulated identities. Their repositories include persistent local implementations and failure tests; the browser demos explain where those boundaries differ.

## Focused projects

| Project | What it does | Start here |
| --- | --- | --- |
| [Semantic Context Lab](https://github.com/demier-demier/semantic-context-lab) | Runs local embeddings and compares lexical, semantic, and hybrid retrieval under a context budget. | [Live search demo](https://bernardo-demier-ai-lab.fancy-fly-9200.chatgpt.site/semantic-context-lab/) · source provenance · measured retrieval results |
| [MCP Contract Guard](https://github.com/demier-demier/mcp-contract-guard) | Detects changes in an agent's MCP tool definitions and requires review before accepting a new contract. | [Live comparison demo](https://bernardo-demier-ai-lab.fancy-fly-9200.chatgpt.site/mcp-contract-guard/) · CI gate · JSON/SARIF output |
| [Incident Evidence Workbench](https://github.com/demier-demier/incident-evidence-workbench) | Correlates security events into triage cases with timelines and traceable evidence. | [Live investigation demo](https://bernardo-demier-ai-lab.fancy-fly-9200.chatgpt.site/incident-evidence-workbench/) · browser Python analysis · evidence timelines |

## Agent engineering foundations

| Project | Engineering focus |
| --- | --- |
| [Agent Eval Kit](https://github.com/demier-demier/agent-eval-kit) | Replay multi-step traces and evaluate tool use, task outcomes, cost, and policy violations. |
| [Context Ledger](https://github.com/demier-demier/context-ledger) | Retrieve context with access boundaries, source versions, freshness, and citations. |
| [Tool Approval Gateway](https://github.com/demier-demier/tool-approval-gateway) | Bind human approvals to proposed tool actions, with expiry, replay protection, and an audit trail. |

These are standalone reference implementations with original synthetic fixtures, documented tradeoffs, reproducible demos, and automated tests. The repositories distinguish measured model behavior from deterministic rules and test doubles.

## Tools I work with

Python, TypeScript, JavaScript, Rust, SQL, React, Next.js, Node.js, APIs, and local AI inference.

I am particularly interested in AI product engineering, agent infrastructure, retrieval, evaluation, and security controls that people can understand and operate.
