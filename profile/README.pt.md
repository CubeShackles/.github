[English](./README.md) | **Português**

# CubeShackles

**Infraestrutura financeira programável, nativa em AOA, concebida em Angola para operar em ambientes institucionais, regulados e de conectividade limitada.**

A CubeShackles é uma plataforma liderada pelo fundador que desenvolve carris financeiros modulares para pagamentos, identidade, crédito, activos digitais, tokenização, compensação, liquidação, custódia, supervisão e integração institucional. O trabalho está organizado em repositórios especializados, com contratos versionados, limites de responsabilidade explícitos e mecanismos de validação auditáveis.

> **Estado da plataforma:** desenvolvimento pré-produção. Os repositórios contêm componentes implementados, protótipos, superfícies contratuais e capacidades planeadas em diferentes níveis de maturidade. A presença de código ou documentação **não** constitui aprovação regulatória, certificação, implantação nacional, endosso de parceria ou disponibilidade comercial.

## Começar aqui

| Recurso | Finalidade |
|---|---|
| [`cubeshackles`](https://github.com/CubeShackles/cubeshackles) | Umbrella público — doutrina da plataforma, mapa de repositórios, normas de contribuição e política de interoperabilidade |
| [Normas de contribuição](https://github.com/CubeShackles/cubeshackles/blob/main/CONTRIBUTING.md) | Como humanos e automação contribuem |
| [Mapa de repositórios](https://github.com/CubeShackles/cubeshackles/blob/main/REPOSITORY_MAP.md) | Como os repositórios especializados se encaixam |
| [Registo de Alegações](https://github.com/CubeShackles/cubeshackles/blob/main/docs/CLAIMS_REGISTER.md) | Maturidade e disciplina de redacção para alegações institucionais sensíveis |

Muitos repositórios irmãos permanecem privados durante a pré-produção. Os visitantes públicos devem tratar o repositório umbrella como o ponto de entrada canónico.

## Princípios de engenharia

- **Angola como jurisdição de origem** — suporte nativo ao kwanza (AOA), requisitos locais e resiliência sob conectividade desigual.
- **Arquitectura institucional** — separação entre livro-razão, compensação, liquidação, custódia, conformidade, supervisão e canais de acesso.
- **Operação verificável** — contratos versionados, validação determinística, rastreabilidade e evidências técnicas.
- **Segurança por desenho** — controlos de acesso, governação de segredos, isolamento de responsabilidades e recuperação operacional.
- **Interoperabilidade** — APIs, SDKs, eventos canónicos e modelos de dados partilhados entre os componentes da plataforma.
- **Transparência de maturidade** — distinção explícita entre implementado, parcialmente implementado, protótipo, experimental, planeado e dependente de autorização externa.

## Verticais da plataforma

Famílias de repositórios representativas (apenas nomes — o acesso pode ser privado durante a pré-produção):

| Vertical | Repositórios representativos |
|---|---|
| Plataforma e governação | `cubeshackles`, `Cubeshackles-core`, `Cubeshackles-control-plane`, `cubeshackles-platform-specs` |
| Livro-razão e liquidação | `cubeshackles-ledger`, `cubeshackles-clearing-house`, `cubeshackles-settlement-engine` |
| Conformidade e supervisão | `cubeshackles-compliance-engine`, `cubeshackles-regulatory-reporting`, `cubeshackles-supervision` |
| Activos e custódia | `cubeshackles-tokenization-engine`, `cubeshackles-asset-registry`, `cubeshackles-rwa-custody`, `cubeshackles-vault` |
| Infraestrutura e resiliência | `cubeshackles-infra`, `cubeshackles-offline-infrastructure`, `cubeshackles-disaster-recovery`, `cubeshackles-observability` |
| Inteligência e conhecimento | `Cubeshackles-ciel`, `cubeshackles-ontology`, `cubeshackles-ai-runtime`, `cubeshackles-agent` |
| Produtos | `CubeWallet`, `kulifikila`, `BualaBuitu`, `national-transit-app-cubeshackles` |
| Integração e desenvolvimento | `cubeshackles-integration`, `cubeshackles-developer-portal`, `cubeshackles-ai-sdk`, `cubeshackles-design-system` |

## Modelo de repositórios

Cada repositório deve declarar:

1. responsabilidade funcional;
2. limites explícitos do âmbito;
3. estado de maturidade;
4. interfaces e dependências;
5. comandos de validação;
6. riscos, pressupostos e capacidades ainda não verificadas.

Ferramentas de inteligência artificial podem apoiar a engenharia. Não são autoras, proprietárias ou responsáveis institucionais pelos activos da CubeShackles. Ver [autoria e ferramentas](https://github.com/CubeShackles/cubeshackles/blob/main/governance/policies/authorship-and-tooling.md).

## Âmbito institucional

A CubeShackles está a estruturar capacidades para integração futura com instituições financeiras, empresas, entidades públicas, operadores tecnológicos e organismos de supervisão. Qualquer utilização regulada permanece sujeita às licenças, autorizações, avaliações de segurança, acordos institucionais e requisitos jurídicos aplicáveis em cada jurisdição.

---

© 2026 CubeShackles. Todos os direitos reservados.

<!--
localization:
  canonical_file: README.md
  locale: pt-AO
  translation_status: machine-assisted
  canonical_commit: f73334cbb9ff5795defd456ca85573201b6aa128
  last_synchronized: 2026-07-22
-->
