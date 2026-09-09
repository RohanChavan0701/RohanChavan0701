# Rohan Chavan

AI/ML engineer building evaluation, safety, and agent systems for language models.

[LinkedIn](https://www.linkedin.com/in/rohan-chavan-708532200/) · [Email](mailto:rohanchavan0701@gmail.com)

## Selected work

### [Adaptive Safety Portfolio](https://github.com/RohanChavan0701/adaptive-safety-portfolio)

An inference-time cascade that spends more compute on uncertain jailbreak classifications. On the committed JailbreakBench run, it reached 0.95 recall at 1,291 ms average latency and 31.1 proxy cost units, versus 0.93 recall, 2,583 ms, and 49.0 units for the always-all baseline; precision decreased from 0.82 to 0.74.

`LLM safety` · `adaptive inference` · `evaluation` · `PyTorch`

### [Chiron](https://github.com/RohanChavan0701/Chiron)

A runtime teacher-repair loop that detects student-model drift, verifies corrections, and adds them to prompt memory without changing model weights. The coding demo improved same-distribution accuracy from 0.273 to 0.455, while held-out experiments document that the gain often disappears.

`teacher–student systems` · `drift detection` · `prompt memory` · `evaluation`

### [Housing Policy Advisor](https://github.com/RohanChavan0701/housing-policy-advisor)

Builds a local housing profile from public data, retrieves policy evidence when a Chroma collection is available, and generates validated structured recommendations. The pipeline degrades explicitly to generation without retrieval when evidence infrastructure is unavailable.

`Census + HUD + BLS · ChromaDB · Structured Generation · Grounding Validation`

### [CareRoute Flight Agent](https://github.com/RohanChavan0701/Codefest_Flightapi)

A standalone FastAPI component for provider-backed flight lookup and status checks, with an A2A JSON-RPC interface, voice integration, and Docker packaging. It was built as the flight-service contribution to the broader CareRoute multi-agent prototype.

`FastAPI` · `A2A JSON-RPC` · `external APIs` · `Docker`
