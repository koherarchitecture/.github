# koherarchitecture

**AI handles language. Code handles judgement. Humans make decisions.**

---

Koher is a philosophy for building AI tools that respect domain expertise rather than replace it.

Every tool here separates language from judgement:

| Layer | What It Does |
|-------|-------------|
| **Qualification** | AI reads language patterns, transforms unstructured input into structured signals |
| **Rules** | Code handles judgement — deterministic logic produces auditable decisions |
| **Language** | AI narrates decisions already made |

When you ask AI to "judge whether this is good," you lose auditability. When you separate the layers, you gain it back. The split has a name — Split-Domain Cognition (SDC) — and a public DOI: [`10.5281/zenodo.19661700`](https://doi.org/10.5281/zenodo.19661700).

---

## Open Tools

Small tools demonstrating the architecture. Each grounded in student conversations before development. Open source — clone the repo, bring your own API key, run locally. Hosted demos run 10 free analyses per day per browser, with no account and no email.

| Tool | What It Does | Released | Licence |
|------|-------------|----------|---------|
| [Sensorium — Sycophancy](https://github.com/koherarchitecture/sensorium) | Map how a language model handles five sycophancy triggers — desktop app for macOS and Linux | May 2026 | AGPL-3.0 |
| [Fragment Mapper](https://github.com/koherarchitecture/fragment-mapper) | See structural relationships between scattered text fragments | March 2026 | MIT |
| [Play Shape Diagnostic](https://github.com/koherarchitecture/play-shape-diagnostic) | Analyse experiential qualities of play concepts | February 2026 | MIT |
| [Coherence Diagnostic](https://github.com/koherarchitecture/coherence-diagnostic) | Analyse design concepts for coherence | February 2026 | MIT |

Tools released up to 5 April 2026 are MIT. Every tool published after is AGPL-3.0.

---

## The Architecture

```
┌─────────────────────────────────────────────────────────────┐
│  Q · Qualification                                          │
│  Transform unstructured input into structured signals       │
│  Principle: AI reads language patterns                      │
└─────────────────────────────────────────────────────────────┘
                              ↓
┌─────────────────────────────────────────────────────────────┐
│  R · Rules                                                  │
│  Apply thresholds, evaluate relationships, produce verdicts │
│  Principle: Code handles judgement                          │
└─────────────────────────────────────────────────────────────┘
                              ↓
┌─────────────────────────────────────────────────────────────┐
│  L · Language                                               │
│  Translate rule outputs into readable explanation           │
│  Principle: AI narrates decisions already made              │
└─────────────────────────────────────────────────────────────┘
```

---

## Links

- **Website:** [koher.app](https://koher.app)
- **Architecture paper (Zenodo):** [`10.5281/zenodo.19661700`](https://doi.org/10.5281/zenodo.19661700)
- **SDC site:** [splitdomaincognition.org](https://splitdomaincognition.org)
- **Contact:** hello@koher.app

---

*Co-created by [Prayas Abhinav](https://prayasabhinav.net) + [Claude Code](https://claude.ai/code)*
