# Governação GitHub da CubeShackles

[English](./README.md) | [Português](./README.pt.md)

Este repositório público constitui a camada transversal de governação, perfil institucional e configuração partilhada da organização CubeShackles no GitHub.

Centraliza metadados públicos da organização, modelos reutilizáveis, fluxos de trabalho e controlos institucionais de engenharia aplicáveis ao portefólio de repositórios CubeShackles.

> Este repositório não contém a implementação da Aplicação GitHub da CubeShackles e não deve armazenar credenciais, chaves privadas, segredos de webhook ou lógica de geração de tokens. A infraestrutura de autenticação deve permanecer num repositório privado separado.

## Âmbito

- Conteúdo do perfil institucional em `profile/`
- Normas partilhadas de contribuição e pull requests
- Modelos de issues e pull requests
- Fluxos reutilizáveis do GitHub Actions
- Convenções de governação dos repositórios
- Controlos de documentação e localização à escala da organização
- Referências de segurança, autoria e políticas de engenharia

## Limite de segurança

Este repositório pode conter apenas políticas públicas e configuração partilhada não sensível.

Os seguintes ativos devem permanecer fora deste repositório:

- Código-fonte e configuração de implantação da Aplicação GitHub
- Chaves privadas da Aplicação GitHub
- Segredos de webhook
- Tokens de acesso de instalação
- Personal Access Tokens
- Credenciais específicas de ambientes
- Runbooks operacionais internos com detalhes sensíveis de acesso

## Referências canónicas

- [Normas de contribuição](https://github.com/CubeShackles/cubeshackles/blob/main/CONTRIBUTING.md)
- [Política de autoria e ferramentas](https://github.com/CubeShackles/cubeshackles/blob/main/governance/policies/authorship-and-tooling.md)
- [Mapa dos repositórios](https://github.com/CubeShackles/cubeshackles/blob/main/REPOSITORY_MAP.md)
- [Taxonomia do GitHub](https://github.com/CubeShackles/cubeshackles/blob/main/docs/GITHUB_TAXONOMY.md)

## Doutrina de governação

Os repositórios CubeShackles devem permanecer auditáveis, tecnicamente legíveis e explícitos quanto à maturidade, titularidade, risco e âmbito regulatório.

Ferramentas de engenharia assistida por inteligência artificial podem apoiar a implementação e a documentação. Não constituem autores, proprietários, reguladores ou aprovadores institucionais dos sistemas CubeShackles.

Cada pull request material deve incluir as etiquetas adequadas `type:*`, `layer:*` e `risk:*`, bem como um marco da plataforma quando aplicável.

## Distinção dos ficheiros e repositórios

- `README.md` documenta este repositório público de governação `.github`.
- `profile/README.md` é apresentado no perfil público da organização CubeShackles.
- `profile/README.pt.md` contém a versão portuguesa do perfil institucional.
- A Aplicação GitHub da CubeShackles deve ser mantida separadamente num repositório privado.

---

**Estado:** Repositório público ativo de governação organizacional  
**Idioma canónico:** Inglês  
**Localização institucional:** Português (`pt-AO`)