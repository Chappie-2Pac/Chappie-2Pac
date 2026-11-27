# Hi, I'm Chappie-2Pac

Building deterministic, local-first AI systems—focused on zero-trust agent control planes, provenance-bound model training, and offline edge voice pipelines.

### Core Architecture & Repositories

| Repository | Focus | Key Guarantees |
| :--- | :--- | :--- |
| **[optimismus-prime](https://github.com//Chappie-2Pac/optimismus-prime)** | Deterministic control plane for local AI & Codex-style agents | SQLite CAS transitions, monotonic lease fencing, fail-closed path policy, durable receipts |
| **[chappie-public](https://github.com/Chappie-2Pac/chappie-public)** | Provenance-first teaching-data & QLoRA workflow core | Character-span provenance, manifest-bound checkpoints, credential-free access guard |
| **[seniorbot](https://github.com/Chappie-2Pac/seniorbot)** | Hardware-agnostic voice-assistant core for Jetson-class edge devices | Deterministic ASR→LLM→TTS routing, bounded memory, `s6-rc` service contracts |

### Design Philosophy

- **Local-First & Offline-Capable:** Core logic, state machines, and test suites run without cloud dependencies, external credentials, or network access.
- **Contracts Over Prompt Conventions:** State transitions, data provenance, and hardware boundaries are enforced in code—never left to model guesswork.
- **Clean Public/Private Boundaries:** Public repositories isolate deterministic architecture and verification harnesses from private hardware labs, training runs, and runtime artifacts.

---

🌐 **Project Showcase:** [werkstatt-core.ludwig-grosse484994.chatgpt.site]([https://chatgpt.site](https://werkstatt-core.ludwig-grosse484994.chatgpt.site/))
