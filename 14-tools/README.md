# Tools Reference for Backend Developers

This section is a **curated reference of tools** useful for Backend Developers.

The goal of this directory is **not** to teach tools step-by-step, but to:
- List tools that solve *real backend problems*
- Categorize them clearly
- Point to concise documentation for each tool

> Tools do not replace fundamentals.  
> They provide **visibility**, **control**, and **diagnostic power** when fundamentals are already understood.

---

## 🧭 How to Use This Section

- Each tool lives in its own directory
- Every tool directory contains a `README.md`
- Each tool README explains:
  - What the tool is
  - What problem it solves
  - When it should be used
  - When it is the wrong choice

---

## 🧪 Network & Traffic Inspection

Tools for observing, inspecting, and debugging network traffic.

- [`Kubeshark`](network/kubeshark/)  
  Inspect and analyze live network traffic inside Kubernetes clusters (Wireshark-like visibility).

- [`tcpdump`](network/tcpdump/)  
  Low-level packet capture tool for Linux systems.

- [`mitmproxy`](network/mitmproxy/)  
  Interactive HTTP/HTTPS interception proxy.

---

## 📊 Observability & Debugging

Tools that improve system visibility at runtime.

- [`Prometheus`](observability/prometheus/)  
  Metrics collection and time-series querying.

- [`Grafana`](observability/grafana/)  
  Metrics visualization and dashboards.

- [`Jaeger`](observability/jaeger/)  
  Distributed tracing for microservices.

- [`Tempo`](observability/tempo/)  
  Scalable distributed tracing backend with minimal indexing.

---

## 🚀 Performance & Load Testing

Tools for performance analysis and traffic simulation.

- [`k6`](performance/k6/)  
  Modern, script-based load testing.

- [`wrk`](performance/wrk/)  
  High-performance HTTP benchmarking tool.

- [`hey`](performance/hey/)  
  Simple HTTP load generator.

---

## 🔐 Security & Analysis

Tools related to security, scanning, and runtime protection.

- [`Trivy`](security/trivy/)  
  Vulnerability scanner for containers, images, and IaC.

- [`Falco`](security/falco/)  
  Runtime security and anomaly detection for Kubernetes.

- [`nmap`](security/nmap/)  
  Network scanning and service discovery.

---

## 🧰 Development Utilities

Tools that improve developer productivity and workflow.

- [`direnv`](development/direnv/)  
  Environment variable management per project.

- [`httpie`](development/httpie/)  
  Human-friendly HTTP client.

- [`jq`](development/jq/)  
  Command-line JSON processor.

---

## 🧠 Important Note

If you do not clearly understand:
- what problem you are solving
- at which layer
- and why it exists

no tool will fix the system.

This section exists to support **informed tool selection**, not tool worship.
