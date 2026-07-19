# Aplicação GitHub da CubeShackles

[English](./README.md) | [Português](./README.pt.md)

Este repositório privado contém a configuração, os controlos operacionais e os recursos de integração transversal utilizados pela Aplicação GitHub da CubeShackles.

A aplicação fornece acesso autenticado aos repositórios CubeShackles autorizados através de tokens temporários de instalação do GitHub App, com permissões granulares, em vez de Personal Access Tokens (PATs) ou credenciais de utilizadores com longa duração.

## Finalidade

- Autenticar automações aprovadas nos repositórios CubeShackles
- Emitir tokens temporários de acesso de instalação
- Aplicar permissões de repositório segundo o princípio do menor privilégio
- Suportar operações da API do GitHub em toda a organização
- Centralizar fluxos reutilizáveis, modelos e controlos de repositórios
- Reduzir a dependência de Personal Access Tokens associados a utilizadores
- Manter uma separação auditável entre contas humanas e sistemas automatizados

## Estrutura do repositório

- `profile/README.md` — fonte inglesa do perfil institucional
- `profile/README.pt.md` — fonte portuguesa do perfil institucional
- `.github/` — fluxos partilhados, modelos e configuração organizacional do GitHub
- `README.md` — documentação canónica deste repositório privado da Aplicação GitHub
- `README.pt.md` — tradução institucional em português

Como este repositório é privado, o ficheiro `profile/README.md` não deve ser considerado o perfil público da organização, salvo se os requisitos de visibilidade do GitHub forem satisfeitos separadamente através de um repositório `.github` público destinado ao perfil.

## Modelo de autenticação

A Aplicação GitHub deve utilizar:

1. Autenticação pela identidade da aplicação
2. Autorização limitada à instalação
3. Tokens temporários de acesso de instalação
4. Seleção explícita dos repositórios autorizados
5. Permissões mínimas necessárias
6. Automação registada, auditável e sujeita a revisão

Personal Access Tokens não integram o modelo operacional normal das automações suportadas.

## Limite de segurança

Este repositório não deve guardar nem expor:

- Chaves privadas da Aplicação GitHub
- Segredos de webhook
- Tokens de acesso de instalação
- Personal Access Tokens
- Credenciais específicas de ambientes
- Segredos não cifrados ou material de autenticação exportado

Os segredos devem permanecer num sistema aprovado de gestão de segredos e ser disponibilizados apenas durante a execução.

## Governação

Todas as permissões da aplicação, alterações de acesso a repositórios e automações devem ser:

- explicitamente delimitadas;
- analisáveis através do controlo de versões;
- atribuíveis a um operador ou fluxo aprovado;
- revogáveis sem dependência de uma conta individual;
- alinhadas com as políticas de segurança e governação de repositórios da CubeShackles.

## Referências canónicas

- [Normas de contribuição](https://github.com/CubeShackles/cubeshackles/blob/main/CONTRIBUTING.md)
- [Política de autoria e ferramentas](https://github.com/CubeShackles/cubeshackles/blob/main/governance/policies/authorship-and-tooling.md)
- [Mapa dos repositórios](https://github.com/CubeShackles/cubeshackles/blob/main/REPOSITORY_MAP.md)
- [Taxonomia do GitHub](https://github.com/CubeShackles/cubeshackles/blob/main/docs/GITHUB_TAXONOMY.md)

---

**Visibilidade:** Privada  
**Função:** Aplicação GitHub da CubeShackles e repositório de controlo da automação organizacional  
**Idioma canónico:** Inglês  
**Localização institucional:** Português (`pt-AO`)
