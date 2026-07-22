# CubeShackles `.github`

[English](./README.md) | [Português](./README.pt.md)

Configuração GitHub ao nível da organização CubeShackles: perfil público da
organização, fluxos reutilizáveis, modelos de issues/PRs e documentação do
modelo operacional da Aplicação GitHub.

## Perfil público da organização

O GitHub apresenta o README da Overview da organização a partir de:

- [`profile/README.md`](./profile/README.md) — Inglês (canónico)
- [`profile/README.pt.md`](./profile/README.pt.md) — Português (`pt-AO`)

Este repositório é **público** para que o conteúdo do perfil fique visível a
não membros em [github.com/CubeShackles](https://github.com/CubeShackles).

A doutrina profunda da plataforma vive no repositório umbrella público
[`cubeshackles`](https://github.com/CubeShackles/cubeshackles).

## O que mais este repositório contém

- `.github/workflows/` — fluxos reutilizáveis da organização (por exemplo
  localização de documentação e CI padrão)
- `.github/ISSUE_TEMPLATE/`, `.github/PULL_REQUEST_TEMPLATE.md` —
  modelos partilhados de contribuição
- Este README — notas operacionais da superfície GitHub da organização

## Modelo operacional da Aplicação GitHub

A automação da CubeShackles deve autenticar-se com tokens temporários de
instalação do GitHub App, em vez de Personal Access Tokens (PATs) de longa
duração.

Propriedades esperadas:

1. Autenticação pela identidade da aplicação
2. Autorização limitada à instalação
3. Tokens temporários de acesso de instalação
4. Seleção explícita dos repositórios
5. Permissões mínimas necessárias
6. Automação registada e sujeita a revisão

## Limite de segurança

Este repositório não deve guardar nem expor:

- Chaves privadas da Aplicação GitHub
- Segredos de webhook
- Tokens de acesso de instalação
- Personal Access Tokens
- Credenciais específicas de ambientes
- Segredos não cifrados ou material de autenticação exportado

Os segredos devem permanecer num sistema aprovado de gestão de segredos e ser
disponibilizados apenas durante a execução.

## Governação

- [Normas de contribuição](https://github.com/CubeShackles/cubeshackles/blob/main/CONTRIBUTING.md)
- [Autoria e ferramentas](https://github.com/CubeShackles/cubeshackles/blob/main/governance/policies/authorship-and-tooling.md)
- [Mapa de repositórios](https://github.com/CubeShackles/cubeshackles/blob/main/REPOSITORY_MAP.md)
- [Taxonomia do GitHub](https://github.com/CubeShackles/cubeshackles/blob/main/docs/GITHUB_TAXONOMY.md)

---

**Visibilidade:** Pública (necessária para o README do perfil da organização)  
**Idioma canónico:** Inglês  
**Localização institucional:** Português (`pt-AO`)

<!--
localization:
  canonical_file: README.md
  locale: pt-AO
  translation_status: machine-assisted
  canonical_commit: PENDING_AFTER_COMMIT
  last_synchronized: 2026-07-22
-->
