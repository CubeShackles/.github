# CubeShackles GitHub App

[English](./README.md) | [Português](./README.pt.md)

This private repository contains the configuration, operational controls and organization-wide integration assets for the CubeShackles GitHub App.

The application provides authenticated access to authorized CubeShackles repositories through fine-grained, short-lived GitHub App installation tokens instead of Personal Access Tokens (PATs) or long-lived user credentials.

## Purpose

- Authenticate approved automation against CubeShackles repositories
- Issue short-lived installation access tokens
- Apply least-privilege repository permissions
- Support GitHub API operations across the organization
- Centralize reusable workflows, templates and repository controls
- Reduce dependence on user-bound Personal Access Tokens
- Maintain an auditable boundary between human accounts and automated systems

## Repository structure

- `profile/README.md` — English organization-profile source
- `profile/README.pt.md` — Portuguese organization-profile source
- `.github/` — shared workflows, templates and organization-level GitHub configuration
- `README.md` — canonical documentation for this private GitHub App repository
- `README.pt.md` — Portuguese institutional translation

Because this repository is private, its `profile/README.md` is not intended to serve as the public organization profile unless GitHub's visibility requirements are separately satisfied through a public `.github` profile repository.

## Authentication model

The GitHub App must use:

1. App identity authentication
2. Installation-scoped authorization
3. Short-lived installation access tokens
4. Explicit repository selection
5. Minimum required permissions
6. Logged and reviewable automation

Personal Access Tokens are not part of the normal operating model for supported automation.

## Security boundary

This repository must not commit or expose:

- GitHub App private keys
- Webhook secrets
- Installation access tokens
- Personal Access Tokens
- Environment-specific credentials
- Unencrypted secrets or exported authentication material

Secrets must remain in an approved secret-management system and be injected only at runtime.

## Governance

All application permissions, repository access changes and automation workflows must be:

- explicitly scoped;
- reviewable through version control;
- attributable to an approved operator or workflow;
- revocable without depending on an individual user account;
- aligned with CubeShackles repository-governance and security policies.

## Canonical references

- [Contribution rules](https://github.com/CubeShackles/cubeshackles/blob/main/CONTRIBUTING.md)
- [Authorship and tooling policy](https://github.com/CubeShackles/cubeshackles/blob/main/governance/policies/authorship-and-tooling.md)
- [Repository map](https://github.com/CubeShackles/cubeshackles/blob/main/REPOSITORY_MAP.md)
- [GitHub taxonomy](https://github.com/CubeShackles/cubeshackles/blob/main/docs/GITHUB_TAXONOMY.md)

---

**Visibility:** Private  
**Function:** CubeShackles GitHub App and organization automation control repository  
**Canonical language:** English  
**Institutional localization:** Portuguese (`pt-AO`)
