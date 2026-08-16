<div align="center">
  <h1>Vikram Babariya</h1>
  <p><b>DevOps Engineer | Cloud Engineering</b></p>
  <p>📍 Gujarat, IN | ☁️ AWS Certified Cloud Practitioner | 🌐 <a href="https://vikram-sre.dev">vikram-sre.dev</a> | 💼 <a href="https://linkedin.com/in/vikram-babariya">LinkedIn</a></p>
</div>

---

## ⚙️ Operational Mandate
DevOps Engineer transitioning from a Python backend foundation to high-availability infrastructure. Specializes in architecting **zero-trust AWS serverless ecosystems**, enforcing **immutable CI/CD delivery pipelines**, and applying **Shift-Left SRE quality gates** to strictly reduce Total Cost of Ownership (TCO) and Mean Time To Recovery (MTTR).

## 🏗️ Architectural Competencies
* **Cloud Infrastructure & Security:** AWS (IAM, S3, API Gateway, DynamoDB, Lambda), OIDC Identity Federation, Zero-Trust Network Segmentation.
* **Pipeline Automation & DevSecOps:** GitHub Actions, Multi-Stage Docker Builds, Container Hardening (PoLP, Non-Root), Semantic Validation (`ajv-cli`, `yamllint`).
* **FinOps & Observability:** AWS CloudWatch, Budget Hard-Capping (₹500 INR/mo limit enforcement), Immutable Infrastructure Patterns.
* **Backend Execution:** Python, Node.js, FastAPI, Django, PostgreSQL.

## 🚀 Flagship Infrastructure

### 1. [Zero-Trust Resume-as-Code (RaC) Platform](https://github.com/VikramBabariya/zero-trust-rac-platform)
* **Architecture:** Serverless AWS delivery pipeline enforcing blast radius containment via **OIDC identity federation**, completely deprecating vulnerable, long-lived IAM keys.
* **Outcome:** Guaranteed flawless artifact hygiene and zero-downtime delivery utilizing idempotent S3 state synchronizations and automated CloudFront edge network invalidations.

### 2. [Inventory System: Containerized Defense-in-Depth → Kubernetes Migration](https://github.com/VikramBabariya/inventory-system)
* **Architecture:** Multi-tier Docker bridge networking → full Kubernetes migration (11 manifests, dedicated namespace, ClusterIP/NodePort topology, PVC-backed PostgreSQL, ConfigMap schema injection). Zero plaintext credentials across all manifests via secretKeyRef. Validated locally on k3d, targeting k3s on OCI ARM64.
* **Outcome:** Slashed production Docker artifacts by 90% (3.5 GB → 364 MB). Property-based manifest test suite (6 Hypothesis tests) enforces structural correctness shift-left — no live cluster required to gate correctness.

## 🔄 Current Architectural Sprint
Completed local Kubernetes deployment of the Inventory System on k3d — 11 manifests, zero-plaintext credentials, property-based manifest validation. Next phase: provisioning OCI ARM64 VM (Always Free A1.Flex, 4 OCPUs / 24GB RAM), installing k3s, and deploying all four services to the live cluster. CI/CD pipeline for automated image build → GHCR push → kubectl apply is the subsequent gate.

---
<div align="center">
  <i>Executing idempotent infrastructure, absolute cost governance, and zero-trust delivery.</i>
</div>
<!---
VikramBabariya/VikramBabariya is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
