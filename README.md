<div align="center">

# <span style="color:#00e5ff; font-family: monospace; font-size: 2.2rem; font-weight: 700;">Abhishek Gali</span>

**Systems Security, Distributed Backend & Forward Deployed Engineer**  
*Specializing in Zero-Trust Architectures, Resilient Event Gateways, Agentic Tool Runtimes, and Applied ML Systems*

<br/>

[![GitHub Activity](https://img.shields.io/badge/Commits-Verified_GPG-34D399?style=flat-square&logo=git&logoColor=white)](#)
[![Python](https://img.shields.io/badge/Runtime-Python_3.11+-3776AB?style=flat-square&logo=python&logoColor=white)](#)
[![FastAPI](https://img.shields.io/badge/API-FastAPI_Async-009688?style=flat-square&logo=fastapi&logoColor=white)](#)
[![PostgreSQL](https://img.shields.io/badge/Store-PostgreSQL_/_Async_SQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)](#)
[![Linux](https://img.shields.io/badge/Core-Linux_/_Kernel_Hooks-FCC624?style=flat-square&logo=linux&logoColor=black)](#)
[![Docker](https://img.shields.io/badge/Deploy-OCI_Containers-2496ED?style=flat-square&logo=docker&logoColor=white)](#)

<br/>

<!-- Engineering Stack & Target Roles -->
<table>
  <tr>
    <td align="right"><b>Target Engineering Roles</b></td>
    <td>
      <img src="https://img.shields.io/badge/Systems_Security_Engineer-0A66C2?style=flat-square" />
      <img src="https://img.shields.io/badge/Backend_&_Distributed_Systems-009688?style=flat-square" />
      <img src="https://img.shields.io/badge/Forward_Deployed_Engineer_(FDE)-4F46E5?style=flat-square" />
      <img src="https://img.shields.io/badge/DevSecOps_&_AppSec_Engineer-10B981?style=flat-square" />
    </td>
  </tr>
  <tr>
    <td align="right"><b>Core Systems & Security</b></td>
    <td>
      <img src="https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white" />
      <img src="https://img.shields.io/badge/Zero--Trust_NIST_800--207-00599C?style=flat-square" />
      <img src="https://img.shields.io/badge/HMAC--SHA256_&_SSRF_Defense-111827?style=flat-square" />
      <img src="https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white" />
      <img src="https://img.shields.io/badge/Ghidra-000000?style=flat-square&logo=reversing&logoColor=white" />
      <img src="https://img.shields.io/badge/OWASP_Top_10-000000?style=flat-square&logo=owasp&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td align="right"><b>Agentic & Inference</b></td>
    <td>
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
      <img src="https://img.shields.io/badge/LangGraph-FF4B4B?style=flat-square" />
      <img src="https://img.shields.io/badge/Model_Context_Protocol-000000?style=flat-square" />
      <img src="https://img.shields.io/badge/Ollama_Runtimes-000000?style=flat-square&logo=ollama&logoColor=white" />
      <img src="https://img.shields.io/badge/PyTorch_Inference-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td align="right"><b>Distributed & Platform Infra</b></td>
    <td>
      <img src="https://img.shields.io/badge/PostgreSQL_/_SQLAlchemy-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
      <img src="https://img.shields.io/badge/Redis_Lua_Rate_Limiting-DC382D?style=flat-square&logo=redis&logoColor=white" />
      <img src="https://img.shields.io/badge/Prometheus_Telemetry-E6522C?style=flat-square&logo=prometheus&logoColor=white" />
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
      <img src="https://img.shields.io/badge/Tailscale_Mesh-000000?style=flat-square&logo=tailscale&logoColor=white" />
      <img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white" />
      <img src="https://img.shields.io/badge/Godot_Engine-478CBF?style=flat-square&logo=godotengine&logoColor=white" />
    </td>
  </tr>
</table>

</div>

---

### 🛡️ Engineering Focus & Capabilities

I engineer deterministic systems at the intersection of **defensive cybersecurity, distributed backend infrastructure, and autonomous agent orchestration**. My work focuses on replacing fragile scripts with production-grade runtimes:

- **Resilient Event Gateways & Distributed Queueing:** Engineering cryptographically verified webhook ingestion and multi-provider delivery engines with raw-byte HMAC-SHA256 verification, bounded payload replay detection, SQL-backed durable job queues with monotonic fencing tokens (`FOR UPDATE SKIP LOCKED`), connect-time DNS SSRF guards, and Dead Letter Queue (DLQ) replay.
- **Zero-Trust Identity & Agent Authorization:** Enforcing strict boundary isolation, cryptographic identity delegation, RBAC/CSRF session controls, and taint analysis for tool-calling agents to prevent Indirect Prompt Injection (IPI).
- **High-Throughput Network Telemetry:** Inspecting layer 4–7 socket and packet streams, measuring packet drop rates, and evaluating systems-level observability via Prometheus metrics and immutable security audit trails.
- **Contract-Aware Security Auditing:** Building asynchronous dynamic scanners and CI/CD DevSecOps pipelines (Gitleaks, Bandit AST, `pip-audit`, SHA-pinned workflows) that enforce deterministic surface hygiene.
- **Game Engine Systems:** Designing deterministic 2D state machines, collision layers, and viewport camera interpolations in Godot.

---

### ⚡ Flagship Architectures & Repositories

| Pillar | System & Repository | Architecture Highlights | Status |
| :--- | :--- | :--- | :---: |
| **01: Event & Webhook Infra** | [**`HookRelay`**](https://github.com/Abhishek-Gali/HookRelay) | Security-hardened webhook ingestion & multi-destination delivery gateway (`GitHub ➔ Discord / Slack / HTTP`). Raw-byte HMAC-SHA256, signed-payload replay guard, durable SQL queue with monotonic fencing tokens, DNS SSRF protection, Redis Lua rate limiting, RBAC/CSRF console, and 64 automated tests. | `Production Ready` |
| **02: Agentic Security** | [**`chloe-agent-core`**](https://github.com/Abhishek-Gali) | Agentic orchestration engine built on FastAPI & LangGraph. Implements MCP tool routing, JSON-RPC schema sanitization, and session state persistence. | `Active` |
| **03: Identity & Defense** | [**`zero-trust-auth-gateway`**](https://github.com/Abhishek-Gali/Intrusion-Prevention-login-managment-system) | Identity-aware authentication proxy with token rotation, brute-force rate-limiting, and NIST SP 800-207 trust boundaries. | `Production Ready` |
| **04: Telemetry & Systems** | [**`packet-inspection-engine`**](https://github.com/Abhishek-Gali/Packet-Sniffer) | Low-level packet ingestion engine with modular protocol dissection (TCP/UDP/ICMP), drop-buffer monitoring, and structured JSON logs. | `Active` |
| **05: Dynamic Auditing** | [**`dynamic-ast-security-scanner`**](https://github.com/Abhishek-Gali/Web-Vulnerability-scanner) | Asynchronous API & web surface fuzzer built on `httpx` with contract-aware fuzzing and boundary resilience. | `Active` |

---

### 🎮 Beyond the Terminal

Systems thinking extends beyond production codebases:
- **Game Mechanics & State Machines:** Developing custom 2D platforming physics in Godot—focusing on tight frame-perfect responsiveness, camera lag damping, and parallax optimization.
- **Complex System Dynamics:** Analyzing combat mechanics, counter-play framing, and system balance in games like *Hollow Knight* and *Wuthering Waves*.
- **Creative & Physical Discipline:** Digital subject masking & post-processing in Affinity Photo, strength training, and deep dives into world-building cultivation structures.

---

<div align="center">
  <sub>All production commits are cryptographically verified • Built with strict operational hygiene</sub>
</div>
