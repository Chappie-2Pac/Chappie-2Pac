# Christoph Ludwig genannt Grosse

## Applied AI & Agent Systems Engineer

I design and implement AI systems that remain understandable under real-world
constraints: edge hardware, local execution, changing state, model failures,
and the need to explain what happened after a run.

My focus is engineering that can be inspected and tested: deterministic agent
orchestration, local edge AI, provenance-aware data pipelines, security
boundaries, and verification tooling.

My work connects applied AI with serious systems engineering:

- deterministic control planes for AI agents
- provenance-first data preparation and training workflows
- local LLM runtimes and fail-closed preflight checks
- hardware-agnostic voice-assistant architecture
- reproducible tests, receipts, state transitions, and recovery paths

## Selected projects

| Project | What it demonstrates |
|---|---|
| [Optimismus Prime](https://github.com/Chappie-2Pac/optimismus-prime) | SQLite CAS state transitions, lease fencing, deterministic dispatch, receipts, replay handling, and recovery |
| [Chappie](https://github.com/Chappie-2Pac/chappie-public) | Integrated provenance-first data curation, deterministic teaching units, quality gates, and Unsloth/QLoRA training orchestration |
| [Seniorbot](https://github.com/Chappie-2Pac/seniorbot) | ASR → dialogue → local LLM → TTS orchestration with replaceable adapters and bounded state |
| [Odysseus](https://github.com/Chappie-2Pac/odysseus-runtime-profile-public) | Fail-closed loopback runtime preflight for local OpenAI-compatible LLM services |

Chappie combines its orchestration core with an integrated `custom-llm-lab` data-curation layer: source extraction, provenance-aware chunking, teaching-unit generation, validation, review, and export continue into a GPU-first Unsloth/QLoRA training path. The public repository presents the reproducible engineering surface; private datasets, model weights, and runtime artifacts remain outside the public snapshot.

## Verification

- [![Optimismus Prime CI](https://github.com/Chappie-2Pac/optimismus-prime/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/Chappie-2Pac/optimismus-prime/actions/workflows/ci.yml) Full control-plane verification suite: 1,180 tests and 1,216 subtests locally verified
- [![Chappie CI](https://github.com/Chappie-2Pac/chappie-public/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/Chappie-2Pac/chappie-public/actions/workflows/ci.yml) 107 offline tests, package build, and public import smoke test
- [![Seniorbot CI](https://github.com/Chappie-2Pac/seniorbot/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/Chappie-2Pac/seniorbot/actions/workflows/ci.yml) Python 3.10–3.12 test matrix
- [![Odysseus CI](https://github.com/Chappie-2Pac/odysseus-runtime-profile-public/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/Chappie-2Pac/odysseus-runtime-profile-public/actions/workflows/ci.yml) Shell syntax and fail-closed 'BLOCKED' path

## How I approach AI engineering

1. Define the state, contracts, and failure modes before adding model
   capabilities.
2. Keep provenance and evidence close to the data and the execution path.
3. Make safety decisions explicit in code instead of relying on prompt
   conventions.
4. Build the test harness and recovery path as part of the feature.
5. Separate reusable engineering from deployment-specific hardware, data, and
   operations.

## Core technologies

Python · POSIX shell · SQLite · Git · Linux · pytest · local LLM runtimes ·
Unsloth/QLoRA · ASR/TTS adapter design · YAML/JSON workflow contracts ·
provenance and data quality tooling · fail-closed security boundaries

## Roles I am targeting

AI Engineer, LLM Infrastructure Engineer, Applied AI Engineer, Agent Systems
Engineer, Edge AI Engineer, or AI Platform Engineer roles where reliable model
integration and strong software engineering matter equally.

## Portfolio case studies

- [Chappie — data and QLoRA pipeline](https://werkstatt-core.ludwig-grosse484994.chatgpt.site/chappie)
- [Seniorbot — local edge voice assistant](https://werkstatt-core.ludwig-grosse484994.chatgpt.site/seniorbot)
- [Optimismus Prime — agent orchestration](https://werkstatt-core.ludwig-grosse484994.chatgpt.site/optimismus-prime)
- [About my engineering approach](https://werkstatt-core.ludwig-grosse484994.chatgpt.site/about)

## Start here

- Read the [Optimismus Prime architecture](https://github.com/Chappie-2Pac/optimismus-prime#architecture) for the control-plane design.
- Run the [Chappie quickstart](https://github.com/Chappie-2Pac/chappie-public#quickstart) for integrated provenance-aware data preparation and training orchestration.
- Review the [Seniorbot pipeline](https://github.com/Chappie-2Pac/seniorbot#architecture) for edge voice-AI boundaries.
- Inspect the [Odysseus preflight](https://github.com/Chappie-2Pac/odysseus-runtime-profile-public#quickstart) for local runtime safety.

## Contact

Portfolio: [Werkstatt Core on ChatGPT](https://werkstatt-core.ludwig-grosse484994.chatgpt.site/)

LinkedIn: [Christoph Ludwig genannt Grosse](https://linkedin.com/in/christoph-ludwig-enannt-grosse-a7b830452)

Email: [ludwig-grosse@gmx.de](mailto:ludwig-grosse@gmx.de)
