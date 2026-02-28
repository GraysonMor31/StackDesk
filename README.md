# StackDesk

**StackDesk** is an open-source, Kubernetes-native, self-hosted operations platform designed specifically for small to mid-sized IT and cybersecurity consultancies.

It unifies business operations and IT service management into a single, security-first platform built for modern DevOps and DevSecOps environments.

---

## 🚀 Overview

StackDesk bridges the gap between operational tooling and business management.  
Instead of forcing consultancies to stitch together multiple SaaS products, StackDesk provides a cohesive, infrastructure-aware platform that runs natively on Kubernetes.

Built with security, auditability, and multi-client isolation at its core, StackDesk enables consultancies to operate like a platform — not just a service desk.

---

## 🔐 Security-First by Design

StackDesk is architected around a zero-trust model:

- Role-Based Access Control (RBAC) with per-client scope
- Multi-client data isolation
- Immutable audit logging
- Secure authentication (JWT, MFA-ready)
- Rate limiting and API validation
- Containerized, non-root runtime
- Designed for hardened Kubernetes deployment

Security is not an add-on — it is foundational.

---

## 🖥 IT Operations

### Multi-Client Ticketing
- Client-scoped ticket queues
- Priority and SLA tracking
- Internal vs client-visible notes
- Time tracking per ticket
- Attachments and audit history

### Asset & Infrastructure Management
- Workstations, servers, firewalls, cloud resources, SaaS tracking
- Warranty and lifecycle tracking
- Tagging and ownership assignment
- Expiration alerts

### Domain & Certificate Management
- Domain registration tracking
- SSL certificate expiration monitoring
- Renewal reminders

### Internal Compliance Management
- Control and policy tracking
- Evidence storage
- Risk register
- Audit export capabilities

### Remote Access Tracking
- Multi-client remote access references
- Secure metadata tracking (no plaintext secrets stored)

---

## 💼 Business Operations

### Timekeeping
- Manual and timer-based entries
- Billable vs non-billable tracking
- Client and ticket association

### Invoicing
- Invoice generation from time entries
- Manual line items
- Tax support
- Status tracking (Draft, Sent, Paid, Overdue)
- PDF and CSV export

### Expense Management
- CAPEX and OPEX categorization
- Receipt attachments
- Approval workflows
- Client assignment

### Employee Lifecycle Management
- Role tracking
- Employment status history
- Onboarding and offboarding checklists
- Certification and training tracking

### CRM (Lightweight)
- Client contact management
- Notes and relationship tracking

---

## 🤖 Extensible & AI-Ready

StackDesk is designed with pluggable integrations:

- Self-hosted AI agents
- GitHub integration
- OnlyOffice integration
- Future API-first external integrations

AI functionality is optional and sandboxed, ensuring secure operation in controlled environments.

---

## ⚙️ Kubernetes-Native Architecture

StackDesk is built to run on Kubernetes by default:

- API service
- Frontend service
- Background workers
- PostgreSQL
- Redis
- Object storage
- Prometheus-compatible metrics endpoint

Designed for GitOps workflows and secure CI/CD pipelines.

---

## 📊 Observability

- Structured JSON logging
- Prometheus metrics
- Health check endpoints
- Audit log export
- Designed for Grafana dashboards

---

## 🎯 Mission

StackDesk exists to help IT and cybersecurity consultancies operate securely, efficiently, and independently — without SaaS lock-in.

Operate your stack. Secure your business. Do it all, just easier.
