<p>
    <img alt="Rolls-Royce Logo" width="100" src="https://raw.githubusercontent.com/rropen/MEC/main/src/frontend/public/logo4.png">
    <br>
    <h3>Crossplane Provider for CSC Domain Manager</h3>
</p>
<p>
<a href="https://ghdocs.rollsroyce-sf.com"><img src="https://img.shields.io/badge/Rolls--Royce-Software%20Factory-10069f" alt="sf badge" /></a>
</p>

---

<p>
  <a href="http://commitizen.github.io/cz-cli/"><img src="https://img.shields.io/badge/commitizen-friendly-brightgreen?style=flat" alt="commitizen badge" /></a>
  <a href="https://go.dev/"><img src="https://img.shields.io/badge/golang-%2300ADD8.svg?style=flat&logo=go&logoColor=white" /></a>
</p>

## Getting Started

This cscdm serves as a starting point for generating a new [Crossplane Provider](https://docs.crossplane.io/latest/packages/providers/) using the [`upjet`](https://github.com/crossplane/upjet) tooling. Please follow the guide linked below to generate a new Provider:

https://github.com/crossplane/upjet/blob/main/docs/generating-a-provider.md

## Developing

Run code-generation pipeline:
```console
go run cmd/generator/main.go "$PWD"
```

Run against a Kubernetes cluster:

```console
make run
```

Build, push, and install:

```console
make all
```

Build binary:

```console
make build
```

## Report a Bug

For filing bugs, suggesting improvements, or requesting new features, please
open an [issue](https://github.com/rropen/provider-cscdm/issues).
