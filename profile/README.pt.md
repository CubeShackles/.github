[English](./README.md) | **Português**

# CubeShackles

**Infraestrutura financeira programável, nativa em AOA, concebida em Angola para operar em ambientes institucionais, regulados e de conectividade limitada.**

A CubeShackles desenvolve uma plataforma financeira modular para pagamentos, identidade, crédito, ativos digitais, tokenização, compensação, liquidação, custódia, supervisão e integração institucional. A arquitetura é organizada em repositórios especializados, com contratos versionados, limites de responsabilidade explícitos e mecanismos de validação auditáveis.

> **Estado da plataforma:** desenvolvimento pré-produção. Os repositórios representam componentes implementados, protótipos, superfícies contratuais e capacidades planeadas em diferentes níveis de maturidade. A presença de código ou documentação não constitui aprovação regulatória, certificação, implantação nacional ou disponibilidade comercial.

## Princípios de engenharia

- **Angola como jurisdição de origem:** suporte nativo ao kwanza, requisitos locais e operação em contextos de conectividade desigual.
- **Arquitetura institucional:** separação entre livro-razão, compensação, liquidação, custódia, conformidade, supervisão e canais de acesso.
- **Operação verificável:** contratos versionados, validação determinística, rastreabilidade e evidências técnicas.
- **Segurança por desenho:** controlos de acesso, gestão de segredos, isolamento de responsabilidades e recuperação operacional.
- **Interoperabilidade:** APIs, SDKs, eventos canónicos e modelos de dados partilhados entre os componentes da plataforma.
- **Transparência de maturidade:** distinção explícita entre implementado, experimental, protótipo, planeado e dependente de autorização externa.

## Principais verticais

| Vertical | Repositórios representativos |
|---|---|
| Plataforma e governação | `cubeshackles`, `Cubeshackles-core`, `Cubeshackles-control-plane`, `cubeshackles-platform-specs` |
| Livro-razão e liquidação | `cubeshackles-ledger`, `cubeshackles-clearing-house`, `cubeshackles-settlement-engine` |
| Conformidade e supervisão | `cubeshackles-compliance-engine`, `cubeshackles-regulatory-reporting`, `cubeshackles-supervision` |
| Ativos e custódia | `cubeshackles-tokenization-engine`, `cubeshackles-asset-registry`, `cubeshackles-rwa-custody`, `cubeshackles-vault` |
| Infraestrutura e resiliência | `cubeshackles-infra`, `cubeshackles-offline-infrastructure`, `cubeshackles-disaster-recovery`, `cubeshackles-observability` |
| Inteligência e conhecimento | `Cubeshackles-ciel`, `cubeshackles-ontology`, `cubeshackles-ai-runtime`, `cubeshackles-agent` |
| Produtos | `CubeWallet`, `kulifikila`, `BualaBuitu`, `national-transit-app-cubeshackles` |
| Integração e desenvolvimento | `cubeshackles-integration`, `cubeshackles-developer-portal`, `cubeshackles-ai-sdk`, `cubeshackles-design-system` |

## Modelo de repositórios

Cada repositório deve declarar:

1. responsabilidade funcional;
2. limites do seu âmbito;
3. estado de maturidade;
4. interfaces e dependências;
5. comandos de validação;
6. riscos, pressupostos e capacidades ainda não verificadas.

O repositório central [`cubeshackles`](https://github.com/CubeShackles/cubeshackles) contém a doutrina da plataforma, normas de contribuição, mapa de repositórios e políticas de interoperabilidade.

## Governação técnica

- [Normas de contribuição](https://github.com/CubeShackles/cubeshackles/blob/main/CONTRIBUTING.md)
- [Autoria e ferramentas](https://github.com/CubeShackles/cubeshackles/blob/main/governance/policies/authorship-and-tooling.md)
- [Mapa de repositórios](https://github.com/CubeShackles/cubeshackles/blob/main/REPOSITORY_MAP.md)
- [Taxonomia do GitHub](https://github.com/CubeShackles/cubeshackles/blob/main/docs/GITHUB_TAXONOMY.md)

Ferramentas de inteligência artificial podem apoiar a engenharia, mas não são autoras, proprietárias ou responsáveis institucionais pelos ativos da CubeShackles.

## Âmbito institucional

A CubeShackles está a estruturar capacidades para integração futura com instituições financeiras, empresas, entidades públicas, operadores tecnológicos e organismos de supervisão. Qualquer utilização regulada permanece sujeita às licenças, autorizações, avaliações de segurança, acordos institucionais e requisitos jurídicos aplicáveis em cada jurisdição.

---

© 2026 CubeShackles. Todos os direitos reservados.

<!--
localization:
  canonical_file: README.md
  locale: pt-AO
  translation_status: machine-assisted
  canonical_commit: 6360573802366c158779d3214328148c4870881e
  last_synchronized: 2026-07-19
-->
