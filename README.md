# MEDICAL_AI

![licence](https://img.shields.io/badge/licence-Apache-2.0-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![checks](https://img.shields.io/badge/checks-unknown_PASS-brightgreen)

> Governed Anticloud packaging of the upstream project `MEDICAL_AI` in category **MEDICAL_HEALTH**. check results: see ISOLATED_LAB_RESULTS. Every number below traces to a named file + run stamp; nothing is borrowed from other projects.

**Upstream:** MEDICAL_AI · **Upstream pin:** `a7904ae138c01cc90ad9c3bdf52c10218bde315f` · **Category:** MEDICAL_HEALTH · **Vendor:** Anticloud FZ LLE · **Licence:** Apache-2.0

---

## What This Project Does

<p align="center">
<img src="https://raw.githubusercontent.com/Project-MONAI/MONAI/dev/docs/images/MONAI-logo-color.png" width="50%" alt='project-monai'>
</p>

**M**edical **O**pen **N**etwork for **AI**

![Supported Python versions](https://raw.githubusercontent.com/Project-MONAI/MONAI/dev/docs/images/python.svg)
[![License](https://img.shields.io/badge/license-Apache%202.0-green.svg)](https://opensource.org/licenses/Apache-2.0)
[![auto-commit-msg](https://img.shields.io/badge/dynamic/json?label=citations&query=%24.citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2FDOI%3A10.48550%2FarXiv.2211.02701%3Ffields%3DcitationCount)](https://arxiv.org/abs/2211.02701)
[![PyPI version](https://badge.fury.io/py/monai.svg)](https://badge.fury.io/py/monai)
[![docker](https://img.shields.io/badge/docker-pull-green.svg?logo=docker&logoColor=white)](https://hub.docker.com/r/projectmonai/monai)
[![conda](https://img.shields.io/conda/vn/conda-forge/monai?color=green)](https://anaconda.org/conda-forge/monai)

[![premerge](https://github.com/Project-MONAI/MONAI/actions/workflows/pythonapp.yml/badge.svg?branch=dev)](https://github.com/Project-MONAI/MONAI/actions/workflows/pythonapp.yml)
[![postmerge](https://img.shields.io/github/checks-status/project-monai/monai/dev?label=postmerge)](https://github.com/Project-MONAI/MONAI/actions?query=branch%3Adev)
[![Documentation Status](https://readthedocs.org/projects/monai/badge/?version=latest)](https://monai.readthedocs.io/en/latest/)
[![codecov](https://codecov.io/gh/Project-MONAI/MONAI/branch/dev/graph/badge.svg?token=6FTC7U1JJ4)](https://codecov.io/gh/Project-MONAI/MONAI)
[![monai Downloads Last Month](https://assets.piptrends.com/get-last-month-downloads-badge/monai.svg 'monai Downloads Last Month by pip Trends')](https://piptrends.com/package/monai)

MONAI is a [PyTorch](https://pytorch.org/)-based, [open-source](https://github.com/Project-MONAI/MONAI/blob/dev/LICENSE) framework for deep learning in healthcare imaging, part of the [PyTorch Ecosystem](https://pytorch.org/ecosystem/).
Its ambitions are as follows:

- Developing a community of academic, industrial and clinical researchers collaborating on a common foundation;
- Creating state-of-the-art, end-to-end training workflows for healthcare imaging;
- Providing researchers with the optimized and standardized way to create and evaluate deep learning models.

## Features

> _Please see [the technical highlights](https://monai.readthedocs.io/en/latest/highlights.html) and [What's New](https://monai.readthedocs.io/en/latest/whatsnew.html) of the milestone releases._

- flexible pre-processing for multi-dimensional medical imaging data;
- compositional & portable APIs for ease of integration in existing workflows;
- domain-specific implementations for networks, losses, evaluation metrics and more;
- customizable design for varying user expertise;
- multi-GPU multi-node data parallelism support.

## Requirements

MONAI works with the [currently supported versions of Python](https://devguide.python.org/versions), and depends directly on NumPy and PyTorch with many optional dependencies.

* Major releases of MONAI will have dependency versions stated for them. The current state of the `dev` branch in this project is the unreleased development version of MONAI which typically will support current versions of dependencies and include updates and bug fixes to do so.
* PyTorch support covers [the current version](https://github.com/pytorch/pytorch/releases) plus three previous minor versions. If compatibility issues with a PyTorch version and other dependencies arise, support for a version may be delayed until a major release.
* Our support policy for other dependencies adheres for the most part to [SPEC0](https://scientific-python.org/specs/spec-0000), where dependency versions are supported where possible for up to two years. Discovered vulnerabilities or defects may require certain versions to be explicitly not supported.
* See the `pyproject.toml` file for dependency version information.

## Installation

To install [the current release](https://pypi.org/project/monai/), you can simply run:

```bash
pip install monai
```

Please refer to [the installation guide](https://monai.readthedocs.io/en/latest/installation.html) for other installation options.

## Getting Started

[MedNIST demo](https://colab.research.google.com/github/Project-MONAI/tutorials/blob/main/2d_classification/mednist_tutorial.ipynb) and [MONAI for PyTorch Users](https://colab.research.google.com/github/Project-MONAI/tutorials/blob/main/modules/developer_guide.ipynb) are available on Colab.

Examples and notebook tutorials are located at [Project-MONAI/tutorials](https://github.com/Project-MONAI/tutorials).

Technical documentation is available at [monai.readthedocs.io](https://monai.readthedocs.io).

## Docker

The MONAI Docker image is available from [Dockerhub](https://hub.docker.com/r/projectmonai/monai),
tagged as `latest` for the latest state of `dev` or with a release version. A slimmed down image can also be built
locally using `Dockerfile.slim`, see that file for instructions.

To get started with the latest MONAI, use `docker run -ti --rm --gpus all projectmonai/monai:latest /bin/bash`.

## Citation

If you have used MONAI in your research, please cite us! The citation can be exported from: <https://arxiv.org/abs/2211.02701>.

## Model Zoo

[The MONAI Model Zoo](https://github.com/Project-MONAI/model-zoo) is a place for researchers and data scientists to share the latest and great models from the community.
Utilizing [the MONAI Bundle format](https://monai.readthedocs.io/en/latest/bundle_intro.html) makes it easy to [get started](https://github.com/Project-MONAI/tutorials/tree/main/model_zoo) building workflows with MONAI.

## Contributing

For guidance on making a contribution to MONAI, see the [contributing guidelines](https://github.com/Project-MONAI/MONAI/blob/dev/CONTRIBUTING.md).

## Community

Join the conversation on Twitter/X [@ProjectMONAI](https://twitter.com/ProjectMONAI), [LinkedIn](https://www.linkedin.com/company/projectmonai), or join our [Slack channel](https://forms.gle/QTxJq3hFictp31UM9).

Ask and answer questions over on [MONAI's GitHub Discussions tab](https://github.com/Project-MONAI/MONAI/discussions).

## Links

- Website: <https://project-monai.github.io/>
- API documentation (milestone): <https://monai.readthedocs.io/>
- API documentation (latest dev): <https://monai.readthedocs.io/en/latest/>
- Code: <https://github.com/Project-MONAI/MONAI>
- Project tracker: <https://github.com/Project-MONAI/MONAI/projects>
- Issue tracker: <https://github.com/Project-MONAI/MONAI/issues>
- Wiki: <https://github.com/Project-MONAI/MONAI/wiki>
- Test status: <https://github.com/Project-MONAI/MONAI/actions>
- PyPI package: <https://pypi.org/project/monai/>
- conda-forge: <https://anaconda.org/conda-forge/monai>
- Weekly previews: <https://pypi.org/project/monai-weekly/>
- Docker Hub: <https://hub.docker.com/r/projectmonai/monai>

---

## Installation

To install [the current release](https://pypi.org/project/monai/), you can simply run:

```bash
pip install monai
```

Please refer to [the installation guide](https://monai.readthedocs.io/en/latest/installation.html) for other installation options.

## Usage

</p>

**M**edical **O**pen **N**etwork for **AI**

![Supported Python versions](https://raw.githubusercontent.com/Project-MONAI/MONAI/dev/docs/images/python.svg)
[![License](https://img.shields.io/badge/license-Apache%202.0-green.svg)](https://opensource.org/licenses/Apache-2.0)
[![auto-commit-msg](https://img.shields.io/badge/dynamic/json?label=citations&query=%24.citationCount&url=https%3A%2F%2Fapi.semanticscholar.org%2Fgraph%2Fv1%2Fpaper%2FDOI%3A10.48550%2FarXiv.2211.02701%3Ffields%3DcitationCount)](https://arxiv.org/abs/2211.02701)
[![PyPI version](https://badge.fury.io/py/monai.svg)](https://badge.fury.io/py/monai)
[![docker](https://img.shields.io/badge/docker-pull-green.svg?logo=docker&logoColor=white)](https://hub.docker.com/r/projectmonai/monai)
[![conda](https://img.shields.io/conda/vn/conda-forge/monai?color=green)](https://anaconda.org/conda-forge/monai)

[![premerge](https://github.com/Project-MONAI/MONAI/actions/workflows/pythonapp.yml/badge.svg?branch=dev)](https://github.com/Project-MONAI/MONAI/actions/workflows/pythonapp.yml)
[![postmerge](https://img.shields.io/github/checks-status/project-monai/monai/dev?label=postmerge)](https://github.com/Project-MONAI/MONAI/actions?query=branch%3Adev)
[![Documentation Status](https://readthedocs.org/projects/monai/badge/?version=latest)](https://monai.readthedocs.io/en/latest/)
[![codecov](https://codecov.io/gh/Project-MONAI/MONAI/branch/dev/graph/badge.svg?token=6FTC7U1JJ4)](https://codecov.io/gh/Project-MONAI/MONAI)
[![monai Downloads Last Month](https://assets.piptrends.com/get-last-month-downloads-badge/monai.svg 'monai Downloads Last Month by pip Trends')](https://piptrends.com/package/monai)

MONAI is a [PyTorch](https://pytorch.org/)-based, [open-source](https://github.com/Project-MONAI/MONAI/blob/dev/LICENSE) framework for deep learning in healthcare imaging, part of the [PyTorch Ecosystem](https://pytorch.org/ecosystem/).
Its ambitions are as follows:

- Developing a community of academic, industrial and clinical researchers collaborating on a common foundation;
- Creating state-of-the-art, end-to-end training workflows for healthcare imaging;
- Providing researchers with the optimized and standardized way to create and evaluate deep learning models.

## API

[![PyPI version](https://badge.fury.io/py/monai.svg)](https://badge.fury.io/py/monai)
[![docker](https://img.shields.io/badge/docker-pull-green.svg?logo=docker&logoColor=white)](https://hub.docker.com/r/projectmonai/monai)
[![conda](https://img.shields.io/conda/vn/conda-forge/monai?color=green)](https://anaconda.org/conda-forge/monai)

[![premerge](https://github.com/Project-MONAI/MONAI/actions/workflows/pythonapp.yml/badge.svg?branch=dev)](https://github.com/Project-MONAI/MONAI/actions/workflows/pythonapp.yml)
[![postmerge](https://img.shields.io/github/checks-status/project-monai/monai/dev?label=postmerge)](https://github.com/Project-MONAI/MONAI/actions?query=branch%3Adev)
[![Documentation Status](https://readthedocs.org/projects/monai/badge/?version=latest)](https://monai.readthedocs.io/en/latest/)
[![codecov](https://codecov.io/gh/Project-MONAI/MONAI/branch/dev/graph/badge.svg?token=6FTC7U1JJ4)](https://codecov.io/gh/Project-MONAI/MONAI)
[![monai Downloads Last Month](https://assets.piptrends.com/get-last-month-downloads-badge/monai.svg 'monai Downloads Last Month by pip Trends')](https://piptrends.com/package/monai)

MONAI is a [PyTorch](https://pytorch.org/)-based, [open-source](https://github.com/Project-MONAI/MONAI/blob/dev/LICENSE) framework for deep learning in healthcare imaging, part of the [PyTorch Ecosystem](https://pytorch.org/ecosystem/).
Its ambitions are as follows:

- Developing a community of academic, industrial and clinical researchers collaborating on a common foundation;
- Creating state-of-the-art, end-to-end training workflows for healthcare imaging;
- Providing researchers with the optimized and standardized way to create and evaluate deep learning models.

## Dependencies

| Metric | Value |
|--------|-------|
| Files | unknown |
| Lines of Code | unknown |
| Dependencies | unknown |
| Upstream license (harvested) | Apache-2.0 |
| Overlay license | Anticommons 0.1.0 |

Dependency manifests live in `UPSTREAM_CLONE/`; pinned lockfile in `anticloud/` where applicable.

## Configuration

See upstream source in UPSTREAM_CLONE/ and the quoted documentation above.

## Contributing

- [Introduction](#introduction)
- [The contribution process](#the-contribution-process)
  - [Preparing pull requests](#preparing-pull-requests)
    1. [Checking the coding style](#checking-the-coding-style)
    1. [Unit testing](#unit-testing)
    1. [Building the documentation](#building-the-documentation)
    1. [Automatic code formatting](#automatic-code-formatting)
    1. [Adding new optional dependencies](#adding-new-optional-dependencies)
    1. [Signing your work](#signing-your-work)
    1. [Utility functions](#utility-functions)
    1. [Backwards compatibility](#backwards-compatibility)
  - [Submitting pull requests](#submitting-pull-requests)
- [The code reviewing process (for the maintainers)](#the-code-reviewing-process)
  - [Reviewing pull requests](#reviewing-pull-requests)
- [Admin tasks (for the maintainers)](#admin-tasks)
  - [Releasing a new version](#release-a-new-version)

## Introduction

Welcome to Project MONAI! We're excited you're here and want to contribute. This documentation is intended for individuals and institutions interested in contributing to MONAI. MONAI is an open-source project and, as such, its success relies on its community of contributors willing to keep improving it. Your contribution will be a valued addition to the code base; we simply ask that you read this page and understand our contribution process, whether you are a seasoned open-source contributor or whether you are a first-time contributor.

### Communicate with us

We are happy to talk with you about your needs for MONAI and your ideas for contributing to the project. One way to do this is to create an issue discussing your thoughts. It might be that a very similar feature is under development or already exists, so an issue is a great starting point. If you are looking for an issue to resolve that will help Project MONAI, see the [*good first issue*](https://github.com/Project-MONAI/MONAI/labels/good%20first%20issue) and [*Contribution wanted*](https://github.com/Project-MONAI/MONAI/labels/Contribution%20wanted) labels.

### Does it belong in PyTorch instead of MONAI?

MONAI is part of [PyTorch Ecosystem](https://pytorch.org/ecosystem/), and mainly based on the PyTorch and Numpy libraries. These libraries implement what we consider to be best practice for general scientific computing and deep learning functionality. MONAI builds on these with a strong focus on medical applications. As such, it is a good idea to consider whether your functionality is medical-application specific or not. General deep learning functionality may be better off in PyTorch; you can find their contribution guidelines [here](https://pytorch.org/docs/stable/community/contribution_guide.html).

## Tool-Assisted Contribution Policy

Contributions generated wholly or in part by generative tools, whether AI-based or not, are acceptable in MONAI so long as the submitting author can take responsibility for the content as if they wrote it themselves. This implies that contributor

## License

Upstream © its respective contributors under Apache-2.0 (harvested MIT/Apache-2.0/BSD source; see `UPSTREAM_CLONE/LICENSE`). This packaging overlay is licensed under Anticommons 0.1.0.

## Upstream

- **project:** MEDICAL_AI
- **Pinned SHA:** `a7904ae138c01cc90ad9c3bdf52c10218bde315f`
- **source:** `UPSTREAM_CLONE/` (pinned at the SHA above)
- **Upstream README source:** `UPSTREAM_CLONE/README.md`

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`b8be5ddce5a6bb637d22f93822979daf54a64e9869004422888596f8b88465d7`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| DANS (KNAW/NWO, Netherlands) | 10.17026/PT | EU-recognised archive |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe
and Mail, Business Insider, National Post, Financial Post, StreetInsider,
Digital Journal, Barchart, International Business Times, and Fox News.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

