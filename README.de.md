# &#128640; Ulas Can Sahin - vollständige deutsche README

<p align="center">
  &#127760; <strong>Dokumentation:</strong>
  <a href="README.de.md"><img src="https://flagcdn.com/w20/de.png" alt="Deutsch" width="20"></a> |
  <a href="README.es.md"><img src="https://flagcdn.com/w20/es.png" alt="Espa&#241;ol" width="20"></a> |
  <a href="README.md"><img src="https://flagcdn.com/w20/gb.png" alt="English" width="20"></a> |
  <a href="README.pt-BR.md"><img src="https://flagcdn.com/w20/br.png" alt="Portugu&#234;s (Brasil)" width="20"></a> |
  <a href="README.tr.md"><img src="https://flagcdn.com/w20/tr.png" alt="T&#252;rk&#231;e" width="20"></a> |
  <a href="README.fr.md"><img src="https://flagcdn.com/w20/fr.png" alt="Fran&#231;ais" width="20"></a>
</p>

> Diese Datei ist eine vollständige deutsche Einstiegseite, kein kurzer Platzhalter. Sie fasst Zweck, Grenzen, Bedienung, Prüfung, Sicherheit und Veröffentlichung in einer Datei zusammen.
>
> Kanonische englische README: [README.md](README.md)

Public GitHub profile and repository gateway for Ulas Can Sahin.

Beginnen Sie mit der kanonischen README, wenn Sie die aktuellste englische Beschreibung brauchen. Verwenden Sie diese Seite, wenn Sie den gleichen Vertrag auf Deutsch lesen wollen.

## Status und Vertrauensrahmen

|Bereich | Details|
|--- | ---|
|Status | Public repository: ucsahinn/ucsahinn|
|Wahrheit | [Kanonische englische README](README.md)|
|Benutzer | Visitors who want to understand what Ulas ships.; Recruiters or collaborators looking for public project context.|
|Prüfung | Language links point to existing files.; Profile assets render from tracked SVG files.|
|Sicherheit | Routes visitors to active public projects without hiding the project boundaries.; Keeps language navigation visible at the top of the profile README.|

## Was dieses Repository ist

- A profile-level entry point for shipped public repositories.
- A language-aware directory for Codex, security, product and documentation projects.
- A lightweight trust surface that points readers to the right repository instead of duplicating every project page.
- A place to show contribution signal, selected repository cards and current working areas.

## Was es nicht ist

- Not the source of truth for each product or package.
- Not a release channel for installers or archives.
- Not a place for private client, token, billing or infrastructure details.
- Not a replacement for each repository README, SECURITY file or release notes.

## Für wen es gedacht ist

- Visitors who want to understand what Ulas ships.
- Recruiters or collaborators looking for public project context.
- Users who need the right repo quickly.
- Maintainers checking that the profile stays public-safe.

## Schnellstart

1. Repository klonen oder aktualisieren.
2. README, Sicherheitsdateien und Dokumentationskarte lesen.
3. Die passenden Prüfungen ausführen.
4. Nur explizit geänderte Dateien stagen.
5. Vor Push oder Release Remote-Status, Secrets und Links erneut prüfen.

## Entscheidungshilfe

- Need repo-specific install commands -> open that repository README.
- Need product release assets -> use the product repo release page, not this profile.
- Need security disclosure -> use the target repo SECURITY file if it exists.
- Need the high-level map -> stay on this profile README.

## Repository-Karte

|Pfad | Warum es wichtig ist|
|--- | ---|
|[README.md](README.md) | canonical profile README and language gateway|
|`README.de.md / README.es.md / README.pt-BR.md / README.tr.md / README.fr.md` | localized complete profile entry pages|
|[assets/profile/](assets/profile/) | public SVG cards used by the profile|
|[AGENTS.md](AGENTS.md) | repo-local working instructions|

## Arbeitsablauf

1. Update profile copy from public repository facts only.
2. Keep links to active public repos clear and current.
3. Avoid stale claims about private work, user counts, rankings or unpublished releases.
4. Run link and secret checks before pushing profile changes.

## Befehle und Prüfung

Führen Sie diese Befehle nur aus, wenn Sie das Repository lokal geclont haben und die Wirkung verstehen.

```powershell
git diff --check
gitleaks dir . --no-banner --redact
git status --short --branch
```

## Validierungs-Checkliste

- Language links point to existing files.
- Profile assets render from tracked SVG files.
- No private paths, local-only release files or token-like values appear in README content.
- Remote main is checked after push.

## Sicherheitsgrenze

- Routes visitors to active public projects without hiding the project boundaries.
- Keeps language navigation visible at the top of the profile README.
- Uses GitHub-native assets and workflow output only for public profile presentation.
- Excludes private operational details, credentials, dashboards and customer data.

Public-safe rule: do not add secrets, tokens, cookies, private keys, private prompts, customer data, local-only auth files, generated logs, archives or build outputs unless the canonical README explicitly says they belong in the public repo.

## Release- und Publikationshygiene

- Profile updates are documentation-only commits.
- Do not attach build artifacts or installers to this repository.
- Push only reviewed README and public asset changes.
- Verify GitHub rendered README after remote update when the change affects visible profile layout.

## Wartung

- Keep this localized README aligned with README.md when the repo contract changes.
- Prefer factual repo links over marketing claims.
- Do not invent install commands, metrics, users, releases or support promises.
- If a command is version-sensitive, re-check it before documenting it.
- When a localized file cannot be updated fully, leave a clear note instead of a partial translation.

## Beitragspfad

- Open a focused change against the smallest set of files.
- Read AGENTS.md or CONTRIBUTING.md when present before editing.
- Run the repo validation commands listed above.
- Review staged diffs explicitly before commit.
- Use security disclosure paths instead of public issues for sensitive reports.

## Definition von fertig

Fertig bedeutet: Inhalt ist lokal vollständig, Links funktionieren, Sicherheitsgrenzen sind klar, Validierung ist gelaufen, Git ist sauber und der Remote-Stand ist nach dem Push geprüft.

|Empfehlung | Warum es wichtig ist|
|--- | ---|
|Content | Public GitHub profile and repository gateway for Ulas Can Sahin.|
|Links | All referenced local files must exist and resolve from the repository root.|
|Security | Profile assets render from tracked SVG files.|
|Verification | Prüfen Sie Struktur, Links, Markdown, Secrets, relevante Skripte und Remote-HEAD, bevor Sie eine öffentliche Aussage machen.|
|Remote | After push, compare local HEAD with origin/main and GitHub remote HEAD.|

## Wichtige Links

|Pfad | Warum es wichtig ist|
|--- | ---|
|[Canonical README](README.md) | README.md|
|[Repo instructions](AGENTS.md) | AGENTS.md|
|[Profile assets](assets/profile/) | assets/profile/|
