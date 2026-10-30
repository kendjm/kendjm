<div align="center">

# Joel Díaz

**Founder of [Gap Hunter Labs](https://github.com/GapHunterLabs)** · Developer tools, static analysis and root-cause research

[![gaphunterlabs.com](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/website.svg)](https://gaphunterlabs.com)
[![GapHunterLabs on GitHub](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/org.svg)](https://github.com/GapHunterLabs)
[![JetBrains Marketplace](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/jetbrains-marketplace.svg)](https://plugins.jetbrains.com/vendor/gap-hunter-labs)
[![VS Code Marketplace](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/vscode-marketplace.svg)](https://marketplace.visualstudio.com/publishers/GapHunterLabs)
[![@GapHunterLabs on X](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/x.svg)](https://x.com/GapHunterLabs)
[![Email contact@gaphunterlabs.com](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/contact.svg)](mailto:contact@gaphunterlabs.com)
[![Sponsor the work](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/sponsor.svg)](https://gaphunterlabs.com/sponsors/)

</div>

---

## About

Trained in systems engineering, with a background in industrial operations and logistics.
Today I build software under one operating principle: rigorous quality control, full
traceability, and validation based on real-world data.

I run [Gap Hunter Labs](https://gaphunterlabs.com), an independent practice that ships
local-first tooling for JetBrains IDEs and VS Code, and does root-cause research in
performance, security and reliability.

I'm open to consulting engagements and select opportunities.

## Stack

| Layer | What I use |
| --- | --- |
| **Platforms** | ![JetBrains IDEs](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/stack-jetbrains-ides.svg) ![IntelliJ IDEA](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/stack-intellij-idea.svg) ![VS Code](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/stack-vscode.svg) ![Windows](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/stack-windows.svg) |
| **Languages** | ![Kotlin](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/stack-kotlin.svg) ![Java](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/stack-java.svg) ![Python](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/stack-python.svg) ![HTML](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/stack-html.svg) ![CSS](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/stack-css.svg) ![SQL](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/stack-sql.svg) |
| **Disciplines** | ![Static analysis](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/stack-static-analysis.svg) ![Performance](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/stack-performance.svg) ![Security research](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/stack-security-research.svg) ![Reliability](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/stack-reliability.svg) |
| **Tooling** | ![Gradle](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/stack-gradle.svg) ![JUnit](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/stack-junit.svg) ![Git](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/stack-git.svg) ![GitHub](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/stack-github.svg) ![GitHub Actions](https://raw.githubusercontent.com/GapHunterLabs/.github/main/profile/badges/stack-github-actions.svg) |

## What I work on

| Area | What it means in practice |
| --- | --- |
| **IDE tooling** | Plugins for IntelliJ Platform IDEs and extensions for VS Code, built local-first. |
| **Static analysis** | Detectors for real defects: blocking calls on the EDT, missing cancellation checks, unsafe defaults. |
| **Root-cause research** | Reproduce first, measure before and after, then report with evidence. |
| **Reliability and security** | Dependency advisories, misconfiguration patterns, performance regressions. |

## Evidence

I reported this work upstream to the IntelliJ Platform, with measurements taken before and
after the change:

| Ticket | Pull request | Outcome |
| --- | --- | --- |
| [IJPL-257919](https://youtrack.jetbrains.com/issue/IJPL-257919) | [#3696](https://github.com/JetBrains/intellij-community/pull/3696) | Fixed; blocking time cut from ~2.2 s to ~0–1 ms. Integrated upstream. |
| [IJPL-257909](https://youtrack.jetbrains.com/issue/IJPL-257909) | [#3701](https://github.com/JetBrains/intellij-community/pull/3701) | 689–931 ms down to 8–22 ms. Open. |
| [IJPL-257908](https://youtrack.jetbrains.com/issue/IJPL-257908) | [#3694](https://github.com/JetBrains/intellij-community/pull/3694) | 157 ms down to 0 ms. Open. |
| [IDEA-393501](https://youtrack.jetbrains.com/issue/IDEA-393501) | — | Fixed by JetBrains on October 28, 2026. |

The full list, with my methodology, is on [gaphunterlabs.com](https://gaphunterlabs.com).

## Tools

What I publish lives under the [GapHunterLabs](https://github.com/GapHunterLabs)
organization, on the
[JetBrains Marketplace](https://plugins.jetbrains.com/vendor/gap-hunter-labs) and on the
[VS Code Marketplace](https://marketplace.visualstudio.com/publishers/GapHunterLabs):

- **[Mermaid Companion](https://gaphunterlabs.com/catalog/mermaid-companion/)** — syntax highlighting and real syntax validation for `.mmd` / `.mermaid` files.
- **[Refactor Simulator](https://gaphunterlabs.com/catalog/refactor-simulator/)** — preview a refactoring in an isolated, in-memory sandbox before you commit it.
- **[ghl-jail](https://gaphunterlabs.com/ghl-jail/)** — run a command-line tool so it can only touch one project folder, not your secrets. Windows, no admin rights, no install.

## Sponsors

**No sponsors yet.** When someone backs this work, I list them here by name, with their
permission.

If you or your company rely on these tools and want to support their maintenance, see
[gaphunterlabs.com/sponsors](https://gaphunterlabs.com/sponsors/) or write to me at
[contact@gaphunterlabs.com](mailto:contact@gaphunterlabs.com).

<!-- Sponsors go here. Add one line per sponsor: [Name](url) -->

## Get in touch

- Website: [gaphunterlabs.com](https://gaphunterlabs.com)
- Email: [contact@gaphunterlabs.com](mailto:contact@gaphunterlabs.com)
- X: [@GapHunterLabs](https://x.com/GapHunterLabs)
- Organization: [GapHunterLabs](https://github.com/GapHunterLabs)
