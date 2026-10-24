# Muhammad Zubair Zafar

**AI / Machine Learning Engineer** · LLM agents · model evaluation · RAG · MLOps · Python / FastAPI

I build evaluated AI systems where **a test result, safety boundary, and reproducible artifact** matter more than a flashy demo. My projects cover QLoRA fine-tuning, tool-use policies, agent safety, grounded retrieval, model promotion, and real-data forecasting.

**[Selected portfolio](#selected-engineering-work) · [AI Automation Doctor demo](https://zubairz4far.github.io/ai-automation-doctor/) · [Hugging Face](https://huggingface.co/zubairz4far)**

## Selected engineering work

| Project | Engineering focus | Evidence and limitations |
| --- | --- | --- |
| [Qwen3 Tool Calling](https://github.com/zubairz4far/qwen3-tool-calling-qlora) | Qwen3-1.7B, 4-bit QLoRA, structured calls, adversarial evaluation | **94.44% strict exact-call** on a locked tool benchmark; clarification behavior regressed, so V1 retained and V2 rejected |
| [ToolGuard / Evaluated Order Agent](https://github.com/zubairz4far/evaluated-order-support-agent) | Deterministic tool guards, replay, model regression gates | Real-model 100-case release **BLOCKED** at 78% pass rate; known abstention/routing failures documented |
| [Production RAG Engine](https://github.com/zubairz4far/production-rag-engine) | Hybrid dense/BM25 retrieval, Qdrant, reranking, grounded generation | 120-query hard retrieval suite and 40-case adversarial generation suite; model and infrastructure assumptions documented |
| [AI Automation Doctor](https://github.com/zubairz4far/ai-automation-doctor) | n8n failure analysis, deterministic remediation, human approvals, crash recovery | [Read-only live demo](https://zubairz4far.github.io/ai-automation-doctor/); AI advisory output never authorizes workflow writes |
| [Production MLOps Control Plane](https://github.com/zubairz4far/production-mlops-control-plane) | Model lineage, canary promotion, drift gates, rollback, audit | Frozen lifecycle and CI smoke validation; demonstrates controls, not live customer traffic |
| [Industrial Predictive Maintenance](https://github.com/zubairz4far/industrial-predictive-maintenance-platform) | Cost-sensitive classification and calibration on UCI Scania APS | **31.9% lower challenge cost** against baseline on the official held-out test; offline benchmark |
| [Energy Grid Intelligence](https://github.com/zubairz4far/energy-grid-intelligence-platform) | Day-ahead load forecast residual correction and risk diagnostics | **7.33% lower MAE/WAPE** on held-out DE-LU period; interval undercoverage disclosed |
| [Smart Warehouse Intelligence](https://github.com/zubairz4far/smart-warehouse-intelligence-platform) | Temporal forecasting and assignment-based warehouse slotting | **10.26% lower simulated route proxy** on later real invoices; ML forecast candidate rejected |
| [Fleet Intelligence Platform](https://github.com/zubairz4far/production-fleet-intelligence-platform) | Telemetry anomaly detection, ETA, routing, MLflow, Kafka, APIs and IaC | CI-integrated architecture; headline mobility benchmarks use **synthetic** fixtures |

## How I evaluate systems

1. **Define the contract:** datasets, permitted tool actions, failure modes, and promotion criteria before testing.
2. **Separate development from final evidence:** preserve held-out tests and reject regressions rather than tuning away failures.
3. **Make results reproducible:** commit machine-readable metrics, source integrity checks, regression tests, and CI workflows.
4. **Enforce safety outside the model:** schema validation, least privilege, deterministic refusal, approval gates, idempotency, and audit trails.
5. **State the limits:** distinguish offline benchmarks, synthetic simulations, CI demonstrations, and deployed systems.

## Stack

**AI and ML:** Python, PyTorch, Transformers, PEFT / QLoRA, scikit-learn, RAG, Qdrant, MLflow, evaluation harnesses

**Services:** FastAPI, Pydantic, REST APIs, Docker, GitHub Actions, Prometheus, Kafka, PostgreSQL / SQLite

**Infrastructure and web:** Kubernetes, Terraform, TypeScript / JavaScript, Linux

## More focused projects

- [MCP Agent Firewall](https://github.com/zubairz4far/mcp-agent-firewall) — deterministic pre- and post-tool-execution policy enforcement.
- [Realtime Voice Agent Platform](https://github.com/zubairz4far/realtime-voice-agent-platform) — WebRTC voice sessions, interruption handling, protected backend tools, and latency tracking.
- [Qwen Serving Platform](https://github.com/zubairz4far/production-qwen-serving-platform) — guarded model-serving gateway, SLO assessment, and GPU benchmark evidence.

**Model:** [Qwen3-1.7B tool-calling adapter](https://huggingface.co/zubairz4far/qwen3-1.7b-tool-calling) · **Interactive evaluation:** [Tool-calling demo](https://huggingface.co/spaces/zubairz4far/qwen3-tool-calling-demo)

---

**Available for:** AI Engineer, Applied AI Engineer, ML Engineer, LLM/Agent Engineer, and MLOps roles. For technical discussions, please use the contact channels on my [GitHub profile](https://github.com/zubairz4far).
