# MegaFace

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green?logo=creativecommons&logoColor=white)](https://creativecommons.org/licenses/by/4.0/)
[![GitHub](https://img.shields.io/badge/GitHub-biometric--community%2FMegaFace-181717?logo=github)](https://github.com/biometric-community/MegaFace)
[![Access: register](https://img.shields.io/badge/access-register-important.svg)](http://megaface.cs.washington.edu/)

**MegaFace** — tbiom catalog packaging for `megaface` (face-recog; access `register`). Docs/helpers only; obtain data via upstream registration.

- **Dataset repository**: https://github.com/biometric-community/MegaFace
- **Upstream source**: http://megaface.cs.washington.edu/
- **License (helpers / docs)**: CC BY 4.0 (see [`LICENSE`](LICENSE))
- **License (data)**: upstream terms — this packaging does **not** relicense or redistribute gated data

| Field | Value |
|-------|-------|
| Catalog id (tbiom) | `megaface` |
| Category | `face-recog` |
| Access | `register` |
| Upstream homepage | http://megaface.cs.washington.edu/ |

## TL;DR

- **Access**: **register** — obtain data from the upstream homepage / license process
- **This mirror**: documentation + download helpers only (no bulk payload in git)
- **Notes**: MegaFace challenge data; registration required.

## Download

### Clone this repository

```bash
git clone git@github.com:biometric-community/MegaFace.git
cd MegaFace
```

### tbiom monorepo helper

```bash
bash projects/datasets/scripts/download_megaface.sh
```

Place licensed archives under `projects/datasets/megaface/` (gitignored).

## Dataset structure

```text
MegaFace/
├── README.md
├── LICENSE
├── .gitignore
└── extracted/   # local only after you obtain upstream data
```

## License

Helpers/docs: CC BY 4.0. Dataset files: upstream license / registration agreement.

## Contact

- Upstream: http://megaface.cs.washington.edu/
- Packaging: https://github.com/biometric-community/MegaFace/issues
