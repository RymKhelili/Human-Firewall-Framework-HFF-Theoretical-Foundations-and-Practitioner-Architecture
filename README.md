# The Human Firewall Framework (HFF)

**A research-grounded approach to social engineering defense, built on cognitive science rather than blame and checklists.**

[![License: All Rights Reserved](https://img.shields.io/badge/License-All%20Rights%20Reserved-red.svg)](LICENSE)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0004--1818--6955-A6CE39?logo=orcid&logoColor=white)](https://orcid.org/0009-0004-1818-6955)

---

## What this is

Most cybersecurity awareness training rests on two assumptions: that people are the "weakest link" in security, and that repeating facts and policies changes behavior under real attack conditions. This repository lays out why both assumptions don't hold up against the research — and builds a practitioner framework, the **Human Firewall Framework (HFF)**, on top of what the research suggests instead.

The project is split into two parts:

| Part | Document | What it covers |
|------|----------|-----------------|
| I | [`docs/01-theoretical-foundations.md`](docs/01-theoretical-foundations.md) | A literature review across information security, cognitive psychology, and behavioral science — covering the "weakest link" trope, controlled trials of awareness training, Cognitive Security, dual-process theory, persuasion science, memory neuroscience, inoculation theory, and behavior change science. |
| II | [`docs/02-human-firewall-framework.md`](docs/02-human-firewall-framework.md) | The applied practitioner architecture built from Part I: four functions (removing blame, teaching mechanism over checklist, inoculation through controlled exposure, and engineering for retention), plus a research-driven, adversarially-tested methodology. |

A planned Part III will map the HFF's four functions onto specific social engineering attack vectors as a case study.

## Why it exists

Both documents are living positions, not finished claims. They're built to be read together: Part I establishes what the evidence says is wrong with conventional awareness training and why; Part II turns that into something a practitioner can actually design and run. Every claim in Part I is sourced to a cited reference; every design choice in Part II is either traced back to a section of Part I or explicitly flagged as reasoned architecture rather than validated outcome data (see Part II, Section 5).

## Status

Both documents are marked as living — expect revisions as the underlying research base grows and as the framework is tested in practice.

## Repository structure

```
.
├── README.md
├── LICENSE
├── CITATION.cff
├── CONTRIBUTING.md
├── .gitignore
└── docs/
    ├── 01-theoretical-foundations.md
    └── 02-human-firewall-framework.md
```

## Citing this work

If you reference this framework or the literature review, please cite it — see [`CITATION.cff`](CITATION.cff) for the machine-readable citation, or cite directly:

> [Your Name]. *The Human Firewall Framework: Theoretical Foundations and Applied Practitioner Architecture.* (2026). https://orcid.org/0009-0004-1818-6955

## License

**All rights reserved.** This is not an open-license (e.g. MIT/CC-BY) project.

You're welcome to **fork this repository and open pull requests** to propose corrections, additions, or new sources — that's the intended way to contribute (see [`CONTRIBUTING.md`](CONTRIBUTING.md)). You may also read and reference this material privately and quote brief excerpts with attribution.

What's **not** permitted without written permission: commercial use, republishing or mirroring this material elsewhere, or presenting it (or an adaptation of it) as your own work.

Full terms are in [`LICENSE`](LICENSE).

## Author

ORCID: [0009-0004-1818-6955](https://orcid.org/0009-0004-1818-6955)
