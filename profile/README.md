**English** | [Português](./README.pt.md)

# CubeShackles

**AOA-native programmable financial infrastructure, designed in Angola for institutional, regulated, and connectivity-constrained environments.**

CubeShackles is developing a modular financial platform spanning payments, identity, credit intelligence, digital assets, tokenization, clearing, settlement, custody, supervision, and institutional integration. The architecture is distributed across specialized repositories with versioned contracts, explicit responsibility boundaries, and auditable validation mechanisms.

> **Platform status:** pre-production development. The repositories contain implemented components, prototypes, contract surfaces, and planned capabilities at different maturity levels. The presence of code or documentation does not constitute regulatory approval, certification, national deployment, or commercial availability.

## Engineering principles

- **Angola as the origin jurisdiction:** native kwanza support, local operating requirements, and resilience under uneven connectivity.
- **Institutional architecture:** separation of ledger, clearing, settlement, custody, compliance, supervision, and access channels.
- **Verifiable operation:** versioned contracts, deterministic validation, traceability, and technical evidence.
- **Security by design:** access controls, secrets governance, responsibility isolation, and operational recovery.
- **Interoperability:** APIs, SDKs, canonical events, and shared data models across platform components.
- **Maturity transparency:** explicit distinction between implemented, experimental, prototype, planned, and externally authorized capabilities.

## Core verticals

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

Each repository should declare:

1. functional responsibility;
2. explicit scope boundaries;
3. maturity status;
4. interfaces and dependencies;
5. validation commands;
6. risks, assumptions, and unverified capabilities.

The central [`cubeshackles`](https://github.com/CubeShackles/cubeshackles) repository contains platform doctrine, contribution standards, the repository map, and interoperability policies.

## Technical governance

- [Contribution rules](https://github.com/CubeShackles/cubeshackles/blob/main/CONTRIBUTING.md)
- [Authorship and tooling](https://github.com/CubeShackles/cubeshackles/blob/main/governance/policies/authorship-and-tooling.md)
- [Repository map](https://github.com/CubeShackles/cubeshackles/blob/main/REPOSITORY_MAP.md)
- [GitHub taxonomy](https://github.com/CubeShackles/cubeshackles/blob/main/docs/GITHUB_TAXONOMY.md)

Artificial-intelligence tools may assist engineering, but they are not authors, owners, or institutional principals of CubeShackles assets.

## Institutional scope

CubeShackles is structuring capabilities for future integration with financial institutions, enterprises, public entities, technology operators, and supervisory bodies. Any regulated use remains subject to the licenses, authorizations, security assessments, institutional agreements, and legal requirements applicable in each jurisdiction.

---

© 2026 CubeShackles. All rights reserved.