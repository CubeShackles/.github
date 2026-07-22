**English** | [Português](./README.pt.md)

# CubeShackles

**AOA-native programmable financial infrastructure, designed in Angola for institutional, regulated, and connectivity-constrained environments.**

CubeShackles is a founder-led platform building modular financial rails for payments, identity, credit intelligence, digital assets, tokenization, clearing, settlement, custody, supervision, and institutional integration. Work is organized across specialized repositories with versioned contracts, explicit responsibility boundaries, and auditable validation mechanisms.

> **Platform status:** pre-production development. Repositories contain implemented components, prototypes, contract surfaces, and planned capabilities at different maturity levels. The presence of code or documentation does **not** constitute regulatory approval, certification, national deployment, partnership endorsement, or commercial availability.

## Start here

| Resource | Purpose |
|---|---|
| [`cubeshackles`](https://github.com/CubeShackles/cubeshackles) | Public umbrella — platform doctrine, repository map, contribution standards, and interoperability policy |
| [Contribution rules](https://github.com/CubeShackles/cubeshackles/blob/main/CONTRIBUTING.md) | How humans and automation contribute |
| [Repository map](https://github.com/CubeShackles/cubeshackles/blob/main/REPOSITORY_MAP.md) | How the specialized repositories fit together |
| [Claims Register](https://github.com/CubeShackles/cubeshackles/blob/main/docs/CLAIMS_REGISTER.md) | Tracked maturity and wording discipline for sensitive institutional claims |

Many sibling repositories remain private during pre-production. Public visitors should treat the umbrella repository as the canonical entry point.

## Engineering principles

- **Angola as the origin jurisdiction** — native kwanza (AOA) support, local operating requirements, and resilience under uneven connectivity.
- **Institutional architecture** — separation of ledger, clearing, settlement, custody, compliance, supervision, and access channels.
- **Verifiable operation** — versioned contracts, deterministic validation, traceability, and technical evidence.
- **Security by design** — access controls, secrets governance, responsibility isolation, and operational recovery.
- **Interoperability** — APIs, SDKs, canonical events, and shared data models across platform components.
- **Maturity transparency** — explicit distinction between implemented, partially implemented, prototype, experimental, planned, and externally authorized capabilities.

## Platform verticals

Representative repository families (names only — access may be private during pre-production):

| Vertical | Representative repositories |
|---|---|
| Platform and governance | `cubeshackles`, `Cubeshackles-core`, `Cubeshackles-control-plane`, `cubeshackles-platform-specs` |
| Ledger and settlement | `cubeshackles-ledger`, `cubeshackles-clearing-house`, `cubeshackles-settlement-engine` |
| Compliance and supervision | `cubeshackles-compliance-engine`, `cubeshackles-regulatory-reporting`, `cubeshackles-supervision` |
| Assets and custody | `cubeshackles-tokenization-engine`, `cubeshackles-asset-registry`, `cubeshackles-rwa-custody`, `cubeshackles-vault` |
| Infrastructure and resilience | `cubeshackles-infra`, `cubeshackles-offline-infrastructure`, `cubeshackles-disaster-recovery`, `cubeshackles-observability` |
| Intelligence and knowledge | `Cubeshackles-ciel`, `cubeshackles-ontology`, `cubeshackles-ai-runtime`, `cubeshackles-agent` |
| Products | `CubeWallet`, `kulifikila`, `BualaBuitu`, `national-transit-app-cubeshackles` |
| Integration and development | `cubeshackles-integration`, `cubeshackles-developer-portal`, `cubeshackles-ai-sdk`, `cubeshackles-design-system` |

## Repository model

Each repository is expected to declare:

1. functional responsibility;
2. explicit scope boundaries;
3. maturity status;
4. interfaces and dependencies;
5. validation commands;
6. risks, assumptions, and unverified capabilities.

Artificial-intelligence tools may assist engineering. They are not authors, owners, or institutional principals of CubeShackles assets. See [authorship and tooling](https://github.com/CubeShackles/cubeshackles/blob/main/governance/policies/authorship-and-tooling.md).

## Institutional scope

CubeShackles is structuring capabilities for future integration with financial institutions, enterprises, public entities, technology operators, and supervisory bodies. Any regulated use remains subject to the licenses, authorizations, security assessments, institutional agreements, and legal requirements applicable in each jurisdiction.

---

© 2026 CubeShackles. All rights reserved.
