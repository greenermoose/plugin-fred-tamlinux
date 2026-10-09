# Acknowledgements — plugin-fred-tamlinux

Researched 2026-10-09. Thank you to the people whose software, designs, maintenance, testing and public reports make this work possible.

Names are ordered alphabetically by the displayed public name (case and accents ignored for sorting). A self-published profile name is used when available; otherwise the public handle or name in an upstream credit is retained. No private identities, locations, phone numbers or commit-email harvesting are included. Affiliations below are self-reported public profile fields or explicitly attributed project roles; they are not independently verified employment records. Contact links and emails are only those publicly offered by the person or their project.

Tamlinux additions are distributed under GPL-3.0-or-later; see [LICENSE](LICENSE). Upstream works retain their own terms. Copyright notices are attributed to works and their stated holders, not inferred from contributor counts. The Free Software Foundation copyright on a GPL/LGPL license document is not treated as ownership of the software. These thanks supplement, and do not replace, required license and source notices.

[UPSTREAM.md](UPSTREAM.md) records this repository’s code ancestry and design references. A runtime dependency, design inspiration, bug report and copied component are different contributions; the entries say which connection is established.

Each named entry identifies an authored component, a documented design influence, a specific change or public report, or responsibility for a foundation used by this repository. Contributor-roster membership alone is not enough for a named entry. Wider communities are credited collectively below.

## People

| Public name and brief background / contribution | Public affiliation and contact |
| --- | --- |
| **David Heinemeier Hansson (`dhh`)** — Creator of Omarchy. Its shell, UI conventions and plugin host form the current base and the documented ancestry of several fred.* components. [Work, license and copyright](#omarchy). [Evidence 1](https://github.com/omacom/omarchy) [Evidence 2](https://github.com/omacom/omawrite) [Evidence 3](https://github.com/omacom/omarchy/commit/b83505d7380bbe0525f56f5dc556c103848d34d5) | 37signals [Public profile / project contact](https://github.com/dhh); [Website](https://dhh.dk); [Public email](mailto:dhh@hey.com) |
| **Fred Horch (`greenermoose`)** — Tamlinux creator and maintainer. Directed this repository’s design, implementation, testing and upstream integration, including the separately documented AI-assisted work. [Evidence](https://github.com/greenermoose/tamlinux) | No affiliation stated in the inspected public profile/credit. [Public profile / project contact](https://github.com/greenermoose) |
| **Guido van Rossum (`gvanrossum`)** — Creator of Python, the interpreter and standard library used by the suite’s command and data helpers. [Work, license and copyright](#python). [Evidence](https://www.python.org/doc/essays/foreword/) | Microsoft [Public profile / project contact](https://github.com/gvanrossum); [Website](https://python.org/~guido/) |
| **HANCORE (`HANCORE-linux`)** — Marketplace maintainer and named public reviewer. Feedback on subprocess supervision, bounded calendar input and safe cache writes shaped the clock’s hardening and shared suite patterns. [Work, license and copyright](#marketplace). [Evidence](https://github.com/omacom/omarchy-plugin-marketplace/issues/6509#issuecomment-5647408125) | No affiliation stated in the inspected public profile/credit. [Public profile / project contact](https://github.com/HANCORE-linux) |
| **Ryan Hughes (`ryanrhughes`)** — Omarchy shell and plugin-system contributor. The v4.0.4 history records work on widget scaling, theme tokens, built-in plugins and plugin management. [Work, license and copyright](#omarchy). [Evidence 1](https://github.com/omacom/omarchy) [Evidence 2](https://github.com/omacom/omarchy/commit/4f0bdb790b75603a6506daa6603b3576349373d6) [Evidence 3](https://github.com/omacom/omarchy/commit/e8fc2ef08f3aad9f6219b85a8ab8884f27fc953a) | Oodle [Public profile / project contact](https://github.com/ryanrhughes); [Website](https://heyoodle.com); [Public email](mailto:ryan@heyoodle.com) |

## Works, licenses and stated copyright notices

The source links below are the authority for complete notices and exceptions. A short notice here is a reference, not a replacement license text. Names in a copyright notice are reproduced as the holder wrote them even when the person now uses a different public display name.

<a id="omarchy"></a>
### Omarchy

- **Connection:** Current Tamlinux 0.x base, shell/plugin integration, and documented cloned components.
- **License:** MIT. [License/source notices](https://github.com/omacom/omarchy/blob/quattro/LICENSE).
- **Stated copyright / limits:** Copyright (c) David Heinemeier Hansson
- **Source:** [Upstream project](https://github.com/omacom/omarchy). [Wider contributor community](https://github.com/omacom/omarchy/graphs/contributors).

<a id="marketplace"></a>
### Omarchy Plugin Marketplace

- **Connection:** Plugin registry, distribution discovery and public security review.
- **License:** MIT. [License/source notices](https://github.com/omacom/omarchy-plugin-marketplace/blob/main/LICENSE).
- **Stated copyright / limits:** Copyright (c) 2026 HANCORE
- **Source:** [Upstream project](https://github.com/omacom/omarchy-plugin-marketplace). [Wider contributor community](https://github.com/omacom/omarchy-plugin-marketplace/graphs/contributors).

<a id="python"></a>
### Python

- **Connection:** Interpreter and standard library used by the Tamlinux helper programs.
- **License:** PSF License Version 2 and historical bundled notices. [License/source notices](https://docs.python.org/3/license.html).
- **Stated copyright / limits:** Python Software Foundation and the historical holders recorded in the license.
- **Source:** [Upstream project](https://docs.python.org/3/license.html).

## Community credit and coverage

We also thank the wider upstream communities: reviewers, translators, documentation writers, package maintainers, testers, issue reporters and accessibility contributors. The project/community links above recognize their wider work. This researched list emphasizes identifiable connections to this repository; it is not a complete census of every transitive dependency or a claim of endorsement. Public profiles and affiliations can change; the date above identifies this review.

The [Qt contributors](https://code.qt.io/), [Wayland contributors](https://gitlab.freedesktop.org/wayland/wayland), [Arch package maintainers](https://archlinux.org/people/) and their dependency communities provide additional foundations. Their licenses and copyright notices remain in the individual upstream projects and installed packages; no blanket ownership or single license is assigned to those communities.

The broader alphabetical list for the public Tamlinux ecosystem, including design, data, typeface, toolchain and planned-base contributions, is in [Tamlinux’s acknowledgements](https://github.com/greenermoose/tamlinux/blob/main/ACKNOWLEDGEMENTS.md).

To correct a name, attribution, affiliation or contact preference, please open an issue in this repository or contact [Fred’s public account](https://github.com/greenermoose). Only evidence-backed additions should be made; do not infer identities behind pseudonyms.

Research and compilation were AI-assisted by Codex under Fred’s direction. AI systems and provider organizations are not listed as humans; existing AI provenance records, where present, describe their separate role.
