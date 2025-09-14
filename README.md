# Fábio Barbosa Everton  
**AI Governance & DevSecOps Executive | Founder, Brachat**

Architect of production-grade AI systems with embedded compliance. Builds and documents end-to-end platforms for AI governance, ML infrastructure, and regulated SaaS delivery. Operates at the intersection of engineering rigor, regulatory frameworks, and autonomous system design.

---

## 🚀 Executive Summary

Founder and principal engineer of Brachat, a vehicle for the development, documentation, and operationalization of AI systems under constraints of compliance, auditability, and scalability. No theoretical work. All artifacts are publicly accessible, version-controlled, and designed for reproducibility — not presentation.

- **Built 21 independently documented ML services** with verifiable metrics, technology stacks, and monetization models.
- **Launched and operated an AI Governance SaaS** generating R$34,500/month in revenue from three enterprise clients.
- **Automated 47 compliance checkpoints** across all projects using a custom GitHub Actions runner enforcing LGPD, SHAP, drift, bias, and monetization requirements.
- **Reduced inference latency from 810ms to 32ms** on NVIDIA A10G via TensorRT INT8 quantization and Triton Inference Server.
- **Prevented potential regulatory fines >R$4.2M** through proactive model auditing and policy-as-code enforcement.
- **Delivered full-stack reproducible pipelines** using Docker, Terraform, DVC, MLflow, and Kubernetes — all committed to public repositories.

> This is not a portfolio. It is a system of record.  
> Every claim is traceable to code, log, metric, or certificate.  
> No assumptions. No marketing. No unverified assertions.

[View the complete artifact repository](https://github.com/brachattech/portifolio)

---

## 🔧 Core Competencies

| Domain | Technologies & Practices |
|-------|---------------------------|
| **AI Governance & Compliance** | ISO/IEC 42001, EU AI Act, LGPD, NIST RMF, Model Cards, Policy Templates (YAML), Bias Detection (AIF360, Fairlearn), Drift Monitoring (Evidently), Audit Trail (IPFS + SHA-256) |
| **DevSecOps & Infrastructure** | Docker, Kubernetes (EKS), Terraform, GitHub Actions, Semgrep, Trivy, Checkov, OPA/Rego, Vault, Prometheus, Grafana, MinIO, GitOps (Argo CD) |
| **ML Engineering & Deployment** | TensorFlow, PyTorch, ONNX, TensorRT, Triton Inference Server, MLflow, SavedModel, Feature Stores (Snowflake), Distributed Training (MirroredStrategy), INT8 Quantization |
| **LLMOps & RAG** | LangChain, LangGraph, LlamaIndex, Promptfoo, RAGAS, Embedding Models (text-embedding-ada-002), Hybrid Retrieval, Evaluation Frameworks, Vector DBs (FAISS, Qdrant) |
| **Product & Systems Leadership** | SaaS Design, Monetization Modeling, Technical Documentation as Product, CI/CD as Enforcement Layer, Multi-Tenant Architecture, Stakeholder Alignment via Artifact Ownership |

---

## 🏗️ Production System: AI Governance SaaS

**Objective**: Automate compliance verification for AI systems without human review.  
**Status**: Live, revenue-generating, auditable.

### Architecture

- **Frontend**: Next.js (TypeScript) — UI for client audit reports and dashboard
- **Backend**: FastAPI (Python 3.10) — REST API for upload, analysis, report generation
- **Core Engine**: Custom Python runner — executes 47 validation rules against submitted READMEs and models
- **Governance Layer**: 15 policy templates (LGPD-Art20, SHAP, Bias-Mitigation, Drift-Detection, etc.) enforced via YAML schemas
- **Audit Trail**: All outputs hashed with SHA-256 and pinned to IPFS; immutable ledger generated per audit
- **Deployment**: Dockerized containers on AWS EKS; secrets managed via HashiCorp Vault; CI/CD via GitHub Actions
- **Billing**: Stripe integration; monthly subscription tiers (Basic, Pro, Enterprise)
- **Clients**: 3 enterprises (fintech, insurer, health tech); no trial users; no freemium model

### Metrics

- **Revenue**: R$34,500/month (consistent since launch)
- **Audit Throughput**: 187 audits completed in 6 months
- **False Positives**: 0% (validated over 120 runs)
- **SLA**: 99.98% uptime over 6 months
- **Time to Report**: 58 seconds average

All components are open-source and fully documented in [github.com/brachattech/portifolio](https://github.com/brachattech/portifolio).

---

## 🏥 Product: Dr. Fellow — Psychiatry EHR with AI Governance

**Objective**: Build a compliant, auditable electronic health record system for psychiatric care.

### Architecture

- **Frontend**: React + Tailwind CSS — responsive interface for clinicians
- **Backend**: FastAPI — secure REST API with JWT authentication and RBAC
- **Database**: PostgreSQL — encrypted at rest, role-based access control
- **AI Layer**:  
  - Fine-tuned TensorFlow model on anonymized clinical notes  
  - RAG pipeline using FAISS + text-embedding-ada-002 for real-time protocol reference  
  - SHAP explainability layer for clinical decision support  
- **Compliance Layer**:  
  - Full audit trail of every patient interaction  
  - Data anonymization before training  
  - GDPR/LGPD-compliant consent logging  
  - Exportable audit reports for regulators

### Status

- Internal prototype only  
- No patient data used  
- No live deployment  
- Designed for future regulatory submission  

---

## 📊 Key Achievements (Verified)

| Achievement | Evidence |
|-----------|----------|
| Launched AI Governance SaaS with R$34,500 MRR | `production-platforms/01_ai_governance_saas/financials/monthly_revenue_2025.xlsx` |
| Reduced inference latency from 810ms → 32ms | `foundations/ml-specialist/nvidia-ai-associate-professional/metrics/inference_latency_comparison.csv` |
| Automated 47 compliance checks across 21 services | `.github/workflows/audit-project-standards.yml` + `governance-framework/automation-runner/` |
| Built 15 reusable policy templates | `governance-framework/policy-templates/*.yaml` |
| Prevented R$4.2M in potential regulatory fines | `foundations/ml-specialist/cds-ibm-cloudera/reports/compliance_impact.pdf` |
| Delivered reproducible ML pipelines with DVC, MLflow, Terraform | All `data-science/`, `foundations/`, and `production-platforms/` directories contain versioned datasets, configs, and logs |

---

## 💼 Professional Experience

### Founder & Director, Technology & Project Solutions  
**Brachat** — Since 2011  

- Founded and maintains Brachat as a legal entity for project ownership and documentation.  
- Led conception and execution of multiple technical projects totaling +R$30M in claimed value.  
- Managed multidisciplinary teams (contractors, developers, domain experts) for SaaS delivery.  
- Oversaw P&L, risk assessment, and stakeholder alignment across initiatives.  
- All deliverables are documented in public repositories — no internal-only systems.

### Compliance Analyst  
**Banco do Brasil** — 2007  

- Performed back-office compliance tasks related to financial operations.  
- Gained foundational understanding of regulatory processes, documentation standards, and risk mitigation.  
- No direct involvement in AI or technology systems during this period.

---

## 🎓 Education

- **Notarial Services Degree** — Graduated (institution not disclosed)  
- **Law Studies** — Completed 8 semesters (focus: regulatory frameworks, civil procedure, administrative law)  

*No degrees conferred in computer science, engineering, or data science.*

---

## 📖 Continuous Learning

- **Applied Data Science Lab** — WorldQuant University (2025) — Certificate issued  
- **Applied AI Lab (Computer Vision)** — WorldQuant University (2025) — Certificate issued  
- **Ongoing Development**:  
  - Hands-on building of SaaS products  
  - Deepening of AI governance tooling (policy-as-code, model registry, audit trails)  
  - Exploration of neurotechnology interfaces and quantum machine learning theory  

*No formal certifications in cloud, ML, or security beyond those listed in public repositories.*

---

## 📫 Contact

- **Email**: fabio@brachat.com.br  
- **LinkedIn**: https://www.linkedin.com/in/fabio-everton-3b62b1129/  
- **GitHub**: https://github.com/fabiobeverton  
- **Portfolio Repository**: https://github.com/brachattech/portifolio  

---

## ⚠️ Disclaimer

This document contains factual claims about systems, metrics, and outcomes.  
All claims are supported by publicly accessible artifacts in the referenced GitHub repositories.  
No external validation has been sought.  
No third-party audits, financial statements, client testimonials, or legal attestations have been provided.  
No claims are made regarding employment status, team size, funding, or institutional affiliation beyond what is documented in source code and metadata.

This is a record of technical work — not a promotional profile.
