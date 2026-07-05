<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/logo-dark.svg">
  <img src="assets/logo.svg" alt="drt logo" width="200">
</picture>

# drt — data reverse tool

**Reverse ETL for the code-first data stack.**

[![PyPI](https://img.shields.io/pypi/v/drt-core?style=flat-square&logo=pypi&logoColor=white&label=PyPI)](https://pypi.org/project/drt-core/)
[![Downloads](https://img.shields.io/pepy/dt/drt-core?style=flat-square&logo=pypi&logoColor=white&label=downloads)](https://pepy.tech/projects/drt-core)
[![CI](https://img.shields.io/github/actions/workflow/status/drt-hub/drt/ci.yml?branch=main&style=flat-square&logo=githubactions&logoColor=white&label=CI)](https://github.com/drt-hub/drt/actions/workflows/ci.yml)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue?style=flat-square)](https://github.com/drt-hub/drt/blob/main/LICENSE)

`dlt (load)` → `dbt (transform)` → `drt (activate)`

</div>

drt syncs data from your warehouse to external services — declaratively, via YAML and CLI. Think `dbt run` → `drt run`: same developer experience, opposite data direction.

- **Code-first** — CLI + YAML, Git-native, CI/CD-ready. No GUI SaaS to click through.
- **40+ connectors** — warehouses & lakehouses in; SaaS APIs, cloud storage, and webhooks out.
- **LLM-native** — MCP server + Claude Code skills built in.

```bash
pip install drt-core
drt init && drt run
```

<div align="center">

**[Get started →](https://github.com/drt-hub/drt)** · [Docs](https://drt-hub.github.io/drt-web/) · [Roadmap](https://github.com/drt-hub/drt/blob/main/ROADMAP.md)

</div>
