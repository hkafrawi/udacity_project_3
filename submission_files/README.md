# Submission Guide – NovaMart Multi-Agent System (Project 3)

## Files

| Path | What it shows |
|---|---|
| `copyenv.env` | Copy of my `.env` (rename to `.env` and place in root folder for test runs). Contains `AGENTCORE_RUNTIME_ARN`, `GUARDRAIL_ID`, `GUARDRAIL_VERSION` and the 3 KB IDs. |
| `all/all.png`, `all/all_tests.txt` | `python tests/test_agent.py all` → **120/120 pts** (Tasks 2–6). |
| `deploy/agentcore_deployment.png` | AgentCore Runtime `udacity_agentcore_runtime` – status **Ready**. |
| `deploy/guardrail.png`, `guardrail_.png` | Bedrock guardrail `udacity-agentcore-guardrail` (version 1). |
| `deploy/config.txt` | Output of `python config.py` (runtime ARN, guardrail ID/version, KB IDs). |
| `kb/KB_overview.png` | The 3 Knowledge Bases, all **Available** with a synced data source. |
| `kb/*_policy_kb.png` | Each KB overview: KB ID, status, data source synced. |
| `kb/*_kb.png` | Each KB vector store: **Amazon S3 Vectors**, bucket `udacity-agentcore-vectors-101099690483-c4b21d00`, index `returns/shipping/warranty-policy-index`, Titan Text Embeddings v2. |
| `test/running_test.txt` | Full output of `python src/agent_orchestrator.py test`. |
| `test/test1.png` – `test3.png` | The 3 live scenarios (return request, policy question, price calculation). All completed. |
| `test/test1_trace.png` – `test3_trace.png` | X-Ray trace of each scenario (0 faults, 0 errors). |
| `test/overall_trace_map.png` | X-Ray Trace Map: `NovaMart-Orchestrator` → Inventory, Refund, Policy, Communication agents and the 3 Knowledge Base retrievers. |

`