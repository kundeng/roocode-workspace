```markdown
# roocode‑workspace

A powerful, flexible VS Code workspace template for Roo Code developers.  
Combines SPARC orchestration, RooFlow memory bank & boomerang mode, and AI‑assisted workflows to minimize token usage and maximize productivity.

---

## Features

- **Persistent Memory Bank**: Automatically maintains project context across sessions.  
- **SPARC Orchestrator**: Breaks down objectives into secure, modular subtasks.  
- **Boomerang Mode**: Coordinates tasks across specialized modes and tracks results.  
- **Fine‑Tuned Modes**: From architecture to testing, security review to DevOps, all modes read/write the memory bank to stay in sync.

---

## Quick Start

1. **Create from Template**  
   Click **Use this template** on the [roocode‑workspace repo](https://github.com/enescingoz/roocode-workspace).

2. **Clone & Open**  
   ```bash
   git clone https://github.com/<your‑org>/<your‑repo>.git
   code <your‑repo>
   ```

3. **Select Mode**  
   In the bottom‑left of VS Code, choose **Architect Mode** for first‑time setup.

4. **Initialize Memory Bank**  
   In RooCode chat, run:
   ```
   initialize memory bank
   ```
   → Creates `memory-bank/` with all core Markdown files.

5. **Update Memory Bank**  
   Any time you need to sync:
   ```
   Update Memory Bank
   ```
   or
   ```
   UMB
   ```

6. **Develop**  
   Switch modes (Code, TDD, Debug, etc.) as you work. The memory bank keeps every session aligned.

---

## Modes Overview

| Mode                              | Role                                                                      |
|-----------------------------------|---------------------------------------------------------------------------|
| ⚡️ **SPARC Orchestrator**         | Breaks objectives into SPARC‑aligned subtasks                             |
| 📋 **Specification & Pseudocode**  | Captures project context and outputs modular pseudocode with TDD anchors  |
| 🏗️ **Architect**                  | Designs system diagrams, data flows, API boundaries                       |
| 🧠 **Code**                        | Implements clean, modular code with externalized configs                  |
| 🧪 **TDD**                         | Drives development via failing tests → minimal code → refactor            |
| 🪲 **Debug**                       | Troubleshoots runtime issues with logging & analysis                      |
| 🛡️ **Security Reviewer**          | Audits for vulnerabilities, exposed secrets, and non‑modular code         |
| 📚 **Documentation Writer**        | Produces clear, concise Markdown docs                                     |
| 🔗 **Integrator**                 | Merges all outputs into a cohesive, secure final product                  |
| 📈 **Post‑Deployment Monitor**     | Collects metrics & feedback for continuous improvement                    |
| 🧹 **Optimizer**                   | Refactors for performance and maintainability                             |
| ❓ **Ask**                         | Guides users in formulating precise, modular requests                     |
| 🚀 **DevOps**                      | Automates secure CI/CD and infrastructure ops                             |
| 📘 **SPARC Tutorial**              | Teaches SPARC process, mode‑to‑mode handoffs, and best practices          |
| 🪃 **Boomerang**                   | Coordinates complex workflows across modes with memory tracking           |

---

## Memory Bank Structure

All project knowledge lives in `memory-bank/` at the repo root. Core files (must exist) load in this order:

1. **productContext.md**  
   High‑level goals, problems, and UX vision.

2. **projectBrief.md**  
   Core requirements, scope, and source of truth.

3. **technical.md**  
   Architecture, patterns, APIs, stack, and integration specs.

4. **README.md**  
   Usage guide, setup, and troubleshooting.

5. **progress.md**  
   Sprint‑by‑sprint progress (append‑only, newest entries at top).

6. **activeContext.md**  
   Current sprint focus, blockers, and next steps (append‑only).

<details>
<summary>Optional & Extended Context Files</summary>

- **decisionLog.md**: Architectural and implementation decisions.  
- **systemPatterns.md**: Recurring coding or architectural patterns.  
- **apiSpecs.md**: Detailed API contracts and examples.  
- **testPlan.md**: Testing strategies and results.  
- **deployment.md**: Deployment procedures and configurations.  

</details>

---

## Sources & Credits

- **RooFlow 0.3.6** — https://github.com/GreatScottyMac/RooFlow  
- **roocode‑modes** — https://github.com/enescingoz/roocode-modes  
- “Boomerang Tasks & SPARC” by Reuven Cohen — https://www.linkedin.com/pulse/boomerang-tasks-automating-code-development-roo-sparc-reuven-cohen-nr3zc  

---

## License

[Apache 2.0](https://github.com/enescingoz/roocode-workspace/blob/main/LICENSE)

---

☕ Like this work? [Buy me a coffee](https://buymeacoffee.com/enescingoz)  
```
