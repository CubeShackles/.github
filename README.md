# CubeShackles GitHub Governance

[English](./README.md) | [Português](./README.pt.md)

This public repository is the organization-wide GitHub governance, profile and shared-configuration layer for the CubeShackles ecosystem.

It centralizes public organization metadata, reusable templates, workflows and institutional engineering controls applied across the CubeShackles repository portfolio.

> This repository is not the CubeShackles GitHub App implementation and must not contain application credentials, private keys, webhook secrets or token-generation logic. Authentication infrastructure belongs in a separate private repository.

## Scope

- Organization profile content under `profile/`
- Shared contribution and pull-request standards
- Issue and pull-request templates
- Reusable GitHub Actions workflows
- Repository governance conventions
- Organization-wide documentation and localization controls
- Security, authorship and engineering policy references

## Security boundary

This repository may contain public policies and non-sensitive shared configuration only.

The following assets must remain outside this repository:

- GitHub App source code and deployment configuration
- GitHub App private keys
- Webhook secrets
- Installation access tokens
- Personal Access Tokens
- Environment-specific credentials
- Internal operational runbooks containing sensitive access details

## Canonical references

- [Contribution rules](https://github.com/CubeShackles/cubeshackles/blob/main/CONTRIBUTING.md)
- [Authorship and tooling policy](https://github.com/CubeShackles/cubeshackles/blob/main/governance/policies/authorship-and-tooling.md)
- [Repository map](https://github.com/CubeShackles/cubeshackles/blob/main/REPOSITORY_MAP.md)
- [GitHub taxonomy](https://github.com/CubeShackles/cubeshackles/blob/main/docs/GITHUB_TAXONOMY.md)

## Governance doctrine

CubeShackles repositories must remain auditable, technically legible and explicit about maturity, ownership, risk and regulatory scope.

AI-assisted engineering tools may support implementation and documentation. They are not authors, owners, regulators or institutional approvers of CubeShackles systems.

Every material pull request should carry the appropriate `type:*`, `layer:*` and `risk:*` labels, together with a platform milestone where applicable.

## Repository distinction

- `README.md` documents this public `.github` governance repository.
- `profile/README.md` is rendered on the public CubeShackles organization profile.
- `profile/README.pt.md` is the Portuguese organization-profile version.
- The CubeShackles GitHub App must be maintained separately in a private repository.

---

**Status:** Active public organization-governance repository  
**Canonical language:** English  
**Institutional localization:** Portuguese (`pt-AO`)