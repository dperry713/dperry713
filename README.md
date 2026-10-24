<div align="center">
  <h1>Dustin Perry</h1>
  <p><strong>Software Developer & Security Engineer</strong><br>
  Building trustworthy agent infrastructure for the Windows platform</p>

  <a href="https://www.linkedin.com/in/dustin-perry">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://github.com/dperry713">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
  </a>
</div>

---

## Focus

I design and build **hardened, auditable agent runtimes** — systems that treat AI agents as supervised processes rather than free-roaming scripts.

My work prioritizes:
- Deny-by-default policy and capability control
- OS-level isolation
- Full event-sourced audit trails
- Crash recovery and deterministic replay

Security and observability are treated as core runtime concerns, not afterthoughts.

---

## Flagship Project: [AIR — AI Runtime](https://github.com/dperry713/AI_runtime)

**TypeScript** • **Windows** • **Node.js** • **Security-first**

AIR is a production-oriented agent runtime and shell for Windows. It sits between LLM APIs and real system access, providing the isolation, policy, and auditability needed to run agents with confidence.

**Key capabilities:**
- Event-sourced journal with crash recovery and deterministic replay
- Deny-by-default policy engine with taint tracking and human approvals
- OS-level sandboxing (Job Objects + AppContainer)
- Network egress control via Windows Filtering Platform
- Provider-agnostic (Anthropic, OpenAI-compatible, Ollama)
- Structured observability and hash-chained audit log

→ [View the repository](https://github.com/dperry713/AI_runtime)

---

## Technical Stack

- **Languages**: TypeScript (strict), PowerShell, Rust (native helpers)
- **Runtime & Platform**: Node.js 22, Windows 10/11
- **Security**: Job Objects, AppContainer, WFP, Credential Manager, path canonicalization
- **Architecture**: Event sourcing, layered modules, dependency-cruiser enforced boundaries
- **Testing**: 1500+ tests, coverage gates, chaos and security suites

---

## GitHub Activity

Currently focused on **[AIR — AI Runtime](https://github.com/dperry713/AI_runtime)** — a Windows-native agent runtime with event-sourced journaling, deny-by-default policy, and OS-level sandboxing.

**Recent work includes:**
- Windows security hardening (WFP egress control, AppContainer isolation, Credential Manager)
- Daemon + named-pipe IPC + interactive shell
- 1500+ tests with coverage gates and security/chaos suites
- Strict layered architecture enforced by dependency-cruiser

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=dperry713&layout=compact&theme=radical)
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=dperry713&show_icons=true&theme=radical&hide_title=true)
---

## Contact

- **LinkedIn**: [linkedin.com/in/dustin-perry](https://www.linkedin.com/in/dustin-perry)
- **Email**: dperry713@gmail.com
- **Open to**: Security-focused engineering roles and agent infrastructure work

---

*“Agents should be managed like processes — isolated, observable, and recoverable.”*
