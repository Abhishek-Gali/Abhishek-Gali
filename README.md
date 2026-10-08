# Abhishek Gali

**Systems Security · Distributed Backend · Security Engineering**

I build security-focused backend and distributed systems with an emphasis on reliability, authorization, defensive infrastructure, and failure-aware design.

![Python](https://img.shields.io/badge/Python-3.11%2B-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-Async-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Async-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-OCI-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-Systems-FCC624?style=flat-square&logo=linux&logoColor=black)

---

### What I Care About

I engineer systems where correctness depends on more than the happy path:

- What happens when a worker crashes halfway through a job?
- What happens when the same event arrives twice?
- What happens when two workers claim the same resource?
- What happens when authentication succeeds but authorization should fail?
- What happens when an attacker controls an input that becomes a network request?

I design around those questions.

**Core principles I work by:**
- Make failure explicit and observable
- Treat security as a boundary problem
- Prefer evidence over adjectives (“secure” → what attack, what invariant, what mechanism, what test?)
- Always ask: *what does this system actually guarantee?*

---

### Featured Work

| # | Project | Focus | Highlights |
|---|---------|-------|----------|
| **01** | [**HookRelay**](https://github.com/Abhishek-Gali/HookRelay) | Security-hardened webhook ingestion & multi-destination delivery | Raw-byte HMAC verification, replay protection, durable SQL queue, monotonic fencing tokens, `FOR UPDATE SKIP LOCKED`, DNS-aware SSRF defense, Redis rate limiting, RBAC/CSRF, DLQ, structured observability, automated failure-mode tests |
| **02** | [**Zero-Trust Auth Gateway**](https://github.com/Abhishek-Gali/Intrusion-Prevention-login-managment-system) | Identity-aware authentication & access control | Clear separation of authentication vs authorization, token lifecycle, session controls, brute-force protection, CSRF defenses, trust boundaries |
| **03** | [**chloe-agent-core**](https://github.com/Abhishek-Gali/chloe-agent-core) | Agent security & tool authorization | FastAPI + LangGraph, MCP-style tool routing, JSON-RPC validation, authorization boundaries, prompt/tool separation, focus on Indirect Prompt Injection as an authorization problem |
| **04** | [**Packet-Sniffer**](https://github.com/Abhishek-Gali/Packet-Sniffer) | Packet inspection & network telemetry | TCP/UDP/ICMP processing, structured JSON logging, drop monitoring, systems-level observability |
| **05** | [**Web Vulnerability Scanner**](https://github.com/Abhishek-Gali/Web-Vulnerability-scanner) | Dynamic security testing | Async HTTP execution, contract-aware fuzzing, boundary testing of what interfaces actually accept vs what they claim |

**HookRelay** is the current centerpiece — a durable distributed workflow rather than a simple “receive → forward” endpoint.

---

### Engineering Focus

**Security**  
Application security · Authentication & Authorization · SSRF · Replay attacks · Request signing · CSRF · Rate limiting · Secret management · Supply-chain security · Prompt injection / tool authorization · Zero-trust architecture

**Distributed Systems**  
Durable queues · Worker coordination · Leases & fencing tokens · Idempotency · Retries & dead-letter queues · Concurrency control · Database locking · Failure recovery · Observability

**DevSecOps**  
Gitleaks · Bandit · pip-audit · SHA-pinned GitHub Actions · Automated security tests · Containerized development · Structured logging & metrics

I prefer security controls that run automatically rather than remaining a final manual checklist.

---

### How I Approach a New System

1. **Define the threat model** — Who can control the input? What can they influence?
2. **Define the invariants** — What must never happen?
3. **Define failure modes** — Database down, worker crash, network timeout, duplicated request, malicious input
4. **Implement the smallest correct boundary**
5. **Test the assumptions** — especially the ones that are easy to forget

---

### Selected Stack

**Backend** · Python · FastAPI · AsyncIO · SQLAlchemy · PostgreSQL  
**Infrastructure** · Redis · Docker · Prometheus · GitHub Actions  
**Security** · OWASP · Burp Suite · Ghidra · Bandit · Gitleaks · pip-audit  
**AI / Agents** · LangGraph · MCP · Ollama  
**Systems** · Linux · Networking · Packet inspection

---

### What I’m Looking For

Roles where I can work on:

- Security-sensitive backend systems
- Distributed infrastructure / platform engineering
- Application security & DevSecOps
- Agent infrastructure & tool authorization
- Reliability engineering

I enjoy moving between design, implementation, debugging, security analysis, and deployment.

---

### Current Philosophy

> Don’t just make it work.  
> Understand why it works.  
> Understand when it fails.  
> Make the failure observable.  
> Make the security boundary explicit.  
> Test the assumption.  
> Then optimize it.

**Build systems that remain understandable when everything goes wrong.**
