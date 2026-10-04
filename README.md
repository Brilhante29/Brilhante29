# Guilherme Brilhante

**Software Engineer | Scalable backends · Production AI · Applied research**

I am a Software Engineer at **Zup Innovation (Itaú Group)**, based in Fortaleza, Brazil. I design resilient backend services and take AI systems from research artifacts to reproducible production workflows. Alongside engineering work, I have co-authored peer-reviewed research on medical imaging, edge AI, wildfire forecasting, and license-plate recognition; that research habit shows up in how I build software: every claim comes with a way to check it.

[LinkedIn](https://www.linkedin.com/in/guilhermefreirebrilhanteseveriano/) · [DBLP](https://dblp.org/pid/353/6812.html)

## Focus

- **Backend and distributed systems:** Java/Kotlin, Spring Boot, Go, Python, Node.js, Kafka, PostgreSQL, Redis, and AWS.
- **Production AI and MLOps:** MLflow, Airflow, FastAPI, Docker, Prometheus, evaluation, model serving, and observability.
- **Applied research:** computer vision, medical imaging, wildfire forecasting, explainability, and reproducible experimentation.

## Selected work

| Project | What it demonstrates |
|---|---|
| [kiri-gcp](https://github.com/Brilhante29/kiri-gcp) | Single-binary Google Cloud emulator: 108 services on one local endpoint with a published fidelity map, Cloud Storage verified end to end with the official Go, Python, and Node.js clients, a cost surface, and signed releases with SBOMs and SLSA provenance. |
| [End-to-End MLOps Pipeline](https://github.com/Brilhante29/mlops-end2end) | Airflow, MLflow registry, quality-gated promotion, and FastAPI serving: validated data to a served model in 58.7 s, ROC AUC 0.928. |
| [Hexagonal Payments](https://github.com/Brilhante29/spring-hexagonal-payments) | Kotlin/Spring Boot payments with database-enforced idempotency, hexagonal boundaries, 95.65% core coverage, and k6 evidence. |
| [Transactional Outbox](https://github.com/Brilhante29/outbox-pattern) | Zero lost events across forced JVM crashes and broker outages, with deduplicated at-least-once delivery. |
| [Kafka Streams Enrichment](https://github.com/Brilhante29/kafka-streams-demo) | Kotlin stream-table join and aggregation proven against a real Kafka 4.3 broker with `exactly_once_v2`. |
| [Stroke CT Segmentation Benchmark](https://github.com/Brilhante29/stroke-signal-demo) | Public, leakage-safe companion to my IJCNN 2023 paper: patient-level splits and immutable Docker evidence. |
| [FireCast](https://github.com/Brilhante29/queimadas-v3) | Glass-box monthly wildfire forecasting with leakage controls, exact XAI, fail-closed API behavior, and production artifacts. |

## Portfolio map

Each repository is built around a falsifiable claim: pinned dependencies, automated checks, containerized execution, explicit limits, and committed benchmark or evaluation evidence.

**Backend reliability**
[spring-hexagonal-payments](https://github.com/Brilhante29/spring-hexagonal-payments) ·
[outbox-pattern](https://github.com/Brilhante29/outbox-pattern) ·
[saga-orchestrator](https://github.com/Brilhante29/saga-orchestrator) ·
[event-sourcing-orders](https://github.com/Brilhante29/event-sourcing-orders) ·
[multi-tenant-starter](https://github.com/Brilhante29/multi-tenant-starter) ·
[cache-strategies-bench](https://github.com/Brilhante29/cache-strategies-bench) ·
[go-rate-limiter](https://github.com/Brilhante29/go-rate-limiter) ·
[api-gateway-lite](https://github.com/Brilhante29/api-gateway-lite) ·
[grpc-vs-rest-bench](https://github.com/Brilhante29/grpc-vs-rest-bench) ·
[kafka-streams-demo](https://github.com/Brilhante29/kafka-streams-demo)

**AI evaluation and GenAI**
[rag-knowledge-base](https://github.com/Brilhante29/rag-knowledge-base) ·
[llm-eval-harness](https://github.com/Brilhante29/llm-eval-harness) ·
[llm-agent-eval](https://github.com/Brilhante29/llm-agent-eval) ·
[prompt-ab-testing](https://github.com/Brilhante29/prompt-ab-testing) ·
[embeddings-benchmark](https://github.com/Brilhante29/embeddings-benchmark) ·
[cost-aware-inference](https://github.com/Brilhante29/cost-aware-inference) ·
[llm-based-doc-scan](https://github.com/Brilhante29/llm-based-doc-scan)

**MLOps and data**
[mlops-end2end](https://github.com/Brilhante29/mlops-end2end) ·
[model-drift-detector](https://github.com/Brilhante29/model-drift-detector) ·
[feature-store-lite](https://github.com/Brilhante29/feature-store-lite) ·
[data-quality-checks](https://github.com/Brilhante29/data-quality-checks)

**Applied computer vision and medical AI**
[stroke-signal-demo](https://github.com/Brilhante29/stroke-signal-demo) ·
[melanoma-classifier](https://github.com/Brilhante29/melanoma-classifier) ·
[yolo-training-pipeline](https://github.com/Brilhante29/yolo-training-pipeline) ·
[vision-serving-fastapi](https://github.com/Brilhante29/vision-serving-fastapi) ·
[alpr-mercosul](https://github.com/Brilhante29/alpr-mercosul)

**Cloud, delivery, and developer tooling**
[kiri-gcp](https://github.com/Brilhante29/kiri-gcp) ·
[kiri-aws](https://github.com/Brilhante29/kiri-aws) ·
[mini-aws-emulator](https://github.com/Brilhante29/mini-aws-emulator) ·
[terraform-aws-baseline](https://github.com/Brilhante29/terraform-aws-baseline) ·
[ci-cd-templates](https://github.com/Brilhante29/ci-cd-templates) ·
[observability-stack](https://github.com/Brilhante29/observability-stack) ·
[load-test-suite](https://github.com/Brilhante29/load-test-suite) ·
[lightpanda-mcp-server](https://github.com/Brilhante29/lightpanda-mcp-server) ·
[fastapi_with_mqtt](https://github.com/Brilhante29/fastapi_with_mqtt)

**Evidence platform**
[portfolio-evidence-api](https://github.com/Brilhante29/portfolio-evidence-api) (NestJS, REST + GraphQL) ·
[portfolio-evidence-console](https://github.com/Brilhante29/portfolio-evidence-console) (Next.js) ·
[portfolio-reuse-kit](https://github.com/Brilhante29/portfolio-reuse-kit) (the shared standard behind every repository)

## How I build

Specification first, then code, then evidence. Architecture, stack, and rejected alternatives are recorded per repository; benchmarks run from pinned containers and publish their provenance. Development is AI-assisted and human-governed: coding agents work inside the guardrails of [portfolio-reuse-kit](https://github.com/Brilhante29/portfolio-reuse-kit), and tests, validators, and CI decide what ships.

## Selected peer-reviewed publications

| Year | Publication | Venue |
|---:|---|---|
| 2026 | [Wildfire Monitor: Real-Time Prediction and Interpretable Alerts from Fused Satellite and Meteorological Data](https://doi.org/10.5753/sbsi.2026.248736) | SBSI |
| 2024 | [Health of Things Melanoma Detection System—detection and segmentation of melanoma in dermoscopic images applied to edge computing using deep learning and fine-tuning models](https://doi.org/10.3389/frcmn.2024.1376191) | Frontiers in Communications and Networks |
| 2024 | [Wearable Stroke Alert System—New Health of Things Approach Based on Generative AI and Datafusion for Real-Time Stroke Monitoring](https://doi.org/10.1109/SBESC65055.2024.10771817) | IEEE SBESC |
| 2023 | [Divisible Cell-Segmentation: A New Approach for Stroke Detection and Segmentation in CT Scans Using Deep Learning and Fine-tuning](https://doi.org/10.1109/IJCNN54540.2023.10191320) | IEEE IJCNN |
| 2023 | [New Approach in LPR Systems Using Deep Learning to Classify Mercosur License Plates with Perspective Adjustment](https://doi.org/10.1007/978-3-031-35507-3_4) | Springer, ISDA |

**Primary stack:** Java · Kotlin · Spring Boot · Go · Python · FastAPI · AWS · Docker · Kafka · PostgreSQL · MLflow · Airflow · Prometheus

## Contact

If you work on scalable platforms, production AI, or applied research, connect with me on [LinkedIn](https://www.linkedin.com/in/guilhermefreirebrilhanteseveriano/).
