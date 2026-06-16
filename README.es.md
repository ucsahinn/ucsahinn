# &#128640; Ulas Can Sahin - README completa en español

<p align="center">
  <a href="README.md"><img src="https://flagcdn.com/w20/gb.png" alt="English" width="20"></a> ·
  <a href="README.de.md"><img src="https://flagcdn.com/w20/de.png" alt="Deutsch" width="20"></a> ·
  <a href="README.es.md"><img src="https://flagcdn.com/w20/es.png" alt="Español" width="20"></a> ·
  <a href="README.pt-BR.md"><img src="https://flagcdn.com/w20/br.png" alt="Português (Brasil)" width="20"></a> ·
  <a href="README.tr.md"><img src="https://flagcdn.com/w20/tr.png" alt="Türkçe" width="20"></a> ·
  <a href="README.fr.md"><img src="https://flagcdn.com/w20/fr.png" alt="Français" width="20"></a>
</p>

> Este archivo es una portada completa en español, no un resumen corto. Cubre propósito, límites, uso, validación, seguridad y publicación.
>
> README canónico en inglés: [README.md](README.md)

Public GitHub profile and repository gateway for Ulas Can Sahin.

Empieza por el README canónico si necesitas la descripción inglesa más actual. Usa esta página cuando quieras el mismo contrato operativo en español.

## Estado y señales de confianza

|Área | Detalle|
|--- | ---|
|Estado | Public repository: ucsahinn/ucsahinn|
|Fuente de verdad | [README canónico en inglés](README.md)|
|Usuarios | Visitors who want to understand what Ulas ships.; Recruiters or collaborators looking for public project context.|
|Validación | Language links point to existing files.; Profile assets render from tracked SVG files.|
|Seguridad | Routes visitors to active public projects without hiding the project boundaries.; Keeps language navigation visible at the top of the profile README.|

## Qué es este repositorio

- A profile-level entry point for shipped public repositories.
- A language-aware directory for Codex, security, product and documentation projects.
- A lightweight trust surface that points readers to the right repository instead of duplicating every project page.
- A place to show contribution signal, selected repository cards and current working areas.

## Qué no es

- Not the source of truth for each product or package.
- Not a release channel for installers or archives.
- Not a place for private client, token, billing or infrastructure details.
- Not a replacement for each repository README, SECURITY file or release notes.

## Para quién es

- Visitors who want to understand what Ulas ships.
- Recruiters or collaborators looking for public project context.
- Users who need the right repo quickly.
- Maintainers checking that the profile stays public-safe.

## Inicio rápido

1. Clona o actualiza el repositorio.
2. Lee README, seguridad y el mapa de documentación.
3. Ejecuta las validaciones adecuadas.
4. Prepara solo los archivos cambiados de forma explícita.
5. Antes de push o release, revisa remoto, secretos y enlaces otra vez.

## Guía de decisión

- Need repo-specific install commands -> open that repository README.
- Need product release assets -> use the product repo release page, not this profile.
- Need security disclosure -> use the target repo SECURITY file if it exists.
- Need the high-level map -> stay on this profile README.

## Mapa del repositorio

|Ruta | Por qué importa|
|--- | ---|
|[README.md](README.md) | canonical profile README and language gateway|
|`README.de.md / README.es.md / README.pt-BR.md / README.tr.md / README.fr.md` | localized complete profile entry pages|
|[assets/profile/](assets/profile/) | public SVG cards used by the profile|
|[AGENTS.md](AGENTS.md) | repo-local working instructions|

## Flujo de trabajo

1. Update profile copy from public repository facts only.
2. Keep links to active public repos clear and current.
3. Avoid stale claims about private work, user counts, rankings or unpublished releases.
4. Run link and secret checks before pushing profile changes.

## Comandos y validación

Ejecuta estos comandos solo después de clonar el repositorio y entender qué escriben o verifican.

```powershell
git diff --check
gitleaks dir . --no-banner --redact
git status --short --branch
```

## Lista de verificación

- Language links point to existing files.
- Profile assets render from tracked SVG files.
- No private paths, local-only release files or token-like values appear in README content.
- Remote main is checked after push.

## Límite de seguridad

- Routes visitors to active public projects without hiding the project boundaries.
- Keeps language navigation visible at the top of the profile README.
- Uses GitHub-native assets and workflow output only for public profile presentation.
- Excludes private operational details, credentials, dashboards and customer data.

Public-safe rule: do not add secrets, tokens, cookies, private keys, private prompts, customer data, local-only auth files, generated logs, archives or build outputs unless the canonical README explicitly says they belong in the public repo.

## Higiene de release y publicación

- Profile updates are documentation-only commits.
- Do not attach build artifacts or installers to this repository.
- Push only reviewed README and public asset changes.
- Verify GitHub rendered README after remote update when the change affects visible profile layout.

## Mantenimiento

- Keep this localized README aligned with README.md when the repo contract changes.
- Prefer factual repo links over marketing claims.
- Do not invent install commands, metrics, users, releases or support promises.
- If a command is version-sensitive, re-check it before documenting it.
- When a localized file cannot be updated fully, leave a clear note instead of a partial translation.

## Ruta de contribución

- Open a focused change against the smallest set of files.
- Read AGENTS.md or CONTRIBUTING.md when present before editing.
- Run the repo validation commands listed above.
- Review staged diffs explicitly before commit.
- Use security disclosure paths instead of public issues for sensitive reports.

## Definición de terminado

Terminado significa: contenido completo, enlaces correctos, límites de seguridad claros, validación ejecutada, Git limpio y remote HEAD verificado después del push.

|Recomendación | Por qué importa|
|--- | ---|
|Content | Public GitHub profile and repository gateway for Ulas Can Sahin.|
|Links | All referenced local files must exist and resolve from the repository root.|
|Security | Profile assets render from tracked SVG files.|
|Verification | Valida estructura, enlaces, Markdown, secretos, scripts relevantes y remote HEAD antes de afirmar que algo está publicado.|
|Remote | After push, compare local HEAD with origin/main and GitHub remote HEAD.|

## Enlaces importantes

|Ruta | Por qué importa|
|--- | ---|
|[Canonical README](README.md) | README.md|
|[Repo instructions](AGENTS.md) | AGENTS.md|
|[Profile assets](assets/profile/) | assets/profile/|
