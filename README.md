# Jaeger-Observability-Lab
Jaeger Observability Lab
📚 5 Learning Modules

Overview — What is distributed tracing, why Jaeger, learning path
Core Concepts — Traces, Spans, Context Propagation, Sampling (with beginner/advanced toggle)
Architecture — Animated SVG diagram matching your uploaded architecture (K8s nodes, Jaeger Agent DaemonSets, Collector, Elasticsearch, Prometheus, Grafana, Alertmanager) with animated data flow arrows
Integrations — Helm/K8s setup, Prometheus metrics, Grafana data source, Alertmanager rules, OpenTelemetry SDK code

⚡ Live Simulation (Canvas-Animated)

Send Request — animates packets flowing User → Gateway → Auth/Order/Payment → Jaeger → Elasticsearch → Grafana with timestamped logs
Simulate Failure — shows error propagation, skipped spans, Alertmanager firing
Slow Service — shows bottleneck detection, p99 latency alerts

🔍 Trace Explorer — Jaeger-UI-style waterfall timeline with clickable span details showing per-service timing bars
🎯 Quiz — 6 scenario-based questions with instant feedback and a score tracker
🤖 AI Assistant — Powered by the Claude API, answers any Jaeger question in real time (falls back to a local knowledge base if offline)
🎛️ Beginner / Advanced toggle — hides/shows code blocks and technical deep-dives per mode
