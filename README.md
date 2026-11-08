# Yakup Akçay

Data science / ML engineering. I build small, self-contained projects around industrial data, retrieval and agents, computer vision and forecasting. Each repo has tests and CI, and runs locally without paid APIs or API keys.

## Projects

### Industrial & predictive maintenance
| Repo | What it does |
| :--- | :--- |
| [industrial-predictive-maintenance](https://github.com/yakupakcy36/industrial-predictive-maintenance) | Fault classification and remaining-useful-life estimation for machines, with drift monitoring and a FastAPI service |
| [scada-cyber-anomaly-detection](https://github.com/yakupakcy36/scada-cyber-anomaly-detection) | Intrusion detection on SCADA telemetry using physical consistency checks plus Isolation Forest |
| [acoustic-machine-anomaly-detector](https://github.com/yakupakcy36/acoustic-machine-anomaly-detector) | Unsupervised anomaly detection on machine audio (STFT, mel features, reconstruction error) |

### LLM, retrieval & agents
| Repo | What it does |
| :--- | :--- |
| [enterprise-rag-guardrails-engine](https://github.com/yakupakcy36/enterprise-rag-guardrails-engine) | RAG with BM25 + dense retrieval, prompt-injection checks, PII redaction and an evaluation harness |
| [autonomous-data-analyst-agent](https://github.com/yakupakcy36/autonomous-data-analyst-agent) | Text-to-SQL agent with a state machine, a SQL safety gate and retry on errors |
| [llm-semantic-router-gateway](https://github.com/yakupakcy36/llm-semantic-router-gateway) | Routes requests across model tiers by complexity, with a circuit breaker and cache (simulated providers) |
| [multimodal-document-intelligence](https://github.com/yakupakcy36/multimodal-document-intelligence) | Layout-based table and field extraction from documents with arithmetic consistency checks |

### Vision & model compression
| Repo | What it does |
| :--- | :--- |
| [industrial-edge-defect-inspection](https://github.com/yakupakcy36/industrial-edge-defect-inspection) | Surface defect detection with classical image processing |
| [conveyor-product-defect-inspection](https://github.com/yakupakcy36/conveyor-product-defect-inspection) | Defect detection for products on a conveyor line, with a reject signal |
| [edge-model-quantization-benchmark](https://github.com/yakupakcy36/edge-model-quantization-benchmark) | INT8 quantization and magnitude pruning, measuring size, error and latency |

### Forecasting, risk & optimization
| Repo | What it does |
| :--- | :--- |
| [smart-grid-energy-forecasting](https://github.com/yakupakcy36/smart-grid-energy-forecasting) | Quantile load forecasting with a linear-programming reserve dispatch |
| [clinical-biomarker-risk-engine](https://github.com/yakupakcy36/clinical-biomarker-risk-engine) | Patient risk model with probability calibration and decision curve analysis |
| [dynamic-inventory-rl-optimizer](https://github.com/yakupakcy36/dynamic-inventory-rl-optimizer) | Inventory replenishment with tabular Q-learning, compared against an (s, S) policy |
| [distributed-feature-store-engine](https://github.com/yakupakcy36/distributed-feature-store-engine) | Feature store with point-in-time joins and online/offline skew checks |
| [financial-aml-graph-sentinel](https://github.com/yakupakcy36/financial-aml-graph-sentinel) | Graph-based detection of cycles and structuring patterns in transactions |

### Earlier coursework & notebooks
Classic ML/DL projects, each with the original notebook and a cross-validated benchmark script:
[langchain-translation-api](https://github.com/yakupakcy36/langchain-translation-api),
[deep-learning-project-1](https://github.com/yakupakcy36/deep-learning-project-1),
[deep-learning-project-2](https://github.com/yakupakcy36/deep-learning-project-2),
[machine-learning-project-1](https://github.com/yakupakcy36/machine-learning-project-1) to
[machine-learning-project-11](https://github.com/yakupakcy36/machine-learning-project-11).

## Notes
- Several industrial and clinical projects use synthetic data generated in the repo, so reported metrics describe the method on that data, not real-world performance.
- Run any project with `pip install -r requirements.txt` and `pytest`.
