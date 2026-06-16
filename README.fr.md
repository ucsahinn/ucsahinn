# &#128640; Ulas Can Sahin - README français complet

<p align="center">
  &#127760; <strong>Documentation:</strong>
  <a href="README.de.md"><img src="https://flagcdn.com/w20/de.png" alt="Deutsch" width="20"></a> |
  <a href="README.es.md"><img src="https://flagcdn.com/w20/es.png" alt="Espa&#241;ol" width="20"></a> |
  <a href="README.md"><img src="https://flagcdn.com/w20/gb.png" alt="English" width="20"></a> |
  <a href="README.pt-BR.md"><img src="https://flagcdn.com/w20/br.png" alt="Portugu&#234;s (Brasil)" width="20"></a> |
  <a href="README.tr.md"><img src="https://flagcdn.com/w20/tr.png" alt="T&#252;rk&#231;e" width="20"></a> |
  <a href="README.fr.md"><img src="https://flagcdn.com/w20/fr.png" alt="Fran&#231;ais" width="20"></a>
</p>

> Ce fichier est une page d’entrée française complète, pas un court résumé. Il couvre objectif, limites, usage, validation, sécurité et publication.
>
> README canonique en anglais: [README.md](README.md)

Public GitHub profile and repository gateway for Ulas Can Sahin.

Commencez par le README canonique si vous voulez la description anglaise la plus actuelle. Utilisez cette page pour lire le même contrat opérationnel en français.

## Statut et signaux de confiance

|Zone | Détail|
|--- | ---|
|Statut | Public repository: ucsahinn/ucsahinn|
|Source de vérité | [README canonique en anglais](README.md)|
|Utilisateurs | Visitors who want to understand what Ulas ships.; Recruiters or collaborators looking for public project context.|
|Validation | Language links point to existing files.; Profile assets render from tracked SVG files.|
|Sécurité | Routes visitors to active public projects without hiding the project boundaries.; Keeps language navigation visible at the top of the profile README.|

## Ce que contient ce dépôt

- A profile-level entry point for shipped public repositories.
- A language-aware directory for Codex, security, product and documentation projects.
- A lightweight trust surface that points readers to the right repository instead of duplicating every project page.
- A place to show contribution signal, selected repository cards and current working areas.

## Ce que ce dépôt n’est pas

- Not the source of truth for each product or package.
- Not a release channel for installers or archives.
- Not a place for private client, token, billing or infrastructure details.
- Not a replacement for each repository README, SECURITY file or release notes.

## Public visé

- Visitors who want to understand what Ulas ships.
- Recruiters or collaborators looking for public project context.
- Users who need the right repo quickly.
- Maintainers checking that the profile stays public-safe.

## Démarrage rapide

1. Clonez ou mettez à jour le dépôt.
2. Lisez README, sécurité et carte documentaire.
3. Lancez les validations adaptées.
4. Stagez uniquement les fichiers explicitement modifiés.
5. Avant push ou release, revérifiez remote, secrets et liens.

## Guide de décision

- Need repo-specific install commands -> open that repository README.
- Need product release assets -> use the product repo release page, not this profile.
- Need security disclosure -> use the target repo SECURITY file if it exists.
- Need the high-level map -> stay on this profile README.

## Carte du dépôt

|Chemin | Pourquoi c’est important|
|--- | ---|
|[README.md](README.md) | canonical profile README and language gateway|
|`README.de.md / README.es.md / README.pt-BR.md / README.tr.md / README.fr.md` | localized complete profile entry pages|
|[assets/profile/](assets/profile/) | public SVG cards used by the profile|
|[AGENTS.md](AGENTS.md) | repo-local working instructions|

## Flux de travail

1. Update profile copy from public repository facts only.
2. Keep links to active public repos clear and current.
3. Avoid stale claims about private work, user counts, rankings or unpublished releases.
4. Run link and secret checks before pushing profile changes.

## Commandes et validation

Exécutez ces commandes seulement après avoir cloné le dépôt et compris ce qu’elles vérifient ou modifient.

```powershell
git diff --check
gitleaks dir . --no-banner --redact
git status --short --branch
```

## Liste de vérification

- Language links point to existing files.
- Profile assets render from tracked SVG files.
- No private paths, local-only release files or token-like values appear in README content.
- Remote main is checked after push.

## Limite de sécurité

- Routes visitors to active public projects without hiding the project boundaries.
- Keeps language navigation visible at the top of the profile README.
- Uses GitHub-native assets and workflow output only for public profile presentation.
- Excludes private operational details, credentials, dashboards and customer data.

Public-safe rule: do not add secrets, tokens, cookies, private keys, private prompts, customer data, local-only auth files, generated logs, archives or build outputs unless the canonical README explicitly says they belong in the public repo.

## Hygiène de release et publication

- Profile updates are documentation-only commits.
- Do not attach build artifacts or installers to this repository.
- Push only reviewed README and public asset changes.
- Verify GitHub rendered README after remote update when the change affects visible profile layout.

## Maintenance

- Keep this localized README aligned with README.md when the repo contract changes.
- Prefer factual repo links over marketing claims.
- Do not invent install commands, metrics, users, releases or support promises.
- If a command is version-sensitive, re-check it before documenting it.
- When a localized file cannot be updated fully, leave a clear note instead of a partial translation.

## Chemin de contribution

- Open a focused change against the smallest set of files.
- Read AGENTS.md or CONTRIBUTING.md when present before editing.
- Run the repo validation commands listed above.
- Review staged diffs explicitly before commit.
- Use security disclosure paths instead of public issues for sensitive reports.

## Définition de terminé

Terminé signifie: contenu complet, liens corrects, limites de sécurité claires, validation exécutée, Git propre et remote HEAD vérifié après le push.

|Recommandation | Pourquoi c’est important|
|--- | ---|
|Content | Public GitHub profile and repository gateway for Ulas Can Sahin.|
|Links | All referenced local files must exist and resolve from the repository root.|
|Security | Profile assets render from tracked SVG files.|
|Verification | Validez structure, liens, Markdown, secrets, scripts pertinents et remote HEAD avant toute annonce publique.|
|Remote | After push, compare local HEAD with origin/main and GitHub remote HEAD.|

## Liens importants

|Chemin | Pourquoi c’est important|
|--- | ---|
|[Canonical README](README.md) | README.md|
|[Repo instructions](AGENTS.md) | AGENTS.md|
|[Profile assets](assets/profile/) | assets/profile/|
