# CubeShackles `.github`

[English](./README.md) | [Português](./README.pt.md)

Organization-level GitHub configuration for CubeShackles: public organization
profile, reusable workflows, issue/PR templates, and documentation of the
GitHub App operating model.

## Public organization profile

GitHub renders the organization Overview README from:

- [`profile/README.md`](./profile/README.md) — English (canonical)
- [`profile/README.pt.md`](./profile/README.pt.md) — Portuguese (`pt-AO`)

This repository is **public** so that profile content is visible to non-members
on [github.com/CubeShackles](https://github.com/CubeShackles).

Deep platform doctrine lives in the public umbrella repository
[`cubeshackles`](https://github.com/CubeShackles/cubeshackles).

## What else this repository holds

- `.github/workflows/` — reusable organization workflows (for example
  docs localization and standard CI)
- `.github/ISSUE_TEMPLATE/`, `.github/PULL_REQUEST_TEMPLATE.md` —
  shared contribution templates
- This README — operating notes for the organization GitHub surface

## GitHub App operating model

CubeShackles automation is intended to authenticate with short-lived GitHub App
installation tokens instead of long-lived Personal Access Tokens (PATs).

Expected properties:

1. App identity authentication
2. Installation-scoped authorization
3. Short-lived installation access tokens
4. Explicit repository selection
5. Minimum required permissions
6. Logged and reviewable automation

## Security boundary

This repository must not commit or expose:

- GitHub App private keys
- Webhook secrets
- Installation access tokens
- Personal Access Tokens
- Environment-specific credentials
- Unencrypted secrets or exported authentication material

Secrets must remain in an approved secret-management system and be injected only
at runtime.

## Governance

- [Contribution rules](https://github.com/CubeShackles/cubeshackles/blob/main/CONTRIBUTING.md)
- [Authorship and tooling](https://github.com/CubeShackles/cubeshackles/blob/main/governance/policies/authorship-and-tooling.md)
- [Repository map](https://github.com/CubeShackles/cubeshackles/blob/main/REPOSITORY_MAP.md)
- [GitHub taxonomy](https://github.com/CubeShackles/cubeshackles/blob/main/docs/GITHUB_TAXONOMY.md)

---

**Visibility:** Public (required for the organization profile README)  
**Canonical language:** English  
**Institutional localization:** Portuguese (`pt-AO`)
