# terra-fmp-research-pipeline

[![Layer](https://img.shields.io/badge/Layer-Publication%20%26%20Workflow%20Infrastructure-7a3cff)](https://github.com/Secret-Uzbek/terra-fmp-research-pipeline)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18061978.svg)](https://doi.org/10.5281/zenodo.18061978)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0000--6394--4912-green)](https://orcid.org/0009-0000-6394-4912)
[![Release](https://img.shields.io/github/v/release/Secret-Uzbek/terra-fmp-research-pipeline?display_name=tag)](https://github.com/Secret-Uzbek/terra-fmp-research-pipeline/releases)
[![Last Commit](https://img.shields.io/github/last-commit/Secret-Uzbek/terra-fmp-research-pipeline)](https://github.com/Secret-Uzbek/terra-fmp-research-pipeline/commits/main)
[![Zenodo Sync](https://github.com/Secret-Uzbek/terra-fmp-research-pipeline/actions/workflows/zenodo-release.yml/badge.svg)](https://github.com/Secret-Uzbek/terra-fmp-research-pipeline/actions/workflows/zenodo-release.yml)
[![Terra Audit](https://github.com/Secret-Uzbek/terra-fmp-research-pipeline/actions/workflows/terra-audit.yml/badge.svg)](https://github.com/Secret-Uzbek/terra-fmp-research-pipeline/actions/workflows/terra-audit.yml)
[![Central Hub](https://img.shields.io/badge/Central-FMP--CENTRAL--REPO-blue)](https://github.com/Secret-Uzbek/FMP-CENTRAL-REPO)
[![Legal](https://img.shields.io/badge/Legal-terra--legal-0f6b57)](https://github.com/AIUZ-Terra-Codex-EcoSystem/terra-legal)

> Publication-and-workflow infrastructure branch connecting theory, code,
> releases, and external publication surfaces such as Zenodo.

## Layer role

This repository is a publication-and-workflow infrastructure layer.

It should hold:

- workflow logic connecting code, releases, and publication;
- release-facing documentation and pipeline artifacts;
- reproducible infrastructure for research publication surfaces;
- clear human entry into the pipeline itself.

It should not become:

- a helper-generated shell with fake DOI badges;
- a generic theory repository;
- a donor governance repository;
- a random mix of unrelated experiments.

## Reading path

1. `README.md`
2. `CITATION.cff`
3. `.github/workflows/`
4. pipeline-specific root files

## Ecosystem position

- `FMP-CENTRAL-REPO` — central public hub
- `FMP-Full-Publication-Package` — publication source layer
- `terra-legal` — donor governance and standards
- `terra-translation-api` — adjacent infrastructure branch
