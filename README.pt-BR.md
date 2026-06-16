# &#128640; Ulas Can Sahin - README completa em português do Brasil

[🇬🇧](README.md) | [🇩🇪](README.de.md) | [🇪🇸](README.es.md) | [🇧🇷](README.pt-BR.md) | [🇹🇷](README.tr.md) | [🇫🇷](README.fr.md)

> Este arquivo é uma porta de entrada completa em português do Brasil, não um resumo curto. Ele cobre objetivo, limites, uso, validação, segurança e publicação.
>
> README canônico em inglês: [README.md](README.md)

Public GitHub profile and repository gateway for Ulas Can Sahin.

Comece pelo README canônico quando precisar da descrição em inglês mais atual. Use esta página para ler o mesmo contrato operacional em português do Brasil.

## Estado e sinais de confiança

|Área | Detalhe|
|--- | ---|
|Status | Public repository: ucsahinn/ucsahinn|
|Fonte da verdade | [README canônico em inglês](README.md)|
|Usuários | Visitors who want to understand what Ulas ships.; Recruiters or collaborators looking for public project context.|
|Validação | Language links point to existing files.; Profile assets render from tracked SVG files.|
|Segurança | Routes visitors to active public projects without hiding the project boundaries.; Keeps language navigation visible at the top of the profile README.|

## O que este repositório é

- A profile-level entry point for shipped public repositories.
- A language-aware directory for Codex, security, product and documentation projects.
- A lightweight trust surface that points readers to the right repository instead of duplicating every project page.
- A place to show contribution signal, selected repository cards and current working areas.

## O que ele não é

- Not the source of truth for each product or package.
- Not a release channel for installers or archives.
- Not a place for private client, token, billing or infrastructure details.
- Not a replacement for each repository README, SECURITY file or release notes.

## Para quem é

- Visitors who want to understand what Ulas ships.
- Recruiters or collaborators looking for public project context.
- Users who need the right repo quickly.
- Maintainers checking that the profile stays public-safe.

## Início rápido

1. Clone ou atualize o repositório.
2. Leia README, segurança e mapa de documentação.
3. Execute as validações adequadas.
4. Stage somente os arquivos alterados de forma explícita.
5. Antes de push ou release, revise remoto, segredos e links novamente.

## Guia de decisão

- Need repo-specific install commands -> open that repository README.
- Need product release assets -> use the product repo release page, not this profile.
- Need security disclosure -> use the target repo SECURITY file if it exists.
- Need the high-level map -> stay on this profile README.

## Mapa do repositório

|Caminho | Por que importa|
|--- | ---|
|[README.md](README.md) | canonical profile README and language gateway|
|`README.de.md / README.es.md / README.pt-BR.md / README.tr.md / README.fr.md` | localized complete profile entry pages|
|[assets/profile/](assets/profile/) | public SVG cards used by the profile|
|[AGENTS.md](AGENTS.md) | repo-local working instructions|

## Fluxo de trabalho

1. Update profile copy from public repository facts only.
2. Keep links to active public repos clear and current.
3. Avoid stale claims about private work, user counts, rankings or unpublished releases.
4. Run link and secret checks before pushing profile changes.

## Comandos e validação

Execute estes comandos somente depois de clonar o repositório e entender o que eles verificam ou escrevem.

```powershell
git diff --check
gitleaks dir . --no-banner --redact
git status --short --branch
```

## Lista de verificação

- Language links point to existing files.
- Profile assets render from tracked SVG files.
- No private paths, local-only release files or token-like values appear in README content.
- Remote main is checked after push.

## Limite de segurança

- Routes visitors to active public projects without hiding the project boundaries.
- Keeps language navigation visible at the top of the profile README.
- Uses GitHub-native assets and workflow output only for public profile presentation.
- Excludes private operational details, credentials, dashboards and customer data.

Public-safe rule: do not add secrets, tokens, cookies, private keys, private prompts, customer data, local-only auth files, generated logs, archives or build outputs unless the canonical README explicitly says they belong in the public repo.

## Higiene de release e publicação

- Profile updates are documentation-only commits.
- Do not attach build artifacts or installers to this repository.
- Push only reviewed README and public asset changes.
- Verify GitHub rendered README after remote update when the change affects visible profile layout.

## Manutenção

- Keep this localized README aligned with README.md when the repo contract changes.
- Prefer factual repo links over marketing claims.
- Do not invent install commands, metrics, users, releases or support promises.
- If a command is version-sensitive, re-check it before documenting it.
- When a localized file cannot be updated fully, leave a clear note instead of a partial translation.

## Caminho de contribuição

- Open a focused change against the smallest set of files.
- Read AGENTS.md or CONTRIBUTING.md when present before editing.
- Run the repo validation commands listed above.
- Review staged diffs explicitly before commit.
- Use security disclosure paths instead of public issues for sensitive reports.

## Definição de concluído

Concluído significa: conteúdo completo, links corretos, limites de segurança claros, validação executada, Git limpo e remote HEAD verificado depois do push.

|Recomendação | Por que importa|
|--- | ---|
|Content | Public GitHub profile and repository gateway for Ulas Can Sahin.|
|Links | All referenced local files must exist and resolve from the repository root.|
|Security | Profile assets render from tracked SVG files.|
|Verification | Valide estrutura, links, Markdown, segredos, scripts relevantes e remote HEAD antes de afirmar que algo foi publicado.|
|Remote | After push, compare local HEAD with origin/main and GitHub remote HEAD.|

## Links importantes

|Caminho | Por que importa|
|--- | ---|
|[Canonical README](README.md) | README.md|
|[Repo instructions](AGENTS.md) | AGENTS.md|
|[Profile assets](assets/profile/) | assets/profile/|
