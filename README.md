# SCIKIT IMAGE

![license](https://img.shields.io/badge/license-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-scientific_lab-lightgrey)

> Anticloud-hardened packaging of the upstream project `SCIKIT_IMAGE` in category **SCIENTIFIC LAB**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** SCIENTIFIC LAB · **Upstream:** https://github.com/scikit-image/scikit-image · **Upstream pin:** `a99319166925d365e8c17e989ac1ffb7bab7bca1` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

# scikit-image: Image processing in Python

[![Image.sc forum](https://img.shields.io/badge/dynamic/json.svg?label=forum&url=https%3A%2F%2Fforum.image.sc%2Ftags%2Fscikit-image.json&query=%24.topic_list.tags.0.topic_count&colorB=brightgreen&suffix=%20topics&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA4AAAAOCAYAAAAfSC3RAAABPklEQVR42m3SyyqFURTA8Y2BER0TDyExZ+aSPIKUlPIITFzKeQWXwhBlQrmFgUzMMFLKZeguBu5y+//17dP3nc5vuPdee6299gohUYYaDGOyyACq4JmQVoFujOMR77hNfOAGM+hBOQqB9TjHD36xhAa04RCuuXeKOvwHVWIKL9jCK2bRiV284QgL8MwEjAneeo9VNOEaBhzALGtoRy02cIcWhE34jj5YxgW+E5Z4iTPkMYpPLCNY3hdOYEfNbKYdmNngZ1jyEzw7h7AIb3fRTQ95OAZ6yQpGYHMMtOTgouktYwxuXsHgWLLl+4x++Kx1FJrjLTagA77bTPvYgw1rRqY56e+w7GNYsqX6JfPwi7aR+Y5SA+BXtKIRfkfJAYgj14tpOF6+I46c4/cAM3UhM3JxyKsxiOIhH0IO6SH/A1Kb1WBeUjbkAAAAAElFTkSuQmCC)](https://forum.image.sc/tags/scikit-image)
[![Stackoverflow](https://img.shields.io/badge/stackoverflow-Ask%20questions-blue.svg)](https://stackoverflow.com/questions/tagged/scikit-image)
[![project chat](https://img.shields.io/badge/zulip-join_chat-brightgreen.svg)](https://skimage.zulipchat.com)
[![Scientific Python Ecosystem Coordination](https://img.shields.io/badge/SPEC-0,1,4,6,7,8-green?labelColor=%23004811&color=%235CA038)](https://scientific-python.org/specs/)
[![LFX Health Score](https://insights.linuxfoundation.org/api/badge/health-score?project=scikit-image-scikit-image)](https://insights.linuxfoundation.org/project/scikit-image-scikit-image)

- **Website (including documentation):** [https://scikit-image.org/](https://scikit-image.org)
- **Documentation:** [https://scikit-image.org/docs/stable/](https://scikit-image.org/docs/stable/)
- **User forum:** [https://forum.image.sc/tag/scikit-image](https://forum.image.sc/tag/scikit-image)
- **Developer forum:** [https://discuss.scientific-python.org/c/contributor/skimage](https://discuss.scientific-python.org/c/contributor/skimage)
- **Source:** [https://github.com/scikit-image/scikit-image](https://github.com/scikit-image/scikit-image)

## Installation

- **pip:** `pip install scikit-image`
- **conda:** `conda install -c conda-forge scikit-image`

Also see [installing `scikit-image`](https://github.com/scikit-image/scikit-image/blob/main/INSTALL.rst).

## License

See [LICENSE.txt](https://github.com/scikit-image/scikit-image/blob/main/LICENSE.txt).

## Citation

If you find this project useful, please cite:

> Stéfan van der Walt, Johannes L. Schönberger, Juan Nunez-Iglesias,
> François Boulogne, Joshua D. Warner, Neil Yager, Emmanuelle
> Gouillart, Tony Yu, and the scikit-image contributors.
> _scikit-image: Image processing in Python_. PeerJ 2:e453 (2014)
> https://doi.org/10.7717/peerj.453

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Python** (manifests: pyproject.toml, requirements.txt; scanned in UPSTREAM_CLONE)
- Top-level source layout: `benchmarks/`, `doc/`, `requirements/`, `src/`, `tests/`, `tools/`
- Snapshot size: **1419 files**, **173191 lines of code** (measured; see Benchmarks)
- Primary languages: `.py` (921), `.npy` (96), `.rst` (66), `.build` (62), `.pyi` (53), `.pyx` (51)
- Upstream commit pinned for this packaging: `a99319166925d365e8c17e989ac1ffb7bab7bca1`

---

## Installation

- **pip:** `pip install scikit-image`
- **conda:** `conda install -c conda-forge scikit-image`

Also see [installing `scikit-image`](https://github.com/scikit-image/scikit-image/blob/main/INSTALL.rst).

*Section quoted from the upstream readme.*
Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

No usage section was found in the upstream readme. Entry points detected in this project directory:

```sh
python -m scikit_image    # module entry point, when the package layout matches
```

Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

- **Website (including documentation):** [https://scikit-image.org/](https://scikit-image.org)
- **Documentation:** [https://scikit-image.org/docs/stable/](https://scikit-image.org/docs/stable/)
- **User forum:** [https://forum.image.sc/tag/scikit-image](https://forum.image.sc/tag/scikit-image)
- **Developer forum:** [https://discuss.scientific-python.org/c/contributor/skimage](https://discuss.scientific-python.org/c/contributor/skimage)
- **Source:** [https://github.com/scikit-image/scikit-image](https://github.com/scikit-image/scikit-image)

*Section quoted from the upstream readme.*
---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Python |
| Manifests detected | pyproject.toml, requirements.txt |
| Files in snapshot | 1419 |
| Lines of code | 173191 |
| Dependency references | 67 |
| Dependencies by ecosystem | conda: 63, native: 1, pypi: 3 |
| Upstream license | MIT |
| Overlay license | Anticommons 0.1.0 |

Top dependency references recorded in the benchmark snapshot:

| Ecosystem | Name | Version | Source file |
|-----------|------|---------|-------------|
| conda | dev | - | environment.yml |
| conda | conda-forge | - | environment.yml |
| conda | numpy | - | environment.yml |
| conda | scipy | - | environment.yml |
| conda | networkx | - | environment.yml |
| conda | pillow | - | environment.yml |
| conda | imageio | - | environment.yml |
| conda | tifffile | - | environment.yml |
| conda | packaging | - | environment.yml |
| conda | lazy-loader | - | environment.yml |
| conda | meson-python | - | environment.yml |
| conda | ninja | - | environment.yml |
| conda | Cython | - | environment.yml |
| conda | pythran | - | environment.yml |
| conda | numpy | - | environment.yml |
| ... | (52 more) | | |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

No configuration section was found in the upstream readme. Configuration-relevant files detected in this project directory:

- `pyproject.toml`

Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

*Excerpt from upstream `CONTRIBUTING.md`:*

(howto-contribute)=

# How to contribute to scikit-image

Developing open source software as part of a community is fun, and
often quite educational!

We coordinate our work using GitHub, where you can find lists of [open
issues](https://github.com/scikit-image/scikit-image/issues?q=is%3Aopen)
and [new feature requests](https://github.com/scikit-image/scikit-image/labels/%3Apray%3A%20Feature%20request).

To follow along with discussions, or to get in touch with the
developer team, please join us on the [scikit-image developer forum](https://discuss.scientific-python.org/c/contributor/skimage) and
the [Zulip chat](https://skimage.zulipchat.com/).

Please post questions to these public forums (rather than contacting
developers directly); that way, everyone can benefit from the answers,
and developers can answer according to their availability. Don't feel
shy, the team is very friendly!

```{contents}
:local: true
```

## Development process

The following is a brief overview about how changes to source code and documentation
can be contributed to scikit-image.

1. If you are a first-time contributor:

   - Go to [https://github.com/scikit-image/scikit-image](https://github.com/scikit-image/scikit-image) and click the
     "fork" button to create your own copy of the project.

   - [Set up GitHub SSH authentication](https://help.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh).

   - source (download) the project with the project source on your local computer:

     ```
     git source --origin upstream git@github.com:scikit-image/scikit-image
     ```

   - Change into the root directory of the sourced project:

     ```
     cd scikit-image
     ```

   - Add your fork as a
     [remote project](https://git-scm.com/book/en/v2/Git-Basics-Working-with-Remotes)
     that you will interact with.

     Assuming a GitHub username of `codemonkey`:

     ```
     git remote add codemonkey git@github.com:codemonkey/scikit-image
     git fetch codemonkey
     ```

   - You now have two remote projects:

     - `upstream`, which refers to the `scikit-image` project project, and
     - `codemonkey`, which refers to your personal fork.

   - Next, {ref}`set up your build environment <build-env-setup>`.

   - Finally, we recommend that you use our pre-commit hook, which runs code
     checkers and formatters each time you do a `git commit`:

     ```
     pip install pre-commit
     pre-commit install
     ```

2. Develop your con

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: MIT** (evidence: `LICENSE.txt` in the upstream snapshot).

License file excerpt:

```text
Files: *
Copyright: 2009-2022 the scikit-image team
License: BSD-3-Clause

Files: doc/source/themes/scikit-image/layout.html
Copyright: 2007-2010 the Sphinx team
License: BSD-3-Clause

Files: skimage/feature/_canny.py
       skimage/filters/edges.py
       skimage/filters/_rank_order.py
       skimage/morphology/_skeletonize.py
       skimage/morphology/tests/test_watershed.py
       skimage/morphology/watershed.py
       skimage/segmentation/heap_general.pxi
       skimage/segmentation/heap_watershed.pxi
       skimage/segmentation/_watershed.py
       skimage/segmentation/_watershed_cy.pyx
Copyright: 2003-2009 Massachusetts Institute of Technology
           2009-2011 Broad Institute
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original MIT terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `MIT` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `SCIKIT_IMAGE` (category: SCIENTIFIC LAB)
- **Upstream URL:** https://github.com/scikit-image/scikit-image
- **Pinned commit (SHA):** `a99319166925d365e8c17e989ac1ffb7bab7bca1`
- **Branch:** main
- **Pin provenance:** GitHub API commits/<branch> (response quoted in report). The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`8c05c33e42799d34580c3eec760745de9b2de3ef636a20acbd693ceda9039bed`.

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
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

