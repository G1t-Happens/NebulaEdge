# NebulaEdge

> ⚡️ Learning project – A modern, AI‑first, Edge‑native platform built with Rust + WebAssembly.

---

## 📖 Overview

NebulaEdge is a **learning project** that experiments with cutting‑edge architectural trends:

* **Rust** for performance and safety.
* **WebAssembly (Wasm)** for portable extensibility.
* **Event‑driven Architecture (EDA)** with NATS as the backbone.
* **RAG (Retrieval Augmented Generation)** and AI integration.
* **Edge deployment** via Cloudflare Workers.

Goal: Explore modern patterns, learn by building, and create a small platform that natively provides AI features at the edge.

---

## 📦 Recommended Project Structure

```
nebulaedge/
  apps/              # Rust microservices (API, Orchestrator, Workers)
    api/             # HTTP API service
    orchestrator/    # Event orchestration service
    edge-worker/     # Cloudflare Worker integration
  crates/            # Shared Rust libraries
    domain/          # Core domain models
    rag-sdk/         # RAG and AI helper library
    skills-sdk/      # Wasm skill SDK
  skills/            # Example Wasm skills
    markdown-to-text/
    pii-redaction/
  infra/             # Infrastructure as Code (Docker, Terraform, Kubernetes)
    docker/
    terraform/
  ops/               # Observability and monitoring
    grafana/
    opentelemetry/
  docs/              # Documentation, design diagrams, notes
  scripts/           # Helper scripts (build, deploy, test)
```

* **apps/** contains all microservices and edge workers.
* **crates/** holds reusable libraries.
* **skills/** are individual, portable Wasm components.
* **infra/** and **ops/** handle infrastructure and monitoring.
* **docs/** and **scripts/** support development and maintenance.

---

## 🎯 Project Goals

* Act as an architecture playground for modern concepts.
* Gain hands‑on experience with Rust, Wasm, Event‑Driven Systems, and Edge Deployments.
* Serve as an **experimental learning codebase**, not production‑ready software.

---

## 🚦 Status

🚧 Work in Progress – **Experimental learning project**.

---


