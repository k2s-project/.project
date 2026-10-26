# .project - K2s

This repository contains standardized metadata for the
[K2s](https://github.com/k2s-project/k2s) project, following the
[CNCF `.project` specification](https://github.com/cncf/automation/tree/main/utilities/dot-project).

## What is K2s?

K2s is a Kubernetes distribution for mixed Windows and Linux workloads. It is
designed for Windows hosts and packages the components required to run Kubernetes
workloads across Windows and Linux nodes.

## Files

| File | Purpose |
|------|---------|
| [project.yaml](./project.yaml) | Core K2s metadata, including its description, repository, sandbox maturity, governance, security, legal, and documentation references. |
| [maintainers.yaml](./maintainers.yaml) | K2s maintainer roster with GitHub handles. |
| [.github/workflows/validate.yaml](./.github/workflows/validate.yaml) | Validates project metadata and maintainer handles. |

## Validation

The metadata is automatically validated on pull requests and pushes to `main`
by the [CNCF validation actions](https://github.com/cncf/automation). The
workflow validates the `.project` schema, links, and maintainer handles.

## Links

- **Website:** <https://k2s-project.github.io/k2s/>
- **Main repository:** <https://github.com/k2s-project/k2s>
- **Architecture:** <https://github.com/k2s-project/k2s/blob/main/docs/dev-guide/architecture.md>
- **CNCF Sandbox onboarding:** <https://github.com/cncf/sandbox/issues/534>
