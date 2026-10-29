<div align="center">

# Joel Díaz

**Founder of [Gap Hunter Labs](https://github.com/GapHunterLabs)** · Developer tools, static analysis and root-cause research

[![Website](https://img.shields.io/badge/website-gaphunterlabs.com-0a0a0a?style=flat-square&logo=cloudflare&logoColor=F38020)](https://gaphunterlabs.com)
[![Organization](https://img.shields.io/badge/org-GapHunterLabs-0a0a0a?style=flat-square&logo=github&logoColor=white)](https://github.com/GapHunterLabs)
[![X](https://img.shields.io/badge/X-@GapHunterLabs-0a0a0a?style=flat-square&logo=x&logoColor=white)](https://x.com/GapHunterLabs)
[![Email](https://img.shields.io/badge/contact-gaphunterlabs.com-0a0a0a?style=flat-square&logo=gmail&logoColor=white)](mailto:contact@gaphunterlabs.com)

</div>

---

## About

Trained in systems engineering, with a background in industrial operations and logistics.
Today I build software under one operating principle: rigorous quality control, full
traceability, and validation based on real-world data.

I run [Gap Hunter Labs](https://gaphunterlabs.com), an independent practice that ships
local-first tooling for JetBrains IDEs and VS Code, and does root-cause research in
performance, security and reliability.

Open to consulting engagements and select opportunities.

## What I work on

| Area | What it means in practice |
| --- | --- |
| **IDE tooling** | Plugins for IntelliJ Platform IDEs and extensions for VS Code, built local-first. |
| **Static analysis** | Detectors for real defects: blocking calls on the EDT, missing cancellation checks, unsafe defaults. |
| **Root-cause research** | Reproduce first, measure before and after, then report with evidence. |
| **Reliability and security** | Dependency advisories, misconfiguration patterns, performance regressions. |

## Evidence

Work reported upstream to the IntelliJ Platform, with measurements taken before and after
the change:

| Ticket | Pull request | Outcome |
| --- | --- | --- |
| [IJPL-257919](https://youtrack.jetbrains.com/issue/IJPL-257919) | [#3696](https://github.com/JetBrains/intellij-community/pull/3696) | Fixed; blocking time cut from ~2.2 s to ~0–1 ms. Integrated upstream. |
| [IJPL-257909](https://youtrack.jetbrains.com/issue/IJPL-257909) | [#3701](https://github.com/JetBrains/intellij-community/pull/3701) | 689–931 ms down to 8–22 ms. Open. |
| [IJPL-257908](https://youtrack.jetbrains.com/issue/IJPL-257908) | [#3694](https://github.com/JetBrains/intellij-community/pull/3694) | 157 ms down to 0 ms. Open. |
| [IDEA-393501](https://youtrack.jetbrains.com/issue/IDEA-393501) | — | In progress on the JetBrains side. |

The full list, with methodology, lives on [gaphunterlabs.com](https://gaphunterlabs.com).

## Tools

What I publish lives under the [GapHunterLabs](https://github.com/GapHunterLabs)
organization and on the
[JetBrains Marketplace](https://plugins.jetbrains.com/vendor/gap-hunter-labs):

- **Mermaid Companion** — syntax highlighting and real syntax validation for `.mmd` / `.mermaid` files.
- **Refactor Simulator** — preview a refactoring in an isolated, in-memory sandbox before you commit it.
- **ghl-jail** — run a command-line tool so it can only touch one project folder, not your secrets. Windows, no admin rights, no install.

## Sponsors

**No sponsors yet.** This space is reserved for the people and companies that back this
work, and they will be listed here by name.

If you or your company rely on these tools and want to support their maintenance, write
to [contact@gaphunterlabs.com](mailto:contact@gaphunterlabs.com).

<!-- Sponsors go here. Add one line per sponsor: [Name](url) -->

## Get in touch

- Website: [gaphunterlabs.com](https://gaphunterlabs.com)
- Email: [contact@gaphunterlabs.com](mailto:contact@gaphunterlabs.com)
- X: [@GapHunterLabs](https://x.com/GapHunterLabs)
- Organization: [GapHunterLabs](https://github.com/GapHunterLabs)
